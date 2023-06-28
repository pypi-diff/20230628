# Comparing `tmp/ckanext-dcat_usmetadata-0.4.1.tar.gz` & `tmp/ckanext-dcat_usmetadata-0.4.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ckanext-dcat_usmetadata-0.4.1.tar", last modified: Mon Jun  5 18:55:07 2023, max compression
+gzip compressed data, was "ckanext-dcat_usmetadata-0.4.2.tar", last modified: Wed Jun 28 14:57:03 2023, max compression
```

## Comparing `ckanext-dcat_usmetadata-0.4.1.tar` & `ckanext-dcat_usmetadata-0.4.2.tar`

### file list

```diff
@@ -1,196 +1,196 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/
--rw-r--r--   0 runner    (1001) docker     (123)    34499 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      202 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     9876 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     9359 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.200062 ckanext-dcat_usmetadata-0.4.1/ckanext/
--rw-r--r--   0 runner    (1001) docker     (123)      219 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.200062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2371 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/blueprint.py
--rw-r--r--   0 runner    (1001) docker     (123)     2247 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     1482 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/db_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.200062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/fanstatic/
--rw-r--r--   0 runner    (1001) docker     (123)      127 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/fanstatic/custom.css
--rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/fanstatic/webassets.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1158 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/plugin.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.196062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.196062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.232062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/
--rw-r--r--   0 runner    (1001) docker     (123)    25896 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.21c58d74.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    23344 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.9efe74f3.eot
--rw-r--r--   0 runner    (1001) docker     (123)    15644 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.b786d169.woff
--rw-r--r--   0 runner    (1001) docker     (123)    11496 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.fc1844c7.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    25880 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.18853b8c.eot
--rw-r--r--   0 runner    (1001) docker     (123)    39420 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.58093e86.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    14296 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.75fb25c1.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    20216 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.f09ccd61.woff
--rw-r--r--   0 runner    (1001) docker     (123)    33984 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.0078d318.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    24320 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.12b71a42.eot
--rw-r--r--   0 runner    (1001) docker     (123)    22436 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.22c8272f.woff
--rw-r--r--   0 runner    (1001) docker     (123)    90628 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.c99f7ae5.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    21308 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.115f5a1d.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    47228 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.46eab112.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    26892 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.704b3917.woff
--rw-r--r--   0 runner    (1001) docker     (123)    19568 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.2750a1e9.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    24464 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.69debb55.woff
--rw-r--r--   0 runner    (1001) docker     (123)    40472 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.9bce1501.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    19252 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.2412c72a.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    39480 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.3ee014ee.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    24152 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.b85b8ae5.woff
--rw-r--r--   0 runner    (1001) docker     (123)    21260 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.4f0fb504.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    26988 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.ddae281a.woff
--rw-r--r--   0 runner    (1001) docker     (123)    49164 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.e6dc7e59.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    18976 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.08acae9c.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    23808 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.af8e7e14.woff
--rw-r--r--   0 runner    (1001) docker     (123)    39456 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.efbd9a2b.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    27512 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.73c28f4e.woff
--rw-r--r--   0 runner    (1001) docker     (123)    49484 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.efc70b44.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    21692 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.fa9b615a.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    11584 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.3c4dc405.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    15440 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.6a13b444.woff
--rw-r--r--   0 runner    (1001) docker     (123)    23602 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.8bb31d27.eot
--rw-r--r--   0 runner    (1001) docker     (123)    23424 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.bf0b1c03.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    13048 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.318b4f41.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    25792 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.346b43cf.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    25978 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.9487423d.eot
--rw-r--r--   0 runner    (1001) docker     (123)    17204 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.c0de58fc.woff
--rw-r--r--   0 runner    (1001) docker     (123)    22902 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.33ec9bca.eot
--rw-r--r--   0 runner    (1001) docker     (123)    15284 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.467063b1.woff
--rw-r--r--   0 runner    (1001) docker     (123)    22712 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.cb95bc69.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    11472 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.e3b01381.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    23032 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.80744a04.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    15364 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.8e80acc0.woff
--rw-r--r--   0 runner    (1001) docker     (123)    11536 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.aebd17d5.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    23226 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.d543421f.eot
--rw-r--r--   0 runner    (1001) docker     (123)      173 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/add.0e3e08bc.svg
--rw-r--r--   0 runner    (1001) docker     (123)      552 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down-primary.51295a10.svg
--rw-r--r--   0 runner    (1001) docker     (123)      544 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down.8e2c6296.svg
--rw-r--r--   0 runner    (1001) docker     (123)      542 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-right.0f46e09b.svg
--rw-r--r--   0 runner    (1001) docker     (123)      551 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-up-white.e60b3e19.svg
--rw-r--r--   0 runner    (1001) docker     (123)      625 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-double-left-solid.a1c42657.svg
--rw-r--r--   0 runner    (1001) docker     (123)      629 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-double-right-solid.9addc335.svg
--rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-left-solid.247b735a.svg
--rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-right-solid.fe82c509.svg
--rw-r--r--   0 runner    (1001) docker     (123)      558 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-both.0bfe2193.svg
--rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-both.50893060.svg
--rw-r--r--   0 runner    (1001) docker     (123)      566 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-down-gray-60.9b52f832.svg
--rw-r--r--   0 runner    (1001) docker     (123)      551 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-down.6c056294.svg
--rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-down.cb9919ed.svg
--rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-left.ffd0d3ac.svg
--rw-r--r--   0 runner    (1001) docker     (123)      553 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-right.750bd27b.svg
--rw-r--r--   0 runner    (1001) docker     (123)      407 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-up.7fa2607f.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1063 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/calendar-alt-solid.95c20e20.svg
--rw-r--r--   0 runner    (1001) docker     (123)      255 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/check_circle.90deb06e.svg
--rw-r--r--   0 runner    (1001) docker     (123)      550 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/checkbox-check-print.fdb58020.svg
--rw-r--r--   0 runner    (1001) docker     (123)      332 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/checkmark-green.142e6c1d.svg
--rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/chevron.f15c792a.svg
--rw-r--r--   0 runner    (1001) docker     (123)      661 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close--primary-darker.05ee67ed.svg
--rw-r--r--   0 runner    (1001) docker     (123)      661 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close--primary.c716dc4c.svg
--rw-r--r--   0 runner    (1001) docker     (123)      251 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close-alt.659d1890.svg
--rw-r--r--   0 runner    (1001) docker     (123)      178 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close-alt.8e9b0025.svg
--rw-r--r--   0 runner    (1001) docker     (123)      495 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close-gray-60.7e82cc30.svg
--rw-r--r--   0 runner    (1001) docker     (123)      626 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close.fe903f4b.svg
--rw-r--r--   0 runner    (1001) docker     (123)      600 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/correct8.1c696dec.svg
--rw-r--r--   0 runner    (1001) docker     (123)      615 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/correct9.1730d813.svg
--rw-r--r--   0 runner    (1001) docker     (123)      367 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/download.381b359a.svg
--rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/error-white.6252fbdb.svg
--rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/error.62d23dd4.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1094 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/error.e73ca64b.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link-alt-hover.74ba81d1.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1171 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link-alt.4b6aa08a.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link-hover.73f16cba.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1167 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link.18ea418e.svg
--rw-r--r--   0 runner    (1001) docker     (123)      415 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/facebook25.754f3a1c.svg
--rw-r--r--   0 runner    (1001) docker     (123)      658 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-excel.f208070c.svg
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-pdf.080ccfc5.svg
--rw-r--r--   0 runner    (1001) docker     (123)      574 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-video.15c2687c.svg
--rw-r--r--   0 runner    (1001) docker     (123)      760 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-word.2fc990ab.svg
--rw-r--r--   0 runner    (1001) docker     (123)      283 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file.eb89414b.svg
--rw-r--r--   0 runner    (1001) docker     (123)   689079 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/hero.544cee01.png
--rw-r--r--   0 runner    (1001) docker     (123)      276 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/image.45732aef.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1890 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/info.157ac1b1.svg
--rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/info.e24db876.svg
--rw-r--r--   0 runner    (1001) docker     (123)      428 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/information-new-hover.2d7be265.svg
--rw-r--r--   0 runner    (1001) docker     (123)      264 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/information-new.3ff7655b.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1298 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/information.61116626.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1713 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/loader.c04c3ed0.svg
--rw-r--r--   0 runner    (1001) docker     (123)      180 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/next.872082d4.svg
--rw-r--r--   0 runner    (1001) docker     (123)      988 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/pdf.f6d71f14.svg
--rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/remove.d788b81e.svg
--rw-r--r--   0 runner    (1001) docker     (123)    32160 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.287fb5bc.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    19884 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.4f691391.woff
--rw-r--r--   0 runner    (1001) docker     (123)    16380 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.db95b37e.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    17340 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.18357dda.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    21052 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.8debb2d5.woff
--rw-r--r--   0 runner    (1001) docker     (123)    32596 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.c24ee49d.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    31092 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.0017dad2.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    15956 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.4bc0bd04.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    19564 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.f61e5a8d.woff
--rw-r--r--   0 runner    (1001) docker     (123)    32564 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.27139953.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    17336 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.5eca10b5.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    21132 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.7324e30e.woff
--rw-r--r--   0 runner    (1001) docker     (123)    17312 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.55befc28.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    21096 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.5711b84f.woff
--rw-r--r--   0 runner    (1001) docker     (123)    32336 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.e3c56211.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    19576 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.1db1469b.woff
--rw-r--r--   0 runner    (1001) docker     (123)    31052 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.c03588a7.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    16028 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.e92cc0fb.woff2
--rw-r--r--   0 runner    (1001) docker     (123)     1484 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/rss25.13c4042b.svg
--rw-r--r--   0 runner    (1001) docker     (123)      387 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/search--white.cebf50fe.svg
--rw-r--r--   0 runner    (1001) docker     (123)    26040 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.738b5fd5.woff
--rw-r--r--   0 runner    (1001) docker     (123)    54340 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.ab04959e.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    20368 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.f12f6a2f.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    38760 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.00a1cd13.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    20164 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.60573f53.woff
--rw-r--r--   0 runner    (1001) docker     (123)    16416 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.dae8945d.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    20204 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.12c96d9d.woff
--rw-r--r--   0 runner    (1001) docker     (123)    16372 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.8740838d.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    38848 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.bf26dc0f.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    20412 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.4572c51e.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    25956 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.9cf8ece9.woff
--rw-r--r--   0 runner    (1001) docker     (123)    54504 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.fb881861.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    39144 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.03f9a24f.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    20256 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.3fa6ebb8.woff
--rw-r--r--   0 runner    (1001) docker     (123)    16316 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.ffb6369e.woff2
--rw-r--r--   0 runner    (1001) docker     (123)    26140 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.34197df8.woff
--rw-r--r--   0 runner    (1001) docker     (123)    54432 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.998d95f8.ttf
--rw-r--r--   0 runner    (1001) docker     (123)    20540 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.d67b548b.woff2
--rw-r--r--   0 runner    (1001) docker     (123)      205 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/star-filled.b51af7f7.svg
--rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/star.85ebfc24.svg
--rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/success-fill.8a5df9fd.svg
--rw-r--r--   0 runner    (1001) docker     (123)      515 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/success.7144d784.svg
--rw-r--r--   0 runner    (1001) docker     (123)     1126 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/twitter16.60eb977c.svg
--rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/warning.2e405b2b.svg
--rw-r--r--   0 runner    (1001) docker     (123)      188 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/warning.62d335b7.svg
--rw-r--r--   0 runner    (1001) docker     (123)     2688 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/youtube15.9d356b3b.svg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.232062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/css/
--rw-r--r--   0 runner    (1001) docker     (123)   434115 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/css/2.chunk.css
--rw-r--r--   0 runner    (1001) docker     (123)     7043 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/css/main.chunk.css
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.232062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/js/
--rw-r--r--   0 runner    (1001) docker     (123)   482374 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/js/2.chunk.js
--rw-r--r--   0 runner    (1001) docker     (123)    82372 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/js/main.chunk.js
--rw-r--r--   0 runner    (1001) docker     (123)     1584 2023-06-05 18:55:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/js/runtime-main.js
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/
--rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/base.html
--rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/new-metadata.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/organization/
--rw-r--r--   0 runner    (1001) docker     (123)      281 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/organization/read.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/package/
--rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/package/read_base.html
--rw-r--r--   0 runner    (1001) docker     (123)     2884 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/package/search.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/snippets/
--rw-r--r--   0 runner    (1001) docker     (123)      116 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/snippets/add_dataset.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2936 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/tests/test_plugin.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     9876 2023-06-05 18:55:07.000000 ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12632 2023-06-05 18:55:07.000000 ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-05 18:55:07.000000 ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      178 2023-06-05 18:55:07.000000 ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-05 18:55:07.000000 ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/namespace_packages.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-05 18:55:07.000000 ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      765 2023-06-05 18:53:05.000000 ckanext-dcat_usmetadata-0.4.1/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-05 18:55:07.236062 ckanext-dcat_usmetadata-0.4.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     3741 2023-06-05 18:55:06.000000 ckanext-dcat_usmetadata-0.4.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/
+-rw-r--r--   0 runner    (1001) docker     (123)    34499 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      202 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     9876 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     9359 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.886515 ckanext-dcat_usmetadata-0.4.2/ckanext/
+-rw-r--r--   0 runner    (1001) docker     (123)      219 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.886515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2371 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/blueprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2247 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1482 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/db_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.886515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/fanstatic/
+-rw-r--r--   0 runner    (1001) docker     (123)      127 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/fanstatic/custom.css
+-rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/fanstatic/webassets.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1158 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/plugin.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.882514 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.882514 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.918515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/
+-rw-r--r--   0 runner    (1001) docker     (123)    25896 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.21c58d74.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    23344 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.9efe74f3.eot
+-rw-r--r--   0 runner    (1001) docker     (123)    15644 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.b786d169.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    11496 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.fc1844c7.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    25880 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.18853b8c.eot
+-rw-r--r--   0 runner    (1001) docker     (123)    39420 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.58093e86.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    14296 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.75fb25c1.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    20216 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.f09ccd61.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    33984 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.0078d318.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    24320 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.12b71a42.eot
+-rw-r--r--   0 runner    (1001) docker     (123)    22436 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.22c8272f.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    90628 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.c99f7ae5.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    21308 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.115f5a1d.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    47228 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.46eab112.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    26892 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.704b3917.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    19568 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.2750a1e9.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    24464 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.69debb55.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    40472 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.9bce1501.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    19252 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.2412c72a.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    39480 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.3ee014ee.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    24152 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.b85b8ae5.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    21260 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.4f0fb504.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    26988 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.ddae281a.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    49164 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.e6dc7e59.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    18976 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.08acae9c.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    23808 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.af8e7e14.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    39456 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.efbd9a2b.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    27512 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.73c28f4e.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    49484 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.efc70b44.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    21692 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.fa9b615a.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    11584 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.3c4dc405.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    15440 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.6a13b444.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    23602 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.8bb31d27.eot
+-rw-r--r--   0 runner    (1001) docker     (123)    23424 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.bf0b1c03.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    13048 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.318b4f41.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    25792 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.346b43cf.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    25978 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.9487423d.eot
+-rw-r--r--   0 runner    (1001) docker     (123)    17204 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.c0de58fc.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    22902 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.33ec9bca.eot
+-rw-r--r--   0 runner    (1001) docker     (123)    15284 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.467063b1.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    22712 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.cb95bc69.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    11472 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.e3b01381.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    23032 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.80744a04.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    15364 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.8e80acc0.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    11536 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.aebd17d5.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    23226 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.d543421f.eot
+-rw-r--r--   0 runner    (1001) docker     (123)      173 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/add.0e3e08bc.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      552 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down-primary.51295a10.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      544 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down.8e2c6296.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      542 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-right.0f46e09b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      551 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-up-white.e60b3e19.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      625 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-double-left-solid.a1c42657.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      629 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-double-right-solid.9addc335.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      422 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-left-solid.247b735a.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-right-solid.fe82c509.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      558 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-both.0bfe2193.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-both.50893060.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      566 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-down-gray-60.9b52f832.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      551 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-down.6c056294.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-down.cb9919ed.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-left.ffd0d3ac.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      553 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-right.750bd27b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      407 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-up.7fa2607f.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1063 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/calendar-alt-solid.95c20e20.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      255 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/check_circle.90deb06e.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      550 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/checkbox-check-print.fdb58020.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      332 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/checkmark-green.142e6c1d.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/chevron.f15c792a.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      661 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close--primary-darker.05ee67ed.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      661 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close--primary.c716dc4c.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      251 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close-alt.659d1890.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      178 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close-alt.8e9b0025.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      495 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close-gray-60.7e82cc30.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      626 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close.fe903f4b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      600 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/correct8.1c696dec.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      615 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/correct9.1730d813.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      367 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/download.381b359a.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/error-white.6252fbdb.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/error.62d23dd4.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1094 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/error.e73ca64b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link-alt-hover.74ba81d1.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1171 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link-alt.4b6aa08a.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1173 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link-hover.73f16cba.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1167 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link.18ea418e.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      415 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/facebook25.754f3a1c.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      658 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-excel.f208070c.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-pdf.080ccfc5.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      574 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-video.15c2687c.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      760 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-word.2fc990ab.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      283 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file.eb89414b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)   689079 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/hero.544cee01.png
+-rw-r--r--   0 runner    (1001) docker     (123)      276 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/image.45732aef.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1890 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/info.157ac1b1.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/info.e24db876.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      428 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/information-new-hover.2d7be265.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      264 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/information-new.3ff7655b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1298 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/information.61116626.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1713 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/loader.c04c3ed0.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      180 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/next.872082d4.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      988 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/pdf.f6d71f14.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/remove.d788b81e.svg
+-rw-r--r--   0 runner    (1001) docker     (123)    32160 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.287fb5bc.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    19884 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.4f691391.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    16380 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.db95b37e.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    17340 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.18357dda.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    21052 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.8debb2d5.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    32596 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.c24ee49d.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    31092 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.0017dad2.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    15956 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.4bc0bd04.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    19564 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.f61e5a8d.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    32564 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.27139953.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    17336 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.5eca10b5.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    21132 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.7324e30e.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    17312 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.55befc28.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    21096 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.5711b84f.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    32336 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.e3c56211.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    19576 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.1db1469b.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    31052 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.c03588a7.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    16028 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.e92cc0fb.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)     1484 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/rss25.13c4042b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      387 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/search--white.cebf50fe.svg
+-rw-r--r--   0 runner    (1001) docker     (123)    26040 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.738b5fd5.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    54340 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.ab04959e.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    20368 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.f12f6a2f.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    38760 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.00a1cd13.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    20164 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.60573f53.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    16416 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.dae8945d.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    20204 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.12c96d9d.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    16372 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.8740838d.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    38848 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.bf26dc0f.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    20412 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.4572c51e.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    25956 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.9cf8ece9.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    54504 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.fb881861.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    39144 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.03f9a24f.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    20256 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.3fa6ebb8.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    16316 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.ffb6369e.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)    26140 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.34197df8.woff
+-rw-r--r--   0 runner    (1001) docker     (123)    54432 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.998d95f8.ttf
+-rw-r--r--   0 runner    (1001) docker     (123)    20540 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.d67b548b.woff2
+-rw-r--r--   0 runner    (1001) docker     (123)      205 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/star-filled.b51af7f7.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/star.85ebfc24.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/success-fill.8a5df9fd.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      515 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/success.7144d784.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     1126 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/twitter16.60eb977c.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/warning.2e405b2b.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      188 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/warning.62d335b7.svg
+-rw-r--r--   0 runner    (1001) docker     (123)     2688 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/youtube15.9d356b3b.svg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.918515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/css/
+-rw-r--r--   0 runner    (1001) docker     (123)   434115 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/css/2.chunk.css
+-rw-r--r--   0 runner    (1001) docker     (123)     7043 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/css/main.chunk.css
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/js/
+-rw-r--r--   0 runner    (1001) docker     (123)   482374 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/js/2.chunk.js
+-rw-r--r--   0 runner    (1001) docker     (123)    82276 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/js/main.chunk.js
+-rw-r--r--   0 runner    (1001) docker     (123)     1584 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/js/runtime-main.js
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)      104 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/base.html
+-rw-r--r--   0 runner    (1001) docker     (123)      473 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/new-metadata.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/organization/
+-rw-r--r--   0 runner    (1001) docker     (123)      281 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/organization/read.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/package/
+-rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/package/read_base.html
+-rw-r--r--   0 runner    (1001) docker     (123)     2884 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/package/search.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/snippets/
+-rw-r--r--   0 runner    (1001) docker     (123)      116 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/snippets/add_dataset.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2936 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/tests/test_plugin.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     9876 2023-06-28 14:57:03.000000 ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12632 2023-06-28 14:57:03.000000 ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:57:03.000000 ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      178 2023-06-28 14:57:03.000000 ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 14:57:03.000000 ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/namespace_packages.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 14:57:03.000000 ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      765 2023-06-28 14:55:01.000000 ckanext-dcat_usmetadata-0.4.2/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-28 14:57:03.922515 ckanext-dcat_usmetadata-0.4.2/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     3741 2023-06-28 14:57:02.000000 ckanext-dcat_usmetadata-0.4.2/setup.py
```

### Comparing `ckanext-dcat_usmetadata-0.4.1/LICENSE` & `ckanext-dcat_usmetadata-0.4.2/LICENSE`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/PKG-INFO` & `ckanext-dcat_usmetadata-0.4.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ckanext-dcat_usmetadata
-Version: 0.4.1
+Version: 0.4.2
 Summary: DCAT USMetadata Form App for CKAN
 Home-page: https://github.com/GSA/ckanext-dcat_usmetadata
 Author: Data.gov
 Author-email: datagovhelp@gsa.gov
 License: AGPL
 Keywords: CKAN
 Platform: UNKNOWN
```

