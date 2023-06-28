# Comparing `tmp/stockstats-0.5.4.tar.gz` & `tmp/stockstats-0.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "stockstats-0.5.4.tar", last modified: Wed Jun 14 15:41:15 2023, max compression
+gzip compressed data, was "stockstats-0.6.0.tar", last modified: Wed Jun 28 15:31:11 2023, max compression
```

## Comparing `stockstats-0.5.4.tar` & `stockstats-0.6.0.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 15:41:15.825227 stockstats-0.5.4/
--rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-06-14 15:41:05.000000 stockstats-0.5.4/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-14 15:41:05.000000 stockstats-0.5.4/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    26076 2023-06-14 15:41:15.825227 stockstats-0.5.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    25144 2023-06-14 15:41:05.000000 stockstats-0.5.4/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-14 15:41:05.000000 stockstats-0.5.4/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-14 15:41:15.825227 stockstats-0.5.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     3667 2023-06-14 15:41:05.000000 stockstats-0.5.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 15:41:15.825227 stockstats-0.5.4/stockstats.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    26076 2023-06-14 15:41:15.000000 stockstats-0.5.4/stockstats.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      274 2023-06-14 15:41:15.000000 stockstats-0.5.4/stockstats.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-14 15:41:15.000000 stockstats-0.5.4/stockstats.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-14 15:41:15.000000 stockstats-0.5.4/stockstats.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-14 15:41:15.000000 stockstats-0.5.4/stockstats.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)    49577 2023-06-14 15:41:05.000000 stockstats-0.5.4/stockstats.py
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-14 15:41:05.000000 stockstats-0.5.4/test-requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:11.017164 stockstats-0.6.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-06-28 15:31:01.000000 stockstats-0.6.0/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 15:31:01.000000 stockstats-0.6.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    34252 2023-06-28 15:31:11.017164 stockstats-0.6.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    33320 2023-06-28 15:31:01.000000 stockstats-0.6.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 15:31:01.000000 stockstats-0.6.0/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-28 15:31:11.017164 stockstats-0.6.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     3667 2023-06-28 15:31:01.000000 stockstats-0.6.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:31:11.017164 stockstats-0.6.0/stockstats.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    34252 2023-06-28 15:31:11.000000 stockstats-0.6.0/stockstats.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      274 2023-06-28 15:31:11.000000 stockstats-0.6.0/stockstats.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:31:11.000000 stockstats-0.6.0/stockstats.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 15:31:11.000000 stockstats-0.6.0/stockstats.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-28 15:31:11.000000 stockstats-0.6.0/stockstats.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    58155 2023-06-28 15:31:01.000000 stockstats-0.6.0/stockstats.py
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 15:31:01.000000 stockstats-0.6.0/test-requirements.txt
```

### Comparing `stockstats-0.5.4/LICENSE.txt` & `stockstats-0.6.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `stockstats-0.5.4/PKG-INFO` & `stockstats-0.6.0/README.md`

 * *Files 20% similar despite different names*

```diff
@@ -1,48 +1,22 @@
-Metadata-Version: 2.1
-Name: stockstats
-Version: 0.5.4
-Summary: DataFrame with inline stock statistics support.
-Home-page: https://github.com/jealous/stockstats
-Author: Cedric Zhuang
-Author-email: jealous@163.com
-License: BSD
-Keywords: stock statistics indicator
-Platform: any
-Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 2.7
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Natural Language :: English
-Classifier: Intended Audience :: Developers
-Classifier: Intended Audience :: Financial and Insurance Industry
-Classifier: Operating System :: OS Independent
-Classifier: Development Status :: 4 - Beta
-Classifier: Topic :: Utilities
-Classifier: License :: OSI Approved :: BSD License
-Description-Content-Type: text/markdown
-License-File: LICENSE.txt
-
 # Stock Statistics/Indicators Calculation Helper
 
 [![build & test](https://github.com/jealous/stockstats/actions/workflows/build-test.yml/badge.svg)](https://github.com/jealous/stockstats/actions/workflows/build-test.yml)
 [![codecov](https://codecov.io/gh/jealous/stockstats/branch/master/graph/badge.svg?token=IFMD1pVJ7T)](https://codecov.io/gh/jealous/stockstats)
 [![pypi](https://img.shields.io/pypi/v/stockstats.svg)](https://pypi.python.org/pypi/stockstats)
 
-VERSION: 0.5.4
+VERSION: 0.6.0
 
 ## Introduction
 
 Supply a wrapper ``StockDataFrame`` for ``pandas.DataFrame`` with inline stock
 statistics/indicators support.
 
 Supported statistics/indicators are:
 
-* change (in percent)
 * delta
 * permutation (zero-based)
 * log return
 * max in range
 * min in range
 * middle = (close + high + low) / 3
 * compare: le, ge, lt, gt, eq, ne
@@ -70,22 +44,33 @@
     * ADXR: Smoothed Moving Average of ADX
 * TRIX: Triple Exponential Moving Average
 * TEMA: Another Triple Exponential Moving Average
 * VR: Volume Variation Index
 * MFI: Money Flow Index
 * VWMA: Volume Weighted Moving Average
 * CHOP: Choppiness Index
+* KER: Kaufman's efficiency ratio
 * KAMA: Kaufman's Adaptive Moving Average
 * PPO: Percentage Price Oscillator
 * StochRSI: Stochastic RSI
 * WT: LazyBear's Wave Trend
 * Supertrend: with the Upper Band and Lower Band
 * Aroon: Aroon Oscillator
 * Z: Z-Score
 * AO: Awesome Oscillator
+* BOP: Balance of Power
+* MAD: Mean Absolute Deviation
+* ROC: Rate of Change
+* Coppock: Coppock Curve
+* Ichimoku: Ichimoku Cloud
+* CTI: Correlation Trend Indicator
+* LRMA: Linear Regression Moving Average
+* ERI: Elder-Ray Index
+* FTR: the Gaussian Fisher Transform Price Reversals indicator
+* RVGI: Relative Vigor Index
 
 ## Installation
 
 ```pip install stockstats```
 
 ## Compatibility
 
@@ -210,18 +195,14 @@
 
 ### Statistics/Indicators
 
 Some statistics have configurable parameters. They are class-level fields. Change
 of these fields is global. And they won't affect the existing results. Removing
 existing columns so that they will be re-evaluated the next time you access them.
 
-#### Change of the Close
-
-`df['change']` is the change of the `close` price in percentage.
-
 #### Delta of Periods
 
 Using pattern `<column>_<window>_d` to retrieve the delta between different periods.
 
 You can also use `<column>_delta` as a shortcut to `<column>_-1_d` 
 
 Examples:
@@ -257,15 +238,15 @@
 
 [2813 rows x 3 columns]
 ```
 
 #### [RSI - Relative Strength Index](https://en.wikipedia.org/wiki/Relative_strength_index)
 
 RSI has a configurable window. The default window size is 14 which is
-configurable through `StockDataFrame.RSI`. e.g.
+configurable through `set_dft_window('rsi', n)`. e.g.
 
 * `df['rsi']`: 14 periods RSI
 * `df['rsi_6']`: 6 periods RSI
 
 #### [Log Return of the Close](https://en.wikipedia.org/wiki/Rate_of_return)
 
 Logarithmic return = ln( close / last close)
@@ -351,47 +332,84 @@
 Use `df['rsv']` or `df['rsv_6']` to access it.
 
 #### [RSI - Relative Strength Index](https://en.wikipedia.org/wiki/Relative_strength_index)
 
 RSI chart the current and historical strength or weakness of a stock. It takes 
 a window parameter.
 
-The default window is 14. Use `StockDataFrame.RSI` to tune it.
+The default window is 14. Use `set_dft_window('rsi', n)` to tune it.
 
 Examples:
 
 * `df['rsi']`: retrieve the RSI of 14 periods
 * `df['rsi_6']`: retrieve the RSI of 6 periods
 
 #### [Stochastic RSI](https://www.investopedia.com/terms/s/stochrsi.asp)
 
 Stochastic RSI gives traders an idea of whether the current RSI value is 
 overbought or oversold. It takes a window parameter.
 
-The default window is 14. Use `StockDataFrame.RSI` to tune it.
+The default window is 14. Use `set_dft_window('stochrsi', n)` to tune it.
 
 Examples:
 
 * `df['stochrsi']`: retrieve the Stochastic RSI of 14 periods
 * `df['stochrsi_6']`: retrieve the Stochastic RSI of 6 periods
 
 #### [WT - Wave Trend](https://medium.com/@samuel.mcculloch/lets-take-a-look-at-wavetrend-with-crosses-lazybear-s-indicator-2ece1737f72f)
 
 Retrieve the LazyBear's Wave Trend with `df['wt1']` and `df['wt2']`.
 
 Wave trend uses two parameters. You can tune them with
-`StockDataFrame.WAVE_TREND_1` and `StockDataFrame.WAVE_TREND_2`.
+`set_dft_window('wt', (10, 21))`.
 
 #### SMMA - Smoothed Moving Average
 
 It requires column and window.
 
 For example, use `df['close_7_smma']` to retrieve the 7 periods smoothed moving
 average of the close price.
 
+#### [ROC - Rate of Change](https://www.investopedia.com/terms/p/pricerateofchange.asp)
+
+The Price Rate of Change (ROC) is a momentum-based technical indicator 
+that measures the percentage change in price between the current price 
+and the price a certain number of periods ago.
+
+Formular:
+
+ROC = (PriceP - PricePn) / PricePn * 100
+
+Where:
+* PriceP: the price of the current period
+* PricePn: the price of the n periods ago
+
+You need a column name and a period to calculate ROC.
+
+Examples:
+* `df['close_10_roc']`: the ROC of the close price in 10 periods
+* `df['high_5_roc']`: the ROC of the high price in 5 periods
+
+#### [MAD - Mean Absolute Deviation](https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/other-measures-of-spread/a/mean-absolute-deviation-mad-review)
+
+The mean absolute deviation of a dataset is the average
+distance between each data point and the mean. It gives 
+us an idea about the variability in a dataset.
+
+Formular:
+1. Calculate the mean.
+2. Calculate how far away each data point is from the 
+   mean using positive distances. These are called 
+   absolute deviations.
+3. Add those deviations together.
+4. Divide the sum by the number of data points.
+
+Example:
+* `df['close_10_mad']`: the MAD of the close price in 10 periods
+
 #### [TRIX - Triple Exponential Average](https://www.investopedia.com/articles/technical/02/092402.asp)
 
 The triple exponential average is used to identify oversold and overbought 
 markets.
 
 The algorithm is:
 
