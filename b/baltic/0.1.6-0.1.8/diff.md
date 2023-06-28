# Comparing `tmp/baltic-0.1.6.tar.gz` & `tmp/baltic-0.1.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/baltic-0.1.6.tar", last modified: Sat Feb 27 15:07:21 2021, max compression
+gzip compressed data, was "baltic-0.1.8.tar", last modified: Wed Jun 28 05:55:19 2023, max compression
```

## Comparing `baltic-0.1.6.tar` & `baltic-0.1.8.tar`

### file list

```diff
@@ -1,32 +1,31 @@
-drwxr-xr-x   0 evogytis   (501) staff       (20)        0 2021-02-27 15:07:21.003956 baltic-0.1.6/
--rw-r--r--   0 evogytis   (501) staff       (20)     5542 2020-05-08 13:28:20.000000 baltic-0.1.6/CODE_OF_CONDUCT.md
--rw-r--r--   0 evogytis   (501) staff       (20)     1683 2020-08-14 08:11:37.000000 baltic-0.1.6/CONTRIBUTING.md
--rw-r--r--   0 evogytis   (501) staff       (20)    35149 2020-05-08 13:28:20.000000 baltic-0.1.6/LICENSE
--rw-r--r--   0 evogytis   (501) staff       (20)       70 2020-08-18 13:15:07.000000 baltic-0.1.6/MANIFEST.in
--rw-r--r--   0 evogytis   (501) staff       (20)     2159 2021-02-27 15:07:21.003377 baltic-0.1.6/PKG-INFO
--rw-r--r--   0 evogytis   (501) staff       (20)     1343 2020-11-18 14:14:51.000000 baltic-0.1.6/README.md
-drwxr-xr-x   0 evogytis   (501) staff       (20)        0 2021-02-27 15:07:20.917366 baltic-0.1.6/baltic/
--rw-r--r--   0 evogytis   (501) staff       (20)       22 2020-07-28 11:23:30.000000 baltic-0.1.6/baltic/__init__.py
--rw-r--r--   0 evogytis   (501) staff       (20)    73674 2021-02-27 13:59:20.000000 baltic-0.1.6/baltic/baltic.py
--rw-r--r--   0 evogytis   (501) staff       (20)    10242 2020-11-18 14:14:51.000000 baltic-0.1.6/baltic/baltic_utils.py
--rw-r--r--   0 evogytis   (501) staff       (20)    21925 2020-05-15 06:47:03.000000 baltic-0.1.6/baltic/samogitia.py
-drwxr-xr-x   0 evogytis   (501) staff       (20)        0 2021-02-27 15:07:20.922330 baltic-0.1.6/baltic.egg-info/
--rw-r--r--   0 evogytis   (501) staff       (20)     2159 2021-02-27 15:07:20.000000 baltic-0.1.6/baltic.egg-info/PKG-INFO
--rw-r--r--   0 evogytis   (501) staff       (20)      558 2021-02-27 15:07:20.000000 baltic-0.1.6/baltic.egg-info/SOURCES.txt
--rw-r--r--   0 evogytis   (501) staff       (20)        1 2021-02-27 15:07:20.000000 baltic-0.1.6/baltic.egg-info/dependency_links.txt
--rw-r--r--   0 evogytis   (501) staff       (20)        1 2021-02-27 15:07:20.000000 baltic-0.1.6/baltic.egg-info/not-zip-safe
--rw-r--r--   0 evogytis   (501) staff       (20)       30 2021-02-27 15:07:20.000000 baltic-0.1.6/baltic.egg-info/requires.txt
--rw-r--r--   0 evogytis   (501) staff       (20)        7 2021-02-27 15:07:20.000000 baltic-0.1.6/baltic.egg-info/top_level.txt
--rw-r--r--   0 evogytis   (501) staff       (20)       66 2020-11-18 14:14:51.000000 baltic-0.1.6/requirements.txt
--rw-r--r--   0 evogytis   (501) staff       (20)       38 2021-02-27 15:07:21.004709 baltic-0.1.6/setup.cfg
--rw-r--r--   0 evogytis   (501) staff       (20)      885 2020-12-31 10:22:20.000000 baltic-0.1.6/setup.py
-drwxr-xr-x   0 evogytis   (501) staff       (20)        0 2021-02-27 15:07:20.922930 baltic-0.1.6/tests/
-drwxr-xr-x   0 evogytis   (501) staff       (20)        0 2021-02-27 15:07:20.981537 baltic-0.1.6/tests/data/
-drwxr-xr-x   0 evogytis   (501) staff       (20)        0 2021-02-27 15:07:21.000456 baltic-0.1.6/tests/data/2020-04-13_treetime/
--rw-r--r--   0 evogytis   (501) staff       (20)    73234 2020-05-15 06:47:03.000000 baltic-0.1.6/tests/data/2020-04-13_treetime/divergence_tree.nexus
--rw-r--r--   0 evogytis   (501) staff       (20)    72774 2020-05-15 06:47:03.000000 baltic-0.1.6/tests/data/2020-04-13_treetime/timetree.nexus
--rw-r--r--   0 evogytis   (501) staff       (20)   272511 2020-11-18 14:14:51.000000 baltic-0.1.6/tests/data/MERS.mcc.tree
--rw-r--r--   0 evogytis   (501) staff       (20)   222372 2020-11-18 14:14:51.000000 baltic-0.1.6/tests/data/miniFluB.mcc.tree
--rw-r--r--   0 evogytis   (501) staff       (20)  2925238 2020-05-15 06:47:03.000000 baltic-0.1.6/tests/data/zika.fa
--rw-r--r--   0 evogytis   (501) staff       (20)    32588 2020-05-15 06:47:03.000000 baltic-0.1.6/tests/data/zika.nwk
--rw-r--r--   0 evogytis   (501) staff       (20)     2002 2020-11-18 14:14:51.000000 baltic-0.1.6/tests/testsuite.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:55:19.034625 baltic-0.1.8/
+-rw-r--r--   0 runner    (1001) docker     (123)     5542 2023-06-28 05:55:05.000000 baltic-0.1.8/CODE_OF_CONDUCT.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1683 2023-06-28 05:55:05.000000 baltic-0.1.8/CONTRIBUTING.md
+-rw-r--r--   0 runner    (1001) docker     (123)    35149 2023-06-28 05:55:05.000000 baltic-0.1.8/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-28 05:55:05.000000 baltic-0.1.8/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     1804 2023-06-28 05:55:19.034625 baltic-0.1.8/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1343 2023-06-28 05:55:05.000000 baltic-0.1.8/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:55:19.026625 baltic-0.1.8/baltic/
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 05:55:05.000000 baltic-0.1.8/baltic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    74525 2023-06-28 05:55:05.000000 baltic-0.1.8/baltic/baltic.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21925 2023-06-28 05:55:05.000000 baltic-0.1.8/baltic/samogitia.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:55:19.026625 baltic-0.1.8/baltic.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1804 2023-06-28 05:55:18.000000 baltic-0.1.8/baltic.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      535 2023-06-28 05:55:18.000000 baltic-0.1.8/baltic.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 05:55:18.000000 baltic-0.1.8/baltic.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 05:55:18.000000 baltic-0.1.8/baltic.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 05:55:18.000000 baltic-0.1.8/baltic.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 05:55:18.000000 baltic-0.1.8/baltic.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       66 2023-06-28 05:55:05.000000 baltic-0.1.8/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 05:55:19.034625 baltic-0.1.8/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      883 2023-06-28 05:55:05.000000 baltic-0.1.8/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:55:19.026625 baltic-0.1.8/tests/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:55:19.030625 baltic-0.1.8/tests/data/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:55:19.034625 baltic-0.1.8/tests/data/2020-04-13_treetime/
+-rw-r--r--   0 runner    (1001) docker     (123)    73234 2023-06-28 05:55:05.000000 baltic-0.1.8/tests/data/2020-04-13_treetime/divergence_tree.nexus
+-rw-r--r--   0 runner    (1001) docker     (123)    72774 2023-06-28 05:55:05.000000 baltic-0.1.8/tests/data/2020-04-13_treetime/timetree.nexus
+-rw-r--r--   0 runner    (1001) docker     (123)   272511 2023-06-28 05:55:05.000000 baltic-0.1.8/tests/data/MERS.mcc.tree
+-rw-r--r--   0 runner    (1001) docker     (123)   222372 2023-06-28 05:55:05.000000 baltic-0.1.8/tests/data/miniFluB.mcc.tree
+-rw-r--r--   0 runner    (1001) docker     (123)  2925238 2023-06-28 05:55:05.000000 baltic-0.1.8/tests/data/zika.fa
+-rw-r--r--   0 runner    (1001) docker     (123)    32588 2023-06-28 05:55:05.000000 baltic-0.1.8/tests/data/zika.nwk
+-rw-r--r--   0 runner    (1001) docker     (123)     2157 2023-06-28 05:55:05.000000 baltic-0.1.8/tests/testsuite.py
```

### Comparing `baltic-0.1.6/CODE_OF_CONDUCT.md` & `baltic-0.1.8/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/CONTRIBUTING.md` & `baltic-0.1.8/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/LICENSE` & `baltic-0.1.8/LICENSE`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/README.md` & `baltic-0.1.8/README.md`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/baltic/baltic.py` & `baltic-0.1.8/baltic/baltic.py`

 * *Files 3% similar despite different names*

```diff
@@ -136,15 +136,15 @@
         self.height=None ## height of tip
         self.parent=None ## parent
         self.traits={} ## trait dictionary
         self.x=None ## position of tip on x axis if the tip were to be plotted
         self.y=None ## position of tip on y axis if the tip were to be plotted
 
     def is_leaflike(self):
