# Comparing `tmp/dahu12-0.0.0.0.2.1.tar.gz` & `tmp/dahu12-0.0.0.0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dahu12-0.0.0.0.2.1.tar", max compression
+gzip compressed data, was "dahu12-0.0.0.0.2.2.tar", max compression
```

## Comparing `dahu12-0.0.0.0.2.1.tar` & `dahu12-0.0.0.0.2.2.tar`

### file list

```diff
@@ -1,15 +1,23 @@
--rw-r--r--   0        0        0      136 2023-04-08 17:02:11.012331 dahu12-0.0.0.0.2.1/DAHU/__init__.py
--rw-r--r--   0        0        0     1243 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/donnees.py
--rw-r--r--   0        0        0      194 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/elec.py
--rw-r--r--   0        0        0     2469 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/erreurs.py
--rw-r--r--   0        0        0     1959 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/graph.py
--rw-r--r--   0        0        0     1466 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/main.py
--rw-r--r--   0        0        0    18747 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/maths.py
--rw-r--r--   0        0        0     1963 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/meca.py
--rw-r--r--   0        0        0     2330 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/papiers.py
--rw-r--r--   0        0        0      200 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/phy.py
--rw-r--r--   0        0        0      933 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/DAHU/test.py
--rw-r--r--   0        0        0     1261 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/LICENSE
--rw-r--r--   0        0        0      699 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/README.md
--rw-r--r--   0        0        0      523 2023-04-08 17:02:11.016331 dahu12-0.0.0.0.2.1/pyproject.toml
--rw-r--r--   0        0        0     1478 1970-01-01 00:00:00.000000 dahu12-0.0.0.0.2.1/PKG-INFO
+-rw-r--r--   0        0        0       47 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/.idea/.gitignore
+-rw-r--r--   0        0        0      441 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/.idea/DAHU.iml
+-rw-r--r--   0        0        0      174 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/.idea/inspectionProfiles/profiles_settings.xml
+-rw-r--r--   0        0        0      186 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/.idea/misc.xml
+-rw-r--r--   0        0        0      260 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/.idea/modules.xml
+-rw-r--r--   0        0        0      183 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/.idea/vcs.xml
+-rw-r--r--   0        0        0      136 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/__init__.py
+-rw-r--r--   0        0        0     1740 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/cartes.py
+-rw-r--r--   0        0        0        0 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/chimie.py
+-rw-r--r--   0        0        0     1243 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/donnees.py
+-rw-r--r--   0        0        0      194 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/elec.py
+-rw-r--r--   0        0        0     2469 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/erreurs.py
+-rw-r--r--   0        0        0      808 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/graph.py
+-rw-r--r--   0        0        0     1466 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/main.py
+-rw-r--r--   0        0        0    25846 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/maths.py
+-rw-r--r--   0        0        0     1963 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/meca.py
+-rw-r--r--   0        0        0     2343 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/papiers.py
+-rw-r--r--   0        0        0      309 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/phy.py
+-rw-r--r--   0        0        0      965 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/DAHU/test.py
+-rw-r--r--   0        0        0     1261 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/LICENSE
+-rw-r--r--   0        0        0      733 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/README.md
+-rw-r--r--   0        0        0      563 2023-06-28 07:40:11.967846 dahu12-0.0.0.0.2.2/pyproject.toml
+-rw-r--r--   0        0        0     1601 1970-01-01 00:00:00.000000 dahu12-0.0.0.0.2.2/PKG-INFO
```

### Comparing `dahu12-0.0.0.0.2.1/DAHU/donnees.py` & `dahu12-0.0.0.0.2.2/DAHU/donnees.py`

 * *Files identical despite different names*

### Comparing `dahu12-0.0.0.0.2.1/DAHU/erreurs.py` & `dahu12-0.0.0.0.2.2/DAHU/erreurs.py`

 * *Files identical despite different names*

### Comparing `dahu12-0.0.0.0.2.1/DAHU/main.py` & `dahu12-0.0.0.0.2.2/DAHU/main.py`

 * *Files identical despite different names*

### Comparing `dahu12-0.0.0.0.2.1/DAHU/maths.py` & `dahu12-0.0.0.0.2.2/DAHU/maths.py`

 * *Files 22% similar despite different names*

```diff
@@ -2,83 +2,171 @@
 
 ## Faire les docstrings : """...""" ##
 
 ## Import des modules & packages essentiels ##
 ## Packages extérieurs
 import giacpy
 import random
