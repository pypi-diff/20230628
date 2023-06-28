# Comparing `tmp/struqture_py-1.2.0.tar.gz` & `tmp/struqture_py-1.3.0.tar.gz`

## Comparing `struqture_py-1.2.0.tar` & `struqture_py-1.3.0.tar`

### file list

```diff
@@ -1,101 +1,102 @@
--rw-r--r--   0        0        0      481 1970-01-01 00:00:00.000000 struqture_py-1.2.0/local_dependencies/struqture-py-macros/Cargo.toml
--rw-r--r--   0     1001      123    11363 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture-py-macros/LICENSE
--rw-r--r--   0     1001      123     3558 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/lib.rs
--rw-r--r--   0     1001      123    34220 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/noiseless_system_wrapper.rs
--rw-r--r--   0     1001      123    45152 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/noisy_system_wrapper.rs
--rw-r--r--   0     1001      123    22659 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/product_wrapper.rs
--rw-r--r--   0        0        0      738 1970-01-01 00:00:00.000000 struqture_py-1.2.0/local_dependencies/struqture/Cargo.toml
--rw-r--r--   0     1001      123    11363 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/LICENSE
--rw-r--r--   0     1001      123    27657 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian.rs
--rw-r--r--   0     1001      123    18930 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian_system.rs
--rw-r--r--   0     1001      123    43766 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_indices.rs
--rw-r--r--   0     1001      123    23910 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_noise_operator.rs
--rw-r--r--   0     1001      123    18296 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_noise_system.rs
--rw-r--r--   0     1001      123    10336 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_open_system.rs
--rw-r--r--   0     1001      123    22829 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_operator.rs
--rw-r--r--   0     1001      123    16840 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_system.rs
--rw-r--r--   0     1001      123     3411 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/bosons/mod.rs
--rw-r--r--   0     1001      123    28439 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian.rs
--rw-r--r--   0     1001      123    20211 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian_system.rs
--rw-r--r--   0     1001      123    57059 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_indices.rs
--rw-r--r--   0     1001      123    27748 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_noise_operator.rs
--rw-r--r--   0     1001      123    19448 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_noise_system.rs
--rw-r--r--   0     1001      123    11507 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_open_system.rs
--rw-r--r--   0     1001      123    24037 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_operator.rs
--rw-r--r--   0     1001      123    18063 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_system.rs
--rw-r--r--   0     1001      123     3509 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/fermions/mod.rs
--rw-r--r--   0     1001      123    36529 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/lib.rs
--rw-r--r--   0     1001      123     2202 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mappings/jordan_wigner.rs
--rw-r--r--   0     1001      123      839 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mappings/mod.rs
--rw-r--r--   0     1001      123    22051 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_decoherence_product.rs
--rw-r--r--   0     1001      123    31450 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian.rs
--rw-r--r--   0     1001      123    29999 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian_system.rs
--rw-r--r--   0     1001      123    34524 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_hermitian_product.rs
--rw-r--r--   0     1001      123    36734 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_operator.rs
--rw-r--r--   0     1001      123    32955 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_system.rs
--rw-r--r--   0     1001      123    16956 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_open_system.rs
--rw-r--r--   0     1001      123    29859 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_operator.rs
--rw-r--r--   0     1001      123    32034 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_operator.rs
--rw-r--r--   0     1001      123    18574 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_product.rs
--rw-r--r--   0     1001      123    28693 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_product.rs
--rw-r--r--   0     1001      123    28830 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_system.rs
--rw-r--r--   0     1001      123     9247 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mod.rs
--rw-r--r--   0     1001      123     1159 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/prelude.rs
--rw-r--r--   0     1001      123    24488 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/decoherence_operator.rs
--rw-r--r--   0     1001      123    37300 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/decoherence_product.rs
--rw-r--r--   0     1001      123    20752 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/mod.rs
--rw-r--r--   0     1001      123    26632 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/pauli_product.rs
--rw-r--r--   0     1001      123    30024 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/plus_minus_noise_operator.rs
--rw-r--r--   0     1001      123    26071 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/plus_minus_operator.rs
--rw-r--r--   0     1001      123    41204 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/plus_minus_product.rs
--rw-r--r--   0     1001      123    25670 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_hamiltonian.rs
--rw-r--r--   0     1001      123    20715 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_hamiltonian_system.rs
--rw-r--r--   0     1001      123    36134 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_noise_operator.rs
--rw-r--r--   0     1001      123    20432 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_noise_system.rs
--rw-r--r--   0     1001      123    13222 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_open_system.rs
--rw-r--r--   0     1001      123    26584 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_operator.rs
--rw-r--r--   0     1001      123    18938 2023-06-12 08:29:03.000000 struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_system.rs
--rw-r--r--   0        0        0     1357 1970-01-01 00:00:00.000000 struqture_py-1.2.0/Cargo.toml
--rw-r--r--   0     1001      123      701 2023-06-12 08:29:03.000000 struqture_py-1.2.0/build.rs
--rw-r--r--   0     1001      123      536 2023-06-12 08:29:03.000000 struqture_py-1.2.0/pyproject.toml
--rw-r--r--   0     1001      123     3168 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/bosons/boson_product.rs
--rw-r--r--   0     1001      123     4992 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/bosons/bosonic_hamiltonian_system.rs
--rw-r--r--   0     1001      123     4194 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/bosons/bosonic_noise_system.rs
--rw-r--r--   0     1001      123     2755 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/bosons/bosonic_open_system.rs
--rw-r--r--   0     1001      123     4370 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/bosons/bosonic_system.rs
--rw-r--r--   0     1001      123     3582 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/bosons/hermitian_boson_product.rs
--rw-r--r--   0     1001      123     2885 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/bosons/mod.rs
--rw-r--r--   0     1001      123     3355 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/fermions/fermion_product.rs
--rw-r--r--   0     1001      123     5267 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/fermions/fermionic_hamiltonian_system.rs
--rw-r--r--   0     1001      123     4260 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/fermions/fermionic_noise_system.rs
--rw-r--r--   0     1001      123     2804 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/fermions/fermionic_open_system.rs
--rw-r--r--   0     1001      123     4450 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/fermions/fermionic_system.rs
--rw-r--r--   0     1001      123     3660 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/fermions/hermitian_fermion_product.rs
--rw-r--r--   0     1001      123     2975 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/fermions/mod.rs
--rw-r--r--   0     1001      123     3200 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/lib.rs
--rw-r--r--   0     1001      123     9101 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_decoherence_product.rs
--rw-r--r--   0     1001      123     6436 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_hamiltonian_system.rs
--rw-r--r--   0     1001      123     9044 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_hermitian_product.rs
--rw-r--r--   0     1001      123     4750 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_noise_system.rs
--rw-r--r--   0     1001      123     3513 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_open_system.rs
--rw-r--r--   0     1001      123     6882 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_plus_minus_operator.rs
--rw-r--r--   0     1001      123     7505 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_plus_minus_product.rs
--rw-r--r--   0     1001      123     8686 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_product.rs
--rw-r--r--   0     1001      123     5348 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mixed_system.rs
--rw-r--r--   0     1001      123     2829 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/mixed_systems/mod.rs
--rw-r--r--   0     1001      123     4682 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/decoherence_product.rs
--rw-r--r--   0     1001      123     2431 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/mod.rs
--rw-r--r--   0     1001      123     4551 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/pauli_product.rs
--rw-r--r--   0     1001      123     7112 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/plus_minus_noise_operator.rs
--rw-r--r--   0     1001      123     8540 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/plus_minus_operator.rs
--rw-r--r--   0     1001      123    12124 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/plus_minus_product.rs
--rw-r--r--   0     1001      123     5282 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/spin_hamiltonian_system.rs
--rw-r--r--   0     1001      123     4237 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/spin_noise_system.rs
--rw-r--r--   0     1001      123     3085 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/spin_open_system.rs
--rw-r--r--   0     1001      123     4682 2023-06-12 08:29:03.000000 struqture_py-1.2.0/src/spins/spin_system.rs
--rw-r--r--   0     1001      123   912517 2023-06-12 08:29:03.000000 struqture_py-1.2.0/struqture_py/DEPENDENCIES
--rw-r--r--   0     1001      123      503 2023-06-12 08:29:03.000000 struqture_py-1.2.0/struqture_py/LICENSE_FOR_BINARY_DISTRIBUTION
--rw-r--r--   0     1001      123     2404 2023-06-12 08:29:03.000000 struqture_py-1.2.0/struqture_py/PYTHON_LICENSE
--rw-r--r--   0     1001      123      558 2023-06-12 08:29:03.000000 struqture_py-1.2.0/struqture_py/__init__.py
--rw-r--r--   0     1001      123    19310 2023-06-12 08:29:03.000000 struqture_py-1.2.0/Cargo.lock
--rw-r--r--   0        0        0      602 1970-01-01 00:00:00.000000 struqture_py-1.2.0/PKG-INFO
+-rw-r--r--   0        0        0      481 1970-01-01 00:00:00.000000 struqture_py-1.3.0/local_dependencies/struqture-py-macros/Cargo.toml
+-rw-r--r--   0     1001      123    11363 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture-py-macros/LICENSE
+-rw-r--r--   0     1001      123     3868 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/lib.rs
+-rw-r--r--   0     1001      123     6356 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/mappings.rs
+-rw-r--r--   0     1001      123    34220 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/noiseless_system_wrapper.rs
+-rw-r--r--   0     1001      123    45152 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/noisy_system_wrapper.rs
+-rw-r--r--   0     1001      123    22660 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/product_wrapper.rs
+-rw-r--r--   0        0        0      738 1970-01-01 00:00:00.000000 struqture_py-1.3.0/local_dependencies/struqture/Cargo.toml
+-rw-r--r--   0     1001      123    11363 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/LICENSE
+-rw-r--r--   0     1001      123    27657 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian.rs
+-rw-r--r--   0     1001      123    18930 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian_system.rs
+-rw-r--r--   0     1001      123    43766 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_indices.rs
+-rw-r--r--   0     1001      123    23910 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_noise_operator.rs
+-rw-r--r--   0     1001      123    18296 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_noise_system.rs
+-rw-r--r--   0     1001      123    10336 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_open_system.rs
+-rw-r--r--   0     1001      123    22829 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_operator.rs
+-rw-r--r--   0     1001      123    16840 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_system.rs
+-rw-r--r--   0     1001      123     3411 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/bosons/mod.rs
+-rw-r--r--   0     1001      123    28439 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian.rs
+-rw-r--r--   0     1001      123    20203 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian_system.rs
+-rw-r--r--   0     1001      123    57059 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_indices.rs
+-rw-r--r--   0     1001      123    27748 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_noise_operator.rs
+-rw-r--r--   0     1001      123    19440 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_noise_system.rs
+-rw-r--r--   0     1001      123    11507 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_open_system.rs
+-rw-r--r--   0     1001      123    24037 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_operator.rs
+-rw-r--r--   0     1001      123    18063 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_system.rs
+-rw-r--r--   0     1001      123     3509 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/fermions/mod.rs
+-rw-r--r--   0     1001      123    36529 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/lib.rs
+-rw-r--r--   0     1001      123     2201 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mappings/jordan_wigner.rs
+-rw-r--r--   0     1001      123      839 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mappings/mod.rs
+-rw-r--r--   0     1001      123    22051 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_decoherence_product.rs
+-rw-r--r--   0     1001      123    31450 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian.rs
+-rw-r--r--   0     1001      123    29999 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian_system.rs
+-rw-r--r--   0     1001      123    34524 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_hermitian_product.rs
+-rw-r--r--   0     1001      123    36734 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_operator.rs
+-rw-r--r--   0     1001      123    32955 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_system.rs
+-rw-r--r--   0     1001      123    16956 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_open_system.rs
+-rw-r--r--   0     1001      123    29859 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_operator.rs
+-rw-r--r--   0     1001      123    32034 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_operator.rs
+-rw-r--r--   0     1001      123    18574 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_product.rs
+-rw-r--r--   0     1001      123    28693 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_product.rs
+-rw-r--r--   0     1001      123    28830 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_system.rs
+-rw-r--r--   0     1001      123     9247 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mod.rs
+-rw-r--r--   0     1001      123     1159 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/prelude.rs
+-rw-r--r--   0     1001      123    24488 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/decoherence_operator.rs
+-rw-r--r--   0     1001      123    37300 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/decoherence_product.rs
+-rw-r--r--   0     1001      123    20752 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/mod.rs
+-rw-r--r--   0     1001      123    26632 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/pauli_product.rs
+-rw-r--r--   0     1001      123    30024 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/plus_minus_noise_operator.rs
+-rw-r--r--   0     1001      123    26071 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/plus_minus_operator.rs
+-rw-r--r--   0     1001      123    41204 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/plus_minus_product.rs
+-rw-r--r--   0     1001      123    25670 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_hamiltonian.rs
+-rw-r--r--   0     1001      123    20707 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_hamiltonian_system.rs
+-rw-r--r--   0     1001      123    36134 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_noise_operator.rs
+-rw-r--r--   0     1001      123    20424 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_noise_system.rs
+-rw-r--r--   0     1001      123    13222 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_open_system.rs
+-rw-r--r--   0     1001      123    26584 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_operator.rs
+-rw-r--r--   0     1001      123    18938 2023-06-28 10:11:35.000000 struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_system.rs
+-rw-r--r--   0        0        0     1379 1970-01-01 00:00:00.000000 struqture_py-1.3.0/Cargo.toml
+-rw-r--r--   0     1001      123      701 2023-06-28 10:11:35.000000 struqture_py-1.3.0/build.rs
+-rw-r--r--   0     1001      123      536 2023-06-28 10:11:35.000000 struqture_py-1.3.0/pyproject.toml
+-rw-r--r--   0     1001      123     3168 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/bosons/boson_product.rs
+-rw-r--r--   0     1001      123     4992 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/bosons/bosonic_hamiltonian_system.rs
+-rw-r--r--   0     1001      123     4194 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/bosons/bosonic_noise_system.rs
+-rw-r--r--   0     1001      123     2755 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/bosons/bosonic_open_system.rs
+-rw-r--r--   0     1001      123     4370 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/bosons/bosonic_system.rs
+-rw-r--r--   0     1001      123     3582 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/bosons/hermitian_boson_product.rs
+-rw-r--r--   0     1001      123     2885 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/bosons/mod.rs
+-rw-r--r--   0     1001      123     3520 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/fermions/fermion_product.rs
+-rw-r--r--   0     1001      123     5418 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/fermions/fermionic_hamiltonian_system.rs
+-rw-r--r--   0     1001      123     4413 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/fermions/fermionic_noise_system.rs
+-rw-r--r--   0     1001      123     2956 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/fermions/fermionic_open_system.rs
+-rw-r--r--   0     1001      123     4590 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/fermions/fermionic_system.rs
+-rw-r--r--   0     1001      123     3836 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/fermions/hermitian_fermion_product.rs
+-rw-r--r--   0     1001      123     2975 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/fermions/mod.rs
+-rw-r--r--   0     1001      123     3200 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/lib.rs
+-rw-r--r--   0     1001      123     9101 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_decoherence_product.rs
+-rw-r--r--   0     1001      123     6436 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_hamiltonian_system.rs
+-rw-r--r--   0     1001      123     9044 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_hermitian_product.rs
+-rw-r--r--   0     1001      123     4750 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_noise_system.rs
+-rw-r--r--   0     1001      123     3513 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_open_system.rs
+-rw-r--r--   0     1001      123     6882 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_plus_minus_operator.rs
+-rw-r--r--   0     1001      123     7505 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_plus_minus_product.rs
+-rw-r--r--   0     1001      123     8686 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_product.rs
+-rw-r--r--   0     1001      123     5348 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mixed_system.rs
+-rw-r--r--   0     1001      123     2829 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/mixed_systems/mod.rs
+-rw-r--r--   0     1001      123     4868 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/decoherence_product.rs
+-rw-r--r--   0     1001      123     2431 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/mod.rs
+-rw-r--r--   0     1001      123     4737 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/pauli_product.rs
+-rw-r--r--   0     1001      123     7324 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/plus_minus_noise_operator.rs
+-rw-r--r--   0     1001      123     8726 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/plus_minus_operator.rs
+-rw-r--r--   0     1001      123    12507 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/plus_minus_product.rs
+-rw-r--r--   0     1001      123     5439 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/spin_hamiltonian_system.rs
+-rw-r--r--   0     1001      123     4396 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/spin_noise_system.rs
+-rw-r--r--   0     1001      123     3243 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/spin_open_system.rs
+-rw-r--r--   0     1001      123     4828 2023-06-28 10:11:35.000000 struqture_py-1.3.0/src/spins/spin_system.rs
+-rw-r--r--   0     1001      123   912517 2023-06-28 10:11:35.000000 struqture_py-1.3.0/struqture_py/DEPENDENCIES
+-rw-r--r--   0     1001      123      503 2023-06-28 10:11:35.000000 struqture_py-1.3.0/struqture_py/LICENSE_FOR_BINARY_DISTRIBUTION
+-rw-r--r--   0     1001      123     2404 2023-06-28 10:11:35.000000 struqture_py-1.3.0/struqture_py/PYTHON_LICENSE
+-rw-r--r--   0     1001      123      558 2023-06-28 10:11:35.000000 struqture_py-1.3.0/struqture_py/__init__.py
+-rw-r--r--   0     1001      123    19795 2023-06-28 10:11:35.000000 struqture_py-1.3.0/Cargo.lock
+-rw-r--r--   0        0        0      602 1970-01-01 00:00:00.000000 struqture_py-1.3.0/PKG-INFO
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture-py-macros/LICENSE` & `struqture_py-1.3.0/local_dependencies/struqture-py-macros/LICENSE`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/lib.rs` & `struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/lib.rs`

 * *Files 4% similar despite different names*

```diff
@@ -27,35 +27,47 @@
 ) -> proc_macro::TokenStream {
     productwrapper(metadata, input)
 }
 
 mod noiseless_system_wrapper;
 use noiseless_system_wrapper::noiselesswrapper;
 