-        return True
+        return False
 
     def is_leaf(self):
         return True
 
     def is_node(self):
         return False
 
@@ -174,42 +174,42 @@
         """ Attaches a new node to current node. """
         new_node=node() ## new node instance
         new_node.index=i ## new node's index is the position along the tree string
         if self.root is None:
             self.root=new_node
 
         new_node.parent=self.cur_node ## new node's parent is current node
-        assert self.cur_node.branchType=='node', 'Attempted to add a child to a non-node object. Check if tip names have illegal characters like parentheses.'
+        assert self.cur_node.is_node(), 'Attempted to add a child to a non-node object. Check if tip names have illegal characters like parentheses.'
         self.cur_node.children.append(new_node) ## new node is a child of current node
         self.cur_node=new_node ## current node is now new node
         self.Objects.append(self.cur_node) ## add new node to list of objects in the tree
 
     def add_leaf(self,i,name):
         """ Attach a new leaf (tip) to current node. """
         new_leaf=leaf() ## new instance of leaf object
         new_leaf.index=i ## index is position along tree string
         if self.root is None: self.root=new_leaf
 
         new_leaf.parent=self.cur_node ## leaf's parent is current node
-        assert self.cur_node.branchType=='node', 'Attempted to add a child to a non-node object. Check if tip names have illegal characters like parentheses.'
+        assert self.cur_node.is_node(), 'Attempted to add a child to a non-node object. Check if tip names have illegal characters like parentheses.'
         self.cur_node.children.append(new_leaf) ## assign leaf to parent's children
         new_leaf.name=name
         self.cur_node=new_leaf ## current node is now new leaf
         self.Objects.append(self.cur_node) ## add leaf to all objects in the tree
 
     def subtree(self,k=None,traverse_condition=None,stem=True):
         """ Generate a subtree (as a baltic tree object) from a traversal.
             k is the starting branch for traversal (default: root).
             traverse_condition is a function that determines whether a child branch should be visited (default: always true).
             Returns a new baltic tree instance.
             Note - custom traversal functions can result in multitype trees.
             If this is undesired call singleType() on the resulting subtree afterwards. """
         subtree=copy.deepcopy(self.traverse_tree(k,include_condition=lambda k:True,traverse_condition=traverse_condition))
 
-        if subtree is None or len([k for k in subtree if k.branchType=='leaf'])==0:
+        if subtree is None or len([k for k in subtree if k.is_leaf()])==0:
             return None
         else:
             local_tree=tree() ## create a new tree object where the subtree will be
             local_tree.Objects=subtree ## assign branches to new tree object
 
             local_tree.root=subtree[0] ## root is the beginning of the traversal
 
@@ -230,17 +230,17 @@
             if self.tipMap: ## if original tree has a tipMap dictionary
                 local_tree.tipMap={tipNum: self.tipMap[tipNum] for tipNum in self.tipMap if self.tipMap[tipNum] in [w.name for w in local_tree.getExternal()]} ## copy over the relevant tip translations
 
             return local_tree
 
     def singleType(self):
         """ Removes any branches with a single child (multitype nodes). """
-        multiTypeNodes=[k for k in self.Objects if k.branchType=='node' and len(k.children)==1]
+        multiTypeNodes=[k for k in self.Objects if k.is_node() and len(k.children)==1]
         while len(multiTypeNodes)>0:
-            multiTypeNodes=[k for k in self.Objects if k.branchType=='node' and len(k.children)==1]
+            multiTypeNodes=[k for k in self.Objects if k.is_node() and len(k.children)==1]
 
             for k in sorted(multiTypeNodes,key=lambda x:-x.height):
                 child=k.children[0] ## fetch child
                 grandparent=k.parent if k.parent.index else self.root ## fetch grandparent
 
                 child.parent=grandparent ## child's parent is now grandparent
                 grandparent.children.append(child) ## add child to grandparent's children
@@ -295,67 +295,76 @@
     def traverse_tree(self,cur_node=None,include_condition=None,traverse_condition=None,collect=None,verbose=False):
         if cur_node==None: ## if no starting point defined - start from root
             if verbose==True: print('Initiated traversal from root')
             cur_node=self.root
 
             if traverse_condition==None and include_condition==None: ## reset heights if traversing from scratch
                 for k in self.Objects: ## reset various parameters