@@ -400,15 +418,15 @@
 TripleEMA = EMA of EMA of EMA
 LastTripleEMA =  TripleEMA of the last period
 ```
 
 It requires column and window. By default, the column is `close`,
 the window is 12.
 
-Use `StockDataFrame.TRIX_EMA_WINDOW` to change the default window.
+Use `set_dft_window('trix', n)` to change the default window.
 
 Examples:
 
 * `df['trix']` stands for 12 periods Trix for the close price.
 * `df['middle_10_trix']` stands for the 10 periods Trix for the typical price.
 
 #### [TEMA - Another Triple Exponential Average](https://www.forextraders.com/forex-education/forex-technical-analysis/triple-exponential-moving-average-the-tema-indicator/)
@@ -418,51 +436,51 @@
 ```
 TEMA=(3 x EMA) - (3 x EMA of EMA) + (EMA of EMA of EMA)
 ```
 
 It takes two parameters, column and window. By default, the column is `close`,
 the window is 5.
 
-Use `StockDataFrame.TEMA_EMA_WINDOW` to change the default window.
+Use `set_dft_window('tema', n)` to change the default window.
 
 Examples:
 
 * `df['tema']` stands for 12 periods TEMA for the close price.
 * `df['middle_10_tema']` stands for the 10 periods TEMA for the typical price.
 
 #### [VR - Volume Variation Index](https://help.eaglesmarkets.com/hc/en-us/articles/900002867026-Summary-of-volume-variation-index)
 
 It is the strength index of the trading volume.
 
-It has a default window of 26. Change it with `StockDataFrame.VR`.
+It has a default window of 26. Change it with `set_dft_window('vr', n)`.
 
 Examples:
 * `df['vr']` retrieves the 26 periods VR.
 * `df['vr_6']` retrieves the 6 periods VR.
 
 #### [WR - Williams Overbought/Oversold Index](https://www.investopedia.com/terms/w/williamsr.asp)
 
 Williams Overbought/Oversold index
 is a type of momentum indicator that moves between 0 and -100 and measures
 overbought and oversold levels.
 
-It takes a window parameter. The default window is 14. Use `StockDataFrame.WR`
+It takes a window parameter. The default window is 14. Use `set_dft_window('wr', n)`
 to change the default window.
 
 Examples:
 
 * `df['wr']` retrieves the 14 periods WR.
 * `df['wr_6']` retrieves the 6 periods WR.
 
 #### [CCI - Commodity Channel Index](https://www.investopedia.com/terms/c/commoditychannelindex.asp)
 
 CCI stands for Commodity Channel Index.
 
 It requires a window parameter. The default window is 14. Use
-`StockDataFrame.CCI` to change it.
+`set_dft_window('cci', n)` to change it.
 
 Examples:
 
 * `df['cci']` retrieves the default 14 periods CCI.
 * `df['cci_6']` retrieves the 6 periods CCI.
 
 #### TR - True Range of Trading
@@ -472,15 +490,15 @@
 
 #### [ATR - Average True Range](https://en.wikipedia.org/wiki/Average_true_range)
 
 The Average True Range is an
 N-period smoothed moving average (SMMA) of the true range value.  
 Default to 14 periods.
 
-Users can modify the default window with `StockDataFrame.ATR_SMMA`.
+Users can modify the default window with `set_dft_window('atr', n)`.
 
 Example:
 
 * `df['atr']` retrieves the 14 periods ATR.
 * `df['atr_5']` retrieves the 5 periods ATR.
 
 #### [Supertrend](https://economictimes.indiatimes.com/markets/stocks/news/how-to-use-supertrend-indicator-to-find-buying-and-selling-opportunities-in-market/articleshow/54492970.cms)
@@ -490,70 +508,73 @@
 It includes 3 lines:
 * `df['supertrend']` is the trend line.
 * `df['supertrend_ub']` is the upper band of the trend
 * `df['supertrend_lb']` is the lower band of the trend
 
 It has 2 parameters:
 * `StockDataFrame.SUPERTREND_MUL` is the multiplier of the band, default to 3.
-* `StockDataFrame.SUPERTREND_WINDOW` is the window size, default to 14.
+* the default window size is 14.  Change it with `set_dft_window('supertrend', n)`
 
 #### DMA - Difference of Moving Average
 
 `df['dma']` retrieves the difference of 10 periods SMA of the close price and
 the 50 periods SMA of the close price.
 
 #### [DMI - Directional Movement Index](https://www.investopedia.com/terms/d/dmi.asp)
 
 The directional movement index (DMI)
 identifies in which direction the price of an asset is moving.
 
 It has several lines:
 
 * `df['pdi']` is the positive directional movement line (+DI)
-* `df['mdi']` is the negative directional movement line (-DI)
+* `df['ndi']` is the negative directional movement line (-DI)
 * `df['dx']` is the directional index (DX)
 * `df['adx']` is the average directional index (ADX)
 * `df['adxr']` is an EMA for ADX
 
 It has several parameters.
 
-* `StockDataFrame.PDI_SMMA` - window for +DI
-* `StockDataFrame.MDI_SMMA` - window for -DI
-* `StockDataFrame.DX_SMMA` - window for DX
-* `StockDataFrame.ADX_EMA` - window for ADX
-* `StockDataFrame.ADXR_EMA` - window for ADXR
+* default window for +DI is 14, change it with `set_dft_window('pdi', n)`
+* default window for -DI is 14, change it with `set_dft_window('ndi', n)`
+* `StockDataFrame.DX_SMMA` - window for DX, default to 14
+* `StockDataFrame.ADX_EMA` - window for ADX, default to 6
+* `StockDataFrame.ADXR_EMA` - window for ADXR, default to 6
 
 #### [KDJ Indicator](https://en.wikipedia.org/wiki/Stochastic_oscillator)
 
-The stochastic oscillator is a momentum indicator that uses support and 
+The stochastic oscillator is a momenxtum indicator that uses support and 
 resistance levels.
 
 It includes three lines:
 * `df['kdjk']` - K series
 * `df['kdjd']` - D series
 * `df['kdjj']` - J series
 
-The default window is 9.  Use `StockDataFrame.KDJ_WINDOW` to change it.
+The default window is 9.  Use `set_dft_window('kdjk', n)` to change it.
 Use `df['kdjk_6']` to retrieve the K series of 6 periods.
 
 KDJ also has two configurable parameters named `StockDataFrame.KDJ_PARAM`.
 The default value is `(2.0/3.0, 1.0/3.0)`
 
 #### [CR - Energy Index](https://support.futunn.com/en/topic167/?lang=en-us)
 
 The Energy Index (Intermediate Willingness Index)
 uses the relationship between the highest price, the lowest price and
 yesterday's middle price to reflect the market's willingness to buy
 and sell.
 
 It contains 4 lines:
 * `df['cr']` - the CR line
-* `df['cr-ma1']` - `StockDataFrame.CR_MA1` periods of the CR moving average
-* `df['cr-ma2']` - `StockDataFrame.CR_MA2` periods of the CR moving average
-* `df['cr-ma3']` - `StockDataFrame.CR_MA3` periods of the CR moving average
+* `df['cr-ma1']` - `StockDataFrame.CR_MA[0]` periods of the CR moving average,
+  the default window is 5
+* `df['cr-ma2']` - `StockDataFrame.CR_MA[1]` periods of the CR moving average,
+  the default window is 10
+* `df['cr-ma3']` - `StockDataFrame.CR_MA[2]` periods of the CR moving average,
+  the default window is 20
 
 #### [Typical Price](https://en.wikipedia.org/wiki/Typical_price)
 
 It's the average of `high`, `low` and `close`.
 Use `df['middle']` to access this value.
 
 When `amount` is available, `middle = amount / volume`
@@ -562,50 +583,44 @@
 #### [Bollinger Bands](https://en.wikipedia.org/wiki/Bollinger_Bands)
 
 The Bollinger bands includes three lines
 * `df['boll']` is the baseline
 * `df['boll_ub']` is the upper band
 * `df['boll_lb']` is the lower band
 
-The default window of boll is defined by `BOLL_PERIOD`.  The default value is 20.
+The default window of boll is 20.
 You can also supply your window with `df['boll_10']`.  It will also
 generate the `boll_ub_10` and `boll_lb_10` column.
 
 The default period of the Bollinger Band can be changed with
-`StockDataFrame.BOLL_PERIOD`.  The width of the bands can be turned with
+`set_dft_window('boll', n)`.  The width of the bands can be turned with
 `StockDataFrame.BOLL_STD_TIMES`.  The default value is 2.
 
 #### [MACD - Moving Average Convergence Divergence](https://en.wikipedia.org/wiki/MACD)
 
 We use the close price to calculate the MACD lines.
 * `df['macd']` is the difference between two exponential moving averages.
 * `df['macds]` is the signal line.
 * `df['macdh']` is he histogram line.
 
-The period of short and long EMA can be tuned with 
-`StockDataFrame.MACD_EMA_SHORT` and `StockDataFrame.MACD_EMA_LONG`.  The default
-value are 12 and 26
-
-The period of the signal line can be tuned with 
-`StockDataFrame.MACD_EMA_SIGNAL`. The default value is 9.
+The period of short, long EMA and signal line can be tuned with 
+`set_dft_window('macd', (short, long, signal))`.  The default
+windows are 12 and 26 and 9.
 
 #### [PPO - Percentage Price Oscillator](https://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:price_oscillators_ppo)
 
 The Percentage Price Oscillator includes three lines.
 
 * `df['ppo']` derives from the difference of 2 exponential moving average.
 * `df['ppos]` is the signal line.
 * `df['ppoh']` is he histogram line.
 
-The period of short and long EMA can be tuned with 
-`StockDataFrame.PPO_EMA_SHORT` and `StockDataFrame.PPO_EMA_LONG`.  The default
-value are 12 and 26
-
-The period of the signal line can be tuned with 
-`StockDataFrame.PPO_EMA_SIGNAL`. The default value is 9.
+The period of short, long EMA and signal line can be tuned with 
+`set_dft_window('ppo', (short, long, signal))`.  The default
+windows are 12 and 26 and 9.
 
 #### [Simple Moving Average](https://www.investopedia.com/terms/m/mean.asp)
 
 Follow the pattern `<columnName>_<window>_sma` to retrieve a simple moving average.
 
 #### [Moving Standard Deviation](https://www.investopedia.com/terms/s/standarddeviation.asp)
 
@@ -616,61 +631,105 @@
 Follow the pattern `<columnName>_<window>_mvar` to retrieve the moving VAR.
 
 #### [Volume Weighted Moving Average](https://www.investopedia.com/articles/trading/11/trading-with-vwap-mvwap.asp)
 
 It's the moving average weighted by volume.
 
 It has a parameter for window size.  The default window is 14.  Change it with
-`StockDataFrame.VWMA`.
+`set_dft_window('vwma', n)`.
 
 Examples:
 * `df['vwma']` retrieves the 14 periods VWMA
 * `df['vwma_6']` retrieves the 6 periods VWMA
 
 #### [CHOP - Choppiness Index](https://www.tradingview.com/education/choppinessindex/)
 
 The Choppiness Index determines if the market is choppy.
 
 It has a parameter for window size.  The default window is 14.  Change it with
-`StockDataFrame.CHOP`.
+`set_dft_window('chop', n)`.
 
 Examples:
 * `df['chop']` retrieves the 14 periods CHOP
 * `df['chop_6']` retrieves the 6 periods CHOP
 
 #### [MFI - Money Flow Index](https://www.investopedia.com/terms/m/mfi.asp)
 
 The Money Flow Index
 identifies overbought or oversold signals in an asset.
 
 It has a parameter for window size.  The default window is 14.  Change it with
-`StockDataFrame.MFI`.
+`set_dft_window('mfi', n)`.
 
 Examples:
 * `df['mfi']` retrieves the 14 periods MFI
 * `df['mfi_6']` retrieves the 6 periods MFI
 
+#### [ERI - Elder-Ray Index](https://admiralmarkets.com/education/articles/forex-indicators/bears-and-bulls-power-indicator)
+
+The Elder-Ray Index contains the bull and the bear power.
+Both are calculated based on the EMA of the close price.
+
+The default window is 13.
+
+Formular:
+* Bulls Power = High - EMA
+* Bears Power = Low - EMA
+* EMA is exponential moving average of close of N periods
+
+Examples:
+* `df['eribull']` retrieves the 13 periods bull power
+* `df['eribear']` retrieves the 13 periods bear power
+* `df['eribull_5']` retrieves the 5 periods bull power
+* `df['eribear_5']` retrieves the 5 periods bear power
+
+#### [KER - Kaufman's efficiency ratio](https://strategyquant.com/codebase/kaufmans-efficiency-ratio-ker/)
+
+The Efficiency Ratio (ER) is calculated by
+dividing the price change over a period by the
+absolute sum of the price movements that occurred
+to achieve that change.
+
+The resulting ratio ranges between 0 and 1 with
+higher values representing a more efficient or
+trending market.
+
+The default column is close.
+
+The default window is 10.
+
+Formular:
+* window_change = ABS(close - close[n])
+* last_change = ABS(close-close[1])
+* volatility = moving sum of last_change in n
+* KER = window_change / volatility
+
+Examples:
+* `df['ker']` retrieves the 10 periods KER of the close price
+* `df['high_5_ker']` retrieves 5 periods KER of the high price
+
 #### [KAMA - Kaufman's Adaptive Moving Average](https://school.stockcharts.com/doku.php?id=technical_indicators:kaufman_s_adaptive_moving_average)
 
 Kaufman's Adaptive Moving Average is designed to account for market noise or 
 volatility.
 
 It has 2 optional parameters and 2 required parameters
 * fast - optional, the parameter for fast EMA smoothing, default to 5
 * slow - optional, the parameter for slow EMA smoothing, default to 34
 * column - required, the column to calculate
 * window - required, rolling window size
 
-The default value for fast and slow can be configured with
-`StockDataFrame.KAMA_FAST` and `StockDataFrame.KAMA_SLOW`
+The default value for window, fast and slow can be configured with
+`set_dft_window('kama', (10, 5, 34))`
 
 Examples:
-* `df['close_10_kama_2_30']` retrieves 10 periods KAMA of the close price with 
-  `fast = 2` and `slow = 30`
+* `df['close_10,2,30_kama']` retrieves 10 periods KAMA of the close 
+  price with `fast = 2` and `slow = 30`
 * `df['close_2_kama']` retrieves 2 periods KAMA of the close price
+  with default fast and slow
 
 #### Cross Upwards and Cross Downwards
 
 Use the pattern `<A>_xu_<B>` to check when A crosses up B.
 
 Use the pattern `<A>_xd_<B>` to check when A crosses down B.
 
@@ -703,15 +762,17 @@
 the mean of a group of values. 
 
 There is no default column name or window for Z-Score.
 
 The statistical formula for a value's z-score is calculated using
 the following formula:
 
-```z = ( x - μ ) / σ```
+```
+z = ( x - μ ) / σ
+```
 
 Where:
 
 * `z` = Z-score
 * `x` = the value being evaluated
 * `μ` = the mean
 * `σ` = the standard deviation
@@ -731,14 +792,178 @@
 * MEDIAN PRICE = (HIGH+LOW)/2
 * AO = SMA(MEDIAN PRICE, 5)-SMA(MEDIAN PRICE, 34)
 
 Examples:
 * `df['ao']` returns the Awesome Oscillator with default windows (5, 34)
 * `df['ao_3,10']` returns the Awesome Oscillator with a window of 3 and 10
 
+#### [Balance of Power](https://school.stockcharts.com/doku.php?id=technical_indicators:balance_of_power)
+
+Balance of Power (BOP) measures the strength of the bulls vs. bears.
+
+Formular:
+```
+BOP = (close - open) / (high - low)
+```
+
+Example:
+* `df['bop']` returns the Balance of Power
+
+#### [Chande Momentum Oscillator] (https://www.investopedia.com/terms/c/chandemomentumoscillator.asp)
+
+The Chande Momentum Oscillator (CMO) is a technical momentum 
+indicator developed by Tushar Chande.
+
+The formula calculates the difference between the sum of recent 
+gains and the sum of recent losses and then divides the result 
+by the sum of all price movements over the same period.
+
+The default window is 14.
+
+Formular:
+```
+CMO = 100 * ((sH - sL) / (sH + sL))
+```
+
+where:
+* sH=the sum of higher closes over N periods
+* sL=the sum of lower closes of N periods
+
+Examples:
+* `df['cmo']` returns the CMO with a window of 14
+* `df['cmo_5']` returns the CMO with a window of 5
+
+#### [Coppock Curve](https://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:coppock_curve)
+
+Coppock Curve is a momentum indicator that signals
+long-term trend reversals.
+
+Formular:
+
+Coppock Curve = 10-period WMA of (14-period RoC + 11-period RoC)
+WMA = Weighted Moving Average
+RoC = Rate-of-Change
+
+Examples:
+* `df['coppock']` returns the Coppock Curve with default windows
+* `df['coppock_5,10,15']` returns the Coppock Curve with WMA window 5,
+  fast window 10, slow window 15. 
+
+#### [Ichimoku Cloud](https://www.investopedia.com/terms/i/ichimoku-cloud.asp)
+
+The Ichimoku Cloud is a collection of technical indicators
+that show support and resistance levels, as well as momentum
+and trend direction.
+
+In this implementation, we only calculate the delta between
+lead A and lead B (which is the width of the cloud).
+
+It contains three windows:
+* window for the conversion line, default to 9
+* window for the baseline and the shifts, default to 26
+* window for the leading line, default to 52
+
+Formular:
+* conversion line = (PH9 + PL9) / 2
+* baseline = (PH26 + PL26) / 2
+* leading span A = (conversion line + baseline) / 2
+* leading span B = (PH52 + PL52) / 2
+* result = leading span A - leading span B
+
+Where:
+* PH = Period High
+* PL = Period Low
+
+Examples:
+* `df['ichimoku']` returns the ichimoku cloud width with default windows
+* `df['ichimoku_7,22,44']` returns the ichimoku cloud width with window sizes
+  7, 22, 44
+
+#### [Linear Regression Moving Average](https://www.daytrading.com/moving-linear-regression)
+
+Linear regression works by taking various data points in a sample and
+providing a “best fit” line to match the general trend in the data. 
+
+Implementation reference:
+
+https://github.com/twopirllc/pandas-ta/blob/main/pandas_ta/overlap/linreg.py
+
+Examples:
+* `df['close_10_lrma']` linear regression of close price with window size 10
+
+#### [Correlation Trend Indicator](https://tlc.thinkorswim.com/center/reference/Tech-Indicators/studies-library/C-D/CorrelationTrendIndicator)
+
+Correlation Trend Indicator is a study that estimates
+the current direction and strength of a trend.
+
+Implementation is based on the following code:
+
+https://github.com/twopirllc/pandas-ta/blob/main/pandas_ta/momentum/cti.py
+
+Examples:
+* `df['cti']` returns the CTI of close price with window 12
+* `df['high_5_cti']` returns the CTI of high price with window 5
+
+#### [the Gaussian Fisher Transform Price Reversals indicator](https://www.tradingview.com/script/ajZT2tZo-Gaussian-Fisher-Transform-Price-Reversals-FTR/)
+
+The Gaussian Fisher Transform Price Reversals indicator, dubbed
+FTR for short, is a stat based price reversal detection indicator
+inspired by and based on the work of the electrical engineer
+now private trader John F. Ehlers.
+
+https://www.tradingview.com/script/ajZT2tZo-Gaussian-Fisher-Transform-Price-Reversals-FTR/
+
+Implementation reference:
+
+https://github.com/twopirllc/pandas-ta/blob/084dbe1c4b76082f383fa3029270ea9ac35e4dc7/pandas_ta/momentum/fisher.py#L9
+
+Formular:
+* Fisher Transform = 0.5 * ln((1 + X) / (1 - X))
+* X is a series whose values are between -1 to 1
+
+Examples:
+* `df['ftr']` returns the FTR with window 9
+* `df['ftr_20']` returns the FTR with window 20
+
+#### [Relative Vigor Index (RVGI)](https://www.investopedia.com/terms/r/relative_vigor_index.asp)
+
+The Relative Vigor Index (RVI) is a momentum indicator
+used in technical analysis that measures the strength
+of a trend by comparing a security's closing price to
+its trading range while smoothing the results using a
+simple moving average (SMA).
+
+Formular
+
+* NUMERATOR= (a+(2×b)+(2×c)+d) / 6
+* DENOMINATOR= (e+(2×f)+(2×g)+h) / 6
+* RVI= SMA-N of DENOMINATOR / SMA-N of NUMERATOR
+* Signal Line = (RVI+(2×i)+(2×j)+k) / 6
+
+where:
+
+* a=Close−Open
+* b=Close−Open One Bar Prior to a
+* c=Close−Open One Bar Prior to b
+* d=Close−Open One Bar Prior to c
+* e=High−Low of Bar a
+* f=High−Low of Bar b
+* g=High−Low of Bar c
+* h=High−Low of Bar d
+* i=RVI Value One Bar Prior
+* j=RVI Value One Bar Prior to i
+* k=RVI Value One Bar Prior to j
+* N=Minutes/Hours/Days/Weeks/Months
+
+Examples:
+* `df['rvgi']` retrieves the RVGI line of window 14
+* `df['rvgis']` retrieves the RVGI signal line of window 14
+* `df['rvgi_5']` retrieves the RVGI line of window 5
+* `df['rvgis_5']` retrieves the RVGI signal line of window 5
+
 ## Issues
 
 We use [Github Issues](https://github.com/jealous/stockstats/issues) to track
 the issues or bugs.
 
 ## Others
```

### Comparing `stockstats-0.5.4/setup.py` & `stockstats-0.6.0/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -75,15 +75,15 @@
     keywords="stock statistics indicator",
     url="https://github.com/jealous/stockstats",
     py_modules=['stockstats'],
     platforms=['any'],
     long_description=get_long_description(),
     classifiers=[
         "Programming Language :: Python",
-        "Programming Language :: Python :: 2.7",
+        "Programming Language :: Python :: 3.9",
         "Programming Language :: Python :: 3.10",
         "Programming Language :: Python :: 3.11",
         "Programming Language :: Python :: Implementation :: CPython",
         "Natural Language :: English",
         "Intended Audience :: Developers",
         "Intended Audience :: Financial and Insurance Industry",
         "Operating System :: OS Independent",
```

### Comparing `stockstats-0.5.4/stockstats.egg-info/PKG-INFO` & `stockstats-0.6.0/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 Metadata-Version: 2.1
 Name: stockstats
-Version: 0.5.4
+Version: 0.6.0
 Summary: DataFrame with inline stock statistics support.
 Home-page: https://github.com/jealous/stockstats
 Author: Cedric Zhuang
 Author-email: jealous@163.com
 License: BSD
 Keywords: stock statistics indicator
 Platform: any
 Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 2.7
+Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Natural Language :: English
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Financial and Insurance Industry
 Classifier: Operating System :: OS Independent
@@ -25,24 +25,23 @@
 
 # Stock Statistics/Indicators Calculation Helper
 
 [![build & test](https://github.com/jealous/stockstats/actions/workflows/build-test.yml/badge.svg)](https://github.com/jealous/stockstats/actions/workflows/build-test.yml)
 [![codecov](https://codecov.io/gh/jealous/stockstats/branch/master/graph/badge.svg?token=IFMD1pVJ7T)](https://codecov.io/gh/jealous/stockstats)
 [![pypi](https://img.shields.io/pypi/v/stockstats.svg)](https://pypi.python.org/pypi/stockstats)
 
-VERSION: 0.5.4
+VERSION: 0.6.0
 
 ## Introduction
 
 Supply a wrapper ``StockDataFrame`` for ``pandas.DataFrame`` with inline stock
 statistics/indicators support.
 
 Supported statistics/indicators are:
 
-* change (in percent)
 * delta
 * permutation (zero-based)
 * log return
 * max in range
 * min in range
 * middle = (close + high + low) / 3
 * compare: le, ge, lt, gt, eq, ne
@@ -70,22 +69,33 @@
     * ADXR: Smoothed Moving Average of ADX
 * TRIX: Triple Exponential Moving Average
 * TEMA: Another Triple Exponential Moving Average
 * VR: Volume Variation Index
 * MFI: Money Flow Index
 * VWMA: Volume Weighted Moving Average
 * CHOP: Choppiness Index
+* KER: Kaufman's efficiency ratio
 * KAMA: Kaufman's Adaptive Moving Average
 * PPO: Percentage Price Oscillator
 * StochRSI: Stochastic RSI
 * WT: LazyBear's Wave Trend
 * Supertrend: with the Upper Band and Lower Band
 * Aroon: Aroon Oscillator
 * Z: Z-Score
 * AO: Awesome Oscillator
+* BOP: Balance of Power
+* MAD: Mean Absolute Deviation
+* ROC: Rate of Change
+* Coppock: Coppock Curve
+* Ichimoku: Ichimoku Cloud
+* CTI: Correlation Trend Indicator
+* LRMA: Linear Regression Moving Average
+* ERI: Elder-Ray Index
+* FTR: the Gaussian Fisher Transform Price Reversals indicator
+* RVGI: Relative Vigor Index
 
 ## Installation
 
 ```pip install stockstats```
 
 ## Compatibility
 
@@ -210,18 +220,14 @@
 
 ### Statistics/Indicators
 
 Some statistics have configurable parameters. They are class-level fields. Change
 of these fields is global. And they won't affect the existing results. Removing
 existing columns so that they will be re-evaluated the next time you access them.
 
-#### Change of the Close
-
-`df['change']` is the change of the `close` price in percentage.
-
 #### Delta of Periods
 
 Using pattern `<column>_<window>_d` to retrieve the delta between different periods.
 
 You can also use `<column>_delta` as a shortcut to `<column>_-1_d` 
 
 Examples:
@@ -257,15 +263,15 @@
 
 [2813 rows x 3 columns]
 ```
 
 #### [RSI - Relative Strength Index](https://en.wikipedia.org/wiki/Relative_strength_index)
 
 RSI has a configurable window. The default window size is 14 which is
-configurable through `StockDataFrame.RSI`. e.g.
+configurable through `set_dft_window('rsi', n)`. e.g.
 
 * `df['rsi']`: 14 periods RSI
 * `df['rsi_6']`: 6 periods RSI
 
 #### [Log Return of the Close](https://en.wikipedia.org/wiki/Rate_of_return)
 
 Logarithmic return = ln( close / last close)
@@ -351,47 +357,84 @@
 Use `df['rsv']` or `df['rsv_6']` to access it.
 
 #### [RSI - Relative Strength Index](https://en.wikipedia.org/wiki/Relative_strength_index)
 
 RSI chart the current and historical strength or weakness of a stock. It takes 
 a window parameter.
 
-The default window is 14. Use `StockDataFrame.RSI` to tune it.
+The default window is 14. Use `set_dft_window('rsi', n)` to tune it.
 
 Examples:
 
 * `df['rsi']`: retrieve the RSI of 14 periods
 * `df['rsi_6']`: retrieve the RSI of 6 periods
 
 #### [Stochastic RSI](https://www.investopedia.com/terms/s/stochrsi.asp)
 
 Stochastic RSI gives traders an idea of whether the current RSI value is 
 overbought or oversold. It takes a window parameter.
 
-The default window is 14. Use `StockDataFrame.RSI` to tune it.
+The default window is 14. Use `set_dft_window('stochrsi', n)` to tune it.
 
 Examples:
 
 * `df['stochrsi']`: retrieve the Stochastic RSI of 14 periods
 * `df['stochrsi_6']`: retrieve the Stochastic RSI of 6 periods
 
 #### [WT - Wave Trend](https://medium.com/@samuel.mcculloch/lets-take-a-look-at-wavetrend-with-crosses-lazybear-s-indicator-2ece1737f72f)
 
 Retrieve the LazyBear's Wave Trend with `df['wt1']` and `df['wt2']`.
 
 Wave trend uses two parameters. You can tune them with
-`StockDataFrame.WAVE_TREND_1` and `StockDataFrame.WAVE_TREND_2`.
+`set_dft_window('wt', (10, 21))`.
 
 #### SMMA - Smoothed Moving Average
 
 It requires column and window.
 
 For example, use `df['close_7_smma']` to retrieve the 7 periods smoothed moving
 average of the close price.
 
+#### [ROC - Rate of Change](https://www.investopedia.com/terms/p/pricerateofchange.asp)
+
+The Price Rate of Change (ROC) is a momentum-based technical indicator 
+that measures the percentage change in price between the current price 
+and the price a certain number of periods ago.
+
+Formular:
+
+ROC = (PriceP - PricePn) / PricePn * 100
+
+Where:
+* PriceP: the price of the current period
+* PricePn: the price of the n periods ago
+
+You need a column name and a period to calculate ROC.
+
+Examples:
+* `df['close_10_roc']`: the ROC of the close price in 10 periods
+* `df['high_5_roc']`: the ROC of the high price in 5 periods
+
+#### [MAD - Mean Absolute Deviation](https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/other-measures-of-spread/a/mean-absolute-deviation-mad-review)
+
+The mean absolute deviation of a dataset is the average
+distance between each data point and the mean. It gives 
+us an idea about the variability in a dataset.
+
+Formular:
+1. Calculate the mean.
+2. Calculate how far away each data point is from the 
+   mean using positive distances. These are called 
+   absolute deviations.
+3. Add those deviations together.
+4. Divide the sum by the number of data points.
+
+Example:
+* `df['close_10_mad']`: the MAD of the close price in 10 periods
+
 #### [TRIX - Triple Exponential Average](https://www.investopedia.com/articles/technical/02/092402.asp)
 
 The triple exponential average is used to identify oversold and overbought 
 markets.
 
 The algorithm is:
 
@@ -400,15 +443,15 @@
 TripleEMA = EMA of EMA of EMA
 LastTripleEMA =  TripleEMA of the last period
 ```
 
 It requires column and window. By default, the column is `close`,
 the window is 12.
 
-Use `StockDataFrame.TRIX_EMA_WINDOW` to change the default window.
+Use `set_dft_window('trix', n)` to change the default window.
 
 Examples:
 
 * `df['trix']` stands for 12 periods Trix for the close price.
 * `df['middle_10_trix']` stands for the 10 periods Trix for the typical price.
 
 #### [TEMA - Another Triple Exponential Average](https://www.forextraders.com/forex-education/forex-technical-analysis/triple-exponential-moving-average-the-tema-indicator/)
@@ -418,51 +461,51 @@
 ```
 TEMA=(3 x EMA) - (3 x EMA of EMA) + (EMA of EMA of EMA)
 ```
 
 It takes two parameters, column and window. By default, the column is `close`,
 the window is 5.
 
-Use `StockDataFrame.TEMA_EMA_WINDOW` to change the default window.
+Use `set_dft_window('tema', n)` to change the default window.
 
 Examples:
 
 * `df['tema']` stands for 12 periods TEMA for the close price.
 * `df['middle_10_tema']` stands for the 10 periods TEMA for the typical price.
 
 #### [VR - Volume Variation Index](https://help.eaglesmarkets.com/hc/en-us/articles/900002867026-Summary-of-volume-variation-index)
 
 It is the strength index of the trading volume.
 
-It has a default window of 26. Change it with `StockDataFrame.VR`.
+It has a default window of 26. Change it with `set_dft_window('vr', n)`.
 
 Examples:
 * `df['vr']` retrieves the 26 periods VR.
 * `df['vr_6']` retrieves the 6 periods VR.
 
 #### [WR - Williams Overbought/Oversold Index](https://www.investopedia.com/terms/w/williamsr.asp)
 
 Williams Overbought/Oversold index
 is a type of momentum indicator that moves between 0 and -100 and measures
 overbought and oversold levels.
 
-It takes a window parameter. The default window is 14. Use `StockDataFrame.WR`
+It takes a window parameter. The default window is 14. Use `set_dft_window('wr', n)`
 to change the default window.
 
 Examples:
 
 * `df['wr']` retrieves the 14 periods WR.
 * `df['wr_6']` retrieves the 6 periods WR.
 
 #### [CCI - Commodity Channel Index](https://www.investopedia.com/terms/c/commoditychannelindex.asp)
 
 CCI stands for Commodity Channel Index.
 
 It requires a window parameter. The default window is 14. Use
-`StockDataFrame.CCI` to change it.
+`set_dft_window('cci', n)` to change it.
 
 Examples:
 
 * `df['cci']` retrieves the default 14 periods CCI.
 * `df['cci_6']` retrieves the 6 periods CCI.
 
 #### TR - True Range of Trading
@@ -472,15 +515,15 @@
 
 #### [ATR - Average True Range](https://en.wikipedia.org/wiki/Average_true_range)
 
 The Average True Range is an
 N-period smoothed moving average (SMMA) of the true range value.  
 Default to 14 periods.
 
-Users can modify the default window with `StockDataFrame.ATR_SMMA`.
+Users can modify the default window with `set_dft_window('atr', n)`.
 
 Example:
 
 * `df['atr']` retrieves the 14 periods ATR.
 * `df['atr_5']` retrieves the 5 periods ATR.
 
 #### [Supertrend](https://economictimes.indiatimes.com/markets/stocks/news/how-to-use-supertrend-indicator-to-find-buying-and-selling-opportunities-in-market/articleshow/54492970.cms)
@@ -490,70 +533,73 @@
 It includes 3 lines:
 * `df['supertrend']` is the trend line.
 * `df['supertrend_ub']` is the upper band of the trend
 * `df['supertrend_lb']` is the lower band of the trend
 
 It has 2 parameters:
 * `StockDataFrame.SUPERTREND_MUL` is the multiplier of the band, default to 3.
-* `StockDataFrame.SUPERTREND_WINDOW` is the window size, default to 14.
+* the default window size is 14.  Change it with `set_dft_window('supertrend', n)`
 
 #### DMA - Difference of Moving Average
 
 `df['dma']` retrieves the difference of 10 periods SMA of the close price and
 the 50 periods SMA of the close price.
 
 #### [DMI - Directional Movement Index](https://www.investopedia.com/terms/d/dmi.asp)
 
 The directional movement index (DMI)
 identifies in which direction the price of an asset is moving.
 
 It has several lines:
 
 * `df['pdi']` is the positive directional movement line (+DI)
-* `df['mdi']` is the negative directional movement line (-DI)
+* `df['ndi']` is the negative directional movement line (-DI)
 * `df['dx']` is the directional index (DX)
 * `df['adx']` is the average directional index (ADX)
 * `df['adxr']` is an EMA for ADX
 
 It has several parameters.
 
-* `StockDataFrame.PDI_SMMA` - window for +DI
-* `StockDataFrame.MDI_SMMA` - window for -DI
-* `StockDataFrame.DX_SMMA` - window for DX
-* `StockDataFrame.ADX_EMA` - window for ADX
-* `StockDataFrame.ADXR_EMA` - window for ADXR
+* default window for +DI is 14, change it with `set_dft_window('pdi', n)`
+* default window for -DI is 14, change it with `set_dft_window('ndi', n)`
+* `StockDataFrame.DX_SMMA` - window for DX, default to 14
+* `StockDataFrame.ADX_EMA` - window for ADX, default to 6
+* `StockDataFrame.ADXR_EMA` - window for ADXR, default to 6
 
 #### [KDJ Indicator](https://en.wikipedia.org/wiki/Stochastic_oscillator)
 
-The stochastic oscillator is a momentum indicator that uses support and 
+The stochastic oscillator is a momenxtum indicator that uses support and 
 resistance levels.
 
 It includes three lines:
 * `df['kdjk']` - K series
 * `df['kdjd']` - D series
 * `df['kdjj']` - J series
 
-The default window is 9.  Use `StockDataFrame.KDJ_WINDOW` to change it.
+The default window is 9.  Use `set_dft_window('kdjk', n)` to change it.
 Use `df['kdjk_6']` to retrieve the K series of 6 periods.
 
 KDJ also has two configurable parameters named `StockDataFrame.KDJ_PARAM`.
 The default value is `(2.0/3.0, 1.0/3.0)`
 
 #### [CR - Energy Index](https://support.futunn.com/en/topic167/?lang=en-us)
 
 The Energy Index (Intermediate Willingness Index)
 uses the relationship between the highest price, the lowest price and
 yesterday's middle price to reflect the market's willingness to buy
 and sell.
 
 It contains 4 lines:
 * `df['cr']` - the CR line
-* `df['cr-ma1']` - `StockDataFrame.CR_MA1` periods of the CR moving average
-* `df['cr-ma2']` - `StockDataFrame.CR_MA2` periods of the CR moving average
-* `df['cr-ma3']` - `StockDataFrame.CR_MA3` periods of the CR moving average
+* `df['cr-ma1']` - `StockDataFrame.CR_MA[0]` periods of the CR moving average,
+  the default window is 5
+* `df['cr-ma2']` - `StockDataFrame.CR_MA[1]` periods of the CR moving average,
+  the default window is 10
+* `df['cr-ma3']` - `StockDataFrame.CR_MA[2]` periods of the CR moving average,
+  the default window is 20
 
 #### [Typical Price](https://en.wikipedia.org/wiki/Typical_price)
 
 It's the average of `high`, `low` and `close`.
 Use `df['middle']` to access this value.
 
 When `amount` is available, `middle = amount / volume`
@@ -562,50 +608,44 @@
 #### [Bollinger Bands](https://en.wikipedia.org/wiki/Bollinger_Bands)
 
 The Bollinger bands includes three lines
 * `df['boll']` is the baseline
 * `df['boll_ub']` is the upper band
 * `df['boll_lb']` is the lower band
 
-The default window of boll is defined by `BOLL_PERIOD`.  The default value is 20.
+The default window of boll is 20.
 You can also supply your window with `df['boll_10']`.  It will also
 generate the `boll_ub_10` and `boll_lb_10` column.
 
 The default period of the Bollinger Band can be changed with
-`StockDataFrame.BOLL_PERIOD`.  The width of the bands can be turned with
+`set_dft_window('boll', n)`.  The width of the bands can be turned with
 `StockDataFrame.BOLL_STD_TIMES`.  The default value is 2.
 
 #### [MACD - Moving Average Convergence Divergence](https://en.wikipedia.org/wiki/MACD)
 
 We use the close price to calculate the MACD lines.
 * `df['macd']` is the difference between two exponential moving averages.
 * `df['macds]` is the signal line.
 * `df['macdh']` is he histogram line.
 
-The period of short and long EMA can be tuned with 
-`StockDataFrame.MACD_EMA_SHORT` and `StockDataFrame.MACD_EMA_LONG`.  The default
-value are 12 and 26
-
-The period of the signal line can be tuned with 
-`StockDataFrame.MACD_EMA_SIGNAL`. The default value is 9.
+The period of short, long EMA and signal line can be tuned with 
+`set_dft_window('macd', (short, long, signal))`.  The default
+windows are 12 and 26 and 9.
 
 #### [PPO - Percentage Price Oscillator](https://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:price_oscillators_ppo)
 
 The Percentage Price Oscillator includes three lines.
 
 * `df['ppo']` derives from the difference of 2 exponential moving average.
 * `df['ppos]` is the signal line.
 * `df['ppoh']` is he histogram line.
 
-The period of short and long EMA can be tuned with 
-`StockDataFrame.PPO_EMA_SHORT` and `StockDataFrame.PPO_EMA_LONG`.  The default
-value are 12 and 26
-
-The period of the signal line can be tuned with 
-`StockDataFrame.PPO_EMA_SIGNAL`. The default value is 9.
+The period of short, long EMA and signal line can be tuned with 
+`set_dft_window('ppo', (short, long, signal))`.  The default
+windows are 12 and 26 and 9.
 
 #### [Simple Moving Average](https://www.investopedia.com/terms/m/mean.asp)
 
 Follow the pattern `<columnName>_<window>_sma` to retrieve a simple moving average.
 
 #### [Moving Standard Deviation](https://www.investopedia.com/terms/s/standarddeviation.asp)
 
@@ -616,61 +656,105 @@
 Follow the pattern `<columnName>_<window>_mvar` to retrieve the moving VAR.
 
 #### [Volume Weighted Moving Average](https://www.investopedia.com/articles/trading/11/trading-with-vwap-mvwap.asp)
 
 It's the moving average weighted by volume.
 
 It has a parameter for window size.  The default window is 14.  Change it with
-`StockDataFrame.VWMA`.
+`set_dft_window('vwma', n)`.
 
 Examples:
 * `df['vwma']` retrieves the 14 periods VWMA
 * `df['vwma_6']` retrieves the 6 periods VWMA
 
 #### [CHOP - Choppiness Index](https://www.tradingview.com/education/choppinessindex/)
 
 The Choppiness Index determines if the market is choppy.
 
 It has a parameter for window size.  The default window is 14.  Change it with
-`StockDataFrame.CHOP`.
+`set_dft_window('chop', n)`.
 
 Examples:
 * `df['chop']` retrieves the 14 periods CHOP
 * `df['chop_6']` retrieves the 6 periods CHOP
 
 #### [MFI - Money Flow Index](https://www.investopedia.com/terms/m/mfi.asp)
 
 The Money Flow Index
 identifies overbought or oversold signals in an asset.
 
 It has a parameter for window size.  The default window is 14.  Change it with
-`StockDataFrame.MFI`.
+`set_dft_window('mfi', n)`.
 
 Examples:
 * `df['mfi']` retrieves the 14 periods MFI
 * `df['mfi_6']` retrieves the 6 periods MFI
 
+#### [ERI - Elder-Ray Index](https://admiralmarkets.com/education/articles/forex-indicators/bears-and-bulls-power-indicator)
+
+The Elder-Ray Index contains the bull and the bear power.
+Both are calculated based on the EMA of the close price.
+
+The default window is 13.
+
+Formular:
+* Bulls Power = High - EMA
+* Bears Power = Low - EMA
+* EMA is exponential moving average of close of N periods
+
+Examples:
+* `df['eribull']` retrieves the 13 periods bull power
+* `df['eribear']` retrieves the 13 periods bear power
+* `df['eribull_5']` retrieves the 5 periods bull power
+* `df['eribear_5']` retrieves the 5 periods bear power
+
+#### [KER - Kaufman's efficiency ratio](https://strategyquant.com/codebase/kaufmans-efficiency-ratio-ker/)
+
+The Efficiency Ratio (ER) is calculated by
+dividing the price change over a period by the
+absolute sum of the price movements that occurred
+to achieve that change.
+
+The resulting ratio ranges between 0 and 1 with
+higher values representing a more efficient or
+trending market.
+
+The default column is close.
+
+The default window is 10.
+
+Formular:
+* window_change = ABS(close - close[n])
+* last_change = ABS(close-close[1])
+* volatility = moving sum of last_change in n
+* KER = window_change / volatility
+
+Examples:
+* `df['ker']` retrieves the 10 periods KER of the close price
+* `df['high_5_ker']` retrieves 5 periods KER of the high price
+
 #### [KAMA - Kaufman's Adaptive Moving Average](https://school.stockcharts.com/doku.php?id=technical_indicators:kaufman_s_adaptive_moving_average)
 
 Kaufman's Adaptive Moving Average is designed to account for market noise or 
 volatility.
 
 It has 2 optional parameters and 2 required parameters
 * fast - optional, the parameter for fast EMA smoothing, default to 5
 * slow - optional, the parameter for slow EMA smoothing, default to 34
 * column - required, the column to calculate
 * window - required, rolling window size
 
-The default value for fast and slow can be configured with
-`StockDataFrame.KAMA_FAST` and `StockDataFrame.KAMA_SLOW`
+The default value for window, fast and slow can be configured with
+`set_dft_window('kama', (10, 5, 34))`
 
 Examples:
-* `df['close_10_kama_2_30']` retrieves 10 periods KAMA of the close price with 
-  `fast = 2` and `slow = 30`
+* `df['close_10,2,30_kama']` retrieves 10 periods KAMA of the close 
+  price with `fast = 2` and `slow = 30`
 * `df['close_2_kama']` retrieves 2 periods KAMA of the close price
+  with default fast and slow
 
 #### Cross Upwards and Cross Downwards
 
 Use the pattern `<A>_xu_<B>` to check when A crosses up B.
 
 Use the pattern `<A>_xd_<B>` to check when A crosses down B.
 
@@ -703,15 +787,17 @@
 the mean of a group of values. 
 
 There is no default column name or window for Z-Score.
 
 The statistical formula for a value's z-score is calculated using
 the following formula:
 
-```z = ( x - μ ) / σ```
+```
+z = ( x - μ ) / σ
+```
 
 Where:
 
 * `z` = Z-score
 * `x` = the value being evaluated
 * `μ` = the mean
 * `σ` = the standard deviation
@@ -731,14 +817,178 @@
 * MEDIAN PRICE = (HIGH+LOW)/2
 * AO = SMA(MEDIAN PRICE, 5)-SMA(MEDIAN PRICE, 34)
 
 Examples:
 * `df['ao']` returns the Awesome Oscillator with default windows (5, 34)
 * `df['ao_3,10']` returns the Awesome Oscillator with a window of 3 and 10
 
+#### [Balance of Power](https://school.stockcharts.com/doku.php?id=technical_indicators:balance_of_power)
+
+Balance of Power (BOP) measures the strength of the bulls vs. bears.
+
+Formular:
+```
+BOP = (close - open) / (high - low)
+```
+
+Example:
+* `df['bop']` returns the Balance of Power
+
+#### [Chande Momentum Oscillator] (https://www.investopedia.com/terms/c/chandemomentumoscillator.asp)
+
+The Chande Momentum Oscillator (CMO) is a technical momentum 
+indicator developed by Tushar Chande.
+
+The formula calculates the difference between the sum of recent 
+gains and the sum of recent losses and then divides the result 
+by the sum of all price movements over the same period.
+
+The default window is 14.
+
+Formular:
+```
+CMO = 100 * ((sH - sL) / (sH + sL))
+```
+
+where:
+* sH=the sum of higher closes over N periods
+* sL=the sum of lower closes of N periods
+
+Examples:
+* `df['cmo']` returns the CMO with a window of 14
+* `df['cmo_5']` returns the CMO with a window of 5
+
+#### [Coppock Curve](https://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:coppock_curve)
+
+Coppock Curve is a momentum indicator that signals
+long-term trend reversals.
+
+Formular:
+
+Coppock Curve = 10-period WMA of (14-period RoC + 11-period RoC)
+WMA = Weighted Moving Average
+RoC = Rate-of-Change
+
+Examples:
+* `df['coppock']` returns the Coppock Curve with default windows
+* `df['coppock_5,10,15']` returns the Coppock Curve with WMA window 5,
+  fast window 10, slow window 15. 
+
+#### [Ichimoku Cloud](https://www.investopedia.com/terms/i/ichimoku-cloud.asp)
+
+The Ichimoku Cloud is a collection of technical indicators
+that show support and resistance levels, as well as momentum
+and trend direction.
+
+In this implementation, we only calculate the delta between
+lead A and lead B (which is the width of the cloud).
+
+It contains three windows:
+* window for the conversion line, default to 9
+* window for the baseline and the shifts, default to 26
+* window for the leading line, default to 52
+
+Formular:
+* conversion line = (PH9 + PL9) / 2
+* baseline = (PH26 + PL26) / 2
+* leading span A = (conversion line + baseline) / 2
+* leading span B = (PH52 + PL52) / 2
+* result = leading span A - leading span B
+
+Where:
+* PH = Period High
+* PL = Period Low
+
+Examples:
+* `df['ichimoku']` returns the ichimoku cloud width with default windows
+* `df['ichimoku_7,22,44']` returns the ichimoku cloud width with window sizes
+  7, 22, 44
+
+#### [Linear Regression Moving Average](https://www.daytrading.com/moving-linear-regression)
+
+Linear regression works by taking various data points in a sample and
+providing a “best fit” line to match the general trend in the data. 
+
+Implementation reference:
+
+https://github.com/twopirllc/pandas-ta/blob/main/pandas_ta/overlap/linreg.py
+
+Examples:
+* `df['close_10_lrma']` linear regression of close price with window size 10
+
+#### [Correlation Trend Indicator](https://tlc.thinkorswim.com/center/reference/Tech-Indicators/studies-library/C-D/CorrelationTrendIndicator)
+
+Correlation Trend Indicator is a study that estimates
+the current direction and strength of a trend.
+
+Implementation is based on the following code:
+
+https://github.com/twopirllc/pandas-ta/blob/main/pandas_ta/momentum/cti.py
+
+Examples:
+* `df['cti']` returns the CTI of close price with window 12
+* `df['high_5_cti']` returns the CTI of high price with window 5
+
+#### [the Gaussian Fisher Transform Price Reversals indicator](https://www.tradingview.com/script/ajZT2tZo-Gaussian-Fisher-Transform-Price-Reversals-FTR/)
+
+The Gaussian Fisher Transform Price Reversals indicator, dubbed
+FTR for short, is a stat based price reversal detection indicator
+inspired by and based on the work of the electrical engineer
+now private trader John F. Ehlers.
+
+https://www.tradingview.com/script/ajZT2tZo-Gaussian-Fisher-Transform-Price-Reversals-FTR/
+
+Implementation reference:
+
+https://github.com/twopirllc/pandas-ta/blob/084dbe1c4b76082f383fa3029270ea9ac35e4dc7/pandas_ta/momentum/fisher.py#L9
+
+Formular:
+* Fisher Transform = 0.5 * ln((1 + X) / (1 - X))
+* X is a series whose values are between -1 to 1
+
+Examples:
+* `df['ftr']` returns the FTR with window 9
+* `df['ftr_20']` returns the FTR with window 20
+
+#### [Relative Vigor Index (RVGI)](https://www.investopedia.com/terms/r/relative_vigor_index.asp)
+
+The Relative Vigor Index (RVI) is a momentum indicator
+used in technical analysis that measures the strength
+of a trend by comparing a security's closing price to
+its trading range while smoothing the results using a
+simple moving average (SMA).
+
+Formular
+
+* NUMERATOR= (a+(2×b)+(2×c)+d) / 6
+* DENOMINATOR= (e+(2×f)+(2×g)+h) / 6
+* RVI= SMA-N of DENOMINATOR / SMA-N of NUMERATOR
+* Signal Line = (RVI+(2×i)+(2×j)+k) / 6
+
+where:
+
+* a=Close−Open
+* b=Close−Open One Bar Prior to a
+* c=Close−Open One Bar Prior to b
+* d=Close−Open One Bar Prior to c
+* e=High−Low of Bar a
+* f=High−Low of Bar b
+* g=High−Low of Bar c
+* h=High−Low of Bar d
+* i=RVI Value One Bar Prior
+* j=RVI Value One Bar Prior to i
+* k=RVI Value One Bar Prior to j
+* N=Minutes/Hours/Days/Weeks/Months
+
+Examples:
+* `df['rvgi']` retrieves the RVGI line of window 14
+* `df['rvgis']` retrieves the RVGI signal line of window 14
+* `df['rvgi_5']` retrieves the RVGI line of window 5
+* `df['rvgis_5']` retrieves the RVGI signal line of window 5
+
 ## Issues
 
 We use [Github Issues](https://github.com/jealous/stockstats/issues) to track
 the issues or bugs.
 
 ## Others
```

### Comparing `stockstats-0.5.4/stockstats.py` & `stockstats-0.6.0/stockstats.py`

 * *Files 18% similar despite different names*

```diff
@@ -24,20 +24,200 @@
 # (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
 # SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
 
 from __future__ import unicode_literals
 
 import itertools
 import re
+from typing import Optional, Callable, Union
 
 import numpy as np
 import pandas as pd
 
 __author__ = 'Cedric Zhuang'
 
+from numpy.lib.stride_tricks import as_strided
+
+
+class StockStatsError(Exception):
+    pass
+
+
+_dft_windows = {
+    # sort alphabetically
+    'ao': (5, 34),
+    'aroon': 25,
+    'atr': 14,
+    'boll': 20,
+    'cci': 14,
+    'change': 1,
+    'chop': 14,
+    'cmo': 14,
+    'coppock': (10, 11, 14),
+    'cr': 26,
+    'cti': 12,
+    'dma': (10, 50),
+    'eri': 13,
+    'eribear': 13,
+    'eribull': 13,
+    'ichimoku': (9, 26, 52),
+    'ftr': 9,
+    'kama': (10, 5, 34),  # window, fast, slow
+    'kdjd': 9,
+    'kdjj': 9,
+    'kdjk': 9,
+    'ker': 10,
+    'macd': (12, 26, 9),  # short, long, signal
+    'mfi': 14,
+    'ndi': 14,
+    'pdi': 14,
+    'ppo': (12, 26, 9),  # short, long, signal
+    'rsi': 14,
+    'rsv': 9,
+    'rvgi': 14,
+    'stochrsi': 14,
+    'supertrend': 14,
+    'tema': 5,
+    'trix': 12,
+    'wr': 14,
+    'wt': (10, 21),
+    'vr': 26,
+    'vwma': 14,
+}
+
+
+def set_dft_window(name: str, windows: Union[int, tuple[int, ...]]):
+    ret = _dft_windows.get(name)
+    _dft_windows[name] = windows
+    return ret
+
+
+_dft_column = {
+    # sort alphabetically
+    'cti': 'close',
+    'dma': 'close',
+    'kama': 'close',
+    'ker': 'close',
+    'tema': 'close',
+    'trix': 'close',
+}
+
+
+def dft_windows(name: str) -> Optional[str]:
+    if name not in _dft_windows:
+        return None
+    dft = _dft_windows[name]
+    if isinstance(dft, int):
+        return str(dft)
+    return ','.join(map(str, dft))
+
+
+def dft_column(name: str) -> Optional[str]:
+    if name not in _dft_column:
+        return None
+    return _dft_column[name]
+
+
+class _Meta:
+    def __init__(self,
+                 name,
+                 *,
+                 column=None,
+                 windows=None):
+        self._name = name
+        self._column = column
+        self._windows = windows
+        self._dft_column = dft_column(name)
+        self._dft_windows = dft_windows(name)
+
+    @staticmethod
+    def _process_segment(windows):
+        if '~' in windows:
+            start, end = windows.split('~')
+            shifts = range(int(start), int(end) + 1)
+        else:
+            shifts = [int(windows)]
+        return shifts
+
+    @property
+    def ints(self) -> list[int]:
+        items = map(self._process_segment, self.windows.split(','))
+        return list(itertools.chain(*items))
+
+    @property
+    def int(self) -> int:
+        numbers = self.ints
+        if len(numbers) != 1:
+            raise StockStatsError('only accept 1 number')
+        return numbers[0]
+
+    def _get_int(self, i):
+        numbers = self.ints
+        if len(numbers) < i + 1:
+            # try the defaults
+            dft_numbers = _dft_windows[self._name]
+            if len(dft_numbers) > i:
+                return dft_numbers[i]
+            raise StockStatsError(f'not enough ints, need {i + 1}')
+        return self.ints[i]
+
+    @property
+    def int0(self) -> int:
+        return self._get_int(0)
+
+    @property
+    def int1(self) -> int:
+        return self._get_int(1)
+
+    @property
+    def int2(self) -> int:
+        return self._get_int(2)
+
+    @property
+    def positive_int(self) -> int:
+        ret = self.int
+        if ret <= 0:
+            raise StockStatsError('window must be greater than 0')
+        return ret
+
+    @property
+    def windows(self):
+        if self._windows is None:
+            return self._dft_windows
+        return self._windows
+
+    @property
+    def column(self):
+        if self._column is None:
+            return self._dft_column
+        return self._column
+
+    @property
+    def name(self):
+        if self._windows is None and self._column is None:
+            return self._name
+        if self._column is None:
+            return f'{self._name}_{self._windows}'
+        return f'{self.column}_{self.windows}_{self._name}'
+
+    def set_name(self, name: str):
+        self._name = name
+        return self
+
+    def name_ex(self, ex):
+        ret = f'{self._name}{ex}'
+        if self._windows is None:
+            return ret
+        return f'{ret}_{self.windows}'
+
+
+def _call_handler(handler: Callable):
+    meta = _Meta(handler.__name__[5:])
+    return handler(meta)
+
 
 def wrap(df, index_column=None):
     """ wraps a pandas DataFrame to StockDataFrame
 
     :param df: pandas DataFrame
     :param index_column: the name of the index column, default to ``date``
     :return: an object of StockDataFrame
@@ -49,170 +229,134 @@
     """ convert a StockDataFrame back to a pandas DataFrame """
     return pd.DataFrame(sdf)
 
 
 class StockDataFrame(pd.DataFrame):
     # Start of options.
     KDJ_PARAM = (2.0 / 3.0, 1.0 / 3.0)
-    KDJ_WINDOW = 9
 
-    BOLL_PERIOD = 20
     BOLL_STD_TIMES = 2
 
-    MACD_EMA_SHORT = 12
-    MACD_EMA_LONG = 26
-    MACD_EMA_SIGNAL = 9
-
-    PPO_EMA_SHORT = 12
-    PPO_EMA_LONG = 26
-    PPO_EMA_SIGNAL = 9
-
-    PDI_SMMA = 14
-    MDI_SMMA = 14
     DX_SMMA = 14
     ADX_EMA = 6
     ADXR_EMA = 6
 
-    CR_MA1 = 5
-    CR_MA2 = 10
-    CR_MA3 = 20
-
-    TRIX_EMA_WINDOW = 12
-
-    TEMA_EMA_WINDOW = 5
-
-    ATR_SMMA = 14
+    CR_MA = (5, 10, 20)
 
     SUPERTREND_MUL = 3
-    SUPERTREND_WINDOW = 14
-
-    VWMA = 14
-
-    CHOP = 14
-
-    MFI = 14
-
-    CCI = 14
-
-    RSI = 14
-
-    VR = 26
-
-    WR = 14
-
-    WAVE_TREND_1 = 10
-    WAVE_TREND_2 = 21
 
-    KAMA_SLOW = 34
-    KAMA_FAST = 5
+    # End of options
 
-    AO_SLOW = 34
-    AO_FAST = 5
+    @property
+    def high(self) -> pd.Series:
+        return self['high']
 
-    MULTI_SPLIT_INDICATORS = ("kama",)
+    @property
+    def low(self) -> pd.Series:
+        return self['low']
 
-    # End of options
+    @property
+    def close(self) -> pd.Series:
+        return self['close']
 
-    @staticmethod
-    def _change(series, window):
-        return series.pct_change(periods=-window).fillna(0.0) * 100
+    @property
+    def open(self) -> pd.Series:
+        return self['open']
 
-    def _get_change(self):
+    def _get_change(self, meta: _Meta):
         """ Get the percentage change column
 
+        It's an alias for ROC
+
         :return: result series
         """
-        self['change'] = self._change(self['close'], -1)
+        self[meta.name] = self.roc(self['close'], meta.int)
 
-    def _get_p(self, column, shifts):
+    def _get_p(self, meta: _Meta):
         """ get the permutation of specified range
 
         example:
         index    x   x_-2,-1_p
         0        1         NaN
         1       -1         NaN
         2        3           2  (0.x > 0, and assigned to weight 2)
         3        5           1  (2.x > 0, and assigned to weight 1)
         4        1           3
-
-        :param column: the column to calculate p from
-        :param shifts: the range to consider
-        :return:
         """
-        column_name = '{}_{}_p'.format(column, shifts)
         # initialize the column if not
-        self.get(column)
-        shifts = self.to_ints(shifts)[::-1]
-        indices = None
+        _ = self.get(meta.column)
+        shifts = meta.ints[::-1]
+        indices: Optional[pd.Series] = None
         count = 0
         for shift in shifts:
             shifted = self.shift(-shift)
-            index = (shifted[column] > 0) * (2 ** count)
+            index = (shifted[meta.column] > 0) * (2 ** count)
             if indices is None:
                 indices = index
             else:
                 indices += index
             count += 1
         if indices is not None:
             cp = indices.copy()
             self.set_nan(cp, shifts)
-            self[column_name] = cp
+            self[meta.name] = cp
 
-    def to_ints(self, shifts):
-        items = map(self._process_shifts_segment, shifts.split(','))
+    @classmethod
+    def to_ints(cls, shifts):
+        items = map(cls._process_shifts_segment, shifts.split(','))
         return sorted(list(set(itertools.chain(*items))))
 
-    def to_int(self, shifts):
-        numbers = self.to_ints(shifts)
+    @classmethod
+    def to_int(cls, shifts):
+        numbers = cls.to_ints(shifts)
         if len(numbers) != 1:
             raise IndexError("only accept 1 number.")
         return numbers[0]
 
     @staticmethod
     def _process_shifts_segment(shift_segment):
         if '~' in shift_segment:
             start, end = shift_segment.split('~')
             shifts = range(int(start), int(end) + 1)
         else:
             shifts = [int(shift_segment)]
         return shifts
 
-    @staticmethod
-    def set_nan(pd_obj, shift):
+    @classmethod
+    def set_nan(cls, pd_obj, shift):
         try:
             iter(shift)
             max_shift = max(shift)
             min_shift = min(shift)
-            StockDataFrame._set_nan_of_single_shift(pd_obj, max_shift)
-            StockDataFrame._set_nan_of_single_shift(pd_obj, min_shift)
+            cls._set_nan_of_single_shift(pd_obj, max_shift)
+            cls._set_nan_of_single_shift(pd_obj, min_shift)
         except TypeError:
             # shift is not iterable
-            StockDataFrame._set_nan_of_single_shift(pd_obj, shift)
+            cls._set_nan_of_single_shift(pd_obj, shift)
 
     @staticmethod
     def _set_nan_of_single_shift(pd_obj, shift):
         val = np.nan
         if shift > 0:
             pd_obj.iloc[-shift:] = val
         elif shift < 0:
             pd_obj.iloc[:-shift] = val
 
-    def _get_r(self, column, shifts):
+    def _get_r(self, meta: _Meta):
         """ Get rate of change of column
 
-        :param column: column name of the rate to calculate
-        :param shifts: periods to shift, accept one shift only
-        :return: None
+        Note this function is different to the roc function.
+        negative values meaning data in the past,
+        positive values meaning data in the future.
         """
-        shift = self.to_int(shifts)
-        rate_key = '{}_{}_r'.format(column, shift)
-        self[rate_key] = self._change(self[column], shift)
+        shift = -meta.int
+        self[meta.name] = self.roc(self[meta.column], shift)
 
     @staticmethod
-    def _shift(series, window):
+    def _shift(series: pd.Series, window: int):
         """ Shift the series
 
         When window is negative, shift the past period to current.
         Fill the gap with the first data available.
 
         When window is positive, shift the future period to current.
         Fill the gap with last data available.
@@ -224,331 +368,246 @@
         ret = series.shift(-window)
         if window < 0:
             ret.iloc[:-window] = series.iloc[0]
         elif window > 0:
             ret.iloc[-window:] = series.iloc[-1]
         return ret
 
-    def _get_s(self, column, shifts):
+    def _get_s(self, meta: _Meta):
         """ Get the column shifted by periods
 
-        :param column: name of the column to shift
-        :param shifts: periods to shift, accept one shift only
-        :return: None
+        Note this method is different to the shift method of pandas.
+        negative values meaning data in the past,
+        positive values meaning data in the future.
         """
-        shift = self.to_int(shifts)
-        shifted_key = "{}_{}_s".format(column, shift)
-        self[shifted_key] = self._shift(self[column], shift)
+        self[meta.name] = self._shift(self[meta.column], meta.int)
 
-    def _get_log_ret(self):
+    def _get_log_ret(self, _: _Meta):
         close = self['close']
         self['log-ret'] = np.log(close / self._shift(close, -1))
 
-    def _get_c(self, column, shifts):
+    def _get_c(self, meta: _Meta) -> pd.Series:
         """ get the count of column in range (shifts)
 
         example: change_20_c
-
-        :param column: column name
-        :param shifts: range to count, only to previous
         :return: result series
         """
-        column_name = '{}_{}_c'.format(column, shifts)
-        shifts = self.get_int_positive(shifts)
-        self[column_name] = self[column].rolling(
-            center=False,
-            window=shifts,
-            min_periods=0).apply(np.count_nonzero)
-        return self[column_name]
+        rolled = self._rolling(self[meta.column], meta.int)
+        counts = rolled.apply(np.count_nonzero, raw=True)
+        self[meta.name] = counts
+        return counts
 
-    def _get_fc(self, column, shifts):
+    def _get_fc(self, meta: _Meta) -> pd.Series:
         """ get the count of column in range of future (shifts)
 
         example: change_20_fc
-
-        :param column: column name
-        :param shifts: range to count, only to future
         :return: result series
         """
-        column_name = '{}_{}_fc'.format(column, shifts)
-        shift = self.get_int_positive(shifts)
-        reversed_series = self[column][::-1]
-        reversed_counts = reversed_series.rolling(
-            center=False,
-            window=shift,
-            min_periods=0).apply(np.count_nonzero)
+        shift = meta.int
+        reversed_series = self[meta.column][::-1]
+        rolled = self._rolling(reversed_series, shift)
+        reversed_counts = rolled.apply(np.count_nonzero, raw=True)
         counts = reversed_counts[::-1]
-        self[column_name] = counts
+        self[meta.name] = counts
         return counts
 
-    def _init_shifted_columns(self, column, shifts):
+    def _shifted_columns(self,
+                         column: pd.Series,
+                         shifts: list[int]) -> pd.DataFrame:
         # initialize the column if not
-        self.get(column)
-        shifts = self.to_ints(shifts)
-        shift_column_names = ['{}_{}_s'.format(column, shift) for shift in
-                              shifts]
-        [self.get(name) for name in shift_column_names]
-        return shift_column_names
-
-    def _get_max(self, column, shifts):
-        column_name = '{}_{}_max'.format(column, shifts)
-        shift_column_names = self._init_shifted_columns(column, shifts)
-        self[column_name] = np.max(self[shift_column_names], axis=1)
-
-    def _get_min(self, column, shifts):
-        column_name = '{}_{}_min'.format(column, shifts)
-        shift_column_names = self._init_shifted_columns(column, shifts)
-        self[column_name] = np.min(self[shift_column_names], axis=1)
+        col = self.get(column)
+        res = pd.DataFrame()
+        for i in shifts:
+            res[int(i)] = self._shift(col, i).values
+        return res
+
+    def _get_max(self, meta: _Meta):
+        column = meta.column
+        shifts = meta.ints
+        cols = self._shifted_columns(column, shifts)
+        self[meta.name] = cols.max(axis=1).values
+
+    def _get_min(self, meta: _Meta):
+        column = meta.column
+        shifts = meta.ints
+        cols = self._shifted_columns(column, shifts)
+        self[meta.name] = cols.min(axis=1).values
+
+    def _rsv(self, window):
+        low_min = self.mov_min(self['low'], window)
+        high_max = self.mov_max(self['high'], window)
+
+        cv = (self['close'] - low_min) / (high_max - low_min)
+        cv.fillna(0.0, inplace=True)
+        return cv * 100
 
-    def _get_rsv(self, window):
+    def _get_rsv(self, meta: _Meta):
         """ Calculate the RSV (Raw Stochastic Value) within N periods
 
         This value is essential for calculating KDJs
         Current day is included in N
 
-        :param window: number of periods
-        :return: None
         """
-        window = self.get_int_positive(window)
-        column_name = 'rsv_{}'.format(window)
-        low_min = self._mov_min(self['low'], window)
-        high_max = self._mov_max(self['high'], window)
+        self[meta.name] = self._rsv(meta.int)
 
-        cv = (self['close'] - low_min) / (high_max - low_min)
-        self[column_name] = cv.fillna(0.0) * 100
+    def _rsi(self, window) -> pd.Series:
+        change = self._delta(self['close'], -1)
+        close_pm = (change + change.abs()) / 2
+        close_nm = (-change + change.abs()) / 2
+        p_ema = self.smma(close_pm, window)
+        n_ema = self.smma(close_nm, window)
+
+        rs = p_ema / n_ema
+        return 100 - 100 / (1.0 + rs)
 
-    def _get_rsi(self, window=None):
+    def _get_rsi(self, meta: _Meta):
         """ Calculate the RSI (Relative Strength Index) within N periods
 
         calculated based on the formula at:
         https://en.wikipedia.org/wiki/Relative_strength_index
-
-        :param window: number of periods
-        :return: None
         """
-        if window is None:
-            window = self.RSI
-            column_name = 'rsi'
-        else:
-            column_name = 'rsi_{}'.format(window)
-        window = self.get_int_positive(window)
+        self[meta.name] = self._rsi(meta.int)
 
-        change = self._delta(self['close'], -1)
-        close_pm = (change + change.abs()) / 2
-        close_nm = (-change + change.abs()) / 2
-        p_ema = self._smma(close_pm, window)
-        n_ema = self._smma(close_nm, window)
-
-        rs_column_name = 'rs_{}'.format(window)
-        self[rs_column_name] = rs = p_ema / n_ema
-        self[column_name] = 100 - 100 / (1.0 + rs)
-
-    def _get_stochrsi(self, window=None):
+    def _get_stochrsi(self, meta: _Meta):
         """ Calculate the Stochastic RSI
 
         calculated based on the formula at:
         https://www.investopedia.com/terms/s/stochrsi.asp
-
-        :param window: number of periods
-        :return: None
         """
-        if window is None:
-            window = self.RSI
-            column_name = 'stochrsi'
-        else:
-            column_name = 'stochrsi_{}'.format(window)
-        window = self.get_int_positive(window)
-
-        rsi = self['rsi_{}'.format(window)]
-        rsi_min = self._mov_min(rsi, window)
-        rsi_max = self._mov_max(rsi, window)
+        window = meta.int
+        rsi = self._rsi(window)
+        rsi_min = self.mov_min(rsi, window)
+        rsi_max = self.mov_max(rsi, window)
 
         cv = (rsi - rsi_min) / (rsi_max - rsi_min)
-        self[column_name] = cv * 100
+        self[meta.name] = cv * 100
 
-    def _get_wave_trend(self):
-        """ Calculate LazyBear's Wavetrend
-        Check the algorithm described below:
-        https://medium.com/@samuel.mcculloch/lets-take-a-look-at-wavetrend-with-crosses-lazybear-s-indicator-2ece1737f72f
+    def _wt1(self, n1: int, n2: int) -> pd.Series:
+        """ wave trand 1
 
         n1: period of EMA on typical price
         n2: period of EMA
-
-        :return: None
         """
-        n1 = self.WAVE_TREND_1
-        n2 = self.WAVE_TREND_2
-
         tp = self._tp()
-        esa = self._ema(tp, n1)
-        d = self._ema((tp - esa).abs(), n1)
+        esa = self.ema(tp, n1)
+        d = self.ema((tp - esa).abs(), n1)
         ci = (tp - esa) / (0.015 * d)
-        tci = self._ema(ci, n2)
-        self["wt1"] = tci
-        self["wt2"] = self._sma(tci, 4)
+        return self.ema(ci, n2)
+
+    def _get_wt1(self, meta: _Meta):
+        self[meta.name] = self._wt1(meta.int0, meta.int1)
+
+    def _get_wt2(self, meta: _Meta):
+        wt1 = self._wt1(meta.int0, meta.int1)
+        self[meta.name] = self.sma(wt1, 4)
+
+    def _get_wt(self, meta: _Meta):
+        """ Calculate LazyBear's Wavetrend
+        Check the algorithm described below:
+        https://medium.com/@samuel.mcculloch/lets-take-a-look-at-wavetrend-with-crosses-lazybear-s-indicator-2ece1737f72f
+        """
+        tci = self._wt1(meta.int0, meta.int1)
+        self[meta.name_ex('1')] = tci
+        self[meta.name_ex('2')] = self.sma(tci, 4)
 
     @staticmethod
-    def _smma(series, window):
+    def smma(series, window):
         return series.ewm(
             ignore_na=False,
             alpha=1.0 / window,
             min_periods=0,
             adjust=True).mean()
 
-    def _get_smma(self, column, windows):
-        """ get smoothed moving average.
+    def _get_smma(self, meta: _Meta):
+        """ get smoothed moving average """
+        self[meta.name] = self.smma(self[meta.column], meta.int)
 
-        :param column: the column to calculate
-        :param windows: range
-        :return: result series
-        """
-        window = self.get_int_positive(windows)
-        column_name = '{}_{}_smma'.format(column, window)
-        self[column_name] = self._smma(self[column], window)
-
-    def _get_trix(self, column=None, windows=None):
+    def _get_trix(self, meta: _Meta):
         """ Triple Exponential Average
 
         https://www.investopedia.com/articles/technical/02/092402.asp
-
-        :param column: the column to calculate
-        :param windows: range
-        :return: result series
         """
-        column_name = ""
-        if column is None and windows is None:
-            column_name = 'trix'
-        if column is None:
-            column = 'close'
-        if windows is None:
-            windows = self.TRIX_EMA_WINDOW
-        if column_name == "":
-            column_name = '{}_{}_trix'.format(column, windows)
-
-        window = self.get_int_positive(windows)
-
-        single = self._ema(self[column], window)
-        double = self._ema(single, window)
-        triple = self._ema(double, window)
+        window = meta.int
+        single = self.ema(self[meta.column], window)
+        double = self.ema(single, window)
+        triple = self.ema(double, window)
         prev_triple = self._shift(triple, -1)
         triple_change = self._delta(triple, -1)
-        self[column_name] = triple_change * 100 / prev_triple
+        self[meta.name] = triple_change * 100 / prev_triple
 
-    def _get_tema(self, column=None, windows=None):
+    def _get_tema(self, meta: _Meta):
         """ Another implementation for triple ema
 
         Check the algorithm described below:
         https://www.forextraders.com/forex-education/forex-technical-analysis/triple-exponential-moving-average-the-tema-indicator/
-
-        :param column: column to calculate ema
-        :param windows: window of the calculation
-        :return: result series
         """
-        column_name = ""
-        if column is None and windows is None:
-            column_name = 'tema'
-        if column is None:
-            column = 'close'
-        if windows is None:
-            windows = self.TEMA_EMA_WINDOW
-        if column_name == "":
-            column_name = '{}_{}_tema'.format(column, windows)
-
-        window = self.get_int_positive(windows)
-
-        single = self._ema(self[column], window)
-        double = self._ema(single, window)
-        triple = self._ema(double, window)
-        self[column_name] = 3 * single - 3 * double + triple
+        window = meta.int
+        single = self.ema(self[meta.column], window)
+        double = self.ema(single, window)
+        triple = self.ema(double, window)
+        self[meta.name] = 3.0 * single - 3.0 * double + triple
 
-    def _get_wr(self, window=None):
+    def _get_wr(self, meta: _Meta):
         """ Williams Overbought/Oversold Index
 
         Definition: https://www.investopedia.com/terms/w/williamsr.asp
         WMS=[(Hn—Ct)/(Hn—Ln)] × -100
         Ct - the close price
         Hn - N periods high
         Ln - N periods low
-
-        :param window: number of periods
-        :return: None
         """
-        if window is None:
-            window = self.WR
-            column_name = 'wr'
-        else:
-            column_name = 'wr_{}'.format(window)
-
-        window = self.get_int_positive(window)
-        ln = self._mov_min(self['low'], window)
-
-        hn = self._mov_max(self['high'], window)
-        self[column_name] = (hn - self['close']) / (hn - ln) * -100
+        window = meta.int
+        ln = self.mov_min(self['low'], window)
+        hn = self.mov_max(self['high'], window)
+        self[meta.name] = (hn - self['close']) / (hn - ln) * -100
 
-    def _get_cci(self, window=None):
+    def _get_cci(self, meta: _Meta):
         """ Commodity Channel Index
 
         CCI = (Typical Price  -  20-period SMA of TP) / (.015 x Mean Deviation)
         * when amount is not available:
           Typical Price (TP) = (High + Low + Close)/3
         * when amount is available:
           Typical Price (TP) = Amount / Volume
         TP is also implemented as 'middle'.
-
-        :param window: number of periods
-        :return: None
         """
-        if window is None:
-            window = self.CCI
-            column_name = 'cci'
-        else:
-            column_name = 'cci_{}'.format(window)
-        window = self.get_int_positive(window)
-
+        window = meta.int
         tp = self._tp()
-        tp_sma = self._sma(tp, window)
-        rolling = tp.rolling(min_periods=1, center=False, window=window)
-        md = rolling.apply(lambda x: np.fabs(x - x.mean()).mean())
-
-        self[column_name] = (tp - tp_sma) / (.015 * md)
+        tp_sma = self.sma(tp, window)
+        mad = self._mad(tp, window)
+        self[meta.name] = (tp - tp_sma) / (.015 * mad)
 
     def _tr(self):
         prev_close = self._shift(self['close'], -1)
         high = self['high']
         low = self['low']
         c1 = high - low
         c2 = (high - prev_close).abs()
         c3 = (low - prev_close).abs()
         return pd.concat((c1, c2, c3), axis=1).max(axis=1)
 
-    def _get_tr(self):
+    def _get_tr(self, meta: _Meta):
         """ True Range of the trading
 
          TR is a measure of volatility of a High-Low-Close series
 
         tr = max[(high - low), abs(high - close_prev), abs(low - close_prev)]
 
         :return: None
         """
-        self['tr'] = self._tr()
+        self[meta.name] = self._tr()
 
-    def _get_supertrend(self, window=None):
+    def _get_supertrend(self, meta: _Meta):
         """ Supertrend
 
         Supertrend indicator shows trend direction.
         It provides buy or sell indicators.
         https://medium.com/codex/step-by-step-implementation-of-the-supertrend-indicator-in-python-656aa678c111
-
-        :param window: number of periods
-        :return: None
         """
-        if window is None:
-            window = self.SUPERTREND_WINDOW
-        window = self.get_int_positive(window)
-
+        window = meta.int
         high = self['high']
         low = self['low']
         close = self['close']
         m_atr = self.SUPERTREND_MUL * self._atr(window)
         hl_avg = (high + low) / 2.0
         # basic upper band
         b_ub = list(hl_avg + m_atr)
@@ -599,56 +658,47 @@
                     st[i] = lb[i]
             elif last_st == last_lb:
                 if curr_close > lb[i]:
                     st[i] = lb[i]
                 else:
                     st[i] = ub[i]
 
-        self['supertrend_ub'] = ub
-        self['supertrend_lb'] = lb
-        self['supertrend'] = st
+        self[f'{meta.name}_ub'] = ub
+        self[f'{meta.name}_lb'] = lb
+        self[f'{meta.name}'] = st
 
-    def _get_aroon(self, window=None):
+    def _get_aroon(self, meta: _Meta):
         """ Aroon Oscillator
 
         The Aroon Oscillator measures the strength of a trend and
         the likelihood that it will continue.
 
         The default window is 25.
 
         * Aroon Oscillator = Aroon Up - Aroon Down
         * Aroon Up = 100 * (n - periods since n-period high) / n
         * Aroon Down = 100 * (n - periods since n-period low) / n
         * n = window size
         """
-        if window is None:
-            window = 25
-            column_name = 'aroon'
-        else:
-            window = self.get_int_positive(window)
-            column_name = 'aroon_{}'.format(window)
+        window = meta.int
 
         def _window_pct(s):
             n = float(window)
             return (n - (n - (s + 1))) / n * 100
 
-        high_since = self['high'].rolling(
-            min_periods=1,
-            window=window,
-            center=False).apply(np.argmax)
-        low_since = self['low'].rolling(
-            min_periods=1,
-            window=window,
-            center=False).apply(np.argmin)
+        high_since = self._rolling(
+            self['high'], window).apply(np.argmax, raw=True)
+        low_since = self._rolling(
+            self['low'], window).apply(np.argmin, raw=True)
 
         aroon_up = _window_pct(high_since)
         aroon_down = _window_pct(low_since)
-        self[column_name] = aroon_up - aroon_down
+        self[meta.name] = aroon_up - aroon_down
 
-    def _get_z(self, column, window):
+    def _get_z(self, meta: _Meta):
         """ Z score
 
         Z-score is a statistical measurement that describes a value's
         relationship to the mean of a group of values.
 
         The statistical formula for a value's z-score is calculated using
         the following formula:
@@ -658,615 +708,846 @@
         Where:
 
         * z = Z-score
         * x = the value being evaluated
         * μ = the mean
         * σ = the standard deviation
         """
-        window = self.get_int_positive(window)
-        column_name = '{}_{}_z'.format(column, window)
-        col = self[column]
-        mean = col.rolling(
-            min_periods=1,
-            window=window,
-            center=False).mean()
-        std = col.rolling(
-            min_periods=1,
-            window=window,
-            center=False).std()
-        self[column_name] = ((col - mean) / std).fillna(0.0)
+        window = meta.int
+        col = self[meta.column]
+        mean = self.sma(col, window)
+        std = self.mov_std(col, window)
+        self[meta.name] = ((col - mean) / std).fillna(0.0)
 
     def _atr(self, window):
         tr = self._tr()
-        return self._smma(tr, window)
+        return self.smma(tr, window)
 
-    def _get_atr(self, window=None):
+    def _get_atr(self, meta: _Meta):
         """ Average True Range
 
         The average true range is an N-day smoothed moving average (SMMA) of
         the true range values.  Default to 14 periods.
         https://en.wikipedia.org/wiki/Average_true_range
-
-        :param window: number of periods
-        :return: None
         """
-        if window is None:
-            window = self.ATR_SMMA
-            column_name = 'atr'
-        else:
-            column_name = 'atr_{}'.format(window)
-        window = self.get_int_positive(window)
-        self[column_name] = self._atr(window)
+        window = meta.int
+        self[meta.name] = self._atr(window)
 
-    def _get_dma(self):
+    def _get_dma(self, meta: _Meta):
         """ Difference of Moving Average
 
         default to 10 and 50.
 
         :return: None
         """
-        self['dma'] = self['close_10_sma'] - self['close_50_sma']
+        fast = meta.int0
+        slow = meta.int1
+        col = self[meta.column]
+        diff = self.sma(col, fast) - self.sma(col, slow)
+        self[meta.name] = diff
 
-    def _get_dmi(self):
+    def _get_dmi(self, _: _Meta):
         """ get the default setting for DMI
 
         including:
         +DI: 14 periods SMMA of +DM,
         -DI: 14 periods SMMA of -DM,
         DX: based on +DI and -DI
         ADX: 6 periods SMMA of DX
 
         :return:
         """
-        self['pdi'] = self._get_pdi(self.PDI_SMMA)
-        self['mdi'] = self._get_mdi(self.MDI_SMMA)
-        self['dx'] = self._get_dx(self.DX_SMMA)
-        self['adx'] = self._ema(self['dx'], self.ADX_EMA)
-        self['adxr'] = self._ema(self['adx'], self.ADXR_EMA)
-
-    def _get_um_dm(self):
-        """ Up move and down move
-
-        initialize up move and down move
-        """
-        hd = self['high_delta']
-        self['um'] = (hd + hd.abs()) / 2
-        ld = -self['low_delta']
-        self['dm'] = (ld + ld.abs()) / 2
+        self['dx'] = self._dx(self.DX_SMMA)
+        self['adx'] = self.ema(self['dx'], self.ADX_EMA)
+        self['adxr'] = self.ema(self['adx'], self.ADXR_EMA)
+
+    def _get_pdm_ndm(self, window):
+        hd = self._col_diff('high')
+        ld = -self._col_diff('low')
+        p = ((hd > 0) & (hd > ld)) * hd
+        n = ((ld > 0) & (ld > hd)) * ld
+        if window > 1:
+            p = self.smma(p, window)
+            n = self.smma(n, window)
+        return p, n
+
+    def _pdm(self, window):
+        ret, _ = self._get_pdm_ndm(window)
+        return ret
+
+    def _ndm(self, window):
+        _, ret = self._get_pdm_ndm(window)
+        return ret
 
-    def _get_pdm(self, windows):
+    def _get_pdm(self, meta: _Meta):
         """ +DM, positive directional moving
 
         If window is not 1, calculate the SMMA of +DM
-
-        :param windows: range
-        :return:
         """
-        window = self.get_int_positive(windows)
-        column_name = 'pdm_{}'.format(window)
-        um, dm = self['um'], self['dm']
-        self['pdm'] = np.where(um > dm, um, 0)
-        if window > 1:
-            pdm = self['pdm_{}_ema'.format(window)]
-        else:
-            pdm = self['pdm']
-        self[column_name] = pdm
+        self[meta.name] = self._pdm(meta.int)
 
-    def _get_vr(self, windows=None):
-        if windows is None:
-            window = self.VR
-            column_name = 'vr'
-        else:
-            window = self.get_int_positive(windows)
-            column_name = 'vr_{}'.format(window)
+    def _get_ndm(self, meta: _Meta):
+        """ -DM, negative directional moving accumulation
+
+        If window is not 1, return the SMA of -DM.
+        """
+        self[meta.name] = self._ndm(meta.int)
 
+    def _get_vr(self, meta: _Meta):
+        """ VR - Volume Variation Index """
+        window = meta.int
         idx = self.index
         gt_zero = np.where(self['change'] > 0, self['volume'], 0)
         av = pd.Series(gt_zero, index=idx)
-        avs = self._mov_sum(av, window)
+        avs = self.mov_sum(av, window)
 
         lt_zero = np.where(self['change'] < 0, self['volume'], 0)
         bv = pd.Series(lt_zero, index=idx)
-        bvs = self._mov_sum(bv, window)
+        bvs = self.mov_sum(bv, window)
 
         eq_zero = np.where(self['change'] == 0, self['volume'], 0)
         cv = pd.Series(eq_zero, index=idx)
-        cvs = self._mov_sum(cv, window)
-
-        self[column_name] = (avs + cvs / 2) / (bvs + cvs / 2) * 100
-
-    def _get_mdm(self, windows):
-        """ -DM, negative directional moving accumulation
-
-        If window is not 1, return the SMA of -DM.
-
-        :param windows: range
-        :return:
-        """
-        window = self.get_int_positive(windows)
-        column_name = 'mdm_{}'.format(window)
-        um, dm = self['um'], self['dm']
-        self['mdm'] = np.where(dm > um, dm, 0)
-        if window > 1:
-            mdm = self['mdm_{}_ema'.format(window)]
-        else:
-            mdm = self['mdm']
-        self[column_name] = mdm
+        cvs = self.mov_sum(cv, window)
 
-    def _get_pdi(self, windows):
-        """ +DI, positive directional moving index
+        self[meta.name] = (avs + cvs / 2) / (bvs + cvs / 2) * 100
 
-        :param windows: range
-        :return:
-        """
-        window = self.get_int_positive(windows)
-        pdm_column = 'pdm_{}'.format(window)
-        tr_column = 'atr_{}'.format(window)
-        pdi_column = 'pdi_{}'.format(window)
-        self[pdi_column] = self[pdm_column] / self[tr_column] * 100
-        return self[pdi_column]
-
-    def _get_mdi(self, windows):
-        window = self.get_int_positive(windows)
-        mdm_column = 'mdm_{}'.format(window)
-        tr_column = 'atr_{}'.format(window)
-        mdi_column = 'mdi_{}'.format(window)
-        self[mdi_column] = self[mdm_column] / self[tr_column] * 100
-        return self[mdi_column]
-
-    def _get_dx(self, windows):
-        window = self.get_int_positive(windows)
-        dx_column = 'dx_{}'.format(window)
-        mdi_column = 'mdi_{}'.format(window)
-        pdi_column = 'pdi_{}'.format(window)
-        mdi, pdi = self[mdi_column], self[pdi_column]
-        self[dx_column] = abs(pdi - mdi) / (pdi + mdi) * 100
-        return self[dx_column]
+    def _get_pdi_ndi(self, window):
+        pdm, ndm = self._get_pdm_ndm(window)
+        atr = self._atr(window)
+        pdi = pdm / atr * 100
+        ndi = ndm / atr * 100
+        return pdi, ndi
+
+    def _get_pdi(self, meta: _Meta):
+        """ +DI, positive directional moving index """
+        pdi, _ = self._get_pdi_ndi(meta.int)
+        self[meta.name] = pdi
+        return pdi
+
+    def _get_ndi(self, meta: _Meta):
+        """ -DI, negative directional moving index """
+        _, ndi = self._get_pdi_ndi(meta.int)
+        self[meta.name] = ndi
+        return ndi
+
+    def _dx(self, window):
+        pdi, mdi = self._get_pdi_ndi(window)
+        return abs(pdi - mdi) / (pdi + mdi) * 100
 
-    def _get_kdj_default(self):
-        """ default KDJ, 9 periods
+    def _get_dx(self, meta: _Meta):
+        self[meta.name] = self._dx(meta.int)
 
-        :return: None
-        """
-        self['kdjk'] = self['kdjk_{}'.format(self.KDJ_WINDOW)]
-        self['kdjd'] = self['kdjd_{}'.format(self.KDJ_WINDOW)]
-        self['kdjj'] = self['kdjj_{}'.format(self.KDJ_WINDOW)]
-
-    def _get_cr(self, windows=None):
+    def _get_cr(self, meta: _Meta):
         """ Energy Index (Intermediate Willingness Index)
 
         https://support.futunn.com/en/topic167/?lang=en-us
         Use the relationship between the highest price, the lowest price and
         yesterday's middle price to reflect the market's willingness to buy
         and sell.
-
-        :param windows: window of the moving sum
-        :return: None
         """
-        if windows is None:
-            window = 26
-        else:
-            window = self.get_int_positive(windows)
-
+        window = meta.int
         middle = self._tp()
         last_middle = self._shift(middle, -1)
         ym = self._shift(middle, -1)
         high = self['high']
         low = self['low']
         p1_m = pd.concat((last_middle, high), axis=1).min(axis=1)
         p2_m = pd.concat((last_middle, low), axis=1).min(axis=1)
-        p1 = self._mov_sum(high - p1_m, window)
-        p2 = self._mov_sum(ym - p2_m, window)
+        p1 = self.mov_sum(high - p1_m, window)
+        p2 = self.mov_sum(ym - p2_m, window)
 
-        if windows is None:
-            cr = 'cr'
-            cr_ma1 = 'cr-ma1'
-            cr_ma2 = 'cr-ma2'
-            cr_ma3 = 'cr-ma3'
-        else:
-            cr = 'cr_{}'.format(window)
-            cr_ma1 = 'cr_{}-ma1'.format(window)
-            cr_ma2 = 'cr_{}-ma2'.format(window)
-            cr_ma3 = 'cr_{}-ma3'.format(window)
-
-        self[cr] = cr = p1 / p2 * 100
-        self[cr_ma1] = self._shifted_cr_sma(cr, self.CR_MA1)
-        self[cr_ma2] = self._shifted_cr_sma(cr, self.CR_MA2)
-        self[cr_ma3] = self._shifted_cr_sma(cr, self.CR_MA3)
+        name = meta.name
+        self[name] = cr = p1 / p2 * 100
+        self[f'{name}-ma1'] = self._shifted_cr_sma(cr, self.CR_MA[0])
+        self[f'{name}-ma2'] = self._shifted_cr_sma(cr, self.CR_MA[1])
+        self[f'{name}-ma3'] = self._shifted_cr_sma(cr, self.CR_MA[2])
 
     def _shifted_cr_sma(self, cr, window):
-        cr_sma = self._sma(cr, window)
+        cr_sma = self.sma(cr, window)
         return self._shift(cr_sma, -int(window / 2.5 + 1))
 
     def _tp(self):
         if 'amount' in self:
             return self['amount'] / self['volume']
         return (self['close'] + self['high'] + self['low']).divide(3.0)
 
-    def _get_tp(self):
-        self['tp'] = self._tp()
+    def _get_tp(self, meta: _Meta):
+        self[meta.name] = self._tp()
 
-    def _get_middle(self):
-        self['middle'] = self._tp()
+    def _get_middle(self, meta: _Meta):
+        self[meta.name] = self._tp()
 
     def _calc_kd(self, column):
         param0, param1 = self.KDJ_PARAM
         k = 50.0
         # noinspection PyTypeChecker
         for i in param1 * column:
             k = param0 * k + i
             yield k
 
-    def _get_kdjk(self, window):
+    def _get_kdjk(self, meta: _Meta):
         """ Get the K of KDJ
 
         K ＝ 2/3 × (prev. K) +1/3 × (curr. RSV)
         2/3 and 1/3 are the smooth parameters.
-        :param window: number of periods
-        :return: None
         """
-        rsv_column = 'rsv_{}'.format(window)
-        k_column = 'kdjk_{}'.format(window)
-        self[k_column] = list(self._calc_kd(self.get(rsv_column)))
+        window = meta.int
+        rsv = self._rsv(window)
+        self[meta.name] = list(self._calc_kd(rsv))
 
-    def _get_kdjd(self, window):
+    def _get_kdjd(self, meta: _Meta):
         """ Get the D of KDJ
 
         D = 2/3 × (prev. D) +1/3 × (curr. K)
         2/3 and 1/3 are the smooth parameters.
-        :param window: number of periods
-        :return: None
         """
-        k_column = 'kdjk_{}'.format(window)
-        d_column = 'kdjd_{}'.format(window)
-        self[d_column] = list(self._calc_kd(self.get(k_column)))
+        k_column = meta.name.replace('kdjd', 'kdjk')
+        self[meta.name] = list(self._calc_kd(self.get(k_column)))
 
-    def _get_kdjj(self, window):
+    def _get_kdjj(self, meta: _Meta):
         """ Get the J of KDJ
 
         J = 3K-2D
-        :param self: data
-        :param window: number of periods
-        :return: None
         """
-        k_column = 'kdjk_{}'.format(window)
-        d_column = 'kdjd_{}'.format(window)
-        j_column = 'kdjj_{}'.format(window)
-        self[j_column] = 3 * self[k_column] - 2 * self[d_column]
+        k_column = meta.name.replace('kdjj', 'kdjk')
+        d_column = meta.name.replace('kdjj', 'kdjd')
+        self[meta.name] = 3 * self[k_column] - 2 * self[d_column]
 
     @staticmethod
     def _delta(series, window):
         return series.diff(-window).fillna(0.0)
 
-    def _get_d(self, column, shifts):
-        shift = self.to_int(shifts)
-        column_name = '{}_{}_d'.format(column, shift)
-        self[column_name] = self._delta(self[column], shift)
+    def _get_d(self, meta: _Meta):
+        self[meta.name] = self._delta(self[meta.column], meta.int)
 
-    @staticmethod
-    def _mov_min(series, size):
-        return series.rolling(min_periods=1, window=size, center=False).min()
+    @classmethod
+    def mov_min(cls, series, size):
+        return cls._rolling(series, size).min()
 
-    @staticmethod
-    def _mov_max(series, size):
-        return series.rolling(min_periods=1, window=size, center=False).max()
+    @classmethod
+    def mov_max(cls, series, size):
+        return cls._rolling(series, size).max()
 
-    @staticmethod
-    def _mov_sum(series, size):
-        return series.rolling(min_periods=1, window=size, center=False).sum()
+    @classmethod
+    def mov_sum(cls, series, size):
+        return cls._rolling(series, size).sum()
+
+    @classmethod
+    def sma(cls, series, size):
+        return cls._rolling(series, size).mean()
 
     @staticmethod
-    def _sma(series, size):
-        return series.rolling(min_periods=1, window=size, center=False).mean()
+    def roc(series, size):
+        ret = series.diff(size) / series.shift(size)
+        if size < 0:
+            ret.iloc[size:] = 0
+        else:
+            ret.iloc[:size] = 0
+        return ret * 100
 
-    def _get_sma(self, column, windows):
-        """ get simple moving average
+    @classmethod
+    def _mad(cls, series, window):
+        """ Mean Absolute Deviation
 
-        :param column: column to calculate
-        :param windows: collection of window of simple moving average
-        :return: None
+        :param series: Series
+        :param window: number of periods
+        :return: Series
+        """
+
+        def f(x):
+            return np.fabs(x - x.mean()).mean()
+
+        return cls._rolling(series, window).apply(f, raw=True)
+
+    def _get_mad(self, meta: _Meta):
+        """ get mean absolute deviation """
+        window = meta.int
+        self[meta.name] = self._mad(self[meta.column], window)
+
+    def _get_sma(self, meta: _Meta):
+        """ get simple moving average """
+        window = meta.int
+        self[meta.name] = self.sma(self[meta.column], window)
+
+    def _get_lrma(self, meta: _Meta):
+        """ get linear regression moving average """
+        window = meta.int
+        self[meta.name] = self.linear_reg(self[meta.column], window)
+
+    def _get_roc(self, meta: _Meta):
+        """get Rate of Change (ROC) of a column
+
+        The Price Rate of Change (ROC) is a momentum-based technical indicator
+        that measures the percentage change in price between the current price
+        and the price a certain number of periods ago.
+
+        https://www.investopedia.com/terms/p/pricerateofchange.asp
+
+        Formular:
+
+        ROC = (PriceP - PricePn) / PricePn * 100
+
+        Where:
+        * PriceP: the price of the current period
+        * PricePn: the price of the n periods ago
         """
-        window = self.get_int_positive(windows)
-        column_name = '{}_{}_sma'.format(column, window)
-        self[column_name] = self._sma(self[column], window)
+        self[meta.name] = self.roc(self[meta.column], meta.int)
 
     @staticmethod
-    def _ema(series, window):
+    def ema(series, window, *, adjust=True):
         return series.ewm(
             ignore_na=False,
             span=window,
-            min_periods=0,
-            adjust=True).mean()
+            min_periods=1,
+            adjust=adjust).mean()
+
+    @staticmethod
+    def _rolling(series: pd.Series, window: int):
+        return series.rolling(window, min_periods=1, center=False)
 
-    def _get_ema(self, column, windows):
-        """ get exponential moving average
+    @classmethod
+    def linear_wma(cls, series, window):
+        total_weight = 0.5 * window * (window + 1)
+        weights = np.arange(1, window + 1) / total_weight
+
+        def linear(w):
+            def _compute(x):
+                try:
+                    return np.dot(x, w)
+                except ValueError:
+                    return 0.0
 
-        :param column: column to calculate
-        :param windows: collection of window of exponential moving average
-        :return: None
-        """
-        window = self.get_int_positive(windows)
-        column_name = '{}_{}_ema'.format(column, window)
-        self[column_name] = self._ema(self[column], window)
+            return _compute
 
-    def _get_boll(self, window=None):
+        rolling = cls._rolling(series, window)
+        return rolling.apply(linear(weights), raw=True)
+
+    @classmethod
+    def linear_reg(cls,
+                   series,
+                   window,
+                   correlation=False):
+        window = cls.get_int_positive(window)
+
+        x = range(1, window + 1)
+        x_sum = 0.5 * window * (window + 1)
+        x2_sum = x_sum * (2 * window + 1) / 3
+        divisor = window * x2_sum - x_sum * x_sum
+
+        def linear_regression(s: pd.Series):
+            y_sum = s.sum()
+            xy_sum = (x * s).sum()
+
+            m = (window * xy_sum - x_sum * y_sum) / divisor
+            b = (y_sum * x2_sum - x_sum * xy_sum) / divisor
+
+            if correlation:
+                y2_sum = (s * s).sum()
+                rn = window * xy_sum - x_sum * y_sum
+                rd = (divisor * (window * y2_sum - y_sum * y_sum)) ** 0.5
+                return rn / rd
+            return m * (window - 1) + b
+
+        def rolling(arr):
+            strides = arr.strides + (arr.strides[-1],)
+            shape = arr.shape[:-1] + (arr.shape[-1] - window + 1, window)
+            return as_strided(arr, shape=shape, strides=strides)
+
+        value = [linear_regression(_)
+                 for _ in rolling(np.array(series))]
+        ret = pd.Series([0.0] * (window - 1) + value,
+                        index=series.index)
+        return ret
+
+    def _get_cti(self, meta: _Meta):
+        """ get correlation trend indicator
+
+        Correlation Trend Indicator is a study that estimates
+        the current direction and strength of a trend.
+        https://tlc.thinkorswim.com/center/reference/Tech-Indicators/studies-library/C-D/CorrelationTrendIndicator
+        """
+        value = self.linear_reg(
+            self[meta.column], meta.int, correlation=True)
+        self[meta.name] = value
+
+    def _get_ema(self, meta: _Meta):
+        """ get exponential moving average """
+        self[meta.name] = self.ema(self[meta.column], meta.int)
+
+    def _get_boll(self, meta: _Meta):
         """ Get Bollinger bands.
 
         boll_ub means the upper band of the Bollinger bands
         boll_lb means the lower band of the Bollinger bands
         boll_ub = MA + Kσ
         boll_lb = MA − Kσ
         M = BOLL_PERIOD
         K = BOLL_STD_TIMES
         :return: None
         """
-        if window is None:
-            n = self.BOLL_PERIOD
-            boll = 'boll'
-            boll_ub = 'boll_ub'
-            boll_lb = 'boll_lb'
-        else:
-            n = self.get_int_positive(window)
-            boll = 'boll_{}'.format(n)
-            boll_ub = 'boll_ub_{}'.format(n)
-            boll_lb = 'boll_lb_{}'.format(n)
-        moving_avg = self._sma(self['close'], n)
-        moving_std = self._mstd(self['close'], n)
+        n = meta.int
+        boll = meta.name
+        boll_ub = meta.name_ex('_ub')
+        boll_lb = meta.name_ex('_lb')
+        moving_avg = self.sma(self['close'], n)
+        moving_std = self.mov_std(self['close'], n)
 
         self[boll] = moving_avg
         width = self.BOLL_STD_TIMES * moving_std
         self[boll_ub] = moving_avg + width
         self[boll_lb] = moving_avg - width
 
-    def _get_macd(self):
+    def _get_macd(self, meta: _Meta):
         """ Moving Average Convergence Divergence
 
         This function will initialize all following columns.
 
         MACD Line (macd): (12-day EMA - 26-day EMA)
         Signal Line (macds): 9-day EMA of MACD Line
         MACD Histogram (macdh): MACD Line - Signal Line
-
-        :return: None
         """
         close = self['close']
-        ema_short = self._ema(close, self.MACD_EMA_SHORT)
-        ema_long = self._ema(close, self.MACD_EMA_LONG)
-        self['macd'] = ema_short - ema_long
-        self['macds'] = self._ema(self['macd'], self.MACD_EMA_SIGNAL)
-        self['macdh'] = self['macd'] - self['macds']
+        short_w, long_w, signal_w = meta.int0, meta.int1, meta.int2
+        ema_short = self.ema(close, short_w)
+        ema_long = self.ema(close, long_w)
+        macd = meta.name
+        macds = meta.name_ex('s')
+        macdh = meta.name_ex('h')
+        self[macd] = ema_short - ema_long
+        self[macds] = self.ema(self[macd], signal_w)
+        self[macdh] = self[macd] - self[macds]
 
-    def _get_ppo(self):
+    def _get_ppo(self, meta: _Meta):
         """ Percentage Price Oscillator
 
         https://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:price_oscillators_ppo
 
         Percentage Price Oscillator (PPO):
             {(12-day EMA - 26-day EMA)/26-day EMA} x 100
 
         Signal Line: 9-day EMA of PPO
 
         PPO Histogram: PPO - Signal Line
-
-        :return: None
         """
         close = self['close']
-        ppo_short = self._ema(close, self.PPO_EMA_SHORT)
-        ppo_long = self._ema(close, self.PPO_EMA_LONG)
+        short_w, long_w, signal_w = meta.int0, meta.int1, meta.int2
+        ppo_short = self.ema(close, short_w)
+        ppo_long = self.ema(close, long_w)
         self['ppo'] = (ppo_short - ppo_long) / ppo_long * 100
-        self['ppos'] = self._ema(self['ppo'], self.PPO_EMA_SIGNAL)
+        self['ppos'] = self.ema(self['ppo'], signal_w)
         self['ppoh'] = self['ppo'] - self['ppos']
 
-    def get_int_positive(self, windows):
+    def _eri(self, window):
+        ema = self.ema(self['close'], window, adjust=False)
+        bull = self['high'] - ema
+        bear = self['low'] - ema
+        return bull, bear
+
+    def _get_eribull(self, meta: _Meta):
+        """ The bull line of Elder-Ray Index """
+        bull, _ = self._eri(meta.int)
+        self[meta.name] = bull
+        return bull
+
+    def _get_eribear(self, meta: _Meta):
+        """ The bear line of Elder-Ray Index """
+        _, bear = self._eri(meta.int)
+        self[meta.name] = bear
+        return bear
+
+    def _get_eri(self, meta: _Meta):
+        """ The Elder-Ray Index
+
+        The Elder-Ray Index contains the bull and the bear power.
+        Both are calculated based on the EMA of the close price.
+
+        The default window is 13.
+
+        https://admiralmarkets.com/education/articles/forex-indicators/bears-and-bulls-power-indicator
+
+        Formular:
+        * Bulls Power = High - EMA
+        * Bears Power = Low - EMA
+        * EMA is exponential moving average of close of N periods
+        """
+        bull, bear = self._eri(meta.int)
+        self[meta.name_ex('bull')] = bull
+        self[meta.name_ex('bear')] = bear
+
+    def _get_coppock(self, meta: _Meta):
+        """ Get Coppock Curve
+
+        Coppock Curve is a momentum indicator that signals
+        long-term trend reversals.
+
+        https://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:coppock_curve
+        """
+        window, fast, slow = meta.int0, meta.int1, meta.int2
+        fast_roc = self.roc(self['close'], fast)
+        slow_roc = self.roc(self['close'], slow)
+        roc_ema = self.linear_wma(fast_roc + slow_roc, window)
+        self[meta.name] = roc_ema
+
+    @classmethod
+    def get_int_positive(cls, windows):
         if isinstance(windows, int):
             window = windows
         else:
-            window = self.to_int(windows)
+            window = cls.to_int(windows)
             if window <= 0:
                 raise IndexError("window must be greater than 0")
         return window
 
-    @staticmethod
-    def _mstd(series, window):
-        return series.rolling(min_periods=1, window=window, center=False).std()
+    def _hl_mid(self, period):
+        ph = self.mov_max(self['high'], period)
+        pl = self.mov_min(self['low'], period)
+        return (ph + pl) * 0.5
+
+    def _get_ichimoku(self, meta: _Meta):
+        """ get Ichimoku Cloud
+
+        The Ichimoku Cloud is a collection of technical indicators
+        that show support and resistance levels, as well as momentum
+        and trend direction.
+
+        In this implementation, we only calculate the delta between
+        lead A and lead B.
+
+        https://www.investopedia.com/terms/i/ichimoku-cloud.asp
+
+        It contains three windows:
+        * window for the conversion line, default to 9
+        * window for the baseline and the shifts, default to 26
+        * window for the leading line, default to 52
+
+        Formular:
+        * conversion line = (PH9 + PL9) / 2
+        * baseline = (PH26 + PL26) / 2
+        * leading span A = (conversion line + baseline) / 2
+        * leading span B = (PH52 + PL52) / 2
+        * result = leading span A - leading span B
 
-    def _get_mstd(self, column, windows):
-        """ get moving standard deviation
+        Where:
+        * PH = Period High
+        * PL = Period Low
 
-        :param column: column to calculate
-        :param windows: collection of window of moving standard deviation
-        :return: None
         """
-        window = self.get_int_positive(windows)
-        column_name = '{}_{}_mstd'.format(column, window)
-        self[column_name] = self._mstd(self[column], window)
+        conv, base, lead = meta.int0, meta.int1, meta.int2
+        conv_line = self._hl_mid(conv)
+        base_line = self._hl_mid(base)
+        lead_a = (conv_line + base_line) * 0.5
+        lead_b = self._hl_mid(lead)
+
+        lead_a_s = lead_a.shift(base, fill_value=lead_a.iloc[0])
+        lead_b_s = lead_b.shift(base, fill_value=lead_b.iloc[0])
+        self[meta.name] = lead_a_s - lead_b_s
+
+    @classmethod
+    def mov_std(cls, series, window):
+        return cls._rolling(series, window).std()
 
-    def _get_mvar(self, column, windows):
-        """ get moving variance
+    def _get_mstd(self, meta: _Meta):
+        """ get moving standard deviation """
+        self[meta.name] = self.mov_std(self[meta.column], meta.int)
 
-        :param column: column to calculate
-        :param windows: collection of window of moving variance
-        :return: None
-        """
-        window = self.get_int_positive(windows)
-        column_name = '{}_{}_mvar'.format(column, window)
-        self[column_name] = self[column].rolling(
-            min_periods=1, window=window, center=False).var()
+    @classmethod
+    def mov_var(cls, series, window):
+        return cls._rolling(series, window).var()
+
+    def _get_mvar(self, meta: _Meta):
+        """ get moving variance """
+        self[meta.name] = self.mov_var(self[meta.column], meta.int)
 
-    def _get_vwma(self, window=None):
+    def _get_vwma(self, meta: _Meta):
         """ get Volume Weighted Moving Average
 
         The definition is available at:
         https://www.investopedia.com/articles/trading/11/trading-with-vwap-mvwap.asp
-
-        :param window: number of periods relevant for the indicator
-        :return: None
         """
-        if window is None:
-            window = self.VWMA
-            column_name = 'vwma'
-        else:
-            column_name = 'vwma_{}'.format(window)
-        window = self.get_int_positive(window)
-
+        window = meta.int
         tpv = self['volume'] * self._tp()
-        rolling_tpv = self._mov_sum(tpv, window)
-        rolling_vol = self._mov_sum(self['volume'], window)
-        self[column_name] = rolling_tpv / rolling_vol
+        rolling_tpv = self.mov_sum(tpv, window)
+        rolling_vol = self.mov_sum(self['volume'], window)
+        self[meta.name] = rolling_tpv / rolling_vol
 
-    def _get_chop(self, window=None):
+    def _get_chop(self, meta: _Meta):
         """ get Choppiness Index (CHOP)
 
         See the definition of the index here:
         https://www.tradingview.com/education/choppinessindex/
 
         Calculation:
 
         100 * LOG10( SUM(ATR(1), n) / ( MaxHi(n) - MinLo(n) ) ) / LOG10(n)
         n = User defined period length.
         LOG10(n) = base-10 LOG of n
         ATR(1) = Average True Range (Period of 1)
         SUM(ATR(1), n) = Sum of the Average True Range over past n bars
         MaxHi(n) = The highest high over past n bars
-
-        :param window: number of periods relevant for the indicator
-        :return: None
         """
-        if window is None:
-            window = self.CHOP
-            column_name = 'chop'
-        else:
-            column_name = 'chop_{}'.format(window)
-        window = self.get_int_positive(window)
+        window = meta.int
         atr = self._atr(1)
-        atr_sum = self._mov_sum(atr, window)
-        high = self._mov_max(self['high'], window)
-        low = self._mov_min(self['low'], window)
+        atr_sum = self.mov_sum(atr, window)
+        high = self.mov_max(self['high'], window)
+        low = self.mov_min(self['low'], window)
         choppy = atr_sum / (high - low)
         numerator = np.log10(choppy) * 100
         denominator = np.log10(window)
-        self[column_name] = numerator / denominator
+        self[meta.name] = numerator / denominator
 
-    def _get_mfi(self, window=None):
+    def _get_mfi(self, meta: _Meta):
         """ get money flow index
 
         The definition of money flow index is available at:
         https://www.investopedia.com/terms/m/mfi.asp
-
-        :param window: number of periods relevant for the indicator
-        :return: None
         """
-        if window is None:
-            window = self.MFI
-            column_name = 'mfi'
-        else:
-            column_name = 'mfi_{}'.format(window)
-        window = self.get_int_positive(window)
+        window = meta.int
         middle = self._tp()
         money_flow = (middle * self["volume"]).fillna(0.0)
         shifted = self._shift(middle, -1)
         delta = (middle - shifted).fillna(0)
         pos_flow = money_flow.mask(delta < 0, 0)
         neg_flow = money_flow.mask(delta >= 0, 0)
-        rolling_pos_flow = self._mov_sum(pos_flow, window)
-        rolling_neg_flow = self._mov_sum(neg_flow, window)
+        rolling_pos_flow = self.mov_sum(pos_flow, window)
+        rolling_neg_flow = self.mov_sum(neg_flow, window)
         money_flow_ratio = rolling_pos_flow / (rolling_neg_flow + 1e-12)
         mfi = (1.0 - 1.0 / (1 + money_flow_ratio))
         mfi.iloc[:window] = 0.5
-        self[column_name] = mfi
+        self[meta.name] = mfi
 
-    def _get_ao(self, windows=None):
+    def _get_ao(self, meta: _Meta):
         """ get awesome oscillator
 
         The AO indicator is a good indicator for measuring the market dynamics,
         it reflects specific changes in the driving force of the market, which
         helps to identify the strength of the trend, including the points of
         its formation and reversal.
 
 
         Awesome Oscillator Formula
         * MEDIAN PRICE = (HIGH+LOW)/2
         * AO = SMA(MEDIAN PRICE, 5)-SMA(MEDIAN PRICE, 34)
 
         https://www.ifcm.co.uk/ntx-indicators/awesome-oscillator
         """
-        if windows is None:
-            fast = self.AO_FAST
-            slow = self.AO_SLOW
-            column_name = 'ao'
-        else:
-            n0, n1 = self.to_ints(windows)
-            fast = min(n0, n1)
-            slow = max(n0, n1)
-            column_name = 'ao_{},{}'.format(fast, slow)
-
+        fast = meta.int0
+        slow = meta.int1
         median_price = (self['high'] + self['low']) * 0.5
-        ao = self._sma(median_price, fast) - self._sma(median_price, slow)
-        self[column_name] = ao
+        ao = self.sma(median_price, fast) - self.sma(median_price, slow)
+        self[meta.name] = ao
 
-    def _get_kama(self, column, windows, fasts=None, slows=None):
-        """ get Kaufman's Adaptive Moving Average.
-        Implemented after
-        https://school.stockcharts.com/doku.php?id=technical_indicators:kaufman_s_adaptive_moving_average
+    def _get_bop(self, meta: _Meta):
+        """ get balance of power
 
-        :param column: column to calculate
-        :param windows: collection of window of exponential moving average
-        :param fasts: fastest EMA constant
-        :param slows: slowest EMA constant
-        :return: None
-        """
-        window = self.get_int_positive(windows)
-        if slows is None or fasts is None:
-            slow, fast = self.KAMA_SLOW, self.KAMA_FAST
-            column_name = "{}_{}_kama".format(column, window)
-        else:
-            slow = self.get_int_positive(slows)
-            fast = self.get_int_positive(fasts)
-            column_name = '{}_{}_kama_{}_{}'.format(column, window, fast, slow)
+        The Balance of Power indicator measures the strength of the bulls.
+        https://school.stockcharts.com/doku.php?id=technical_indicators:balance_of_power
+
+        BOP = (close - open) / (high - low)
+        """
+        dividend = self['close'] - self['open']
+        divisor = self['high'] - self['low']
+        self[meta.name] = dividend / divisor
+
+    def _get_cmo(self, meta: _Meta):
+        """ get Chande Momentum Oscillator
+
+        The Chande Momentum Oscillator (CMO) is a technical momentum
+        indicator developed by Tushar Chande.
+        https://www.investopedia.com/terms/c/chandemomentumoscillator.asp
+
+        CMO = 100 * ((sH - sL) / (sH + sL))
+
+        where:
+        * sH=the sum of higher closes over N periods
+        * sL=the sum of lower closes of N periods
+        """
+        window = meta.int
+        close_diff = self._col_diff('close')
+        up = close_diff.clip(lower=0)
+        down = close_diff.clip(upper=0).abs()
+        sum_up = self.mov_sum(up, window)
+        sum_down = self.mov_sum(down, window)
+        dividend = sum_up - sum_down
+        divisor = sum_up + sum_down
+        res = 100 * dividend / divisor
+        res.iloc[0] = 0.0
+        self[meta.name] = res
 
+    def ker(self, column, window):
         col = self[column]
         col_window_s = self._shift(col, -window)
-        col_last = self._shift(col, -1)
-        change = (col - col_window_s).abs()
-        volatility = self._mov_sum((col - col_last).abs(), window)
-        efficiency_ratio = change / volatility
+        window_diff = (col - col_window_s).abs()
+        diff = self._col_diff(column).abs()
+        volatility = self.mov_sum(diff, window)
+        ret = window_diff / volatility
+        ret.iloc[0] = 0
+        return ret
+
+    def _get_ker(self, meta: _Meta):
+        """ get Kaufman's efficiency ratio
+
+        The Efficiency Ratio (ER) is calculated by
+        dividing the price change over a period by the
+        absolute sum of the price movements that occurred
+        to achieve that change.
+        The resulting ratio ranges between 0 and 1 with
+        higher values representing a more efficient or
+        trending market.
+
+        The default column is close.
+        The default window is 10.
+
+        https://strategyquant.com/codebase/kaufmans-efficiency-ratio-ker/
+
+        Formular:
+        window_change = ABS(close - close[n])
+        last_change = ABS(close-close[1])
+        volatility = moving sum of last_change in n
+        KER = window_change / volatility
+        """
+        self[meta.name] = self.ker(meta.column, meta.int)
+
+    def _get_kama(self, meta: _Meta):
+        """ get Kaufman's Adaptive Moving Average.
+        Implemented after
+        https://school.stockcharts.com/doku.php?id=technical_indicators:kaufman_s_adaptive_moving_average
+        """
+        window, fast, slow = meta.int0, meta.int1, meta.int2
+        efficiency_ratio = self.ker(meta.column, window)
         fast_ema_smoothing = 2.0 / (fast + 1)
         slow_ema_smoothing = 2.0 / (slow + 1)
         smoothing_2 = fast_ema_smoothing - slow_ema_smoothing
         efficient_smoothing = efficiency_ratio * smoothing_2
         smoothing = list(2 * (efficient_smoothing + slow_ema_smoothing))
 
         # start with simple moving average
-        kama = list(self._sma(col, window))
-        col_list = list(col)
+        col = self[meta.column]
+        kama = list(self.sma(col, window))
         if len(kama) >= window:
             last_kama = kama[window - 1]
         else:
             last_kama = 0.0
+
+        col_list = list(col)
         for i in range(window, len(kama)):
             cur = smoothing[i] * (col_list[i] - last_kama) + last_kama
             kama[i] = cur
             last_kama = cur
-        self[column_name] = kama
+        self[meta.name] = kama
+
+    def _ftr(self, window: int) -> pd.Series:
+        mp = (self.high + self.low) * 0.5
+        highest = mp.rolling(window).max()
+        lowest = mp.rolling(window).min()
+        width = highest - lowest
+        width[width < 0.001] = 0.001
+        position = list(((mp - lowest) / width) - 0.5)
+
+        v = 0
+        size = self.high.size
+        result = np.zeros(size)
+        for i in range(window, size):
+            v = 0.66 * position[i] + 0.67 * v
+            if v < -0.99:
+                v = -0.999
+            if v > 0.99:
+                v = 0.999
+            r = 0.5 * (np.log((1 + v) / (1 - v)) + result[i - 1])
+            result[i] = r
+        return pd.Series(result, index=self.index)
+
+    def _get_ftr(self, meta: _Meta):
+        """ the Gaussian Fisher Transform Price Reversals indicator
+
+        The Gaussian Fisher Transform Price Reversals indicator, dubbed
+        FTR for short, is a stat based price reversal detection indicator
+        inspired by and based on the work of the electrical engineer
+        now private trader John F. Ehlers.
+
+        https://www.tradingview.com/script/ajZT2tZo-Gaussian-Fisher-Transform-Price-Reversals-FTR/
+
+        Implementation reference:
+
+        https://github.com/twopirllc/pandas-ta/blob/084dbe1c4b76082f383fa3029270ea9ac35e4dc7/pandas_ta/momentum/fisher.py#L9
+
+        Formular:
+        * Fisher Transform = 0.5 * ln((1 + X) / (1 - X))
+        * X is a series whose values are between -1 to 1
+        """
+        self[meta.name] = self._ftr(meta.int)
+
+    @staticmethod
+    def sym_wma4(series: pd.Series) -> pd.Series:
+        arr = np.array([1, 2, 2, 1])
+        weights = arr / sum(arr)
+        rolled = series.rolling(arr.size)
+        ret = rolled.apply(lambda x: np.dot(x, weights), raw=True)
+        ret.iloc[:arr.size - 1] = 0.0
+        return ret
+
+    def _rvgi(self, window: int) -> pd.Series:
+        """ Relative Vigor Index (RVGI)
+
+        The Relative Vigor Index (RVI) is a momentum indicator
+        used in technical analysis that measures the strength
+        of a trend by comparing a security's closing price to
+        its trading range while smoothing the results using a
+        simple moving average (SMA).
+
+        https://www.investopedia.com/terms/r/relative_vigor_index.asp
+
+        Formular
+        * NUMERATOR= (a+(2×b)+(2×c)+d) / 6
+        * DENOMINATOR= (e+(2×f)+(2×g)+h) / 6
+        * RVI= SMA-N of DENOMINATOR / SMA-N of NUMERATOR
+        * Signal Line = (RVI+(2×i)+(2×j)+k) / 6
+
+        where:
+        * a=Close−Open
+        * b=Close−Open One Bar Prior to a
+        * c=Close−Open One Bar Prior to b
+        * d=Close−Open One Bar Prior to c
+        * e=High−Low of Bar a
+        * f=High−Low of Bar b
+        * g=High−Low of Bar c
+        * h=High−Low of Bar d
+        * i=RVI Value One Bar Prior
+        * j=RVI Value One Bar Prior to i
+        * k=RVI Value One Bar Prior to j
+        * N=Minutes/Hours/Days/Weeks/Months
+        """
+        co = self.close - self.open
+        hl = self.high - self.low
+
+        nu = self.sym_wma4(co)
+        de = self.sym_wma4(hl)
+        ret = self.sma(nu, window) / self.sma(de, window)
+        return ret
+
+    def _get_rvgis(self, meta: _Meta):
+        self._get_rvgi(meta.set_name('rvgi'))
+
+    def _get_rvgi(self, meta: _Meta):
+        rvgi = self._rvgi(meta.int)
+        rvgi.iloc[:3] = 0.0
+        rvgi_s = self.sym_wma4(rvgi)
+        rvgi_s.iloc[:6] = 0.0
+        self[meta.name] = rvgi
+        self[meta.name_ex('s')] = rvgi_s
 
     @staticmethod
     def parse_column_name(name):
         m = re.match(r'(.*)_([\d\-+~,.]+)_(\w+)', name)
         ret = (None,)
         if m is None:
             m = re.match(r'(.*)_([\d\-+~,]+)', name)
             if m is not None:
                 ret = m.group(1, 2)
         else:
             ret = m.group(1, 2, 3)
-            if any(map(lambda i: i in ret[0],
-                       StockDataFrame.MULTI_SPLIT_INDICATORS)):
-                m_prev = re.match(r'(.*)_([\d\-+~,.]+)_(\w+)', ret[0])
-                if m_prev is not None:
-                    ret = m_prev.group(1, 2, 3) + ret[1:]
         return ret
 
     CROSS_COLUMN_MATCH_STR = '(.+)_(x|xu|xd)_(.+)'
 
     @classmethod
     def is_cross_columns(cls, name):
         return re.match(cls.CROSS_COLUMN_MATCH_STR, name) is not None
@@ -1275,24 +1556,26 @@
     def parse_cross_column(cls, name):
         m = re.match(cls.CROSS_COLUMN_MATCH_STR, name)
         ret = [None, None, None]
         if m is not None:
             ret = m.group(1, 2, 3)
         return ret
 
-    def _get_rate(self):
-        """ same as percent
-
-        :return: None
-        """
+    def _get_rate(self, _: _Meta):
+        """ same as percent """
         self['rate'] = self['close'].pct_change() * 100
 
+    def _col_diff(self, col):
+        ret = self[col].diff()
+        ret.iloc[0] = 0.0
+        return ret
+
     def _get_delta(self, key):
         key_to_delta = key.replace('_delta', '')
-        self[key] = self[key_to_delta].diff()
+        self[key] = self._col_diff(key_to_delta)
         return self[key]
 
     def _get_cross(self, key):
         left, op, right = StockDataFrame.parse_cross_column(key)
         lt_series = self[left] > self[right]
         # noinspection PyTypeChecker
         different = np.zeros_like(lt_series)
@@ -1307,15 +1590,15 @@
         elif op == 'xd':
             self[key] = different & ~lt_series
         return self[key]
 
     def init_all(self):
         """ initialize all stats. in the handler """
         for handler in self.handler.values():
-            handler()
+            _call_handler(handler)
 
     def drop_column(self, names=None, inplace=False):
         """ drop column by the name
 
         multiple names can be supplied in a list
         :return: StockDataFrame
         """
@@ -1356,66 +1639,72 @@
             ('stochrsi',): self._get_stochrsi,
             ('rate',): self._get_rate,
             ('middle',): self._get_middle,
             ('tp',): self._get_tp,
             ('boll', 'boll_ub', 'boll_lb'): self._get_boll,
             ('macd', 'macds', 'macdh'): self._get_macd,
             ('ppo', 'ppos', 'ppoh'): self._get_ppo,
-            ('kdjk', 'kdjd', 'kdjj'): self._get_kdj_default,
+            ('kdjk',): self._get_kdjk,
+            ('kdjd',): self._get_kdjd,
+            ('kdjj',): self._get_kdjj,
+            ('rsv',): self._get_rsv,
             ('cr', 'cr-ma1', 'cr-ma2', 'cr-ma3'): self._get_cr,
             ('cci',): self._get_cci,
             ('tr',): self._get_tr,
             ('atr',): self._get_atr,
-            ('um', 'dm'): self._get_um_dm,
-            ('pdi', 'mdi', 'dx', 'adx', 'adxr'): self._get_dmi,
+            ('pdi',): self._get_pdi,
+            ('ndi',): self._get_ndi,
+            ('dx', 'adx', 'adxr'): self._get_dmi,
             ('trix',): self._get_trix,
             ('tema',): self._get_tema,
             ('vr',): self._get_vr,
             ('dma',): self._get_dma,
             ('vwma',): self._get_vwma,
             ('chop',): self._get_chop,
             ('log-ret',): self._get_log_ret,
             ('mfi',): self._get_mfi,
-            ('wt1', 'wt2'): self._get_wave_trend,
+            ('wt1', 'wt2'): self._get_wt,
             ('wr',): self._get_wr,
             ('supertrend',
              'supertrend_lb',
              'supertrend_ub'): self._get_supertrend,
             ('aroon',): self._get_aroon,
             ('ao',): self._get_ao,
+            ('bop',): self._get_bop,
+            ('cmo',): self._get_cmo,
+            ('coppock',): self._get_coppock,
+            ('ichimoku',): self._get_ichimoku,
+            ('cti',): self._get_cti,
+            ('ker',): self._get_ker,
+            ('eribull', 'eribear'): self._get_eri,
+            ('ftr',): self._get_ftr,
+            ('rvgi', 'rvgis'): self._get_rvgi,
         }
 
     def __init_not_exist_column(self, key):
         for names, handler in self.handler.items():
             if key in names:
-                handler()
-                return
+                return _call_handler(handler)
 
         if key.endswith('_delta'):
             self._get_delta(key)
         elif self.is_cross_columns(key):
             self._get_cross(key)
         else:
             ret = self.parse_column_name(key)
-            if len(ret) == 5:
-                c, r, t, s, f = ret
-                func_name = '_get_{}'.format(t)
-                getattr(self, func_name)(c, r, s, f)
-            elif len(ret) == 3:
-                c, r, t = ret
-                func_name = '_get_{}'.format(t)
-                getattr(self, func_name)(c, r)
+            if len(ret) == 3:
+                col, n, name = ret
             elif len(ret) == 2:
-                c, r = ret
-                func_name = '_get_{}'.format(c)
-                getattr(self, func_name)(r)
+                name, n = ret
+                col = None
             else:
                 raise UserWarning("Invalid number of return arguments "
-                                  "after parsing column name: '{}'"
-                                  .format(key))
+                                  f"after parsing column name: '{key}'")
+            meta = _Meta(name, windows=n, column=col)
+            getattr(self, f'_get_{name}')(meta)
 
     def __init_column(self, key):
         if key not in self:
             if len(self) == 0:
                 self[key] = []
             else:
                 self.__init_not_exist_column(key)
@@ -1440,14 +1729,15 @@
 
     def start_from(self, start_date):
         return self[self.index >= start_date]
 
     def within(self, start_date, end_date):
         return self.start_from(start_date).till(end_date)
 
+    # noinspection PyFinal
     def copy(self, deep=True):
         return wrap(super(StockDataFrame, self).copy(deep))
 
     @staticmethod
     def _ensure_type(obj):
         """ override the method in pandas, omit the check
```