+import copy
 
 ## Modules internes
-from DAHU.donnees import pi
+from donnees import pi
 
 # Utilisation de Giac pour gestion des variables et des expressions et autres pitits trucs #
 
 ## Definitions d'objets mathématiques généraux ##
 
 class Expression :
+    """Classe permettant de créer et manipuler les expressions"""
 
     def __init__(self,expr,var,cte = None) : #Création d'une expression à l'aide d'un str (Faire les filtres) !
         self.c = {"var" : var ,"cte" : cte}
         self.Expr = giacpy.giac(expr)
         self.sexpr = str(self.Expr)
         self.derivs = []
         self.ints = []
+        self.ty = ""
+        if "=" in self.sexpr :
+            self.ty = "equa"
 
     def __getitem__(self,index) :
         return self.Expr[index]
 
     def __setitem__(self,index,valeur) :
         self.Expr[index] = valeur
     
     def __str__(self) :
         return self.sexpr
 
     def __len__(self):
         return len(self.sexpr)
     
     def __repr__(self) :
-        a = str(self)
-        return self
+        return self.sexpr
 
     def __add__(self,autre) :
-        a = self.sexpr
-        b = autre.sexpr
-        a = giacpy.giac(a)
-        b = giacpy.giac(b)
-        c = a + b
-        self.Expr = c
-        self.sexpr = str(c)
-        return self
+        if isinstance(autre,Expression) :
+            a = self.sexpr
+            b = autre.sexpr
+            a = giacpy.giac(a)
+            b = giacpy.giac(b)
+            c = a + b
+            self.Expr = c
+            self.sexpr = str(c)
+            return self
+        if isinstance(autre,int) :
+            a = "("+self.sexpr+")+"+str(autre)
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+        if isinstance(autre,float) :
+            a = "("+self.sexpr+")+"+str(autre)
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+    
+    def __radd__(autre,self) :
+        if isinstance(autre,Expression) :
+            return autre + self
+        if isinstance(autre,int) :
+            a = str(autre)+"+("+self.sexpr+")"
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+        if isinstance(autre,float) :
+            a = str(autre)+"+("+self.sexpr+")"
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+
+    def __iadd__(self,autre) : #A faire
+        pass
+
+    def __sub__(self,autre) : #A faire
+        pass
+
+    def __rsub__(self,autre) : #A faire
+        pass
+
+    def __isub__(self,autre) : #A faire
+        pass
+
+    def __mul__(self,autre) : #!!
+        if isinstance(autre,Expression) :
+            a = self.sexpr
+            b = autre.sexpr
+            self.sexpr = a+"*"+b
+            self.Expr = giacpy.giac(self.sexpr)
+            return self
+        if isinstance(autre,int) :
+            a = "("+self.sexpr+")*"+str(autre)
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+        if isinstance(autre,float) :
+            a = "("+self.sexpr+")*"+str(autre)
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+
+    def __rmul__(autre,self) : #!!
+        if isinstance(autre,Expression) :
+            return autre * self
+        if isinstance(autre,int) :
+            a = str(autre)+"*("+self.sexpr+")"
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+        if isinstance(autre,float) :
+            a = str(autre)+"*("+self.sexpr+")"
+            self.sexpr = a
+            self.Expr = giacpy.giac(a)
+            return self
+
+    def __imul__(self,autre) : #A faire
+        pass
 