-                    if k.branchType=='node':
+                    if k.is_node():
                         k.leaves=set()
                         k.childHeight=None
                     k.height=None
 
         if traverse_condition==None: traverse_condition=lambda k: True
-        if include_condition==None: include_condition=lambda k: k.branchType=='leaf'
+        if include_condition==None: include_condition=lambda k: k.is_leaf()
 
         if collect==None: ## initiate collect list if not initiated
             collect=[]
 
         if cur_node.parent and cur_node.height==None: ## cur_node has a parent - set height if it doesn't have it already
             cur_node.height=cur_node.length+cur_node.parent.height
         elif cur_node.height==None: ## cur_node does not have a parent (root), if height not set before it's zero
             cur_node.height=0.0
 
         if verbose==True: print('at %s (%s)'%(cur_node.index,cur_node.branchType))
 
         if include_condition(cur_node): ## test if interested in cur_node
             collect.append(cur_node) ## add to collect list for reporting later
 
-        if cur_node.branchType=='leaf' and self.root!=cur_node: ## cur_node is a tip (and tree is not single tip)
+        if cur_node.is_leaf() and self.root!=cur_node: ## cur_node is a tip (and tree is not single tip)
             cur_node.parent.leaves.add(cur_node.name) ## add to parent's list of tips
 
-        elif cur_node.branchType=='node': ## cur_node is node
+        elif cur_node.is_node(): ## cur_node is node
             for child in filter(traverse_condition,cur_node.children): ## only traverse through children we're interested
                 if verbose==True: print('visiting child %s'%(child.index))
                 self.traverse_tree(cur_node=child,include_condition=include_condition,traverse_condition=traverse_condition,verbose=verbose,collect=collect) ## recurse through children
                 if verbose==True: print('child %s done'%(child.index))
             assert len(cur_node.children)>0, 'Tried traversing through hanging node without children. Index: %s'%(cur_node.index)
-            cur_node.childHeight=max([child.childHeight if child.branchType=='node' else child.height for child in cur_node.children])
+            cur_node.childHeight=max([child.childHeight if child.is_node() else child.height for child in cur_node.children])
 
             if cur_node.parent:
                 cur_node.parent.leaves=cur_node.parent.leaves.union(cur_node.leaves) ## pass tips seen during traversal to parent
             self.treeHeight=cur_node.childHeight ## it's the highest child of the starting node
         return collect
 
+
     def renameTips(self,d=None):
         """ Give each tip its correct label using a dictionary. """
         if d==None and self.tipMap!=None:
             d=self.tipMap
         for k in self.getExternal(): ## iterate through leaf objects in tree
             # k.name=d[k.numName] ## change its name
             k.name=d[k.name] ## change its name
 
-    def sortBranches(self,descending=True,sort_function=None):
-        """ Sort descendants of each node. """
-        mod=-1 if descending else 0
+    def sortBranches(self,descending=True,sort_function=None,sortByHeight=True):
+        mod=-1 if descending else 1
         if sort_function==None: sort_function=lambda k: (k.is_node(),-len(k.leaves)*mod,k.length*mod) if k.is_node() else (k.is_node(),k.length*mod)
+        if sortByHeight: # Sort nodes by height and group nodes and leaves together
+            """ Sort descendants of each node. """
 
-        for k in self.getInternal(): ## iterate over nodes
-            k.children=sorted(k.children,key=sort_function)
-
+            for k in self.getInternal(): ## iterate over nodes
+                k.children=sorted(k.children,key=sort_function)
+        else: # Do not sort by height. Retain leaves at original positions. Only sort nodes
+            for k in self.getInternal():
+                leavesIdx = [(i,ctr) for ctr, i in enumerate(k.children) if i.branchType=="leaf"] # Get original indices of leaves
+                nodes=sorted([x for x in k.children if x.branchType=='node'],key=sort_function) # Sort nodes only by number of descendants
+                children = nodes
+                for i in leavesIdx: # Insert leaves back into same positions
+                    children.insert(i[1], i[0])
+                k.children = children
         self.drawTree() ## update x and y positions of each branch, since y positions will have changed because of sorting
 
     def drawTree(self,order=None,width_function=None,pad_nodes=None,verbose=False):
         """ Find x and y coordinates of each branch. """
         if order==None:
             order=self.traverse_tree() ## order is a list of tips recovered from a tree traversal to make sure they're plotted in the correct order along the vertical tree dimension
             if verbose==True: print('Drawing tree in pre-order')
@@ -412,67 +421,62 @@
                     x=k.height ## x position is height
                     children_y_coords=[q.y for q in k.children if q.y!=None] ## get all existing y coordinates of the node
                     y=sum(children_y_coords)/float(len(children_y_coords)) ## internal branch is in the middle of the vertical bar
                     k.x=x
                     k.y=y
                     drawn[k.index]=None ## remember that this objects has been drawn
                     if verbose==True: print('%s (%s branches drawn)'%(k.y,len(drawn)))
-                    minYrange=min([min(child.yRange) if child.branchType=='node' else child.y for child in k.children]) ## get lowest y coordinate across children
-                    maxYrange=max([max(child.yRange) if child.branchType=='node' else child.y for child in k.children]) ## get highest y coordinate across children
+                    minYrange=min([min(child.yRange) if child.is_node() else child.y for child in k.children]) ## get lowest y coordinate across children
+                    maxYrange=max([max(child.yRange) if child.is_node() else child.y for child in k.children]) ## get highest y coordinate across children
                     setattr(k,'yRange',[minYrange,maxYrange]) ## assign the maximum extent of children's y coordinates
 
             if len(self.Objects)>len(drawn):
                 assert len(drawn)>storePlotted,'Got stuck trying to find y positions of objects (%d branches drawn this iteration, %d branches during previous iteration out of %d total)'%(len(drawn),storePlotted,len(tree.Objects))
             storePlotted=len(drawn) ## remember how many branches were drawn this iteration
 
         yvalues=[k.y for k in self.Objects] ## all y values
         self.ySpan=max(yvalues)-min(yvalues)+min(yvalues)*2 ## determine appropriate y axis span of tree
 
-        if self.root.branchType=='node':
+        if self.root.is_node():
             self.root.x=min([q.x-q.length for q in self.root.children if q.x!=None]) ## set root x and y coordinates
             children_y_coords=[q.y for q in self.root.children if q.y!=None]
             self.root.y=sum(children_y_coords)/float(len(children_y_coords))
         else:
             self.root.x=self.root.length
 
-    def drawUnrooted(self,n=None,total=None):
+    def drawUnrooted(self,rotate=0.0,n=None,total=None):
         """
         Calculate x and y coordinates in an unrooted arrangement.
         Code translated from https://github.com/nextstrain/auspice/commit/fc50bbf5e1d09908be2209450c6c3264f298e98c, written by Richard Neher.
         """
         if n==None:
-            total=sum([1 if isinstance(x,leaf) else x.width+1 for x in self.getExternal()])
+            total=sum([1 if x.is_leaf() else x.width+1 for x in self.getExternal()])
             n=self.root#.children[0]
             for k in self.Objects:
-                k.traits['tau']=0.0
+                k.traits['tau']=2*math.pi*rotate
                 k.x=0.0
                 k.y=0.0
 
-        if n.branchType=='leaf':
-            w=2*math.pi*1.0/float(total)
-        else:
-            w=2*math.pi*len(n.leaves)/float(total)
+        w=2*math.pi*1.0/float(total) if n.is_leaf() else 2*math.pi*len(n.leaves)/float(total)
 
         if n.parent.x==None:
             n.parent.x=0.0
             n.parent.y=0.0
 
         n.x = n.parent.x + n.length * math.cos(n.traits['tau'] + w*0.5)
         n.y = n.parent.y + n.length * math.sin(n.traits['tau'] + w*0.5)
         eta=n.traits['tau']
 
-        if n.branchType=='node':
+        if n.is_node():
             for ch in n.children:
-                if ch.branchType=='leaf':
-                    w=2*math.pi*1.0/float(total)
-                else:
-                    w=2*math.pi*len(ch.leaves)/float(total)
+                w=2*math.pi*1.0/float(total) if ch.is_leaf() else 2*math.pi*len(ch.leaves)/float(total)
+
                 ch.traits['tau'] = eta
                 eta += w
-                self.drawUnrooted(ch,total)
+                self.drawUnrooted(rotate,ch,total)
 
     def commonAncestor(self,descendants,strict=False):
         """
         Find the most recent node object that gave rise to a given list of descendant branches.
         """
         assert len(descendants)>1,'Not enough descendants to find common ancestor: %d'%(len(descendants))
         paths_to_root={k.index: set() for k in descendants} ## for every descendant create an empty set
@@ -482,15 +486,15 @@
                 paths_to_root[k.index].add(cur_node) ## remember every node visited along the way
                 cur_node=cur_node.parent ## descend
 
         return sorted(reduce(set.intersection,paths_to_root.values()),key=lambda k: k.height)[-1] ## return the most recent branch that is shared across all paths to root
 
     def collapseSubtree(self,cl,givenName,verbose=False,widthFunction=lambda k:len(k.leaves)):
         """ Collapse an entire subtree into a clade object. """
-        assert cl.branchType=='node','Cannot collapse non-node class'
+        assert cl.is_node(),'Cannot collapse non-node class'
         collapsedClade=clade(givenName)
         collapsedClade.index=cl.index
         collapsedClade.leaves=cl.leaves
         collapsedClade.length=cl.length
         collapsedClade.height=cl.height
         collapsedClade.parent=cl.parent
         collapsedClade.absoluteTime=cl.absoluteTime
@@ -538,15 +542,15 @@
     def collapseBranches(self,collapseIf=lambda x:x.traits['posterior']<=0.5,designated_nodes=[],verbose=False):
         """ Collapse all branches that satisfy a function collapseIf (default is an anonymous function that returns true if posterior probability is <=0.5).
             Alternatively, a list of nodes can be supplied to the script.
             Returns a deep copied version of the tree.
         """
         newTree=copy.deepcopy(self) ## work on a copy of the tree
         if len(designated_nodes)==0: ## no nodes were designated for deletion - relying on anonymous function to collapse nodes
-            nodes_to_delete=list(filter(lambda n: n.branchType=='node' and collapseIf(n)==True and n!=newTree.root, newTree.Objects)) ## fetch a list of all nodes who are not the root and who satisfy the condition
+            nodes_to_delete=list(filter(lambda n: n.is_node() and collapseIf(n)==True and n!=newTree.root, newTree.Objects)) ## fetch a list of all nodes who are not the root and who satisfy the condition
         else:
             assert [w.branchType for w in designated_nodes].count('node')==len(designated_nodes),'Non-node class detected in list of nodes designated for deletion'
             assert len([w for w in designated_nodes if w!=newTree.root])==0,'Root node was designated for deletion'
 
             nodes_to_delete=list(filter(lambda w: w.index in [q.index for q in designated_nodes], newTree.Objects)) ## need to look up nodes designated for deletion by their indices, since the tree has been copied and nodes will have new memory addresses
         if verbose==True: print('%s nodes set for collapsing: %s'%(len(nodes_to_delete),[w.index for w in nodes_to_delete]))
         assert len(nodes_to_delete)<len(newTree.getInternal())-1,'Chosen cutoff would remove all branches'
@@ -568,15 +572,15 @@
                         if verbose==True: print('Fixing branch length for node %s'%(w.index))
                 k.parent.children.remove(k) ## remove traces of deleted node - it doesn't exist as a child, doesn't exist in the tree and doesn't exist in the nodes list
                 newTree.Objects.remove(k)
 
                 nodes_to_delete.remove(k) ## in fact, the node never existed
 
                 if len(designated_nodes)==0:
-                    nodes_to_delete==list(filter(lambda n: n.branchType=='node' and collapseIf(n)==True and n!=newTree.root, newTree.Objects))
+                    nodes_to_delete==list(filter(lambda n: n.is_node() and collapseIf(n)==True and n!=newTree.root, newTree.Objects))
                 else:
                     assert [w.branchType for w in designated_nodes].count('node')==len(designated_nodes),'Non-node class detected in list of nodes designated for deletion'
                     assert len([w for w in designated_nodes if w!=newTree.root])==0,'Root node was designated for deletion'
                     nodes_to_delete=[w for w in newTree.Objects if w.index in [q.index for q in designated_nodes]]
 
                 if verbose==True: print('Removing references to node %s'%(k.index))
         newTree.sortBranches() ## sort the tree to traverse, draw and sort tree to adjust y coordinates
@@ -615,31 +619,33 @@
                     elif isinstance(cur_node.traits[tr],list): ## lists
                         rangeComment=[]
                         for val in cur_node.traits[tr]:
                             if isinstance(val,str): ## string
                                 rangeComment.append('"%s"'%(val))
                             elif isinstance(val,float) or isinstance(val,int): ## float or integer
                                 rangeComment.append('%s'%(val))
+                            elif isinstance(val, list): ## list of lists, example complete history annotated on tree
+                                rangeComment.append("{{{}}}".format(",".join(val)))
                         comment.append('%s={%s}'%(tr,','.join(rangeComment)))
                         if verbose==True: print('adding range comment %s'%(comment[-1]))
                 elif verbose==True: print('trait %s unavailable for %s (%s)'%(tr,cur_node.index,cur_node.branchType))
 
