# Comparing `tmp/checkpasswords-2022.0.1.tar.gz` & `tmp/checkpasswords-2023.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "checkpasswords-2022.0.1.tar", max compression
+gzip compressed data, was "checkpasswords-2023.tar", max compression
```

## Comparing `checkpasswords-2022.0.1.tar` & `checkpasswords-2023.tar`

### file list

```diff
@@ -1,13 +1,13 @@
--rw-r--r--   0        0        0        0 2022-04-09 16:18:09.906662 checkpasswords-2022.0.1/checkpasswords/__init__.py
--rw-r--r--   0        0        0     2088 2022-04-09 16:18:09.906662 checkpasswords-2022.0.1/checkpasswords/__main__.py
--rw-r--r--   0        0        0     2360 2022-04-09 16:18:09.905664 checkpasswords-2022.0.1/checkpasswords/auxiliary.py
--rw-r--r--   0        0        0     4054 2022-04-09 16:18:09.906662 checkpasswords-2022.0.1/checkpasswords/credentials.py
--rw-r--r--   0        0        0        0 2022-04-09 16:18:09.908657 checkpasswords-2022.0.1/checkpasswords/io/__init__.py
--rw-r--r--   0        0        0     1772 2022-04-09 16:18:09.907659 checkpasswords-2022.0.1/checkpasswords/io/input.py
--rw-r--r--   0        0        0     7003 2022-04-09 16:18:09.907659 checkpasswords-2022.0.1/checkpasswords/io/output.py
--rw-r--r--   0        0        0    18126 2022-04-07 20:06:55.855940 checkpasswords-2022.0.1/checkpasswords/mfa_sites.txt
--rw-r--r--   0        0        0    35591 2022-04-09 16:41:59.921568 checkpasswords-2022.0.1/LICENSE.md
--rw-r--r--   0        0        0     2033 2022-04-09 17:07:56.474210 checkpasswords-2022.0.1/pyproject.toml
--rw-r--r--   0        0        0     9595 2022-04-09 16:42:35.637828 checkpasswords-2022.0.1/README.md
--rw-r--r--   0        0        0    10719 2022-04-09 17:08:01.304525 checkpasswords-2022.0.1/setup.py
--rw-r--r--   0        0        0    10866 2022-04-09 17:08:01.310136 checkpasswords-2022.0.1/PKG-INFO
+-rw-r--r--   0        0        0        0 2023-06-27 22:31:23.589445 checkpasswords-2023/checkpasswords/__init__.py
+-rw-r--r--   0        0        0     2088 2023-06-27 22:31:23.590444 checkpasswords-2023/checkpasswords/__main__.py
+-rw-r--r--   0        0        0     2601 2023-06-27 22:31:23.587446 checkpasswords-2023/checkpasswords/auxiliary.py
+-rw-r--r--   0        0        0     3985 2023-06-27 22:31:23.588445 checkpasswords-2023/checkpasswords/credentials.py
+-rw-r--r--   0        0        0        0 2023-06-27 22:31:23.593447 checkpasswords-2023/checkpasswords/io/__init__.py
+-rw-r--r--   0        0        0     2118 2023-06-27 22:31:23.591445 checkpasswords-2023/checkpasswords/io/input.py
+-rw-r--r--   0        0        0     7005 2023-06-27 22:31:23.592446 checkpasswords-2023/checkpasswords/io/output.py
+-rw-r--r--   0        0        0    22292 2023-06-27 21:34:04.614638 checkpasswords-2023/checkpasswords/mfa_sites.txt
+-rw-r--r--   0        0        0    34916 2023-01-01 17:52:37.970355 checkpasswords-2023/LICENSE.md
+-rw-r--r--   0        0        0     2242 2023-06-27 22:33:00.270927 checkpasswords-2023/pyproject.toml
+-rw-r--r--   0        0        0    10036 2023-01-03 22:59:22.623313 checkpasswords-2023/README.md
+-rw-r--r--   0        0        0    11485 1970-01-01 00:00:00.000000 checkpasswords-2023/setup.py
+-rw-r--r--   0        0        0    11647 1970-01-01 00:00:00.000000 checkpasswords-2023/PKG-INFO
```

### Comparing `checkpasswords-2022.0.1/checkpasswords/__main__.py` & `checkpasswords-2023/checkpasswords/__main__.py`

 * *Files identical despite different names*

### Comparing `checkpasswords-2022.0.1/checkpasswords/auxiliary.py` & `checkpasswords-2023/checkpasswords/auxiliary.py`

 * *Files 15% similar despite different names*

```diff
@@ -28,15 +28,31 @@
 
 	Args:
 		notes (str): notes field
 
 	Returns:
 		bool: isMfaEnabled
 	"""
-	return re.search(r"[2m]fa.*?enabled", notes, re.I) is not None
+
+	patterns = [
+		r"[2m]fa.*?enabled",
+		r"authenticated.*?x\d*",
+		r"sms.*?[2m]fa",
+		r"text.*?[2m]fa",
+		r"[2m]fa.*?sms",
+		r"[2m]fa.*?text",
+		r"\w.*?authenticat",
+		"aegis",
+		"otp",
+		"authy",
+		"keepass",
+		"duo",
+	]
+
+	return re.search("|".join(patterns), notes, re.I) is not None
 
 
 def isHttp(urlstr: str) -> bool:
 	"""Use the urls field to determine if http is used instead of https
 
 	Args:
 		urlstr (str): urlstr field
@@ -46,15 +62,15 @@
 	"""
 	return "http:" in urlstr
 
 
 def entropyLen(string: str):
 	"""Calculates the Shannon entropy * length of a string"""
 	prob = [string.count(c) / len(string) for c in set(string)]
-	entropy = -sum([p * math.log(p) / math.log(2.0) for p in prob])
+	entropy = -sum(p * math.log(p) / math.log(2.0) for p in prob)
 	return entropy * len(string)
 
 
 def zxcvbnScore(password: str) -> ZxcvbnScore:
 	"""Calculate a ZxcvbnScore from a password
 
 	Args:
@@ -64,15 +80,15 @@
 		ZxcvbnScore: Return a dict of type ZxcvbnScore
 	"""
 	try:
 		scores = zxcvbn(password)
 	except IndexError:
 		return {"score": -1, "suggestions": "Add a password", "crack_time": -1}
 	return {
-		"score": scores["score"] + entropyLen(password) / 50,
+		"score": int(scores["score"] + entropyLen(password) / 50),
 		"suggestions": " ".join(scores["feedback"]["suggestions"]),
 		"crack_time": float(scores["crack_times_seconds"]["offline_slow_hashing_1e4_per_second"])
 		/ 100,
 	}
 
 
 def passwordPrint(password: str) -> str:
@@ -80,15 +96,15 @@
 
 	Args:
 		password (str): raw password
 
 	Returns:
 		str: obfuscated password
 	"""
-	if len(password) < 5:
+	if len(password) < 7:
 		return "*" * len(password)
 	return password[:2] + ("*" * (len(password) - 4)) + password[-2:]
 
 
 MFA = Path(f"{THISDIR}/mfa_sites.txt").read_text(encoding="utf-8").splitlines()
```

### Comparing `checkpasswords-2022.0.1/checkpasswords/credentials.py` & `checkpasswords-2023/checkpasswords/credentials.py`

 * *Files 6% similar despite different names*

```diff
@@ -32,15 +32,15 @@
 	"""
 
 	name: str
 	urls: list[str]
 	username: str
 	password: str
 	notes: str
-	totp: str
+	otpauth: str
 	zxcvbnScore: ZxcvbnScore = field(init=False)
 	isPasswordDuplicate: bool = field(init=False)
 	passwordPrint: str = field(init=False)
 	isHttp: bool = field(init=False)
 	isMfaAvailable: bool = field(init=False)
 	isMfaEnabled: bool = field(init=False)
 
@@ -49,15 +49,15 @@
 		self.username = self.username.strip()
 		urlstr = " ".join(self.urls).lower()
 		self.zxcvbnScore = zxcvbnScore(self.password)
 		self.isPasswordDuplicate = False
 		self.passwordPrint = passwordPrint(self.password)
 		self.isHttp = isHttp(urlstr)
 		self.isMfaAvailable = isMfaAvailable(urlstr)
-		self.isMfaEnabled = len(self.totp) > 0 or isMfaEnabled(self.notes)
+		self.isMfaEnabled = len(self.otpauth) > 0 or isMfaEnabled(self.notes)
 		self.instructEnableMfa = self.isMfaAvailable and not self.isMfaEnabled
 
 
 def applyPasswordDuplicate(credentials: list[Credentials]):
 	"""Apply duplicate password flag to each credentials
 
 	Args:
@@ -101,36 +101,36 @@
 	Args:
 		credentials (list[Credentials]): list of credentials parsed from some input file.
 		Such as a bitwarden export to CSV
 	"""
 	credentials = orderCredentials(credentials)
 	applyPasswordDuplicate(credentials)
 
-	duplicatePasswordsTable = [("Name", "Username", "Password")] + [  # type: ignore
+	duplicatePasswordsTable = [("Name", "Username", "Password")] + [
 		(cred.name, cred.username, cred.passwordPrint)
 		for cred in credentials
 		if cred.isPasswordDuplicate
 	]
 
-	weakPasswordsTable = [("Name", "Username", "Password", "Score", "Suggestion")] + [  # type: ignore
+	weakPasswordsTable = [("Name", "Username", "Password", "Score", "Suggestion")] + [
 		(
 			cred.name,
 			cred.username,
 			cred.passwordPrint,
-			cred.zxcvbnScore["score"],
+			str(cred.zxcvbnScore["score"]),
 			cred.zxcvbnScore["suggestions"],
 		)
 		for cred in credentials
 		if -1 < cred.zxcvbnScore["score"] < 4
 	]
 
-	httpSitesTable = [("Name", "Username")] + [  # type: ignore
+	httpSitesTable = [("Name", "Username")] + [
 		(cred.name, cred.username) for cred in credentials if cred.isHttp
 	]
 
-	enable2faTable = [("Name", "Username")] + [  # type: ignore
+	enable2faTable = [("Name", "Username")] + [
 		(cred.name, cred.username) for cred in credentials if cred.instructEnableMfa
 	]
 
-	emailsTable = [("Emails",)] + [(email,) for email in sorted(emails(credentials))]  # type: ignore
+	emailsTable = [("Emails",)] + [(email,) for email in sorted(emails(credentials))]
 
 	return duplicatePasswordsTable, weakPasswordsTable, httpSitesTable, enable2faTable, emailsTable
```

### Comparing `checkpasswords-2022.0.1/checkpasswords/io/input.py` & `checkpasswords-2023/checkpasswords/io/input.py`

 * *Files 4% similar despite different names*

```diff
@@ -36,25 +36,39 @@
 		else:
 			print(" [x] Error: Must specify input_format e.g. -i bitwarden")
 			sys.exit(1)
 	conf["in"] = path
 	conf["importer"] = passManager.name
 	data = pass_import(conf, passManager)
 
-	# Convert pass_import representation to checkpasswords representation (list[Credentials])
+	if data is None:
+		raise RuntimeError(
+			f"Failed to handle password file from {path} (password_manager={manager})"
+		)
+
+	return transformPass(data)
+
+
+def transformPass(data: list[dict]) -> list[Credentials]:
+	"""Convert pass_import representation to checkpasswords representation (list[Credentials])
+
+
+	:param dict list[dict]: pass_import representation
+	:return list[Credentials]: checkpasswords representation
+	"""
 	credentials = []
 	for row in data:
 		credentials.append(
 			Credentials(
 				name=row["title"],
 				urls=[
 					x
 					for x in ([row.get("url")] + [row.get(f"url{y}") for y in range(10)])
 					if x is not None
 				],
 				username=row.get("login", ""),
 				password=row.get("password", ""),
 				notes=row.get("comments", ""),
-				totp=row.get("otpauth", ""),
+				otpauth=row.get("otpauth", ""),
 			)
 		)
 	return credentials
```

### Comparing `checkpasswords-2022.0.1/checkpasswords/io/output.py` & `checkpasswords-2023/checkpasswords/io/output.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,15 +26,15 @@
 from rich.table import Table
 
 from checkpasswords.credentials import Credentials, generateTables
 
 INFO = {"program": "checkpasswords", "version": "2022"}
 
 
-def stripAnsi(string: str) -> str:
+def _stripAnsi(string: str) -> str:
 	"""Strip ansi codes from a given string
 
 	Args:
 		string (str): string to strip codes from
 
 	Returns:
 		str: plaintext, utf-8 string (safe for writing to files)
@@ -123,15 +123,15 @@
 	Args:
 		credentials (list[Credentials]): list of credentials parsed from some input file.
 		Such as a bitwarden export to CSV
 
 	Returns:
 		str: string to send to specified output in plain text format
 	"""
-	return stripAnsi(ansi(credentials))
+	return _stripAnsi(ansi(credentials))
 
 
 def markdown(credentials: list[Credentials]) -> str:
 	"""Format to markdown
 
 	Args:
 		credentials (list[Credentials]): list of credentials parsed from some input file.
@@ -148,19 +148,19 @@
 		enable2faTable,
 		emailsTable,
 	) = generateTables(credentials)
 	count = lambda x: len(x) - 1
 	toTB = lambda z: "\n".join([f'|{"|".join([str(y) for y in x])}|' for x in z[1:]])
 
 	strBuf.append("\nSummary\n|Issue|No. Instances|\n|:--|:--|")
-	strBuf.append(f"|duplicate_passwords|{count((duplicatePasswordsTable))}")
-	strBuf.append(f"|weak_passwords|{count((weakPasswordsTable))}")
-	strBuf.append(f"|http_sites|{count((httpSitesTable))}")
-	strBuf.append(f"|enable_2fa|{count((enable2faTable))}")
-	strBuf.append(f"|emails|{count((emailsTable))}")
+	strBuf.append(f"|Duplicate Passwords|{count((duplicatePasswordsTable))}")
+	strBuf.append(f"|Weak Passwords|{count((weakPasswordsTable))}")
+	strBuf.append(f"|HTTP Sites|{count((httpSitesTable))}")
+	strBuf.append(f"|Enable 2FA|{count((enable2faTable))}")
+	strBuf.append(f"|Emails|{count((emailsTable))}")
 
 	strBuf.append("\nDuplicate Passwords\n|Name|Username|Password|\n|:--|:--|:--|")
 	strBuf.append(toTB(duplicatePasswordsTable))
 	strBuf.append("\nWeak Passwords")
 	strBuf.append("|Name|Username|Password|Score|Suggestion\n|:--|:--|:--|:--|:--|")
 	strBuf.append(toTB(weakPasswordsTable))
 	strBuf.append("\nHTTP Sites\n|Name|Username|\n|:--|:--")