-    def subs(self,var_1,var_2) :
+    def __div__(self,autre) : #A faire
+        pass
+
+    def __rdiv__(self,autre) : #A faire
+        pass
+
+    def __idiv__(self,autre) : #A faire
+        pass
+
+    def __pow__(self,autre) : #A faire
+        pass
+
+    def subs(self,var_1,var_2) : #Substitue une variable en une autre
         a = self.sexpr
         b = a.replace(str(var_1),str(var_2))
         return b
     
-    def eval(self,var,val) :
+    def eval(self,var,val) : #Evalue l'expression pour une valeur
         a = self.subs(var,val)
         b = giacpy.giac(a)
         return float(b)
     
     ## Calcul infinitesimal : derivees, integrales, limites ...##
 
-    def deriv(self,var) : 
-        expr1 = giacpy.diff(self.Expr,var)
+    def deriv(self, var) :
+        expr1 = giacpy.diff(self.Expr, var)
         self.derivs.append(str(expr1))
-        derivexpr = Expression(str(expr1),var=self.c)
+        derivexpr = Expression(str(expr1), var=self.c)
         return derivexpr
     
-    def int(self,var,a=None,b=None):
+    def int(self, var, a=None, b=None):
         if a == None and b == None :
             self.Expr = giacpy.int(self.Expr,var)
             self.ints.append(str(self.Expr))
             intexpr = Expression(str(self.Expr),var=self.c)
             return intexpr
         else :
-            pass
+            return giacpy.int(self.Expr,var,a,b)
 
     def simp(self) :
         self.Expr = giacpy.simplify(self.Expr)
         self.sexpr = str(self.Expr)
         return self
 
     def sucderiv(self,var,nb) :
@@ -95,14 +183,20 @@
     def hessi(self,ordre): #Renvoie la matrice hessienne d'une fonction ! (faire les filtres)
         pass
 
     def lim(self,var,val): #Renvoie la limite d'une fonction en une valeur (faire les filtres)
         lim = giacpy.limit(self.Expr,var,giacpy.giac(val))
         lim = str(lim)
         return lim
+    
+    def solve(self) :
+        if self.ty == "equa" :
+            print(giacpy.solve(self.Expr,self.c["var"]))
+        else :
+            return None
 
 class Matrice :
     """Classe permettant de creer et manipuler les matrices"""
     
     ## Definition des fonctions elementaires et operations de la classe ##
 
     def __init__(self,nbl,nbc) : #Initialise une matrice (genere la matrice nulle)
@@ -232,20 +326,83 @@
         # + Verification matrice meme dimension
         for i in range(self.nbl) :
             for j in range(self.nbc) :
                 if self[i][j] != autre[i][j] :
                     return False
                 else :
                     return True
-    
+
+    def round(self, n=None):
+        for i in range(self.nbl):
+            for j in range(self.nbc):
+                self[i][j] = round(self[i][j],n)
+        return self
+
+    def clear(self) :
+        for i in range(self.nbl) :
+            for j in range(self.nbc) :
+                self[i][j] = 0
+
+    def copy(self):
+        mat = Matrice(self.nbl,self.nbc)
+        mat.Matrice = copy.deepcopy(self.Matrice)
+        return mat
+
     def giac_convert(self) :
         return giacpy.giac(self.Matrice)
 
     ## Methodes ##
 
