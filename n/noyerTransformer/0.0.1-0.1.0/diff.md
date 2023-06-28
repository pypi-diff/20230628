# Comparing `tmp/noyerTransformer-0.0.1.tar.gz` & `tmp/noyerTransformer-0.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "noyerTransformer-0.0.1.tar", last modified: Wed Jun 28 13:30:40 2023, max compression
+gzip compressed data, was "noyerTransformer-0.1.0.tar", last modified: Wed Jun 28 14:48:05 2023, max compression
```

## Comparing `noyerTransformer-0.0.1.tar` & `noyerTransformer-0.1.0.tar`

### file list

```diff
@@ -1,22 +1,24 @@
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 13:30:40.513291 noyerTransformer-0.0.1/
--rwxrwxrwx   0 root         (0) root         (0)      234 2023-06-28 13:30:40.513118 noyerTransformer-0.0.1/PKG-INFO
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 13:30:40.509617 noyerTransformer-0.0.1/noyerTransformer/
--rwxrwxrwx   0 root         (0) root         (0)     1048 2023-06-26 14:02:27.000000 noyerTransformer-0.0.1/noyerTransformer/CONST.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 13:30:40.512834 noyerTransformer-0.0.1/noyerTransformer/TexSoup/
--rwxrwxrwx   0 root         (0) root         (0)     2369 2023-06-28 13:01:30.000000 noyerTransformer-0.0.1/noyerTransformer/TexSoup/__init__.py
--rwxrwxrwx   0 root         (0) root         (0)     2165 2023-06-28 13:02:03.000000 noyerTransformer-0.0.1/noyerTransformer/TexSoup/category.py
--rwxrwxrwx   0 root         (0) root         (0)    44222 2023-06-28 13:01:59.000000 noyerTransformer-0.0.1/noyerTransformer/TexSoup/data.py
--rwxrwxrwx   0 root         (0) root         (0)    20046 2023-06-28 13:01:56.000000 noyerTransformer-0.0.1/noyerTransformer/TexSoup/reader.py
--rwxrwxrwx   0 root         (0) root         (0)      745 2023-06-28 13:01:45.000000 noyerTransformer-0.0.1/noyerTransformer/TexSoup/tex.py
--rwxrwxrwx   0 root         (0) root         (0)    11724 2023-06-28 13:02:10.000000 noyerTransformer-0.0.1/noyerTransformer/TexSoup/tokens.py
--rwxrwxrwx   0 root         (0) root         (0)    14713 2023-06-24 20:46:07.000000 noyerTransformer-0.0.1/noyerTransformer/TexSoup/utils.py
--rwxrwxrwx   0 root         (0) root         (0)      345 2023-06-28 12:59:38.000000 noyerTransformer-0.0.1/noyerTransformer/__init__.py
--rwxrwxrwx   0 root         (0) root         (0)    14870 2023-06-28 13:25:08.000000 noyerTransformer-0.0.1/noyerTransformer/convertNoyer.py
--rwxrwxrwx   0 root         (0) root         (0)     4967 2023-06-26 14:04:28.000000 noyerTransformer-0.0.1/noyerTransformer/latex2png.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 13:30:40.510640 noyerTransformer-0.0.1/noyerTransformer.egg-info/
--rwxrwxrwx   0 root         (0) root         (0)      234 2023-06-28 13:30:40.000000 noyerTransformer-0.0.1/noyerTransformer.egg-info/PKG-INFO
--rwxrwxrwx   0 root         (0) root         (0)      529 2023-06-28 13:30:40.000000 noyerTransformer-0.0.1/noyerTransformer.egg-info/SOURCES.txt
--rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 13:30:40.000000 noyerTransformer-0.0.1/noyerTransformer.egg-info/dependency_links.txt
--rwxrwxrwx   0 root         (0) root         (0)       17 2023-06-28 13:30:40.000000 noyerTransformer-0.0.1/noyerTransformer.egg-info/top_level.txt
--rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-28 13:30:40.513348 noyerTransformer-0.0.1/setup.cfg
--rwxrwxrwx   0 root         (0) root         (0)      334 2023-06-28 12:57:33.000000 noyerTransformer-0.0.1/setup.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 14:48:05.076949 noyerTransformer-0.1.0/
+-rwxrwxrwx   0 root         (0) root         (0)      234 2023-06-28 14:48:05.076791 noyerTransformer-0.1.0/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)     1485 2023-06-28 14:47:28.000000 noyerTransformer-0.1.0/README.md
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 14:48:05.074098 noyerTransformer-0.1.0/noyerTransformer/
+-rwxrwxrwx   0 root         (0) root         (0)     1048 2023-06-26 14:02:27.000000 noyerTransformer-0.1.0/noyerTransformer/CONST.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 14:48:05.076522 noyerTransformer-0.1.0/noyerTransformer/TexSoup/
+-rwxrwxrwx   0 root         (0) root         (0)     2369 2023-06-28 13:01:30.000000 noyerTransformer-0.1.0/noyerTransformer/TexSoup/__init__.py
+-rwxrwxrwx   0 root         (0) root         (0)     2165 2023-06-28 13:02:03.000000 noyerTransformer-0.1.0/noyerTransformer/TexSoup/category.py
+-rwxrwxrwx   0 root         (0) root         (0)    44222 2023-06-28 13:01:59.000000 noyerTransformer-0.1.0/noyerTransformer/TexSoup/data.py
+-rwxrwxrwx   0 root         (0) root         (0)    20046 2023-06-28 13:01:56.000000 noyerTransformer-0.1.0/noyerTransformer/TexSoup/reader.py
+-rwxrwxrwx   0 root         (0) root         (0)      745 2023-06-28 13:01:45.000000 noyerTransformer-0.1.0/noyerTransformer/TexSoup/tex.py
+-rwxrwxrwx   0 root         (0) root         (0)    11724 2023-06-28 13:02:10.000000 noyerTransformer-0.1.0/noyerTransformer/TexSoup/tokens.py
+-rwxrwxrwx   0 root         (0) root         (0)    14713 2023-06-24 20:46:07.000000 noyerTransformer-0.1.0/noyerTransformer/TexSoup/utils.py
+-rwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 14:10:02.000000 noyerTransformer-0.1.0/noyerTransformer/__init__.py
+-rwxrwxrwx   0 root         (0) root         (0)      391 2023-06-28 14:09:57.000000 noyerTransformer-0.1.0/noyerTransformer/__main__.py
+-rwxrwxrwx   0 root         (0) root         (0)    17873 2023-06-28 14:44:30.000000 noyerTransformer-0.1.0/noyerTransformer/convertNoyer.py
+-rwxrwxrwx   0 root         (0) root         (0)     4967 2023-06-26 14:04:28.000000 noyerTransformer-0.1.0/noyerTransformer/latex2png.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 14:48:05.074924 noyerTransformer-0.1.0/noyerTransformer.egg-info/
+-rwxrwxrwx   0 root         (0) root         (0)      234 2023-06-28 14:48:05.000000 noyerTransformer-0.1.0/noyerTransformer.egg-info/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)      568 2023-06-28 14:48:05.000000 noyerTransformer-0.1.0/noyerTransformer.egg-info/SOURCES.txt
+-rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 14:48:05.000000 noyerTransformer-0.1.0/noyerTransformer.egg-info/dependency_links.txt
+-rwxrwxrwx   0 root         (0) root         (0)       17 2023-06-28 14:48:05.000000 noyerTransformer-0.1.0/noyerTransformer.egg-info/top_level.txt
+-rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-28 14:48:05.077001 noyerTransformer-0.1.0/setup.cfg
+-rwxrwxrwx   0 root         (0) root         (0)      334 2023-06-28 14:47:54.000000 noyerTransformer-0.1.0/setup.py
```

### Comparing `noyerTransformer-0.0.1/noyerTransformer/CONST.py` & `noyerTransformer-0.1.0/noyerTransformer/CONST.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/TexSoup/__init__.py` & `noyerTransformer-0.1.0/noyerTransformer/TexSoup/__init__.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/TexSoup/category.py` & `noyerTransformer-0.1.0/noyerTransformer/TexSoup/category.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/TexSoup/data.py` & `noyerTransformer-0.1.0/noyerTransformer/TexSoup/data.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/TexSoup/reader.py` & `noyerTransformer-0.1.0/noyerTransformer/TexSoup/reader.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/TexSoup/tex.py` & `noyerTransformer-0.1.0/noyerTransformer/TexSoup/tex.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/TexSoup/tokens.py` & `noyerTransformer-0.1.0/noyerTransformer/TexSoup/tokens.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/TexSoup/utils.py` & `noyerTransformer-0.1.0/noyerTransformer/TexSoup/utils.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer/convertNoyer.py` & `noyerTransformer-0.1.0/noyerTransformer/convertNoyer.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,433 +1,461 @@
 #!/usr/bin/env python3
 '''
  Name : Elowan
  Creation : 24-06-2023 20:53:52
- Last modified : 28-06-2023 15:00:51
+ Last modified : 28-06-2023 16:44:30
 '''
 from .TexSoup import TexSoup, utils, data
 import re
 import os
 
 from .CONST import disponible_environments, skip_envs
 from .latex2png import pnglatex
 
 # Soup = l'intérieur d'une balise
 
