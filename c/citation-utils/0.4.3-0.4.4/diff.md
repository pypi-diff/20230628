# Comparing `tmp/citation_utils-0.4.3.tar.gz` & `tmp/citation_utils-0.4.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "citation_utils-0.4.3.tar", max compression
+gzip compressed data, was "citation_utils-0.4.4.tar", max compression
```

## Comparing `citation_utils-0.4.3.tar` & `citation_utils-0.4.4.tar`

### file list

```diff
@@ -1,27 +1,27 @@
--rw-r--r--   0        0        0     1491 2023-06-23 10:27:21.228309 citation_utils-0.4.3/LICENSE
--rw-r--r--   0        0        0      653 2023-06-25 09:54:14.887730 citation_utils-0.4.3/citation_utils/__init__.py
--rw-r--r--   0        0        0    16831 2023-06-26 01:44:57.939840 citation_utils-0.4.3/citation_utils/citation.py
--rw-r--r--   0        0        0     1179 2023-06-25 09:54:14.891749 citation_utils-0.4.3/citation_utils/dockets/__init__.py
--rw-r--r--   0        0        0     3155 2023-06-25 09:54:14.895013 citation_utils-0.4.3/citation_utils/dockets/constructed_ac.py
--rw-r--r--   0        0        0     3194 2023-06-25 09:54:14.895319 citation_utils-0.4.3/citation_utils/dockets/constructed_am.py
--rw-r--r--   0        0        0     2457 2023-06-25 09:54:14.895608 citation_utils-0.4.3/citation_utils/dockets/constructed_bm.py
--rw-r--r--   0        0        0     2893 2023-06-25 09:54:14.895906 citation_utils-0.4.3/citation_utils/dockets/constructed_gr.py
--rw-r--r--   0        0        0     2094 2023-06-25 09:54:14.896184 citation_utils-0.4.3/citation_utils/dockets/constructed_jib.py
--rw-r--r--   0        0        0     2385 2023-06-25 09:54:14.896448 citation_utils-0.4.3/citation_utils/dockets/constructed_oca.py
--rw-r--r--   0        0        0     1597 2023-06-25 09:54:14.896710 citation_utils-0.4.3/citation_utils/dockets/constructed_pet.py
--rw-r--r--   0        0        0     1767 2023-06-25 09:54:14.896999 citation_utils-0.4.3/citation_utils/dockets/constructed_udk.py
--rw-r--r--   0        0        0      364 2023-06-25 10:00:40.543092 citation_utils-0.4.3/citation_utils/dockets/models/__init__.py
--rw-r--r--   0        0        0     4834 2023-06-25 09:54:14.900031 citation_utils-0.4.3/citation_utils/dockets/models/constructor.py
--rw-r--r--   0        0        0     1373 2023-06-25 09:54:14.900293 citation_utils-0.4.3/citation_utils/dockets/models/docket_category.py
--rw-r--r--   0        0        0     1696 2023-06-25 09:54:14.900588 citation_utils-0.4.3/citation_utils/dockets/models/docket_citation.py
--rw-r--r--   0        0        0     5272 2023-06-26 01:40:40.533138 citation_utils-0.4.3/citation_utils/dockets/models/docket_model.py
--rw-r--r--   0        0        0     1419 2023-06-25 09:54:14.901088 citation_utils-0.4.3/citation_utils/dockets/models/docket_rules.py
--rw-r--r--   0        0        0     2911 2023-06-25 09:54:14.901368 citation_utils-0.4.3/citation_utils/dockets/models/gr_clean.py
--rw-r--r--   0        0        0       81 2023-06-25 09:54:14.902014 citation_utils-0.4.3/citation_utils/dockets/models/misc/__init__.py
--rw-r--r--   0        0        0      746 2023-06-25 09:54:14.903593 citation_utils-0.4.3/citation_utils/dockets/models/misc/extra.py
--rw-r--r--   0        0        0     1514 2023-06-25 09:54:14.903861 citation_utils-0.4.3/citation_utils/dockets/models/misc/num.py
--rw-r--r--   0        0        0      242 2023-06-25 09:54:14.904129 citation_utils-0.4.3/citation_utils/dockets/models/misc/x.py
--rw-r--r--   0        0        0     5760 2023-06-25 09:54:14.904387 citation_utils-0.4.3/citation_utils/document.py
--rw-r--r--   0        0        0     2531 2023-06-25 09:54:14.904670 citation_utils-0.4.3/citation_utils/special.py
--rw-r--r--   0        0        0     1312 2023-06-26 01:48:45.055874 citation_utils-0.4.3/pyproject.toml
--rw-r--r--   0        0        0      759 1970-01-01 00:00:00.000000 citation_utils-0.4.3/PKG-INFO
+-rw-r--r--   0        0        0     1491 2023-06-23 10:27:21.228309 citation_utils-0.4.4/LICENSE
+-rw-r--r--   0        0        0      653 2023-06-25 09:54:14.887730 citation_utils-0.4.4/citation_utils/__init__.py
+-rw-r--r--   0        0        0    17192 2023-06-28 02:19:25.479601 citation_utils-0.4.4/citation_utils/citation.py
+-rw-r--r--   0        0        0     1179 2023-06-25 09:54:14.891749 citation_utils-0.4.4/citation_utils/dockets/__init__.py
+-rw-r--r--   0        0        0     3155 2023-06-25 09:54:14.895013 citation_utils-0.4.4/citation_utils/dockets/constructed_ac.py
+-rw-r--r--   0        0        0     3194 2023-06-25 09:54:14.895319 citation_utils-0.4.4/citation_utils/dockets/constructed_am.py
+-rw-r--r--   0        0        0     2457 2023-06-25 09:54:14.895608 citation_utils-0.4.4/citation_utils/dockets/constructed_bm.py
+-rw-r--r--   0        0        0     2896 2023-06-28 02:09:40.197586 citation_utils-0.4.4/citation_utils/dockets/constructed_gr.py
+-rw-r--r--   0        0        0     2094 2023-06-25 09:54:14.896184 citation_utils-0.4.4/citation_utils/dockets/constructed_jib.py
+-rw-r--r--   0        0        0     2385 2023-06-25 09:54:14.896448 citation_utils-0.4.4/citation_utils/dockets/constructed_oca.py
+-rw-r--r--   0        0        0     1597 2023-06-25 09:54:14.896710 citation_utils-0.4.4/citation_utils/dockets/constructed_pet.py
+-rw-r--r--   0        0        0     1767 2023-06-25 09:54:14.896999 citation_utils-0.4.4/citation_utils/dockets/constructed_udk.py
+-rw-r--r--   0        0        0      364 2023-06-25 10:00:40.543092 citation_utils-0.4.4/citation_utils/dockets/models/__init__.py
+-rw-r--r--   0        0        0     4834 2023-06-25 09:54:14.900031 citation_utils-0.4.4/citation_utils/dockets/models/constructor.py
+-rw-r--r--   0        0        0     1373 2023-06-25 09:54:14.900293 citation_utils-0.4.4/citation_utils/dockets/models/docket_category.py
+-rw-r--r--   0        0        0     1696 2023-06-25 09:54:14.900588 citation_utils-0.4.4/citation_utils/dockets/models/docket_citation.py
+-rw-r--r--   0        0        0     5272 2023-06-26 01:40:40.533138 citation_utils-0.4.4/citation_utils/dockets/models/docket_model.py
+-rw-r--r--   0        0        0     3404 2023-06-28 02:34:55.066065 citation_utils-0.4.4/citation_utils/dockets/models/docket_rules.py
+-rw-r--r--   0        0        0     2911 2023-06-25 09:54:14.901368 citation_utils-0.4.4/citation_utils/dockets/models/gr_clean.py
+-rw-r--r--   0        0        0       81 2023-06-25 09:54:14.902014 citation_utils-0.4.4/citation_utils/dockets/models/misc/__init__.py
+-rw-r--r--   0        0        0      746 2023-06-25 09:54:14.903593 citation_utils-0.4.4/citation_utils/dockets/models/misc/extra.py
+-rw-r--r--   0        0        0     1514 2023-06-25 09:54:14.903861 citation_utils-0.4.4/citation_utils/dockets/models/misc/num.py
+-rw-r--r--   0        0        0      242 2023-06-25 09:54:14.904129 citation_utils-0.4.4/citation_utils/dockets/models/misc/x.py
+-rw-r--r--   0        0        0     5760 2023-06-25 09:54:14.904387 citation_utils-0.4.4/citation_utils/document.py
+-rw-r--r--   0        0        0     2531 2023-06-25 09:54:14.904670 citation_utils-0.4.4/citation_utils/special.py
+-rw-r--r--   0        0        0     1312 2023-06-28 02:18:26.642111 citation_utils-0.4.4/pyproject.toml
+-rw-r--r--   0        0        0      759 1970-01-01 00:00:00.000000 citation_utils-0.4.4/PKG-INFO
```

### Comparing `citation_utils-0.4.3/LICENSE` & `citation_utils-0.4.4/LICENSE`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/__init__.py` & `citation_utils-0.4.4/citation_utils/__init__.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/citation.py` & `citation_utils-0.4.4/citation_utils/citation.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,15 +2,14 @@
 import logging
 from collections.abc import Iterator
 from functools import cached_property
 from typing import Self
 
 from citation_date import DOCKET_DATE_FORMAT
 from citation_report import Report
-from citation_report.main import is_eq
 from dateutil.parser import parse
 from pydantic import BaseModel, ConfigDict, Field, field_serializer, model_serializer
 
 from .dockets import Docket, DocketCategory
 from .document import CitableDocument
 
 
@@ -41,57 +40,66 @@
     GR 138570, Oct. 10, 2000 | `docket` | optional (str) | Combined `docket_category` `docket_serial` `docket_date`
     None | `phil` | optional (str) | combined `volume` Phil. `page`
     342 SCRA 449 | `scra` | optional (str) | combined `volume` SCRA `page`
     None | `offg` | optional (str) | combined `volume` O.G. `page`
     """  # noqa: E501
 
     model_config = ConfigDict(use_enum_values=True, str_strip_whitespace=True)
-    docket_category: DocketCategory | None = Field(default=None)
-    docket_serial: str | None = Field(default=None)
-    docket_date: datetime.date | None = Field(default=None)
+    docket_category: DocketCategory | None = Field(default=None, alias="cat")
+    docket_serial: str | None = Field(default=None, alias="num")
+    docket_date: datetime.date | None = Field(default=None, alias="date")
     phil: str | None = Field(default=None)
     scra: str | None = Field(default=None)
     offg: str | None = Field(default=None)
 
-    @cached_property
-    def bits(self) -> list[str]:
-        _bits = []
-        if docket := self.get_docket_display():
-            _bits.append(docket)
-        if self.phil:
-            _bits.append(self.phil)
-        if self.scra:
-            _bits.append(self.scra)
-        if self.offg:
-            _bits.append(self.offg)
-        return _bits
-
     def __repr__(self) -> str:
         return f"<Citation: {str(self)}>"
 
     def __str__(self) -> str:
-        return ", ".join(self.bits) if self.bits else "Bad citation."
+        docket_str = self.get_docket_display()
+        report_str = self.phil or self.scra or self.offg
+        if docket_str and report_str:
+            return f"{docket_str}, {report_str}"
+        elif docket_str:
+            return f"{docket_str}"
+        elif report_str:
+            return f"{report_str}"
+        return f"<Bad citation str: {self.docket_category=} {self.docket_serial=} {self.docket_date=}>"  # noqa: E501
 
     def __eq__(self, other: Self) -> bool:
-        """Helps `seen` variable in `CountedCitation`."""
-        ok_cat = self.docket_category is not None and other.docket_category is not None
-        ok_serial = self.docket_serial is not None and other.docket_serial is not None
-        ok_date = self.docket_date is not None and other.docket_date is not None
+        """Helps `seen` variable in `CountedCitation`: either the docket bits match
+        or any of the report fields match."""
+
+        def is_docket_match(other: Self) -> bool:
+            """All the docket elements must match to be equal."""
+            cat_is_eq = (
+                self.docket_category is not None
+                and other.docket_category is not None
+                and (self.docket_category == other.docket_category)
+            )
+            num_is_eq = (
+                self.docket_serial is not None
+                and other.docket_serial is not None
+                and (self.docket_serial == other.docket_serial)
+            )
+            date_is_eq = (
+                self.docket_date is not None
+                and other.docket_date is not None
+                and (self.docket_date == other.docket_date)
+            )
+            return all([cat_is_eq, num_is_eq, date_is_eq])
+
+        if is_docket_match(other):
+            return True
+
         return any(
             [
-                is_eq(self.scra, other.scra),
-                is_eq(self.offg, other.offg),
-                is_eq(self.phil, other.phil),
-                all(
-                    [
-                        ok_cat and (self.docket_category == other.docket_category),
-                        ok_serial and (self.docket_serial == other.docket_serial),
-                        ok_date and (self.docket_date == other.docket_date),
-                    ]
-                ),
+                self.scra and other.scra and self.scra.lower() == other.scra.lower(),
+                self.phil and other.phil and self.phil.lower() == other.phil.lower(),
+                self.offg and other.offg and self.offg.lower() == other.offg.lower(),
             ]
         )
 
     @field_serializer("docket_date")
     def serialize_dt(self, dt: datetime.date | None = None):
         if dt:
             return dt.isoformat()
@@ -165,17 +173,17 @@
         num: str,
         date: str,
         opt_phil: str | None,
         opt_scra: str | None,
         opt_offg: str | None,
     ):
         return cls(
-            docket_category=DocketCategory[cat.upper()],
-            docket_serial=num,
-            docket_date=parse(date).date(),
+            cat=DocketCategory[cat.upper()],
+            num=num,
+            date=parse(date).date(),
             phil=cls.get_report(opt_phil),
             scra=cls.get_report(opt_scra),
             offg=cls.get_report(opt_offg),
         )
 
     @cached_property
     def is_docket(self) -> bool:
@@ -234,17 +242,17 @@
             return None
 
     @classmethod
     def _set_docket_report(cls, text: str):
         try:
             obj = next(CitableDocument.get_docketed_reports(text))
             return cls(
-                docket_category=obj.category,
-                docket_serial=obj.serial_text,
-                docket_date=obj.docket_date,
+                cat=obj.category,
+                num=obj.serial_text,
+                date=obj.docket_date,
                 phil=obj.phil,
                 scra=obj.scra,
                 offg=obj.offg,
             )
         except StopIteration:
             logging.debug(f"{text} is not a Docket nor a Report instance.")
             return None
@@ -301,56 +309,43 @@
 
 class CountedCitation(Citation):
     mentions: int = Field(default=1, description="Get count via Citation __eq__")
 
     def __repr__(self) -> str:
         return f"{str(self)}: {self.mentions}"
 
-    def __str__(self) -> str:
-        docket_str = self.get_docket_display()
-        report_str = self.phil or self.scra or self.offg
-        if docket_str and report_str:
-            return f"{docket_str}, {report_str}"
-        elif docket_str:
-            return f"{docket_str}"
-        elif report_str:
-            return f"{report_str}"
-        return "<Bad citation str>"
-
     @classmethod
     def from_source(cls, text: str) -> list[Self]:
         """Computes mentions of `counted_dockets()` vis-a-vis `counted_reports()` and
         count the number of unique items, taking into account the Citation
         structure and the use of __eq__ re: what is considered unique.
 
         Examples:
             >>> source = "374 Phil. 1, 10-11 (1999) 1111 SCRA 1111; G.R. No. 147033, April 30, 2003; G.R. No. 147033, April 30, 2003, 374 Phil. 1, 600; ABC v. XYZ, G.R. Nos. 138570, 138572, 138587, 138680, 138698, October 10, 2000, 342 SCRA 449;  XXX, G.R. No. 31711, Sept. 30, 1971, 35 SCRA 190; Hello World, 1111 SCRA 1111; Y v. Z, 35 SCRA 190; 1 Off. Gaz. 41 Bar Matter No. 803, Jan. 1, 2000 Bar Matter No. 411, Feb. 1, 2000 Bar Matter No. 412, Jan. 1, 2000, 1111 SCRA 1111; 374 Phil. 1"
             >>> len(CountedCitation.from_source(source))
-            6
+            5
 
         Args:
             text (str): Text to Evaluate.
 
         Returns:
             list[Self]: Unique citations with their counts.
         """  # noqa: E501
         all_reports = cls.counted_reports(text)  # includes reports in docket_reports
-        docket_reports = cls.counted_docket_reports(text)
-        for report in all_reports:
-            for dr in docket_reports:
-                if report == dr:  # uses Citation __eq__
-                    balance = 0
-                    if report.mentions > dr.mentions:
-                        balance = report.mentions - dr.mentions
-                    dr.mentions = dr.mentions + balance
-                    report.mentions = 0
-
-        return docket_reports + [
-            report for report in all_reports if report.mentions > 0
-        ]
+        if drs := cls.counted_docket_reports(text):
+            for dr in drs:
+                for report in all_reports:
+                    if report == dr:  # uses Citation __eq__
+                        balance = 0
+                        if report.mentions > dr.mentions:
+                            balance = report.mentions - dr.mentions
+                        dr.mentions = dr.mentions + balance
+                        report.mentions = 0
+            return drs + [report for report in all_reports if report.mentions > 0]
+        return all_reports
 
     @classmethod
     def from_repr_format(cls, repr_texts: list[str]) -> Iterator[Self]:
         """Generate their pydantic counterparts from `<cat> <id>: <mentions>` format.
 
         Examples:
             >>> repr_texts = ['BM No. 412, Jan 01, 2000, 1111 SCRA 1111: 3', 'GR No. 147033, Apr 30, 2003, 374 Phil. 1: 3']
@@ -364,64 +359,70 @@
         Yields:
             Iterator[Self]: Instances of CountedCitation.
         """  # noqa: E501
         for text in repr_texts:
             counted_bits = text.split(":")
             if len(counted_bits) == 2:
                 if cite := cls.extract_citation(counted_bits[0].strip()):
-                    obj = cite.model_dump()
-                    citation = cls(**obj)
+                    citation = CountedCitation(
+                        cat=cite.docket_category,
+                        num=cite.docket_serial,
+                        date=cite.docket_date,
+                        phil=cite.phil,
+                        scra=cite.scra,
+                        offg=cite.offg,
+                    )
                     citation.mentions = int(counted_bits[1].strip())
                     yield citation
 
     @classmethod
     def counted_reports(cls, text: str):
         """Detect _reports_ only from source `text` by first converting
         raw citations into a `Citation` object to take advantage of `__eq__` in
         a `seen` list. This will also populate the the unique records with missing
         values.
         """
         seen: list[cls] = []
         reports = Report.extract_reports(text=text)
         for report in reports:
-            cite = Citation(
-                docket_category=None,
-                docket_serial=None,
-                docket_date=None,
-                phil=report.phil,
-                scra=report.scra,
-                offg=report.offg,
-            )
+            cite = Citation(phil=report.phil, scra=report.scra, offg=report.offg)
             if cite not in seen:
                 seen.append(cls(**cite.model_dump()))
             else:
                 included = seen[seen.index(cite)]
                 included.mentions += 1
         return seen
 
     @classmethod
     def counted_docket_reports(cls, text: str):
         """Detect _dockets with reports_ from source `text` by first converting
         raw citations into a `Citation` object to take advantage of `__eq__` in
-        a `seen` list. This will also populate the the unique records with missing
-        values.
+        a `seen` list. Will populate unique records with missing values.
         """
 
         seen: list[cls] = []
         for obj in CitableDocument.get_docketed_reports(text=text):
             cite = Citation(
-                docket_category=obj.category,
-                docket_serial=obj.serial_text,
-                docket_date=obj.docket_date,
+                cat=obj.category,
+                num=obj.serial_text,
+                date=obj.docket_date,
                 phil=obj.phil,
                 scra=obj.scra,
                 offg=obj.offg,
             )
             if cite not in seen:
-                seen.append(cls(**cite.model_dump()))
+                seen_citation = CountedCitation(
+                    cat=cite.docket_category,
+                    num=cite.docket_serial,
+                    date=cite.docket_date,
+                    phil=cite.phil,
+                    scra=cite.scra,
+                    offg=cite.offg,
+                )
+                seen.append(seen_citation)
             else:
                 included = seen[seen.index(cite)]
                 included.mentions += 1
                 included.add_values(cite)  # for citations, can add missing
         return seen
 
     def add_values(self, other: Citation):
```

