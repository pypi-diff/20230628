# Comparing `tmp/cyclonedx_python_lib-4.0.0rc3.tar.gz` & `tmp/cyclonedx_python_lib-4.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cyclonedx_python_lib-4.0.0rc3.tar", max compression
+gzip compressed data, was "cyclonedx_python_lib-4.0.1.tar", max compression
```

## Comparing `cyclonedx_python_lib-4.0.0rc3.tar` & `cyclonedx_python_lib-4.0.1.tar`

### file list

```diff
@@ -1,183 +1,185 @@
--rw-r--r--   0        0        0    11357 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/LICENSE
--rw-r--r--   0        0        0     4150 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/README.md
--rw-r--r--   0        0        0      697 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/__init__.py
--rw-r--r--   0        0        0      791 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/__init__.py
--rw-r--r--   0        0        0     1501 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/factory.py
--rw-r--r--   0        0        0     2290 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/model.py
--rw-r--r--   0        0        0     1101 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/output.py
--rw-r--r--   0        0        0      699 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/factory/__init__.py
--rw-r--r--   0        0        0     3875 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/factory/license.py
--rw-r--r--   0        0        0    43349 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/__init__.py
--rw-r--r--   0        0        0    21188 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/bom.py
--rw-r--r--   0        0        0     1840 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/bom_ref.py
--rw-r--r--   0        0        0    42826 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/component.py
--rw-r--r--   0        0        0     3575 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/dependency.py
--rw-r--r--   0        0        0     3585 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/impact_analysis.py
--rw-r--r--   0        0        0     6975 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/issue.py
--rw-r--r--   0        0        0     8829 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/release_note.py
--rw-r--r--   0        0        0    12358 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/service.py
--rw-r--r--   0        0        0    41904 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/vulnerability.py
--rw-r--r--   0        0        0     3534 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/output/__init__.py
--rw-r--r--   0        0        0     3481 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/output/json.py
--rw-r--r--   0        0        0     3143 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/output/xml.py
--rw-r--r--   0        0        0     1817 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/parser/__init__.py
--rw-r--r--   0        0        0      153 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/py.typed
--rw-r--r--   0        0        0     1062 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/__init__.py
--rw-r--r--   0        0        0    13593 2023-03-16 23:49:32.376059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.0.xsd
--rw-r--r--   0        0        0    39460 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.1.xsd
--rw-r--r--   0        0        0    36866 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2-strict.schema.json
--rw-r--r--   0        0        0    35999 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2.schema.json
--rw-r--r--   0        0        0    76122 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2.xsd
--rw-r--r--   0        0        0    37056 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2b.schema.json
--rw-r--r--   0        0        0    40148 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3-strict.schema.json
--rw-r--r--   0        0        0    23176 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3.proto
--rw-r--r--   0        0        0    39090 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3.schema.json
--rw-r--r--   0        0        0    88359 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3.xsd
--rw-r--r--   0        0        0    40239 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3a.schema.json
--rw-r--r--   0        0        0    72250 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.4.schema.json
--rw-r--r--   0        0        0   133591 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.4.xsd
--rw-r--r--   0        0        0     9063 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/bom-descriptor-0.9.xsd
--rw-r--r--   0        0        0     8233 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/bom-descriptor-1.0.xsd
--rw-r--r--   0        0        0     3146 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/dependency-graph-1.0.xsd
--rw-r--r--   0        0        0     6380 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/vulnerability-1.0-SNAPSHOT.schema.json
--rw-r--r--   0        0        0    14195 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/vulnerability-1.0.xsd
--rw-r--r--   0        0        0     1967 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/schema.py
--rw-r--r--   0        0        0    10481 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/spdx.schema.json
--rw-r--r--   0        0        0   125048 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/spdx.xsd
--rw-r--r--   0        0        0     2313 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/serialization/__init__.py
--rw-r--r--   0        0        0     2071 2023-03-16 23:49:32.380059 cyclonedx_python_lib-4.0.0rc3/cyclonedx/spdx.py
--rw-r--r--   0        0        0     2653 2023-03-16 23:49:53.183993 cyclonedx_python_lib-4.0.0rc3/pyproject.toml
--rw-r--r--   0        0        0     1035 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/__init__.py
--rw-r--r--   0        0        0     6034 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/base.py
--rw-r--r--   0        0        0    23220 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/data.py
--rw-r--r--   0        0        0      391 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/README.md
--rw-r--r--   0        0        0     1542 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_dependencies.json
--rw-r--r--   0        0        0     1555 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_dependencies_component.json
--rw-r--r--   0        0        0      630 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_external_references.json
--rw-r--r--   0        0        0     1562 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_issue_275_components.json
--rw-r--r--   0        0        0     1409 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_issue_328_components.json
--rw-r--r--   0        0        0     2044 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_services_complex.json
--rw-r--r--   0        0        0     3752 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_services_nested.json
--rw-r--r--   0        0        0     1031 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_services_simple.json
--rw-r--r--   0        0        0      867 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools.json
--rw-r--r--   0        0        0     6998 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools_complete.json
--rw-r--r--   0        0        0      840 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools_no_version.json
--rw-r--r--   0        0        0      932 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools_with_cpe.json
--rw-r--r--   0        0        0     1057 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_toml_1.json
--rw-r--r--   0        0        0     7869 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_with_full_metadata.json
--rw-r--r--   0        0        0     1729 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_dependencies.json
--rw-r--r--   0        0        0     1742 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_dependencies_component.json
--rw-r--r--   0        0        0      793 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_external_references.json
--rw-r--r--   0        0        0     1562 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_issue_275_components.json
--rw-r--r--   0        0        0     1409 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_issue_328_components.json
--rw-r--r--   0        0        0     2407 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_services_complex.json
--rw-r--r--   0        0        0     4115 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_services_nested.json
--rw-r--r--   0        0        0     1031 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_services_simple.json
--rw-r--r--   0        0        0      867 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools.json
--rw-r--r--   0        0        0     8197 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools_complete.json
--rw-r--r--   0        0        0      840 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools_no_version.json
--rw-r--r--   0        0        0      932 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools_with_cpe.json
--rw-r--r--   0        0        0     1244 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_toml_1.json
--rw-r--r--   0        0        0     9595 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_with_full_metadata.json
--rw-r--r--   0        0        0     2835 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_dependencies.json
--rw-r--r--   0        0        0     2848 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_dependencies_component.json
--rw-r--r--   0        0        0     1899 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_external_references.json
--rw-r--r--   0        0        0     2668 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_issue_275_components.json
--rw-r--r--   0        0        0     2515 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_issue_328_components.json
--rw-r--r--   0        0        0     5326 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_services_complex.json
--rw-r--r--   0        0        0     7034 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_services_nested.json
--rw-r--r--   0        0        0     2137 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_services_simple.json
--rw-r--r--   0        0        0     1973 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools.json
--rw-r--r--   0        0        0    11062 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_complete.json
--rw-r--r--   0        0        0     1925 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_no_version.json
--rw-r--r--   0        0        0     2038 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_with_cpe.json
--rw-r--r--   0        0        0     3786 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_with_release_notes.json
--rw-r--r--   0        0        0     5090 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_with_vulnerabilities.json
--rw-r--r--   0        0        0     2350 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_toml_1.json
--rw-r--r--   0        0        0    12460 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_with_full_metadata.json
--rw-r--r--   0        0        0      126 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_empty.xml
--rw-r--r--   0        0        0      726 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_issue_275_components.xml
--rw-r--r--   0        0        0      852 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_issue_328_components.xml
--rw-r--r--   0        0        0      381 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_setuptools.xml
--rw-r--r--   0        0        0     1437 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_setuptools_complete.xml
--rw-r--r--   0        0        0      359 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_setuptools_no_version.xml
--rw-r--r--   0        0        0      453 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_setuptools_with_cpe.xml
--rw-r--r--   0        0        0      520 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_toml_hashes_and_references.xml
--rw-r--r--   0        0        0     1195 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_dependencies.xml
--rw-r--r--   0        0        0      192 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_empty.xml
--rw-r--r--   0        0        0      492 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_external_references.xml
--rw-r--r--   0        0        0      808 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_issue_275_components.xml
--rw-r--r--   0        0        0      843 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_issue_328_components.xml
--rw-r--r--   0        0        0      562 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools.xml
--rw-r--r--   0        0        0     6103 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_complete.xml
--rw-r--r--   0        0        0      533 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_no_version.xml
--rw-r--r--   0        0        0      634 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_with_cpe.xml
--rw-r--r--   0        0        0     2505 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_with_vulnerabilities.xml
--rw-r--r--   0        0        0      842 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_toml_hashes_and_references.xml
--rw-r--r--   0        0        0     1807 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_dependencies.xml
--rw-r--r--   0        0        0     1807 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_dependencies_component.xml
--rw-r--r--   0        0        0      777 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_external_references.xml
--rw-r--r--   0        0        0     1828 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_issue_275_components.xml
--rw-r--r--   0        0        0     1689 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_issue_328_components.xml
--rw-r--r--   0        0        0     2528 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_services_complex.xml
--rw-r--r--   0        0        0     4767 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_services_nested.xml
--rw-r--r--   0        0        0     1181 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_services_simple.xml
--rw-r--r--   0        0        0     1017 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools.xml
--rw-r--r--   0        0        0     8381 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_complete.xml
--rw-r--r--   0        0        0      981 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_no_version.xml
--rw-r--r--   0        0        0     1089 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_with_cpe.xml
--rw-r--r--   0        0        0     2960 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_with_vulnerabilities.xml
--rw-r--r--   0        0        0     1250 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_toml_hashes_and_references.xml
--rw-r--r--   0        0        0     9464 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_with_full_metadata.xml
--rw-r--r--   0        0        0     1982 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_dependencies.xml
--rw-r--r--   0        0        0     1982 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_dependencies_component.xml
--rw-r--r--   0        0        0      928 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_external_references.xml
--rw-r--r--   0        0        0     1828 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_issue_275_components.xml
--rw-r--r--   0        0        0     1689 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_issue_328_components.xml
--rw-r--r--   0        0        0     2863 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_services_complex.xml
--rw-r--r--   0        0        0     5101 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_services_nested.xml
--rw-r--r--   0        0        0     1181 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_services_simple.xml
--rw-r--r--   0        0        0     1017 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools.xml
--rw-r--r--   0        0        0     9530 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_complete.xml
--rw-r--r--   0        0        0      981 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_no_version.xml
--rw-r--r--   0        0        0     1089 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_with_cpe.xml
--rw-r--r--   0        0        0     2960 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_with_vulnerabilities.xml
--rw-r--r--   0        0        0     1425 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_toml_hashes_and_references.xml
--rw-r--r--   0        0        0    11093 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_with_full_metadata.xml
--rw-r--r--   0        0        0     3426 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_dependencies.xml
--rw-r--r--   0        0        0     3426 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_dependencies_component.xml
--rw-r--r--   0        0        0     2367 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_external_references.xml
--rw-r--r--   0        0        0     3272 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_issue_275_components.xml
--rw-r--r--   0        0        0     3128 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_issue_328_components.xml
--rw-r--r--   0        0        0     6523 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_services_complex.xml
--rw-r--r--   0        0        0     8763 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_services_nested.xml
--rw-r--r--   0        0        0     2628 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_services_simple.xml
--rw-r--r--   0        0        0     2461 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools.xml
--rw-r--r--   0        0        0    13121 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_complete.xml
--rw-r--r--   0        0        0     2402 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_no_version.xml
--rw-r--r--   0        0        0     2533 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_with_cpe.xml
--rw-r--r--   0        0        0     4678 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_with_release_notes.xml
--rw-r--r--   0        0        0     7006 2023-03-16 23:49:32.384059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_with_vulnerabilities.xml
--rw-r--r--   0        0        0     2869 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_toml_hashes_and_references.xml
--rw-r--r--   0        0        0    14684 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_with_full_metadata.xml
--rw-r--r--   0        0        0    98508 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/webgoat-6.1.xml
--rw-r--r--   0        0        0     2977 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_component.py
--rw-r--r--   0        0        0    19632 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_deserialize_json.py
--rw-r--r--   0        0        0    33489 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_deserialize_xml.py
--rw-r--r--   0        0        0     3295 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_e2e_environment.py
--rw-r--r--   0        0        0     6050 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_factory_license.py
--rw-r--r--   0        0        0    22687 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model.py
--rw-r--r--   0        0        0     8112 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_bom.py
--rw-r--r--   0        0        0     1278 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_bom_ref.py
--rw-r--r--   0        0        0    18882 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_component.py
--rw-r--r--   0        0        0     1817 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_dependency.py
--rw-r--r--   0        0        0     4054 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_issue.py
--rw-r--r--   0        0        0     2777 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_release_note.py
--rw-r--r--   0        0        0     3750 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_service.py
--rw-r--r--   0        0        0    14825 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_model_vulnerability.py
--rw-r--r--   0        0        0     1880 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_output_generic.py
--rw-r--r--   0        0        0    17637 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_output_json.py
--rw-r--r--   0        0        0    23296 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_output_xml.py
--rw-r--r--   0        0        0     1706 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_real_world_examples.py
--rw-r--r--   0        0        0     2862 2023-03-16 23:49:32.388059 cyclonedx_python_lib-4.0.0rc3/tests/test_spdx.py
--rw-r--r--   0        0        0     6085 1970-01-01 00:00:00.000000 cyclonedx_python_lib-4.0.0rc3/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/LICENSE
+-rw-r--r--   0        0        0     4150 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/README.md
+-rw-r--r--   0        0        0      697 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/__init__.py
+-rw-r--r--   0        0        0      791 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/exception/__init__.py
+-rw-r--r--   0        0        0     1501 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/exception/factory.py
+-rw-r--r--   0        0        0     2290 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/exception/model.py
+-rw-r--r--   0        0        0     1101 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/exception/output.py
+-rw-r--r--   0        0        0      699 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/factory/__init__.py
+-rw-r--r--   0        0        0     3875 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/factory/license.py
+-rw-r--r--   0        0        0    43349 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/__init__.py
+-rw-r--r--   0        0        0    21230 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/bom.py
+-rw-r--r--   0        0        0     1840 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/bom_ref.py
+-rw-r--r--   0        0        0    42810 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/component.py
+-rw-r--r--   0        0        0     3566 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/dependency.py
+-rw-r--r--   0        0        0     3585 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/impact_analysis.py
+-rw-r--r--   0        0        0     6975 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/issue.py
+-rw-r--r--   0        0        0     8829 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/release_note.py
+-rw-r--r--   0        0        0    12358 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/service.py
+-rw-r--r--   0        0        0    41920 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/model/vulnerability.py
+-rw-r--r--   0        0        0     3534 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/output/__init__.py
+-rw-r--r--   0        0        0     3481 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/output/json.py
+-rw-r--r--   0        0        0     3143 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/output/xml.py
+-rw-r--r--   0        0        0     1817 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/parser/__init__.py
+-rw-r--r--   0        0        0      153 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/py.typed
+-rw-r--r--   0        0        0     1062 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/__init__.py
+-rw-r--r--   0        0        0    13593 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.0.xsd
+-rw-r--r--   0        0        0    39460 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.1.xsd
+-rw-r--r--   0        0        0    36866 2023-06-28 15:25:43.477215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2-strict.schema.json
+-rw-r--r--   0        0        0    35999 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2.schema.json
+-rw-r--r--   0        0        0    76122 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2.xsd
+-rw-r--r--   0        0        0    37056 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2b.schema.json
+-rw-r--r--   0        0        0    40148 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3-strict.schema.json
+-rw-r--r--   0        0        0    23176 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3.proto
+-rw-r--r--   0        0        0    39090 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3.schema.json
+-rw-r--r--   0        0        0    88359 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3.xsd
+-rw-r--r--   0        0        0    40239 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3a.schema.json
+-rw-r--r--   0        0        0    72250 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.4.schema.json
+-rw-r--r--   0        0        0   133591 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.4.xsd
+-rw-r--r--   0        0        0     9063 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/bom-descriptor-0.9.xsd
+-rw-r--r--   0        0        0     8233 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/bom-descriptor-1.0.xsd
+-rw-r--r--   0        0        0     3146 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/dependency-graph-1.0.xsd
+-rw-r--r--   0        0        0     6380 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/vulnerability-1.0-SNAPSHOT.schema.json
+-rw-r--r--   0        0        0    14195 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/vulnerability-1.0.xsd
+-rw-r--r--   0        0        0     1967 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/schema.py
+-rw-r--r--   0        0        0    10481 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/spdx.schema.json
+-rw-r--r--   0        0        0   125048 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/schema/spdx.xsd
+-rw-r--r--   0        0        0     2291 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/serialization/__init__.py
+-rw-r--r--   0        0        0     2071 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/cyclonedx/spdx.py
+-rw-r--r--   0        0        0     2512 2023-06-28 15:26:06.781432 cyclonedx_python_lib-4.0.1/pyproject.toml
+-rw-r--r--   0        0        0     1035 2023-06-28 15:25:43.481215 cyclonedx_python_lib-4.0.1/tests/__init__.py
+-rw-r--r--   0        0        0     6034 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/base.py
+-rw-r--r--   0        0        0    24157 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/data.py
+-rw-r--r--   0        0        0      391 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/README.md
+-rw-r--r--   0        0        0     1542 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_dependencies.json
+-rw-r--r--   0        0        0     1555 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_dependencies_component.json
+-rw-r--r--   0        0        0      630 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_external_references.json
+-rw-r--r--   0        0        0     1562 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_issue_275_components.json
+-rw-r--r--   0        0        0     1409 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_issue_328_components.json
+-rw-r--r--   0        0        0     2044 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_services_complex.json
+-rw-r--r--   0        0        0     3752 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_services_nested.json
+-rw-r--r--   0        0        0     1031 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_services_simple.json
+-rw-r--r--   0        0        0      867 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools.json
+-rw-r--r--   0        0        0     6998 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools_complete.json
+-rw-r--r--   0        0        0      840 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools_no_version.json
+-rw-r--r--   0        0        0      932 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools_with_cpe.json
+-rw-r--r--   0        0        0     1057 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_toml_1.json
+-rw-r--r--   0        0        0     7869 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_with_full_metadata.json
+-rw-r--r--   0        0        0     1729 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_dependencies.json
+-rw-r--r--   0        0        0     1742 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_dependencies_component.json
+-rw-r--r--   0        0        0      793 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_external_references.json
+-rw-r--r--   0        0        0     1562 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_issue_275_components.json
+-rw-r--r--   0        0        0     1409 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_issue_328_components.json
+-rw-r--r--   0        0        0     2407 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_services_complex.json
+-rw-r--r--   0        0        0     4115 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_services_nested.json
+-rw-r--r--   0        0        0     1031 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_services_simple.json
+-rw-r--r--   0        0        0      867 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools.json
+-rw-r--r--   0        0        0     8197 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools_complete.json
+-rw-r--r--   0        0        0      840 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools_no_version.json
+-rw-r--r--   0        0        0      932 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools_with_cpe.json
+-rw-r--r--   0        0        0     1244 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_toml_1.json
+-rw-r--r--   0        0        0     9595 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_with_full_metadata.json
+-rw-r--r--   0        0        0     2835 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_dependencies.json
+-rw-r--r--   0        0        0     2848 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_dependencies_component.json
+-rw-r--r--   0        0        0     1899 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_external_references.json
+-rw-r--r--   0        0        0     2668 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_issue_275_components.json
+-rw-r--r--   0        0        0     2515 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_issue_328_components.json
+-rw-r--r--   0        0        0     5326 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_services_complex.json
+-rw-r--r--   0        0        0     7034 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_services_nested.json
+-rw-r--r--   0        0        0     2137 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_services_simple.json
+-rw-r--r--   0        0        0     1973 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools.json
+-rw-r--r--   0        0        0    11062 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_complete.json
+-rw-r--r--   0        0        0     1925 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_no_version.json
+-rw-r--r--   0        0        0     2038 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_with_cpe.json
+-rw-r--r--   0        0        0     3786 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_with_release_notes.json
+-rw-r--r--   0        0        0     5090 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_with_vulnerabilities.json
+-rw-r--r--   0        0        0     2350 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_toml_1.json
+-rw-r--r--   0        0        0     1582 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_with_dependencies_hanging.json
+-rw-r--r--   0        0        0    12460 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_with_full_metadata.json
+-rw-r--r--   0        0        0      126 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_empty.xml
+-rw-r--r--   0        0        0      726 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_issue_275_components.xml
+-rw-r--r--   0        0        0      852 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_issue_328_components.xml
+-rw-r--r--   0        0        0      381 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_setuptools.xml
+-rw-r--r--   0        0        0     1437 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_setuptools_complete.xml
+-rw-r--r--   0        0        0      359 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_setuptools_no_version.xml
+-rw-r--r--   0        0        0      453 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_setuptools_with_cpe.xml
+-rw-r--r--   0        0        0      520 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_toml_hashes_and_references.xml
+-rw-r--r--   0        0        0     1195 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_dependencies.xml
+-rw-r--r--   0        0        0      192 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_empty.xml
+-rw-r--r--   0        0        0      492 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_external_references.xml
+-rw-r--r--   0        0        0      808 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_issue_275_components.xml
+-rw-r--r--   0        0        0      843 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_issue_328_components.xml
+-rw-r--r--   0        0        0      562 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools.xml
+-rw-r--r--   0        0        0     6103 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_complete.xml
+-rw-r--r--   0        0        0      533 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_no_version.xml
+-rw-r--r--   0        0        0      634 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_with_cpe.xml
+-rw-r--r--   0        0        0     2505 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_with_vulnerabilities.xml
+-rw-r--r--   0        0        0      842 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_toml_hashes_and_references.xml
+-rw-r--r--   0        0        0     1807 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_dependencies.xml
+-rw-r--r--   0        0        0     1807 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_dependencies_component.xml
+-rw-r--r--   0        0        0      777 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_external_references.xml
+-rw-r--r--   0        0        0     1828 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_issue_275_components.xml
+-rw-r--r--   0        0        0     1689 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_issue_328_components.xml
+-rw-r--r--   0        0        0     2528 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_services_complex.xml
+-rw-r--r--   0        0        0     4767 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_services_nested.xml
+-rw-r--r--   0        0        0     1181 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_services_simple.xml
+-rw-r--r--   0        0        0     1017 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools.xml
+-rw-r--r--   0        0        0     8381 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_complete.xml
+-rw-r--r--   0        0        0      981 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_no_version.xml
+-rw-r--r--   0        0        0     1089 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_with_cpe.xml
+-rw-r--r--   0        0        0     2960 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_with_vulnerabilities.xml
+-rw-r--r--   0        0        0     1250 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_toml_hashes_and_references.xml
+-rw-r--r--   0        0        0     9464 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_with_full_metadata.xml
+-rw-r--r--   0        0        0     1982 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_dependencies.xml
+-rw-r--r--   0        0        0     1982 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_dependencies_component.xml
+-rw-r--r--   0        0        0      928 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_external_references.xml
+-rw-r--r--   0        0        0     1828 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_issue_275_components.xml
+-rw-r--r--   0        0        0     1689 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_issue_328_components.xml
+-rw-r--r--   0        0        0     2863 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_services_complex.xml
+-rw-r--r--   0        0        0     5101 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_services_nested.xml
+-rw-r--r--   0        0        0     1181 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_services_simple.xml
+-rw-r--r--   0        0        0     1017 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools.xml
+-rw-r--r--   0        0        0     9530 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_complete.xml
+-rw-r--r--   0        0        0      981 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_no_version.xml
+-rw-r--r--   0        0        0     1089 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_with_cpe.xml
+-rw-r--r--   0        0        0     2960 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_with_vulnerabilities.xml
+-rw-r--r--   0        0        0     1425 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_toml_hashes_and_references.xml
+-rw-r--r--   0        0        0    11093 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_with_full_metadata.xml
+-rw-r--r--   0        0        0     3426 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_dependencies.xml
+-rw-r--r--   0        0        0     3426 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_dependencies_component.xml
+-rw-r--r--   0        0        0     2367 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_external_references.xml
+-rw-r--r--   0        0        0     3272 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_issue_275_components.xml
+-rw-r--r--   0        0        0     3128 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_issue_328_components.xml
+-rw-r--r--   0        0        0     6523 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_services_complex.xml
+-rw-r--r--   0        0        0     8763 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_services_nested.xml
+-rw-r--r--   0        0        0     2628 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_services_simple.xml
+-rw-r--r--   0        0        0     2461 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools.xml
+-rw-r--r--   0        0        0    13121 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_complete.xml
+-rw-r--r--   0        0        0     2402 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_no_version.xml
+-rw-r--r--   0        0        0     2533 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_with_cpe.xml
+-rw-r--r--   0        0        0     4678 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_with_release_notes.xml
+-rw-r--r--   0        0        0     7006 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_with_vulnerabilities.xml
+-rw-r--r--   0        0        0     2869 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_toml_hashes_and_references.xml
+-rw-r--r--   0        0        0     1776 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_with_dependencies_hanging.xml
+-rw-r--r--   0        0        0    14684 2023-06-28 15:25:43.485215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_with_full_metadata.xml
+-rw-r--r--   0        0        0    98508 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/webgoat-6.1.xml
+-rw-r--r--   0        0        0     2961 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_component.py
+-rw-r--r--   0        0        0    19632 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_deserialize_json.py
+-rw-r--r--   0        0        0    33041 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_deserialize_xml.py
+-rw-r--r--   0        0        0     3295 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_e2e_environment.py
+-rw-r--r--   0        0        0     6050 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_factory_license.py
+-rw-r--r--   0        0        0    22687 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model.py
+-rw-r--r--   0        0        0     8112 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_bom.py
+-rw-r--r--   0        0        0     1278 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_bom_ref.py
+-rw-r--r--   0        0        0    18882 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_component.py
+-rw-r--r--   0        0        0     1817 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_dependency.py
+-rw-r--r--   0        0        0     4054 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_issue.py
+-rw-r--r--   0        0        0     2777 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_release_note.py
+-rw-r--r--   0        0        0     3750 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_service.py
+-rw-r--r--   0        0        0    14825 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_model_vulnerability.py
+-rw-r--r--   0        0        0     1880 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_output_generic.py
+-rw-r--r--   0        0        0    18099 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_output_json.py
+-rw-r--r--   0        0        0    23276 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_output_xml.py
+-rw-r--r--   0        0        0     1706 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_real_world_examples.py
+-rw-r--r--   0        0        0     2862 2023-06-28 15:25:43.489215 cyclonedx_python_lib-4.0.1/tests/test_spdx.py
+-rw-r--r--   0        0        0     5831 1970-01-01 00:00:00.000000 cyclonedx_python_lib-4.0.1/PKG-INFO
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/LICENSE` & `cyclonedx_python_lib-4.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/README.md` & `cyclonedx_python_lib-4.0.1/README.md`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/exception/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/factory.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/exception/factory.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/model.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/exception/model.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/exception/output.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/exception/output.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/factory/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/factory/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/factory/license.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/factory/license.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/bom.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/bom.py`

 * *Files 1% similar despite different names*

