# Comparing `tmp/treat-sim-0.2.0.tar.gz` & `tmp/treat-sim-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "treat-sim-0.2.0.tar", last modified: Tue Jun 20 16:03:18 2023, max compression
+gzip compressed data, was "treat-sim-1.0.0.tar", last modified: Wed Jun 28 14:46:40 2023, max compression
```

## Comparing `treat-sim-0.2.0.tar` & `treat-sim-1.0.0.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-20 16:03:18.712889 treat-sim-0.2.0/
--rw-rw-r--   0 tom       (1001) tom       (1001)       52 2022-10-25 08:21:31.000000 treat-sim-0.2.0/MANIFEST.in
--rw-rw-r--   0 tom       (1001) tom       (1001)     1824 2023-06-20 16:03:18.712889 treat-sim-0.2.0/PKG-INFO
--rw-rw-r--   0 tom       (1001) tom       (1001)     1266 2022-10-25 08:21:31.000000 treat-sim-0.2.0/README.md
--rw-rw-r--   0 tom       (1001) tom       (1001)       82 2023-06-20 16:00:11.000000 treat-sim-0.2.0/requirements.txt
--rw-rw-r--   0 tom       (1001) tom       (1001)       38 2023-06-20 16:03:18.712889 treat-sim-0.2.0/setup.cfg
--rw-rw-r--   0 tom       (1001) tom       (1001)     1817 2022-10-25 08:21:31.000000 treat-sim-0.2.0/setup.py
-drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-20 16:03:18.712889 treat-sim-0.2.0/treat_sim/
--rw-rw-r--   0 tom       (1001) tom       (1001)       45 2023-06-20 16:00:44.000000 treat-sim-0.2.0/treat_sim/__init__.py
-drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-20 16:03:18.712889 treat-sim-0.2.0/treat_sim/data/
--rw-rw-r--   0 tom       (1001) tom       (1001)      381 2022-10-25 08:21:31.000000 treat-sim-0.2.0/treat_sim/data/ed_arrivals.csv
--rw-rw-r--   0 tom       (1001) tom       (1001)     5895 2022-10-25 08:21:31.000000 treat-sim-0.2.0/treat_sim/distributions.py
--rw-rw-r--   0 tom       (1001) tom       (1001)    37160 2022-10-25 08:21:31.000000 treat-sim-0.2.0/treat_sim/model.py
-drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-20 16:03:18.712889 treat-sim-0.2.0/treat_sim.egg-info/
--rw-rw-r--   0 tom       (1001) tom       (1001)     1824 2023-06-20 16:03:18.000000 treat-sim-0.2.0/treat_sim.egg-info/PKG-INFO
--rw-rw-r--   0 tom       (1001) tom       (1001)      310 2023-06-20 16:03:18.000000 treat-sim-0.2.0/treat_sim.egg-info/SOURCES.txt
--rw-rw-r--   0 tom       (1001) tom       (1001)        1 2023-06-20 16:03:18.000000 treat-sim-0.2.0/treat_sim.egg-info/dependency_links.txt
--rw-rw-r--   0 tom       (1001) tom       (1001)       72 2023-06-20 16:03:18.000000 treat-sim-0.2.0/treat_sim.egg-info/requires.txt
--rw-rw-r--   0 tom       (1001) tom       (1001)       10 2023-06-20 16:03:18.000000 treat-sim-0.2.0/treat_sim.egg-info/top_level.txt
+drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-28 14:46:40.523695 treat-sim-1.0.0/
+-rw-rw-r--   0 tom       (1001) tom       (1001)       52 2022-10-25 08:21:31.000000 treat-sim-1.0.0/MANIFEST.in
+-rw-rw-r--   0 tom       (1001) tom       (1001)     1844 2023-06-28 14:46:40.523695 treat-sim-1.0.0/PKG-INFO
+-rw-rw-r--   0 tom       (1001) tom       (1001)     1266 2022-10-25 08:21:31.000000 treat-sim-1.0.0/README.md
+-rw-rw-r--   0 tom       (1001) tom       (1001)       82 2023-06-28 13:53:35.000000 treat-sim-1.0.0/requirements.txt
+-rw-rw-r--   0 tom       (1001) tom       (1001)       38 2023-06-28 14:46:40.523695 treat-sim-1.0.0/setup.cfg
+-rw-rw-r--   0 tom       (1001) tom       (1001)     1817 2022-10-25 08:21:31.000000 treat-sim-1.0.0/setup.py
+drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-28 14:46:40.523695 treat-sim-1.0.0/treat_sim/
+-rw-rw-r--   0 tom       (1001) tom       (1001)       45 2023-06-28 14:43:14.000000 treat-sim-1.0.0/treat_sim/__init__.py
+drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-28 14:46:40.523695 treat-sim-1.0.0/treat_sim/data/
+-rw-rw-r--   0 tom       (1001) tom       (1001)      381 2022-10-25 08:21:31.000000 treat-sim-1.0.0/treat_sim/data/ed_arrivals.csv
+-rw-rw-r--   0 tom       (1001) tom       (1001)     5895 2022-10-25 08:21:31.000000 treat-sim-1.0.0/treat_sim/distributions.py
+-rw-rw-r--   0 tom       (1001) tom       (1001)    38255 2023-06-28 14:32:50.000000 treat-sim-1.0.0/treat_sim/model.py
+drwxrwxr-x   0 tom       (1001) tom       (1001)        0 2023-06-28 14:46:40.523695 treat-sim-1.0.0/treat_sim.egg-info/
+-rw-rw-r--   0 tom       (1001) tom       (1001)     1844 2023-06-28 14:46:40.000000 treat-sim-1.0.0/treat_sim.egg-info/PKG-INFO
+-rw-rw-r--   0 tom       (1001) tom       (1001)      310 2023-06-28 14:46:40.000000 treat-sim-1.0.0/treat_sim.egg-info/SOURCES.txt
+-rw-rw-r--   0 tom       (1001) tom       (1001)        1 2023-06-28 14:46:40.000000 treat-sim-1.0.0/treat_sim.egg-info/dependency_links.txt
+-rw-rw-r--   0 tom       (1001) tom       (1001)       72 2023-06-28 14:46:40.000000 treat-sim-1.0.0/treat_sim.egg-info/requires.txt
+-rw-rw-r--   0 tom       (1001) tom       (1001)       10 2023-06-28 14:46:40.000000 treat-sim-1.0.0/treat_sim.egg-info/top_level.txt
```

### Comparing `treat-sim-0.2.0/PKG-INFO` & `treat-sim-1.0.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 Metadata-Version: 2.1
 Name: treat-sim