-        if cur_node.branchType=='node':
+        if cur_node.is_node():
             if verbose==True: print('node: %s'%(cur_node.index))
             string_fragment.append('(')
             traverseChildren=list(filter(traverse_condition,cur_node.children))
             assert len(traverseChildren)>0,'Node %s does not have traversable children'%(cur_node.index)
             for c,child in enumerate(traverseChildren): ## iterate through children of node if they satisfy traverse condition
                 if verbose==True: print('moving to child %s of node %s'%(child.index,cur_node.index))
                 self.toString(cur_node=child,traits=traits,verbose=verbose,nexus=nexus,string_fragment=string_fragment,traverse_condition=traverse_condition,rename=rename,quotechar=quotechar)
                 if (c+1)<len(traverseChildren): ## not done with children, add comma for next iteration
                     string_fragment.append(',')
             string_fragment.append(')') ## last child, node terminates
 
-        elif cur_node.branchType=='leaf':
+        elif cur_node.is_leaf():
             if rename==None:
                 treeName=cur_node.name ## designated numName
             else:
                 assert isinstance(rename,dict), 'Variable "rename" is not a dictionary'
                 assert cur_node.name in rename, 'Tip name %s not in rename dictionary'%(cur_node.name)
                 treeName=rename[cur_node.name]
 
@@ -678,30 +684,30 @@
 
     def reduceTree(self,keep,verbose=False):
         """
         Reduce the tree to just those tracking a small number of tips.
         Returns a new baltic tree object.
         """
         assert len(keep)>0,"No tips given to reduce the tree to."
-        assert len([k for k in keep if k.branchType!='leaf'])==0, "Embedding contains %d non-leaf branches."%(len([k for k in keep if k.branchType!='leaf']))
+        assert len([k for k in keep if not k.is_leaf()])==0, "Embedding contains %d non-leaf branches."%(len([k for k in keep if k.is_leaf()==False]))
         if verbose==True: print("Preparing branch hash for keeping %d branches"%(len(keep)))
         branch_hash={k.index:k for k in keep}
         embedding=[]
         if verbose==True: print("Deep copying tree")
         reduced_tree=copy.deepcopy(self) ## new tree object
         for k in reduced_tree.Objects: ## deep copy branches from current tree
             if k.index in branch_hash: ## if branch is designated as one to keep
                 cur_b=k
                 if verbose==True: print("Traversing to root from %s"%(cur_b.index))
                 while cur_b!=reduced_tree.root: ## descend to root
                     if verbose==True: print("at %s root: %s"%(cur_b.index,cur_b==reduced_tree.root))
                     embedding.append(cur_b) ## keep track of the path to root
                     cur_b=cur_b.parent
         embedding.append(reduced_tree.root) ## add root to embedding
-        if verbose==True: print("Finished extracting embedding with %s branches (%s tips, %s nodes)"%(len(embedding),len([w for w in embedding if w.branchType=='leaf']),len([w for w in embedding if w.branchType=='node'])))
+        if verbose==True: print("Finished extracting embedding with %s branches (%s tips, %s nodes)"%(len(embedding),len([w for w in embedding if w.is_leaf()]),len([w for w in embedding if w.is_node()])))
         embedding=set(embedding) ## prune down to only unique branches
 
         reduced_tree.Objects=sorted(list(embedding),key=lambda x:x.height) ## assign branches that are kept to new tree's Objects
         if verbose==True: print("Pruning untraversed lineages")
         for k in reduced_tree.getInternal(): ## iterate through reduced tree
             k.children = [c for c in k.children if c in embedding] ## only keep children that are present in lineage traceback
         reduced_tree.root.children=[c for c in reduced_tree.root.children if c in embedding] ## do the same for root
@@ -718,23 +724,23 @@
         return len([k for k in self.Objects if getattr(k.parent,attr)!=None and getattr(k.parent,attr)<t<=getattr(k,attr) and condition(k)])
 
     def getExternal(self,secondFilter=None):
         """
         Get all branches whose branchType is "leaf".
         A function can be provided to filter internal nodes according to an additional property.
         """
-        externals=list(filter(secondFilter,filter(lambda k:k.branchType=='leaf',self.Objects)))
+        externals=list(filter(secondFilter,filter(lambda k: k.is_leaf(),self.Objects)))
         return externals
 
     def getInternal(self,secondFilter=None):
         """
         Get all branches whose branchType is "node".
         A function can be provided to filter internal nodes according to an additional property.
         """
-        internals=list(filter(secondFilter,filter(lambda k:k.branchType=='node',self.Objects)))
+        internals=list(filter(secondFilter,filter(lambda k: k.is_node(),self.Objects)))
         return internals
 
     def getBranches(self,attrs=lambda x:True,warn=True):
         select=list(filter(attrs,self.Objects))
 
         if len(select)==0 and warn==True:
             raise Exception('No branches satisfying function were found amongst branches')
@@ -761,38 +767,38 @@
             params=[k.traits[statistic] for k in branches if statistic in k.traits]
         return params
 
     def fixHangingNodes(self):
         """
         Remove internal nodes without any children.
         """
-        hangingCondition=lambda k:k.branchType=='node' and len(k.children)==0
+        hangingCondition=lambda k: k.is_node() and len(k.children)==0
         hangingNodes=list(filter(hangingCondition,self.Objects)) ## check for nodes without any children (hanging nodes)
         while len(hangingNodes)>0:
             for h in sorted(hangingNodes,key=lambda x:-x.height):
                 h.parent.children.remove(h) ## remove old parent from grandparent's children
                 hangingNodes.remove(h) ## remove old parent from multitype nodes
                 self.Objects.remove(h) ## remove old parent from all objects
             hangingNodes=list(filter(hangingCondition,self.Objects)) ## regenerate list
 
     def addText(self,ax,target=None,x_attr=None,y_attr=None,text=None,zorder=None,**kwargs):
-        if target==None: target=lambda k: k.branchType=='leaf'
+        if target==None: target=lambda k: k.is_leaf()
         if x_attr==None: x_attr=lambda k: k.x
         if y_attr==None: y_attr=lambda k: k.y
         if text==None: text=lambda k: k.name
         if zorder==None: zorder=4
         for k in filter(target,self.Objects):
             x,y=x_attr(k),y_attr(k)
             z=zorder
             ax.text(x,y,text(k),zorder=z,**kwargs)
         return ax
 
     def plotPoints(self,ax,x_attr=None,y_attr=None,target=None,size=None,colour=None,
                zorder=None,outline=None,outline_size=None,outline_colour=None,**kwargs):
-        if target==None: target=lambda k: k.branchType=='leaf'
+        if target==None: target=lambda k: k.is_leaf()
         if x_attr==None: x_attr=lambda k:k.x
         if y_attr==None: y_attr=lambda k:k.y
         if size==None: size=40
         if colour==None: colour=lambda f:'k'
         if zorder==None: zorder=3
 
         if outline==None: outline=True
@@ -849,29 +855,30 @@
                 colours.append(colour(k)) if callable(colour) else colours.append(colour)
             except KeyError:
                 colours.append((0.7,0.7,0.7))
             linewidths.append(width(k)) if callable(width) else linewidths.append(width)
 
             if connection_type=='baltic':
                 branches.append(((xp,y),(x,y)))