-/// Attribute macro for constructing the pyo3 implementation for mixed indices.
+/// Attribute macro for constructing the pyo3 implementation for noiseless systems.
 #[proc_macro_attribute]
 pub fn noiseless_system_wrapper(
     metadata: proc_macro::TokenStream,
     input: proc_macro::TokenStream,
 ) -> proc_macro::TokenStream {
     noiselesswrapper(metadata, input)
 }
 
 mod noisy_system_wrapper;
 use noisy_system_wrapper::noisywrapper;
 
-/// Attribute macro for constructing the pyo3 implementation for mixed indices.
+/// Attribute macro for constructing the pyo3 implementation for noisy systems.
 #[proc_macro_attribute]
 pub fn noisy_system_wrapper(
     metadata: proc_macro::TokenStream,
     input: proc_macro::TokenStream,
 ) -> proc_macro::TokenStream {
     noisywrapper(metadata, input)
 }
 
+mod mappings;
+use mappings::mappings_macro;
+
+/// Attribute macro for constructing the pyo3 implementation for mappings.
+#[proc_macro_attribute]
+pub fn mappings(
+    metadata: proc_macro::TokenStream,
+    input: proc_macro::TokenStream,
+) -> proc_macro::TokenStream {
+    mappings_macro(metadata, input)
+}
+
 // Helper functions
 // Struct for parsed derive macro arguments. Used to identify structs belonging to enums
 #[derive(Debug)]
 struct AttributeMacroArguments(HashSet<String>);
 
 impl AttributeMacroArguments {
     pub fn contains(&self, st: &str) -> bool {
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/noiseless_system_wrapper.rs` & `struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/noiseless_system_wrapper.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/noisy_system_wrapper.rs` & `struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/noisy_system_wrapper.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture-py-macros/src/product_wrapper.rs` & `struqture_py-1.3.0/local_dependencies/struqture-py-macros/src/product_wrapper.rs`

 * *Files 0% similar despite different names*

```diff
@@ -334,14 +334,15 @@
 
             }
                 }
 
             )
         }
     }