```

### Comparing `checkpasswords-2022.0.1/LICENSE.md` & `checkpasswords-2023/LICENSE.md`

 * *Ordering differences only*

 * *Files 4% similar despite different names*

```diff
@@ -1,675 +1,675 @@
-### GNU GENERAL PUBLIC LICENSE
-
-Version 3, 29 June 2007
-
-Copyright (C) 2007 Free Software Foundation, Inc.
-<https://fsf.org/>
-
-Everyone is permitted to copy and distribute verbatim copies of this
-license document, but changing it is not allowed.
-
-### Preamble
-
-The GNU General Public License is a free, copyleft license for
-software and other kinds of works.
-
-The licenses for most software and other practical works are designed
-to take away your freedom to share and change the works. By contrast,
-the GNU General Public License is intended to guarantee your freedom
-to share and change all versions of a program--to make sure it remains
-free software for all its users. We, the Free Software Foundation, use
-the GNU General Public License for most of our software; it applies
-also to any other work released this way by its authors. You can apply
-it to your programs, too.
-
-When we speak of free software, we are referring to freedom, not
-price. Our General Public Licenses are designed to make sure that you
-have the freedom to distribute copies of free software (and charge for
-them if you wish), that you receive source code or can get it if you
-want it, that you can change the software or use pieces of it in new
-free programs, and that you know you can do these things.
-
-To protect your rights, we need to prevent others from denying you
-these rights or asking you to surrender the rights. Therefore, you
-have certain responsibilities if you distribute copies of the
-software, or if you modify it: responsibilities to respect the freedom
-of others.
-
-For example, if you distribute copies of such a program, whether
-gratis or for a fee, you must pass on to the recipients the same
-freedoms that you received. You must make sure that they, too, receive
-or can get the source code. And you must show them these terms so they
-know their rights.
-
-Developers that use the GNU GPL protect your rights with two steps:
-(1) assert copyright on the software, and (2) offer you this License
-giving you legal permission to copy, distribute and/or modify it.
-
-For the developers' and authors' protection, the GPL clearly explains
-that there is no warranty for this free software. For both users' and
-authors' sake, the GPL requires that modified versions be marked as
-changed, so that their problems will not be attributed erroneously to
-authors of previous versions.
-
-Some devices are designed to deny users access to install or run
-modified versions of the software inside them, although the
-manufacturer can do so. This is fundamentally incompatible with the
-aim of protecting users' freedom to change the software. The
-systematic pattern of such abuse occurs in the area of products for
-individuals to use, which is precisely where it is most unacceptable.
-Therefore, we have designed this version of the GPL to prohibit the
-practice for those products. If such problems arise substantially in
-other domains, we stand ready to extend this provision to those
-domains in future versions of the GPL, as needed to protect the
-freedom of users.
-
-Finally, every program is threatened constantly by software patents.
-States should not allow patents to restrict development and use of
-software on general-purpose computers, but in those that do, we wish
-to avoid the special danger that patents applied to a free program
-could make it effectively proprietary. To prevent this, the GPL
-assures that patents cannot be used to render the program non-free.
-
-The precise terms and conditions for copying, distribution and
-modification follow.
-
-### TERMS AND CONDITIONS
-
-#### 0. Definitions.
-
-"This License" refers to version 3 of the GNU General Public License.
-
-"Copyright" also means copyright-like laws that apply to other kinds
-of works, such as semiconductor masks.
-
-"The Program" refers to any copyrightable work licensed under this
-License. Each licensee is addressed as "you". "Licensees" and
-"recipients" may be individuals or organizations.
-
-To "modify" a work means to copy from or adapt all or part of the work
-in a fashion requiring copyright permission, other than the making of
-an exact copy. The resulting work is called a "modified version" of
-the earlier work or a work "based on" the earlier work.
-
-A "covered work" means either the unmodified Program or a work based
-on the Program.
-
-To "propagate" a work means to do anything with it that, without
-permission, would make you directly or secondarily liable for
-infringement under applicable copyright law, except executing it on a
-computer or modifying a private copy. Propagation includes copying,
-distribution (with or without modification), making available to the
-public, and in some countries other activities as well.
-
-To "convey" a work means any kind of propagation that enables other
-parties to make or receive copies. Mere interaction with a user
-through a computer network, with no transfer of a copy, is not
-conveying.
-
-An interactive user interface displays "Appropriate Legal Notices" to
-the extent that it includes a convenient and prominently visible
-feature that (1) displays an appropriate copyright notice, and (2)
-tells the user that there is no warranty for the work (except to the
-extent that warranties are provided), that licensees may convey the
-work under this License, and how to view a copy of this License. If
-the interface presents a list of user commands or options, such as a
-menu, a prominent item in the list meets this criterion.
-
-#### 1. Source Code.
-
-The "source code" for a work means the preferred form of the work for
-making modifications to it. "Object code" means any non-source form of
-a work.
-
-A "Standard Interface" means an interface that either is an official
-standard defined by a recognized standards body, or, in the case of
-interfaces specified for a particular programming language, one that
-is widely used among developers working in that language.
-
-The "System Libraries" of an executable work include anything, other
-than the work as a whole, that (a) is included in the normal form of
-packaging a Major Component, but which is not part of that Major
-Component, and (b) serves only to enable use of the work with that
-Major Component, or to implement a Standard Interface for which an
-implementation is available to the public in source code form. A
-"Major Component", in this context, means a major essential component
-(kernel, window system, and so on) of the specific operating system
-(if any) on which the executable work runs, or a compiler used to
-produce the work, or an object code interpreter used to run it.
-
-The "Corresponding Source" for a work in object code form means all
-the source code needed to generate, install, and (for an executable
-work) run the object code and to modify the work, including scripts to
-control those activities. However, it does not include the work's
-System Libraries, or general-purpose tools or generally available free
-programs which are used unmodified in performing those activities but
-which are not part of the work. For example, Corresponding Source
-includes interface definition files associated with source files for
-the work, and the source code for shared libraries and dynamically
-linked subprograms that the work is specifically designed to require,
-such as by intimate data communication or control flow between those
-subprograms and other parts of the work.
-
-The Corresponding Source need not include anything that users can
-regenerate automatically from other parts of the Corresponding Source.
-
-The Corresponding Source for a work in source code form is that same
-work.
-
-#### 2. Basic Permissions.
-
-All rights granted under this License are granted for the term of
-copyright on the Program, and are irrevocable provided the stated
-conditions are met. This License explicitly affirms your unlimited
-permission to run the unmodified Program. The output from running a
-covered work is covered by this License only if the output, given its
-content, constitutes a covered work. This License acknowledges your
-rights of fair use or other equivalent, as provided by copyright law.
-
-You may make, run and propagate covered works that you do not convey,
-without conditions so long as your license otherwise remains in force.
-You may convey covered works to others for the sole purpose of having
-them make modifications exclusively for you, or provide you with
-facilities for running those works, provided that you comply with the
-terms of this License in conveying all material for which you do not
-control copyright. Those thus making or running the covered works for
-you must do so exclusively on your behalf, under your direction and
-control, on terms that prohibit them from making any copies of your
-copyrighted material outside their relationship with you.
-
-Conveying under any other circumstances is permitted solely under the
-conditions stated below. Sublicensing is not allowed; section 10 makes
-it unnecessary.
-
-#### 3. Protecting Users' Legal Rights From Anti-Circumvention Law.
-
-No covered work shall be deemed part of an effective technological
-measure under any applicable law fulfilling obligations under article
-11 of the WIPO copyright treaty adopted on 20 December 1996, or
-similar laws prohibiting or restricting circumvention of such
-measures.
-
-When you convey a covered work, you waive any legal power to forbid
-circumvention of technological measures to the extent such
-circumvention is effected by exercising rights under this License with
-respect to the covered work, and you disclaim any intention to limit
-operation or modification of the work as a means of enforcing, against
-the work's users, your or third parties' legal rights to forbid
-circumvention of technological measures.
-
-#### 4. Conveying Verbatim Copies.
-
-You may convey verbatim copies of the Program's source code as you
-receive it, in any medium, provided that you conspicuously and
-appropriately publish on each copy an appropriate copyright notice;
-keep intact all notices stating that this License and any
-non-permissive terms added in accord with section 7 apply to the code;
-keep intact all notices of the absence of any warranty; and give all
-recipients a copy of this License along with the Program.
-
-You may charge any price or no price for each copy that you convey,
-and you may offer support or warranty protection for a fee.
-
-#### 5. Conveying Modified Source Versions.
-
-You may convey a work based on the Program, or the modifications to
-produce it from the Program, in the form of source code under the
-terms of section 4, provided that you also meet all of these
-conditions:
-
--   a) The work must carry prominent notices stating that you modified
-    it, and giving a relevant date.
--   b) The work must carry prominent notices stating that it is
-    released under this License and any conditions added under
-    section 7. This requirement modifies the requirement in section 4
-    to "keep intact all notices".
--   c) You must license the entire work, as a whole, under this
-    License to anyone who comes into possession of a copy. This
-    License will therefore apply, along with any applicable section 7
-    additional terms, to the whole of the work, and all its parts,
-    regardless of how they are packaged. This License gives no
-    permission to license the work in any other way, but it does not
-    invalidate such permission if you have separately received it.
--   d) If the work has interactive user interfaces, each must display
-    Appropriate Legal Notices; however, if the Program has interactive
-    interfaces that do not display Appropriate Legal Notices, your
-    work need not make them do so.
-
-A compilation of a covered work with other separate and independent
-works, which are not by their nature extensions of the covered work,
-and which are not combined with it such as to form a larger program,
-in or on a volume of a storage or distribution medium, is called an
-"aggregate" if the compilation and its resulting copyright are not
-used to limit the access or legal rights of the compilation's users
-beyond what the individual works permit. Inclusion of a covered work
-in an aggregate does not cause this License to apply to the other
-parts of the aggregate.
-
-#### 6. Conveying Non-Source Forms.
-
-You may convey a covered work in object code form under the terms of
-sections 4 and 5, provided that you also convey the machine-readable
-Corresponding Source under the terms of this License, in one of these
-ways:
-
--   a) Convey the object code in, or embodied in, a physical product
-    (including a physical distribution medium), accompanied by the
-    Corresponding Source fixed on a durable physical medium
-    customarily used for software interchange.
--   b) Convey the object code in, or embodied in, a physical product
-    (including a physical distribution medium), accompanied by a
-    written offer, valid for at least three years and valid for as
-    long as you offer spare parts or customer support for that product
-    model, to give anyone who possesses the object code either (1) a
-    copy of the Corresponding Source for all the software in the
-    product that is covered by this License, on a durable physical
-    medium customarily used for software interchange, for a price no
-    more than your reasonable cost of physically performing this
-    conveying of source, or (2) access to copy the Corresponding
-    Source from a network server at no charge.
--   c) Convey individual copies of the object code with a copy of the
-    written offer to provide the Corresponding Source. This
-    alternative is allowed only occasionally and noncommercially, and
-    only if you received the object code with such an offer, in accord
-    with subsection 6b.
--   d) Convey the object code by offering access from a designated
-    place (gratis or for a charge), and offer equivalent access to the
-    Corresponding Source in the same way through the same place at no
-    further charge. You need not require recipients to copy the
-    Corresponding Source along with the object code. If the place to
-    copy the object code is a network server, the Corresponding Source
-    may be on a different server (operated by you or a third party)
-    that supports equivalent copying facilities, provided you maintain
-    clear directions next to the object code saying where to find the
-    Corresponding Source. Regardless of what server hosts the
-    Corresponding Source, you remain obligated to ensure that it is
-    available for as long as needed to satisfy these requirements.
--   e) Convey the object code using peer-to-peer transmission,
-    provided you inform other peers where the object code and
-    Corresponding Source of the work are being offered to the general
-    public at no charge under subsection 6d.
-
-A separable portion of the object code, whose source code is excluded
-from the Corresponding Source as a System Library, need not be
-included in conveying the object code work.
-
-A "User Product" is either (1) a "consumer product", which means any
-tangible personal property which is normally used for personal,
-family, or household purposes, or (2) anything designed or sold for
-incorporation into a dwelling. In determining whether a product is a
-consumer product, doubtful cases shall be resolved in favor of
-coverage. For a particular product received by a particular user,
-"normally used" refers to a typical or common use of that class of
-product, regardless of the status of the particular user or of the way
-in which the particular user actually uses, or expects or is expected
-to use, the product. A product is a consumer product regardless of
-whether the product has substantial commercial, industrial or
-non-consumer uses, unless such uses represent the only significant
-mode of use of the product.
-
-"Installation Information" for a User Product means any methods,
-procedures, authorization keys, or other information required to
-install and execute modified versions of a covered work in that User
-Product from a modified version of its Corresponding Source. The
-information must suffice to ensure that the continued functioning of
-the modified object code is in no case prevented or interfered with
-solely because modification has been made.
-
-If you convey an object code work under this section in, or with, or
-specifically for use in, a User Product, and the conveying occurs as
-part of a transaction in which the right of possession and use of the
-User Product is transferred to the recipient in perpetuity or for a
-fixed term (regardless of how the transaction is characterized), the
-Corresponding Source conveyed under this section must be accompanied
-by the Installation Information. But this requirement does not apply
-if neither you nor any third party retains the ability to install
-modified object code on the User Product (for example, the work has
-been installed in ROM).
-
-The requirement to provide Installation Information does not include a
-requirement to continue to provide support service, warranty, or
-updates for a work that has been modified or installed by the
-recipient, or for the User Product in which it has been modified or
-installed. Access to a network may be denied when the modification
-itself materially and adversely affects the operation of the network
-or violates the rules and protocols for communication across the
-network.
-
-Corresponding Source conveyed, and Installation Information provided,
-in accord with this section must be in a format that is publicly
-documented (and with an implementation available to the public in
-source code form), and must require no special password or key for
-unpacking, reading or copying.
-
-#### 7. Additional Terms.
-
-"Additional permissions" are terms that supplement the terms of this
-License by making exceptions from one or more of its conditions.
-Additional permissions that are applicable to the entire Program shall
-be treated as though they were included in this License, to the extent
-that they are valid under applicable law. If additional permissions
-apply only to part of the Program, that part may be used separately
-under those permissions, but the entire Program remains governed by
-this License without regard to the additional permissions.
-
-When you convey a copy of a covered work, you may at your option
-remove any additional permissions from that copy, or from any part of
-it. (Additional permissions may be written to require their own
-removal in certain cases when you modify the work.) You may place
-additional permissions on material, added by you to a covered work,
-for which you have or can give appropriate copyright permission.
-
-Notwithstanding any other provision of this License, for material you
-add to a covered work, you may (if authorized by the copyright holders
-of that material) supplement the terms of this License with terms:
-
--   a) Disclaiming warranty or limiting liability differently from the
-    terms of sections 15 and 16 of this License; or
--   b) Requiring preservation of specified reasonable legal notices or
-    author attributions in that material or in the Appropriate Legal
-    Notices displayed by works containing it; or
--   c) Prohibiting misrepresentation of the origin of that material,
-    or requiring that modified versions of such material be marked in
-    reasonable ways as different from the original version; or
--   d) Limiting the use for publicity purposes of names of licensors
-    or authors of the material; or
--   e) Declining to grant rights under trademark law for use of some
-    trade names, trademarks, or service marks; or
--   f) Requiring indemnification of licensors and authors of that
-    material by anyone who conveys the material (or modified versions
-    of it) with contractual assumptions of liability to the recipient,
-    for any liability that these contractual assumptions directly
-    impose on those licensors and authors.
-
-All other non-permissive additional terms are considered "further
-restrictions" within the meaning of section 10. If the Program as you
-received it, or any part of it, contains a notice stating that it is
-governed by this License along with a term that is a further
-restriction, you may remove that term. If a license document contains
-a further restriction but permits relicensing or conveying under this
-License, you may add to a covered work material governed by the terms
-of that license document, provided that the further restriction does
-not survive such relicensing or conveying.
-
-If you add terms to a covered work in accord with this section, you
-must place, in the relevant source files, a statement of the
-additional terms that apply to those files, or a notice indicating
-where to find the applicable terms.
-
-Additional terms, permissive or non-permissive, may be stated in the
-form of a separately written license, or stated as exceptions; the
-above requirements apply either way.
-
-#### 8. Termination.
-
-You may not propagate or modify a covered work except as expressly
-provided under this License. Any attempt otherwise to propagate or
-modify it is void, and will automatically terminate your rights under
-this License (including any patent licenses granted under the third
-paragraph of section 11).
-
-However, if you cease all violation of this License, then your license
-from a particular copyright holder is reinstated (a) provisionally,
-unless and until the copyright holder explicitly and finally
-terminates your license, and (b) permanently, if the copyright holder
-fails to notify you of the violation by some reasonable means prior to
-60 days after the cessation.
-
-Moreover, your license from a particular copyright holder is
-reinstated permanently if the copyright holder notifies you of the
-violation by some reasonable means, this is the first time you have
-received notice of violation of this License (for any work) from that
-copyright holder, and you cure the violation prior to 30 days after
-your receipt of the notice.
-
-Termination of your rights under this section does not terminate the
-licenses of parties who have received copies or rights from you under
-this License. If your rights have been terminated and not permanently
-reinstated, you do not qualify to receive new licenses for the same
-material under section 10.
-
-#### 9. Acceptance Not Required for Having Copies.
-
-You are not required to accept this License in order to receive or run
-a copy of the Program. Ancillary propagation of a covered work
-occurring solely as a consequence of using peer-to-peer transmission
-to receive a copy likewise does not require acceptance. However,
-nothing other than this License grants you permission to propagate or
-modify any covered work. These actions infringe copyright if you do
-not accept this License. Therefore, by modifying or propagating a
-covered work, you indicate your acceptance of this License to do so.
-
-#### 10. Automatic Licensing of Downstream Recipients.
-
-Each time you convey a covered work, the recipient automatically
-receives a license from the original licensors, to run, modify and
-propagate that work, subject to this License. You are not responsible
-for enforcing compliance by third parties with this License.
-
-An "entity transaction" is a transaction transferring control of an
-organization, or substantially all assets of one, or subdividing an
-organization, or merging organizations. If propagation of a covered
-work results from an entity transaction, each party to that
-transaction who receives a copy of the work also receives whatever
-licenses to the work the party's predecessor in interest had or could
-give under the previous paragraph, plus a right to possession of the
-Corresponding Source of the work from the predecessor in interest, if
-the predecessor has it or can get it with reasonable efforts.
-
-You may not impose any further restrictions on the exercise of the
-rights granted or affirmed under this License. For example, you may
-not impose a license fee, royalty, or other charge for exercise of
-rights granted under this License, and you may not initiate litigation
-(including a cross-claim or counterclaim in a lawsuit) alleging that
-any patent claim is infringed by making, using, selling, offering for
-sale, or importing the Program or any portion of it.
-
-#### 11. Patents.
-
-A "contributor" is a copyright holder who authorizes use under this
-License of the Program or a work on which the Program is based. The
-work thus licensed is called the contributor's "contributor version".
-
-A contributor's "essential patent claims" are all patent claims owned
-or controlled by the contributor, whether already acquired or
-hereafter acquired, that would be infringed by some manner, permitted
-by this License, of making, using, or selling its contributor version,
-but do not include claims that would be infringed only as a
-consequence of further modification of the contributor version. For
-purposes of this definition, "control" includes the right to grant
-patent sublicenses in a manner consistent with the requirements of
-this License.
-
-Each contributor grants you a non-exclusive, worldwide, royalty-free
-patent license under the contributor's essential patent claims, to
-make, use, sell, offer for sale, import and otherwise run, modify and
-propagate the contents of its contributor version.
-
-In the following three paragraphs, a "patent license" is any express
-agreement or commitment, however denominated, not to enforce a patent
-(such as an express permission to practice a patent or covenant not to
-sue for patent infringement). To "grant" such a patent license to a
-party means to make such an agreement or commitment not to enforce a
-patent against the party.
-
-If you convey a covered work, knowingly relying on a patent license,
-and the Corresponding Source of the work is not available for anyone
-to copy, free of charge and under the terms of this License, through a
-publicly available network server or other readily accessible means,
-then you must either (1) cause the Corresponding Source to be so
-available, or (2) arrange to deprive yourself of the benefit of the
-patent license for this particular work, or (3) arrange, in a manner
-consistent with the requirements of this License, to extend the patent
-license to downstream recipients. "Knowingly relying" means you have
-actual knowledge that, but for the patent license, your conveying the
-covered work in a country, or your recipient's use of the covered work
-in a country, would infringe one or more identifiable patents in that
-country that you have reason to believe are valid.
-
-If, pursuant to or in connection with a single transaction or
-arrangement, you convey, or propagate by procuring conveyance of, a
-covered work, and grant a patent license to some of the parties
-receiving the covered work authorizing them to use, propagate, modify
-or convey a specific copy of the covered work, then the patent license
-you grant is automatically extended to all recipients of the covered
-work and works based on it.
-
-A patent license is "discriminatory" if it does not include within the
-scope of its coverage, prohibits the exercise of, or is conditioned on
-the non-exercise of one or more of the rights that are specifically
-granted under this License. You may not convey a covered work if you
-are a party to an arrangement with a third party that is in the
-business of distributing software, under which you make payment to the
-third party based on the extent of your activity of conveying the
-work, and under which the third party grants, to any of the parties
-who would receive the covered work from you, a discriminatory patent
-license (a) in connection with copies of the covered work conveyed by
-you (or copies made from those copies), or (b) primarily for and in
-connection with specific products or compilations that contain the
-covered work, unless you entered into that arrangement, or that patent
-license was granted, prior to 28 March 2007.
-
-Nothing in this License shall be construed as excluding or limiting
-any implied license or other defenses to infringement that may
-otherwise be available to you under applicable patent law.
-
-#### 12. No Surrender of Others' Freedom.
-
-If conditions are imposed on you (whether by court order, agreement or
-otherwise) that contradict the conditions of this License, they do not
-excuse you from the conditions of this License. If you cannot convey a
-covered work so as to satisfy simultaneously your obligations under
-this License and any other pertinent obligations, then as a
-consequence you may not convey it at all. For example, if you agree to
-terms that obligate you to collect a royalty for further conveying
-from those to whom you convey the Program, the only way you could
-satisfy both those terms and this License would be to refrain entirely
-from conveying the Program.
-
-#### 13. Use with the GNU Affero General Public License.
-
-Notwithstanding any other provision of this License, you have
-permission to link or combine any covered work with a work licensed
-under version 3 of the GNU Affero General Public License into a single
-combined work, and to convey the resulting work. The terms of this
-License will continue to apply to the part which is the covered work,
-but the special requirements of the GNU Affero General Public License,
-section 13, concerning interaction through a network will apply to the
-combination as such.
-
-#### 14. Revised Versions of this License.
-
-The Free Software Foundation may publish revised and/or new versions
-of the GNU General Public License from time to time. Such new versions
-will be similar in spirit to the present version, but may differ in
-detail to address new problems or concerns.
-
-Each version is given a distinguishing version number. If the Program
-specifies that a certain numbered version of the GNU General Public
-License "or any later version" applies to it, you have the option of
-following the terms and conditions either of that numbered version or
-of any later version published by the Free Software Foundation. If the
-Program does not specify a version number of the GNU General Public
-License, you may choose any version ever published by the Free
-Software Foundation.
-
-If the Program specifies that a proxy can decide which future versions
-of the GNU General Public License can be used, that proxy's public
-statement of acceptance of a version permanently authorizes you to
-choose that version for the Program.
-
-Later license versions may give you additional or different
-permissions. However, no additional obligations are imposed on any
-author or copyright holder as a result of your choosing to follow a
-later version.
-
-#### 15. Disclaimer of Warranty.
-
-THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
-APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
-HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT
-WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT
-LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
-A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND
-PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE
-DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR
-CORRECTION.
-
-#### 16. Limitation of Liability.
-
-IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
-WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR
-CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES,
-INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES
-ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT
-NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR
-LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM
-TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER
-PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
-
-#### 17. Interpretation of Sections 15 and 16.
-
-If the disclaimer of warranty and limitation of liability provided
-above cannot be given local legal effect according to their terms,
-reviewing courts shall apply local law that most closely approximates
-an absolute waiver of all civil liability in connection with the
-Program, unless a warranty or assumption of liability accompanies a
-copy of the Program in return for a fee.
-
-END OF TERMS AND CONDITIONS
-
-### How to Apply These Terms to Your New Programs
-
-If you develop a new program, and you want it to be of the greatest
-possible use to the public, the best way to achieve this is to make it
-free software which everyone can redistribute and change under these
-terms.
-
-To do so, attach the following notices to the program. It is safest to
-attach them to the start of each source file to most effectively state
-the exclusion of warranty; and each file should have at least the
-"copyright" line and a pointer to where the full notice is found.
-
-        <one line to give the program's name and a brief idea of what it does.>
-        Copyright (C) <year>  <name of author>
-
-        This program is free software: you can redistribute it and/or modify
-        it under the terms of the GNU General Public License as published by
-        the Free Software Foundation, either version 3 of the License, or
-        (at your option) any later version.
-
-        This program is distributed in the hope that it will be useful,
-        but WITHOUT ANY WARRANTY; without even the implied warranty of
-        MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-        GNU General Public License for more details.
-
-        You should have received a copy of the GNU General Public License
-        along with this program.  If not, see <https://www.gnu.org/licenses/>.
-
-Also add information on how to contact you by electronic and paper
-mail.
-
-If the program does terminal interaction, make it output a short
-notice like this when it starts in an interactive mode:
-
-        <program>  Copyright (C) <year>  <name of author>
-        This program comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
-        This is free software, and you are welcome to redistribute it
-        under certain conditions; type `show c' for details.
-
-The hypothetical commands \`show w' and \`show c' should show the
-appropriate parts of the General Public License. Of course, your
-program's commands might be different; for a GUI interface, you would
-use an "about box".
-
-You should also get your employer (if you work as a programmer) or
-school, if any, to sign a "copyright disclaimer" for the program, if
-necessary. For more information on this, and how to apply and follow
-the GNU GPL, see <https://www.gnu.org/licenses/>.
-
-The GNU General Public License does not permit incorporating your
-program into proprietary programs. If your program is a subroutine
-library, you may consider it more useful to permit linking proprietary
-applications with the library. If this is what you want to do, use the
-GNU Lesser General Public License instead of this License. But first,
-please read <https://www.gnu.org/licenses/why-not-lgpl.html>.
+### GNU GENERAL PUBLIC LICENSE
+
+Version 3, 29 June 2007
+
+Copyright (C) 2007 Free Software Foundation, Inc.
+<https://fsf.org/>
+
+Everyone is permitted to copy and distribute verbatim copies of this
+license document, but changing it is not allowed.
+
+### Preamble
+
+The GNU General Public License is a free, copyleft license for
+software and other kinds of works.
+
+The licenses for most software and other practical works are designed
+to take away your freedom to share and change the works. By contrast,
+the GNU General Public License is intended to guarantee your freedom
+to share and change all versions of a program--to make sure it remains
+free software for all its users. We, the Free Software Foundation, use
+the GNU General Public License for most of our software; it applies
+also to any other work released this way by its authors. You can apply
+it to your programs, too.
+
+When we speak of free software, we are referring to freedom, not
+price. Our General Public Licenses are designed to make sure that you
+have the freedom to distribute copies of free software (and charge for
+them if you wish), that you receive source code or can get it if you
+want it, that you can change the software or use pieces of it in new
+free programs, and that you know you can do these things.
+
+To protect your rights, we need to prevent others from denying you
+these rights or asking you to surrender the rights. Therefore, you
+have certain responsibilities if you distribute copies of the
+software, or if you modify it: responsibilities to respect the freedom
+of others.
+
+For example, if you distribute copies of such a program, whether
+gratis or for a fee, you must pass on to the recipients the same
+freedoms that you received. You must make sure that they, too, receive
+or can get the source code. And you must show them these terms so they
+know their rights.
+
+Developers that use the GNU GPL protect your rights with two steps:
+(1) assert copyright on the software, and (2) offer you this License
+giving you legal permission to copy, distribute and/or modify it.
+
+For the developers' and authors' protection, the GPL clearly explains
+that there is no warranty for this free software. For both users' and
+authors' sake, the GPL requires that modified versions be marked as
+changed, so that their problems will not be attributed erroneously to
+authors of previous versions.
+
+Some devices are designed to deny users access to install or run
+modified versions of the software inside them, although the
+manufacturer can do so. This is fundamentally incompatible with the
+aim of protecting users' freedom to change the software. The
+systematic pattern of such abuse occurs in the area of products for
+individuals to use, which is precisely where it is most unacceptable.
+Therefore, we have designed this version of the GPL to prohibit the
+practice for those products. If such problems arise substantially in
+other domains, we stand ready to extend this provision to those
+domains in future versions of the GPL, as needed to protect the
+freedom of users.
+
+Finally, every program is threatened constantly by software patents.
+States should not allow patents to restrict development and use of
+software on general-purpose computers, but in those that do, we wish
+to avoid the special danger that patents applied to a free program
+could make it effectively proprietary. To prevent this, the GPL
+assures that patents cannot be used to render the program non-free.
+
+The precise terms and conditions for copying, distribution and
+modification follow.
+
+### TERMS AND CONDITIONS
+
+#### 0. Definitions.
+
+"This License" refers to version 3 of the GNU General Public License.
+
+"Copyright" also means copyright-like laws that apply to other kinds
+of works, such as semiconductor masks.
+
+"The Program" refers to any copyrightable work licensed under this
+License. Each licensee is addressed as "you". "Licensees" and
+"recipients" may be individuals or organizations.
+
+To "modify" a work means to copy from or adapt all or part of the work
+in a fashion requiring copyright permission, other than the making of
+an exact copy. The resulting work is called a "modified version" of
+the earlier work or a work "based on" the earlier work.
+
+A "covered work" means either the unmodified Program or a work based
+on the Program.
+
+To "propagate" a work means to do anything with it that, without
+permission, would make you directly or secondarily liable for
+infringement under applicable copyright law, except executing it on a
+computer or modifying a private copy. Propagation includes copying,
+distribution (with or without modification), making available to the
+public, and in some countries other activities as well.
+
+To "convey" a work means any kind of propagation that enables other
+parties to make or receive copies. Mere interaction with a user
+through a computer network, with no transfer of a copy, is not
+conveying.
+
+An interactive user interface displays "Appropriate Legal Notices" to
+the extent that it includes a convenient and prominently visible
+feature that (1) displays an appropriate copyright notice, and (2)
+tells the user that there is no warranty for the work (except to the
+extent that warranties are provided), that licensees may convey the
+work under this License, and how to view a copy of this License. If
+the interface presents a list of user commands or options, such as a
+menu, a prominent item in the list meets this criterion.
+
+#### 1. Source Code.
+
+The "source code" for a work means the preferred form of the work for
+making modifications to it. "Object code" means any non-source form of
+a work.
+
+A "Standard Interface" means an interface that either is an official
+standard defined by a recognized standards body, or, in the case of
+interfaces specified for a particular programming language, one that
+is widely used among developers working in that language.
+
+The "System Libraries" of an executable work include anything, other
+than the work as a whole, that (a) is included in the normal form of
+packaging a Major Component, but which is not part of that Major
+Component, and (b) serves only to enable use of the work with that
+Major Component, or to implement a Standard Interface for which an
+implementation is available to the public in source code form. A
+"Major Component", in this context, means a major essential component
+(kernel, window system, and so on) of the specific operating system
+(if any) on which the executable work runs, or a compiler used to
+produce the work, or an object code interpreter used to run it.
+
+The "Corresponding Source" for a work in object code form means all
+the source code needed to generate, install, and (for an executable
+work) run the object code and to modify the work, including scripts to
+control those activities. However, it does not include the work's
+System Libraries, or general-purpose tools or generally available free
+programs which are used unmodified in performing those activities but
+which are not part of the work. For example, Corresponding Source
+includes interface definition files associated with source files for
+the work, and the source code for shared libraries and dynamically
+linked subprograms that the work is specifically designed to require,
+such as by intimate data communication or control flow between those
+subprograms and other parts of the work.
+
+The Corresponding Source need not include anything that users can
+regenerate automatically from other parts of the Corresponding Source.
+
+The Corresponding Source for a work in source code form is that same
+work.
+
+#### 2. Basic Permissions.
+
+All rights granted under this License are granted for the term of
+copyright on the Program, and are irrevocable provided the stated
+conditions are met. This License explicitly affirms your unlimited
+permission to run the unmodified Program. The output from running a
+covered work is covered by this License only if the output, given its
+content, constitutes a covered work. This License acknowledges your
+rights of fair use or other equivalent, as provided by copyright law.
+
+You may make, run and propagate covered works that you do not convey,
+without conditions so long as your license otherwise remains in force.
+You may convey covered works to others for the sole purpose of having
+them make modifications exclusively for you, or provide you with
+facilities for running those works, provided that you comply with the
+terms of this License in conveying all material for which you do not
+control copyright. Those thus making or running the covered works for
+you must do so exclusively on your behalf, under your direction and
+control, on terms that prohibit them from making any copies of your
+copyrighted material outside their relationship with you.
+
+Conveying under any other circumstances is permitted solely under the
+conditions stated below. Sublicensing is not allowed; section 10 makes
+it unnecessary.
+
+#### 3. Protecting Users' Legal Rights From Anti-Circumvention Law.
+
+No covered work shall be deemed part of an effective technological
+measure under any applicable law fulfilling obligations under article
+11 of the WIPO copyright treaty adopted on 20 December 1996, or
+similar laws prohibiting or restricting circumvention of such
+measures.
+
+When you convey a covered work, you waive any legal power to forbid
+circumvention of technological measures to the extent such
+circumvention is effected by exercising rights under this License with
+respect to the covered work, and you disclaim any intention to limit
+operation or modification of the work as a means of enforcing, against
+the work's users, your or third parties' legal rights to forbid
+circumvention of technological measures.
+
+#### 4. Conveying Verbatim Copies.
+
+You may convey verbatim copies of the Program's source code as you
+receive it, in any medium, provided that you conspicuously and
+appropriately publish on each copy an appropriate copyright notice;
+keep intact all notices stating that this License and any
+non-permissive terms added in accord with section 7 apply to the code;
+keep intact all notices of the absence of any warranty; and give all
+recipients a copy of this License along with the Program.
+
+You may charge any price or no price for each copy that you convey,
+and you may offer support or warranty protection for a fee.
+
+#### 5. Conveying Modified Source Versions.
+
+You may convey a work based on the Program, or the modifications to
+produce it from the Program, in the form of source code under the
+terms of section 4, provided that you also meet all of these
+conditions:
+
+-   a) The work must carry prominent notices stating that you modified
+    it, and giving a relevant date.
+-   b) The work must carry prominent notices stating that it is
+    released under this License and any conditions added under
+    section 7. This requirement modifies the requirement in section 4
+    to "keep intact all notices".
+-   c) You must license the entire work, as a whole, under this
+    License to anyone who comes into possession of a copy. This
+    License will therefore apply, along with any applicable section 7
+    additional terms, to the whole of the work, and all its parts,
+    regardless of how they are packaged. This License gives no
+    permission to license the work in any other way, but it does not
+    invalidate such permission if you have separately received it.
+-   d) If the work has interactive user interfaces, each must display
+    Appropriate Legal Notices; however, if the Program has interactive
+    interfaces that do not display Appropriate Legal Notices, your
+    work need not make them do so.
+
+A compilation of a covered work with other separate and independent
+works, which are not by their nature extensions of the covered work,
+and which are not combined with it such as to form a larger program,
+in or on a volume of a storage or distribution medium, is called an
+"aggregate" if the compilation and its resulting copyright are not
+used to limit the access or legal rights of the compilation's users
+beyond what the individual works permit. Inclusion of a covered work
+in an aggregate does not cause this License to apply to the other
+parts of the aggregate.
+
+#### 6. Conveying Non-Source Forms.
+
+You may convey a covered work in object code form under the terms of
+sections 4 and 5, provided that you also convey the machine-readable
+Corresponding Source under the terms of this License, in one of these
+ways:
+
+-   a) Convey the object code in, or embodied in, a physical product
+    (including a physical distribution medium), accompanied by the
+    Corresponding Source fixed on a durable physical medium
+    customarily used for software interchange.
+-   b) Convey the object code in, or embodied in, a physical product
+    (including a physical distribution medium), accompanied by a
+    written offer, valid for at least three years and valid for as
+    long as you offer spare parts or customer support for that product
+    model, to give anyone who possesses the object code either (1) a
+    copy of the Corresponding Source for all the software in the
+    product that is covered by this License, on a durable physical
+    medium customarily used for software interchange, for a price no
+    more than your reasonable cost of physically performing this
+    conveying of source, or (2) access to copy the Corresponding
+    Source from a network server at no charge.
+-   c) Convey individual copies of the object code with a copy of the
+    written offer to provide the Corresponding Source. This
+    alternative is allowed only occasionally and noncommercially, and
+    only if you received the object code with such an offer, in accord
+    with subsection 6b.
+-   d) Convey the object code by offering access from a designated
+    place (gratis or for a charge), and offer equivalent access to the
+    Corresponding Source in the same way through the same place at no
+    further charge. You need not require recipients to copy the
+    Corresponding Source along with the object code. If the place to
+    copy the object code is a network server, the Corresponding Source
+    may be on a different server (operated by you or a third party)
+    that supports equivalent copying facilities, provided you maintain
+    clear directions next to the object code saying where to find the
+    Corresponding Source. Regardless of what server hosts the
+    Corresponding Source, you remain obligated to ensure that it is
+    available for as long as needed to satisfy these requirements.
+-   e) Convey the object code using peer-to-peer transmission,
+    provided you inform other peers where the object code and
+    Corresponding Source of the work are being offered to the general
+    public at no charge under subsection 6d.
+
+A separable portion of the object code, whose source code is excluded
+from the Corresponding Source as a System Library, need not be
+included in conveying the object code work.
+
+A "User Product" is either (1) a "consumer product", which means any
+tangible personal property which is normally used for personal,
+family, or household purposes, or (2) anything designed or sold for
+incorporation into a dwelling. In determining whether a product is a
+consumer product, doubtful cases shall be resolved in favor of
+coverage. For a particular product received by a particular user,
+"normally used" refers to a typical or common use of that class of
+product, regardless of the status of the particular user or of the way
+in which the particular user actually uses, or expects or is expected
+to use, the product. A product is a consumer product regardless of
+whether the product has substantial commercial, industrial or
+non-consumer uses, unless such uses represent the only significant
+mode of use of the product.
+
+"Installation Information" for a User Product means any methods,
+procedures, authorization keys, or other information required to
+install and execute modified versions of a covered work in that User
+Product from a modified version of its Corresponding Source. The
+information must suffice to ensure that the continued functioning of
+the modified object code is in no case prevented or interfered with
+solely because modification has been made.
+
+If you convey an object code work under this section in, or with, or
+specifically for use in, a User Product, and the conveying occurs as
+part of a transaction in which the right of possession and use of the
+User Product is transferred to the recipient in perpetuity or for a
+fixed term (regardless of how the transaction is characterized), the
+Corresponding Source conveyed under this section must be accompanied
+by the Installation Information. But this requirement does not apply
+if neither you nor any third party retains the ability to install
+modified object code on the User Product (for example, the work has
+been installed in ROM).
+
+The requirement to provide Installation Information does not include a
+requirement to continue to provide support service, warranty, or
+updates for a work that has been modified or installed by the
+recipient, or for the User Product in which it has been modified or
+installed. Access to a network may be denied when the modification
+itself materially and adversely affects the operation of the network
+or violates the rules and protocols for communication across the
+network.
+
+Corresponding Source conveyed, and Installation Information provided,
+in accord with this section must be in a format that is publicly
+documented (and with an implementation available to the public in
+source code form), and must require no special password or key for
+unpacking, reading or copying.
+
+#### 7. Additional Terms.
+
+"Additional permissions" are terms that supplement the terms of this
+License by making exceptions from one or more of its conditions.
+Additional permissions that are applicable to the entire Program shall
+be treated as though they were included in this License, to the extent
+that they are valid under applicable law. If additional permissions
+apply only to part of the Program, that part may be used separately
+under those permissions, but the entire Program remains governed by
+this License without regard to the additional permissions.
+
+When you convey a copy of a covered work, you may at your option
+remove any additional permissions from that copy, or from any part of
+it. (Additional permissions may be written to require their own
+removal in certain cases when you modify the work.) You may place
+additional permissions on material, added by you to a covered work,
+for which you have or can give appropriate copyright permission.
+
+Notwithstanding any other provision of this License, for material you
+add to a covered work, you may (if authorized by the copyright holders
+of that material) supplement the terms of this License with terms:
+
+-   a) Disclaiming warranty or limiting liability differently from the
+    terms of sections 15 and 16 of this License; or
+-   b) Requiring preservation of specified reasonable legal notices or
+    author attributions in that material or in the Appropriate Legal
+    Notices displayed by works containing it; or
+-   c) Prohibiting misrepresentation of the origin of that material,
+    or requiring that modified versions of such material be marked in
+    reasonable ways as different from the original version; or
+-   d) Limiting the use for publicity purposes of names of licensors
+    or authors of the material; or
+-   e) Declining to grant rights under trademark law for use of some
+    trade names, trademarks, or service marks; or
+-   f) Requiring indemnification of licensors and authors of that
+    material by anyone who conveys the material (or modified versions
+    of it) with contractual assumptions of liability to the recipient,
+    for any liability that these contractual assumptions directly
+    impose on those licensors and authors.
+
+All other non-permissive additional terms are considered "further
+restrictions" within the meaning of section 10. If the Program as you
+received it, or any part of it, contains a notice stating that it is
+governed by this License along with a term that is a further
+restriction, you may remove that term. If a license document contains
+a further restriction but permits relicensing or conveying under this
+License, you may add to a covered work material governed by the terms
+of that license document, provided that the further restriction does
+not survive such relicensing or conveying.
+
+If you add terms to a covered work in accord with this section, you
+must place, in the relevant source files, a statement of the
+additional terms that apply to those files, or a notice indicating
+where to find the applicable terms.
+
+Additional terms, permissive or non-permissive, may be stated in the
+form of a separately written license, or stated as exceptions; the
+above requirements apply either way.
+
+#### 8. Termination.
+
+You may not propagate or modify a covered work except as expressly
+provided under this License. Any attempt otherwise to propagate or
+modify it is void, and will automatically terminate your rights under
+this License (including any patent licenses granted under the third
+paragraph of section 11).
+
+However, if you cease all violation of this License, then your license
+from a particular copyright holder is reinstated (a) provisionally,
+unless and until the copyright holder explicitly and finally
+terminates your license, and (b) permanently, if the copyright holder
+fails to notify you of the violation by some reasonable means prior to
+60 days after the cessation.
+
+Moreover, your license from a particular copyright holder is
+reinstated permanently if the copyright holder notifies you of the
+violation by some reasonable means, this is the first time you have
+received notice of violation of this License (for any work) from that
+copyright holder, and you cure the violation prior to 30 days after
+your receipt of the notice.
+
+Termination of your rights under this section does not terminate the
+licenses of parties who have received copies or rights from you under
+this License. If your rights have been terminated and not permanently
+reinstated, you do not qualify to receive new licenses for the same
+material under section 10.
+
+#### 9. Acceptance Not Required for Having Copies.
+
+You are not required to accept this License in order to receive or run
+a copy of the Program. Ancillary propagation of a covered work
+occurring solely as a consequence of using peer-to-peer transmission
+to receive a copy likewise does not require acceptance. However,
+nothing other than this License grants you permission to propagate or
+modify any covered work. These actions infringe copyright if you do
+not accept this License. Therefore, by modifying or propagating a
+covered work, you indicate your acceptance of this License to do so.
+
+#### 10. Automatic Licensing of Downstream Recipients.
+
+Each time you convey a covered work, the recipient automatically
+receives a license from the original licensors, to run, modify and
+propagate that work, subject to this License. You are not responsible
+for enforcing compliance by third parties with this License.
+
+An "entity transaction" is a transaction transferring control of an
+organization, or substantially all assets of one, or subdividing an
+organization, or merging organizations. If propagation of a covered
+work results from an entity transaction, each party to that
+transaction who receives a copy of the work also receives whatever
+licenses to the work the party's predecessor in interest had or could
+give under the previous paragraph, plus a right to possession of the
+Corresponding Source of the work from the predecessor in interest, if
+the predecessor has it or can get it with reasonable efforts.
+
+You may not impose any further restrictions on the exercise of the
+rights granted or affirmed under this License. For example, you may
+not impose a license fee, royalty, or other charge for exercise of
+rights granted under this License, and you may not initiate litigation
+(including a cross-claim or counterclaim in a lawsuit) alleging that
+any patent claim is infringed by making, using, selling, offering for
+sale, or importing the Program or any portion of it.
+
+#### 11. Patents.
+
+A "contributor" is a copyright holder who authorizes use under this
+License of the Program or a work on which the Program is based. The
+work thus licensed is called the contributor's "contributor version".
+
+A contributor's "essential patent claims" are all patent claims owned
+or controlled by the contributor, whether already acquired or
+hereafter acquired, that would be infringed by some manner, permitted
+by this License, of making, using, or selling its contributor version,
+but do not include claims that would be infringed only as a
+consequence of further modification of the contributor version. For
+purposes of this definition, "control" includes the right to grant
+patent sublicenses in a manner consistent with the requirements of
+this License.
+
+Each contributor grants you a non-exclusive, worldwide, royalty-free
+patent license under the contributor's essential patent claims, to
+make, use, sell, offer for sale, import and otherwise run, modify and
+propagate the contents of its contributor version.
+
+In the following three paragraphs, a "patent license" is any express
+agreement or commitment, however denominated, not to enforce a patent
+(such as an express permission to practice a patent or covenant not to
+sue for patent infringement). To "grant" such a patent license to a
+party means to make such an agreement or commitment not to enforce a
+patent against the party.
+
+If you convey a covered work, knowingly relying on a patent license,
+and the Corresponding Source of the work is not available for anyone
+to copy, free of charge and under the terms of this License, through a
+publicly available network server or other readily accessible means,
+then you must either (1) cause the Corresponding Source to be so
+available, or (2) arrange to deprive yourself of the benefit of the
+patent license for this particular work, or (3) arrange, in a manner
+consistent with the requirements of this License, to extend the patent
+license to downstream recipients. "Knowingly relying" means you have
+actual knowledge that, but for the patent license, your conveying the
+covered work in a country, or your recipient's use of the covered work
+in a country, would infringe one or more identifiable patents in that
+country that you have reason to believe are valid.
+
+If, pursuant to or in connection with a single transaction or
+arrangement, you convey, or propagate by procuring conveyance of, a
+covered work, and grant a patent license to some of the parties
+receiving the covered work authorizing them to use, propagate, modify
+or convey a specific copy of the covered work, then the patent license
+you grant is automatically extended to all recipients of the covered
+work and works based on it.
+
+A patent license is "discriminatory" if it does not include within the
+scope of its coverage, prohibits the exercise of, or is conditioned on
+the non-exercise of one or more of the rights that are specifically
+granted under this License. You may not convey a covered work if you
+are a party to an arrangement with a third party that is in the
+business of distributing software, under which you make payment to the
+third party based on the extent of your activity of conveying the
+work, and under which the third party grants, to any of the parties
+who would receive the covered work from you, a discriminatory patent
+license (a) in connection with copies of the covered work conveyed by
+you (or copies made from those copies), or (b) primarily for and in
+connection with specific products or compilations that contain the
+covered work, unless you entered into that arrangement, or that patent
+license was granted, prior to 28 March 2007.
+
+Nothing in this License shall be construed as excluding or limiting
+any implied license or other defenses to infringement that may
+otherwise be available to you under applicable patent law.
+
+#### 12. No Surrender of Others' Freedom.
+
+If conditions are imposed on you (whether by court order, agreement or
+otherwise) that contradict the conditions of this License, they do not
+excuse you from the conditions of this License. If you cannot convey a
+covered work so as to satisfy simultaneously your obligations under
+this License and any other pertinent obligations, then as a
+consequence you may not convey it at all. For example, if you agree to
+terms that obligate you to collect a royalty for further conveying
+from those to whom you convey the Program, the only way you could
+satisfy both those terms and this License would be to refrain entirely
+from conveying the Program.
+
+#### 13. Use with the GNU Affero General Public License.
+
+Notwithstanding any other provision of this License, you have
+permission to link or combine any covered work with a work licensed
+under version 3 of the GNU Affero General Public License into a single
+combined work, and to convey the resulting work. The terms of this
+License will continue to apply to the part which is the covered work,
+but the special requirements of the GNU Affero General Public License,
+section 13, concerning interaction through a network will apply to the
+combination as such.
+
+#### 14. Revised Versions of this License.
+
+The Free Software Foundation may publish revised and/or new versions
+of the GNU General Public License from time to time. Such new versions
+will be similar in spirit to the present version, but may differ in
+detail to address new problems or concerns.
+
+Each version is given a distinguishing version number. If the Program
+specifies that a certain numbered version of the GNU General Public
+License "or any later version" applies to it, you have the option of
+following the terms and conditions either of that numbered version or
+of any later version published by the Free Software Foundation. If the
+Program does not specify a version number of the GNU General Public
+License, you may choose any version ever published by the Free
+Software Foundation.
+
+If the Program specifies that a proxy can decide which future versions
+of the GNU General Public License can be used, that proxy's public
+statement of acceptance of a version permanently authorizes you to
+choose that version for the Program.
+
+Later license versions may give you additional or different
+permissions. However, no additional obligations are imposed on any
+author or copyright holder as a result of your choosing to follow a
+later version.
+
+#### 15. Disclaimer of Warranty.
+
+THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
+APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
+HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT
+WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT
+LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
+A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND
+PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE
+DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR
+CORRECTION.
+
+#### 16. Limitation of Liability.
+
+IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
+WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR
+CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES,
+INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES
+ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT
+NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR
+LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM
+TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER
+PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
+
+#### 17. Interpretation of Sections 15 and 16.
+
+If the disclaimer of warranty and limitation of liability provided
+above cannot be given local legal effect according to their terms,
+reviewing courts shall apply local law that most closely approximates
+an absolute waiver of all civil liability in connection with the
+Program, unless a warranty or assumption of liability accompanies a
+copy of the Program in return for a fee.
+
+END OF TERMS AND CONDITIONS
+
+### How to Apply These Terms to Your New Programs
+
+If you develop a new program, and you want it to be of the greatest
+possible use to the public, the best way to achieve this is to make it
+free software which everyone can redistribute and change under these
+terms.
+
+To do so, attach the following notices to the program. It is safest to
+attach them to the start of each source file to most effectively state
+the exclusion of warranty; and each file should have at least the
+"copyright" line and a pointer to where the full notice is found.
+
+        <one line to give the program's name and a brief idea of what it does.>
+        Copyright (C) <year>  <name of author>
+
+        This program is free software: you can redistribute it and/or modify
+        it under the terms of the GNU General Public License as published by
+        the Free Software Foundation, either version 3 of the License, or
+        (at your option) any later version.
+
+        This program is distributed in the hope that it will be useful,
+        but WITHOUT ANY WARRANTY; without even the implied warranty of
+        MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+        GNU General Public License for more details.
+
+        You should have received a copy of the GNU General Public License
+        along with this program.  If not, see <https://www.gnu.org/licenses/>.
+
+Also add information on how to contact you by electronic and paper
+mail.
+
+If the program does terminal interaction, make it output a short
+notice like this when it starts in an interactive mode:
+
+        <program>  Copyright (C) <year>  <name of author>
+        This program comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
+        This is free software, and you are welcome to redistribute it
+        under certain conditions; type `show c' for details.
+
+The hypothetical commands \`show w' and \`show c' should show the
+appropriate parts of the General Public License. Of course, your
+program's commands might be different; for a GUI interface, you would
+use an "about box".
+
+You should also get your employer (if you work as a programmer) or
+school, if any, to sign a "copyright disclaimer" for the program, if
+necessary. For more information on this, and how to apply and follow
+the GNU GPL, see <https://www.gnu.org/licenses/>.
+
+The GNU General Public License does not permit incorporating your
+program into proprietary programs. If your program is a subroutine
+library, you may consider it more useful to permit linking proprietary
+applications with the library. If this is what you want to do, use the
+GNU Lesser General Public License instead of this License. But first,
+please read <https://www.gnu.org/licenses/why-not-lgpl.html>.
```