-                if k.branchType=='node':
+                if k.is_node():
                     yl,yr=y_attr(k.children[0]),y_attr(k.children[-1])
                     branches.append(((x,yl),(x,yr)))
                     linewidths.append(linewidths[-1])
                     colours.append(colours[-1])
             elif connection_type=='elbow':
                 yp=y_attr(k.parent) if k.parent else y ## get parent x position
                 branches.append(((xp,yp),(xp,y),(x,y)))
             elif connection_type=='direct':
                 yp=y_attr(k.parent) ## get y position
                 branches.append(((xp,yp),(x,y)))
             else:
                 pass ## for now
 
-        line_segments = LineCollection(branches,lw=linewidths,color=colours,capstyle='projecting',**kwargs)
+        if 'capstyle' not in kwargs: kwargs['capstyle']='projecting'
+        line_segments = LineCollection(branches,lw=linewidths,color=colours,**kwargs)
         ax.add_collection(line_segments)
         return ax
 
     def plotCircularTree(self,ax,target=None,x_attr=None,y_attr=None,width=None,colour=None,
                          circStart=0.0,circFrac=1.0,inwardSpace=0.0,normaliseHeight=None,precision=15,**kwargs):
 
         if target==None: target=lambda k: True
@@ -905,15 +912,15 @@
             linewidths.append(width(k)) if callable (width) else linewidths.append(width)
 
             y=circ_s+circ*y/self.ySpan
             X=math.sin(y)
             Y=math.cos(y)
             branches.append(((X*xp,Y*xp),(X*x,Y*x)))
 
-            if k.branchType=='node':
+            if k.is_node():
                 yl,yr=y_attr(k.children[0]),y_attr(k.children[-1]) ## get leftmost and rightmost children's y coordinates
                 yl=circ_s+circ*yl/self.ySpan ## transform y into a fraction of total y
                 yr=circ_s+circ*yr/self.ySpan
                 ybar=linspace(yl,yr,precision) ## what used to be vertical node bar is now a curved line
 
                 xs=[yx*x for yx in map(math.sin,ybar)] ## convert to polar coordinates
                 ys=[yy*x for yy in map(math.cos,ybar)]
@@ -925,15 +932,15 @@
 
         line_segments = LineCollection(branches,lw=linewidths,ls='-',color=colours,capstyle='projecting',zorder=1) ## create line segments
         ax.add_collection(line_segments) ## add collection to axes
         return ax
 
     def plotCircularPoints(self,ax,x_attr=None,y_attr=None,target=None,size=None,colour=None,circStart=0.0,circFrac=1.0,inwardSpace=0.0,normaliseHeight=None,
                zorder=None,outline=None,outline_size=None,outline_colour=None,**kwargs):
-        if target==None: target=lambda k: k.branchType=='leaf'
+        if target==None: target=lambda k: k.is_leaf()
         if x_attr==None: x_attr=lambda k:k.x
         if y_attr==None: y_attr=lambda k:k.y
         if size==None: size=40
         if colour==None: colour='k'
         if zorder==None: zorder=3
 
         if outline==None: outline=True
@@ -1004,15 +1011,15 @@
             if verbose: print('%d vs %d'%(cur,nex))
             for k in sorted(tree2.getInternal(),key=lambda branch: branch.height): ## iterate through nodes of next tree by height (start from root)
                 clade_y_positions=sorted([y_positions[tree2][tip] for tip in k.leaves]) ## sorted list of available y coordinates for node
                 costs={} ## will store cost of all children permutations
                 if len(k.children)>=10: raise RuntimeWarning('Node is too polytomic and untangling will take an astronomically long time')
                 if verbose==True: print(len(k.children))
                 for permutation in permutations(k.children): ## iterate over permutations of node's children
-                    clade_order=sum([[child.name] if child.branchType=='leaf' else list(child.leaves) for child in permutation],[]) ## flat list of tip names as they would appear in permutation order
+                    clade_order=sum([[child.name] if child.is_leaf() else list(child.leaves) for child in permutation],[]) ## flat list of tip names as they would appear in permutation order
                     new_y_positions={clade_order[i]: clade_y_positions[i] for i in range(len(clade_y_positions))} ## assign available y positions in order
 
                     tip_costs=list(map(cost_function,[(y_positions[tree1][tip],new_y_positions[tip]) for tip in clade_order if tip in y_positions[tree1]]))
                     costs[permutation]=sum(tip_costs)/len(tip_costs) ## compute cost of this permutation in relation to next tree
 
                 best=sorted(costs.keys(),key=lambda w: -costs[w])[0] ## get tree with smallest cost
                 k.children=list(best) ## reorder children according to minimised cost
@@ -1058,20 +1065,20 @@
 
         cerberus=re.match(patterns['non_beast_tip'],data[i-1:i+200])  ## look for tips with unencoded names - if the tips have some unusual format you'll have to modify this
         if cerberus is not None:
             if verbose==True: print('%d adding leaf (non-BEAST) %s'%(i,cerberus.group(3)))
             ll.add_leaf(i,cerberus.group(3).strip('"').strip("'"))  ## add tip
             i+=len(cerberus.group(3))+cerberus.group().count("'")+cerberus.group().count('"') ## advance in tree string by however many characters the tip is encoded
 
-        cerberus=re.match('\)([0-9]+)\[',data[i-1:i+100]) ## look for multitype tree singletons.
+        cerberus=re.match(r'\)([0-9]+)\[',data[i-1:i+100]) ## look for multitype tree singletons.
         if cerberus is not None:
             if verbose==True: print('%d adding multitype node %s'%(i,cerberus.group(1)))
             i+=len(cerberus.group(1))
 
-        cerberus=re.match('[\(,](#[A-Za-z0-9]+)',data[i-1:i+200]) ## look for beginning of reticulate branch
+        cerberus=re.match(r'[\(,](#[A-Za-z0-9]+)',data[i-1:i+200]) ## look for beginning of reticulate branch
         if cerberus is not None:
             if verbose==True: print('%d adding outgoing reticulation branch %s'%(i,cerberus.group(1)))
             ll.add_reticulation(cerberus.group(1)) ## add reticulate branch
 
             destination=None
             for k in ll.Objects: ## iterate over branches parsed so far
                 if 'label' in k.traits and k.traits['label']==cerberus.group(1): ## if there's a branch with a matching id
@@ -1083,15 +1090,15 @@
                 if verbose==True: print('identified %s destination'%(cerberus.group(1)))
                 ll.cur_node.target=destination ## set current node's target as the destination
                 setattr(destination,"contribution",ll.cur_node) ## add contributing edge to destination
             else:
                 if verbose==True: print('destination of %s not identified yet'%(cerberus.group(1)))
             i+=len(cerberus.group())-1
 
-        cerberus=re.match('\)(#[A-Za-z0-9]+)',data[i-1:i+200]) ## look for landing point of reticulate branch
+        cerberus=re.match(r'\)(#[A-Za-z0-9]+)',data[i-1:i+200]) ## look for landing point of reticulate branch
         if cerberus is not None:
             if verbose==True: print('%d adding incoming reticulation branch %s'%(i,cerberus.group(1)))
             ll.cur_node.traits['label']=cerberus.group(1) ## set node label
 
             origin=None ## branch is landing, check if its origin was seen previously
             for k in ll.Objects: ## iterate over currently existing branches
                 if isinstance(k,reticulation) and k.name==cerberus.group(1): ## check if any reticulate branches match the origin