### Comparing `ckanext-dcat_usmetadata-0.4.1/README.md` & `ckanext-dcat_usmetadata-0.4.2/README.md`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/blueprint.py` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/blueprint.py`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/cli.py` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/cli.py`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/db_utils.py` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/db_utils.py`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/plugin.py` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/plugin.py`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.21c58d74.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.21c58d74.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.9efe74f3.eot` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.9efe74f3.eot`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.b786d169.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.b786d169.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.fc1844c7.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Bold.fc1844c7.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.18853b8c.eot` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.18853b8c.eot`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.58093e86.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.58093e86.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.75fb25c1.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.75fb25c1.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.f09ccd61.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Italic.f09ccd61.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.0078d318.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.0078d318.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.12b71a42.eot` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.12b71a42.eot`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.22c8272f.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.22c8272f.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.c99f7ae5.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Bitter-Regular.c99f7ae5.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.115f5a1d.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.115f5a1d.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.46eab112.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.46eab112.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.704b3917.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Bold.704b3917.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.2750a1e9.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.2750a1e9.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.69debb55.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.69debb55.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.9bce1501.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-BoldItalic.9bce1501.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.2412c72a.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.2412c72a.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.3ee014ee.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.3ee014ee.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.b85b8ae5.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Italic.b85b8ae5.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.4f0fb504.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.4f0fb504.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.ddae281a.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.ddae281a.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.e6dc7e59.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Light.e6dc7e59.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.08acae9c.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.08acae9c.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.af8e7e14.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.af8e7e14.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.efbd9a2b.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-LightItalic.efbd9a2b.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.73c28f4e.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.73c28f4e.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.efc70b44.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.efc70b44.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.fa9b615a.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/Latin-Merriweather-Regular.fa9b615a.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.3c4dc405.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.3c4dc405.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.6a13b444.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.6a13b444.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.8bb31d27.eot` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.8bb31d27.eot`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.bf0b1c03.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Bold-webfont.bf0b1c03.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.318b4f41.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.318b4f41.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.346b43cf.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.346b43cf.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.9487423d.eot` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.9487423d.eot`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.c0de58fc.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Italic-webfont.c0de58fc.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.33ec9bca.eot` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.33ec9bca.eot`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.467063b1.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.467063b1.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.cb95bc69.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.cb95bc69.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.e3b01381.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Regular-webfont.e3b01381.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.80744a04.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.80744a04.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.8e80acc0.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.8e80acc0.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.aebd17d5.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.aebd17d5.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.d543421f.eot` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/OpenSans-Semibold-webfont.d543421f.eot`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down-primary.51295a10.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down-primary.51295a10.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down.8e2c6296.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-down.8e2c6296.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-right.0f46e09b.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-right.0f46e09b.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-up-white.e60b3e19.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-arrow-up-white.e60b3e19.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-double-left-solid.a1c42657.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-double-left-solid.a1c42657.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/angle-double-right-solid.9addc335.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/angle-double-right-solid.9addc335.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-both.0bfe2193.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-both.0bfe2193.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-down-gray-60.9b52f832.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-down-gray-60.9b52f832.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-down.6c056294.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-down.6c056294.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-left.ffd0d3ac.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-left.ffd0d3ac.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/arrow-right.750bd27b.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/arrow-right.750bd27b.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/calendar-alt-solid.95c20e20.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/calendar-alt-solid.95c20e20.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/checkbox-check-print.fdb58020.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/checkbox-check-print.fdb58020.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/chevron.f15c792a.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/chevron.f15c792a.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close--primary-darker.05ee67ed.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close--primary-darker.05ee67ed.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close--primary.c716dc4c.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close--primary.c716dc4c.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/close.fe903f4b.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/close.fe903f4b.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/correct8.1c696dec.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/correct8.1c696dec.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/correct9.1730d813.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/correct9.1730d813.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/error.e73ca64b.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/error.e73ca64b.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link-alt-hover.74ba81d1.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link-alt-hover.74ba81d1.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link-alt.4b6aa08a.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link-alt.4b6aa08a.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link-hover.73f16cba.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link-hover.73f16cba.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/external-link.18ea418e.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/external-link.18ea418e.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-excel.f208070c.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-excel.f208070c.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-pdf.080ccfc5.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-pdf.080ccfc5.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-video.15c2687c.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-video.15c2687c.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/file-word.2fc990ab.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/file-word.2fc990ab.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/hero.544cee01.png` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/hero.544cee01.png`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/info.157ac1b1.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/info.157ac1b1.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/information.61116626.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/information.61116626.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/loader.c04c3ed0.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/loader.c04c3ed0.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/pdf.f6d71f14.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/pdf.f6d71f14.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.287fb5bc.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.287fb5bc.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.4f691391.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.4f691391.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.db95b37e.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300.db95b37e.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.18357dda.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.18357dda.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.8debb2d5.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.8debb2d5.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.c24ee49d.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-300italic.c24ee49d.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.0017dad2.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.0017dad2.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.4bc0bd04.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.4bc0bd04.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.f61e5a8d.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700.f61e5a8d.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.27139953.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.27139953.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.5eca10b5.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.5eca10b5.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.7324e30e.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-700italic.7324e30e.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.55befc28.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.55befc28.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.5711b84f.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.5711b84f.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.e3c56211.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-italic.e3c56211.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.1db1469b.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.1db1469b.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.c03588a7.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.c03588a7.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.e92cc0fb.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/roboto-mono-v5-latin-regular.e92cc0fb.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/rss25.13c4042b.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/rss25.13c4042b.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.738b5fd5.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.738b5fd5.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.ab04959e.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.ab04959e.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.f12f6a2f.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bold-webfont.f12f6a2f.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.00a1cd13.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.00a1cd13.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.60573f53.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.60573f53.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.dae8945d.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-bolditalic-webfont.dae8945d.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.12c96d9d.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.12c96d9d.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.8740838d.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.8740838d.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.bf26dc0f.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-italic-webfont.bf26dc0f.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.4572c51e.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.4572c51e.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.9cf8ece9.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.9cf8ece9.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.fb881861.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-light-webfont.fb881861.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.03f9a24f.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.03f9a24f.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.3fa6ebb8.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.3fa6ebb8.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.ffb6369e.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-lightitalic-webfont.ffb6369e.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.34197df8.woff` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.34197df8.woff`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.998d95f8.ttf` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.998d95f8.ttf`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.d67b548b.woff2` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/sourcesanspro-regular-webfont.d67b548b.woff2`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/success-fill.8a5df9fd.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/success-fill.8a5df9fd.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/success.7144d784.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/success.7144d784.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/twitter16.60eb977c.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/twitter16.60eb977c.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/warning.2e405b2b.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/warning.2e405b2b.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/assets/media/youtube15.9d356b3b.svg` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/assets/media/youtube15.9d356b3b.svg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/css/2.chunk.css` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/css/2.chunk.css`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/css/main.chunk.css` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/css/main.chunk.css`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/js/2.chunk.js` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/js/2.chunk.js`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/js/main.chunk.js` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/js/main.chunk.js`

 * *Files 2% similar despite different names*

