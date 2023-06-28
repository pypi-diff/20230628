# Comparing `tmp/atomcalc-0.1.6.tar.gz` & `tmp/atomcalc-0.1.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "atomcalc-0.1.6.tar", max compression
+gzip compressed data, was "atomcalc-0.1.7.tar", max compression
```

## Comparing `atomcalc-0.1.6.tar` & `atomcalc-0.1.7.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0      182 2023-06-21 20:35:37.142815 atomcalc-0.1.6/atomcalc/__init__.py
--rw-r--r--   0        0        0     1206 2023-06-21 19:20:53.765656 atomcalc-0.1.6/atomcalc/Decay.py
--rw-r--r--   0        0        0     1531 2023-06-21 19:20:53.766656 atomcalc-0.1.6/atomcalc/Laser.py
--rw-r--r--   0        0        0      457 2023-06-21 19:20:53.762652 atomcalc-0.1.6/atomcalc/Level.py
--rw-r--r--   0        0        0      876 2023-06-21 19:20:53.792679 atomcalc-0.1.6/atomcalc/plot_pulse.py
--rw-r--r--   0        0        0    24121 2023-06-21 19:20:54.536355 atomcalc-0.1.6/atomcalc/System.py
--rw-r--r--   0        0        0      631 2023-06-21 20:49:35.930368 atomcalc-0.1.6/pyproject.toml
--rw-r--r--   0        0        0     1142 2023-06-21 18:51:17.200721 atomcalc-0.1.6/README.md
--rw-r--r--   0        0        0     1696 1970-01-01 00:00:00.000000 atomcalc-0.1.6/PKG-INFO
+-rw-r--r--   0        0        0      182 2023-06-21 20:35:37.142815 atomcalc-0.1.7/atomcalc/__init__.py
+-rw-r--r--   0        0        0     1206 2023-06-21 19:20:53.765656 atomcalc-0.1.7/atomcalc/Decay.py
+-rw-r--r--   0        0        0     1828 2023-06-28 09:23:44.230826 atomcalc-0.1.7/atomcalc/Laser.py
+-rw-r--r--   0        0        0      515 2023-06-28 09:19:40.742708 atomcalc-0.1.7/atomcalc/Level.py
+-rw-r--r--   0        0        0      759 2023-06-24 14:09:21.389999 atomcalc-0.1.7/atomcalc/plot_pulse.py
+-rw-r--r--   0        0        0    24760 2023-06-24 14:11:15.073771 atomcalc-0.1.7/atomcalc/System.py
+-rw-r--r--   0        0        0      631 2023-06-28 09:35:39.074241 atomcalc-0.1.7/pyproject.toml
+-rw-r--r--   0        0        0     1142 2023-06-21 18:51:17.200721 atomcalc-0.1.7/README.md
+-rw-r--r--   0        0        0     1696 1970-01-01 00:00:00.000000 atomcalc-0.1.7/PKG-INFO
```

### Comparing `atomcalc-0.1.6/atomcalc/Decay.py` & `atomcalc-0.1.7/atomcalc/Decay.py`

 * *Files identical despite different names*

### Comparing `atomcalc-0.1.6/atomcalc/Laser.py` & `atomcalc-0.1.7/atomcalc/Laser.py`

 * *Files 26% similar despite different names*

```diff
@@ -3,36 +3,39 @@
 import matplotlib.pylab as plt
 import scipy
 
 
 class Laser:
     """
     An object that describes values for a laser: Rabi frequency, frequency, and coupled states.
+    One laser only affects the one specific transition that is defined in the couple parameter.
 
     Args:
         rabifreq (number): value for :attr:`rabifreq`
-        frequency (number): value for :attr:`frequency`
+        detuning (number): value for :attr:`detuning`
         couple (list): value for :attr:`couple`
         pulse (None or function or list): value for :attr:`pulse`
 
 
     Attributes:
-        rabifreq (number): Rabi frequency of the laser.
-        frequency (number): The to the frequency of the laser corresponding energy.
+        rabifreq (number): Rabi frequency of the laser as angular frequency.
+        frequency (number): The angular frequency of the laser. Represents the energy gap of the transition.
+        detuning (number): The detuning of the laser.
         couple (list): A tupel of :class:`Level` objects that assigns the laser to this transition.
         pulse (None or function or list): A time dependent function of the Rabi frequency of the laser OR a list of numbers describing a Rabi frequency pulse.
 
     Example:
 
         >>> Laser(1, 100, [Level(0),Level(20)])
         The transition between Level(20) and Level(0) is assigned a laser with Rabi frequency of 1 and a frequency of 100.
 
     Note:
-        Sort Level couples from low to high.
+        Level couples need to be sorted by energy in ascending order.
     """
 