-def frameAnalyse(soup):
+class Converter:
     """
-    Analyse le contenu d'un frame et le transforme en markdown
-
-    (Prend en compte les frames fragiles et les titres pas dans des 
-    frametitle)
-
-    :param soup: le contenu du frame
-    :type soup: TexSoup.TexNode
-    :return: le contenu du frame en markdown
+    Classe de conversion d'un fichier latex en markdown
     """
-    # Si la frame est sans paramètres
-    if len(soup.args) == 0:
-        return transformSoupToMarkdown(list(soup.contents))
-    
-    # Si la frame est fragile
-    if soup.args[0] == '[fragile]':
-        string = ''
-
-        # Si la frame a un titre
-        if len(soup.args) >= 2:
-            string += "\n#### " + removeWeirdSpacing(str(soup.args[1])) \
-                    .replace('{', '').replace('}', '') + "\n\n"
-            return string + transformSoupToMarkdown(list(soup.contents)[2:])
+
+    def __init__(self, filename):
+        """
+        Initialise le convertisseur
+
+        :param filename: le nom du fichier à convertir
+        :type filename: str
+        """
+        self.filename = filename.split("/")[-1]
+        self.sourcedir = "/".join(filename.split("/")[:-1]) + "/"
+        self.workingdir = os.getcwd() + "/"
+        self.imgdir = self.workingdir + "images/{}/".format(
+            filename.split("/")[-1].split('.')[0].replace(' ', '_'))
+        self.stringSoup = ""
+        self.packages = []
+
+    def frameAnalyse(self, soup):
+        """
+        Analyse le contenu d'un frame et le transforme en markdown
+
+        (Prend en compte les frames fragiles et les titres pas dans des 
+        frametitle)
+
+        :param soup: le contenu du frame
+        :type soup: TexSoup.TexNode
+        :return: le contenu du frame en markdown
+        """
+        # Si la frame est sans paramètres
+        if len(soup.args) == 0:
+            return self.transformSoupToMarkdown(list(soup.contents))
         