```diff
@@ -48,15 +48,15 @@
 from .bom_ref import BomRef
 from .component import Component
 from .dependency import Dependable, Dependency
 from .service import Service
 from .vulnerability import Vulnerability
 
 if TYPE_CHECKING:
-    from packageurl import PackageURL  # type:ignore[import]
+    from packageurl import PackageURL
 
 
 @serializable.serializable_class
 class BomMetaData:
     """
     This is our internal representation of the metadata complex type within the CycloneDX standard.
 
@@ -558,22 +558,23 @@
 
         dependency_diff = all_dependency_bom_refs - all_bom_refs
         if len(dependency_diff) > 0:
             raise UnknownComponentDependencyException(
                 f'One or more Components have Dependency references to Components/Services that are not known in this '
                 f'BOM. They are: {dependency_diff}')
 
-        # 2. Dependencies should exist for the Component this BOM is describing, if one is set
-        if self.metadata.component and filter(
-            lambda _d: _d.ref == self.metadata.component.bom_ref, self.dependencies  # type: ignore[arg-type]
-        ):
+        # 2. if root component is set: dependencies should exist for the Component this BOM is describing
+        if self.metadata.component and not any(map(
+            lambda d: d.ref == self.metadata.component.bom_ref and len(d.dependencies) > 0,  # type: ignore[union-attr]
+            self.dependencies
+        )):
             warnings.warn(
                 f'The Component this BOM is describing {self.metadata.component.purl} has no defined dependencies '
-                f'which means the Dependency Graph is incomplete - you should add direct dependencies to this Component'
-                f'to complete the Dependency Graph data.',
+                f'which means the Dependency Graph is incomplete - you should add direct dependencies to this '
+                f'"root" Component to complete the Dependency Graph data.',
                 UserWarning
             )
 
         return True
 
     def __eq__(self, other: object) -> bool:
         if isinstance(other, Bom):
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/bom_ref.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/bom_ref.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/component.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/component.py`

 * *Files 0% similar despite different names*