-    def __init__(self, rabifreq, frequency, couple, polarization=None, pulse=None):
+    def __init__(self, rabifreq, detuning, couple, polarization=None, pulse=None):
         self.rabi = rabifreq
         self.couple = couple
-        self.frequency = frequency
+        self.detuning = detuning
+        self.frequency = np.abs(couple[0].energy-couple[1].energy) + detuning
         self.polarization = polarization  # Not yet included. A list of a normalized E-field vector in the laser coordinate system, a theta_k and a theta_p (in degrees) and a pair [m_i,m_f].
         self.pulse = pulse
```

### Comparing `atomcalc-0.1.6/atomcalc/plot_pulse.py` & `atomcalc-0.1.7/atomcalc/plot_pulse.py`

 * *Files 26% similar despite different names*

```diff
@@ -7,18 +7,14 @@
 
 
 def plot_pulse(pulse, tlist):
     """
     A function to plot a pulse function.
 
     Args:
-        pulse (function): value for :attr:`pulse`
-        tlist (list): value for :attr:`tlist`
-
-    Attributes:
         pulse (function): A time dependent pulse function.
         tlist (list): A list of points in time where the pulse should be plotted.
 
     """
     fig, ax = plt.subplots()
     pulse = np.array([pulse(t) for t in tlist])
     tlist = np.array(tlist)
```

### Comparing `atomcalc-0.1.6/atomcalc/System.py` & `atomcalc-0.1.7/atomcalc/System.py`

 * *Files 4% similar despite different names*

```diff
@@ -25,15 +25,15 @@
         >>> level3 = Level(100)
         >>> laser1 = Laser(1, 120, [level1,level3])
         >>> laser2 = Laser(1, 100, [level2,level3])
         >>> decay = Decay([0],[[level3,level1]])
         >>> system = System([level1, level2, level3], [laser1,laser2], decay)
 
     Note:
-        Sort levels by energy in ascending order.
+        Levels need to be sorted by energy in ascending order.
     """
 
     def __init__(self, levels, lasers, decay):
         self.lasers = lasers
         self.levels = levels
         self.dim = len(levels)
         self.decay = decay
@@ -84,47 +84,80 @@
             i2 = self.levels.index(self.lasers[i].couple[1])
             x = [0.1 + 0.2 * i1, 0.1 + 0.2 * i2]
             y = [min_couple, max_couple + detuning[i]]
             plt.plot(x, y, linestyle="-", label="Laser {}".format(i + 1))
         plt.legend(loc="center left", bbox_to_anchor=(1, 0.5))
         plt.show()
 
+    def _plot_population(self, result, dim):
+        fig, ax = plt.subplots()
+        for i in range(dim):
+            if i != 12:
+                ax.plot(
+                    result.times,
+                    result.expect[i],
+                    linewidth=1,
+                    label="{}".format(i + 1),
+                )
+        ax.legend()
+        ax.set_ylim([-0.01, 1.01])
+        ax.set_xlabel("Time")
+        ax.set_ylabel("Population")
+        plt.show()
+
+    def _plot_population_diagonalization(self, tlist, result, dim):
+        fig, ax = plt.subplots()
+        tlist = np.array(tlist)
+        n = dim
+        for i in range(dim):
+            ax.plot(
+                tlist, np.real(result[:, i]), linewidth=1.5, label="{}".format(i + 1)
+            )
+        ax.legend()
+        ax.set_ylim([-0.1, 1.1])
+        ax.set_xlabel(r"Time")
+        ax.set_ylabel(r"Population")
+        plt.show()
+
     def simulate(
         self,
         initial_state_index_list,
-        read_out_level,
+        level_to_print_max_value,
         maxtime,
         delta_stark_shift=0,
         Diagonalization=True,
         plot_pop=True,
         Trotterintervals=500,
+        points_per_TI=2,
         resolution=250,
     ):
         """