### Comparing `checkpasswords-2022.0.1/pyproject.toml` & `checkpasswords-2023/pyproject.toml`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "checkpasswords"
-version = "2022.0.1"
+version = "2023"
 license = "GPL-3.0-or-later"
 description = "CheckPasswords uses pass_import to read a password manager source file to check for duplicate passwords; check for weak passwords; identify http sites; list available 2fa options; list emails"
 authors = ["FredHappyface"]
 classifiers = [
 	"Environment :: Console",
 	"Environment :: MacOS X",
 	"Environment :: Win32 (MS Windows)",
@@ -24,24 +24,29 @@
 readme = "README.md"
 
 [tool.poetry.scripts]
 CheckPasswords = 'checkpasswords:cli'
 
 [tool.poetry.dependencies]
 python = "^3.8"
-rich = "<13,>=12.2.0"
+rich = "<14,>=13.4.2"
 zxcvbn-python = "<5,>=4.4.24"
-pass-import = "<4,>=3.2"
+pass-import = "<4,>=3.4"
 
 [tool.poetry.dev-dependencies]
-pytest = "^6.2.5"
+pytest = "^7.1.1"
+pylint = "^2.13.5"
+handsdown = "^1.1.0"
+
+[tool.poetry.group.dev.dependencies]
+gitpython = "^3.1.31"
 
 [tool.black]
 line-length = 100
-target-version = ["py37"]
+target-version = ["py38"]
 
 [tool.isort]
 profile = "black"
 indent = "Tab"
 
 [tool.pydocstyle]
 convention = "google"
@@ -58,16 +63,26 @@
 method-naming-style = "camelCase"
 variable-naming-style = "camelCase"
 
 [tool.pylint.format]
 indent-string = "\t"
 
 [tool.pylint.master]
-ignore-patterns = "test_.*?py"
+ignore-paths = ["tests"]
 
 [tool.pylint.messages_control]
 enable = ["F", "E", "W", "R", "C"]
-disable = [
-	"pointless-string-statement",
-	"superfluous-parens",
-	"bad-continuation"
-]
+disable = ["pointless-string-statement", "superfluous-parens"]
+
+[tool.tox]
+legacy_tox_ini = """
+[tox]
+env_list =
+	py311
+	py310
+	py39
+	py38
+
+[testenv]
+deps = pytest
+commands = pytest tests
+"""
```

### Comparing `checkpasswords-2022.0.1/README.md` & `checkpasswords-2023/README.md`

 * *Files 13% similar despite different names*

```diff
@@ -1,293 +1,323 @@
-[![GitHub top language](https://img.shields.io/github/languages/top/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)
-[![Repository size](https://img.shields.io/github/repo-size/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)
-[![Issues](https://img.shields.io/github/issues/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../issues)
-[![License](https://img.shields.io/github/license/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](/LICENSE.md)
-[![Commit activity](https://img.shields.io/github/commit-activity/m/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)
-[![Last commit](https://img.shields.io/github/last-commit/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)
-[![PyPI Downloads](https://img.shields.io/pypi/dm/CheckPasswords.svg?style=for-the-badge)](https://pypistats.org/packages/CheckPasswords)
-[![PyPI Total Downloads](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=total%20downloads&query=%24.total_downloads&url=https%3A%2F%2Fapi.pepy.tech%2Fapi%2Fprojects%2Fcheckpasswords)](https://pepy.tech/project/CheckPasswords)
-[![PyPI Version](https://img.shields.io/pypi/v/CheckPasswords.svg?style=for-the-badge)](https://pypi.org/project/CheckPasswords)
-
-<!-- omit in toc -->
-# CheckPasswords
-
-<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">
-
-Uses pass_import to read a password manager source file storing raw data and infers data such as:
-
-- zxcvbnScore
-- isPasswordDuplicate
-- passwordPrint
-- isHttp
-- isMfaAvailable
-- isMfaEnabled
-
-Used to:
-
-- check for duplicate passwords
-- check for weak passwords
-- identify http sites
-- list available 2fa options using data from https://2fa.directory/
-- list emails to submit to HIBP or similar
-
-<!-- omit in toc -->
-## Table of Contents
-
-- [Using](#using)
-	- [CLI Help](#cli-help)
-	- [Example Output](#example-output)
-- [Documentation](#documentation)
-- [Install With PIP](#install-with-pip)
-- [Language information](#language-information)
-	- [Built for](#built-for)
-- [Install Python on Windows](#install-python-on-windows)
-	- [Chocolatey](#chocolatey)
-	- [Windows - Python.org](#windows---pythonorg)
-- [Install Python on Linux](#install-python-on-linux)
-	- [Apt](#apt)
-	- [Dnf](#dnf)
-- [Install Python on MacOS](#install-python-on-macos)
-	- [Homebrew](#homebrew)
-	- [MacOS - Python.org](#macos---pythonorg)
-- [How to run](#how-to-run)
-	- [Windows](#windows)
-	- [Linux/ MacOS](#linux-macos)
-- [Download Project](#download-project)
-	- [Clone](#clone)
-		- [Using The Command Line](#using-the-command-line)
-		- [Using GitHub Desktop](#using-github-desktop)
-	- [Download Zip File](#download-zip-file)
-- [Community Files](#community-files)
-	- [Licence](#licence)
-	- [Changelog](#changelog)
-	- [Code of Conduct](#code-of-conduct)
-	- [Contributing](#contributing)
-	- [Security](#security)
-	- [Support](#support)
-	- [Rationale](#rationale)
-
-## Using
-
-### CLI Help
-
-```txt
-usage: __main__.py [-h] [--output-format OUTPUT_FORMAT] [--input-format INPUT_FORMAT] [--file FILE] [--no-colour]
-                   credentials
-
-checkpasswords: Uses pass_import to read a password manager source file storing raw
-data and infers data such as:
-
-- zxcvbnScore
-- isPasswordDuplicate
-- passwordPrint
-- isHttp
-- isMfaAvailable
-- isMfaEnabled
-
-Used to:
-
-- check for duplicate passwords
-- check for weak passwords
-- identify http sites
-- list available 2fa options using data from https://2fa.directory/
-- list emails to submit to HIBP or similar
-
-positional arguments:
-  credentials           Credentials/ passwords file to check
-
-options:
-  -h, --help            show this help message and exit
-  --output-format OUTPUT_FORMAT, -o OUTPUT_FORMAT
-                        Output format. One of ['ansi', 'plain', 'markdown', 'json', 'raw', 'raw-csv']. default=ansi
-  --input-format INPUT_FORMAT, -i INPUT_FORMAT
-                        Input format. One of ['1password', 'aegis', 'andotp', 'apple-keychain', 'bitwarden', 'blur', 'buttercup', 'chrome', 'clipperz', 'csv', 'dashlane', 'encryptr', 'enpass', 'firefox', 'fpm', 'freeotp+', 'gnome', 'gnome-auth', 'gopass', 'gorilla', 'kedpm', 'keepass', 'keepassx', 'keepassx2', 'keepassxc', 'keeper', 'lastpass', 'myki', 'network-manager', 'padlock', 'pass', 'passman', 'passpack', 'passpie', 'pwsafe', 'revelation', 'roboform', 'saferpass', 'upm', 'zoho']
-  --file FILE, -f FILE  Filename to write to (omit for stdout)
-  --no-colour, -z       No ANSI colours
-```
-
-### Example Output
-
-```txt
-
-                Summary
-┏━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
-┃ Issue               ┃ No. Instances ┃
-┡━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
-│ Duplicate Passwords │ 2             │
-│ Weak Passwords      │ 9             │
-│ HTTP Sites          │ 9             │
-│ Enable 2FA          │ 16            │
-│ Emails              │ 17            │
-└─────────────────────┴───────────────┘
-
-...
-```
-
-## Documentation
-
-A high-level overview of how the documentation is organized organized will help you know
-where to look for certain things:
-
-<!--
-- [Tutorials](/documentation/tutorials) take you by the hand through a series of steps to get
-  started using the software. Start here if you’re new.
--->
-- The [Technical Reference](/documentation/reference) documents APIs and other aspects of the
-  machinery. This documentation describes how to use the classes and functions at a lower level
-  and assume that you have a good high-level understanding of the software.
-<!--
-- The [Help](/documentation/help) guide provides a starting point and outlines common issues that you
-  may have.
--->
-
-## Install With PIP
-
-```python
-pip install CheckPasswords
-```
-
-Head to https://pypi.org/project/CheckPasswords/ for more info
-
-## Language information
-
-### Built for
-
-This program has been written for Python versions 3.7 - 3.10 and has been tested with both 3.7 and
-3.10
-
-## Install Python on Windows
-
-### Chocolatey
-
-```powershell
-choco install python
-```
-
-### Windows - Python.org
-
-To install Python, go to https://www.python.org/downloads/windows/ and download the latest
-version.
-
-## Install Python on Linux
-
-### Apt
-
-```bash
-sudo apt install python3.x
-```
-
-### Dnf
-
-```bash
-sudo dnf install python3.x
-```
-
-## Install Python on MacOS
-
-### Homebrew
-
-```bash
-brew install python@3.x
-```
-
-### MacOS - Python.org
-
-To install Python, go to https://www.python.org/downloads/macos/ and download the latest
-version.
-
-## How to run
-
-### Windows
-
-- Module
-	`py -3.x -m [module]` or `[module]` (if module installs a script)
-
-- File
-	`py -3.x [file]` or `./[file]`
-
-### Linux/ MacOS
-
-- Module
-	`python3.x -m [module]` or `[module]` (if module installs a script)
-
-- File
-	`python3.x [file]` or `./[file]`
-
-## Download Project
-
-### Clone
-
-#### Using The Command Line
-
-1. Press the Clone or download button in the top right
-2. Copy the URL (link)
-3. Open the command line and change directory to where you wish to
-clone to
-4. Type 'git clone' followed by URL in step 2
-	```bash
-	git clone https://github.com/FHPythonUtils/CheckPasswords
-	```
-
-More information can be found at
-https://help.github.com/en/articles/cloning-a-repository
-
-#### Using GitHub Desktop
-
-1. Press the Clone or download button in the top right
-2. Click open in desktop
-3. Choose the path for where you want and click Clone
-
-More information can be found at
-https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop
-
-### Download Zip File
-
-1. Download this GitHub repository
-2. Extract the zip archive
-3. Copy/ move to the desired location
-
-## Community Files
-
-### Licence
-
-GPLv3 License (due to `pass-import` dependency)
-(See the [LICENSE](/LICENSE.md) for more information.)
-
-### Changelog
-
-See the [Changelog](/CHANGELOG.md) for more information.
-
-### Code of Conduct
-
-Online communities include people from many backgrounds. The *Project*
-contributors are committed to providing a friendly, safe and welcoming
-environment for all. Please see the
-[Code of Conduct](https://github.com/FHPythonUtils/.github/blob/master/CODE_OF_CONDUCT.md)
- for more information.
-
-### Contributing
-
-Contributions are welcome, please see the
-[Contributing Guidelines](https://github.com/FHPythonUtils/.github/blob/master/CONTRIBUTING.md)
-for more information.
-
-### Security
-
-Thank you for improving the security of the project, please see the
-[Security Policy](https://github.com/FHPythonUtils/.github/blob/master/SECURITY.md)
-for more information.
-
-### Support
-
-Thank you for using this project, I hope it is of use to you. Please be aware that
-those involved with the project often do so for fun along with other commitments
-(such as work, family, etc). Please see the
-[Support Policy](https://github.com/FHPythonUtils/.github/blob/master/SUPPORT.md)
-for more information.
-
-### Rationale
-
-The rationale acts as a guide to various processes regarding projects such as
-the versioning scheme and the programming styles used. Please see the
-[Rationale](https://github.com/FHPythonUtils/.github/blob/master/RATIONALE.md)
-for more information.
+[![GitHub top language](https://img.shields.io/github/languages/top/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)
+[![Repository size](https://img.shields.io/github/repo-size/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)
+[![Issues](https://img.shields.io/github/issues/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../issues)
+[![License](https://img.shields.io/github/license/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](/LICENSE.md)
+[![Commit activity](https://img.shields.io/github/commit-activity/m/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)
+[![Last commit](https://img.shields.io/github/last-commit/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)
+[![PyPI Downloads](https://img.shields.io/pypi/dm/checkpasswords.svg?style=for-the-badge)](https://pypistats.org/packages/checkpasswords)
+[![PyPI Total Downloads](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=total%20downloads&query=%24.total_downloads&url=https%3A%2F%2Fapi.pepy.tech%2Fapi%2Fprojects%2Fcheckpasswords)](https://pepy.tech/project/CheckPasswords)
+[![PyPI Version](https://img.shields.io/pypi/v/CheckPasswords.svg?style=for-the-badge)](https://pypi.org/project/CheckPasswords)
+
+<!-- omit in toc -->
+# CheckPasswords
+
+<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">
+
+Uses pass_import to read a password manager source file storing raw data and infers data such as:
+
+- zxcvbnScore
+- isPasswordDuplicate
+- passwordPrint
+- isHttp
+- isMfaAvailable
+- isMfaEnabled
+
+Used to:
+
+- check for duplicate passwords
+- check for weak passwords
+- identify http sites
+- list available 2fa options using data from https://2fa.directory/
+- list emails to submit to HIBP or similar
+
+<!-- omit in toc -->
+## Table of Contents
+
+- [Using](#using)
+	- [CLI Help](#cli-help)
+	- [Example Output](#example-output)
+- [Documentation](#documentation)
+- [Install With PIP](#install-with-pip)
+- [Language information](#language-information)
+	- [Built for](#built-for)
+- [Install Python on Windows](#install-python-on-windows)
+	- [Chocolatey](#chocolatey)
+	- [Windows - Python.org](#windows---pythonorg)
+- [Install Python on Linux](#install-python-on-linux)
+	- [Apt](#apt)
+	- [Dnf](#dnf)
+- [Install Python on MacOS](#install-python-on-macos)
+	- [Homebrew](#homebrew)
+	- [MacOS - Python.org](#macos---pythonorg)
+- [How to run](#how-to-run)
+	- [Windows](#windows)
+	- [Linux/ MacOS](#linux-macos)
+- [Download Project](#download-project)
+	- [Clone](#clone)
+		- [Using The Command Line](#using-the-command-line)
+		- [Using GitHub Desktop](#using-github-desktop)
+	- [Download Zip File](#download-zip-file)
+- [Community Files](#community-files)
+	- [Licence](#licence)
+	- [Changelog](#changelog)
+	- [Code of Conduct](#code-of-conduct)
+	- [Contributing](#contributing)
+	- [Security](#security)
+	- [Support](#support)
+	- [Rationale](#rationale)
+
+## Using
+
+### CLI Help
+
+```txt
+usage: __main__.py [-h] [--output-format OUTPUT_FORMAT] [--input-format INPUT_FORMAT] [--file FILE] [--no-colour]
+                   credentials
+
+checkpasswords: Uses pass_import to read a password manager source file storing raw
+data and infers data such as:
+
+- zxcvbnScore
+- isPasswordDuplicate
+- passwordPrint
+- isHttp
+- isMfaAvailable
+- isMfaEnabled
+
+Used to:
+
+- check for duplicate passwords
+- check for weak passwords
+- identify http sites
+- list available 2fa options using data from https://2fa.directory/
+- list emails to submit to HIBP or similar
+
+positional arguments:
+  credentials           Credentials/ passwords file to check
+
+options:
+  -h, --help            show this help message and exit
+  --output-format OUTPUT_FORMAT, -o OUTPUT_FORMAT
+                        Output format. One of ['ansi', 'plain', 'markdown', 'json', 'raw', 'raw-csv']. default=ansi
+  --input-format INPUT_FORMAT, -i INPUT_FORMAT
+                        Input format. One of ['1password', 'aegis', 'andotp', 'apple-keychain', 'bitwarden', 'blur', 'buttercup', 'chrome', 'clipperz', 'csv', 'dashlane', 'encryptr', 'enpass', 'firefox', 'fpm', 'freeotp+', 'gnome', 'gnome-auth', 'gopass', 'gorilla', 'kedpm', 'keepass', 'keepassx', 'keepassx2', 'keepassxc', 'keeper', 'lastpass', 'myki', 'network-manager', 'padlock', 'pass', 'passman', 'passpack', 'passpie', 'pwsafe', 'revelation', 'roboform', 'saferpass', 'upm', 'zoho']
+  --file FILE, -f FILE  Filename to write to (omit for stdout)
+  --no-colour, -z       No ANSI colours
+```
+
+### Example Output
+
+```txt
+
+                Summary
+┏━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
+┃ Issue               ┃ No. Instances ┃
+┡━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
+│ Duplicate Passwords │ 2             │
+│ Weak Passwords      │ 9             │
+│ HTTP Sites          │ 9             │
+│ Enable 2FA          │ 16            │
+│ Emails              │ 17            │
+└─────────────────────┴───────────────┘
+
+...
+```
+
+## Documentation
+
+A high-level overview of how the documentation is organized organized will help you know
+where to look for certain things:
+
+<!--
+- [Tutorials](/documentation/tutorials) take you by the hand through a series of steps to get
+  started using the software. Start here if you’re new.
+-->
+- The [Technical Reference](/documentation/reference) documents APIs and other aspects of the
+  machinery. This documentation describes how to use the classes and functions at a lower level
+  and assume that you have a good high-level understanding of the software.
+<!--
+- The [Help](/documentation/help) guide provides a starting point and outlines common issues that you
+  may have.
+-->
+
+## Install With PIP
+
+```python
+pip install CheckPasswords
+```
+
+Head to https://pypi.org/project/CheckPasswords/ for more info
+
+## Language information
+
+### Built for
+
+This program has been written for Python versions 3.8 - 3.11 and has been tested with both 3.8 and
+3.11
+
+## Install Python on Windows
+
+### Chocolatey
+
+```powershell
+choco install python
+```
+
+### Windows - Python.org
+
+To install Python, go to https://www.python.org/downloads/windows/ and download the latest
+version.
+
+## Install Python on Linux
+
+### Apt
+
+```bash
+sudo apt install python3.x
+```
+
+### Dnf
+
+```bash
+sudo dnf install python3.x
+```
+
+## Install Python on MacOS
+
+### Homebrew
+
+```bash
+brew install python@3.x
+```
+
+### MacOS - Python.org
+
+To install Python, go to https://www.python.org/downloads/macos/ and download the latest
+version.
+
+## How to run
+
+### Windows
+
+- Module
+	`py -3.x -m [module]` or `[module]` (if module installs a script)
+
+- File
+	`py -3.x [file]` or `./[file]`
+
+### Linux/ MacOS
+
+- Module
+	`python3.x -m [module]` or `[module]` (if module installs a script)
+
+- File
+	`python3.x [file]` or `./[file]`
+
+## Building
+
+This project uses https://github.com/FHPythonUtils/FHMake to automate most of the building. This
+command generates the documentation, updates the requirements.txt and builds the library artefacts
+
+Note the functionality provided by fhmake can be approximated by the following
+
+```sh
+handsdown  --cleanup -o documentation/reference
+poetry export -f requirements.txt --output requirements.txt
+poetry export -f requirements.txt --with dev --output requirements_optional.txt
+poetry build
+```
+
+`fhmake audit` can be run to perform additional checks
+
+## Testing
+
+For testing with the version of python used by poetry use
+
+```sh
+poetry run pytest
+```
+
+Alternatively use `tox` to run tests over python 3.8 - 3.11
+
+```sh
+tox
+```
+
+## Download Project
+
+### Clone
+
+#### Using The Command Line
+
+1. Press the Clone or download button in the top right
+2. Copy the URL (link)
+3. Open the command line and change directory to where you wish to
+clone to
+4. Type 'git clone' followed by URL in step 2
+	```bash
+	git clone https://github.com/FHPythonUtils/CheckPasswords
+	```
+
+More information can be found at
+https://help.github.com/en/articles/cloning-a-repository
+
+#### Using GitHub Desktop
+
+1. Press the Clone or download button in the top right
+2. Click open in desktop
+3. Choose the path for where you want and click Clone
+
+More information can be found at
+https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop
+
+### Download Zip File
+
+1. Download this GitHub repository
+2. Extract the zip archive
+3. Copy/ move to the desired location
+
+## Community Files
+
+### Licence
+
+GPLv3 License (due to `pass-import` dependency)
+(See the [LICENSE](/LICENSE.md) for more information.)
+
+### Changelog
+
+See the [Changelog](/CHANGELOG.md) for more information.
+
+### Code of Conduct
+
+Online communities include people from many backgrounds. The *Project*
+contributors are committed to providing a friendly, safe and welcoming
+environment for all. Please see the
+[Code of Conduct](https://github.com/FHPythonUtils/.github/blob/master/CODE_OF_CONDUCT.md)
+ for more information.
+
+### Contributing
+
+Contributions are welcome, please see the
+[Contributing Guidelines](https://github.com/FHPythonUtils/.github/blob/master/CONTRIBUTING.md)
+for more information.
+
+### Security
+
+Thank you for improving the security of the project, please see the
+[Security Policy](https://github.com/FHPythonUtils/.github/blob/master/SECURITY.md)
+for more information.
+
+### Support
+
+Thank you for using this project, I hope it is of use to you. Please be aware that
+those involved with the project often do so for fun along with other commitments
+(such as work, family, etc). Please see the
+[Support Policy](https://github.com/FHPythonUtils/.github/blob/master/SUPPORT.md)
+for more information.
+
+### Rationale
+
+The rationale acts as a guide to various processes regarding projects such as
+the versioning scheme and the programming styles used. Please see the
+[Rationale](https://github.com/FHPythonUtils/.github/blob/master/RATIONALE.md)
+for more information.
```

### Comparing `checkpasswords-2022.0.1/setup.py` & `checkpasswords-2023/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -4,28 +4,28 @@
 packages = \
 ['checkpasswords', 'checkpasswords.io']
 
 package_data = \
 {'': ['*']}
 
 install_requires = \
-['pass-import>=3.2,<4', 'rich>=12.2.0,<13', 'zxcvbn-python>=4.4.24,<5']
+['pass-import>=3.4,<4', 'rich>=13.4.2,<14', 'zxcvbn-python>=4.4.24,<5']
 
 entry_points = \
 {'console_scripts': ['CheckPasswords = checkpasswords:cli']}
 
 setup_kwargs = {
     'name': 'checkpasswords',
-    'version': '2022.0.1',
+    'version': '2023',
     'description': 'CheckPasswords uses pass_import to read a password manager source file to check for duplicate passwords; check for weak passwords; identify http sites; list available 2fa options; list emails',
-    'long_description': '[![GitHub top language](https://img.shields.io/github/languages/top/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)\n[![Repository size](https://img.shields.io/github/repo-size/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)\n[![Issues](https://img.shields.io/github/issues/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../issues)\n[![License](https://img.shields.io/github/license/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](/LICENSE.md)\n[![Commit activity](https://img.shields.io/github/commit-activity/m/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)\n[![Last commit](https://img.shields.io/github/last-commit/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)\n[![PyPI Downloads](https://img.shields.io/pypi/dm/CheckPasswords.svg?style=for-the-badge)](https://pypistats.org/packages/CheckPasswords)\n[![PyPI Total Downloads](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=total%20downloads&query=%24.total_downloads&url=https%3A%2F%2Fapi.pepy.tech%2Fapi%2Fprojects%2Fcheckpasswords)](https://pepy.tech/project/CheckPasswords)\n[![PyPI Version](https://img.shields.io/pypi/v/CheckPasswords.svg?style=for-the-badge)](https://pypi.org/project/CheckPasswords)\n\n<!-- omit in toc -->\n# CheckPasswords\n\n<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">\n\nUses pass_import to read a password manager source file storing raw data and infers data such as:\n\n- zxcvbnScore\n- isPasswordDuplicate\n- passwordPrint\n- isHttp\n- isMfaAvailable\n- isMfaEnabled\n\nUsed to:\n\n- check for duplicate passwords\n- check for weak passwords\n- identify http sites\n- list available 2fa options using data from https://2fa.directory/\n- list emails to submit to HIBP or similar\n\n<!-- omit in toc -->\n## Table of Contents\n\n- [Using](#using)\n\t- [CLI Help](#cli-help)\n\t- [Example Output](#example-output)\n- [Documentation](#documentation)\n- [Install With PIP](#install-with-pip)\n- [Language information](#language-information)\n\t- [Built for](#built-for)\n- [Install Python on Windows](#install-python-on-windows)\n\t- [Chocolatey](#chocolatey)\n\t- [Windows - Python.org](#windows---pythonorg)\n- [Install Python on Linux](#install-python-on-linux)\n\t- [Apt](#apt)\n\t- [Dnf](#dnf)\n- [Install Python on MacOS](#install-python-on-macos)\n\t- [Homebrew](#homebrew)\n\t- [MacOS - Python.org](#macos---pythonorg)\n- [How to run](#how-to-run)\n\t- [Windows](#windows)\n\t- [Linux/ MacOS](#linux-macos)\n- [Download Project](#download-project)\n\t- [Clone](#clone)\n\t\t- [Using The Command Line](#using-the-command-line)\n\t\t- [Using GitHub Desktop](#using-github-desktop)\n\t- [Download Zip File](#download-zip-file)\n- [Community Files](#community-files)\n\t- [Licence](#licence)\n\t- [Changelog](#changelog)\n\t- [Code of Conduct](#code-of-conduct)\n\t- [Contributing](#contributing)\n\t- [Security](#security)\n\t- [Support](#support)\n\t- [Rationale](#rationale)\n\n## Using\n\n### CLI Help\n\n```txt\nusage: __main__.py [-h] [--output-format OUTPUT_FORMAT] [--input-format INPUT_FORMAT] [--file FILE] [--no-colour]\n                   credentials\n\ncheckpasswords: Uses pass_import to read a password manager source file storing raw\ndata and infers data such as:\n\n- zxcvbnScore\n- isPasswordDuplicate\n- passwordPrint\n- isHttp\n- isMfaAvailable\n- isMfaEnabled\n\nUsed to:\n\n- check for duplicate passwords\n- check for weak passwords\n- identify http sites\n- list available 2fa options using data from https://2fa.directory/\n- list emails to submit to HIBP or similar\n\npositional arguments:\n  credentials           Credentials/ passwords file to check\n\noptions:\n  -h, --help            show this help message and exit\n  --output-format OUTPUT_FORMAT, -o OUTPUT_FORMAT\n                        Output format. One of [\'ansi\', \'plain\', \'markdown\', \'json\', \'raw\', \'raw-csv\']. default=ansi\n  --input-format INPUT_FORMAT, -i INPUT_FORMAT\n                        Input format. One of [\'1password\', \'aegis\', \'andotp\', \'apple-keychain\', \'bitwarden\', \'blur\', \'buttercup\', \'chrome\', \'clipperz\', \'csv\', \'dashlane\', \'encryptr\', \'enpass\', \'firefox\', \'fpm\', \'freeotp+\', \'gnome\', \'gnome-auth\', \'gopass\', \'gorilla\', \'kedpm\', \'keepass\', \'keepassx\', \'keepassx2\', \'keepassxc\', \'keeper\', \'lastpass\', \'myki\', \'network-manager\', \'padlock\', \'pass\', \'passman\', \'passpack\', \'passpie\', \'pwsafe\', \'revelation\', \'roboform\', \'saferpass\', \'upm\', \'zoho\']\n  --file FILE, -f FILE  Filename to write to (omit for stdout)\n  --no-colour, -z       No ANSI colours\n```\n\n### Example Output\n\n```txt\n\n                Summary\n┏━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓\n┃ Issue               ┃ No. Instances ┃\n┡━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩\n│ Duplicate Passwords │ 2             │\n│ Weak Passwords      │ 9             │\n│ HTTP Sites          │ 9             │\n│ Enable 2FA          │ 16            │\n│ Emails              │ 17            │\n└─────────────────────┴───────────────┘\n\n...\n```\n\n## Documentation\n\nA high-level overview of how the documentation is organized organized will help you know\nwhere to look for certain things:\n\n<!--\n- [Tutorials](/documentation/tutorials) take you by the hand through a series of steps to get\n  started using the software. Start here if you’re new.\n-->\n- The [Technical Reference](/documentation/reference) documents APIs and other aspects of the\n  machinery. This documentation describes how to use the classes and functions at a lower level\n  and assume that you have a good high-level understanding of the software.\n<!--\n- The [Help](/documentation/help) guide provides a starting point and outlines common issues that you\n  may have.\n-->\n\n## Install With PIP\n\n```python\npip install CheckPasswords\n```\n\nHead to https://pypi.org/project/CheckPasswords/ for more info\n\n## Language information\n\n### Built for\n\nThis program has been written for Python versions 3.7 - 3.10 and has been tested with both 3.7 and\n3.10\n\n## Install Python on Windows\n\n### Chocolatey\n\n```powershell\nchoco install python\n```\n\n### Windows - Python.org\n\nTo install Python, go to https://www.python.org/downloads/windows/ and download the latest\nversion.\n\n## Install Python on Linux\n\n### Apt\n\n```bash\nsudo apt install python3.x\n```\n\n### Dnf\n\n```bash\nsudo dnf install python3.x\n```\n\n## Install Python on MacOS\n\n### Homebrew\n\n```bash\nbrew install python@3.x\n```\n\n### MacOS - Python.org\n\nTo install Python, go to https://www.python.org/downloads/macos/ and download the latest\nversion.\n\n## How to run\n\n### Windows\n\n- Module\n\t`py -3.x -m [module]` or `[module]` (if module installs a script)\n\n- File\n\t`py -3.x [file]` or `./[file]`\n\n### Linux/ MacOS\n\n- Module\n\t`python3.x -m [module]` or `[module]` (if module installs a script)\n\n- File\n\t`python3.x [file]` or `./[file]`\n\n## Download Project\n\n### Clone\n\n#### Using The Command Line\n\n1. Press the Clone or download button in the top right\n2. Copy the URL (link)\n3. Open the command line and change directory to where you wish to\nclone to\n4. Type \'git clone\' followed by URL in step 2\n\t```bash\n\tgit clone https://github.com/FHPythonUtils/CheckPasswords\n\t```\n\nMore information can be found at\nhttps://help.github.com/en/articles/cloning-a-repository\n\n#### Using GitHub Desktop\n\n1. Press the Clone or download button in the top right\n2. Click open in desktop\n3. Choose the path for where you want and click Clone\n\nMore information can be found at\nhttps://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop\n\n### Download Zip File\n\n1. Download this GitHub repository\n2. Extract the zip archive\n3. Copy/ move to the desired location\n\n## Community Files\n\n### Licence\n\nGPLv3 License (due to `pass-import` dependency)\n(See the [LICENSE](/LICENSE.md) for more information.)\n\n### Changelog\n\nSee the [Changelog](/CHANGELOG.md) for more information.\n\n### Code of Conduct\n\nOnline communities include people from many backgrounds. The *Project*\ncontributors are committed to providing a friendly, safe and welcoming\nenvironment for all. Please see the\n[Code of Conduct](https://github.com/FHPythonUtils/.github/blob/master/CODE_OF_CONDUCT.md)\n for more information.\n\n### Contributing\n\nContributions are welcome, please see the\n[Contributing Guidelines](https://github.com/FHPythonUtils/.github/blob/master/CONTRIBUTING.md)\nfor more information.\n\n### Security\n\nThank you for improving the security of the project, please see the\n[Security Policy](https://github.com/FHPythonUtils/.github/blob/master/SECURITY.md)\nfor more information.\n\n### Support\n\nThank you for using this project, I hope it is of use to you. Please be aware that\nthose involved with the project often do so for fun along with other commitments\n(such as work, family, etc). Please see the\n[Support Policy](https://github.com/FHPythonUtils/.github/blob/master/SUPPORT.md)\nfor more information.\n\n### Rationale\n\nThe rationale acts as a guide to various processes regarding projects such as\nthe versioning scheme and the programming styles used. Please see the\n[Rationale](https://github.com/FHPythonUtils/.github/blob/master/RATIONALE.md)\nfor more information.\n',
+    'long_description': '[![GitHub top language](https://img.shields.io/github/languages/top/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)\n[![Repository size](https://img.shields.io/github/repo-size/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)\n[![Issues](https://img.shields.io/github/issues/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../issues)\n[![License](https://img.shields.io/github/license/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](/LICENSE.md)\n[![Commit activity](https://img.shields.io/github/commit-activity/m/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)\n[![Last commit](https://img.shields.io/github/last-commit/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)\n[![PyPI Downloads](https://img.shields.io/pypi/dm/checkpasswords.svg?style=for-the-badge)](https://pypistats.org/packages/checkpasswords)\n[![PyPI Total Downloads](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=total%20downloads&query=%24.total_downloads&url=https%3A%2F%2Fapi.pepy.tech%2Fapi%2Fprojects%2Fcheckpasswords)](https://pepy.tech/project/CheckPasswords)\n[![PyPI Version](https://img.shields.io/pypi/v/CheckPasswords.svg?style=for-the-badge)](https://pypi.org/project/CheckPasswords)\n\n<!-- omit in toc -->\n# CheckPasswords\n\n<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">\n\nUses pass_import to read a password manager source file storing raw data and infers data such as:\n\n- zxcvbnScore\n- isPasswordDuplicate\n- passwordPrint\n- isHttp\n- isMfaAvailable\n- isMfaEnabled\n\nUsed to:\n\n- check for duplicate passwords\n- check for weak passwords\n- identify http sites\n- list available 2fa options using data from https://2fa.directory/\n- list emails to submit to HIBP or similar\n\n<!-- omit in toc -->\n## Table of Contents\n\n- [Using](#using)\n\t- [CLI Help](#cli-help)\n\t- [Example Output](#example-output)\n- [Documentation](#documentation)\n- [Install With PIP](#install-with-pip)\n- [Language information](#language-information)\n\t- [Built for](#built-for)\n- [Install Python on Windows](#install-python-on-windows)\n\t- [Chocolatey](#chocolatey)\n\t- [Windows - Python.org](#windows---pythonorg)\n- [Install Python on Linux](#install-python-on-linux)\n\t- [Apt](#apt)\n\t- [Dnf](#dnf)\n- [Install Python on MacOS](#install-python-on-macos)\n\t- [Homebrew](#homebrew)\n\t- [MacOS - Python.org](#macos---pythonorg)\n- [How to run](#how-to-run)\n\t- [Windows](#windows)\n\t- [Linux/ MacOS](#linux-macos)\n- [Download Project](#download-project)\n\t- [Clone](#clone)\n\t\t- [Using The Command Line](#using-the-command-line)\n\t\t- [Using GitHub Desktop](#using-github-desktop)\n\t- [Download Zip File](#download-zip-file)\n- [Community Files](#community-files)\n\t- [Licence](#licence)\n\t- [Changelog](#changelog)\n\t- [Code of Conduct](#code-of-conduct)\n\t- [Contributing](#contributing)\n\t- [Security](#security)\n\t- [Support](#support)\n\t- [Rationale](#rationale)\n\n## Using\n\n### CLI Help\n\n```txt\nusage: __main__.py [-h] [--output-format OUTPUT_FORMAT] [--input-format INPUT_FORMAT] [--file FILE] [--no-colour]\n                   credentials\n\ncheckpasswords: Uses pass_import to read a password manager source file storing raw\ndata and infers data such as:\n\n- zxcvbnScore\n- isPasswordDuplicate\n- passwordPrint\n- isHttp\n- isMfaAvailable\n- isMfaEnabled\n\nUsed to:\n\n- check for duplicate passwords\n- check for weak passwords\n- identify http sites\n- list available 2fa options using data from https://2fa.directory/\n- list emails to submit to HIBP or similar\n\npositional arguments:\n  credentials           Credentials/ passwords file to check\n\noptions:\n  -h, --help            show this help message and exit\n  --output-format OUTPUT_FORMAT, -o OUTPUT_FORMAT\n                        Output format. One of [\'ansi\', \'plain\', \'markdown\', \'json\', \'raw\', \'raw-csv\']. default=ansi\n  --input-format INPUT_FORMAT, -i INPUT_FORMAT\n                        Input format. One of [\'1password\', \'aegis\', \'andotp\', \'apple-keychain\', \'bitwarden\', \'blur\', \'buttercup\', \'chrome\', \'clipperz\', \'csv\', \'dashlane\', \'encryptr\', \'enpass\', \'firefox\', \'fpm\', \'freeotp+\', \'gnome\', \'gnome-auth\', \'gopass\', \'gorilla\', \'kedpm\', \'keepass\', \'keepassx\', \'keepassx2\', \'keepassxc\', \'keeper\', \'lastpass\', \'myki\', \'network-manager\', \'padlock\', \'pass\', \'passman\', \'passpack\', \'passpie\', \'pwsafe\', \'revelation\', \'roboform\', \'saferpass\', \'upm\', \'zoho\']\n  --file FILE, -f FILE  Filename to write to (omit for stdout)\n  --no-colour, -z       No ANSI colours\n```\n\n### Example Output\n\n```txt\n\n                Summary\n┏━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓\n┃ Issue               ┃ No. Instances ┃\n┡━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩\n│ Duplicate Passwords │ 2             │\n│ Weak Passwords      │ 9             │\n│ HTTP Sites          │ 9             │\n│ Enable 2FA          │ 16            │\n│ Emails              │ 17            │\n└─────────────────────┴───────────────┘\n\n...\n```\n\n## Documentation\n\nA high-level overview of how the documentation is organized organized will help you know\nwhere to look for certain things:\n\n<!--\n- [Tutorials](/documentation/tutorials) take you by the hand through a series of steps to get\n  started using the software. Start here if you’re new.\n-->\n- The [Technical Reference](/documentation/reference) documents APIs and other aspects of the\n  machinery. This documentation describes how to use the classes and functions at a lower level\n  and assume that you have a good high-level understanding of the software.\n<!--\n- The [Help](/documentation/help) guide provides a starting point and outlines common issues that you\n  may have.\n-->\n\n## Install With PIP\n\n```python\npip install CheckPasswords\n```\n\nHead to https://pypi.org/project/CheckPasswords/ for more info\n\n## Language information\n\n### Built for\n\nThis program has been written for Python versions 3.8 - 3.11 and has been tested with both 3.8 and\n3.11\n\n## Install Python on Windows\n\n### Chocolatey\n\n```powershell\nchoco install python\n```\n\n### Windows - Python.org\n\nTo install Python, go to https://www.python.org/downloads/windows/ and download the latest\nversion.\n\n## Install Python on Linux\n\n### Apt\n\n```bash\nsudo apt install python3.x\n```\n\n### Dnf\n\n```bash\nsudo dnf install python3.x\n```\n\n## Install Python on MacOS\n\n### Homebrew\n\n```bash\nbrew install python@3.x\n```\n\n### MacOS - Python.org\n\nTo install Python, go to https://www.python.org/downloads/macos/ and download the latest\nversion.\n\n## How to run\n\n### Windows\n\n- Module\n\t`py -3.x -m [module]` or `[module]` (if module installs a script)\n\n- File\n\t`py -3.x [file]` or `./[file]`\n\n### Linux/ MacOS\n\n- Module\n\t`python3.x -m [module]` or `[module]` (if module installs a script)\n\n- File\n\t`python3.x [file]` or `./[file]`\n\n## Building\n\nThis project uses https://github.com/FHPythonUtils/FHMake to automate most of the building. This\ncommand generates the documentation, updates the requirements.txt and builds the library artefacts\n\nNote the functionality provided by fhmake can be approximated by the following\n\n```sh\nhandsdown  --cleanup -o documentation/reference\npoetry export -f requirements.txt --output requirements.txt\npoetry export -f requirements.txt --with dev --output requirements_optional.txt\npoetry build\n```\n\n`fhmake audit` can be run to perform additional checks\n\n## Testing\n\nFor testing with the version of python used by poetry use\n\n```sh\npoetry run pytest\n```\n\nAlternatively use `tox` to run tests over python 3.8 - 3.11\n\n```sh\ntox\n```\n\n## Download Project\n\n### Clone\n\n#### Using The Command Line\n\n1. Press the Clone or download button in the top right\n2. Copy the URL (link)\n3. Open the command line and change directory to where you wish to\nclone to\n4. Type \'git clone\' followed by URL in step 2\n\t```bash\n\tgit clone https://github.com/FHPythonUtils/CheckPasswords\n\t```\n\nMore information can be found at\nhttps://help.github.com/en/articles/cloning-a-repository\n\n#### Using GitHub Desktop\n\n1. Press the Clone or download button in the top right\n2. Click open in desktop\n3. Choose the path for where you want and click Clone\n\nMore information can be found at\nhttps://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop\n\n### Download Zip File\n\n1. Download this GitHub repository\n2. Extract the zip archive\n3. Copy/ move to the desired location\n\n## Community Files\n\n### Licence\n\nGPLv3 License (due to `pass-import` dependency)\n(See the [LICENSE](/LICENSE.md) for more information.)\n\n### Changelog\n\nSee the [Changelog](/CHANGELOG.md) for more information.\n\n### Code of Conduct\n\nOnline communities include people from many backgrounds. The *Project*\ncontributors are committed to providing a friendly, safe and welcoming\nenvironment for all. Please see the\n[Code of Conduct](https://github.com/FHPythonUtils/.github/blob/master/CODE_OF_CONDUCT.md)\n for more information.\n\n### Contributing\n\nContributions are welcome, please see the\n[Contributing Guidelines](https://github.com/FHPythonUtils/.github/blob/master/CONTRIBUTING.md)\nfor more information.\n\n### Security\n\nThank you for improving the security of the project, please see the\n[Security Policy](https://github.com/FHPythonUtils/.github/blob/master/SECURITY.md)\nfor more information.\n\n### Support\n\nThank you for using this project, I hope it is of use to you. Please be aware that\nthose involved with the project often do so for fun along with other commitments\n(such as work, family, etc). Please see the\n[Support Policy](https://github.com/FHPythonUtils/.github/blob/master/SUPPORT.md)\nfor more information.\n\n### Rationale\n\nThe rationale acts as a guide to various processes regarding projects such as\nthe versioning scheme and the programming styles used. Please see the\n[Rationale](https://github.com/FHPythonUtils/.github/blob/master/RATIONALE.md)\nfor more information.\n',
     'author': 'FredHappyface',
-    'author_email': None,
-    'maintainer': None,
-    'maintainer_email': None,
+    'author_email': 'None',
+    'maintainer': 'None',
+    'maintainer_email': 'None',
     'url': 'https://github.com/FHPythonUtils/CheckPasswords',
     'packages': packages,
     'package_data': package_data,
     'install_requires': install_requires,
     'entry_points': entry_points,
     'python_requires': '>=3.8,<4.0',
 }
```

### Comparing `checkpasswords-2022.0.1/PKG-INFO` & `checkpasswords-2023/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: checkpasswords
-Version: 2022.0.1
+Version: 2023
 Summary: CheckPasswords uses pass_import to read a password manager source file to check for duplicate passwords; check for weak passwords; identify http sites; list available 2fa options; list emails
 Home-page: https://github.com/FHPythonUtils/CheckPasswords
 License: GPL-3.0-or-later
 Author: FredHappyface
 Requires-Python: >=3.8,<4.0
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
@@ -12,35 +12,36 @@
 Classifier: Environment :: Win32 (MS Windows)
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Education
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Natural Language :: English
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Topic :: Security
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Utilities
-Requires-Dist: pass-import (>=3.2,<4)
-Requires-Dist: rich (>=12.2.0,<13)
+Requires-Dist: pass-import (>=3.4,<4)
+Requires-Dist: rich (>=13.4.2,<14)
 Requires-Dist: zxcvbn-python (>=4.4.24,<5)
 Project-URL: Documentation, https://github.com/FHPythonUtils/CheckPasswords/blob/master/README.md
 Project-URL: Repository, https://github.com/FHPythonUtils/CheckPasswords
 Description-Content-Type: text/markdown
 
 [![GitHub top language](https://img.shields.io/github/languages/top/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)
 [![Repository size](https://img.shields.io/github/repo-size/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../)
 [![Issues](https://img.shields.io/github/issues/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../issues)
 [![License](https://img.shields.io/github/license/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](/LICENSE.md)
 [![Commit activity](https://img.shields.io/github/commit-activity/m/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)
 [![Last commit](https://img.shields.io/github/last-commit/FHPythonUtils/CheckPasswords.svg?style=for-the-badge)](../../commits/master)
-[![PyPI Downloads](https://img.shields.io/pypi/dm/CheckPasswords.svg?style=for-the-badge)](https://pypistats.org/packages/CheckPasswords)
+[![PyPI Downloads](https://img.shields.io/pypi/dm/checkpasswords.svg?style=for-the-badge)](https://pypistats.org/packages/checkpasswords)
 [![PyPI Total Downloads](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=total%20downloads&query=%24.total_downloads&url=https%3A%2F%2Fapi.pepy.tech%2Fapi%2Fprojects%2Fcheckpasswords)](https://pepy.tech/project/CheckPasswords)
 [![PyPI Version](https://img.shields.io/pypi/v/CheckPasswords.svg?style=for-the-badge)](https://pypi.org/project/CheckPasswords)
 
 <!-- omit in toc -->
 # CheckPasswords
 
 <img src="readme-assets/icons/name.png" alt="Project Icon" width="750">
@@ -180,16 +181,16 @@
 
 Head to https://pypi.org/project/CheckPasswords/ for more info
 
 ## Language information
 
 ### Built for
 
-This program has been written for Python versions 3.7 - 3.10 and has been tested with both 3.7 and
-3.10
+This program has been written for Python versions 3.8 - 3.11 and has been tested with both 3.8 and
+3.11
 
 ## Install Python on Windows
 
 ### Chocolatey
 
 ```powershell
 choco install python
@@ -241,14 +242,44 @@
 
 - Module
 	`python3.x -m [module]` or `[module]` (if module installs a script)
 
 - File
 	`python3.x [file]` or `./[file]`
 
+## Building
+
+This project uses https://github.com/FHPythonUtils/FHMake to automate most of the building. This
+command generates the documentation, updates the requirements.txt and builds the library artefacts
+
+Note the functionality provided by fhmake can be approximated by the following
+
+```sh
+handsdown  --cleanup -o documentation/reference
+poetry export -f requirements.txt --output requirements.txt
+poetry export -f requirements.txt --with dev --output requirements_optional.txt
+poetry build
+```
+
+`fhmake audit` can be run to perform additional checks
+
+## Testing
+
+For testing with the version of python used by poetry use
+
+```sh
+poetry run pytest
+```
+
+Alternatively use `tox` to run tests over python 3.8 - 3.11
+
+```sh
+tox
+```
+
 ## Download Project
 
 ### Clone
 
 #### Using The Command Line
 
 1. Press the Clone or download button in the top right
```