+
         #[pymethods]
         impl #ident {
 
             #(#items)*
 
             #symmetric_index_quote
             #mode_index_quote
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/Cargo.toml` & `struqture_py-1.3.0/local_dependencies/struqture/Cargo.toml`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [package]
 name = "struqture"
-version = "1.2.0"
+version = "1.3.0"
 authors = ["HQS Quantum Simulations <info@quantumsimulations.de>"]
 edition = "2021"
 rust-version = "1.57"
 categories = ["science", "simulation"]
 description = "HQS tool for representing operators, Hamiltonians and open systems."
 license = "Apache-2.0"
 include = ["Cargo.toml", "src*", "LICENSE", "../README.md"]
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/LICENSE` & `struqture_py-1.3.0/local_dependencies/struqture/LICENSE`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_hamiltonian_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_indices.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_indices.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_noise_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_noise_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_noise_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_noise_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_open_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_open_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/bosonic_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/bosonic_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/bosons/mod.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/bosons/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_hamiltonian_system.rs`

 * *Files 0% similar despite different names*

```diff
@@ -541,12 +541,12 @@
     ///
     /// # Panics
     ///
     /// * Internal error in jordan_wigner transformation for FermionHamiltonian.
     fn jordan_wigner(&self) -> Self::Output {
         SpinHamiltonianSystem::from_hamiltonian(
             self.hamiltonian().jordan_wigner(),
-            Some(self.number_modes()),
+            self.number_modes,
         )
         .expect("Internal bug in jordan_wigner for FermionHamiltonian. The number of spins in the resulting Hamiltonian should equal the number of modes of the FermionHamiltonian.")
     }
 }
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_indices.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_indices.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_noise_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_noise_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_noise_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_noise_system.rs`

 * *Files 0% similar despite different names*

```diff
@@ -507,12 +507,12 @@
     ///
     /// # Panics
     ///
     /// * Internal error in jordan_wigner transformation for FermionLindbladNoiseOperator.
     fn jordan_wigner(&self) -> Self::Output {
         SpinLindbladNoiseSystem::from_operator(
             self.operator().jordan_wigner(),
-            Some(self.number_modes()),
+            self.number_modes,
         )
             .expect("Internal bug in jordan_wigner for FermionLindbladNoiseOperator. The number of spins in the resulting SpinLindbladNoiseOperator should equal the number of modes of the FermionLindbladNoiseOperator.")
     }
 }
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_open_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_open_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/fermionic_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/fermionic_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/fermions/mod.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/fermions/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/lib.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/lib.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mappings/jordan_wigner.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mappings/jordan_wigner.rs`

 * *Files 1% similar despite different names*

```diff
@@ -35,14 +35,13 @@
 pub trait JordanWignerSpinToFermion {
     /// The Output type for the JordanWigner transformation
     ///
     /// For a PauliProduct, SpinOperator or PlusMinusOperator it will be a FermionOperator
     /// For a SpinHamiltonian it will be a FermionHamiltonian
     /// For a SpinLindbladNoiseOperator it will be a FermionLindbladNoiseOperator
     /// For a SpinLindbladOpenSystem it will be a FermionLindbladOpenSystem
-
     type Output;
 
-    /// Transform the given fermionic object into a spin object using
+    /// Transform the given spin object into a fermionic object using
     /// the Jordan Wigner mapping.
     fn jordan_wigner(&self) -> Self::Output;
 }
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mappings/mod.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mappings/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_decoherence_product.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_decoherence_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_hamiltonian_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_hermitian_product.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_hermitian_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_noise_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_open_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_open_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_product.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_plus_minus_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_product.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mixed_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mixed_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/mixed_systems/mod.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/mixed_systems/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/prelude.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/prelude.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/decoherence_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/decoherence_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/decoherence_product.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/decoherence_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/mod.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/pauli_product.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/pauli_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/plus_minus_noise_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/plus_minus_noise_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/plus_minus_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/plus_minus_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/plus_minus_product.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/plus_minus_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_hamiltonian.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_hamiltonian.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_hamiltonian_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_hamiltonian_system.rs`

 * *Files 0% similar despite different names*

```diff
@@ -576,12 +576,12 @@
     ///
     /// # Panics
     ///
     /// * Internal error in jordan_wigner() for SpinHamiltonian.
     fn jordan_wigner(&self) -> Self::Output {
         FermionHamiltonianSystem::from_hamiltonian(
             self.hamiltonian().jordan_wigner(),
-            Some(self.number_spins()),
+            self.number_spins,
         )
             .expect("Internal bug in jordan_wigner() for SpinHamiltonian. The number of modes in the resulting fermionic Hamiltonian should equal the number of spins of the spin Hamiltonian.")
     }
 }
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_noise_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_noise_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_noise_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_noise_system.rs`

 * *Files 0% similar despite different names*

```diff
@@ -547,12 +547,12 @@
     ///
     /// # Panics
     ///
     /// * Internal error in jordan_wigner() for SpinLindbladNoiseOperator.
     fn jordan_wigner(&self) -> Self::Output {
         FermionLindbladNoiseSystem::from_operator(
             self.operator().jordan_wigner(),
-            Some(self.number_spins()),
+            self.number_spins,
         )
             .expect("Internal bug in jordan_wigner() for SpinLindbladNoiseOperator. The number of modes in the resulting fermionic noise operator should equal the number of spins of the spin noise operator.")
     }
 }
