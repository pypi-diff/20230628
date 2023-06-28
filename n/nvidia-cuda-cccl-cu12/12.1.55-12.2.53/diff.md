# Comparing `tmp/nvidia_cuda_cccl_cu12-12.1.55-py3-none-win_amd64.whl.zip` & `tmp/nvidia_cuda_cccl_cu12-12.2.53-py3-none-manylinux1_x86_64.whl.zip`

## zipinfo {}

```diff
@@ -1,1011 +1,1281 @@
-Zip file size: 1852033 bytes, number of entries: 1009
--rw-r--r--  2.0 unx        0 b- defN 23-Jan-25 03:52 nvidia/__init__.py
--rw-r--r--  2.0 unx        0 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/__init__.py
--rw-r--r--  2.0 unx        0 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/bin/__init__.py
--rw-r--r--  2.0 unx        0 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/__init__.py
--rw-r--r--  2.0 unx     2000 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/config.cuh
--rw-r--r--  2.0 unx     4099 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/cub.cuh
--rw-r--r--  2.0 unx    29056 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_allocator.cuh
--rw-r--r--  2.0 unx     6229 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_arch.cuh
--rw-r--r--  2.0 unx     3644 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_compiler.cuh
--rw-r--r--  2.0 unx     6333 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_cpp_dialect.cuh
--rw-r--r--  2.0 unx     9578 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_debug.cuh
--rw-r--r--  2.0 unx     3733 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_deprecated.cuh
--rw-r--r--  2.0 unx    23006 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_device.cuh
--rw-r--r--  2.0 unx     4275 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_macro.cuh
--rw-r--r--  2.0 unx     4476 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_math.cuh
--rw-r--r--  2.0 unx     5702 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_namespace.cuh
--rw-r--r--  2.0 unx    23119 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_ptx.cuh
--rw-r--r--  2.0 unx    43860 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/util_type.cuh
--rw-r--r--  2.0 unx     3116 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/version.cuh
--rw-r--r--  2.0 unx     9725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_adjacent_difference.cuh
--rw-r--r--  2.0 unx    33064 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_histogram.cuh
--rw-r--r--  2.0 unx    26107 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_merge_sort.cuh
--rw-r--r--  2.0 unx    29119 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_downsweep.cuh
--rw-r--r--  2.0 unx     9298 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_histogram.cuh
--rw-r--r--  2.0 unx    24649 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_onesweep.cuh
--rw-r--r--  2.0 unx    17878 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_upsweep.cuh
--rw-r--r--  2.0 unx    17178 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_reduce.cuh
--rw-r--r--  2.0 unx    23463 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_reduce_by_key.cuh
--rw-r--r--  2.0 unx    35265 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_rle.cuh
--rw-r--r--  2.0 unx    18747 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_scan.cuh
--rw-r--r--  2.0 unx    18102 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_scan_by_key.cuh
--rw-r--r--  2.0 unx    16588 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_segment_fixup.cuh
--rw-r--r--  2.0 unx    10023 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_segmented_radix_sort.cuh
--rw-r--r--  2.0 unx    28925 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_select_if.cuh
--rw-r--r--  2.0 unx    27874 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_spmv_orig.cuh
--rw-r--r--  2.0 unx    11325 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_sub_warp_merge_sort.cuh
--rw-r--r--  2.0 unx    21856 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_three_way_partition.cuh
--rw-r--r--  2.0 unx    21283 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/agent_unique_by_key.cuh
--rw-r--r--  2.0 unx    27546 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/agent/single_pass_scan_operators.cuh
--rw-r--r--  2.0 unx    52579 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_adjacent_difference.cuh
--rw-r--r--  2.0 unx    52893 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_discontinuity.cuh
--rw-r--r--  2.0 unx    50116 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_exchange.cuh
--rw-r--r--  2.0 unx    16713 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_histogram.cuh
--rw-r--r--  2.0 unx    56629 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_load.cuh
--rw-r--r--  2.0 unx    28743 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_merge_sort.cuh
--rw-r--r--  2.0 unx    42558 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_radix_rank.cuh
--rw-r--r--  2.0 unx    40081 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_radix_sort.cuh
--rw-r--r--  2.0 unx     5964 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_raking_layout.cuh
--rw-r--r--  2.0 unx    25510 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_reduce.cuh
--rw-r--r--  2.0 unx    18949 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_run_length_decode.cuh
--rw-r--r--  2.0 unx   103189 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_scan.cuh
--rw-r--r--  2.0 unx    11727 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_shuffle.cuh
--rw-r--r--  2.0 unx    44245 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/block_store.cuh
--rw-r--r--  2.0 unx     5732 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/radix_rank_sort_operations.cuh
--rw-r--r--  2.0 unx     3154 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/specializations/block_histogram_atomic.cuh
--rw-r--r--  2.0 unx     8229 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/specializations/block_histogram_sort.cuh
--rw-r--r--  2.0 unx     9595 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking.cuh
--rw-r--r--  2.0 unx     8334 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking_commutative_only.cuh
--rw-r--r--  2.0 unx     9697 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_warp_reductions.cuh
--rw-r--r--  2.0 unx    28293 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/specializations/block_scan_raking.cuh
--rw-r--r--  2.0 unx    19175 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/block/specializations/block_scan_warp_scans.cuh
--rw-r--r--  2.0 unx     2581 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/choose_offset.cuh
--rw-r--r--  2.0 unx      874 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/cpp_compatibility.cuh
--rw-r--r--  2.0 unx     3476 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/detect_cuda_runtime.cuh
--rw-r--r--  2.0 unx     2698 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/device_double_buffer.cuh
--rw-r--r--  2.0 unx     1926 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/device_synchronize.cuh
--rw-r--r--  2.0 unx     1181 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/exec_check_disable.cuh
--rw-r--r--  2.0 unx     8634 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/temporary_storage.cuh
--rw-r--r--  2.0 unx     2485 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/type_traits.cuh
--rw-r--r--  2.0 unx     2492 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/detail/uninitialized_copy.cuh
--rw-r--r--  2.0 unx    26211 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_adjacent_difference.cuh
--rw-r--r--  2.0 unx    68310 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_histogram.cuh
--rw-r--r--  2.0 unx    37131 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_merge_sort.cuh
--rw-r--r--  2.0 unx    28990 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_partition.cuh
--rw-r--r--  2.0 unx    54487 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_radix_sort.cuh
--rw-r--r--  2.0 unx    47219 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_reduce.cuh
--rw-r--r--  2.0 unx    17929 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_run_length_encode.cuh
--rw-r--r--  2.0 unx    85061 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_scan.cuh
--rw-r--r--  2.0 unx    73338 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_segmented_radix_sort.cuh
--rw-r--r--  2.0 unx    46499 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_segmented_reduce.cuh
--rw-r--r--  2.0 unx   130046 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_segmented_sort.cuh
--rw-r--r--  2.0 unx    40912 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_select.cuh
--rw-r--r--  2.0 unx     9516 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/device_spmv.cuh
--rw-r--r--  2.0 unx    14322 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_adjacent_difference.cuh
--rw-r--r--  2.0 unx    64634 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_histogram.cuh
--rw-r--r--  2.0 unx    31943 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_merge_sort.cuh
--rw-r--r--  2.0 unx   103689 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_radix_sort.cuh
--rw-r--r--  2.0 unx    43479 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce.cuh
--rw-r--r--  2.0 unx    25820 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce_by_key.cuh
--rw-r--r--  2.0 unx    21927 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_rle.cuh
--rw-r--r--  2.0 unx    22771 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_scan.cuh
--rw-r--r--  2.0 unx    23645 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_scan_by_key.cuh
--rw-r--r--  2.0 unx    67162 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_segmented_sort.cuh
--rw-r--r--  2.0 unx    23154 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_select_if.cuh
--rw-r--r--  2.0 unx    32807 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_spmv_orig.cuh
--rw-r--r--  2.0 unx    20642 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_three_way_partition.cuh
--rw-r--r--  2.0 unx    22728 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_unique_by_key.cuh
--rw-r--r--  2.0 unx     5730 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/grid/grid_barrier.cuh
--rw-r--r--  2.0 unx     8287 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/grid/grid_even_share.cuh
--rw-r--r--  2.0 unx     4696 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/grid/grid_mapping.cuh
--rw-r--r--  2.0 unx     7886 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/grid/grid_queue.cuh
--rw-r--r--  2.0 unx     4325 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/host/mutex.cuh
--rw-r--r--  2.0 unx     8668 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/arg_index_input_iterator.cuh
--rw-r--r--  2.0 unx     8008 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/cache_modified_input_iterator.cuh
--rw-r--r--  2.0 unx     8228 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/cache_modified_output_iterator.cuh
--rw-r--r--  2.0 unx     7558 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/constant_input_iterator.cuh
--rw-r--r--  2.0 unx     7277 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/counting_input_iterator.cuh
--rw-r--r--  2.0 unx     6543 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/discard_output_iterator.cuh
--rw-r--r--  2.0 unx    10891 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/tex_obj_input_iterator.cuh
--rw-r--r--  2.0 unx     4581 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/tex_ref_input_iterator.cuh
--rw-r--r--  2.0 unx     8378 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/iterator/transform_input_iterator.cuh
--rw-r--r--  2.0 unx    18053 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/thread/thread_load.cuh
--rw-r--r--  2.0 unx    11134 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/thread/thread_operators.cuh
--rw-r--r--  2.0 unx     6260 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/thread/thread_reduce.cuh
--rw-r--r--  2.0 unx    10435 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/thread/thread_scan.cuh
--rw-r--r--  2.0 unx     5630 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/thread/thread_search.cuh
--rw-r--r--  2.0 unx     3543 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/thread/thread_sort.cuh
--rw-r--r--  2.0 unx    17566 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/thread/thread_store.cuh
--rw-r--r--  2.0 unx    17966 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/warp_exchange.cuh
--rw-r--r--  2.0 unx    25456 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/warp_load.cuh
--rw-r--r--  2.0 unx     6341 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/warp_merge_sort.cuh
--rw-r--r--  2.0 unx    26349 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/warp_reduce.cuh
--rw-r--r--  2.0 unx    38677 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/warp_scan.cuh
--rw-r--r--  2.0 unx    20347 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/warp_store.cuh
--rw-r--r--  2.0 unx    24530 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_shfl.cuh
--rw-r--r--  2.0 unx    13923 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_smem.cuh
--rw-r--r--  2.0 unx    25037 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_shfl.cuh
--rw-r--r--  2.0 unx    15617 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_smem.cuh
--rw-r--r--  2.0 unx     2121 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__bsd_locale_defaults.h
--rw-r--r--  2.0 unx     4100 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__bsd_locale_fallbacks.h
--rw-r--r--  2.0 unx      755 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/complex.h
--rw-r--r--  2.0 unx     1165 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/ctype.h
--rw-r--r--  2.0 unx     5160 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/errno.h
--rw-r--r--  2.0 unx     1879 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/fenv.h
--rw-r--r--  2.0 unx     1688 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/float.h
--rw-r--r--  2.0 unx     3905 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/inttypes.h
--rw-r--r--  2.0 unx     1539 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/limits.h
--rw-r--r--  2.0 unx      792 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/locale.h
--rw-r--r--  2.0 unx    51607 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/math.h
--rw-r--r--  2.0 unx      818 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/setjmp.h
--rw-r--r--  2.0 unx      831 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdbool.h
--rw-r--r--  2.0 unx     1405 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stddef.h
--rw-r--r--  2.0 unx     2395 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdint.h
--rw-r--r--  2.0 unx     3541 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdio.h
--rw-r--r--  2.0 unx     3696 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdlib.h
--rw-r--r--  2.0 unx     4821 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/string.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/tgmath.h
--rw-r--r--  2.0 unx     8573 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wchar.h
--rw-r--r--  2.0 unx     1570 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wctype.h
--rw-r--r--  2.0 unx     1836 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/android/locale_bionic.h
--rw-r--r--  2.0 unx     9306 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_base.h
--rw-r--r--  2.0 unx     9126 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_c11.h
--rw-r--r--  2.0 unx    20331 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda.h
--rw-r--r--  2.0 unx     6885 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_derived.h
--rw-r--r--  2.0 unx   262265 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_generated.h
--rw-r--r--  2.0 unx      556 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_gcc.h
--rw-r--r--  2.0 unx    21895 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_msvc.h
--rw-r--r--  2.0 unx      561 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_nvrtc.h
--rw-r--r--  2.0 unx     1770 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_scopes.h
--rw-r--r--  2.0 unx     6422 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/cxx_atomic.h
--rw-r--r--  2.0 unx      719 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/fuchsia/xlocale.h
--rw-r--r--  2.0 unx     3622 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/limits.h
--rw-r--r--  2.0 unx     2466 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/locale_mgmt_aix.h
--rw-r--r--  2.0 unx     1705 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/support.h
--rw-r--r--  2.0 unx     5718 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/xlocale.h
--rw-r--r--  2.0 unx     1886 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/musl/xlocale.h
--rw-r--r--  2.0 unx      845 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/newlib/xlocale.h
--rw-r--r--  2.0 unx      476 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/floatingpoint.h
--rw-r--r--  2.0 unx     1230 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/wchar.h
--rw-r--r--  2.0 unx     2257 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/xlocale.h
--rw-r--r--  2.0 unx     2648 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/limits_msvc_win32.h
--rw-r--r--  2.0 unx     6858 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/locale_win32.h
--rw-r--r--  2.0 unx     1439 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__nop_locale_mgmt.h
--rw-r--r--  2.0 unx     4757 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__posix_l_fallback.h
--rw-r--r--  2.0 unx     2396 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__strtonum_fallback.h
--rw-r--r--  2.0 unx      806 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/addressof.h
--rw-r--r--  2.0 unx    11470 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/adjacent_difference.h
--rw-r--r--  2.0 unx     4146 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/advance.h
--rw-r--r--  2.0 unx    11786 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/allocate_unique.h
--rw-r--r--  2.0 unx    84960 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/binary_search.h
--rw-r--r--  2.0 unx    30032 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/complex.h
--rw-r--r--  2.0 unx    22187 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/copy.h
--rw-r--r--  2.0 unx     8688 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/count.h
--rw-r--r--  2.0 unx     3909 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_allocator.h
--rw-r--r--  2.0 unx     1419 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_delete.h
--rw-r--r--  2.0 unx     1713 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_free.h
--rw-r--r--  2.0 unx     1855 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_make_unique.h
--rw-r--r--  2.0 unx     2703 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_malloc.h
--rw-r--r--  2.0 unx     5901 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_malloc_allocator.h
--rw-r--r--  2.0 unx     2725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_new.h
--rw-r--r--  2.0 unx     5484 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_new_allocator.h
--rw-r--r--  2.0 unx     6033 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_ptr.h
--rw-r--r--  2.0 unx    28560 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_reference.h
--rw-r--r--  2.0 unx    17803 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/device_vector.h
--rw-r--r--  2.0 unx     2358 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/distance.h
--rw-r--r--  2.0 unx     9996 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/equal.h
--rw-r--r--  2.0 unx      813 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/event.h
--rw-r--r--  2.0 unx    12161 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/execution_policy.h
--rw-r--r--  2.0 unx    31413 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/extrema.h
--rw-r--r--  2.0 unx     7526 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/fill.h
--rw-r--r--  2.0 unx    11830 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/find.h
--rw-r--r--  2.0 unx    10406 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/for_each.h
--rw-r--r--  2.0 unx    55075 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/functional.h
--rw-r--r--  2.0 unx     5286 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/future.h
--rw-r--r--  2.0 unx    23135 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/gather.h
--rw-r--r--  2.0 unx     8286 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/generate.h
--rw-r--r--  2.0 unx    17906 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/host_vector.h
--rw-r--r--  2.0 unx    12051 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/inner_product.h
--rw-r--r--  2.0 unx      412 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/limits.h
--rw-r--r--  2.0 unx    10369 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/logical.h
--rw-r--r--  2.0 unx    15359 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/memory.h
--rw-r--r--  2.0 unx    39495 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/merge.h
--rw-r--r--  2.0 unx    11041 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mismatch.h
--rw-r--r--  2.0 unx    97945 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/optional.h
--rw-r--r--  2.0 unx     9424 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/pair.h
--rw-r--r--  2.0 unx    67577 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/partition.h
--rw-r--r--  2.0 unx     3724 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/per_device_resource.h
--rw-r--r--  2.0 unx     3773 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random.h
--rw-r--r--  2.0 unx    37631 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/reduce.h
--rw-r--r--  2.0 unx    37924 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/remove.h
--rw-r--r--  2.0 unx    33675 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/replace.h
--rw-r--r--  2.0 unx     8423 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/reverse.h
--rw-r--r--  2.0 unx    80567 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/scan.h
--rw-r--r--  2.0 unx    21699 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/scatter.h
--rw-r--r--  2.0 unx    11827 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/sequence.h
--rw-r--r--  2.0 unx   186894 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/set_operations.h
--rw-r--r--  2.0 unx     6664 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/shuffle.h
--rw-r--r--  2.0 unx    60965 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/sort.h
--rw-r--r--  2.0 unx     6737 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/swap.h
--rw-r--r--  2.0 unx     1454 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system_error.h
--rw-r--r--  2.0 unx     4785 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/tabulate.h
--rw-r--r--  2.0 unx    36715 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/transform.h
--rw-r--r--  2.0 unx     8316 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/transform_reduce.h
--rw-r--r--  2.0 unx    15301 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/transform_scan.h
--rw-r--r--  2.0 unx    20598 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/tuple.h
--rw-r--r--  2.0 unx    12752 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/uninitialized_copy.h
--rw-r--r--  2.0 unx    10409 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/uninitialized_fill.h
--rw-r--r--  2.0 unx    53968 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/unique.h
--rw-r--r--  2.0 unx     2684 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/universal_allocator.h
--rw-r--r--  2.0 unx      810 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/universal_ptr.h
--rw-r--r--  2.0 unx     1918 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/universal_vector.h
--rw-r--r--  2.0 unx     2848 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/version.h
--rw-r--r--  2.0 unx     6881 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/zip_function.h
--rw-r--r--  2.0 unx     3897 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/async/copy.h
--rw-r--r--  2.0 unx     2867 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/async/for_each.h
--rw-r--r--  2.0 unx    11680 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/async/reduce.h
--rw-r--r--  2.0 unx     9648 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/async/scan.h
--rw-r--r--  2.0 unx     6915 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/async/sort.h
--rw-r--r--  2.0 unx     3152 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/async/transform.h
--rw-r--r--  2.0 unx     3376 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/adjacent_difference.inl
--rw-r--r--  2.0 unx     2085 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/advance.inl
--rw-r--r--  2.0 unx     1087 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/algorithm_wrapper.h
--rw-r--r--  2.0 unx     8099 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/alignment.h
--rw-r--r--  2.0 unx     2793 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator_aware_execution_policy.h
--rw-r--r--  2.0 unx    19330 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/binary_search.inl
--rw-r--r--  2.0 unx     1329 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/caching_allocator.h
--rw-r--r--  2.0 unx      768 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config.h
--rw-r--r--  2.0 unx     7398 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/contiguous_storage.h
--rw-r--r--  2.0 unx    16225 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/contiguous_storage.inl
--rw-r--r--  2.0 unx     2924 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/copy.h
--rw-r--r--  2.0 unx     4690 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/copy.inl
--rw-r--r--  2.0 unx     2369 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/copy_if.h
--rw-r--r--  2.0 unx     3758 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/copy_if.inl
--rw-r--r--  2.0 unx     1999 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/count.h
--rw-r--r--  2.0 unx     2831 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/count.inl
--rw-r--r--  2.0 unx      893 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/cpp11_required.h
--rw-r--r--  2.0 unx      892 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/cpp14_required.h
--rw-r--r--  2.0 unx     2464 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/cstdint.h
--rw-r--r--  2.0 unx     2827 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/dependencies_aware_execution_policy.h
--rw-r--r--  2.0 unx     1233 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/device_delete.inl
--rw-r--r--  2.0 unx     1177 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/device_free.inl
--rw-r--r--  2.0 unx     1596 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/device_malloc.inl
--rw-r--r--  2.0 unx     1664 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/device_new.inl
--rw-r--r--  2.0 unx     1703 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/device_ptr.inl
--rw-r--r--  2.0 unx     1135 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/distance.inl
--rw-r--r--  2.0 unx     2918 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/equal.inl
--rw-r--r--  2.0 unx     4450 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/event_error.h
--rw-r--r--  2.0 unx     5260 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/execute_with_allocator.h
--rw-r--r--  2.0 unx     3131 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/execute_with_allocator_fwd.h
--rw-r--r--  2.0 unx     7813 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/execute_with_dependencies.h
--rw-r--r--  2.0 unx     2115 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/execution_policy.h
--rw-r--r--  2.0 unx     6164 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/extrema.inl
--rw-r--r--  2.0 unx     2730 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/fill.inl
--rw-r--r--  2.0 unx     3633 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/find.inl
--rw-r--r--  2.0 unx     2892 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/for_each.inl
--rw-r--r--  2.0 unx     4752 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/function.h
--rw-r--r--  2.0 unx     4292 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional.inl
--rw-r--r--  2.0 unx     6932 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/gather.inl
--rw-r--r--  2.0 unx     2899 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/generate.inl
--rw-r--r--  2.0 unx     2005 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/get_iterator_value.h
--rw-r--r--  2.0 unx     3771 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/inner_product.inl
--rw-r--r--  2.0 unx     3653 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/integer_math.h
--rw-r--r--  2.0 unx     3006 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/integer_traits.h
--rw-r--r--  2.0 unx    13655 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/internal_functional.h
--rw-r--r--  2.0 unx     3245 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/logical.inl
--rw-r--r--  2.0 unx     2738 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/malloc_and_free.h
--rw-r--r--  2.0 unx     5928 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/memory_algorithms.h
--rw-r--r--  2.0 unx     1304 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/memory_wrapper.h
--rw-r--r--  2.0 unx     9084 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/merge.inl
--rw-r--r--  2.0 unx     1465 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/minmax.h
--rw-r--r--  2.0 unx     3765 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/mismatch.inl
--rw-r--r--  2.0 unx      893 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/modern_gcc_required.h
--rw-r--r--  2.0 unx     3438 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/numeric_traits.h
--rw-r--r--  2.0 unx     1085 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/numeric_wrapper.h
--rw-r--r--  2.0 unx     4307 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/overlapped_copy.h
--rw-r--r--  2.0 unx     5007 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/pair.inl
--rw-r--r--  2.0 unx    15177 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/partition.inl
--rw-r--r--  2.0 unx     9240 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/pointer.h
--rw-r--r--  2.0 unx     6755 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/pointer.inl
--rw-r--r--  2.0 unx    42969 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/preprocessor.h
--rw-r--r--  2.0 unx     1542 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/raw_pointer_cast.h
--rw-r--r--  2.0 unx     8069 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/raw_reference_cast.h
--rw-r--r--  2.0 unx     9632 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/reduce.inl
--rw-r--r--  2.0 unx    14913 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/reference.h
--rw-r--r--  2.0 unx      848 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/reference_forward_declaration.h
--rw-r--r--  2.0 unx     8570 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/remove.inl
--rw-r--r--  2.0 unx     8650 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/replace.inl
--rw-r--r--  2.0 unx     2974 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/reverse.inl
--rw-r--r--  2.0 unx    20546 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/scan.inl
--rw-r--r--  2.0 unx     5726 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/scatter.inl
--rw-r--r--  2.0 unx     2514 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/select_system.h
--rw-r--r--  2.0 unx     1460 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/seq.h
--rw-r--r--  2.0 unx     3537 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/sequence.inl
--rw-r--r--  2.0 unx    41943 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/set_operations.inl
--rw-r--r--  2.0 unx     2905 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/shuffle.inl
--rw-r--r--  2.0 unx    13901 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/sort.inl
--rw-r--r--  2.0 unx     3156 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/static_assert.h
--rw-r--r--  2.0 unx     4363 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/static_map.h
--rw-r--r--  2.0 unx      930 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/swap.h
--rw-r--r--  2.0 unx      731 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/swap.inl
--rw-r--r--  2.0 unx     2155 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/swap_ranges.inl
--rw-r--r--  2.0 unx     1883 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/tabulate.inl
--rw-r--r--  2.0 unx     5245 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/temporary_array.h
--rw-r--r--  2.0 unx     5105 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/temporary_array.inl
--rw-r--r--  2.0 unx     2865 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/temporary_buffer.h
--rw-r--r--  2.0 unx     9221 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/transform.inl
--rw-r--r--  2.0 unx     2385 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/transform_reduce.inl
--rw-r--r--  2.0 unx     4651 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/transform_scan.inl
--rw-r--r--  2.0 unx     3050 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/trivial_sequence.h
--rw-r--r--  2.0 unx    30303 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/tuple.inl
--rw-r--r--  2.0 unx     2869 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/tuple_algorithms.h
--rw-r--r--  2.0 unx     1833 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/tuple_meta_transform.h
--rw-r--r--  2.0 unx     2577 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/tuple_transform.h
--rw-r--r--  2.0 unx     3697 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_deduction.h
--rw-r--r--  2.0 unx    21607 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits.h
--rw-r--r--  2.0 unx     3481 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/uninitialized_copy.inl
--rw-r--r--  2.0 unx     3080 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/uninitialized_fill.inl
--rw-r--r--  2.0 unx    14409 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/unique.inl
--rw-r--r--  2.0 unx      737 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/use_default.h
--rw-r--r--  2.0 unx    22957 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/vector_base.h
--rw-r--r--  2.0 unx    37715 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/vector_base.inl
--rw-r--r--  2.0 unx    13771 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/allocator_traits.h
--rw-r--r--  2.0 unx    12771 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/allocator_traits.inl
--rw-r--r--  2.0 unx     1632 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/copy_construct_range.h
--rw-r--r--  2.0 unx    11114 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/copy_construct_range.inl
--rw-r--r--  2.0 unx      968 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/default_construct_range.h
--rw-r--r--  2.0 unx     3139 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/default_construct_range.inl
--rw-r--r--  2.0 unx      947 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/destroy_range.h
--rw-r--r--  2.0 unx     4495 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/destroy_range.inl
--rw-r--r--  2.0 unx      989 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/fill_construct_range.h
--rw-r--r--  2.0 unx     3083 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/fill_construct_range.inl
--rw-r--r--  2.0 unx     1388 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/malloc_allocator.h
--rw-r--r--  2.0 unx     1992 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/malloc_allocator.inl
--rw-r--r--  2.0 unx     1861 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/no_throw_allocator.h
--rw-r--r--  2.0 unx     3886 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/tagged_allocator.h
--rw-r--r--  2.0 unx     2656 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/tagged_allocator.inl
--rw-r--r--  2.0 unx     2325 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/temporary_allocator.h
--rw-r--r--  2.0 unx     2481 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/allocator/temporary_allocator.inl
--rw-r--r--  2.0 unx     7437 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/arithmetic.h
--rw-r--r--  2.0 unx     4475 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/c99math.h
--rw-r--r--  2.0 unx    24185 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/catrig.h
--rw-r--r--  2.0 unx    14279 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/catrigf.h
--rw-r--r--  2.0 unx     7222 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/ccosh.h
--rw-r--r--  2.0 unx     4624 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/ccoshf.h
--rw-r--r--  2.0 unx     5818 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/cexp.h
--rw-r--r--  2.0 unx     5039 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/cexpf.h
--rw-r--r--  2.0 unx     5851 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/clog.h
--rw-r--r--  2.0 unx     5387 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/clogf.h
--rw-r--r--  2.0 unx     8058 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/complex.inl
--rw-r--r--  2.0 unx     1695 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/cpow.h
--rw-r--r--  2.0 unx     1892 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/cproj.h
--rw-r--r--  2.0 unx     6787 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/csinh.h
--rw-r--r--  2.0 unx     4567 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/csinhf.h
--rw-r--r--  2.0 unx     4620 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/csqrt.h
--rw-r--r--  2.0 unx     4526 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/csqrtf.h
--rw-r--r--  2.0 unx     6117 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/ctanh.h
--rw-r--r--  2.0 unx     3802 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/ctanhf.h
--rw-r--r--  2.0 unx     3203 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/math_private.h
--rw-r--r--  2.0 unx     1725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/complex/stream.h
--rw-r--r--  2.0 unx     8378 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/compiler.h
--rw-r--r--  2.0 unx     2041 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/compiler_fence.h
--rw-r--r--  2.0 unx     1478 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/config.h
--rw-r--r--  2.0 unx     3806 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/cpp_compatibility.h
--rw-r--r--  2.0 unx     5461 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/cpp_dialect.h
--rw-r--r--  2.0 unx      956 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/debug.h
--rw-r--r--  2.0 unx     1437 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/deprecated.h
--rw-r--r--  2.0 unx     1575 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/device_system.h
--rw-r--r--  2.0 unx     1329 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/exec_check_disable.h
--rw-r--r--  2.0 unx      896 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/forceinline.h
--rw-r--r--  2.0 unx      995 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/global_workarounds.h
--rw-r--r--  2.0 unx     1278 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/host_device.h
--rw-r--r--  2.0 unx     1386 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/host_system.h
--rw-r--r--  2.0 unx     1222 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/memory_resource.h
--rw-r--r--  2.0 unx     4173 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/namespace.h
--rw-r--r--  2.0 unx      897 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/config/simple_defines.h
--rw-r--r--  2.0 unx     3975 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/actor.h
--rw-r--r--  2.0 unx     3249 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/actor.inl
--rw-r--r--  2.0 unx     1613 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/argument.h
--rw-r--r--  2.0 unx     4163 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/composite.h
--rw-r--r--  2.0 unx     1015 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators.h
--rw-r--r--  2.0 unx      970 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/placeholder.h
--rw-r--r--  2.0 unx     1523 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/value.h
--rw-r--r--  2.0 unx    10319 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators/arithmetic_operators.h
--rw-r--r--  2.0 unx     2164 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators/assignment_operator.h
--rw-r--r--  2.0 unx     8009 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators/bitwise_operators.h
--rw-r--r--  2.0 unx    12970 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators/compound_assignment_operators.h
--rw-r--r--  2.0 unx     3583 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators/logical_operators.h
--rw-r--r--  2.0 unx     3747 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators/operator_adaptors.h
--rw-r--r--  2.0 unx     7904 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/functional/operators/relational_operators.h
--rw-r--r--  2.0 unx     3039 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/mpl/math.h
--rw-r--r--  2.0 unx     7043 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/range/head_flags.h
--rw-r--r--  2.0 unx     3933 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/range/tail_flags.h
--rw-r--r--  2.0 unx     3375 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/function_traits.h
--rw-r--r--  2.0 unx     1933 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_member_function.h
--rw-r--r--  2.0 unx     1135 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_nested_type.h
--rw-r--r--  2.0 unx     1466 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_trivial_assign.h
--rw-r--r--  2.0 unx    16096 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/is_call_possible.h
--rw-r--r--  2.0 unx     1094 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/is_metafunction_defined.h
--rw-r--r--  2.0 unx     4445 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/minimum_type.h
--rw-r--r--  2.0 unx    11185 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/pointer_traits.h
--rw-r--r--  2.0 unx     1743 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/result_of_adaptable_function.h
--rw-r--r--  2.0 unx     1073 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/iterator/is_discard_iterator.h
--rw-r--r--  2.0 unx     1755 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/type_traits/iterator/is_output_iterator.h
--rw-r--r--  2.0 unx     1360 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/detail/util/align.h
--rw-r--r--  2.0 unx     8335 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/constant_iterator.h
--rw-r--r--  2.0 unx     8164 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/counting_iterator.h
--rw-r--r--  2.0 unx     4968 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/discard_iterator.h
--rw-r--r--  2.0 unx     8353 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/iterator_adaptor.h
--rw-r--r--  2.0 unx     9225 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/iterator_categories.h
--rw-r--r--  2.0 unx    22014 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/iterator_facade.h
--rw-r--r--  2.0 unx     1948 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/iterator_traits.h
--rw-r--r--  2.0 unx     7252 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/permutation_iterator.h
--rw-r--r--  2.0 unx     2379 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/retag.h
--rw-r--r--  2.0 unx     7185 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/reverse_iterator.h
--rw-r--r--  2.0 unx     5697 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/transform_input_output_iterator.h
--rw-r--r--  2.0 unx    11679 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/transform_iterator.h
--rw-r--r--  2.0 unx     5212 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/transform_output_iterator.h
--rw-r--r--  2.0 unx     8303 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/zip_iterator.h
--rw-r--r--  2.0 unx     1196 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/any_assign.h
--rw-r--r--  2.0 unx     1006 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/any_system_tag.h
--rw-r--r--  2.0 unx     2159 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/constant_iterator_base.h
--rw-r--r--  2.0 unx     4469 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/counting_iterator.inl
--rw-r--r--  2.0 unx     1033 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/device_system_tag.h
--rw-r--r--  2.0 unx     1742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/discard_iterator_base.h
--rw-r--r--  2.0 unx     1228 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/distance_from_result.h
--rw-r--r--  2.0 unx     1019 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/host_system_tag.h
--rw-r--r--  2.0 unx     1611 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/is_iterator_category.h
--rw-r--r--  2.0 unx     2713 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_adaptor_base.h
--rw-r--r--  2.0 unx     2457 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_category_to_system.h
--rw-r--r--  2.0 unx     4066 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_category_to_traversal.h
--rw-r--r--  2.0 unx     1746 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_category_with_system_and_traversal.h
--rw-r--r--  2.0 unx     9981 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_facade_category.h
--rw-r--r--  2.0 unx     3578 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_traits.inl
--rw-r--r--  2.0 unx     1108 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_traversal_tags.h
--rw-r--r--  2.0 unx     4098 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/join_iterator.h
--rw-r--r--  2.0 unx     1873 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/minimum_category.h
--rw-r--r--  2.0 unx     2900 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/minimum_system.h
--rw-r--r--  2.0 unx     2005 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/normal_iterator.h
--rw-r--r--  2.0 unx     1611 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/permutation_iterator_base.h
--rw-r--r--  2.0 unx     3800 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/retag.h
--rw-r--r--  2.0 unx     3494 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/reverse_iterator.inl
--rw-r--r--  2.0 unx     1119 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/reverse_iterator_base.h
--rw-r--r--  2.0 unx     2550 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/tagged_iterator.h
--rw-r--r--  2.0 unx     3433 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/transform_input_output_iterator.inl
--rw-r--r--  2.0 unx     2680 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/transform_iterator.inl
--rw-r--r--  2.0 unx     2395 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/transform_output_iterator.inl
--rw-r--r--  2.0 unx     3978 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/tuple_of_iterator_references.h
--rw-r--r--  2.0 unx     2475 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/universal_categories.h
--rw-r--r--  2.0 unx     4335 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/zip_iterator.inl
--rw-r--r--  2.0 unx     8879 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/iterator/detail/zip_iterator_base.h
--rw-r--r--  2.0 unx     8829 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/allocator.h
--rw-r--r--  2.0 unx     1311 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/device_memory_resource.h
--rw-r--r--  2.0 unx    17230 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/disjoint_pool.h
--rw-r--r--  2.0 unx     3712 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/disjoint_sync_pool.h
--rw-r--r--  2.0 unx     2064 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/disjoint_tls_pool.h
--rw-r--r--  2.0 unx     1753 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/fancy_pointer_resource.h
--rw-r--r--  2.0 unx     1041 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/host_memory_resource.h
--rw-r--r--  2.0 unx     7471 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/memory_resource.h
--rw-r--r--  2.0 unx     2987 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/new.h
--rw-r--r--  2.0 unx     1605 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/polymorphic_adaptor.h
--rw-r--r--  2.0 unx    19640 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/pool.h
--rw-r--r--  2.0 unx     5017 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/pool_options.h
--rw-r--r--  2.0 unx     3296 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/sync_pool.h
--rw-r--r--  2.0 unx     1744 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/tls_pool.h
--rw-r--r--  2.0 unx      714 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/universal_memory_resource.h
--rw-r--r--  2.0 unx     1249 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/mr/validator.h
--rw-r--r--  2.0 unx     8399 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/discard_block_engine.h
--rw-r--r--  2.0 unx     9594 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/linear_congruential_engine.h
--rw-r--r--  2.0 unx     7463 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/linear_feedback_shift_engine.h
--rw-r--r--  2.0 unx     9535 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/normal_distribution.h
--rw-r--r--  2.0 unx     8583 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/subtract_with_carry_engine.h
--rw-r--r--  2.0 unx     9527 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/uniform_int_distribution.h
--rw-r--r--  2.0 unx     9580 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/uniform_real_distribution.h
--rw-r--r--  2.0 unx     9200 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/xor_combine_engine.h
--rw-r--r--  2.0 unx     5053 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/discard_block_engine.inl
--rw-r--r--  2.0 unx     4910 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/linear_congruential_engine.inl
--rw-r--r--  2.0 unx     3183 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/linear_congruential_engine_discard.h
--rw-r--r--  2.0 unx     4962 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/linear_feedback_shift_engine.inl
--rw-r--r--  2.0 unx     1194 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/linear_feedback_shift_engine_wordmask.h
--rw-r--r--  2.0 unx     1757 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/mod.h
--rw-r--r--  2.0 unx     6499 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/normal_distribution.inl
--rw-r--r--  2.0 unx     4200 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/normal_distribution_base.h
--rw-r--r--  2.0 unx     1334 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/random_core_access.h
--rw-r--r--  2.0 unx     5896 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/subtract_with_carry_engine.inl
--rw-r--r--  2.0 unx     6754 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/uniform_int_distribution.inl
--rw-r--r--  2.0 unx     6699 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/uniform_real_distribution.inl
--rw-r--r--  2.0 unx     6274 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/xor_combine_engine.inl
--rw-r--r--  2.0 unx     7961 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/random/detail/xor_combine_engine_max.h
--rw-r--r--  2.0 unx    18347 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/error_code.h
--rw-r--r--  2.0 unx     5649 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/system_error.h
--rw-r--r--  2.0 unx     5152 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/execution_policy.h
--rw-r--r--  2.0 unx     3356 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/memory.h
--rw-r--r--  2.0 unx     2007 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/memory_resource.h
--rw-r--r--  2.0 unx     3773 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/pointer.h
--rw-r--r--  2.0 unx     3166 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/vector.h
--rw-r--r--  2.0 unx      777 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/adjacent_difference.h
--rw-r--r--  2.0 unx      763 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/assign_value.h
--rw-r--r--  2.0 unx      801 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/binary_search.h
--rw-r--r--  2.0 unx      747 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/copy.h
--rw-r--r--  2.0 unx      753 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/copy_if.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/count.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/equal.h
--rw-r--r--  2.0 unx     2075 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/execution_policy.h
--rw-r--r--  2.0 unx      764 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/extrema.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/fill.h
--rw-r--r--  2.0 unx      747 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/find.h
--rw-r--r--  2.0 unx      755 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/for_each.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/gather.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/generate.h
--rw-r--r--  2.0 unx      757 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/get_value.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/inner_product.h
--rw-r--r--  2.0 unx      757 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/iter_swap.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/logical.h
--rw-r--r--  2.0 unx      767 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/malloc_and_free.h
--rw-r--r--  2.0 unx     1346 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/memory.inl
--rw-r--r--  2.0 unx      749 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/merge.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/mismatch.h
--rw-r--r--  2.0 unx     1340 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/par.h
--rw-r--r--  2.0 unx      757 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/partition.h
--rw-r--r--  2.0 unx      723 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/per_device_resource.h
--rw-r--r--  2.0 unx      751 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/reduce.h
--rw-r--r--  2.0 unx      765 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/reduce_by_key.h
--rw-r--r--  2.0 unx      751 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/remove.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/replace.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/reverse.h
--rw-r--r--  2.0 unx      747 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/scan.h
--rw-r--r--  2.0 unx      776 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/scan_by_key.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/scatter.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/sequence.h
--rw-r--r--  2.0 unx      771 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/set_operations.h
--rw-r--r--  2.0 unx      747 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/sort.h
--rw-r--r--  2.0 unx      702 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/swap_ranges.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/tabulate.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/temporary_buffer.h
--rw-r--r--  2.0 unx      700 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform_reduce.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform_scan.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/uninitialized_copy.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/uninitialized_fill.h
--rw-r--r--  2.0 unx      751 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/unique.h
--rw-r--r--  2.0 unx      765 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/unique_by_key.h
--rw-r--r--  2.0 unx     3023 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cpp/detail/vector.inl
--rw-r--r--  2.0 unx     5328 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/config.h
--rw-r--r--  2.0 unx     7603 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/error.h
--rw-r--r--  2.0 unx     1889 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/execution_policy.h
--rw-r--r--  2.0 unx     1529 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/future.h
--rw-r--r--  2.0 unx     3672 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/memory.h
--rw-r--r--  2.0 unx     3903 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/memory_resource.h
--rw-r--r--  2.0 unx     4433 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/pointer.h
--rw-r--r--  2.0 unx     3269 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/vector.h
--rw-r--r--  2.0 unx    11691 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/adjacent_difference.h
--rw-r--r--  2.0 unx     2975 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/assign_value.h
--rw-r--r--  2.0 unx      669 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/binary_search.h
--rw-r--r--  2.0 unx     3310 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/cdp_dispatch.h
--rw-r--r--  2.0 unx     6472 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/copy.h
--rw-r--r--  2.0 unx    29007 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/copy_if.h
--rw-r--r--  2.0 unx     3412 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/count.h
--rw-r--r--  2.0 unx    11581 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/cross_system.h
--rw-r--r--  2.0 unx     3678 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/dispatch.h
--rw-r--r--  2.0 unx     2990 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/equal.h
--rw-r--r--  2.0 unx     2358 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/error.inl
--rw-r--r--  2.0 unx     3185 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/execution_policy.h
--rw-r--r--  2.0 unx    19192 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/extrema.h
--rw-r--r--  2.0 unx     3288 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/fill.h
--rw-r--r--  2.0 unx     7127 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/find.h
--rw-r--r--  2.0 unx     3740 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/for_each.h
--rw-r--r--  2.0 unx    34440 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/future.inl
--rw-r--r--  2.0 unx     4134 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/gather.h
--rw-r--r--  2.0 unx     3305 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/generate.h
--rw-r--r--  2.0 unx     2538 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/get_value.h
--rw-r--r--  2.0 unx     1185 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/guarded_cuda_runtime_api.h
--rw-r--r--  2.0 unx     1925 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/guarded_driver_types.h
--rw-r--r--  2.0 unx     3886 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/inner_product.h
--rw-r--r--  2.0 unx     1716 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/iter_swap.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/logical.h
--rw-r--r--  2.0 unx     1221 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/make_unsigned_special.h
--rw-r--r--  2.0 unx     3728 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/malloc_and_free.h
--rw-r--r--  2.0 unx     1378 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/memory.inl
--rw-r--r--  2.0 unx    35370 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/merge.h
--rw-r--r--  2.0 unx     4575 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/mismatch.h
--rw-r--r--  2.0 unx     8060 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/par.h
--rw-r--r--  2.0 unx     3070 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/par_to_seq.h
--rw-r--r--  2.0 unx     5683 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/parallel_for.h
--rw-r--r--  2.0 unx    38777 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/partition.h
--rw-r--r--  2.0 unx     2637 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/per_device_resource.h
--rw-r--r--  2.0 unx    39414 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce.h
--rw-r--r--  2.0 unx    46028 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce_by_key.h
--rw-r--r--  2.0 unx     4764 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/remove.h
--rw-r--r--  2.0 unx     7294 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/replace.h
--rw-r--r--  2.0 unx     3770 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/reverse.h
--rw-r--r--  2.0 unx    14325 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scan.h
--rw-r--r--  2.0 unx    18657 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scan_by_key.h
--rw-r--r--  2.0 unx     3980 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scatter.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/sequence.h
--rw-r--r--  2.0 unx    69146 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/set_operations.h
--rw-r--r--  2.0 unx    24404 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/sort.h
--rw-r--r--  2.0 unx     3813 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/swap_ranges.h
--rw-r--r--  2.0 unx     3145 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/tabulate.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/temporary_buffer.h
--rw-r--r--  2.0 unx     2218 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/terminate.h
--rw-r--r--  2.0 unx    13521 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform.h
--rw-r--r--  2.0 unx     3052 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform_reduce.h
--rw-r--r--  2.0 unx     4866 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform_scan.h
--rw-r--r--  2.0 unx     4129 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/uninitialized_copy.h
--rw-r--r--  2.0 unx     3924 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/uninitialized_fill.h
--rw-r--r--  2.0 unx    28154 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/unique.h
--rw-r--r--  2.0 unx    32569 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/unique_by_key.h
--rw-r--r--  2.0 unx    16539 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/util.h
--rw-r--r--  2.0 unx    15870 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/copy.h
--rw-r--r--  2.0 unx     4424 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/customization.h
--rw-r--r--  2.0 unx     7117 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/exclusive_scan.h
--rw-r--r--  2.0 unx     4562 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/for_each.h
--rw-r--r--  2.0 unx     6887 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/inclusive_scan.h
--rw-r--r--  2.0 unx     9060 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/reduce.h
--rw-r--r--  2.0 unx     1920 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/scan.h
--rw-r--r--  2.0 unx    13297 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/sort.h
--rw-r--r--  2.0 unx     4865 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/transform.h
--rw-r--r--  2.0 unx    57014 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/agent_launcher.h
--rw-r--r--  2.0 unx     4227 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/alignment.h
--rw-r--r--  2.0 unx     4949 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/triple_chevron_launch.h
--rw-r--r--  2.0 unx    25804 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/util.h
--rw-r--r--  2.0 unx     9487 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/internal/copy_cross_system.h
--rw-r--r--  2.0 unx     2788 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/cuda/detail/internal/copy_device_to_device.h
--rw-r--r--  2.0 unx     1337 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/bad_alloc.h
--rw-r--r--  2.0 unx     4271 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/errno.h
--rw-r--r--  2.0 unx     9628 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/error_category.inl
--rw-r--r--  2.0 unx     4539 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/error_code.inl
--rw-r--r--  2.0 unx     3203 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/error_condition.inl
--rw-r--r--  2.0 unx     2346 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/system_error.inl
--rw-r--r--  2.0 unx     1839 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/adjacent_difference.h
--rw-r--r--  2.0 unx     1734 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/assign_value.h
--rw-r--r--  2.0 unx     1749 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/binary_search.h
--rw-r--r--  2.0 unx     1614 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/copy.h
--rw-r--r--  2.0 unx     1664 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/copy_if.h
--rw-r--r--  2.0 unx     1630 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/count.h
--rw-r--r--  2.0 unx     1630 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/equal.h
--rw-r--r--  2.0 unx     1662 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/extrema.h
--rw-r--r--  2.0 unx     1614 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/fill.h
--rw-r--r--  2.0 unx     1614 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/find.h
--rw-r--r--  2.0 unx     1674 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/for_each.h
--rw-r--r--  2.0 unx     1644 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/gather.h
--rw-r--r--  2.0 unx     1674 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/generate.h
--rw-r--r--  2.0 unx     1689 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/get_value.h
--rw-r--r--  2.0 unx     1749 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/inner_product.h
--rw-r--r--  2.0 unx     1689 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/iter_swap.h
--rw-r--r--  2.0 unx     1659 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/logical.h
--rw-r--r--  2.0 unx     1779 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/malloc_and_free.h
--rw-r--r--  2.0 unx     1629 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/merge.h
--rw-r--r--  2.0 unx     1661 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/mismatch.h
--rw-r--r--  2.0 unx     1689 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/partition.h
--rw-r--r--  2.0 unx     1647 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/per_device_resource.h
--rw-r--r--  2.0 unx     1644 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/reduce.h
--rw-r--r--  2.0 unx     1749 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/reduce_by_key.h
--rw-r--r--  2.0 unx     1644 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/remove.h
--rw-r--r--  2.0 unx     1659 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/replace.h
--rw-r--r--  2.0 unx     1659 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/reverse.h
--rw-r--r--  2.0 unx     1601 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/scan.h
--rw-r--r--  2.0 unx     1719 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/scan_by_key.h
--rw-r--r--  2.0 unx     1659 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/scatter.h
--rw-r--r--  2.0 unx     1674 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/sequence.h
--rw-r--r--  2.0 unx     1764 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/set_operations.h
--rw-r--r--  2.0 unx     1614 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/sort.h
--rw-r--r--  2.0 unx     1719 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/swap_ranges.h
--rw-r--r--  2.0 unx     1674 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/tabulate.h
--rw-r--r--  2.0 unx     1825 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/temporary_buffer.h
--rw-r--r--  2.0 unx     1689 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/transform.h
--rw-r--r--  2.0 unx     1794 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/transform_reduce.h
--rw-r--r--  2.0 unx     1764 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/transform_scan.h
--rw-r--r--  2.0 unx     1824 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/uninitialized_copy.h
--rw-r--r--  2.0 unx     1824 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/uninitialized_fill.h
--rw-r--r--  2.0 unx     1644 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/unique.h
--rw-r--r--  2.0 unx     1749 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/unique_by_key.h
--rw-r--r--  2.0 unx     1315 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/copy.h
--rw-r--r--  2.0 unx     1359 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/for_each.h
--rw-r--r--  2.0 unx     1337 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/reduce.h
--rw-r--r--  2.0 unx     1316 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/scan.h
--rw-r--r--  2.0 unx     1315 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/sort.h
--rw-r--r--  2.0 unx     1375 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/transform.h
--rw-r--r--  2.0 unx     1786 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/adjacent_difference.h
--rw-r--r--  2.0 unx     2697 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/adjacent_difference.inl
--rw-r--r--  2.0 unx     1021 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/advance.h
--rw-r--r--  2.0 unx     1744 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/advance.inl
--rw-r--r--  2.0 unx     6884 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/binary_search.h
--rw-r--r--  2.0 unx    14695 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/binary_search.inl
--rw-r--r--  2.0 unx     1594 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy.h
--rw-r--r--  2.0 unx     2690 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy.inl
--rw-r--r--  2.0 unx     1850 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy_if.h
--rw-r--r--  2.0 unx     5234 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy_if.inl
--rw-r--r--  2.0 unx     1530 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/count.h
--rw-r--r--  2.0 unx     2473 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/count.inl
--rw-r--r--  2.0 unx     1133 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/distance.h
--rw-r--r--  2.0 unx     2124 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/distance.inl
--rw-r--r--  2.0 unx     1467 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/equal.h
--rw-r--r--  2.0 unx     2020 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/equal.inl
--rw-r--r--  2.0 unx     3080 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/extrema.h
--rw-r--r--  2.0 unx     9522 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/extrema.inl
--rw-r--r--  2.0 unx     1814 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/fill.h
--rw-r--r--  2.0 unx     1820 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/find.h
--rw-r--r--  2.0 unx     4606 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/find.inl
--rw-r--r--  2.0 unx     2155 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/for_each.h
--rw-r--r--  2.0 unx     2915 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/gather.h
--rw-r--r--  2.0 unx     4258 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/gather.inl
--rw-r--r--  2.0 unx     1595 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/generate.h
--rw-r--r--  2.0 unx     3865 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/generate.inl
--rw-r--r--  2.0 unx     1894 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/inner_product.h
--rw-r--r--  2.0 unx     2626 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/inner_product.inl
--rw-r--r--  2.0 unx     1828 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/logical.h
--rw-r--r--  2.0 unx     2078 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/memory.h
--rw-r--r--  2.0 unx     2876 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/memory.inl
--rw-r--r--  2.0 unx     3335 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/merge.h
--rw-r--r--  2.0 unx     5275 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/merge.inl
--rw-r--r--  2.0 unx     1653 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/mismatch.h
--rw-r--r--  2.0 unx     2479 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/mismatch.inl
--rw-r--r--  2.0 unx     5622 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/partition.h
--rw-r--r--  2.0 unx     8845 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/partition.inl
--rw-r--r--  2.0 unx     1181 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/per_device_resource.h
--rw-r--r--  2.0 unx     1712 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce.h
--rw-r--r--  2.0 unx     2374 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce.inl
--rw-r--r--  2.0 unx     2862 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce_by_key.h
--rw-r--r--  2.0 unx     7101 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce_by_key.inl
--rw-r--r--  2.0 unx     3501 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/remove.h
--rw-r--r--  2.0 unx     4852 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/remove.inl
--rw-r--r--  2.0 unx     3478 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/replace.h
--rw-r--r--  2.0 unx     5734 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/replace.inl
--rw-r--r--  2.0 unx     1566 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/reverse.h
--rw-r--r--  2.0 unx     2340 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/reverse.inl
--rw-r--r--  2.0 unx     3226 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan.h
--rw-r--r--  2.0 unx     4151 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan.inl
--rw-r--r--  2.0 unx     5309 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan_by_key.h
--rw-r--r--  2.0 unx     9479 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan_by_key.inl
--rw-r--r--  2.0 unx     2330 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scatter.h
--rw-r--r--  2.0 unx     3165 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scatter.inl
--rw-r--r--  2.0 unx     4713 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/select_system.h
--rw-r--r--  2.0 unx     6033 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/select_system.inl
--rw-r--r--  2.0 unx     4985 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/select_system_exists.h
--rw-r--r--  2.0 unx     1723 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/sequence.h
--rw-r--r--  2.0 unx     2718 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/sequence.inl
--rw-r--r--  2.0 unx    15559 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/set_operations.h
--rw-r--r--  2.0 unx    22743 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/set_operations.inl
--rw-r--r--  2.0 unx     1624 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/shuffle.h
--rw-r--r--  2.0 unx     6848 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/shuffle.inl
--rw-r--r--  2.0 unx     5028 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/sort.h
--rw-r--r--  2.0 unx     7399 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/sort.inl
--rw-r--r--  2.0 unx     1326 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/swap_ranges.h
--rw-r--r--  2.0 unx     2397 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/swap_ranges.inl
--rw-r--r--  2.0 unx     1258 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/tabulate.h
--rw-r--r--  2.0 unx     2056 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/tabulate.inl
--rw-r--r--  2.0 unx     1153 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/tag.h
--rw-r--r--  2.0 unx     1704 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/temporary_buffer.h
--rw-r--r--  2.0 unx     2948 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/temporary_buffer.inl
--rw-r--r--  2.0 unx     3726 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform.h
--rw-r--r--  2.0 unx     7211 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform.inl
--rw-r--r--  2.0 unx     1487 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_reduce.h
--rw-r--r--  2.0 unx     1775 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_reduce.inl
--rw-r--r--  2.0 unx     2252 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_scan.h
--rw-r--r--  2.0 unx     3503 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_scan.inl
--rw-r--r--  2.0 unx     1755 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_copy.h
--rw-r--r--  2.0 unx     6897 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_copy.inl
--rw-r--r--  2.0 unx     1661 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_fill.h
--rw-r--r--  2.0 unx     4809 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_fill.inl
--rw-r--r--  2.0 unx     2998 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique.h
--rw-r--r--  2.0 unx     4641 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique.inl
--rw-r--r--  2.0 unx     3078 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique_by_key.h
--rw-r--r--  2.0 unx     5316 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique_by_key.inl
--rw-r--r--  2.0 unx     2673 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scalar/binary_search.h
--rw-r--r--  2.0 unx     4320 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/generic/scalar/binary_search.inl
--rw-r--r--  2.0 unx     3136 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/internal/decompose.h
--rw-r--r--  2.0 unx     1874 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/adjacent_difference.h
--rw-r--r--  2.0 unx     1212 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/assign_value.h
--rw-r--r--  2.0 unx     3770 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/binary_search.h
--rw-r--r--  2.0 unx     1724 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy.h
--rw-r--r--  2.0 unx     4621 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy.inl
--rw-r--r--  2.0 unx     1297 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy_backward.h
--rw-r--r--  2.0 unx     1825 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy_if.h
--rw-r--r--  2.0 unx      714 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/count.h
--rw-r--r--  2.0 unx      714 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/equal.h
--rw-r--r--  2.0 unx     1770 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/execution_policy.h
--rw-r--r--  2.0 unx     3273 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/extrema.h
--rw-r--r--  2.0 unx      713 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/fill.h
--rw-r--r--  2.0 unx     1621 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/find.h
--rw-r--r--  2.0 unx     2259 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/for_each.h
--rw-r--r--  2.0 unx      715 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/gather.h
--rw-r--r--  2.0 unx     3852 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/general_copy.h
--rw-r--r--  2.0 unx      717 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/generate.h
--rw-r--r--  2.0 unx     1193 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/get_value.h
--rw-r--r--  2.0 unx      722 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/inner_product.h
--rw-r--r--  2.0 unx     3623 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/insertion_sort.h
--rw-r--r--  2.0 unx     1259 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/iter_swap.h
--rw-r--r--  2.0 unx      716 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/logical.h
--rw-r--r--  2.0 unx     1355 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/malloc_and_free.h
--rw-r--r--  2.0 unx     2389 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/merge.h
--rw-r--r--  2.0 unx     3953 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/merge.inl
--rw-r--r--  2.0 unx      717 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/mismatch.h
--rw-r--r--  2.0 unx     8091 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/partition.h
--rw-r--r--  2.0 unx      723 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/per_device_resource.h
--rw-r--r--  2.0 unx     1759 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/reduce.h
--rw-r--r--  2.0 unx     2853 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/reduce_by_key.h
--rw-r--r--  2.0 unx     4498 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/remove.h
--rw-r--r--  2.0 unx      716 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/replace.h
--rw-r--r--  2.0 unx      716 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/reverse.h
--rw-r--r--  2.0 unx     3296 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/scan.h
--rw-r--r--  2.0 unx     4092 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/scan_by_key.h
--rw-r--r--  2.0 unx      716 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/scatter.h
--rw-r--r--  2.0 unx      717 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/sequence.h
--rw-r--r--  2.0 unx     5906 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/set_operations.h
--rw-r--r--  2.0 unx     1846 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/sort.h
--rw-r--r--  2.0 unx     6653 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/sort.inl
--rw-r--r--  2.0 unx     1845 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_merge_sort.h
--rw-r--r--  2.0 unx    14742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_merge_sort.inl
--rw-r--r--  2.0 unx     1700 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_primitive_sort.h
--rw-r--r--  2.0 unx     5091 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_primitive_sort.inl
--rw-r--r--  2.0 unx     1666 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_radix_sort.h
--rw-r--r--  2.0 unx    17969 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_radix_sort.inl
--rw-r--r--  2.0 unx      720 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/swap_ranges.h
--rw-r--r--  2.0 unx      717 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/tabulate.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/temporary_buffer.h
--rw-r--r--  2.0 unx      718 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/transform.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/transform_reduce.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/transform_scan.h
--rw-r--r--  2.0 unx     1498 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/trivial_copy.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/uninitialized_copy.h
--rw-r--r--  2.0 unx      726 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/uninitialized_fill.h
--rw-r--r--  2.0 unx     3243 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/unique.h
--rw-r--r--  2.0 unx     3402 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/detail/sequential/unique_by_key.h
--rw-r--r--  2.0 unx     5095 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/execution_policy.h
--rw-r--r--  2.0 unx     3396 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/memory.h
--rw-r--r--  2.0 unx     1967 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/memory_resource.h
--rw-r--r--  2.0 unx     3783 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/pointer.h
--rw-r--r--  2.0 unx     3161 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/vector.h
--rw-r--r--  2.0 unx     1586 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/adjacent_difference.h
--rw-r--r--  2.0 unx      756 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/assign_value.h
--rw-r--r--  2.0 unx     2463 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/binary_search.h
--rw-r--r--  2.0 unx     1536 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy.h
--rw-r--r--  2.0 unx     4299 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy.inl
--rw-r--r--  2.0 unx     1379 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy_if.h
--rw-r--r--  2.0 unx     1534 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy_if.inl
--rw-r--r--  2.0 unx      742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/count.h
--rw-r--r--  2.0 unx     1210 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/default_decomposition.h
--rw-r--r--  2.0 unx     2069 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/default_decomposition.inl
--rw-r--r--  2.0 unx      742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/equal.h
--rw-r--r--  2.0 unx     2921 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/execution_policy.h
--rw-r--r--  2.0 unx     2469 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/extrema.h
--rw-r--r--  2.0 unx      740 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/fill.h
--rw-r--r--  2.0 unx     1406 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/find.h
--rw-r--r--  2.0 unx     1806 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/for_each.h
--rw-r--r--  2.0 unx     3055 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/for_each.inl
--rw-r--r--  2.0 unx      744 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/gather.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/generate.h
--rw-r--r--  2.0 unx      750 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/get_value.h
--rw-r--r--  2.0 unx      758 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/inner_product.h
--rw-r--r--  2.0 unx      750 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/iter_swap.h
--rw-r--r--  2.0 unx      746 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/logical.h
--rw-r--r--  2.0 unx      762 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/malloc_and_free.h
--rw-r--r--  2.0 unx     2423 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/memory.inl
--rw-r--r--  2.0 unx      742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/merge.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/mismatch.h
--rw-r--r--  2.0 unx     1330 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/par.h
--rw-r--r--  2.0 unx     2951 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/partition.h
--rw-r--r--  2.0 unx     3751 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/partition.inl
--rw-r--r--  2.0 unx      723 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/per_device_resource.h
--rw-r--r--  2.0 unx     2798 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/pragma_omp.h
--rw-r--r--  2.0 unx     1383 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce.h
--rw-r--r--  2.0 unx     2466 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce.inl
--rw-r--r--  2.0 unx     1712 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_by_key.h
--rw-r--r--  2.0 unx     1867 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_by_key.inl
--rw-r--r--  2.0 unx     1471 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_intervals.h
--rw-r--r--  2.0 unx     2901 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_intervals.inl
--rw-r--r--  2.0 unx     2568 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/remove.h
--rw-r--r--  2.0 unx     3161 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/remove.inl
--rw-r--r--  2.0 unx      753 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/replace.h
--rw-r--r--  2.0 unx      746 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/reverse.h
--rw-r--r--  2.0 unx      740 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/scan.h
--rw-r--r--  2.0 unx      757 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/scan_by_key.h
--rw-r--r--  2.0 unx      753 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/scatter.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/sequence.h
--rw-r--r--  2.0 unx      760 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/set_operations.h
--rw-r--r--  2.0 unx     1689 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/sort.h
--rw-r--r--  2.0 unx     8864 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/sort.inl
--rw-r--r--  2.0 unx      746 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/swap_ranges.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/tabulate.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/temporary_buffer.h
--rw-r--r--  2.0 unx      742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/transform.h
--rw-r--r--  2.0 unx      764 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/transform_reduce.h
--rw-r--r--  2.0 unx      760 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/transform_scan.h
--rw-r--r--  2.0 unx      768 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/uninitialized_copy.h
--rw-r--r--  2.0 unx      768 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/uninitialized_fill.h
--rw-r--r--  2.0 unx     2062 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique.h
--rw-r--r--  2.0 unx     2542 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique.inl
--rw-r--r--  2.0 unx     2048 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique_by_key.h
--rw-r--r--  2.0 unx     2485 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique_by_key.inl
--rw-r--r--  2.0 unx     5071 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/execution_policy.h
--rw-r--r--  2.0 unx     3394 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/memory.h
--rw-r--r--  2.0 unx     1978 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/memory_resource.h
--rw-r--r--  2.0 unx     3780 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/pointer.h
--rw-r--r--  2.0 unx     3157 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/vector.h
--rw-r--r--  2.0 unx     1586 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/adjacent_difference.h
--rw-r--r--  2.0 unx      756 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/assign_value.h
--rw-r--r--  2.0 unx      758 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/binary_search.h
--rw-r--r--  2.0 unx     1536 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy.h
--rw-r--r--  2.0 unx     4322 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy.inl
--rw-r--r--  2.0 unx     1312 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy_if.h
--rw-r--r--  2.0 unx     3295 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy_if.inl
--rw-r--r--  2.0 unx      742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/count.h
--rw-r--r--  2.0 unx      742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/equal.h
--rw-r--r--  2.0 unx     2144 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/execution_policy.h
--rw-r--r--  2.0 unx     2469 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/extrema.h
--rw-r--r--  2.0 unx      740 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/fill.h
--rw-r--r--  2.0 unx     1337 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/find.h
--rw-r--r--  2.0 unx     1654 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/for_each.h
--rw-r--r--  2.0 unx     2946 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/for_each.inl
--rw-r--r--  2.0 unx      744 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/gather.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/generate.h
--rw-r--r--  2.0 unx      750 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/get_value.h
--rw-r--r--  2.0 unx      758 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/inner_product.h
--rw-r--r--  2.0 unx      750 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/iter_swap.h
--rw-r--r--  2.0 unx      746 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/logical.h
--rw-r--r--  2.0 unx      762 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/malloc_and_free.h
--rw-r--r--  2.0 unx     2424 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/memory.inl
--rw-r--r--  2.0 unx     2198 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/merge.h
--rw-r--r--  2.0 unx     9380 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/merge.inl
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/mismatch.h
--rw-r--r--  2.0 unx     1330 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/par.h
--rw-r--r--  2.0 unx     2872 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/partition.h
--rw-r--r--  2.0 unx     3670 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/partition.inl
--rw-r--r--  2.0 unx      723 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/per_device_resource.h
--rw-r--r--  2.0 unx     1368 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce.h
--rw-r--r--  2.0 unx     3470 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce.inl
--rw-r--r--  2.0 unx     1650 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce_by_key.h
--rw-r--r--  2.0 unx    14239 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce_by_key.inl
--rw-r--r--  2.0 unx     4287 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce_intervals.h
--rw-r--r--  2.0 unx     2584 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/remove.h
--rw-r--r--  2.0 unx     3161 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/remove.inl
--rw-r--r--  2.0 unx      753 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/replace.h
--rw-r--r--  2.0 unx      746 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reverse.h
--rw-r--r--  2.0 unx     1795 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scan.h
--rw-r--r--  2.0 unx     7066 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scan.inl
--rw-r--r--  2.0 unx      754 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scan_by_key.h
--rw-r--r--  2.0 unx      753 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scatter.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/sequence.h
--rw-r--r--  2.0 unx      760 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/set_operations.h
--rw-r--r--  2.0 unx     1703 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/sort.h
--rw-r--r--  2.0 unx     8169 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/sort.inl
--rw-r--r--  2.0 unx      746 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/swap_ranges.h
--rw-r--r--  2.0 unx      748 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/tabulate.h
--rw-r--r--  2.0 unx      725 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/temporary_buffer.h
--rw-r--r--  2.0 unx      742 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/transform.h
--rw-r--r--  2.0 unx      764 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/transform_reduce.h
--rw-r--r--  2.0 unx      760 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/transform_scan.h
--rw-r--r--  2.0 unx      768 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/uninitialized_copy.h
--rw-r--r--  2.0 unx      768 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/uninitialized_fill.h
--rw-r--r--  2.0 unx     2070 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique.h
--rw-r--r--  2.0 unx     2542 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique.inl
--rw-r--r--  2.0 unx     2048 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique_by_key.h
--rw-r--r--  2.0 unx     2485 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique_by_key.inl
--rw-r--r--  2.0 unx    10578 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/integer_sequence.h
--rw-r--r--  2.0 unx     8482 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/is_contiguous_iterator.h
--rw-r--r--  2.0 unx     1702 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/is_execution_policy.h
--rw-r--r--  2.0 unx     6372 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/is_operator_less_or_greater_function_object.h
--rw-r--r--  2.0 unx     3064 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/is_operator_plus_function_object.h
--rw-r--r--  2.0 unx    12644 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/is_trivially_relocatable.h
--rw-r--r--  2.0 unx     7888 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/logical_metafunctions.h
--rw-r--r--  2.0 unx     3187 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/remove_cvref.h
--rw-r--r--  2.0 unx     1458 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/include/thrust/type_traits/void_t.h
--rw-r--r--  2.0 unx     1363 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/cub/cub-config-version.cmake
--rw-r--r--  2.0 unx     4689 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/cub/cub-config.cmake
--rw-r--r--  2.0 unx      744 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/cub/cub-header-search.cmake
--rw-r--r--  2.0 unx     1247 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config-version.cmake
--rw-r--r--  2.0 unx     2612 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config.cmake
--rw-r--r--  2.0 unx      399 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-header-search.cmake
--rw-r--r--  2.0 unx    16707 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/thrust/FindTBB.cmake
--rw-r--r--  2.0 unx     8459 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/thrust/README.md
--rw-r--r--  2.0 unx     1437 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/thrust/thrust-config-version.cmake
--rw-r--r--  2.0 unx    29918 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/thrust/thrust-config.cmake
--rw-r--r--  2.0 unx      757 b- defN 23-Jan-25 03:52 nvidia/cuda_cccl/lib/cmake/thrust/thrust-header-search.cmake
--rw-r--r--  2.0 unx    59262 b- defN 23-Jan-25 03:52 nvidia_cuda_cccl_cu12-12.1.55.dist-info/License.txt
--rw-r--r--  2.0 unx     1485 b- defN 23-Jan-25 03:52 nvidia_cuda_cccl_cu12-12.1.55.dist-info/METADATA
--rw-r--r--  2.0 unx       98 b- defN 23-Jan-25 03:52 nvidia_cuda_cccl_cu12-12.1.55.dist-info/WHEEL
--rw-r--r--  2.0 unx        7 b- defN 23-Jan-25 03:52 nvidia_cuda_cccl_cu12-12.1.55.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx   118980 b- defN 23-Jan-25 03:52 nvidia_cuda_cccl_cu12-12.1.55.dist-info/RECORD
-1009 files, 8244493 bytes uncompressed, 1652295 bytes compressed:  80.0%
+Zip file size: 2215514 bytes, number of entries: 1279
+-rw-r--r--  2.0 unx        0 b- defN 23-May-01 02:46 nvidia/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 23-May-01 02:46 nvidia/cuda_cccl/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/__init__.py
+-rw-r--r--  2.0 unx     2000 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/config.cuh
+-rw-r--r--  2.0 unx     4132 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/cub.cuh
+-rw-r--r--  2.0 unx    29056 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_allocator.cuh
+-rw-r--r--  2.0 unx     6059 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_arch.cuh
+-rw-r--r--  2.0 unx     3644 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_compiler.cuh
+-rw-r--r--  2.0 unx     6333 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_cpp_dialect.cuh
+-rw-r--r--  2.0 unx     9578 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_debug.cuh
+-rw-r--r--  2.0 unx     3733 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_deprecated.cuh
+-rw-r--r--  2.0 unx    23043 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_device.cuh
+-rw-r--r--  2.0 unx     4348 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_macro.cuh
+-rw-r--r--  2.0 unx     4476 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_math.cuh
+-rw-r--r--  2.0 unx    11031 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_namespace.cuh
+-rw-r--r--  2.0 unx    24522 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_ptx.cuh
+-rw-r--r--  2.0 unx    45967 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/util_type.cuh
+-rw-r--r--  2.0 unx     3116 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/version.cuh
+-rw-r--r--  2.0 unx     9725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_adjacent_difference.cuh
+-rw-r--r--  2.0 unx    48960 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_batch_memcpy.cuh
+-rw-r--r--  2.0 unx    33064 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_histogram.cuh
+-rw-r--r--  2.0 unx    26107 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_merge_sort.cuh
+-rw-r--r--  2.0 unx    28053 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_downsweep.cuh
+-rw-r--r--  2.0 unx     9298 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_histogram.cuh
+-rw-r--r--  2.0 unx    24649 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_onesweep.cuh
+-rw-r--r--  2.0 unx    17878 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_upsweep.cuh
+-rw-r--r--  2.0 unx    18284 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_reduce.cuh
+-rw-r--r--  2.0 unx    23479 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_reduce_by_key.cuh
+-rw-r--r--  2.0 unx    35265 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_rle.cuh
+-rw-r--r--  2.0 unx    18747 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_scan.cuh
+-rw-r--r--  2.0 unx    18102 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_scan_by_key.cuh
+-rw-r--r--  2.0 unx    16588 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_segment_fixup.cuh
+-rw-r--r--  2.0 unx    10023 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_segmented_radix_sort.cuh
+-rw-r--r--  2.0 unx    28925 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_select_if.cuh
+-rw-r--r--  2.0 unx    27874 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_spmv_orig.cuh
+-rw-r--r--  2.0 unx    11731 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_sub_warp_merge_sort.cuh
+-rw-r--r--  2.0 unx    21856 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_three_way_partition.cuh
+-rw-r--r--  2.0 unx    21283 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/agent_unique_by_key.cuh
+-rw-r--r--  2.0 unx    29923 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/agent/single_pass_scan_operators.cuh
+-rw-r--r--  2.0 unx    52579 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_adjacent_difference.cuh
+-rw-r--r--  2.0 unx    52893 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_discontinuity.cuh
+-rw-r--r--  2.0 unx    50116 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_exchange.cuh
+-rw-r--r--  2.0 unx    16713 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_histogram.cuh
+-rw-r--r--  2.0 unx    56629 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_load.cuh
+-rw-r--r--  2.0 unx    28724 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_merge_sort.cuh
+-rw-r--r--  2.0 unx    46271 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_radix_rank.cuh
+-rw-r--r--  2.0 unx    40081 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_radix_sort.cuh
+-rw-r--r--  2.0 unx     5964 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_raking_layout.cuh
+-rw-r--r--  2.0 unx    25510 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_reduce.cuh
+-rw-r--r--  2.0 unx    18949 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_run_length_decode.cuh
+-rw-r--r--  2.0 unx   103189 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_scan.cuh
+-rw-r--r--  2.0 unx    11726 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_shuffle.cuh
+-rw-r--r--  2.0 unx    44245 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/block_store.cuh
+-rw-r--r--  2.0 unx     5732 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/radix_rank_sort_operations.cuh
+-rw-r--r--  2.0 unx     3154 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/specializations/block_histogram_atomic.cuh
+-rw-r--r--  2.0 unx     8229 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/specializations/block_histogram_sort.cuh
+-rw-r--r--  2.0 unx     9610 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking.cuh
+-rw-r--r--  2.0 unx     8334 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking_commutative_only.cuh
+-rw-r--r--  2.0 unx     9697 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_warp_reductions.cuh
+-rw-r--r--  2.0 unx    28535 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/specializations/block_scan_raking.cuh
+-rw-r--r--  2.0 unx    19175 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/block/specializations/block_scan_warp_scans.cuh
+-rw-r--r--  2.0 unx     2581 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/choose_offset.cuh
+-rw-r--r--  2.0 unx      874 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/cpp_compatibility.cuh
+-rw-r--r--  2.0 unx     3665 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/detect_cuda_runtime.cuh
+-rw-r--r--  2.0 unx     2698 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/device_double_buffer.cuh
+-rw-r--r--  2.0 unx     1926 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/device_synchronize.cuh
+-rw-r--r--  2.0 unx     1181 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/exec_check_disable.cuh
+-rw-r--r--  2.0 unx     7278 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/strong_load.cuh
+-rw-r--r--  2.0 unx    12231 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/strong_store.cuh
+-rw-r--r--  2.0 unx     8634 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/temporary_storage.cuh
+-rw-r--r--  2.0 unx     2485 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/type_traits.cuh
+-rw-r--r--  2.0 unx     2693 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/detail/uninitialized_copy.cuh
+-rw-r--r--  2.0 unx    26211 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_adjacent_difference.cuh
+-rw-r--r--  2.0 unx    68310 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_histogram.cuh
+-rw-r--r--  2.0 unx     8296 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_memcpy.cuh
+-rw-r--r--  2.0 unx    42009 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_merge_sort.cuh
+-rw-r--r--  2.0 unx    28990 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_partition.cuh
+-rw-r--r--  2.0 unx    54487 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_radix_sort.cuh
+-rw-r--r--  2.0 unx    48146 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_reduce.cuh
+-rw-r--r--  2.0 unx    17929 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_run_length_encode.cuh
+-rw-r--r--  2.0 unx    85061 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_scan.cuh
+-rw-r--r--  2.0 unx    73338 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_segmented_radix_sort.cuh
+-rw-r--r--  2.0 unx    46499 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_segmented_reduce.cuh
+-rw-r--r--  2.0 unx   130046 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_segmented_sort.cuh
+-rw-r--r--  2.0 unx    40912 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_select.cuh
+-rw-r--r--  2.0 unx     9516 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/device_spmv.cuh
+-rw-r--r--  2.0 unx    14322 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_adjacent_difference.cuh
+-rw-r--r--  2.0 unx    30982 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_batch_memcpy.cuh
+-rw-r--r--  2.0 unx    64634 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_histogram.cuh
+-rw-r--r--  2.0 unx    31943 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_merge_sort.cuh
+-rw-r--r--  2.0 unx   106789 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_radix_sort.cuh
+-rw-r--r--  2.0 unx    43564 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce.cuh
+-rw-r--r--  2.0 unx    25820 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce_by_key.cuh
+-rw-r--r--  2.0 unx    21927 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_rle.cuh
+-rw-r--r--  2.0 unx    22771 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_scan.cuh
+-rw-r--r--  2.0 unx    23645 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_scan_by_key.cuh
+-rw-r--r--  2.0 unx    67162 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_segmented_sort.cuh
+-rw-r--r--  2.0 unx    23154 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_select_if.cuh
+-rw-r--r--  2.0 unx    35878 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_spmv_orig.cuh
+-rw-r--r--  2.0 unx    20642 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_three_way_partition.cuh
+-rw-r--r--  2.0 unx    22728 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_unique_by_key.cuh
+-rw-r--r--  2.0 unx     5730 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/grid/grid_barrier.cuh
+-rw-r--r--  2.0 unx     8287 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/grid/grid_even_share.cuh
+-rw-r--r--  2.0 unx     4696 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/grid/grid_mapping.cuh
+-rw-r--r--  2.0 unx     7886 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/grid/grid_queue.cuh
+-rw-r--r--  2.0 unx     4325 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/host/mutex.cuh
+-rw-r--r--  2.0 unx     8668 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/arg_index_input_iterator.cuh
+-rw-r--r--  2.0 unx     8008 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/cache_modified_input_iterator.cuh
+-rw-r--r--  2.0 unx     8228 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/cache_modified_output_iterator.cuh
+-rw-r--r--  2.0 unx     7558 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/constant_input_iterator.cuh
+-rw-r--r--  2.0 unx     7277 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/counting_input_iterator.cuh
+-rw-r--r--  2.0 unx     6543 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/discard_output_iterator.cuh
+-rw-r--r--  2.0 unx    10891 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/tex_obj_input_iterator.cuh
+-rw-r--r--  2.0 unx     4581 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/tex_ref_input_iterator.cuh
+-rw-r--r--  2.0 unx     8378 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/iterator/transform_input_iterator.cuh
+-rw-r--r--  2.0 unx    18053 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/thread/thread_load.cuh
+-rw-r--r--  2.0 unx    11494 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/thread/thread_operators.cuh
+-rw-r--r--  2.0 unx     6260 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/thread/thread_reduce.cuh
+-rw-r--r--  2.0 unx    10435 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/thread/thread_scan.cuh
+-rw-r--r--  2.0 unx     5630 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/thread/thread_search.cuh
+-rw-r--r--  2.0 unx     3543 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/thread/thread_sort.cuh
+-rw-r--r--  2.0 unx    17566 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/thread/thread_store.cuh
+-rw-r--r--  2.0 unx    17966 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/warp_exchange.cuh
+-rw-r--r--  2.0 unx    25456 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/warp_load.cuh
+-rw-r--r--  2.0 unx     6341 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/warp_merge_sort.cuh
+-rw-r--r--  2.0 unx    26349 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/warp_reduce.cuh
+-rw-r--r--  2.0 unx    38675 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/warp_scan.cuh
+-rw-r--r--  2.0 unx    20347 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/warp_store.cuh
+-rw-r--r--  2.0 unx    23024 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_shfl.cuh
+-rw-r--r--  2.0 unx    13923 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_smem.cuh
+-rw-r--r--  2.0 unx    22355 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_shfl.cuh
+-rw-r--r--  2.0 unx    15617 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_smem.cuh
+-rw-r--r--  2.0 unx     2121 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__bsd_locale_defaults.h
+-rw-r--r--  2.0 unx     4100 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__bsd_locale_fallbacks.h
+-rw-r--r--  2.0 unx      755 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/complex.h
+-rw-r--r--  2.0 unx     1165 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/ctype.h
+-rw-r--r--  2.0 unx     5160 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/errno.h
+-rw-r--r--  2.0 unx     1879 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/fenv.h
+-rw-r--r--  2.0 unx     1688 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/float.h
+-rw-r--r--  2.0 unx     3905 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/inttypes.h
+-rw-r--r--  2.0 unx     1539 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/limits.h
+-rw-r--r--  2.0 unx      792 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/locale.h
+-rw-r--r--  2.0 unx    51607 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/math.h
+-rw-r--r--  2.0 unx      818 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/setjmp.h
+-rw-r--r--  2.0 unx      831 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdbool.h
+-rw-r--r--  2.0 unx     1405 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stddef.h
+-rw-r--r--  2.0 unx     2395 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdint.h
+-rw-r--r--  2.0 unx     3541 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdio.h
+-rw-r--r--  2.0 unx     3696 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdlib.h
+-rw-r--r--  2.0 unx     4821 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/string.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/tgmath.h
+-rw-r--r--  2.0 unx     8573 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wchar.h
+-rw-r--r--  2.0 unx     1570 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wctype.h
+-rw-r--r--  2.0 unx     1143 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__algorithm/swap_ranges.h
+-rw-r--r--  2.0 unx     1238 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/_One_of.h
+-rw-r--r--  2.0 unx    14723 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/__concept_macros.h
+-rw-r--r--  2.0 unx     1926 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/arithmetic.h
+-rw-r--r--  2.0 unx     1970 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/assignable.h
+-rw-r--r--  2.0 unx     1753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/boolean_testable.h
+-rw-r--r--  2.0 unx     1563 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/class_or_enum.h
+-rw-r--r--  2.0 unx     2292 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/common_reference_with.h
+-rw-r--r--  2.0 unx     3211 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/common_with.h
+-rw-r--r--  2.0 unx     3768 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/constructible.h
+-rw-r--r--  2.0 unx     1955 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/convertible_to.h
+-rw-r--r--  2.0 unx     1651 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/copyable.h
+-rw-r--r--  2.0 unx     1634 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/derived_from.h
+-rw-r--r--  2.0 unx     2167 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/destructible.h
+-rw-r--r--  2.0 unx     1124 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/different_from.h
+-rw-r--r--  2.0 unx     3637 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/equality_comparable.h
+-rw-r--r--  2.0 unx     1843 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/invocable.h
+-rw-r--r--  2.0 unx     1557 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/movable.h
+-rw-r--r--  2.0 unx     1555 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/predicate.h
+-rw-r--r--  2.0 unx     1393 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/regular.h
+-rw-r--r--  2.0 unx     2078 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/relation.h
+-rw-r--r--  2.0 unx     1170 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/same_as.h
+-rw-r--r--  2.0 unx     1410 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/semiregular.h
+-rw-r--r--  2.0 unx     8118 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/swappable.h
+-rw-r--r--  2.0 unx     3667 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/totally_ordered.h
+-rw-r--r--  2.0 unx    10088 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/atomic.h
+-rw-r--r--  2.0 unx     2072 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/atomic_prelude.h
+-rw-r--r--  2.0 unx    35638 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/barrier.h
+-rw-r--r--  2.0 unx     1783 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/chrono.h
+-rw-r--r--  2.0 unx     3473 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/climits_prelude.h
+-rw-r--r--  2.0 unx     1020 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/cstddef_prelude.h
+-rw-r--r--  2.0 unx     2872 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/cstdint_prelude.h
+-rw-r--r--  2.0 unx     1005 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/latch.h
+-rw-r--r--  2.0 unx     1562 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/semaphore.h
+-rw-r--r--  2.0 unx     2097 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binary_function.h
+-rw-r--r--  2.0 unx     2014 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binary_negate.h
+-rw-r--r--  2.0 unx    13436 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind.h
+-rw-r--r--  2.0 unx     3449 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind_back.h
+-rw-r--r--  2.0 unx     2565 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind_front.h
+-rw-r--r--  2.0 unx     2158 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binder1st.h
+-rw-r--r--  2.0 unx     2137 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binder2nd.h
+-rw-r--r--  2.0 unx     2484 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/compose.h
+-rw-r--r--  2.0 unx     5746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/default_searcher.h
+-rw-r--r--  2.0 unx    39611 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/function.h
+-rw-r--r--  2.0 unx    20163 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/hash.h
+-rw-r--r--  2.0 unx     1418 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/identity.h
+-rw-r--r--  2.0 unx    19303 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/invoke.h
+-rw-r--r--  2.0 unx     1163 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/is_transparent.h
+-rw-r--r--  2.0 unx     1751 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/mem_fn.h
+-rw-r--r--  2.0 unx     6105 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/mem_fun_ref.h
+-rw-r--r--  2.0 unx     2070 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/not_fn.h
+-rw-r--r--  2.0 unx    19272 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/operations.h
+-rw-r--r--  2.0 unx     5464 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/perfect_forward.h
+-rw-r--r--  2.0 unx     1762 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/pointer_to_binary_function.h
+-rw-r--r--  2.0 unx     1745 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/pointer_to_unary_function.h
+-rw-r--r--  2.0 unx     3093 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/reference_wrapper.h
+-rw-r--r--  2.0 unx     1809 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unary_function.h
+-rw-r--r--  2.0 unx     1816 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unary_negate.h
+-rw-r--r--  2.0 unx     1695 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unwrap_ref.h
+-rw-r--r--  2.0 unx     8734 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/weak_result_type.h
+-rw-r--r--  2.0 unx      867 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/array.h
+-rw-r--r--  2.0 unx     3303 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/get.h
+-rw-r--r--  2.0 unx      822 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/hash.h
+-rw-r--r--  2.0 unx      919 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/memory_resource.h
+-rw-r--r--  2.0 unx      829 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/pair.h
+-rw-r--r--  2.0 unx      995 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/span.h
+-rw-r--r--  2.0 unx     3041 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/string.h
+-rw-r--r--  2.0 unx     1725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/string_view.h
+-rw-r--r--  2.0 unx      894 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/tuple.h
+-rw-r--r--  2.0 unx     2806 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/access.h
+-rw-r--r--  2.0 unx     2233 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/advance.h
+-rw-r--r--  2.0 unx     2490 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/back_insert_iterator.h
+-rw-r--r--  2.0 unx     1540 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/data.h
+-rw-r--r--  2.0 unx     1787 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/distance.h
+-rw-r--r--  2.0 unx     1489 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/empty.h
+-rw-r--r--  2.0 unx     1337 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/erase_if_container.h
+-rw-r--r--  2.0 unx     2505 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/front_insert_iterator.h
+-rw-r--r--  2.0 unx     2595 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/insert_iterator.h
+-rw-r--r--  2.0 unx     3551 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/istream_iterator.h
+-rw-r--r--  2.0 unx     3757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/istreambuf_iterator.h
+-rw-r--r--  2.0 unx     1218 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/iterator.h
+-rw-r--r--  2.0 unx     5952 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/iterator_traits.h
+-rw-r--r--  2.0 unx     6437 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/move_iterator.h
+-rw-r--r--  2.0 unx     1431 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/next.h
+-rw-r--r--  2.0 unx     2383 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/ostream_iterator.h
+-rw-r--r--  2.0 unx     2712 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/ostreambuf_iterator.h
+-rw-r--r--  2.0 unx     1431 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/prev.h
+-rw-r--r--  2.0 unx     2834 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/reverse_access.h
+-rw-r--r--  2.0 unx     7422 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/reverse_iterator.h
+-rw-r--r--  2.0 unx     2172 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/size.h
+-rw-r--r--  2.0 unx    15990 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/wrap_iter.h
+-rw-r--r--  2.0 unx     9718 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/compressed_pair.h
+-rw-r--r--  2.0 unx    10600 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/config.h
+-rw-r--r--  2.0 unx     3367 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/default_accessor.h
+-rw-r--r--  2.0 unx     2897 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/dynamic_extent.h
+-rw-r--r--  2.0 unx    20581 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/extents.h
+-rw-r--r--  2.0 unx     2559 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/full_extent_t.h
+-rw-r--r--  2.0 unx    10227 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_left.h
+-rw-r--r--  2.0 unx    10542 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_right.h
+-rw-r--r--  2.0 unx    21746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_stride.h
+-rw-r--r--  2.0 unx    24869 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/macros.h
+-rw-r--r--  2.0 unx     6174 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/maybe_static_value.h
+-rw-r--r--  2.0 unx    20990 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/mdspan.h
+-rw-r--r--  2.0 unx     5752 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/no_unique_address.h
+-rw-r--r--  2.0 unx    26272 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/standard_layout_static_array.h
+-rw-r--r--  2.0 unx    11248 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/static_array.h
+-rw-r--r--  2.0 unx    24272 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/submdspan.h
+-rw-r--r--  2.0 unx     4511 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/type_list.h
+-rw-r--r--  2.0 unx     2459 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/addressof.h
+-rw-r--r--  2.0 unx     6383 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/construct_at.h
+-rw-r--r--  2.0 unx    12174 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/pointer_traits.h
+-rw-r--r--  2.0 unx     1144 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/voidify.h
+-rw-r--r--  2.0 unx     2393 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/apply_cv.h
+-rw-r--r--  2.0 unx     3265 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/make_tuple_types.h
+-rw-r--r--  2.0 unx     7608 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/sfinae_helpers.h
+-rw-r--r--  2.0 unx     6113 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/structured_bindings.h
+-rw-r--r--  2.0 unx     3885 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_element.h
+-rw-r--r--  2.0 unx     1134 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_indices.h
+-rw-r--r--  2.0 unx     1685 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_like.h
+-rw-r--r--  2.0 unx     2722 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_size.h
+-rw-r--r--  2.0 unx      845 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_types.h
+-rw-r--r--  2.0 unx     1036 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_const.h
+-rw-r--r--  2.0 unx     1027 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_cv.h
+-rw-r--r--  2.0 unx     1829 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_lvalue_reference.h
+-rw-r--r--  2.0 unx     1900 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_pointer.h
+-rw-r--r--  2.0 unx     1805 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_rvalue_reference.h
+-rw-r--r--  2.0 unx     1057 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_volatile.h
+-rw-r--r--  2.0 unx     4551 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/aligned_storage.h
+-rw-r--r--  2.0 unx     1977 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/aligned_union.h
+-rw-r--r--  2.0 unx     1215 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/alignment_of.h
+-rw-r--r--  2.0 unx     2007 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/apply_cv.h
+-rw-r--r--  2.0 unx     2340 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/can_extract_key.h
+-rw-r--r--  2.0 unx     8880 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/common_reference.h
+-rw-r--r--  2.0 unx     4528 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/common_type.h
+-rw-r--r--  2.0 unx     1842 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/conditional.h
+-rw-r--r--  2.0 unx     2086 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/conjunction.h
+-rw-r--r--  2.0 unx     1579 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/copy_cv.h
+-rw-r--r--  2.0 unx     1437 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/copy_cvref.h
+-rw-r--r--  2.0 unx     2478 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/decay.h
+-rw-r--r--  2.0 unx      916 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/dependent_type.h
+-rw-r--r--  2.0 unx     2256 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/disjunction.h
+-rw-r--r--  2.0 unx     1236 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/enable_if.h
+-rw-r--r--  2.0 unx     2334 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/extent.h
+-rw-r--r--  2.0 unx     1527 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/has_unique_object_representation.h
+-rw-r--r--  2.0 unx     1606 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/has_virtual_destructor.h
+-rw-r--r--  2.0 unx     1879 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/integral_constant.h
+-rw-r--r--  2.0 unx     1172 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_abstract.h
+-rw-r--r--  2.0 unx     1307 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_aggregate.h
+-rw-r--r--  2.0 unx     1244 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_allocator.h
+-rw-r--r--  2.0 unx     1359 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_arithmetic.h
+-rw-r--r--  2.0 unx     1993 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_array.h
+-rw-r--r--  2.0 unx     2515 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_assignable.h
+-rw-r--r--  2.0 unx     2366 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_base_of.h
+-rw-r--r--  2.0 unx     1502 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_bounded_array.h
+-rw-r--r--  2.0 unx     1273 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_callable.h
+-rw-r--r--  2.0 unx     1068 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_char_like_type.h
+-rw-r--r--  2.0 unx     1891 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_class.h
+-rw-r--r--  2.0 unx     1753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_compound.h
+-rw-r--r--  2.0 unx     1728 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_const.h
+-rw-r--r--  2.0 unx     1458 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_constant_evaluated.h
+-rw-r--r--  2.0 unx     6480 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_constructible.h
+-rw-r--r--  2.0 unx     6222 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_convertible.h
+-rw-r--r--  2.0 unx     1391 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_copy_assignable.h
+-rw-r--r--  2.0 unx     1362 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_copy_constructible.h
+-rw-r--r--  2.0 unx     1484 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_core_convertible.h
+-rw-r--r--  2.0 unx     1227 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_default_constructible.h
+-rw-r--r--  2.0 unx     3361 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_destructible.h
+-rw-r--r--  2.0 unx     1987 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_empty.h
+-rw-r--r--  2.0 unx     2735 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_enum.h
+-rw-r--r--  2.0 unx     1809 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_final.h
+-rw-r--r--  2.0 unx     1623 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_floating_point.h
+-rw-r--r--  2.0 unx     1812 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_function.h
+-rw-r--r--  2.0 unx     1966 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_fundamental.h
+-rw-r--r--  2.0 unx     1881 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_implicitly_default_constructible.h
+-rw-r--r--  2.0 unx     3692 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_integral.h
+-rw-r--r--  2.0 unx     2090 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_literal_type.h
+-rw-r--r--  2.0 unx     2391 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_function_pointer.h
+-rw-r--r--  2.0 unx     2024 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_object_pointer.h
+-rw-r--r--  2.0 unx     1927 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_pointer.h
+-rw-r--r--  2.0 unx     1349 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_move_assignable.h
+-rw-r--r--  2.0 unx     1348 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_move_constructible.h
+-rw-r--r--  2.0 unx     4615 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_assignable.h
+-rw-r--r--  2.0 unx     5276 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_constructible.h
+-rw-r--r--  2.0 unx     1982 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_convertible.h
+-rw-r--r--  2.0 unx     2249 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_copy_assignable.h
+-rw-r--r--  2.0 unx     1430 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_copy_constructible.h
+-rw-r--r--  2.0 unx     1967 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_default_constructible.h
+-rw-r--r--  2.0 unx     3112 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_destructible.h
+-rw-r--r--  2.0 unx     2148 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_move_assignable.h
+-rw-r--r--  2.0 unx     1368 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_move_constructible.h
+-rw-r--r--  2.0 unx     1612 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_null_pointer.h
+-rw-r--r--  2.0 unx     2018 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_object.h
+-rw-r--r--  2.0 unx     2175 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_pod.h
+-rw-r--r--  2.0 unx     2459 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_pointer.h
+-rw-r--r--  2.0 unx     2022 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_polymorphic.h
+-rw-r--r--  2.0 unx     1213 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_primary_template.h
+-rw-r--r--  2.0 unx     3255 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_reference.h
+-rw-r--r--  2.0 unx     1292 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_reference_wrapper.h
+-rw-r--r--  2.0 unx     1642 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_referenceable.h
+-rw-r--r--  2.0 unx     2961 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_same.h
+-rw-r--r--  2.0 unx     2561 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_scalar.h
+-rw-r--r--  2.0 unx     1481 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_scoped_enum.h
+-rw-r--r--  2.0 unx     2138 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_signed.h
+-rw-r--r--  2.0 unx     1523 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_signed_integer.h
+-rw-r--r--  2.0 unx     1875 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_standard_layout.h
+-rw-r--r--  2.0 unx     5409 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_swappable.h
+-rw-r--r--  2.0 unx     1913 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivial.h
+-rw-r--r--  2.0 unx     2379 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_assignable.h
+-rw-r--r--  2.0 unx     2919 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_constructible.h
+-rw-r--r--  2.0 unx     2335 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copy_assignable.h
+-rw-r--r--  2.0 unx     2225 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copy_constructible.h
+-rw-r--r--  2.0 unx     1962 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copyable.h
+-rw-r--r--  2.0 unx     1979 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_default_constructible.h
+-rw-r--r--  2.0 unx     2462 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_destructible.h
+-rw-r--r--  2.0 unx     2162 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_move_assignable.h
+-rw-r--r--  2.0 unx     2107 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_move_constructible.h
+-rw-r--r--  2.0 unx     1438 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unbounded_array.h
+-rw-r--r--  2.0 unx     1752 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_union.h
+-rw-r--r--  2.0 unx     2394 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unsigned.h
+-rw-r--r--  2.0 unx     1555 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unsigned_integer.h
+-rw-r--r--  2.0 unx     1326 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_valid_expansion.h
+-rw-r--r--  2.0 unx     1698 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_void.h
+-rw-r--r--  2.0 unx     1781 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_volatile.h
+-rw-r--r--  2.0 unx      887 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/lazy.h
+-rw-r--r--  2.0 unx     1794 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_32_64_or_128_bit.h
+-rw-r--r--  2.0 unx      985 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_const_lvalue_ref.h
+-rw-r--r--  2.0 unx     3250 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_signed.h
+-rw-r--r--  2.0 unx     3889 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_unsigned.h
+-rw-r--r--  2.0 unx      953 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/maybe_const.h
+-rw-r--r--  2.0 unx      970 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/nat.h
+-rw-r--r--  2.0 unx     1126 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/negation.h
+-rw-r--r--  2.0 unx     3111 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/promote.h
+-rw-r--r--  2.0 unx     1891 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/rank.h
+-rw-r--r--  2.0 unx     1893 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_all_extents.h
+-rw-r--r--  2.0 unx     1586 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_const.h
+-rw-r--r--  2.0 unx     1023 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_const_ref.h
+-rw-r--r--  2.0 unx     1573 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_cv.h
+-rw-r--r--  2.0 unx     1723 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_cvref.h
+-rw-r--r--  2.0 unx     1732 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_extent.h
+-rw-r--r--  2.0 unx     2094 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_pointer.h
+-rw-r--r--  2.0 unx     1875 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_reference.h
+-rw-r--r--  2.0 unx     1642 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_volatile.h
+-rw-r--r--  2.0 unx     1423 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/result_of.h
+-rw-r--r--  2.0 unx     1177 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/type_identity.h
+-rw-r--r--  2.0 unx     1394 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/type_list.h
+-rw-r--r--  2.0 unx     1847 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/underlying_type.h
+-rw-r--r--  2.0 unx      920 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/void_t.h
+-rw-r--r--  2.0 unx     1078 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/as_const.h
+-rw-r--r--  2.0 unx      877 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/auto_cast.h
+-rw-r--r--  2.0 unx     3620 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/cmp.h
+-rw-r--r--  2.0 unx     2705 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/convert_to_integral.h
+-rw-r--r--  2.0 unx     1235 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/declval.h
+-rw-r--r--  2.0 unx     1412 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/exchange.h
+-rw-r--r--  2.0 unx     1426 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/forward.h
+-rw-r--r--  2.0 unx     1656 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/forward_like.h
+-rw-r--r--  2.0 unx     2013 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/in_place.h
+-rw-r--r--  2.0 unx     6483 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/integer_sequence.h
+-rw-r--r--  2.0 unx     1680 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/move.h
+-rw-r--r--  2.0 unx    26530 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/pair.h
+-rw-r--r--  2.0 unx     1242 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/piecewise_construct.h
+-rw-r--r--  2.0 unx      941 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/priority_tag.h
+-rw-r--r--  2.0 unx     1438 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/rel_ops.h
+-rw-r--r--  2.0 unx     1821 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/swap.h
+-rw-r--r--  2.0 unx     1368 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/to_underlying.h
+-rw-r--r--  2.0 unx     1072 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/unreachable.h
+-rw-r--r--  2.0 unx     1836 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/android/locale_bionic.h
+-rw-r--r--  2.0 unx     9401 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_base.h
+-rw-r--r--  2.0 unx     9205 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_c11.h
+-rw-r--r--  2.0 unx    20589 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda.h
+-rw-r--r--  2.0 unx     6964 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_derived.h
+-rw-r--r--  2.0 unx   262344 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_generated.h
+-rw-r--r--  2.0 unx      635 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_gcc.h
+-rw-r--r--  2.0 unx    22447 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_msvc.h
+-rw-r--r--  2.0 unx      640 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_nvrtc.h
+-rw-r--r--  2.0 unx     1770 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_scopes.h
+-rw-r--r--  2.0 unx     6501 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/cxx_atomic.h
+-rw-r--r--  2.0 unx      719 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/fuchsia/xlocale.h
+-rw-r--r--  2.0 unx     3622 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/limits.h
+-rw-r--r--  2.0 unx     2466 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/locale_mgmt_aix.h
+-rw-r--r--  2.0 unx     1705 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/support.h
+-rw-r--r--  2.0 unx     5718 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/xlocale.h
+-rw-r--r--  2.0 unx     1886 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/musl/xlocale.h
+-rw-r--r--  2.0 unx      845 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/newlib/xlocale.h
+-rw-r--r--  2.0 unx      476 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/floatingpoint.h
+-rw-r--r--  2.0 unx     1230 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/wchar.h
+-rw-r--r--  2.0 unx     2257 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/xlocale.h
+-rw-r--r--  2.0 unx     2840 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/limits_msvc_win32.h
+-rw-r--r--  2.0 unx     6858 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/locale_win32.h
+-rw-r--r--  2.0 unx     1439 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__nop_locale_mgmt.h
+-rw-r--r--  2.0 unx     4757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__posix_l_fallback.h
+-rw-r--r--  2.0 unx     2396 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__strtonum_fallback.h
+-rw-r--r--  2.0 unx      806 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/addressof.h
+-rw-r--r--  2.0 unx    11470 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/adjacent_difference.h
+-rw-r--r--  2.0 unx     4146 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/advance.h
+-rw-r--r--  2.0 unx    11786 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/allocate_unique.h
+-rw-r--r--  2.0 unx    84960 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/binary_search.h
+-rw-r--r--  2.0 unx    30032 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/complex.h
+-rw-r--r--  2.0 unx    22187 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/copy.h
+-rw-r--r--  2.0 unx     8688 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/count.h
+-rw-r--r--  2.0 unx     3909 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_allocator.h
+-rw-r--r--  2.0 unx     1419 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_delete.h
+-rw-r--r--  2.0 unx     1713 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_free.h
+-rw-r--r--  2.0 unx     1855 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_make_unique.h
+-rw-r--r--  2.0 unx     2703 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_malloc.h
+-rw-r--r--  2.0 unx     5901 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_malloc_allocator.h
+-rw-r--r--  2.0 unx     2725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_new.h
+-rw-r--r--  2.0 unx     5541 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_new_allocator.h
+-rw-r--r--  2.0 unx     6033 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_ptr.h
+-rw-r--r--  2.0 unx    28560 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_reference.h
+-rw-r--r--  2.0 unx    18536 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/device_vector.h
+-rw-r--r--  2.0 unx     2358 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/distance.h
+-rw-r--r--  2.0 unx     9996 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/equal.h
+-rw-r--r--  2.0 unx      813 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/event.h
+-rw-r--r--  2.0 unx    12124 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/execution_policy.h
+-rw-r--r--  2.0 unx    31413 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/extrema.h
+-rw-r--r--  2.0 unx     7526 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/fill.h
+-rw-r--r--  2.0 unx    11830 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/find.h
+-rw-r--r--  2.0 unx    10406 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/for_each.h
+-rw-r--r--  2.0 unx    55075 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/functional.h
+-rw-r--r--  2.0 unx     5286 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/future.h
+-rw-r--r--  2.0 unx    23135 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/gather.h
+-rw-r--r--  2.0 unx     8286 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/generate.h
+-rw-r--r--  2.0 unx    18632 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/host_vector.h
+-rw-r--r--  2.0 unx    12051 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/inner_product.h
+-rw-r--r--  2.0 unx      412 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/limits.h
+-rw-r--r--  2.0 unx    10369 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/logical.h
+-rw-r--r--  2.0 unx    15359 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/memory.h
+-rw-r--r--  2.0 unx    39495 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/merge.h
+-rw-r--r--  2.0 unx    11041 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mismatch.h
+-rw-r--r--  2.0 unx    97957 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/optional.h
+-rw-r--r--  2.0 unx     9424 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/pair.h
+-rw-r--r--  2.0 unx    67577 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/partition.h
+-rw-r--r--  2.0 unx     3724 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/per_device_resource.h
+-rw-r--r--  2.0 unx     3773 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random.h
+-rw-r--r--  2.0 unx    37631 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/reduce.h
+-rw-r--r--  2.0 unx    37924 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/remove.h
+-rw-r--r--  2.0 unx    33675 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/replace.h
+-rw-r--r--  2.0 unx     8423 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/reverse.h
+-rw-r--r--  2.0 unx    80567 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/scan.h
+-rw-r--r--  2.0 unx    21699 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/scatter.h
+-rw-r--r--  2.0 unx    11827 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/sequence.h
+-rw-r--r--  2.0 unx   186894 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/set_operations.h
+-rw-r--r--  2.0 unx     6664 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/shuffle.h
+-rw-r--r--  2.0 unx    60965 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/sort.h
+-rw-r--r--  2.0 unx     6737 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/swap.h
+-rw-r--r--  2.0 unx     1454 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system_error.h
+-rw-r--r--  2.0 unx     4785 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/tabulate.h
+-rw-r--r--  2.0 unx    36715 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/transform.h
+-rw-r--r--  2.0 unx     8316 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/transform_reduce.h
+-rw-r--r--  2.0 unx    15301 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/transform_scan.h
+-rw-r--r--  2.0 unx    20598 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/tuple.h
+-rw-r--r--  2.0 unx    12752 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/uninitialized_copy.h
+-rw-r--r--  2.0 unx    10409 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/uninitialized_fill.h
+-rw-r--r--  2.0 unx    53968 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/unique.h
+-rw-r--r--  2.0 unx     2684 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/universal_allocator.h
+-rw-r--r--  2.0 unx      810 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/universal_ptr.h
+-rw-r--r--  2.0 unx     1918 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/universal_vector.h
+-rw-r--r--  2.0 unx     2848 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/version.h
+-rw-r--r--  2.0 unx     6881 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/zip_function.h
+-rw-r--r--  2.0 unx     3897 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/async/copy.h
+-rw-r--r--  2.0 unx     2867 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/async/for_each.h
+-rw-r--r--  2.0 unx    11680 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/async/reduce.h
+-rw-r--r--  2.0 unx     9648 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/async/scan.h
+-rw-r--r--  2.0 unx     6915 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/async/sort.h
+-rw-r--r--  2.0 unx     3152 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/async/transform.h
+-rw-r--r--  2.0 unx     3376 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/adjacent_difference.inl
+-rw-r--r--  2.0 unx     2085 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/advance.inl
+-rw-r--r--  2.0 unx     1087 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/algorithm_wrapper.h
+-rw-r--r--  2.0 unx     8099 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/alignment.h
+-rw-r--r--  2.0 unx     2793 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator_aware_execution_policy.h
+-rw-r--r--  2.0 unx    19330 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/binary_search.inl
+-rw-r--r--  2.0 unx     1329 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/caching_allocator.h
+-rw-r--r--  2.0 unx      768 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config.h
+-rw-r--r--  2.0 unx     7398 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/contiguous_storage.h
+-rw-r--r--  2.0 unx    16225 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/contiguous_storage.inl
+-rw-r--r--  2.0 unx     2924 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/copy.h
+-rw-r--r--  2.0 unx     4690 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/copy.inl
+-rw-r--r--  2.0 unx     2369 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/copy_if.h
+-rw-r--r--  2.0 unx     3758 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/copy_if.inl
+-rw-r--r--  2.0 unx     1999 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/count.h
+-rw-r--r--  2.0 unx     2831 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/count.inl
+-rw-r--r--  2.0 unx      893 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/cpp11_required.h
+-rw-r--r--  2.0 unx      892 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/cpp14_required.h
+-rw-r--r--  2.0 unx     2464 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/cstdint.h
+-rw-r--r--  2.0 unx     2827 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/dependencies_aware_execution_policy.h
+-rw-r--r--  2.0 unx     1233 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/device_delete.inl
+-rw-r--r--  2.0 unx     1177 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/device_free.inl
+-rw-r--r--  2.0 unx     1596 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/device_malloc.inl
+-rw-r--r--  2.0 unx     1664 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/device_new.inl
+-rw-r--r--  2.0 unx     1703 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/device_ptr.inl
+-rw-r--r--  2.0 unx     1135 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/distance.inl
+-rw-r--r--  2.0 unx     2918 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/equal.inl
+-rw-r--r--  2.0 unx     4450 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/event_error.h
+-rw-r--r--  2.0 unx     5260 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/execute_with_allocator.h
+-rw-r--r--  2.0 unx     3131 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/execute_with_allocator_fwd.h
+-rw-r--r--  2.0 unx     7813 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/execute_with_dependencies.h
+-rw-r--r--  2.0 unx     2115 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/execution_policy.h
+-rw-r--r--  2.0 unx     6164 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/extrema.inl
+-rw-r--r--  2.0 unx     2730 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/fill.inl
+-rw-r--r--  2.0 unx     3633 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/find.inl
+-rw-r--r--  2.0 unx     2892 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/for_each.inl
+-rw-r--r--  2.0 unx     4752 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/function.h
+-rw-r--r--  2.0 unx     4292 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional.inl
+-rw-r--r--  2.0 unx     6932 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/gather.inl
+-rw-r--r--  2.0 unx     2899 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/generate.inl
+-rw-r--r--  2.0 unx     2005 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/get_iterator_value.h
+-rw-r--r--  2.0 unx     3771 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/inner_product.inl
+-rw-r--r--  2.0 unx     3653 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/integer_math.h
+-rw-r--r--  2.0 unx     3006 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/integer_traits.h
+-rw-r--r--  2.0 unx    13655 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/internal_functional.h
+-rw-r--r--  2.0 unx     3245 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/logical.inl
+-rw-r--r--  2.0 unx     2738 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/malloc_and_free.h
+-rw-r--r--  2.0 unx     5928 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/memory_algorithms.h
+-rw-r--r--  2.0 unx     1304 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/memory_wrapper.h
+-rw-r--r--  2.0 unx     9084 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/merge.inl
+-rw-r--r--  2.0 unx     1465 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/minmax.h
+-rw-r--r--  2.0 unx     3765 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/mismatch.inl
+-rw-r--r--  2.0 unx      893 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/modern_gcc_required.h
+-rw-r--r--  2.0 unx     3438 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/numeric_traits.h
+-rw-r--r--  2.0 unx     1085 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/numeric_wrapper.h
+-rw-r--r--  2.0 unx     4307 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/overlapped_copy.h
+-rw-r--r--  2.0 unx     5007 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/pair.inl
+-rw-r--r--  2.0 unx    15177 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/partition.inl
+-rw-r--r--  2.0 unx     9240 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/pointer.h
+-rw-r--r--  2.0 unx     6755 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/pointer.inl
+-rw-r--r--  2.0 unx    42969 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/preprocessor.h
+-rw-r--r--  2.0 unx     1542 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/raw_pointer_cast.h
+-rw-r--r--  2.0 unx     8069 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/raw_reference_cast.h
+-rw-r--r--  2.0 unx     9632 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/reduce.inl
+-rw-r--r--  2.0 unx    14913 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/reference.h
+-rw-r--r--  2.0 unx      848 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/reference_forward_declaration.h
+-rw-r--r--  2.0 unx     8570 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/remove.inl
+-rw-r--r--  2.0 unx     8650 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/replace.inl
+-rw-r--r--  2.0 unx     2974 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/reverse.inl
+-rw-r--r--  2.0 unx    20546 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/scan.inl
+-rw-r--r--  2.0 unx     5726 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/scatter.inl
+-rw-r--r--  2.0 unx     2514 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/select_system.h
+-rw-r--r--  2.0 unx     1460 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/seq.h
+-rw-r--r--  2.0 unx     3537 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/sequence.inl
+-rw-r--r--  2.0 unx    41943 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/set_operations.inl
+-rw-r--r--  2.0 unx     2905 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/shuffle.inl
+-rw-r--r--  2.0 unx    13901 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/sort.inl
+-rw-r--r--  2.0 unx     3156 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/static_assert.h
+-rw-r--r--  2.0 unx     4363 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/static_map.h
+-rw-r--r--  2.0 unx      930 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/swap.h
+-rw-r--r--  2.0 unx      731 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/swap.inl
+-rw-r--r--  2.0 unx     2155 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/swap_ranges.inl
+-rw-r--r--  2.0 unx     1883 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/tabulate.inl
+-rw-r--r--  2.0 unx     5245 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/temporary_array.h
+-rw-r--r--  2.0 unx     5105 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/temporary_array.inl
+-rw-r--r--  2.0 unx     2865 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/temporary_buffer.h
+-rw-r--r--  2.0 unx     9221 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/transform.inl
+-rw-r--r--  2.0 unx     2385 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/transform_reduce.inl
+-rw-r--r--  2.0 unx     4651 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/transform_scan.inl
+-rw-r--r--  2.0 unx     3050 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/trivial_sequence.h
+-rw-r--r--  2.0 unx    30303 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/tuple.inl
+-rw-r--r--  2.0 unx     2869 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/tuple_algorithms.h
+-rw-r--r--  2.0 unx     1833 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/tuple_meta_transform.h
+-rw-r--r--  2.0 unx     2577 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/tuple_transform.h
+-rw-r--r--  2.0 unx     3697 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_deduction.h
+-rw-r--r--  2.0 unx    20928 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits.h
+-rw-r--r--  2.0 unx     3481 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/uninitialized_copy.inl
+-rw-r--r--  2.0 unx     3080 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/uninitialized_fill.inl
+-rw-r--r--  2.0 unx    14409 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/unique.inl
+-rw-r--r--  2.0 unx      737 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/use_default.h
+-rw-r--r--  2.0 unx    23537 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/vector_base.h
+-rw-r--r--  2.0 unx    38433 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/vector_base.inl
+-rw-r--r--  2.0 unx    13771 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/allocator_traits.h
+-rw-r--r--  2.0 unx    12771 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/allocator_traits.inl
+-rw-r--r--  2.0 unx     1632 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/copy_construct_range.h
+-rw-r--r--  2.0 unx    11114 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/copy_construct_range.inl
+-rw-r--r--  2.0 unx      968 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/default_construct_range.h
+-rw-r--r--  2.0 unx     3139 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/default_construct_range.inl
+-rw-r--r--  2.0 unx      947 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/destroy_range.h
+-rw-r--r--  2.0 unx     4495 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/destroy_range.inl
+-rw-r--r--  2.0 unx      989 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/fill_construct_range.h
+-rw-r--r--  2.0 unx     3083 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/fill_construct_range.inl
+-rw-r--r--  2.0 unx     1388 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/malloc_allocator.h
+-rw-r--r--  2.0 unx     1992 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/malloc_allocator.inl
+-rw-r--r--  2.0 unx     1861 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/no_throw_allocator.h
+-rw-r--r--  2.0 unx     3886 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/tagged_allocator.h
+-rw-r--r--  2.0 unx     2656 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/tagged_allocator.inl
+-rw-r--r--  2.0 unx     2325 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/temporary_allocator.h
+-rw-r--r--  2.0 unx     2481 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/allocator/temporary_allocator.inl
+-rw-r--r--  2.0 unx     7437 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/arithmetic.h
+-rw-r--r--  2.0 unx     4475 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/c99math.h
+-rw-r--r--  2.0 unx    24185 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/catrig.h
+-rw-r--r--  2.0 unx    14281 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/catrigf.h
+-rw-r--r--  2.0 unx     7222 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/ccosh.h
+-rw-r--r--  2.0 unx     4624 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/ccoshf.h
+-rw-r--r--  2.0 unx     5818 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/cexp.h
+-rw-r--r--  2.0 unx     5039 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/cexpf.h
+-rw-r--r--  2.0 unx     5851 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/clog.h
+-rw-r--r--  2.0 unx     5387 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/clogf.h
+-rw-r--r--  2.0 unx     8058 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/complex.inl
+-rw-r--r--  2.0 unx     1695 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/cpow.h
+-rw-r--r--  2.0 unx     1892 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/cproj.h
+-rw-r--r--  2.0 unx     6787 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/csinh.h
+-rw-r--r--  2.0 unx     4567 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/csinhf.h
+-rw-r--r--  2.0 unx     4620 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/csqrt.h
+-rw-r--r--  2.0 unx     4526 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/csqrtf.h
+-rw-r--r--  2.0 unx     6117 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/ctanh.h
+-rw-r--r--  2.0 unx     3802 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/ctanhf.h
+-rw-r--r--  2.0 unx     3203 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/math_private.h
+-rw-r--r--  2.0 unx     1725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/complex/stream.h
+-rw-r--r--  2.0 unx     8378 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/compiler.h
+-rw-r--r--  2.0 unx     2041 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/compiler_fence.h
+-rw-r--r--  2.0 unx     1478 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/config.h
+-rw-r--r--  2.0 unx     3806 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/cpp_compatibility.h
+-rw-r--r--  2.0 unx     5461 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/cpp_dialect.h
+-rw-r--r--  2.0 unx      956 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/debug.h
+-rw-r--r--  2.0 unx     1437 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/deprecated.h
+-rw-r--r--  2.0 unx     1575 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/device_system.h
+-rw-r--r--  2.0 unx     1329 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/exec_check_disable.h
+-rw-r--r--  2.0 unx      896 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/forceinline.h
+-rw-r--r--  2.0 unx      995 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/global_workarounds.h
+-rw-r--r--  2.0 unx     1278 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/host_device.h
+-rw-r--r--  2.0 unx     1386 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/host_system.h
+-rw-r--r--  2.0 unx     1222 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/memory_resource.h
+-rw-r--r--  2.0 unx     4173 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/namespace.h
+-rw-r--r--  2.0 unx      897 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/config/simple_defines.h
+-rw-r--r--  2.0 unx     3975 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/actor.h
+-rw-r--r--  2.0 unx     3249 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/actor.inl
+-rw-r--r--  2.0 unx     1613 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/argument.h
+-rw-r--r--  2.0 unx     4163 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/composite.h
+-rw-r--r--  2.0 unx     1015 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators.h
+-rw-r--r--  2.0 unx      970 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/placeholder.h
+-rw-r--r--  2.0 unx     1523 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/value.h
+-rw-r--r--  2.0 unx    10319 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators/arithmetic_operators.h
+-rw-r--r--  2.0 unx     2164 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators/assignment_operator.h
+-rw-r--r--  2.0 unx     8009 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators/bitwise_operators.h
+-rw-r--r--  2.0 unx    12970 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators/compound_assignment_operators.h
+-rw-r--r--  2.0 unx     3583 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators/logical_operators.h
+-rw-r--r--  2.0 unx     3747 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators/operator_adaptors.h
+-rw-r--r--  2.0 unx     7904 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/functional/operators/relational_operators.h
+-rw-r--r--  2.0 unx     3039 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/mpl/math.h
+-rw-r--r--  2.0 unx     7043 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/range/head_flags.h
+-rw-r--r--  2.0 unx     3933 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/range/tail_flags.h
+-rw-r--r--  2.0 unx     3375 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/function_traits.h
+-rw-r--r--  2.0 unx     1933 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_member_function.h
+-rw-r--r--  2.0 unx     1135 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_nested_type.h
+-rw-r--r--  2.0 unx     1163 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_trivial_assign.h
+-rw-r--r--  2.0 unx    16096 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/is_call_possible.h
+-rw-r--r--  2.0 unx     1094 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/is_metafunction_defined.h
+-rw-r--r--  2.0 unx     4445 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/minimum_type.h
+-rw-r--r--  2.0 unx    11185 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/pointer_traits.h
+-rw-r--r--  2.0 unx     1743 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/result_of_adaptable_function.h
+-rw-r--r--  2.0 unx     1073 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/iterator/is_discard_iterator.h
+-rw-r--r--  2.0 unx     1755 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/type_traits/iterator/is_output_iterator.h
+-rw-r--r--  2.0 unx     1360 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/detail/util/align.h
+-rw-r--r--  2.0 unx     8335 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/constant_iterator.h
+-rw-r--r--  2.0 unx     8164 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/counting_iterator.h
+-rw-r--r--  2.0 unx     4968 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/discard_iterator.h
+-rw-r--r--  2.0 unx     8353 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/iterator_adaptor.h
+-rw-r--r--  2.0 unx     9225 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/iterator_categories.h
+-rw-r--r--  2.0 unx    22014 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/iterator_facade.h
+-rw-r--r--  2.0 unx     1948 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/iterator_traits.h
+-rw-r--r--  2.0 unx     7252 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/permutation_iterator.h
+-rw-r--r--  2.0 unx     2379 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/retag.h
+-rw-r--r--  2.0 unx     7185 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/reverse_iterator.h
+-rw-r--r--  2.0 unx     5745 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/transform_input_output_iterator.h
+-rw-r--r--  2.0 unx    11679 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/transform_iterator.h
+-rw-r--r--  2.0 unx     5254 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/transform_output_iterator.h
+-rw-r--r--  2.0 unx     8303 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/zip_iterator.h
+-rw-r--r--  2.0 unx     1196 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/any_assign.h
+-rw-r--r--  2.0 unx     1006 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/any_system_tag.h
+-rw-r--r--  2.0 unx     2159 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/constant_iterator_base.h
+-rw-r--r--  2.0 unx     4469 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/counting_iterator.inl
+-rw-r--r--  2.0 unx     1033 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/device_system_tag.h
+-rw-r--r--  2.0 unx     1742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/discard_iterator_base.h
+-rw-r--r--  2.0 unx     1228 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/distance_from_result.h
+-rw-r--r--  2.0 unx     1019 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/host_system_tag.h
+-rw-r--r--  2.0 unx     1611 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/is_iterator_category.h
+-rw-r--r--  2.0 unx     2713 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_adaptor_base.h
+-rw-r--r--  2.0 unx     2457 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_category_to_system.h
+-rw-r--r--  2.0 unx     4066 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_category_to_traversal.h
+-rw-r--r--  2.0 unx     1746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_category_with_system_and_traversal.h
+-rw-r--r--  2.0 unx     9981 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_facade_category.h
+-rw-r--r--  2.0 unx     3578 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_traits.inl
+-rw-r--r--  2.0 unx     1108 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/iterator_traversal_tags.h
+-rw-r--r--  2.0 unx     4098 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/join_iterator.h
+-rw-r--r--  2.0 unx     1873 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/minimum_category.h
+-rw-r--r--  2.0 unx     2900 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/minimum_system.h
+-rw-r--r--  2.0 unx     2005 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/normal_iterator.h
+-rw-r--r--  2.0 unx     1611 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/permutation_iterator_base.h
+-rw-r--r--  2.0 unx     3800 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/retag.h
+-rw-r--r--  2.0 unx     3494 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/reverse_iterator.inl
+-rw-r--r--  2.0 unx     1119 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/reverse_iterator_base.h
+-rw-r--r--  2.0 unx     2550 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/tagged_iterator.h
+-rw-r--r--  2.0 unx     3433 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/transform_input_output_iterator.inl
+-rw-r--r--  2.0 unx     2680 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/transform_iterator.inl
+-rw-r--r--  2.0 unx     2395 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/transform_output_iterator.inl
+-rw-r--r--  2.0 unx     3978 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/tuple_of_iterator_references.h
+-rw-r--r--  2.0 unx     2475 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/universal_categories.h
+-rw-r--r--  2.0 unx     4335 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/zip_iterator.inl
+-rw-r--r--  2.0 unx     8879 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/iterator/detail/zip_iterator_base.h
+-rw-r--r--  2.0 unx     8829 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/allocator.h
+-rw-r--r--  2.0 unx     1311 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/device_memory_resource.h
+-rw-r--r--  2.0 unx    17230 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/disjoint_pool.h
+-rw-r--r--  2.0 unx     3712 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/disjoint_sync_pool.h
+-rw-r--r--  2.0 unx     2064 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/disjoint_tls_pool.h
+-rw-r--r--  2.0 unx     1753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/fancy_pointer_resource.h
+-rw-r--r--  2.0 unx     1041 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/host_memory_resource.h
+-rw-r--r--  2.0 unx     7471 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/memory_resource.h
+-rw-r--r--  2.0 unx     2987 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/new.h
+-rw-r--r--  2.0 unx     1605 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/polymorphic_adaptor.h
+-rw-r--r--  2.0 unx    19640 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/pool.h
+-rw-r--r--  2.0 unx     5017 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/pool_options.h
+-rw-r--r--  2.0 unx     3296 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/sync_pool.h
+-rw-r--r--  2.0 unx     1744 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/tls_pool.h
+-rw-r--r--  2.0 unx      714 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/universal_memory_resource.h
+-rw-r--r--  2.0 unx     1249 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/mr/validator.h
+-rw-r--r--  2.0 unx     8399 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/discard_block_engine.h
+-rw-r--r--  2.0 unx     9594 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/linear_congruential_engine.h
+-rw-r--r--  2.0 unx     7463 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/linear_feedback_shift_engine.h
+-rw-r--r--  2.0 unx     9535 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/normal_distribution.h
+-rw-r--r--  2.0 unx     8583 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/subtract_with_carry_engine.h
+-rw-r--r--  2.0 unx     9527 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/uniform_int_distribution.h
+-rw-r--r--  2.0 unx     9580 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/uniform_real_distribution.h
+-rw-r--r--  2.0 unx     9200 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/xor_combine_engine.h
+-rw-r--r--  2.0 unx     5053 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/discard_block_engine.inl
+-rw-r--r--  2.0 unx     4910 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/linear_congruential_engine.inl
+-rw-r--r--  2.0 unx     3183 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/linear_congruential_engine_discard.h
+-rw-r--r--  2.0 unx     4962 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/linear_feedback_shift_engine.inl
+-rw-r--r--  2.0 unx     1194 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/linear_feedback_shift_engine_wordmask.h
+-rw-r--r--  2.0 unx     1757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/mod.h
+-rw-r--r--  2.0 unx     6499 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/normal_distribution.inl
+-rw-r--r--  2.0 unx     4200 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/normal_distribution_base.h
+-rw-r--r--  2.0 unx     1334 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/random_core_access.h
+-rw-r--r--  2.0 unx     5896 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/subtract_with_carry_engine.inl
+-rw-r--r--  2.0 unx     6754 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/uniform_int_distribution.inl
+-rw-r--r--  2.0 unx     6699 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/uniform_real_distribution.inl
+-rw-r--r--  2.0 unx     6274 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/xor_combine_engine.inl
+-rw-r--r--  2.0 unx     7961 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/random/detail/xor_combine_engine_max.h
+-rw-r--r--  2.0 unx    18347 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/error_code.h
+-rw-r--r--  2.0 unx     5649 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/system_error.h
+-rw-r--r--  2.0 unx     5152 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/execution_policy.h
+-rw-r--r--  2.0 unx     3356 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/memory.h
+-rw-r--r--  2.0 unx     2007 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/memory_resource.h
+-rw-r--r--  2.0 unx     3773 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/pointer.h
+-rw-r--r--  2.0 unx     3166 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/vector.h
+-rw-r--r--  2.0 unx      777 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/adjacent_difference.h
+-rw-r--r--  2.0 unx      763 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/assign_value.h
+-rw-r--r--  2.0 unx      801 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/binary_search.h
+-rw-r--r--  2.0 unx      747 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/copy.h
+-rw-r--r--  2.0 unx      753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/copy_if.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/count.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/equal.h
+-rw-r--r--  2.0 unx     2075 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/execution_policy.h
+-rw-r--r--  2.0 unx      764 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/extrema.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/fill.h
+-rw-r--r--  2.0 unx      747 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/find.h
+-rw-r--r--  2.0 unx      755 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/for_each.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/gather.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/generate.h
+-rw-r--r--  2.0 unx      757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/get_value.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/inner_product.h
+-rw-r--r--  2.0 unx      757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/iter_swap.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/logical.h
+-rw-r--r--  2.0 unx      767 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/malloc_and_free.h
+-rw-r--r--  2.0 unx     1346 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/memory.inl
+-rw-r--r--  2.0 unx      749 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/merge.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/mismatch.h
+-rw-r--r--  2.0 unx     1340 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/par.h
+-rw-r--r--  2.0 unx      757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/partition.h
+-rw-r--r--  2.0 unx      723 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/per_device_resource.h
+-rw-r--r--  2.0 unx      751 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/reduce.h
+-rw-r--r--  2.0 unx      765 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/reduce_by_key.h
+-rw-r--r--  2.0 unx      751 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/remove.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/replace.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/reverse.h
+-rw-r--r--  2.0 unx      747 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/scan.h
+-rw-r--r--  2.0 unx      776 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/scan_by_key.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/scatter.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/sequence.h
+-rw-r--r--  2.0 unx      771 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/set_operations.h
+-rw-r--r--  2.0 unx      747 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/sort.h
+-rw-r--r--  2.0 unx      702 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/swap_ranges.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/tabulate.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/temporary_buffer.h
+-rw-r--r--  2.0 unx      700 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform_reduce.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform_scan.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/uninitialized_copy.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/uninitialized_fill.h
+-rw-r--r--  2.0 unx      751 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/unique.h
+-rw-r--r--  2.0 unx      765 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/unique_by_key.h
+-rw-r--r--  2.0 unx     3535 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cpp/detail/vector.inl
+-rw-r--r--  2.0 unx     5328 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/config.h
+-rw-r--r--  2.0 unx     6921 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/error.h
+-rw-r--r--  2.0 unx     1889 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/execution_policy.h
+-rw-r--r--  2.0 unx     1529 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/future.h
+-rw-r--r--  2.0 unx     3672 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/memory.h
+-rw-r--r--  2.0 unx     3903 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/memory_resource.h
+-rw-r--r--  2.0 unx     4433 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/pointer.h
+-rw-r--r--  2.0 unx     3269 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/vector.h
+-rw-r--r--  2.0 unx    11691 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/adjacent_difference.h
+-rw-r--r--  2.0 unx     2975 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/assign_value.h
+-rw-r--r--  2.0 unx      669 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/binary_search.h
+-rw-r--r--  2.0 unx     3268 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/cdp_dispatch.h
+-rw-r--r--  2.0 unx     6472 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/copy.h
+-rw-r--r--  2.0 unx    29007 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/copy_if.h
+-rw-r--r--  2.0 unx     3412 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/count.h
+-rw-r--r--  2.0 unx    11581 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/cross_system.h
+-rw-r--r--  2.0 unx     3678 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/dispatch.h
+-rw-r--r--  2.0 unx     2990 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/equal.h
+-rw-r--r--  2.0 unx     2351 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/error.inl
+-rw-r--r--  2.0 unx     3185 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/execution_policy.h
+-rw-r--r--  2.0 unx    19192 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/extrema.h
+-rw-r--r--  2.0 unx     3288 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/fill.h
+-rw-r--r--  2.0 unx     7127 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/find.h
+-rw-r--r--  2.0 unx     3740 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/for_each.h
+-rw-r--r--  2.0 unx    34440 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/future.inl
+-rw-r--r--  2.0 unx     4134 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/gather.h
+-rw-r--r--  2.0 unx     3305 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/generate.h
+-rw-r--r--  2.0 unx     2538 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/get_value.h
+-rw-r--r--  2.0 unx     1185 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/guarded_cuda_runtime_api.h
+-rw-r--r--  2.0 unx     1925 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/guarded_driver_types.h
+-rw-r--r--  2.0 unx     3886 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/inner_product.h
+-rw-r--r--  2.0 unx     1716 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/iter_swap.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/logical.h
+-rw-r--r--  2.0 unx     1221 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/make_unsigned_special.h
+-rw-r--r--  2.0 unx     3728 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/malloc_and_free.h
+-rw-r--r--  2.0 unx     1378 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/memory.inl
+-rw-r--r--  2.0 unx    35370 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/merge.h
+-rw-r--r--  2.0 unx     4575 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/mismatch.h
+-rw-r--r--  2.0 unx     8060 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/par.h
+-rw-r--r--  2.0 unx     3070 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/par_to_seq.h
+-rw-r--r--  2.0 unx     5683 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/parallel_for.h
+-rw-r--r--  2.0 unx    38777 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/partition.h
+-rw-r--r--  2.0 unx     2637 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/per_device_resource.h
+-rw-r--r--  2.0 unx    39246 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce.h
+-rw-r--r--  2.0 unx    46036 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce_by_key.h
+-rw-r--r--  2.0 unx     4764 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/remove.h
+-rw-r--r--  2.0 unx     7294 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/replace.h
+-rw-r--r--  2.0 unx     3770 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/reverse.h
+-rw-r--r--  2.0 unx    14325 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scan.h
+-rw-r--r--  2.0 unx    18657 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scan_by_key.h
+-rw-r--r--  2.0 unx     3980 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scatter.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/sequence.h
+-rw-r--r--  2.0 unx    69146 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/set_operations.h
+-rw-r--r--  2.0 unx    24404 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/sort.h
+-rw-r--r--  2.0 unx     3813 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/swap_ranges.h
+-rw-r--r--  2.0 unx     3145 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/tabulate.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/temporary_buffer.h
+-rw-r--r--  2.0 unx     2218 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/terminate.h
+-rw-r--r--  2.0 unx    13521 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform.h
+-rw-r--r--  2.0 unx     3052 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform_reduce.h
+-rw-r--r--  2.0 unx     4866 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform_scan.h
+-rw-r--r--  2.0 unx     4129 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/uninitialized_copy.h
+-rw-r--r--  2.0 unx     3924 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/uninitialized_fill.h
+-rw-r--r--  2.0 unx    28154 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/unique.h
+-rw-r--r--  2.0 unx    32569 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/unique_by_key.h
+-rw-r--r--  2.0 unx    16584 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/util.h
+-rw-r--r--  2.0 unx    15870 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/copy.h
+-rw-r--r--  2.0 unx     4424 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/customization.h
+-rw-r--r--  2.0 unx     7117 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/exclusive_scan.h
+-rw-r--r--  2.0 unx     4562 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/for_each.h
+-rw-r--r--  2.0 unx     6887 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/inclusive_scan.h
+-rw-r--r--  2.0 unx     9060 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/reduce.h
+-rw-r--r--  2.0 unx     1920 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/scan.h
+-rw-r--r--  2.0 unx    13297 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/sort.h
+-rw-r--r--  2.0 unx     4865 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/transform.h
+-rw-r--r--  2.0 unx    56831 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/agent_launcher.h
+-rw-r--r--  2.0 unx     4227 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/alignment.h
+-rw-r--r--  2.0 unx     4949 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/triple_chevron_launch.h
+-rw-r--r--  2.0 unx    27432 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/util.h
+-rw-r--r--  2.0 unx     9487 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/internal/copy_cross_system.h
+-rw-r--r--  2.0 unx     2788 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/cuda/detail/internal/copy_device_to_device.h
+-rw-r--r--  2.0 unx     1337 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/bad_alloc.h
+-rw-r--r--  2.0 unx     4271 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/errno.h
+-rw-r--r--  2.0 unx     9628 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/error_category.inl
+-rw-r--r--  2.0 unx     4539 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/error_code.inl
+-rw-r--r--  2.0 unx     3203 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/error_condition.inl
+-rw-r--r--  2.0 unx     2346 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/system_error.inl
+-rw-r--r--  2.0 unx     1839 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/adjacent_difference.h
+-rw-r--r--  2.0 unx     1734 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/assign_value.h
+-rw-r--r--  2.0 unx     1749 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/binary_search.h
+-rw-r--r--  2.0 unx     1614 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/copy.h
+-rw-r--r--  2.0 unx     1664 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/copy_if.h
+-rw-r--r--  2.0 unx     1630 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/count.h
+-rw-r--r--  2.0 unx     1630 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/equal.h
+-rw-r--r--  2.0 unx     1662 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/extrema.h
+-rw-r--r--  2.0 unx     1614 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/fill.h
+-rw-r--r--  2.0 unx     1614 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/find.h
+-rw-r--r--  2.0 unx     1674 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/for_each.h
+-rw-r--r--  2.0 unx     1644 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/gather.h
+-rw-r--r--  2.0 unx     1674 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/generate.h
+-rw-r--r--  2.0 unx     1689 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/get_value.h
+-rw-r--r--  2.0 unx     1749 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/inner_product.h
+-rw-r--r--  2.0 unx     1689 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/iter_swap.h
+-rw-r--r--  2.0 unx     1659 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/logical.h
+-rw-r--r--  2.0 unx     1779 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/malloc_and_free.h
+-rw-r--r--  2.0 unx     1629 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/merge.h
+-rw-r--r--  2.0 unx     1661 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/mismatch.h
+-rw-r--r--  2.0 unx     1689 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/partition.h
+-rw-r--r--  2.0 unx     1647 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/per_device_resource.h
+-rw-r--r--  2.0 unx     1644 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/reduce.h
+-rw-r--r--  2.0 unx     1749 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/reduce_by_key.h
+-rw-r--r--  2.0 unx     1644 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/remove.h
+-rw-r--r--  2.0 unx     1659 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/replace.h
+-rw-r--r--  2.0 unx     1659 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/reverse.h
+-rw-r--r--  2.0 unx     1601 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/scan.h
+-rw-r--r--  2.0 unx     1719 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/scan_by_key.h
+-rw-r--r--  2.0 unx     1659 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/scatter.h
+-rw-r--r--  2.0 unx     1674 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/sequence.h
+-rw-r--r--  2.0 unx     1764 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/set_operations.h
+-rw-r--r--  2.0 unx     1614 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/sort.h
+-rw-r--r--  2.0 unx     1719 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/swap_ranges.h
+-rw-r--r--  2.0 unx     1674 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/tabulate.h
+-rw-r--r--  2.0 unx     1825 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/temporary_buffer.h
+-rw-r--r--  2.0 unx     1689 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/transform.h
+-rw-r--r--  2.0 unx     1794 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/transform_reduce.h
+-rw-r--r--  2.0 unx     1764 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/transform_scan.h
+-rw-r--r--  2.0 unx     1824 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/uninitialized_copy.h
+-rw-r--r--  2.0 unx     1824 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/uninitialized_fill.h
+-rw-r--r--  2.0 unx     1644 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/unique.h
+-rw-r--r--  2.0 unx     1749 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/unique_by_key.h
+-rw-r--r--  2.0 unx     1315 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/copy.h
+-rw-r--r--  2.0 unx     1359 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/for_each.h
+-rw-r--r--  2.0 unx     1337 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/reduce.h
+-rw-r--r--  2.0 unx     1316 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/scan.h
+-rw-r--r--  2.0 unx     1315 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/sort.h
+-rw-r--r--  2.0 unx     1375 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/adl/async/transform.h
+-rw-r--r--  2.0 unx     1786 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/adjacent_difference.h
+-rw-r--r--  2.0 unx     2697 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/adjacent_difference.inl
+-rw-r--r--  2.0 unx     1021 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/advance.h
+-rw-r--r--  2.0 unx     1744 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/advance.inl
+-rw-r--r--  2.0 unx     6884 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/binary_search.h
+-rw-r--r--  2.0 unx    14695 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/binary_search.inl
+-rw-r--r--  2.0 unx     1594 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy.h
+-rw-r--r--  2.0 unx     2690 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy.inl
+-rw-r--r--  2.0 unx     1850 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy_if.h
+-rw-r--r--  2.0 unx     5234 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/copy_if.inl
+-rw-r--r--  2.0 unx     1530 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/count.h
+-rw-r--r--  2.0 unx     2473 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/count.inl
+-rw-r--r--  2.0 unx     1133 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/distance.h
+-rw-r--r--  2.0 unx     2124 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/distance.inl
+-rw-r--r--  2.0 unx     1467 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/equal.h
+-rw-r--r--  2.0 unx     2020 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/equal.inl
+-rw-r--r--  2.0 unx     3080 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/extrema.h
+-rw-r--r--  2.0 unx     9522 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/extrema.inl
+-rw-r--r--  2.0 unx     1814 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/fill.h
+-rw-r--r--  2.0 unx     1820 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/find.h
+-rw-r--r--  2.0 unx     4606 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/find.inl
+-rw-r--r--  2.0 unx     2155 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/for_each.h
+-rw-r--r--  2.0 unx     2915 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/gather.h
+-rw-r--r--  2.0 unx     4258 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/gather.inl
+-rw-r--r--  2.0 unx     1595 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/generate.h
+-rw-r--r--  2.0 unx     3865 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/generate.inl
+-rw-r--r--  2.0 unx     1894 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/inner_product.h
+-rw-r--r--  2.0 unx     2626 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/inner_product.inl
+-rw-r--r--  2.0 unx     1828 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/logical.h
+-rw-r--r--  2.0 unx     2078 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/memory.h
+-rw-r--r--  2.0 unx     2876 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/memory.inl
+-rw-r--r--  2.0 unx     3335 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/merge.h
+-rw-r--r--  2.0 unx     5275 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/merge.inl
+-rw-r--r--  2.0 unx     1653 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/mismatch.h
+-rw-r--r--  2.0 unx     2479 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/mismatch.inl
+-rw-r--r--  2.0 unx     5622 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/partition.h
+-rw-r--r--  2.0 unx     8845 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/partition.inl
+-rw-r--r--  2.0 unx     1181 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/per_device_resource.h
+-rw-r--r--  2.0 unx     1712 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce.h
+-rw-r--r--  2.0 unx     2374 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce.inl
+-rw-r--r--  2.0 unx     2862 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce_by_key.h
+-rw-r--r--  2.0 unx     7101 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/reduce_by_key.inl
+-rw-r--r--  2.0 unx     3501 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/remove.h
+-rw-r--r--  2.0 unx     4852 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/remove.inl
+-rw-r--r--  2.0 unx     3478 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/replace.h
+-rw-r--r--  2.0 unx     5734 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/replace.inl
+-rw-r--r--  2.0 unx     1566 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/reverse.h
+-rw-r--r--  2.0 unx     2340 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/reverse.inl
+-rw-r--r--  2.0 unx     3226 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan.h
+-rw-r--r--  2.0 unx     4151 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan.inl
+-rw-r--r--  2.0 unx     5309 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan_by_key.h
+-rw-r--r--  2.0 unx     9479 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scan_by_key.inl
+-rw-r--r--  2.0 unx     2330 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scatter.h
+-rw-r--r--  2.0 unx     3165 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scatter.inl
+-rw-r--r--  2.0 unx     4713 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/select_system.h
+-rw-r--r--  2.0 unx     6033 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/select_system.inl
+-rw-r--r--  2.0 unx     4985 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/select_system_exists.h
+-rw-r--r--  2.0 unx     1723 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/sequence.h
+-rw-r--r--  2.0 unx     2718 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/sequence.inl
+-rw-r--r--  2.0 unx    15559 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/set_operations.h
+-rw-r--r--  2.0 unx    22743 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/set_operations.inl
+-rw-r--r--  2.0 unx     1624 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/shuffle.h
+-rw-r--r--  2.0 unx     6848 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/shuffle.inl
+-rw-r--r--  2.0 unx     5028 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/sort.h
+-rw-r--r--  2.0 unx     7399 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/sort.inl
+-rw-r--r--  2.0 unx     1326 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/swap_ranges.h
+-rw-r--r--  2.0 unx     2397 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/swap_ranges.inl
+-rw-r--r--  2.0 unx     1258 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/tabulate.h
+-rw-r--r--  2.0 unx     2056 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/tabulate.inl
+-rw-r--r--  2.0 unx     1153 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/tag.h
+-rw-r--r--  2.0 unx     1704 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/temporary_buffer.h
+-rw-r--r--  2.0 unx     2948 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/temporary_buffer.inl
+-rw-r--r--  2.0 unx     3726 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform.h
+-rw-r--r--  2.0 unx     7211 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform.inl
+-rw-r--r--  2.0 unx     1487 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_reduce.h
+-rw-r--r--  2.0 unx     1775 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_reduce.inl
+-rw-r--r--  2.0 unx     2252 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_scan.h
+-rw-r--r--  2.0 unx     3503 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/transform_scan.inl
+-rw-r--r--  2.0 unx     1755 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_copy.h
+-rw-r--r--  2.0 unx     6897 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_copy.inl
+-rw-r--r--  2.0 unx     1661 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_fill.h
+-rw-r--r--  2.0 unx     4809 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/uninitialized_fill.inl
+-rw-r--r--  2.0 unx     2998 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique.h
+-rw-r--r--  2.0 unx     4641 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique.inl
+-rw-r--r--  2.0 unx     3078 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique_by_key.h
+-rw-r--r--  2.0 unx     5316 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/unique_by_key.inl
+-rw-r--r--  2.0 unx     2673 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scalar/binary_search.h
+-rw-r--r--  2.0 unx     4320 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/generic/scalar/binary_search.inl
+-rw-r--r--  2.0 unx     3136 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/internal/decompose.h
+-rw-r--r--  2.0 unx     1874 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/adjacent_difference.h
+-rw-r--r--  2.0 unx     1212 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/assign_value.h
+-rw-r--r--  2.0 unx     3770 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/binary_search.h
+-rw-r--r--  2.0 unx     1724 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy.h
+-rw-r--r--  2.0 unx     4621 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy.inl
+-rw-r--r--  2.0 unx     1297 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy_backward.h
+-rw-r--r--  2.0 unx     1825 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/copy_if.h
+-rw-r--r--  2.0 unx      714 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/count.h
+-rw-r--r--  2.0 unx      714 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/equal.h
+-rw-r--r--  2.0 unx     1770 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/execution_policy.h
+-rw-r--r--  2.0 unx     3273 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/extrema.h
+-rw-r--r--  2.0 unx      713 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/fill.h
+-rw-r--r--  2.0 unx     1621 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/find.h
+-rw-r--r--  2.0 unx     2259 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/for_each.h
+-rw-r--r--  2.0 unx      715 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/gather.h
+-rw-r--r--  2.0 unx     3852 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/general_copy.h
+-rw-r--r--  2.0 unx      717 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/generate.h
+-rw-r--r--  2.0 unx     1193 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/get_value.h
+-rw-r--r--  2.0 unx      722 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/inner_product.h
+-rw-r--r--  2.0 unx     3623 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/insertion_sort.h
+-rw-r--r--  2.0 unx     1259 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/iter_swap.h
+-rw-r--r--  2.0 unx      716 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/logical.h
+-rw-r--r--  2.0 unx     1355 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/malloc_and_free.h
+-rw-r--r--  2.0 unx     2389 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/merge.h
+-rw-r--r--  2.0 unx     3953 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/merge.inl
+-rw-r--r--  2.0 unx      717 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/mismatch.h
+-rw-r--r--  2.0 unx     8091 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/partition.h
+-rw-r--r--  2.0 unx      723 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/per_device_resource.h
+-rw-r--r--  2.0 unx     1759 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/reduce.h
+-rw-r--r--  2.0 unx     2853 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/reduce_by_key.h
+-rw-r--r--  2.0 unx     4498 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/remove.h
+-rw-r--r--  2.0 unx      716 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/replace.h
+-rw-r--r--  2.0 unx      716 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/reverse.h
+-rw-r--r--  2.0 unx     3296 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/scan.h
+-rw-r--r--  2.0 unx     4092 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/scan_by_key.h
+-rw-r--r--  2.0 unx      716 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/scatter.h
+-rw-r--r--  2.0 unx      717 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/sequence.h
+-rw-r--r--  2.0 unx     5906 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/set_operations.h
+-rw-r--r--  2.0 unx     1846 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/sort.h
+-rw-r--r--  2.0 unx     6653 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/sort.inl
+-rw-r--r--  2.0 unx     1845 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_merge_sort.h
+-rw-r--r--  2.0 unx    14742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_merge_sort.inl
+-rw-r--r--  2.0 unx     1700 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_primitive_sort.h
+-rw-r--r--  2.0 unx     5091 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_primitive_sort.inl
+-rw-r--r--  2.0 unx     1666 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_radix_sort.h
+-rw-r--r--  2.0 unx    17969 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/stable_radix_sort.inl
+-rw-r--r--  2.0 unx      720 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/swap_ranges.h
+-rw-r--r--  2.0 unx      717 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/tabulate.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/temporary_buffer.h
+-rw-r--r--  2.0 unx      718 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/transform.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/transform_reduce.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/transform_scan.h
+-rw-r--r--  2.0 unx     1498 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/trivial_copy.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/uninitialized_copy.h
+-rw-r--r--  2.0 unx      726 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/uninitialized_fill.h
+-rw-r--r--  2.0 unx     3243 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/unique.h
+-rw-r--r--  2.0 unx     3402 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/detail/sequential/unique_by_key.h
+-rw-r--r--  2.0 unx     5095 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/execution_policy.h
+-rw-r--r--  2.0 unx     3396 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/memory.h
+-rw-r--r--  2.0 unx     1967 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/memory_resource.h
+-rw-r--r--  2.0 unx     3783 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/pointer.h
+-rw-r--r--  2.0 unx     3161 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/vector.h
+-rw-r--r--  2.0 unx     1586 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/adjacent_difference.h
+-rw-r--r--  2.0 unx      756 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/assign_value.h
+-rw-r--r--  2.0 unx     2463 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/binary_search.h
+-rw-r--r--  2.0 unx     1536 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy.h
+-rw-r--r--  2.0 unx     4299 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy.inl
+-rw-r--r--  2.0 unx     1379 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy_if.h
+-rw-r--r--  2.0 unx     1534 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/copy_if.inl
+-rw-r--r--  2.0 unx      742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/count.h
+-rw-r--r--  2.0 unx     1210 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/default_decomposition.h
+-rw-r--r--  2.0 unx     2069 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/default_decomposition.inl
+-rw-r--r--  2.0 unx      742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/equal.h
+-rw-r--r--  2.0 unx     2921 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/execution_policy.h
+-rw-r--r--  2.0 unx     2469 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/extrema.h
+-rw-r--r--  2.0 unx      740 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/fill.h
+-rw-r--r--  2.0 unx     1406 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/find.h
+-rw-r--r--  2.0 unx     1806 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/for_each.h
+-rw-r--r--  2.0 unx     3055 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/for_each.inl
+-rw-r--r--  2.0 unx      744 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/gather.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/generate.h
+-rw-r--r--  2.0 unx      750 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/get_value.h
+-rw-r--r--  2.0 unx      758 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/inner_product.h
+-rw-r--r--  2.0 unx      750 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/iter_swap.h
+-rw-r--r--  2.0 unx      746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/logical.h
+-rw-r--r--  2.0 unx      762 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/malloc_and_free.h
+-rw-r--r--  2.0 unx     2423 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/memory.inl
+-rw-r--r--  2.0 unx      742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/merge.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/mismatch.h
+-rw-r--r--  2.0 unx     1330 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/par.h
+-rw-r--r--  2.0 unx     2951 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/partition.h
+-rw-r--r--  2.0 unx     3751 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/partition.inl
+-rw-r--r--  2.0 unx      723 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/per_device_resource.h
+-rw-r--r--  2.0 unx     2798 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/pragma_omp.h
+-rw-r--r--  2.0 unx     1383 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce.h
+-rw-r--r--  2.0 unx     2466 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce.inl
+-rw-r--r--  2.0 unx     1712 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_by_key.h
+-rw-r--r--  2.0 unx     1867 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_by_key.inl
+-rw-r--r--  2.0 unx     1471 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_intervals.h
+-rw-r--r--  2.0 unx     2901 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/reduce_intervals.inl
+-rw-r--r--  2.0 unx     2568 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/remove.h
+-rw-r--r--  2.0 unx     3161 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/remove.inl
+-rw-r--r--  2.0 unx      753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/replace.h
+-rw-r--r--  2.0 unx      746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/reverse.h
+-rw-r--r--  2.0 unx      740 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/scan.h
+-rw-r--r--  2.0 unx      757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/scan_by_key.h
+-rw-r--r--  2.0 unx      753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/scatter.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/sequence.h
+-rw-r--r--  2.0 unx      760 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/set_operations.h
+-rw-r--r--  2.0 unx     1689 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/sort.h
+-rw-r--r--  2.0 unx     8864 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/sort.inl
+-rw-r--r--  2.0 unx      746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/swap_ranges.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/tabulate.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/temporary_buffer.h
+-rw-r--r--  2.0 unx      742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/transform.h
+-rw-r--r--  2.0 unx      764 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/transform_reduce.h
+-rw-r--r--  2.0 unx      760 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/transform_scan.h
+-rw-r--r--  2.0 unx      768 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/uninitialized_copy.h
+-rw-r--r--  2.0 unx      768 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/uninitialized_fill.h
+-rw-r--r--  2.0 unx     2062 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique.h
+-rw-r--r--  2.0 unx     2542 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique.inl
+-rw-r--r--  2.0 unx     2048 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique_by_key.h
+-rw-r--r--  2.0 unx     2485 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/omp/detail/unique_by_key.inl
+-rw-r--r--  2.0 unx     5071 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/execution_policy.h
+-rw-r--r--  2.0 unx     3394 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/memory.h
+-rw-r--r--  2.0 unx     1978 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/memory_resource.h
+-rw-r--r--  2.0 unx     3780 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/pointer.h
+-rw-r--r--  2.0 unx     3157 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/vector.h
+-rw-r--r--  2.0 unx     1586 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/adjacent_difference.h
+-rw-r--r--  2.0 unx      756 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/assign_value.h
+-rw-r--r--  2.0 unx      758 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/binary_search.h
+-rw-r--r--  2.0 unx     1536 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy.h
+-rw-r--r--  2.0 unx     4322 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy.inl
+-rw-r--r--  2.0 unx     1312 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy_if.h
+-rw-r--r--  2.0 unx     3295 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/copy_if.inl
+-rw-r--r--  2.0 unx      742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/count.h
+-rw-r--r--  2.0 unx      742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/equal.h
+-rw-r--r--  2.0 unx     2144 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/execution_policy.h
+-rw-r--r--  2.0 unx     2469 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/extrema.h
+-rw-r--r--  2.0 unx      740 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/fill.h
+-rw-r--r--  2.0 unx     1337 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/find.h
+-rw-r--r--  2.0 unx     1654 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/for_each.h
+-rw-r--r--  2.0 unx     2946 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/for_each.inl
+-rw-r--r--  2.0 unx      744 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/gather.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/generate.h
+-rw-r--r--  2.0 unx      750 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/get_value.h
+-rw-r--r--  2.0 unx      758 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/inner_product.h
+-rw-r--r--  2.0 unx      750 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/iter_swap.h
+-rw-r--r--  2.0 unx      746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/logical.h
+-rw-r--r--  2.0 unx      762 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/malloc_and_free.h
+-rw-r--r--  2.0 unx     2424 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/memory.inl
+-rw-r--r--  2.0 unx     2198 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/merge.h
+-rw-r--r--  2.0 unx     9380 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/merge.inl
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/mismatch.h
+-rw-r--r--  2.0 unx     1330 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/par.h
+-rw-r--r--  2.0 unx     2872 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/partition.h
+-rw-r--r--  2.0 unx     3670 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/partition.inl
+-rw-r--r--  2.0 unx      723 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/per_device_resource.h
+-rw-r--r--  2.0 unx     1368 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce.h
+-rw-r--r--  2.0 unx     3470 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce.inl
+-rw-r--r--  2.0 unx     1650 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce_by_key.h
+-rw-r--r--  2.0 unx    14239 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce_by_key.inl
+-rw-r--r--  2.0 unx     4287 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reduce_intervals.h
+-rw-r--r--  2.0 unx     2584 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/remove.h
+-rw-r--r--  2.0 unx     3161 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/remove.inl
+-rw-r--r--  2.0 unx      753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/replace.h
+-rw-r--r--  2.0 unx      746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/reverse.h
+-rw-r--r--  2.0 unx     1795 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scan.h
+-rw-r--r--  2.0 unx     7066 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scan.inl
+-rw-r--r--  2.0 unx      754 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scan_by_key.h
+-rw-r--r--  2.0 unx      753 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/scatter.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/sequence.h
+-rw-r--r--  2.0 unx      760 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/set_operations.h
+-rw-r--r--  2.0 unx     1703 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/sort.h
+-rw-r--r--  2.0 unx     8169 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/sort.inl
+-rw-r--r--  2.0 unx      746 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/swap_ranges.h
+-rw-r--r--  2.0 unx      748 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/tabulate.h
+-rw-r--r--  2.0 unx      725 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/temporary_buffer.h
+-rw-r--r--  2.0 unx      742 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/transform.h
+-rw-r--r--  2.0 unx      764 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/transform_reduce.h
+-rw-r--r--  2.0 unx      760 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/transform_scan.h
+-rw-r--r--  2.0 unx      768 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/uninitialized_copy.h
+-rw-r--r--  2.0 unx      768 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/uninitialized_fill.h
+-rw-r--r--  2.0 unx     2070 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique.h
+-rw-r--r--  2.0 unx     2542 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique.inl
+-rw-r--r--  2.0 unx     2048 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique_by_key.h
+-rw-r--r--  2.0 unx     2485 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/system/tbb/detail/unique_by_key.inl
+-rw-r--r--  2.0 unx    10578 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/integer_sequence.h
+-rw-r--r--  2.0 unx     8482 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/is_contiguous_iterator.h
+-rw-r--r--  2.0 unx     1702 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/is_execution_policy.h
+-rw-r--r--  2.0 unx     6372 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/is_operator_less_or_greater_function_object.h
+-rw-r--r--  2.0 unx     3064 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/is_operator_plus_function_object.h
+-rw-r--r--  2.0 unx    12644 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/is_trivially_relocatable.h
+-rw-r--r--  2.0 unx     7888 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/logical_metafunctions.h
+-rw-r--r--  2.0 unx     3187 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/remove_cvref.h
+-rw-r--r--  2.0 unx     1458 b- defN 23-May-01 02:46 nvidia/cuda_cccl/include/thrust/type_traits/void_t.h
+-rw-r--r--  2.0 unx        0 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/__init__.py
+-rw-r--r--  2.0 unx     1363 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/cub/cub-config-version.cmake
+-rw-r--r--  2.0 unx     4689 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/cub/cub-config.cmake
+-rw-r--r--  2.0 unx      744 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/cub/cub-header-search.cmake
+-rw-r--r--  2.0 unx     1163 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config-version.cmake
+-rw-r--r--  2.0 unx     2612 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config.cmake
+-rw-r--r--  2.0 unx      503 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-header-search.cmake
+-rw-r--r--  2.0 unx    16707 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/thrust/FindTBB.cmake
+-rw-r--r--  2.0 unx     8459 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/thrust/README.md
+-rw-r--r--  2.0 unx     1437 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/thrust/thrust-config-version.cmake
+-rw-r--r--  2.0 unx    29918 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/thrust/thrust-config.cmake
+-rw-r--r--  2.0 unx      757 b- defN 23-May-01 02:46 nvidia/cuda_cccl/lib/cmake/thrust/thrust-header-search.cmake
+-rw-r--r--  2.0 unx    59262 b- defN 23-May-01 02:46 nvidia_cuda_cccl_cu12-12.2.53.dist-info/License.txt
+-rw-r--r--  2.0 unx     1485 b- defN 23-May-01 02:46 nvidia_cuda_cccl_cu12-12.2.53.dist-info/METADATA
+-rw-r--r--  2.0 unx      106 b- defN 23-May-01 02:46 nvidia_cuda_cccl_cu12-12.2.53.dist-info/WHEEL
+-rw-r--r--  2.0 unx        7 b- defN 23-May-01 02:46 nvidia_cuda_cccl_cu12-12.2.53.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx   156707 b- defN 23-May-01 02:46 nvidia_cuda_cccl_cu12-12.2.53.dist-info/RECORD
+1279 files, 9399162 bytes uncompressed, 1950604 bytes compressed:  79.2%
```

## zipnote {}

```diff
@@ -1,16 +1,13 @@
 Filename: nvidia/__init__.py
 Comment: 
 
 Filename: nvidia/cuda_cccl/__init__.py
 Comment: 
 
-Filename: nvidia/cuda_cccl/bin/__init__.py
-Comment: 
-
 Filename: nvidia/cuda_cccl/include/__init__.py
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/config.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/cub.cuh
@@ -54,14 +51,17 @@
 
 Filename: nvidia/cuda_cccl/include/cub/version.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/agent/agent_adjacent_difference.cuh
 Comment: 
 
+Filename: nvidia/cuda_cccl/include/cub/agent/agent_batch_memcpy.cuh
+Comment: 
+
 Filename: nvidia/cuda_cccl/include/cub/agent/agent_histogram.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/agent/agent_merge_sort.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_downsweep.cuh
@@ -195,14 +195,20 @@
 
 Filename: nvidia/cuda_cccl/include/cub/detail/device_synchronize.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/detail/exec_check_disable.cuh
 Comment: 
 
+Filename: nvidia/cuda_cccl/include/cub/detail/strong_load.cuh
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cub/detail/strong_store.cuh
+Comment: 
+
 Filename: nvidia/cuda_cccl/include/cub/detail/temporary_storage.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/detail/type_traits.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/detail/uninitialized_copy.cuh
@@ -210,14 +216,17 @@
 
 Filename: nvidia/cuda_cccl/include/cub/device/device_adjacent_difference.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/device/device_histogram.cuh
 Comment: 
 
+Filename: nvidia/cuda_cccl/include/cub/device/device_memcpy.cuh
+Comment: 
+
 Filename: nvidia/cuda_cccl/include/cub/device/device_merge_sort.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/device/device_partition.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/device/device_radix_sort.cuh
@@ -246,14 +255,17 @@
 
 Filename: nvidia/cuda_cccl/include/cub/device/device_spmv.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_adjacent_difference.cuh
 Comment: 
 
+Filename: nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_batch_memcpy.cuh
+Comment: 
+
 Filename: nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_histogram.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_merge_sort.cuh
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_radix_sort.cuh
@@ -441,14 +453,809 @@
 
 Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wchar.h
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wctype.h
 Comment: 
 
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__algorithm/swap_ranges.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/_One_of.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/__concept_macros.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/arithmetic.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/boolean_testable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/class_or_enum.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/common_reference_with.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/common_with.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/convertible_to.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/copyable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/derived_from.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/destructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/different_from.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/equality_comparable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/invocable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/movable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/predicate.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/regular.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/relation.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/same_as.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/semiregular.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/swappable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/totally_ordered.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/atomic.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/atomic_prelude.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/barrier.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/chrono.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/climits_prelude.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/cstddef_prelude.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/cstdint_prelude.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/latch.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/semaphore.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binary_function.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binary_negate.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind_back.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind_front.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binder1st.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binder2nd.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/compose.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/default_searcher.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/function.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/hash.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/identity.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/invoke.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/is_transparent.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/mem_fn.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/mem_fun_ref.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/not_fn.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/operations.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/perfect_forward.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/pointer_to_binary_function.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/pointer_to_unary_function.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/reference_wrapper.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unary_function.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unary_negate.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unwrap_ref.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/weak_result_type.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/array.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/get.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/hash.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/memory_resource.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/pair.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/span.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/string.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/string_view.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/tuple.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/access.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/advance.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/back_insert_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/data.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/distance.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/empty.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/erase_if_container.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/front_insert_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/insert_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/istream_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/istreambuf_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/iterator_traits.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/move_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/next.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/ostream_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/ostreambuf_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/prev.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/reverse_access.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/reverse_iterator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/size.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/wrap_iter.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/compressed_pair.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/config.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/default_accessor.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/dynamic_extent.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/extents.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/full_extent_t.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_left.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_right.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_stride.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/macros.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/maybe_static_value.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/mdspan.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/no_unique_address.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/standard_layout_static_array.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/static_array.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/submdspan.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/type_list.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/addressof.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/construct_at.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/pointer_traits.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/voidify.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/apply_cv.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/make_tuple_types.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/sfinae_helpers.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/structured_bindings.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_element.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_indices.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_like.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_size.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_types.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_const.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_cv.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_lvalue_reference.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_pointer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_rvalue_reference.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_volatile.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/aligned_storage.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/aligned_union.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/alignment_of.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/apply_cv.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/can_extract_key.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/common_reference.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/common_type.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/conditional.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/conjunction.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/copy_cv.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/copy_cvref.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/decay.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/dependent_type.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/disjunction.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/enable_if.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/extent.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/has_unique_object_representation.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/has_virtual_destructor.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/integral_constant.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_abstract.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_aggregate.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_allocator.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_arithmetic.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_array.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_base_of.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_bounded_array.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_callable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_char_like_type.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_class.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_compound.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_const.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_constant_evaluated.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_convertible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_copy_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_copy_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_core_convertible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_default_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_destructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_empty.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_enum.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_final.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_floating_point.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_function.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_fundamental.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_implicitly_default_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_integral.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_literal_type.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_function_pointer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_object_pointer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_pointer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_move_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_move_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_convertible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_copy_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_copy_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_default_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_destructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_move_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_move_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_null_pointer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_object.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_pod.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_pointer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_polymorphic.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_primary_template.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_reference.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_reference_wrapper.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_referenceable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_same.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_scalar.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_scoped_enum.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_signed.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_signed_integer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_standard_layout.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_swappable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivial.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copy_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copy_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copyable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_default_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_destructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_move_assignable.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_move_constructible.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unbounded_array.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_union.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unsigned.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unsigned_integer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_valid_expansion.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_void.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_volatile.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/lazy.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_32_64_or_128_bit.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_const_lvalue_ref.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_signed.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_unsigned.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/maybe_const.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/nat.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/negation.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/promote.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/rank.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_all_extents.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_const.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_const_ref.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_cv.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_cvref.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_extent.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_pointer.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_reference.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_volatile.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/result_of.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/type_identity.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/type_list.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/underlying_type.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/void_t.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/as_const.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/auto_cast.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/cmp.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/convert_to_integral.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/declval.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/exchange.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/forward.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/forward_like.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/in_place.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/integer_sequence.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/move.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/pair.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/piecewise_construct.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/priority_tag.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/rel_ops.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/swap.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/to_underlying.h
+Comment: 
+
+Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/unreachable.h
+Comment: 
+
 Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/android/locale_bionic.h
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_base.h
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_c11.h
@@ -2973,14 +3780,17 @@
 
 Filename: nvidia/cuda_cccl/include/thrust/type_traits/remove_cvref.h
 Comment: 
 
 Filename: nvidia/cuda_cccl/include/thrust/type_traits/void_t.h
 Comment: 
 
+Filename: nvidia/cuda_cccl/lib/__init__.py
+Comment: 
+
 Filename: nvidia/cuda_cccl/lib/cmake/cub/cub-config-version.cmake
 Comment: 
 
 Filename: nvidia/cuda_cccl/lib/cmake/cub/cub-config.cmake
 Comment: 
 
 Filename: nvidia/cuda_cccl/lib/cmake/cub/cub-header-search.cmake
@@ -3006,23 +3816,23 @@
 
 Filename: nvidia/cuda_cccl/lib/cmake/thrust/thrust-config.cmake
 Comment: 
 
 Filename: nvidia/cuda_cccl/lib/cmake/thrust/thrust-header-search.cmake
 Comment: 
 
-Filename: nvidia_cuda_cccl_cu12-12.1.55.dist-info/License.txt
+Filename: nvidia_cuda_cccl_cu12-12.2.53.dist-info/License.txt
 Comment: 
 
-Filename: nvidia_cuda_cccl_cu12-12.1.55.dist-info/METADATA
+Filename: nvidia_cuda_cccl_cu12-12.2.53.dist-info/METADATA
 Comment: 
 
-Filename: nvidia_cuda_cccl_cu12-12.1.55.dist-info/WHEEL
+Filename: nvidia_cuda_cccl_cu12-12.2.53.dist-info/WHEEL
 Comment: 
 
-Filename: nvidia_cuda_cccl_cu12-12.1.55.dist-info/top_level.txt
+Filename: nvidia_cuda_cccl_cu12-12.2.53.dist-info/top_level.txt
 Comment: 
 
-Filename: nvidia_cuda_cccl_cu12-12.1.55.dist-info/RECORD
+Filename: nvidia_cuda_cccl_cu12-12.2.53.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## nvidia/cuda_cccl/include/cub/cub.cuh

```diff
@@ -1,22 +1,22 @@
 /******************************************************************************
  * Copyright (c) 2011, Duane Merrill.  All rights reserved.
  * Copyright (c) 2011-2018, NVIDIA CORPORATION.  All rights reserved.
- * 
+ *
  * Redistribution and use in source and binary forms, with or without
  * modification, are permitted provided that the following conditions are met:
  *     * Redistributions of source code must retain the above copyright
  *       notice, this list of conditions and the following disclaimer.
  *     * Redistributions in binary form must reproduce the above copyright
  *       notice, this list of conditions and the following disclaimer in the
  *       documentation and/or other materials provided with the distribution.
  *     * Neither the name of the NVIDIA CORPORATION nor the
  *       names of its contributors may be used to endorse or promote products
  *       derived from this software without specific prior written permission.
- * 
+ *
  * THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
  * ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
  * WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
  * DISCLAIMED. IN NO EVENT SHALL NVIDIA CORPORATION BE LIABLE FOR ANY
  * DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
  * (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
  * LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
@@ -33,41 +33,42 @@
 
 #pragma once
 
 // Static configuration
 #include "config.cuh"
 
 // Block
-#include "block/block_histogram.cuh"
 #include "block/block_adjacent_difference.cuh"
 #include "block/block_discontinuity.cuh"
 #include "block/block_exchange.cuh"
+#include "block/block_histogram.cuh"
 #include "block/block_load.cuh"
+#include "block/block_merge_sort.cuh"
 #include "block/block_radix_rank.cuh"
 #include "block/block_radix_sort.cuh"
-#include "block/block_merge_sort.cuh"
 #include "block/block_reduce.cuh"
 #include "block/block_scan.cuh"
 #include "block/block_store.cuh"
 //#include "block/block_shift.cuh"
 
 // Device
-#include "device/device_merge_sort.cuh"
+#include "device/device_adjacent_difference.cuh"
 #include "device/device_histogram.cuh"
+#include "device/device_memcpy.cuh"
+#include "device/device_merge_sort.cuh"
 #include "device/device_partition.cuh"
 #include "device/device_radix_sort.cuh"
 #include "device/device_reduce.cuh"
 #include "device/device_run_length_encode.cuh"
 #include "device/device_scan.cuh"
-#include "device/device_segmented_sort.cuh"
 #include "device/device_segmented_radix_sort.cuh"
 #include "device/device_segmented_reduce.cuh"
+#include "device/device_segmented_sort.cuh"
 #include "device/device_select.cuh"
 #include "device/device_spmv.cuh"
-#include "device/device_adjacent_difference.cuh"
 
 // Grid
 //#include "grid/grid_barrier.cuh"
 #include "grid/grid_even_share.cuh"
 #include "grid/grid_mapping.cuh"
 #include "grid/grid_queue.cuh"
 
@@ -101,8 +102,7 @@
 #include "util_allocator.cuh"
 #include "util_arch.cuh"
 #include "util_debug.cuh"
 #include "util_device.cuh"
 #include "util_macro.cuh"
 #include "util_ptx.cuh"
 #include "util_type.cuh"
-
```

## nvidia/cuda_cccl/include/cub/util_arch.cuh

```diff
@@ -40,19 +40,16 @@
 // Legacy include; this functionality used to be defined in here.
 #include <cub/detail/detect_cuda_runtime.cuh>
 
 CUB_NAMESPACE_BEGIN
 
 #ifndef DOXYGEN_SHOULD_SKIP_THIS    // Do not document
 
-#if ((__CUDACC_VER_MAJOR__ >= 9) || defined(_NVHPC_CUDA) ||            \
-     CUDA_VERSION >= 9000) &&                                                  \
-  !defined(CUB_USE_COOPERATIVE_GROUPS)
+// \deprecated [Since 2.1.0] 
 #define CUB_USE_COOPERATIVE_GROUPS
-#endif
 
 /// In device code, CUB_PTX_ARCH expands to the PTX version for which we are
 /// compiling. In host code, CUB_PTX_ARCH's value is implementation defined.
 #ifndef CUB_PTX_ARCH
     #if defined(_NVHPC_CUDA)
         // __NVCOMPILER_CUDA_ARCH__ is the target PTX version, and is defined
         // when compiling both host code and device code. Currently, only one
```

## nvidia/cuda_cccl/include/cub/util_device.cuh

```diff
@@ -29,14 +29,16 @@
 /**
  * \file
  * Properties of a given CUDA device and the corresponding PTX bundle
  */
 
 #pragma once
 
+#include <cuda/std/utility>
+
 #include <cub/detail/device_synchronize.cuh>
 #include <cub/util_arch.cuh>
 #include <cub/util_cpp_dialect.cuh>
 #include <cub/util_debug.cuh>
 #include <cub/util_macro.cuh>
 #include <cub/util_namespace.cuh>
 #include <cub/util_type.cuh>
@@ -278,15 +280,15 @@
             {
                 // We successfully set the state to `DeviceEntryInitializing`;
                 // we have the lock and it's our job to initialize this entry
                 // and then release it.
 
                 // We don't use `CubDebug` here because we let the user code
                 // decide whether or not errors are hard errors.
-                payload.error = std::forward<Invocable>(f)(payload.attribute);
+                payload.error = ::cuda::std::forward<Invocable>(f)(payload.attribute);
                 if (payload.error)
                     // Clear the global CUDA error state which may have been
                     // set by the last call. Otherwise, errors may "leak" to
                     // unrelated kernel launches.
                     cudaGetLastError();
 
                 // Release the lock by setting the state to `DeviceEntryReady`.
```

## nvidia/cuda_cccl/include/cub/util_macro.cuh

```diff
@@ -28,17 +28,17 @@
 
 /******************************************************************************
  * Common C/C++ macro utilities
  ******************************************************************************/
 
 #pragma once
 
-#include "util_namespace.cuh"
+#include <cuda/std/utility>
 
-#include <utility>
+#include "util_namespace.cuh"
 
 CUB_NAMESPACE_BEGIN
 
 
 /**
  * \addtogroup UtilModule
  * @{
@@ -55,25 +55,25 @@
 #endif
 
 #define CUB_PREVENT_MACRO_SUBSTITUTION
 
 template <typename T, typename U>
 constexpr __host__ __device__ auto min CUB_PREVENT_MACRO_SUBSTITUTION(T &&t,
                                                                       U &&u)
-  -> decltype(t < u ? std::forward<T>(t) : std::forward<U>(u))
+  -> decltype(t < u ? ::cuda::std::forward<T>(t) : ::cuda::std::forward<U>(u))
 {
-  return t < u ? std::forward<T>(t) : std::forward<U>(u);
+  return t < u ? ::cuda::std::forward<T>(t) : ::cuda::std::forward<U>(u);
 }
 
 template <typename T, typename U>
 constexpr __host__ __device__ auto max CUB_PREVENT_MACRO_SUBSTITUTION(T &&t,
                                                                       U &&u)
-  -> decltype(t < u ? std::forward<U>(u) : std::forward<T>(t))
+  -> decltype(t < u ? ::cuda::std::forward<U>(u) : ::cuda::std::forward<T>(t))
 {
-  return t < u ? std::forward<U>(u) : std::forward<T>(t);
+  return t < u ? ::cuda::std::forward<U>(u) : ::cuda::std::forward<T>(t);
 }
 
 #ifndef CUB_MAX
     /// Select maximum(a, b)
     #define CUB_MAX(a, b) (((b) > (a)) ? (b) : (a))
 #endif
```

## nvidia/cuda_cccl/include/cub/util_namespace.cuh

```diff
@@ -104,32 +104,105 @@
  * defined by users, in which case CUB_NS_PREFIX, CUB_NS_POSTFIX, and
  * CUB_NS_QUALIFIER must all be set consistently.
  */
 #ifndef CUB_NS_QUALIFIER
 #define CUB_NS_QUALIFIER ::cub
 #endif
 
+#if !defined(CUB_DETAIL_MAGIC_NS_NAME)
+#define CUB_DETAIL_COUNT_N(_1, _2, _3, _4, _5, _6, _7, _8, _9, _10, _11, _12, _13, \
+                           _14, _15, _16, _17, _18, _19, _20, N, ...)              \
+                           N
+#define CUB_DETAIL_COUNT(...)                                                      \
+  CUB_DETAIL_IDENTITY(CUB_DETAIL_COUNT_N(__VA_ARGS__, 20, 19, 18, 17, 16, 15, 14, 13, 12, \
+                                         11, 10, 9, 8, 7, 6, 5, 4, 3, 2, 1))
+#define CUB_DETAIL_IDENTITY(N) N
+#define CUB_DETAIL_APPLY(MACRO, ...) CUB_DETAIL_IDENTITY(MACRO(__VA_ARGS__))
+#define CUB_DETAIL_MAGIC_NS_NAME1(P1) \
+    CUB_##P1##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME2(P1, P2) \
+    CUB_##P1##_##P2##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME3(P1, P2, P3) \
+    CUB_##P1##_##P2##_##P3##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME4(P1, P2, P3, P4) \
+    CUB_##P1##_##P2##_##P3##_##P4##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME5(P1, P2, P3, P4, P5) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME6(P1, P2, P3, P4, P5, P6) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME7(P1, P2, P3, P4, P5, P6, P7) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME8(P1, P2, P3, P4, P5, P6, P7, P8) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME9(P1, P2, P3, P4, P5, P6, P7, P8, P9) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME10(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME11(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME12(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME13(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME14(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_##P14##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME15(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_##P14##_##P15##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME16(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_##P14##_##P15##_##P16##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME17(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_##P14##_##P15##_##P16##_##P17##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME18(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_##P14##_##P15##_##P16##_##P17##_##P18##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME19(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18, P19) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_##P14##_##P15##_##P16##_##P17##_##P18##_##P19##_NS
+#define CUB_DETAIL_MAGIC_NS_NAME20(P1, P2, P3, P4, P5, P6, P7, P8, P9, P10, P11, P12, P13, P14, P15, P16, P17, P18, P19, P20) \
+    CUB_##P1##_##P2##_##P3##_##P4##_##P5##_##P6##_##P7##_##P8##_##P9##_##P10##_##P11##_##P12##_##P13##_##P14##_##P15##_##P16##_##P17##_##P18##_##P19##_##P20##_NS
+#define CUB_DETAIL_DISPATCH(N) CUB_DETAIL_MAGIC_NS_NAME ## N
+#define CUB_DETAIL_MAGIC_NS_NAME(...) CUB_DETAIL_IDENTITY(CUB_DETAIL_APPLY(CUB_DETAIL_DISPATCH, CUB_DETAIL_COUNT(__VA_ARGS__))(__VA_ARGS__))
+#endif // !defined(CUB_DETAIL_MAGIC_NS_NAME)
+
+#if defined(CUB_DISABLE_NAMESPACE_MAGIC)
+#if !defined(CUB_WRAPPED_NAMESPACE)
+#if !defined(CUB_IGNORE_NAMESPACE_MAGIC_ERROR)
+#error "Disabling namespace magic is unsafe without wrapping namespace"
+#endif // !defined(CUB_IGNORE_NAMESPACE_MAGIC_ERROR)
+#endif // !defined(CUB_WRAPPED_NAMESPACE)
+#define CUB_DETAIL_MAGIC_NS_BEGIN
+#define CUB_DETAIL_MAGIC_NS_END
+#else // not defined(CUB_DISABLE_NAMESPACE_MAGIC)
+#if defined(_NVHPC_CUDA)
+#define CUB_DETAIL_MAGIC_NS_BEGIN inline namespace CUB_DETAIL_MAGIC_NS_NAME(CUB_VERSION, NV_TARGET_SM_INTEGER_LIST) {
+#define CUB_DETAIL_MAGIC_NS_END }
+#else // not defined(_NVHPC_CUDA)
+#define CUB_DETAIL_MAGIC_NS_BEGIN inline namespace CUB_DETAIL_MAGIC_NS_NAME(CUB_VERSION, __CUDA_ARCH_LIST__) {
+#define CUB_DETAIL_MAGIC_NS_END }
+#endif // not defined(_NVHPC_CUDA)
+#endif // not defined(CUB_DISABLE_NAMESPACE_MAGIC)
+
 /**
  * \def CUB_NAMESPACE_BEGIN
  * This macro is used to open a `cub::` namespace block, along with any
  * enclosing namespaces requested by CUB_WRAPPED_NAMESPACE, etc.
  * This macro is defined by CUB and may not be overridden.
  */
 #define CUB_NAMESPACE_BEGIN                                                 \
   CUB_NS_PREFIX                                                             \
   namespace cub                                                             \
-  {
+  {                                                                         \
+  CUB_DETAIL_MAGIC_NS_BEGIN                                                        
 
 /**
  * \def CUB_NAMESPACE_END
  * This macro is used to close a `cub::` namespace block, along with any
  * enclosing namespaces requested by CUB_WRAPPED_NAMESPACE, etc.
  * This macro is defined by CUB and may not be overridden.
  */
 #define CUB_NAMESPACE_END                                                   \
+  CUB_DETAIL_MAGIC_NS_END                                                   \
   } /* end namespace cub */                                                 \
   CUB_NS_POSTFIX
 
 // Declare these namespaces here for the purpose of Doxygenating them
 CUB_NS_PREFIX
 
 /*! \namespace cub
```

## nvidia/cuda_cccl/include/cub/util_ptx.cuh

```diff
@@ -73,14 +73,39 @@
 #endif // DOXYGEN_SHOULD_SKIP_THIS
 
 
 /******************************************************************************
  * Inlined PTX intrinsics
  ******************************************************************************/
 
+namespace detail
+{
+/**
+ * @brief Shifts @p val left by the amount specified by unsigned 32-bit value in @p num_bits. If @p
+ * num_bits is larger than 32 bits, @p num_bits is clamped to 32.
+ */
+__device__ __forceinline__ uint32_t LogicShiftLeft(uint32_t val, uint32_t num_bits)
+{
+  uint32_t ret{};
+  asm("shl.b32 %0, %1, %2;" : "=r"(ret) : "r"(val), "r"(num_bits));
+  return ret;
+}
+
+/**
+ * @brief Shifts @p val right by the amount specified by unsigned 32-bit value in @p num_bits. If @p
+ * num_bits is larger than 32 bits, @p num_bits is clamped to 32.
+ */
+__device__ __forceinline__ uint32_t LogicShiftRight(uint32_t val, uint32_t num_bits)
+{
+  uint32_t ret{};
+  asm("shr.b32 %0, %1, %2;" : "=r"(ret) : "r"(val), "r"(num_bits));
+  return ret;
+}
+} // namespace detail
+
 /**
  * \brief Shift-right then add.  Returns (\p x >> \p shift) + \p addend.
  */
 __device__ __forceinline__ unsigned int SHR_ADD(
     unsigned int x,
     unsigned int shift,
     unsigned int addend)
@@ -134,14 +159,30 @@
     unsigned int            num_bits,
     Int2Type<8>             /*byte_len*/)
 {
     const unsigned long long MASK = (1ull << num_bits) - 1;
     return (source >> bit_start) & MASK;
 }
 
+#if CUB_IS_INT128_ENABLED 
+/**
+ * Bitfield-extract for 128-bit types.
+ */
+template <typename UnsignedBits>
+__device__ __forceinline__ unsigned int BFE(
+    UnsignedBits            source,
+    unsigned int            bit_start,
+    unsigned int            num_bits,
+    Int2Type<16>            /*byte_len*/)
+{
+    const __uint128_t MASK = (__uint128_t{1} << num_bits) - 1;
+    return (source >> bit_start) & MASK;
+}
+#endif
+
 #endif // DOXYGEN_SHOULD_SKIP_THIS
 
 /**
  * \brief Bitfield-extract.  Extracts \p num_bits from \p source starting at bit-offset \p bit_start.  The input \p source may be an 8b, 16b, 32b, or 64b unsigned integer type.
  */
 template <typename UnsignedBits>
 __device__ __forceinline__ unsigned int BFE(
@@ -249,118 +290,85 @@
 
 
 /**
  * Warp barrier
  */
 __device__  __forceinline__ void WARP_SYNC(unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
     __syncwarp(member_mask);
-#endif
 }
 
 
 /**
  * Warp any
  */
 __device__  __forceinline__ int WARP_ANY(int predicate, unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
     return __any_sync(member_mask, predicate);
-#else
-    return ::__any(predicate);
-#endif
 }
 
 
 /**
  * Warp any
  */
 __device__  __forceinline__ int WARP_ALL(int predicate, unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
     return __all_sync(member_mask, predicate);
-#else
-    return ::__all(predicate);
-#endif
 }
 
 
 /**
  * Warp ballot
  */
 __device__  __forceinline__ int WARP_BALLOT(int predicate, unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
     return __ballot_sync(member_mask, predicate);
-#else
-    return __ballot(predicate);
-#endif
 }
 
 
 /**
  * Warp synchronous shfl_up
  */
 __device__ __forceinline__ 
 unsigned int SHFL_UP_SYNC(unsigned int word, int src_offset, int flags, unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
     asm volatile("shfl.sync.up.b32 %0, %1, %2, %3, %4;"
         : "=r"(word) : "r"(word), "r"(src_offset), "r"(flags), "r"(member_mask));
-#else
-    asm volatile("shfl.up.b32 %0, %1, %2, %3;"
-        : "=r"(word) : "r"(word), "r"(src_offset), "r"(flags));
-#endif
     return word;
 }
 
 /**
  * Warp synchronous shfl_down
  */
 __device__ __forceinline__ 
 unsigned int SHFL_DOWN_SYNC(unsigned int word, int src_offset, int flags, unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
     asm volatile("shfl.sync.down.b32 %0, %1, %2, %3, %4;"
         : "=r"(word) : "r"(word), "r"(src_offset), "r"(flags), "r"(member_mask));
-#else
-    asm volatile("shfl.down.b32 %0, %1, %2, %3;"
-        : "=r"(word) : "r"(word), "r"(src_offset), "r"(flags));
-#endif
     return word;
 }
 
 /**
  * Warp synchronous shfl_idx
  */
 __device__ __forceinline__ 
 unsigned int SHFL_IDX_SYNC(unsigned int word, int src_lane, int flags, unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
     asm volatile("shfl.sync.idx.b32 %0, %1, %2, %3, %4;"
         : "=r"(word) : "r"(word), "r"(src_lane), "r"(flags), "r"(member_mask));
-#else
-    asm volatile("shfl.idx.b32 %0, %1, %2, %3;"
-        : "=r"(word) : "r"(word), "r"(src_lane), "r"(flags));
-#endif
     return word;
 }
 
 /**
  * Warp synchronous shfl_idx
  */
 __device__ __forceinline__ 
 unsigned int SHFL_IDX_SYNC(unsigned int word, int src_lane, unsigned int member_mask)
 {
-#ifdef CUB_USE_COOPERATIVE_GROUPS
-  return __shfl_sync(member_mask, word, src_lane);
-#else
-  return __shfl(word, src_lane);
-#endif
+    return __shfl_sync(member_mask, word, src_lane);
 }
 
 /**
  * Floating point multiply. (Mantissa LSB rounds towards zero.)
  */
 __device__ __forceinline__ float FMUL_RZ(float a, float b)
 {
@@ -715,51 +723,82 @@
         output_alias[WORD] = shuffle_word;
     }
 
     return output;
 }
 
 
+namespace detail 
+{
 
-/**
- * Compute a 32b mask of threads having the same least-significant
- * LABEL_BITS of \p label as the calling thread.
+/** 
+ * Implementation detail for `MatchAny`. It provides specializations for full and partial warps. 
+ * For partial warps, inactive threads must be masked out. This is done in the partial warp 
+ * specialization below. 
+ * Usage:
+ * ```
+ * // returns a mask of threads with the same 4 least-significant bits of `label` 
+ * // in a warp with 16 active threads
+ * warp_matcher_t<4, 16>::match_any(label); 
+ *
+ * // returns a mask of threads with the same 4 least-significant bits of `label` 
+ * // in a warp with 32 active threads (no extra work is done)
+ * warp_matcher_t<4, 32>::match_any(label); 
+ * ```
  */
+template <int LABEL_BITS, int WARP_ACTIVE_THREADS>
+struct warp_matcher_t 
+{
+
+  static __device__ unsigned int match_any(unsigned int label)
+  {
+    return warp_matcher_t<LABEL_BITS, 32>::match_any(label) & ~(~0 << WARP_ACTIVE_THREADS);
+  }
+
+};
+
 template <int LABEL_BITS>
-inline __device__ unsigned int MatchAny(unsigned int label)
+struct warp_matcher_t<LABEL_BITS, CUB_PTX_WARP_THREADS> 
 {
-    unsigned int retval;
 
-    // Extract masks of common threads for each bit
-    #pragma unroll
-    for (int BIT = 0; BIT < LABEL_BITS; ++BIT)
-    {
-        unsigned int mask;
-        unsigned int current_bit = 1 << BIT;
-        asm ("{\n"
-            "    .reg .pred p;\n"
-            "    and.b32 %0, %1, %2;"
-            "    setp.eq.u32 p, %0, %2;\n"
-#ifdef CUB_USE_COOPERATIVE_GROUPS
-            "    vote.ballot.sync.b32 %0, p, 0xffffffff;\n"
-#else
-            "    vote.ballot.b32 %0, p;\n"
-#endif
-            "    @!p not.b32 %0, %0;\n"
-            "}\n" : "=r"(mask) : "r"(label), "r"(current_bit));
+  // match.any.sync.b32 is slower when matching a few bits
+  // using a ballot loop instead
+  static __device__ unsigned int match_any(unsigned int label)
+  {
+      unsigned int retval;
 
-        // Remove peers who differ
-        retval = (BIT == 0) ? mask : retval & mask;
-    }
+      // Extract masks of common threads for each bit
+      #pragma unroll
+      for (int BIT = 0; BIT < LABEL_BITS; ++BIT)
+      {
+          unsigned int mask;
+          unsigned int current_bit = 1 << BIT;
+          asm ("{\n"
+              "    .reg .pred p;\n"
+              "    and.b32 %0, %1, %2;"
+              "    setp.eq.u32 p, %0, %2;\n"
+              "    vote.ballot.sync.b32 %0, p, 0xffffffff;\n"
+              "    @!p not.b32 %0, %0;\n"
+              "}\n" : "=r"(mask) : "r"(label), "r"(current_bit));
+
+          // Remove peers who differ
+          retval = (BIT == 0) ? mask : retval & mask;
+      }
+
+      return retval;
+  }
 
-    return retval;
+};
 
-//  // VOLTA match
-//    unsigned int retval;
-//    asm ("{\n"
-//         "    match.any.sync.b32 %0, %1, 0xffffffff;\n"
-//         "}\n" : "=r"(retval) : "r"(label));
-//    return retval;
+} // namespace detail
 
+/**
+ * Compute a 32b mask of threads having the same least-significant
+ * LABEL_BITS of \p label as the calling thread.
+ */
+template <int LABEL_BITS, int WARP_ACTIVE_THREADS = CUB_PTX_WARP_THREADS>
+inline __device__ unsigned int MatchAny(unsigned int label)
+{
+  return detail::warp_matcher_t<LABEL_BITS, WARP_ACTIVE_THREADS>::match_any(label);
 }
 
 CUB_NAMESPACE_END
```

## nvidia/cuda_cccl/include/cub/util_type.cuh

```diff
@@ -35,30 +35,47 @@
 
 #include <cfloat>
 #include <iostream>
 #include <iterator>
 #include <limits>
 #include <type_traits>
 
-#if (__CUDACC_VER_MAJOR__ >= 9 || CUDA_VERSION >= 9000) && !_NVHPC_CUDA
+#include <cuda.h>
+
+#if !_NVHPC_CUDA
     #include <cuda_fp16.h>
 #endif
-#if (__CUDACC_VER_MAJOR__ >= 11 || CUDA_VERSION >= 11000) && !_NVHPC_CUDA &&   \
-  !defined(CUB_DISABLE_BF16_SUPPORT)
-#include <cuda_bf16.h>
+#if !_NVHPC_CUDA && !defined(CUB_DISABLE_BF16_SUPPORT)
+    #include <cuda_bf16.h>
 #endif
 
 #include <cub/detail/uninitialized_copy.cuh>
 #include <cub/util_arch.cuh>
+#include <cub/util_compiler.cuh>
 #include <cub/util_deprecated.cuh>
 #include <cub/util_macro.cuh>
 #include <cub/util_namespace.cuh>
 
 CUB_NAMESPACE_BEGIN
 
+#ifndef CUB_IS_INT128_ENABLED
+#if defined(__CUDACC_RTC__)
+#if defined(__CUDACC_RTC_INT128__)
+#define CUB_IS_INT128_ENABLED 1
+#endif // !defined(__CUDACC_RTC_INT128__)
+#else  // !defined(__CUDACC_RTC__)
+#if CUDA_VERSION >= 11050
+#if (CUB_HOST_COMPILER == CUB_HOST_COMPILER_GCC) || \
+    (CUB_HOST_COMPILER == CUB_HOST_COMPILER_CLANG) || \
+    defined(__ICC) || defined(_NVHPC_CUDA)
+#define CUB_IS_INT128_ENABLED 1
+#endif // GCC || CLANG || ICC || NVHPC
+#endif // CTK >= 11.5
+#endif // !defined(__CUDACC_RTC__)
+#endif // !defined(CUB_IS_INT128_ENABLED)
 
 /**
  * \addtogroup UtilModule
  * @{
  */
 
 
@@ -1087,15 +1104,15 @@
     }
 
     static __host__ __device__ __forceinline__ double Lowest() {
         return DBL_MAX  * double(-1);
     }
 };
 
-#if (__CUDACC_VER_MAJOR__ >= 9 || CUDA_VERSION >= 9000) && !_NVHPC_CUDA
+#if !_NVHPC_CUDA
 template <>
 struct FpLimits<__half>
 {
     static __host__ __device__ __forceinline__ __half Max() {
         unsigned short max_word = 0x7BFF;
         return reinterpret_cast<__half&>(max_word);
     }
@@ -1103,16 +1120,15 @@
     static __host__ __device__ __forceinline__ __half Lowest() {
         unsigned short lowest_word = 0xFBFF;
         return reinterpret_cast<__half&>(lowest_word);
     }
 };
 #endif
 
-#if (__CUDACC_VER_MAJOR__ >= 11 || CUDA_VERSION >= 11000) && !_NVHPC_CUDA &&   \
-  !defined(CUB_DISABLE_BF16_SUPPORT)
+#if !_NVHPC_CUDA && !defined(CUB_DISABLE_BF16_SUPPORT)
 template <>
 struct FpLimits<__nv_bfloat16>
 {
     static __host__ __device__ __forceinline__ __nv_bfloat16 Max() {
         unsigned short max_word = 0x7F7F;
         return reinterpret_cast<__nv_bfloat16&>(max_word);
     }
@@ -1182,21 +1198,94 @@
 
 template <> struct NumericTraits<unsigned char> :       BaseTraits<UNSIGNED_INTEGER, true, false, unsigned char, unsigned char> {};
 template <> struct NumericTraits<unsigned short> :      BaseTraits<UNSIGNED_INTEGER, true, false, unsigned short, unsigned short> {};
 template <> struct NumericTraits<unsigned int> :        BaseTraits<UNSIGNED_INTEGER, true, false, unsigned int, unsigned int> {};
 template <> struct NumericTraits<unsigned long> :       BaseTraits<UNSIGNED_INTEGER, true, false, unsigned long, unsigned long> {};
 template <> struct NumericTraits<unsigned long long> :  BaseTraits<UNSIGNED_INTEGER, true, false, unsigned long long, unsigned long long> {};
 
+
+#if CUB_IS_INT128_ENABLED 
+template <>
+struct NumericTraits<__uint128_t>
+{
+  using T = __uint128_t;
+  using UnsignedBits = __uint128_t;
+
+  static constexpr Category       CATEGORY    = UNSIGNED_INTEGER;
+  static constexpr UnsignedBits   LOWEST_KEY  = UnsignedBits(0);
+  static constexpr UnsignedBits   MAX_KEY     = UnsignedBits(-1);
+
+  static constexpr bool PRIMITIVE = false;
+  static constexpr bool NULL_TYPE = false;
+
+  static __host__ __device__ __forceinline__ UnsignedBits TwiddleIn(UnsignedBits key)
+  {
+    return key;
+  }
+
+  static __host__ __device__ __forceinline__ UnsignedBits TwiddleOut(UnsignedBits key)
+  {
+    return key;
+  }
+
+  static __host__ __device__ __forceinline__ T Max()
+  {
+    return MAX_KEY;
+  }
+
+  static __host__ __device__ __forceinline__ T Lowest()
+  {
+    return LOWEST_KEY;
+  }
+};
+
+template <>
+struct NumericTraits<__int128_t>
+{
+  using T = __int128_t;
+  using UnsignedBits = __uint128_t;
+
+  static constexpr Category       CATEGORY    = SIGNED_INTEGER;
+  static constexpr UnsignedBits   HIGH_BIT    = UnsignedBits(1) << ((sizeof(UnsignedBits) * 8) - 1);
+  static constexpr UnsignedBits   LOWEST_KEY  = HIGH_BIT;
+  static constexpr UnsignedBits   MAX_KEY     = UnsignedBits(-1) ^ HIGH_BIT;
+
+  static constexpr bool PRIMITIVE = false;
+  static constexpr bool NULL_TYPE = false;
+
+  static __host__ __device__ __forceinline__ UnsignedBits TwiddleIn(UnsignedBits key)
+  {
+    return key ^ HIGH_BIT;
+  };
+
+  static __host__ __device__ __forceinline__ UnsignedBits TwiddleOut(UnsignedBits key)
+  {
+    return key ^ HIGH_BIT;
+  };
+
+  static __host__ __device__ __forceinline__ T Max()
+  {
+    UnsignedBits retval = MAX_KEY;
+    return reinterpret_cast<T&>(retval);
+  }
+
+  static __host__ __device__ __forceinline__ T Lowest()
+  {
+    UnsignedBits retval = LOWEST_KEY;
+    return reinterpret_cast<T&>(retval);
+  }
+};
+#endif
+
 template <> struct NumericTraits<float> :               BaseTraits<FLOATING_POINT, true, false, unsigned int, float> {};
 template <> struct NumericTraits<double> :              BaseTraits<FLOATING_POINT, true, false, unsigned long long, double> {};
-#if (__CUDACC_VER_MAJOR__ >= 9 || CUDA_VERSION >= 9000) && !_NVHPC_CUDA
+#if !_NVHPC_CUDA
     template <> struct NumericTraits<__half> :          BaseTraits<FLOATING_POINT, true, false, unsigned short, __half> {};
 #endif
-#if (__CUDACC_VER_MAJOR__ >= 11 || CUDA_VERSION >= 11000) && !_NVHPC_CUDA &&   \
-  !defined(CUB_DISABLE_BF16_SUPPORT)
+#if !_NVHPC_CUDA && !defined(CUB_DISABLE_BF16_SUPPORT)
     template <> struct NumericTraits<__nv_bfloat16> :   BaseTraits<FLOATING_POINT, true, false, unsigned short, __nv_bfloat16> {};
 #endif
 
 template <> struct NumericTraits<bool> :                BaseTraits<UNSIGNED_INTEGER, true, false, typename UnitWord<bool>::VolatileWord, bool> {};
 // clang-format on
 
 /**
```

## nvidia/cuda_cccl/include/cub/version.cuh

```diff
@@ -39,15 +39,15 @@
  *  \brief The preprocessor macro \p CUB_VERSION encodes the version
  *         number of the CUB library.
  *
  *         <tt>CUB_VERSION % 100</tt> is the sub-minor version.
  *         <tt>CUB_VERSION / 100 % 1000</tt> is the minor version.
  *         <tt>CUB_VERSION / 100000</tt> is the major version.
  */
-#define CUB_VERSION 200001
+#define CUB_VERSION 200101
 
 /*! \def CUB_MAJOR_VERSION
  *  \brief The preprocessor macro \p CUB_MAJOR_VERSION encodes the
  *         major version number of the CUB library.
  */
 #define CUB_MAJOR_VERSION     (CUB_VERSION / 100000)
```

## nvidia/cuda_cccl/include/cub/agent/agent_histogram.cuh

 * *Ordering differences only*

```diff
@@ -691,20 +691,20 @@
         CounterT*           (&d_output_histograms)[NUM_ACTIVE_CHANNELS],        ///< Reference to final output histograms
         CounterT*           (&d_privatized_histograms)[NUM_ACTIVE_CHANNELS],    ///< Reference to privatized histograms
         OutputDecodeOpT     (&output_decode_op)[NUM_ACTIVE_CHANNELS],           ///< The transform operator for determining output bin-ids from privatized counter indices, one for each channel
         PrivatizedDecodeOpT (&privatized_decode_op)[NUM_ACTIVE_CHANNELS])       ///< The transform operator for determining privatized counter indices from samples, one for each channel
     :
         temp_storage(temp_storage.Alias()),
         d_wrapped_samples(d_samples),
+        d_native_samples(NativePointer(d_wrapped_samples)),
         num_output_bins(num_output_bins),
         num_privatized_bins(num_privatized_bins),
         d_output_histograms(d_output_histograms),
-        privatized_decode_op(privatized_decode_op),
         output_decode_op(output_decode_op),
-        d_native_samples(NativePointer(d_wrapped_samples)),
+        privatized_decode_op(privatized_decode_op),
         prefer_smem((MEM_PREFERENCE == SMEM) ?
             true :                              // prefer smem privatized histograms
             (MEM_PREFERENCE == GMEM) ?
                 false :                         // prefer gmem privatized histograms
                 blockIdx.x & 1)                 // prefer blended privatized histograms
     {
         int blockId = (blockIdx.y * gridDim.x) + blockIdx.x;
```

## nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_downsweep.cuh

```diff
@@ -132,35 +132,17 @@
     };
 
     // Input iterator wrapper type (for applying cache modifier)s
     using KeysItr = CacheModifiedInputIterator<LOAD_MODIFIER, UnsignedBits, OffsetT>;
     using ValuesItr = CacheModifiedInputIterator<LOAD_MODIFIER, ValueT, OffsetT>;
 
     // Radix ranking type to use
-    using BlockRadixRankT = cub::detail::conditional_t<
-      RANK_ALGORITHM == RADIX_RANK_BASIC,
-      BlockRadixRank<BLOCK_THREADS, RADIX_BITS, IS_DESCENDING, false, SCAN_ALGORITHM>,
-      cub::detail::conditional_t<
-        RANK_ALGORITHM == RADIX_RANK_MEMOIZE,
-        BlockRadixRank<BLOCK_THREADS, RADIX_BITS, IS_DESCENDING, true, SCAN_ALGORITHM>,
-        cub::detail::conditional_t<
-          RANK_ALGORITHM == RADIX_RANK_MATCH,
-          BlockRadixRankMatch<BLOCK_THREADS, RADIX_BITS, IS_DESCENDING, SCAN_ALGORITHM>,
-          cub::detail::conditional_t<
-            RANK_ALGORITHM == RADIX_RANK_MATCH_EARLY_COUNTS_ANY,
-            BlockRadixRankMatchEarlyCounts<BLOCK_THREADS,
-                                           RADIX_BITS,
-                                           IS_DESCENDING,
-                                           SCAN_ALGORITHM,
-                                           WARP_MATCH_ANY>,
-            BlockRadixRankMatchEarlyCounts<BLOCK_THREADS,
-                                           RADIX_BITS,
-                                           IS_DESCENDING,
-                                           SCAN_ALGORITHM,
-                                           WARP_MATCH_ATOMIC_OR>>>>>;
+    using BlockRadixRankT = 
+      cub::detail::block_radix_rank_t<
+        RANK_ALGORITHM, BLOCK_THREADS, RADIX_BITS, IS_DESCENDING, SCAN_ALGORITHM>;
 
     // Digit extractor type
     using DigitExtractorT = BFEDigitExtractor<KeyT>;
 
     enum
     {
         /// Number of bin-starting offsets tracked per thread
```

## nvidia/cuda_cccl/include/cub/agent/agent_reduce.cuh

```diff
@@ -351,56 +351,30 @@
   template <int CAN_VECTORIZE>
   __device__ __forceinline__ AccumT
   ConsumeRange(GridEvenShare<OffsetT> &even_share,
                Int2Type<CAN_VECTORIZE> can_vectorize)
   {
     AccumT thread_aggregate{};
 
-    if (even_share.block_offset + TILE_ITEMS > even_share.block_end)
+    if (even_share.block_end - even_share.block_offset < TILE_ITEMS)
     {
       // First tile isn't full (not all threads have valid items)
       int valid_items = even_share.block_end - even_share.block_offset;
       ConsumeTile<true>(thread_aggregate,
                         even_share.block_offset,
                         valid_items,
                         Int2Type<false>(),
                         can_vectorize);
       return BlockReduceT(temp_storage.reduce)
         .Reduce(thread_aggregate, reduction_op, valid_items);
     }
 
-    // At least one full block
-    ConsumeTile<true>(thread_aggregate,
-                      even_share.block_offset,
-                      TILE_ITEMS,
-                      Int2Type<true>(),
-                      can_vectorize);
-    even_share.block_offset += even_share.block_stride;
-
-    // Consume subsequent full tiles of input
-    while (even_share.block_offset + TILE_ITEMS <= even_share.block_end)
-    {
-      ConsumeTile<false>(thread_aggregate,
-                         even_share.block_offset,
-                         TILE_ITEMS,
-                         Int2Type<true>(),
-                         can_vectorize);
-      even_share.block_offset += even_share.block_stride;
-    }
-
-    // Consume a partially-full tile
-    if (even_share.block_offset < even_share.block_end)
-    {
-      int valid_items = even_share.block_end - even_share.block_offset;
-      ConsumeTile<false>(thread_aggregate,
-                         even_share.block_offset,
-                         valid_items,
-                         Int2Type<false>(),
-                         can_vectorize);
-    }
+    // Extracting this into a function saves 8% of generated kernel size by allowing to reuse 
+    // the block reduction below. This also workaround hang in nvcc.
+    ConsumeFullTileRange(thread_aggregate, even_share, can_vectorize);
 
     // Compute block-wide reduction (all threads have valid items)
     return BlockReduceT(temp_storage.reduce)
       .Reduce(thread_aggregate, reduction_op);
   }
 
   /**
@@ -424,21 +398,78 @@
   /**
    * Reduce a contiguous segment of input tiles
    * @param[in] even_share GridEvenShare descriptor
    */
   __device__ __forceinline__ AccumT
   ConsumeTiles(GridEvenShare<OffsetT> &even_share)
   {
-    // Initialize GRID_MAPPING_STRIP_MINE even-share descriptor for this thread
-    // block
+    // Initialize GRID_MAPPING_STRIP_MINE even-share descriptor for this thread block
     even_share.template BlockInit<TILE_ITEMS, GRID_MAPPING_STRIP_MINE>();
 
     return (IsAligned(d_in, Int2Type<ATTEMPT_VECTORIZATION>()))
              ? ConsumeRange(even_share,
                             Int2Type < true && ATTEMPT_VECTORIZATION > ())
              : ConsumeRange(even_share,
                             Int2Type < false && ATTEMPT_VECTORIZATION > ());
   }
+
+private:
+  /**
+   * @brief Reduce a contiguous segment of input tiles with more than `TILE_ITEMS` elements
+   * @param even_share GridEvenShare descriptor
+   * @param can_vectorize Whether or not we can vectorize loads
+   */
+  template <int CAN_VECTORIZE>
+  __device__ __forceinline__ void
+  ConsumeFullTileRange(AccumT &thread_aggregate,
+                       GridEvenShare<OffsetT> &even_share,
+                       Int2Type<CAN_VECTORIZE> can_vectorize)
+  {
+    // At least one full block
+    ConsumeTile<true>(thread_aggregate,
+                      even_share.block_offset,
+                      TILE_ITEMS,
+                      Int2Type<true>(),
+                      can_vectorize);
+
+    if (even_share.block_end - even_share.block_offset < even_share.block_stride)
+    {
+      // Exit early to handle offset overflow
+      return;
+    }
+
+    even_share.block_offset += even_share.block_stride;
+
+    // Consume subsequent full tiles of input, at least one full tile was processed, so 
+    // `even_share.block_end >= TILE_ITEMS`
+    while (even_share.block_offset <= even_share.block_end - TILE_ITEMS)
+    {
+      ConsumeTile<false>(thread_aggregate,
+                         even_share.block_offset,
+                         TILE_ITEMS,
+                         Int2Type<true>(),
+                         can_vectorize);
+
+      if (even_share.block_end - even_share.block_offset < even_share.block_stride)
+      {
+        // Exit early to handle offset overflow
+        return;
+      }
+
+      even_share.block_offset += even_share.block_stride;
+    }
+
+    // Consume a partially-full tile
+    if (even_share.block_offset < even_share.block_end)
+    {
+      int valid_items = even_share.block_end - even_share.block_offset;
+      ConsumeTile<false>(thread_aggregate,
+                         even_share.block_offset,
+                         valid_items,
+                         Int2Type<false>(),
+                         can_vectorize);
+    }
+  }
 };
 
 CUB_NAMESPACE_END
```

## nvidia/cuda_cccl/include/cub/agent/agent_reduce_by_key.cuh

```diff
@@ -9,17 +9,17 @@
  *     * Redistributions in binary form must reproduce the above copyright
  *       notice, this list of conditions and the following disclaimer in the
  *       documentation and/or other materials provided with the distribution.
  *     * Neither the name of the NVIDIA CORPORATION nor the
  *       names of its contributors may be used to endorse or promote products
  *       derived from this software without specific prior written permission.
  *
- * THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
- * AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
- * IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE 
+ * THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
+ * AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
+ * IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
  * ARE DISCLAIMED. IN NO EVENT SHALL NVIDIA CORPORATION BE LIABLE FOR ANY
  * DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
  * (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
  * LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
  * ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
  * (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
  * SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
@@ -29,25 +29,25 @@
 /**
  * @file cub::AgentReduceByKey implements a stateful abstraction of CUDA thread
  *       blocks for participating in device-wide reduce-value-by-key.
  */
 
 #pragma once
 
-#include <iterator>
-
 #include <cub/agent/single_pass_scan_operators.cuh>
 #include <cub/block/block_discontinuity.cuh>
 #include <cub/block/block_load.cuh>
 #include <cub/block/block_scan.cuh>
 #include <cub/block/block_store.cuh>
 #include <cub/config.cuh>
 #include <cub/iterator/cache_modified_input_iterator.cuh>
 #include <cub/iterator/constant_input_iterator.cuh>
 
+#include <iterator>
+
 CUB_NAMESPACE_BEGIN
 
 /******************************************************************************
  * Tuning policy types
  ******************************************************************************/
 
 /**
@@ -142,16 +142,15 @@
   // Types and constants
   //---------------------------------------------------------------------
 
   // The input keys type
   using KeyInputT = cub::detail::value_t<KeysInputIteratorT>;
 
   // The output keys type
-  using KeyOutputT =
-    cub::detail::non_void_value_t<UniqueOutputIteratorT, KeyInputT>;
+  using KeyOutputT = cub::detail::non_void_value_t<UniqueOutputIteratorT, KeyInputT>;
 
   // The input values type
   using ValueInputT = cub::detail::value_t<ValuesInputIteratorT>;
 
   // Tuple type for scanning (pairs accumulated segment-value with
   // segment-index)
   using OffsetValuePairT = KeyValuePair<OffsetT, AccumT>;
@@ -169,104 +168,88 @@
     /// Wrapped equality operator
     _EqualityOpT op;
 
     /// Items remaining
     int num_remaining;
 
     /// Constructor
-    __host__ __device__ __forceinline__
-    GuardedInequalityWrapper(_EqualityOpT op, int num_remaining)
+    __host__ __device__ __forceinline__ GuardedInequalityWrapper(_EqualityOpT op, int num_remaining)
         : op(op)
         , num_remaining(num_remaining)
     {}
 
     /// Boolean inequality operator, returns <tt>(a != b)</tt>
     template <typename T>
-    __host__ __device__ __forceinline__ bool operator()(const T &a,
-                                                        const T &b,
-                                                        int idx) const
+    __host__ __device__ __forceinline__ bool operator()(const T &a, const T &b, int idx) const
     {
       if (idx < num_remaining)
       {
         return !op(a, b); // In bounds
       }
 
       // Return true if first out-of-bounds item, false otherwise
       return (idx == num_remaining);
     }
   };
 
   // Constants
-  static constexpr int BLOCK_THREADS = AgentReduceByKeyPolicyT::BLOCK_THREADS;
-  static constexpr int ITEMS_PER_THREAD =
-    AgentReduceByKeyPolicyT::ITEMS_PER_THREAD;
+  static constexpr int BLOCK_THREADS     = AgentReduceByKeyPolicyT::BLOCK_THREADS;
+  static constexpr int ITEMS_PER_THREAD  = AgentReduceByKeyPolicyT::ITEMS_PER_THREAD;
   static constexpr int TILE_ITEMS        = BLOCK_THREADS * ITEMS_PER_THREAD;
   static constexpr int TWO_PHASE_SCATTER = (ITEMS_PER_THREAD > 1);
 
   // Whether or not the scan operation has a zero-valued identity value (true
   // if we're performing addition on a primitive type)
-  static constexpr int HAS_IDENTITY_ZERO =
-    (std::is_same<ReductionOpT, cub::Sum>::value) &&
-    (Traits<AccumT>::PRIMITIVE);
+  static constexpr int HAS_IDENTITY_ZERO = (std::is_same<ReductionOpT, cub::Sum>::value) &&
+                                           (Traits<AccumT>::PRIMITIVE);
 
   // Cache-modified Input iterator wrapper type (for applying cache modifier)
   // for keys Wrap the native input pointer with
   // CacheModifiedValuesInputIterator or directly use the supplied input
   // iterator type
   using WrappedKeysInputIteratorT = cub::detail::conditional_t<
     std::is_pointer<KeysInputIteratorT>::value,
-    CacheModifiedInputIterator<AgentReduceByKeyPolicyT::LOAD_MODIFIER,
-                               KeyInputT,
-                               OffsetT>,
+    CacheModifiedInputIterator<AgentReduceByKeyPolicyT::LOAD_MODIFIER, KeyInputT, OffsetT>,
     KeysInputIteratorT>;
 
   // Cache-modified Input iterator wrapper type (for applying cache modifier)
   // for values Wrap the native input pointer with
   // CacheModifiedValuesInputIterator or directly use the supplied input
   // iterator type
   using WrappedValuesInputIteratorT = cub::detail::conditional_t<
     std::is_pointer<ValuesInputIteratorT>::value,
-    CacheModifiedInputIterator<AgentReduceByKeyPolicyT::LOAD_MODIFIER,
-                               ValueInputT,
-                               OffsetT>,
+    CacheModifiedInputIterator<AgentReduceByKeyPolicyT::LOAD_MODIFIER, ValueInputT, OffsetT>,
     ValuesInputIteratorT>;
 
   // Cache-modified Input iterator wrapper type (for applying cache modifier)
   // for fixup values Wrap the native input pointer with
   // CacheModifiedValuesInputIterator or directly use the supplied input
   // iterator type
   using WrappedFixupInputIteratorT = cub::detail::conditional_t<
     std::is_pointer<AggregatesOutputIteratorT>::value,
-    CacheModifiedInputIterator<AgentReduceByKeyPolicyT::LOAD_MODIFIER,
-                               ValueInputT,
-                               OffsetT>,
+    CacheModifiedInputIterator<AgentReduceByKeyPolicyT::LOAD_MODIFIER, ValueInputT, OffsetT>,
     AggregatesOutputIteratorT>;
 
   // Reduce-value-by-segment scan operator
   using ReduceBySegmentOpT = ReduceBySegmentOp<ReductionOpT>;
 
   // Parameterized BlockLoad type for keys
-  using BlockLoadKeysT = BlockLoad<KeyOutputT,
-                                   BLOCK_THREADS,
-                                   ITEMS_PER_THREAD,
-                                   AgentReduceByKeyPolicyT::LOAD_ALGORITHM>;
+  using BlockLoadKeysT =
+    BlockLoad<KeyOutputT, BLOCK_THREADS, ITEMS_PER_THREAD, AgentReduceByKeyPolicyT::LOAD_ALGORITHM>;
 
   // Parameterized BlockLoad type for values
-  using BlockLoadValuesT = BlockLoad<AccumT,
-                                     BLOCK_THREADS,
-                                     ITEMS_PER_THREAD,
-                                     AgentReduceByKeyPolicyT::LOAD_ALGORITHM>;
+  using BlockLoadValuesT =
+    BlockLoad<AccumT, BLOCK_THREADS, ITEMS_PER_THREAD, AgentReduceByKeyPolicyT::LOAD_ALGORITHM>;
 
   // Parameterized BlockDiscontinuity type for keys
   using BlockDiscontinuityKeys = BlockDiscontinuity<KeyOutputT, BLOCK_THREADS>;
 
   // Parameterized BlockScan type
-  using BlockScanT = BlockScan<OffsetValuePairT,
-                               BLOCK_THREADS,
-                               AgentReduceByKeyPolicyT::SCAN_ALGORITHM>;
+  using BlockScanT =
+    BlockScan<OffsetValuePairT, BLOCK_THREADS, AgentReduceByKeyPolicyT::SCAN_ALGORITHM>;
 
   // Callback type for obtaining tile prefix during block scan
   using TilePrefixCallbackOpT =
     TilePrefixCallbackOp<OffsetValuePairT, ReduceBySegmentOpT, ScanTileStateT>;
 
   // Key and value exchange types
   typedef KeyOutputT KeyExchangeT[TILE_ITEMS + 1];
@@ -358,23 +341,22 @@
    *
    * @param equality_op
    *   KeyT equality operator
    *
    * @param reduction_op
    *   ValueT reduction operator
    */
-  __device__ __forceinline__
-  AgentReduceByKey(TempStorage &temp_storage,
-                   KeysInputIteratorT d_keys_in,
-                   UniqueOutputIteratorT d_unique_out,
-                   ValuesInputIteratorT d_values_in,
-                   AggregatesOutputIteratorT d_aggregates_out,
-                   NumRunsOutputIteratorT d_num_runs_out,
-                   EqualityOpT equality_op,
-                   ReductionOpT reduction_op)
+  __device__ __forceinline__ AgentReduceByKey(TempStorage &temp_storage,
+                                              KeysInputIteratorT d_keys_in,
+                                              UniqueOutputIteratorT d_unique_out,
+                                              ValuesInputIteratorT d_values_in,
+                                              AggregatesOutputIteratorT d_aggregates_out,
+                                              NumRunsOutputIteratorT d_num_runs_out,
+                                              EqualityOpT equality_op,
+                                              ReductionOpT reduction_op)
       : temp_storage(temp_storage.Alias())
       , d_keys_in(d_keys_in)
       , d_unique_out(d_unique_out)
       , d_values_in(d_values_in)
       , d_aggregates_out(d_aggregates_out)
       , d_num_runs_out(d_num_runs_out)
       , equality_op(equality_op)
@@ -385,18 +367,17 @@
   //---------------------------------------------------------------------
   // Scatter utility methods
   //---------------------------------------------------------------------
 
   /**
    * Directly scatter flagged items to output offsets
    */
-  __device__ __forceinline__ void
-  ScatterDirect(KeyValuePairT (&scatter_items)[ITEMS_PER_THREAD],
-                OffsetT (&segment_flags)[ITEMS_PER_THREAD],
-                OffsetT (&segment_indices)[ITEMS_PER_THREAD])
+  __device__ __forceinline__ void ScatterDirect(KeyValuePairT (&scatter_items)[ITEMS_PER_THREAD],
+                                                OffsetT (&segment_flags)[ITEMS_PER_THREAD],
+                                                OffsetT (&segment_indices)[ITEMS_PER_THREAD])
   {
 // Scatter flagged keys and values
 #pragma unroll
     for (int ITEM = 0; ITEM < ITEMS_PER_THREAD; ++ITEM)
     {
       if (segment_flags[ITEM])
       {
@@ -409,55 +390,51 @@
   /**
    * 2-phase scatter flagged items to output offsets
    *
    * The exclusive scan causes each head flag to be paired with the previous
    * value aggregate: the scatter offsets must be decremented for value
    * aggregates
    */
-  __device__ __forceinline__ void
-  ScatterTwoPhase(KeyValuePairT (&scatter_items)[ITEMS_PER_THREAD],
-                  OffsetT (&segment_flags)[ITEMS_PER_THREAD],
-                  OffsetT (&segment_indices)[ITEMS_PER_THREAD],
-                  OffsetT num_tile_segments,
-                  OffsetT num_tile_segments_prefix)
+  __device__ __forceinline__ void ScatterTwoPhase(KeyValuePairT (&scatter_items)[ITEMS_PER_THREAD],
+                                                  OffsetT (&segment_flags)[ITEMS_PER_THREAD],
+                                                  OffsetT (&segment_indices)[ITEMS_PER_THREAD],
+                                                  OffsetT num_tile_segments,
+                                                  OffsetT num_tile_segments_prefix)
   {
     CTA_SYNC();
 
 // Compact and scatter pairs
 #pragma unroll
     for (int ITEM = 0; ITEM < ITEMS_PER_THREAD; ++ITEM)
     {
       if (segment_flags[ITEM])
       {
-        temp_storage.raw_exchange
-          .Alias()[segment_indices[ITEM] - num_tile_segments_prefix] =
+        temp_storage.raw_exchange.Alias()[segment_indices[ITEM] - num_tile_segments_prefix] =
           scatter_items[ITEM];
       }
     }
 
     CTA_SYNC();
 
-    for (int item = threadIdx.x; item < num_tile_segments;
-         item += BLOCK_THREADS)
+    for (int item = threadIdx.x; item < num_tile_segments; item += BLOCK_THREADS)
     {
-      KeyValuePairT pair = temp_storage.raw_exchange.Alias()[item];
+      KeyValuePairT pair                                = temp_storage.raw_exchange.Alias()[item];
       d_unique_out[num_tile_segments_prefix + item]     = pair.key;
       d_aggregates_out[num_tile_segments_prefix + item] = pair.value;
     }
   }
 
   /**
    * Scatter flagged items
    */
-  __device__ __forceinline__ void
-  Scatter(KeyValuePairT (&scatter_items)[ITEMS_PER_THREAD],
-          OffsetT (&segment_flags)[ITEMS_PER_THREAD],
-          OffsetT (&segment_indices)[ITEMS_PER_THREAD],
-          OffsetT num_tile_segments,
-          OffsetT num_tile_segments_prefix)
+  __device__ __forceinline__ void Scatter(KeyValuePairT (&scatter_items)[ITEMS_PER_THREAD],
+                                          OffsetT (&segment_flags)[ITEMS_PER_THREAD],
+                                          OffsetT (&segment_indices)[ITEMS_PER_THREAD],
+                                          OffsetT num_tile_segments,
+                                          OffsetT num_tile_segments_prefix)
   {
     // Do a one-phase scatter if (a) two-phase is disabled or (b) the average
     // number of selected items per thread is less than one
     if (TWO_PHASE_SCATTER && (num_tile_segments > BLOCK_THREADS))
     {
       ScatterTwoPhase(scatter_items,
                       segment_flags,
@@ -490,18 +467,16 @@
    * @param tile_offset
    *   Tile offset
    *
    * @param tile_state
    *   Global tile state descriptor
    */
   template <bool IS_LAST_TILE>
-  __device__ __forceinline__ void ConsumeTile(OffsetT num_remaining,
-                                              int tile_idx,
-                                              OffsetT tile_offset,
-                                              ScanTileStateT &tile_state)
+  __device__ __forceinline__ void
+  ConsumeTile(OffsetT num_remaining, int tile_idx, OffsetT tile_offset, ScanTileStateT &tile_state)
   {
     // Tile keys
     KeyOutputT keys[ITEMS_PER_THREAD];
 
     // Tile keys shuffled up
     KeyOutputT prev_keys[ITEMS_PER_THREAD];
 
@@ -519,16 +494,15 @@
 
     // Zipped key value pairs for scattering
     KeyValuePairT scatter_items[ITEMS_PER_THREAD];
 
     // Load keys
     if (IS_LAST_TILE)
     {
-      BlockLoadKeysT(temp_storage.load_keys)
-        .Load(d_keys_in + tile_offset, keys, num_remaining);
+      BlockLoadKeysT(temp_storage.load_keys).Load(d_keys_in + tile_offset, keys, num_remaining);
     }
     else
     {
       BlockLoadKeysT(temp_storage.load_keys).Load(d_keys_in + tile_offset, keys);
     }
 
     // Load tile predecessor key in first thread
@@ -549,16 +523,15 @@
     if (IS_LAST_TILE)
     {
       BlockLoadValuesT(temp_storage.load_values)
         .Load(d_values_in + tile_offset, values, num_remaining);
     }
     else
     {
-      BlockLoadValuesT(temp_storage.load_values)
-        .Load(d_values_in + tile_offset, values);
+      BlockLoadValuesT(temp_storage.load_values).Load(d_values_in + tile_offset, values);
     }
 
     CTA_SYNC();
 
     // Initialize head-flags and shuffle up the previous keys
     if (IS_LAST_TILE)
     {
@@ -571,15 +544,22 @@
     else
     {
       InequalityWrapper<EqualityOpT> flag_op(equality_op);
       BlockDiscontinuityKeys(temp_storage.scan_storage.discontinuity)
         .FlagHeads(head_flags, keys, prev_keys, flag_op, tile_predecessor);
     }
 
-// Zip values and head flags
+    // Reset head-flag on the very first item to make sure we don't start a new run for data where
+    // (key[0] == key[0]) is false (e.g., when key[0] is NaN)
+    if (threadIdx.x == 0 && tile_idx == 0)
+    {
+      head_flags[0] = 0;
+    }
+
+    // Zip values and head flags
 #pragma unroll
     for (int ITEM = 0; ITEM < ITEMS_PER_THREAD; ++ITEM)
     {
       scan_items[ITEM].value = values[ITEM];
       scan_items[ITEM].key   = head_flags[ITEM];
     }
 
@@ -634,19 +614,15 @@
     // At this point, each flagged segment head has:
     //  - The key for the previous segment
     //  - The reduced value from the previous segment
     //  - The segment index for the reduced value
 
     // Scatter flagged keys and values
     OffsetT num_tile_segments = block_aggregate.key;
-    Scatter(scatter_items,
-            head_flags,
-            segment_indices,
-            num_tile_segments,
-            num_segments_prefix);
+    Scatter(scatter_items, head_flags, segment_indices, num_tile_segments, num_segments_prefix);
 
     // Last thread in last tile will output final count (and last pair, if
     // necessary)
     if ((IS_LAST_TILE) && (threadIdx.x == BLOCK_THREADS - 1))
     {
       OffsetT num_segments = num_segments_prefix + num_tile_segments;
 
@@ -701,8 +677,7 @@
       // Last tile
       ConsumeTile<true>(num_remaining, tile_idx, tile_offset, tile_state);
     }
   }
 };
 
 CUB_NAMESPACE_END
-
```

## nvidia/cuda_cccl/include/cub/agent/agent_select_if.cuh

 * *Ordering differences only*

```diff
@@ -227,18 +227,18 @@
         SelectedOutputIteratorT     d_selected_out,     ///< Output data
         SelectOpT                   select_op,          ///< Selection operator
         EqualityOpT                 equality_op,        ///< Equality operator
         OffsetT                     num_items)          ///< Total number of input items
     :
         temp_storage(temp_storage.Alias()),
         d_in(d_in),
-        d_flags_in(d_flags_in),
         d_selected_out(d_selected_out),
-        select_op(select_op),
+        d_flags_in(d_flags_in),
         inequality_op(equality_op),
+        select_op(select_op),
         num_items(num_items)
     {}
 
 
     //---------------------------------------------------------------------
     // Utility methods for initializing the selections
     //---------------------------------------------------------------------
```

## nvidia/cuda_cccl/include/cub/agent/agent_sub_warp_merge_sort.cuh

```diff
@@ -151,14 +151,33 @@
 
   template <typename T>
   __device__ static bool equal(T lhs, T rhs)
   {
     return lhs == rhs;
   }
 
+  __device__ static bool get_oob_default(Int2Type<true> /* is bool */) 
+  {
+    // Traits<KeyT>::MAX_KEY for `bool` is 0xFF which is different from `true` and makes
+    // comparison with oob unreliable.
+    return !IS_DESCENDING;
+  }
+
+  __device__ static KeyT get_oob_default(Int2Type<false> /* is bool */) 
+  {
+    // For FP64 the difference is:
+    // Lowest() -> -1.79769e+308 = 00...00b -> TwiddleIn -> -0 = 10...00b
+    // LOWEST   -> -nan          = 11...11b -> TwiddleIn ->  0 = 00...00b
+
+    using UnsignedBitsT = typename Traits<KeyT>::UnsignedBits;
+    UnsignedBitsT default_key_bits = IS_DESCENDING ? Traits<KeyT>::LOWEST_KEY
+                                                   : Traits<KeyT>::MAX_KEY;
+    return reinterpret_cast<KeyT &>(default_key_bits);
+  }
+
 public:
   static constexpr bool KEYS_ONLY = std::is_same<ValueT, cub::NullType>::value;
 
   using WarpMergeSortT =
     WarpMergeSort<KeyT, PolicyT::ITEMS_PER_THREAD, PolicyT::WARP_THREADS, ValueT>;
 
   using KeysLoadItT = typename THRUST_NS_QUALIFIER::cuda_cub::core::
@@ -225,22 +244,16 @@
                    BinaryOpT{});
     }
     else
     {
       KeyT keys[PolicyT::ITEMS_PER_THREAD];
       ValueT values[PolicyT::ITEMS_PER_THREAD];
 
-      // For FP64 the difference is:
-      // Lowest() -> -1.79769e+308 = 00...00b -> TwiddleIn -> -0 = 10...00b
-      // LOWEST   -> -nan          = 11...11b -> TwiddleIn ->  0 = 00...00b
-
-      using UnsignedBitsT = typename Traits<KeyT>::UnsignedBits;
-      UnsignedBitsT default_key_bits = IS_DESCENDING ? Traits<KeyT>::LOWEST_KEY
-                                                     : Traits<KeyT>::MAX_KEY;
-      KeyT oob_default = reinterpret_cast<KeyT &>(default_key_bits);
+      KeyT oob_default = 
+        AgentSubWarpSort::get_oob_default(Int2Type<std::is_same<bool, KeyT>::value>{});
 
       WarpLoadKeysT(storage.load_keys)
         .Load(keys_input, keys, segment_size, oob_default);
       WARP_SYNC(warp_merge_sort.get_member_mask());
 
       if (!KEYS_ONLY)
       {
```

## nvidia/cuda_cccl/include/cub/agent/single_pass_scan_operators.cuh

```diff
@@ -32,20 +32,24 @@
  */
 
 #pragma once
 
 #include <iterator>
 
 #include <cub/config.cuh>
+#include <cub/detail/strong_load.cuh>
+#include <cub/detail/strong_store.cuh>
 #include <cub/detail/uninitialized_copy.cuh>
 #include <cub/thread/thread_load.cuh>
 #include <cub/thread/thread_store.cuh>
 #include <cub/util_device.cuh>
 #include <cub/warp/warp_reduce.cuh>
 
+#include <nv/target>
+
 CUB_NAMESPACE_BEGIN
 
 
 /******************************************************************************
  * Prefix functor type for maintaining a running prefix while scanning a
  * region independent of other thread blocks
  ******************************************************************************/
@@ -102,14 +106,52 @@
 {
     SCAN_TILE_OOB,          // Out-of-bounds (e.g., padding)
     SCAN_TILE_INVALID = 99, // Not yet processed
     SCAN_TILE_PARTIAL,      // Tile aggregate is available
     SCAN_TILE_INCLUSIVE,    // Inclusive tile prefix is available
 };
 
+namespace detail 
+{
+
+template <int Delay, unsigned int GridThreshold = 500>
+__device__ __forceinline__ void delay()
+{
+  NV_IF_TARGET(NV_PROVIDES_SM_70,
+               (if (Delay > 0) 
+                {
+                  if (gridDim.x < GridThreshold) 
+                  {
+                    __threadfence_block();
+                  }
+                  else 
+                  {
+                    __nanosleep(Delay); 
+                  }
+                }));
+}
+
+template <int Delay = 350, unsigned int GridThreshold = 500>
+__device__ __forceinline__ void delay_or_prevent_hoisting()
+{
+  NV_IF_TARGET(NV_PROVIDES_SM_70,
+               (delay<Delay, GridThreshold>();),
+               (__threadfence_block();));
+}
+
+template <int Delay = 350, unsigned int GridThreshold = 500>
+__device__ __forceinline__ void delay_on_dc_gpu_or_prevent_hoisting()
+{
+  NV_DISPATCH_TARGET(
+    NV_IS_EXACTLY_SM_80, (delay<Delay, GridThreshold>();),
+    NV_PROVIDES_SM_70,   (delay<    0, GridThreshold>();),
+    NV_IS_DEVICE,        (__threadfence_block();));
+}
+
+}
 
 /**
  * Tile status interface.
  */
 template <
     typename    T,
     bool        SINGLE_WORD = Traits<T>::PRIMITIVE>
@@ -123,28 +165,28 @@
  */
 template <typename T>
 struct ScanTileState<T, true>
 {
     // Status word type
     using StatusWord = cub::detail::conditional_t<
       sizeof(T) == 8,
-      long long,
+      unsigned long long,
       cub::detail::conditional_t<
         sizeof(T) == 4,
-        int,
-        cub::detail::conditional_t<sizeof(T) == 2, short, char>>>;
+        unsigned int,
+        cub::detail::conditional_t<sizeof(T) == 2, unsigned short, unsigned char>>>;
 
     // Unit word type
     using TxnWord = cub::detail::conditional_t<
       sizeof(T) == 8,
-      longlong2,
+      ulonglong2,
       cub::detail::conditional_t<
         sizeof(T) == 4,
-        int2,
-        cub::detail::conditional_t<sizeof(T) == 2, int, uchar2>>>;
+        uint2,
+        unsigned int>>;
 
     // Device word type
     struct TileDescriptor
     {
         StatusWord  status;
         T           value;
     };
@@ -184,15 +226,15 @@
      * Compute device memory needed for tile status
      */
     __host__ __device__ __forceinline__
     static cudaError_t AllocationSize(
         int     num_tiles,                          ///< [in] Number of tiles
         size_t  &temp_storage_bytes)                ///< [out] Size in bytes of \t d_temp_storage allocation
     {
-        temp_storage_bytes = (num_tiles + TILE_STATUS_PADDING) * sizeof(TileDescriptor);       // bytes needed for tile status descriptors
+        temp_storage_bytes = (num_tiles + TILE_STATUS_PADDING) * sizeof(TxnWord);       // bytes needed for tile status descriptors
         return cudaSuccess;
     }
 
 
     /**
      * Initialize (from device)
      */
@@ -226,66 +268,83 @@
     {
         TileDescriptor tile_descriptor;
         tile_descriptor.status = SCAN_TILE_INCLUSIVE;
         tile_descriptor.value = tile_inclusive;
 
         TxnWord alias;
         *reinterpret_cast<TileDescriptor*>(&alias) = tile_descriptor;
-        ThreadStore<STORE_CG>(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
+
+        detail::store_relaxed(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
     }
 
 
     /**
      * Update the specified tile's partial value and corresponding status
      */
     __device__ __forceinline__ void SetPartial(int tile_idx, T tile_partial)
     {
         TileDescriptor tile_descriptor;
         tile_descriptor.status = SCAN_TILE_PARTIAL;
         tile_descriptor.value = tile_partial;
 
         TxnWord alias;
         *reinterpret_cast<TileDescriptor*>(&alias) = tile_descriptor;
-        ThreadStore<STORE_CG>(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
+
+        detail::store_relaxed(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
     }
 
     /**
      * Wait for the corresponding tile to become non-invalid
      */
     __device__ __forceinline__ void WaitForValid(
         int             tile_idx,
         StatusWord      &status,
         T               &value)
     {
         TileDescriptor tile_descriptor;
-        do
+
         {
-            __threadfence_block(); // prevent hoisting loads from loop
-            TxnWord alias = ThreadLoad<LOAD_CG>(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx);
-            tile_descriptor = reinterpret_cast<TileDescriptor&>(alias);
+          TxnWord alias = detail::load_relaxed(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx);
+          tile_descriptor = reinterpret_cast<TileDescriptor&>(alias);
+        }
 
-        } while (WARP_ANY((tile_descriptor.status == SCAN_TILE_INVALID), 0xffffffff));
+        while (WARP_ANY((tile_descriptor.status == SCAN_TILE_INVALID), 0xffffffff))
+        {   
+          detail::delay_or_prevent_hoisting();
+          TxnWord alias = detail::load_relaxed(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx);
+          tile_descriptor = reinterpret_cast<TileDescriptor&>(alias);
+        }
 
         status = tile_descriptor.status;
         value = tile_descriptor.value;
     }
 
+    /**
+     * Loads and returns the tile's value. The returned value is undefined if either (a) the tile's status is invalid or
+     * (b) there is no memory fence between reading a non-invalid status and the call to LoadValid.
+     */
+     __device__ __forceinline__ T LoadValid(int tile_idx)                        
+    {                                                                           
+        TxnWord alias = d_tile_descriptors[TILE_STATUS_PADDING + tile_idx];
+        TileDescriptor tile_descriptor = reinterpret_cast<TileDescriptor&>(alias);
+        return tile_descriptor.value;                                           
+    }
 };
 
 
 
 /**
  * Tile status interface specialized for scan status and value types that
  * cannot be combined into one machine word.
  */
 template <typename T>
 struct ScanTileState<T, false>
 {
     // Status word type
-    typedef char StatusWord;
+    using StatusWord = unsigned int;
 
     // Constants
     enum
     {
         TILE_STATUS_PADDING = CUB_PTX_WARP_THREADS,
     };
 
@@ -378,57 +437,60 @@
     /**
      * Update the specified tile's inclusive value and corresponding status
      */
     __device__ __forceinline__ void SetInclusive(int tile_idx, T tile_inclusive)
     {
         // Update tile inclusive value
         ThreadStore<STORE_CG>(d_tile_inclusive + TILE_STATUS_PADDING + tile_idx, tile_inclusive);
-
-        // Fence
-        __threadfence();
-
-        // Update tile status
-        ThreadStore<STORE_CG>(d_tile_status + TILE_STATUS_PADDING + tile_idx, StatusWord(SCAN_TILE_INCLUSIVE));
+        detail::store_release(d_tile_status + TILE_STATUS_PADDING + tile_idx, StatusWord(SCAN_TILE_INCLUSIVE));
     }
 
 
     /**
      * Update the specified tile's partial value and corresponding status
      */
     __device__ __forceinline__ void SetPartial(int tile_idx, T tile_partial)
     {
         // Update tile partial value
         ThreadStore<STORE_CG>(d_tile_partial + TILE_STATUS_PADDING + tile_idx, tile_partial);
-
-        // Fence
-        __threadfence();
-
-        // Update tile status
-        ThreadStore<STORE_CG>(d_tile_status + TILE_STATUS_PADDING + tile_idx, StatusWord(SCAN_TILE_PARTIAL));
+        detail::store_release(d_tile_status + TILE_STATUS_PADDING + tile_idx, StatusWord(SCAN_TILE_PARTIAL));
     }
 
     /**
      * Wait for the corresponding tile to become non-invalid
      */
     __device__ __forceinline__ void WaitForValid(
         int             tile_idx,
         StatusWord      &status,
         T               &value)
     {
-        do {
-            status = ThreadLoad<LOAD_CG>(d_tile_status + TILE_STATUS_PADDING + tile_idx);
-
-            __threadfence();    // prevent hoisting loads from loop or loads below above this one
+        do
+        {
+          status = detail::load_relaxed(d_tile_status + TILE_STATUS_PADDING + tile_idx);
+          __threadfence();
 
-        } while (status == SCAN_TILE_INVALID);
+        } while (WARP_ANY((status == SCAN_TILE_INVALID), 0xffffffff));
 
         if (status == StatusWord(SCAN_TILE_PARTIAL)) 
-            value = ThreadLoad<LOAD_CG>(d_tile_partial + TILE_STATUS_PADDING + tile_idx);
+        {
+          value = ThreadLoad<LOAD_CG>(d_tile_partial + TILE_STATUS_PADDING + tile_idx);
+        }
         else
-            value = ThreadLoad<LOAD_CG>(d_tile_inclusive + TILE_STATUS_PADDING + tile_idx);
+        {
+          value = ThreadLoad<LOAD_CG>(d_tile_inclusive + TILE_STATUS_PADDING + tile_idx);
+        }
+    }
+
+    /**
+     * Loads and returns the tile's value. The returned value is undefined if either (a) the tile's status is invalid or
+     * (b) there is no memory fence between reading a non-invalid status and the call to LoadValid.
+     */
+    __device__ __forceinline__ T LoadValid(int tile_idx)                        
+    {                                                                           
+        return d_tile_inclusive[TILE_STATUS_PADDING + tile_idx];                                          
     }
 };
 
 
 /******************************************************************************
  * ReduceByKey tile status interface types for block-cooperative scans
  ******************************************************************************/
@@ -467,40 +529,40 @@
  * can be combined into one machine word that can be read/written coherently in a single access.
  */
 template <
     typename ValueT,
     typename KeyT>
 struct ReduceByKeyScanTileState<ValueT, KeyT, true>
 {
-    typedef KeyValuePair<KeyT, ValueT>KeyValuePairT;
+    using KeyValuePairT = KeyValuePair<KeyT, ValueT>;
 
     // Constants
     enum
     {
         PAIR_SIZE           = static_cast<int>(sizeof(ValueT) + sizeof(KeyT)),
         TXN_WORD_SIZE       = 1 << Log2<PAIR_SIZE + 1>::VALUE,
         STATUS_WORD_SIZE    = TXN_WORD_SIZE - PAIR_SIZE,
 
         TILE_STATUS_PADDING = CUB_PTX_WARP_THREADS,
     };
 
     // Status word type
     using StatusWord = cub::detail::conditional_t<
       STATUS_WORD_SIZE == 8,
-      long long,
+      unsigned long long,
       cub::detail::conditional_t<
         STATUS_WORD_SIZE == 4,
-        int,
-        cub::detail::conditional_t<STATUS_WORD_SIZE == 2, short, char>>>;
+        unsigned int,
+        cub::detail::conditional_t<STATUS_WORD_SIZE == 2, unsigned short, unsigned char>>>;
 
     // Status word type
     using TxnWord = cub::detail::conditional_t<
       TXN_WORD_SIZE == 16,
-      longlong2,
-      cub::detail::conditional_t<TXN_WORD_SIZE == 8, long long, int>>;
+      ulonglong2,
+      cub::detail::conditional_t<TXN_WORD_SIZE == 8, unsigned long long, unsigned int>>;
 
     // Device word type (for when sizeof(ValueT) == sizeof(KeyT))
     struct TileDescriptorBigStatus
     {
         KeyT        key;
         ValueT      value;
         StatusWord  status;
@@ -548,15 +610,15 @@
      * Compute device memory needed for tile status
      */
     __host__ __device__ __forceinline__
     static cudaError_t AllocationSize(
         int     num_tiles,                          ///< [in] Number of tiles
         size_t  &temp_storage_bytes)                ///< [out] Size in bytes of \t d_temp_storage allocation
     {
-        temp_storage_bytes = (num_tiles + TILE_STATUS_PADDING) * sizeof(TileDescriptor);       // bytes needed for tile status descriptors
+        temp_storage_bytes = (num_tiles + TILE_STATUS_PADDING) * sizeof(TxnWord);       // bytes needed for tile status descriptors
         return cudaSuccess;
     }
 
 
     /**
      * Initialize (from device)
      */
@@ -590,15 +652,16 @@
         TileDescriptor tile_descriptor;
         tile_descriptor.status  = SCAN_TILE_INCLUSIVE;
         tile_descriptor.value   = tile_inclusive.value;
         tile_descriptor.key     = tile_inclusive.key;
 
         TxnWord alias;
         *reinterpret_cast<TileDescriptor*>(&alias) = tile_descriptor;
-        ThreadStore<STORE_CG>(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
+
+        detail::store_relaxed(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
     }
 
 
     /**
      * Update the specified tile's partial value and corresponding status
      */
     __device__ __forceinline__ void SetPartial(int tile_idx, KeyValuePairT tile_partial)
@@ -606,15 +669,16 @@
         TileDescriptor tile_descriptor;
         tile_descriptor.status  = SCAN_TILE_PARTIAL;
         tile_descriptor.value   = tile_partial.value;
         tile_descriptor.key     = tile_partial.key;
 
         TxnWord alias;
         *reinterpret_cast<TileDescriptor*>(&alias) = tile_descriptor;
-        ThreadStore<STORE_CG>(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
+
+        detail::store_relaxed(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx, alias);
     }
 
     /**
      * Wait for the corresponding tile to become non-invalid
      */
     __device__ __forceinline__ void WaitForValid(
         int                     tile_idx,
@@ -633,19 +697,20 @@
 //        }
 //
 //        status      = tile_descriptor.status;
 //        value.value = tile_descriptor.value;
 //        value.key   = tile_descriptor.key;
 
         TileDescriptor tile_descriptor;
+
         do
         {
-            __threadfence_block(); // prevent hoisting loads from loop
-            TxnWord alias = ThreadLoad<LOAD_CG>(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx);
-            tile_descriptor = reinterpret_cast<TileDescriptor&>(alias);
+          detail::delay_on_dc_gpu_or_prevent_hoisting();
+          TxnWord alias = detail::load_relaxed(d_tile_descriptors + TILE_STATUS_PADDING + tile_idx);
+          tile_descriptor = reinterpret_cast<TileDescriptor&>(alias);
 
         } while (WARP_ANY((tile_descriptor.status == SCAN_TILE_INVALID), 0xffffffff));
 
         status      = tile_descriptor.status;
         value.value = tile_descriptor.value;
         value.key   = tile_descriptor.key;
     }
@@ -746,14 +811,15 @@
         }
 
         int         predecessor_idx = tile_idx - threadIdx.x - 1;
         StatusWord  predecessor_status;
         T           window_aggregate;
 
         // Wait for the warp-wide window of predecessor tiles to become valid
+        detail::delay<450>();
         ProcessWindow(predecessor_idx, predecessor_status, window_aggregate);
 
         // The exclusive tile prefix starts out as the current window aggregate
         exclusive_prefix = window_aggregate;
 
         // Keep sliding the window back until we come across a tile whose inclusive prefix is known
         while (WARP_ALL((predecessor_status != StatusWord(SCAN_TILE_INCLUSIVE)), 0xffffffff))
```

## nvidia/cuda_cccl/include/cub/block/block_exchange.cuh

 * *Ordering differences only*

```diff
@@ -728,16 +728,16 @@
     /**
      * \brief Collective constructor using a private static allocation of shared memory as temporary storage.
      */
     __device__ __forceinline__ BlockExchange()
     :
         temp_storage(PrivateStorage()),
         linear_tid(RowMajorTid(BLOCK_DIM_X, BLOCK_DIM_Y, BLOCK_DIM_Z)),
-        warp_id((WARPS == 1) ? 0 : linear_tid / WARP_THREADS),
         lane_id(LaneId()),
+        warp_id((WARPS == 1) ? 0 : linear_tid / WARP_THREADS),
         warp_offset(warp_id * WARP_TIME_SLICED_ITEMS)
     {}
 
 
     /**
      * \brief Collective constructor using the specified memory allocation as temporary storage.
      */
```

## nvidia/cuda_cccl/include/cub/block/block_merge_sort.cuh

```diff
@@ -403,15 +403,14 @@
     {
       StableOddEvenSort(keys, items, compare_op);
     }
 
     // each thread has sorted keys
     // merge sort keys in shared memory
     //
-    #pragma unroll
     for (int target_merged_threads_number = 2;
          target_merged_threads_number <= NUM_THREADS;
          target_merged_threads_number *= 2)
     {
       int merged_threads_number = target_merged_threads_number / 2;
       int mask = target_merged_threads_number - 1;
```

## nvidia/cuda_cccl/include/cub/block/block_radix_rank.cuh

```diff
@@ -88,14 +88,43 @@
 template <int BINS_PER_THREAD>
 struct BlockRadixRankEmptyCallback
 {
     __device__ __forceinline__ void operator()(int (&bins)[BINS_PER_THREAD]) {}
 };
 
 
+namespace detail
+{
+
+template <int Bits, int PartialWarpThreads, int PartialWarpId>
+struct warp_in_block_matcher_t
+{
+  static __device__ unsigned int match_any(unsigned int label, unsigned int warp_id)
+  {
+    if (warp_id == static_cast<unsigned int>(PartialWarpId)) 
+    {
+      return MatchAny<Bits, PartialWarpThreads>(label);
+    }
+
+    return MatchAny<Bits>(label);
+  }
+};
+
+template <int Bits, int PartialWarpId>
+struct warp_in_block_matcher_t<Bits, 0, PartialWarpId>
+{
+  static __device__ unsigned int match_any(unsigned int label, unsigned int warp_id)
+  {
+    return MatchAny<Bits>(label);
+  }
+};
+
+} // namespace detail
+
+
 /**
  * \brief BlockRadixRank provides operations for ranking unsigned integer types within a CUDA thread block.
  * \ingroup BlockModule
  *
  * \tparam BLOCK_DIM_X          The thread block length in threads along the X dimension
  * \tparam RADIX_BITS           The number of radix bits per digit place
  * \tparam IS_DESCENDING           Whether or not the sorted-order is high-to-low
@@ -110,25 +139,42 @@
  * Blah...
  * - Keys must be in a form suitable for radix ranking (i.e., unsigned bits).
  * - \blocked
  *
  * \par Performance Considerations
  * - \granularity
  *
- * \par Examples
  * \par
- * - <b>Example 1:</b> Simple radix rank of 32-bit integer keys
- *      \code
- *      #include <cub/cub.cuh>
+ * \code
+ * #include <cub/cub.cuh>
+ *
+ * __global__ void ExampleKernel(...)
+ * {
+ *   constexpr int block_threads = 2;
+ *   constexpr int radix_bits = 5;
+ *
+ *   // Specialize BlockRadixRank for a 1D block of 2 threads 
+ *   using block_radix_rank = cub::BlockRadixRank<block_threads, radix_bits>;
+ *   using storage_t = typename block_radix_rank::TempStorage;
+ *
+ *   // Allocate shared memory for BlockRadixSort
+ *   __shared__ storage_t temp_storage;
+ *
+ *   // Obtain a segment of consecutive items that are blocked across threads
+ *   int keys[2];
+ *   int ranks[2];
+ *   ...
  *
- *      template <int BLOCK_THREADS>
- *      __global__ void ExampleKernel(...)
- *      {
+ *   cub::BFEDigitExtractor<int> extractor(0, radix_bits);
+ *   block_radix_rank(temp_storage).RankKeys(keys, ranks, extractor);
  *
- *      \endcode
+ *   ...
+ * \endcode
+ * Suppose the set of input `keys` across the block of threads is `{ [16,10], [9,11] }`.  
+ * The corresponding output `ranks` in those threads will be `{ [3,1], [0,2] }`.
  *
  * \par Re-using dynamically allocating shared memory
  * The following example under the examples/block folder illustrates usage of
  * dynamically shared memory with BlockReduce and how to re-purpose
  * the same memory region:
  * <a href="../../examples/block/example_block_reduce_dyn_smem.cu">example_block_reduce_dyn_smem.cu</a>
  *
@@ -524,14 +570,15 @@
         // The thread block size in threads
         BLOCK_THREADS               = BLOCK_DIM_X * BLOCK_DIM_Y * BLOCK_DIM_Z,
 
         RADIX_DIGITS                = 1 << RADIX_BITS,
 
         LOG_WARP_THREADS            = CUB_LOG_WARP_THREADS(0),
         WARP_THREADS                = 1 << LOG_WARP_THREADS,
+        PARTIAL_WARP_THREADS        = BLOCK_THREADS % WARP_THREADS,
         WARPS                       = (BLOCK_THREADS + WARP_THREADS - 1) / WARP_THREADS,
 
         PADDED_WARPS            = ((WARPS & 0x1) == 0) ?
                                     WARPS + 1 :
                                     WARPS,
 
         COUNTERS                = PADDED_WARPS * RADIX_DIGITS,
@@ -694,15 +741,19 @@
             // My digit
             uint32_t digit = digit_extractor.Digit(keys[ITEM]);
 
             if (IS_DESCENDING)
                 digit = RADIX_DIGITS - digit - 1;
 
             // Mask of peers who have same digit as me
-            uint32_t peer_mask = MatchAny<RADIX_BITS>(digit);
+            uint32_t peer_mask =
+              detail::warp_in_block_matcher_t<
+                RADIX_BITS, 
+                PARTIAL_WARP_THREADS, 
+                WARPS - 1>::match_any(digit, warp_id);
 
             // Pointer to smem digit counter for this key
             digit_counters[ITEM] = &temp_storage.aliasable.warp_digit_counters[digit][warp_id];
 
             // Number of occurrences in previous strips
             DigitCounterT warp_digit_prefix = *digit_counters[ITEM];
 
@@ -840,15 +891,17 @@
     {
         BLOCK_THREADS = BLOCK_DIM_X,
         RADIX_DIGITS = 1 << RADIX_BITS,
         BINS_PER_THREAD = (RADIX_DIGITS + BLOCK_THREADS - 1) / BLOCK_THREADS,
         BINS_TRACKED_PER_THREAD = BINS_PER_THREAD,
         FULL_BINS = BINS_PER_THREAD * BLOCK_THREADS == RADIX_DIGITS,
         WARP_THREADS = CUB_PTX_WARP_THREADS,
+        PARTIAL_WARP_THREADS = BLOCK_THREADS % WARP_THREADS,
         BLOCK_WARPS = BLOCK_THREADS / WARP_THREADS,
+        PARTIAL_WARP_ID = BLOCK_WARPS - 1,
         WARP_MASK = ~0,
         NUM_MATCH_MASKS = MATCH_ALGORITHM == WARP_MATCH_ATOMIC_OR ? BLOCK_WARPS : 0,
         // Guard against declaring zero-sized array:
         MATCH_MASKS_ALLOC_SIZE = NUM_MATCH_MASKS < 1 ? 1 : NUM_MATCH_MASKS,
     };
 
     // types
@@ -1018,15 +1071,15 @@
                 int warp_offset = 0;
                 int popc = __popc(bin_mask & LaneMaskLe());
                 if (lane == leader)
                 {
                     // atomic is a bit faster
                     warp_offset = atomicAdd(&warp_offsets[bin], popc);
                 }
-                warp_offset = SHFL_IDX_SYNC(warp_offset, leader, bin_mask);
+                warp_offset = SHFL_IDX_SYNC(warp_offset, leader, WARP_MASK);
                 if (lane == leader) *p_match_mask = 0;
                 WARP_SYNC(WARP_MASK);
                 ranks[u] = warp_offset + popc - 1;
             }
         }
 
         __device__ __forceinline__
@@ -1036,24 +1089,27 @@
         {
             // compute key ranks
             int* warp_offsets = &s.warp_offsets[warp][0];
             #pragma unroll
             for (int u = 0; u < KEYS_PER_THREAD; ++u)
             {
                 int bin = Digit(keys[u]);
-                int bin_mask = MatchAny<RADIX_BITS>(bin);
+                int bin_mask = detail::warp_in_block_matcher_t<RADIX_BITS,
+                                                               PARTIAL_WARP_THREADS,
+                                                               BLOCK_WARPS - 1>::match_any(bin,
+                                                                                           warp);
                 int leader = (WARP_THREADS - 1) - __clz(bin_mask);
                 int warp_offset = 0;
                 int popc = __popc(bin_mask & LaneMaskLe());
                 if (lane == leader)
                 {
                     // atomic is a bit faster
                     warp_offset = atomicAdd(&warp_offsets[bin], popc);
                 }
-                warp_offset = SHFL_IDX_SYNC(warp_offset, leader, bin_mask);
+                warp_offset = SHFL_IDX_SYNC(warp_offset, leader, WARP_MASK);
                 ranks[u] = warp_offset + popc - 1;
             }
         }
 
         __device__ __forceinline__ void RankKeys(
             UnsignedBits (&keys)[KEYS_PER_THREAD],
             int (&ranks)[KEYS_PER_THREAD],
@@ -1121,10 +1177,51 @@
     {
         int exclusive_digit_prefix[BINS_PER_THREAD];
         RankKeys(keys, ranks, digit_extractor, exclusive_digit_prefix);
     }
 };
 
 
+namespace detail 
+{
+
+// `BlockRadixRank` doesn't conform to the typical pattern, not exposing the algorithm 
+// template parameter. Other algorithms don't provide the same template parameters, not allowing 
+// multi-dimensional thread block specializations. 
+// 
+// TODO(senior-zero) for 3.0:
+// - Put existing implementations into the detail namespace
+// - Support multi-dimensional thread blocks in the rest of implementations
+// - Repurpose BlockRadixRank as an entry name with the algorithm template parameter
+template <RadixRankAlgorithm RankAlgorithm,
+          int BlockDimX,
+          int RadixBits,
+          bool IsDescending,
+          BlockScanAlgorithm ScanAlgorithm>
+using block_radix_rank_t = cub::detail::conditional_t<
+  RankAlgorithm == RADIX_RANK_BASIC,
+  BlockRadixRank<BlockDimX, RadixBits, IsDescending, false, ScanAlgorithm>,
+  cub::detail::conditional_t<
+    RankAlgorithm == RADIX_RANK_MEMOIZE,
+    BlockRadixRank<BlockDimX, RadixBits, IsDescending, true, ScanAlgorithm>,
+    cub::detail::conditional_t<
+      RankAlgorithm == RADIX_RANK_MATCH,
+      BlockRadixRankMatch<BlockDimX, RadixBits, IsDescending, ScanAlgorithm>,
+      cub::detail::conditional_t<
+        RankAlgorithm == RADIX_RANK_MATCH_EARLY_COUNTS_ANY,
+        BlockRadixRankMatchEarlyCounts<BlockDimX,
+                                       RadixBits,
+                                       IsDescending,
+                                       ScanAlgorithm,
+                                       WARP_MATCH_ANY>,
+        BlockRadixRankMatchEarlyCounts<BlockDimX,
+                                       RadixBits,
+                                       IsDescending,
+                                       ScanAlgorithm,
+                                       WARP_MATCH_ATOMIC_OR>>>>>;
+
+} // namespace detail
+
+
 CUB_NAMESPACE_END
```

## nvidia/cuda_cccl/include/cub/block/block_shuffle.cuh

```diff
@@ -186,15 +186,15 @@
         T&  output,                 ///< [out] The \p input item from thread <em>thread</em><sub>(<em>i</em>+<tt>distance></tt>)%<tt>BLOCK_THREADS</tt></sub> (may be aliased to \p input).  This value is not updated for <em>thread</em><sub>BLOCK_THREADS-1</sub>
         unsigned int distance = 1)  ///< [in] Offset distance (0 < \p distance < <tt>BLOCK_THREADS</tt>)
     {
         temp_storage[linear_tid] = input;
 
         CTA_SYNC();
 
-        unsigned int offset = threadIdx.x + distance;
+        unsigned int offset = linear_tid + distance;
         if (offset >= BLOCK_THREADS)
             offset -= BLOCK_THREADS;
 
         output = temp_storage[offset];
     }
```

## nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking.cuh

```diff
@@ -47,17 +47,17 @@
  *
  * Supports non-commutative binary reduction operators.  Unlike commutative
  * reduction operators (e.g., addition), the application of a non-commutative
  * reduction operator (e.g, string concatenation) across a sequence of inputs must
  * honor the relative ordering of items and partial reductions when applying the
  * reduction operator.
  *
- * Compared to the implementation of BlockReduceRaking (which does not support
- * non-commutative operators), this implementation requires a few extra
- * rounds of inter-thread communication.
+ * Compared to the implementation of BlockReduceRakingCommutativeOnly (which
+ * does not support non-commutative operators), this implementation requires a
+ * few extra rounds of inter-thread communication.
  */
 template <
     typename    T,              ///< Data type being reduced
     int         BLOCK_DIM_X,    ///< The thread block length in threads along the X dimension
     int         BLOCK_DIM_Y,    ///< The thread block length in threads along the Y dimension
     int         BLOCK_DIM_Z,    ///< The thread block length in threads along the Z dimension
     int         LEGACY_PTX_ARCH = 0> ///< The PTX compute capability for which to to specialize this collective
```

## nvidia/cuda_cccl/include/cub/block/specializations/block_scan_raking.cuh

```diff
@@ -30,20 +30,22 @@
 /**
  * \file
  * cub::BlockScanRaking provides variants of raking-based parallel prefix scan across a CUDA thread block.
  */
 
 #pragma once
 
-#include "../../config.cuh"
-#include "../../util_ptx.cuh"
-#include "../../block/block_raking_layout.cuh"
-#include "../../thread/thread_reduce.cuh"
-#include "../../thread/thread_scan.cuh"
-#include "../../warp/warp_scan.cuh"
+#include <cub/config.cuh>
+
+#include <cub/block/block_raking_layout.cuh>
+#include <cub/detail/uninitialized_copy.cuh>
+#include <cub/thread/thread_reduce.cuh>
+#include <cub/thread/thread_scan.cuh>
+#include <cub/util_ptx.cuh>
+#include <cub/warp/warp_scan.cuh>
 
 CUB_NAMESPACE_BEGIN
 
 
 /**
  * \brief BlockScanRaking provides variants of raking-based parallel prefix scan across a CUDA thread block.
  */
@@ -252,15 +254,15 @@
             // Short-circuit directly to warp-synchronous scan
             WarpScan(temp_storage.warp_scan).ExclusiveScan(input, exclusive_output, scan_op);
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 // Raking upsweep reduction across shared partials
@@ -294,15 +296,15 @@
             // Short-circuit directly to warp-synchronous scan
             WarpScan(temp_storage.warp_scan).ExclusiveScan(input, output, initial_value, scan_op);
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 // Raking upsweep reduction across shared partials
@@ -337,15 +339,15 @@
             // Short-circuit directly to warp-synchronous scan
             WarpScan(temp_storage.warp_scan).ExclusiveScan(input, output, scan_op, block_aggregate);
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 // Raking upsweep reduction across shared partials
@@ -389,15 +391,15 @@
             // Short-circuit directly to warp-synchronous scan
             WarpScan(temp_storage.warp_scan).ExclusiveScan(input, output, initial_value, scan_op, block_aggregate);
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 // Raking upsweep reduction across shared partials
@@ -451,15 +453,15 @@
             if (linear_tid == 0)
                 output = block_prefix;
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 WarpScan warp_scan(temp_storage.warp_scan);
@@ -508,15 +510,15 @@
             // Short-circuit directly to warp-synchronous scan
             WarpScan(temp_storage.warp_scan).InclusiveScan(input, output, scan_op);
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 // Raking upsweep reduction across shared partials
@@ -551,15 +553,15 @@
             // Short-circuit directly to warp-synchronous scan
             WarpScan(temp_storage.warp_scan).InclusiveScan(input, output, scan_op, block_aggregate);
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 // Raking upsweep reduction across shared partials
@@ -613,15 +615,15 @@
             // Update prefix with exclusive warpscan partial
             output = scan_op(block_prefix, output);
         }
         else
         {
             // Place thread partial into shared memory raking grid
             T *placement_ptr = BlockRakingLayout::PlacementPtr(temp_storage.raking_grid, linear_tid);
-            *placement_ptr = input;
+            detail::uninitialized_copy(placement_ptr, input);
 
             CTA_SYNC();
 
             // Reduce parallelism down to just raking threads
             if (linear_tid < RAKING_THREADS)
             {
                 WarpScan warp_scan(temp_storage.warp_scan);
```

## nvidia/cuda_cccl/include/cub/detail/detect_cuda_runtime.cuh

```diff
@@ -40,17 +40,24 @@
 CUB_NAMESPACE_BEGIN
 namespace detail
 {
 
 #ifdef DOXYGEN_SHOULD_SKIP_THIS // Only parse this during doxygen passes:
 
 /**
+ * \def CUB_DISABLE_CDP
+ *
+ * If defined, support for device-side usage of CUB is disabled.
+ */
+#define CUB_DISABLE_CDP
+
+/**
  * \def CUB_RDC_ENABLED
  *
- * Defined if RDC is enabled.
+ * Defined if RDC is enabled and CUB_DISABLE_CDP is not defined.
  */
 #define CUB_RDC_ENABLED
 
 /**
  * \def CUB_RUNTIME_FUNCTION
  *
  * Execution space for functions that can use the CUDA runtime API (`__host__`
@@ -72,15 +79,15 @@
  */
 #define CUB_RUNTIME_ENABLED
 
 #else // Non-doxygen pass:
 
 #ifndef CUB_RUNTIME_FUNCTION
 
-#if defined(__CUDACC_RDC__)
+#if defined(__CUDACC_RDC__) && !defined(CUB_DISABLE_CDP)
 
 #define CUB_RDC_ENABLED
 #define CUB_RUNTIME_FUNCTION __host__ __device__
 
 #else // RDC disabled:
 
 #define CUB_RUNTIME_FUNCTION __host__
```

## nvidia/cuda_cccl/include/cub/detail/uninitialized_copy.cuh

```diff
@@ -33,14 +33,22 @@
 
 CUB_NAMESPACE_BEGIN
 
 
 namespace detail
 {
 
+#if defined(_NVHPC_CUDA)
+template <typename T, typename U>
+__host__ __device__ void uninitialized_copy(T *ptr, U &&val)
+{
+  // NVBug 3384810
+  new (ptr) T(::cuda::std::forward<U>(val));
+}
+#else
 template <typename T,
           typename U,
           typename ::cuda::std::enable_if<
             ::cuda::std::is_trivially_copyable<T>::value, 
             int
           >::type = 0>
 __host__ __device__ void uninitialized_copy(T *ptr, U &&val)
@@ -54,13 +62,14 @@
            !::cuda::std::is_trivially_copyable<T>::value,
            int
          >::type = 0>
 __host__ __device__ void uninitialized_copy(T *ptr, U &&val)
 {
   new (ptr) T(::cuda::std::forward<U>(val));
 }
+#endif
 
 } // namespace detail
 
 
 CUB_NAMESPACE_END
```

## nvidia/cuda_cccl/include/cub/device/device_merge_sort.cuh

```diff
@@ -990,10 +990,129 @@
     return StableSortKeys<KeyIteratorT, OffsetT, CompareOpT>(d_temp_storage,
                                                              temp_storage_bytes,
                                                              d_keys,
                                                              num_items,
                                                              compare_op,
                                                              stream);
   }
+
+  /**
+   * @brief Sorts items using a merge sorting method.
+   *
+   * @par
+   * - StableSortKeysCopy is stable: it preserves the relative ordering of equivalent
+   *   elements. That is, if `x` and `y` are elements such that `x` precedes `y`,
+   *   and if the two elements are equivalent (neither `x < y` nor `y < x`) then
+   *   a postcondition of stable_sort is that `x` still precedes `y`.
+   * - Input array d_input_keys is not modified
+   * - Note that the behavior is undefined if the input and output ranges overlap
+   *   in any way.
+   *
+   * @par Snippet
+   * The code snippet below illustrates the sorting of a device vector of `int`
+   * keys.
+   * \par
+   * \code
+   * #include <cub/cub.cuh>
+   * // or equivalently <cub/device/device_merge_sort.cuh>
+   *
+   * // Declare, allocate, and initialize device-accessible pointers for
+   * // sorting data
+   * int  num_items;       // e.g., 7
+   * int  *d_input_keys;   // e.g., [8, 6, 7, 5, 3, 0, 9]
+   * int  *d_output_keys;  // must hold at least num_items elements
+   * ...
+   *
+   * // Initialize comparator
+   * CustomOpT custom_op;
+   *
+   * // Determine temporary device storage requirements
+   * void *d_temp_storage = nullptr;
+   * std::size_t temp_storage_bytes = 0;
+   * cub::DeviceMergeSort::StableSortKeysCopy(
+   *   d_temp_storage, temp_storage_bytes,
+   *   d_input_keys, d_output_keys, num_items, custom_op);
+   *
+   * // Allocate temporary storage
+   * cudaMalloc(&d_temp_storage, temp_storage_bytes);
+   *
+   * // Run sorting operation
+   * cub::DeviceMergeSort::StableSortKeysCopy(
+   *   d_temp_storage, temp_storage_bytes,
+   *   d_input_keys, d_output_keys, num_items, custom_op);
+   *
+   * // d_output_keys   <-- [0, 3, 5, 6, 7, 8, 9]
+   * @endcode
+   *
+   * @tparam KeyInputIteratorT
+   *   is a model of [Random Access Iterator]. Its `value_type` is a model of
+   *   [LessThan Comparable]. This `value_type`'s ordering relation is a
+   *   *strict weak ordering* as defined in the [LessThan Comparable]
+   *   requirements.
+   *
+   * @tparam KeyIteratorT
+   *   is a model of [Random Access Iterator]. `KeyIteratorT` is mutable, and
+   *   its `value_type` is a model of [LessThan Comparable]. This `value_type`'s
+   *   ordering relation is a *strict weak ordering* as defined in
+   *   the [LessThan Comparable] requirements.
+   *
+   * @tparam OffsetT
+   *   is an integer type for global offsets.
+   *
+   * @tparam CompareOpT
+   *   is a type of callable object with the signature
+   *   `bool operator()(KeyT lhs, KeyT rhs)` that models
+   *   the [Strict Weak Ordering] concept.
+   *
+   * @param[in] d_temp_storage
+   *   Device-accessible allocation of temporary storage. When `nullptr`, the
+   *   required allocation size is written to `temp_storage_bytes` and no work
+   *   is done.
+   *
+   * @param[in,out] temp_storage_bytes
+   *   Reference to size in bytes of `d_temp_storage` allocation
+   *
+   * @param[in] d_input_keys
+   *   Pointer to the input sequence of unsorted input keys
+   *
+   * @param[out] d_output_keys
+   *   Pointer to the output sequence of sorted input keys
+   *
+   * @param[in] num_items
+   *   Number of elements in d_input_keys to sort
+   *
+   * @param[in] compare_op
+   *   Comparison function object which returns true if the first argument is
+   *   ordered before the second
+   *
+   * @param[in] stream
+   *   **[optional]** CUDA stream to launch kernels within. Default is
+   *   stream<sub>0</sub>.
+   *
+   * [Random Access Iterator]: https://en.cppreference.com/w/cpp/iterator/random_access_iterator
+   * [Strict Weak Ordering]: https://en.cppreference.com/w/cpp/concepts/strict_weak_order
+   * [LessThan Comparable]: https://en.cppreference.com/w/cpp/named_req/LessThanComparable
+   */
+  template <typename KeyInputIteratorT,
+            typename KeyIteratorT,
+            typename OffsetT,
+            typename CompareOpT>
+  CUB_RUNTIME_FUNCTION static cudaError_t
+  StableSortKeysCopy(void *d_temp_storage,
+                     std::size_t &temp_storage_bytes,
+                     KeyInputIteratorT d_input_keys,
+                     KeyIteratorT d_output_keys,
+                     OffsetT num_items,
+                     CompareOpT compare_op,
+                     cudaStream_t stream = 0)
+  {
+    return SortKeysCopy<KeyInputIteratorT, KeyIteratorT, OffsetT, CompareOpT>(d_temp_storage,
+                                                                              temp_storage_bytes,
+                                                                              d_input_keys,
+                                                                              d_output_keys,
+                                                                              num_items,
+                                                                              compare_op,
+                                                                              stream);
+  }
 };
 
 CUB_NAMESPACE_END
```

## nvidia/cuda_cccl/include/cub/device/device_reduce.cuh

```diff
@@ -34,14 +34,15 @@
 
 #pragma once
 
 #include <iterator>
 #include <limits>
 
 #include <cub/config.cuh>
+#include <cub/detail/choose_offset.cuh>
 #include <cub/device/dispatch/dispatch_reduce.cuh>
 #include <cub/device/dispatch/dispatch_reduce_by_key.cuh>
 #include <cub/iterator/arg_index_input_iterator.cuh>
 #include <cub/util_deprecated.cuh>
 
 CUB_NAMESPACE_BEGIN
 
@@ -154,14 +155,16 @@
    *   **[inferred]** Binary reduction functor type having member 
    *   `T operator()(const T &a, const T &b)`
    *
    * @tparam T                    
    *   **[inferred]** Data element type that is convertible to the `value` type 
    *   of `InputIteratorT`
    *
+   * @tparam NumItemsT **[inferred]** Type of num_items
+   *
    * @param[in] d_temp_storage 
    *   Device-accessible allocation of temporary storage. When `nullptr`, the 
    *   required allocation size is written to `temp_storage_bytes` and no work 
    *   is done.
    *
    * @param[in,out] temp_storage_bytes 
    *   Reference to size in bytes of `d_temp_storage` allocation
@@ -184,36 +187,37 @@
    * @param[in] stream  
    *   **[optional]** CUDA stream to launch kernels within.  
    *   Default is stream<sub>0</sub>.
    */
   template <typename InputIteratorT,
             typename OutputIteratorT,
             typename ReductionOpT,
-            typename T>
+            typename T,
+            typename NumItemsT>
   CUB_RUNTIME_FUNCTION static cudaError_t Reduce(void *d_temp_storage,
                                                  size_t &temp_storage_bytes,
                                                  InputIteratorT d_in,
                                                  OutputIteratorT d_out,
-                                                 int num_items,
+                                                 NumItemsT num_items,
                                                  ReductionOpT reduction_op,
                                                  T init,
                                                  cudaStream_t stream = 0)
   {
     // Signed integer type for global offsets
-    using OffsetT = int;
+    using OffsetT = typename detail::ChooseOffsetT<NumItemsT>::Type;
 
     return DispatchReduce<InputIteratorT,
                           OutputIteratorT,
                           OffsetT,
                           ReductionOpT,
                           T>::Dispatch(d_temp_storage,
                                        temp_storage_bytes,
                                        d_in,
                                        d_out,
-                                       num_items,
+                                       static_cast<OffsetT>(num_items),
                                        reduction_op,
                                        init,
                                        stream);
   }
 
   template <typename InputIteratorT,
             typename OutputIteratorT,
@@ -299,14 +303,16 @@
    *   **[inferred]** Random-access input iterator type for reading input 
    *   items \iterator
    *
    * @tparam OutputIteratorT    
    *   **[inferred]** Output iterator type for recording the reduced 
    *   aggregate \iterator
    *
+   * @tparam NumItemsT **[inferred]** Type of num_items
+   *
    * @param[in] d_temp_storage  
    *   Device-accessible allocation of temporary storage. When `nullptr`, the 
    *   required allocation size is written to `temp_storage_bytes` and no work 
    *   is done.
    *
    * @param[in,out] temp_storage_bytes  
    *   Reference to size in bytes of `d_temp_storage` allocation
@@ -320,24 +326,26 @@
    * @param[in] num_items  
    *   Total number of input items (i.e., length of `d_in`)
    *
    * @param[in] stream  
    *   **[optional]** CUDA stream to launch kernels within.  
    *   Default is stream<sub>0</sub>.
    */
-  template <typename InputIteratorT, typename OutputIteratorT>
+  template <typename InputIteratorT, 
+            typename OutputIteratorT, 
+            typename NumItemsT>
   CUB_RUNTIME_FUNCTION static cudaError_t Sum(void *d_temp_storage,
                                               size_t &temp_storage_bytes,
                                               InputIteratorT d_in,
                                               OutputIteratorT d_out,
-                                              int num_items,
-                                              cudaStream_t stream    = 0)
+                                              NumItemsT num_items,
+                                              cudaStream_t stream = 0)
   {
     // Signed integer type for global offsets
-    using OffsetT = int;
+    using OffsetT = typename detail::ChooseOffsetT<NumItemsT>::Type;
 
     // The output value type
     using OutputT =
       cub::detail::non_void_value_t<OutputIteratorT,
                                     cub::detail::value_t<InputIteratorT>>;
 
     using InitT = OutputT; 
@@ -346,15 +354,15 @@
                           OutputIteratorT,  
                           OffsetT, 
                           cub::Sum, 
                           InitT>::Dispatch(d_temp_storage,
                                            temp_storage_bytes,
                                            d_in,
                                            d_out,
-                                           num_items,
+                                           static_cast<OffsetT>(num_items),
                                            cub::Sum(),
                                            InitT{}, // zero-initialize
                                            stream);
   }
 
   template <typename InputIteratorT, typename OutputIteratorT>
   CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED
@@ -425,14 +433,16 @@
    *   **[inferred]** Random-access input iterator type for reading input 
    *   items \iterator
    *
    * @tparam OutputIteratorT    
    *   **[inferred]** Output iterator type for recording the reduced 
    *   aggregate \iterator
    *
+   * @tparam NumItemsT **[inferred]** Type of num_items
+   *
    * @param[in] d_temp_storage  
    *   Device-accessible allocation of temporary storage. When `nullptr`, the 
    *   required allocation size is written to `temp_storage_bytes` and no work 
    *   is done.
    *
    * @param[in,out] temp_storage_bytes  
    *   Reference to size in bytes of `d_temp_storage` allocation
@@ -446,39 +456,41 @@
    * @param[in] num_items  
    *   Total number of input items (i.e., length of `d_in`)
    *
    * @param[in] stream  
    *   **[optional]** CUDA stream to launch kernels within.  
    *   Default is stream<sub>0</sub>.
    */
-  template <typename InputIteratorT, typename OutputIteratorT>
+  template <typename InputIteratorT,
+            typename OutputIteratorT,
+            typename NumItemsT>
   CUB_RUNTIME_FUNCTION static cudaError_t Min(void *d_temp_storage,
                                               size_t &temp_storage_bytes,
                                               InputIteratorT d_in,
                                               OutputIteratorT d_out,
-                                              int num_items,
+                                              NumItemsT num_items,
                                               cudaStream_t stream = 0)
   {
     // Signed integer type for global offsets
-    using OffsetT = int;
+    using OffsetT = typename detail::ChooseOffsetT<NumItemsT>::Type;
 
     // The input value type
     using InputT = cub::detail::value_t<InputIteratorT>;
 
     using InitT = InputT;
 
     return DispatchReduce<InputIteratorT,   
                           OutputIteratorT,  
                           OffsetT, 
                           cub::Min,
                           InitT>::Dispatch(d_temp_storage,
                                            temp_storage_bytes,
                                            d_in,
                                            d_out,
-                                           num_items,
+                                           static_cast<OffsetT>(num_items),
                                            cub::Min(),
                                            // replace with 
                                            // std::numeric_limits<T>::max() when
                                            // C++11 support is more prevalent
                                            Traits<InitT>::Max(), 
                                            stream);
   }
@@ -579,15 +591,16 @@
    * @param[in] num_items  
    *   Total number of input items (i.e., length of `d_in`)
    *
    * @param[in] stream  
    *   **[optional]** CUDA stream to launch kernels within.  
    *   Default is stream<sub>0</sub>.
    */
-  template <typename InputIteratorT, typename OutputIteratorT>
+  template <typename InputIteratorT, 
+            typename OutputIteratorT>
   CUB_RUNTIME_FUNCTION static cudaError_t ArgMin(void *d_temp_storage,
                                                  size_t &temp_storage_bytes,
                                                  InputIteratorT d_in,
                                                  OutputIteratorT d_out,
                                                  int num_items,
                                                  cudaStream_t stream = 0)
   {
@@ -703,14 +716,16 @@
    *   **[inferred]** Random-access input iterator type for reading input 
    *   items \iterator
    *
    * @tparam OutputIteratorT    
    *   **[inferred]** Output iterator type for recording the reduced 
    *   aggregate \iterator
    *
+   * @tparam NumItemsT **[inferred]** Type of num_items
+   *
    * @param[in] d_temp_storage  
    *   Device-accessible allocation of temporary storage. When `nullptr`, the 
    *   required allocation size is written to `temp_storage_bytes` and no work 
    *   is done.
    *
    * @param[in,out] temp_storage_bytes  
    *   Reference to size in bytes of `d_temp_storage` allocation
@@ -724,39 +739,41 @@
    * @param[in] num_items  
    *   Total number of input items (i.e., length of `d_in`)
    *
    * @param[in] stream  
    *   **[optional]** CUDA stream to launch kernels within. 
    *   Default is stream<sub>0</sub>.
    */
-  template <typename InputIteratorT, typename OutputIteratorT>
+  template <typename InputIteratorT, 
+            typename OutputIteratorT,
+            typename NumItemsT>
   CUB_RUNTIME_FUNCTION static cudaError_t Max(void *d_temp_storage,
                                               size_t &temp_storage_bytes,
                                               InputIteratorT d_in,
                                               OutputIteratorT d_out,
-                                              int num_items,
+                                              NumItemsT num_items,
                                               cudaStream_t stream = 0)
   {
     // Signed integer type for global offsets
-    using OffsetT = int;
+    using OffsetT = typename detail::ChooseOffsetT<NumItemsT>::Type;
 
     // The input value type
     using InputT = cub::detail::value_t<InputIteratorT>;
 
     using InitT = InputT;
 
     return DispatchReduce<InputIteratorT,   
                           OutputIteratorT,  
                           OffsetT, 
                           cub::Max,
                           InitT>::Dispatch(d_temp_storage,
                                            temp_storage_bytes,
                                            d_in,
                                            d_out,
-                                           num_items,
+                                           static_cast<OffsetT>(num_items),
                                            cub::Max(),
                                            // replace with 
                                            // std::numeric_limits<T>::lowest()
                                            // when C++11 support is more 
                                            // prevalent
                                            Traits<InitT>::Lowest(), 
                                            stream);
@@ -859,15 +876,16 @@
    * @param[in] num_items  
    *   Total number of input items (i.e., length of `d_in`)
    *
    * @param[in] stream  
    *   **[optional]** CUDA stream to launch kernels within.  
    *   Default is stream<sub>0</sub>.
    */
-  template <typename InputIteratorT, typename OutputIteratorT>
+  template <typename InputIteratorT, 
+            typename OutputIteratorT>
   CUB_RUNTIME_FUNCTION static cudaError_t ArgMax(void *d_temp_storage,
                                                  size_t &temp_storage_bytes,
                                                  InputIteratorT d_in,
                                                  OutputIteratorT d_out,
                                                  int num_items,
                                                  cudaStream_t stream = 0)
   {
@@ -1050,14 +1068,16 @@
    *   **[inferred]** Output iterator type for recording the number of runs 
    *   encountered \iterator
    *
    * @tparam ReductionOpT              
    *   **[inferred]*8 Binary reduction functor type having member 
    *   `T operator()(const T &a, const T &b)`
    *
+   * @tparam NumItemsT **[inferred]** Type of num_items
+   *
    * @param[in] d_temp_storage  
    *   Device-accessible allocation of temporary storage. When `nullptr`, the 
    *   required allocation size is written to `temp_storage_bytes` and no work 
    *   is done.
    *
    * @param[in,out] temp_storage_bytes  
    *   Reference to size in bytes of `d_temp_storage` allocation
@@ -1091,29 +1111,30 @@
    *   Default is stream<sub>0</sub>.
    */
   template <typename KeysInputIteratorT,
             typename UniqueOutputIteratorT,
             typename ValuesInputIteratorT,
             typename AggregatesOutputIteratorT,
             typename NumRunsOutputIteratorT,
-            typename ReductionOpT>
+            typename ReductionOpT,
+            typename NumItemsT>
   CUB_RUNTIME_FUNCTION __forceinline__ static cudaError_t
   ReduceByKey(void *d_temp_storage,
               size_t &temp_storage_bytes,
               KeysInputIteratorT d_keys_in,
               UniqueOutputIteratorT d_unique_out,
               ValuesInputIteratorT d_values_in,
               AggregatesOutputIteratorT d_aggregates_out,
               NumRunsOutputIteratorT d_num_runs_out,
               ReductionOpT reduction_op,
-              int num_items,
+              NumItemsT num_items,
               cudaStream_t stream = 0)
   {
     // Signed integer type for global offsets
-    using OffsetT = int;
+    using OffsetT = typename detail::ChooseOffsetT<NumItemsT>::Type;
 
     // FlagT iterator type (not used)
 
     // Selection op (not used)
 
     // Default == operator
     typedef Equality EqualityOp;
@@ -1130,15 +1151,15 @@
                                                   d_keys_in,
                                                   d_unique_out,
                                                   d_values_in,
                                                   d_aggregates_out,
                                                   d_num_runs_out,
                                                   EqualityOp(),
                                                   reduction_op,
-                                                  num_items,
+                                                  static_cast<OffsetT>(num_items),
                                                   stream);
   }
 
   template <typename KeysInputIteratorT,
             typename UniqueOutputIteratorT,
             typename ValuesInputIteratorT,
             typename AggregatesOutputIteratorT,
```

### html2text {}

```diff
@@ -21,14 +21,15 @@
 NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS * SOFTWARE,
 EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. *
 ******************************************************************************/
 /** * @file cub::DeviceReduce provides device-wide, parallel operations for *
 computing a reduction across a sequence of data items residing within * device-
 accessible memory. */ #pragma once #include  #include  #include
 onfig.cuh> #include
+etail/choose_offset.cuh> #include
 evice/dispatch/dispatch_reduce.cuh> #include
 evice/dispatch/dispatch_reduce_by_key.cuh> #include
 terator/arg_index_input_iterator.cuh> #include
 til_deprecated.cuh> CUB_NAMESPACE_BEGIN /** * @brief DeviceReduce provides
 device-wide, parallel operations for computing * a reduction across a sequence
 of data items residing within * device-accessible memory. ![](reduce_logo.png)
 * @ingroup SingleModule * * @par Overview * A *reduction* * (or *fold*) uses a
@@ -68,32 +69,34 @@
 d_temp_storage, temp_storage_bytes, * d_in, d_out, num_items, min_op, init); *
 * // d_out <-- [0] * @endcode * * @tparam InputIteratorT * **[inferred]**
 Random-access input iterator type for reading input * items \iterator * *
 @tparam OutputIteratorT * **[inferred]** Output iterator type for recording the
 reduced * aggregate \iterator * * @tparam ReductionOpT * **[inferred]** Binary
 reduction functor type having member * `T operator()(const T &a, const T &b)` *
 * @tparam T * **[inferred]** Data element type that is convertible to the
-`value` type * of `InputIteratorT` * * @param[in] d_temp_storage * Device-
-accessible allocation of temporary storage. When `nullptr`, the * required
-allocation size is written to `temp_storage_bytes` and no work * is done. * *
-@param[in,out] temp_storage_bytes * Reference to size in bytes of
-`d_temp_storage` allocation * * @param d_in[in] * Pointer to the input sequence
-of data items * * @param d_out[out] * Pointer to the output aggregate * *
-@param num_items[in] * Total number of input items (i.e., length of `d_in`) * *
-@param reduction_op[in] * Binary reduction functor * * @param[in] init *
-Initial value of the reduction * * @param[in] stream * **[optional]** CUDA
-stream to launch kernels within. * Default is stream0. */ template
- typename OutputIteratorT, typename ReductionOpT, typename T>
-CUB_RUNTIME_FUNCTION static cudaError_t Reduce(void *d_temp_storage, size_t
-&temp_storage_bytes, InputIteratorT d_in, OutputIteratorT d_out, int num_items,
-ReductionOpT reduction_op, T init, cudaStream_t stream = 0) { // Signed integer
-type for global offsets using OffsetT = int; return DispatchReduce
+`value` type * of `InputIteratorT` * * @tparam NumItemsT **[inferred]** Type of
+num_items * * @param[in] d_temp_storage * Device-accessible allocation of
+temporary storage. When `nullptr`, the * required allocation size is written to
+`temp_storage_bytes` and no work * is done. * * @param[in,out]
+temp_storage_bytes * Reference to size in bytes of `d_temp_storage` allocation
+* * @param d_in[in] * Pointer to the input sequence of data items * * @param
+d_out[out] * Pointer to the output aggregate * * @param num_items[in] * Total
+number of input items (i.e., length of `d_in`) * * @param reduction_op[in] *
+Binary reduction functor * * @param[in] init * Initial value of the reduction *
+* @param[in] stream * **[optional]** CUDA stream to launch kernels within. *
+Default is stream0. */ template
+ typename OutputIteratorT, typename ReductionOpT, typename T, typename
+NumItemsT> CUB_RUNTIME_FUNCTION static cudaError_t Reduce(void *d_temp_storage,
+size_t &temp_storage_bytes, InputIteratorT d_in, OutputIteratorT d_out,
+NumItemsT num_items, ReductionOpT reduction_op, T init, cudaStream_t stream =
+0) { // Signed integer type for global offsets using OffsetT = typename
+detail::ChooseOffsetT::Type; return DispatchReduce
  OutputIteratorT, OffsetT, ReductionOpT, T>::Dispatch(d_temp_storage,
-temp_storage_bytes, d_in, d_out, num_items, reduction_op, init, stream); }
-template
+temp_storage_bytes, d_in, d_out, static_cast(num_items), reduction_op, init,
+stream); } template
  typename OutputIteratorT, typename ReductionOpT, typename T>
 CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED CUB_RUNTIME_FUNCTION static
 cudaError_t Reduce(void *d_temp_storage, size_t &temp_storage_bytes,
 InputIteratorT d_in, OutputIteratorT d_out, int num_items, ReductionOpT
 reduction_op, T init, cudaStream_t stream, bool debug_synchronous)
 { CUB_DETAIL_RUNTIME_DEBUG_SYNC_USAGE_LOG return Reduce
  OutputIteratorT, ReductionOpT, T>( d_temp_storage, temp_storage_bytes, d_in,
@@ -120,32 +123,34 @@
 NULL; * size_t temp_storage_bytes = 0; * cub::DeviceReduce::Sum( *
 d_temp_storage, temp_storage_bytes, d_in, d_out, num_items); * * // Allocate
 temporary storage * cudaMalloc(&d_temp_storage, temp_storage_bytes); * * // Run
 sum-reduction * cub::DeviceReduce::Sum( * d_temp_storage, temp_storage_bytes,
 d_in, d_out, num_items); * * // d_out <-- [38] * @endcode * * @tparam
 InputIteratorT * **[inferred]** Random-access input iterator type for reading
 input * items \iterator * * @tparam OutputIteratorT * **[inferred]** Output
-iterator type for recording the reduced * aggregate \iterator * * @param[in]
-d_temp_storage * Device-accessible allocation of temporary storage. When
-`nullptr`, the * required allocation size is written to `temp_storage_bytes`
-and no work * is done. * * @param[in,out] temp_storage_bytes * Reference to
-size in bytes of `d_temp_storage` allocation * * @param[in] d_in * Pointer to
-the input sequence of data items * * @param[out] d_out * Pointer to the output
-aggregate * * @param[in] num_items * Total number of input items (i.e., length
-of `d_in`) * * @param[in] stream * **[optional]** CUDA stream to launch kernels
-within. * Default is stream0. */ template
- typename OutputIteratorT> CUB_RUNTIME_FUNCTION static cudaError_t Sum(void
-*d_temp_storage, size_t &temp_storage_bytes, InputIteratorT d_in,
-OutputIteratorT d_out, int num_items, cudaStream_t stream = 0) { // Signed
-integer type for global offsets using OffsetT = int; // The output value type
-using OutputT = cub::detail::non_void_value_t
+iterator type for recording the reduced * aggregate \iterator * * @tparam
+NumItemsT **[inferred]** Type of num_items * * @param[in] d_temp_storage *
+Device-accessible allocation of temporary storage. When `nullptr`, the *
+required allocation size is written to `temp_storage_bytes` and no work * is
+done. * * @param[in,out] temp_storage_bytes * Reference to size in bytes of
+`d_temp_storage` allocation * * @param[in] d_in * Pointer to the input sequence
+of data items * * @param[out] d_out * Pointer to the output aggregate * *
+@param[in] num_items * Total number of input items (i.e., length of `d_in`) * *
+@param[in] stream * **[optional]** CUDA stream to launch kernels within. *
+Default is stream0. */ template
+ typename OutputIteratorT, typename NumItemsT> CUB_RUNTIME_FUNCTION static
+cudaError_t Sum(void *d_temp_storage, size_t &temp_storage_bytes,
+InputIteratorT d_in, OutputIteratorT d_out, NumItemsT num_items, cudaStream_t
+stream = 0) { // Signed integer type for global offsets using OffsetT =
+typename detail::ChooseOffsetT::Type; // The output value type using OutputT =
+cub::detail::non_void_value_t
  cub::detail::value_t>; using InitT = OutputT; return DispatchReduce
  OutputIteratorT, OffsetT, cub::Sum, InitT>::Dispatch(d_temp_storage,
-temp_storage_bytes, d_in, d_out, num_items, cub::Sum(), InitT{}, // zero-
-initialize stream); } template
+temp_storage_bytes, d_in, d_out, static_cast(num_items), cub::Sum(), InitT{}, /
+/ zero-initialize stream); } template
  typename OutputIteratorT> CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED
 CUB_RUNTIME_FUNCTION static cudaError_t Sum(void *d_temp_storage, size_t
 &temp_storage_bytes, InputIteratorT d_in, OutputIteratorT d_out, int num_items,
 cudaStream_t stream, bool debug_synchronous)
 { CUB_DETAIL_RUNTIME_DEBUG_SYNC_USAGE_LOG return Sum
  OutputIteratorT>(d_temp_storage, temp_storage_bytes, d_in, d_out, num_items,
 stream); } /** * @brief Computes a device-wide minimum using the less-than
@@ -167,33 +172,34 @@
 NULL; * size_t temp_storage_bytes = 0; * cub::DeviceReduce::Min( *
 d_temp_storage, temp_storage_bytes, d_in, d_out, num_items); * * // Allocate
 temporary storage * cudaMalloc(&d_temp_storage, temp_storage_bytes); * * // Run
 min-reduction * cub::DeviceReduce::Min( * d_temp_storage, temp_storage_bytes,
 d_in, d_out, num_items); * * // d_out <-- [0] * @endcode * * @tparam
 InputIteratorT * **[inferred]** Random-access input iterator type for reading
 input * items \iterator * * @tparam OutputIteratorT * **[inferred]** Output
-iterator type for recording the reduced * aggregate \iterator * * @param[in]
-d_temp_storage * Device-accessible allocation of temporary storage. When
-`nullptr`, the * required allocation size is written to `temp_storage_bytes`
-and no work * is done. * * @param[in,out] temp_storage_bytes * Reference to
-size in bytes of `d_temp_storage` allocation * * @param[in] d_in * Pointer to
-the input sequence of data items * * @param[out] d_out * Pointer to the output
-aggregate * * @param[in] num_items * Total number of input items (i.e., length
-of `d_in`) * * @param[in] stream * **[optional]** CUDA stream to launch kernels
-within. * Default is stream0. */ template
- typename OutputIteratorT> CUB_RUNTIME_FUNCTION static cudaError_t Min(void
-*d_temp_storage, size_t &temp_storage_bytes, InputIteratorT d_in,
-OutputIteratorT d_out, int num_items, cudaStream_t stream = 0) { // Signed
-integer type for global offsets using OffsetT = int; // The input value type
-using InputT = cub::detail::value_t; using InitT = InputT; return
-DispatchReduce
+iterator type for recording the reduced * aggregate \iterator * * @tparam
+NumItemsT **[inferred]** Type of num_items * * @param[in] d_temp_storage *
+Device-accessible allocation of temporary storage. When `nullptr`, the *
+required allocation size is written to `temp_storage_bytes` and no work * is
+done. * * @param[in,out] temp_storage_bytes * Reference to size in bytes of
+`d_temp_storage` allocation * * @param[in] d_in * Pointer to the input sequence
+of data items * * @param[out] d_out * Pointer to the output aggregate * *
+@param[in] num_items * Total number of input items (i.e., length of `d_in`) * *
+@param[in] stream * **[optional]** CUDA stream to launch kernels within. *
+Default is stream0. */ template
+ typename OutputIteratorT, typename NumItemsT> CUB_RUNTIME_FUNCTION static
+cudaError_t Min(void *d_temp_storage, size_t &temp_storage_bytes,
+InputIteratorT d_in, OutputIteratorT d_out, NumItemsT num_items, cudaStream_t
+stream = 0) { // Signed integer type for global offsets using OffsetT =
+typename detail::ChooseOffsetT::Type; // The input value type using InputT =
+cub::detail::value_t; using InitT = InputT; return DispatchReduce
  OutputIteratorT, OffsetT, cub::Min, InitT>::Dispatch(d_temp_storage,
-temp_storage_bytes, d_in, d_out, num_items, cub::Min(), // replace with /
-/ std::numeric_limits::max() when // C++11 support is more prevalent Traits::
-Max(), stream); } template
+temp_storage_bytes, d_in, d_out, static_cast(num_items), cub::Min(), // replace
+with // std::numeric_limits::max() when // C++11 support is more prevalent
+Traits::Max(), stream); } template
  typename OutputIteratorT> CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED
 CUB_RUNTIME_FUNCTION static cudaError_t Min(void *d_temp_storage, size_t
 &temp_storage_bytes, InputIteratorT d_in, OutputIteratorT d_out, int num_items,
 cudaStream_t stream, bool debug_synchronous)
 { CUB_DETAIL_RUNTIME_DEBUG_SYNC_USAGE_LOG return Min
  OutputIteratorT>(d_temp_storage, temp_storage_bytes, d_in, d_out, num_items,
 stream); } /** * @brief Finds the first device-wide minimum using the less-than
@@ -277,33 +283,34 @@
 NULL; * size_t temp_storage_bytes = 0; * cub::DeviceReduce::Max( *
 d_temp_storage, temp_storage_bytes, d_in, d_max, num_items); * * // Allocate
 temporary storage * cudaMalloc(&d_temp_storage, temp_storage_bytes); * * // Run
 max-reduction * cub::DeviceReduce::Max( * d_temp_storage, temp_storage_bytes,
 d_in, d_max, num_items); * * // d_out <-- [9] * @endcode * * @tparam
 InputIteratorT * **[inferred]** Random-access input iterator type for reading
 input * items \iterator * * @tparam OutputIteratorT * **[inferred]** Output
-iterator type for recording the reduced * aggregate \iterator * * @param[in]
-d_temp_storage * Device-accessible allocation of temporary storage. When
-`nullptr`, the * required allocation size is written to `temp_storage_bytes`
-and no work * is done. * * @param[in,out] temp_storage_bytes * Reference to
-size in bytes of `d_temp_storage` allocation * * @param[in] d_in * Pointer to
-the input sequence of data items * * @param[out] d_out * Pointer to the output
-aggregate * * @param[in] num_items * Total number of input items (i.e., length
-of `d_in`) * * @param[in] stream * **[optional]** CUDA stream to launch kernels
-within. * Default is stream0. */ template
- typename OutputIteratorT> CUB_RUNTIME_FUNCTION static cudaError_t Max(void
-*d_temp_storage, size_t &temp_storage_bytes, InputIteratorT d_in,
-OutputIteratorT d_out, int num_items, cudaStream_t stream = 0) { // Signed
-integer type for global offsets using OffsetT = int; // The input value type
-using InputT = cub::detail::value_t; using InitT = InputT; return
-DispatchReduce
+iterator type for recording the reduced * aggregate \iterator * * @tparam
+NumItemsT **[inferred]** Type of num_items * * @param[in] d_temp_storage *
+Device-accessible allocation of temporary storage. When `nullptr`, the *
+required allocation size is written to `temp_storage_bytes` and no work * is
+done. * * @param[in,out] temp_storage_bytes * Reference to size in bytes of
+`d_temp_storage` allocation * * @param[in] d_in * Pointer to the input sequence
+of data items * * @param[out] d_out * Pointer to the output aggregate * *
+@param[in] num_items * Total number of input items (i.e., length of `d_in`) * *
+@param[in] stream * **[optional]** CUDA stream to launch kernels within. *
+Default is stream0. */ template
+ typename OutputIteratorT, typename NumItemsT> CUB_RUNTIME_FUNCTION static
+cudaError_t Max(void *d_temp_storage, size_t &temp_storage_bytes,
+InputIteratorT d_in, OutputIteratorT d_out, NumItemsT num_items, cudaStream_t
+stream = 0) { // Signed integer type for global offsets using OffsetT =
+typename detail::ChooseOffsetT::Type; // The input value type using InputT =
+cub::detail::value_t; using InitT = InputT; return DispatchReduce
  OutputIteratorT, OffsetT, cub::Max, InitT>::Dispatch(d_temp_storage,
-temp_storage_bytes, d_in, d_out, num_items, cub::Max(), // replace with /
-/ std::numeric_limits::lowest() // when C++11 support is more // prevalent
-Traits::Lowest(), stream); } template
+temp_storage_bytes, d_in, d_out, static_cast(num_items), cub::Max(), // replace
+with // std::numeric_limits::lowest() // when C++11 support is more /
+/ prevalent Traits::Lowest(), stream); } template
  typename OutputIteratorT> CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED
 CUB_RUNTIME_FUNCTION static cudaError_t Max(void *d_temp_storage, size_t
 &temp_storage_bytes, InputIteratorT d_in, OutputIteratorT d_out, int num_items,
 cudaStream_t stream, bool debug_synchronous)
 { CUB_DETAIL_RUNTIME_DEBUG_SYNC_USAGE_LOG return Max
  OutputIteratorT>(d_temp_storage, temp_storage_bytes, d_in, d_out, num_items,
 stream); } /** * @brief Finds the first device-wide maximum using the greater-
@@ -422,45 +429,46 @@
 writing unique * output keys \iterator * * @tparam ValuesInputIteratorT * **
 [inferred]** Random-access input iterator type for reading input * values
 \iterator * * @tparam AggregatesOutputIterator * **[inferred]** Random-access
 output iterator type for writing output * value aggregates \iterator * *
 @tparam NumRunsOutputIteratorT * **[inferred]** Output iterator type for
 recording the number of runs * encountered \iterator * * @tparam ReductionOpT *
 **[inferred]*8 Binary reduction functor type having member * `T operator()
-(const T &a, const T &b)` * * @param[in] d_temp_storage * Device-accessible
-allocation of temporary storage. When `nullptr`, the * required allocation size
-is written to `temp_storage_bytes` and no work * is done. * * @param[in,out]
+(const T &a, const T &b)` * * @tparam NumItemsT **[inferred]** Type of
+num_items * * @param[in] d_temp_storage * Device-accessible allocation of
+temporary storage. When `nullptr`, the * required allocation size is written to
+`temp_storage_bytes` and no work * is done. * * @param[in,out]
 temp_storage_bytes * Reference to size in bytes of `d_temp_storage` allocation
 * * @param[in] d_keys_in * Pointer to the input sequence of keys * * @param
 [out] d_unique_out * Pointer to the output sequence of unique keys (one key per
 run) * * @param[in] d_values_in * Pointer to the input sequence of
 corresponding values * * @param[out] d_aggregates_out * Pointer to the output
 sequence of value aggregates * (one aggregate per run) * * @param[out]
 d_num_runs_out * Pointer to total number of runs encountered * (i.e., the
 length of `d_unique_out`) * * @param[in] reduction_op * Binary reduction
 functor * * @param[in] num_items * Total number of associated key+value pairs *
 (i.e., the length of `d_in_keys` and `d_in_values`) * * @param[in] stream * **
 [optional]** CUDA stream to launch kernels within. * Default is stream0. */
 template
  typename UniqueOutputIteratorT, typename ValuesInputIteratorT, typename
 AggregatesOutputIteratorT, typename NumRunsOutputIteratorT, typename
-ReductionOpT> CUB_RUNTIME_FUNCTION __forceinline__ static cudaError_t
-ReduceByKey(void *d_temp_storage, size_t &temp_storage_bytes,
+ReductionOpT, typename NumItemsT> CUB_RUNTIME_FUNCTION __forceinline__ static
+cudaError_t ReduceByKey(void *d_temp_storage, size_t &temp_storage_bytes,
 KeysInputIteratorT d_keys_in, UniqueOutputIteratorT d_unique_out,
 ValuesInputIteratorT d_values_in, AggregatesOutputIteratorT d_aggregates_out,
-NumRunsOutputIteratorT d_num_runs_out, ReductionOpT reduction_op, int
+NumRunsOutputIteratorT d_num_runs_out, ReductionOpT reduction_op, NumItemsT
 num_items, cudaStream_t stream = 0) { // Signed integer type for global offsets
-using OffsetT = int; // FlagT iterator type (not used) // Selection op (not
-used) // Default == operator typedef Equality EqualityOp; return
-DispatchReduceByKey
+using OffsetT = typename detail::ChooseOffsetT::Type; // FlagT iterator type
+(not used) // Selection op (not used) // Default == operator typedef Equality
+EqualityOp; return DispatchReduceByKey
  UniqueOutputIteratorT, ValuesInputIteratorT, AggregatesOutputIteratorT,
 NumRunsOutputIteratorT, EqualityOp, ReductionOpT, OffsetT>::Dispatch
 (d_temp_storage, temp_storage_bytes, d_keys_in, d_unique_out, d_values_in,
-d_aggregates_out, d_num_runs_out, EqualityOp(), reduction_op, num_items,
-stream); } template
+d_aggregates_out, d_num_runs_out, EqualityOp(), reduction_op, static_cast
+(num_items), stream); } template
  typename UniqueOutputIteratorT, typename ValuesInputIteratorT, typename
 AggregatesOutputIteratorT, typename NumRunsOutputIteratorT, typename
 ReductionOpT> CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED
 CUB_RUNTIME_FUNCTION __forceinline__ static cudaError_t ReduceByKey(void
 *d_temp_storage, size_t &temp_storage_bytes, KeysInputIteratorT d_keys_in,
 UniqueOutputIteratorT d_unique_out, ValuesInputIteratorT d_values_in,
 AggregatesOutputIteratorT d_aggregates_out, NumRunsOutputIteratorT
```

## nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_radix_sort.cuh

```diff
@@ -948,19 +948,68 @@
         typedef AgentRadixSortDownsweepPolicy <256, 19, DominantT,  BLOCK_LOAD_DIRECT, LOAD_LDG, RADIX_RANK_MEMOIZE, BLOCK_SCAN_WARP_SCANS, SINGLE_TILE_RADIX_BITS>          SingleTilePolicy;
 
         // Segmented policies
         typedef AgentRadixSortDownsweepPolicy <192, 39, DominantT,  BLOCK_LOAD_TRANSPOSE, LOAD_DEFAULT, RADIX_RANK_MEMOIZE, BLOCK_SCAN_WARP_SCANS, SEGMENTED_RADIX_BITS>     SegmentedPolicy;
         typedef AgentRadixSortDownsweepPolicy <384, 11, DominantT,  BLOCK_LOAD_TRANSPOSE, LOAD_DEFAULT, RADIX_RANK_MEMOIZE, BLOCK_SCAN_WARP_SCANS, SEGMENTED_RADIX_BITS - 1> AltSegmentedPolicy;
     };
 
+    /// SM90
+    struct Policy900 : ChainedPolicy<900, Policy900, Policy800>
+    {
+        enum {
+            PRIMARY_RADIX_BITS     = (sizeof(KeyT) > 1) ? 7 : 5,
+            SINGLE_TILE_RADIX_BITS = (sizeof(KeyT) > 1) ? 6 : 5,
+            SEGMENTED_RADIX_BITS   = (sizeof(KeyT) > 1) ? 6 : 5,
+            ONESWEEP               = sizeof(KeyT) >= sizeof(uint32_t),
+            ONESWEEP_RADIX_BITS    = 8,
+            OFFSET_64BIT           = sizeof(OffsetT) == 8 ? 1 : 0,
+            FLOAT_KEYS             = std::is_same<KeyT, float>::value ? 1 : 0,
+        };
 
-    /// MaxPolicy
-    typedef Policy800 MaxPolicy;
+        // Histogram policy
+        typedef AgentRadixSortHistogramPolicy <128, 16, 1, KeyT, ONESWEEP_RADIX_BITS> HistogramPolicy;
+
+        // Exclusive sum policy
+        typedef AgentRadixSortExclusiveSumPolicy <256, ONESWEEP_RADIX_BITS> ExclusiveSumPolicy;
+
+        typedef AgentRadixSortOnesweepPolicy <384,
+            KEYS_ONLY ? 20 - OFFSET_64BIT - FLOAT_KEYS :
+            (sizeof(ValueT) < 8 ? (OFFSET_64BIT ? 17 : 23) : (OFFSET_64BIT ? 29 : 30)),
+            DominantT, 1, RADIX_RANK_MATCH_EARLY_COUNTS_ANY, BLOCK_SCAN_RAKING_MEMOIZE,
+            RADIX_SORT_STORE_DIRECT, ONESWEEP_RADIX_BITS> OnesweepPolicyKey32;
+
+        typedef AgentRadixSortOnesweepPolicy <384, sizeof(ValueT) < 8 ? 30 : 24, DominantT, 1,
+            RADIX_RANK_MATCH_EARLY_COUNTS_ANY, BLOCK_SCAN_RAKING_MEMOIZE,
+            RADIX_SORT_STORE_DIRECT, ONESWEEP_RADIX_BITS> OnesweepPolicyKey64;
+
+        typedef typename std::conditional<sizeof(KeyT) == 4,
+            OnesweepPolicyKey32, OnesweepPolicyKey64>::type OnesweepPolicy;
+
+        // ScanPolicy
+        typedef AgentScanPolicy <512, 23, OffsetT, BLOCK_LOAD_WARP_TRANSPOSE, LOAD_DEFAULT, BLOCK_STORE_WARP_TRANSPOSE, BLOCK_SCAN_RAKING_MEMOIZE> ScanPolicy;
+
+        // Downsweep policies
+        typedef AgentRadixSortDownsweepPolicy <512, 23, DominantT,  BLOCK_LOAD_TRANSPOSE, LOAD_DEFAULT, RADIX_RANK_MATCH, BLOCK_SCAN_WARP_SCANS, PRIMARY_RADIX_BITS>   DownsweepPolicy;
+        typedef AgentRadixSortDownsweepPolicy <(sizeof(KeyT) > 1) ? 256 : 128, 47, DominantT,  BLOCK_LOAD_TRANSPOSE, LOAD_DEFAULT, RADIX_RANK_MEMOIZE, BLOCK_SCAN_WARP_SCANS, PRIMARY_RADIX_BITS - 1>   AltDownsweepPolicy;
+
+        // Upsweep policies
+        typedef AgentRadixSortUpsweepPolicy <256, 23, DominantT, LOAD_DEFAULT, PRIMARY_RADIX_BITS>     UpsweepPolicy;
+        typedef AgentRadixSortUpsweepPolicy <256, 47, DominantT, LOAD_DEFAULT, PRIMARY_RADIX_BITS - 1> AltUpsweepPolicy;
+
+        // Single-tile policy
+        typedef AgentRadixSortDownsweepPolicy <256, 19, DominantT,  BLOCK_LOAD_DIRECT, LOAD_LDG, RADIX_RANK_MEMOIZE, BLOCK_SCAN_WARP_SCANS, SINGLE_TILE_RADIX_BITS>          SingleTilePolicy;
+
+        // Segmented policies
+        typedef AgentRadixSortDownsweepPolicy <192, 39, DominantT,  BLOCK_LOAD_TRANSPOSE, LOAD_DEFAULT, RADIX_RANK_MEMOIZE, BLOCK_SCAN_WARP_SCANS, SEGMENTED_RADIX_BITS>     SegmentedPolicy;
+        typedef AgentRadixSortDownsweepPolicy <384, 11, DominantT,  BLOCK_LOAD_TRANSPOSE, LOAD_DEFAULT, RADIX_RANK_MEMOIZE, BLOCK_SCAN_WARP_SCANS, SEGMENTED_RADIX_BITS - 1> AltSegmentedPolicy;
+    };
 
 
+    /// MaxPolicy
+    typedef Policy900 MaxPolicy;
 };
 
 
 
 /******************************************************************************
  * Single-problem dispatch
  ******************************************************************************/
@@ -1917,17 +1966,17 @@
         d_values(d_values),
         num_items(num_items),
         num_segments(num_segments),
         d_begin_offsets(d_begin_offsets),
         d_end_offsets(d_end_offsets),
         begin_bit(begin_bit),
         end_bit(end_bit),
-        is_overwrite_okay(is_overwrite_okay),
         stream(stream),
-        ptx_version(ptx_version)
+        ptx_version(ptx_version),
+        is_overwrite_okay(is_overwrite_okay)
     {}
 
     CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED
     CUB_RUNTIME_FUNCTION __forceinline__
     DispatchSegmentedRadixSort(
         void*                   d_temp_storage,
         size_t                  &temp_storage_bytes,
@@ -1950,17 +1999,17 @@
         d_values(d_values),
         num_items(num_items),
         num_segments(num_segments),
         d_begin_offsets(d_begin_offsets),
         d_end_offsets(d_end_offsets),
         begin_bit(begin_bit),
         end_bit(end_bit),
-        is_overwrite_okay(is_overwrite_okay),
         stream(stream),
-        ptx_version(ptx_version)
+        ptx_version(ptx_version),
+        is_overwrite_okay(is_overwrite_okay)
     {
       CUB_DETAIL_RUNTIME_DEBUG_SYNC_USAGE_LOG
     }
 
 
     //------------------------------------------------------------------------------
     // Multi-segment invocation
```

## nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce.cuh

```diff
@@ -779,15 +779,15 @@
         1,
         ActivePolicyT::SingleTilePolicy::BLOCK_THREADS,
         0,
         stream)
         .doit(single_tile_kernel,
               d_block_reductions,
               d_out,
-              reduce_grid_size,
+              reduce_grid_size, // triple_chevron is not type safe, make sure to use int
               reduction_op,
               init);
 
       // Check for failure to launch
       if (CubDebug(error = cudaPeekAtLastError()))
       {
         break;
@@ -837,15 +837,15 @@
                            InputIteratorT,
                            OffsetT,
                            ReductionOpT,
                            AccumT>,
         DeviceReduceSingleTileKernel<MaxPolicyT,
                                      AccumT *,
                                      OutputIteratorT,
-                                     OffsetT,
+                                     int, // Always used with int offsets
                                      ReductionOpT,
                                      InitT,
                                      AccumT>);
     }
   }
 
   //---------------------------------------------------------------------------
```

## nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_spmv_orig.cuh

```diff
@@ -34,29 +34,30 @@
 
 #pragma once
 
 #include <cub/agent/agent_segment_fixup.cuh>
 #include <cub/agent/agent_spmv_orig.cuh>
 #include <cub/agent/single_pass_scan_operators.cuh>
 #include <cub/config.cuh>
+#include <cub/detail/cpp_compatibility.cuh>
 #include <cub/grid/grid_queue.cuh>
 #include <cub/thread/thread_search.cuh>
 #include <cub/util_debug.cuh>
 #include <cub/util_deprecated.cuh>
 #include <cub/util_device.cuh>
 #include <cub/util_math.cuh>
 #include <cub/util_type.cuh>
 
-#include <nv/target>
-
 #include <thrust/system/cuda/detail/core/triple_chevron_launch.h>
 
 #include <cstdio>
 #include <iterator>
 
+#include <nv/target>
+
 CUB_NAMESPACE_BEGIN
 
 
 /******************************************************************************
  * SpMV kernel entry points
  *****************************************************************************/
 
@@ -183,14 +184,33 @@
         num_tiles);
 
     // Initialize fixup tile status
     tile_state.InitializeStatus(num_segment_fixup_tiles);
 
 }
 
+template <typename ValueT,  ///< Matrix and vector value type
+          typename OffsetT, ///< Signed integer type for sequence offsets
+          bool HAS_BETA>    ///< Whether the input parameter Beta is 0
+__global__ void DeviceSpmvEmptyMatrixKernel(SpmvParams<ValueT, OffsetT> spmv_params)
+{
+    const int row = static_cast<int>(threadIdx.x + blockIdx.x * blockDim.x);
+
+    if (row < spmv_params.num_rows)
+    {
+        ValueT result = 0.0;
+
+        CUB_IF_CONSTEXPR(HAS_BETA) 
+        {
+            result += spmv_params.beta * spmv_params.d_vector_y[row]; 
+        }
+
+        spmv_params.d_vector_y[row] = result;
+    }
+}
 
 /**
  * Multi-block reduce-by-key sweep kernel entry point
  */
 template <
     typename    AgentSegmentFixupPolicyT,       ///< Parameterized AgentSegmentFixupPolicy tuning policy type
     typename    PairsInputIteratorT,            ///< Random-access input iterator type for keys
@@ -240,15 +260,16 @@
 {
     //---------------------------------------------------------------------
     // Constants and Types
     //---------------------------------------------------------------------
 
     enum
     {
-        INIT_KERNEL_THREADS = 128
+        INIT_KERNEL_THREADS = 128,
+        EMPTY_MATRIX_KERNEL_THREADS = 128
     };
 
     // SpmvParams bundle type
     typedef SpmvParams<ValueT, OffsetT> SpmvParamsT;
 
     // 2D merge path coordinate type
     typedef typename CubVector<OffsetT, 2>::Type CoordinateT;
@@ -465,25 +486,27 @@
      * If the input is larger than a single tile, this method uses two-passes of
      * kernel invocations.
      */
     template <
         typename                Spmv1ColKernelT,                    ///< Function type of cub::DeviceSpmv1ColKernel
         typename                SpmvSearchKernelT,                  ///< Function type of cub::AgentSpmvSearchKernel
         typename                SpmvKernelT,                        ///< Function type of cub::AgentSpmvKernel
-        typename                SegmentFixupKernelT>                ///< Function type of cub::DeviceSegmentFixupKernelT
+        typename                SegmentFixupKernelT,                ///< Function type of cub::DeviceSegmentFixupKernelT
+        typename                SpmvEmptyMatrixKernelT>             ///< Function type of cub::DeviceSpmvEmptyMatrixKernel
     CUB_RUNTIME_FUNCTION __forceinline__
     static cudaError_t Dispatch(
         void*                   d_temp_storage,                     ///< [in] Device-accessible allocation of temporary storage.  When NULL, the required allocation size is written to \p temp_storage_bytes and no work is done.
         size_t&                 temp_storage_bytes,                 ///< [in,out] Reference to size in bytes of \p d_temp_storage allocation
         SpmvParamsT&            spmv_params,                        ///< SpMV input parameter bundle
         cudaStream_t            stream,                             ///< [in] CUDA stream to launch kernels within.  Default is stream<sub>0</sub>.
         Spmv1ColKernelT         spmv_1col_kernel,                   ///< [in] Kernel function pointer to parameterization of DeviceSpmv1ColKernel
         SpmvSearchKernelT       spmv_search_kernel,                 ///< [in] Kernel function pointer to parameterization of AgentSpmvSearchKernel
         SpmvKernelT             spmv_kernel,                        ///< [in] Kernel function pointer to parameterization of AgentSpmvKernel
         SegmentFixupKernelT     segment_fixup_kernel,               ///< [in] Kernel function pointer to parameterization of cub::DeviceSegmentFixupKernel
+        SpmvEmptyMatrixKernelT  spmv_empty_matrix_kernel,           ///< [in] Kernel function pointer to parameterization of cub::DeviceSpmvEmptyMatrixKernel
         KernelConfig            spmv_config,                        ///< [in] Dispatch parameters that match the policy that \p spmv_kernel was compiled for
         KernelConfig            segment_fixup_config)               ///< [in] Dispatch parameters that match the policy that \p segment_fixup_kernel was compiled for
     {
         cudaError error = cudaSuccess;
         do
         {
             if (spmv_params.num_rows < 0 || spmv_params.num_cols < 0)
@@ -497,14 +520,54 @@
                 {
                     temp_storage_bytes = 1;
                 }
 
                 break;
             }
 
+            if (spmv_params.num_nonzeros == 0)
+            {
+                if (d_temp_storage == NULL)
+                {
+                    // Return if the caller is simply requesting the size of the storage allocation
+                    temp_storage_bytes = 1;
+                    break;
+                }
+
+                const int threads_in_block = EMPTY_MATRIX_KERNEL_THREADS;
+                const int blocks_in_grid = cub::DivideAndRoundUp(spmv_params.num_rows,
+                                                                 threads_in_block);
+
+                #ifdef CUB_DETAIL_DEBUG_ENABLE_LOG
+                _CubLog("Invoking spmv_empty_matrix_kernel<<<%d, %d, 0, %lld>>>()\n",
+                        blocks_in_grid,
+                        threads_in_block,
+                        (long long)stream);
+                #endif
+                error = THRUST_NS_QUALIFIER::cuda_cub::launcher::triple_chevron(blocks_in_grid,
+                                                                                threads_in_block,
+                                                                                0,
+                                                                                stream)
+                          .doit(spmv_empty_matrix_kernel, spmv_params);
+
+                if (CubDebug(error))
+                {
+                    break;
+                }
+
+                // Sync the stream if specified to flush runtime errors
+                error = detail::DebugSyncStream(stream);
+                if (CubDebug(error))
+                {
+                    break;
+                }
+
+                break;
+            }
+
             if (spmv_params.num_cols == 1)
             {
                 if (d_temp_storage == NULL)
                 {
                     // Return if the caller is simply requesting the size of the storage allocation
                     temp_storage_bytes = 1;
                     break;
@@ -713,44 +776,48 @@
 
         return error;
     }
 
     template <typename Spmv1ColKernelT,
               typename SpmvSearchKernelT,
               typename SpmvKernelT,
-              typename SegmentFixupKernelT>
+              typename SegmentFixupKernelT,
+              typename SpmvEmptyMatrixKernelT>
     CUB_DETAIL_RUNTIME_DEBUG_SYNC_IS_NOT_SUPPORTED
     CUB_RUNTIME_FUNCTION __forceinline__ static cudaError_t
     Dispatch(void *d_temp_storage,
              size_t &temp_storage_bytes,
              SpmvParamsT &spmv_params,
              cudaStream_t stream,
              bool debug_synchronous,
              Spmv1ColKernelT spmv_1col_kernel,
              SpmvSearchKernelT spmv_search_kernel,
              SpmvKernelT spmv_kernel,
              SegmentFixupKernelT segment_fixup_kernel,
+             SpmvEmptyMatrixKernelT spmv_empty_matrix_kernel,
              KernelConfig spmv_config,
              KernelConfig segment_fixup_config)
     {
       CUB_DETAIL_RUNTIME_DEBUG_SYNC_USAGE_LOG
 
       return Dispatch<Spmv1ColKernelT,
                       SpmvSearchKernelT,
                       SpmvKernelT,
-                      SegmentFixupKernelT>(d_temp_storage,
-                                           temp_storage_bytes,
-                                           spmv_params,
-                                           stream,
-                                           spmv_1col_kernel,
-                                           spmv_search_kernel,
-                                           spmv_kernel,
-                                           segment_fixup_kernel,
-                                           spmv_config,
-                                           segment_fixup_config);
+                      SegmentFixupKernelT,
+                      SpmvEmptyMatrixKernelT>(d_temp_storage,
+                                              temp_storage_bytes,
+                                              spmv_params,
+                                              stream,
+                                              spmv_1col_kernel,
+                                              spmv_search_kernel,
+                                              spmv_kernel,
+                                              segment_fixup_kernel,
+                                              spmv_empty_matrix_kernel,
+                                              spmv_config,
+                                              segment_fixup_config);
     }
 
     /**
      * Internal dispatch routine for computing a device-wide reduction
      */
     CUB_RUNTIME_FUNCTION __forceinline__
     static cudaError_t Dispatch(
@@ -766,20 +833,24 @@
             int ptx_version = 0;
             if (CubDebug(error = PtxVersion(ptx_version))) break;
 
             // Get kernel kernel dispatch configurations
             KernelConfig spmv_config, segment_fixup_config;
             InitConfigs(ptx_version, spmv_config, segment_fixup_config);
 
+            constexpr bool has_alpha = false;
+            constexpr bool has_beta = false;
+
             if (CubDebug(error = Dispatch(
                 d_temp_storage, temp_storage_bytes, spmv_params, stream, 
                 DeviceSpmv1ColKernel<PtxSpmvPolicyT, ValueT, OffsetT>,
                 DeviceSpmvSearchKernel<PtxSpmvPolicyT, OffsetT, CoordinateT, SpmvParamsT>,
-                DeviceSpmvKernel<PtxSpmvPolicyT, ScanTileStateT, ValueT, OffsetT, CoordinateT, false, false>,
+                DeviceSpmvKernel<PtxSpmvPolicyT, ScanTileStateT, ValueT, OffsetT, CoordinateT, has_alpha, has_beta>,
                 DeviceSegmentFixupKernel<PtxSegmentFixupPolicy, KeyValuePairT*, ValueT*, OffsetT, ScanTileStateT>,
+                DeviceSpmvEmptyMatrixKernel<ValueT, OffsetT, has_beta>,
                 spmv_config, segment_fixup_config))) break;
 
         }
         while (0);
 
         return error;
     }
```

## nvidia/cuda_cccl/include/cub/thread/thread_operators.cuh

```diff
@@ -34,27 +34,56 @@
 /******************************************************************************
  * Simple functor operators
  ******************************************************************************/
 
 #pragma once
 
 #include <cub/config.cuh>
+#include <cub/util_cpp_dialect.cuh>
 #include <cub/util_type.cuh>
 
+#include <cuda/std/functional>
 #include <cuda/std/type_traits>
 #include <cuda/std/utility>
 
 CUB_NAMESPACE_BEGIN
 
 
 /**
  * @addtogroup UtilModule
  * @{
  */
 
+/// @brief Inequality functor (wraps equality functor)
+template <typename EqualityOp>
+struct InequalityWrapper
+{
+  /// Wrapped equality operator
+  EqualityOp op;
+
+  /// Constructor
+  __host__ __device__ __forceinline__ InequalityWrapper(EqualityOp op)
+      : op(op)
+  {}
+
+  /// Boolean inequality operator, returns `t != u`
+  template <typename T, typename U>
+  __host__ __device__ __forceinline__ bool operator()(T &&t, U &&u)
+  {
+    return !op(::cuda::std::forward<T>(t), ::cuda::std::forward<U>(u));
+  }
+};
+
+#if CUB_CPP_DIALECT > 2011
+using Equality = ::cuda::std::equal_to<>;
+using Inequality = ::cuda::std::not_equal_to<>;
+using Sum = ::cuda::std::plus<>;
+using Difference = ::cuda::std::minus<>;
+using Division = ::cuda::std::divides<>;
+#else
 /// @brief Default equality functor
 struct Equality
 {
   /// Boolean equality operator, returns `t == u`
   template <typename T, typename U>
   __host__ __device__ __forceinline__ bool operator()(T &&t, U &&u) const
   {
@@ -69,34 +98,14 @@
   template <typename T, typename U>
   __host__ __device__ __forceinline__ bool operator()(T &&t, U &&u) const
   {
     return ::cuda::std::forward<T>(t) != ::cuda::std::forward<U>(u);
   }
 };
 
-/// @brief Inequality functor (wraps equality functor)
-template <typename EqualityOp>
-struct InequalityWrapper
-{
-  /// Wrapped equality operator
-  EqualityOp op;
-
-  /// Constructor
-  __host__ __device__ __forceinline__ InequalityWrapper(EqualityOp op)
-      : op(op)
-  {}
-
-  /// Boolean inequality operator, returns `t != u`
-  template <typename T, typename U>
-  __host__ __device__ __forceinline__ bool operator()(T &&t, U &&u)
-  {
-    return !op(std::forward<T>(t), std::forward<U>(u));
-  }
-};
-
 /// @brief Default sum functor
 struct Sum
 {
   /// Binary sum operator, returns `t + u`
   template <typename T, typename U>
   __host__ __device__ __forceinline__ auto operator()(T &&t, U &&u) const
     -> decltype(::cuda::std::forward<T>(t) + ::cuda::std::forward<U>(u))
@@ -124,14 +133,15 @@
   template <typename T, typename U>
   __host__ __device__ __forceinline__ auto operator()(T &&t, U &&u) const
     -> decltype(::cuda::std::forward<T>(t) / ::cuda::std::forward<U>(u))
   {
     return ::cuda::std::forward<T>(t) / ::cuda::std::forward<U>(u);
   }
 };
+#endif
 
 /// @brief Default max functor
 struct Max
 {
   /// Boolean max operator, returns `(t > u) ? t : u`
   template <typename T, typename U>
   __host__ __device__ __forceinline__
@@ -363,18 +373,18 @@
 
   __device__ __host__ explicit BinaryFlip(BinaryOpT binary_op)
       : binary_op(binary_op)
   {}
 
   template <typename T, typename U>
   __device__ auto
-  operator()(T &&t, U &&u) -> decltype(binary_op(std::forward<U>(u),
-                                                 std::forward<T>(t)))
+  operator()(T &&t, U &&u) -> decltype(binary_op(::cuda::std::forward<U>(u),
+                                                 ::cuda::std::forward<T>(t)))
   {
-    return binary_op(std::forward<U>(u), std::forward<T>(t));
+    return binary_op(::cuda::std::forward<U>(u), ::cuda::std::forward<T>(t));
   }
 };
 
 template <typename BinaryOpT>
 __device__ __host__ BinaryFlip<BinaryOpT> MakeBinaryFlip(BinaryOpT binary_op)
 {
   return BinaryFlip<BinaryOpT>(binary_op);
```

## nvidia/cuda_cccl/include/cub/warp/warp_scan.cuh

```diff
@@ -343,15 +343,15 @@
      * <tt>0, 1, 2, ..., 31}</tt>.
      *
      */
     __device__ __forceinline__ void ExclusiveSum(
         T               input,              ///< [in] Calling thread's input item.
         T               &exclusive_output)  ///< [out] Calling thread's output item.  May be aliased with \p input.
     {
-        T initial_value = 0;
+        T initial_value {};
         ExclusiveScan(input, exclusive_output, initial_value, cub::Sum());
     }
 
 
     /**
      * \brief Computes an exclusive prefix sum across the calling warp.  The value of 0 is applied as the initial value, and is assigned to \p exclusive_output in <em>thread</em><sub>0</sub>.  Also provides every thread with the warp-wide \p warp_aggregate of all inputs.
      *
@@ -389,15 +389,15 @@
      * <tt>0, 1, 2, ..., 31}</tt>.  Furthermore, \p warp_aggregate for all threads in all warps will be \p 32.
      */
     __device__ __forceinline__ void ExclusiveSum(
         T               input,              ///< [in] Calling thread's input item.
         T               &exclusive_output,  ///< [out] Calling thread's output item.  May be aliased with \p input.
         T               &warp_aggregate)    ///< [out] Warp-wide aggregate reduction of input items.
     {
-        T initial_value = 0;
+        T initial_value {};
         ExclusiveScan(input, exclusive_output, initial_value, cub::Sum(), warp_aggregate);
     }
 
 
     //@}  end member group
     /******************************************************************//**
      * \name Inclusive prefix scans
```

## nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_shfl.cuh

```diff
@@ -35,21 +35,51 @@
 
 #include "../../config.cuh"
 #include "../../thread/thread_operators.cuh"
 #include "../../util_ptx.cuh"
 #include "../../util_type.cuh"
 
 #include <stdint.h>
-#include <type_traits>
 
+#include <cuda/std/type_traits>
 #include <nv/target>
 
 CUB_NAMESPACE_BEGIN
 
 
+namespace detail 
+{
+
+template <class A = int, class = A>
+struct reduce_add_exists : ::cuda::std::false_type 
+{};
+
+template <class T>
+struct reduce_add_exists<T, decltype(__reduce_add_sync(0xFFFFFFFF, T{}))> : ::cuda::std::true_type 
+{};
+
+template <class T = int, class = T>
+struct reduce_min_exists : ::cuda::std::false_type 
+{};
+
+template <class T>
+struct reduce_min_exists<T, decltype(__reduce_min_sync(0xFFFFFFFF, T{}))> : ::cuda::std::true_type 
+{};
+
+template <class T = int, class = T>
+struct reduce_max_exists : ::cuda::std::false_type 
+{};
+
+template <class T>
+struct reduce_max_exists<T, decltype(__reduce_max_sync(0xFFFFFFFF, T{}))> : ::cuda::std::true_type 
+{};
+
+}
+
+
 /**
  * \brief WarpReduceShfl provides SHFL-based variants of parallel reduction of items partitioned across a CUDA thread warp.
  *
  * LOGICAL_WARP_THREADS must be a power-of-two
  */
 template <
     typename    T,                      ///< Data type being reduced
@@ -137,35 +167,23 @@
         int             last_lane,          ///< [in] Index of last lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         unsigned int output;
         int shfl_c = last_lane | SHFL_C;   // Shuffle control (mask and last_lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .u32 r0;"
             "  .reg .pred p;"
             "  shfl.sync.down.b32 r0|p, %1, %2, %3, %5;"
             "  @p add.u32 r0, r0, %4;"
             "  mov.u32 %0, r0;"
             "}"
             : "=r"(output) : "r"(input), "r"(offset), "r"(shfl_c), "r"(input), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .u32 r0;"
-            "  .reg .pred p;"
-            "  shfl.down.b32 r0|p, %1, %2, %3;"
-            "  @p add.u32 r0, r0, %4;"
-            "  mov.u32 %0, r0;"
-            "}"
-            : "=r"(output) : "r"(input), "r"(offset), "r"(shfl_c), "r"(input));
-#endif
 
         return output;
     }
 
 
     /// Reduction (specialized for summation across fp32 types)
     __device__ __forceinline__ float ReduceStep(
@@ -174,35 +192,23 @@
         int             last_lane,          ///< [in] Index of last lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         float output;
         int shfl_c = last_lane | SHFL_C;   // Shuffle control (mask and last_lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .f32 r0;"
             "  .reg .pred p;"
             "  shfl.sync.down.b32 r0|p, %1, %2, %3, %5;"
             "  @p add.f32 r0, r0, %4;"
             "  mov.f32 %0, r0;"
             "}"
             : "=f"(output) : "f"(input), "r"(offset), "r"(shfl_c), "f"(input), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .f32 r0;"
-            "  .reg .pred p;"
-            "  shfl.down.b32 r0|p, %1, %2, %3;"
-            "  @p add.f32 r0, r0, %4;"
-            "  mov.f32 %0, r0;"
-            "}"
-            : "=f"(output) : "f"(input), "r"(offset), "r"(shfl_c), "f"(input));
-#endif
 
         return output;
     }
 
 
     /// Reduction (specialized for summation across unsigned long long types)
     __device__ __forceinline__ unsigned long long ReduceStep(
@@ -210,41 +216,26 @@
         cub::Sum            /*reduction_op*/,   ///< [in] Binary reduction operator
         int                 last_lane,          ///< [in] Index of last lane in segment
         int                 offset)             ///< [in] Up-offset to pull from
     {
         unsigned long long output;
         int shfl_c = last_lane | SHFL_C;   // Shuffle control (mask and last_lane)
 
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .u32 lo;"
             "  .reg .u32 hi;"
             "  .reg .pred p;"
             "  mov.b64 {lo, hi}, %1;"
             "  shfl.sync.down.b32 lo|p, lo, %2, %3, %4;"
             "  shfl.sync.down.b32 hi|p, hi, %2, %3, %4;"
             "  mov.b64 %0, {lo, hi};"
             "  @p add.u64 %0, %0, %1;"
             "}"
             : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .u32 lo;"
-            "  .reg .u32 hi;"
-            "  .reg .pred p;"
-            "  mov.b64 {lo, hi}, %1;"
-            "  shfl.down.b32 lo|p, lo, %2, %3;"
-            "  shfl.down.b32 hi|p, hi, %2, %3;"
-            "  mov.b64 %0, {lo, hi};"
-            "  @p add.u64 %0, %0, %1;"
-            "}"
-            : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c));
-#endif
 
         return output;
     }
 
 
     /// Reduction (specialized for summation across long long types)
     __device__ __forceinline__ long long ReduceStep(
@@ -253,41 +244,26 @@
         int                 last_lane,          ///< [in] Index of last lane in segment
         int                 offset)             ///< [in] Up-offset to pull from
     {
         long long output;
         int shfl_c = last_lane | SHFL_C;   // Shuffle control (mask and last_lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .u32 lo;"
             "  .reg .u32 hi;"
             "  .reg .pred p;"
             "  mov.b64 {lo, hi}, %1;"
             "  shfl.sync.down.b32 lo|p, lo, %2, %3, %4;"
             "  shfl.sync.down.b32 hi|p, hi, %2, %3, %4;"
             "  mov.b64 %0, {lo, hi};"
             "  @p add.s64 %0, %0, %1;"
             "}"
             : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .u32 lo;"
-            "  .reg .u32 hi;"
-            "  .reg .pred p;"
-            "  mov.b64 {lo, hi}, %1;"
-            "  shfl.down.b32 lo|p, lo, %2, %3;"
-            "  shfl.down.b32 hi|p, hi, %2, %3;"
-            "  mov.b64 %0, {lo, hi};"
-            "  @p add.s64 %0, %0, %1;"
-            "}"
-            : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c));
-#endif
 
         return output;
     }
 
 
     /// Reduction (specialized for summation across double types)
     __device__ __forceinline__ double ReduceStep(
@@ -296,45 +272,28 @@
         int                 last_lane,          ///< [in] Index of last lane in segment
         int                 offset)             ///< [in] Up-offset to pull from
     {
         double output;
         int shfl_c = last_lane | SHFL_C;   // Shuffle control (mask and last_lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .u32 lo;"
             "  .reg .u32 hi;"
             "  .reg .pred p;"
             "  .reg .f64 r0;"
             "  mov.b64 %0, %1;"
             "  mov.b64 {lo, hi}, %1;"
             "  shfl.sync.down.b32 lo|p, lo, %2, %3, %4;"
             "  shfl.sync.down.b32 hi|p, hi, %2, %3, %4;"
             "  mov.b64 r0, {lo, hi};"
             "  @p add.f64 %0, %0, r0;"
             "}"
             : "=d"(output) : "d"(input), "r"(offset), "r"(shfl_c), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .u32 lo;"
-            "  .reg .u32 hi;"
-            "  .reg .pred p;"
-            "  .reg .f64 r0;"
-            "  mov.b64 %0, %1;"
-            "  mov.b64 {lo, hi}, %1;"
-            "  shfl.down.b32 lo|p, lo, %2, %3;"
-            "  shfl.down.b32 hi|p, hi, %2, %3;"
-            "  mov.b64 r0, {lo, hi};"
-            "  @p add.f64 %0, %0, r0;"
-            "}"
-            : "=d"(output) : "d"(input), "r"(offset), "r"(shfl_c));
-#endif
 
         return output;
     }
 
 
     /// Reduction (specialized for swizzled ReduceByKeyOp<cub::Sum> across KeyValuePair<KeyT, ValueT> types)
     template <typename ValueT, typename KeyT>
@@ -488,21 +447,19 @@
 
         // Template-iterate reduction steps
         ReduceStep(output, reduction_op, last_lane, Int2Type<0>());
 
         return output;
     }
 
-    // Warp reduce functions are not supported by nvc++ (NVBug 3694682)
-#ifndef _NVHPC_CUDA 
     template <class U = T>
     __device__ __forceinline__ 
     typename std::enable_if<
-               std::is_same<int, U>::value 
-            || std::is_same<unsigned int, U>::value, T>::type
+               (std::is_same<int, U>::value || std::is_same<unsigned int, U>::value)
+            && detail::reduce_add_exists<>::value, T>::type
     ReduceImpl(Int2Type<1> /* all_lanes_valid */,
                T input,
                int /* valid_items */,
                cub::Sum /* reduction_op */)
     {
       T output = input;
 
@@ -515,16 +472,16 @@
 
       return output;
     }
 
     template <class U = T>
     __device__ __forceinline__ 
     typename std::enable_if<
-               std::is_same<int, U>::value 
-            || std::is_same<unsigned int, U>::value, T>::type
+               (std::is_same<int, U>::value || std::is_same<unsigned int, U>::value)
+            && detail::reduce_min_exists<>::value, T>::type
     ReduceImpl(Int2Type<1> /* all_lanes_valid */,
                T input,
                int /* valid_items */,
                cub::Min /* reduction_op */)
     {
       T output = input;
 
@@ -537,16 +494,16 @@
 
       return output;
     }
 
     template <class U = T>
     __device__ __forceinline__ 
     typename std::enable_if<
-               std::is_same<int, U>::value 
-            || std::is_same<unsigned int, U>::value, T>::type
+               (std::is_same<int, U>::value || std::is_same<unsigned int, U>::value)
+            && detail::reduce_max_exists<>::value, T>::type
     ReduceImpl(Int2Type<1> /* all_lanes_valid */,
                T input,
                int /* valid_items */,
                cub::Max /* reduction_op */)
     {
       T output = input;
 
@@ -555,15 +512,14 @@
                    (output = ReduceImpl<cub::Max>(Int2Type<1>{},
                                                   input,
                                                   LOGICAL_WARP_THREADS,
                                                   cub::Max{});));
 
       return output;
     }
-#endif // _NVHPC_CUDA 
 
     /// Reduction
     template <
         bool            ALL_LANES_VALID,        ///< Whether all lanes in each warp are contributing a valid fold of items
         typename        ReductionOp>
     __device__ __forceinline__ T Reduce(
         T               input,                  ///< [in] Calling thread's input
```

## nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_shfl.cuh

```diff
@@ -122,35 +122,23 @@
         int             first_lane,         ///< [in] Index of first lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         int output;
         int shfl_c = first_lane | SHFL_C;   // Shuffle control (mask and first-lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .s32 r0;"
             "  .reg .pred p;"
             "  shfl.sync.up.b32 r0|p, %1, %2, %3, %5;"
             "  @p add.s32 r0, r0, %4;"
             "  mov.s32 %0, r0;"
             "}"
             : "=r"(output) : "r"(input), "r"(offset), "r"(shfl_c), "r"(input), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .s32 r0;"
-            "  .reg .pred p;"
-            "  shfl.up.b32 r0|p, %1, %2, %3;"
-            "  @p add.s32 r0, r0, %4;"
-            "  mov.s32 %0, r0;"
-            "}"
-            : "=r"(output) : "r"(input), "r"(offset), "r"(shfl_c), "r"(input));
-#endif
 
         return output;
     }
 
     /// Inclusive prefix scan step (specialized for summation across uint32 types)
     __device__ __forceinline__ unsigned int InclusiveScanStep(
         unsigned int    input,              ///< [in] Calling thread's input item.
@@ -158,35 +146,23 @@
         int             first_lane,         ///< [in] Index of first lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         unsigned int output;
         int shfl_c = first_lane | SHFL_C;   // Shuffle control (mask and first-lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .u32 r0;"
             "  .reg .pred p;"
             "  shfl.sync.up.b32 r0|p, %1, %2, %3, %5;"
             "  @p add.u32 r0, r0, %4;"
             "  mov.u32 %0, r0;"
             "}"
             : "=r"(output) : "r"(input), "r"(offset), "r"(shfl_c), "r"(input), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .u32 r0;"
-            "  .reg .pred p;"
-            "  shfl.up.b32 r0|p, %1, %2, %3;"
-            "  @p add.u32 r0, r0, %4;"
-            "  mov.u32 %0, r0;"
-            "}"
-            : "=r"(output) : "r"(input), "r"(offset), "r"(shfl_c), "r"(input));
-#endif
 
         return output;
     }
 
 
     /// Inclusive prefix scan step (specialized for summation across fp32 types)
     __device__ __forceinline__ float InclusiveScanStep(
@@ -195,35 +171,23 @@
         int             first_lane,         ///< [in] Index of first lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         float output;
         int shfl_c = first_lane | SHFL_C;   // Shuffle control (mask and first-lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .f32 r0;"
             "  .reg .pred p;"
             "  shfl.sync.up.b32 r0|p, %1, %2, %3, %5;"
             "  @p add.f32 r0, r0, %4;"
             "  mov.f32 %0, r0;"
             "}"
             : "=f"(output) : "f"(input), "r"(offset), "r"(shfl_c), "f"(input), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .f32 r0;"
-            "  .reg .pred p;"
-            "  shfl.up.b32 r0|p, %1, %2, %3;"
-            "  @p add.f32 r0, r0, %4;"
-            "  mov.f32 %0, r0;"
-            "}"
-            : "=f"(output) : "f"(input), "r"(offset), "r"(shfl_c), "f"(input));
-#endif
 
         return output;
     }
 
 
     /// Inclusive prefix scan step (specialized for summation across unsigned long long types)
     __device__ __forceinline__ unsigned long long InclusiveScanStep(
@@ -232,45 +196,28 @@
         int             first_lane,         ///< [in] Index of first lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         unsigned long long output;
         int shfl_c = first_lane | SHFL_C;   // Shuffle control (mask and first-lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .u64 r0;"
             "  .reg .u32 lo;"
             "  .reg .u32 hi;"
             "  .reg .pred p;"
             "  mov.b64 {lo, hi}, %1;"
             "  shfl.sync.up.b32 lo|p, lo, %2, %3, %5;"
             "  shfl.sync.up.b32 hi|p, hi, %2, %3, %5;"
             "  mov.b64 r0, {lo, hi};"
             "  @p add.u64 r0, r0, %4;"
             "  mov.u64 %0, r0;"
             "}"
             : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c), "l"(input), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .u64 r0;"
-            "  .reg .u32 lo;"
-            "  .reg .u32 hi;"
-            "  .reg .pred p;"
-            "  mov.b64 {lo, hi}, %1;"
-            "  shfl.up.b32 lo|p, lo, %2, %3;"
-            "  shfl.up.b32 hi|p, hi, %2, %3;"
-            "  mov.b64 r0, {lo, hi};"
-            "  @p add.u64 r0, r0, %4;"
-            "  mov.u64 %0, r0;"
-            "}"
-            : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c), "l"(input));
-#endif
 
         return output;
     }
 
 
     /// Inclusive prefix scan step (specialized for summation across long long types)
     __device__ __forceinline__ long long InclusiveScanStep(
@@ -279,45 +226,28 @@
         int             first_lane,         ///< [in] Index of first lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         long long output;
         int shfl_c = first_lane | SHFL_C;   // Shuffle control (mask and first-lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .s64 r0;"
             "  .reg .u32 lo;"
             "  .reg .u32 hi;"
             "  .reg .pred p;"
             "  mov.b64 {lo, hi}, %1;"
             "  shfl.sync.up.b32 lo|p, lo, %2, %3, %5;"
             "  shfl.sync.up.b32 hi|p, hi, %2, %3, %5;"
             "  mov.b64 r0, {lo, hi};"
             "  @p add.s64 r0, r0, %4;"
             "  mov.s64 %0, r0;"
             "}"
             : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c), "l"(input), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .s64 r0;"
-            "  .reg .u32 lo;"
-            "  .reg .u32 hi;"
-            "  .reg .pred p;"
-            "  mov.b64 {lo, hi}, %1;"
-            "  shfl.up.b32 lo|p, lo, %2, %3;"
-            "  shfl.up.b32 hi|p, hi, %2, %3;"
-            "  mov.b64 r0, {lo, hi};"
-            "  @p add.s64 r0, r0, %4;"
-            "  mov.s64 %0, r0;"
-            "}"
-            : "=l"(output) : "l"(input), "r"(offset), "r"(shfl_c), "l"(input));
-#endif
 
         return output;
     }
 
 
     /// Inclusive prefix scan step (specialized for summation across fp64 types)
     __device__ __forceinline__ double InclusiveScanStep(
@@ -326,45 +256,28 @@
         int             first_lane,         ///< [in] Index of first lane in segment
         int             offset)             ///< [in] Up-offset to pull from
     {
         double output;
         int shfl_c = first_lane | SHFL_C;   // Shuffle control (mask and first-lane)
 
         // Use predicate set from SHFL to guard against invalid peers
-#ifdef CUB_USE_COOPERATIVE_GROUPS
         asm volatile(
             "{"
             "  .reg .u32 lo;"
             "  .reg .u32 hi;"
             "  .reg .pred p;"
             "  .reg .f64 r0;"
             "  mov.b64 %0, %1;"
             "  mov.b64 {lo, hi}, %1;"
             "  shfl.sync.up.b32 lo|p, lo, %2, %3, %4;"
             "  shfl.sync.up.b32 hi|p, hi, %2, %3, %4;"
             "  mov.b64 r0, {lo, hi};"
             "  @p add.f64 %0, %0, r0;"
             "}"
             : "=d"(output) : "d"(input), "r"(offset), "r"(shfl_c), "r"(member_mask));
-#else
-        asm volatile(
-            "{"
-            "  .reg .u32 lo;"
-            "  .reg .u32 hi;"
-            "  .reg .pred p;"
-            "  .reg .f64 r0;"
-            "  mov.b64 %0, %1;"
-            "  mov.b64 {lo, hi}, %1;"
-            "  shfl.up.b32 lo|p, lo, %2, %3;"
-            "  shfl.up.b32 hi|p, hi, %2, %3;"
-            "  mov.b64 r0, {lo, hi};"
-            "  @p add.f64 %0, %0, r0;"
-            "}"
-            : "=d"(output) : "d"(input), "r"(offset), "r"(shfl_c));
-#endif
 
         return output;
     }
 
 
 /*
     /// Inclusive prefix scan (specialized for ReduceBySegmentOp<cub::Sum> across KeyValuePair<OffsetT, Value> types)
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_base.h

```diff
@@ -1,14 +1,15 @@
 // -*- C++ -*-
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 #ifndef _LIBCUDACXX_ATOMIC_BASE_H
 #define _LIBCUDACXX_ATOMIC_BASE_H
 
 #include "cxx_atomic.h"
@@ -115,46 +116,46 @@
 // FIXME: Haven't figured out what the spec says about using arrays with
 // atomic_fetch_add. Force a failure rather than creating bad behavior.
 template <typename _Tp>
 struct __atomic_ptr_inc<_Tp[]> { };
 template <typename _Tp, int n>
 struct __atomic_ptr_inc<_Tp[n]> { };
 
-template <typename _Tp, typename _Td, _EnableIf<!is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
+template <typename _Tp, typename _Td, __enable_if_t<!is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
 inline auto __cxx_atomic_fetch_add(_Tp* __a, _Td __delta,
                            memory_order __order) -> __cxx_atomic_underlying_t<_Tp> {
   constexpr auto __skip_v = __atomic_ptr_inc<__cxx_atomic_underlying_t<_Tp>>::value;
   auto __a_tmp = __cxx_get_underlying_atomic(__cxx_atomic_unwrap(__a));
   return __atomic_fetch_add(__a_tmp, __delta * __skip_v,
                             __cxx_atomic_order_to_int(__order));
 }
 
-template <typename _Tp, typename _Td, _EnableIf<is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
+template <typename _Tp, typename _Td, __enable_if_t<is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
 inline auto __cxx_atomic_fetch_add(_Tp* __a, _Td __delta,
                            memory_order __order) -> __cxx_atomic_underlying_t<_Tp> {
   auto __expected = __cxx_atomic_load(__a, memory_order_relaxed);
   auto __desired = __expected + __delta;
 
   while(!__cxx_atomic_compare_exchange_strong(__a, &__expected, __desired, __order, __order)) {
       __desired = __expected + __delta;
   }
 
   return __expected;
 }
 
-template <typename _Tp, typename _Td, _EnableIf<!is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
+template <typename _Tp, typename _Td, __enable_if_t<!is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
 inline auto __cxx_atomic_fetch_sub(_Tp* __a, _Td __delta,
                            memory_order __order) -> __cxx_atomic_underlying_t<_Tp> {
   constexpr auto __skip_v = __atomic_ptr_inc<__cxx_atomic_underlying_t<_Tp>>::value;
   auto __a_tmp = __cxx_get_underlying_atomic(__cxx_atomic_unwrap(__a));
   return __atomic_fetch_sub(__a_tmp, __delta * __skip_v,
                             __cxx_atomic_order_to_int(__order));
 }
 
-template <typename _Tp, typename _Td, _EnableIf<is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
+template <typename _Tp, typename _Td, __enable_if_t<is_floating_point<__cxx_atomic_underlying_t<_Tp>>::value, int> = 0>
 inline auto __cxx_atomic_fetch_sub(_Tp* __a, _Td __delta,
                            memory_order __order) -> __cxx_atomic_underlying_t<_Tp> {
   auto __expected = __cxx_atomic_load(__a, memory_order_relaxed);
   auto __desired = __expected - __delta;
 
   while(!__cxx_atomic_compare_exchange_strong(__a, &__expected, __desired, __order, __order)) {
       __desired = __expected - __delta;
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_c11.h

```diff
@@ -1,14 +1,15 @@
 // -*- C++ -*-
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 // Atomics for C11
 
 template <typename _Tp>
 struct __cxx_atomic_base_impl {
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda.h

```diff
@@ -1,42 +1,21 @@
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 #if defined(__CUDA_MINIMUM_ARCH__) && ((!defined(_MSC_VER) && __CUDA_MINIMUM_ARCH__ < 600) || (defined(_MSC_VER) && __CUDA_MINIMUM_ARCH__ < 700))
 #  error "CUDA atomics are only supported for sm_60 and up on *nix and sm_70 and up on Windows."
 #endif
 
-#if !defined(__CLANG_ATOMIC_BOOL_LOCK_FREE) && !defined(__GCC_ATOMIC_BOOL_LOCK_FREE)
-#define ATOMIC_BOOL_LOCK_FREE      2
-#define ATOMIC_CHAR_LOCK_FREE      2
-#define ATOMIC_CHAR16_T_LOCK_FREE  2
-#define ATOMIC_CHAR32_T_LOCK_FREE  2
-#define ATOMIC_WCHAR_T_LOCK_FREE   2
-#define ATOMIC_SHORT_LOCK_FREE     2
-#define ATOMIC_INT_LOCK_FREE       2
-#define ATOMIC_LONG_LOCK_FREE      2
-#define ATOMIC_LLONG_LOCK_FREE     2
-#define ATOMIC_POINTER_LOCK_FREE   2
-#endif //!defined(__CLANG_ATOMIC_BOOL_LOCK_FREE) && !defined(__GCC_ATOMIC_BOOL_LOCK_FREE)
-
-#ifndef __ATOMIC_RELAXED
-#define __ATOMIC_RELAXED 0
-#define __ATOMIC_CONSUME 1
-#define __ATOMIC_ACQUIRE 2
-#define __ATOMIC_RELEASE 3
-#define __ATOMIC_ACQ_REL 4
-#define __ATOMIC_SEQ_CST 5
-#endif //__ATOMIC_RELAXED
-
 inline __host__ __device__ int __stronger_order_cuda(int __a, int __b) {
     int const __max = __a > __b ? __a : __b;
     if(__max != __ATOMIC_RELEASE)
         return __max;
     static int const __xform[] = {
         __ATOMIC_RELEASE,
         __ATOMIC_ACQ_REL,
@@ -60,14 +39,16 @@
 //TODO
 // #  include "atomic_c11.h"
 #elif defined(_LIBCUDACXX_COMPILER_NVRTC)
 #  include "atomic_nvrtc.h"
 #endif
 }
 
+using __host::__cxx_atomic_underlying_t;
+
 #include "atomic_cuda_generated.h"
 #include "atomic_cuda_derived.h"
 
 _LIBCUDACXX_INLINE_VISIBILITY
 inline
  void __cxx_atomic_thread_fence(memory_order __order) {
     NV_DISPATCH_TARGET(
@@ -97,28 +78,34 @@
 struct __cxx_atomic_base_heterogeneous_impl {
     __cxx_atomic_base_heterogeneous_impl() noexcept = default;
 
     _LIBCUDACXX_INLINE_VISIBILITY _LIBCUDACXX_CONSTEXPR explicit
       __cxx_atomic_base_heterogeneous_impl(_Tp __value) : __a_value(__value) {
     }
 
+    using __underlying_t = _Tp;
+    static constexpr int __sco = _Sco;
+
     __host::__cxx_atomic_base_impl<_Tp, _Sco> __a_value;
 };
 
 template <typename _Tp, int _Sco>
 struct __cxx_atomic_base_heterogeneous_impl<_Tp, _Sco, true> {
     __cxx_atomic_base_heterogeneous_impl() noexcept = default;
 
     static_assert(sizeof(_Tp) >= 4, "atomic_ref does not support 1 or 2 byte types");
     static_assert(sizeof(_Tp) <= 8, "atomic_ref does not support types larger than 8 bytes");
 
     _LIBCUDACXX_INLINE_VISIBILITY _LIBCUDACXX_CONSTEXPR explicit
       __cxx_atomic_base_heterogeneous_impl(_Tp& __value) : __a_value(__value) {
     }
 
+    using __underlying_t = _Tp;
+    static constexpr int __sco = _Sco;
+
     __host::__cxx_atomic_ref_base_impl<_Tp, _Sco> __a_value;
 };
 
 template <typename _Tp, int _Sco, bool _Ref>
 _LIBCUDACXX_INLINE_VISIBILITY _LIBCUDACXX_CONSTEXPR
 _Tp* __cxx_get_underlying_device_atomic(__cxx_atomic_base_heterogeneous_impl<_Tp, _Sco, _Ref> * __a) _NOEXCEPT {
   return __cxx_get_underlying_atomic(&__a->__a_value);
@@ -139,30 +126,59 @@
 template <typename _Tp, int _Sco, bool _Ref>
 _LIBCUDACXX_INLINE_VISIBILITY _LIBCUDACXX_CONSTEXPR
 const volatile _Tp* __cxx_get_underlying_device_atomic(__cxx_atomic_base_heterogeneous_impl<_Tp, _Sco, _Ref> const volatile* __a) _NOEXCEPT {
   return __cxx_get_underlying_atomic(&__a->__a_value);
 }
 
 template <typename _Tp>
-using __cxx_atomic_small_to_32 = typename conditional<is_signed<_Tp>::value, int32_t, uint32_t>::type;
+using __cxx_atomic_small_to_32 = __conditional_t<is_signed<_Tp>::value, int32_t, uint32_t>;
+
+// Arithmetic conversions to/from proxy types
+template<class _Tp, __enable_if_t<is_arithmetic<_Tp>::value, int> = 0>
+_LIBCUDACXX_CONSTEXPR _LIBCUDACXX_INLINE_VISIBILITY inline __cxx_atomic_small_to_32<_Tp> __cxx_small_to_32(_Tp __val) {
+    return static_cast<__cxx_atomic_small_to_32<_Tp>>(__val);
+}
+
+template<class _Tp, __enable_if_t<is_arithmetic<_Tp>::value, int> = 0>
+_LIBCUDACXX_CONSTEXPR _LIBCUDACXX_INLINE_VISIBILITY inline _Tp __cxx_small_from_32(__cxx_atomic_small_to_32<_Tp> __val) {
+    return static_cast<_Tp>(__val);
+}
+
+// Non-arithmetic conversion to/from proxy types
+template<class _Tp, __enable_if_t<!is_arithmetic<_Tp>::value, int> = 0>
+_LIBCUDACXX_INLINE_VISIBILITY inline __cxx_atomic_small_to_32<_Tp> __cxx_small_to_32(_Tp __val) {
+    __cxx_atomic_small_to_32<_Tp> __temp{};
+    memcpy(&__temp, &__val, sizeof(_Tp));
+    return __temp;
+}
+
+template<class _Tp, __enable_if_t<!is_arithmetic<_Tp>::value, int> = 0>
+_LIBCUDACXX_INLINE_VISIBILITY inline _Tp __cxx_small_from_32(__cxx_atomic_small_to_32<_Tp> __val) {
+    _Tp __temp{};
+    memcpy(&__temp, &__val, sizeof(_Tp));
+    return __temp;
+}
 
 template <typename _Tp, int _Sco>
 struct __cxx_atomic_base_small_impl {
     __cxx_atomic_base_small_impl() noexcept = default;
     _LIBCUDACXX_INLINE_VISIBILITY _LIBCUDACXX_CONSTEXPR explicit
-      __cxx_atomic_base_small_impl(_Tp __value) : __a_value(__value) {
+      __cxx_atomic_base_small_impl(_Tp __value) : __a_value(__cxx_small_to_32(__value)) {
     }
 
+    using __underlying_t = _Tp;
+    static constexpr int __sco = _Sco;
+
     __cxx_atomic_base_heterogeneous_impl<__cxx_atomic_small_to_32<_Tp>, _Sco, false> __a_value;
 };
 
 template <typename _Tp, int _Sco>
-using __cxx_atomic_base_impl = typename conditional<sizeof(_Tp) < 4,
+using __cxx_atomic_base_impl = __conditional_t<sizeof(_Tp) < 4,
                                     __cxx_atomic_base_small_impl<_Tp, _Sco>,
-                                    __cxx_atomic_base_heterogeneous_impl<_Tp, _Sco> >::type;
+                                    __cxx_atomic_base_heterogeneous_impl<_Tp, _Sco> >;
 
 
 template <typename _Tp, int _Sco>
 using __cxx_atomic_ref_base_impl = __cxx_atomic_base_heterogeneous_impl<_Tp, _Sco, true>;
 
 template <typename _Tp, int _Sco, bool _Ref>
 __host__ __device__
@@ -359,29 +375,14 @@
             return __atomic_fetch_min_cuda(__cxx_get_underlying_device_atomic(__a), __val, static_cast<__memory_order_underlying_t>(__order), __scope_tag<_Sco>());
         ), (
             return __host::__cxx_atomic_fetch_min(&__a->__a_value, __val, __order);
         )
     )
 }
 
-template<class _Tp>
-__host__ __device__ inline __cxx_atomic_small_to_32<_Tp> __cxx_small_to_32(_Tp __val) {
-    _Tp __temp = 0;
-    memcpy(&__temp, &__val, sizeof(_Tp));
-    return __temp;
-}
-
-template<class _Tp>
-__host__ __device__ inline _Tp __cxx_small_from_32(__cxx_atomic_small_to_32<_Tp> __val) {
-    _Tp __temp = static_cast<_Tp>(__val);
-    _Tp __result;
-    memcpy(&__result, &__temp, sizeof(_Tp));
-    return __result;
-}
-
 template <typename _Tp, int _Sco>
 __host__ __device__ inline void __cxx_atomic_init(__cxx_atomic_base_small_impl<_Tp, _Sco> volatile* __a, _Tp __val) {
     __cxx_atomic_init(&__a->__a_value, __cxx_small_to_32(__val));
 }
 
 template <typename _Tp, int _Sco>
 __host__ __device__ inline void __cxx_atomic_store(__cxx_atomic_base_small_impl<_Tp, _Sco> volatile* __a, _Tp __val, memory_order __order) {
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_derived.h

```diff
@@ -1,13 +1,14 @@
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 template<class _Type, class _Scope, typename _CUDA_VSTD::enable_if<sizeof(_Type) <= 2, int>::type = 0>
 bool __device__ __atomic_compare_exchange_cuda(_Type volatile *__ptr, _Type *__expected, const _Type *__desired, bool, int __success_memorder, int __failure_memorder, _Scope __s) {
 
     auto const __aligned = (uint32_t*)((intptr_t)__ptr & ~(sizeof(uint32_t) - 1));
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_generated.h

```diff
@@ -1,13 +1,14 @@
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 
 static inline __device__ void __cuda_membar_block() { asm volatile("membar.cta;":::"memory"); }
 static inline __device__ void __cuda_fence_acq_rel_block() { asm volatile("fence.acq_rel.cta;":::"memory"); }
 static inline __device__ void __cuda_fence_sc_block() { asm volatile("fence.sc.cta;":::"memory"); }
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_gcc.h

```diff
@@ -1,14 +1,15 @@
 // -*- C++ -*-
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 #ifndef _LIBCUDACXX_ATOMIC_GCC_H
 #define _LIBCUDACXX_ATOMIC_GCC_H
 
 #include "atomic_base.h"
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_msvc.h

```diff
@@ -1,30 +1,31 @@
 // -*- C++ -*-
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 #ifndef _MSC_VER
 #error "This file is only for CL.EXE's benefit"
 #endif
 
-#define _Compiler_barrier() _ReadWriteBarrier()
+#define _LIBCUDACXX_COMPILER_BARRIER() _ReadWriteBarrier()
 
 #if defined(_M_ARM) || defined(_M_ARM64)
-    #define _Memory_barrier()             __dmb(0xB) // inner shared data memory barrier
-    #define _Compiler_or_memory_barrier() _Memory_barrier()
+    #define _LIBCUDACXX_MEMORY_BARRIER()             __dmb(0xB) // inner shared data memory barrier
+    #define _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER() _LIBCUDACXX_MEMORY_BARRIER()
 #elif defined(_M_IX86) || defined(_M_X64)
-    #define _Memory_barrier()             __faststorefence()
+    #define _LIBCUDACXX_MEMORY_BARRIER()             __faststorefence()
     // x86/x64 hardware only emits memory barriers inside _Interlocked intrinsics
-    #define _Compiler_or_memory_barrier() _Compiler_barrier()
+    #define _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER() _LIBCUDACXX_COMPILER_BARRIER()
 #else // ^^^ x86/x64 / unsupported hardware vvv
     #error Unsupported hardware
 #endif // hardware
 
 // MSVC Does not have compiler intrinsics for lock-free checking
 #ifndef _LIBCUDACXX_ATOMIC_IS_LOCK_FREE
 #define _LIBCUDACXX_ATOMIC_IS_LOCK_FREE(__x) (__x <= 8)
@@ -40,20 +41,20 @@
         __ATOMIC_ACQ_REL,
         __ATOMIC_RELEASE };
     return __xform[__a < __b ? __a : __b];
 }
 
 static inline void __atomic_signal_fence(int __memorder) {
     if (__memorder != __ATOMIC_RELAXED)
-        _Compiler_barrier();
+        _LIBCUDACXX_COMPILER_BARRIER();
 }
 
 static inline void __atomic_thread_fence(int __memorder) {
     if (__memorder != __ATOMIC_RELAXED)
-        _Memory_barrier();
+        _LIBCUDACXX_MEMORY_BARRIER();
 }
 
 template <typename _Type, size_t _Size>
 using _enable_if_sized_as = typename enable_if<sizeof(_Type) == _Size, int>::type;
 
 template<class _Type, _enable_if_sized_as<_Type,1> = 0>
 void __atomic_load_relaxed(const volatile _Type *__ptr, _Type *__ret) {
@@ -91,17 +92,17 @@
 #endif
     *__ret = reinterpret_cast<_Type&>(__tmp);
 }
 
 template<class _Type>
 void __atomic_load(const volatile _Type *__ptr, _Type *__ret, int __memorder) {
     switch (__memorder) {
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_CONSUME:
-    case __ATOMIC_ACQUIRE: __atomic_load_relaxed(__ptr, __ret); _Compiler_or_memory_barrier(); break;
+    case __ATOMIC_ACQUIRE: __atomic_load_relaxed(__ptr, __ret); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
     case __ATOMIC_RELAXED: __atomic_load_relaxed(__ptr, __ret); break;
     default: assert(0);
     }
 }
 
 template<class _Type, _enable_if_sized_as<_Type,1> = 0>
 void __atomic_store_relaxed(volatile _Type *__ptr, _Type *__val) {
@@ -144,16 +145,16 @@
     __iso_volatile_store64(__d, *__t);
 #endif
 }
 
 template<class _Type>
 void __atomic_store(volatile _Type *__ptr, _Type *__val, int __memorder) {
     switch (__memorder) {
-    case __ATOMIC_RELEASE: _Compiler_or_memory_barrier(); __atomic_store_relaxed(__ptr, __val); break;
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_RELEASE: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); __atomic_store_relaxed(__ptr, __val); break;
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_RELAXED: __atomic_store_relaxed(__ptr, __val); break;
     default: assert(0);
     }
 }
 
 template<class _Type, _enable_if_sized_as<_Type,1> = 0>
 bool __atomic_compare_exchange_relaxed(const volatile _Type *__ptr, _Type *__expected, const _Type *__desired) {
@@ -195,19 +196,19 @@
     *__expected = reinterpret_cast<const _Type&>(__old);
     return false;
 }
 template<class _Type>
 bool __atomic_compare_exchange(_Type volatile *__ptr, _Type *__expected, const _Type *__desired, bool, int __success_memorder, int __failure_memorder) {
     bool success = false;
     switch (__stronger_order_msvc(__success_memorder, __failure_memorder)) {
-    case __ATOMIC_RELEASE: _Compiler_or_memory_barrier(); success = __atomic_compare_exchange_relaxed(__ptr, __expected, __desired); break;
-    case __ATOMIC_ACQ_REL: _Compiler_or_memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_RELEASE: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); success = __atomic_compare_exchange_relaxed(__ptr, __expected, __desired); break;
+    case __ATOMIC_ACQ_REL: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_CONSUME:
-    case __ATOMIC_ACQUIRE: success = __atomic_compare_exchange_relaxed(__ptr, __expected, __desired); _Compiler_or_memory_barrier(); break;
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); success = __atomic_compare_exchange_relaxed(__ptr, __expected, __desired); _Compiler_or_memory_barrier(); break;
+    case __ATOMIC_ACQUIRE: success = __atomic_compare_exchange_relaxed(__ptr, __expected, __desired); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); success = __atomic_compare_exchange_relaxed(__ptr, __expected, __desired); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
     case __ATOMIC_RELAXED: success = __atomic_compare_exchange_relaxed(__ptr, __expected, __desired); break;
     default: assert(0);
     }
     return success;
 }
 
 template<class _Type, _enable_if_sized_as<_Type,1> = 0>
@@ -229,19 +230,19 @@
 void __atomic_exchange_relaxed(const volatile _Type *__ptr, const _Type *__val, _Type *__ret) {
     auto const __old = _InterlockedExchange64((volatile __int64 *)__ptr, reinterpret_cast<__int64 const&>(*__val));
     *__ret = reinterpret_cast<_Type const&>(__old);
 }
 template<class _Type>
 void __atomic_exchange(_Type volatile *__ptr, const _Type *__val, _Type *__ret, int __memorder) {
     switch (__memorder) {
-    case __ATOMIC_RELEASE: _Compiler_or_memory_barrier(); __atomic_exchange_relaxed(__ptr, __val, __ret);break;
-    case __ATOMIC_ACQ_REL: _Compiler_or_memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_RELEASE: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); __atomic_exchange_relaxed(__ptr, __val, __ret);break;
+    case __ATOMIC_ACQ_REL: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_CONSUME:
-    case __ATOMIC_ACQUIRE: __atomic_exchange_relaxed(__ptr, __val, __ret); _Compiler_or_memory_barrier(); break;
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); __atomic_exchange_relaxed(__ptr, __val, __ret); _Compiler_or_memory_barrier(); break;
+    case __ATOMIC_ACQUIRE: __atomic_exchange_relaxed(__ptr, __val, __ret); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); __atomic_exchange_relaxed(__ptr, __val, __ret); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
     case __ATOMIC_RELAXED: __atomic_exchange_relaxed(__ptr, __val, __ret); break;
     default: assert(0);
     }
 }
 
 template<class _Type, class _Delta, _enable_if_sized_as<_Type,1> = 0>
 void __atomic_fetch_add_relaxed(const volatile _Type *__ptr, const _Delta *__val, _Type *__ret) {
@@ -265,19 +266,19 @@
 }
 template<class _Type, class _Delta>
 _Type __atomic_fetch_add(_Type volatile *__ptr, _Delta __val, int __memorder) {
     alignas(_Type) unsigned char __buf[sizeof(_Type)] = {};
     auto* __dest = reinterpret_cast<_Type*>(__buf);
 
     switch (__memorder) {
-    case __ATOMIC_RELEASE: _Compiler_or_memory_barrier(); __atomic_fetch_add_relaxed(__ptr, &__val, __dest);break;
-    case __ATOMIC_ACQ_REL: _Compiler_or_memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_RELEASE: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); __atomic_fetch_add_relaxed(__ptr, &__val, __dest);break;
+    case __ATOMIC_ACQ_REL: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_CONSUME:
-    case __ATOMIC_ACQUIRE: __atomic_fetch_add_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); __atomic_fetch_add_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
+    case __ATOMIC_ACQUIRE: __atomic_fetch_add_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); __atomic_fetch_add_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
     case __ATOMIC_RELAXED: __atomic_fetch_add_relaxed(__ptr, &__val, __dest); break;
     default: assert(0);
     }
     return *__dest;
 }
 template<class _Type, class _Delta>
 _Type __atomic_fetch_sub(_Type volatile *__ptr, _Delta __val, int __memorder) {
@@ -307,19 +308,19 @@
 }
 template<class _Type, class _Delta>
 _Type __atomic_fetch_and(_Type volatile *__ptr, _Delta __val, int __memorder) {
     alignas(_Type) unsigned char __buf[sizeof(_Type)] = {};
     auto* __dest = reinterpret_cast<_Type*>(__buf);
 
     switch (__memorder) {
-    case __ATOMIC_RELEASE: _Compiler_or_memory_barrier(); __atomic_fetch_and_relaxed(__ptr, &__val, __dest);break;
-    case __ATOMIC_ACQ_REL: _Compiler_or_memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_RELEASE: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); __atomic_fetch_and_relaxed(__ptr, &__val, __dest);break;
+    case __ATOMIC_ACQ_REL: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_CONSUME:
-    case __ATOMIC_ACQUIRE: __atomic_fetch_and_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); __atomic_fetch_and_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
+    case __ATOMIC_ACQUIRE: __atomic_fetch_and_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); __atomic_fetch_and_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
     case __ATOMIC_RELAXED: __atomic_fetch_and_relaxed(__ptr, &__val, __dest); break;
     default: assert(0);
     }
     return *__dest;
 }
 
 template<class _Type, class _Delta, _enable_if_sized_as<_Type,1> = 0>
@@ -344,19 +345,19 @@
 }
 template<class _Type, class _Delta>
 _Type __atomic_fetch_xor(_Type volatile *__ptr, _Delta __val, int __memorder) {
     alignas(_Type) unsigned char __buf[sizeof(_Type)] = {};
     auto* __dest = reinterpret_cast<_Type*>(__buf);
 
     switch (__memorder) {
-    case __ATOMIC_RELEASE: _Compiler_or_memory_barrier(); __atomic_fetch_xor_relaxed(__ptr, &__val, __dest);break;
-    case __ATOMIC_ACQ_REL: _Compiler_or_memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_RELEASE: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); __atomic_fetch_xor_relaxed(__ptr, &__val, __dest);break;
+    case __ATOMIC_ACQ_REL: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_CONSUME:
-    case __ATOMIC_ACQUIRE: __atomic_fetch_xor_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); __atomic_fetch_xor_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
+    case __ATOMIC_ACQUIRE: __atomic_fetch_xor_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); __atomic_fetch_xor_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
     case __ATOMIC_RELAXED: __atomic_fetch_xor_relaxed(__ptr, &__val, __dest); break;
     default: assert(0);
     }
     return *__dest;
 }
 
 template<class _Type, class _Delta, _enable_if_sized_as<_Type,1> = 0>
@@ -381,19 +382,19 @@
 }
 template<class _Type, class _Delta>
 _Type __atomic_fetch_or(_Type volatile *__ptr, _Delta __val, int __memorder) {
     alignas(_Type) unsigned char __buf[sizeof(_Type)] = {};
     auto* __dest = reinterpret_cast<_Type*>(__buf);
 
     switch (__memorder) {
-    case __ATOMIC_RELEASE: _Compiler_or_memory_barrier(); __atomic_fetch_or_relaxed(__ptr, &__val, __dest);break;
-    case __ATOMIC_ACQ_REL: _Compiler_or_memory_barrier(); _LIBCUDACXX_FALLTHROUGH();
+    case __ATOMIC_RELEASE: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); __atomic_fetch_or_relaxed(__ptr, &__val, __dest);break;
+    case __ATOMIC_ACQ_REL: _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); _LIBCUDACXX_FALLTHROUGH();
     case __ATOMIC_CONSUME:
-    case __ATOMIC_ACQUIRE: __atomic_fetch_or_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
-    case __ATOMIC_SEQ_CST: _Memory_barrier(); __atomic_fetch_or_relaxed(__ptr, &__val, __dest); _Compiler_or_memory_barrier(); break;
+    case __ATOMIC_ACQUIRE: __atomic_fetch_or_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
+    case __ATOMIC_SEQ_CST: _LIBCUDACXX_MEMORY_BARRIER(); __atomic_fetch_or_relaxed(__ptr, &__val, __dest); _LIBCUDACXX_COMPILER_OR_MEMORY_BARRIER(); break;
     case __ATOMIC_RELAXED: __atomic_fetch_or_relaxed(__ptr, &__val, __dest); break;
     default: assert(0);
     }
     return *__dest;
 }
 
 template<class _Type>
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_nvrtc.h

```diff
@@ -1,14 +1,15 @@
 // -*- C++ -*-
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 #ifndef _LIBCUDACXX_ATOMIC_NVRTC_H
 #define _LIBCUDACXX_ATOMIC_NVRTC_H
 
 #include "cxx_atomic.h"
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/cxx_atomic.h

```diff
@@ -1,14 +1,15 @@
 // -*- C++ -*-
 //===----------------------------------------------------------------------===//
 //
 // Part of libcu++, the C++ Standard Library for your entire system,
 // under the Apache License v2.0 with LLVM Exceptions.
 // See https://llvm.org/LICENSE.txt for license information.
 // SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
+// SPDX-FileCopyrightText: Copyright (c) 2023 NVIDIA CORPORATION & AFFILIATES.
 //
 //===----------------------------------------------------------------------===//
 
 #ifndef _LIBCUDACXX_CXX_ATOMIC_H
 #define _LIBCUDACXX_CXX_ATOMIC_H
 
 template <typename _Tp, int _Sco>
```

## nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/limits_msvc_win32.h

```diff
@@ -60,12 +60,18 @@
 #define __LDBL_MIN__        LDBL_MIN
 #define __LDBL_MAX__        LDBL_MAX
 #define __LDBL_EPSILON__    LDBL_EPSILON
 // predefined by MinGW GCC
 #define __LDBL_DENORM_MIN__ 3.64519953188247460253e-4951L
 
 // __builtin replacements/workarounds
+#if _MSC_VER < 1934
 #define __builtin_huge_vall()    _LInf._Long_double
 #define __builtin_nanl(__dummmy) _LNan._Long_double
 #define __builtin_nansl(__dummy) _LSnan._Long_double
+#else
+#define __builtin_huge_vall()    __builtin_huge_val()
+#define __builtin_nanl(__v)      __builtin_nan(__v)
+#define __builtin_nansl(__v)     __builtin_nans(__v)
+#endif
 
 #endif // _LIBCUDACXX_SUPPORT_WIN32_LIMITS_MSVC_WIN32_H
```

## nvidia/cuda_cccl/include/thrust/device_new_allocator.h

```diff
@@ -21,15 +21,18 @@
 #pragma once
 
 #include <thrust/detail/config.h>
 #include <thrust/device_ptr.h>
 #include <thrust/device_reference.h>
 #include <thrust/device_new.h>
 #include <thrust/device_delete.h>
-#include <limits>
+
+#include <cuda/std/cstdint>
+#include <cuda/std/limits>
+
 #include <stdexcept>
 
 THRUST_NAMESPACE_BEGIN
 
 /*! \addtogroup allocators Allocators
  *  \ingroup memory_management
  *  \{
@@ -57,16 +60,16 @@
 
     /*! Reference to allocated element, \c device_reference<T>. */
     typedef device_reference<T>               reference;
 
     /*! \c const reference to allocated element, \c device_reference<const T>. */
     typedef device_reference<const T>         const_reference;
 
-    /*! Type of allocation size, \c std::size_t. */
-    typedef std::size_t                       size_type;
+    /*! Type of allocation size, \c ::cuda::std::size_t. */
+    typedef ::cuda::std::size_t                 size_type;
 
     /*! Type of allocation difference, \c pointer::difference_type. */
     typedef typename pointer::difference_type difference_type;
 
     /*! The \p rebind metafunction provides the type of a \p device_new_allocator
      *  instantiated with another type.
      *
@@ -143,15 +146,15 @@
 
     /*! Returns the largest value \c n for which <tt>allocate(n)</tt> might succeed.
      *  \return The largest value \c n for which <tt>allocate(n)</tt> might succeed.
      */
     __host__ __device__
     inline size_type max_size() const
     {
-      return std::numeric_limits<size_type>::max THRUST_PREVENT_MACRO_SUBSTITUTION () / sizeof(T);
+      return ::cuda::std::numeric_limits<size_type>::max THRUST_PREVENT_MACRO_SUBSTITUTION () / sizeof(T);
     } // end max_size()
 
     /*! Compares against another \p device_malloc_allocator for equality.
      *  \return \c true
      */
     __host__ __device__
     inline bool operator==(device_new_allocator const&) { return true; }
```

## nvidia/cuda_cccl/include/thrust/device_vector.h

```diff
@@ -22,14 +22,15 @@
 
 #pragma once
 
 #include <thrust/detail/config.h>
 #include <thrust/detail/vector_base.h>
 #include <thrust/device_allocator.h>
 
+#include <initializer_list>
 #include <vector>
 #include <utility>
 
 THRUST_NAMESPACE_BEGIN
 
 /*! \addtogroup containers Containers
  *  \{
@@ -193,14 +194,33 @@
     /*! Assign a \p vector_base whose element type is convertible to \c T.
      *  \param v The \p vector_base to copy.
      */
     template<typename OtherT, typename OtherAlloc>
     device_vector &operator=(const detail::vector_base<OtherT,OtherAlloc> &v)
     { Parent::operator=(v); return *this; }
 
+    /*! This constructor builds a \p device_vector from an intializer_list.
+     *  \param il The intializer_list.
+     */
+    device_vector(std::initializer_list<T> il)
+      :Parent(il) {}
+      
+    /*! This constructor builds a \p device_vector from an intializer_list.
+     *  \param il The intializer_list.
+     *  \param alloc The allocator to use by this device_vector.
+     */
+    device_vector(std::initializer_list<T> il, const Alloc &alloc)
+      :Parent(il, alloc) {}
+      
+    /*! Assign an \p intializer_list with a matching element type
+     *  \param il The intializer_list.
+     */
+    device_vector &operator=(std::initializer_list<T> il)
+    { Parent::operator=(il); return *this; }
+
     /*! This constructor builds a \p device_vector from a range.
      *  \param first The beginning of the range.
      *  \param last The end of the range.
      */
     template<typename InputIterator>
     device_vector(InputIterator first, InputIterator last)
       :Parent(first,last) {}
```

## nvidia/cuda_cccl/include/thrust/execution_policy.h

```diff
@@ -278,18 +278,17 @@
  *    __host__ __device__
  *    void operator()(int x)
  *    {
  *      printf("%d\n", x);
  *    }
  *  };
  *  ...
- *  int vec(3);
- *  vec[0] = 0; vec[1] = 1; vec[2] = 2;
+ *  int vec[] = { 0, 1, 2 };
  *
- *  thrust::for_each(thrust::host, vec.begin(), vec.end(), printf_functor());
+ *  thrust::for_each(thrust::host, vec, vec + 3, printf_functor());
  *
  *  // 0 1 2 is printed to standard output in some unspecified order
  *  \endcode
  *
  *  \see host_execution_policy
  *  \see thrust::device
  */
```

## nvidia/cuda_cccl/include/thrust/host_vector.h

```diff
@@ -21,14 +21,16 @@
  */
 
 #pragma once
 
 #include <thrust/detail/config.h>
 #include <thrust/detail/memory_wrapper.h>
 #include <thrust/detail/vector_base.h>
+
+#include <initializer_list>
 #include <vector>
 #include <utility>
 
 THRUST_NAMESPACE_BEGIN
 
 /*! \addtogroup container_classes Container Classes
  *  \addtogroup host_containers Host Containers
@@ -212,14 +214,33 @@
      *
      *  \param v The \p vector_base to copy.
      */
     template<typename OtherT, typename OtherAlloc>
     __host__
     host_vector &operator=(const detail::vector_base<OtherT,OtherAlloc> &v)
     { Parent::operator=(v); return *this; }
+    
+    /*! This constructor builds a \p host_vector from an intializer_list.
+     *  \param il The intializer_list.
+     */
+    host_vector(std::initializer_list<T> il)
+      :Parent(il) {}
+      
+    /*! This constructor builds a \p host_vector from an intializer_list.
+     *  \param il The intializer_list.
+     *  \param alloc The allocator to use by this host_vector.
+     */
+    host_vector(std::initializer_list<T> il, const Alloc &alloc)
+      :Parent(il, alloc) {}
+      
+    /*! Assign an \p intializer_list with a matching element type
+     *  \param il The intializer_list.
+     */
+    host_vector &operator=(std::initializer_list<T> il)
+    { Parent::operator=(il); return *this; }
 
     /*! This constructor builds a \p host_vector from a range.
      *  \param first The beginning of the range.
      *  \param last The end of the range.
      */
     template<typename InputIterator>
     __host__
```

## nvidia/cuda_cccl/include/thrust/optional.h

```diff
@@ -1576,29 +1576,29 @@
   __host__ __device__
   T &emplace(Args &&... args) {
     static_assert(std::is_constructible<T, Args &&...>::value,
                   "T must be constructible with Args");
 
     *this = nullopt;
     this->construct(std::forward<Args>(args)...);
-    return value();
+    return this->m_value;
   }
 
   /// \group emplace
   /// \synopsis template <class U, class... Args>\nT& emplace(std::initializer_list<U> il, Args &&... args);
   __thrust_exec_check_disable__
   template <class U, class... Args>
   __host__ __device__
   detail::enable_if_t<
       std::is_constructible<T, std::initializer_list<U> &, Args &&...>::value,
       T &>
   emplace(std::initializer_list<U> il, Args &&... args) {
     *this = nullopt;
     this->construct(il, std::forward<Args>(args)...);
-    return value();
+    return this->m_value;
   }
 
   /// Swaps this optional with the other.
   ///
   /// If neither optionals have a value, nothing happens.
   /// If both have a value, the values are swapped.
   /// If one has a value, it is moved to the other and the movee is left
```

## nvidia/cuda_cccl/include/thrust/version.h

```diff
@@ -43,15 +43,15 @@
  *  \brief The preprocessor macro \p THRUST_VERSION encodes the version
  *         number of the Thrust library.
  *
  *         <tt>THRUST_VERSION % 100</tt> is the sub-minor version.
  *         <tt>THRUST_VERSION / 100 % 1000</tt> is the minor version.
  *         <tt>THRUST_VERSION / 100000</tt> is the major version.
  */
-#define THRUST_VERSION 200001
+#define THRUST_VERSION 200101
 
 /*! \def THRUST_MAJOR_VERSION
  *  \brief The preprocessor macro \p THRUST_MAJOR_VERSION encodes the
  *         major version number of the Thrust library.
  */
 #define THRUST_MAJOR_VERSION     (THRUST_VERSION / 100000)
```

## nvidia/cuda_cccl/include/thrust/detail/type_traits.h

```diff
@@ -132,44 +132,22 @@
        || __is_pod(T)
 #endif // GCC VERSION
 #endif // THRUST_HOST_COMPILER
      >
  {};
 
 
-template<typename T> struct has_trivial_constructor
-  : public integral_constant<
-      bool,
-      is_pod<T>::value
-#if THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_MSVC || \
-    THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_CLANG
-      || __has_trivial_constructor(T)
-#elif THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_GCC
-// only use the intrinsic for >= 4.3
-#if (__GNUC__ >= 4) && (__GNUC_MINOR__ >= 3)
-      || __has_trivial_constructor(T)
-#endif // GCC VERSION
-#endif // THRUST_HOST_COMPILER
-      >
+template <typename T> 
+struct has_trivial_constructor
+  : public integral_constant<bool, is_pod<T>::value || ::cuda::std::is_trivially_constructible<T>::value> 
 {};
 
-template<typename T> struct has_trivial_copy_constructor
-  : public integral_constant<
-      bool,
-      is_pod<T>::value
-#if THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_MSVC || \
-    THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_CLANG
-      || __has_trivial_copy(T)
-#elif THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_GCC
-// only use the intrinsic for >= 4.3
-#if (__GNUC__ >= 4) && (__GNUC_MINOR__ >= 3)
-      || __has_trivial_copy(T)
-#endif // GCC VERSION
-#endif // THRUST_HOST_COMPILER
-    >
+template<typename T> 
+struct has_trivial_copy_constructor
+  : public integral_constant<bool, is_pod<T>::value || ::cuda::std::is_trivially_copyable<T>::value>
 {};
 
 template<typename T> struct has_trivial_destructor : public is_pod<T> {};
 
 template<typename T> struct is_const          : public false_type {};
 template<typename T> struct is_const<const T> : public true_type {};
```

## nvidia/cuda_cccl/include/thrust/detail/vector_base.h

```diff
@@ -24,14 +24,16 @@
 
 #include <thrust/iterator/detail/normal_iterator.h>
 #include <thrust/iterator/reverse_iterator.h>
 #include <thrust/iterator/iterator_traits.h>
 #include <thrust/detail/type_traits.h>
 #include <thrust/detail/config.h>
 #include <thrust/detail/contiguous_storage.h>
+
+#include <initializer_list>
 #include <vector>
 
 THRUST_NAMESPACE_BEGIN
 
 namespace detail
 {
 
@@ -119,20 +121,34 @@
   #endif
 
     /*! Copy assign operator copies from another vector_base.
      *  \param v The vector_base to copy.
      */
     vector_base &operator=(const vector_base &v);
 
-  #if THRUST_CPP_DIALECT >= 2011
     /*! Move assign operator moves from another vector_base.
      *  \param v The vector_base to move.
      */
     vector_base &operator=(vector_base &&v);
-  #endif
+
+    /*! This constructor builds a \p vector_base from an intializer_list.
+     *  \param il The intializer_list.
+     */
+    vector_base(std::initializer_list<T> il);
+      
+    /*! This constructor builds a \p vector_base from an intializer_list.
+     *  \param il The intializer_list.
+     *  \param alloc The allocator to use by this device_vector.
+     */
+    vector_base(std::initializer_list<T> il, const Alloc &alloc);
+    
+    /*! Assign operator copies from an initializer_list
+     *  \param il The initializer_list.
+     */
+    vector_base &operator=(std::initializer_list<T> il);
 
     /*! Copy constructor copies from an exemplar vector_base with different
      *  type.
      *  \param v The vector_base to copy.
      */
     template<typename OtherT, typename OtherAlloc>
     vector_base(const vector_base<OtherT, OtherAlloc> &v);
```

## nvidia/cuda_cccl/include/thrust/detail/vector_base.inl

```diff
@@ -191,14 +191,42 @@
         ::operator=(const std::vector<OtherT,OtherAlloc> &v)
 {
   assign(v.begin(), v.end());
 
   return *this;
 } // end vector_base::operator=()
 
+  template<typename T, typename Alloc>
+    vector_base<T,Alloc>
+      ::vector_base(std::initializer_list<T> il)
+        :m_storage(),
+         m_size(0)
+  {
+    range_init(il.begin(), il.end());
+  } // end vector_base::vector_base()
+
+  template<typename T, typename Alloc>
+  vector_base<T,Alloc>
+    ::vector_base(std::initializer_list<T> il, const Alloc &alloc)
+    :m_storage(alloc),
+      m_size(0)
+  {
+    range_init(il.begin(), il.end());
+  } // end vector_base::vector_base()
+
+  template<typename T, typename Alloc>
+    vector_base<T,Alloc> &
+      vector_base<T,Alloc>
+      ::operator=(std::initializer_list<T> il)
+  {
+    assign(il.begin(), il.end());
+
+    return *this;
+  } // end vector_base::operator=()
+
 template<typename T, typename Alloc>
   template<typename IteratorOrIntegralType>
     void vector_base<T,Alloc>
       ::init_dispatch(IteratorOrIntegralType n,
                       IteratorOrIntegralType value,
                       true_type)
 {
```

## nvidia/cuda_cccl/include/thrust/detail/complex/catrigf.h

```diff
@@ -163,15 +163,15 @@
 __host__ __device__ inline
 complex<float>
 casinhf(complex<float> z)
 {
   float x, y, ax, ay, rx, ry, B, sqrt_A2my2, new_y;
   int B_is_usable;
   complex<float> w;
-  const float RECIP_EPSILON = 1.0 / FLT_EPSILON;
+  const float RECIP_EPSILON = 1.0f / FLT_EPSILON;
   const float m_ln2 = 6.9314718055994531e-1f; /*  0x162e42fefa39ef.0p-53 */
   x = z.real();
   y = z.imag();
   ax = fabsf(x);
   ay = fabsf(y);
 
   if (isnan(x) || isnan(y)) {
@@ -242,15 +242,15 @@
     if (isinf(y))
       return (complex<float>(x + x, -y));
     if (x == 0)
       return (complex<float>(pio2_hi + pio2_lo, y + y));
     return (complex<float>(x + 0.0f + (y + 0), x + 0.0f + (y + 0)));
   }
 
-  const float RECIP_EPSILON = 1.0 / FLT_EPSILON;
+  const float RECIP_EPSILON = 1.0f / FLT_EPSILON;
   if (ax > RECIP_EPSILON || ay > RECIP_EPSILON) {
     w = clog_for_large_values(z);
     rx = fabsf(w.imag());
     ry = w.real() + m_ln2;
     if (sy == 0)
       ry = -ry;
     return (complex<float>(rx, ry));
```

## nvidia/cuda_cccl/include/thrust/detail/type_traits/has_trivial_assign.h

```diff
@@ -21,33 +21,27 @@
  */
 
 #pragma once
 
 #include <thrust/detail/config.h>
 #include <thrust/detail/type_traits.h>
 
+#include <cuda/std/type_traits>
+
 THRUST_NAMESPACE_BEGIN
 
 namespace detail
 {
 
-template<typename T> struct has_trivial_assign
+template<typename T> 
+struct has_trivial_assign
   : public integral_constant<
-      bool,
-      (is_pod<T>::value && !is_const<T>::value)
-#if THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_MSVC
-      || __has_trivial_assign(T)
-#elif THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_GCC
-// only use the intrinsic for >= 4.3
-#if (__GNUC__ >= 4) && (__GNUC_MINOR__ >= 3)
-      || __has_trivial_assign(T)
-#endif // GCC VERSION
-#elif THRUST_HOST_COMPILER == THRUST_HOST_COMPILER_CLANG
-      || __has_trivial_assign(T)
-#endif // THRUST_HOST_COMPILER
+      bool, 
+      (is_pod<T>::value && !is_const<T>::value) 
+      || ::cuda::std::is_trivially_copy_assignable<T>::value
     >
 {};
 
 } // end detail
 
 THRUST_NAMESPACE_END
```

## nvidia/cuda_cccl/include/thrust/iterator/transform_input_output_iterator.h

```diff
@@ -98,14 +98,16 @@
     detail::transform_input_output_iterator_base<InputFunction, OutputFunction, Iterator>::type
     super_t;
 
     friend class thrust::iterator_core_access;
   /*! \endcond
    */
 
+  transform_input_output_iterator() = default;
+
   /*! This constructor takes as argument a \c Iterator an \c InputFunction and an
    * \c OutputFunction and copies them to a new \p transform_input_output_iterator
    *
    * \param io An \c Iterator pointing to where the input to \c InputFunction
    *           will be read from and the result of \c OutputFunction will be written to
    * \param input_function An \c InputFunction to be executed on values read from the iterator
    * \param output_function An \c OutputFunction to be executed on values written to the iterator
```

## nvidia/cuda_cccl/include/thrust/iterator/transform_output_iterator.h

```diff
@@ -100,14 +100,16 @@
     detail::transform_output_iterator_base<UnaryFunction, OutputIterator>::type
     super_t;
 
     friend class thrust::iterator_core_access;
   /*! \endcond
    */
 
+  transform_output_iterator() = default;
+
   /*! This constructor takes as argument an \c OutputIterator and an \c
    * UnaryFunction and copies them to a new \p transform_output_iterator
    *
    * \param out An \c OutputIterator pointing to the output range whereto the result of 
    *            \p transform_output_iterator's \c UnaryFunction will be written.
    * \param fun An \c UnaryFunction used to transform the objects assigned to
    *            this \p transform_output_iterator.
```

## nvidia/cuda_cccl/include/thrust/system/cpp/detail/vector.inl

```diff
@@ -94,14 +94,35 @@
       vector<T,Allocator>
         ::operator=(vector &&x)
   {
     super_t::operator=(std::move(x));
     return *this;
   }
 #endif
+  
+  template<typename T, typename Allocator>
+    vector<T,Allocator>
+      ::vector(std::initializer_list<T> il)
+        : super_t(il)
+  {}
+  
+  template<typename T, typename Allocator>
+    vector<T,Allocator>
+      ::vector(std::initializer_list<T> il, const Allocator& alloc)
+        : super_t(il, alloc)
+  {}
+
+  template<typename T, typename Allocator>
+    vector<T,Allocator> &
+      vector<T,Allocator>
+        ::operator=(std::initializer_list<T> il)
+  {
+    super_t::operator=(il);
+    return *this;
+  }
 
 template<typename T, typename Allocator>
   template<typename OtherT, typename OtherAllocator>
     vector<T,Allocator> &
       vector<T,Allocator>
         ::operator=(const std::vector<OtherT,OtherAllocator> &x)
 {
```

## nvidia/cuda_cccl/include/thrust/system/cuda/error.h

```diff
@@ -51,42 +51,32 @@
   // from cuda/include/driver_types.h
   // mirror their order
   success                            = cudaSuccess,
   missing_configuration              = cudaErrorMissingConfiguration,
   memory_allocation                  = cudaErrorMemoryAllocation,
   initialization_error               = cudaErrorInitializationError,
   launch_failure                     = cudaErrorLaunchFailure,
-  prior_launch_failure               = cudaErrorPriorLaunchFailure,
   launch_timeout                     = cudaErrorLaunchTimeout,
   launch_out_of_resources            = cudaErrorLaunchOutOfResources,
   invalid_device_function            = cudaErrorInvalidDeviceFunction,
   invalid_configuration              = cudaErrorInvalidConfiguration,
   invalid_device                     = cudaErrorInvalidDevice,
   invalid_value                      = cudaErrorInvalidValue,
   invalid_pitch_value                = cudaErrorInvalidPitchValue,
   invalid_symbol                     = cudaErrorInvalidSymbol,
   map_buffer_object_failed           = cudaErrorMapBufferObjectFailed,
   unmap_buffer_object_failed         = cudaErrorUnmapBufferObjectFailed,
-  invalid_host_pointer               = cudaErrorInvalidHostPointer,
-  invalid_device_pointer             = cudaErrorInvalidDevicePointer,
   invalid_texture                    = cudaErrorInvalidTexture,
   invalid_texture_binding            = cudaErrorInvalidTextureBinding,
   invalid_channel_descriptor         = cudaErrorInvalidChannelDescriptor,
   invalid_memcpy_direction           = cudaErrorInvalidMemcpyDirection,
-  address_of_constant_error          = cudaErrorAddressOfConstant,
-  texture_fetch_failed               = cudaErrorTextureFetchFailed,
-  texture_not_bound                  = cudaErrorTextureNotBound,
-  synchronization_error              = cudaErrorSynchronizationError,
   invalid_filter_setting             = cudaErrorInvalidFilterSetting,
   invalid_norm_setting               = cudaErrorInvalidNormSetting,
-  mixed_device_execution             = cudaErrorMixedDeviceExecution,
   cuda_runtime_unloading             = cudaErrorCudartUnloading,
   unknown                            = cudaErrorUnknown,
-  not_yet_implemented                = cudaErrorNotYetImplemented,
-  memory_value_too_large             = cudaErrorMemoryValueTooLarge,
   invalid_resource_handle            = cudaErrorInvalidResourceHandle,
   not_ready                          = cudaErrorNotReady,
   insufficient_driver                = cudaErrorInsufficientDriver,
   set_on_active_process_error        = cudaErrorSetOnActiveProcess,
   no_device                          = cudaErrorNoDevice,
   ecc_uncorrectable                  = cudaErrorECCUncorrectable,
```

## nvidia/cuda_cccl/include/thrust/system/cuda/detail/cdp_dispatch.h

```diff
@@ -50,21 +50,21 @@
 
 // seq_impl only used on platforms that do not support device synchronization.
 #define THRUST_CDP_DISPATCH(par_impl, seq_impl)                                \
   if (false)                                                                   \
   { /* Without this, the device pass won't compile any kernels. */             \
     NV_IF_TARGET(NV_ANY_TARGET, par_impl);                                     \
   }                                                                            \
-  NV_DISPATCH_TARGET(NV_PROVIDES_SM_90, seq_impl, NV_ANY_TARGET, par_impl)
+  NV_IF_TARGET(NV_PROVIDES_SM_90, seq_impl, par_impl)
 
 #else // NVCC device pass
 
 // seq_impl only used on platforms that do not support device synchronization.
 #define THRUST_CDP_DISPATCH(par_impl, seq_impl)                                \
-  NV_DISPATCH_TARGET(NV_PROVIDES_SM_90, seq_impl, NV_ANY_TARGET, par_impl)
+  NV_IF_TARGET(NV_PROVIDES_SM_90, seq_impl, par_impl)
 
 #endif // NVCC device pass
 
 #else // CDPv1 unavailable. Always fallback to serial on device:
 
 // Special case for NVCC -- need to inform the device path about the kernels
 // that are launched from the host path.
```

## nvidia/cuda_cccl/include/thrust/system/cuda/detail/error.inl

```diff
@@ -68,15 +68,15 @@
            + ": " + (c_str ? c_str : unknown_str);
     }
 
     inline virtual error_condition default_error_condition(int ev) const
     {
       using namespace cuda::errc;
 
-      if(ev < ::cudaErrorApiFailureBase)
+      if(ev < ::cudaErrorUnknown)
       {
         return make_error_condition(static_cast<errc_t>(ev));
       }
 
       return system_category().default_error_condition(ev);
     }
 }; // end cuda_error_category
```

## nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce.h

```diff
@@ -939,19 +939,16 @@
   cudaStream_t stream = cuda_cub::stream(policy);
   cudaError_t status;
 
   // Determine temporary device storage requirements.
 
   size_t tmp_size = 0;
 
-  THRUST_INDEX_TYPE_DISPATCH2(status,
+  THRUST_INDEX_TYPE_DISPATCH(status,
     cub::DeviceReduce::Reduce,
-    (cub::DispatchReduce<
-        InputIt, T*, Size, BinaryOp, T
-    >::Dispatch),
     num_items,
     (NULL, tmp_size, first, reinterpret_cast<T*>(NULL),
         num_items_fixed, binary_op, init, stream));
   cuda_cub::throw_on_error(status, "after reduction step 1");
 
   // Allocate temporary storage.
 
@@ -966,19 +963,16 @@
   // `static_cast` to `void*`.
   //
   // The array was dynamically allocated, so we assume that it's suitably
   // aligned for any type of data. `malloc`/`cudaMalloc`/`new`/`std::allocator`
   // make this guarantee.
   T* ret_ptr = thrust::detail::aligned_reinterpret_cast<T*>(tmp.data().get());
   void* tmp_ptr = static_cast<void*>((tmp.data() + sizeof(T)).get());
-  THRUST_INDEX_TYPE_DISPATCH2(status,
+  THRUST_INDEX_TYPE_DISPATCH(status,
     cub::DeviceReduce::Reduce,
-    (cub::DispatchReduce<
-        InputIt, T*, Size, BinaryOp, T
-    >::Dispatch),
     num_items,
     (tmp_ptr, tmp_size, first, ret_ptr,
         num_items_fixed, binary_op, init, stream));
   cuda_cub::throw_on_error(status, "after reduction step 2");
 
   // Synchronize the stream and get the value.
```

## nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce_by_key.h

```diff
@@ -1075,20 +1075,21 @@
                 EqualityOp                 equality_op,
                 ReductionOp                reduction_op)
   {
     using size_type = typename iterator_traits<KeysInputIt>::difference_type;
 
     size_type num_items = thrust::distance(keys_first, keys_last);
 
+    pair<KeysOutputIt, ValuesOutputIt> result = thrust::make_pair(keys_output, values_output);
+
     if (num_items == 0)
     {
-      return thrust::make_pair(keys_output, values_output);
+      return result;
     }
 
-    pair<KeysOutputIt, ValuesOutputIt> result{};
     THRUST_INDEX_TYPE_DISPATCH(result,
                                reduce_by_key_dispatch,
                                num_items,
                                (policy,
                                 keys_first,
                                 num_items_fixed,
                                 values_first,
```

## nvidia/cuda_cccl/include/thrust/system/cuda/detail/util.h

```diff
@@ -313,14 +313,15 @@
 
 #if THRUST_CPP_DIALECT >= 2011
   transform_input_iterator_t(const self_t &) = default;
 #endif
 
   // UnaryOp might not be copy assignable, such as when it is a lambda.  Define
   // an explicit copy assignment operator that doesn't try to assign it.
+  __host__ __device__ 
   self_t& operator=(const self_t& o)
   {
     input = o.input;
     return *this;
   }
 
   /// Postfix increment
@@ -427,14 +428,15 @@
 
 #if THRUST_CPP_DIALECT >= 2011
   transform_pair_of_input_iterators_t(const self_t &) = default;
 #endif
 
   // BinaryOp might not be copy assignable, such as when it is a lambda.
   // Define an explicit copy assignment operator that doesn't try to assign it.
+  __host__ __device__
   self_t& operator=(const self_t& o)
   {
     input1 = o.input1;
     input2 = o.input2;
     return *this;
   }
```

## nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/agent_launcher.h

```diff
@@ -471,32 +471,29 @@
       // if user mix & match ptx versions in a separably compiled function
       // http://nvbugs/1772071
       // XXX may be it is too string of a requirements, consider relaxing it in
       // the future
 #ifdef __CUDACC_RDC__
       return core::get_agent_plan<Agent>(s, d_ptr);
 #else
-      core::cuda_optional<int> ptx_version = core::get_ptx_version();
-      //CUDA_CUB_RET_IF_FAIL(ptx_version.status());
-      return get_agent_plan<Agent>(ptx_version);
+      return get_agent_plan<Agent>(core::get_ptx_version());
 #endif
     }
     THRUST_RUNTIME_FUNCTION
     AgentPlan static get_plan_default()
     {
       return get_agent_plan<Agent>(sm_arch<0>::type::ver);
     }
 #endif
 
     THRUST_RUNTIME_FUNCTION
     typename core::get_plan<Agent>::type static get_plan(cudaStream_t , void* d_ptr = 0)
     {
       THRUST_UNUSED_VAR(d_ptr);
-      core::cuda_optional<int> ptx_version = core::get_ptx_version();
-      return get_agent_plan<Agent>(ptx_version);
+      return get_agent_plan<Agent>(core::get_ptx_version());
     }
 
     THRUST_RUNTIME_FUNCTION
     typename core::get_plan<Agent>::type static get_plan()
     {
       return get_agent_plan<Agent>(lowest_supported_sm_arch::ver);
     }
@@ -524,15 +521,15 @@
 
     template<class K>
     THRUST_RUNTIME_FUNCTION
     void print_info(K k) const
     {
       #if THRUST_DEBUG_SYNC_FLAG 
       cuda_optional<int> occ = max_sm_occupancy(k);
-      core::cuda_optional<int> ptx_version = core::get_ptx_version();
+      const int ptx_version = core::get_ptx_version();
       if (count > 0)
       {
         _CubLog("Invoking %s<<<%u, %d, %d, %lld>>>(), %llu items total, %d items per thread, %d SM occupancy, %d vshmem size, %d ptx_version \n",
                 name,
                 grid,
                 plan.block_threads,
                 (has_shmem ? (int)plan.shared_memory_size : 0),
```

## nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/util.h

```diff
@@ -26,14 +26,15 @@
  ******************************************************************************/
 #pragma once
 
 #include <thrust/detail/config.h>
 #include <thrust/detail/raw_pointer_cast.h>
 #include <thrust/system/cuda/config.h>
 #include <thrust/system/cuda/detail/util.h>
+#include <thrust/system/system_error.h>
 #include <thrust/type_traits/is_contiguous_iterator.h>
 
 #include <cub/block/block_load.cuh>
 #include <cub/block/block_scan.cuh>
 #include <cub/block/block_store.cuh>
 
 #include <nv/target>
@@ -611,19 +612,65 @@
     __host__ __device__ T const &
     value() const { return value_; }
 
     __host__ __device__ operator T const &() const { return value_; }
   };
 
   THRUST_RUNTIME_FUNCTION
-  inline cuda_optional<int> get_ptx_version()
+  inline int get_ptx_version()
   {
     int ptx_version = 0;
-    cudaError_t status = cub::PtxVersion(ptx_version);
-    return cuda_optional<int>(ptx_version, status);
+    if (cub::PtxVersion(ptx_version) != cudaSuccess) 
+    {
+      // Failure might mean that there's no device found
+      const int current_device = cub::CurrentDevice();
+      if (current_device < 0)
+      {
+        cuda_cub::throw_on_error(cudaErrorNoDevice, "No GPU is available\n");
+      }
+
+      // Any subsequent failure means the provided device binary does not match 
+      // the generated function code
+      int major = 0, minor = 0;
+      cudaError_t attr_status;
+
+      attr_status = cudaDeviceGetAttribute(&major, cudaDevAttrComputeCapabilityMajor, current_device);
+      cuda_cub::throw_on_error(attr_status,
+                              "get_ptx_version :"
+                              "failed to get major CUDA device compute capability version.");
+
+      attr_status = cudaDeviceGetAttribute(&minor, cudaDevAttrComputeCapabilityMinor, current_device);
+      cuda_cub::throw_on_error(attr_status,
+                              "get_ptx_version :"
+                              "failed to get minor CUDA device compute capability version.");
+        
+      // Index from which SM code has to start in the message below
+      int code_offset = 37;
+      char str[] = "This program was not compiled for SM     \n";
+
+      auto print_1_helper = [&](int v) {
+        str[code_offset] = static_cast<char>(v) + '0';
+        code_offset++;
+      };
+
+      // Assume two digits will be enough
+      auto print_2_helper = [&](int v) {
+        if (v / 10 != 0) {
+          print_1_helper(v / 10);
+        }
+        print_1_helper(v % 10);
+      };
+
+      print_2_helper(major);
+      print_2_helper(minor);
+
+      cuda_cub::throw_on_error(cudaErrorInvalidDevice, str);
+    }
+
+    return ptx_version;
   }
 
   THRUST_RUNTIME_FUNCTION
   inline cudaError_t sync_stream(cudaStream_t stream)
   {
     return cub::SyncStream(stream);
   }
```

## nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config-version.cmake

```diff
@@ -22,15 +22,13 @@
 
 set(PACKAGE_VERSION ${libcudacxx_VERSION})
 set(PACKAGE_VERSION_COMPATIBLE FALSE)
 set(PACKAGE_VERSION_EXACT FALSE)
 set(PACKAGE_VERSION_UNSUITABLE FALSE)
 
 if(PACKAGE_VERSION VERSION_GREATER_EQUAL PACKAGE_FIND_VERSION)
-  if(PACKAGE_FIND_VERSION_MAJOR VERSION_EQUAL libcudacxx_VERSION_MAJOR)
-    set(PACKAGE_VERSION_COMPATIBLE TRUE)
-  endif()
+  set(PACKAGE_VERSION_COMPATIBLE TRUE)
 
   if(PACKAGE_FIND_VERSION VERSION_EQUAL PACKAGE_VERSION)
     set(PACKAGE_VERSION_EXACT TRUE)
   endif()
 endif()
```

## nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-header-search.cmake

```diff
@@ -1,8 +1,12 @@
 # Parse version information from version header:
 unset(_libcudacxx_VERSION_INCLUDE_DIR CACHE) # Clear old result to force search
+
+# Find CMAKE_INSTALL_INCLUDEDIR=include directory"
+set(from_install_prefix "../../../")
+
 find_path(_libcudacxx_VERSION_INCLUDE_DIR cuda/std/detail/__config
   NO_DEFAULT_PATH # Only search explicit paths below:
   PATHS
-    "${CMAKE_CURRENT_LIST_DIR}/../../../include" # Install tree
+    "${CMAKE_CURRENT_LIST_DIR}/${from_install_prefix}/include" # Install tree
 )
 set_property(CACHE _libcudacxx_VERSION_INCLUDE_DIR PROPERTY TYPE INTERNAL)
```

## Comparing `nvidia_cuda_cccl_cu12-12.1.55.dist-info/License.txt` & `nvidia_cuda_cccl_cu12-12.2.53.dist-info/License.txt`

 * *Files identical despite different names*

## Comparing `nvidia_cuda_cccl_cu12-12.1.55.dist-info/METADATA` & `nvidia_cuda_cccl_cu12-12.2.53.dist-info/METADATA`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nvidia-cuda-cccl-cu12
-Version: 12.1.55
+Version: 12.2.53
 Summary: CUDA CCCL
 Home-page: https://developer.nvidia.com/cuda-zone
 Author: Nvidia CUDA Installer Team
 Author-email: cuda_installer@nvidia.com
 License: NVIDIA Proprietary Software
 Keywords: cuda,nvidia,runtime,machine learning,deep learning
 Classifier: Development Status :: 4 - Beta
```

## Comparing `nvidia_cuda_cccl_cu12-12.1.55.dist-info/RECORD` & `nvidia_cuda_cccl_cu12-12.2.53.dist-info/RECORD`

 * *Files 22% similar despite different names*

```diff
@@ -1,102 +1,106 @@
 nvidia/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 nvidia/cuda_cccl/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
-nvidia/cuda_cccl/bin/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 nvidia/cuda_cccl/include/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 nvidia/cuda_cccl/include/cub/config.cuh,sha256=EYwE2J1Dxd8dVhpYWAXaJhTuD9qD8BEM_-WBNx3sMCk,2000
-nvidia/cuda_cccl/include/cub/cub.cuh,sha256=QBJzOd2WVvHev67I3aZ3taLr7DFBTOq4pW-o-Ep9B_k,4099
+nvidia/cuda_cccl/include/cub/cub.cuh,sha256=WKbpxbOQndRB1i-lmDxX_og7tOC2Ce1ZJsp0x8fhoXw,4132
 nvidia/cuda_cccl/include/cub/util_allocator.cuh,sha256=3j6KLVw1R_XHSdWxT_wE45Hm7SU8G5hhxtVgFlt87I8,29056
-nvidia/cuda_cccl/include/cub/util_arch.cuh,sha256=tRHPsTYkEm2soD9dxOcksVMDvT2Z-ytKs5q0K0PYh0Q,6229
+nvidia/cuda_cccl/include/cub/util_arch.cuh,sha256=nG_egh7LNqYrM8BRuPjk_LpD2a8erLrwwvzLdf9Ef9s,6059
 nvidia/cuda_cccl/include/cub/util_compiler.cuh,sha256=eY8xMPIbk0URcQM7fO8EuaRVHP86J1mpUykpx6rKuCY,3644
 nvidia/cuda_cccl/include/cub/util_cpp_dialect.cuh,sha256=lOjUgM7To0ky9WlDeq0pDrvaYs7xRUk60O8BqwBzL1U,6333
 nvidia/cuda_cccl/include/cub/util_debug.cuh,sha256=2JpdOEiqyHcxrzAVH2eNwBL5WgltJjzKqeEqiqYHx3Q,9578
 nvidia/cuda_cccl/include/cub/util_deprecated.cuh,sha256=GNc0vdKBLjhlxkOKNUKHWnm4DIubvpClLa4ObA_xsY0,3733
-nvidia/cuda_cccl/include/cub/util_device.cuh,sha256=VR0J2eQuDhNhvVWWJCZCN7tAaJ6CD5bScCJbcFMs-Lw,23006
-nvidia/cuda_cccl/include/cub/util_macro.cuh,sha256=7gXMY84zVo4MgLKk4uAtUAqQ_b5KdJt3Yh9xcEGTgj0,4275
+nvidia/cuda_cccl/include/cub/util_device.cuh,sha256=f-lqIpe1I_j9ZqN2gfPd56_PYFYfNDCKG9cdCPNpMag,23043
+nvidia/cuda_cccl/include/cub/util_macro.cuh,sha256=yygJuAWEv1dflrpiBJl3979B48EauavV0UXHkv-RyGM,4348
 nvidia/cuda_cccl/include/cub/util_math.cuh,sha256=mtXLJaHD-Dpx1ak0fi9fT3fNcnWpw2Ve9V1wJnI2szM,4476
-nvidia/cuda_cccl/include/cub/util_namespace.cuh,sha256=HhqdoiGI3XXbmkxZq_SXEVgdIT7JSddrRMVJI7Ol_MM,5702
-nvidia/cuda_cccl/include/cub/util_ptx.cuh,sha256=f3gvzXEgCPd34yGW8XWq3LAbem70_KBEoRmJFQ1JtP0,23119
-nvidia/cuda_cccl/include/cub/util_type.cuh,sha256=coeqw87056_v5kGLlo7GrIecgS8BpiC2iDSxJlfSPvI,43860
-nvidia/cuda_cccl/include/cub/version.cuh,sha256=ymCUCj2ssJozmXUiqfqvXWRZXQRoIJoziQII7e8vgd8,3116
+nvidia/cuda_cccl/include/cub/util_namespace.cuh,sha256=pI6smL4uqwsN7E6duXET_HGFw9RNHBZSjy3mAUEGt4g,11031
+nvidia/cuda_cccl/include/cub/util_ptx.cuh,sha256=tQURAZYU9hwmu5yl60Bn1K619GXVeOJQ0vZ3g8mM2HA,24522
+nvidia/cuda_cccl/include/cub/util_type.cuh,sha256=kuFJwJ4AmgyPc45abbudBb3NCxF02WpJ-qIr5BnStDo,45967
+nvidia/cuda_cccl/include/cub/version.cuh,sha256=VlplpvNmwTS3VhOvxarwnvKwZiz52rL2o_0aLNNxs84,3116
 nvidia/cuda_cccl/include/cub/agent/agent_adjacent_difference.cuh,sha256=A9HSbQ1Y9QZJ6oUqZcgxzBgQ4BWUl9dPtwe8OcDIEfA,9725
-nvidia/cuda_cccl/include/cub/agent/agent_histogram.cuh,sha256=kGKYgNd1WH69GXFvxrGXhqwdTFPEGPDShqojEOqNqo4,33064
+nvidia/cuda_cccl/include/cub/agent/agent_batch_memcpy.cuh,sha256=6m81brU2v6PBKe7DV0tP0ZCsrwgr9N5Wo6HbfXhjeYc,48960
+nvidia/cuda_cccl/include/cub/agent/agent_histogram.cuh,sha256=EfdxaN2Pwxr_c6vmT8K0ADqFRP8zT3vpHqy0dsPmz3c,33064
 nvidia/cuda_cccl/include/cub/agent/agent_merge_sort.cuh,sha256=yNwvpjjxVWHDYSakMUJxGto8uFFaWkAqmQUP9rOqT_0,26107
-nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_downsweep.cuh,sha256=xksAuhv0ZRHEAltm5RulbSNhynybHWDhrHhZjD1r4rE,29119
+nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_downsweep.cuh,sha256=qBmZLYiR_m_F7VpR8XF67730-jbUGqQf_38sHVb7UuI,28053
 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_histogram.cuh,sha256=6rvMfJMfa0EgCDNTCsEy0yK2jiM_vKepJKbVta6r7AE,9298
 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_onesweep.cuh,sha256=q6KsGWmvUONmtW1kPCmDyYJeVh-WOvLoc5654-IjxF0,24649
 nvidia/cuda_cccl/include/cub/agent/agent_radix_sort_upsweep.cuh,sha256=7V8sIiObsPeq-rQdJwkwhFoNguvJ9o0aU6ZG_VzBVJA,17878
-nvidia/cuda_cccl/include/cub/agent/agent_reduce.cuh,sha256=QQzNnCSxyGTWTljer1c2DTkk8JyvliPCJ72xx4eVDNk,17178
-nvidia/cuda_cccl/include/cub/agent/agent_reduce_by_key.cuh,sha256=NpZjsMm102JQ221Ho1oRz4Fr9x-iJCnH3hGc4MnIvBw,23463
+nvidia/cuda_cccl/include/cub/agent/agent_reduce.cuh,sha256=Ld0SrYsoEpAuYm8_KXFqiLxBXarplHSxDoyrjdi8Gjs,18284
+nvidia/cuda_cccl/include/cub/agent/agent_reduce_by_key.cuh,sha256=G_lkR2XQbdmB_jQJo8tGA8PDktT2v026nDl5rs7VObU,23479
 nvidia/cuda_cccl/include/cub/agent/agent_rle.cuh,sha256=-HzmvjwMnWFJfm61Gz2lRvzrrua3fQPzz87TxThKDTI,35265
 nvidia/cuda_cccl/include/cub/agent/agent_scan.cuh,sha256=fx9t2USDGRv1sR21aVxoZKjNXZrd-49g1XUClTYCbKM,18747
 nvidia/cuda_cccl/include/cub/agent/agent_scan_by_key.cuh,sha256=xCbg7ZeDMCf4_06lrazFtoN8ZROw442P2PsBJXiXn4Y,18102
 nvidia/cuda_cccl/include/cub/agent/agent_segment_fixup.cuh,sha256=D4NIfwQmdrfY4irAuaodO2Zh-afm-em4IWXhpikRtvQ,16588
 nvidia/cuda_cccl/include/cub/agent/agent_segmented_radix_sort.cuh,sha256=rIk3ocmuI9DGiHvLTVPna7JadSQX2Pnkz9bN-4I1y_4,10023
-nvidia/cuda_cccl/include/cub/agent/agent_select_if.cuh,sha256=5hD_UOoSH38zIN-MHHpIJ_z9-RIN1hhKLdmxICNcqmY,28925
+nvidia/cuda_cccl/include/cub/agent/agent_select_if.cuh,sha256=fMamf-8zpfUrRxI0NGdl2hVFECCe_KgsLSjXdCdVFK0,28925
 nvidia/cuda_cccl/include/cub/agent/agent_spmv_orig.cuh,sha256=q4A_vygNut8Kj24fqXSkOSiIKZOWMrHs59Z_ug3YGLs,27874
-nvidia/cuda_cccl/include/cub/agent/agent_sub_warp_merge_sort.cuh,sha256=oyTbKXx5wBgIAVVTeSZFOR9J_s5J5s07DsvrNdZqdTw,11325
+nvidia/cuda_cccl/include/cub/agent/agent_sub_warp_merge_sort.cuh,sha256=S4wIPHpNa_YCqVm4Mp6NBcwAOnFxQx4fDTqG7iAGs_U,11731
 nvidia/cuda_cccl/include/cub/agent/agent_three_way_partition.cuh,sha256=qYU3JiLfZt-JsoXqY3GkYMnntvDiJJE2Qk6uyR3lgpk,21856
 nvidia/cuda_cccl/include/cub/agent/agent_unique_by_key.cuh,sha256=7IDKkVjAcEDbEgRVQObMJkAvVbtgTyhSblfdYfR_y2s,21283
-nvidia/cuda_cccl/include/cub/agent/single_pass_scan_operators.cuh,sha256=vgR8pJ_S1xKpe7Wikti8Dy4wruEfS1hFrlzNHDAcERI,27546
+nvidia/cuda_cccl/include/cub/agent/single_pass_scan_operators.cuh,sha256=4JXEEp-CHwVd0p9IwgsEwEpqLHZhTO1Tor6XO8ihquY,29923
 nvidia/cuda_cccl/include/cub/block/block_adjacent_difference.cuh,sha256=9qfaeX5bCvTZu2Qb-A6VN-JT95uJMZlTqFNJOJuyPfs,52579
 nvidia/cuda_cccl/include/cub/block/block_discontinuity.cuh,sha256=K0X-uUPRbOvkIr1zeNMZdPnvhucT6-6wlcYHah3n97M,52893
-nvidia/cuda_cccl/include/cub/block/block_exchange.cuh,sha256=SXZ-aql3HhCiUtUM5qnfvkgMJztQ3sksG1kyMmhc3c4,50116
+nvidia/cuda_cccl/include/cub/block/block_exchange.cuh,sha256=z8v7USohDdLnaNf-_vh1laYEjfq51c_Jeu7dU3ZHoH4,50116
 nvidia/cuda_cccl/include/cub/block/block_histogram.cuh,sha256=6JetJlvo81HBHjAMifSe4ciyY1Nfhr7yBHNjGjvj40w,16713
 nvidia/cuda_cccl/include/cub/block/block_load.cuh,sha256=tyjP12X0FnQh5riifuh2RH57Wiaq_5VPnALzkK6u2rM,56629
-nvidia/cuda_cccl/include/cub/block/block_merge_sort.cuh,sha256=XeL1aTqR4Xj9MgtrbBkbNW74YHTQlOBCr9gLIk8dE6s,28743
-nvidia/cuda_cccl/include/cub/block/block_radix_rank.cuh,sha256=RVFpgyYSWXM3CKwtiTmkI8Ct1VxDecO5QVUegiOxPX8,42558
+nvidia/cuda_cccl/include/cub/block/block_merge_sort.cuh,sha256=i7ZxaufMs7yOEaSD_jU77zgjwjbAYk2qWwtasOppVRk,28724
+nvidia/cuda_cccl/include/cub/block/block_radix_rank.cuh,sha256=AQHSsHryWK0Rmw4Xz-5I5LNZAC1iZ_eS2yd9NbAT1Ss,46271
 nvidia/cuda_cccl/include/cub/block/block_radix_sort.cuh,sha256=EVFWcDVSiZyQzqniX86_nMX8YkhJfHpZtC2DktQe58Q,40081
 nvidia/cuda_cccl/include/cub/block/block_raking_layout.cuh,sha256=SU6b1p6Mkfy3V61hWQaNcyA3pwWB7WgxBRTdFUBVVTY,5964
 nvidia/cuda_cccl/include/cub/block/block_reduce.cuh,sha256=t4KWa2Ryht-kKEKMqo6yTxlE7BQvDwLo3dNBKv_ffes,25510
 nvidia/cuda_cccl/include/cub/block/block_run_length_decode.cuh,sha256=xRye2THxjhoX-titRpFe9cJHFNwTC29F6QDmCMRYqYY,18949
 nvidia/cuda_cccl/include/cub/block/block_scan.cuh,sha256=vuCqd91Zk5dhhynSnjGP_LK7fXkoqDnoJeePqvsUD38,103189
-nvidia/cuda_cccl/include/cub/block/block_shuffle.cuh,sha256=pwtwHb2l6lW29lSvfSKrvuKY7h3CDgiK2xP7gAlXt9A,11727
+nvidia/cuda_cccl/include/cub/block/block_shuffle.cuh,sha256=mdk3hq0etGcMSlJc8emNXCfeQYv_sT9ET1dPApiZOL4,11726
 nvidia/cuda_cccl/include/cub/block/block_store.cuh,sha256=Yyizys99SWTm4LwxKSAOU2Y5pcUi3GOm1sK7ztdMf-I,44245
 nvidia/cuda_cccl/include/cub/block/radix_rank_sort_operations.cuh,sha256=WywSdCmZCtc8MULg802eOL8scWGwx13WUIBhicU2U7w,5732
 nvidia/cuda_cccl/include/cub/block/specializations/block_histogram_atomic.cuh,sha256=WDotjXCGrXSqhm9y3gaeb8gwWxOmeVugf_Y6LlBQAIc,3154
 nvidia/cuda_cccl/include/cub/block/specializations/block_histogram_sort.cuh,sha256=mdO74MCvxWnu7wGeABuV2mB--kQ81E1N1krI0frD_6U,8229
-nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking.cuh,sha256=l0hSAqjymSD3LPfcrtEKKTsIv6fsICsxTyOG6yvqEmE,9595
+nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking.cuh,sha256=LfaFEQ95hMUrfOEw4dUNUjSDkqUSeC01MEMUsKtJ3g8,9610
 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_raking_commutative_only.cuh,sha256=HjLC4uB9dGn4y7DIC7XCtW2tHCf9lxDP6xle5vzuRmc,8334
 nvidia/cuda_cccl/include/cub/block/specializations/block_reduce_warp_reductions.cuh,sha256=iItXUGvg3sk9T3VlXUXC0YpPpgV1dlQO0XT3tse5kgA,9697
-nvidia/cuda_cccl/include/cub/block/specializations/block_scan_raking.cuh,sha256=reWWtqOFM1PLgJdEOrEuGfSlQPVjdN-gNjuZQQSnrUQ,28293
+nvidia/cuda_cccl/include/cub/block/specializations/block_scan_raking.cuh,sha256=UDV5535Qy-7Bx9gPDU0wv2fcqTz_7DGi2m_UcG94E58,28535
 nvidia/cuda_cccl/include/cub/block/specializations/block_scan_warp_scans.cuh,sha256=MKMXx6wRwqYGVZnycYLS50S0Yqn-gP61i6AIyuLIUm4,19175
 nvidia/cuda_cccl/include/cub/detail/choose_offset.cuh,sha256=N6Zo8Q7z0sbSAxIchTd2T0OyXppK1rVuUUrSqU1Ve_0,2581
 nvidia/cuda_cccl/include/cub/detail/cpp_compatibility.cuh,sha256=JuloMrg7UXqbmZgUV2pZ477RRcK1ZNqrNoQe4Ozqr9Q,874
-nvidia/cuda_cccl/include/cub/detail/detect_cuda_runtime.cuh,sha256=4BhROKKy6CSx7LmnNXZ0_6WbUpSsdCQ70_S9Jx3CzMc,3476
+nvidia/cuda_cccl/include/cub/detail/detect_cuda_runtime.cuh,sha256=R-e3pyqrJSU_bCY-ZYAj_vBzMNYR4YtMwuVcSLr2g3w,3665
 nvidia/cuda_cccl/include/cub/detail/device_double_buffer.cuh,sha256=qm38dNC77K5LSf3QLmTXyGaYPm1EqjBiYuvkzH7C3To,2698
 nvidia/cuda_cccl/include/cub/detail/device_synchronize.cuh,sha256=yKZHV3gFQ6elvsCH3498cSZFI6rPhV0ePiWT1iVJVYY,1926
 nvidia/cuda_cccl/include/cub/detail/exec_check_disable.cuh,sha256=zQNBZ-1Ap2cK5xIDbzU7mvxdZ0_EmIulp6BkNYe-oMY,1181
+nvidia/cuda_cccl/include/cub/detail/strong_load.cuh,sha256=StUd0eonWEvIENaHRT0ntFwhxIGGkquP0wNnA9bL4Is,7278
+nvidia/cuda_cccl/include/cub/detail/strong_store.cuh,sha256=tFLLH6ZM9kzRvKbp6SBnnejc-BatEEvm7xnNbubO5Js,12231
 nvidia/cuda_cccl/include/cub/detail/temporary_storage.cuh,sha256=KGaKde9oZhI-f4tqs14UFwQPyRb-wiIYsNCevXkbjQQ,8634
 nvidia/cuda_cccl/include/cub/detail/type_traits.cuh,sha256=8BIXZBy37i2kxUDYPizNtep3l7p3aE8Z2MMmb5vpW_8,2485
-nvidia/cuda_cccl/include/cub/detail/uninitialized_copy.cuh,sha256=pHAB1FU2slHm-9WQprzqDakpUY2kLFyTd2lyGPQaaBA,2492
+nvidia/cuda_cccl/include/cub/detail/uninitialized_copy.cuh,sha256=Ow_92GaDnIgWnN7JV8lFNdOIlYQ2sVUE8BNXF5EAJdM,2693
 nvidia/cuda_cccl/include/cub/device/device_adjacent_difference.cuh,sha256=I2tvsIlWZkrm7XdNaK1fV6lWD6_ETaLpNDgzU_Nmbbo,26211
 nvidia/cuda_cccl/include/cub/device/device_histogram.cuh,sha256=jqqnoikVptAOocoSupZDr63o7Y3AVJvO1IgYv1zKK0c,68310
-nvidia/cuda_cccl/include/cub/device/device_merge_sort.cuh,sha256=uvTOw3P-PybW21VymjHDpjI7YZ8A2LdX5XpZcVKtYlQ,37131
+nvidia/cuda_cccl/include/cub/device/device_memcpy.cuh,sha256=6cjSCLKAiLND6DXBhz_Kl00nmzPVcFGBeWDxaESL62k,8296
+nvidia/cuda_cccl/include/cub/device/device_merge_sort.cuh,sha256=4ii8cSOlp78x_2syZjaYPit1RvelRxJNlP6FqTHWA28,42009
 nvidia/cuda_cccl/include/cub/device/device_partition.cuh,sha256=vTiPjnYdRy3R0e6-V7lkxwcVm8vvryoM0V5SYxPKCS8,28990
 nvidia/cuda_cccl/include/cub/device/device_radix_sort.cuh,sha256=uhueqCGSuQ7F-Nc7Lc4BD_tTGwDyUwEVeBqvrrUcqA8,54487
-nvidia/cuda_cccl/include/cub/device/device_reduce.cuh,sha256=yewR9thyCFt_bKkNIvXnlt3ZQyDsh6I05C9FIN5FsOY,47219
+nvidia/cuda_cccl/include/cub/device/device_reduce.cuh,sha256=bDEzAF4XODwOi4C6ckhL41BoSKe53jPuNCG9xHI8jlI,48146
 nvidia/cuda_cccl/include/cub/device/device_run_length_encode.cuh,sha256=dyQWiqPnvShwoquGFJ-5F4ZoVsdXUCZ69GVHYXijbiQ,17929
 nvidia/cuda_cccl/include/cub/device/device_scan.cuh,sha256=C9GGuvoSH3RT4ExCXvjvxGFAcqMAacFwDt_snwZQSl4,85061
 nvidia/cuda_cccl/include/cub/device/device_segmented_radix_sort.cuh,sha256=Wim8EUMkuiPd8sSccWh7m_bgsXIpkA505lrc1HJF3Jc,73338
 nvidia/cuda_cccl/include/cub/device/device_segmented_reduce.cuh,sha256=Ij1cvJUqKyXpyRgXyo7Yp7yyq0OdZk9jtwLu3XSW6x4,46499
 nvidia/cuda_cccl/include/cub/device/device_segmented_sort.cuh,sha256=UwHmlzFfxcSelDSgZr025b42LchmZWVAbiobgj8jMNE,130046
 nvidia/cuda_cccl/include/cub/device/device_select.cuh,sha256=uPBAHrTjXd5WQG-L8M0_i9ILM4G8ae9ELfw8Kh4eKnw,40912
 nvidia/cuda_cccl/include/cub/device/device_spmv.cuh,sha256=EPBJqxKjKof2nRNc4FspluY4cHnHx1ANMeWTXiGaFUM,9516
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_adjacent_difference.cuh,sha256=jx4rD2Usw4F4A6a2nV_thDKpBLGk4jU9Bpn45WU-lbo,14322
+nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_batch_memcpy.cuh,sha256=4_GyZYe0JyNH_REKJdHGYC1vml98yVXtT1toRVkr6G8,30982
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_histogram.cuh,sha256=gAvA-hIRf_f8Ghk816SOqDKNOoR9i-HKRWkMtdhGkGw,64634
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_merge_sort.cuh,sha256=HFR2WtHsrAT7NgYjwx22OAncNJtM0Y4r6wsWWAn22sM,31943
-nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_radix_sort.cuh,sha256=2RrwlujoLSz-0LQ7JD8wWpGiqXndM00Q6Y0psajBkEI,103689
-nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce.cuh,sha256=eAjqZzuSchiu3NE_frBirVbcK5R3xRrZOU_n9KUUE-g,43479
+nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_radix_sort.cuh,sha256=90xtKq4L5Asax-C12O1p09ITUtynv4FyereR82gX9X4,106789
+nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce.cuh,sha256=HeTlV2Xh58jlz3RbFNse0rcXMNfTgw2_ZAnW3GszuyI,43564
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_reduce_by_key.cuh,sha256=Z5dP8zfAH5t1Vf70w_bQ67twGz3_6c29XirOTIpB0As,25820
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_rle.cuh,sha256=X9PrWcJB27lsy9H0bOcydVcS5HY1E1MB2ZpHxpV1Gxw,21927
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_scan.cuh,sha256=06dhK0Zhsw7oNQAwrDRKEFu5P5m_oiGPs93mbFyw2aE,22771
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_scan_by_key.cuh,sha256=UcQcKqu5cw9oupMML4PysNdugpGXvdVp3luUIKab64o,23645
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_segmented_sort.cuh,sha256=VpAqM3e6FjymEqrLXpNTr0a6GNgQnikfTSaFD7C-bQ8,67162
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_select_if.cuh,sha256=g-PTLmiZCY_j9Tpxcup42lwSvSf6gKrXs_5HwZTOvDs,23154
-nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_spmv_orig.cuh,sha256=uN-2MdqxCj6p50RQEA4JR20JyqdYMN0a3mFcdxRjkRU,32807
+nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_spmv_orig.cuh,sha256=EPsETs05k5UVrMzTFN-7E1_7_Q5DW9pYaaaDSybm8MI,35878
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_three_way_partition.cuh,sha256=kfHpBaesfgxoupjegAiC2aflAxnkrTlzs9hd1SCw-is,20642
 nvidia/cuda_cccl/include/cub/device/dispatch/dispatch_unique_by_key.cuh,sha256=IMM85xHZCQlhYVJwjkpdlGS5YDJ0tGj-eQjqXBjpDPA,22728
 nvidia/cuda_cccl/include/cub/grid/grid_barrier.cuh,sha256=IRGX1OEmM4W9NDFxuhH1-2gId1NlEoeJG0Lqxe4nVjg,5730
 nvidia/cuda_cccl/include/cub/grid/grid_even_share.cuh,sha256=seJ7nCPuGtoTH6B9feJocKngs_EwxC9nDQAoOZZ1Xz4,8287
 nvidia/cuda_cccl/include/cub/grid/grid_mapping.cuh,sha256=wm0QeZ-CEgcgKMh0GI7p58LfYrAQkYXcjcv4CvByeao,4696
 nvidia/cuda_cccl/include/cub/grid/grid_queue.cuh,sha256=JK2_Gc4KphfanDYipyG5rv47TaZbZjoon4S_4CvlWmc,7886
 nvidia/cuda_cccl/include/cub/host/mutex.cuh,sha256=NP9twpF-1L1wKP08j6vkpcckaRhJtZMe4G5-yW7_FXY,4325
@@ -106,29 +110,29 @@
 nvidia/cuda_cccl/include/cub/iterator/constant_input_iterator.cuh,sha256=qrWbsv9zwWYWmLE--76ih6RJkT3z821FNWmQgRWsENE,7558
 nvidia/cuda_cccl/include/cub/iterator/counting_input_iterator.cuh,sha256=ML3XoC3u74_GL1AAVAssfUolpW0sAFFG24MXroRDVho,7277
 nvidia/cuda_cccl/include/cub/iterator/discard_output_iterator.cuh,sha256=OaNwpnsIhfSI3U-V-r_zy4yYv0cYgtJ31_Ity15al4I,6543
 nvidia/cuda_cccl/include/cub/iterator/tex_obj_input_iterator.cuh,sha256=9fbpzXDnSyFT9k-TZBoBDxEXGeVFQBvnty--GAVjKZQ,10891
 nvidia/cuda_cccl/include/cub/iterator/tex_ref_input_iterator.cuh,sha256=UNDFGNI-4EUO2Yq7ly3PVZbuvDqmG3QaKPxdJiBNxyM,4581
 nvidia/cuda_cccl/include/cub/iterator/transform_input_iterator.cuh,sha256=w0UAOs08CSxnEQGHcXvH0yqJk1HfMCvOAbrtuXTPSLQ,8378
 nvidia/cuda_cccl/include/cub/thread/thread_load.cuh,sha256=C3tDxla8dWlUisQYh69pJF5wgIN7tjSzC3NZQKWolOA,18053
-nvidia/cuda_cccl/include/cub/thread/thread_operators.cuh,sha256=9EEVy8-qa42zgyYGtaE1A8D_cvY2wM1okwyi6p3-LQ4,11134
+nvidia/cuda_cccl/include/cub/thread/thread_operators.cuh,sha256=dcy1vEm6admmnNPBJtrba1hoh-H9qNWUTB1GRx9Omvc,11494
 nvidia/cuda_cccl/include/cub/thread/thread_reduce.cuh,sha256=1j9BW7qdmoUhE90PZCcwXI7Hna9QaDaFbn52N96Pt5I,6260
 nvidia/cuda_cccl/include/cub/thread/thread_scan.cuh,sha256=UApS0JYq7OeoSO7li4ufcchMErwauo-JgUp-EaraKnE,10435
 nvidia/cuda_cccl/include/cub/thread/thread_search.cuh,sha256=DOz_KwvYOFCIyxRk1tfdy9wUt6ZxHJypR02Jh_ZWk98,5630
 nvidia/cuda_cccl/include/cub/thread/thread_sort.cuh,sha256=VxXRlIMV6-5NUPwCwgBz7NBeJ8Quj8d8W5kTR6Evfeg,3543
 nvidia/cuda_cccl/include/cub/thread/thread_store.cuh,sha256=gKzGBK3fBDoovK2y8y2yBzWNAx5N0pv8B1-pnXvNvJA,17566
 nvidia/cuda_cccl/include/cub/warp/warp_exchange.cuh,sha256=2qMbycc_K8QGnvy2DJJV3H0cjuYck279FjZ6ENjDhsQ,17966
 nvidia/cuda_cccl/include/cub/warp/warp_load.cuh,sha256=p32N1hQ3rvmuT71iQ4S6a8r-JC2Ug5Tf5SrWpcRuxPA,25456
 nvidia/cuda_cccl/include/cub/warp/warp_merge_sort.cuh,sha256=1OqExqUY5DyTEAqyoW8wGreI8ib_1JR_nq3cPKqBO1c,6341
 nvidia/cuda_cccl/include/cub/warp/warp_reduce.cuh,sha256=X9Atp2sANKVDNg9Lq9sfg9sXgkNojGOIGpEZ7xTN3hA,26349
-nvidia/cuda_cccl/include/cub/warp/warp_scan.cuh,sha256=l71Ph7YqfxIQMPPhKL0FPMU1-c1eMqvO1t9xZPR6q4o,38677
+nvidia/cuda_cccl/include/cub/warp/warp_scan.cuh,sha256=BUOZDg4p1jHgkIG61PpSpXTmtnIR2YxEbjdute87q3c,38675
 nvidia/cuda_cccl/include/cub/warp/warp_store.cuh,sha256=yDi09zhArkEMIRcdn6FsSMnOBswKyWk2C5ITYxl9Mls,20347
-nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_shfl.cuh,sha256=xqDMy3-F0qE-AKr_jqcDdf4mWwSYO0Al10aFVZ4JgvE,24530
+nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_shfl.cuh,sha256=z8Lh0ok2in9MQqXlL_4sza7ckMDrPPuxeSWO4XQASX0,23024
 nvidia/cuda_cccl/include/cub/warp/specializations/warp_reduce_smem.cuh,sha256=xJ18fHii4w1MvcVRo2Bm30szyVIe0xV7E0K1xMS_nws,13923
-nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_shfl.cuh,sha256=9Xh44WkrsA5iU7hRRUPb-qav0lXvL6kyca99fFln1EI,25037
+nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_shfl.cuh,sha256=SENrUs6UuYg9qAtXQHjptJYqOPO9gBrizf88M-9QcoI,22355
 nvidia/cuda_cccl/include/cub/warp/specializations/warp_scan_smem.cuh,sha256=lhs-fbTpX0X3ql38yIC3-CmvpDfwPwKiohO6lJwBKug,15617
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__bsd_locale_defaults.h,sha256=vPnHf_i4BfSM_T9ZlOOkjwphErzTGm9ZCu8VvkbmCL8,2121
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__bsd_locale_fallbacks.h,sha256=QsHpd0FVlR8ksp_6t_WxS22aQRfzlY7klUrNn_Pmlzg,4100
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/complex.h,sha256=wVwtYKqQH0ILXU_JF6be_NIogOARA_WkweZraEfNsXs,755
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/ctype.h,sha256=XiqOqrXolRKLG8sbGwsfkJAk-cgsCCuQ_qUiCIdG8d8,1165
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/errno.h,sha256=M-KIqaKFMR12qbtAUjbLQ3euDEYxKU9s3-a70C6khEs,5160
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/fenv.h,sha256=GPkOJnJRSuMHFdZPpQ0b4WiGr4W-g3MbOEC3ahbLSso,1879
@@ -143,36 +147,301 @@
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdint.h,sha256=nUzh9MpfQ4ml2ugihv9a7M1h7zhs626eDxstxxzIZzs,2395
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdio.h,sha256=lhCXEFbyk77kh23hFx_mN7kzI3u6zfQQhBzBUuNUm4c,3541
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/stdlib.h,sha256=mmh82pa200twP_dau6ZSyogGDTq4NhjYXiU3AC-a7mI,3696
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/string.h,sha256=rN1U52vlM3hsh5nivnUciM8s0EWPcbjbOeYxl8ppUzk,4821
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/tgmath.h,sha256=apzZqK3poat7E3xz_Lu68W6lXBGYnKxVQ7DwYqkcT24,748
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wchar.h,sha256=jc-UJmKth6c-gom3Q1DwzXFXCDuUlz5wURWus6NvVg4,8573
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/wctype.h,sha256=Bvf6aJp_cB8yBHlOi1dBc60GiM0wRHAchKA_81RfIhY,1570
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__algorithm/swap_ranges.h,sha256=JX4G4bNA0Y2v-j2wwpKJdAIkxE4Q-ZZDts-YPtn0Vuc,1143
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/_One_of.h,sha256=WYbtbcfs5QP8YlWb1amCjDAiR9FcnrQ8cswLCr4kHZw,1238
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/__concept_macros.h,sha256=8ZN1j1lGIQXGJIMkZ8hTl3f_klGehKrod9tcxPjX-ZY,14723
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/arithmetic.h,sha256=4ethDBgR4X3sbBiXv1xK2DnIPLOQt668HgzDomHG2Fw,1926
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/assignable.h,sha256=NkOIeRIZbW6mlIAYcw8cx48DktVGtpOTCHNR35MVdp8,1970
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/boolean_testable.h,sha256=GdOusXfV5-wUhP7LCyJ5cZZCPnJxXvsdSWDi3ExmRrE,1753
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/class_or_enum.h,sha256=bmberGIWBT4pVSkyTZu6ftLdp_z-wXSkZoZao0-mrtk,1563
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/common_reference_with.h,sha256=3NT_IDWSRCEbc7jWfVNOl4fPK-ggQi5uVrBLSRzk2YE,2292
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/common_with.h,sha256=hC8Dr_i1Y3SJAWfHzFJZb5Sy0jPJNFK5KKBxxAoETXQ,3211
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/constructible.h,sha256=m_y73CFixYNszSY6xGXmCedrfxttCcnCiFaMoLJE02w,3768
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/convertible_to.h,sha256=uaS3m0U1bJOHWHOUnkViJXU1h0VRoLsoAb2d4SKqxLc,1955
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/copyable.h,sha256=Bni6cPpVbLvAvdnXDu7zn_kUuS_ezD-RHNsEnEYK4jE,1651
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/derived_from.h,sha256=95D-C8jK7hRM13qMfE5NDRhg3jRvxEN_y6ogSn1F55s,1634
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/destructible.h,sha256=5uxodfruSRvi20_nVdkChdB_e-EdF0rH5YyHjShb9_s,2167
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/different_from.h,sha256=bFVlc6oOCkl4Scgq6-dvM4EgWjkTGhAzVr_g5cJPACw,1124
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/equality_comparable.h,sha256=Y5efheGoEi2ls7GNJfVnWMLfGNGvwqjrjknEaO43ngU,3637
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/invocable.h,sha256=IAHqlpgCesst3u0yY6eIH-WtbUZYFFXXiygnvrgc84A,1843
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/movable.h,sha256=immmj6-jlFv0Ya5HJNkrhm8vNjDOig46pu0NagLfiX4,1557
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/predicate.h,sha256=ouqA5piYQ1tp1xV73NJl7bwRdWqnOIvYyB2T1ALf7AI,1555
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/regular.h,sha256=D8-CuavILZ3kxhnEjQICyaTmOd6Y4rr8w8QF-18V4QQ,1393
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/relation.h,sha256=Gq5_TeIxzFxjVBSd9LRU5QYyQYeWtY3mxzD5SVwopMw,2078
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/same_as.h,sha256=Pmz8hYvON11vJS05dlD1syUd5HRI5oJQIt14mM5q_88,1170
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/semiregular.h,sha256=CMRyRvOyPA1ishgIIgz9ZIfwG2j-oGc0PVdyvRjHb2U,1410
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/swappable.h,sha256=rTLJCjdDtM-PARHOKuEFA2rc9XFDZrUSs4wqkHSItd8,8118
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__concepts/totally_ordered.h,sha256=gy3xYZlSm6DwkD7OXclS0Eb3ajr2PMF6wMl1SRgfySw,3667
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/atomic.h,sha256=b6Ri2CwPPx3yAA-ZroROjsFBRK-1ARPzLSHFWGJh2Fs,10088
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/atomic_prelude.h,sha256=UHNIoOkOt1H99IcscfiBEwuZ4MTCLuAPdmx6MoZGsl4,2072
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/barrier.h,sha256=31SjlN93-RGY-C9KsDFx9R3cN7A-vdN7EVuF3Y4KA50,35638
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/chrono.h,sha256=KJlTI3oBhjOVb5B4pH9H1j_aYbGwSyhwLQw6V71UO5U,1783
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/climits_prelude.h,sha256=aQkk0LtafjjgezS_A9IR8E0Oxwq8o65zdHqBQ5rDOws,3473
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/cstddef_prelude.h,sha256=Y1QRgeZZyE-INVkPk3Ybz9SBg0jkMAvCznosykDZG3k,1020
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/cstdint_prelude.h,sha256=8ok-tRaDQIr4WU0wny6w89ZKGP4ZOy7TKgCMsHafLKE,2872
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/latch.h,sha256=P7MyKbb20Kjc1v_N2Z4AsS4aSrDK1F-sagJXG2yZifM,1005
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__cuda/semaphore.h,sha256=Ewn0dk5cvOxYEzkz-j08oGncFE2oWWfopYnnx37OckQ,1562
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binary_function.h,sha256=XcECiDTLmNhpBF-PE7oVfZyRrfDt6U0XkUWBKoF0NaM,2097
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binary_negate.h,sha256=vBFL2ZQThabQCNWjX4F_ZhfIRChEkfZw4WTiKlZXN1A,2014
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind.h,sha256=cakVnlhimHrbsOxGgEnPA3Fg2FQVmFooUkTyiKHQh48,13436
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind_back.h,sha256=dTCRQXss4l78RH8mv4CECx4KtGbMhZijdAUkqtZKegM,3449
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/bind_front.h,sha256=UoSbfr0aB8MN-ySnC6eglsXK_BQ4VcNrODdrUwUpSHY,2565
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binder1st.h,sha256=JHwzaPATg8-xAXhJSkvVzBf-aEzEzqs5vcHenzDro3U,2158
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/binder2nd.h,sha256=Do5Er1aJpeAL2A6vJnm2e4YF81gOQC9Dl9pVyE5BC0o,2137
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/compose.h,sha256=sqbEZr1doCbrz9RtlLlek962r1qzijVDU0gDEb-pHUE,2484
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/default_searcher.h,sha256=Jh1dAi6PS-4oztLvkjOT3SFLRByFIB8xvLKOr9SyYNI,5746
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/function.h,sha256=SHkQtGIPBB7foZbP-BVl8n7aOx4bePYsKXyCzrAOCGQ,39611
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/hash.h,sha256=bOlK86f5VFkRzybXsxQ6p1prttptPDA8XwR93HWJJkk,20163
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/identity.h,sha256=YWHNzD-uCFF-75Q8--R2ZtYFhfLBNVh_Vea4Z9jntCo,1418
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/invoke.h,sha256=RUjR1Q4GXT_pIlZqUhbItMM8XJPoPPIRT6fFinAL4bg,19303
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/is_transparent.h,sha256=NXy5ezqcmlg7z6i1R5lf-5tGLGvOSlzFhyPqMN2KwSg,1163
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/mem_fn.h,sha256=56y4CihnolpZpGlYW3WWzq0AVBtJ5jYvOjBzzCdD0MA,1751
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/mem_fun_ref.h,sha256=Gv1h9X68JsbOHYtOaPQGSPtf9xIzdBUXRrHq9n5ZulE,6105
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/not_fn.h,sha256=IjOAltnrt4KOOwGfa1YnHGFSn-jDFgH9sYrx1RnPhgI,2070
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/operations.h,sha256=ID93kwADYyhXXUaCUzbwPOLatMaRgvkpzATOpCsGsn4,19272
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/perfect_forward.h,sha256=t7PEuCGRwSwXsXWW9g6qLnqMYsRGjWBY3wXk2aFBXoI,5464
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/pointer_to_binary_function.h,sha256=94OTAzb0cgQKsqUFNDYM-5-i8tKtIdrq9dSaK8wnpjg,1762
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/pointer_to_unary_function.h,sha256=Ncnoou1Bo4Y5cyNUWhMskEAqWyNEB0ViBRQ2_r1bQeM,1745
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/reference_wrapper.h,sha256=jNuofba0thKnr7aCNYalA4XG44Bs188GXoKPX5tKia0,3093
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unary_function.h,sha256=fgWdlXa-aqPOQ0mw3F5wKRz5iOoqGsVTXmMGFp42gYI,1809
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unary_negate.h,sha256=rmuYb9aJqUaUrvX4ul8VfOgYp0AINokV5OClsI0dV9s,1816
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/unwrap_ref.h,sha256=9RXe7pa9LDGxyGA1kJAmF4eA4lWB4cLLEY2L4v_VFXA,1695
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__functional/weak_result_type.h,sha256=sFn5ZmjtYhs34tHvE6uwZTPm9QGMKeQlB7p55FBo2-A,8734
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/array.h,sha256=ufPI6ZUmaKiIpJGQicrNlpreE9J8sTaXkOrTGGfVQsI,867
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/get.h,sha256=AGOI65c4m6aXwR1ZNpkHPNVUUV97MVUHUYPd0ubURok,3303
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/hash.h,sha256=mgyaKjntJ0igV4IZBsUf5kW4Uo2e6y00aweSGjBWXtc,822
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/memory_resource.h,sha256=9ahyYIu5i8fmeX6yUB0amG9oI0D8JurRUlg74KuoD4E,919
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/pair.h,sha256=WFc-Utp4aQYhMqiK5l3nkSiBf43YcxZhp7F5QOUDXH0,829
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/span.h,sha256=9ETAUy1sz7tQa8bzpyNgMBsOLZrnLTyPCAGNYlJlsIw,995
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/string.h,sha256=NC2odfXOEZgBb4sHcXBSL0TV7oiDQ2YsoZ7n_9O5jVo,3041
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/string_view.h,sha256=ifmLMSBFtaObBGvtYVt_5MO5QYwi-GyRd8VH3xdho7M,1725
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__fwd/tuple.h,sha256=Mhsm7nRIeq1KfsPveSHliv9_sM8YHuzt7gCnkN4J5BM,894
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/access.h,sha256=sSe87PN4YLljv9SDSyxyUX7JJZDAcU3U0Jn4wJTI57g,2806
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/advance.h,sha256=5W8iIvfXjbZKJENjDKkEvxZ-YAIH8BmZX7JLJdPvor4,2233
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/back_insert_iterator.h,sha256=FqAQ_QTd8Shm5rGBHYiwHZAxCvhO0j69MzljFs-Yw4s,2490
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/data.h,sha256=acqvi-vj6WtC39gWLIlDpQ2HgsddCL9DMUqJ5heygCg,1540
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/distance.h,sha256=g-h5RcPty9TQ72UNT_uZx2ov1zdoYorXwXbN_JNcVUM,1787
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/empty.h,sha256=pdFIw2PSWPxXwtauO5lwP5UtyMjCnCfCQqz1Huj7Z4I,1489
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/erase_if_container.h,sha256=tslW5BDSTRC184y2jEZAEkz40IyFr-nt16C65NWryeo,1337
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/front_insert_iterator.h,sha256=nst7s5-wAKasTgm6MOv2vPaZliKKMM4AS4xVquh5FsQ,2505
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/insert_iterator.h,sha256=u4UAeIkRpiOvmABbjXKmlCN3jrHcUGGd8ZplTtMw0YI,2595
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/istream_iterator.h,sha256=FlvuVMMIwZQfhQw5PPKAENFNK6ZapGrAZidUiP9o60U,3551
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/istreambuf_iterator.h,sha256=jvbNXuWqOxJmn-cOP7VEh0vDEkL8ijRud-jYydRc7iY,3757
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/iterator.h,sha256=tVL3NpfmK_XURFPxMLp5bB-A6HXuAm6rdmRH117Xx3I,1218
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/iterator_traits.h,sha256=8yYKd4af_ul1hgVDLRgZqgExJiQxnLMGwlHXsRc7UXY,5952
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/move_iterator.h,sha256=xGsS2GS1QJFlGHWvR5Eu_Ax1JBDyl1byPlG_1wbOFxM,6437
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/next.h,sha256=VIA_iqTgI5B7YkSt9aCxWf76XN4k-ndiXLUwp3MsX4g,1431
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/ostream_iterator.h,sha256=iTUtTwVuPIIC2Z0jLgJVziiU4TSXObNIcXgAegGZdYE,2383
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/ostreambuf_iterator.h,sha256=sE-cZx3fpgo5RZ9j2-iZaey5xmEkRsrb6tjmk27-g70,2712
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/prev.h,sha256=wWzkSZGExBMV6EBIewwiqmZHkRPOTyq1PboC2-Y-db8,1431
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/reverse_access.h,sha256=JbZuabYCuPkmom60F3W5puoRVuV5ui8tL8HDtI-KHs0,2834
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/reverse_iterator.h,sha256=a-uXtWUVSlwGXjsJLvSKnR19HsTeT1wO8Ir9heGRK_g,7422
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/size.h,sha256=r-6kV2UgIG_Dk0nsyzRVTTEUl75vEIGfeqauvDb18yo,2172
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__iterator/wrap_iter.h,sha256=5UEGL2CFe0vcExbkqOK_dwZnzmTTJrp6ZF5hR6Vv5aQ,15990
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/compressed_pair.h,sha256=kAp0jxpAHUTiYLs1CKtQCzqsOKDhhRV76m6sKX5VqXY,9718
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/config.h,sha256=VTBEACF3KlK0Cqm_An5SWUfQLMTAI8lB78kBfabmlAw,10600
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/default_accessor.h,sha256=3EQLkIfgu88y5OFoHK09hrdtE3AJgVn_l4ejWUe2qXw,3367
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/dynamic_extent.h,sha256=3jeGjRypdCCa8cZLpDLTvHHhVorc6DmxFSs1tjT2o58,2897
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/extents.h,sha256=3jrcBVwFlz-lCYEOXnZ_6alKcuYTDkCy74RB-Pcm3PE,20581
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/full_extent_t.h,sha256=nm1ung403pFHuxyop6uCevckaWSiLVtNpliDlF4k65U,2559
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_left.h,sha256=OGmLUltLXNwyVLtxMtiyEsZvXOMQPvmQ-m_NBm9TsS0,10227
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_right.h,sha256=YCf5aNWW2APeteUsKmZasmgB9weADzWNCI_Hmt0Eh3s,10542
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/layout_stride.h,sha256=RoGiownVapWAWDllCaxtOG3Sg77Z4zISvFZLI7wkLGE,21746
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/macros.h,sha256=Secs0R5X_MUxLaKq_ClQ0FJ31kham2E9NefB98SkGWs,24869
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/maybe_static_value.h,sha256=4il4TQbC5J7QcKONqqkWIu0WJWynw3CfcDh9gyDzdss,6174
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/mdspan.h,sha256=42CGrrbRuAQmU4gOY2byjIeFg9CvMiLu1gCxJKPQ5Y0,20990
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/no_unique_address.h,sha256=DGCp3fm_BWfn0tTFNre_VcKHhwqZVARkvbShpp_SVY0,5752
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/standard_layout_static_array.h,sha256=nJAQ44apdJ71PQRxikNlVC7q9iq5q5c-AUAscVxpRkk,26272
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/static_array.h,sha256=VlKopMKu4CmSApScgvD2j0eelHFr5KZol0J362GDN-k,11248
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/submdspan.h,sha256=LS6x0YWA9WvrPt5FPMoxfPcP0oRaS7LGWWIENvNyLDE,24272
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__mdspan/type_list.h,sha256=YD3gqO7rTepsNTolWWmmQAROBXLW1QqIxmU4qyb0v7M,4511
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/addressof.h,sha256=V6vj7-1aWy9qXn5yaxg-Sqpx640S9gVG5kxK56gtK9Q,2459
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/construct_at.h,sha256=FGxfh0_1aY8yywcu5MId5-lWYHWaNefVtPTGVUjDQM0,6383
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/pointer_traits.h,sha256=03BYDVYIwXkQaO62Ms33XYbq6lP2TJL2gGp0zLUq7Vg,12174
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__memory/voidify.h,sha256=vBuPqewpMvACx27LWCZijWCdRUFH9QmCbRm2fuhfM7M,1144
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/apply_cv.h,sha256=iT6OVf0YZMywKLbvLk8ocloYTyo0fxUlM1G38vQK_kU,2393
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/make_tuple_types.h,sha256=bkpgwzBd9cYXkXOtweQO8HqH9oTEeAS1UUkxcMowVwI,3265
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/sfinae_helpers.h,sha256=UV1RjcFGfqXOUt-liZSeL8ZWsoESA8wYNQ-wUjsJizU,7608
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/structured_bindings.h,sha256=6hy2GlVtKAO0BEhKhD6MUPggYImw3l2aDhL4AZVxTj4,6113
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_element.h,sha256=QnmonWnsTp-9NvURp76x6ziAZvjCClv4u_t9Z9vXpqA,3885
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_indices.h,sha256=usDn0X4LKAFjJeIX-gTU-jyZ5r3tNWD3dIqKj8HTPIw,1134
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_like.h,sha256=ZPzIFWrKJHjjxJfn49yXwnQQ-ccO0vZWNzcBUyUpBK0,1685
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_size.h,sha256=w4qJrpwUGUtQSattQ5EM-vZs7TDUthS_kDIXKBuln1E,2722
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__tuple_dir/tuple_types.h,sha256=_iAz1mlUUcI_mLp58wubemgOvWHYRwaaFAEm933B6Lo,845
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_const.h,sha256=E4We2WDiEeEVK82tKi7pCATC7lX-bEoUQ5ZsxbvNTxM,1036
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_cv.h,sha256=oxoVZClnWdhxgybsNYAAo-p88aghHgYeb65RmurjpYs,1027
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_lvalue_reference.h,sha256=SBSP27Sy45sKa3Jcz2tdAhfNGZJjW0PwyJ9V6yk8M3o,1829
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_pointer.h,sha256=WCHqghAwEPqG2FLGshnDojVG30I8nXpY0gBz5p9AZFI,1900
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_rvalue_reference.h,sha256=OnLXyHhAzF-np8Ig1d1IdaYzZ1iTnUlJWORiCtr4wIk,1805
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/add_volatile.h,sha256=Sbjd2WbptTn-a7g5t7-VaPu4wbT-WQNniMja3QfQPCY,1057
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/aligned_storage.h,sha256=Vdn1GupHV2AInwKN02w8IXhjIIIK_SPnh7wGa4HyxLg,4551
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/aligned_union.h,sha256=QKCPlwN9reNJwZL6G2LPd2UViGN6DT1uVyXj9hhUxXY,1977
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/alignment_of.h,sha256=EaEI9wa910p2PJIyaj9mHgL7pK5LyxdCMVAF1krxisU,1215
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/apply_cv.h,sha256=68vLf5-mk-7dgu0j4AXTgjZBTdCXK_EXUnZf-B3c24Q,2007
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/can_extract_key.h,sha256=nJ1bpxee0QQNrorbLYKODI_0zTnW6L6qyxfViBlmjUg,2340
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/common_reference.h,sha256=rAqDqh_sEibyfTKQw-mcUQHSyn100frmoaOn_IWnnfE,8880
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/common_type.h,sha256=hk1nVcbBuCtaJ4sZP68fzPrC4-Yi-ITNivXJkDDTJDY,4528
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/conditional.h,sha256=drMeNWHLKfAVg590N08plz-spyuHsihHmPTvr6meUlo,1842
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/conjunction.h,sha256=5v15LXRH3FWHMlFsChBl3n-4OqU3ChNUXDshtXe202M,2086
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/copy_cv.h,sha256=cMQQe216AK3ciZsKCMLiJZzuaqu4ood6hi4qkrqK2LI,1579
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/copy_cvref.h,sha256=LGNfEc6Wom8Gs95A8ZTkCmmLydwVWbc8Fk9btyDTm8A,1437
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/decay.h,sha256=AVPtNeadgSy0pvCQtkA0U5MKvEEiY4VQZCF6UZflzHM,2478
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/dependent_type.h,sha256=Ji-9Ymn0s6VLMF7FzIylz2-lt3Rst4kM17DdcTyxF1o,916
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/disjunction.h,sha256=4pznRHFG_vTYoYzWd7CgLJtccoa_KgtczEdal5lcMWQ,2256
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/enable_if.h,sha256=S066aPm5Dm6H1oIX7ks8nxN-_SSav1cU_YrDpDNAU0s,1236
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/extent.h,sha256=kbd0MDiO2adS4Z-QQ5_4ISEczxwwNAa_gu3FgMkIcjg,2334
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/has_unique_object_representation.h,sha256=lsUmpJ__8_4nAxK5mSi_g24r0I5B2hgmWeAsgZUZ11Y,1527
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/has_virtual_destructor.h,sha256=JUH8UZPILCSpz6_ibGv-OU1uWBG0KcA7xebXHdiP2rs,1606
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/integral_constant.h,sha256=_u1jdnsJS1LqTJuTtYA9jh2t16rEkK1xXloVlrOjzE8,1879
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_abstract.h,sha256=XOjxLF3hFIKQLFT_RO6QKodc8y0nkOr7bWh1wJrfOQs,1172
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_aggregate.h,sha256=6cqLPrxYNDm5ckvi961bfX9ePhHp-ydvqo3_JU4Ui_s,1307
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_allocator.h,sha256=onQ_pihCzVe7EbnD1C-tzfV8nRIf19p4mH0oucxT-6A,1244
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_arithmetic.h,sha256=6suT3Z_4OXi2SREAT-PVyz1xvxuja7U-KJRx7BoSE7s,1359
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_array.h,sha256=1NTq6WDiyDEib2k7QQg9vjhWoMPiUxwhtYJ64Rsgx7g,1993
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_assignable.h,sha256=87Bcqd0ScF19Ad3yxSYa66oUAlo48C5OM-nT6MZOr1E,2515
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_base_of.h,sha256=gtXZ9zO8_zXib0hJqd0dTqYXpbrtwcJNhgY7A6LbMj0,2366
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_bounded_array.h,sha256=wTMlqM-TS4vTboCdk7PgNVxmP2JlJLeH6TrdDxlcTFo,1502
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_callable.h,sha256=agmMBmBec3-oIkXG9hhCDnIj2CpoIuopbtgHo1DxI4g,1273
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_char_like_type.h,sha256=0OR07bP-H9qG9Ymi4BFxf6_DV45CfrtdkoyxSVmDQfE,1068
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_class.h,sha256=57tlm1oMHNrtqjtLZXUZn5MtTkGQgCpbcQADtnvlfao,1891
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_compound.h,sha256=vZcPAAVzb3YOedEkp0HSqFFwiVRBJZqkflPyaW8QSWs,1753
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_const.h,sha256=7HouPxV6TTF-ZQdbs2r4co5jxL6RbjrRJSFqgXUegRA,1728
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_constant_evaluated.h,sha256=cyJ3DtMTKmMs3hDYYOOAoa_qxdUVnfqUxxzpHlKozFk,1458
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_constructible.h,sha256=h1lkJMBhTCsiptaIBdo4A2iVKHNpuhSJ8ugfEc-D2AU,6480
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_convertible.h,sha256=QQx4EK9u3w5iVLVzTMU7n6PlLsf6mwytGFR5E7wPD1o,6222
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_copy_assignable.h,sha256=C_XtBsv3lJG8SYYUS-mN3jfkw1c7GEzc7ljvgg7Y-QA,1391
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_copy_constructible.h,sha256=dcTq9EiD_YEtt57d0H6WxK1rzqxZ7H47yqimdqJvSRM,1362
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_core_convertible.h,sha256=O8YDmCGeLFY45ONI-5PBavgj4pxuF_MJqzwpOBRWAjs,1484
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_default_constructible.h,sha256=0KSMR6tuFq6bnjGJyzEFz9QtuUuR-w-gD3VxxJ71m4g,1227
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_destructible.h,sha256=dKOUviumZM_rBvX5isaBM8bzWQO8SUrop9u5YwmTnxY,3361
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_empty.h,sha256=sVvpsHHvvWf2tMXwWCMsABZqLXKPOd2k1re4Qv6Y84o,1987
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_enum.h,sha256=ce1-CHrOvnfty-tzJ83NDFK_9Hh-Zp17zdvhe3MM6RA,2735
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_final.h,sha256=LnTHan4L8hjAhJHWWLcT7DJfApDI2pKIE6bPEUIzl4Y,1809
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_floating_point.h,sha256=A78VqRQWYX7IbE000LPSaH1J8eng0agRMqDaVDSWuPU,1623
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_function.h,sha256=utuB3VjjDcpuHiQ_Md8QmoWvFpd99M6KbKFPbCiV-pg,1812
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_fundamental.h,sha256=kXxaDAo6b79QWWRGaoekBfai-Si33c1kAkq6_Fuf_e4,1966
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_implicitly_default_constructible.h,sha256=sqnr0x7uU6lrML7FwTOTJVq5bZdgFduUIajctH-jEOE,1881
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_integral.h,sha256=rZVgBnnHIsGmym4yVzSfEzZDVpQL8BByy3cPAAEFixE,3692
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_literal_type.h,sha256=RHCF6lQ6YL6JdFMrQZ1yB7Wnok9l9xY0EzRDWYT4i3A,2090
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_function_pointer.h,sha256=ehlHFnjR8vIMcLS25_oDj0BZw3PaZhtvo0Qr1rG_sxI,2391
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_object_pointer.h,sha256=1i5vxew9-X8GKnIfrM_LgiEVJ2cIRgsey8vcMW_oAD0,2024
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_member_pointer.h,sha256=8Lpk1b6p9ZcGYuWJhHktTmYvqoLNjfGBW_4qUsAKdGY,1927
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_move_assignable.h,sha256=Kb5x93AB3bbhBsFEZbRrXmLzZQpmdQ6I5wMbrUrLnAc,1349
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_move_constructible.h,sha256=EVlpQGobeZ6dGBis5Rd1HCZ4Eux1Txk2X-cIbHMjZHg,1348
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_assignable.h,sha256=I-oL6Pb3u5eOmlMDK2PH__tPtoyWN22NmCXVjoNVq00,4615
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_constructible.h,sha256=aL__XVnICzW3Bc_Rxtf4-CERb5YlKqK-R0xrngT2ZOQ,5276
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_convertible.h,sha256=UaUiVeX9c0LJSYs66BQ3XDwo8Arr12EIvUxvEzPt_hM,1982
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_copy_assignable.h,sha256=NTIuqRrh5zu85RJKpQOXFAj8Tp5a09SAHcAz6QiwHnE,2249
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_copy_constructible.h,sha256=ODiGv9fukzqv_3M7MR6CqPH4bLYZhm3D-hhIHcfVj-U,1430
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_default_constructible.h,sha256=aYpe-rsGA0Pd9N0-J0kEf-fN9S0osc-R3CB-ExIyD58,1967
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_destructible.h,sha256=Y4WhoL7fCiZlWZEnTAoraHgt9VyrvL6_kJH2vbwY2tc,3112
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_move_assignable.h,sha256=jA3za6M9cP-ObFCpx3nTu83lZ26204ZxTDxA_U6Kdmc,2148
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_nothrow_move_constructible.h,sha256=hM_aQIPLq-dt7HXh_he-vJIRhnexFSgq-CEIjgnLNHI,1368
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_null_pointer.h,sha256=TVQg61yfZhf4qXYwU_vMMVLewmzaUpwnUZyr_tF-q3w,1612
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_object.h,sha256=SEf0ucEljfGOto4euPx1UUaxmyDK3JaIIBOOwMISLkQ,2018
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_pod.h,sha256=v_eZZsy0PduNx4yUNnHniZWeyXvrfvfb2eZLnDTorQY,2175
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_pointer.h,sha256=AFMG71h73NtoV5t6_2L2w6Vrs7PzIEdV9BFHnBvoJO8,2459
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_polymorphic.h,sha256=vsKq00JMNfPC8lljfLKIv32SpbE52zB4FVekMSxpLbg,2022
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_primary_template.h,sha256=FCYysdacdIJ-7P30gfr2IERmIXYF0zMDBDd5OR6SLQc,1213
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_reference.h,sha256=A4Q4uaSAlxfv2P5EBJL9FUcOXVNOPTYKs5WD-FGa2zI,3255
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_reference_wrapper.h,sha256=tRW3p8USzhHT4z9SzfIoaMhCu5MHtFpBBZz2j488X6o,1292
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_referenceable.h,sha256=As0lSp9TyzVPP2Su5Y4WjmwgGbubMdmJOgNsgau_hN8,1642
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_same.h,sha256=KBDGGWL6KqIfboPa5TcvLOr4TiOTfarep5jkDqgxqUI,2961
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_scalar.h,sha256=YOpVO9zjwWEzxKaRlqRVuCeeAFhwU2NcVnpQHtLMyu4,2561
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_scoped_enum.h,sha256=0flSzBAMcWQrZrLps9KGpwf4GioB8yQE3EFpoCwc5LU,1481
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_signed.h,sha256=24O3ZiCkJ_iFTW-TWvBcWyKFWxb0GertkK30QuSySlo,2138
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_signed_integer.h,sha256=CLBm_OS1dJzkonxPz0slPAhd8D7VHhIq45fRUl9aPhc,1523
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_standard_layout.h,sha256=TJtQEaF96L3sZrD3rU2IomPl0pg-VUtLgLUEILAuM8c,1875
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_swappable.h,sha256=EbNoY4ABlAnDRi50o8nOR1DVA0b8w7Ql2ZqP0QPmQ18,5409
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivial.h,sha256=N_lTfMHDZvnX1DVKgFETlwNuiii7byMcXlsC4P1nkaE,1913
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_assignable.h,sha256=eYQpkJ1bOyTv8ZHgY0bprjKQqq3_pv4eJwnp0nS_vFY,2379
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_constructible.h,sha256=QeC5VHPZ7Ec4DhqWSSnYlmcPUnR44nTIsmBSgYNTEAQ,2919
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copy_assignable.h,sha256=Th5aXUQIJgVEkMw4hvjQ1snGn0uPvvY4r3GIRr-3Ess,2335
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copy_constructible.h,sha256=482-_NYDkgdIKdtLVoS4n1kEfgQoz4Iei84SsCFPsJA,2225
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_copyable.h,sha256=-JHvKBz0EDsjL6f4Rnrzbu60xQ1Z9iBxSxXN6U2fnr4,1962
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_default_constructible.h,sha256=0PQd5tWcqgbS1G_-vf-lWT6kG7m2onDJtwjW64db6jU,1979
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_destructible.h,sha256=3IgGenfoZj-luN8zQNofLjEwCU0f0CFb0g7_pGqN_h0,2462
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_move_assignable.h,sha256=Rr0gusB7GkVOCwWxcdAUuO_GvXycUvXO7Ty2OqHwa1g,2162
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_trivially_move_constructible.h,sha256=Z4WD1Iy1gD2-4qWDDEgYrHMnmcKij6MCHAN4c9N0O4A,2107
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unbounded_array.h,sha256=rCOTRuAq-rzkrIgvlbCx7BefitqnK7OI1-zGKuCTbCg,1438
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_union.h,sha256=gqhpbvM5p9bRjFWPASCIVmj3ypUC4MJCfS_0R2TfEog,1752
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unsigned.h,sha256=uOCD6JW0FPRaLzk_fpCV1ql1KSlCsRT3at-fQlqrwHc,2394
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_unsigned_integer.h,sha256=OeW2ELwbd5UPTgKbixY5udX_P74MmjhmBd8DPQnLx1c,1555
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_valid_expansion.h,sha256=NUObjGwwcrPfWdSsk1Kh8Z2ImOt2KEfz_Ks2DHCo01Q,1326
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_void.h,sha256=LCDwMnh3pEfdNYVjbm2M4T1RdbodUzXV8qwytsBeEd4,1698
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/is_volatile.h,sha256=SgzpdtPjHqoU7-8D_GAwJlIt5BzyK43OJ3hYpu6TXgg,1781
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/lazy.h,sha256=IbH537TsoUTceSHUKuNGzg64BQgaGb8Uujzg4Yt9ZNM,887
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_32_64_or_128_bit.h,sha256=1Qq7N55COSa7d3km1cG-OuYzeVkW-jU6Catzd1BOfE4,1794
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_const_lvalue_ref.h,sha256=rsen81Mp_a9GohUckrIberZ0pz-hk22rgD3YFrb70TM,985
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_signed.h,sha256=aS8J5I82jKcfPfGfmZRTqryCEUWVfHNjjMettLOXUfc,3250
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/make_unsigned.h,sha256=LTNdTFFUnc0GyeCVY0RsInOX1gwSqg8HAg2K2aybWCw,3889
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/maybe_const.h,sha256=kJdEIyALCn-5RteTtwlIrCSSvegRp4nxHct2i56hqRY,953
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/nat.h,sha256=FerZOi3GfRJY50EF6fYO_2Svdj4MBGzszLgexVMTJz0,970
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/negation.h,sha256=K_vWpW7-AqkUBdgLCHBBAmDC8AuOFgCsHwip-jyZUK0,1126
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/promote.h,sha256=S2Kro62NezHFRdYSdmyH33AMLLbCCAkh0N17saoxmVg,3111
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/rank.h,sha256=_8KvgpwvTTQNLCsBwm6w5nIcBuzLjsiX0bnJi7p3Vyg,1891
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_all_extents.h,sha256=EgSFIAHi28C1mIqDLnvRB7DNG9YSCNnh2PN1kE5vWJY,1893
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_const.h,sha256=0qppi3JeGMDJQdPI9C9QOADVHziegimjY31WxTFBVao,1586
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_const_ref.h,sha256=n3_27AYO2-LM91QvWk4d_B8bCsECQzXAeK0f1-Uzn18,1023
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_cv.h,sha256=zzGIWEFjQXhzNLoJzTznnxJcC7ebBMaw3jjC4ignqwc,1573
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_cvref.h,sha256=Zyfy7rqHil15knNAz7CJSmaKo4v2-f8jnjrcxQnDET0,1723
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_extent.h,sha256=B_-M9vlc4vCZXXgXAeqHC1YnC77LElOznp6zyp7_E1k,1732
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_pointer.h,sha256=RyY0dQGUKTrpV87rPQYMoTQE-vJ2_wV3hM2AnqdzmGs,2094
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_reference.h,sha256=FZ6CG18p6f578JWVhuQcpsjrXbkmP1KZoYomvFAuznQ,1875
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/remove_volatile.h,sha256=_I_7UBviGJGxbkGizXANU6zYwwXL5v8Uzruho75VflA,1642
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/result_of.h,sha256=WZ0FwJh9DNY5cH6aKIU0wAYhgh7soidZH49G2WCwljc,1423
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/type_identity.h,sha256=hKQOdXFK_CcKJ49EvQEuTScI-5RlbyB3xS6a_56GVXU,1177
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/type_list.h,sha256=-oC6PQ32lvxZzRhYB-VegVD49kd317eYvE4jtq2Etro,1394
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/underlying_type.h,sha256=fjJz3_yqd-cGGTrJiX1aTvB62flc1MOulBIwR-YYj6U,1847
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__type_traits/void_t.h,sha256=NIxWIaTgHol4ptMJua4ymoCROj2iSL8nNiUpihmaftg,920
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/as_const.h,sha256=njjLBf2lmQ06t7OuFUsJJ_W-NX6OFIFg3v1dfYAvE3M,1078
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/auto_cast.h,sha256=0xBDjcKasOs1wHPpErCo0GnPrHmMjJn2E7wQE8JhVtY,877
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/cmp.h,sha256=UP3SmtJw_lruoVs4zwKMEvNnUJfrqEAoGtoAC2oQWFY,3620
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/convert_to_integral.h,sha256=BXhG1ITE27v4t9LNxN8ei7a_vyJHtO5o600YAbTRny4,2705
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/declval.h,sha256=1nMhBBem9TB3TKeq_-8IadC8pnfvtT8FDWiY5Zrk8Oc,1235
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/exchange.h,sha256=_mlS22tF85T0H1kDMe3TZ-9N_4Rv28x2WWUCOS9rRLc,1412
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/forward.h,sha256=Xr94L6OaIZMuQSAlwCKFdedIJ5zKkgO5RlM2qDftv9Q,1426
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/forward_like.h,sha256=XuYpLzX0OXv6Tfj3ave0GZjQmRTYCKnjEabLU_K2_SM,1656
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/in_place.h,sha256=-FRu2rZ6d6H0kyktrQ_JJKdxUz9l_tHd0ADMUgW-u-w,2013
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/integer_sequence.h,sha256=d-i_POiIehgq_SjgCDN8d6TtL4aq8CaGcv53xVEAfpI,6483
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/move.h,sha256=IvwjmhXRKOcOJe45SzxMPPxo3eMBsd3b7gH_th1p_qM,1680
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/pair.h,sha256=uwiwUD4qJt-T6G0f_HMQLMPurYVxYVDu93hGnjVltF4,26530
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/piecewise_construct.h,sha256=kKGw0HEK-aRdTBMDJcHuyoiJPo7CqHVQP3kzVCCaqlI,1242
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/priority_tag.h,sha256=UHCfyDgvoJIPA3GtwuzDp6T9muq2U53RI7wVX4veYTs,941
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/rel_ops.h,sha256=H1COjJvF3vun7xXXd8ybcHRsSIKootrGzcSyl31IIcU,1438
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/swap.h,sha256=170rQDwFGFd9bYjN6qXr95i19Ll-dHDtcNZliH3fdl8,1821
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/to_underlying.h,sha256=pMR31OfN3T9lATWFs65WPryTyyqq0P0uXQMkSM35HO4,1368
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/__utility/unreachable.h,sha256=yKuH8CKCnx0-3rwAqWioRUv7W3vD2V9H_TCyJsLs51I,1072
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/android/locale_bionic.h,sha256=zoPlnOPpTy6gX8BRkCfYaruDsAEmYBSu9nI0tPp5TDg,1836
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_base.h,sha256=bpg3TZgP0vC8Y0ZA035LCOhPdAyq62aDuejSHvmTnic,9306
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_c11.h,sha256=CVo_mZLg1uPBv2AfB9gTZMUsxquZq9qO82w5PadWdNI,9126
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda.h,sha256=UXLa5hHyJDHcqnlnr886_-e7vJITnBsWN1ATPk1VVPA,20331
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_derived.h,sha256=tfYI2qDtfiSLn1nF1D1ea6TWMyNrq_hJsjJizS1qOjc,6885
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_generated.h,sha256=3YHPbz2oY08DSxVOHgt9AOcCjNJviqBdsHSn6Rdi9Bs,262265
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_gcc.h,sha256=L4hu1a0zQbjyifY-7TD0rIw0R8DCzTiDmCaQRXkYqL0,556
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_msvc.h,sha256=uKnuyK80Nv4HbF_ipeXQoZ7Upe8wsAF8uKLoOGveuJ4,21895
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_nvrtc.h,sha256=DZ1WgB9Xa8FVYK_EKLnXZrilseINX-Y5LiB4vcKqnWA,561
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_base.h,sha256=OFWQaAFSOw1touHLkvVWHNH3nYnYd6UZly2bZm7qIIE,9401
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_c11.h,sha256=Ojad-SdURhQZzDcHcqwPGS2TzEPUF9dpDg-ZGzNbirA,9205
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda.h,sha256=2_qJigheCuB0csh0ph0p6o-pXlbKAN0K0j0o6NA7f-A,20589
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_derived.h,sha256=_x9kptgqghYPxNsDQz4k7URf-niIlqfxB-fqBWGnAhI,6964
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_cuda_generated.h,sha256=h65NxSvL0dy-UUYZihNWcH5KxKOgK2TB61Pq6GYW59Q,262344
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_gcc.h,sha256=ZEhwk-NyN3lbjkyS7K8QiJNeykJth0rEic-FBadADQI,635
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_msvc.h,sha256=vQ5u2deIOQgW6wL97JmFmEoPWtYZiSEtIiWGqnQ_HSE,22447
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_nvrtc.h,sha256=O38aFtM9aYjmZOt_11SCNDo9BhrzCM5fz4Td6ZnjQkE,640
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/atomic_scopes.h,sha256=3nkG3GI1-Nl8ITZRXOObtvBK4vnckk5_toiEaj7XqNY,1770
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/cxx_atomic.h,sha256=uxMWroEw3fmR-IEGS8S3pjh3BqsSueHJ3zUhEDde7Fw,6422
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/atomic/cxx_atomic.h,sha256=lneL4EQ7AHwuwjnyORbnUCu7Kyc0eil-q7bbwHY26qA,6501
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/fuchsia/xlocale.h,sha256=Uj1_T50BphJ3EFcR0kLT1IU42nJ_2qFxY_Wang27UgY,719
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/limits.h,sha256=8sOfpm5BDoi-lqKQ94TtEXA6JKAtzqnl2ke_EROnmZM,3622
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/locale_mgmt_aix.h,sha256=SEJsXlFv71PeRExZNluSG_IQrz89IcjmCM2vSauFlo4,2466
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/support.h,sha256=Cx_BLZmSAjKhfeciYbQTucc64dC7Tytij6kE4mUEK0M,1705
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/ibm/xlocale.h,sha256=2OqyGg6BZVar1RovGTKwRMyJ1NmbBVNqve58TAInEBg,5718
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/musl/xlocale.h,sha256=XsKOT4mPjpkLikFydyP-3N7FvuwpmCBapNpq5GspgVs,1886
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/newlib/xlocale.h,sha256=yT3bbVq_tvE4aiMGQjanwjC7L9MZg-e9dADpAGQQodA,845
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/floatingpoint.h,sha256=YRkhZdGInMpeQpowOehgj0Lu6QYXnuBTuBxZPuqYZXg,476
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/wchar.h,sha256=SKQW1ytPSaWFHVXZ-d0dIpXhhVUUvjIzaPm-0nel62I,1230
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/solaris/xlocale.h,sha256=wO42pe-u6sHYD4VGHYw51M8TzGXxunHrJODHLxrU6_M,2257
-nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/limits_msvc_win32.h,sha256=0WBtRzHuAQDF_puVtSTt23hbizVYfQI5e7JOGhxFhAk,2648
+nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/limits_msvc_win32.h,sha256=yA5eBAhgofiPD-CxDI6eAowDVUoBn83lv4G4eycn__k,2840
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/win32/locale_win32.h,sha256=S7kWMncBNewdAZ_AcPi0aHl2VW_sMemqcf5qUzU2Mxo,6858
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__nop_locale_mgmt.h,sha256=h3I-8OV_cBw_bHNonm2slYtdyGqwWkv5YhiOQnHJL2I,1439
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__posix_l_fallback.h,sha256=XvPhy1AFhpoMPyiV-lMY9Uzu5kEQNF1no2UYbm7iypM,4757
 nvidia/cuda_cccl/include/cuda/std/detail/libcxx/include/support/xlocale/__strtonum_fallback.h,sha256=QIt5-3I0BlY3l_ZP9VwKCcuCWNPs1Ih9CmC1RzVM9u8,2396
 nvidia/cuda_cccl/include/thrust/addressof.h,sha256=RbkUeN_ze0qF3znr_MzOhIWG22GTXbzk_esbrCszbdA,806
 nvidia/cuda_cccl/include/thrust/adjacent_difference.h,sha256=74xN4bmKcw-W5zaNQGYvqKXNK812bifxLzR32LEmrv8,11470
 nvidia/cuda_cccl/include/thrust/advance.h,sha256=8mDFZzwrybIim4RY52meXbjrKxnc2cb5TvPZ024IB-M,4146
@@ -184,38 +453,38 @@
 nvidia/cuda_cccl/include/thrust/device_allocator.h,sha256=I0SJ2lWrqgKHPwWJPphrLJslafbChvvdt5TDVxL9o90,3909
 nvidia/cuda_cccl/include/thrust/device_delete.h,sha256=Mghj949mVU8s8ccmiZVtZuWfU9hLlqDzSm16i1d6lv4,1419
 nvidia/cuda_cccl/include/thrust/device_free.h,sha256=ngdPUUapFONSkQ53g6sHAuXLqAqCRT263T44_QZjFwA,1713
 nvidia/cuda_cccl/include/thrust/device_make_unique.h,sha256=UR63XsC9yCSd0Nd_xQeYzp9eXC-t-VlzQvAzfcrN7Bw,1855
 nvidia/cuda_cccl/include/thrust/device_malloc.h,sha256=aOtY_Erv4Iq3476gacVC6xoxSOBIyz6BiozTyxGveE8,2703
 nvidia/cuda_cccl/include/thrust/device_malloc_allocator.h,sha256=k5jkgs7M_M1RcZdsOl31jiYJFEp9T8svK9RJnbOOseA,5901
 nvidia/cuda_cccl/include/thrust/device_new.h,sha256=fKEx39pBAtby28ETPUIo9JOP5QXOjXAn-rYbZY2SKSw,2725
-nvidia/cuda_cccl/include/thrust/device_new_allocator.h,sha256=wjMBlG6gntyMIY90dJ_N-BRKA--FbrA-fujha6mHEVY,5484
+nvidia/cuda_cccl/include/thrust/device_new_allocator.h,sha256=A3npOKY3NPaFjkepFmfxAewb91p-PUVSyBgEvFJUOlk,5541
 nvidia/cuda_cccl/include/thrust/device_ptr.h,sha256=6ujIN19_vMZYwLbMnzEauvy522KUIGuStYDDxjlsAP0,6033
 nvidia/cuda_cccl/include/thrust/device_reference.h,sha256=vsSrBXJk-_5YbKGY5YoHbbj7KHxfTDtKIyDp1_ZQwxc,28560
-nvidia/cuda_cccl/include/thrust/device_vector.h,sha256=KIbpNsKe0BsO-3BbYexIcmo_Q4V9RadOo6dWsB9NtRg,17803
+nvidia/cuda_cccl/include/thrust/device_vector.h,sha256=e5THKUt1pkUj8wE7UkNtWTvTMf7kv0OciK563z30Ips,18536
 nvidia/cuda_cccl/include/thrust/distance.h,sha256=2uL1JZ4z5ECu3R6d2QV8QRYwuEAZWlVy00ksUxgmruU,2358
 nvidia/cuda_cccl/include/thrust/equal.h,sha256=QeUbFHrsxsPSBQcf9B-xs1rYtuOGyXuKk9RXhQ6P5fg,9996
 nvidia/cuda_cccl/include/thrust/event.h,sha256=tTm9T0ffaqC3oCE_FvWgssvCWzBMVlP6dDh7ChJ3E6g,813
-nvidia/cuda_cccl/include/thrust/execution_policy.h,sha256=M7Dcyhea65iEN64hmBGZh_ddhpPZ9bCtEONEYieYL9o,12161
+nvidia/cuda_cccl/include/thrust/execution_policy.h,sha256=DyAHmDNWVw9mE4PRr-vTy9CKe4VTM2kdcVFG78IiPEA,12124
 nvidia/cuda_cccl/include/thrust/extrema.h,sha256=Vjeu-IHY9FEToWYK0B9IOQ9Uz75YYPd-6KbCetb4JRU,31413
 nvidia/cuda_cccl/include/thrust/fill.h,sha256=pxnshK_V1INuBMWdnEImZ6rBhhbwTXCUj4w2RFnv9-U,7526
 nvidia/cuda_cccl/include/thrust/find.h,sha256=J9wY_gcrERo9VmHofujaoH48F4eSu9bEKtbtSzJewBU,11830
 nvidia/cuda_cccl/include/thrust/for_each.h,sha256=RfqAB7ZGlkkuVhUA-sl4isPt1ZUDrfVb6_fRMAFFAPI,10406
 nvidia/cuda_cccl/include/thrust/functional.h,sha256=AN1hQYGUbmhEKs1VgT_H07KCa_2m4FwEf96wLy8ZIyo,55075
 nvidia/cuda_cccl/include/thrust/future.h,sha256=MpNf2UyZm3EOQhXOBk58Lp02aanF4rMGNU8AO2JWJxY,5286
 nvidia/cuda_cccl/include/thrust/gather.h,sha256=t4RvmBnSDtjqkxGYmgJBEiF_vetKR-OwmjloHGEVadc,23135
 nvidia/cuda_cccl/include/thrust/generate.h,sha256=53B0OnC6ANatYKB6mOo4BVx0xru0PLbvIzsNZIORFuE,8286
-nvidia/cuda_cccl/include/thrust/host_vector.h,sha256=2c_jCGA8Tt91mphE9C3qqn78OK4eHy1ZieP6LuZVzTQ,17906
+nvidia/cuda_cccl/include/thrust/host_vector.h,sha256=COmDMU6-V5c90nVSwK20HVnZJaeNwhea78vpCguet-c,18632
 nvidia/cuda_cccl/include/thrust/inner_product.h,sha256=znPeTbS4f2Lu72jiP04-BF5jOFxPGwSx1kZ20ME3lOI,12051
 nvidia/cuda_cccl/include/thrust/limits.h,sha256=57qgDxGt_xPJLbJaEPSS81LIbVXjxD0b2Her6mZM-l4,412
 nvidia/cuda_cccl/include/thrust/logical.h,sha256=BE4YBmwy87ZvH4E7Wzvk0EMnQ90ewQiz5UJruHdL5Go,10369
 nvidia/cuda_cccl/include/thrust/memory.h,sha256=eLHMe2D-9at-mqpc0tXSRu_DkYgCBvf-tAeoZBZSSH0,15359
 nvidia/cuda_cccl/include/thrust/merge.h,sha256=AnKqFZtxGnxUybQDpbpqEJop_jfPjfbfQGo488WgvmM,39495
 nvidia/cuda_cccl/include/thrust/mismatch.h,sha256=W3bV1flp4hGEPo3moMPzXb3q9DioFiIx2OsLoJ6Dsmg,11041
-nvidia/cuda_cccl/include/thrust/optional.h,sha256=R5y1iIXWtck6nfRbDLuG2fOIlyaMPaDyf010ss3hgqw,97945
+nvidia/cuda_cccl/include/thrust/optional.h,sha256=KXQ4iD-S6MjX0eaRBztU6l39xRZB0RB3Qqt34-OI-dk,97957
 nvidia/cuda_cccl/include/thrust/pair.h,sha256=Bdas4Gi72h4TvqiMNN8XR1SeQxU3bpNkli9VQ2tFntg,9424
 nvidia/cuda_cccl/include/thrust/partition.h,sha256=__e9bQUtk7DlgPMDuvm2M69TvcfudxytwvF88ORgdqs,67577
 nvidia/cuda_cccl/include/thrust/per_device_resource.h,sha256=cr39paN3ZvTaQAGVGovjihbYI87ihDV1lUaHgREexBQ,3724
 nvidia/cuda_cccl/include/thrust/random.h,sha256=vEHzunwY40bS6_kiEWaA6_Pte3V7mR3LBnL5WTZLQRg,3773
 nvidia/cuda_cccl/include/thrust/reduce.h,sha256=5aSHEQvHNYd77nTuZ5mNvrmjAdP1M-zq2a0nibu7ues,37631
 nvidia/cuda_cccl/include/thrust/remove.h,sha256=-hwhV-AIGS1pRcIqomPXNn4tgGgTbJS3j-aarHWchss,37924
 nvidia/cuda_cccl/include/thrust/replace.h,sha256=oeqIql7MyTNhBZ7CLI15xg4FseCNjV5ChJylxuAl2PY,33675
@@ -235,15 +504,15 @@
 nvidia/cuda_cccl/include/thrust/tuple.h,sha256=UN9Rrw8Sh61WqG9i6Qb2zmsRsA5ynV93iqeR2IKCBh0,20598
 nvidia/cuda_cccl/include/thrust/uninitialized_copy.h,sha256=hCDJ0v8KhAMaPZtPvmbqXrYRMB1cVK_7hwL8hMzXOvE,12752
 nvidia/cuda_cccl/include/thrust/uninitialized_fill.h,sha256=jFTMfr0pBdTymZtxJikFDYIoWnFnlXBTdpvcP-eI_Jc,10409
 nvidia/cuda_cccl/include/thrust/unique.h,sha256=FPQ3wL0jrQuJoaTHFOgXEoP995bW4JYdPqeNS_we53Q,53968
 nvidia/cuda_cccl/include/thrust/universal_allocator.h,sha256=YWIxT1Vxv2CEGzzuYA62c3QEcxeLwSvD2PkBDbCTZ7M,2684
 nvidia/cuda_cccl/include/thrust/universal_ptr.h,sha256=j70tHvGVV51-IsaHNiZ-XRU3-FlVA2ZnrKQORSa34l8,810
 nvidia/cuda_cccl/include/thrust/universal_vector.h,sha256=KY8y55krR-dgaDibJbnfp5PCyfGaisUurXRINfhFZOc,1918
-nvidia/cuda_cccl/include/thrust/version.h,sha256=Fp49pnrGXwqunU9xzA4F5AS49RTpwEXx-1BbB3wXqG8,2848
+nvidia/cuda_cccl/include/thrust/version.h,sha256=WtLUQeFOR4_PMZ4259T5_IHApXGOiKr48HqSGuFETEM,2848
 nvidia/cuda_cccl/include/thrust/zip_function.h,sha256=aomYMoUpE3q_0PcBALKI6tQ98Yn70p9kJjVGF9JR3f4,6881
 nvidia/cuda_cccl/include/thrust/async/copy.h,sha256=ziesUak0-DamN2zdC5SJ-ivIZqj4FFAeLTpf4UsmrqU,3897
 nvidia/cuda_cccl/include/thrust/async/for_each.h,sha256=R3TYFvP1tjZNRH0qKqLWKCBFppmZiV27bxvLZUuYlvQ,2867
 nvidia/cuda_cccl/include/thrust/async/reduce.h,sha256=CyW7oZT2c-_oa5iwFd0_FurvEfiair9QuR_IX3tVNnA,11680
 nvidia/cuda_cccl/include/thrust/async/scan.h,sha256=g_pwDLRQG-Awm4Qyl9mbXz7-PPVx2p3RcynaA93LDNk,9648
 nvidia/cuda_cccl/include/thrust/async/sort.h,sha256=3KaftAf7D1bkQLLMppEMdgmlMmKc8Hozn7aMwqfESqE,6915
 nvidia/cuda_cccl/include/thrust/async/transform.h,sha256=Dis81wIWDXiCyM3_JZe47Cy7Hcw48c-5qpmEjdJsYO0,3152
@@ -338,21 +607,21 @@
 nvidia/cuda_cccl/include/thrust/detail/transform_scan.inl,sha256=Vw-5B3uOnszLzZ6zqFnxmNgCpYsPEQdXhYpu6Vp1KbA,4651
 nvidia/cuda_cccl/include/thrust/detail/trivial_sequence.h,sha256=l9uBfojj1kekth47oj1v-_O9QC_hR0cRar2KsxBTfgw,3050
 nvidia/cuda_cccl/include/thrust/detail/tuple.inl,sha256=z3KWHRmUrG9aJ1oVd5VNYRAY3Z1W_u-veX-2ZcH_fGI,30303
 nvidia/cuda_cccl/include/thrust/detail/tuple_algorithms.h,sha256=Y51LOCydmUXWvW05dXd19_SlZAJ7iSliPfiAMGZOrvM,2869
 nvidia/cuda_cccl/include/thrust/detail/tuple_meta_transform.h,sha256=t9_mPmhIUMhUNcfpXzb83rcHws5hYyt6vtOifv7-ZYc,1833
 nvidia/cuda_cccl/include/thrust/detail/tuple_transform.h,sha256=vhv_fUfK0vgFNAoTkh6akS0R2wLVvdbpxZR7hraX3-s,2577
 nvidia/cuda_cccl/include/thrust/detail/type_deduction.h,sha256=NrQPRRZNyCxjuCpF07_mea5NsR5Ry_Lm0ie4M3CLCvY,3697
-nvidia/cuda_cccl/include/thrust/detail/type_traits.h,sha256=Ya4Rue-7UYGMl7y1EcP-P_Gn8GhTw5uzzbf-7E6dvAA,21607
+nvidia/cuda_cccl/include/thrust/detail/type_traits.h,sha256=CjuFEQ0S0ha0ErOlWPC3iDpF831Rr6pJG-x_HU8rpgg,20928
 nvidia/cuda_cccl/include/thrust/detail/uninitialized_copy.inl,sha256=eQXN5aYtEoi7wDzyZ2WeYwgG1oOGpCd_pq6lzwZI4eA,3481
 nvidia/cuda_cccl/include/thrust/detail/uninitialized_fill.inl,sha256=PXX4xId7nHISn8I9fx4PVC2li8IRmKyeMbkHgjVHYWs,3080
 nvidia/cuda_cccl/include/thrust/detail/unique.inl,sha256=omrHJWkphlFI0ZYuC50a4uZVqRQaj-zMJHQEQMAqiCQ,14409
 nvidia/cuda_cccl/include/thrust/detail/use_default.h,sha256=d428LAhv1pcWL2AEVSfRvdi3tI67qObSyM-VqvCsgZ4,737
-nvidia/cuda_cccl/include/thrust/detail/vector_base.h,sha256=_Hy9xLgiACwxzdsb1C66soQWnc4IDw9tpOq7s8JtFto,22957
-nvidia/cuda_cccl/include/thrust/detail/vector_base.inl,sha256=CQcKInLoXdL6yv3CJ-rMOlhO-Wa4XVcl-RCvwTd7fS4,37715
+nvidia/cuda_cccl/include/thrust/detail/vector_base.h,sha256=Ty7Vgei5shJ8sWMzTvxQ-fUp9VqM5oFI9aFQkXOF3Ug,23537
+nvidia/cuda_cccl/include/thrust/detail/vector_base.inl,sha256=Y-_zJ92OFNnhQxEwXz8jCrPQyUcSOUApvr4EQj24v7w,38433
 nvidia/cuda_cccl/include/thrust/detail/allocator/allocator_traits.h,sha256=lVP7aXSC4v1Kcas-MYsbvm3HgXKHbYWxDVeNgPWDGm8,13771
 nvidia/cuda_cccl/include/thrust/detail/allocator/allocator_traits.inl,sha256=aMTz6UTiup7qFTHAPk_xwu3_4nD8wiw-p8gArDHdXkI,12771
 nvidia/cuda_cccl/include/thrust/detail/allocator/copy_construct_range.h,sha256=CNGcTZaODtKxtQDyBvEEQ86J9gBrg2t0u4cejPtwXx8,1632
 nvidia/cuda_cccl/include/thrust/detail/allocator/copy_construct_range.inl,sha256=ov8ZLbp4i3DAlWRWOgGjOWR30alveO2eqprL_0ZlI8c,11114
 nvidia/cuda_cccl/include/thrust/detail/allocator/default_construct_range.h,sha256=s5QY5upepz05TQn3Sr-fclDu0EO5JtTJckA-DZ94FAs,968
 nvidia/cuda_cccl/include/thrust/detail/allocator/default_construct_range.inl,sha256=48asoHsb43MsE_mxJJpiNY2PgKIduwL4kHtdIjCW4xs,3139
 nvidia/cuda_cccl/include/thrust/detail/allocator/destroy_range.h,sha256=tuSsXDgT-bii3NHqlY0j67_1zT82u4ITDQnsE0vWK-k,947
@@ -365,15 +634,15 @@
 nvidia/cuda_cccl/include/thrust/detail/allocator/tagged_allocator.h,sha256=F-oqb75D2gfimepWl5yNyyntkpDiSFGq48KteaTrGJk,3886
 nvidia/cuda_cccl/include/thrust/detail/allocator/tagged_allocator.inl,sha256=rimP_llkpdkqkjzj-WP9bNoTBpYPc5oV0M03tcjJFXU,2656
 nvidia/cuda_cccl/include/thrust/detail/allocator/temporary_allocator.h,sha256=nz5vOVRLwWSc5aRxp4SrGE2kcUUA3ymNR9lLSxeX0uc,2325
 nvidia/cuda_cccl/include/thrust/detail/allocator/temporary_allocator.inl,sha256=W3VBWcWLMCNHCkvlg0a5bdA9vWZhSa8cx95YtcVT_jY,2481
 nvidia/cuda_cccl/include/thrust/detail/complex/arithmetic.h,sha256=bBCPfKym0Ta4S6ZVH4fJ4KNa_yI3lF46Mb-ak0taCxY,7437
 nvidia/cuda_cccl/include/thrust/detail/complex/c99math.h,sha256=6j5vBfs-LzQJERgU9henU39P-ZHunCRGIrb3Vk-dbhg,4475
 nvidia/cuda_cccl/include/thrust/detail/complex/catrig.h,sha256=PlCDs1Ziw29nQJMQ2FjmYPm3rSgczeZwzryN_Wy8358,24185
-nvidia/cuda_cccl/include/thrust/detail/complex/catrigf.h,sha256=FRpYLpL8Jol2l3VgnZfDBV36Gf1Fen28nQ99KBx87Ks,14279
+nvidia/cuda_cccl/include/thrust/detail/complex/catrigf.h,sha256=lrWHgBYXlbeAJTxI3ccd3wqip7bMRpgzJ2CTM-20nbQ,14281
 nvidia/cuda_cccl/include/thrust/detail/complex/ccosh.h,sha256=hB-LWw05imaMwNJpKfc69VF3av1glfdzF2gOG9t2kYc,7222
 nvidia/cuda_cccl/include/thrust/detail/complex/ccoshf.h,sha256=uEEhDfwzinNYkKdvy2jgYe4mo6tjEfaIYsCAXOb50YI,4624
 nvidia/cuda_cccl/include/thrust/detail/complex/cexp.h,sha256=1c5jA4aC1XzDOkujsd2SHpcH5Aq57t7TibmdGiBPD70,5818
 nvidia/cuda_cccl/include/thrust/detail/complex/cexpf.h,sha256=MNyhJfp4WDgdCZ8H_W538bh7l8GULIlvAciT2ppC8P4,5039
 nvidia/cuda_cccl/include/thrust/detail/complex/clog.h,sha256=8arDEX_o5OvQiI426LgxmUaiTd8O8rjMVr0BQIC6atU,5851
 nvidia/cuda_cccl/include/thrust/detail/complex/clogf.h,sha256=NSZdqRGE22aNC7ZDhe5EOrb9E0FDaaiKqRBbX0HnG30,5387
 nvidia/cuda_cccl/include/thrust/detail/complex/complex.inl,sha256=Xg1LFmRMTIy0f2Cv_IgkZZbnI_90xnlvfx1iX8ab8L4,8058
@@ -419,15 +688,15 @@
 nvidia/cuda_cccl/include/thrust/detail/functional/operators/relational_operators.h,sha256=7vLi-QcB98hK2EXb0_usKR_gOBORu28J8ukDlWwRmLw,7904
 nvidia/cuda_cccl/include/thrust/detail/mpl/math.h,sha256=awEl_FEBdgjnoP6Dgnc0r1y-OYNRJL_N-uI0dez8AwI,3039
 nvidia/cuda_cccl/include/thrust/detail/range/head_flags.h,sha256=mPH2yILkMzcRu1km7VcEOm5y8BgpTHPZfQkGUS_1BgI,7043
 nvidia/cuda_cccl/include/thrust/detail/range/tail_flags.h,sha256=1oBcLUG5H11CiQ_08Obt1mXpfzbaVp6cqsefj6mDBvI,3933
 nvidia/cuda_cccl/include/thrust/detail/type_traits/function_traits.h,sha256=5wEEiREk--NV-0ZZz4HI1Nd8zYt-1OgQEFhF78yi1DI,3375
 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_member_function.h,sha256=Y-ojkTnencDYDqfKLMBKY50mLPxa8uhTEc6iypAgrLs,1933
 nvidia/cuda_cccl/include/thrust/detail/type_traits/has_nested_type.h,sha256=pyJvfo4YiaFt4U3V7XxqIjd25vDdO9xB2cOFnWRhlYo,1135
-nvidia/cuda_cccl/include/thrust/detail/type_traits/has_trivial_assign.h,sha256=7jCK1uzpzSX6NEVisPIPKLIunX83T4T6-ZZnr_-hR-M,1466
+nvidia/cuda_cccl/include/thrust/detail/type_traits/has_trivial_assign.h,sha256=kDEb5H-c-RnZj6H9ercL9vYOUWRsKAjPtDRUWfAKiGY,1163
 nvidia/cuda_cccl/include/thrust/detail/type_traits/is_call_possible.h,sha256=Ru_Oencdehmr2eCTnSlu8CUzUhG930-ZSrEvbBrMvAU,16096
 nvidia/cuda_cccl/include/thrust/detail/type_traits/is_metafunction_defined.h,sha256=K3gZUxmlWAsLXVIhyxPjrFqk61-ELlyxFyymzIenOU4,1094
 nvidia/cuda_cccl/include/thrust/detail/type_traits/minimum_type.h,sha256=bvnyG80wVV5rdUPG4cdbYiNuuBvWisw-0lqM8qtaIIY,4445
 nvidia/cuda_cccl/include/thrust/detail/type_traits/pointer_traits.h,sha256=AP_WmW8gcRfS-6pkoshGoti1aPqRo_N9WeVt3-XEhOA,11185
 nvidia/cuda_cccl/include/thrust/detail/type_traits/result_of_adaptable_function.h,sha256=b2u6KpDvPjNZzUyet-O2ziJrDbYYdDMJAxEWeMKhWDM,1743
 nvidia/cuda_cccl/include/thrust/detail/type_traits/iterator/is_discard_iterator.h,sha256=jTYSEjLrar3EXsnsk7xRQ9djyVtX5PlinxZ18P2x1BU,1073
 nvidia/cuda_cccl/include/thrust/detail/type_traits/iterator/is_output_iterator.h,sha256=x34KsKZM4BZt3cQsHO5RU3lAVxhWZDbmlqzQiQSMoHg,1755
@@ -438,17 +707,17 @@
 nvidia/cuda_cccl/include/thrust/iterator/iterator_adaptor.h,sha256=rDedHKrMcxa3gkMGbmbmiamoWbu1iyFRbRmGY1MiSRw,8353
 nvidia/cuda_cccl/include/thrust/iterator/iterator_categories.h,sha256=h5wyuTLNNlmmXuM4nzltU2PaWUA1OIT3UujhhrVFWFA,9225
 nvidia/cuda_cccl/include/thrust/iterator/iterator_facade.h,sha256=p9fjJq2h0wEfXNAxLEf-O6F5CBHeY27oqCww-uLKbfE,22014
 nvidia/cuda_cccl/include/thrust/iterator/iterator_traits.h,sha256=XHMmysqUdDYfmsP5jvgvpBGVufzTEBL2fL-8gXy4Nq4,1948
 nvidia/cuda_cccl/include/thrust/iterator/permutation_iterator.h,sha256=kjokzqUm3A7zgHSnAnKk42XK41BMpeZsmixiJVV_nUI,7252
 nvidia/cuda_cccl/include/thrust/iterator/retag.h,sha256=_o8O9_Y_wl0WUDiCNEopEqxuT5IrPAJYRZlv8CXXJno,2379
 nvidia/cuda_cccl/include/thrust/iterator/reverse_iterator.h,sha256=z7diM-p4U_qGddTQofP-WxwcIL_MmqgO0KW-vbl9sPc,7185
-nvidia/cuda_cccl/include/thrust/iterator/transform_input_output_iterator.h,sha256=U1TFAKQPxFvEzVJAwOIkGLGymts9tCG8ICWkQtL1GQA,5697
+nvidia/cuda_cccl/include/thrust/iterator/transform_input_output_iterator.h,sha256=9UmTfFIPkcPMwmeAa5m7mZ9j4y2ir8mo1U7kcrIQrVY,5745
 nvidia/cuda_cccl/include/thrust/iterator/transform_iterator.h,sha256=4I8Z1MdGJI2dUfol_M7jLdId97kydTNiihwdQTYo2O4,11679
-nvidia/cuda_cccl/include/thrust/iterator/transform_output_iterator.h,sha256=URIEO-rAVohOHIxKx5RDUUjaWWQWrvupb4IIHpJsTi4,5212
+nvidia/cuda_cccl/include/thrust/iterator/transform_output_iterator.h,sha256=sYiAcJ-JHsWR1a6US5oulR0sMva0fv_e5nI3DY5msVE,5254
 nvidia/cuda_cccl/include/thrust/iterator/zip_iterator.h,sha256=jJ-2I1vazFScL6BRcIRX_pFbtC3nrAMbxOsHd7aQ2-4,8303
 nvidia/cuda_cccl/include/thrust/iterator/detail/any_assign.h,sha256=micXpS5YyW7StzS5yK7dQpTDfDfgvnTPDgKgSAPSTNg,1196
 nvidia/cuda_cccl/include/thrust/iterator/detail/any_system_tag.h,sha256=He7EoRFqWcQ6Ku1lbjV7NEWTR83fIh0P0UX4B4q3XPo,1006
 nvidia/cuda_cccl/include/thrust/iterator/detail/constant_iterator_base.h,sha256=qhENl_wjtilvhEWNeIoRBrQEt_T9f0LUi5MQ4IqQhHY,2159
 nvidia/cuda_cccl/include/thrust/iterator/detail/counting_iterator.inl,sha256=xjQLoisWCSoNdhLC8cm_wvA9qqNYVq3WYkz63au6wF4,4469
 nvidia/cuda_cccl/include/thrust/iterator/detail/device_system_tag.h,sha256=VcPs7J_5AjH3IE0uS8U9ppH_SB8dQm3dqtmZYgxGlrU,1033
 nvidia/cuda_cccl/include/thrust/iterator/detail/discard_iterator_base.h,sha256=Mt85OCEI-kz-lB-sUrrCdyFky15xIYKEpAVL1epToSM,1742
@@ -565,34 +834,34 @@
 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform.h,sha256=WVzyFrMgmL0xxczZ2xWPUa_rzyBqa4Mxujo57dIbvAY,700
 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform_reduce.h,sha256=GQw_WjMkFnETvjsLujKULYTrAw9gfznbYTx3biCqrDw,725
 nvidia/cuda_cccl/include/thrust/system/cpp/detail/transform_scan.h,sha256=GQw_WjMkFnETvjsLujKULYTrAw9gfznbYTx3biCqrDw,725
 nvidia/cuda_cccl/include/thrust/system/cpp/detail/uninitialized_copy.h,sha256=GQw_WjMkFnETvjsLujKULYTrAw9gfznbYTx3biCqrDw,725
 nvidia/cuda_cccl/include/thrust/system/cpp/detail/uninitialized_fill.h,sha256=GQw_WjMkFnETvjsLujKULYTrAw9gfznbYTx3biCqrDw,725
 nvidia/cuda_cccl/include/thrust/system/cpp/detail/unique.h,sha256=FdwN9qUKPKI06zhfR1v6vs7XZCwwh1ZHnvI9eRT-xNc,751
 nvidia/cuda_cccl/include/thrust/system/cpp/detail/unique_by_key.h,sha256=ekrEiX4tF17iEMQCYOq7zhuEpXTfjBtlMZx7_7fH3lg,765
-nvidia/cuda_cccl/include/thrust/system/cpp/detail/vector.inl,sha256=7tw7AjGcJhhbSSoEcgBjZqK57x5XUoyYkQak0Ix-ZNg,3023
+nvidia/cuda_cccl/include/thrust/system/cpp/detail/vector.inl,sha256=xZDCRnQ_u2I8IhPayRW_2f4v20HUx5r9ifsIjg1TiEk,3535
 nvidia/cuda_cccl/include/thrust/system/cuda/config.h,sha256=_YuhGzvyHo2Mekte-7xRj82yrp5m_dgZPgLgtLcjjtI,5328
-nvidia/cuda_cccl/include/thrust/system/cuda/error.h,sha256=kwu8EZShWqSseYRFR9BpBgJUS1Iizt44SAIuWGvpEwo,7603
+nvidia/cuda_cccl/include/thrust/system/cuda/error.h,sha256=fEzGPrfSkxJWGuiXV_mGz_g4BMt-V_qHYjMZwEDhXsw,6921
 nvidia/cuda_cccl/include/thrust/system/cuda/execution_policy.h,sha256=0JYcchwbXGpT2JbvpWIwUs6fypSK4H9nXK5ZEgnBCbk,1889
 nvidia/cuda_cccl/include/thrust/system/cuda/future.h,sha256=IAutZPn2u5asy_pCspYx5jbkPVlpsYTd1yB5UjUGxhE,1529
 nvidia/cuda_cccl/include/thrust/system/cuda/memory.h,sha256=GQj9Bo6o5ogvXQv9MPkP2FXtTLUzAKpBo3b74iqNXIQ,3672
 nvidia/cuda_cccl/include/thrust/system/cuda/memory_resource.h,sha256=M1Tw81mKpCzEYDTuGbariyaLgsxk66CkTN_D3HM1bLg,3903
 nvidia/cuda_cccl/include/thrust/system/cuda/pointer.h,sha256=sMI9KPafCM_otbPdBh1oNETA3sj3jtAbV3X4dJH-rQU,4433
 nvidia/cuda_cccl/include/thrust/system/cuda/vector.h,sha256=htSI8qw0DY8G6eMQF2typb0EzHH0WusCaFvmtK-OCqk,3269
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/adjacent_difference.h,sha256=kLWV9Uuk_bMY5qdf8c-CCD214KWjezRax3r84tlY7Mw,11691
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/assign_value.h,sha256=vdnS-a8SLZip-br0_95STKHaCy34APX9HEqKEV8ITyA,2975
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/binary_search.h,sha256=F08yu3Gs_vBuisSDS7W49HWDyXv3rdehooiIGot0Pas,669
-nvidia/cuda_cccl/include/thrust/system/cuda/detail/cdp_dispatch.h,sha256=4yQ11xitYnsOvlB2WlStdfE6ajwZptwsTjYrE8Sy9jU,3310
+nvidia/cuda_cccl/include/thrust/system/cuda/detail/cdp_dispatch.h,sha256=8i-25R7YhqQ02w_T8xxgcKqMNp6DRNIVW85fmWWYinA,3268
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/copy.h,sha256=dyFZHWVnYD7hR5VqPNawtCCJGtMsu5REzj1kSZxCov4,6472
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/copy_if.h,sha256=Heay_7OQnpE-prTfqfVNHzBuqKyCj_8Ymxablq8wk2o,29007
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/count.h,sha256=bIZ7PMb_a_jm8WQTERVvxTq-cOIvpoJDTnNXIAXzxMY,3412
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/cross_system.h,sha256=mt3LwQjtf-WHMXkI3U-YkNIsx7MmRQNNZm7zMA7NGcM,11581
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/dispatch.h,sha256=14lMg7LMkjK_71EnvPHXJzzDaI27Xu0RomQL3H2BYt4,3678
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/equal.h,sha256=xjd5OnvDWc1dLolNFhkIJs3w7ngshaKGon_zoNqSkbU,2990
-nvidia/cuda_cccl/include/thrust/system/cuda/detail/error.inl,sha256=YHxcqntUCr3GHkTIidu0GbtAs0x8MWSr6YQNCTejSUU,2358
+nvidia/cuda_cccl/include/thrust/system/cuda/detail/error.inl,sha256=EZAuS2xe_wjm7furhNlVIrjgVzB1NlZikffeWwb9gco,2351
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/execution_policy.h,sha256=kceWEjTpWPsS8NaRHo5HAqYsCUqRFILOIWx5RT9JT4c,3185
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/extrema.h,sha256=nBDEvj-dYEY1Hz9vKwwyY_0Skc1pAkI1bkFmGPYYT7g,19192
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/fill.h,sha256=VkqE5aZc1wyiCNCiaWjoRZ2kGMHCbIk_oohW14AQA0U,3288
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/find.h,sha256=nlOZHjrAai7K3RqRupaN_EIPlFqVG3-EaDbB_8rDXX4,7127
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/for_each.h,sha256=lWVjLwDuFNxgKoLhuQBHpIl_Bu1mU73PsIWBOibytPA,3740
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/future.inl,sha256=ED--dOi-4GDI3Zr2mzpIOwVnFe2leIGI4hBgk5Wea0U,34440
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/gather.h,sha256=yaEg9pce5ccSFfzejHwQwqo9paxDHqUAf-W75kde15o,4134
@@ -609,16 +878,16 @@
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/merge.h,sha256=ekSwe-8LRAc-3khHKSqGnQO1RCGzJZCDnkU7VnOwOXc,35370
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/mismatch.h,sha256=qclpoKTcSu1mM3zi_wtS3Y_PHwv0if4zZCRnbsnkT3w,4575
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/par.h,sha256=9l2LGkQ-PEhbP88BUjWCA_WZO6OLkyqDMDSRt3-TQaY,8060
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/par_to_seq.h,sha256=EqtU43fmZaVYR8nEdKcRpMbzg0-Pd4np97nsJouUB-4,3070
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/parallel_for.h,sha256=SEe4InkaIYpyyKEbC-aF5THzDDlUW7sYGtv8h8Z_FCA,5683
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/partition.h,sha256=04oC9NopIrU8VMXRxh9zJxRM7t41bsPNdGdw7Oh-xiE,38777
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/per_device_resource.h,sha256=vzS-H_mfHRVToyz-uWI3NM9BCTGTgOOZDwQezy2-C8g,2637
-nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce.h,sha256=AKoJGtG8wauIxeCVoTmAHfaqAt0tbY7aBiPkjrA8a9Q,39414
-nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce_by_key.h,sha256=0miTrCBSQIl-z-JHzMgAJ6l15NL-zP1yTif5mrKxvRg,46028
+nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce.h,sha256=l0WtqD52z5uB5HmgdFyb6lOREJlUS2txFOatgkz6Xo0,39246
+nvidia/cuda_cccl/include/thrust/system/cuda/detail/reduce_by_key.h,sha256=z5RDyOYn1CzmZDuoSyV4AzC2RyS4IaQJyYqyIiJivA0,46036
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/remove.h,sha256=yFnX9ljWCKGdM5a3g_IFWnAO1l0rUnPsfmKWDvSVBzo,4764
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/replace.h,sha256=ny5SENPaQY2ku9pT6ShuGCa5GItQzZnJfk_TpYtt6Hw,7294
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/reverse.h,sha256=8KRZ75PrSVPq05uXwQelHS7rgKcoxOruLLLeqezu5ro,3770
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scan.h,sha256=ul8r2Udu_P-84AtpshgiEu_7gFxXFnZ-e9Ebfn702bs,14325
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scan_by_key.h,sha256=51fqsjcIhEF8nieFdTxlLjNlTqhX6LZhHTcY3niJTyA,18657
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/scatter.h,sha256=SAi44IJ4EuWvMB-O11eBO7RM9k-UT09Skeufv_kK4Ao,3980
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/sequence.h,sha256=GQw_WjMkFnETvjsLujKULYTrAw9gfznbYTx3biCqrDw,725
@@ -631,28 +900,28 @@
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform.h,sha256=p3YXHzYB_q5Ho5PjIvKkZ9gvGH3mmZ1LA2eCjlGADVI,13521
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform_reduce.h,sha256=M73uLKCEO_MBPStP5QaL3BgLmewl5YrZvIQ5kct5zEs,3052
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/transform_scan.h,sha256=HU1fvwoApsQPyfzVxMANJp-FFmvNBzMB_JWUGI-dFKs,4866
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/uninitialized_copy.h,sha256=2Vt4kE9pim5BZFffY9zN_BWqKuoTKWnnJDSAQ-nP14Y,4129
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/uninitialized_fill.h,sha256=Qwu_SQgBM5aDngYa9MXqQJLTU9cEi6JS0kW_s3uIffA,3924
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/unique.h,sha256=MhFIhYINSvGIRtjGDXL7tmcSexGtQSppookVKA3U2H8,28154
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/unique_by_key.h,sha256=AEa7MAo3QK5wuXMnaL6_iKnGO4ZztHnF5qpxPW-ShBc,32569
-nvidia/cuda_cccl/include/thrust/system/cuda/detail/util.h,sha256=-wBIX9lXkGdiXQ3EEH4BRewbYA14d5eDQPakQtRlK54,16539
+nvidia/cuda_cccl/include/thrust/system/cuda/detail/util.h,sha256=l8_Ss0EcA6LvQ5U7llVr_9zT1b_J1pGqyk3cHpwr_q0,16584
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/copy.h,sha256=-tGWr0l8UWi3cvdmQg-EbbJFNHJD0xrGWep9U7WF92M,15870
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/customization.h,sha256=pPIY57mkBFqPqZ1oI2B0EOJDwcFbGuelXkIMyNrKvMI,4424
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/exclusive_scan.h,sha256=LS3Bf4-8v1qOMek4Ody9g5vvKHRohukzHvxw8nzAGWg,7117
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/for_each.h,sha256=93s5PlwLpzo2ihMKaMVcBN_0Q598SyiYCYIDJ5LRnGo,4562
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/inclusive_scan.h,sha256=vaMOgHi1a-pKz8cY0ri4n1qRWJM6OXB7r9IT_X2K9Oc,6887
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/reduce.h,sha256=eoh6fBm90bIkGauMcQuCjvSePzl969EFArQLEuXDU6I,9060
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/scan.h,sha256=Xw3qRWLFLKZed4k9agZyKoh9Bu3NZKww-xDkZFZgEX4,1920
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/sort.h,sha256=L339moaKVU46HKDBWPyASskOb9IAIr6HFqXAFzD6F6o,13297
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/async/transform.h,sha256=VuHdMBeX1evZyubFumbL7UoxYjWmTXu9zrYr3eZctCQ,4865
-nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/agent_launcher.h,sha256=FEQ8xtC-QZidj2C_JnF89ltkZpAOrK_-yIDEGuwqmik,57014
+nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/agent_launcher.h,sha256=fZj0IdYV8icgJ4pwG4IrMw4MgWevht1wENlc7jB1B88,56831
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/alignment.h,sha256=XvguKp_lTO6P3QqnhrB2mc2JomKYnYVX5T3SqRoU2Dc,4227
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/triple_chevron_launch.h,sha256=XHvqlpMFI9h9jElXefMcjZKJVkcIMq3Qe8zuKx_NB-8,4949
-nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/util.h,sha256=nLjy8oaDzEHbxaO2gCo2x3gNQuLe73ypycr8Ks3DPF0,25804
+nvidia/cuda_cccl/include/thrust/system/cuda/detail/core/util.h,sha256=bRnbGuiQlfYkV_PmY0KE8SLwSmHdvOHSJviWbqLVcF8,27432
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/internal/copy_cross_system.h,sha256=1MWsgwfLI4PMoW87h8MPdcSD5FUNaSjhgPrPpSPAcc4,9487
 nvidia/cuda_cccl/include/thrust/system/cuda/detail/internal/copy_device_to_device.h,sha256=WtvV7v6uBiJDfwRBCExKbPQcXPsK0xFqPbfh8O3qNm4,2788
 nvidia/cuda_cccl/include/thrust/system/detail/bad_alloc.h,sha256=3qrWvyvtlBs2Na1Zu5e0gqwcho2m3E2e0Zce-PHN_4g,1337
 nvidia/cuda_cccl/include/thrust/system/detail/errno.h,sha256=FSlhHWa1u8xzWNfgVkrq7Q5ePOe800WnZ8fPZMpE1c4,4271
 nvidia/cuda_cccl/include/thrust/system/detail/error_category.inl,sha256=G5zg_S3aua-5Q9IxM-mx5KxcpQ50MlVleoPyX0EoGuo,9628
 nvidia/cuda_cccl/include/thrust/system/detail/error_code.inl,sha256=fdybJk19zUZjnRLm0En6hX-2yjLkQCM8-Z7by4vvy8Q,4539
 nvidia/cuda_cccl/include/thrust/system/detail/error_condition.inl,sha256=4ftVdUA2snho5YXTpnZplFnZclxTUVW5SMn3cyuCMqM,3203
@@ -987,23 +1256,24 @@
 nvidia/cuda_cccl/include/thrust/type_traits/is_execution_policy.h,sha256=VPsjaG94Wr03Cw4sDJbfYpRFjnXN2ZUC4ClUdtRdvEg,1702
 nvidia/cuda_cccl/include/thrust/type_traits/is_operator_less_or_greater_function_object.h,sha256=SKCnDlfbULZlXbJKUKf4M6t8vKk9BGYlXE9MeHHmOqQ,6372
 nvidia/cuda_cccl/include/thrust/type_traits/is_operator_plus_function_object.h,sha256=-v7QyHEc0Mb1hELPq7W_Nr_zykf8dzA-LUgRYT2q3Rk,3064
 nvidia/cuda_cccl/include/thrust/type_traits/is_trivially_relocatable.h,sha256=G6fZydS9GObWzjWjV1EqheL2L2FNqOnpHH_cH-U-l3s,12644
 nvidia/cuda_cccl/include/thrust/type_traits/logical_metafunctions.h,sha256=2FtwIhLsSKDh_W5p4gc7Nh0OObYFUx0k1n4fIhDG1aA,7888
 nvidia/cuda_cccl/include/thrust/type_traits/remove_cvref.h,sha256=tF41huhxS3QF1UvDGoyAfJgUaIQYkRG20LS1ziEtRws,3187
 nvidia/cuda_cccl/include/thrust/type_traits/void_t.h,sha256=xjYTLiMoXWV5_ncQhDpVtg-dn7go4u4_keWFLATKrWs,1458
+nvidia/cuda_cccl/lib/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 nvidia/cuda_cccl/lib/cmake/cub/cub-config-version.cmake,sha256=SZkq0sXInXPrJOkk1_HR-uDfDChIAvPW_auM8Q3Q6wg,1363
 nvidia/cuda_cccl/lib/cmake/cub/cub-config.cmake,sha256=QtlJQf3aAcJ3MVFuoFtu-tGDvIsuKFWbiqn0bBZ5kN8,4689
 nvidia/cuda_cccl/lib/cmake/cub/cub-header-search.cmake,sha256=MrBtVyc53LVbWxNxN2l2FY7jNcFULPai6kfTIYMXRWk,744
-nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config-version.cmake,sha256=lV3HA4qq72oLaJGhFh1hsa70FkwtI8cOcIlrL8hs6o4,1247
+nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config-version.cmake,sha256=HPgodaLVF6dS1hICw1_FdcZcbwcCOJ3BNAqukezvric,1163
 nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-config.cmake,sha256=Rl3dy96yPBfVDOFEfUuvoG7_ETTtCiBTUcv0Y-QHDmI,2612
-nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-header-search.cmake,sha256=EhodKDG6Pm9_O64_nC8IKjACZs0di4O4DqRVemFARTA,399
+nvidia/cuda_cccl/lib/cmake/libcudacxx/libcudacxx-header-search.cmake,sha256=4o4EV0DLJemAIMmH9vjkaKBKAy6TjIxtCu3mArD2fp8,503
 nvidia/cuda_cccl/lib/cmake/thrust/FindTBB.cmake,sha256=SO3v6irP-KLXntJZtTvJmtfUuPvbqdQxJibfckKikqo,16707
 nvidia/cuda_cccl/lib/cmake/thrust/README.md,sha256=Q2Xvdi0kIv4TIHMJxN8a7wcEuVP7gYSDBgnQikL9dLU,8459
 nvidia/cuda_cccl/lib/cmake/thrust/thrust-config-version.cmake,sha256=wei2Q8XCx4PN-jy7xIbOlecaS_Z1gUa_po3grhxgNGQ,1437
 nvidia/cuda_cccl/lib/cmake/thrust/thrust-config.cmake,sha256=odL-JFDfMg4lp3jZ0knuMXKyYUf2qOTXhVYeaND8GUw,29918
 nvidia/cuda_cccl/lib/cmake/thrust/thrust-header-search.cmake,sha256=Ijv_irccTfyqlq0YSjo-56tGCk-Ouabr_pfa24CQUfA,757
-nvidia_cuda_cccl_cu12-12.1.55.dist-info/License.txt,sha256=rW9YU_ugyg0VnQ9Y1JrkmDDC-Mk_epJki5zpCttMbM0,59262
-nvidia_cuda_cccl_cu12-12.1.55.dist-info/METADATA,sha256=OqBkFxxwqhdjrBDWd3ZN634PFRZ5MmiiI0yqFYGFDTo,1485
-nvidia_cuda_cccl_cu12-12.1.55.dist-info/WHEEL,sha256=i9qQj8KaD8_YEW0Vc2oS56fKju23RkQ-FVz-QmzVakQ,98
-nvidia_cuda_cccl_cu12-12.1.55.dist-info/top_level.txt,sha256=fTkAtiFuL16nUrB9ytDDtpytz2t0B4NvYTnRzwAhO14,7
-nvidia_cuda_cccl_cu12-12.1.55.dist-info/RECORD,,
+nvidia_cuda_cccl_cu12-12.2.53.dist-info/License.txt,sha256=rW9YU_ugyg0VnQ9Y1JrkmDDC-Mk_epJki5zpCttMbM0,59262
+nvidia_cuda_cccl_cu12-12.2.53.dist-info/METADATA,sha256=pvUIyim1rVKzCdgluG-npMXxrlODsPOPMO-tjLuNM7E,1485
+nvidia_cuda_cccl_cu12-12.2.53.dist-info/WHEEL,sha256=-kQi_VMfvRQozZJT7HUPMfY-5vLo0LVTmAylNJ3Ft98,106
+nvidia_cuda_cccl_cu12-12.2.53.dist-info/top_level.txt,sha256=fTkAtiFuL16nUrB9ytDDtpytz2t0B4NvYTnRzwAhO14,7
+nvidia_cuda_cccl_cu12-12.2.53.dist-info/RECORD,,
```