@@ -1103,15 +1110,15 @@
                 if verbose==True: print('identified %s origin'%(cerberus.group(1)))
                 origin.target=ll.cur_node ## set origin's landing at this node
                 setattr(ll.cur_node,"contribution",origin) ## add contributing edge to this node
             else:
                 if verbose==True: print('origin of %s not identified yet'%(cerberus.group(1)))
             i+=len(cerberus.group())-1
 
-        cerberus=re.match('(\:)*\[(&[A-Za-z\_\-{}\,0-9\.\%=\"\'\+!# :\/\(\)\&]+)\]',data[i:])## look for MCC comments
+        cerberus=re.match(r'(\:)*\[(&[A-Za-z\_\-{}\,0-9\.\%=\"\'\+!# :\/\(\)\&]+)\]',data[i:])## look for MCC comments
         if cerberus is not None:
             if verbose==True: print('%d comment: %s'%(i,cerberus.group(2)))
             comment=cerberus.group(2)
             numerics=re.findall('[,&][A-Za-z\_\.0-9]+=[0-9\-Ee\.]+',comment) ## find all entries that have values as floats
             strings=re.findall('[,&][A-Za-z\_\.0-9]+=["|\']*[A-Za-z\_0-9\.\+ :\/\(\)\&\-]+[\"|\']*',comment) ## strings
             treelist=re.findall('[,&][A-Za-z\_\.0-9]+={[A-Za-z\_,{}0-9\. :\/\(\)\&]+}',comment) ## complete history logged robust counting (MCMC trees)
             sets=re.findall('[,&][A-Za-z\_\.0-9\%]+={[A-Za-z\.\-0-9eE,\"\_ :\/\(\)\&]+}',comment) ## sets and ranges
@@ -1129,19 +1136,23 @@
                 tr=tr[1:]
                 if val.replace('E','',1).replace('e','',1).replace('-','',1).replace('.','',1).isdigit():
                     ll.cur_node.traits[tr]=float(val)
 
             for val in treelist:
                 tr,val=val.split('=')
                 tr=tr[1:]
-                microcerberus=re.findall('{([0-9]+,[0-9\.\-e]+,[A-Z]+,[A-Z]+)}',val)
+                microcerberus = []
+                if val.count(",") == 2:
+                    microcerberus=re.findall(r'{([0-9\.\-e]+,[a-z_A-Z]+,[a-z_A-Z]+)}',val)
+                elif val.count(",") == 3:
+                    microcerberus=re.findall(r'{([0-9]+,[0-9\.\-e]+,[A-Z]+,[A-Z]+)}',val)
                 ll.cur_node.traits[tr]=[]
                 for val in microcerberus:
-                    codon,timing,start,end=val.split(',')
-                    ll.cur_node.traits[tr].append((int(codon),float(timing),start,end))
+                    val_split = val.split(',')
+                    ll.cur_node.traits[tr].append(val.split(","))
 
             for vals in sets:
                 tr,val=vals.split('=')
                 tr=tr[1:]
                 if 'set' in tr:
                     ll.cur_node.traits[tr]=[]
                     for v in val[1:-1].split(','):
@@ -1156,22 +1167,22 @@
                         print('some other trait: %s'%(vals))
 
             if len(figtree)>0:
                 print('FigTree comment found, ignoring')
 
             i+=len(cerberus.group()) ## advance in tree string by however many characters it took to encode labels
 
-        cerberus=re.match('([A-Za-z\_\-0-9\.]+)(\:|\;)',data[i:])## look for old school node labels
+        cerberus=re.match(r'([A-Za-z\_\-0-9\.]+)(\:|\;)',data[i:])## look for old school node labels
         if cerberus is not None:
             if verbose==True: print('old school comment found: %s'%(cerberus.group(1)))
             ll.cur_node.traits['label']=cerberus.group(1)
 
             i+=len(cerberus.group(1))
 
-        microcerberus=re.match('(\:)*([0-9\.\-Ee]+)',data[i:i+100]) ## look for branch lengths without comments
+        microcerberus=re.match(r'(\:)*([0-9\.\-Ee]+)',data[i:i+100]) ## look for branch lengths without comments
         if microcerberus is not None:
             if verbose==True: print('adding branch length (%d) %.6f'%(i,float(microcerberus.group(2))))
             ll.cur_node.length=float(microcerberus.group(2)) ## set branch length of current node
             i+=len(microcerberus.group()) ## advance in tree string by however many characters it took to encode branch length
 
         if data[i] == ',' or data[i] == ')': ## look for bifurcations or clade ends
             i+=1 ## advance in tree string
@@ -1204,15 +1215,15 @@
 
     if 'children' in JSONnode:
         for child in JSONnode['children']:
             make_treeJSON(child,json_translation,ll)
             ll.cur_node=ll.cur_node.parent
     return ll
 
-def loadNewick(tree_path,tip_regex='\|([0-9]+\-[0-9]+\-[0-9]+)',date_fmt='%Y-%m-%d',variableDate=True,absoluteTime=False,verbose=False):
+def loadNewick(tree_path,tip_regex='\|([0-9]+\-[0-9]+\-[0-9]+)',date_fmt='%Y-%m-%d',variableDate=True,absoluteTime=False,verbose=False, sortBranches = True):
     """
     Load newick file
     """
     ll=None
     if isinstance(tree_path,str):
         handle=open(tree_path,'r')
     else:
@@ -1223,15 +1234,16 @@
         if '(' in l:
             treeString_start=l.index('(')
             ll=make_tree(l[treeString_start:],verbose=verbose) ## send tree string to make_tree function
             if verbose==True: print('Identified tree string')
 
     assert ll,'Regular expression failed to find tree string'
     ll.traverse_tree(verbose=verbose) ## traverse tree
-    ll.sortBranches() ## traverses tree, sorts branches, draws tree
+    if sortBranches:
+        ll.sortBranches() ## traverses tree, sorts branches, draws tree
 
     if absoluteTime==True:
         tipDates=[]
         tipNames=[]
         for k in ll.getExternal():
             n=k.name
             tipNames.append(n)
@@ -1241,15 +1253,15 @@
         assert len(tipDates)>0,'Regular expression failed to find tip dates in tip names, review regex pattern or set absoluteTime option to False.\nFirst tip name encountered: %s\nDate regex set to: %s\nExpected date format: %s'%(tipNames[0],tip_regex,date_fmt)
         highestTip=max(tipDates)
         ll.setAbsoluteTime(highestTip)
     if isinstance(tree_path,str):
         handle.close()
     return ll
 