-Version: 0.2.0
+Version: 1.0.0
 Summary: A free and open implementation of the Treatment Centre Model from Nelson (2013)
 Home-page: https://github.com/TomMonks/treatment-centre-sim
 Author: Thomas Monks
 Author-email: forecast-tools@gmail.com
 License: The MIT License (MIT)
+Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8.12
 Description-Content-Type: text/markdown
 
@@ -26,7 +27,9 @@
 
 The repo contains an free and open implementation of the Treatment Centre Model from Nelson (2013).  It is published under a permissive MIT license.
 
 ## References
 
 1. *Monks.T, Harper.A, Anagnoustou. A, Allen.M, Taylor.S. (2022) Open Science for Computer Simulation*
 2. *Nelson. B.L. (2013). [Foundations and methods of stochastic simulation](https://www.amazon.co.uk/Foundations-Methods-Stochastic-Simulation-International/dp/1461461596/ref=sr_1_1?dchild=1&keywords=foundations+and+methods+of+stochastic+simulation&qid=1617050801&sr=8-1). Springer.* 
+
+
```

### Comparing `treat-sim-0.2.0/README.md` & `treat-sim-1.0.0/README.md`

 * *Files identical despite different names*

### Comparing `treat-sim-0.2.0/setup.py` & `treat-sim-1.0.0/setup.py`

 * *Files identical despite different names*

### Comparing `treat-sim-0.2.0/treat_sim/distributions.py` & `treat-sim-1.0.0/treat_sim/distributions.py`

 * *Files identical despite different names*

### Comparing `treat-sim-0.2.0/treat_sim/model.py` & `treat-sim-1.0.0/treat_sim/model.py`

 * *Files 4% similar despite different names*

```diff
@@ -155,171 +155,202 @@
     '''
     if TRACE:
         print(msg)
 
 
 # ## Model parameterisation
 
-
 class Scenario:
     '''
     Container class for scenario parameters/arguments
-
-    For convienience a container class is used to hold the large number of model 
-    parameters.  The `Scenario` class includes defaults  these can easily be 
-    changed and at runtime to experiments with different designs.
     
     Passed to a model and its process classes
     '''
-    def __init__(self, random_number_set=DEFAULT_RNG_SET):
+    def __init__(self, random_number_set=DEFAULT_RNG_SET,
+                 n_triage=DEFAULT_N_TRIAGE,
+                 n_reg=DEFAULT_N_REG,
+                 n_exam=DEFAULT_N_EXAM,
+                 n_trauma=DEFAULT_N_TRAUMA,
+                 n_cubicles_1=DEFAULT_N_CUBICLES_1,
+                 n_cubicles_2=DEFAULT_N_CUBICLES_2,
+                 triage_mean=DEFAULT_TRIAGE_MEAN,
+                 reg_mean=DEFAULT_REG_MEAN,
+                 reg_var=DEFAULT_REG_VAR,
+                 exam_mean=DEFAULT_EXAM_MEAN,
+                 exam_var=DEFAULT_EXAM_VAR,
+                 trauma_mean=DEFAULT_TRAUMA_MEAN,
+                 trauma_treat_mean=DEFAULT_TRAUMA_TREAT_MEAN,
+                 trauma_treat_var=DEFAULT_TRAUMA_TREAT_VAR,
+                 non_trauma_treat_mean=DEFAULT_NON_TRAUMA_TREAT_MEAN,
+                 non_trauma_treat_var=DEFAULT_NON_TRAUMA_TREAT_VAR,
+                 non_trauma_treat_p=DEFAULT_NON_TRAUMA_TREAT_P,
+                 prob_trauma=DEFAULT_PROB_TRAUMA):
         '''
-        The init method sets up our defaults.
+        Create a scenario to parameterise the simulation model
         
         Parameters:
         -----------
         random_number_set: int, optional (default=DEFAULT_RNG_SET)
             Set to control the initial seeds of each stream of pseudo
             random numbers used in the model.
+        
+        n_triage: int
+            The number of triage cubicles
+        
+        n_reg: int
+            The number of registration clerks
+            
+        n_exam: int
+            The number of examination rooms
+            
+        n_trauma: int
+            The number of trauma bays for stablisation
+            
+        n_cubicles_1: int
+            The number of non-trauma treatment cubicles
+            
+        n_cubicles_2: int
+            The number of trauma treatment cubicles
+            
+        triage_mean: float
+            Mean duration of the triage distribution (Exponential)
+            
+        reg_mean: float
+            Mean duration of the registration distribution (Lognormal)
+            
+        reg_var: float
+            Variance of the registration distribution (Lognormal)
+            
+        exam_mean: float
+            Mean of the examination distribution (Normal)
+            
+        exam_var: float
+            Variance of the examination distribution (Normal)
+            
+        trauma_mean: float
+            Mean of the trauma stabilisation distribution (Exponential)
+            
+        trauma_treat_mean: float
+            Mean of the trauma cubicle treatment distribution (Lognormal)
+            
+        trauma_treat_var: float
+            Variance of the trauma cubicle treatment distribution (Lognormal)
+        
+        non_trauma_treat_mean: float
+            Mean of the non trauma treatment distribution
+            
+        non_trauma_treat_var: float
+            Variance of the non trauma treatment distribution
+        
+        non_trauma_treat_p: float
+            Probability non trauma patient requires treatment
+            
+        prob_trauma: float
+            probability that a new arrival is a trauma patient.
         '''
         # sampling
         self.random_number_set = random_number_set
-
-        # count of each type of resource
-        self.init_resourse_counts()
-
-        # pathway variables
-        self.init_pathway_variables()
-
-        # sampling distributions
+        
+        # store parameters for sampling
+        self.triage_mean = triage_mean
+        self.reg_mean = reg_mean
+        self.reg_var = reg_var
+        self.exam_mean= exam_mean
+        self.exam_var = exam_var
+        self.trauma_mean = trauma_mean
+        self.trauma_treat_mean = trauma_treat_mean
+        self.trauma_treat_var = trauma_treat_var
+        self.non_trauma_treat_mean = non_trauma_treat_mean
+        self.non_trauma_treat_var = non_trauma_treat_var
+        self.non_trauma_treat_p = non_trauma_treat_p
+        self.prob_trauma = prob_trauma
+        
         self.init_sampling()
-            
+        
+        # count of each type of resource
+        self.init_resourse_counts(n_triage, n_reg, n_exam, n_trauma,
+                                  n_cubicles_1, n_cubicles_2)
+    
     def set_random_no_set(self, random_number_set):
         '''
         Controls the random sampling 
         Parameters:
         ----------
         random_number_set: int
             Used to control the set of psuedo random numbers
             used by the distributions in the simulation.
         '''
         self.random_number_set = random_number_set
         self.init_sampling()
 
-    def init_resourse_counts(self):
+    def init_resourse_counts(self, n_triage, n_reg, n_exam, n_trauma,
+                             n_cubicles_1, n_cubicles_2):
         '''
         Init the counts of resources to default values...
         '''
-        self.n_triage = DEFAULT_N_TRIAGE
-        self.n_reg = DEFAULT_N_REG
-        self.n_exam = DEFAULT_N_EXAM
-        self.n_trauma = DEFAULT_N_TRAUMA
+        self.n_triage = n_triage
+        self.n_reg = n_reg
+        self.n_exam = n_exam
+        self.n_trauma = n_trauma
         
         # non-trauma (1), trauma (2) treatment cubicles
-        self.n_cubicles_1 = DEFAULT_N_CUBICLES_1
-        self.n_cubicles_2 = DEFAULT_N_CUBICLES_2
-
-    def init_pathway_variables(self):
-        # trauma pathway
-        self.prob_trauma = DEFAULT_PROB_TRAUMA
-        self.treat_trauma_mean = DEFAULT_TRAUMA_TREAT_MEAN
-        self.treat_trauma_var = DEFAULT_TRAUMA_TREAT_VAR
-
-        #non trauma pathway
-        self.exam_mean = DEFAULT_EXAM_MEAN
-        self.exam_var = DEFAULT_EXAM_VAR
-
-        self.nt_treat_prob = DEFAULT_NON_TRAUMA_TREAT_P       
-        self.nt_treat_mean = DEFAULT_NON_TRAUMA_TREAT_MEAN
-        self.nt_treat_var = DEFAULT_NON_TRAUMA_TREAT_VAR
-
-    # def __eq__(self, other):
-    #     return self.n_triage == other.n_triage and \
-    #            self.n_reg == other.n_reg and \
-    #            self.n_exam == other.n_exam and \
-    #            self.n_trauma == other.n_trauma and \
-    #            self.n_cubicles_1 == other.n_cubicles_1 and \
-    #            self.n_cubicles_2 == other.n_cubicles_2 and \
-    #            self.prob_trauma == other.prob_trauma and \
-    #            self.treat_trauma_mean == other.treat_trauma_mean and \
-    #            self.treat_trauma_var == other.treat_trauma_var and \
-    #            self.exam_mean == other.exam_mean and \
-    #            self.exam_var == other.exam_var and \
-    #            self.nt_treat_prob == other.nt_treat_prob and \
-    #            self.nt_treat_mean == other.self.nt_treat_mean and \
-    #            self.nt_treat_var == other.nt_treat_var
- 
-    # def __hash__(self):
-    #     ''''''
-    #     return hash((self.n_triage,
-    #                  self.n_reg,
-    #                  self.n_exam,
-    #                  self.n_trauma,
-    #                  self.n_cubicles_1,
-    #                  self.n_cubicles_2,
-    #                  self.prob_trauma,
-    #                  self.treat_trauma_mean,
-    #                  self.treat_trauma_var,
-    #                  self.exam_mean,
-    #                  self.exam_var,
-    #                  self.nt_treat_prob,
-    #                  self.nt_treat_mean,
-    #                  self.nt_treat_var))
+        self.n_cubicles_1 = n_cubicles_1
+        self.n_cubicles_2 = n_cubicles_2
 
     def init_sampling(self):
         '''
         Create the distributions used by the model and initialise 
         the random seeds of each.
         '''
         # create random number streams
         rng_streams = np.random.default_rng(self.random_number_set)
         self.seeds = rng_streams.integers(0, 999999999, size=N_STREAMS)
 
         # create distributions
         
         # Triage duration
-        self.triage_dist = Exponential(DEFAULT_TRIAGE_MEAN, 
+        self.triage_dist = Exponential(self.triage_mean, 
                                        random_seed=self.seeds[0])
         
         # Registration duration (non-trauma only)
-        self.reg_dist = Lognormal(DEFAULT_REG_MEAN, 
-                                  np.sqrt(DEFAULT_REG_VAR),
+        self.reg_dist = Lognormal(self.reg_mean, 
+                                  np.sqrt(self.reg_var),
                                   random_seed=self.seeds[1])
         
         # Evaluation (non-trauma only)
         self.exam_dist = Normal(self.exam_mean,
                                 np.sqrt(self.exam_var),
                                 random_seed=self.seeds[2])
         
         # Trauma/stablisation duration (trauma only)
-        self.trauma_dist = Exponential(DEFAULT_TRAUMA_MEAN, 
+        self.trauma_dist = Exponential(self.trauma_mean, 
                                        random_seed=self.seeds[3])
         
         # Non-trauma treatment
-        self.nt_treat_dist = Lognormal(self.nt_treat_mean, 
-                                       np.sqrt(self.nt_treat_var),
+        self.nt_treat_dist = Lognormal(self.non_trauma_treat_mean, 
+                                       np.sqrt(self.non_trauma_treat_var),
                                        random_seed=self.seeds[4])
         
         # treatment of trauma patients
-        self.treat_dist = Lognormal(self.treat_trauma_mean, 
-                                    np.sqrt(self.treat_trauma_var),
+        self.treat_dist = Lognormal(self.trauma_treat_mean, 
+                                    np.sqrt(self.non_trauma_treat_var),
                                     random_seed=self.seeds[5])
         
         # probability of non-trauma patient requiring treatment
-        self.nt_p_treat_dist = Bernoulli(self.nt_treat_prob, 
+        self.nt_p_treat_dist = Bernoulli(self.non_trauma_treat_p, 
                                          random_seed=self.seeds[6])
         
         
         # probability of non-trauma versus trauma patient
         self.p_trauma_dist = Bernoulli(self.prob_trauma, 
                                        random_seed=self.seeds[7])
         
         # init sampling for non-stationary poisson process
         self.init_nspp()
-
-            
+        
     def init_nspp(self):
         
         # read arrival profile
         self.arrivals = pd.read_csv(NSPP_PATH)
         self.arrivals['mean_iat'] = 60 / self.arrivals['arrival_rate']
        
         # maximum arrival rate (smallest time between arrivals)
@@ -1024,39 +1055,34 @@
     dict
         Contains the scenarios for the model
     '''
     scenarios = {}
     scenarios['base'] = Scenario()
     
     # extra triage capacity
-    scenarios['triage+1'] = Scenario()
-    scenarios['triage+1'].n_triage += 1
+    scenarios['triage+1'] = Scenario(n_triage=DEFAULT_N_TRIAGE+1)
         
     # extra examination capacity
-    scenarios['exam+1'] = Scenario()
-    scenarios['exam+1'].n_exam += 1
+    scenarios['exam+1'] = Scenario(n_exam=DEFAULT_N_EXAM+1)
     
     # extra non-trauma treatment capacity
-    scenarios['treat+1'] = Scenario()
-    scenarios['treat+1'].n_cubicles_1 += 1
-    
-    #swap over 1 exam room for extra treat cubicle
-    scenarios['swap_exam_treat'] = Scenario()
-    scenarios['swap_exam_treat'].n_cubicles_1 += 1
-    scenarios['swap_exam_treat'].n_exam -= 1
-
-    #scenario + 3 min short mean exam times.
-    scenarios['short_exam'] = Scenario()
-    scenarios['short_exam'].n_cubicles_1 += 1
-    scenarios['short_exam'].n_exam -= 1
-    scenarios['short_exam'].exam_mean = 12.0
+    scenarios['treat+1'] = Scenario(n_cubicles_1=DEFAULT_N_CUBICLES_1+1)
     
+    # swap over 1 exam room for extra treat cubicle
+    scenarios['swap_exam_treat'] = Scenario(n_triage=DEFAULT_N_TRIAGE+1,
+                                            n_exam=DEFAULT_N_EXAM-1)
+    
+    # scenario + 3 min short mean exam times.
+    scenarios['short_exam'] = Scenario(n_triage=DEFAULT_N_TRIAGE+1,
+                                       n_exam=DEFAULT_N_EXAM-1,
+                                       exam_mean=12.0)    
     return scenarios
 
 
+
 def run_scenario_analysis(scenarios, rc_period, n_reps):
     '''
     Run each of the scenarios for a specified results
     collection period and replications.
     
     Params:
     ------
```

### Comparing `treat-sim-0.2.0/treat_sim.egg-info/PKG-INFO` & `treat-sim-1.0.0/treat_sim.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 Metadata-Version: 2.1
 Name: treat-sim
-Version: 0.2.0
+Version: 1.0.0
 Summary: A free and open implementation of the Treatment Centre Model from Nelson (2013)
 Home-page: https://github.com/TomMonks/treatment-centre-sim
 Author: Thomas Monks
 Author-email: forecast-tools@gmail.com
 License: The MIT License (MIT)
+Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8.12
 Description-Content-Type: text/markdown
 
@@ -26,7 +27,9 @@
 
 The repo contains an free and open implementation of the Treatment Centre Model from Nelson (2013).  It is published under a permissive MIT license.
 
 ## References
 
 1. *Monks.T, Harper.A, Anagnoustou. A, Allen.M, Taylor.S. (2022) Open Science for Computer Simulation*
 2. *Nelson. B.L. (2013). [Foundations and methods of stochastic simulation](https://www.amazon.co.uk/Foundations-Methods-Stochastic-Simulation-International/dp/1461461596/ref=sr_1_1?dchild=1&keywords=foundations+and+methods+of+stochastic+simulation&qid=1617050801&sr=8-1). Springer.* 
+
+
```