#### js-beautify {}

```diff
@@ -176,17 +176,17 @@
                 _ = t.n(E),
                 x = t(225),
                 S = t(226),
                 w = t(227),
                 N = "url",
                 O = "upload",
                 D = "linkToApi",
-                P = "accessUrl",
-                k = ["publisher", "publisher_1", "publisher_2", "publisher_3", "publisher_4", "publisher_5"],
-                T = function(e) {
+                k = "accessUrl",
+                T = ["publisher", "publisher_1", "publisher_2", "publisher_3", "publisher_4", "publisher_5"],
+                P = function(e) {
                     return e.publisher_5 || e.publisher_4 || e.publisher_3 || e.publisher_2 || e.publisher_1 || e.publisher
                 },
                 I = function(e) {
                     return JSON.parse(JSON.stringify(e))
                 },
                 C = function(e) {
                     var a = e,
@@ -196,35 +196,35 @@
                             r = l[0],
                             n = l[1],
                             i = l[2];
                         a = "".concat(i, "-").concat(r, "-").concat(n)
                     }
                     return a
                 },
-                A = {
+                F = {
                     accrual_periodicity: "accrualPeriodicity",
                     data_dictionary_type: "describedByType"
                 },
-                F = function(e) {
+                R = function(e) {
                     var a = I(e);
                     return a.extras.forEach((function(e) {
-                        var t = A[e.key] || e.key;
+                        var t = F[e.key] || e.key;
                         a[t] = e.value
                     })), a
                 },
-                R = function(e) {
+                j = function(e) {
                     return encodeURIComponent(JSON.stringify(e))
                 },
-                j = function(e) {
+                A = function(e) {
                     var a = I(e);
-                    return a.urlType && (a.urlType !== D && a.urlType !== P || (a.resource_type = "accessurl", a.url_type = "url"), a.urlType === N && (a.url_type = "url")), delete a.urlType, a
+                    return a.urlType && (a.urlType !== D && a.urlType !== k || (a.resource_type = "accessurl", a.url_type = "url"), a.urlType === N && (a.url_type = "url")), delete a.urlType, a
                 },
                 M = function(e) {
                     var a = I(e);
-                    return a.urlType = e.url_type, "accessurl" === a.resource_type && (a.urlType = P, "API" === a.format && (a.urlType = D)), a
+                    return a.urlType = e.url_type, "accessurl" === a.resource_type && (a.urlType = k, "API" === a.format && (a.urlType = D)), a
                 },
                 L = function(e) {
                     var a = I(e);
                     if (a.modified = new Date, a.extras = a.extras || [], e.title) {
                         var t = a.extras.findIndex((function(e) {
                             return "title" === e.key
                         }));
@@ -329,27 +329,27 @@
                     })), N > -1 && (a.extras[N].value = a.is_parent)) : "No" === e.isParent ? (a.is_parent = "false", N > -1 && (a.extras[N].value = a.is_parent), e.parentDataset ? a.parent_dataset = e.parentDataset : (delete a.parent_dataset, a.extras = a.extras.filter((function(e) {
                         return "parent_dataset" !== e.key
                     })))) : (delete a.is_parent, delete a.parent_dataset);
                     var O = a.selectedPublisher;
                     if (O) {
                         a.extras && (a.extras = a.extras.filter((function(e) {
                             var t = e.key;
-                            return !k.includes(t) || (delete a[t], !1)
+                            return !T.includes(t) || (delete a[t], !1)
                         })));
-                        var D, P = Object(y.a)(k);
+                        var D, k = Object(y.a)(T);
                         try {
-                            for (P.s(); !(D = P.n()).done;) {
-                                var T = D.value,
-                                    A = O[T];
-                                A && (a[T] = A)
+                            for (k.s(); !(D = k.n()).done;) {
+                                var P = D.value,
+                                    F = O[P];
+                                F && (a[P] = F)
                             }
-                        } catch (F) {
-                            P.e(F)
+                        } catch (R) {
+                            k.e(R)
                         } finally {
-                            P.f()
+                            k.f()
                         }
                     }
                     return a
                 },
                 U = function(e) {
                     var a = I(e);
                     if (a.resources = (a.resources || []).map((function(e) {
@@ -382,73 +382,76 @@
                     "true" === e.is_parent ? a.isParent = "Yes" : a.isParent = "No", e.parent_dataset && (a.parentDataset = e.parent_dataset), e.accrualPeriodicity && (w.find((function(a) {
                         return a.value === e.accrualPeriodicity
                     })) ? a.accrualPeriodicity = e.accrualPeriodicity : -1 !== e.accrualPeriodicity.indexOf("R/P") && (a.accrualPeriodicity = "other", a.accrualPeriodicityOther = e.accrualPeriodicity));
                     var i = {};
                     return (e.extras || []).map((function(e) {
                         var a = e.key,
                             t = e.value;
-                        k.includes(a) && (i[a] = t)
-                    })), a.publisher = T(i), a
+                        T.includes(a) && (i[a] = t)
+                    })), a.publisher = P(i), a
                 },
                 G = function(e) {
                     for (var a = I(e), t = [], l = ["publisher", "contact_name", "contact_email", "unique_id", "modified", "public_access_level", "bureau_code", "program_code", "release_date", "accrual_periodicity", "language", "data_quality", "publishing_status", "is_parent", "parent_dataset", "category", "related_documents", "conforms_to", "homepage_url", "system_of_records", "primary_it_investment_uii", "publisher_1", "publisher_2", "publisher_3", "publisher_4", "publisher_5"], r = 0; r < l.length; r += 1) l[r] in e && (t.push({
                         key: l[r],
                         value: e[l[r]]
                     }), delete a[l[r]]);
                     for (var n = {}, i = 0; i < t.length; i += 1) n[t[i].key] = t[i].value;
                     return a.common_core = n, a.extras = t, a
                 },
-                B = {
+                B = function(e) {
+                    var a = arguments.length > 1 && void 0 !== arguments[1] && arguments[1],
+                        t = window.document.querySelector('meta[name="_csrf_token"]'),
+                        l = {
+                            "X-CKAN-API-Key": e,
+                            "X-CSRFToken": t.content
+                        },
+                        r = {
+                            "Content-Type": "application/x-www-form-urlencoded"
+                        };
+                    return a ? Object.assign(l, r) : l
+                },
+                q = {
                     createDataset: function(e, a, t) {
                         var l = L(e);
                         return l.name = e.url ? e.url.split("/").pop() : v()(e.title, {
                             lower: !0,
                             remove: /[*+~.()'"!:@]/g
-                        }), l.notes = l.notes || "", delete l.url, l.bureau_code = "015:11", l.program_code = "015:001", _.a.post("".concat(a, "package_create"), R(G(l)), {
-                            headers: {
-                                "X-CKAN-API-Key": t
-                            }
+                        }), l.notes = l.notes || "", delete l.url, l.bureau_code = "015:11", l.program_code = "015:001", _.a.post("".concat(a, "package_create"), j(G(l)), {
+                            headers: B(t)
                         }).then((function(e) {
                             var a = e.data.result;
-                            return U(F(a))
+                            return U(R(a))
                         }))
                     },
                     updateDataset: function(e, a, t, l) {
                         var r = L(a);
-                        return r.id = e, r.name = a.url ? a.url.split("/").pop() : r.name, delete r.url, r.bureau_code = "015:11", r.program_code = "015:001", _.a.post("".concat(t, "package_update"), R(G(r)), {
-                            headers: {
-                                "X-CKAN-API-Key": l
-                            }
+                        return r.id = e, r.name = a.url ? a.url.split("/").pop() : r.name, delete r.url, r.bureau_code = "015:11", r.program_code = "015:001", _.a.post("".concat(t, "package_update"), j(G(r)), {
+                            headers: B(l)
                         }).then((function(e) {
                             var a = e.data.result;
-                            return U(F(a))
+                            return U(R(a))
                         }))
                     },
                     patchDataset: function(e, a, t, l) {
                         var r = Object.assign(a, {
                             id: e
                         });
-                        return _.a.post("".concat(t, "package_patch"), R(r), {
-                            headers: {
-                                "X-CKAN-API-Key": l,
-                                "Content-Type": "application/x-www-form-urlencoded"
-                            }
+                        return _.a.post("".concat(t, "package_patch"), j(r), {
+                            headers: B(l, !0)
                         })
                     },
                     fetchDataset: function() {
                         var e = Object(o.a)(c.a.mark((function e(a, t, l) {
                             return c.a.wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
                                         return e.abrupt("return", _.a.get("".concat(t, "package_show?id=").concat(a), {
-                                            headers: {
-                                                "X-CKAN-API-Key": l
-                                            }
+                                            headers: B(l)
                                         }).then((function(e) {
-                                            var a = U(F(e.data.result));
+                                            var a = U(R(e.data.result));
                                             return a.description = a.notes, a
                                         })));
                                     case 1:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e)
@@ -460,17 +463,15 @@
                     fetchTags: function() {
                         var e = Object(o.a)(c.a.mark((function e(a, t, l) {
                             var r, n;
                             return c.a.wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
                                         return e.prev = 0, r = "".concat(t, "tag_list?query=").concat(a), e.next = 4, _.a.get(r, {
-                                            headers: {
-                                                "X-CKAN-API-Key": l
-                                            }
+                                            headers: B(l)
                                         });
                                     case 4:
                                         return n = e.sent, e.abrupt("return", n.data.result.map((function(e, a) {
                                             return {
                                                 id: a,
                                                 name: e
                                             }
@@ -494,17 +495,15 @@
                             var l, r, n;
                             return c.a.wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
                                         return e.prev = 0, l = "".concat(a, "organization_list_for_user"), r = {
                                             permission: "create_dataset"
                                         }, e.next = 5, _.a.post(l, r, {
-                                            headers: {
-                                                "X-CKAN-API-Key": t
-                                            }
+                                            headers: B(t)
                                         });
                                     case 5:
                                         return n = e.sent, e.abrupt("return", n.data.result);
                                     case 9:
                                         return e.prev = 9, e.t0 = e.catch(0), e.abrupt("return", Promise.reject(e.t0));
                                     case 12:
                                     case "end":
@@ -521,17 +520,15 @@
                     fetchParentDatasets: function() {
                         var e = Object(o.a)(c.a.mark((function e(a, t, l) {
                             var r, n;
                             return c.a.wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
                                         return e.prev = 0, r = "".concat(t, "parent_dataset_options"), e.next = 4, _.a.post(r, {}, {
-                                            headers: {
-                                                "X-CKAN-API-Key": l
-                                            }
+                                            headers: B(l)
                                         });
                                     case 4:
                                         return n = e.sent, e.abrupt("return", Object.keys(n.data.result).map((function(e) {
                                             return {
                                                 id: e,
                                                 name: n.data.result[e]
                                             }
@@ -548,53 +545,44 @@
                         })));
                         return function(a, t, l) {
                             return e.apply(this, arguments)
                         }
                     }(),
                     createResource: function(e, a, t, l) {
                         var r;
-                        return a.upload ? ((r = new FormData).append("package_id", e), Object.keys(j(a)).forEach((function(e) {
+                        return a.upload ? ((r = new FormData).append("package_id", e), Object.keys(A(a)).forEach((function(e) {
                             r.append(e, a[e])
-                        }))) : ((r = j(a)).package_id = e, r = R(r)), _.a.post("".concat(t, "resource_create"), r, {
-                            headers: {
-                                "X-CKAN-API-Key": l,
-                                "Content-Type": "application/x-www-form-urlencoded"
-                            }
+                        }))) : ((r = A(a)).package_id = e, r = j(r)), _.a.post("".concat(t, "resource_create"), r, {
+                            headers: B(l, !0)
                         }).then((function(e) {
                             return e.data && (e.data.result = M(e.data.result)), e
                         }))
                     },
                     updateResource: function(e, a, t) {
                         var l;
-                        return e.upload ? (l = new FormData, Object.keys(j(e)).forEach((function(a) {
+                        return e.upload ? (l = new FormData, Object.keys(A(e)).forEach((function(a) {
                             null !== e[a] && l.append(a, e[a])
-                        }))) : l = R(j(e)), _.a.post("".concat(a, "resource_update"), l, {
-                            headers: {
-                                "X-CKAN-API-Key": t,
-                                "Content-Type": "application/x-www-form-urlencoded"
-                            }
+                        }))) : l = j(A(e)), _.a.post("".concat(a, "resource_update"), l, {
+                            headers: B(t, !0)
                         }).then((function(e) {
                             return e.data && (e.data.result = M(e.data.result)), e
                         }))
                     },
                     deleteResource: function(e, a, t) {
-                        var l = R({
+                        var l = j({
                             id: e
                         });
                         return _.a.post("".concat(a, "resource_delete"), l, {
-                            headers: {
-                                "X-CKAN-API-Key": t,
-                                "Content-Type": "application/x-www-form-urlencoded"
-                            }
+                            headers: B(t, !0)
                         })
                     },
                     helpers: {
                         serializeSupplementalValues: L,
                         deserializeSupplementalValues: U,
-                        deserializeExtras: F,
+                        deserializeExtras: R,
                         clone: I
                     },
                     fetchPublishers: function() {
                         var e = Object(o.a)(c.a.mark((function e(a, t, l) {
                             var r, n, i, s;
                             return c.a.wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
@@ -602,17 +590,15 @@
                                         if (a) {
                                             e.next = 2;
                                             break
                                         }
                                         return e.abrupt("return", []);
                                     case 2:
                                         return r = "".concat(t, "organization_show?id=").concat(a), e.next = 5, _.a.get(r, {
-                                            headers: {
-                                                "X-CKAN-API-Key": l
-                                            }
+                                            headers: B(l)
                                         });
                                     case 5:
                                         if (n = e.sent, i = n.data.result.extras.find((function(e) {
                                                 return "publisher" === e.key
                                             }))) {
                                             e.next = 9;
                                             break
@@ -626,15 +612,15 @@
                                                 publisher_2: e[3] || null,
                                                 publisher_3: e[4] || null,
                                                 publisher_4: e[5] || null,
                                                 publisher_5: e[6] || null
                                             }
                                         })), e.abrupt("return", s.map((function(e, a) {
                                             var t = a,
-                                                l = T(e);
+                                                l = P(e);
                                             return Object(u.a)({
                                                 id: t,
                                                 name: l
                                             }, e)
                                         })).sort());
                                     case 11:
                                     case "end":
@@ -643,17 +629,17 @@
                             }), e)
                         })));
                         return function(a, t, l) {
                             return e.apply(this, arguments)
                         }
                     }()
                 },
-                q = t(151),
-                K = t.n(q),
-                z = (t(480), function(e) {
+                K = t(151),
+                z = t.n(K),
+                V = (t(480), function(e) {
                     var a = e.tags,
                         t = e.name,
                         n = e.helptext,
                         i = e.placeholder,
                         s = e.apiUrl,
                         u = e.apiKey,
                         p = e.errors,
@@ -670,15 +656,15 @@
                         var S = e.value ? [{
                             name: e.value
                         }] : [];
                         return r.a.createElement("div", {
                             className: "react-tags-input grid-col-12 ".concat(p && p[t] && "field-error")
                         }, r.a.createElement("div", {
                             className: "usa-helptext"
-                        }, n), r.a.createElement(K.a, {
+                        }, n), r.a.createElement(z.a, {
                             tags: S,
                             suggestions: h,
                             allowNew: !0,
                             addOnBlur: !0,
                             ref: r.a.createRef(),
                             onAddition: function(e) {
                                 x(e.id)
@@ -717,15 +703,15 @@
                     return r.a.createElement(m.b, {
                         name: t,
                         render: function(e) {
                             return r.a.createElement("div", {
                                 className: "react-tags-input grid-col-12 ".concat(p && p[t] && "field-error")
                             }, p && p[t] && r.a.createElement("span", {
                                 className: "error-msg"
-                            }, "String" === p[t].constructor.name ? p[t] : JSON.stringify(p[t]), r.a.createElement("br", null)), n, r.a.createElement(K.a, {
+                            }, "String" === p[t].constructor.name ? p[t] : JSON.stringify(p[t]), r.a.createElement("br", null)), n, r.a.createElement(z.a, {
                                 tags: a,
                                 suggestions: h,
                                 allowNew: !0,
                                 addOnBlur: !0,
                                 ref: r.a.createRef(),
                                 onAddition: e.push,
                                 onDelete: e.remove,
@@ -755,26 +741,26 @@
                                         return e.apply(this, arguments)
                                     }
                                 }()
                             }))
                         }
                     })
                 }),
-                X = t(253),
-                V = t.n(X),
-                Y = (t(491), function(e) {
+                Y = t(253),
+                J = t.n(Y),
+                X = (t(491), function(e) {
                     return e.name
                 }),
-                J = function(e, a) {
+                W = function(e, a) {
                     var t = a.query,
                         l = e.name,
                         n = l.substring(t.length, l.length);
                     return r.a.createElement("div", null, r.a.createElement("mark", null, t), n)
                 },
-                W = function(e) {
+                Z = function(e) {
                     var a = e.name,
                         t = e.helptext,
                         n = e.inputValue,
                         i = e.value,
                         s = e.placeholder,
                         u = e.apiUrl,
                         p = e.apiKey,
@@ -788,19 +774,19 @@
                         _ = Object(d.a)(E, 2),
                         x = _[0],
                         S = _[1],
                         w = Object(m.e)(a),
                         N = Object(d.a)(w, 3),
                         O = (N[0], N[1], N[2].setValue),
                         D = Object(l.useState)(""),
-                        P = Object(d.a)(D, 2),
-                        k = P[0],
-                        T = P[1];
+                        k = Object(d.a)(D, 2),
+                        T = k[0],
+                        P = k[1];
                     Object(l.useEffect)((function() {
-                        !n || i === n && k ? T(n || "") : (T(n || ""), S({
+                        !n || i === n && T ? P(n || "") : (P(n || ""), S({
                             id: i,
                             name: n
                         }))
                     }), [n]);
                     var I = function() {
                             var e = Object(o.a)(c.a.mark((function e(a) {
                                 var t, l;
@@ -851,25 +837,25 @@
                                 return e.apply(this, arguments)
                             }
                         }();
                     return r.a.createElement("div", {
                         className: "react-tags-input grid-col-12 ".concat(v && v[a] && "field-error")
                     }, r.a.createElement("div", {
                         className: "usa-helptext"
-                    }, t), r.a.createElement(V.a, {
+                    }, t), r.a.createElement(J.a, {
                         suggestions: h,
                         onSuggestionsFetchRequested: C,
                         onSuggestionsClearRequested: function() {
                             y([])
                         },
-                        getSuggestionValue: Y,
-                        renderSuggestion: J,
+                        getSuggestionValue: X,
+                        renderSuggestion: W,
                         onSuggestionSelected: function(e, a) {
                             var t = a.suggestion;
-                            S(t), T(t.name), O(t.id)
+                            S(t), P(t.name), O(t.id)
                         },
                         theme: {
                             container: "react-autosuggest__container",
                             containerOpen: "react-autosuggest__container--open",
                             input: "usa-input",
                             inputOpen: "react-autosuggest__input--open",
                             inputFocused: "react-autosuggest__input--focused",
@@ -881,32 +867,32 @@
                             suggestionHighlighted: "react-autosuggest__suggestion--highlighted",
                             sectionContainer: "react-autosuggest__section-container",
                             sectionContainerFirst: "react-autosuggest__section-container--first",
                             sectionTitle: "react-autosuggest__section-title"
                         },
                         inputProps: {
                             placeholder: s,
-                            value: k,
+                            value: T,
                             onChange: function(e) {
                                 var a = e.target.value;
-                                a || (O(""), S(null)), T(a || "")
+                                a || (O(""), S(null)), P(a || "")
                             },
                             onBlur: function() {
-                                T(x ? x.name : "")
+                                P(x ? x.name : "")
                             }
                         }
                     }))
                 },
-                Z = function(e) {
+                H = function(e) {
                     var a = e.children;
                     return r.a.createElement("span", {
                         className: "usa-helptext"
                     }, a)
                 },
-                H = function(e) {
+                Q = function(e) {
                     var a = e.label,
                         t = e.value,
                         l = e.styleClass,
                         n = e.id,
                         i = e.name;
                     return r.a.createElement("div", {
                         className: "form-group ".concat(l)
@@ -917,37 +903,37 @@
                         name: i,
                         id: n
                     }), r.a.createElement("label", {
                         className: "usa-radio__label",
                         htmlFor: n
                     }, a))
                 };
-            H.defaultProps = {
+            Q.defaultProps = {
                 styleClass: ""
             };
-            var Q = H,
-                $ = function(e) {
+            var $ = Q,
+                ee = function(e) {
                     var a = e.children,
                         t = e.href,
                         l = e.rel,
                         n = e.target,
                         i = ["usa-link"],
                         s = l ? [l] : [];
                     return (/^https?:\/\//.test(t) || "_blank" === n) && (i = i.concat(["usa-link--external"]), s = s.concat(["noopener", "noreferrer"])), r.a.createElement("a", Object.assign({
                         href: t,
                         className: i.join(" "),
                         rel: s.length ? s.join(" ") : void 0
                     }, e), a)
                 };
-            $.defaultValues = {
+            ee.defaultValues = {
                 rel: null
             };
-            var ee = $,
-                ae = t(226),
-                te = function(e) {
+            var ae = ee,
+                te = t(226),
+                le = function(e) {
                     var a = e.values,
                         t = e.errors,
                         n = e.apiUrl,
                         i = e.apiKey,
                         s = e.draftSaved,
                         u = e.setFieldValue,
                         m = e.submitForm,
@@ -957,40 +943,40 @@
                         y = g[0],
                         E = g[1],
                         _ = Object(l.useState)([]),
                         x = Object(d.a)(_, 2),
                         S = x[0],
                         w = x[1];
                     Object(l.useEffect)((function() {
-                        B.fetchOrganizationsForUser(n, i).then((function(e) {
+                        q.fetchOrganizationsForUser(n, i).then((function(e) {
                             var a = new URLSearchParams(window.location.search).get("group");
                             a && u("owner_org", a), 1 === e.length && u("owner_org", e[0].id), E(e)
                         }))
                     }), []);
                     var N = Object(l.useState)(!0),
                         O = Object(d.a)(N, 2),
                         D = O[0],
-                        P = O[1],
-                        k = function(e) {
-                            return r.a.createElement(Z, null, e)
+                        k = O[1],
+                        T = function(e) {
+                            return r.a.createElement(H, null, e)
                         },
-                        T = "".concat(window.location.origin, "/dataset/"),
+                        P = "".concat(window.location.origin, "/dataset/"),
                         I = function(e) {
-                            return "".concat(T).concat(v()(e || "", {
+                            return "".concat(P).concat(v()(e || "", {
                                 lower: !0,
                                 remove: /[*+~.()'"!:@]/g
                             }))
                         },
                         C = function() {
                             var e = Object(o.a)(c.a.mark((function e() {
                                 var t;
                                 return c.a.wrap((function(e) {
                                     for (;;) switch (e.prev = e.next) {
                                         case 0:
-                                            return e.next = 2, B.fetchPublishers(a.owner_org, n, i);
+                                            return e.next = 2, q.fetchPublishers(a.owner_org, n, i);
                                         case 2:
                                             return t = e.sent, w(t), e.abrupt("return", t);
                                         case 5:
                                         case "end":
                                             return e.stop()
                                     }
                                 }), e)
@@ -1004,51 +990,51 @@
                         if (e || 0 === e) {
                             var t = S.find((function(a) {
                                 return a.id === e
                             }));
                             u("selectedPublisher", t)
                         }
                     }), [a.publisher]);
-                    var A = {
-                        title: r.a.createElement(Z, null, "Use", " ", r.a.createElement(ee, {
+                    var F = {
+                        title: r.a.createElement(H, null, "Use", " ", r.a.createElement(ae, {
                             target: "_blank",
                             href: "https://plainlanguage.gov/"
                         }, "everyday language"), " ", "to make the dataset easy to find and understand."),
-                        description: r.a.createElement(Z, null, "Write a description (like an abstract) with enough detail to help a user quickly decide if the asset is of interest. You can use", " ", r.a.createElement(ee, {
+                        description: r.a.createElement(H, null, "Write a description (like an abstract) with enough detail to help a user quickly decide if the asset is of interest. You can use", " ", r.a.createElement(ae, {
                             target: "_blank",
                             href: "https://www.markdownguide.org/basic-syntax/"
                         }, "Markdown Formatting"), " ", "here."),
-                        select: r.a.createElement(Z, null, "Start typing to see list of publishers. If you do not see the Publisher for your dataset listed, please contact", " ", r.a.createElement(ee, {
+                        select: r.a.createElement(H, null, "Start typing to see list of publishers. If you do not see the Publisher for your dataset listed, please contact", " ", r.a.createElement(ae, {
                             target: "_blank",
                             href: "mailto:inventory-help@gsa.gov"
                         }, "inventory-help@gsa.gov"), " ", "for further assistance.")
                     };
                     return r.a.createElement("div", {
                         className: "usa-form-custom"
                     }, r.a.createElement("section", {
                         id: "section-basic-mega-menu",
                         className: "site-component-section"
                     }, r.a.createElement("p", {
                         className: "site-text-intro"
-                    }, "The following fields are required metadata for each dataset in an agency\u2019s inventory (", r.a.createElement(ee, {
+                    }, "The following fields are required metadata for each dataset in an agency\u2019s inventory (", r.a.createElement(ae, {
                         target: "_blank",
                         href: "https://www.congress.gov/115/plaws/publ435/PLAW-115publ435.pdf"
-                    }, "per Section 202 of the OPEN Government Data Act"), "). For more information about the form fields, consult the", " ", r.a.createElement(ee, {
+                    }, "per Section 202 of the OPEN Government Data Act"), "). For more information about the form fields, consult the", " ", r.a.createElement(ae, {
                         target: "_blank",
                         href: "https://resources.data.gov/resources/dcat-us/"
                     }, "DCAT-US Schema"), ".")), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Title",
                         name: "title",
                         type: "string",
                         placeholder: "",
-                        helptext: A.title,
+                        helptext: F.title,
                         value: a.title,
                         errors: t,
                         required: !0
                     }), r.a.createElement("div", {
                         className: D ? "" : "dynamic-url"
                     }, r.a.createElement(h, {
                         name: "url",
@@ -1064,44 +1050,44 @@
                             display: D ? "inline" : "none"
                         }
                     }, a.url || a.name || I(a.title)), r.a.createElement("button", {
                         type: "button",
                         className: "usa-button dataset_url_edit",
                         onClick: function() {
                             var e = a.url;
-                            D ? a.url || (a.url = I(a.title)) : e && (a.url = "".concat(T).concat(v()(e.substring(T.length, e.length)))), P(!D)
+                            D ? a.url || (a.url = I(a.title)) : e && (a.url = "".concat(P).concat(v()(e.substring(P.length, e.length)))), k(!D)
                         }
                     }, D ? "Edit" : "Update")))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement(h, {
                         label: "Description",
                         name: "description",
                         type: "string",
                         component: "textarea",
                         rows: "6",
-                        helptext: A.description,
+                        helptext: F.description,
                         value: a.description,
                         errors: t,
                         required: !0
                     })), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("span", {
                         className: "usa-label"
-                    }, "Tags"), r.a.createElement(z, {
+                    }, "Tags"), r.a.createElement(V, {
                         id: "tags-autocomplete-input",
                         tags: a.tags,
                         apiUrl: n,
                         apiKey: i,
-                        fetchOpts: B.fetchTags,
+                        fetchOpts: q.fetchTags,
                         name: "tags",
                         titleField: "name",
                         required: !0,
                         placeholder: "Start typing to search",
                         errors: t,
-                        helptext: k("Use both technical and non-technical terms to help users find your dataset. Press tab or enter to add each new tag.")
+                        helptext: T("Use both technical and non-technical terms to help users find your dataset. Press tab or enter to add each new tag.")
                     })), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement(h, {
                         label: "Organization",
                         name: "owner_org",
                         type: "select",
                         value: a.owner_org,
@@ -1114,24 +1100,24 @@
                         errors: t
                     })), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("span", {
                         className: "usa-label"
-                    }, "Select Publisher", r.a.createElement(f, null, r.a.createElement("h3", null, "Publisher"), r.a.createElement("p", null, "The publishing entity (e.g. your agency, department, bureau, or office)."))), r.a.createElement(W, {
+                    }, "Select Publisher", r.a.createElement(f, null, r.a.createElement("h3", null, "Publisher"), r.a.createElement("p", null, "The publishing entity (e.g. your agency, department, bureau, or office)."))), r.a.createElement(Z, {
                         name: "publisher",
                         type: "string",
                         value: a.publisher,
                         inputValue: function() {
                             var e = a.selectedPublisher;
                             return e ? e.name : "string" === typeof a.publisher ? a.publisher : ""
                         }(),
                         placeholder: "Select publisher",
-                        helptext: A.select,
+                        helptext: F.select,
                         fetchOpts: C,
                         apiUrl: n,
                         apiKey: i
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement(h, {
                         label: "Contact Name",
@@ -1151,15 +1137,15 @@
                     })), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement(h, {
                         label: "Unique ID",
                         name: "unique_id",
                         type: "string",
                         required: !0,
-                        helptext: k("Every dataset must have a ID number that is unique within the agency."),
+                        helptext: T("Every dataset must have a ID number that is unique within the agency."),
                         infoText: "This is the ID number or code used within your agency to differentiate this dataset from other datasets.",
                         errors: t
                     })), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement(h, {
                         label: "Public Access level",
                         name: "public_access_level",
@@ -1183,114 +1169,114 @@
                         required: !0
                     })), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement(h, {
                         label: "License",
                         name: "license",
                         type: "select",
-                        choices: ae,
+                        choices: te,
                         value: a.license,
                         className: "error-msg",
                         errors: t,
                         required: !0
                     }), r.a.createElement(h, {
                         name: "licenseOther",
                         type: "string",
-                        helptext: k('If you selected \u201cOther\u201d, please specify the name of your License in URL format. Please include "https://" at the beginning of your URL.*'),
+                        helptext: T('If you selected \u201cOther\u201d, please specify the name of your License in URL format. Please include "https://" at the beginning of your URL.*'),
                         value: a.licenseOther,
                         disabled: "other" !== a.license,
                         errors: t,
                         required: !0
                     })), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("span", {
                         className: "usa-label"
                     }, "Rights"), " ", r.a.createElement("br", null), t && t.rights && r.a.createElement("span", {
                         className: "error-msg"
-                    }, t.rights), r.a.createElement(Q, {
+                    }, t.rights), r.a.createElement($, {
                         label: "My dataset is public",
                         name: "access_level_comment",
                         errors: t,
                         value: "true",
                         id: "rights_option_1"
-                    }), r.a.createElement(Q, {
+                    }), r.a.createElement($, {
                         label: "My dataset is not public",
                         name: "access_level_comment",
                         value: "false",
                         id: "rights_option_2"
                     }), r.a.createElement(h, {
                         name: "rights_desc",
                         type: "string",
                         value: a.rights_desc,
                         errors: t,
-                        helptext: k("If your dataset is not public, please add an explanation of rights and feel free to include any instructions on restrictions, or how to access a restricted file (max 255 characters)*"),
+                        helptext: T("If your dataset is not public, please add an explanation of rights and feel free to include any instructions on restrictions, or how to access a restricted file (max 255 characters)*"),
                         disabled: "true" === a.access_level_comment
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("span", {
                         className: "usa-label"
                     }, "Relevant Location"), " ", r.a.createElement("br", null), t && t.spatial && r.a.createElement("span", {
                         className: "error-msg"
-                    }, t.spatial), r.a.createElement(Q, {
+                    }, t.spatial), r.a.createElement($, {
                         label: "My dataset does not have a spatial component",
                         name: "spatial",
                         value: "false",
                         errors: t,
                         id: "spatial_option_1"
-                    }), r.a.createElement(Q, {
+                    }), r.a.createElement($, {
                         label: "My dataset does have a spatial component",
                         name: "spatial",
                         value: "true",
                         id: "spatial_option_2"
                     }), r.a.createElement(h, {
                         name: "spatial_location_desc",
                         type: "string",
                         value: a.spatial_location_desc,
                         errors: t,
-                        helptext: k("If your dataset has a spatial component, please provide location such as place name or latitude/longitude pairs above*"),
+                        helptext: T("If your dataset has a spatial component, please provide location such as place name or latitude/longitude pairs above*"),
                         disabled: "false" === a.spatial
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("span", {
                         className: "usa-label"
                     }, "Temporal", r.a.createElement(f, null, r.a.createElement("h3", null, "Temporal"), r.a.createElement("p", null, "For example, for a 2010 Census dataset (which runs for 10 years until April 1st of the year of the Census), the temporal extent would cover a period of time beginning 2000-04-02 and ending 2010-04-01."))), " ", r.a.createElement("br", null), t && t.temporal && r.a.createElement("span", {
                         className: "error-msg"
-                    }, t.temporal), r.a.createElement(Q, {
+                    }, t.temporal), r.a.createElement($, {
                         label: "My dataset does not have a start and end date for the applicability of data",
                         name: "temporal",
                         value: "false",
                         errors: t,
                         id: "temporal_option_1"
-                    }), r.a.createElement(Q, {
+                    }), r.a.createElement($, {
                         label: "My dataset has a start and end date for the applicability of data",
                         name: "temporal",
                         value: "true",
                         errors: t,
                         id: "temporal_option_2"
                     }), r.a.createElement(h, {
                         name: "temporal_start_date",
                         type: "date",
                         id: "temporal_start_date",
                         value: a.temporal_start_date,
                         errors: t,
-                        helptext: k("If your dataset has a temporal component, please provide start date for applicability of data above (MM/DD/YYYY)*"),
+                        helptext: T("If your dataset has a temporal component, please provide start date for applicability of data above (MM/DD/YYYY)*"),
                         disabled: "false" === a.temporal
                     }), r.a.createElement(h, {
                         name: "temporal_end_date",
                         type: "date",
                         id: "temporal_end_date",
                         value: a.temporal_end_date,
                         errors: t,
-                        helptext: k("If your dataset has a temporal component, please provide end date for applicability of data above (MM/DD/YYYY)*"),
+                        helptext: T("If your dataset has a temporal component, please provide end date for applicability of data above (MM/DD/YYYY)*"),
                         disabled: "false" === a.temporal
                     }))), r.a.createElement("div", {
                         className: "margin-top-6 clearfix"
                     }, "Published" === a.publishing_status ? "" : r.a.createElement("button", {
                         className: "usa-button usa-button--outline",
                         type: "button",
                         onClick: Object(o.a)(c.a.mark((function e() {
@@ -1326,65 +1312,65 @@
                         style: {
                             marginTop: "1rem"
                         }
                     }, r.a.createElement("div", {
                         className: "grid-col-12 text-mint"
                     }, r.a.createElement("i", null, "Draft saved:", r.a.createElement("br", null), "[", s, "]"))))
                 },
-                le = t(3),
-                re = le.e().shape({
-                    saveDraft: le.b(),
-                    title: le.f().required("Title is required"),
-                    owner_org: le.f().required("Organization is required"),
-                    contact_name: le.f().when("saveDraft", (function(e, a) {
+                re = t(3),
+                ne = re.e().shape({
+                    saveDraft: re.b(),
+                    title: re.f().required("Title is required"),
+                    owner_org: re.f().required("Organization is required"),
+                    contact_name: re.f().when("saveDraft", (function(e, a) {
                         return e ? a : a.required("Contact is required")
                     })),
-                    unique_id: le.f().when("saveDraft", (function(e, a) {
+                    unique_id: re.f().when("saveDraft", (function(e, a) {
                         return e ? a : a.required("Unique ID is required")
                     })),
-                    contact_email: le.f().when("saveDraft", (function(e, a) {
+                    contact_email: re.f().when("saveDraft", (function(e, a) {
                         return e ? a : a.email("Must be valid email").required("Contact email is required")
                     })),
-                    description: le.f().when("saveDraft", (function(e, a) {
+                    description: re.f().when("saveDraft", (function(e, a) {
                         return e ? a : a.required("Description is required")
                     })),
-                    tags: le.a().when("saveDraft", (function(e, a) {
-                        return e ? a : a.of(le.e().shape({
-                            name: le.f().min(2).max(100).matches(/[a-zA-Z0-9-_.]+/),
-                            vocabulary_id: le.f()
+                    tags: re.a().when("saveDraft", (function(e, a) {
+                        return e ? a : a.of(re.e().shape({
+                            name: re.f().min(2).max(100).matches(/[a-zA-Z0-9-_.]+/),
+                            vocabulary_id: re.f()
                         })).required("Tags are required. Please, provide at least one tag. Note that a tag name must be a string between 2 and 100 characters long containing only alphanumeric characters and -, _ and .")
                     })),
-                    publisher: le.f().when("saveDraft", (function(e, a) {
+                    publisher: re.f().when("saveDraft", (function(e, a) {
                         return e ? a : a.required("Publisher is required")
                     })),
-                    public_access_level: le.f().when("saveDraft", (function(e, a) {
+                    public_access_level: re.f().when("saveDraft", (function(e, a) {
                         return e ? a : a.required("Access level is required")
                     })),
-                    rights_desc: le.f().required("Please add explanation of rights").when("access_level_comment", (function(e, a) {
-                        return "false" === e ? a : le.f()
+                    rights_desc: re.f().required("Please add explanation of rights").when("access_level_comment", (function(e, a) {
+                        return "false" === e ? a : re.f()
                     })),
-                    spatial: le.f().test("spatial-location-extra", "Please provide location description.", (function(e) {
+                    spatial: re.f().test("spatial-location-extra", "Please provide location description.", (function(e) {
                         var a = this.from[0].value;
                         return !("true" === e && !a.spatial_location_desc)
                     })),
-                    spatial_location_desc: le.f(),
-                    licenseOther: le.f().required("License is required").url("License should be a valid url").when("license", (function(e, a) {
-                        return "other" === e ? a : le.f()
+                    spatial_location_desc: re.f(),
+                    licenseOther: re.f().required("License is required").url("License should be a valid url").when("license", (function(e, a) {
+                        return "other" === e ? a : re.f()
                     })),
-                    license: le.f().when("saveDraft", (function(e, a) {
+                    license: re.f().when("saveDraft", (function(e, a) {
                         return e ? a : a.required("License is required")
                     })),
-                    temporal: le.f().test("temporal-start-end", "Please specify start and end date", (function(e) {
+                    temporal: re.f().test("temporal-start-end", "Please specify start and end date", (function(e) {
                         var a = this.from[0].value;
                         return !!("true" !== e || a.temporal_start_date && a.temporal_end_date)
                     })),
-                    temporal_start_date: le.c().typeError("Please specify a valid start date"),
-                    temporal_end_date: le.c().typeError("Please specify a valid end date")
+                    temporal_start_date: re.c().typeError("Please specify a valid start date"),
+                    temporal_end_date: re.c().typeError("Please specify a valid end date")
                 }),
-                ne = {
+                ie = {
                     title: "Title",
                     contact_name: "Contact Name",
                     unique_id: "Unique ID",
                     contact_email: "Contact Email",
                     description: "Description",
                     publisher: "Publisher",
                     public_access_level: "Public Access Level",
@@ -1395,23 +1381,23 @@
                     licenseOther: "License",
                     temporal: "Temporal",
                     tags: "Tags",
                     owner_org: "Organization",
                     temporal_start_date: "Temporal Start Date",
                     temporal_end_date: "Temporal End Date"
                 },
-                ie = {
+                se = {
                     access_level_comment: "true",
                     spatial: "false",
                     spatial_location: "false",
                     temporal: "false",
                     modifiedOther: "",
                     publisher: ""
                 },
-                se = {
+                ce = {
                     dataQuality: "",
                     themes: "",
                     describedByType: "",
                     accrualPeriodicity: "",
                     landingPage: "",
                     languageSubTag: "en",
                     languageRegSubTag: "US",
@@ -1419,36 +1405,36 @@
                     references: "",
                     issued: "",
                     systemOfRecordsUSG: "",
                     isPartOf: "",
                     isParent: "",
                     parentDataset: ""
                 },
-                ce = t(590),
-                oe = t(225).sort((function(e, a) {
+                oe = t(590),
+                ue = t(225).sort((function(e, a) {
                     var t = (e.label || "").toLowerCase(),
                         l = (a.label || "").toLowerCase();
                     return t < l ? -1 : t > l ? 1 : 0
                 })),
-                ue = t(227),
-                de = {
-                    describedBy: r.a.createElement(Z, null, 'Provide a link to data dictionary or other reference that helps users understand the dataset. Example: "https://www.agency.gov/vegetables/vegetables-all.zip"'),
-                    landingPage: r.a.createElement(Z, null, 'This landing page should contain or be linked to all resources tied to the dataset. Example: "https://www.agency.gov/vegetables"'),
-                    primaryITInvestmentUIIUSG: r.a.createElement(Z, null, "This can often be found in Exhibit 53 documents, and takes the form ###-#########. Learn more about Exhibit 53 documents at", " ", r.a.createElement(ee, {
+                de = t(227),
+                me = {
+                    describedBy: r.a.createElement(H, null, 'Provide a link to data dictionary or other reference that helps users understand the dataset. Example: "https://www.agency.gov/vegetables/vegetables-all.zip"'),
+                    landingPage: r.a.createElement(H, null, 'This landing page should contain or be linked to all resources tied to the dataset. Example: "https://www.agency.gov/vegetables"'),
+                    primaryITInvestmentUIIUSG: r.a.createElement(H, null, "This can often be found in Exhibit 53 documents, and takes the form ###-#########. Learn more about Exhibit 53 documents at", " ", r.a.createElement(ae, {
                         target: "_blank",
                         href: "https://www.whitehouse.gov/wp-content/uploads/2018/06/fy-2020-it-budget-guidance.pdf"
                     }, "this PDF"), "."),
-                    references: r.a.createElement(Z, null, "Related documents such as technical information about a dataset, developer documentation, etc. Format for entry is: https://www.agency.gov/fruits/fruits.csv, https://www.agency.gov/legumes/legumes"),
-                    systemOfRecordsUSG: r.a.createElement(Z, null, "If the dataset is a designated System of Records under the Privacy Act of 1974, provide the URL for the System of Records Notice"),
-                    accrualPeriodicity: r.a.createElement(Z, null, "If you selected \u201cOther, please specify a valid", " ", r.a.createElement(ee, {
+                    references: r.a.createElement(H, null, "Related documents such as technical information about a dataset, developer documentation, etc. Format for entry is: https://www.agency.gov/fruits/fruits.csv, https://www.agency.gov/legumes/legumes"),
+                    systemOfRecordsUSG: r.a.createElement(H, null, "If the dataset is a designated System of Records under the Privacy Act of 1974, provide the URL for the System of Records Notice"),
+                    accrualPeriodicity: r.a.createElement(H, null, "If you selected \u201cOther, please specify a valid", " ", r.a.createElement(ae, {
                         target: "_blank",
                         href: "https://en.wikipedia.org/wiki/ISO_8601"
                     }, "ISO 8601"), " ", "timestamp")
                 },
-                me = function(e) {
+                pe = function(e) {
                     var a, t = e.values,
                         l = e.apiUrl,
                         n = e.errors,
                         i = e.apiKey,
                         s = e.draftSaved,
                         u = e.setFieldValue,
                         d = e.submitForm,
@@ -1456,15 +1442,15 @@
                     return r.a.createElement("div", {
                         className: "usa-form-custom"
                     }, r.a.createElement("section", {
                         id: "section-basic-mega-menu",
                         className: "site-component-section"
                     }, r.a.createElement("p", {
                         className: "site-text-intro"
-                    }, "Please note that the additional metadata that you upload will help public users better find and use this dataset. Not all of these criteria will apply to each dataset, so feel free to only answer what applies. For more information about the form fields, consult the", " ", r.a.createElement(ee, {
+                    }, "Please note that the additional metadata that you upload will help public users better find and use this dataset. Not all of these criteria will apply to each dataset, so feel free to only answer what applies. For more information about the form fields, consult the", " ", r.a.createElement(ae, {
                         target: "_blank",
                         href: "https://resources.data.gov/schemas/dcat-us/v1.1/"
                     }, "DCAT-US Schema"), ".")), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
@@ -1476,121 +1462,121 @@
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("span", {
                         className: "usa-label"
                     }, "Geospatial"), r.a.createElement("div", {
                         className: "usa-helptext"
-                    }, "Geospatial datasets are included in", " ", r.a.createElement(ee, {
+                    }, "Geospatial datasets are included in", " ", r.a.createElement(ae, {
                         target: "_blank",
                         href: "https://www.geoplatform.gov/"
-                    }, "geoplatform.gov"), "."), r.a.createElement(Q, {
+                    }, "geoplatform.gov"), "."), r.a.createElement($, {
                         label: "My dataset is a geospatial dataset",
                         name: "category",
                         value: "geospatial",
                         id: "category-option-yes"
-                    }), r.a.createElement(Q, {
+                    }), r.a.createElement($, {
                         label: "My dataset is not a geospatial dataset",
                         name: "category",
                         value: "",
                         id: "category-option-no"
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Data Dictionary URL",
                         name: "data_dictionary",
                         type: "string",
                         helptext: 'Please include "https://" at the beginning of your URL.',
-                        infoText: de.describedBy
+                        infoText: me.describedBy
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Data Dictionary Type",
                         name: "describedByType",
                         value: t.describedByType,
                         type: "select",
-                        choices: oe
+                        choices: ue
                     }), r.a.createElement(h, {
                         disabled: "other" !== t.describedByType,
                         name: "otherDataDictionaryType",
                         value: t.otherDataDictionaryType,
                         type: "string",
                         helptext: "If you selected \u201cOther\u201d, please specify your Data Dictionary Type"
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Data Publishing Frequency",
                         name: "accrualPeriodicity",
                         type: "select",
-                        choices: ue,
+                        choices: de,
                         className: "error-msg",
                         errors: n
                     }), r.a.createElement(h, {
                         name: "accrualPeriodicityOther",
                         type: "string",
-                        helptext: de.accrualPeriodicity,
+                        helptext: me.accrualPeriodicity,
                         disabled: "other" !== t.accrualPeriodicity,
                         errors: n
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Dataset Landing Page URL",
                         name: "homepage_url",
                         type: "string",
                         helptext: 'Please include "https://" at the beginning of your URL.',
-                        infoText: de.landingPage
+                        infoText: me.landingPage
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Language - Language Subtag",
                         name: "languageSubTag",
                         value: t.languageSubTag,
                         type: "select",
-                        choices: ce
+                        choices: oe
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         disabled: !t.languageSubTag,
                         label: "Language - Regional Subtag",
                         name: "languageRegSubTag",
                         value: t.languageRegSubTag,
                         type: "select",
-                        choices: (a = t.languageSubTag, (ce.find((function(e) {
+                        choices: (a = t.languageSubTag, (oe.find((function(e) {
                             return e.value === a
                         })) || {}).regions)
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Dataset's IT Unique Investment Identifier",
                         name: "primary_it_investment_uii",
                         type: "string",
-                        infoText: de.primaryITInvestmentUIIUSG
+                        infoText: me.primaryITInvestmentUIIUSG
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Related Documents",
                         name: "related_documents",
                         type: "string",
-                        infoText: de.references
+                        infoText: me.references
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Release Date",
                         name: "release_date",
@@ -1600,15 +1586,15 @@
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "System of Records Notice URL",
                         name: "system_of_records",
                         type: "string",
-                        infoText: de.systemOfRecordsUSG
+                        infoText: me.systemOfRecordsUSG
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Is parent dataset",
                         name: "isParent",
@@ -1616,23 +1602,23 @@
                         choices: ["Yes", "No"]
                     }))), "No" === t.isParent && r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("span", {
                         className: "usa-label"
-                    }, "Select Parent Dataset"), r.a.createElement(W, {
+                    }, "Select Parent Dataset"), r.a.createElement(Z, {
                         label: "Select Parent Dataset",
                         name: "parentDataset",
                         type: "string",
                         value: t.parentDataset,
                         inputValue: t.parentDatasetTitle,
                         placeholder: "Select parent dataset",
                         helptext: "Start typing to see list of matching datasets by title",
-                        fetchOpts: B.fetchParentDatasets,
+                        fetchOpts: q.fetchParentDatasets,
                         apiUrl: l,
                         apiKey: i
                     }))), r.a.createElement("div", {
                         className: "margin-top-6 clearfix"
                     }, "Published" === t.publishing_status ? "" : r.a.createElement("button", {
                         className: "usa-button usa-button--outline",
                         type: "button",
@@ -1680,47 +1666,47 @@
                         style: {
                             marginTop: "1rem"
                         }
                     }, r.a.createElement("div", {
                         className: "col-md-12 text-mint"
                     }, r.a.createElement("i", null, "Draft saved:", r.a.createElement("br", null), "[", s, "]"))))
                 },
-                pe = /^P(?:(\d+(?:[\.,]\d+)?)Y)?(?:(\d+(?:[\.,]\d+)?)M)?(?:(\d+(?:[\.,]\d+)?)D)?(?:T(?:(\d+(?:[\.,]\d+)?)H)?(?:(\d+(?:[\.,]\d+)?)M)?(?:(\d+(?:[\.,]\d+)?)S)?)?$/,
-                ve = le.e().shape({
-                    dataQuality: le.f(),
-                    category: le.f(),
-                    data_dictionary: le.f().url(),
-                    data_dictionary_type: le.f(),
-                    primary_it_investment_uii: le.f().trim().matches(/^[0-9]{3}-[0-9]{9}$/, "uii should match format: 000-000000000"),
-                    homepage_url: le.f().url(),
-                    related_documents: le.f(),
-                    deribed_by: le.f().url(),
-                    described_by_type: le.f(),
-                    system_of_records: le.f(),
-                    release_date: le.c().typeError("Please specify a valid release date"),
-                    accrualPeriodicityOther: le.f().test("accrual-periodicity-other", "Data Publishing Frequency should be formatted as a proper ISO 8601 timestamp", (function(e) {
-                        return e && pe.test(e.replace("R/", ""))
+                ve = /^P(?:(\d+(?:[\.,]\d+)?)Y)?(?:(\d+(?:[\.,]\d+)?)M)?(?:(\d+(?:[\.,]\d+)?)D)?(?:T(?:(\d+(?:[\.,]\d+)?)H)?(?:(\d+(?:[\.,]\d+)?)M)?(?:(\d+(?:[\.,]\d+)?)S)?)?$/,
+                be = re.e().shape({
+                    dataQuality: re.f(),
+                    category: re.f(),
+                    data_dictionary: re.f().url(),
+                    data_dictionary_type: re.f(),
+                    primary_it_investment_uii: re.f().trim().matches(/^[0-9]{3}-[0-9]{9}$/, "uii should match format: 000-000000000"),
+                    homepage_url: re.f().url(),
+                    related_documents: re.f(),
+                    deribed_by: re.f().url(),
+                    described_by_type: re.f(),
+                    system_of_records: re.f(),
+                    release_date: re.c().typeError("Please specify a valid release date"),
+                    accrualPeriodicityOther: re.f().test("accrual-periodicity-other", "Data Publishing Frequency should be formatted as a proper ISO 8601 timestamp", (function(e) {
+                        return e && ve.test(e.replace("R/", ""))
                     })).when("accrualPeriodicity", (function(e, a) {
-                        return "other" === e ? a : le.f()
+                        return "other" === e ? a : re.f()
                     }))
                 }),
-                be = t(600),
-                ge = t(257),
-                fe = (t(591), ge.sort((function(e, a) {
+                ge = t(600),
+                fe = t(257),
+                he = (t(591), fe.sort((function(e, a) {
                     var t = e.label.toUpperCase(),
                         l = a.label.toUpperCase();
                     return t < l ? -1 : t > l ? 1 : 0
                 }))),
-                he = {
-                    conformsTo: r.a.createElement(Z, null, "Refer to documentation here for", " ", r.a.createElement(ee, {
+                ye = {
+                    conformsTo: r.a.createElement(H, null, "Refer to documentation here for", " ", r.a.createElement(ae, {
                         target: "_blank",
                         href: "https://github.com/GSA/ckanext-datajson/tree/main/ckanext/datajson/tests/datajson-samples#datajson-examples"
                     }, "geospatial datasets"), " ")
                 },
-                ye = function(e) {
+                Ee = function(e) {
                     var a = e.values,
                         t = e.errors,
                         n = e.setFieldValue,
                         i = e.submitForm,
                         s = e.draftSaved,
                         u = e.isSubmitting,
                         m = e.handleSteps,
@@ -1731,38 +1717,38 @@
                         f = v.name,
                         y = v.description,
                         E = v.mimetype,
                         _ = v.conformsTo,
                         x = v.format,
                         S = Object(l.useState)(!1),
                         w = Object(d.a)(S, 2),
-                        k = w[0],
-                        T = w[1],
+                        T = w[0],
+                        P = w[1],
                         I = Object(l.useState)(!1),
                         C = Object(d.a)(I, 2),
-                        A = C[0],
-                        F = C[1];
+                        F = C[0],
+                        R = C[1];
                     Object(l.useEffect)((function() {
                         v.format || v.urlType !== D || n("resource.format", "API")
                     }), [v.urlType]);
-                    var R = function() {
-                        F(!1)
+                    var j = function() {
+                        R(!1)
                     };
                     return r.a.createElement("div", {
                         className: "usa-form-custom",
                         id: "resource-upload"
                     }, r.a.createElement("section", {
                         id: "section-basic-mega-menu",
                         className: "site-component-section"
                     }, r.a.createElement("h1", {
                         className: "usite-page-title",
                         id: "basic-mega-menu"
                     }, "Resource Upload"), r.a.createElement("p", {
                         className: "site-text-intro"
-                    }, "You can add the URL of the dataset where it is available on the agency website. If you are uploading the dataset itself, please notify the Data.gov team at", " ", r.a.createElement(ee, {
+                    }, "You can add the URL of the dataset where it is available on the agency website. If you are uploading the dataset itself, please notify the Data.gov team at", " ", r.a.createElement(ae, {
                         target: "_blank",
                         href: "mailto:inventory-help@gsa.gov"
                     }, "inventory-help@gsa.gov"), ". You can also add a URL or file of information related to the dataset such as a data dictionary.")), b.length ? r.a.createElement("div", {
                         className: "margin-top-10 padding-bottom-8 border-gray-10 border-bottom-2px"
                     }, r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
@@ -1774,82 +1760,82 @@
                         }, r.a.createElement("div", {
                             className: "grid-col-12 bg-base-lightest padding-x-1"
                         }, r.a.createElement("div", {
                             className: "resource-item-name"
                         }, e.name), r.a.createElement("button", {
                             id: "delete-".concat(e.name),
                             onClick: function() {
-                                return a = e.name, void F(a);
+                                return a = e.name, void R(a);
                                 var a
                             },
                             type: "button",
                             className: "usa-button--unstyled resource-action-button"
-                        }, "Delete"), A === e.name && r.a.createElement(be.a, {
+                        }, "Delete"), F === e.name && r.a.createElement(ge.a, {
                             onExit: function() {
-                                return R()
+                                return j()
                             },
                             getApplicationNode: function() {
                                 return document.getElementById("resource-upload")
                             },
                             heading: "Please Confirm Action",
                             underlayClickExits: !0,
                             actions: [r.a.createElement("button", {
                                 type: "button",
                                 className: "ds-c-button ds-c-button--primary",
                                 key: "primary",
                                 onClick: function() {
                                     ! function(e) {
                                         n("resource", {
                                             id: e.id
-                                        }), n("resourceAction", "delete"), n("publish", !1), n("saveDraft", !1), T(!1), i()
-                                    }(e), R()
+                                        }), n("resourceAction", "delete"), n("publish", !1), n("saveDraft", !1), P(!1), i()
+                                    }(e), j()
                                 }
                             }, "Delete"), r.a.createElement("button", {
                                 type: "button",
                                 className: "ds-c-button ds-c-button--transparent",
                                 key: "cancel",
                                 onClick: function() {
-                                    return R()
+                                    return j()
                                 }
                             }, "Cancel")]
                         }, "Are you sure you want to delete this resource?"), r.a.createElement("button", {
                             id: "edit-".concat(e.name),
                             onClick: function() {
                                 ! function(e) {
-                                    n("resourceAction", "edit"), T(!1), n("resource", e), n("resource.size", ""), n("resource.webstore_last_updated", ""), n("resource.cache_last_updated", "")
+                                    n("resourceAction", "edit"), P(!1), n("resource", e), n("resource.size", ""), n("resource.webstore_last_updated", ""), n("resource.cache_last_updated", "")
                                 }(e)
                             },
                             type: "button",
                             className: "usa-button--unstyled resource-action-button"
                         }, "Edit")))
                     }))) : "", r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("span", {
                         className: "usa-label"
-                    }, "Resource"), r.a.createElement(Q, {
+                    }, "Resource"), r.a.createElement($, {
                         label: r.a.createElement(r.a.Fragment, null, r.a.createElement("b", null, "Link to a file:"), " Provide a direct download link to a file"),
                         name: "resource.urlType",
                         value: N,
                         id: "resource-option-link-to-file"
-                    }), r.a.createElement(Q, {
+                    }), r.a.createElement($, {
                         label: r.a.createElement(r.a.Fragment, null, r.a.createElement("b", null, "Upload a file:"), " Upload a file from your computer"),
                         name: "resource.urlType",
                         value: O,
                         id: "resource-option-upload-file"
-                    }), r.a.createElement(Q, {
+                    }), r.a.createElement($, {
                         label: r.a.createElement(r.a.Fragment, null, r.a.createElement("b", null, "Link to an API:"), " Provide a link to access a dataset via API"),
                         name: "resource.urlType",
                         value: D,
                         id: "resource-option-link-to-api"
-                    }), r.a.createElement(Q, {
+                    }), r.a.createElement($, {
                         label: r.a.createElement(r.a.Fragment, null, r.a.createElement("b", null, "Access URL:"), " Provide a link to a resource that is not directly downloadable, like an html website"),
                         name: "resource.urlType",
-                        value: P,
+                        value: k,
                         id: "resource-option-access-url"
                     })), r.a.createElement("div", {
                         className: "grid-col-12"
                     }, v.urlType && r.a.createElement("label", {
                         className: "usa-label"
                     }, v.urlType === O ? "File" : "URL"), v.urlType && v.urlType !== O || g ? r.a.createElement("div", null, r.a.createElement("p", {
                         className: "usa-helptext"
@@ -1858,34 +1844,34 @@
                         name: "resource.url",
                         type: "url",
                         value: g,
                         onClick: function() {
                             n("resource.url", "")
                         },
                         errors: t
-                    })) : k ? r.a.createElement(h, {
+                    })) : T ? r.a.createElement(h, {
                         name: "resource.fileName",
                         type: "label",
                         value: v.fileName,
                         onClick: function() {
-                            n("resource.upload", null), n("resource.fileName", ""), n("resource.name", ""), n("resource.description", ""), n("resource.mimetype", ""), n("resource.conformsTo", ""), n("resource.format", ""), T(!1)
+                            n("resource.upload", null), n("resource.fileName", ""), n("resource.name", ""), n("resource.description", ""), n("resource.mimetype", ""), n("resource.conformsTo", ""), n("resource.format", ""), P(!1)
                         }
                     }) : v.urlType === O && r.a.createElement(r.a.Fragment, null, r.a.createElement("br", null), r.a.createElement("label", {
                         tabIndex: "0",
                         htmlFor: "upload",
                         className: "usa-button usa-button--base"
                     }, r.a.createElement("i", {
                         className: "fa fa-cloud-upload",
                         "aria-hidden": "true"
                     }), " Upload data"), r.a.createElement("input", {
                         id: "upload",
                         name: "resource.upload",
                         type: "file",
                         onChange: function(e) {
-                            if (T(!k), n("resource.fileName", e.currentTarget.files[0].name), f || n("resource.name", e.currentTarget.files[0].name), E || n("resource.mimetype", e.currentTarget.files[0].type), !x) {
+                            if (P(!T), n("resource.fileName", e.currentTarget.files[0].name), f || n("resource.name", e.currentTarget.files[0].name), E || n("resource.mimetype", e.currentTarget.files[0].type), !x) {
                                 var a = e.currentTarget.files[0].name && e.currentTarget.files[0].name.split(".").slice(-1)[0];
                                 n("resource.format", a || "")
                             }
                             n("resource.upload", e.currentTarget.files[0])
                         }
                     }), r.a.createElement("p", {
                         className: "usa-helptext"
@@ -1916,26 +1902,26 @@
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Media Type",
                         name: "resource.mimetype",
                         type: "select",
-                        choices: fe,
+                        choices: he,
                         value: E
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Conforms To",
                         name: "resource.conformsTo",
                         type: "string",
                         helptext: "Please ensure this is a resolvable URL.",
-                        infoText: he.conformsTo,
+                        infoText: ye.conformsTo,
                         value: _
                     }))), r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement(h, {
                         label: "Format",
@@ -1947,15 +1933,15 @@
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("button", {
                         type: "button",
                         className: "usa-button usa-button--outline",
                         onClick: function() {
-                            n("publish", !1), n("saveDraft", !1), T(!1), i()
+                            n("publish", !1), n("saveDraft", !1), P(!1), i()
                         },
                         disabled: u
                     }, "edit" === p ? "Save" : "Save and add another resource"))), a.lastSavedResource && b.length ? r.a.createElement("div", {
                         className: "grid-row margin-top-3"
                     }, r.a.createElement("div", {
                         className: "grid-col-12"
                     }, r.a.createElement("div", {
@@ -2012,34 +1998,34 @@
                         style: {
                             marginTop: "1rem"
                         }
                     }, r.a.createElement("div", {
                         className: "grid-col-12 text-custom-green"
                     }, r.a.createElement("i", null, "Draft saved:", r.a.createElement("br", null), "[", s, "]"))))
                 },
-                Ee = le.e().shape({
-                    resource: le.e().shape({
-                        name: le.f(),
-                        description: le.f(),
-                        mimetype: le.f(),
-                        format: le.f(),
-                        url: le.f().url('If you are linking to a dataset, please include "https://" at the beginning of your URL.'),
-                        upload: le.d()
+                _e = re.e().shape({
+                    resource: re.e().shape({
+                        name: re.f(),
+                        description: re.f(),
+                        mimetype: re.f(),
+                        format: re.f(),
+                        url: re.f().url('If you are linking to a dataset, please include "https://" at the beginning of your URL.'),
+                        upload: re.d()
                     })
                 }),
-                _e = {
+                xe = {
                     name: "",
                     description: "",
                     url: "",
                     format: "",
                     mimetype: "",
                     conformsTo: "",
                     upload: null
                 },
-                xe = function(e) {
+                Se = function(e) {
                     var a = e.currentStep,
                         t = e.handleSteps;
                     return r.a.createElement("div", {
                         className: "app_navigation",
                         id: "app_navigation"
                     }, r.a.createElement("div", {
                         tabIndex: "0",
@@ -2070,15 +2056,15 @@
                             13 === e.keyCode && t(2)
                         },
                         onClick: function() {
                             t(2)
                         }
                     }, r.a.createElement("span", null, "Resource Upload")))
                 },
-                Se = function(e) {
+                we = function(e) {
                     Object(l.useEffect)((function() {
                         window.scrollTo(0, 0)
                     }), []);
                     var a = e.type,
                         t = e.errors,
                         n = e.message,
                         i = e.heading,
@@ -2116,238 +2102,238 @@
                         className: "usa-alert__text"
                     }, "string" === typeof n && n, "object" === typeof n && n.map((function(e) {
                         return r.a.createElement("p", {
                             key: e
                         }, e)
                     })), c)))))
                 },
-                we = (t(597), function(e) {
+                Ne = (t(597), function(e) {
                     return Object.keys(e).map((function(a) {
                         return {
                             name: a,
-                            label: ne[a],
+                            label: ie[a],
                             message: e[a]
                         }
                     }))
                 }),
-                Ne = function(e) {
+                Oe = function(e) {
                     return "".concat(["0".concat(e.getHours()).slice(-2), "0".concat(e.getMinutes()).slice(-2)].join(":"), ", ").concat(["0".concat(e.getMonth() + 1).slice(-2), "0".concat(e.getDate()).slice(-2), e.getFullYear().toString().slice(-2)].join("-"))
                 },
-                Oe = function(e) {
+                De = function(e) {
                     var a = e.currentStep;
                     return 0 === a ? r.a.createElement("h1", {
                         className: "usite-page-title",
                         id: "basic-mega-menu"
                     }, "Required Metadata") : 1 === a ? r.a.createElement("h1", {
                         className: "usite-page-title",
                         id: "basic-mega-menu"
                     }, "Additional Metadata") : ""
                 },
-                De = function(e) {
+                ke = function(e) {
                     var a = e.apiUrl,
                         t = e.apiKey,
                         n = e.ownerOrg,
                         i = e.datasetId,
                         s = Object(l.useState)(!0),
                         p = Object(d.a)(s, 2),
                         v = p[0],
                         b = p[1],
                         g = Object(l.useState)(i),
                         f = Object(d.a)(g, 2),
                         h = f[0],
                         y = f[1],
-                        E = Object(l.useState)(Object(u.a)(Object(u.a)(Object(u.a)({}, ie), se), {}, {
+                        E = Object(l.useState)(Object(u.a)(Object(u.a)(Object(u.a)({}, se), ce), {}, {
                             publishing_status: "Draft",
                             private: !0,
                             saveDraft: !1
                         })),
                         _ = Object(d.a)(E, 2),
                         x = _[0],
                         S = _[1],
                         w = Object(l.useState)(null),
                         N = Object(d.a)(w, 2),
                         O = N[0],
                         D = N[1],
-                        P = Object(l.useState)(0),
-                        k = Object(d.a)(P, 2),
-                        T = k[0],
-                        I = k[1],
+                        k = Object(l.useState)(0),
+                        T = Object(d.a)(k, 2),
+                        P = T[0],
+                        I = T[1],
                         C = Object(l.useState)(),
-                        A = Object(d.a)(C, 2),
-                        F = A[0],
-                        R = A[1],
-                        j = Object(l.useState)(),
-                        M = Object(d.a)(j, 2),
+                        F = Object(d.a)(C, 2),
+                        R = F[0],
+                        j = F[1],
+                        A = Object(l.useState)(),
+                        M = Object(d.a)(A, 2),
                         L = M[0],
                         U = M[1],
                         G = Object(l.useState)("/dataset"),
-                        q = Object(d.a)(G, 2),
-                        K = q[0],
-                        z = q[1];
+                        B = Object(d.a)(G, 2),
+                        K = B[0],
+                        z = B[1];
                     Object(l.useEffect)((function() {
                         S(Object(u.a)(Object(u.a)({}, x), {}, {
                             resources: O || x.resources
                         }))
-                    }), [T]);
-                    var X = function(e) {
+                    }), [P]);
+                    var V = function(e) {
                         var a = [];
                         a = e.response ? e.response.data && e.response.data.error ? Object.keys(e.response.data.error).map((function(a) {
                             return "object" === typeof e.response.data.error[a] ? e.response.data.error[a].join("; ") : e.response.data.error[a]
-                        })) : "Something has failed. Please, try again later or contact site administrator." : e.request ? "Please, check your connection or try again later. If the issue persists, contact site administrator." : "Something has failed. Please, try again later or contact site administrator.", R(r.a.createElement(Se, {
+                        })) : "Something has failed. Please, try again later or contact site administrator." : e.request ? "Please, check your connection or try again later. If the issue persists, contact site administrator." : "Something has failed. Please, try again later or contact site administrator.", j(r.a.createElement(we, {
                             type: "error",
                             heading: "Error saving metadata",
                             message: a
                         })), window.scrollTo(0, 0)
                     };
-                    return h && v && (b(!1), B.fetchDataset(h, a, t).then((function(e) {
+                    return h && v && (b(!1), q.fetchDataset(h, a, t).then((function(e) {
                         var l = Object.assign({}, e);
-                        l.description = e.notes, y(l.id), l.parentDataset ? B.fetchDataset(l.parentDataset, a, t).then((function(e) {
+                        l.description = e.notes, y(l.id), l.parentDataset ? q.fetchDataset(l.parentDataset, a, t).then((function(e) {
                             S(Object.assign({}, x, l, {
                                 parentDatasetTitle: e.title
                             }))
-                        })).catch(X) : S(Object.assign({}, x, l))
-                    })).catch(X)), Object(l.useEffect)((function() {
+                        })).catch(V) : S(Object.assign({}, x, l))
+                    })).catch(V)), Object(l.useEffect)((function() {
                         var e = new URLSearchParams(window.location.search).get("group");
                         e && z("/organization/".concat(e))
                     }), []), r.a.createElement("div", {
                         className: "grid-container"
-                    }, r.a.createElement(xe, {
-                        currentStep: T,
+                    }, r.a.createElement(Se, {
+                        currentStep: P,
                         handleSteps: I
                     }), r.a.createElement("a", {
                         href: K
-                    }, "< Back to dashboard"), r.a.createElement(Oe, {
-                        currentStep: T
-                    }), F, 0 === T && r.a.createElement(m.d, {
+                    }, "< Back to dashboard"), r.a.createElement(De, {
+                        currentStep: P
+                    }), R, 0 === P && r.a.createElement(m.d, {
                         initialValues: x,
                         enableReinitialize: !0,
                         validateOnChange: !1,
                         validateOnBlur: !1,
                         validateOnMount: !1,
                         onSubmit: function(e) {
-                            R(), h ? B.updateDataset(h, e, a, t).then((function() {
-                                S(Object.assign({}, e)), e.saveDraft ? U(new Date) : (R(r.a.createElement(Se, {
+                            j(), h ? q.updateDataset(h, e, a, t).then((function() {
+                                S(Object.assign({}, e)), e.saveDraft ? U(new Date) : (j(r.a.createElement(we, {
                                     type: "success",
                                     heading: "Dataset saved successfully"
                                 })), I(1), window.scrollTo(0, 0))
-                            })).catch(X) : B.createDataset(e, a, t).then((function(a) {
-                                S(Object.assign({}, e)), y(a.id), e.saveDraft ? U(new Date) : (R(r.a.createElement(Se, {
+                            })).catch(V) : q.createDataset(e, a, t).then((function(a) {
+                                S(Object.assign({}, e)), y(a.id), e.saveDraft ? U(new Date) : (j(r.a.createElement(we, {
                                     type: "success",
                                     heading: "Dataset saved successfully"
                                 })), I(1), window.scrollTo(0, 0))
-                            })).catch(X)
+                            })).catch(V)
                         },
                         validate: function() {
-                            R()
+                            j()
                         },
-                        validationSchema: re
+                        validationSchema: ne
                     }, (function(e) {
                         var l = e.values,
                             i = e.handleSubmit,
                             s = e.errors,
                             c = e.setFieldValue,
                             o = e.submitForm,
                             u = e.handleChange;
-                        return r.a.createElement("div", null, s && Object.keys(s).length > 0 && r.a.createElement("div", null, r.a.createElement(Se, {
+                        return r.a.createElement("div", null, s && Object.keys(s).length > 0 && r.a.createElement("div", null, r.a.createElement(we, {
                             type: "error",
                             heading: "This form contains invalid entries",
-                            errors: we(s)
+                            errors: Ne(s)
                         })), r.a.createElement(m.c, {
                             onSubmit: i
-                        }, r.a.createElement("div", null, r.a.createElement(te, {
+                        }, r.a.createElement("div", null, r.a.createElement(le, {
                             apiKey: t,
                             apiUrl: a,
                             ownerOrg: n,
                             currentStep: 0,
                             fetchDatasetsOpts: "false",
                             values: l || {},
                             errors: s,
-                            draftSaved: L ? Ne(L) : void 0,
+                            draftSaved: L ? Oe(L) : void 0,
                             setFieldValue: c,
                             submitForm: o,
                             handleChange: u
                         }))))
-                    })), 1 === T && r.a.createElement(m.d, {
+                    })), 1 === P && r.a.createElement(m.d, {
                         initialValues: x,
                         enableReinitialize: !0,
                         validateOnChange: !1,
                         validateOnBlur: !1,
                         onSubmit: function(e) {
-                            R();
+                            j();
                             var l = x && x.id;
-                            S(Object.assign({}, x, e)), l ? B.updateDataset(l, e, a, t).then((function() {
-                                e.saveDraft ? U(new Date) : (R(r.a.createElement(Se, {
+                            S(Object.assign({}, x, e)), l ? q.updateDataset(l, e, a, t).then((function() {
+                                e.saveDraft ? U(new Date) : (j(r.a.createElement(we, {
                                     type: "success",
                                     heading: "Dataset saved successfully"
                                 })), I(2), window.scrollTo(0, 0))
-                            })).catch(X) : (R(r.a.createElement(Se, {
+                            })).catch(V) : (j(r.a.createElement(we, {
                                 type: "error",
                                 heading: "No valid metadata saved in step 1.",
                                 message: "Please complete complete step one before submitting step 2."
                             })), window.scrollTo(0, 0))
                         },
                         validate: function() {
-                            R()
+                            j()
                         },
-                        validationSchema: ve
+                        validationSchema: be
                     }, (function(e) {
                         var l = e.values,
                             i = e.handleSubmit,
                             s = e.errors,
                             c = e.setFieldValue,
                             o = e.submitForm;
-                        return r.a.createElement("div", null, s && Object.keys(s).length > 0 && r.a.createElement("div", null, r.a.createElement(Se, {
+                        return r.a.createElement("div", null, s && Object.keys(s).length > 0 && r.a.createElement("div", null, r.a.createElement(we, {
                             type: "error",
                             heading: "This form contains invalid entries",
-                            errors: we(s)
+                            errors: Ne(s)
                         })), r.a.createElement(m.c, {
                             onSubmit: i
-                        }, r.a.createElement("div", null, r.a.createElement(me, {
+                        }, r.a.createElement("div", null, r.a.createElement(pe, {
                             apiKey: t,
                             apiUrl: a,
                             ownerOrg: n,
                             currentStep: 1,
                             fetchDatasetsOpts: "false",
                             values: l || {},
                             errors: s,
-                            draftSaved: L ? Ne(L) : void 0,
+                            draftSaved: L ? Oe(L) : void 0,
                             setFieldValue: c,
                             submitForm: o,
                             handleSteps: I
                         }))))
-                    })), 2 === T && r.a.createElement(m.d, {
+                    })), 2 === P && r.a.createElement(m.d, {
                         initialValues: {
-                            resource: JSON.parse(JSON.stringify(_e)),
+                            resource: JSON.parse(JSON.stringify(xe)),
                             resources: x.resources,
                             publish: !0,
                             savedResources: 0,
                             lastSavedResource: null,
                             saveDraft: !1,
                             publishing_status: x.publishing_status
                         },
                         enableReinitialize: !0,
                         validateOnChange: !1,
                         validateOnBlur: !1,
                         onSubmit: function(e, l) {
                             var n = l.setFieldValue,
                                 i = l.setSubmitting;
-                            R();
-                            var s = JSON.stringify(_e) !== JSON.stringify(e.resource);
+                            j();
+                            var s = JSON.stringify(xe) !== JSON.stringify(e.resource);
                             if (h) {
                                 var u, d = new URL(a),
                                     m = "".concat(d.origin, "/dataset/").concat(h);
                                 switch (e.resourceAction) {
                                     case "edit":
-                                        u = B.updateResource(e.resource, a, t);
+                                        u = q.updateResource(e.resource, a, t);
                                         break;
                                     case "delete":
-                                        u = B.deleteResource(e.resource.id, a, t);
+                                        u = q.deleteResource(e.resource.id, a, t);
                                         break;
                                     default:
-                                        s && (u = B.createResource(h, e.resource, a, t))
+                                        s && (u = q.createResource(h, e.resource, a, t))
                                 }
                                 u ? u.then(function() {
                                     var l = Object(o.a)(c.a.mark((function l(r) {
                                         var s;
                                         return c.a.wrap((function(l) {
                                             for (;;) switch (l.prev = l.next) {
                                                 case 0:
@@ -2355,107 +2341,107 @@
                                                         l.next = 5;
                                                         break
                                                     }
                                                     if (!e.resource.upload) {
                                                         l.next = 4;
                                                         break
                                                     }
-                                                    return l.next = 4, B.patchDataset(h, {
+                                                    return l.next = 4, q.patchDataset(h, {
                                                         private: !1
                                                     }, a, t);
                                                 case 4:
-                                                    e.publish ? B.patchDataset(h, {
+                                                    e.publish ? q.patchDataset(h, {
                                                         publishing_status: "Published"
                                                     }, a, t).then((function(e) {
                                                         200 === e.status && window.location.replace(m)
                                                     })) : e.saveDraft ? (U(new Date), i(!1)) : (U(new Date), s = e.resources.filter((function(a) {
                                                         return a.id !== e.resource.id
-                                                    })), "delete" !== e.resourceAction && (s.push(r.data.result), n("savedResources", e.savedResources + 1), n("lastSavedResource", e.resource.name || e.resource.url)), n("resources", s), D(s), n("resource", JSON.parse(JSON.stringify(_e))), i(!1));
+                                                    })), "delete" !== e.resourceAction && (s.push(r.data.result), n("savedResources", e.savedResources + 1), n("lastSavedResource", e.resource.name || e.resource.url)), n("resources", s), D(s), n("resource", JSON.parse(JSON.stringify(xe))), i(!1));
                                                 case 5:
                                                     n("resourceAction", void 0);
                                                 case 6:
                                                 case "end":
                                                     return l.stop()
                                             }
                                         }), l)
                                     })));
                                     return function(e) {
                                         return l.apply(this, arguments)
                                     }
                                 }()).catch((function(e) {
-                                    X(e), i(!1)
-                                })) : e.publish ? B.patchDataset(h, {
+                                    V(e), i(!1)
+                                })) : e.publish ? q.patchDataset(h, {
                                     publishing_status: "Published"
                                 }, a, t).then((function(e) {
                                     200 === e.status && window.location.replace(m)
                                 })).catch((function(e) {
-                                    X(e), i(!1)
+                                    V(e), i(!1)
                                 })) : e.saveDraft ? (U(new Date), i(!1)) : i(!1)
-                            } else R(r.a.createElement(Se, {
+                            } else j(r.a.createElement(we, {
                                 type: "error",
                                 heading: "No valid metadata saved in previous steps.",
                                 message: "Please complete previous steps before submitting resource(s)."
                             }))
                         },
                         validate: function() {
-                            R()
+                            j()
                         },
-                        validationSchema: Ee,
+                        validationSchema: _e,
                         render: function(e) {
                             var a = e.values,
                                 t = e.errors,
                                 l = e.handleSubmit,
                                 n = e.setFieldValue,
                                 i = e.submitForm,
                                 s = e.isSubmitting;
                             return r.a.createElement("div", {
                                 className: ""
-                            }, t && Object.keys(t).length > 0 && r.a.createElement("div", null, r.a.createElement(Se, {
+                            }, t && Object.keys(t).length > 0 && r.a.createElement("div", null, r.a.createElement(we, {
                                 type: "error",
                                 heading: "This form contains invalid entries",
-                                errors: we(t)
+                                errors: Ne(t)
                             })), r.a.createElement(m.c, {
                                 onSubmit: l
-                            }, r.a.createElement(ye, {
+                            }, r.a.createElement(Ee, {
                                 values: a,
                                 errors: t,
-                                draftSaved: L ? Ne(L) : void 0,
+                                draftSaved: L ? Oe(L) : void 0,
                                 setFieldValue: n,
                                 submitForm: i,
                                 isSubmitting: s,
                                 handleSteps: I
                             })))
                         }
                     }))
                 },
-                Pe = function(e) {
+                Te = function(e) {
                     var a = e.apiUrl,
                         t = e.apiKey,
                         l = e.ownerOrg,
                         n = e.datasetId;
                     return r.a.createElement("div", {
                         className: "App"
-                    }, r.a.createElement(De, {
+                    }, r.a.createElement(ke, {
                         apiUrl: a,
                         apiKey: t,
                         ownerOrg: l,
                         datasetId: n
                     }))
                 };
             Boolean("localhost" === window.location.hostname || "[::1]" === window.location.hostname || window.location.hostname.match(/^127(?:\.(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)){3}$/));
-            var ke = document.getElementById("root"),
-                Te = ke.getAttribute("data-apiUrl"),
-                Ie = ke.getAttribute("data-apiKey"),
-                Ce = ke.getAttribute("data-ownerOrg"),
-                Ae = ke.getAttribute("data-datasetId");
-            i.a.render(r.a.createElement(r.a.StrictMode, null, r.a.createElement(Pe, {
-                apiUrl: Te,
-                apiKey: Ie,
-                ownerOrg: Ce,
-                datasetId: Ae
+            var Pe = document.getElementById("root"),
+                Ie = Pe.getAttribute("data-apiUrl"),
+                Ce = Pe.getAttribute("data-apiKey"),
+                Fe = Pe.getAttribute("data-ownerOrg"),
+                Re = Pe.getAttribute("data-datasetId");
+            i.a.render(r.a.createElement(r.a.StrictMode, null, r.a.createElement(Te, {
+                apiUrl: Ie,
+                apiKey: Ce,
+                ownerOrg: Fe,
+                datasetId: Re
             })), document.getElementById("root")), "serviceWorker" in navigator && navigator.serviceWorker.ready.then((function(e) {
                 e.unregister()
             })).catch((function(e) {
                 console.error(e.message)
             }))
         }
     },
```

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/public/js/runtime-main.js` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/public/js/runtime-main.js`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/package/read_base.html` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/package/read_base.html`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/templates/package/search.html` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/templates/package/search.html`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext/dcat_usmetadata/tests/test_plugin.py` & `ckanext-dcat_usmetadata-0.4.2/ckanext/dcat_usmetadata/tests/test_plugin.py`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/PKG-INFO` & `ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ckanext-dcat-usmetadata
-Version: 0.4.1
+Version: 0.4.2
 Summary: DCAT USMetadata Form App for CKAN
 Home-page: https://github.com/GSA/ckanext-dcat_usmetadata
 Author: Data.gov
 Author-email: datagovhelp@gsa.gov
 License: AGPL
 Keywords: CKAN
 Platform: UNKNOWN
```

### Comparing `ckanext-dcat_usmetadata-0.4.1/ckanext_dcat_usmetadata.egg-info/SOURCES.txt` & `ckanext-dcat_usmetadata-0.4.2/ckanext_dcat_usmetadata.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/requirements.txt` & `ckanext-dcat_usmetadata-0.4.2/requirements.txt`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/setup.cfg` & `ckanext-dcat_usmetadata-0.4.2/setup.cfg`

 * *Files identical despite different names*

### Comparing `ckanext-dcat_usmetadata-0.4.1/setup.py` & `ckanext-dcat_usmetadata-0.4.2/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 
 setup(
     name='''ckanext-dcat_usmetadata''',
 
     # Versions should comply with PEP440.  For a discussion on single-sourcing
     # the version across setup.py and the project code, see
     # http://packaging.python.org/en/latest/tutorial.html#version
-    version='0.4.1',
+    version='0.4.2',
 
     description='''DCAT USMetadata Form App for CKAN''',
     long_description=long_description,
     long_description_content_type='text/markdown',
 
     # The project's main homepage.
     url='https://github.com/GSA/ckanext-dcat_usmetadata',
```

