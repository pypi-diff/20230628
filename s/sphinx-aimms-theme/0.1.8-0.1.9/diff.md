# Comparing `tmp/sphinx_aimms_theme-0.1.8.tar.gz` & `tmp/sphinx_aimms_theme-0.1.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\sphinx_aimms_theme-0.1.8.tar", last modified: Tue Jan  7 15:54:55 2020, max compression
+gzip compressed data, was "dist\sphinx_aimms_theme-0.1.9.tar", last modified: Thu Jan  9 13:02:35 2020, max compression
```

## Comparing `sphinx_aimms_theme-0.1.8.tar` & `sphinx_aimms_theme-0.1.9.tar`

### file list

```diff
@@ -1,165 +1,165 @@
-drwxrwxrwx   0        0        0        0 2020-01-07 15:54:55.000000 sphinx_aimms_theme-0.1.8/
--rw-rw-rw-   0        0        0     1078 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/LICENSE
--rw-rw-rw-   0        0        0      280 2019-12-23 20:42:53.000000 sphinx_aimms_theme-0.1.8/MANIFEST.in
--rw-rw-rw-   0        0        0      344 2020-01-07 15:54:55.000000 sphinx_aimms_theme-0.1.8/PKG-INFO
--rw-rw-rw-   0        0        0     4732 2019-12-16 21:47:19.000000 sphinx_aimms_theme-0.1.8/README.md
--rw-rw-rw-   0        0        0       86 2020-01-07 15:54:55.000000 sphinx_aimms_theme-0.1.8/setup.cfg
--rw-rw-rw-   0        0        0      926 2020-01-07 15:54:40.000000 sphinx_aimms_theme-0.1.8/setup.py
-drwxrwxrwx   0        0        0        0 2020-01-07 15:54:54.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/
--rw-rw-rw-   0        0        0    23132 2019-12-06 11:49:40.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/AIMMSDomain.py
--rw-rw-rw-   0        0        0    33851 2019-12-06 11:34:16.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/AIMMSLexer.py
--rw-rw-rw-   0        0        0     4356 2020-01-07 15:51:09.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/breadcrumbs.html
--rw-rw-rw-   0        0        0     1800 2019-11-23 17:54:47.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/footer.html
--rw-rw-rw-   0        0        0     2840 2020-01-07 15:51:38.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/layout.html
--rw-rw-rw-   0        0        0      462 2019-11-23 17:54:47.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/searchbox.html
-drwxrwxrwx   0        0        0        0 2020-01-07 15:54:54.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/
-drwxrwxrwx   0        0        0        0 2020-01-07 15:54:54.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/aimms_css/
--rw-rw-rw-   0        0        0    19439 2019-12-26 11:50:00.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/aimms_css/styles.css
--rw-rw-rw-   0        0        0    64598 2019-05-17 16:00:25.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/AIMMS_logo_H_RGB.png
--rw-rw-rw-   0        0        0    65941 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/AIMMS_logo_S_RGB.png
--rw-rw-rw-   0        0        0     4822 2019-11-23 17:54:47.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/copycode.js
--rw-rw-rw-   0        0        0   116244 2020-01-07 15:45:56.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/favicon.ico
-drwxrwxrwx   0        0        0        0 2020-01-07 15:54:55.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/
--rw-rw-rw-   0        0        0     1082 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/105.png
--rw-rw-rw-   0        0        0      404 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/11.png
--rw-rw-rw-   0        0        0      369 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/110.png
--rw-rw-rw-   0        0        0      386 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/111.png
--rw-rw-rw-   0        0        0      356 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/12.png
--rw-rw-rw-   0        0        0      377 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/13.png
--rw-rw-rw-   0        0        0      350 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/14.png
--rw-rw-rw-   0        0        0      497 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/140.png
--rw-rw-rw-   0        0        0      661 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/141.png
--rw-rw-rw-   0        0        0      408 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/145.png
--rw-rw-rw-   0        0        0      333 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/15 (1).png
--rw-rw-rw-   0        0        0      333 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/15.png
--rw-rw-rw-   0        0        0     2263 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/150.png
--rw-rw-rw-   0        0        0      246 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/152.png
--rw-rw-rw-   0        0        0      337 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/16.png
--rw-rw-rw-   0        0        0     4057 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/160.png
--rw-rw-rw-   0        0        0     4694 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/161.png
--rw-rw-rw-   0        0        0     1261 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/162.png
--rw-rw-rw-   0        0        0      760 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/163.png
--rw-rw-rw-   0        0        0      551 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/168.png
--rw-rw-rw-   0        0        0     1161 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/170.png
--rw-rw-rw-   0        0        0      234 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/172.png
--rw-rw-rw-   0        0        0      433 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/175.png
--rw-rw-rw-   0        0        0     2816 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/176.png
--rw-rw-rw-   0        0        0      378 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/180.png
--rw-rw-rw-   0        0        0      443 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/181.png
--rw-rw-rw-   0        0        0      231 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/200.png
--rw-rw-rw-   0        0        0      330 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/201.png
--rw-rw-rw-   0        0        0      430 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/202.png
--rw-rw-rw-   0        0        0      437 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/203.png
--rw-rw-rw-   0        0        0      371 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/204.png
--rw-rw-rw-   0        0        0      712 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/205.png
--rw-rw-rw-   0        0        0      578 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/205a.png
--rw-rw-rw-   0        0        0      713 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/205b.png
--rw-rw-rw-   0        0        0      400 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/207.png
--rw-rw-rw-   0        0        0      595 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/208.png
--rw-rw-rw-   0        0        0      194 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/210.png
--rw-rw-rw-   0        0        0      213 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/210b.png
--rw-rw-rw-   0        0        0      189 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/211.png
--rw-rw-rw-   0        0        0      184 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/212.png
--rw-rw-rw-   0        0        0     4888 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/3000.png
--rw-rw-rw-   0        0        0      421 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/301.png
--rw-rw-rw-   0        0        0      437 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/302.png
--rw-rw-rw-   0        0        0      367 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/303.png
--rw-rw-rw-   0        0        0      204 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/304.png
--rw-rw-rw-   0        0        0     2562 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/961.png
--rw-rw-rw-   0        0        0     2733 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/962.png
--rw-rw-rw-   0        0        0     2737 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/963.png
--rw-rw-rw-   0        0        0     3267 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/964.png
--rw-rw-rw-   0        0        0     2364 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/965.png
--rw-rw-rw-   0        0        0     3517 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/966.png
--rw-rw-rw-   0        0        0      830 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/activeXIcons.png
--rw-rw-rw-   0        0        0      183 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/apply.png
--rw-rw-rw-   0        0        0      212 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/attribdn.png
--rw-rw-rw-   0        0        0      208 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/attribup.png
--rw-rw-rw-   0        0        0     1225 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/bitmap15.png
--rw-rw-rw-   0        0        0     1183 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/bitmap310.png
--rw-rw-rw-   0        0        0      234 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/blend1.png
--rw-rw-rw-   0        0        0      218 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/blend2.png
--rw-rw-rw-   0        0        0      235 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/blend3.png
--rw-rw-rw-   0        0        0      242 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/blend4.png
--rw-rw-rw-   0        0        0      230 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/blend5.png
--rw-rw-rw-   0        0        0      177 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/btndel.png
--rw-rw-rw-   0        0        0      153 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/btnplus.png
--rw-rw-rw-   0        0        0      211 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/cancel.png
--rw-rw-rw-   0        0        0      211 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/check.png
--rw-rw-rw-   0        0        0      209 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/chkclose.png
--rw-rw-rw-   0        0        0      174 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/ClosedNodeModelExplorer.PNG
--rw-rw-rw-   0        0        0      395 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/copy.png
--rw-rw-rw-   0        0        0      369 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/copyinto.png
--rw-rw-rw-   0        0        0      438 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/copytext.png
--rw-rw-rw-   0        0        0      279 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/DeclarationSectionIcon.PNG
--rw-rw-rw-   0        0        0      230 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/delfoldr.png
--rw-rw-rw-   0        0        0      241 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/delta.png
--rw-rw-rw-   0        0        0     1770 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/dockIcons.png
--rw-rw-rw-   0        0        0      404 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/drag_rmo.png
--rw-rw-rw-   0        0        0      255 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/externalprocedure.png
--rw-rw-rw-   0        0        0      349 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/find.png
--rw-rw-rw-   0        0        0      261 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/FunctionIcon.PNG
--rw-rw-rw-   0        0        0     1817 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/GuiAxProp.png
--rw-rw-rw-   0        0        0      415 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/help.png
--rw-rw-rw-   0        0        0      173 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/hlarger.png
--rw-rw-rw-   0        0        0      173 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/hsmaller.png
--rw-rw-rw-   0        0        0      285 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/IDECheckLeave.PNG
--rw-rw-rw-   0        0        0      370 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/IDESaveAll.PNG
--rw-rw-rw-   0        0        0      212 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/kast.png
--rw-rw-rw-   0        0        0      201 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/lade.png
--rw-rw-rw-   0        0        0      216 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/ladeopen.png
--rw-rw-rw-   0        0        0      356 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/leftarrow.png
--rw-rw-rw-   0        0        0      239 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/librarymodule.png
--rw-rw-rw-   0        0        0      215 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclActivity.PNG
--rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclArc.PNG
--rw-rw-rw-   0        0        0      209 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclAssertion.PNG
--rw-rw-rw-   0        0        0      227 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclCal.PNG
--rw-rw-rw-   0        0        0      229 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclComplVar.PNG
--rw-rw-rw-   0        0        0      214 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclCon.PNG
--rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclConvention.PNG
--rw-rw-rw-   0        0        0      210 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclDatabaseTable.PNG
--rw-rw-rw-   0        0        0      243 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclElementVariable.PNG
--rw-rw-rw-   0        0        0      224 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclElemPar.PNG
--rw-rw-rw-   0        0        0      193 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclFile.PNG
--rw-rw-rw-   0        0        0      152 2019-10-03 15:12:39.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclHandle.PNG
--rw-rw-rw-   0        0        0      191 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclIndex.PNG
--rw-rw-rw-   0        0        0      191 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclMacro.PNG
--rw-rw-rw-   0        0        0      218 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclMP.PNG
--rw-rw-rw-   0        0        0      223 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclNode.PNG
--rw-rw-rw-   0        0        0      180 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclOther.PNG
--rw-rw-rw-   0        0        0      233 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclPar.PNG
--rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclQnt.PNG
--rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclQuantity.PNG
--rw-rw-rw-   0        0        0      218 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclResource.PNG
--rw-rw-rw-   0        0        0      249 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclSet.PNG
--rw-rw-rw-   0        0        0      219 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclStringPar.PNG
--rw-rw-rw-   0        0        0      228 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclUncerConst.PNG
--rw-rw-rw-   0        0        0      217 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEDeclVar.PNG
--rw-rw-rw-   0        0        0      213 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/MEInsertHere.PNG
--rw-rw-rw-   0        0        0      217 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/minmax.png
--rw-rw-rw-   0        0        0      392 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/move.png
--rw-rw-rw-   0        0        0      181 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/movedown.png
--rw-rw-rw-   0        0        0      433 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/movetext.png
--rw-rw-rw-   0        0        0      186 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/moveup.png
--rw-rw-rw-   0        0        0      269 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/newcase.png
--rw-rw-rw-   0        0        0      287 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/newdtset.png
--rw-rw-rw-   0        0        0      234 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/newfoldr.png
--rw-rw-rw-   0        0        0      404 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/none.png
--rw-rw-rw-   0        0        0      200 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/OpenNodeModelExplorer.PNG
--rw-rw-rw-   0        0        0      275 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/ProcedureIcon.PNG
--rw-rw-rw-   0        0        0      232 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/prtbmp.png
--rw-rw-rw-   0        0        0      324 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/SectionIcon.PNG
--rw-rw-rw-   0        0        0      622 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/statusbarIcons.png
--rw-rw-rw-   0        0        0      223 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/totree.png
--rw-rw-rw-   0        0        0      189 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/updir.png
--rw-rw-rw-   0        0        0      175 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/vlarger.png
--rw-rw-rw-   0        0        0      172 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/vsmaller.png
--rw-rw-rw-   0        0        0      498 2019-12-13 11:41:10.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/theme.conf
--rw-rw-rw-   0        0        0      892 2019-12-23 20:25:36.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/__init__.py
-drwxrwxrwx   0        0        0        0 2020-01-07 15:54:54.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/
--rw-rw-rw-   0        0        0        1 2020-01-07 15:54:53.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       62 2020-01-07 15:54:53.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0      344 2020-01-07 15:54:53.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0       24 2020-01-07 15:54:53.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/requires.txt
--rw-rw-rw-   0        0        0     6689 2020-01-07 15:54:54.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0       19 2020-01-07 15:54:53.000000 sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2020-01-09 13:02:35.000000 sphinx_aimms_theme-0.1.9/
+-rw-rw-rw-   0        0        0     1078 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/LICENSE
+-rw-rw-rw-   0        0        0      280 2019-12-23 20:42:53.000000 sphinx_aimms_theme-0.1.9/MANIFEST.in
+-rw-rw-rw-   0        0        0      344 2020-01-09 13:02:35.000000 sphinx_aimms_theme-0.1.9/PKG-INFO
+-rw-rw-rw-   0        0        0     4732 2019-12-16 21:47:19.000000 sphinx_aimms_theme-0.1.9/README.md
+-rw-rw-rw-   0        0        0       86 2020-01-09 13:02:35.000000 sphinx_aimms_theme-0.1.9/setup.cfg
+-rw-rw-rw-   0        0        0      926 2020-01-09 13:02:22.000000 sphinx_aimms_theme-0.1.9/setup.py
+drwxrwxrwx   0        0        0        0 2020-01-09 13:02:34.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/
+-rw-rw-rw-   0        0        0    23132 2019-12-06 11:49:40.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/AIMMSDomain.py
+-rw-rw-rw-   0        0        0    33851 2019-12-06 11:34:16.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/AIMMSLexer.py
+-rw-rw-rw-   0        0        0     4356 2020-01-07 15:51:09.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/breadcrumbs.html
+-rw-rw-rw-   0        0        0     1800 2019-11-23 17:54:47.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/footer.html
+-rw-rw-rw-   0        0        0     3089 2020-01-07 15:57:47.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/layout.html
+-rw-rw-rw-   0        0        0      462 2019-11-23 17:54:47.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/searchbox.html
+drwxrwxrwx   0        0        0        0 2020-01-09 13:02:34.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/
+drwxrwxrwx   0        0        0        0 2020-01-09 13:02:34.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/aimms_css/
+-rw-rw-rw-   0        0        0    19205 2020-01-07 15:58:08.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/aimms_css/styles.css
+-rw-rw-rw-   0        0        0    64598 2019-05-17 16:00:25.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/AIMMS_logo_H_RGB.png
+-rw-rw-rw-   0        0        0    65941 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/AIMMS_logo_S_RGB.png
+-rw-rw-rw-   0        0        0     4822 2019-11-23 17:54:47.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/copycode.js
+-rw-rw-rw-   0        0        0   116244 2020-01-07 15:45:56.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/favicon.ico
+drwxrwxrwx   0        0        0        0 2020-01-09 13:02:35.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/
+-rw-rw-rw-   0        0        0     1082 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/105.png
+-rw-rw-rw-   0        0        0      404 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/11.png
+-rw-rw-rw-   0        0        0      369 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/110.png
+-rw-rw-rw-   0        0        0      386 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/111.png
+-rw-rw-rw-   0        0        0      356 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/12.png
+-rw-rw-rw-   0        0        0      377 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/13.png
+-rw-rw-rw-   0        0        0      350 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/14.png
+-rw-rw-rw-   0        0        0      497 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/140.png
+-rw-rw-rw-   0        0        0      661 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/141.png
+-rw-rw-rw-   0        0        0      408 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/145.png
+-rw-rw-rw-   0        0        0      333 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/15 (1).png
+-rw-rw-rw-   0        0        0      333 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/15.png
+-rw-rw-rw-   0        0        0     2263 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/150.png
+-rw-rw-rw-   0        0        0      246 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/152.png
+-rw-rw-rw-   0        0        0      337 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/16.png
+-rw-rw-rw-   0        0        0     4057 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/160.png
+-rw-rw-rw-   0        0        0     4694 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/161.png
+-rw-rw-rw-   0        0        0     1261 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/162.png
+-rw-rw-rw-   0        0        0      760 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/163.png
+-rw-rw-rw-   0        0        0      551 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/168.png
+-rw-rw-rw-   0        0        0     1161 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/170.png
+-rw-rw-rw-   0        0        0      234 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/172.png
+-rw-rw-rw-   0        0        0      433 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/175.png
+-rw-rw-rw-   0        0        0     2816 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/176.png
+-rw-rw-rw-   0        0        0      378 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/180.png
+-rw-rw-rw-   0        0        0      443 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/181.png
+-rw-rw-rw-   0        0        0      231 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/200.png
+-rw-rw-rw-   0        0        0      330 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/201.png
+-rw-rw-rw-   0        0        0      430 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/202.png
+-rw-rw-rw-   0        0        0      437 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/203.png
+-rw-rw-rw-   0        0        0      371 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/204.png
+-rw-rw-rw-   0        0        0      712 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/205.png
+-rw-rw-rw-   0        0        0      578 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/205a.png
+-rw-rw-rw-   0        0        0      713 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/205b.png
+-rw-rw-rw-   0        0        0      400 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/207.png
+-rw-rw-rw-   0        0        0      595 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/208.png
+-rw-rw-rw-   0        0        0      194 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/210.png
+-rw-rw-rw-   0        0        0      213 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/210b.png
+-rw-rw-rw-   0        0        0      189 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/211.png
+-rw-rw-rw-   0        0        0      184 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/212.png
+-rw-rw-rw-   0        0        0     4888 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/3000.png
+-rw-rw-rw-   0        0        0      421 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/301.png
+-rw-rw-rw-   0        0        0      437 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/302.png
+-rw-rw-rw-   0        0        0      367 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/303.png
+-rw-rw-rw-   0        0        0      204 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/304.png
+-rw-rw-rw-   0        0        0     2562 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/961.png
+-rw-rw-rw-   0        0        0     2733 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/962.png
+-rw-rw-rw-   0        0        0     2737 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/963.png
+-rw-rw-rw-   0        0        0     3267 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/964.png
+-rw-rw-rw-   0        0        0     2364 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/965.png
+-rw-rw-rw-   0        0        0     3517 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/966.png
+-rw-rw-rw-   0        0        0      830 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/activeXIcons.png
+-rw-rw-rw-   0        0        0      183 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/apply.png
+-rw-rw-rw-   0        0        0      212 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/attribdn.png
+-rw-rw-rw-   0        0        0      208 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/attribup.png
+-rw-rw-rw-   0        0        0     1225 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/bitmap15.png
+-rw-rw-rw-   0        0        0     1183 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/bitmap310.png
+-rw-rw-rw-   0        0        0      234 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/blend1.png
+-rw-rw-rw-   0        0        0      218 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/blend2.png
+-rw-rw-rw-   0        0        0      235 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/blend3.png
+-rw-rw-rw-   0        0        0      242 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/blend4.png
+-rw-rw-rw-   0        0        0      230 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/blend5.png
+-rw-rw-rw-   0        0        0      177 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/btndel.png
+-rw-rw-rw-   0        0        0      153 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/btnplus.png
+-rw-rw-rw-   0        0        0      211 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/cancel.png
+-rw-rw-rw-   0        0        0      211 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/check.png
+-rw-rw-rw-   0        0        0      209 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/chkclose.png
+-rw-rw-rw-   0        0        0      174 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/ClosedNodeModelExplorer.PNG
+-rw-rw-rw-   0        0        0      395 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/copy.png
+-rw-rw-rw-   0        0        0      369 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/copyinto.png
+-rw-rw-rw-   0        0        0      438 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/copytext.png
+-rw-rw-rw-   0        0        0      279 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/DeclarationSectionIcon.PNG
+-rw-rw-rw-   0        0        0      230 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/delfoldr.png
+-rw-rw-rw-   0        0        0      241 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/delta.png
+-rw-rw-rw-   0        0        0     1770 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/dockIcons.png
+-rw-rw-rw-   0        0        0      404 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/drag_rmo.png
+-rw-rw-rw-   0        0        0      255 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/externalprocedure.png
+-rw-rw-rw-   0        0        0      349 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/find.png
+-rw-rw-rw-   0        0        0      261 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/FunctionIcon.PNG
+-rw-rw-rw-   0        0        0     1817 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/GuiAxProp.png
+-rw-rw-rw-   0        0        0      415 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/help.png
+-rw-rw-rw-   0        0        0      173 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/hlarger.png
+-rw-rw-rw-   0        0        0      173 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/hsmaller.png
+-rw-rw-rw-   0        0        0      285 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/IDECheckLeave.PNG
+-rw-rw-rw-   0        0        0      370 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/IDESaveAll.PNG
+-rw-rw-rw-   0        0        0      212 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/kast.png
+-rw-rw-rw-   0        0        0      201 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/lade.png
+-rw-rw-rw-   0        0        0      216 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/ladeopen.png
+-rw-rw-rw-   0        0        0      356 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/leftarrow.png
+-rw-rw-rw-   0        0        0      239 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/librarymodule.png
+-rw-rw-rw-   0        0        0      215 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclActivity.PNG
+-rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclArc.PNG
+-rw-rw-rw-   0        0        0      209 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclAssertion.PNG
+-rw-rw-rw-   0        0        0      227 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclCal.PNG
+-rw-rw-rw-   0        0        0      229 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclComplVar.PNG
+-rw-rw-rw-   0        0        0      214 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclCon.PNG
+-rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclConvention.PNG
+-rw-rw-rw-   0        0        0      210 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclDatabaseTable.PNG
+-rw-rw-rw-   0        0        0      243 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclElementVariable.PNG
+-rw-rw-rw-   0        0        0      224 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclElemPar.PNG
+-rw-rw-rw-   0        0        0      193 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclFile.PNG
+-rw-rw-rw-   0        0        0      152 2019-10-03 15:12:39.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclHandle.PNG
+-rw-rw-rw-   0        0        0      191 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclIndex.PNG
+-rw-rw-rw-   0        0        0      191 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclMacro.PNG
+-rw-rw-rw-   0        0        0      218 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclMP.PNG
+-rw-rw-rw-   0        0        0      223 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclNode.PNG
+-rw-rw-rw-   0        0        0      180 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclOther.PNG
+-rw-rw-rw-   0        0        0      233 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclPar.PNG
+-rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclQnt.PNG
+-rw-rw-rw-   0        0        0      222 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclQuantity.PNG
+-rw-rw-rw-   0        0        0      218 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclResource.PNG
+-rw-rw-rw-   0        0        0      249 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclSet.PNG
+-rw-rw-rw-   0        0        0      219 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclStringPar.PNG
+-rw-rw-rw-   0        0        0      228 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclUncerConst.PNG
+-rw-rw-rw-   0        0        0      217 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEDeclVar.PNG
+-rw-rw-rw-   0        0        0      213 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/MEInsertHere.PNG
+-rw-rw-rw-   0        0        0      217 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/minmax.png
+-rw-rw-rw-   0        0        0      392 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/move.png
+-rw-rw-rw-   0        0        0      181 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/movedown.png
+-rw-rw-rw-   0        0        0      433 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/movetext.png
+-rw-rw-rw-   0        0        0      186 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/moveup.png
+-rw-rw-rw-   0        0        0      269 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/newcase.png
+-rw-rw-rw-   0        0        0      287 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/newdtset.png
+-rw-rw-rw-   0        0        0      234 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/newfoldr.png
+-rw-rw-rw-   0        0        0      404 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/none.png
+-rw-rw-rw-   0        0        0      200 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/OpenNodeModelExplorer.PNG
+-rw-rw-rw-   0        0        0      275 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/ProcedureIcon.PNG
+-rw-rw-rw-   0        0        0      232 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/prtbmp.png
+-rw-rw-rw-   0        0        0      324 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/SectionIcon.PNG
+-rw-rw-rw-   0        0        0      622 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/statusbarIcons.png
+-rw-rw-rw-   0        0        0      223 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/totree.png
+-rw-rw-rw-   0        0        0      189 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/updir.png
+-rw-rw-rw-   0        0        0      175 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/vlarger.png
+-rw-rw-rw-   0        0        0      172 2019-10-02 08:46:51.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/vsmaller.png
+-rw-rw-rw-   0        0        0      498 2019-12-13 11:41:10.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/theme.conf
+-rw-rw-rw-   0        0        0      892 2019-12-23 20:25:36.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/__init__.py
+drwxrwxrwx   0        0        0        0 2020-01-09 13:02:34.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/
+-rw-rw-rw-   0        0        0        1 2020-01-09 13:02:33.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       62 2020-01-09 13:02:33.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0      344 2020-01-09 13:02:33.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0       24 2020-01-09 13:02:33.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/requires.txt
+-rw-rw-rw-   0        0        0     6689 2020-01-09 13:02:34.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0       19 2020-01-09 13:02:33.000000 sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/top_level.txt
```

### Comparing `sphinx_aimms_theme-0.1.8/LICENSE` & `sphinx_aimms_theme-0.1.9/LICENSE`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/README.md` & `sphinx_aimms_theme-0.1.9/README.md`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/setup.py` & `sphinx_aimms_theme-0.1.9/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 import setuptools
 import sys
 
 
 setup(
     
     name = "sphinx_aimms_theme",
-    version = '0.1.8',
+    version = '0.1.9',
     license = "MIT",
     packages= ['sphinx_aimms_theme'],
     url = "https://gitlab.com/ArthurdHerbemont/sphinx-aimms-theme",
     description = 'AIMMS theme for Sphinx',
     long_description='Please refer to https://gitlab.com/ArthurdHerbemont/sphinx-aimms-theme',
     author = "AIMMS User Support",
     author_email = "support@aimms.com",
```

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/AIMMSDomain.py` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/AIMMSDomain.py`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/AIMMSLexer.py` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/AIMMSLexer.py`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/breadcrumbs.html` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/breadcrumbs.html`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/footer.html` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/footer.html`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/layout.html` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/layout.html`

 * *Files 12% similar despite different names*

```diff
@@ -3,14 +3,21 @@
 <link rel="stylesheet" href="https://use.typekit.net/ydq4pad.css">
 <link rel='stylesheet' id='font-awesome-original-css' href='https://techblog.aimms.com/wp-content/plugins/dpArticleShare/css/font-awesome.css?ver=1.3.4' type='text/css' media='all' /> 
 
 {% block extrahead %}
 {% if theme_display_algolia_search %}
 <!-- Algolia's docsearch stylesheet -->
 <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/docsearch.js@2/dist/cdn/docsearch.min.css" />
+<style>
+/*---------- Algolia search ----------*/
+/*In order to have the search widget on top of the content */
+.wy-nav-side { overflow: visible; }
+.wy-side-scroll { overflow: inherit; }
+.ds-input {vertical-align: inherit!important;}
+</style>
 {% endif %}
 <link rel="shortcut icon" href="_static/favicon.ico"/>
 {% if pagename == master_doc %} 
 <meta name="description" content="{{ theme_home_page_description }}"> 
 {% endif %} {% endblock %} 
 
 {% block sidebartitle %}{% include "searchbox.html" %} {% endblock %}
```

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/aimms_css/styles.css` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/aimms_css/styles.css`

 * *Files 1% similar despite different names*

```diff
@@ -246,21 +246,14 @@
 }
     
 /* --------------     Styling for intersphinx references -------------------------------- */
 
 /*Brown color for items coming from the AIMMS Function Reference intersphinx*/
 a[title="(in AIMMS Function Reference)"] .aimms .pre { color: brown; }
 