### Comparing `citation_utils-0.4.3/citation_utils/dockets/__init__.py` & `citation_utils-0.4.4/citation_utils/dockets/__init__.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_ac.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_ac.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_am.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_am.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_bm.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_bm.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_gr.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_gr.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from collections.abc import Iterator
 from typing import Self
 
 from .models import CitationConstructor, DocketCategory, DocketReportCitation, Num
 
 separator = r"[,\.\s-]*"
-digit = r"\d[\d-]*"  # e.g. 323-23, 343-34
+digit = r"\d[\d-]*"  # e.g. 323-23, 343-34, L
 
 
 gr_key = rf"""
     (
         (
             (?<!CA\s)  # CA GR
             (?<!CA-)  # CA-GR
```

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_jib.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_jib.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_oca.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_oca.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_pet.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_pet.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/constructed_udk.py` & `citation_utils-0.4.4/citation_utils/dockets/constructed_udk.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/models/constructor.py` & `citation_utils-0.4.4/citation_utils/dockets/models/constructor.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/models/docket_category.py` & `citation_utils-0.4.4/citation_utils/dockets/models/docket_category.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/models/docket_citation.py` & `citation_utils-0.4.4/citation_utils/dockets/models/docket_citation.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/models/docket_model.py` & `citation_utils-0.4.4/citation_utils/dockets/models/docket_model.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/models/gr_clean.py` & `citation_utils-0.4.4/citation_utils/dockets/models/gr_clean.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/models/misc/extra.py` & `citation_utils-0.4.4/citation_utils/dockets/models/misc/extra.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/dockets/models/misc/num.py` & `citation_utils-0.4.4/citation_utils/dockets/models/misc/num.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/document.py` & `citation_utils-0.4.4/citation_utils/document.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/citation_utils/special.py` & `citation_utils-0.4.4/citation_utils/special.py`

 * *Files identical despite different names*

### Comparing `citation_utils-0.4.3/pyproject.toml` & `citation_utils-0.4.4/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "citation_utils"
-version = "0.4.3"
+version = "0.4.4"
 description = "Pattern matching Philippine Supreme Court citations."
 authors = ["Marcelino G. Veloso III <contact@mv3.dev>"]
 homepage = "https://lawsql.com"
 repository = "https://github.com/justmars/citation-utils"
 documentation = "https://justmars.github.io/citation-utils"
 classifiers = [
   "Topic :: Text Processing :: General",
```

### Comparing `citation_utils-0.4.3/PKG-INFO` & `citation_utils-0.4.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: citation-utils
-Version: 0.4.3
+Version: 0.4.4
 Summary: Pattern matching Philippine Supreme Court citations.
 Home-page: https://lawsql.com
 Author: Marcelino G. Veloso III
 Author-email: contact@mv3.dev
 Requires-Python: >=3.11,<4.0
 Classifier: Development Status :: 4 - Beta
 Classifier: Framework :: Pydantic
```