+        # Si la frame est fragile
+        if soup.args[0] == '[fragile]':
+            string = ''
+
+            # Si la frame a un titre
+            if len(soup.args) >= 2:
+                string += "\n#### " + Converter.removeWeirdSpacing(str(soup.args[1])) \
+                        .replace('{', '').replace('}', '') + "\n\n"
+                return string + self.transformSoupToMarkdown(list(soup.contents)[2:])
+            
+            else:
+                return "\n" + self.transformSoupToMarkdown(list(soup.contents)[1:])
         else:
-            return "\n" + transformSoupToMarkdown(list(soup.contents)[1:])
-    else:
-        # Si la frame a un titre mais pas de mention fragile
-        string = "\n#### " + removeWeirdSpacing(str(soup.args[0])).replace('{', '').replace('}', '') + "\n\n"
-        return string + transformSoupToMarkdown(list(soup.contents)[1:])
-    
-def getEnvironment(string):
-    """
-    Récupère le contenu d'un environnement dans un string
-
-    Trouve le premier '{' et renvoie tout ce qu'il y a dedans 
-
-    :param string: le string à analyser
-    :type string: str
-    :return: le contenu de l'environnement
-    """
-    count = None
-    ignoreLine = False
-    for i in range(len(string)):
-        if ignoreLine:
-            continue
-
-        if string[i] == '%':
-            ignoreLine = True
-            continue
-
-        if string[i] == '{':
-            if count == None: count = 0
-            count += 1
-        elif string[i] == '}':
-            count -= 1
-        if count == 0:
-            return string[string.find('{')+1:i]
-
-def getWeirdEnvironment(string):
-    """
-    Récupère le contenu d'une commande de la forme "\env ... {}" 
-    dans un string avec ... les options de la commande
-
-    :param string: le string à analyser
-    :type string: str
-    :return: (
-        la commande, 
-        le contenu de l'environnement, 
-        la commande complète
-    )
-    """
-    command = ""
-
-    # Récupère la commande latex
-    for i in range(len(string)):
-        if string[i] == '\\':
-            command += string[i:string.find('{')]
-            break
-
-    # Récupère le contenu de l'environnement
-    envContent = getEnvironment(string[len(command):])
-    
-    return string[string.find('\\'):len(command)+len(envContent)+3]
-
-def renderImage(name, string):
-    """
-    Rend une image latex en png
-
-    :param name: le nom de l'image
-    :type name: str
-    :param string: le contenu de l'image
-    :type string: str
-    :return: le nom de l'image
-    :rtype: str
-    """
-    print("/!\ Commande impossible à parser : {}".format(
-                removeWeirdSpacing(string)))
-    print("Conversion en image...\n")
-    
-    imageNumber = len([name for name in os.listdir(DIR) if os.path.isfile(os.path.join(DIR, name))])
-
-    # Convertit le latex en image
-    try:
-        filename = "{}_{}.png".format(name, imageNumber)
-        pnglatex(string, DIR + "{}".format(filename), packages=packages)
-
-    except ValueError:
-        print("/!\ Erreur lors de la conversion en image\n")
-        return "\n!!!danger \"Erreur de convertion : {}\"\n".format(
-                removeWeirdSpacing(filename))
-    
-
-    else:
-        print("Conversion en image réussie\n")
-        return "\n\n![{}]({})\n\n".format(name, DIR + "{}".format(filename))
-
-# Fonctions de transformation de balise en markdown
-functions_for_envs = {
-    # MetaBalises
-    "input": lambda x, indent: "\n\n!!!danger \"Include\"\n", # TODO: include the file
-    "frame": lambda x, indent: frameAnalyse(x),
-    "title": lambda x, indent: "# " + removeWeirdSpacing(str(x.string)) + "\n\n",
-    "section": lambda x, indent: "\n## " + removeWeirdSpacing(str(x.string)) + "\n\n",
-    "subsection": lambda x, indent: "\n### " + removeWeirdSpacing(str(x.string)) + "\n\n",
-    "frametitle": lambda x, indent: "\n\n#### " + removeWeirdSpacing(str(x.string)) + "\n\n",
-    "framesubtitle": lambda x, indent: "\n##### " + removeWeirdSpacing(str(x.string)) + "\n\n",
-
-    
-    # Blocs à part entière
-    "label": lambda x, indent: "", # On dégage les labels
-    "tiny": lambda x, indent: str(transformSoupToMarkdown(list(x.contents))),
-    "small": lambda x, indent: str(transformSoupToMarkdown(list(x.contents))),
-    "ref": lambda x, indent: "[" + removeWeirdSpacing(str(x.string)) + "](#"
-                            + str(x.string) + ")",
-    "tabular": lambda x, indent: renderImage(str(x.name), str(x)),
-
-    "figure": lambda x, indent: "\n" + renderImage(x.name, str(x)),
-    
-    "itemize": lambda x, indent: "\n\n" + "\n".join([indent + "- " + str(
-                                    transformSoupToMarkdown(list(elmt))
-                                    ).rstrip().lstrip() 
-                                    for elmt in list(x.children)]) + "\n\n",
-
-    "enumerate": lambda x, indent: "\n\n" + "\n".join([indent + "1. " + str(
-                                    transformSoupToMarkdown(list(elmt), indent)
-                                    ).rstrip().lstrip()
-                                    for elmt in list(x.children)]) + "\n\n",
-
-    "lstlisting": lambda x, indent: "\n```{} linenums=\"1\"\n".format(str(x.contents[0])
-                                    .replace("style=", "")) + 
-                                    str(x.contents[1]).replace('    ', ' ') + 
-                                    "\n```\n",
-
-    "columns": lambda x, indent: str(transformSoupToMarkdown(list(x.contents[2:]), indent)),
-    "column": lambda x, indent: str(transformSoupToMarkdown(list(x.contents[1:]), indent)),
-
-    "defn": lambda x, indent: '\n\n!!!quote "Définition"\n' + "     " + 
-                                    str(transformSoupToMarkdown(list(x.contents), 
-                                    indent + "     ")) + "\n\n",
-
-    "rem": lambda x, indent: '\n\n!!!tip ""\n    **Remarque**\n\n' + "     " +
-                                    str(transformSoupToMarkdown(list(x.contents), 
-                                    indent + "     ")) + "\n\n",
-
-    "prop": lambda x, indent: '\n\n!!!warning ""\n    **Propriété**\n\n' + "     " +
-                                    str(transformSoupToMarkdown(list(x.contents), 
-                                    indent + "     ")) + "\n\n",
-    "block": lambda x, indent: "\n\n" + str(transformSoupToMarkdown(list(x.contents),
-                                    indent)) + "\n\n",
-    "cod": lambda x, indent: "\n`" + str(transformSoupToMarkdown(list(x.contents),
-                                    indent)) + "`\n",
-    
-
-    # Inline elements
-    "href": lambda x, indent: "[" + removeWeirdSpacing(str(x.args[1].string)) + 
-                                    "](" + str(x.args[0].string) + ")",
-
-    "emph": lambda x, indent: " *" + str(transformSoupToMarkdown(list(x.contents)
-                                    )) + "*",
-    "enquote": lambda x, indent: "\"" + str(transformSoupToMarkdown(list(x.contents)
-                                    )) + "\"",
-    "textcolor": lambda x, indent: "<span style='color:{}'>".format(
-                                    str(x.args[0].string)
-                                    ) + str(transformSoupToMarkdown(
-                                        list(x.contents[1:]))
-                                    ) + "</span>",
-
-    "displaymath": lambda x, indent: "\n\n$$\n" + " ".join(
-                                    [ str(x).rstrip().lstrip() for x in x.contents]
-                                    ) + "$$\n\n",
-    "BraceGroup": lambda x, indent: str(transformSoupToMarkdown(
-                                    list(x.contents), indent)),
-
-    # "alert": lambda x, indent: str(transformSoupToMarkdown(
-    #                                 list(TexSoup(getEnvironment(stringSoup[x.position:]), 
-    #                                 skip_envs=skip_envs)), indent)),
-
-    "textbf": lambda x, indent: "**" + str(transformSoupToMarkdown(
-                                    list(x.contents))
-                                    ) + "**",
-    
-    "gbox": lambda x, indent: " `" + str(transformSoupToMarkdown(
-                                    list(x.contents))
-                                    ) + "`",
-    "textwidth": lambda x, indent: str(transformSoupToMarkdown(
-                                    list(x.contents))
-                                    ),
-
-    # Abréviations (TODO: à vérifier)
-    "node": lambda x, indent: "noeud",
-    "ie": lambda x, indent: "ie",
-    "ssi": lambda x, indent: "si et seulement si",
-    "": lambda x, indent: transformSoupToMarkdown(list(x.contents), indent),
-}
-
-
-def transformSoupToMarkdown(soupList, indent=""):
-    """
-    Transforme une liste de soup en markdown, si un % est placé au début de la ligne,
-    alors la ligne n'est pas gardée. La fonction est récursive.
-
-    :param list: une liste de soup
-    :type list: List
-
-    :return: string
-    """
-    resultString = ''
-    toSkip = -1
-
-    # Parcours de la liste de soup
-    for i in range(len(soupList)):
-        soup = soupList[i]
-
-        if soup.position < toSkip:
-            continue
-
-        # Si c'est un commentaire, on passe à la ligne suivante
-        if str(soup).startswith('%'):
-            continue
-
-        # Si c'est un simple texte ou des maths, on le retourne
-        if type(soup) == utils.Token or soup.name == "$":
-            resultString += ' ' + removeWeirdSpacing(str(soup))
-
-            if type(soup) != data.TexNode:
-                resultString = resultString.rstrip().lstrip()
-                
-            continue
-
-        # Si on a prévu une fonction pour cette balise, on l'applique
-        if soup.name in functions_for_envs:
-            resultString += str(functions_for_envs[soup.name](soup, indent))
-            continue
+            # Si la frame a un titre mais pas de mention fragile
+            string = "\n#### " + Converter.removeWeirdSpacing(str(soup.args[0])).replace('{', '').replace('}', '') + "\n\n"
+            return string + self.transformSoupToMarkdown(list(soup.contents)[1:])
         