+    def mat_augm_lig(self, pos = None):  # Insère une ligne vide à la position mise en agrument
+        lig = []
+        for i in range(self.nbc):
+            lig.append(0)
+        if pos != None:
+            sto_lig = {}
+            for i in range(pos - 1, self.nbl):
+                sto_lig[str(i)] = self[i]
+            self[pos - 1] = lig
+            for k in sto_lig.keys():
+                if int(k) + 1 <= self.nbl:
+                    self.Matrice.append(sto_lig[k])
+                for j in range(self.nbc):
+                    self[int(k) + 1] = sto_lig[k]
+            self.nbl += 1
+        else:
+            self.Matrice.append(lig)
+            self.nbl += 1
+
+    def mat_augm_col(self, pos = None):
+        if pos != None:
+            for i in range(self.nbl):
+                self.Matrice[i].insert(pos - 1, 0)
+            self.nbc += 1
+        else:
+            for i in range(self.nbl):
+                self.Matrice[i].insert(self.nbc, 0)
+            self.nbc += 1
+
+    def mat_sup_lig(self, pos = None):
+        if pos != None :
+            del self.Matrice[pos-1]
+            self.nbl -= 1
+        else :
+            del self.Matrice[self.nbl-1]
+            self.nbl -= 1
+
+    def mat_sup_col(self, pos = None):
+        if pos != None :
+            for i in range(self.nbl) :
+                del self.Matrice[i][pos-1]
+            self.nbc -= 1
+        else :
+            for i in range(self.nbl) :
+                del self.Matrice[i][self.nbc-1]
+            self.nbc -= 1
+
     def dim(self): #Renvoie la dimension de la matrice !
         return (self.nbl,self.nbc)
 
     def iscarree(self) : #Vérification qu'une matrice est carree
         if self.nbl == self.nbc :
             return True
         else :
@@ -284,44 +441,55 @@
         if self.iscarree() == True :
             if self.dim() == (2,2) :
                 det = self[0][0]*self[1][1] - self[0][1]*self[1][0]
                 return det
             else :
                 a = self.giac_convert()
                 det = giacpy.det(a)
-                return det
+                return int(det)
 
     def tranvesction_lig(self,ligne_1,ligne_2,valeur) : #Transvecte une ligne avec une autre d'une certaine valeur (faire les filtres) !
         n = self.dim()
         a = mel_transvection(ligne_1,ligne_2,valeur,n[1])
         return a*self
 
     def tranvesction_col(self,ligne_1,ligne_2,valeur) : #Transvecte une colonne avec une autre d'une certaine valeur (faire les filtres) !
         n = self.dim()
         a = mel_transvection(ligne_1,ligne_2,valeur,n[1])
         return self*a
 
-    def comatrice(self) : #Retourne la matrice de cofacteur d'une matrice (A faire) !
-        pass
+    def comatrice(self) : #Retourne la matrice de cofacteur d'une matrice !
+        mat = Matrice(self.nbl,self.nbc)
+        for i in range(self.nbl) :
+            for j in range(self.nbc) :
+                a = self.copy()
+                a.mat_sup_lig(pos = i+1)
+                a.mat_sup_col(pos = j+1)
+                print(a)
+                mat[i][j] = a.det()*(-1)**(i+j)
+        return mat
 
-    def inverse(self) : #Nous retourne la matrice inverse (Definir comatrice()) (Faire les filtres) !
-        if self.isinversible() == True :
+    def inverse(self, arr=True, dig=3): #Nous retourne la matrice inverse (Definir comatrice()) (Faire les filtres) !
+        if self.isinversible()==True:
             a = self.comatrice()
             b = 1/(self.det())*(a.transposee())
-            self.Matrice = b
+            if arr == True:
+                b.round(dig)
+            return b
 
     def gauss_jordan(self) : #Met la matrice sous forme echelon reduite (A faire) !
         n = self.dim()
         pass
 
     def eigenval(self) :
         #Vérification matrice carrée
         for i in range(self.dim()[0]) :
             self[i][i] = Expression(str(self[i][i])+"-t",var=["t"])
         det = self.det()
+        print(det)
         # Définir résolution polynomiale pour résolution det(A)=0
 
     def eigenvec(self) :
         pass
 
     def Spectre(self) : #Renvoie le spectre de la matrice si elle est diagonalisable (A faire) !
         pass
@@ -335,14 +503,18 @@
     def tr(self) :
         a = 0
         for lig in range(self.nbl) :
             for col in range(self.nbc) :
                 if col == lig :
                     a += self[lig][col]
         return a
+    
+    def pseudo_inverse(self):
+        pass
+
 
 class Vecteur(Matrice) :
 
     def __init__(self,n) : #Initialisation d'un vecteur (genere le vecteur nul)
         self.l = n
         vec = super().__init__(n,1)
         self.Vecteur = vec