```diff
@@ -21,15 +21,15 @@
 from enum import Enum
 from os.path import exists
 from typing import Any, Iterable, Optional, Set, Union
 from uuid import uuid4
 
 # See https://github.com/package-url/packageurl-python/issues/65
 import serializable
-from packageurl import PackageURL  # type: ignore
+from packageurl import PackageURL
 from sortedcontainers import SortedSet
 
 from ..exception.model import NoPropertiesProvidedException
 from ..schema.schema import (
     SchemaVersion1Dot0,
     SchemaVersion1Dot1,
     SchemaVersion1Dot2,
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/dependency.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/dependency.py`

 * *Files 4% similar despite different names*

```diff
@@ -54,15 +54,15 @@
 
     .. note::
         See https://cyclonedx.org/docs/1.4/xml/#type_dependencyType
     """
 
     def __init__(self, ref: BomRef, dependencies: Optional[Iterable["Dependency"]] = None) -> None:
         self.ref = ref
-        self.dependencies = SortedSet(dependencies) or SortedSet()
+        self.dependencies = SortedSet(dependencies or [])
 
     @property  # type: ignore[misc]
     @serializable.type_mapping(BomRefHelper)
     @serializable.xml_attribute()
     def ref(self) -> BomRef:
         return self._ref
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/impact_analysis.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/impact_analysis.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/issue.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/issue.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/release_note.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/release_note.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/service.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/service.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/model/vulnerability.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/model/vulnerability.py`

 * *Files 0% similar despite different names*