-def loadNexus(tree_path,tip_regex='\|([0-9]+\-[0-9]+\-[0-9]+)',date_fmt='%Y-%m-%d',treestring_regex='tree [A-Za-z\_]+([0-9]+)',variableDate=True,absoluteTime=True,verbose=False):
+def loadNexus(tree_path,tip_regex='\|([0-9]+\-[0-9]+\-[0-9]+)',date_fmt='%Y-%m-%d',treestring_regex='tree [A-Za-z\_]+([0-9]+)',variableDate=True,absoluteTime=True,verbose=False, sortBranches=True):
     """
     Load nexus file
     """
     tipFlag=False
     tips={}
     tipNum=0
     ll=None
@@ -1257,41 +1269,42 @@
         handle=open(tree_path,'r')
     else:
         handle=tree_path
 
     for line in handle:
         l=line.strip('\n')
 
-        cerberus=re.search('dimensions ntax=([0-9]+);',l.lower())
+        cerberus=re.search('Dimensions ntax=([0-9]+);',l)
         if cerberus is not None:
             tipNum=int(cerberus.group(1))
             if verbose==True: print('File should contain %d taxa'%(tipNum))
 
-        cerberus=re.search(treestring_regex,l.lower())
+        cerberus=re.search(treestring_regex,l)
         if cerberus is not None:
             treeString_start=l.index('(')
             ll=make_tree(l[treeString_start:]) ## send tree string to make_tree function
             if verbose==True: print('Identified tree string')
 
         if tipFlag==True:
             cerberus=re.search('([0-9]+) ([A-Za-z\-\_\/\.\'0-9 \|?]+)',l)
             if cerberus is not None:
                 tips[cerberus.group(1)]=cerberus.group(2).strip('"').strip("'")
                 if verbose==True: print('Identified tip translation %s: %s'%(cerberus.group(1),tips[cerberus.group(1)]))
             elif ';' not in l:
                 print('tip not captured by regex:',l.replace('\t',''))
 
-        if 'translate' in l.lower():
+        if 'Translate' in l:
             tipFlag=True
         if ';' in l:
             tipFlag=False
 
     assert ll,'Regular expression failed to find tree string'
     ll.traverse_tree() ## traverse tree
-    ll.sortBranches() ## traverses tree, sorts branches, draws tree
+    if sortBranches:
+        ll.sortBranches() ## traverses tree, sorts branches, draws tree
     if len(tips)>0:
         ll.renameTips(tips) ## renames tips from numbers to actual names
         ll.tipMap=tips
     if absoluteTime==True:
         tipDates=[]
         tipNames=[]
         for k in ll.getExternal():
```

### Comparing `baltic-0.1.6/baltic/samogitia.py` & `baltic-0.1.8/baltic/samogitia.py`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/baltic.egg-info/SOURCES.txt` & `baltic-0.1.8/baltic.egg-info/SOURCES.txt`

 * *Files 18% similar despite different names*

```diff
@@ -3,15 +3,14 @@
 LICENSE
 MANIFEST.in
 README.md
 requirements.txt
 setup.py
 baltic/__init__.py
 baltic/baltic.py
-baltic/baltic_utils.py
 baltic/samogitia.py
 baltic.egg-info/PKG-INFO
 baltic.egg-info/SOURCES.txt
 baltic.egg-info/dependency_links.txt
 baltic.egg-info/not-zip-safe
 baltic.egg-info/requires.txt
 baltic.egg-info/top_level.txt
```

### Comparing `baltic-0.1.6/setup.py` & `baltic-0.1.8/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -4,24 +4,24 @@
     long_description = fh.read().decode()
 
 with open("requirements.txt") as fh:
     requirements = fh.read().splitlines()
 
 setup(
     name="baltic",
-    version="0.1.6",
+    version="0.1.8",
     packages=find_packages(),
     url="https://github.com/evogytis/baltic",
-    download_url="https://github.com/evogytis/baltic/archive/v0.1.5.tar.gz",
+    download_url="https://github.com/evogytis/baltic/archive/v0.1.8.tar.gz",
     keywords = ['phylogeny', 'visualization'],
     license="gpl-3.0",
     author="Gytis Dudas",
     author_email="gytisdudas@gmail.com",
     description="Lightweight package for analyzing, manipulating and visualizing annotated phylogenetic trees",
     long_description=long_description,
     long_description_content_type="text/markdown",
     install_requires=requirements,
-    python_requires=">=3.4.*",
+    python_requires=">=3.5",
     include_package_data=False,
     zip_safe=False,
     # classifiers=[],
 )
```

### Comparing `baltic-0.1.6/tests/data/2020-04-13_treetime/divergence_tree.nexus` & `baltic-0.1.8/tests/data/2020-04-13_treetime/divergence_tree.nexus`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/tests/data/2020-04-13_treetime/timetree.nexus` & `baltic-0.1.8/tests/data/2020-04-13_treetime/timetree.nexus`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/tests/data/MERS.mcc.tree` & `baltic-0.1.8/tests/data/MERS.mcc.tree`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/tests/data/miniFluB.mcc.tree` & `baltic-0.1.8/tests/data/miniFluB.mcc.tree`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/tests/data/zika.fa` & `baltic-0.1.8/tests/data/zika.fa`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/tests/data/zika.nwk` & `baltic-0.1.8/tests/data/zika.nwk`

 * *Files identical despite different names*

### Comparing `baltic-0.1.6/tests/testsuite.py` & `baltic-0.1.8/tests/testsuite.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,12 +1,15 @@
 import unittest
-import baltic as bt
+import importlib.util
+spec = importlib.util.spec_from_file_location("baltic", "baltic/baltic.py")
+bt = importlib.util.module_from_spec(spec)
+spec.loader.exec_module(bt)
 
 class test_parsers(unittest.TestCase):
-
+    
     def test_beast1_traits(self):
         print('Testing BEAST v1 trait parsing')
 
         ll=bt.loadNexus('./tests/data/miniFluB.mcc.tree',tip_regex='_([0-9-]+)')
 
         ll.traverse_tree()
         print('Test if branches have correct number of traits')
@@ -35,21 +38,23 @@
                 assert len(k.traits)==13
             elif k.is_leaf():
                 assert len(k.traits) in [9,12]
 
         print('Branches have correct number of traits')
 
     def test_newick(self):
+
         tree = bt.loadNewick('./tests/data/zika.nwk')
         expected_num_nodes = 564
         assert len(tree.Objects) == expected_num_nodes, 'Newick tree does not contain correct number of nodes. Expected: {}. Observed: {}'.format(expected_num_nodes, len(tree.Objects))
         max_height = round(max([i.height for i in tree.Objects]), 4)
         expected_height = 0.0058
         assert max_height == expected_height, 'Newick tree height is not correct. Expected: {}. Observed: {}'.format(expected_height, max_height)
 
     def test_nexus(self):
+
         tree = bt.loadNexus('./tests/data/2020-04-13_treetime/divergence_tree.nexus')
         tree.treeStats()
         pass
 
 if __name__ == '__main__':
     unittest.main()
```