@@ -416,14 +588,18 @@
             self.r = self.a
             self.th = 0
         elif self.a == 0 and self.b != 0 :
             self.r = self.b
             self.th = (pi)/2
         return (self.r, self.th)
 
+class Graphe :
+    def __init__(self):
+        pass
+
 class Fonction(Expression) :
     def __init__(self,nom,expr,var) :
         self.Fonction = {"{}".format(nom) : expr, "var" : var}
         self.df = [] #Liste d'intervalles ou 1 intervalle (domaine de def)
         self.lim = [] #Liste des limites associées aux valeurs limval
         self.limval = []
 
@@ -561,14 +737,19 @@
     return mat
 
 def mel_transvection(ligne_1,ligne_2,valeur,n) : #Matrice elementaire de transvections de 2 lignes (l1 prend la valeur de l1-valeur*l2) (faire les filtres) !
     a = valeur * mat_creuse_1(ligne_2,ligne_1,1,n)
     mat = matriceid(n) +  a
     return mat
 
+def matrice_augmentee(mat_1,mat_2) :
+    m_a = []
+    m_a.append(mat_1)
+    m_a.append(mat_2)
+    return m_a
 
 ## Fonctions de Calcul algebrique ##
 
 
 def taylor(expr,var,pt,ordre) :
     expr.sucderiv(var,ordre)
 
@@ -584,35 +765,98 @@
 
 def PPCM(nb_1,nb_2) : #Renvoie le plus petit commun multiple de deux nombres
     pass
 
 def eratostene(n) : #Renvoie une liste contenant tous les nombres premier de 1 jusqu'a n par le crible d'eratostene
     pass
 
-def segme(start,stop,step): #Faire les filtres
-    f = []
-    f.append(start)
-    while start != stop or start < stop :
-        start += step
-        if start > stop :
-            break
-        f.append(start)
-    return f
+def segme(start,stop,nbpts): #Definit un découpage sur un segment entre deux valeurs Faire les filtres
+    delta_x = (stop - start)/(nbpts-1)
+    segme = [start+i*delta_x for i in range(0,nbpts)]
+    return segme
 
 
-## Analyse numérique
+## Statistiques
+
+def moyenne(x,n=None):
+    if n == None :
+        j = 0
+        for i in len(x):
+            j += x[i]
+        moy = j/len(x)
+        return moy
+    else :
+        if len(x) == len(n) :
+            j = 0
+            for i in len(n) :
+                j+=x[i]*n[i]
+            moy = j/len(n)
+        
+        return moy
+
+def variance():
+    pass
+
+def ecart_type():
+    pass
+
+def covariance():
+    pass
+
+def coef_correlation() :
+    pass
+
+def choix_reg():
+    pass
+
+## Analyse numérique et de donnees
+
+def num_deriv(x,y=None,pas=None) : #Prend une liste donnees
+    deriv = []
+    if y != None and pas == None :
+        if len(x) == len(y) :
+            for i in range(1,len(x)-1) :
+                deriv.append((x[i]-x[i-1])/(y[i]-y[i-1]))
+            return deriv
+        else :
+            print("Erreur")
+    elif y == None and pas != None :
+        for i in range(1,len(x)-1) :
+            deriv.append((x[i]-x[i-1])/pas)
+    else :
+        print("Erreur")
 
 def regr() : #Regression linéaire, logarithmique, exponentielle ou puissance à partir de données
     pass
 
 def MCNL () : #Curvefit avec la méthode des moindres carrées non linéaire
     pass
 
 
 ## Autres & vrac
 
 def red_gauss(q) :
     return giacpy.gauss(q.Expr,q.c["var"])
 