-        # Si la balise n'est pas prise en charge par le script
-        # qui se chargera de l'afficher sur le site, on affiche un warning
-        if soup.name not in disponible_environments:
-            string = getWeirdEnvironment(stringSoup[soup.position-1:])
+    @staticmethod
+    def getEnvironment(string):
+        """
+        Récupère le contenu d'un environnement dans un string
+
+        Trouve le premier '{' et renvoie tout ce qu'il y a dedans 
+
+        :param string: le string à analyser
+        :type string: str
+        :return: le contenu de l'environnement
+        """
+        count = None
+        ignoreLine = False
+        for i in range(len(string)):
+            if ignoreLine:
+                continue
+
+            if string[i] == '%':
+                ignoreLine = True
+                continue
+
+            if string[i] == '{':
+                if count == None: count = 0
+                count += 1
+            elif string[i] == '}':
+                count -= 1
+            if count == 0:
+                return string[string.find('{')+1:i]
+
+    @staticmethod
+    def getWeirdEnvironment(string):
+        """
+        Récupère le contenu d'une commande de la forme "\env ... {}" 
+        dans un string avec ... les options de la commande
+
+        :param string: le string à analyser
+        :type string: str
+        :return: (
+            la commande, 
+            le contenu de l'environnement, 
+            la commande complète
+        )
+        """
+        command = ""
+
+        # Récupère la commande latex
+        for i in range(len(string)):
+            if string[i] == '\\':
+                command += string[i:string.find('{')]
+                break
 
