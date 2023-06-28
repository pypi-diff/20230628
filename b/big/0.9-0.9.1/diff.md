# Comparing `tmp/big-0.9.tar.gz` & `tmp/big-0.9.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "big-0.9.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
+gzip compressed data, was "big-0.9.1.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
```

## Comparing `big-0.9.tar` & `big-0.9.1.tar`

### file list

```diff
@@ -1,32 +1,34 @@
--rw-r--r--   0        0        0       50 2022-12-06 08:53:33.203521 big-0.9/.gitignore
--rw-r--r--   0        0        0     1084 2023-04-12 21:51:57.496190 big-0.9/LICENSE
--rw-r--r--   0        0        0   147240 2023-06-16 06:38:12.573340 big-0.9/README.md
--rw-r--r--   0        0        0     1240 2023-06-16 06:35:24.967805 big-0.9/big/__init__.py
--rw-r--r--   0        0        0     1941 2023-04-12 21:51:57.504191 big-0.9/big/all.py
--rw-r--r--   0        0        0     7825 2023-06-16 05:58:09.499819 big-0.9/big/boundinnerclass.py
--rw-r--r--   0        0        0     3274 2023-04-12 21:51:57.504191 big-0.9/big/builtin.py
--rw-r--r--   0        0        0    11015 2023-04-12 21:51:57.504191 big-0.9/big/file.py
--rw-r--r--   0        0        0    25350 2023-04-12 21:51:57.504191 big-0.9/big/graph.py
--rw-r--r--   0        0        0     5347 2023-04-12 21:51:57.504191 big-0.9/big/heap.py
--rw-r--r--   0        0        0     2499 2023-04-12 21:51:57.504191 big-0.9/big/itertools.py
--rw-r--r--   0        0        0    12574 2023-04-12 21:51:57.504191 big-0.9/big/scheduler.py
--rw-r--r--   0        0        0   108729 2023-06-12 04:56:42.197905 big-0.9/big/text.py
--rw-r--r--   0        0        0     7163 2023-04-12 21:51:57.504191 big-0.9/big/time.py
--rw-r--r--   0        0        0      613 2023-04-12 21:51:57.504191 big-0.9/pyproject.toml
--rw-r--r--   0        0        0       16 2022-12-06 08:53:33.203521 big-0.9/requirements.txt
--rw-r--r--   0        0        0   174313 2022-05-27 04:32:07.000000 big-0.9/resources/experiments/alice.in.wonderland.txt
--rw-r--r--   0        0        0     6060 2023-04-12 21:51:57.504191 big-0.9/resources/experiments/time_multisplit.py
--rw-r--r--   0        0        0  1391641 2022-06-02 13:08:28.000000 big-0.9/resources/images/big.header.png
--rw-r--r--   0        0        0     3576 2023-06-16 06:08:11.681574 big-0.9/tests/bigtestlib.py
--rw-r--r--   0        0        0       50 2022-05-28 09:56:21.000000 big-0.9/tests/grepfile
--rw-r--r--   0        0        0     1455 2023-06-12 04:42:29.754589 big-0.9/tests/test_all.py
--rw-r--r--   0        0        0     8721 2023-06-16 06:17:18.590218 big-0.9/tests/test_boundinnerclass.py
--rw-r--r--   0        0        0     6518 2023-06-12 04:41:10.137906 big-0.9/tests/test_builtin.py
--rw-r--r--   0        0        0     8363 2023-06-12 04:41:42.094180 big-0.9/tests/test_file.py
--rw-r--r--   0        0        0    12333 2023-06-12 04:42:21.830521 big-0.9/tests/test_graph.py
--rw-r--r--   0        0        0     5007 2023-05-28 20:37:20.059918 big-0.9/tests/test_heap.py
--rw-r--r--   0        0        0     3403 2023-06-12 04:40:55.577781 big-0.9/tests/test_itertools.py
--rw-r--r--   0        0        0    11473 2023-05-28 20:36:59.947749 big-0.9/tests/test_scheduler.py
--rw-r--r--   0        0        0   140256 2023-06-12 04:59:30.039346 big-0.9/tests/test_text.py
--rw-r--r--   0        0        0     6101 2023-06-12 04:41:31.070086 big-0.9/tests/test_time.py
--rw-r--r--   0        0        0   147843 1970-01-01 00:00:00.000000 big-0.9/PKG-INFO
+-rw-r--r--   0        0        0       50 2022-12-06 08:53:33.203521 big-0.9.1/.gitignore
+-rw-r--r--   0        0        0     1084 2023-06-16 06:39:59.562319 big-0.9.1/LICENSE
+-rw-r--r--   0        0        0   150629 2023-06-28 11:25:56.173595 big-0.9.1/README.md
+-rw-r--r--   0        0        0     1242 2023-06-28 11:25:56.173595 big-0.9.1/big/__init__.py
+-rw-r--r--   0        0        0     2007 2023-06-28 11:25:56.173595 big-0.9.1/big/all.py
+-rw-r--r--   0        0        0     7825 2023-06-18 07:30:42.346660 big-0.9.1/big/boundinnerclass.py
+-rw-r--r--   0        0        0     3274 2023-06-18 07:30:42.346660 big-0.9.1/big/builtin.py
+-rw-r--r--   0        0        0    11015 2023-06-18 07:30:42.346660 big-0.9.1/big/file.py
+-rw-r--r--   0        0        0    25350 2023-06-18 07:30:42.346660 big-0.9.1/big/graph.py
+-rw-r--r--   0        0        0     5347 2023-06-18 07:30:42.346660 big-0.9.1/big/heap.py
+-rw-r--r--   0        0        0     2499 2023-06-28 10:08:06.167307 big-0.9.1/big/itertools.py
+-rw-r--r--   0        0        0     6358 2023-06-28 11:25:56.173595 big-0.9.1/big/log.py
+-rw-r--r--   0        0        0    12574 2023-06-18 07:30:42.346660 big-0.9.1/big/scheduler.py
+-rw-r--r--   0        0        0   108729 2023-06-18 07:30:42.346660 big-0.9.1/big/text.py
+-rw-r--r--   0        0        0     7163 2023-06-18 07:30:42.346660 big-0.9.1/big/time.py
+-rw-r--r--   0        0        0      613 2023-06-16 06:39:59.562319 big-0.9.1/pyproject.toml
+-rw-r--r--   0        0        0       16 2022-12-06 08:53:33.203521 big-0.9.1/requirements.txt
+-rw-r--r--   0        0        0   174313 2022-05-27 04:32:07.000000 big-0.9.1/resources/experiments/alice.in.wonderland.txt
+-rw-r--r--   0        0        0     6060 2023-06-16 06:39:59.562319 big-0.9.1/resources/experiments/time_multisplit.py
+-rw-r--r--   0        0        0  1391641 2022-06-02 13:08:28.000000 big-0.9.1/resources/images/big.header.png
+-rw-r--r--   0        0        0     3531 2023-06-24 07:13:15.776575 big-0.9.1/tests/bigtestlib.py
+-rw-r--r--   0        0        0       50 2023-06-16 06:39:59.562319 big-0.9.1/tests/grepfile
+-rw-r--r--   0        0        0     1468 2023-06-28 11:25:56.173595 big-0.9.1/tests/test_all.py
+-rw-r--r--   0        0        0     8721 2023-06-16 06:39:59.562319 big-0.9.1/tests/test_boundinnerclass.py
+-rw-r--r--   0        0        0     6517 2023-06-28 11:25:56.173595 big-0.9.1/tests/test_builtin.py
+-rw-r--r--   0        0        0     8363 2023-06-16 06:39:59.566320 big-0.9.1/tests/test_file.py
+-rw-r--r--   0        0        0    12333 2023-06-16 06:39:59.566320 big-0.9.1/tests/test_graph.py
+-rw-r--r--   0        0        0     5007 2023-06-16 06:39:59.566320 big-0.9.1/tests/test_heap.py
+-rw-r--r--   0        0        0     3403 2023-06-16 06:39:59.566320 big-0.9.1/tests/test_itertools.py
+-rw-r--r--   0        0        0     4259 2023-06-28 11:25:56.173595 big-0.9.1/tests/test_log.py
+-rw-r--r--   0        0        0    11473 2023-06-16 06:39:59.566320 big-0.9.1/tests/test_scheduler.py
+-rw-r--r--   0        0        0   140256 2023-06-16 06:39:59.566320 big-0.9.1/tests/test_text.py
+-rw-r--r--   0        0        0     6101 2023-06-16 06:39:59.566320 big-0.9.1/tests/test_time.py
+-rw-r--r--   0        0        0   151234 1970-01-01 00:00:00.000000 big-0.9.1/PKG-INFO
```

### Comparing `big-0.9/LICENSE` & `big-0.9.1/LICENSE`

 * *Files identical despite different names*

### Comparing `big-0.9/README.md` & `big-0.9.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -83,28 +83,32 @@
 
 [`big.graph`](#biggraph)
 
 [`big.heap`](#bigheap)
 
 [`big.itertools`](#bigitertools)
 
+[`big.log`](#biglog)
+
 [`big.scheduler`](#bigscheduler)
 
 [`big.text`](#bigtext)
 
 [`big.time`](#bigtime)
 
 [`BoundInnerClass`](#boundinnerclasscls)
 
 [`CycleError`](#cycleerror)
 
 [`datetime_ensure_timezone(d, timezone)`](#datetime_ensure_timezoned-timezone)
 
 [`datetime_set_timezone(d, timezone)`](#datetime_set_timezoned-timezone)
 
+[`default_clock()`](#default_clock)
+
 [`Delimiter(open, close, *, backslash=False, nested=True)`](#delimiteropen-close--backslashfalse-nestedtrue)
 
 [`Event(scheduler, event, time, priority, sequence)`](#eventscheduler-event-time-priority-sequence)
 
 [`Event.cancel()`](#eventcancel)
 
 [`fgrep(path, text, *, encoding=None, enumerate=False, case_insensitive=False)`](#fgreppath-text--encodingnone-enumeratefalse-case_insensitivefalse)
@@ -163,14 +167,24 @@
 
 [`lines_strip(li)`](#lines_stripli)
 
 [`lines_strip_comments(li, comment_separators, *, quotes=('"', "'"), backslash='\\', rstrip=True, triple_quotes=True)`](#lines_strip_commentsli-comment_separators--quotes--backslash-rstriptrue-triple_quotestrue)
 
 [`lines_strip_indent(li)`](#lines_strip_indentli)
 
+[`Log`](#log)
+
+[`Log.enter(subsystem)`](#logentersubsystem)
+
+[`Log.exit()`](#logexit)
+
+[`Log.print(*, print=None, title="[event log]", headings=True, indent=2, seconds_width=2, fractional_width=9)`](#logprint--printnone-titleeventlog-headingstrue-indent2-seconds_width2-fractional_width9)
+
+[`Log.reset()`](#logreset)
+
 [`merge_columns(*columns, column_separator=" ", overflow_response=OverflowResponse.RAISE, overflow_before=0, overflow_after=0)`](#merge_columnscolumns-column_separator--overflow_responseoverflowresponseraise-overflow_before0-overflow_after0)
 
 [`multipartition(s, separators, count=1, *, reverse=False, separate=True)`](#multipartitions-separators-count1--reverseFalse-separateTrue)
 
 [`multisplit(s, separators, *, keep=False, maxsplit=-1, reverse=False, separate=False, strip=False)`](#multisplits-separators--keepFalse-maxsplit-1-reverseFalse-separateFalse-stripFalse)
 
 [`multistrip(s, separators, left=True, right=True)`](#multistrips-separators-leftTrue-rightTrue)
@@ -801,14 +815,110 @@
 > Pushes a value into the iterator's internal stack.
 > When a `PushbackIterator` is iterated over, and there are
 > any pushed values, the top value on the stack will be popped
 > and yielded.  `PushbackIterator` only yields from the
 > iterator it wraps when this internal stack is empty.
 
 
+## `big.log`
+
+A simple and lightweight logging class, useful for performance analysis.
+Not intended as a full-fledged logging facility like Python's
+[`logging`](https://docs.python.org/3/library/logging.html) module.
+
+#### `default_clock()`
+
+> The default clock function used by the `Log` class.
+> This function returns elapsed time in nanoseconds,
+> expressed as an integer.
+>
+> In Python 3.7+,
+> this is `time.monotonic_ns`; in Python 3.6 this is
+> a custom function that calls `time.perf_counter`,
+> then converts that time to requisite format.
+
+#### `Log(*, clock=None)`
+
+> A simple and lightweight logging class, useful for performance analysis.
+> Not intended as a full-fledged logging facility like Python's
+> [`logging`](https://docs.python.org/3/library/logging.html) module.
+>
+> Allows nesting, which is literally just a presentation thing.
+>
+> The `clock` named parameter specifies the function the `Log` object
+> should call to get the time.  This function should return an `int`,
+> representing elapsed time in nanoseconds.
+>
+> To use: first, create your `Log` object.
+>
+>     log = Log()
+>
+> Then log events by calling your `Log` object, passing in
+> a string describing the event.
+>
+>     log('text')
+>
+> Enter a nested subsystem containing events with log.enter:
+>
+>     log.enter('subsystem')
+>
+> Then later exit that subsystem with log.exit:
+>
+>     log.exit()
+>
+> And finally print the log:
+>
+>     log.print()
+>
+> You can also iterate over the log events using `iter(log)`.
+> This yields 4-tuples:
+>
+>     (start_time, elapsed_time, event, depth)
+
+#### `Log.enter(subsystem)`
+
+> Notifies the log that you've entered a subsystem.
+> The `subsystem` parameter should be a string describing the subsystem.
+>
+> This is really just a presentation
+> thing; all subsequent logged entries will be indented
+> until you make the corresponding `log.exit()` call.
+>
+> You may nest subsystems as deeply as you like.
+
+#### `Log.exit()`
+
+> Exits a logged subsystem.  See [`Log.enter.`](#logentersubsystem)
+
+#### `Log.print(*, print=None, title="[event log]", headings=True, indent=2, seconds_width=2, fractional_width=9)`
+
+> Prints the log.
+>
+> Keyword-only parameters:
+>
+> `print` specifies the print function to use, default is `builtins.print`.
+>
+> `title` specifies the title to print at the beginning.
+> Default is `"[event log]"`.  To suppress, pass in `None`.
+>
+> `headings` is a boolean; if `True` (the default),
+> prints column headings for the log.
+>
+> `indent` is the number of spaces to indent in front of log entries,
+> and also how many spaces to indent each time we enter a subsystem.
+>
+> `seconds_width` is how wide to make the seconds column, default 2.
+>
+> `fractional_width` is how wide to make the fractional column, default 9.
+
+#### `Log.reset()`
+
+> Resets the log to its initial state.
+
+
 ## `big.scheduler`
 
 > A replacement for Python's `sched.scheduler` object,
 > adding full threading support and a modern Python interface.
 >
 > Python's `sched.scheduler` object was a clever idea for the
 > time.  It abstracted away the concept of time from its interface,
@@ -2724,15 +2834,15 @@
 
 All lines modifier functions are composable with each
 other; you can "stack" them together simply by passing
 the output of one into the input of another.  For example,
 
 ```Python
      with open("textfile.txt", "rt") as f:
-         for info, lines in big.lines_filter_empty_lines(
+         for info, line in big.lines_filter_empty_lines(
      	     big.lines_rstrip(lines(f.read()))):
      	     ...
 ```
 
 will iterate over the lines of `textfile.txt`, skipping
 over all empty lines and lines that consist only of
 whitespace.
@@ -2741,15 +2851,15 @@
 *outer* modifiers happen *later*.  In the above example,
 each line is first "r-stripped", and then discarded
 if it's empty.  If you stacked the line modifiers in
 the opposite order:
 
 ```Python
      with open("textfile.txt", "rt") as f:
-         for info, lines in big.lines_rstrip(
+         for info, line in big.lines_rstrip(
      	     big.lines_filter_empty_lines(lines(f.read()))):
      	     ...
 ```
 
 then it'd filter out empty lines first, and *then*
 "r-strip" the lines.  So lines in the input that contained
 only whitespace would still get yielded as empty lines,
@@ -3370,14 +3480,20 @@
   class from the `__init__` of the outer class, which should allow
   the code to cache the bound inner class instance before a second
   thread could ever get a reference to the outer object.
 
 
 ## Release history
 
+**0.9.1** *2023/0628*
+
+* Added the new [`big.log`](#biglog) module, with its new [`Log`](#log) class!
+  I wrote this for another project--but it turned out so nice
+  I just had to add it to **big**!
+
 **0.9** *2023/06/15*
 
 * Bugfix!  If an outer class `Outer` had an inner class `Inner`
   decorated with `@BoundInnerClass`, and `o` is an instance of
   `Outer`, and `o` evaluated to false in a boolean context,
   `o.Inner` would be the *unbound* version of `Inner`.  Now
   it's the bound version, as is proper.
```

### Comparing `big-0.9/big/__init__.py` & `big-0.9.1/big/__init__.py`

 * *Files 8% similar despite different names*

```diff
@@ -27,9 +27,9 @@
 IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
 DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
 OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR
 THE USE OR OTHER DEALINGS IN THE SOFTWARE.
 """
 
 
-__version__ = "0.9"
+__version__ = "0.9.1"
```

### Comparing `big-0.9/big/all.py` & `big-0.9.1/big/all.py`

 * *Files 2% similar despite different names*

```diff
@@ -55,14 +55,18 @@
 __all__.extend(heap.__all__)
 from .heap import *
 
 from . import itertools
 __all__.extend(itertools.__all__)
 from .itertools import *
 
+from . import log
+__all__.extend(log.__all__)
+from .log import *
+
 from . import scheduler
 __all__.extend(scheduler.__all__)
 from .scheduler import *
 
 from . import text
 __all__.extend(text.__all__)
 from .text import *
```

### Comparing `big-0.9/big/boundinnerclass.py` & `big-0.9.1/big/boundinnerclass.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/builtin.py` & `big-0.9.1/big/builtin.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/file.py` & `big-0.9.1/big/file.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/graph.py` & `big-0.9.1/big/graph.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/heap.py` & `big-0.9.1/big/heap.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/itertools.py` & `big-0.9.1/big/itertools.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/scheduler.py` & `big-0.9.1/big/scheduler.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/text.py` & `big-0.9.1/big/text.py`

 * *Files identical despite different names*

### Comparing `big-0.9/big/time.py` & `big-0.9.1/big/time.py`

 * *Files identical despite different names*

### Comparing `big-0.9/pyproject.toml` & `big-0.9.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `big-0.9/resources/experiments/alice.in.wonderland.txt` & `big-0.9.1/resources/experiments/alice.in.wonderland.txt`

 * *Files identical despite different names*

### Comparing `big-0.9/resources/experiments/time_multisplit.py` & `big-0.9.1/resources/experiments/time_multisplit.py`

 * *Files identical despite different names*

### Comparing `big-0.9/resources/images/big.header.png` & `big-0.9.1/resources/images/big.header.png`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/bigtestlib.py` & `big-0.9.1/tests/bigtestlib.py`

 * *Files 6% similar despite different names*

```diff
@@ -45,16 +45,17 @@
     }
 
 def preload_local_big():
     """
     Pre-load the local "big" module, to preclude finding
     an already-installed one on the path.
     """
-    from os.path import abspath, dirname, isfile, join, normpath
+    import pathlib
     import sys
+
     argv_0 = pathlib.Path(sys.argv[0])
     big_dir = argv_0.resolve().parent
     while True:
         big_init = big_dir / "big" / "__init__.py"
         if big_init.is_file():
             break
         big_dir = big_dir.parent
```

### Comparing `big-0.9/tests/test_all.py` & `big-0.9.1/tests/test_all.py`

 * *Files 1% similar despite different names*

```diff
@@ -31,14 +31,15 @@
 for test_module in """
     test_boundinnerclass
     test_builtin
     test_file
     test_graph
     test_heap
     test_itertools
+    test_log
     test_scheduler
     test_text
     test_time
 """.strip().split():
     module = __import__(test_module)
     module.run_tests()
```

### Comparing `big-0.9/tests/test_boundinnerclass.py` & `big-0.9.1/tests/test_boundinnerclass.py`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/test_builtin.py` & `big-0.9.1/tests/test_builtin.py`

 * *Files 0% similar despite different names*

```diff
@@ -141,12 +141,12 @@
         self.assertEqual(big.get_int_or_float(d), d)
         self.assertEqual(big.get_int_or_float(3j), 3j)
         self.assertEqual(big.get_int_or_float(None), None)
         self.assertEqual(big.get_int_or_float("abc"), "abc")
 
 
 def run_tests():
-    bigtestlib.run(name="big.__init__", module=__name__)
+    bigtestlib.run(name="big.builtin", module=__name__)
 
 if __name__ == "__main__": # pragma: no cover
     run_tests()
     bigtestlib.finish()
```

### Comparing `big-0.9/tests/test_file.py` & `big-0.9.1/tests/test_file.py`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/test_graph.py` & `big-0.9.1/tests/test_graph.py`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/test_heap.py` & `big-0.9.1/tests/test_heap.py`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/test_itertools.py` & `big-0.9.1/tests/test_itertools.py`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/test_scheduler.py` & `big-0.9.1/tests/test_scheduler.py`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/test_text.py` & `big-0.9.1/tests/test_text.py`

 * *Files identical despite different names*

### Comparing `big-0.9/tests/test_time.py` & `big-0.9.1/tests/test_time.py`

 * *Files identical despite different names*

### Comparing `big-0.9/PKG-INFO` & `big-0.9.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: big
-Version: 0.9
+Version: 0.9.1
 Summary: The big package is a grab-bag of cool code for use in your programs.
 Author-email: Larry Hastings <larry@hastings.org>
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Classifier: Intended Audience :: Developers
 Classifier: License :: CC0 1.0 Universal (CC0 1.0) Public Domain Dedication
 Classifier: Programming Language :: Python :: 3 :: Only
@@ -99,28 +99,32 @@
 
 [`big.graph`](#biggraph)
 
 [`big.heap`](#bigheap)
 
 [`big.itertools`](#bigitertools)
 
+[`big.log`](#biglog)
+
 [`big.scheduler`](#bigscheduler)
 
 [`big.text`](#bigtext)
 
 [`big.time`](#bigtime)
 
 [`BoundInnerClass`](#boundinnerclasscls)
 
 [`CycleError`](#cycleerror)
 
 [`datetime_ensure_timezone(d, timezone)`](#datetime_ensure_timezoned-timezone)
 
 [`datetime_set_timezone(d, timezone)`](#datetime_set_timezoned-timezone)
 
+[`default_clock()`](#default_clock)
+
 [`Delimiter(open, close, *, backslash=False, nested=True)`](#delimiteropen-close--backslashfalse-nestedtrue)
 
 [`Event(scheduler, event, time, priority, sequence)`](#eventscheduler-event-time-priority-sequence)
 
 [`Event.cancel()`](#eventcancel)
 
 [`fgrep(path, text, *, encoding=None, enumerate=False, case_insensitive=False)`](#fgreppath-text--encodingnone-enumeratefalse-case_insensitivefalse)
@@ -179,14 +183,24 @@
 
 [`lines_strip(li)`](#lines_stripli)
 
 [`lines_strip_comments(li, comment_separators, *, quotes=('"', "'"), backslash='\\', rstrip=True, triple_quotes=True)`](#lines_strip_commentsli-comment_separators--quotes--backslash-rstriptrue-triple_quotestrue)
 
 [`lines_strip_indent(li)`](#lines_strip_indentli)
 
+[`Log`](#log)
+
+[`Log.enter(subsystem)`](#logentersubsystem)
+
+[`Log.exit()`](#logexit)
+
+[`Log.print(*, print=None, title="[event log]", headings=True, indent=2, seconds_width=2, fractional_width=9)`](#logprint--printnone-titleeventlog-headingstrue-indent2-seconds_width2-fractional_width9)
+
+[`Log.reset()`](#logreset)
+
 [`merge_columns(*columns, column_separator=" ", overflow_response=OverflowResponse.RAISE, overflow_before=0, overflow_after=0)`](#merge_columnscolumns-column_separator--overflow_responseoverflowresponseraise-overflow_before0-overflow_after0)
 
 [`multipartition(s, separators, count=1, *, reverse=False, separate=True)`](#multipartitions-separators-count1--reverseFalse-separateTrue)
 
 [`multisplit(s, separators, *, keep=False, maxsplit=-1, reverse=False, separate=False, strip=False)`](#multisplits-separators--keepFalse-maxsplit-1-reverseFalse-separateFalse-stripFalse)
 
 [`multistrip(s, separators, left=True, right=True)`](#multistrips-separators-leftTrue-rightTrue)
@@ -817,14 +831,110 @@
 > Pushes a value into the iterator's internal stack.
 > When a `PushbackIterator` is iterated over, and there are
 > any pushed values, the top value on the stack will be popped
 > and yielded.  `PushbackIterator` only yields from the
 > iterator it wraps when this internal stack is empty.
 
 
+## `big.log`
+
+A simple and lightweight logging class, useful for performance analysis.
+Not intended as a full-fledged logging facility like Python's
+[`logging`](https://docs.python.org/3/library/logging.html) module.
+
+#### `default_clock()`
+
+> The default clock function used by the `Log` class.
+> This function returns elapsed time in nanoseconds,
+> expressed as an integer.
+>
+> In Python 3.7+,
+> this is `time.monotonic_ns`; in Python 3.6 this is
+> a custom function that calls `time.perf_counter`,
+> then converts that time to requisite format.
+
+#### `Log(*, clock=None)`
+
+> A simple and lightweight logging class, useful for performance analysis.
+> Not intended as a full-fledged logging facility like Python's
+> [`logging`](https://docs.python.org/3/library/logging.html) module.
+>
+> Allows nesting, which is literally just a presentation thing.
+>
+> The `clock` named parameter specifies the function the `Log` object
+> should call to get the time.  This function should return an `int`,
+> representing elapsed time in nanoseconds.
+>
+> To use: first, create your `Log` object.
+>
+>     log = Log()
+>
+> Then log events by calling your `Log` object, passing in
+> a string describing the event.
+>
+>     log('text')
+>
+> Enter a nested subsystem containing events with log.enter:
+>
+>     log.enter('subsystem')
+>
+> Then later exit that subsystem with log.exit:
+>
+>     log.exit()
+>
+> And finally print the log:
+>
+>     log.print()
+>
+> You can also iterate over the log events using `iter(log)`.
+> This yields 4-tuples:
+>
+>     (start_time, elapsed_time, event, depth)
+
+#### `Log.enter(subsystem)`
+
+> Notifies the log that you've entered a subsystem.
+> The `subsystem` parameter should be a string describing the subsystem.
+>
+> This is really just a presentation
+> thing; all subsequent logged entries will be indented
+> until you make the corresponding `log.exit()` call.
+>
+> You may nest subsystems as deeply as you like.
+
+#### `Log.exit()`
+
+> Exits a logged subsystem.  See [`Log.enter.`](#logentersubsystem)
+
+#### `Log.print(*, print=None, title="[event log]", headings=True, indent=2, seconds_width=2, fractional_width=9)`
+
+> Prints the log.
+>
+> Keyword-only parameters:
+>
+> `print` specifies the print function to use, default is `builtins.print`.
+>
+> `title` specifies the title to print at the beginning.
+> Default is `"[event log]"`.  To suppress, pass in `None`.
+>
+> `headings` is a boolean; if `True` (the default),
+> prints column headings for the log.
+>
+> `indent` is the number of spaces to indent in front of log entries,
+> and also how many spaces to indent each time we enter a subsystem.
+>
+> `seconds_width` is how wide to make the seconds column, default 2.
+>
+> `fractional_width` is how wide to make the fractional column, default 9.
+
+#### `Log.reset()`
+
+> Resets the log to its initial state.
+
+
 ## `big.scheduler`
 
 > A replacement for Python's `sched.scheduler` object,
 > adding full threading support and a modern Python interface.
 >
 > Python's `sched.scheduler` object was a clever idea for the
 > time.  It abstracted away the concept of time from its interface,
@@ -2740,15 +2850,15 @@
 
 All lines modifier functions are composable with each
 other; you can "stack" them together simply by passing
 the output of one into the input of another.  For example,
 
 ```Python
      with open("textfile.txt", "rt") as f:
-         for info, lines in big.lines_filter_empty_lines(
+         for info, line in big.lines_filter_empty_lines(
      	     big.lines_rstrip(lines(f.read()))):
      	     ...
 ```
 
 will iterate over the lines of `textfile.txt`, skipping
 over all empty lines and lines that consist only of
 whitespace.
@@ -2757,15 +2867,15 @@
 *outer* modifiers happen *later*.  In the above example,
 each line is first "r-stripped", and then discarded
 if it's empty.  If you stacked the line modifiers in
 the opposite order:
 
 ```Python
      with open("textfile.txt", "rt") as f:
-         for info, lines in big.lines_rstrip(
+         for info, line in big.lines_rstrip(
      	     big.lines_filter_empty_lines(lines(f.read()))):
      	     ...
 ```
 
 then it'd filter out empty lines first, and *then*
 "r-strip" the lines.  So lines in the input that contained
 only whitespace would still get yielded as empty lines,
@@ -3386,14 +3496,20 @@
   class from the `__init__` of the outer class, which should allow
   the code to cache the bound inner class instance before a second
   thread could ever get a reference to the outer object.
 
 
 ## Release history
 
+**0.9.1** *2023/0628*
+
+* Added the new [`big.log`](#biglog) module, with its new [`Log`](#log) class!
+  I wrote this for another project--but it turned out so nice
+  I just had to add it to **big**!
+
 **0.9** *2023/06/15*
 
 * Bugfix!  If an outer class `Outer` had an inner class `Inner`
   decorated with `@BoundInnerClass`, and `o` is an instance of
   `Outer`, and `o` evaluated to false in a boolean context,
   `o.Inner` would be the *unbound* version of `Inner`.  Now
   it's the bound version, as is proper.
```