-
-
+def trigo_fourier(f) : #Donne les coefficients trigonométriques de Fourier généraux sous la forme d'une liste (dans l'intervale -pi pi, donc série est 2pi périodique) Faire les filtres
+    coef = []
+    a0 = str(giacpy.fourier_an)
+    return coef
+
+def somme(expr,indic,max) : #Utilisation de la somme sigma
+    if indic in expr.c["var"] :
+        modifex = Expression(expr.sexpr,var=expr.c["var"].remove(indic))
+    ssomme = ""
+    for i in range(max) :
+        a = expr.subs(indic,i+1)
+        if i == max-1 :
+            ssomme += str(a)
+        else :
+            ssomme += str(a) + "+"
+    somme = Expression(ssomme,var=modifex.c["var"])
+    return somme
+
+def serie_fourier(coefs,max) :
+    a = Expression(str(coefs[1])+"*cos(nx)"+"+"+str(coefs[2])+"*sin(nx)",var=["n","x"])
+    serie = coefs[0]+somme(a,"n",max)
+    return serie
```

### Comparing `dahu12-0.0.0.0.2.1/DAHU/meca.py` & `dahu12-0.0.0.0.2.2/DAHU/meca.py`

 * *Files identical despite different names*

### Comparing `dahu12-0.0.0.0.2.1/DAHU/papiers.py` & `dahu12-0.0.0.0.2.2/DAHU/papiers.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 from reportlab.pdfgen import canvas
 from reportlab.lib.pagesizes import landscape
 from reportlab.lib.units import mm
 from math import tan
+
 ## Formats et themes predefinis ## 
 
 A4 = (297*mm,210*mm)
 
 defaut = {} #Noir
 
 class Papier :
@@ -28,22 +29,22 @@
         self.pdf.save()
 
 def milli(format=A4,nom="milli.pdf",mar=[6*mm,6*mm,6*mm,10*mm]) :
     pdf = canvas.Canvas(nom,pagesize=landscape(format))
     c = 0
     marges = [0+mar[0],0+mar[1],format[0]-mar[2],format[1]-mar[3]]
     print(marges)
-    for i in range(format[0],294) :
+    for i in range(int(format[0]),294) :
         if c%5 == 0 or c == 0 :
             pdf.setLineWidth(0.3*mm)
-            pdf.line(a*mm,5*mm,a*mm,190*mm)
+            pdf.line(i*mm,5*mm,i*mm,190*mm)
             c += 1
         else :
             pdf.setLineWidth(0.1*mm)
-            pdf.line(a*mm,5*mm,a*mm,190*mm)
+            pdf.line(i*mm,5*mm,i*mm,190*mm)
             c+= 1
     c = 0
     for i in range(5,191) :
         if i%5 == 0 or c == 0 :
             pdf.setLineWidth(0.3*mm)
             pdf.line(3.5*mm,i*mm,293.5*mm,i*mm)
             c += 1
@@ -72,8 +73,8 @@
         a.circle(xc,yc,i*mm)
     a.line(xc,0,xc,b[3])
     a.line(0,yc,b[2],yc)
     for i in [30,40,60,120,130,150] :
         a.line(xc,yc,b[2],(xc*tan(i))+yc)
     a.save()
 
-milli()
+milli().save()
```

### Comparing `dahu12-0.0.0.0.2.1/DAHU/test.py` & `dahu12-0.0.0.0.2.2/DAHU/test.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,8 +1,9 @@
 import maths as ma
+from .cartes import Board as b
 
 # a = ma.Expression("2t+3",var="t")
 # b = ma.Expression("4t^3+6t", var="t")
 # d = ma.Expression("(y)/(x**2)",var=["t","y"])
 # e = ma.Expression("(4*t^2-1)/(t^3+1)",var="t")
 # f = ma.Expression("(4*t^3-t)/(t^3+1)",var="t")
 # print(e.deriv("t").simp())
@@ -34,8 +35,8 @@
 # print(h)
 
 # f = ma.Expression("e^(x^2-y)*(5-2*x+y)",var=["x","y"])
 # a = f.lim("x","+infinity")
 # print(a)
 
 a = ma.Polynôme([1,2,3],"t")