-            # Transforme la balise en image             
-            string = renderImage(soup.name, string)
-
-            toSkip = soup.position + len(string) + 1
-            
-            resultString += string
+        # Récupère le contenu de l'environnement
+        envContent = Converter.getEnvironment(string[len(command):])
+        
+        return string[string.find('\\'):len(command)+len(envContent)+3]
 
-            # resultString += "\n\n$$\n" + removeWeirdSpacing(str(soup)).rstrip().lstrip() + "\n$$\n\n"
-            continue
+    def renderImage(self, name, string):
+        """
+        Rend une image latex en png
+
+        :param name: le nom de l'image
+        :type name: str
+        :param string: le contenu de l'image
+        :type string: str
+        :return: le nom de l'image
+        :rtype: str
+        """
+        print("/!\ Commande impossible à parser : {}".format(
+                    Converter.removeWeirdSpacing(string)))
+        print("Conversion en image...\n")
+        
+        imageNumber = len([name for name in os.listdir(self.imgdir) if os.path.isfile(os.path.join(self.imgdir, name))])
 
-        # Sinon on applique la fonction sur tous les enfants de la balise
-        resultString += transformSoupToMarkdown(list(soup.contents), indent)
+        # Convertit le latex en image
+        try:
+            filename = "{}_{}.png".format(name, imageNumber)
+            pnglatex(string, self.imgdir + "{}".format(filename), packages=self.packages)
 
-        resultString += "\n"
+        except ValueError:
+            print("/!\ Erreur lors de la conversion en image\n")
+            return "\n!!!danger \"Erreur de convertion : {}\"\n".format(
+                    Converter.removeWeirdSpacing(filename))
         