-        A function to simulate the time evolution of the population of every level. It also returns the maximum population of specifically the read_out_level.
+        A function to simulate the time evolution of the population of every level. It also returns the maximum population of specifically the level_to_print_max_value.
 
         Args:
             initial_state_index_list (list): value for :attr:`initial_state_index_list`
-            read_out_level (number): value for :attr:`read_out_level`
+            level_to_print_max_value (number): value for :attr:`level_to_print_max_value`
             maxtime (integer): value for :attr:`maxtime`
             delta_stark_shift (number): value for :attr:`delta_stark_shift`
             Diagonalization (bool): value for :attr:`Diagonalization`
             plot_pop (bool): value for :attr:`plot_pop`
-            Trotterintervals (number) : value for :attr:`Trotterintervals`
+            Trotterintervals (number): value for :attr:`Trotterintervals`
+            points_per_TI (number): value for :attr:`points_per_TI`
             resolution (number): value for :attr:`resolution`
 
         Attributes:
             initial_state_index_list (list): Initial population distribution. First entry denotes the population of the first level and so on. Length of the list needs to be equal to the level-count and the entries need to sum up to one.
-            read_out_level (number): Determines which levels population maximum is printed in the output. 0 is the first level.
+            level_to_print_max_value (number): Just affects the output. Determines which levels population maximum is printed in the output. 0 is the first level.
             maxtime (integer): Maximum time the system is simulated.
             delta_stark_shift (number): Detuning of the first level.
             Diagonalization (bool): If False, simulate the system with the integration method 'qutip.mesolve' from QuTiP. If True, simulate the system using diagonalization.
             plot_pop (bool): If False, do not show the population plot.
             Trotterintervals (number): Only relevant if a pulse is given. Discretizes the pulse into a step function of `Trotterintervals` time intervals.