-print(a)
+print(a)
```

### Comparing `dahu12-0.0.0.0.2.1/LICENSE` & `dahu12-0.0.0.0.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `dahu12-0.0.0.0.2.1/README.md` & `dahu12-0.0.0.0.2.2/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -1,14 +1,14 @@
-# DAHU.py
+# DAHU.py (En cours de développement)
 ## _Package scientifique python_
 ***
 ## Auteurs : 
 - LOUVAT SEGURA Anthony
 - CHEMINOT Virgile
 
 ## Remerciements
 Nous souhaitons dans un premier temps remercier tous particulièrement notre professeur de mathématiques : Bernard Parisse, sans qui le projet ne serait pas là où il en est actuellement (faites un tour sur sa page personnel de l'université joseph fourrier).
-Il a nous permis d'utiliser sa création : le CAS Giac, sur qui est basé toute la gestion d'expression algébrique du package.
+Il a nous permis d'utiliser sa création : le CAS Giac, sur laquelle est basé toute la gestion d'expression algébrique du package.
 
 DAHU est une librairie python destiné aux étudiants et scientifiques, qui contient beaucoup de fonction leurs étant utile.
 
 Installation provisoire : https://pypi.org/project/DAHU12/
```

### Comparing `dahu12-0.0.0.0.2.1/pyproject.toml` & `dahu12-0.0.0.0.2.2/pyproject.toml`

 * *Files 24% similar despite different names*

```diff
@@ -1,21 +1,24 @@
 [tool.poetry]
 name = "DAHU12"
-version = "0.0.0.0.2.1"
+version = "0.0.0.0.2.2"
 description = "Package de calcul formel (pour l'instant ;=) )"
 authors = ["LOUVAT SEGURA Anthony","CHEMINOT Virgile"]
 license = "MIT"
 readme = "README.md"
 repository = "https://github.com/MoiCAntho/DAHU"
 packages = [
     {include = "DAHU"},]
 
 [tool.poetry.dependencies]
 python = "^3.7"
-giacpy = "0.7.1"
+giacpy = "^0.7.1"
+wheel = "^0.40.0"
+cython = "^0.29.35"
+
 
 [tool.poetry.urls]
 "Bug Tracker" = "https://github.com/MoiCAntho/DAHU/issues"
 
 
 
 [build-system]
```

### Comparing `dahu12-0.0.0.0.2.1/PKG-INFO` & `dahu12-0.0.0.0.2.2/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,35 +1,37 @@
 Metadata-Version: 2.1
 Name: dahu12
-Version: 0.0.0.0.2.1
+Version: 0.0.0.0.2.2
 Summary: Package de calcul formel (pour l'instant ;=) )
 Home-page: https://github.com/MoiCAntho/DAHU
 License: MIT
 Author: LOUVAT SEGURA Anthony
 Requires-Python: >=3.7,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Requires-Dist: giacpy (==0.7.1)
+Requires-Dist: cython (>=0.29.35,<0.30.0)
+Requires-Dist: giacpy (>=0.7.1,<0.8.0)
+Requires-Dist: wheel (>=0.40.0,<0.41.0)
 Project-URL: Bug Tracker, https://github.com/MoiCAntho/DAHU/issues
 Project-URL: Repository, https://github.com/MoiCAntho/DAHU
 Description-Content-Type: text/markdown
 
-# DAHU.py
+# DAHU.py (En cours de développement)
 ## _Package scientifique python_
 ***
 ## Auteurs : 
 - LOUVAT SEGURA Anthony
 - CHEMINOT Virgile
 
 ## Remerciements
 Nous souhaitons dans un premier temps remercier tous particulièrement notre professeur de mathématiques : Bernard Parisse, sans qui le projet ne serait pas là où il en est actuellement (faites un tour sur sa page personnel de l'université joseph fourrier).
-Il a nous permis d'utiliser sa création : le CAS Giac, sur qui est basé toute la gestion d'expression algébrique du package.
+Il a nous permis d'utiliser sa création : le CAS Giac, sur laquelle est basé toute la gestion d'expression algébrique du package.
 
 DAHU est une librairie python destiné aux étudiants et scientifiques, qui contient beaucoup de fonction leurs étant utile.
 
 Installation provisoire : https://pypi.org/project/DAHU12/
```