-    return resultString
-
-def removeWeirdSpacing(string):
-    """
-    Enlève les espaces/saut à la ligne en trop dans une string
 
-    :param string: la string à modifier
-    :type string: string
+        else:
+            print("Conversion en image réussie\n")
+            return "\n\n![{}]({})\n\n".format(name, self.imgdir + "{}".format(filename))
 
-    :return: string
-    """
-    # On enlève les sauts à la ligne, les espaces et les % en trop
-    reg1 = re.compile(r'\s+')
-    reg2 = re.compile(r'[\n\r%]')
-    string = re.sub(reg1, ' ', string)
-    return re.sub(reg2, '', string)
+    # Fonctions de transformation de balise en markdown
+    def get_functions_for_envs(self, fun):
+        functions_for_envs = {
+            # MetaBalises
+            "input": lambda x, indent: "\n\n!!!danger \"Include\"\n", # TODO: include the file
+            "frame": lambda x, indent: self.frameAnalyse(x),
+            "title": lambda x, indent: "# " + Converter.removeWeirdSpacing(str(x.string)) + "\n\n",
+            "section": lambda x, indent: "\n## " + Converter.removeWeirdSpacing(str(x.string)) + "\n\n",
+            "subsection": lambda x, indent: "\n### " + Converter.removeWeirdSpacing(str(x.string)) + "\n\n",
+            "frametitle": lambda x, indent: "\n\n#### " + Converter.removeWeirdSpacing(str(x.string)) + "\n\n",
+            "framesubtitle": lambda x, indent: "\n##### " + Converter.removeWeirdSpacing(str(x.string)) + "\n\n",
 
-def includeFiles(soup):
-    """
-    Include les fichiers .tex dans le fichier principal
+            
+            # Blocs à part entière
+            "label": lambda x, indent: "", # On dégage les labels
+            "tiny": lambda x, indent: str(self.transformSoupToMarkdown(list(x.contents))),
+            "small": lambda x, indent: str(self.transformSoupToMarkdown(list(x.contents))),
+            "ref": lambda x, indent: "[" + Converter.removeWeirdSpacing(str(x.string)) + "](#"
+                                    + str(x.string) + ")",
+            "tabular": lambda x, indent: self.renderImage(str(x.name), str(x)),
 
-    :param soup: le fichier principal
-    :type soup: TexSoup
+            "figure": lambda x, indent: "\n" + self.renderImage(x.name, str(x)),
+            
+            "itemize": lambda x, indent: "\n\n" + "\n".join([indent + "- " + str(
+                                            self.transformSoupToMarkdown(list(elmt))
+                                            ).rstrip().lstrip() 
+                                            for elmt in list(x.children)]) + "\n\n",
+
+            "enumerate": lambda x, indent: "\n\n" + "\n".join([indent + "1. " + str(
+                                            self.transformSoupToMarkdown(list(elmt), indent)
+                                            ).rstrip().lstrip()
+                                            for elmt in list(x.children)]) + "\n\n",
+
+            "lstlisting": lambda x, indent: "\n```{} linenums=\"1\"\n".format(str(x.contents[0])
+                                            .replace("style=", "")) + 
+                                            str(x.contents[1]).replace('    ', ' ') + 
+                                            "\n```\n",
+
+            "columns": lambda x, indent: str(self.transformSoupToMarkdown(list(x.contents[2:]), indent)),
+            "column": lambda x, indent: str(self.transformSoupToMarkdown(list(x.contents[1:]), indent)),
+
+            "defn": lambda x, indent: '\n\n!!!quote "Définition"\n' + "     " + 
+                                            str(self.transformSoupToMarkdown(list(x.contents), 
+                                            indent + "     ")) + "\n\n",
+
+            "rem": lambda x, indent: '\n\n!!!tip ""\n    **Remarque**\n\n' + "     " +
+                                            str(self.transformSoupToMarkdown(list(x.contents), 
+                                            indent + "     ")) + "\n\n",
+
+            "prop": lambda x, indent: '\n\n!!!warning ""\n    **Propriété**\n\n' + "     " +
+                                            str(self.transformSoupToMarkdown(list(x.contents), 
+                                            indent + "     ")) + "\n\n",
+            "block": lambda x, indent: "\n\n" + str(self.transformSoupToMarkdown(list(x.contents),
+                                            indent)) + "\n\n",
+            "cod": lambda x, indent: "\n`" + str(self.transformSoupToMarkdown(list(x.contents),
+                                            indent)) + "`\n",
+            
 
-    :return: string
-    """
-    # Récupère les fichiers à inclure
-    inputs = soup.find_all('input')
-    for input_soup in inputs:
-        # Ouvre le fichier
-        try:
-            with open(str(input_soup.args[0].string), 'r') as f:
-                stringSoup = f.read()
+            # Inline elements
+            "href": lambda x, indent: "[" + Converter.removeWeirdSpacing(str(x.args[1].string)) + 
+                                            "](" + str(x.args[0].string) + ")",
+
+            "emph": lambda x, indent: " *" + str(self.transformSoupToMarkdown(list(x.contents)
+                                            )) + "*",
+            "enquote": lambda x, indent: "\"" + str(self.transformSoupToMarkdown(list(x.contents)
+                                            )) + "\"",
+            "textcolor": lambda x, indent: "<span style='color:{}'>".format(
+                                            str(x.args[0].string)
+                                            ) + str(self.transformSoupToMarkdown(
+                                                list(x.contents[1:]))
+                                            ) + "</span>",
+
+            "displaymath": lambda x, indent: "\n\n$$\n" + " ".join(
+                                            [ str(x).rstrip().lstrip() for x in x.contents]
+                                            ) + "$$\n\n",
+            "BraceGroup": lambda x, indent: str(self.transformSoupToMarkdown(
+                                            list(x.contents), indent)),
+
+            # "alert": lambda x, indent: str(self.transformSoupToMarkdown(
+            #                                 list(TexSoup(getEnvironment(self.stringSoup[x.position:]), 
+            #                                 skip_envs=skip_envs)), indent)),
+
+            "textbf": lambda x, indent: "**" + str(self.transformSoupToMarkdown(
+                                            list(x.contents))
+                                            ) + "**",
+            
+            "gbox": lambda x, indent: " `" + str(self.transformSoupToMarkdown(
+                                            list(x.contents))
+                                            ) + "`",
+            "textwidth": lambda x, indent: str(self.transformSoupToMarkdown(
+                                            list(x.contents))
+                                            ),
+
+            # Abréviations (TODO: à vérifier)
+            "node": lambda x, indent: "noeud",
+            "ie": lambda x, indent: "ie",
+            "ssi": lambda x, indent: "si et seulement si",
+            "": lambda x, indent: self.transformSoupToMarkdown(list(x.contents), indent),
+        }
 