```diff
@@ -540,15 +540,15 @@
         backport some of the changes for pre-1.4.
 
         Returns:
             `str`
         """
         if self == VulnerabilityScoreSource.OWASP:
             return 'OWASP Risk'
-        return self.value
+        return self.value  # type: ignore
 
 
 class VulnerabilitySeverity(str, Enum):
     """
     Class that defines the permissible severities for a Vulnerability.
 
     .. note::
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/output/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/output/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/output/json.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/output/json.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/output/xml.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/output/xml.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/parser/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/parser/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.0.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.0.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.1.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.1.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2-strict.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2-strict.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.2b.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.2b.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3-strict.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3-strict.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3.proto` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3.proto`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.3a.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.3a.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.4.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.4.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/bom-1.4.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/bom-1.4.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/bom-descriptor-0.9.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/bom-descriptor-0.9.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/bom-descriptor-1.0.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/bom-descriptor-1.0.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/dependency-graph-1.0.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/dependency-graph-1.0.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/vulnerability-1.0-SNAPSHOT.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/vulnerability-1.0-SNAPSHOT.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/ext/vulnerability-1.0.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/ext/vulnerability-1.0.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/schema.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/schema.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/spdx.schema.json` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/spdx.schema.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/schema/spdx.xsd` & `cyclonedx_python_lib-4.0.1/cyclonedx/schema/spdx.xsd`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/serialization/__init__.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/serialization/__init__.py`

 * *Files 3% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 """
 Set of helper classes for use with ``serializable`` when conducting (de-)serialization.
 """
 
 from uuid import UUID
 
 # See https://github.com/package-url/packageurl-python/issues/65