-            resolution (number): Only relevant if Diagonalization = True. Divides the simulation time interval into `resolution` uniformly distributed points of time.
+            points_per_TI (number): Only relevant if a pulse is given. Divides one trotterinterval in points_per_TI intervals. This determines the number of points calculated within one trotterinterval.
+            resolution (number): Only relevant if Diagonalization = True and no pulse is given. Divides the simulation time interval into `resolution` uniformly distributed points of time.
 
         """
         Trotter = False
         # make basis: levels to kets
         initial_state_dm = qutip.qzero(self.dim)
         level_ket = [[]] * self.dim  # empty ket with 'dim' empty entries
         proj = [[]] * self.dim
@@ -290,15 +323,14 @@
                 raise Exception(
                     "The number of trotterintervals of {} doesnt divide the given timerange of {} into trotterintervals with integer time".format(
                         number_TI, maxtime
                     )
                 )
             td = np.linspace(0, maxtime, number_TI + 1)
             print("One trotterinterval has size {}.".format(td[1]))
-            points_per_TI = 2  # divides one trotterinterval in points_per_TI intervals
             if td[1] / points_per_TI != int(td[1] / points_per_TI):
                 raise Exception(
                     "The number of timeintervals per trotterinterval of {} doesnt divide one trotterinterval of size {} into timeintervals with integer time".format(
                         points_per_TI, td[1]
                     )
                 )
             print("One trotter step has size {}.".format(td[1] / points_per_TI))
@@ -396,17 +428,19 @@
                                 ),
                             )
                         result[t + n * points_per_TI] = np.array(expect_value)
             result = np.array(
                 result
             )  # result[t] is a list of expectation values of all levels for the point of time that is indexed with t
             if plot_pop == True:
-                plot_population_diagonalization(tlist_ges[:], result[:], self.dim)
-            print("Maximum population of level {}:".format(read_out_level + 1))
-            return np.real(np.amax(result[:, read_out_level]))
+                self._plot_population_diagonalization(tlist_ges[:], result[:], self.dim)
+            print(
+                "Maximum population of level {}:".format(level_to_print_max_value + 1)
+            )
+            return np.real(np.amax(result[:, level_to_print_max_value]))
 
         elif Diagonalization == True:
             # Liouvillian
             L = qutip.liouvillian(H, c_ops)
             L = np.reshape(L, (self.dim**2, self.dim**2))
 
             # Time evolution:
@@ -444,49 +478,24 @@
                         qutip.Qobj(np.reshape(dm_t[t], (self.dim, self.dim))),
                     )
                 result[t] = np.array(np.reshape(expect_value, (self.dim,)))
             result = np.array(
                 result
             )  # result[t] is a list of expectation values of all levels for the point of time that is indexed with t
             if plot_pop == True:
-                plot_population_diagonalization(tlist, result, self.dim)
-            print("Maximum population of level {}:".format(read_out_level + 1))
-            return np.real(np.amax(result[:, read_out_level]))
+                self._plot_population_diagonalization(tlist, result, self.dim)
+            print(
+                "Maximum population of level {}:".format(level_to_print_max_value + 1)
+            )
+            return np.real(np.amax(result[:, level_to_print_max_value]))
 
         else:  # Integration-solver from QuTip. See QuTiP Documentation of the mesolve function.
             tlist = list(range(0, maxtime, int(41300000 / 100)))
             print("Length of tlist: {}".format(len(tlist)))
             # opts=Options(nsteps=1000)
             # print(options)
             # start = time.time()
             result = qutip.mesolve(H, initial_state_dm, tlist, c_ops, proj)
             # end = time.time()
             # print(f"{end-start:5.3f}s")
-            plot_population(result, self.dim)
+            self._plot_population(result, self.dim)
             print(result.expect[1][-1])
-
-
-def plot_population(result, dim):
-    fig, ax = plt.subplots()
-    for i in range(dim):
-        if i != 12:
-            ax.plot(
-                result.times, result.expect[i], linewidth=1, label="{}".format(i + 1)
-            )
-    ax.legend()
-    ax.set_ylim([-0.01, 1.01])
-    ax.set_xlabel("Time")
-    ax.set_ylabel("Population")
-    plt.show()
-
-
-def plot_population_diagonalization(tlist, result, dim):
-    fig, ax = plt.subplots()
-    tlist = np.array(tlist)
-    n = dim
-    for i in range(dim):
-        ax.plot(tlist, np.real(result[:, i]), linewidth=1.5, label="{}".format(i + 1))
-    ax.legend()
-    ax.set_ylim([-0.1, 1.1])
-    ax.set_xlabel(r"Time")
-    ax.set_ylabel(r"Population")
-    plt.show()
```

### Comparing `atomcalc-0.1.6/pyproject.toml` & `atomcalc-0.1.7/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "atomcalc"
-version = "0.1.6"
+version = "0.1.7"
 description = ""
 authors = ["Moritz Wilke"]
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = ">=3.8.5,<3.12"
 numpy = "^1.24.3"
```

### Comparing `atomcalc-0.1.6/README.md` & `atomcalc-0.1.7/README.md`

 * *Files identical despite different names*

### Comparing `atomcalc-0.1.6/PKG-INFO` & `atomcalc-0.1.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: atomcalc
-Version: 0.1.6
+Version: 0.1.7
 Summary: 
 Author: Moritz Wilke
 Requires-Python: >=3.8.5,<3.12
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
```