-            # Ajoute le contenu du fichier au fichier principal
-            input_soup.replace_with(TexSoup(stringSoup, skip_envs=skip_envs))
+        if fun in functions_for_envs:
+            return functions_for_envs[fun]
         
-        except FileNotFoundError:
-            print("/!\ Impossible d'importer le fichier " + 
-                  str(input_soup.args[0].string))
+        else:
+            return None
+
+    def transformSoupToMarkdown(self, soupList, indent=""):
+        """
+        Transforme une liste de soup en markdown, si un % est placé au début de la ligne,
+        alors la ligne n'est pas gardée. La fonction est récursive.
+
+        :param list: une liste de soup
+        :type list: List
+
+        :return: string
+        """
+        resultString = ''
+        toSkip = -1
+
+        # Parcours de la liste de soup
+        for i in range(len(soupList)):
+            soup = soupList[i]
+
+            if soup.position < toSkip:
+                continue
+
+            # Si c'est un commentaire, on passe à la ligne suivante
+            if str(soup).startswith('%'):
+                continue
+
+            # Si c'est un simple texte ou des maths, on le retourne
+            if type(soup) == utils.Token or soup.name == "$":
+                resultString += ' ' + Converter.removeWeirdSpacing(str(soup))
+
+                if type(soup) != data.TexNode:
+                    resultString = resultString.rstrip().lstrip()
+                    
+                continue
+
+            # Si on a prévu une fonction pour cette balise, on l'applique
+            func = self.get_functions_for_envs(soup.name)
+            if func is not None:
+                resultString += str(func(soup, indent))
+                continue
             
-    return TexSoup(str(soup), skip_envs=skip_envs)
+            # Si la balise n'est pas prise en charge par le script
+            # qui se chargera de l'afficher sur le site, on affiche un warning
+            if soup.name not in disponible_environments:
+                string = Converter.getWeirdEnvironment(self.stringSoup[soup.position-1:])
 
-def getAllImportedPackages(soup):
-    """
-    Récupère tous les packages importés dans le fichier
+                # Transforme la balise en image             
+                string = self.renderImage(soup.name, string)
 
-    :param soup: le fichier principal
-    :type soup: TexSoup
+                toSkip = soup.position + len(string) + 1
+                
+                resultString += string
 
-    :return: List
-    """
-    packages = []
-    for package in soup.find_all('usepackage'):
-        packages.append(str(package))
-    return packages
+                # resultString += "\n\n$$\n" + Converter.removeWeirdSpacing(str(soup)).rstrip().lstrip() + "\n$$\n\n"
+                continue
 
-def removeComments(soup):
-    """
-    Enlève les commentaires du fichier
+            # Sinon on applique la fonction sur tous les enfants de la balise
+            resultString += self.transformSoupToMarkdown(list(soup.contents), indent)
 
-    :param soup: le fichier principal
-    :type soup: TexSoup
+            resultString += "\n"
+            
+        return resultString
 
-    :return: string
-    """
-    # Récupère tous les commentaires
-    ignoreLine = False
-    soupstr = str(soup)
-    outstring = ""
-    for i in range(len(soupstr)):
-        if soupstr[i] == '%':
-            ignoreLine = True
-            continue
+    @staticmethod
+    def removeWeirdSpacing(string):
+        """
+        Enlève les espaces/saut à la ligne en trop dans une string
+
+        :param string: la string à modifier
+        :type string: string
+
+        :return: string
+        """
+        # On enlève les sauts à la ligne, les espaces et les % en trop
+        reg1 = re.compile(r'\s+')
+        reg2 = re.compile(r'[\n\r%]')
+        string = re.sub(reg1, ' ', string)
+        return re.sub(reg2, '', string)
+
+    def includeFiles(self, soup):
+        """
+        Include les fichiers .tex dans le fichier principal
+
+        :param soup: le fichier principal
+        :type soup: TexSoup
+
+        :return: string
+        """
+        # Récupère les fichiers à inclure
+        inputs = soup.find_all('input')
+        for input_soup in inputs:
+            # Ouvre le fichier
+            try:
+                with open(self.sourcedir + str(input_soup.args[0].string), 'r') as f:
+                    stringSoup = f.read()
 
-        if soupstr[i] == '\n':
-            ignoreLine = False
+                # Ajoute le contenu du fichier au fichier principal
+                input_soup.replace_with(TexSoup(stringSoup, skip_envs=skip_envs))
             
-        if not ignoreLine:
-            outstring += soupstr[i]
+            except FileNotFoundError:
+                print("/!\ Impossible d'importer le fichier " + 
+                    str(input_soup.args[0].string))
+                
+        return TexSoup(str(soup), skip_envs=skip_envs)
 