-from packageurl import PackageURL  # type: ignore
+from packageurl import PackageURL
 from serializable.helpers import BaseHelper
 
 from ..model.bom_ref import BomRef
 
 
 class BomRefHelper(BaseHelper):
 
@@ -67,12 +67,12 @@
     def serialize(cls, o: object) -> str:
         if isinstance(o, UUID):
             return o.urn
 
         raise ValueError(f'Attempt to serialize a non-UUID: {o.__class__}')
 
     @classmethod
-    def deserialize(cls, o: object) -> PackageURL:
+    def deserialize(cls, o: object) -> UUID:
         try:
             return UUID(str(o))
         except ValueError:
             raise ValueError(f'UUID string supplied ({o}) does not parse!')
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/cyclonedx/spdx.py` & `cyclonedx_python_lib-4.0.1/cyclonedx/spdx.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/pyproject.toml` & `cyclonedx_python_lib-4.0.1/pyproject.toml`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "cyclonedx-python-lib"
-version = "4.0.0-rc3"
+version = "4.0.1"
 description = "A library for producing CycloneDX SBOM (Software Bill of Materials) files."
 authors = ["Paul Horton <phorton@sonatype.com>"]
 maintainers = [
   "Paul Horton <phorton@sonatype.com>",
   "Jan Kowalleck <jan.kowalleck@gmail.com>",
 ]
 license = "Apache-2.0"
@@ -41,35 +41,33 @@
   "BOM", "SBOM", "SCA", "OWASP",
 ]
 
 [tool.poetry.urls]
 "Bug Tracker" = "https://github.com/CycloneDX/cyclonedx-python-lib/issues"
 
 [tool.poetry.dependencies]
-# ATTENTION: keep `requirements.lowest.txt` file in sync
+# ATTENTION: keep `deps.lowest.r` file in sync
 python = "^3.7"
 importlib-metadata = { version = "^3.4.0", python = "<3.8" }
-packageurl-python = ">= 0.9"
+packageurl-python = ">= 0.11"
 py-serializable = "^0.11.1"
 sortedcontainers = "^2.4.0"
 
 [tool.poetry.dev-dependencies]
 ddt = "^1.6.0"
-coverage = "^7.2.1"
+coverage = "^7.2.7"
 flake8 = "^5.0.4" # last version supporting Python 3.7
 flake8-annotations = "^2.9.1" # last version supporting Python 3.7
 flake8-bugbear = "^22.7.1"
 flake8-isort = "^4.1.2"
 isort = "^5.11.5" # last version supporting Python 3.7
 jsonschema = ">= 4.4.0"
-mypy = "^1.1.1"
+mypy = "^1.4.0"
 lxml = ">=4.7.0"
 tox = "^3.2.8"
-# `types-setuptools` need to stay in sync with version of `setuptools` - but 47 was not typed...
-types-setuptools = ">= 57.0.0"
 xmldiff = ">=2.4"
 
 [build-system]
 requires = ["poetry-core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
 
 [tool.semantic_release]
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/__init__.py` & `cyclonedx_python_lib-4.0.1/tests/__init__.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/base.py` & `cyclonedx_python_lib-4.0.1/tests/base.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/data.py` & `cyclonedx_python_lib-4.0.1/tests/data.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,15 +20,15 @@
 import base64
 from datetime import datetime, timezone
 from decimal import Decimal
 from typing import List, Optional, TypeVar
 from uuid import UUID
 
 # See https://github.com/package-url/packageurl-python/issues/65
-from packageurl import PackageURL  # type: ignore
+from packageurl import PackageURL
 
 from cyclonedx.model import (
     AttachedText,
     DataClassification,
     DataFlow,
     Encoding,
     ExternalReference,
@@ -40,15 +40,15 @@
     NoteText,
     OrganizationalContact,
     OrganizationalEntity,
     Property,
     Tool,
     XsUri,
 )
-from cyclonedx.model.bom import Bom
+from cyclonedx.model.bom import Bom, BomMetaData
 from cyclonedx.model.component import (
     Commit,
     Component,
     ComponentEvidence,
     ComponentScope,
     ComponentType,
     Copyright,
@@ -127,14 +127,43 @@
                 Dependency(ref=c2.bom_ref)
             ]),
             Dependency(ref=c2.bom_ref)
         ]
     )
 
 
+def get_bom_with_dependencies_hanging() -> Bom:
+    """
+    A bom with a RootComponent and components,
+    but no dependencies are connected to RootComponent.
+    """
+    c1 = get_component_setuptools_simple('setuptools')
+    c2 = get_component_toml_with_hashes_with_references('toml')
+    bom = Bom(
+        serial_number=UUID(hex='12345678395b41f5a30f1234567890ab'),
+        version=23,
+        metadata=BomMetaData(
+            component=Component(name='rootComponent', type=ComponentType.APPLICATION, bom_ref='root-component'),
+        ),
+        components=[c1, c2],
+        dependencies=[
+            Dependency(c1.bom_ref, [
+                Dependency(c2.bom_ref)
+            ]),
+            Dependency(c2.bom_ref)
+        ]
+    )
+    bom.metadata.tools.clear()
+    bom.metadata.timestamp = datetime(
+        year=2023, month=6, day=1,
+        hour=3, minute=3, second=7, microsecond=0,
+        tzinfo=timezone.utc)
+    return bom
+
+
 def get_bom_with_dependencies_invalid() -> Bom:
     c1 = get_component_setuptools_simple()
     return Bom(components=[c1], dependencies=[Dependency(ref=c1.bom_ref)])
 
 
 def get_bom_with_metadata_component_and_dependencies() -> Bom:
     bom = Bom(components=[get_component_toml_with_hashes_with_references()])
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_dependencies.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_dependencies.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_dependencies_component.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_dependencies_component.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_external_references.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_external_references.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_issue_275_components.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_issue_275_components.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_issue_328_components.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_issue_328_components.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_services_complex.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_services_complex.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_services_nested.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_services_nested.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_services_simple.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_services_simple.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools_complete.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools_complete.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools_no_version.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools_no_version.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_setuptools_with_cpe.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_setuptools_with_cpe.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_toml_1.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_toml_1.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.2/bom_with_full_metadata.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.2/bom_with_full_metadata.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_dependencies.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_dependencies.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_dependencies_component.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_dependencies_component.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_external_references.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_external_references.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_issue_275_components.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_issue_275_components.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_issue_328_components.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_issue_328_components.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_services_complex.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_services_complex.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_services_nested.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_services_nested.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_services_simple.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_services_simple.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools_complete.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools_complete.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools_no_version.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools_no_version.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_setuptools_with_cpe.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_setuptools_with_cpe.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_toml_1.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_toml_1.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.3/bom_with_full_metadata.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.3/bom_with_full_metadata.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_dependencies.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_dependencies.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_dependencies_component.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_dependencies_component.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_external_references.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_external_references.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_issue_275_components.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_issue_275_components.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_issue_328_components.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_issue_328_components.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_services_complex.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_services_complex.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_services_nested.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_services_nested.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_services_simple.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_services_simple.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_complete.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_complete.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_no_version.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_no_version.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_with_cpe.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_with_cpe.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_with_release_notes.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_with_release_notes.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_setuptools_with_vulnerabilities.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_setuptools_with_vulnerabilities.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_toml_1.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_toml_1.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/json/1.4/bom_with_full_metadata.json` & `cyclonedx_python_lib-4.0.1/tests/fixtures/json/1.4/bom_with_full_metadata.json`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_issue_275_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_issue_275_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_issue_328_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_issue_328_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_setuptools_complete.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_setuptools_complete.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.0/bom_toml_hashes_and_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.0/bom_toml_hashes_and_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_dependencies.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_dependencies.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_issue_275_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_issue_275_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_issue_328_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_issue_328_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_complete.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_complete.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_no_version.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_no_version.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_with_cpe.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_with_cpe.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_setuptools_with_vulnerabilities.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_setuptools_with_vulnerabilities.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.1/bom_toml_hashes_and_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.1/bom_toml_hashes_and_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_dependencies.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_dependencies.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_dependencies_component.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_dependencies_component.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_external_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_external_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_issue_275_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_issue_275_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_issue_328_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_issue_328_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_services_complex.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_services_complex.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_services_nested.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_services_nested.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_services_simple.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_services_simple.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_complete.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_complete.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_no_version.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_no_version.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_with_cpe.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_with_cpe.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_setuptools_with_vulnerabilities.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_setuptools_with_vulnerabilities.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_toml_hashes_and_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_toml_hashes_and_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.2/bom_with_full_metadata.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.2/bom_with_full_metadata.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_dependencies.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_dependencies.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_dependencies_component.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_dependencies_component.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_external_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_external_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_issue_275_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_issue_275_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_issue_328_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_issue_328_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_services_complex.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_services_complex.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_services_nested.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_services_nested.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_services_simple.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_services_simple.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_complete.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_complete.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_no_version.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_no_version.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_with_cpe.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_with_cpe.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_setuptools_with_vulnerabilities.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_setuptools_with_vulnerabilities.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_toml_hashes_and_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_toml_hashes_and_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.3/bom_with_full_metadata.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.3/bom_with_full_metadata.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_dependencies.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_dependencies.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_dependencies_component.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_dependencies_component.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_external_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_external_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_issue_275_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_issue_275_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_issue_328_components.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_issue_328_components.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_services_complex.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_services_complex.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_services_nested.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_services_nested.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_services_simple.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_services_simple.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_complete.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_complete.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_no_version.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_no_version.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_with_cpe.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_with_cpe.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_with_release_notes.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_with_release_notes.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_setuptools_with_vulnerabilities.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_setuptools_with_vulnerabilities.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_toml_hashes_and_references.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_toml_hashes_and_references.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/bom_with_full_metadata.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/bom_with_full_metadata.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/fixtures/xml/1.4/webgoat-6.1.xml` & `cyclonedx_python_lib-4.0.1/tests/fixtures/xml/1.4/webgoat-6.1.xml`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_component.py` & `cyclonedx_python_lib-4.0.1/tests/test_component.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 # SPDX-License-Identifier: Apache-2.0
 # Copyright (c) OWASP Foundation. All Rights Reserved.
 
 from os.path import dirname, join
 from unittest import TestCase
 
 # See https://github.com/package-url/packageurl-python/issues/65
-from packageurl import PackageURL  # type: ignore
+from packageurl import PackageURL
 
 from cyclonedx.model import sha1sum
 from cyclonedx.model.component import Component
 
 from .data import get_component_setuptools_simple
 
 FIXTURES_DIRECTORY = join('fixtures', 'xml', '1.4')
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_deserialize_json.py` & `cyclonedx_python_lib-4.0.1/tests/test_deserialize_json.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_deserialize_xml.py` & `cyclonedx_python_lib-4.0.1/tests/test_deserialize_xml.py`

 * *Files 2% similar despite different names*