```

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_open_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_open_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_operator.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/local_dependencies/struqture/src/spins/spin_system.rs` & `struqture_py-1.3.0/local_dependencies/struqture/src/spins/spin_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/Cargo.toml` & `struqture_py-1.3.0/Cargo.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [package]
 name = "struqture-py"
-version = "1.2.0"
+version = "1.3.0"
 authors = ["HQS Quantum Simulations <info@quantumsimulations.de>"]
 edition = "2021"
 rust-version = "1.57"
 categories = ["science", "simulation"]
 description = "Python interface of struqture, the HQS tool for representing operators, Hamiltonians and open systems."
 license = "Apache-2.0"
 include=["src*", "struqture_py", "Cargo.toml", "build.rs", "pyproject.toml"]
@@ -13,27 +13,27 @@
 name = "struqture_py"
 path = "src/lib.rs"
 doctest = false
 crate-type = ["cdylib", "rlib"]
 
 [dependencies.pyo3]
 version = "0.18"
-features = ["num-complex"]
+features = ["num-complex", "multiple-pymethods"]
 
 [dependencies]
-struqture = {version="1.2.0", path= "local_dependencies/struqture", default-features=false}
+struqture = {version="1.3.0", path= "local_dependencies/struqture", default-features=false}
 serde = { version = "1.0", features = ["derive"] }
 numpy = "0.18"
 qoqo_calculator = {version="1.1", default-features=false}
 qoqo_calculator_pyo3 = {version="1.1", default-features=false}
 bincode = "1.3"
 serde_json = "1.0"
 thiserror = "1.0"
 num-complex = "0.4"
-struqture-py-macros = {version="1.2.0", path= "local_dependencies/struqture-py-macros" }
+struqture-py-macros = {version="1.3.0", path= "local_dependencies/struqture-py-macros" }
 
 
 [build-dependencies]
 quote = "1.0"
 syn = { version = "2.0", features = ["full", "visit"] }
 proc-macro2 = "1.0"
 pyo3-build-config="0.18"
```

### Comparing `struqture_py-1.2.0/build.rs` & `struqture_py-1.3.0/build.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/pyproject.toml` & `struqture_py-1.3.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name = "struqture-py"
-version = "1.2.0"
+version = "1.3.0"
 dependencies = [
   'numpy',
   'qoqo_calculator_pyo3>=1.1.0',
 ]
 license = {text="Apache-2.0 AND Apache-2.0 with LLVM-exception AND MIT AND Unicode-DFS-2016 AND BSD-2-Clause AND BSD-3-CLause"}
 maintainers = [{name = "HQS Quantum Simulations GmbH", email = "info@quantumsimulations.de"}]
 requires-python = ">=3.7"
```

### Comparing `struqture_py-1.2.0/src/bosons/boson_product.rs` & `struqture_py-1.3.0/src/bosons/boson_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/bosons/bosonic_hamiltonian_system.rs` & `struqture_py-1.3.0/src/bosons/bosonic_hamiltonian_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/bosons/bosonic_noise_system.rs` & `struqture_py-1.3.0/src/bosons/bosonic_noise_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/bosons/bosonic_open_system.rs` & `struqture_py-1.3.0/src/bosons/bosonic_open_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/bosons/bosonic_system.rs` & `struqture_py-1.3.0/src/bosons/bosonic_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/bosons/hermitian_boson_product.rs` & `struqture_py-1.3.0/src/bosons/hermitian_boson_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/bosons/mod.rs` & `struqture_py-1.3.0/src/bosons/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/fermions/fermion_product.rs` & `struqture_py-1.3.0/src/fermions/fermion_product.rs`

 * *Files 5% similar despite different names*

```diff
@@ -6,24 +6,27 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::spins::SpinSystemWrapper;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use pyo3::types::PyType;
 use std::collections::hash_map::DefaultHasher;
 use std::hash::{Hash, Hasher};
 use std::str::FromStr;
 use struqture::fermions::*;
+use struqture::mappings::JordanWignerFermionToSpin;
 use struqture::prelude::*;
-use struqture_py_macros::product_wrapper;
+use struqture::spins::*;
+use struqture_py_macros::{mappings, product_wrapper};
 
 /// A product of fermionic creation and annihilation operators.
 ///
 /// The FermionProduct is used as an index for non-hermitian, normal ordered fermionic operators.
 /// A fermionic operator can be written as a sum over normal ordered products of creation and annihilation operators.
 /// The FermionProduct is used as an index when setting or adding new summands to a fermionic operator and when querrying the
 /// weight of a product of operators in the sum.
@@ -42,14 +45,15 @@
 ///     
 #[pyclass(name = "FermionProduct", module = "struqture_py.fermions")]
 #[derive(Clone, Debug, PartialEq, Eq, PartialOrd, Ord, Default)]
 pub struct FermionProductWrapper {
     pub internal: FermionProduct,
 }
 