-/*---------- Algolia search ----------*/
-/*In order to have the search widget on top of the content */
-
-.wy-nav-side { overflow: visible; }
-.wy-side-scroll { overflow: inherit; }
-.ds-input {vertical-align: inherit!important;}
-
 /* --------------     Global document styling -------------------------------- */
 
 h1, h2, .rst-content .toctree-wrapper p.caption, h3, h4, h5, h6, legend, p {
   font-family: "Open Sans", sans-serif;
   margin-top: 20px; }
 
 .btn {
```

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/AIMMS_logo_H_RGB.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/AIMMS_logo_H_RGB.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/AIMMS_logo_S_RGB.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/AIMMS_logo_S_RGB.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/copycode.js` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/copycode.js`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/favicon.ico` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/favicon.ico`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/105.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/105.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/141.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/141.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/150.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/150.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/160.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/160.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/161.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/161.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/162.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/162.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/163.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/163.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/168.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/168.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/170.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/170.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/176.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/176.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/205.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/205.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/205a.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/205a.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/205b.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/205b.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/208.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/208.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/3000.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/3000.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/961.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/961.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/962.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/962.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/963.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/963.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/964.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/964.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/965.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/965.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/966.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/966.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/activeXIcons.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/activeXIcons.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/bitmap15.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/bitmap15.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/bitmap310.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/bitmap310.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/dockIcons.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/dockIcons.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/GuiAxProp.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/GuiAxProp.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/static/icons/statusbarIcons.png` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/static/icons/statusbarIcons.png`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme/__init__.py` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme/__init__.py`

 * *Files identical despite different names*

### Comparing `sphinx_aimms_theme-0.1.8/sphinx_aimms_theme.egg-info/SOURCES.txt` & `sphinx_aimms_theme-0.1.9/sphinx_aimms_theme.egg-info/SOURCES.txt`

 * *Files identical despite different names*