```diff
@@ -619,74 +619,67 @@
             bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_4,
             fixture='bom_dependencies_component.xml'
         )
         mock_uuid.assert_called()
 
     @patch('cyclonedx.model.bom.uuid4', return_value=MOCK_BOM_UUID_1)
     def test_bom_v1_3_dependencies_for_bom_component(self, mock_uuid: Mock) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_3,
-                fixture='bom_dependencies_component.xml'
-            )
-            mock_uuid.assert_called()
+        self._validate_xml_bom(
+            bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_3,
+            fixture='bom_dependencies_component.xml'
+        )
+        mock_uuid.assert_called()
 
     @patch('cyclonedx.model.bom.uuid4', return_value=MOCK_BOM_UUID_1)
     def test_bom_v1_2_dependencies_for_bom_component(self, mock_uuid: Mock) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_2,
-                fixture='bom_dependencies_component.xml'
-            )
-            mock_uuid.assert_called()
+        self._validate_xml_bom(
+            bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_2,
+            fixture='bom_dependencies_component.xml'
+        )
+        mock_uuid.assert_called()
 
     @patch('cyclonedx.model.bom.uuid4', return_value=MOCK_BOM_UUID_1)
     def test_bom_v1_4_issue_275_components(self, mock_uuid: Mock) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_4,
-                fixture='bom_issue_275_components.xml'
-            )
-            mock_uuid.assert_called()
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_4,
+            fixture='bom_issue_275_components.xml'
+        )
+        mock_uuid.assert_called()
 
     @patch('cyclonedx.model.bom.uuid4', return_value=MOCK_BOM_UUID_1)
     def test_bom_v1_3_issue_275_components(self, mock_uuid: Mock) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_3,
-                fixture='bom_issue_275_components.xml'
-            )
-            mock_uuid.assert_called()
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_3,
+            fixture='bom_issue_275_components.xml'
+        )
+        mock_uuid.assert_called()
 
     @patch('cyclonedx.model.bom.uuid4', return_value=MOCK_BOM_UUID_1)
     def test_bom_v1_2_issue_275_components(self, mock_uuid: Mock) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_2,
-                fixture='bom_issue_275_components.xml'
-            )
-            mock_uuid.assert_called()
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_2,
+            fixture='bom_issue_275_components.xml'
+        )
+        mock_uuid.assert_called()
 
     @patch('cyclonedx.model.bom.uuid4', return_value=MOCK_BOM_UUID_1)
     def test_bom_v1_1_issue_275_components(self, mock_uuid: Mock) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_1,
-                fixture='bom_issue_275_components.xml'
-            )
-            mock_uuid.assert_called()
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_1,
+            fixture='bom_issue_275_components.xml'
+        )
+        mock_uuid.assert_called()
 
     @patch('cyclonedx.model.bom.uuid4', return_value=MOCK_BOM_UUID_1)
     def test_bom_v1_0_issue_275_components(self, mock_uuid: Mock) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_0,
-                fixture='bom_issue_275_components.xml'
-            )
-            mock_uuid.assert_called()
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_0,
+            fixture='bom_issue_275_components.xml'
+        )
+        mock_uuid.assert_called()
 
     # Helper methods
     def _validate_xml_bom(self, bom: Bom, schema_version: SchemaVersion, fixture: str) -> None:
         bom.metadata.timestamp = fixed_date_time()
         bom.validate()
 
         if schema_version != LATEST_SUPPORTED_SCHEMA_VERSION:
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_e2e_environment.py` & `cyclonedx_python_lib-4.0.1/tests/test_e2e_environment.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_factory_license.py` & `cyclonedx_python_lib-4.0.1/tests/test_factory_license.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model.py` & `cyclonedx_python_lib-4.0.1/tests/test_model.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_bom.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_bom.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_bom_ref.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_bom_ref.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_component.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_component.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_dependency.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_dependency.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_issue.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_issue.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_release_note.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_release_note.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_service.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_service.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_model_vulnerability.py` & `cyclonedx_python_lib-4.0.1/tests/test_model_vulnerability.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_output_generic.py` & `cyclonedx_python_lib-4.0.1/tests/test_output_generic.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_output_json.py` & `cyclonedx_python_lib-4.0.1/tests/test_output_json.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,14 +38,15 @@
     get_bom_with_component_setuptools_basic,
     get_bom_with_component_setuptools_complete,
     get_bom_with_component_setuptools_no_component_version,
     get_bom_with_component_setuptools_with_cpe,
     get_bom_with_component_setuptools_with_release_notes,
     get_bom_with_component_setuptools_with_vulnerability,
     get_bom_with_component_toml_1,
+    get_bom_with_dependencies_hanging,
     get_bom_with_dependencies_valid,
     get_bom_with_external_references,
     get_bom_with_metadata_component_and_dependencies,
     get_bom_with_nested_services,
     get_bom_with_services_complex,
     get_bom_with_services_simple,
 )
@@ -380,14 +381,23 @@
 
     def test_bom_v1_2_issue_275_components(self) -> None:
         self._validate_json_bom(
             bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_2,
             fixture='bom_issue_275_components.json'
         )
 
+    def test_bom_v1_4_warn_dependencies(self) -> None:
+        with self.assertWarns(UserWarning):
+            # this data set is expected to throw this UserWarning.
+            # that is the while point of this test!
+            self._validate_json_bom(
+                bom=get_bom_with_dependencies_hanging(), schema_version=SchemaVersion.V1_4,
+                fixture='bom_with_dependencies_hanging.json'
+            )
+
     # region Helper methods
 
     def _validate_json_bom(self, bom: Bom, schema_version: SchemaVersion, fixture: str) -> None:
         outputter = get_instance(bom=bom, output_format=OutputFormat.JSON, schema_version=schema_version)
         self.assertEqual(outputter.schema_version, schema_version)
         with open(
                 join(dirname(__file__), f'fixtures/json/{schema_version.to_version()}/{fixture}')) as expected_json:
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_output_xml.py` & `cyclonedx_python_lib-4.0.1/tests/test_output_xml.py`

 * *Files 4% similar despite different names*