+#[mappings(JordanWignerFermionToSpin)]
 #[product_wrapper(FermionIndex, ModeIndex, SymmetricIndex)]
 impl FermionProductWrapper {
     /// Create a new FermionProduct.
     ///
     /// Args:
     ///     creators (List[int]): List of creator sub-indices.
     ///     annihilators (List[int]): List of annihilator sub-indices.
```

### Comparing `struqture_py-1.2.0/src/fermions/fermionic_hamiltonian_system.rs` & `struqture_py-1.3.0/src/fermions/fermionic_hamiltonian_system.rs`

 * *Files 6% similar despite different names*

```diff
@@ -8,23 +8,25 @@
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
 use super::FermionSystemWrapper;
 use crate::fermions::HermitianFermionProductWrapper;
+use crate::spins::SpinHamiltonianSystemWrapper;
 use bincode::deserialize;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator::CalculatorComplex;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
 use struqture::fermions::FermionHamiltonianSystem;
+use struqture::mappings::JordanWignerFermionToSpin;
 use struqture::{OperateOnDensityMatrix, OperateOnModes, OperateOnState};
-use struqture_py_macros::noiseless_system_wrapper;
+use struqture_py_macros::{mappings, noiseless_system_wrapper};
 
 /// These are representations of systems of fermions.
 ///
 /// FermionHamiltonianSystems are characterized by a FermionOperator to represent the hamiltonian of the spin system
 /// and an optional number of fermions.
 ///
 /// Examples
@@ -47,14 +49,15 @@
 #[pyclass(name = "FermionHamiltonianSystem", module = "struqture_py.fermions")]
 #[derive(Clone, Debug, PartialEq)]
 pub struct FermionHamiltonianSystemWrapper {
     /// Internal storage of [struqture::fermions::FermionHamiltonianSystem]
     pub internal: FermionHamiltonianSystem,
 }
 
+#[mappings(JordanWignerFermionToSpin)]
 #[noiseless_system_wrapper(
     OperateOnFermions,
     OperateOnState,
     OperateOnModes,
     OperateOnDensityMatrix,
     Calculus
 )]
```

### Comparing `struqture_py-1.2.0/src/fermions/fermionic_noise_system.rs` & `struqture_py-1.3.0/src/fermions/fermionic_noise_system.rs`

 * *Files 11% similar despite different names*

```diff
@@ -7,22 +7,24 @@
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
 use crate::fermions::FermionProductWrapper;
+use crate::spins::SpinLindbladNoiseSystemWrapper;
 use bincode::deserialize;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
 use struqture::fermions::FermionLindbladNoiseSystem;
+use struqture::mappings::JordanWignerFermionToSpin;
 use struqture::{OperateOnDensityMatrix, OperateOnModes};
-use struqture_py_macros::noisy_system_wrapper;
+use struqture_py_macros::{mappings, noisy_system_wrapper};
 
 /// These are representations of noisy systems of fermions.
 ///
 /// In a FermionLindbladNoiseSystem is characterized by a FermionLindbladNoiseOperator to represent the hamiltonian of the system, and an optional number of fermions.
 ///
 /// Examples
 /// --------
@@ -43,14 +45,15 @@
 #[pyclass(name = "FermionLindbladNoiseSystem", module = "struqture_py.fermions")]
 #[derive(Clone, Debug, PartialEq, Default)]
 pub struct FermionLindbladNoiseSystemWrapper {
     /// Internal storage of [struqture::fermions::FermionLindbladNoiseSystem]
     pub internal: FermionLindbladNoiseSystem,
 }
 
+#[mappings(JordanWignerFermionToSpin)]
 #[noisy_system_wrapper(OperateOnModes, OperateOnFermions, OperateOnDensityMatrix, Calculus)]
 impl FermionLindbladNoiseSystemWrapper {
     /// Create a new FermionLindbladNoiseSystem.
     ///
     /// Args:
     ///     number_fermions (Optional(int)): The number of fermions in the FermionLindbladNoiseSystem.
     ///
```

### Comparing `struqture_py-1.2.0/src/fermions/fermionic_open_system.rs` & `struqture_py-1.3.0/src/fermions/fermionic_open_system.rs`

 * *Files 8% similar despite different names*

```diff
@@ -10,22 +10,24 @@
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
 use super::{
     FermionHamiltonianSystemWrapper, FermionLindbladNoiseSystemWrapper, FermionProductWrapper,
     HermitianFermionProductWrapper,
 };
+use crate::spins::SpinLindbladOpenSystemWrapper;
 use bincode::deserialize;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
 use struqture::fermions::FermionLindbladOpenSystem;
+use struqture::mappings::JordanWignerFermionToSpin;
 use struqture::{OpenSystem, OperateOnDensityMatrix, OperateOnModes};
-use struqture_py_macros::noisy_system_wrapper;
+use struqture_py_macros::{mappings, noisy_system_wrapper};
 
 /// These are representations of noisy systems of fermions.
 ///
 /// In a FermionLindbladOpenSystem is characterized by a FermionLindbladOpenOperator to represent the hamiltonian of the system, and an optional number of fermions.
 ///
 /// Examples
 /// --------
@@ -46,14 +48,15 @@
 #[pyclass(name = "FermionLindbladOpenSystem", module = "struqture_py.fermions")]
 #[derive(Clone, Debug, PartialEq, Default)]
 pub struct FermionLindbladOpenSystemWrapper {
     /// Internal storage of [struqture::fermions::FermionLindbladOpenSystem]
     pub internal: FermionLindbladOpenSystem,
 }
 
+#[mappings(JordanWignerFermionToSpin)]
 #[noisy_system_wrapper(OpenSystem, OperateOnModes, Calculus)]
 impl FermionLindbladOpenSystemWrapper {
     /// Create a new FermionLindbladOpenSystem.
     ///
     /// Args:
     ///     number_fermions (Optional(int)): The number of fermions in the FermionLindbladOpenSystem.
     ///
```

### Comparing `struqture_py-1.2.0/src/fermions/fermionic_system.rs` & `struqture_py-1.3.0/src/fermions/fermionic_system.rs`

 * *Files 6% similar despite different names*

```diff
@@ -7,23 +7,25 @@
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
 use crate::fermions::FermionProductWrapper;
+use crate::spins::SpinSystemWrapper;
 use bincode::deserialize;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator::CalculatorComplex;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
 use struqture::fermions::FermionSystem;
+use struqture::mappings::JordanWignerFermionToSpin;
 use struqture::{OperateOnDensityMatrix, OperateOnModes, OperateOnState};
-use struqture_py_macros::noiseless_system_wrapper;
+use struqture_py_macros::{mappings, noiseless_system_wrapper};
 
 /// These are representations of systems of fermions.
 ///
 /// FermionSystems are characterized by a FermionOperator to represent the hamiltonian of the spin system
 /// and an optional number of fermions.
 ///
 /// Examples
@@ -46,14 +48,15 @@
 #[pyclass(name = "FermionSystem", module = "struqture_py.fermions")]
 #[derive(Clone, Debug, PartialEq)]
 pub struct FermionSystemWrapper {
     /// Internal storage of [struqture::fermions::FermionSystem]
     pub internal: FermionSystem,
 }
 
+#[mappings(JordanWignerFermionToSpin)]
 #[noiseless_system_wrapper(
     OperateOnFermions,
     OperateOnState,
     OperateOnModes,
     OperateOnDensityMatrix,
     Calculus
 )]
```

### Comparing `struqture_py-1.2.0/src/fermions/hermitian_fermion_product.rs` & `struqture_py-1.3.0/src/fermions/hermitian_fermion_product.rs`

 * *Files 4% similar despite different names*

```diff
@@ -7,24 +7,27 @@
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
 use super::FermionProductWrapper;
+use crate::spins::SpinHamiltonianSystemWrapper;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use pyo3::types::PyType;
 use std::collections::hash_map::DefaultHasher;
 use std::hash::{Hash, Hasher};
 use std::str::FromStr;
 use struqture::fermions::*;