-    return TexSoup(outstring)
+    @staticmethod
+    def getAllImportedPackages(soup):
+        """
+        Récupère tous les packages importés dans le fichier
+
+        :param soup: le fichier principal
+        :type soup: TexSoup
+
+        :return: List
+        """
+        packages = []
+        for package in soup.find_all('usepackage'):
+            packages.append(str(package))
+        return packages
+
+    @staticmethod
+    def removeComments(soup):
+        """
+        Enlève les commentaires du fichier
+
+        :param soup: le fichier principal
+        :type soup: TexSoup
+
+        :return: string
+        """
+        # Récupère tous les commentaires
+        ignoreLine = False
+        soupstr = str(soup)
+        outstring = ""
+        for i in range(len(soupstr)):
+            if soupstr[i] == '%':
+                ignoreLine = True
+                continue
 
-def removeOldImages():
-    """
-    Supprime les images précédentes
-    """
-    if os.path.exists(DIR):
-        for file in os.listdir(DIR):
-            os.remove(DIR + file)
+            if soupstr[i] == '\n':
+                ignoreLine = False
+                
+            if not ignoreLine:
+                outstring += soupstr[i]
 
-def run(filename):
-    """
-    Fonction principale du script, transforme un fichier .tex en markdown
-    
-    :param filename: le nom du fichier à transformer
-    :type filename: string
-    """
-    global stringSoup
-    global packages 
+        return TexSoup(outstring)
 
-    # Ouverture du fichier
-    with open(filename, 'r') as f:
-        stringSoup = f.read()
-        
-    soup = TexSoup(stringSoup, skip_envs=skip_envs)
-    soup = includeFiles(soup)
-    soup = removeComments(soup)
+    @staticmethod
+    def removeOldImages(imgdir):
+        """
+        Supprime les images précédentes
+        """
+        if os.path.exists(imgdir):
+            for file in os.listdir(imgdir):
+                os.remove(imgdir + file)
+
+    def run(self):
+        """
+        Fonction principale du script, transforme un fichier .tex en markdown
+        """
+        # Ouverture du fichier
+        with open(self.sourcedir + self.filename, 'r') as f:
+            stringSoup = f.read()
+            
+        soup = TexSoup(stringSoup, skip_envs=skip_envs)
+        soup = self.includeFiles(soup)
+        soup = Converter.removeComments(soup)
 
-    stringSoup = str(soup)
+        # Récupération des informations importantes
+        self.stringSoup = str(soup)
+        self.packages = Converter.getAllImportedPackages(soup)
 
-    # Supprime les images précédentes
-    removeOldImages()
-    os.makedirs(DIR, exist_ok=True)
+        # Supprime les images précédentes
+        Converter.removeOldImages(self.imgdir)
+        os.makedirs(self.imgdir, exist_ok=True)
 
-    # Récupère tous les packages importés
-    packages = getAllImportedPackages(soup)
+        # Récupération de la partie importante du fichier
+        document = soup.find('document')
+        documentList = list(document.contents)
 
-    # Récupération de la partie importante du fichier
-    document = soup.find('document')
-    documentList = list(document.contents)
+        # Transformation en markdown
+        outputString = ""
 
-    # Transformation en markdown
-    outputString = ""
+        # Ajout du titre, author et date
+        outputString += "# " + Converter.removeWeirdSpacing(str(soup.find("title").string)) + "\n\n"
+        outputString += "## " + Converter.removeWeirdSpacing(str(soup.find("author").string)) + "\n\n"
 
-    # Ajout du titre, author et date
-    outputString += "# " + removeWeirdSpacing(str(soup.find("title").string)) + "\n\n"
-    outputString += "## " + removeWeirdSpacing(str(soup.find("author").string)) + "\n\n"
+        outputString += self.transformSoupToMarkdown(documentList)
 
-    outputString += transformSoupToMarkdown(documentList)
+        # Supprime les faux espaces utilisés pour l'indentation
+        outputString = outputString.replace(' ', '')
 
-    # Supprime les faux espaces utilisés pour l'indentation
-    outputString = outputString.replace(' ', '')
+        # Ecriture dans le fichier
+        with open(self.workingdir + self.filename +'.md', 'w') as f:
+            f.write(outputString)
 
-    # Ecriture dans le fichier
-    with open(filename+'.md', 'w') as f:
-        f.write(outputString)
+        print("Conversion terminée !")
         
 if __name__ == '__main__':
     filename = "graphes (copia).tex"
-    DIR = 'images/{}/'.format((filename).replace(' ', '_'))
-    run(filename)
+    converter = Converter(filename)
+    converter.run()
```

### Comparing `noyerTransformer-0.0.1/noyerTransformer/latex2png.py` & `noyerTransformer-0.1.0/noyerTransformer/latex2png.py`

 * *Files identical despite different names*

### Comparing `noyerTransformer-0.0.1/noyerTransformer.egg-info/SOURCES.txt` & `noyerTransformer-0.1.0/noyerTransformer.egg-info/SOURCES.txt`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,12 @@
+README.md
 setup.py
 noyerTransformer/CONST.py
 noyerTransformer/__init__.py
+noyerTransformer/__main__.py
 noyerTransformer/convertNoyer.py
 noyerTransformer/latex2png.py
 noyerTransformer.egg-info/PKG-INFO
 noyerTransformer.egg-info/SOURCES.txt
 noyerTransformer.egg-info/dependency_links.txt
 noyerTransformer.egg-info/top_level.txt
 noyerTransformer/TexSoup/__init__.py
```