```diff
@@ -37,14 +37,15 @@
     get_bom_with_component_setuptools_basic,
     get_bom_with_component_setuptools_complete,
     get_bom_with_component_setuptools_no_component_version,
     get_bom_with_component_setuptools_with_cpe,
     get_bom_with_component_setuptools_with_release_notes,
     get_bom_with_component_setuptools_with_vulnerability,
     get_bom_with_component_toml_1,
+    get_bom_with_dependencies_hanging,
     get_bom_with_dependencies_valid,
     get_bom_with_external_references,
     get_bom_with_metadata_component_and_dependencies,
     get_bom_with_nested_services,
     get_bom_with_services_complex,
     get_bom_with_services_simple,
 )
@@ -463,67 +464,68 @@
     def test_bom_v1_1_dependencies(self) -> None:
         self._validate_xml_bom(
             bom=get_bom_with_dependencies_valid(), schema_version=SchemaVersion.V1_1,
             fixture='bom_dependencies.xml'
         )
 
     def test_bom_v1_4_dependencies_for_bom_component(self) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_4,
-                fixture='bom_dependencies_component.xml'
-            )
+        self._validate_xml_bom(
+            bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_4,
+            fixture='bom_dependencies_component.xml'
+        )
 
     def test_bom_v1_3_dependencies_for_bom_component(self) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_3,
-                fixture='bom_dependencies_component.xml'
-            )
+        self._validate_xml_bom(
+            bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_3,
+            fixture='bom_dependencies_component.xml'
+        )
 
     def test_bom_v1_2_dependencies_for_bom_component(self) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_2,
-                fixture='bom_dependencies_component.xml'
-            )
+        self._validate_xml_bom(
+            bom=get_bom_with_metadata_component_and_dependencies(), schema_version=SchemaVersion.V1_2,
+            fixture='bom_dependencies_component.xml'
+        )
 
     def test_bom_v1_4_issue_275_components(self) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_4,
-                fixture='bom_issue_275_components.xml'
-            )
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_4,
+            fixture='bom_issue_275_components.xml'
+        )
 
     def test_bom_v1_3_issue_275_components(self) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_3,
-                fixture='bom_issue_275_components.xml'
-            )
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_3,
+            fixture='bom_issue_275_components.xml'
+        )
 
     def test_bom_v1_2_issue_275_components(self) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_2,
-                fixture='bom_issue_275_components.xml'
-            )
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_2,
+            fixture='bom_issue_275_components.xml'
+        )
 
     def test_bom_v1_1_issue_275_components(self) -> None:
-        with self.assertWarns(UserWarning):
-            self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_1,
-                fixture='bom_issue_275_components.xml'
-            )
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_1,
+            fixture='bom_issue_275_components.xml'
+        )
 
     def test_bom_v1_0_issue_275_components(self) -> None:
+        self._validate_xml_bom(
+            bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_0,
+            fixture='bom_issue_275_components.xml'
+        )
+
+    def test_bom_v1_4_warn_dependencies(self) -> None:
         with self.assertWarns(UserWarning):
+            # this data set is expected to throw this UserWarning.
+            # that is the while point of this test!
             self._validate_xml_bom(
-                bom=get_bom_for_issue_275_components(), schema_version=SchemaVersion.V1_0,
-                fixture='bom_issue_275_components.xml'
+                bom=get_bom_with_dependencies_hanging(), schema_version=SchemaVersion.V1_4,
+                fixture='bom_with_dependencies_hanging.xml'
             )
 
     # region Helper methods
 
     def _validate_xml_bom(self, bom: Bom, schema_version: SchemaVersion, fixture: str) -> None:
         outputter = get_instance(bom=bom, schema_version=schema_version)
         self.assertEqual(outputter.schema_version, schema_version)
```

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_real_world_examples.py` & `cyclonedx_python_lib-4.0.1/tests/test_real_world_examples.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/tests/test_spdx.py` & `cyclonedx_python_lib-4.0.1/tests/test_spdx.py`

 * *Files identical despite different names*

### Comparing `cyclonedx_python_lib-4.0.0rc3/PKG-INFO` & `cyclonedx_python_lib-4.0.1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cyclonedx-python-lib
-Version: 4.0.0rc3
+Version: 4.0.1
 Summary: A library for producing CycloneDX SBOM (Software Bill of Materials) files.
 Home-page: https://github.com/CycloneDX/cyclonedx-python-lib/#readme
 License: Apache-2.0
 Keywords: BOM,SBOM,SCA,OWASP
 Author: Paul Horton
 Author-email: phorton@sonatype.com
 Maintainer: Paul Horton
@@ -18,25 +18,20 @@
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
 Classifier: Topic :: Security
 Classifier: Topic :: Software Development
 Classifier: Topic :: System :: Software Distribution
 Classifier: Typing :: Typed
 Requires-Dist: importlib-metadata (>=3.4.0,<4.0.0) ; python_version < "3.8"
-Requires-Dist: packageurl-python (>=0.9)
+Requires-Dist: packageurl-python (>=0.11)
 Requires-Dist: py-serializable (>=0.11.1,<0.12.0)
 Requires-Dist: sortedcontainers (>=2.4.0,<3.0.0)
 Project-URL: Bug Tracker, https://github.com/CycloneDX/cyclonedx-python-lib/issues
 Project-URL: Documentation, https://cyclonedx-python-library.readthedocs.io/
 Project-URL: Repository, https://github.com/CycloneDX/cyclonedx-python-lib
 Description-Content-Type: text/markdown
```