+use struqture::mappings::JordanWignerFermionToSpin;
 use struqture::prelude::*;
-use struqture_py_macros::product_wrapper;
+use struqture::spins::*;
+use struqture_py_macros::{mappings, product_wrapper};
 
 /// A product of fermionic creation and annihilation operators.
 ///
 /// The HermitianFermionProduct is used as an index for non-hermitian, normal ordered fermionic operators.
 /// A fermionic operator can be written as a sum over normal ordered products of creation and annihilation operators.
 /// The HermitianFermionProduct is used as an index when setting or adding new summands to a fermionic operator and when querrying the
 /// weight of a product of operators in the sum.
@@ -43,14 +46,15 @@
 ///     
 #[pyclass(name = "HermitianFermionProduct", module = "struqture_py.fermions")]
 #[derive(Clone, Debug, PartialEq, Eq, PartialOrd, Ord, Default)]
 pub struct HermitianFermionProductWrapper {
     pub internal: HermitianFermionProduct,
 }
 
+#[mappings(JordanWignerFermionToSpin)]
 #[product_wrapper(FermionIndex, ModeIndex, SymmetricIndex)]
 impl HermitianFermionProductWrapper {
     /// Create a new HermitianFermionProduct.
     ///
     /// Args:
     ///     creators (List[int]): List of creator sub-indices.
     ///     annihilators (List[int]): List of annihilator sub-indices.
```

### Comparing `struqture_py-1.2.0/src/fermions/mod.rs` & `struqture_py-1.3.0/src/fermions/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/lib.rs` & `struqture_py-1.3.0/src/lib.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_decoherence_product.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_decoherence_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_hamiltonian_system.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_hamiltonian_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_hermitian_product.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_hermitian_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_noise_system.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_noise_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_open_system.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_open_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_plus_minus_operator.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_plus_minus_operator.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_plus_minus_product.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_plus_minus_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_product.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_product.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mixed_system.rs` & `struqture_py-1.3.0/src/mixed_systems/mixed_system.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/mixed_systems/mod.rs` & `struqture_py-1.3.0/src/mixed_systems/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/spins/decoherence_product.rs` & `struqture_py-1.3.0/src/spins/decoherence_product.rs`

 * *Files 11% similar despite different names*

```diff
@@ -6,25 +6,28 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::fermions::FermionSystemWrapper;
 use num_complex::Complex64;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use std::collections::hash_map::DefaultHasher;
 use std::collections::HashMap;
 use std::hash::{Hash, Hasher};
 use std::str::FromStr;
+use struqture::fermions::FermionSystem;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{DecoherenceProduct, SingleDecoherenceOperator};
 use struqture::{SpinIndex, SymmetricIndex};
-use struqture_py_macros::product_wrapper;
+use struqture_py_macros::{mappings, product_wrapper};
 
 /// These are combinations of SingleDecoherenceOperators on specific qubits.
 ///
 /// DecoherenceProducts act in a noisy system. They are representation of products of decoherence
 /// matrices acting on qubits in order to build the terms of a hamiltonian.
 /// For instance, to represent the term :math:`\sigma_0^{x}` :math:`\sigma_2^{z}`:
 ///
@@ -49,14 +52,15 @@
 #[pyclass(name = "DecoherenceProduct", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq, Eq, PartialOrd, Ord, Default)]
 pub struct DecoherenceProductWrapper {
     /// Internal storage of [struqture::spins::DecoherenceProduct]
     pub internal: DecoherenceProduct,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[product_wrapper(SpinIndex, SymmetricIndex)]
 impl DecoherenceProductWrapper {
     /// Create an empty DecoherenceProduct.
     ///
     /// Returns:
     ///     self: The new, empty DecoherenceProduct.
     #[new]
```

### Comparing `struqture_py-1.2.0/src/spins/mod.rs` & `struqture_py-1.3.0/src/spins/mod.rs`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/src/spins/pauli_product.rs` & `struqture_py-1.3.0/src/spins/pauli_product.rs`

 * *Files 9% similar despite different names*

```diff
@@ -6,25 +6,28 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::fermions::FermionSystemWrapper;
 use num_complex::Complex64;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use std::collections::hash_map::DefaultHasher;
 use std::collections::HashMap;
 use std::hash::{Hash, Hasher};
 use std::str::FromStr;
+use struqture::fermions::FermionSystem;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{PauliProduct, SingleSpinOperator};
 use struqture::{SpinIndex, SymmetricIndex};
-use struqture_py_macros::product_wrapper;
+use struqture_py_macros::{mappings, product_wrapper};
 
 /// PauliProducts are combinations of SingleSpinOperators on specific qubits.
 ///
 /// PauliProducts can be used in either noise-free or a noisy system.
 /// They are representations of products of pauli matrices acting on qubits,
 /// in order to build the terms of a hamiltonian.
 /// For instance, to represent the term :math:`\sigma_0^{x}` :math:`\sigma_2^{x}` :
@@ -51,14 +54,15 @@
 #[pyclass(name = "PauliProduct", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq, Eq, PartialOrd, Ord, Hash, Default)]
 pub struct PauliProductWrapper {
     /// Internal storage of [struqture::spins::PauliProduct]
     pub internal: PauliProduct,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[product_wrapper(SpinIndex, SymmetricIndex)]
 impl PauliProductWrapper {
     /// Create an empty PauliProduct.
     ///
     /// Returns:
     ///     self: The new, empty PauliProduct.
     #[new]
```

### Comparing `struqture_py-1.2.0/src/spins/plus_minus_noise_operator.rs` & `struqture_py-1.3.0/src/spins/plus_minus_noise_operator.rs`

 * *Files 2% similar despite different names*

```diff
@@ -6,25 +6,28 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::fermions::FermionLindbladNoiseSystemWrapper;
 use crate::spins::PlusMinusProductWrapper;
 use bincode::deserialize;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
+use struqture::fermions::FermionLindbladNoiseSystem;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{
     PlusMinusLindbladNoiseOperator, SpinLindbladNoiseOperator, SpinLindbladNoiseSystem,
 };
 use struqture::OperateOnDensityMatrix;
-use struqture_py_macros::noisy_system_wrapper;
+use struqture_py_macros::{mappings, noisy_system_wrapper};
 
 use super::SpinLindbladNoiseSystemWrapper;
 
 /// These are representations of noisy systems of spins.
 ///
 /// In a PlusMinusLindbladNoiseOperator is characterized by a SpinLindbladNoiseOperator to represent the hamiltonian of the spin system, and an optional number of spins.
 ///
@@ -46,14 +49,15 @@
 #[pyclass(name = "PlusMinusLindbladNoiseOperator", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq, Default)]
 pub struct PlusMinusLindbladNoiseOperatorWrapper {
     /// Internal storage of [struqture::spins::PlusMinusLindbladNoiseOperator]
     pub internal: PlusMinusLindbladNoiseOperator,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[noisy_system_wrapper(OperateOnDensityMatrix)]
 impl PlusMinusLindbladNoiseOperatorWrapper {
     /// Create a new PlusMinusLindbladNoiseOperator.
     ///
     /// Returns:
     ///     self: The new PlusMinusLindbladNoiseOperator with the input number of spins.
     #[new]
```

### Comparing `struqture_py-1.2.0/src/spins/plus_minus_operator.rs` & `struqture_py-1.3.0/src/spins/plus_minus_operator.rs`

 * *Files 2% similar despite different names*

```diff
@@ -6,26 +6,29 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::fermions::FermionSystemWrapper;
 use crate::spins::{PlusMinusProductWrapper, SpinSystemWrapper};
 use bincode::deserialize;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator::CalculatorComplex;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
+use struqture::fermions::FermionSystem;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{
     PlusMinusOperator, SpinHamiltonian, SpinHamiltonianSystem, SpinOperator, SpinSystem,
 };
 use struqture::{OperateOnDensityMatrix, OperateOnState};
-use struqture_py_macros::noiseless_system_wrapper;
+use struqture_py_macros::{mappings, noiseless_system_wrapper};
 
 use super::SpinHamiltonianSystemWrapper;
 
 /// These are representations of systems of spins.
 ///
 /// PlusMinusOperators are characterized by a SpinOperator to represent the hamiltonian of the spin system
 /// and an optional number of spins.
@@ -48,14 +51,15 @@
 #[pyclass(name = "PlusMinusOperator", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq)]
 pub struct PlusMinusOperatorWrapper {
     /// Internal storage of [struqture::spins::PlusMinusOperator]
     pub internal: PlusMinusOperator,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[noiseless_system_wrapper(OperateOnState, OperateOnDensityMatrix)]
 impl PlusMinusOperatorWrapper {
     /// Create an empty PlusMinusOperator.
     ///
     /// Returns:
     ///     self: The new PlusMinusOperator with the input number of spins.
     #[new]
```

### Comparing `struqture_py-1.2.0/src/spins/plus_minus_product.rs` & `struqture_py-1.3.0/src/spins/plus_minus_product.rs`

 * *Files 2% similar despite different names*

```diff
@@ -6,29 +6,32 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::fermions::FermionSystemWrapper;
 use num_complex::Complex64;
 use pyo3::exceptions::{PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::{PyAny, PyByteArray};
 use qoqo_calculator::CalculatorComplex;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
 use std::collections::hash_map::DefaultHasher;
 use std::collections::HashMap;
 use std::hash::{Hash, Hasher};
 use std::str::FromStr;
+use struqture::fermions::FermionSystem;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{
     DecoherenceProduct, PauliProduct, PlusMinusProduct, SinglePlusMinusOperator,
 };
 use struqture::SymmetricIndex;
-use struqture_py_macros::product_wrapper;
+use struqture_py_macros::{mappings, product_wrapper};
 
 use super::{DecoherenceProductWrapper, PauliProductWrapper};
 
 /// PlusMinusProducts are combinations of SinglePlusMinusOperators on specific qubits.
 ///
 /// PlusMinusProducts can be used in either noise-free or a noisy system.
 /// They are representations of products of pauli matrices acting on qubits,
@@ -53,14 +56,15 @@
 #[pyclass(name = "PlusMinusProduct", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq, Eq, PartialOrd, Ord, Hash, Default)]
 pub struct PlusMinusProductWrapper {
     /// Internal storage of [struqture::spins::PlusMinusProduct]
     pub internal: PlusMinusProduct,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[product_wrapper(SymmetricIndex)]
 impl PlusMinusProductWrapper {
     /// Create an empty PlusMinusProduct.
     ///
     /// Returns:
     ///     self: The new, empty PlusMinusProduct.
     #[new]
@@ -145,14 +149,22 @@
     /// Returns:
     ///     list[int]: The sequence of qubit index keys of self.
     pub fn keys(&self) -> Vec<usize> {
         let keys: Vec<usize> = self.internal.iter().map(|(k, _)| k).copied().collect();
         keys
     }
 
+    /// Return maximum index in self.
+    ///
+    /// Returns:
+    ///     int: Maximum index.
+    pub fn current_number_spins(&self) -> usize {
+        self.internal.current_number_spins()
+    }
+
     /// Return number of entries in object.
     ///
     /// Returns:
     ///     int: The length of the content of the object.
     pub fn __len__(&self) -> usize {
         self.internal.iter().len()
     }
```

### Comparing `struqture_py-1.2.0/src/spins/spin_hamiltonian_system.rs` & `struqture_py-1.3.0/src/spins/spin_hamiltonian_system.rs`

 * *Files 6% similar despite different names*

```diff
@@ -7,29 +7,31 @@
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
 use super::SpinSystemWrapper;
+use crate::fermions::FermionHamiltonianSystemWrapper;
 use crate::spins::PauliProductWrapper;
 use crate::{to_py_coo, PyCooMatrix};
 use bincode::deserialize;
 use num_complex::Complex64;
 use pyo3::exceptions::{PyRuntimeError, PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator::CalculatorComplex;
 use qoqo_calculator_pyo3::CalculatorFloatWrapper;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{
     OperateOnSpins, SpinHamiltonianSystem, ToSparseMatrixOperator, ToSparseMatrixSuperOperator,
 };
 use struqture::StruqtureError;
 use struqture::{OperateOnDensityMatrix, OperateOnState};
-use struqture_py_macros::noiseless_system_wrapper;
+use struqture_py_macros::{mappings, noiseless_system_wrapper};
 
 /// These are representations of systems of spins.
 ///
 /// SpinHamiltonianSystems are characterized by a SpinOperator to represent the hamiltonian of the spin system
 /// and an optional number of spins.
 ///
 /// Examples
@@ -54,14 +56,15 @@
 #[pyclass(name = "SpinHamiltonianSystem", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq)]
 pub struct SpinHamiltonianSystemWrapper {
     /// Internal storage of [struqture::spins::SpinHamiltonianSystem]
     pub internal: SpinHamiltonianSystem,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[noiseless_system_wrapper(
     OperateOnSpins,
     OperateOnState,
     ToSparseMatrixOperator,
     ToSparseMatrixSuperOperator,
     OperateOnDensityMatrix,
     Calculus
```

### Comparing `struqture_py-1.2.0/src/spins/spin_noise_system.rs` & `struqture_py-1.3.0/src/spins/spin_noise_system.rs`

 * *Files 4% similar despite different names*

```diff
@@ -6,25 +6,27 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::fermions::FermionLindbladNoiseSystemWrapper;
 use crate::spins::DecoherenceProductWrapper;
 use crate::{to_py_coo, PyCooMatrix};
 use bincode::deserialize;
 use num_complex::Complex64;
 use pyo3::exceptions::{PyRuntimeError, PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{OperateOnSpins, SpinLindbladNoiseSystem, ToSparseMatrixSuperOperator};
 use struqture::{OperateOnDensityMatrix, StruqtureError};
-use struqture_py_macros::noisy_system_wrapper;
+use struqture_py_macros::{mappings, noisy_system_wrapper};
 
 /// These are representations of noisy systems of spins.
 ///
 /// In a SpinLindbladNoiseSystem is characterized by a SpinLindbladNoiseOperator to represent the hamiltonian of the spin system, and an optional number of spins.
 ///
 /// Examples
 /// --------
@@ -48,14 +50,15 @@
 #[pyclass(name = "SpinLindbladNoiseSystem", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq, Default)]
 pub struct SpinLindbladNoiseSystemWrapper {
     /// Internal storage of [struqture::spins::SpinLindbladNoiseSystem]
     pub internal: SpinLindbladNoiseSystem,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[noisy_system_wrapper(
     OperateOnSpins,
     OperateOnDensityMatrix,
     ToSparseMatrixSuperOperator,
     Calculus
 )]
 impl SpinLindbladNoiseSystemWrapper {
```

### Comparing `struqture_py-1.2.0/src/spins/spin_open_system.rs` & `struqture_py-1.3.0/src/spins/spin_open_system.rs`

 * *Files 7% similar despite different names*

```diff
@@ -8,24 +8,26 @@
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
 use super::{DecoherenceProductWrapper, PauliProductWrapper};
 use super::{SpinHamiltonianSystemWrapper, SpinLindbladNoiseSystemWrapper};
+use crate::fermions::FermionLindbladOpenSystemWrapper;
 use crate::{to_py_coo, PyCooMatrix};
 use bincode::deserialize;
 use num_complex::Complex64;
 use pyo3::exceptions::{PyRuntimeError, PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator_pyo3::{CalculatorComplexWrapper, CalculatorFloatWrapper};
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{OperateOnSpins, SpinLindbladOpenSystem, ToSparseMatrixSuperOperator};
 use struqture::{OpenSystem, OperateOnDensityMatrix, StruqtureError};
-use struqture_py_macros::noisy_system_wrapper;
+use struqture_py_macros::{mappings, noisy_system_wrapper};
 
 /// These are representations of noisy systems of spins.
 ///
 /// In a SpinLindbladOpenSystem is characterized by a SpinLindbladOpenOperator to represent the hamiltonian of the system, and an optional number of spins.
 ///
 /// Examples
 /// --------
@@ -48,14 +50,15 @@
 #[pyclass(name = "SpinLindbladOpenSystem", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq, Default)]
 pub struct SpinLindbladOpenSystemWrapper {
     /// Internal storage of [struqture::spins::SpinLindbladOpenSystem]
     pub internal: SpinLindbladOpenSystem,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[noisy_system_wrapper(OpenSystem, OperateOnSpins, ToSparseMatrixSuperOperator, Calculus)]
 impl SpinLindbladOpenSystemWrapper {
     /// Create a new SpinLindbladOpenSystem.
     ///
     /// Args:
     ///     number_spins (Optional[int]): The number of spins in the SpinLindbladOpenSystem.
     ///
```

### Comparing `struqture_py-1.2.0/src/spins/spin_system.rs` & `struqture_py-1.3.0/src/spins/spin_system.rs`

 * *Files 7% similar despite different names*

```diff
@@ -6,29 +6,31 @@
 //     http://www.apache.org/licenses/LICENSE-2.0
 //
 // Unless required by applicable law or agreed to in writing, software distributed under the
 // License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
 // express or implied. See the License for the specific language governing permissions and
 // limitations under the License.
 
+use crate::fermions::FermionSystemWrapper;
 use crate::spins::PauliProductWrapper;
 use crate::{to_py_coo, PyCooMatrix};
 use bincode::deserialize;
 use num_complex::Complex64;
 use pyo3::exceptions::{PyRuntimeError, PyTypeError, PyValueError};
 use pyo3::prelude::*;
 use pyo3::types::PyByteArray;
 use qoqo_calculator::CalculatorComplex;
 use qoqo_calculator_pyo3::CalculatorComplexWrapper;
+use struqture::mappings::JordanWignerSpinToFermion;
 use struqture::spins::{
     OperateOnSpins, SpinSystem, ToSparseMatrixOperator, ToSparseMatrixSuperOperator,
 };
 use struqture::StruqtureError;
 use struqture::{OperateOnDensityMatrix, OperateOnState};
-use struqture_py_macros::noiseless_system_wrapper;
+use struqture_py_macros::{mappings, noiseless_system_wrapper};
 
 /// These are representations of systems of spins.
 ///
 /// SpinSystems are characterized by a SpinOperator to represent the hamiltonian of the spin system
 /// and an optional number of spins.
 ///
 /// Examples
@@ -53,14 +55,15 @@
 #[pyclass(name = "SpinSystem", module = "struqture_py.spins")]
 #[derive(Clone, Debug, PartialEq)]
 pub struct SpinSystemWrapper {
     /// Internal storage of [struqture::spins::SpinSystem]
     pub internal: SpinSystem,
 }
 
+#[mappings(JordanWignerSpinToFermion)]
 #[noiseless_system_wrapper(
     OperateOnSpins,
     OperateOnState,
     ToSparseMatrixOperator,
     ToSparseMatrixSuperOperator,
     OperateOnDensityMatrix,
     Calculus
```

### Comparing `struqture_py-1.2.0/struqture_py/DEPENDENCIES` & `struqture_py-1.3.0/struqture_py/DEPENDENCIES`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/struqture_py/PYTHON_LICENSE` & `struqture_py-1.3.0/struqture_py/PYTHON_LICENSE`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/struqture_py/__init__.py` & `struqture_py-1.3.0/struqture_py/__init__.py`

 * *Files identical despite different names*

### Comparing `struqture_py-1.2.0/Cargo.lock` & `struqture_py-1.3.0/Cargo.lock`

 * *Files 4% similar despite different names*

```diff
@@ -58,20 +58,40 @@
 dependencies = [
  "cfg-if",
  "libc",
  "wasi",
 ]
 
 [[package]]
+name = "ghost"
+version = "0.1.9"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "e77ac7b51b8e6313251737fcef4b1c01a2ea102bde68415b62c0ee9268fec357"
+dependencies = [
+ "proc-macro2",
+ "quote",
+ "syn 2.0.18",
+]
+
+[[package]]
 name = "indoc"
 version = "1.0.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "bfa799dd5ed20a7e349f3b4639aa80d74549c81716d9ec4f994c9b5815598306"
 
 [[package]]
+name = "inventory"
+version = "0.3.6"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "e0539b5de9241582ce6bd6b0ba7399313560151e58c9aaf8b74b711b1bdce644"
+dependencies = [
+ "ghost",
+]
+
+[[package]]
 name = "itertools"
 version = "0.10.5"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "b0fd2260e829bddf4cb6ea802289de2f86d6a7a690192fbe91b3f46e0f2c8473"
 dependencies = [
  "either",
 ]
@@ -290,14 +310,15 @@
 name = "pyo3"
 version = "0.18.3"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "e3b1ac5b3731ba34fdaa9785f8d74d17448cd18f30cf19e0c7e7b1fdb5272109"
 dependencies = [
  "cfg-if",
  "indoc",
+ "inventory",
  "libc",
  "memoffset",
  "num-complex",
  "parking_lot",
  "pyo3-build-config",
  "pyo3-ffi",
  "pyo3-macros",
@@ -510,15 +531,15 @@
 name = "smallvec"
 version = "1.10.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "a507befe795404456341dfab10cef66ead4c041f62b8b11bbb92bffe5d0953e0"
 
 [[package]]
 name = "struqture"
-version = "1.2.0"
+version = "1.3.0"
 dependencies = [
  "bincode",
  "itertools",
  "nalgebra",
  "ndarray",
  "num-complex",
  "qoqo_calculator",
@@ -529,15 +550,15 @@
  "test-case",
  "thiserror",
  "tinyvec",
 ]
 
 [[package]]
 name = "struqture-py"
-version = "1.2.0"
+version = "1.3.0"
 dependencies = [
  "bincode",
  "nalgebra",
  "ndarray",
  "num-complex",
  "numpy",
  "proc-macro2",
@@ -553,15 +574,15 @@
  "syn 2.0.18",
  "test-case",
  "thiserror",
 ]
 
 [[package]]
 name = "struqture-py-macros"
-version = "1.2.0"
+version = "1.3.0"
 dependencies = [
  "num-complex",
  "proc-macro2",
  "quote",
  "syn 2.0.18",
 ]
```

### Comparing `struqture_py-1.2.0/PKG-INFO` & `struqture_py-1.3.0/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: struqture-py
-Version: 1.2.0
+Version: 1.3.0
 Requires-Dist: numpy
 Requires-Dist: qoqo_calculator_pyo3 >=1.1.0
 License-File: LICENSE
 Summary: Python interface of struqture, the HQS tool for representing operators, Hamiltonians and open systems.
 Author: HQS Quantum Simulations <info@quantumsimulations.de>
 Author-email: HQS Quantum Simulations <info@quantumsimulations.de>
 Maintainer-email: HQS Quantum Simulations GmbH <info@quantumsimulations.de>
```

