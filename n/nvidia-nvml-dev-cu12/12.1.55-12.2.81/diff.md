# Comparing `tmp/nvidia_nvml_dev_cu12-12.1.55-py3-none-win_amd64.whl.zip` & `tmp/nvidia_nvml_dev_cu12-12.2.81-py3-none-manylinux1_x86_64.whl.zip`

## zipinfo {}

```diff
@@ -1,12 +1,11 @@
-Zip file size: 104859 bytes, number of entries: 10
--rw-r--r--  2.0 unx        0 b- defN 23-Jan-25 04:53 nvidia/__init__.py
--rw-r--r--  2.0 unx        0 b- defN 23-Jan-25 04:53 nvidia/nvml_dev/__init__.py
--rw-r--r--  2.0 unx        0 b- defN 23-Jan-25 04:53 nvidia/nvml_dev/include/__init__.py
--rw-r--r--  2.0 unx   502957 b- defN 23-Jan-25 04:53 nvidia/nvml_dev/include/nvml.h
--rw-r--r--  2.0 unx    83052 b- defN 23-Jan-25 04:53 nvidia/nvml_dev/lib/x64/nvml.lib
--rw-r--r--  2.0 unx    59262 b- defN 23-Jan-25 04:53 nvidia_nvml_dev_cu12-12.1.55.dist-info/License.txt
--rw-r--r--  2.0 unx     1504 b- defN 23-Jan-25 04:53 nvidia_nvml_dev_cu12-12.1.55.dist-info/METADATA
--rw-r--r--  2.0 unx       98 b- defN 23-Jan-25 04:53 nvidia_nvml_dev_cu12-12.1.55.dist-info/WHEEL
--rw-r--r--  2.0 unx        7 b- defN 23-Jan-25 04:53 nvidia_nvml_dev_cu12-12.1.55.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      886 b- defN 23-Jan-25 04:53 nvidia_nvml_dev_cu12-12.1.55.dist-info/RECORD
-10 files, 647766 bytes uncompressed, 103317 bytes compressed:  84.1%
+Zip file size: 96822 bytes, number of entries: 9
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-02 05:12 nvidia/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-02 05:12 nvidia/nvml_dev/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-02 05:12 nvidia/nvml_dev/include/__init__.py
+-rw-r--r--  2.0 unx   535622 b- defN 23-Jun-02 05:12 nvidia/nvml_dev/include/nvml.h
+-rw-r--r--  2.0 unx    59262 b- defN 23-Jun-02 05:12 nvidia_nvml_dev_cu12-12.2.81.dist-info/License.txt
+-rw-r--r--  2.0 unx     1504 b- defN 23-Jun-02 05:12 nvidia_nvml_dev_cu12-12.2.81.dist-info/METADATA
+-rw-r--r--  2.0 unx      106 b- defN 23-Jun-02 05:12 nvidia_nvml_dev_cu12-12.2.81.dist-info/WHEEL
+-rw-r--r--  2.0 unx        7 b- defN 23-Jun-02 05:12 nvidia_nvml_dev_cu12-12.2.81.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx      797 b- defN 23-Jun-02 05:12 nvidia_nvml_dev_cu12-12.2.81.dist-info/RECORD
+9 files, 597298 bytes uncompressed, 95420 bytes compressed:  84.0%
```

## zipnote {}

```diff
@@ -6,26 +6,23 @@
 
 Filename: nvidia/nvml_dev/include/__init__.py
 Comment: 
 
 Filename: nvidia/nvml_dev/include/nvml.h
 Comment: 
 
-Filename: nvidia/nvml_dev/lib/x64/nvml.lib
+Filename: nvidia_nvml_dev_cu12-12.2.81.dist-info/License.txt
 Comment: 
 
-Filename: nvidia_nvml_dev_cu12-12.1.55.dist-info/License.txt
+Filename: nvidia_nvml_dev_cu12-12.2.81.dist-info/METADATA
 Comment: 
 
-Filename: nvidia_nvml_dev_cu12-12.1.55.dist-info/METADATA
+Filename: nvidia_nvml_dev_cu12-12.2.81.dist-info/WHEEL
 Comment: 
 
-Filename: nvidia_nvml_dev_cu12-12.1.55.dist-info/WHEEL
+Filename: nvidia_nvml_dev_cu12-12.2.81.dist-info/top_level.txt
 Comment: 
 
-Filename: nvidia_nvml_dev_cu12-12.1.55.dist-info/top_level.txt
-Comment: 
-
-Filename: nvidia_nvml_dev_cu12-12.1.55.dist-info/RECORD
+Filename: nvidia_nvml_dev_cu12-12.2.81.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## nvidia/nvml_dev/include/nvml.h

```diff
@@ -1,9 +1,9 @@
 /*
- * Copyright 1993-2022 NVIDIA Corporation.  All rights reserved.
+ * Copyright 1993-2023 NVIDIA Corporation.  All rights reserved.
  *
  * NOTICE TO USER:
  *
  * This source code is subject to NVIDIA ownership rights under U.S. and
  * international Copyright laws.  Users and possessors of this source code
  * are hereby granted a nonexclusive, royalty-free license to use this code
  * in individual and commercial software.
@@ -276,25 +276,27 @@
     unsigned int        computeInstanceId;  //!< If MIG is enabled, stores a valid compute instance ID. computeInstanceId is set to
                                             //  0xFFFFFFFF otherwise.
 } nvmlProcessInfo_v2_t;
 
 /**
  * Information about running compute processes on the GPU
  * Version 2 adds versioning for the struct
+ * and the conf compute protected memory in output.
  */
 typedef struct nvmlProcessInfo_st
 {
     unsigned int        pid;                //!< Process ID
     unsigned long long  usedGpuMemory;      //!< Amount of used GPU memory in bytes.
                                             //! Under WDDM, \ref NVML_VALUE_NOT_AVAILABLE is always reported
                                             //! because Windows KMD manages all the memory and not the NVIDIA driver
     unsigned int        gpuInstanceId;      //!< If MIG is enabled, stores a valid GPU instance ID. gpuInstanceId is set to
                                             //  0xFFFFFFFF otherwise.
     unsigned int        computeInstanceId;  //!< If MIG is enabled, stores a valid compute instance ID. computeInstanceId is set to
                                             //  0xFFFFFFFF otherwise.
+    unsigned long long  usedGpuCcProtectedMemory; //!< Amount of used GPU conf compute protected memory in bytes.
 } nvmlProcessInfo_t;
 
 typedef struct nvmlDeviceAttributes_st
 {
     unsigned int multiprocessorCount;       //!< Streaming Multiprocessor count
     unsigned int sharedCopyEngineCount;     //!< Shared Copy Engine count
     unsigned int sharedDecoderCount;        //!< Shared Decoder Engine count
@@ -494,14 +496,15 @@
     NVML_TOTAL_POWER_SAMPLES        = 0, //!< To represent total power drawn by GPU
     NVML_GPU_UTILIZATION_SAMPLES    = 1, //!< To represent percent of time during which one or more kernels was executing on the GPU
     NVML_MEMORY_UTILIZATION_SAMPLES = 2, //!< To represent percent of time during which global (device) memory was being read or written
     NVML_ENC_UTILIZATION_SAMPLES    = 3, //!< To represent percent of time during which NVENC remains busy
     NVML_DEC_UTILIZATION_SAMPLES    = 4, //!< To represent percent of time during which NVDEC remains busy
     NVML_PROCESSOR_CLK_SAMPLES      = 5, //!< To represent processor clock samples
     NVML_MEMORY_CLK_SAMPLES         = 6, //!< To represent memory clock samples
+    NVML_MODULE_POWER_SAMPLES       = 7, //!< To represent module power samples for total module starting Grace Hopper
 
     // Keep this last
     NVML_SAMPLINGTYPE_COUNT
 }nvmlSamplingType_t;
 
 /**
  * Represents the queryable PCIe utilization counters
@@ -521,26 +524,28 @@
 typedef enum nvmlValueType_enum
 {
     NVML_VALUE_TYPE_DOUBLE = 0,
     NVML_VALUE_TYPE_UNSIGNED_INT = 1,
     NVML_VALUE_TYPE_UNSIGNED_LONG = 2,
     NVML_VALUE_TYPE_UNSIGNED_LONG_LONG = 3,
     NVML_VALUE_TYPE_SIGNED_LONG_LONG = 4,
+    NVML_VALUE_TYPE_SIGNED_INT = 5,
 
     // Keep this last
     NVML_VALUE_TYPE_COUNT
 }nvmlValueType_t;
 
 
 /**
  * Union to represent different types of Value
  */
 typedef union nvmlValue_st
 {
     double dVal;                    //!< If the value is double
+    int siVal;                      //!< If the value is signed int
     unsigned int uiVal;             //!< If the value is unsigned int
     unsigned long ulVal;            //!< If the value is unsigned long
     unsigned long long ullVal;      //!< If the value is unsigned long long
     signed long long sllVal;        //!< If the value is signed long long
 }nvmlValue_t;
 
 /**
@@ -968,15 +973,16 @@
     NVML_ERROR_IN_USE = 19,                    //!< An operation cannot be performed because the GPU is currently in use
     NVML_ERROR_MEMORY = 20,                    //!< Insufficient memory
     NVML_ERROR_NO_DATA = 21,                   //!< No data
     NVML_ERROR_VGPU_ECC_NOT_SUPPORTED = 22,    //!< The requested vgpu operation is not available on target device, becasue ECC is enabled
     NVML_ERROR_INSUFFICIENT_RESOURCES = 23,    //!< Ran out of critical resources, other than memory
     NVML_ERROR_FREQ_NOT_SUPPORTED = 24,        //!< Ran out of critical resources, other than memory
     NVML_ERROR_ARGUMENT_VERSION_MISMATCH = 25, //!< The provided version is invalid/unsupported
-    NVML_ERROR_DEPRECATED  = 26,	           //!< The requested functionality has been deprecated
+    NVML_ERROR_DEPRECATED  = 26,               //!< The requested functionality has been deprecated
+    NVML_ERROR_NOT_READY = 27,                 //!< The system is not ready for the request
     NVML_ERROR_UNKNOWN = 999                   //!< An internal driver error occurred
 } nvmlReturn_t;
 
 /**
  * See \ref nvmlDeviceGetMemoryErrorCounter
  */
 typedef enum nvmlMemoryLocation_enum
@@ -1099,26 +1105,24 @@
     NVML_VGPU_CAP_MULTI_VGPU_EXCLUSIVE          = 2,  //!< vGPU profile cannot be mixed with other vGPU profiles in same VM
     NVML_VGPU_CAP_EXCLUSIVE_TYPE                = 3,  //!< vGPU profile cannot run on a GPU alongside other profiles of different type
     NVML_VGPU_CAP_EXCLUSIVE_SIZE                = 4,  //!< vGPU profile cannot run on a GPU alongside other profiles of different size
     // Keep this last
     NVML_VGPU_CAP_COUNT
 } nvmlVgpuCapability_t;
 
-
 /**
 * vGPU driver queryable capabilities
 */
 typedef enum nvmlVgpuDriverCapability_enum
 {
     NVML_VGPU_DRIVER_CAP_HETEROGENEOUS_MULTI_VGPU = 0,      //!< Supports mixing of different vGPU profiles within one guest VM
     // Keep this last
     NVML_VGPU_DRIVER_CAP_COUNT
 } nvmlVgpuDriverCapability_t;
 
-
 /**
 * Device vGPU queryable capabilities
 */
 typedef enum nvmlDeviceVgpuCapability_enum
 {
     NVML_DEVICE_VGPU_CAP_FRACTIONAL_MULTI_VGPU            = 0,    //!< Fractional vGPU profiles on this GPU can be used in multi-vGPU configurations
     NVML_DEVICE_VGPU_CAP_HETEROGENEOUS_TIMESLICE_PROFILES = 1,    //!< Supports concurrent execution of timesliced vGPU profiles of differing types
@@ -1202,14 +1206,123 @@
     unsigned int        smUtil;                                     //!< SM (3D/Compute) Util Value
     unsigned int        memUtil;                                    //!< Frame Buffer Memory Util Value
     unsigned int        encUtil;                                    //!< Encoder Util Value
     unsigned int        decUtil;                                    //!< Decoder Util Value
 } nvmlVgpuProcessUtilizationSample_t;
 
 /**
+ * vGPU scheduler policies
+ */
+#define NVML_VGPU_SCHEDULER_POLICY_UNKNOWN      0
+#define NVML_VGPU_SCHEDULER_POLICY_BEST_EFFORT  1
+#define NVML_VGPU_SCHEDULER_POLICY_EQUAL_SHARE  2
+#define NVML_VGPU_SCHEDULER_POLICY_FIXED_SHARE  3
+
+#define NVML_SUPPORTED_VGPU_SCHEDULER_POLICY_COUNT 3
+
+#define NVML_SCHEDULER_SW_MAX_LOG_ENTRIES 200
+
+/**
+ * Union to represent the vGPU Scheduler Parameters
+ */
+typedef union
+{
+    struct
+    {
+        unsigned int    avgFactor;          //!< Average factor in compensating the timeslice for Adaptive Round Robin mode
+        unsigned int    timeslice;          //!< The timeslice in ns for each software run list as configured, or the default value otherwise
+    } vgpuSchedDataWithARR;
+
+    struct
+    {
+        unsigned int    timeslice;          //!< The timeslice in ns for each software run list as configured, or the default value otherwise
+    } vgpuSchedData;
+
+} nvmlVgpuSchedulerParams_t;
+
+/**
+ * Structure to store the state and logs of a software runlist
+ */
+typedef struct nvmlVgpuSchedulerLogEntries_st
+{
+    unsigned long long          timestamp;                  //!< Timestamp in ns when this software runlist was preeempted
+    unsigned long long          timeRunTotal;               //!< Total time in ns this software runlist has run
+    unsigned long long          timeRun;                    //!< Time in ns this software runlist ran before preemption
+    unsigned int                swRunlistId;                //!< Software runlist Id
+    unsigned long long          targetTimeSlice;            //!< The actual timeslice after deduction
+    unsigned long long          cumulativePreemptionTime;   //!< Preemption time in ns for this SW runlist
+} nvmlVgpuSchedulerLogEntry_t;
+
+/**
+ * Structure to store a vGPU software scheduler log
+ */
+typedef struct nvmlVgpuSchedulerLog_st
+{
+    unsigned int                engineId;                                       //!< Engine whose software runlist log entries are fetched
+    unsigned int                schedulerPolicy;                                //!< Scheduler policy
+    unsigned int                isEnabledARR;                                   //!< Flag to check Adaptive Round Robin scheduler mode
+    nvmlVgpuSchedulerParams_t   schedulerParams;
+    unsigned int                entriesCount;                                   //!< Count of log entries fetched
+    nvmlVgpuSchedulerLogEntry_t logEntries[NVML_SCHEDULER_SW_MAX_LOG_ENTRIES];
+} nvmlVgpuSchedulerLog_t;
+
+/**
+ * Structure to store the vGPU scheduler state
+ */
+typedef struct nvmlVgpuSchedulerGetState_st
+{
+    unsigned int                schedulerPolicy;    //!< Scheduler policy
+    unsigned int                isEnabledARR;       //!< Flag to check Adaptive Round Robin scheduler mode
+    nvmlVgpuSchedulerParams_t   schedulerParams;
+} nvmlVgpuSchedulerGetState_t;
+
+/**
+ * Union to represent the vGPU Scheduler set Parameters
+ */
+typedef union
+{
+    struct
+    {
+        unsigned int    avgFactor;          //!< Average factor in compensating the timeslice for Adaptive Round Robin mode
+        unsigned int    frequency;          //!< Frequency for Adaptive Round Robin mode
+    } vgpuSchedDataWithARR;
+
+    struct
+    {
+        unsigned int    timeslice;          //!< The timeslice in ns(Nanoseconds) for each software run list as configured, or the default value otherwise
+    } vgpuSchedData;
+
+} nvmlVgpuSchedulerSetParams_t;
+
+/**
+ * Structure to set the vGPU scheduler state
+ */
+typedef struct nvmlVgpuSchedulerSetState_st
+{
+    unsigned int                    schedulerPolicy;    //!< Scheduler policy
+    unsigned int                    enableARRMode;      //!< Flag to enable/disable Adaptive Round Robin scheduler
+    nvmlVgpuSchedulerSetParams_t    schedulerParams;
+} nvmlVgpuSchedulerSetState_t;
+
+/**
+ * Structure to store the vGPU scheduler capabilities
+ */
+typedef struct nvmlVgpuSchedulerCapabilities_st
+{
+    unsigned int        supportedSchedulers[NVML_SUPPORTED_VGPU_SCHEDULER_POLICY_COUNT]; //!< List the supported vGPU schedulers on the device
+    unsigned int        maxTimeslice;                                                    //!< Maximum timeslice value in ns
+    unsigned int        minTimeslice;                                                    //!< Minimum timeslice value in ns
+    unsigned int        isArrModeSupported;                                              //!< Flag to check Adaptive Round Robin mode enabled/disabled.
+    unsigned int        maxFrequencyForARR;                                              //!< Maximum frequency for Adaptive Round Robin mode
+    unsigned int        minFrequencyForARR;                                              //!< Minimum frequency for Adaptive Round Robin mode
+    unsigned int        maxAvgFactorForARR;                                              //!< Maximum averaging factor for Adaptive Round Robin mode
+    unsigned int        minAvgFactorForARR;                                              //!< Minimum averaging factor for Adaptive Round Robin mode
+} nvmlVgpuSchedulerCapabilities_t;
+
+/**
  * Structure to store the vGPU license expiry details
  */
 typedef struct nvmlVgpuLicenseExpiry_st
 {
     unsigned int    year;        //!< Year of license expiry
     unsigned short  month;       //!< Month of license expiry
     unsigned short  day;         //!< Day of license expiry
@@ -1332,16 +1445,17 @@
 #define NVML_FAN_POLICY_MANUAL                   1
 
 typedef unsigned int nvmlFanControlPolicy_t;
 
 /**
  * Device Power Source
  */
-#define NVML_POWER_SOURCE_AC      0x00000000
-#define NVML_POWER_SOURCE_BATTERY 0x00000001
+#define NVML_POWER_SOURCE_AC         0x00000000
+#define NVML_POWER_SOURCE_BATTERY    0x00000001
+#define NVML_POWER_SOURCE_UNDERSIZED 0x00000002
 
 typedef unsigned int nvmlPowerSource_t;
 
 /*
  * Device PCIE link Max Speed
  */
 #define NVML_PCIE_LINK_MAX_SPEED_INVALID   0x00000000
@@ -1645,15 +1759,62 @@
 #define NVML_FI_DEV_NVLINK_GET_VERSION                166 //!< NVLink Version
 
 #define NVML_FI_DEV_NVLINK_GET_POWER_STATE            167 //!< NVLink Power state. 0=HIGH_SPEED 1=LOW_SPEED
 #define NVML_FI_DEV_NVLINK_GET_POWER_THRESHOLD        168 //!< NVLink length of idle period (in units of 100us) before transitioning links to sleep state
 
 #define NVML_FI_DEV_PCIE_L0_TO_RECOVERY_COUNTER       169 //!< Device PEX error recovery counter
 
-#define NVML_FI_MAX 173 //!< One greater than the largest field ID defined above
+#define NVML_FI_DEV_C2C_LINK_COUNT                    170 //!< Number of C2C Links present on the device
+#define NVML_FI_DEV_C2C_LINK_GET_STATUS               171 //!< C2C Link Status 0=INACTIVE 1=ACTIVE
+#define NVML_FI_DEV_C2C_LINK_GET_MAX_BW               172 //!< C2C Link Speed in MBps for active links
+
+#define NVML_FI_DEV_PCIE_COUNT_CORRECTABLE_ERRORS     173
+#define NVML_FI_DEV_PCIE_COUNT_NAKS_RECEIVED          174
+#define NVML_FI_DEV_PCIE_COUNT_RECEIVER_ERROR         175
+#define NVML_FI_DEV_PCIE_COUNT_BAD_TLP                176
+#define NVML_FI_DEV_PCIE_COUNT_NAKS_SENT              177
+#define NVML_FI_DEV_PCIE_COUNT_BAD_DLLP               178
+#define NVML_FI_DEV_PCIE_COUNT_NON_FATAL_ERROR        179
+#define NVML_FI_DEV_PCIE_COUNT_FATAL_ERROR            180
+#define NVML_FI_DEV_PCIE_COUNT_UNSUPPORTED_REQ        181
+#define NVML_FI_DEV_PCIE_COUNT_LCRC_ERROR             182
+#define NVML_FI_DEV_PCIE_COUNT_LANE_ERROR             183
+
+#define NVML_FI_DEV_IS_RESETLESS_MIG_SUPPORTED        184
+
+/**
+ * Retrieves power usage for this GPU in milliwatts.
+ * It is only available if power management mode is supported. See \ref nvmlDeviceGetPowerManagementMode and
+ * \ref nvmlDeviceGetPowerUsage.
+ *
+ * scopeId needs to be specified. It signifies:
+ * 0 - GPU Only Scope - Metrics for GPU are retrieved
+ * 1 - Module scope - Metrics for the module (e.g. CPU + GPU) are retrieved.
+ * Note: CPU here refers to NVIDIA CPU (e.g. Grace). x86 or non-NVIDIA ARM is not supported
+ */
+#define NVML_FI_DEV_POWER_AVERAGE                     185 //!< GPU power averaged over 1 sec interval, supported on Ampere (except GA100) or newer architectures.
+#define NVML_FI_DEV_POWER_INSTANT                     186 //!< Current GPU power, supported on all architectures.
+#define NVML_FI_DEV_POWER_MIN_LIMIT                   187 //!< Minimum power limit in milliwatts.
+#define NVML_FI_DEV_POWER_MAX_LIMIT                   188 //!< Maximum power limit in milliwatts.
+#define NVML_FI_DEV_POWER_DEFAULT_LIMIT               189 //!< Default power limit in milliwatts (limit which device boots with).
+#define NVML_FI_DEV_POWER_CURRENT_LIMIT               190 //!< Limit currently enforced in milliwatts (This includes other limits set elsewhere. E.g. Out-of-band).
+#define NVML_FI_DEV_ENERGY                            191 //!< Total energy consumption (in mJ) since the driver was last reloaded. Same as \ref NVML_FI_DEV_TOTAL_ENERGY_CONSUMPTION for the GPU.
+#define NVML_FI_DEV_POWER_REQUESTED_LIMIT             192 //!< Power limit requested by NVML or any other userspace client.
+
+/**
+ * GPU T.Limit temperature thresholds in degree Celsius
+ *
+ * These fields are supported on Ada and later architectures and supersedes \ref nvmlDeviceGetTemperatureThreshold.
+ */
+#define NVML_FI_DEV_TEMPERATURE_SHUTDOWN_TLIMIT       193 //!< T.Limit temperature after which GPU may shut down for HW protection
+#define NVML_FI_DEV_TEMPERATURE_SLOWDOWN_TLIMIT       194 //!< T.Limit temperature after which GPU may begin HW slowdown
+#define NVML_FI_DEV_TEMPERATURE_MEM_MAX_TLIMIT        195 //!< T.Limit temperature after which GPU may begin SW slowdown due to memory temperature
+#define NVML_FI_DEV_TEMPERATURE_GPU_MAX_TLIMIT        196 //!< T.Limit temperature after which GPU may be throttled below base clock
+
+#define NVML_FI_MAX                                   197 //!< One greater than the largest field ID defined above
 
 /**
  * Information for a Field Value Sample
  */
 typedef struct nvmlFieldValue_st
 {
     unsigned int fieldId;       //!< ID of the NVML field to retrieve. This must be set before any call that uses this struct. See the constants starting with NVML_FI_ above.
@@ -1854,44 +2015,44 @@
                                             //   compute instance, stores a valid compute instance ID. computeInstanceId is set to
                                             //   0xFFFFFFFF otherwise.
 } nvmlEventData_t;
 
 /** @} */
 
 /***************************************************************************************************/
-/** @addtogroup nvmlClocksThrottleReasons
+/** @addtogroup nvmlClocksEventReasons
  *  @{
  */
 /***************************************************************************************************/
 
 /** Nothing is running on the GPU and the clocks are dropping to Idle state
  * \note This limiter may be removed in a later release
  */
-#define nvmlClocksThrottleReasonGpuIdle                   0x0000000000000001LL
+#define nvmlClocksEventReasonGpuIdle                   0x0000000000000001LL
 
 /** GPU clocks are limited by current setting of applications clocks
  *
  * @see nvmlDeviceSetApplicationsClocks
  * @see nvmlDeviceGetApplicationsClock
  */
-#define nvmlClocksThrottleReasonApplicationsClocksSetting 0x0000000000000002LL
+#define nvmlClocksEventReasonApplicationsClocksSetting 0x0000000000000002LL
 
 /**
  * @deprecated Renamed to \ref nvmlClocksThrottleReasonApplicationsClocksSetting
  *             as the name describes the situation more accurately.
  */
-#define nvmlClocksThrottleReasonUserDefinedClocks         nvmlClocksThrottleReasonApplicationsClocksSetting
+#define nvmlClocksThrottleReasonUserDefinedClocks         nvmlClocksEventReasonApplicationsClocksSetting
 
-/** SW Power Scaling algorithm is reducing the clocks below requested clocks
+/** The clocks have been optimized to ensure not to exceed currently set power limits
  *
  * @see nvmlDeviceGetPowerUsage
  * @see nvmlDeviceSetPowerManagementLimit
  * @see nvmlDeviceGetPowerManagementLimit
  */
-#define nvmlClocksThrottleReasonSwPowerCap                0x0000000000000004LL
+#define nvmlClocksEventReasonSwPowerCap                0x0000000000000004LL
 
 /** HW Slowdown (reducing the core clocks by a factor of 2 or more) is engaged
  *
  * This is an indicator of:
  *   - temperature being too high
  *   - External Power Brake Assertion is triggered (e.g. by the system power supply)
  *   - Power draw is too high and Fast Trigger protection is reducing the clocks
@@ -1909,24 +2070,24 @@
  * This GPU has been added to a Sync boost group with nvidia-smi or DCGM in
  * order to maximize performance per watt. All GPUs in the sync boost group
  * will boost to the minimum possible clocks across the entire group. Look at
  * the throttle reasons for other GPUs in the system to see why those GPUs are
  * holding this one at lower clocks.
  *
  */
-#define nvmlClocksThrottleReasonSyncBoost                 0x0000000000000010LL
+#define nvmlClocksEventReasonSyncBoost                 0x0000000000000010LL
 
 /** SW Thermal Slowdown
  *
- * This is an indicator of one or more of the following:
- *  - Current GPU temperature above the GPU Max Operating Temperature
- *  - Current memory temperature above the Memory Max Operating Temperature
+ * The current clocks have been optimized to ensure the the following is true:
+ *  - Current GPU temperature does not exceed GPU Max Operating Temperature
+ *  - Current memory temperature does not exceeed Memory Max Operating Temperature
  *
  */
-#define nvmlClocksThrottleReasonSwThermalSlowdown         0x0000000000000020LL
+#define nvmlClocksEventReasonSwThermalSlowdown         0x0000000000000020LL
 
 /** HW Thermal Slowdown (reducing the core clocks by a factor of 2 or more) is engaged
  *
  * This is an indicator of:
  *   - temperature being too high
  *
  * @see nvmlDeviceGetTemperature
@@ -1946,36 +2107,69 @@
  */
 #define nvmlClocksThrottleReasonHwPowerBrakeSlowdown      0x0000000000000080LL
 
 /** GPU clocks are limited by current setting of Display clocks
  *
  * @see bug 1997531
  */
-#define nvmlClocksThrottleReasonDisplayClockSetting       0x0000000000000100LL
+#define nvmlClocksEventReasonDisplayClockSetting       0x0000000000000100LL
 
 /** Bit mask representing no clocks throttling
  *
  * Clocks are as high as possible.
  * */
-#define nvmlClocksThrottleReasonNone                      0x0000000000000000LL
+#define nvmlClocksEventReasonNone                      0x0000000000000000LL
 
 /** Bit mask representing all supported clocks throttling reasons
  * New reasons might be added to this list in the future
  */
-#define nvmlClocksThrottleReasonAll (nvmlClocksThrottleReasonNone \
-      | nvmlClocksThrottleReasonGpuIdle                           \
-      | nvmlClocksThrottleReasonApplicationsClocksSetting         \
-      | nvmlClocksThrottleReasonSwPowerCap                        \
+#define nvmlClocksEventReasonAll (nvmlClocksThrottleReasonNone \
+      | nvmlClocksEventReasonGpuIdle                           \
+      | nvmlClocksEventReasonApplicationsClocksSetting         \
+      | nvmlClocksEventReasonSwPowerCap                        \
       | nvmlClocksThrottleReasonHwSlowdown                        \
-      | nvmlClocksThrottleReasonSyncBoost                         \
-      | nvmlClocksThrottleReasonSwThermalSlowdown                 \
+      | nvmlClocksEventReasonSyncBoost                         \
+      | nvmlClocksEventReasonSwThermalSlowdown                 \
       | nvmlClocksThrottleReasonHwThermalSlowdown                 \
       | nvmlClocksThrottleReasonHwPowerBrakeSlowdown              \
-      | nvmlClocksThrottleReasonDisplayClockSetting               \
+      | nvmlClocksEventReasonDisplayClockSetting               \
 )
+
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonGpuIdle instead
+ */
+#define nvmlClocksThrottleReasonGpuIdle                      nvmlClocksEventReasonGpuIdle
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonApplicationsClocksSetting instead
+ */
+#define nvmlClocksThrottleReasonApplicationsClocksSetting    nvmlClocksEventReasonApplicationsClocksSetting
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonSyncBoost instead
+ */
+#define nvmlClocksThrottleReasonSyncBoost                    nvmlClocksEventReasonSyncBoost
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonSwPowerCap instead
+ */
+#define nvmlClocksThrottleReasonSwPowerCap                   nvmlClocksEventReasonSwPowerCap
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonSwThermalSlowdown instead
+ */
+#define nvmlClocksThrottleReasonSwThermalSlowdown            nvmlClocksEventReasonSwThermalSlowdown
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonDisplayClockSetting instead
+ */
+#define nvmlClocksThrottleReasonDisplayClockSetting          nvmlClocksEventReasonDisplayClockSetting
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonNone instead
+ */
+#define nvmlClocksThrottleReasonNone                         nvmlClocksEventReasonNone
+/**
+ * @deprecated Use \ref nvmlClocksEventReasonAll instead
+ */
+#define nvmlClocksThrottleReasonAll                          nvmlClocksEventReasonAll
 /** @} */
 
 /***************************************************************************************************/
 /** @defgroup nvmlAccountingStats Accounting Statistics
  *  @{
  *
  *  Set of APIs designed to provide per process information about usage of GPU.
@@ -2055,15 +2249,15 @@
 /***************************************************************************************************/
 
 /**
  * Represents frame buffer capture session type
  */
 typedef enum nvmlFBCSessionType_enum
 {
-    NVML_FBC_SESSION_TYPE_UNKNOWN = 0,     //!< Unknwon
+    NVML_FBC_SESSION_TYPE_UNKNOWN = 0,     //!< Unknown
     NVML_FBC_SESSION_TYPE_TOSYS,           //!< ToSys
     NVML_FBC_SESSION_TYPE_CUDA,            //!< Cuda
     NVML_FBC_SESSION_TYPE_VID,             //!< Vid
     NVML_FBC_SESSION_TYPE_HWENC            //!< HEnc
 } nvmlFBCSessionType_t;
 
 /**
@@ -2125,14 +2319,110 @@
 {
     NVML_PCIE_LINK_KEEP         = 0,
     NVML_PCIE_LINK_SHUT_DOWN
 } nvmlPcieLinkState_t;
 
 /** @} */
 
+/***************************************************************************************************/
+/** @defgroup nvmlSystem/nvmlDevice definitions related to Confidential Computing
+ *  @{
+ */
+/***************************************************************************************************/
+/**
+ * Confidential Compute CPU Capabilities values
+ */
+#define NVML_CC_SYSTEM_CPU_CAPS_NONE    0
+#define NVML_CC_SYSTEM_CPU_CAPS_AMD_SEV 1
+
+/**
+ * Confidenial Compute GPU Capabilities values
+ */
+#define NVML_CC_SYSTEM_GPUS_CC_NOT_CAPABLE 0
+#define NVML_CC_SYSTEM_GPUS_CC_CAPABLE     1
+
+typedef struct nvmlConfComputeSystemCaps_st {
+    unsigned int cpuCaps;
+    unsigned int gpusCaps;
+} nvmlConfComputeSystemCaps_t;
+
+/**
+ * Confidential Compute DevTools Mode values
+ */
+#define NVML_CC_SYSTEM_DEVTOOLS_MODE_OFF 0
+#define NVML_CC_SYSTEM_DEVTOOLS_MODE_ON  1
+
+/**
+ * Confidential Compute Environment values
+ */
+#define NVML_CC_SYSTEM_ENVIRONMENT_UNAVAILABLE 0
+#define NVML_CC_SYSTEM_ENVIRONMENT_SIM         1
+#define NVML_CC_SYSTEM_ENVIRONMENT_PROD        2
+
+/**
+ * Confidential Compute Feature Status values
+ */
+#define NVML_CC_SYSTEM_FEATURE_DISABLED 0
+#define NVML_CC_SYSTEM_FEATURE_ENABLED  1
+
+typedef struct nvmlConfComputeSystemState_st {
+    unsigned int environment;
+    unsigned int ccFeature;
+    unsigned int devToolsMode;
+} nvmlConfComputeSystemState_t;
+
+/**
+ * Protected memory size
+ */
+typedef struct
+nvmlConfComputeMemSizeInfo_st
+{
+    unsigned long long protectedMemSizeKib;
+    unsigned long long unprotectedMemSizeKib;
+} nvmlConfComputeMemSizeInfo_t;
+
+/**
+ * Confidential Compute GPUs/System Ready State values
+ */
+#define NVML_CC_ACCEPTING_CLIENT_REQUESTS_FALSE 0
+#define NVML_CC_ACCEPTING_CLIENT_REQUESTS_TRUE  1
+
+/**
+ * GPU Certificate Details
+ */
+#define NVML_GPU_CERT_CHAIN_SIZE 0x1000
+#define NVML_GPU_ATTESTATION_CERT_CHAIN_SIZE 0x1400
+
+typedef struct nvmlConfComputeGpuCertificate_st {
+    unsigned int certChainSize;
+    unsigned int attestationCertChainSize;
+    unsigned char certChain[NVML_GPU_CERT_CHAIN_SIZE];
+    unsigned char attestationCertChain[NVML_GPU_ATTESTATION_CERT_CHAIN_SIZE];
+} nvmlConfComputeGpuCertificate_t;
+
+/**
+ * GPU Attestation Report
+ */
+#define NVML_CC_GPU_CEC_NONCE_SIZE 0x20
+#define NVML_CC_GPU_ATTESTATION_REPORT_SIZE 0x2000
+#define NVML_CC_GPU_CEC_ATTESTATION_REPORT_SIZE 0x1000
+#define NVML_CC_CEC_ATTESTATION_REPORT_NOT_PRESENT 0
+#define NVML_CC_CEC_ATTESTATION_REPORT_PRESENT 1
+
+typedef struct nvmlConfComputeGpuAttestationReport_st {
+    unsigned int isCecAttestationReportPresent;
+    unsigned int attestationReportSize;
+    unsigned int cecAttestationReportSize;
+    unsigned char nonce[NVML_CC_GPU_CEC_NONCE_SIZE];
+    unsigned char attestationReport[NVML_CC_GPU_ATTESTATION_REPORT_SIZE];
+    unsigned char cecAttestationReport[NVML_CC_GPU_CEC_ATTESTATION_REPORT_SIZE];
+} nvmlConfComputeGpuAttestationReport_t;
+
+/** @} */
+
 #define NVML_GPU_FABRIC_UUID_LEN 16
 
 #define NVML_GPU_FABRIC_STATE_NOT_SUPPORTED 0
 #define NVML_GPU_FABRIC_STATE_NOT_STARTED   1
 #define NVML_GPU_FABRIC_STATE_IN_PROGRESS   2
 #define NVML_GPU_FABRIC_STATE_COMPLETED     3
 
@@ -2140,14 +2430,32 @@
 
 typedef struct {
     char                 clusterUuid[NVML_GPU_FABRIC_UUID_LEN]; //!< Uuid of the cluster to which this GPU belongs
     nvmlReturn_t         status;                                //!< Error status, if any. Must be checked only if state returns "complete".
     unsigned int         partitionId;                           //!< ID of the fabric partition to which this GPU belongs
     nvmlGpuFabricState_t state;                                 //!< Current state of GPU registration process
 } nvmlGpuFabricInfo_t;
+
+/**
+ * Device Scope - This is useful to retrieve the telemetry at GPU and module (e.g. GPU + CPU) level
+ */
+#define NVML_POWER_SCOPE_GPU     0U    //!< Targets only GPU
+#define NVML_POWER_SCOPE_MODULE  1U    //!< Targets the whole module
+
+typedef unsigned char nvmlPowerScopeType_t;
+
+typedef struct
+{
+    unsigned int         version;       //!< Structure format version (must be 1)
+    nvmlPowerScopeType_t powerScope;    //!< [in]  Device type: GPU or Total Module
+    unsigned int         powerValueMw;  //!< [out] Power value to retrieve or set in milliwatts
+} nvmlPowerValue_v2_t;
+ 
+#define nvmlPowerValue_v2 NVML_STRUCT_VERSION(PowerValue, 2)
+
 /** @} */
 
 /***************************************************************************************************/
 /** @defgroup nvmlInitializationAndCleanup Initialization and Cleanup
  * This chapter describes the methods that handle NVML initialization and cleanup.
  * It is the user's responsibility to call \ref nvmlInit_v2() before calling any other methods, and
  * nvmlShutdown() once NVML is no longer being used.
@@ -2881,14 +3189,31 @@
  *         - \ref NVML_ERROR_INSUFFICIENT_SIZE if \a length is too small
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetSerial(nvmlDevice_t device, char *serial, unsigned int length);
 
+/*
+* Get a unique identifier for the device module on the baseboard
+*
+* This API retrieves a unique identifier for each GPU module that exists on a given baseboard.
+* For non-baseboard products, this ID would always be 0.
+*
+* @param device                               The identifier of the target device
+* @param moduleId                             Unique identifier for the GPU module
+*
+* @return
+*         - \ref NVML_SUCCESS                 if \a moduleId has been successfully retrieved
+*         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+*         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device or \a moduleId is invalid
+*         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+*/
+nvmlReturn_t DECLDIR nvmlDeviceGetModuleId(nvmlDevice_t device, unsigned int *moduleId);
+
 
 /***************************************************************************************************/
 
 /** @defgroup nvmlAffinity CPU and Memory Affinity
  *  This chapter describes NVML operations that are associated with CPU and memory
  *  affinity.
  *  @{
@@ -3557,14 +3882,28 @@
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device cannot report the specified clock
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetMaxClockInfo(nvmlDevice_t device, nvmlClockType_t type, unsigned int *clock);
 
 /**
+ * Retrieve the GPCCLK VF offset value
+ * @param[in]   device                         The identifier of the target device
+ * @param[out]  offset                         The retrieved GPCCLK VF offset value
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetGpcClkVfOffset(nvmlDevice_t device, int *offset);
+
+/**
  * Retrieves the current setting of a clock that applications will use unless an overspec situation occurs.
  * Can be changed using \ref nvmlDeviceSetApplicationsClocks.
  *
  * For Kepler &tm; or newer fully supported devices.
  *
  * @param device                               The identifier of the target device
  * @param clockType                            Identify which clock domain to query
@@ -4012,14 +4351,22 @@
 /**
  * Retrieves the temperature threshold for the GPU with the specified threshold type in degrees C.
  *
  * For Kepler &tm; or newer fully supported devices.
  *
  * See \ref nvmlTemperatureThresholds_t for details on available temperature thresholds.
  *
+ * Note: This API is no longer the preferred interface for retrieving the following temperature thresholds
+ * on Ada and later architectures: NVML_TEMPERATURE_THRESHOLD_SHUTDOWN, NVML_TEMPERATURE_THRESHOLD_SLOWDOWN,
+ * NVML_TEMPERATURE_THRESHOLD_MEM_MAX and NVML_TEMPERATURE_THRESHOLD_GPU_MAX.
+ *
+ * Support for reading these temperature thresholds for Ada and later architectures would be removed from this
+ * API in future releases. Please use \ref nvmlDeviceGetFieldValues with NVML_FI_DEV_TEMPERATURE_* fields to retrieve
+ * temperature thresholds on these architectures.
+ *
  * @param device                               The identifier of the target device
  * @param thresholdType                        The type of threshold value queried
  * @param temp                                 Reference in which to return the temperature reading
  * @return
  *         - \ref NVML_SUCCESS                 if \a temp has been set
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
  *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid, \a thresholdType is invalid or \a temp is NULL
@@ -4083,58 +4430,68 @@
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetPerformanceState(nvmlDevice_t device, nvmlPstates_t *pState);
 
 /**
- * Retrieves current clocks throttling reasons.
+ * Retrieves current clocks event reasons.
  *
  * For all fully supported products.
  *
  * \note More than one bit can be enabled at the same time. Multiple reasons can be affecting clocks at once.
  *
  * @param device                                The identifier of the target device
- * @param clocksThrottleReasons                 Reference in which to return bitmask of active clocks throttle
+ * @param clocksEventReasons                    Reference in which to return bitmask of active clocks event
  *                                                  reasons
  *
  * @return
- *         - \ref NVML_SUCCESS                 if \a clocksThrottleReasons has been set
+ *         - \ref NVML_SUCCESS                 if \a clocksEventReasons has been set
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a clocksThrottleReasons is NULL
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a clocksEventReasons is NULL
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  *
- * @see nvmlClocksThrottleReasons
- * @see nvmlDeviceGetSupportedClocksThrottleReasons
+ * @see nvmlClocksEventReasons
+ * @see nvmlDeviceGetSupportedClocksEventReasons
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetCurrentClocksEventReasons(nvmlDevice_t device, unsigned long long *clocksEventReasons);
+
+/**
+ * @deprecated Use \ref nvmlDeviceGetCurrentClocksEventReasons instead
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetCurrentClocksThrottleReasons(nvmlDevice_t device, unsigned long long *clocksThrottleReasons);
 
 /**
- * Retrieves bitmask of supported clocks throttle reasons that can be returned by
- * \ref nvmlDeviceGetCurrentClocksThrottleReasons
+ * Retrieves bitmask of supported clocks event reasons that can be returned by
+ * \ref nvmlDeviceGetCurrentClocksEventReasons
  *
  * For all fully supported products.
  *
  * This method is not supported in virtual machines running virtual GPU (vGPU).
  *
  * @param device                               The identifier of the target device
- * @param supportedClocksThrottleReasons       Reference in which to return bitmask of supported
- *                                              clocks throttle reasons
+ * @param supportedClocksEventReasons       Reference in which to return bitmask of supported
+ *                                              clocks event reasons
  *
  * @return
- *         - \ref NVML_SUCCESS                 if \a supportedClocksThrottleReasons has been set
+ *         - \ref NVML_SUCCESS                 if \a supportedClocksEventReasons has been set
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a supportedClocksThrottleReasons is NULL
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a supportedClocksEventReasons is NULL
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  *
- * @see nvmlClocksThrottleReasons
- * @see nvmlDeviceGetCurrentClocksThrottleReasons
+ * @see nvmlClocksEventReasons
+ * @see nvmlDeviceGetCurrentClocksEventReasons
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetSupportedClocksEventReasons(nvmlDevice_t device, unsigned long long *supportedClocksEventReasons);
+
+/**
+ * @deprecated Use \ref nvmlDeviceGetSupportedClocksEventReasons instead
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetSupportedClocksThrottleReasons(nvmlDevice_t device, unsigned long long *supportedClocksThrottleReasons);
 
 /**
  * Deprecated: Use \ref nvmlDeviceGetPerformanceState. This function exposes an incorrect generalization.
  *
  * Retrieve the current performance state for the device.
@@ -4153,14 +4510,121 @@
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetPowerState(nvmlDevice_t device, nvmlPstates_t *pState);
 
 /**
+ * Retrieve performance monitor samples from the associated subdevice.
+ *
+ * @param device
+ * @param pDynamicPstatesInfo
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a pDynamicPstatesInfo has been set
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a pDynamicPstatesInfo is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetDynamicPstatesInfo(nvmlDevice_t device, nvmlGpuDynamicPstatesInfo_t *pDynamicPstatesInfo);
+
+/**
+ * Retrieve the MemClk (Memory Clock) VF offset value.
+ * @param[in]   device                         The identifier of the target device
+ * @param[out]  offset                         The retrieved MemClk VF offset value
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetMemClkVfOffset(nvmlDevice_t device, int *offset);
+
+/**
+ * Retrieve min and max clocks of some clock domain for a given PState
+ *
+ * @param device                               The identifier of the target device
+ * @param type                                 Clock domain
+ * @param pstate                               PState to query
+ * @param minClockMHz                          Reference in which to return min clock frequency
+ * @param maxClockMHz                          Reference in which to return max clock frequency
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if everything worked
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device, \a type or \a pstate are invalid or both
+ *                                                  \a minClockMHz and \a maxClockMHz are NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetMinMaxClockOfPState(nvmlDevice_t device, nvmlClockType_t type, nvmlPstates_t pstate,
+                                                      unsigned int * minClockMHz, unsigned int * maxClockMHz);
+
+/**
+ * Get all supported Performance States (P-States) for the device.
+ *
+ * The returned array would contain a contiguous list of valid P-States supported by
+ * the device. If the number of supported P-States is fewer than the size of the array
+ * supplied missing elements would contain \a NVML_PSTATE_UNKNOWN.
+ *
+ * The number of elements in the returned list will never exceed \a NVML_MAX_GPU_PERF_PSTATES.
+ *
+ * @param device                               The identifier of the target device
+ * @param pstates                              Container to return the list of performance states
+ *                                             supported by device
+ * @param size                                 Size of the supplied \a pstates array in bytes
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a pstates array has been retrieved
+ *         - \ref NVML_ERROR_INSUFFICIENT_SIZE if the the container supplied was not large enough to
+ *                                             hold the resulting list
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device or \a pstates is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support performance state readings
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetSupportedPerformanceStates(nvmlDevice_t device,
+                                                             nvmlPstates_t *pstates, unsigned int size);
+
+/**
+ * Retrieve the GPCCLK min max VF offset value.
+ * @param[in]   device                         The identifier of the target device
+ * @param[out]  minOffset                      The retrieved GPCCLK VF min offset value
+ * @param[out]  maxOffset                      The retrieved GPCCLK VF max offset value
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetGpcClkMinMaxVfOffset(nvmlDevice_t device,
+                                                       int *minOffset, int *maxOffset);
+
+/**
+ * Retrieve the MemClk (Memory Clock) min max VF offset value.
+ * @param[in]   device                         The identifier of the target device
+ * @param[out]  minOffset                      The retrieved MemClk VF min offset value
+ * @param[out]  maxOffset                      The retrieved MemClk VF max offset value
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetMemClkMinMaxVfOffset(nvmlDevice_t device,
+                                                       int *minOffset, int *maxOffset);
+
+/**
  * This API has been deprecated.
  *
  * Retrieves the power management mode associated with this device.
  *
  * For products from the Fermi family.
  *     - Requires \a NVML_INFOROM_POWER version 3.0 or higher.
  *
@@ -4251,15 +4715,20 @@
 nvmlReturn_t DECLDIR nvmlDeviceGetPowerManagementDefaultLimit(nvmlDevice_t device, unsigned int *defaultLimit);
 
 /**
  * Retrieves power usage for this GPU in milliwatts and its associated circuitry (e.g. memory)
  *
  * For Fermi &tm; or newer fully supported devices.
  *
- * On Fermi and Kepler GPUs the reading is accurate to within +/- 5% of current power draw.
+ * On Fermi and Kepler GPUs the reading is accurate to within +/- 5% of current power draw. On Ampere
+ * (except GA100) or newer GPUs, the API returns power averaged over 1 sec interval. On GA100 and
+ * older architectures, instantaneous power is returned.
+ *
+ * See \ref NVML_FI_DEV_POWER_AVERAGE and \ref NVML_FI_DEV_POWER_INSTANT to query specific power
+ * values.
  *
  * It is only available if power management mode is supported. See \ref nvmlDeviceGetPowerManagementMode.
  *
  * @param device                               The identifier of the target device
  * @param power                                Reference in which to return the power usage information
  *
  * @return
@@ -4707,18 +5176,18 @@
 nvmlReturn_t DECLDIR nvmlDeviceGetEncoderStats (nvmlDevice_t device, unsigned int *sessionCount,
                                                 unsigned int *averageFps, unsigned int *averageLatency);
 
 /**
  * Retrieves information about active encoder sessions on a target device.
  *
  * An array of active encoder sessions is returned in the caller-supplied buffer pointed at by \a sessionInfos. The
- * array elememt count is passed in \a sessionCount, and \a sessionCount is used to return the number of sessions
+ * array element count is passed in \a sessionCount, and \a sessionCount is used to return the number of sessions
  * written to the buffer.
  *
- * If the supplied buffer is not large enough to accomodate the active session array, the function returns
+ * If the supplied buffer is not large enough to accommodate the active session array, the function returns
  * NVML_ERROR_INSUFFICIENT_SIZE, with the element count of nvmlEncoderSessionInfo_t array required in \a sessionCount.
  * To query the number of active encoder sessions, call this function with *sessionCount = 0.  The code will return
  * NVML_SUCCESS with number of active encoder sessions updated in *sessionCount.
  *
  * For Maxwell &tm; or newer fully supported devices.
  *
  * @param device                            The identifier of the target device
@@ -4754,20 +5223,62 @@
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetDecoderUtilization(nvmlDevice_t device, unsigned int *utilization, unsigned int *samplingPeriodUs);
 
 /**
+ * Retrieves the current utilization and sampling size in microseconds for the JPG
+ *
+ * %TURING_OR_NEWER%
+ *
+ * @note On MIG-enabled GPUs, querying decoder utilization is not currently supported.
+ *
+ * @param device                               The identifier of the target device
+ * @param utilization                          Reference to an unsigned int for jpg utilization info
+ * @param samplingPeriodUs                     Reference to an unsigned int for the sampling period in US
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a utilization has been populated
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid, \a utilization is NULL, or \a samplingPeriodUs is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetJpgUtilization(nvmlDevice_t device, unsigned int *utilization, unsigned int *samplingPeriodUs);
+
+/**
+ * Retrieves the current utilization and sampling size in microseconds for the OFA (Optical Flow Accelerator)
+ *
+ * %TURING_OR_NEWER%
+ *
+ * @note On MIG-enabled GPUs, querying decoder utilization is not currently supported.
+ *
+ * @param device                               The identifier of the target device
+ * @param utilization                          Reference to an unsigned int for ofa utilization info
+ * @param samplingPeriodUs                     Reference to an unsigned int for the sampling period in US
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a utilization has been populated
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid, \a utilization is NULL, or \a samplingPeriodUs is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetOfaUtilization(nvmlDevice_t device, unsigned int *utilization, unsigned int *samplingPeriodUs);
+
+/**
 * Retrieves the active frame buffer capture sessions statistics for a given device.
 *
 * For Maxwell &tm; or newer fully supported devices.
 *
 * @param device                            The identifier of the target device
-* @param fbcStats                          Reference to nvmlFBCStats_t structure contianing NvFBC stats
+* @param fbcStats                          Reference to nvmlFBCStats_t structure containing NvFBC stats
 *
 * @return
 *         - \ref NVML_SUCCESS                  if \a fbcStats is fetched
 *         - \ref NVML_ERROR_UNINITIALIZED      if the library has not been successfully initialized
 *         - \ref NVML_ERROR_INVALID_ARGUMENT   if \a fbcStats is NULL
 *         - \ref NVML_ERROR_GPU_IS_LOST        if the target GPU has fallen off the bus or is otherwise inaccessible
 *         - \ref NVML_ERROR_UNKNOWN            on any unexpected error
@@ -4777,15 +5288,15 @@
 /**
 * Retrieves information about active frame buffer capture sessions on a target device.
 *
 * An array of active FBC sessions is returned in the caller-supplied buffer pointed at by \a sessionInfo. The
 * array element count is passed in \a sessionCount, and \a sessionCount is used to return the number of sessions
 * written to the buffer.
 *
-* If the supplied buffer is not large enough to accomodate the active session array, the function returns
+* If the supplied buffer is not large enough to accommodate the active session array, the function returns
 * NVML_ERROR_INSUFFICIENT_SIZE, with the element count of nvmlFBCSessionInfo_t array required in \a sessionCount.
 * To query the number of active FBC sessions, call this function with *sessionCount = 0.  The code will return
 * NVML_SUCCESS with number of active FBC sessions updated in *sessionCount.
 *
 * For Maxwell &tm; or newer fully supported devices.
 *
 * @note hResolution, vResolution, averageFPS and averageLatency data for a FBC session returned in \a sessionInfo may
@@ -5242,27 +5753,186 @@
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetPcieSpeed(nvmlDevice_t device, unsigned int *pcieSpeed);
 
 /**
  * Gets the device's Adaptive Clock status
  *
  * @param device                               The identifier of the target device
- * @param adaptiveClockStatus                  The current adaptive clocking status
+ * @param adaptiveClockStatus                  The current adaptive clocking status, either
+ *                                             @ref NVML_ADAPTIVE_CLOCKING_INFO_STATUS_DISABLED 
+ *                                             or @ref NVML_ADAPTIVE_CLOCKING_INFO_STATUS_ENABLED
  *
  * @return
  *         - \ref NVML_SUCCESS                 if the current adaptive clocking status is successfully retrieved
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
  *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid, or \a adaptiveClockStatus is NULL
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
  *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
  *
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetAdaptiveClockInfoStatus(nvmlDevice_t device, unsigned int *adaptiveClockStatus);
 
 /**
+ * Get the type of the GPU Bus (PCIe, PCI, ...)
+ *
+ * @param device                               The identifier of the target device
+ * @param type                                 The PCI Bus type
+ *
+ * return
+ *         - \ref NVML_SUCCESS                 if the bus \a type is successfully retreived
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \device is invalid or \type is NULL
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetBusType(nvmlDevice_t device, nvmlBusType_t *type);
+
+/**
+ * Get fabric information associated with the device.
+ *
+ * %HOPPER_OR_NEWER%
+ *
+ * On Hopper + NVSwitch systems, GPU is registered with the NVIDIA Fabric Manager
+ * Upon successful registration, the GPU is added to the NVLink fabric to enable
+ * peer-to-peer communication.
+ * This API reports the current state of the GPU in the NVLink fabric
+ * along with other useful information.
+ *
+ * @param device                               The identifier of the target device
+ * @param gpuFabricInfo                        Information about GPU fabric state
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 Upon success
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     If \a device doesn't support gpu fabric
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetGpuFabricInfo(nvmlDevice_t device, nvmlGpuFabricInfo_t *gpuFabricInfo);
+
+/**
+ * Get Conf Computing System capabilities.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param capabilities                         System CC capabilities
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a capabilities were successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a capabilities is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ */
+nvmlReturn_t DECLDIR nvmlSystemGetConfComputeCapabilities(nvmlConfComputeSystemCaps_t *capabilities);
+
+/**
+ * Get Conf Computing System State.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param state                                System CC State
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a state were successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a state is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ */
+nvmlReturn_t DECLDIR nvmlSystemGetConfComputeState(nvmlConfComputeSystemState_t *state);
+
+/**
+ * Get Conf Computing Protected and Unprotected Memory Sizes.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param device                               Device handle
+ * @param memInfo                              Protected/Unprotected Memory sizes
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a memInfo were successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a memInfo or \a device is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetConfComputeMemSizeInfo(nvmlDevice_t device, nvmlConfComputeMemSizeInfo_t *memInfo);
+
+/**
+ * Get Conf Computing GPUs ready state.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param isAcceptingWork                      Returns GPU current work accepting state,
+ *                                             NVML_CC_ACCEPTING_CLIENT_REQUESTS_TRUE or
+ *                                             NVML_CC_ACCEPTING_CLIENT_REQUESTS_FALSE
+ *
+ * return
+ *         - \ref NVML_SUCCESS                 if \a current GPUs ready state were successfully queried
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a isAcceptingWork is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ */
+nvmlReturn_t DECLDIR nvmlSystemGetConfComputeGpusReadyState(unsigned int *isAcceptingWork);
+
+/**
+ * Get Conf Computing protected memory usage.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param device                               The identifier of the target device
+ * @param memory                               Reference in which to return the memory information
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a memory has been populated
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a memory is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetConfComputeProtectedMemoryUsage(nvmlDevice_t device, nvmlMemory_t *memory);
+
+/**
+ * Get Conf Computing Gpu certificate details.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param device                               The identifier of the target device
+ * @param gpuCert                              Reference in which to return the gpu certificate information
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a gpu certificate info has been populated
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a memory is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetConfComputeGpuCertificate(nvmlDevice_t device,
+                                                            nvmlConfComputeGpuCertificate_t *gpuCert);
+
+/**
+ * Get Conf Computing Gpu attestation report.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param device                               The identifier of the target device
+ * @param gpuAtstReport                        Reference in which to return the gpu attestation report
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a gpu attestation report has been populated
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a memory is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetConfComputeGpuAttestationReport(nvmlDevice_t device,
+                                                                  nvmlConfComputeGpuAttestationReport_t *gpuAtstReport);
+
+/**
  * @}
  */
 
 /** @addtogroup nvmlAccountingStats
  *  @{
  */
 
@@ -5416,15 +6086,15 @@
     unsigned int *pageCount, unsigned long long *addresses);
 
 /**
  * Returns the list of retired pages by source, including pages that are pending retirement
  * The address information provided from this API is the hardware address of the page that was retired.  Note
  * that this does not match the virtual address used in CUDA, but will match the address information in XID 63
  *
- * \note nvmlDeviceGetRetiredPages_v2 adds an additional timestamps paramter to return the time of each page's
+ * \note nvmlDeviceGetRetiredPages_v2 adds an additional timestamps parameter to return the time of each page's
  *       retirement.
  *
  * For Kepler &tm; or newer fully supported devices.
  *
  * @param device                            The identifier of the target device
  * @param cause                             Filter page addresses by cause of retirement
  * @param pageCount                         Reference in which to provide the \a addresses buffer size, and
@@ -5753,15 +6423,15 @@
     NVML_CLOCK_LIMIT_ID_UNLIMITED
 } nvmlClockLimitId_t;
 
 /**
  * Set clocks that device will lock to.
  *
  * Sets the clocks that the device will be running at to the value in the range of minGpuClockMHz to maxGpuClockMHz.
- * Setting this will supercede application clock values and take effect regardless if a cuda app is running.
+ * Setting this will supersede application clock values and take effect regardless if a cuda app is running.
  * See /ref nvmlDeviceSetApplicationsClocks
  *
  * Can be used as a setting to request constant performance.
  *
  * This can be called with a pair of integer clock frequencies in MHz, or a pair of /ref nvmlClockLimitId_t values.
  * See the table below for valid combinations of these values.
  *
@@ -6021,14 +6691,102 @@
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  *
  * @see nvmlRestrictedAPI_t
  */
 nvmlReturn_t DECLDIR nvmlDeviceSetAPIRestriction(nvmlDevice_t device, nvmlRestrictedAPI_t apiType, nvmlEnableState_t isRestricted);
 
 /**
+ * Sets the speed of a specified fan.
+ *
+ * WARNING: This function changes the fan control policy to manual. It means that YOU have to monitor
+ *          the temperature and adjust the fan speed accordingly.
+ *          If you set the fan speed too low you can burn your GPU!
+ *          Use nvmlDeviceSetDefaultFanSpeed_v2 to restore default control policy.
+ *
+ * For all cuda-capable discrete products with fans that are Maxwell or Newer.
+ *
+ * device                                The identifier of the target device
+ * fan                                   The index of the fan, starting at zero
+ * speed                                 The target speed of the fan [0-100] in % of max speed
+ *
+ * return
+ *        NVML_SUCCESS                   if the fan speed has been set
+ *        NVML_ERROR_UNINITIALIZED       if the library has not been successfully initialized
+ *        NVML_ERROR_INVALID_ARGUMENT    if the device is not valid, or the speed is outside acceptable ranges,
+ *                                              or if the fan index doesn't reference an actual fan.
+ *        NVML_ERROR_NOT_SUPPORTED       if the device is older than Maxwell.
+ *        NVML_ERROR_UNKNOWN             if there was an unexpected error.
+ */
+nvmlReturn_t DECLDIR nvmlDeviceSetFanSpeed_v2(nvmlDevice_t device, unsigned int fan, unsigned int speed);
+
+/**
+ * Set the GPCCLK VF offset value
+ * @param[in]   device                         The identifier of the target device
+ * @param[in]   offset                         The GPCCLK VF offset value to set
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a offset has been set
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceSetGpcClkVfOffset(nvmlDevice_t device, int offset);
+
+/**
+ * Set the MemClk (Memory Clock) VF offset value. It requires elevated privileges.
+ * @param[in]   device                         The identifier of the target device
+ * @param[in]   offset                         The MemClk VF offset value to set
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a offset has been set
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceSetMemClkVfOffset(nvmlDevice_t device, int offset);
+
+/**
+ * Set Conf Computing Unprotected Memory Size.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param device                               Device Handle
+ * @param sizeKiB                              Unprotected Memory size to be set in KiB
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a sizeKiB successfully set
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ */
+nvmlReturn_t DECLDIR nvmlDeviceSetConfComputeUnprotectedMemSize(nvmlDevice_t device, unsigned long long sizeKiB);
+
+/**
+ * Set Conf Computing GPUs ready state.
+ *
+ * For Ampere &tm; or newer fully supported devices.
+ * Supported on Linux, Windows TCC.
+ *
+ * @param isAcceptingWork                      GPU accepting new work, NVML_CC_ACCEPTING_CLIENT_REQUESTS_TRUE or
+ *                                             NVML_CC_ACCEPTING_CLIENT_REQUESTS_FALSE
+ *
+ * return
+ *         - \ref NVML_SUCCESS                 if \a current GPUs ready state is successfully set
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a isAcceptingWork is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
+ */
+nvmlReturn_t DECLDIR nvmlSystemSetConfComputeGpusReadyState(unsigned int isAcceptingWork);
+
+/**
  * @}
  */
 
 /** @addtogroup nvmlAccountingStats
  *  @{
  */
 
@@ -6870,15 +7628,15 @@
 /**
  * Retrieve the supported vGPU types on a physical GPU (device).
  *
  * An array of supported vGPU types for the physical GPU indicated by \a device is returned in the caller-supplied buffer
  * pointed at by \a vgpuTypeIds. The element count of nvmlVgpuTypeId_t array is passed in \a vgpuCount, and \a vgpuCount
  * is used to return the number of vGPU types written to the buffer.
  *
- * If the supplied buffer is not large enough to accomodate the vGPU type array, the function returns
+ * If the supplied buffer is not large enough to accommodate the vGPU type array, the function returns
  * NVML_ERROR_INSUFFICIENT_SIZE, with the element count of nvmlVgpuTypeId_t array required in \a vgpuCount.
  * To query the number of vGPU types supported for the GPU, call this function with *vgpuCount = 0.
  * The code will return NVML_ERROR_INSUFFICIENT_SIZE, or NVML_SUCCESS if no vGPU types are supported.
  *
  * @param device                   The identifier of the target device
  * @param vgpuCount                Pointer to caller-supplied array size, and returns number of vGPU types
  * @param vgpuTypeIds              Pointer to caller-supplied array in which to return list of vGPU types
@@ -6899,17 +7657,17 @@
  * pointed at by \a vgpuTypeIds. The element count of nvmlVgpuTypeId_t array is passed in \a vgpuCount, and \a vgpuCount
  * is used to return the number of vGPU types written to the buffer.
  *
  * The creatable vGPU types for a device may differ over time, as there may be restrictions on what type of vGPU types
  * can concurrently run on a device.  For example, if only one vGPU type is allowed at a time on a device, then the creatable
  * list will be restricted to whatever vGPU type is already running on the device.
  *
- * If the supplied buffer is not large enough to accomodate the vGPU type array, the function returns
+ * If the supplied buffer is not large enough to accommodate the vGPU type array, the function returns
  * NVML_ERROR_INSUFFICIENT_SIZE, with the element count of nvmlVgpuTypeId_t array required in \a vgpuCount.
- * To query the number of vGPU types createable for the GPU, call this function with *vgpuCount = 0.
+ * To query the number of vGPU types that can be created for the GPU, call this function with *vgpuCount = 0.
  * The code will return NVML_ERROR_INSUFFICIENT_SIZE, or NVML_SUCCESS if no vGPU types are creatable.
  *
  * @param device                   The identifier of the target device
  * @param vgpuCount                Pointer to caller-supplied array size, and returns number of vGPU types
  * @param vgpuTypeIds              Pointer to caller-supplied array in which to return list of vGPU types
  *
  * @return
@@ -6981,15 +7739,15 @@
 /**
  * Retrieve the device ID of a vGPU type.
  *
  * For Kepler &tm; or newer fully supported devices.
  *
  * @param vgpuTypeId               Handle to vGPU type
  * @param deviceID                 Device ID and vendor ID of the device contained in single 32 bit value
- * @param subsystemID              Subsytem ID and subsytem vendor ID of the device contained in single 32 bit value
+ * @param subsystemID              Subsystem ID and subsystem vendor ID of the device contained in single 32 bit value
  *
  * @return
  *         - \ref NVML_SUCCESS                 successful completion
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
  *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a vgpuTypeId is invalid, or \a deviceId or \a subsystemID are NULL
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
@@ -7120,18 +7878,18 @@
  */
 nvmlReturn_t DECLDIR nvmlVgpuTypeGetMaxInstancesPerVm(nvmlVgpuTypeId_t vgpuTypeId, unsigned int *vgpuInstanceCountPerVm);
 
 /**
  * Retrieve the active vGPU instances on a device.
  *
  * An array of active vGPU instances is returned in the caller-supplied buffer pointed at by \a vgpuInstances. The
- * array elememt count is passed in \a vgpuCount, and \a vgpuCount is used to return the number of vGPU instances
+ * array element count is passed in \a vgpuCount, and \a vgpuCount is used to return the number of vGPU instances
  * written to the buffer.
  *
- * If the supplied buffer is not large enough to accomodate the vGPU instance array, the function returns
+ * If the supplied buffer is not large enough to accommodate the vGPU instance array, the function returns
  * NVML_ERROR_INSUFFICIENT_SIZE, with the element count of nvmlVgpuInstance_t array required in \a vgpuCount.
  * To query the number of active vGPU instances, call this function with *vgpuCount = 0.  The code will return
  * NVML_ERROR_INSUFFICIENT_SIZE, or NVML_SUCCESS if no vGPU Types are supported.
  *
  * For Kepler &tm; or newer fully supported devices.
  *
  * @param device                   The identifier of the target device
@@ -7324,15 +8082,15 @@
  *
  * For Maxwell &tm; or newer fully supported devices.
  *
  * @param vgpuInstance             Identifier of the target vGPU instance
  * @param encoderCapacity          Reference to an unsigned int for the encoder capacity
  *
  * @return
- *         - \ref NVML_SUCCESS                 if \a encoderCapacity has been retrived
+ *         - \ref NVML_SUCCESS                 if \a encoderCapacity has been retrieved
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
  *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a vgpuInstance is 0, or \a encoderQueryType is invalid
  *         - \ref NVML_ERROR_NOT_FOUND         if \a vgpuInstance does not match a valid active vGPU instance on the system
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlVgpuInstanceGetEncoderCapacity(nvmlVgpuInstance_t vgpuInstance, unsigned int *encoderCapacity);
 
@@ -7377,15 +8135,15 @@
 /**
  * Retrieves information about all active encoder sessions on a vGPU Instance.
  *
  * An array of active encoder sessions is returned in the caller-supplied buffer pointed at by \a sessionInfo. The
  * array element count is passed in \a sessionCount, and \a sessionCount is used to return the number of sessions
  * written to the buffer.
  *
- * If the supplied buffer is not large enough to accomodate the active session array, the function returns
+ * If the supplied buffer is not large enough to accommodate the active session array, the function returns
  * NVML_ERROR_INSUFFICIENT_SIZE, with the element count of nvmlEncoderSessionInfo_t array required in \a sessionCount.
  * To query the number of active encoder sessions, call this function with *sessionCount = 0. The code will return
  * NVML_SUCCESS with number of active encoder sessions updated in *sessionCount.
  *
  * For Maxwell &tm; or newer fully supported devices.
  *
  * @param vgpuInstance                      Identifier of the target vGPU instance
@@ -7407,15 +8165,15 @@
 
 /**
 * Retrieves the active frame buffer capture sessions statistics of a vGPU Instance
 *
 * For Maxwell &tm; or newer fully supported devices.
 *
 * @param vgpuInstance                      Identifier of the target vGPU instance
-* @param fbcStats                          Reference to nvmlFBCStats_t structure contianing NvFBC stats
+* @param fbcStats                          Reference to nvmlFBCStats_t structure containing NvFBC stats
 *
 * @return
 *         - \ref NVML_SUCCESS                  if \a fbcStats is fetched
 *         - \ref NVML_ERROR_UNINITIALIZED      if the library has not been successfully initialized
 *         - \ref NVML_ERROR_INVALID_ARGUMENT   if \a vgpuInstance is 0, or \a fbcStats is NULL
 *         - \ref NVML_ERROR_NOT_FOUND          if \a vgpuInstance does not match a valid active vGPU instance on the system
 *         - \ref NVML_ERROR_UNKNOWN            on any unexpected error
@@ -7425,15 +8183,15 @@
 /**
 * Retrieves information about active frame buffer capture sessions on a vGPU Instance.
 *
 * An array of active FBC sessions is returned in the caller-supplied buffer pointed at by \a sessionInfo. The
 * array element count is passed in \a sessionCount, and \a sessionCount is used to return the number of sessions
 * written to the buffer.
 *
-* If the supplied buffer is not large enough to accomodate the active session array, the function returns
+* If the supplied buffer is not large enough to accommodate the active session array, the function returns
 * NVML_ERROR_INSUFFICIENT_SIZE, with the element count of nvmlFBCSessionInfo_t array required in \a sessionCount.
 * To query the number of active FBC sessions, call this function with *sessionCount = 0.  The code will return
 * NVML_SUCCESS with number of active FBC sessions updated in *sessionCount.
 *
 * For Maxwell &tm; or newer fully supported devices.
 *
 * @note hResolution, vResolution, averageFPS and averageLatency data for a FBC session returned in \a sessionInfo may
@@ -7535,29 +8293,29 @@
 {
     unsigned int             version;                                                    //!< Current version of the structure
     unsigned int             revision;                                                   //!< Current revision of the structure
     nvmlVgpuGuestInfoState_t guestInfoState;                                             //!< Current state of Guest-dependent fields
     char                     guestDriverVersion[NVML_SYSTEM_DRIVER_VERSION_BUFFER_SIZE]; //!< Version of driver installed in guest
     char                     hostDriverVersion[NVML_SYSTEM_DRIVER_VERSION_BUFFER_SIZE];  //!< Version of driver installed in host
     unsigned int             reserved[6];                                                //!< Reserved for internal use
-    unsigned int             vgpuVirtualizationCaps;                                     //!< vGPU virtualizaion capabilities bitfileld
+    unsigned int             vgpuVirtualizationCaps;                                     //!< vGPU virtualization capabilities bitfield
     unsigned int             guestVgpuVersion;                                           //!< vGPU version of guest driver
     unsigned int             opaqueDataSize;                                             //!< Size of opaque data field in bytes
     char                     opaqueData[4];                                              //!< Opaque data
 } nvmlVgpuMetadata_t;
 
 /**
  * Physical GPU metadata structure
  */
 typedef struct nvmlVgpuPgpuMetadata_st
 {
     unsigned int            version;                                                    //!< Current version of the structure
     unsigned int            revision;                                                   //!< Current revision of the structure
     char                    hostDriverVersion[NVML_SYSTEM_DRIVER_VERSION_BUFFER_SIZE];  //!< Host driver version
-    unsigned int            pgpuVirtualizationCaps;                                     //!< Pgpu virtualizaion capabilities bitfileld
+    unsigned int            pgpuVirtualizationCaps;                                     //!< Pgpu virtualization capabilities bitfield
     unsigned int            reserved[5];                                                //!< Reserved for internal use
     nvmlVgpuVersion_t       hostSupportedVgpuRange;                                     //!< vGPU version range supported by host driver
     unsigned int            opaqueDataSize;                                             //!< Size of opaque data field in bytes
     char                    opaqueData[4];                                              //!< Opaque data
 } nvmlVgpuPgpuMetadata_t;
 
 /**
@@ -7647,15 +8405,15 @@
 /**
  * Takes a vGPU instance metadata structure read from \ref nvmlVgpuInstanceGetMetadata(), and a vGPU metadata structure for a
  * physical GPU read from \ref nvmlDeviceGetVgpuMetadata(), and returns compatibility information of the vGPU instance and the
  * physical GPU.
  *
  * The caller passes in a buffer via \a compatibilityInfo, into which a compatibility information structure is written. The
  * structure defines the states in which the vGPU / VM may be booted on the physical GPU. If the vGPU / VM compatibility
- * with the physical GPU is limited, a limit code indicates the factor limiting compability.
+ * with the physical GPU is limited, a limit code indicates the factor limiting compatability.
  * (see \ref nvmlVgpuPgpuCompatibilityLimitCode_t for details).
  *
  * Note: vGPU compatibility does not take into account dynamic capacity conditions that may limit a system's ability to
  *       boot a given vGPU or associated VM.
  *
  * @param vgpuMetadata          Pointer to caller-supplied vGPU metadata structure
  * @param pgpuMetadata          Pointer to caller-supplied GPU metadata structure
@@ -7684,14 +8442,98 @@
  *         - \ref NVML_ERROR_INSUFFICIENT_SIZE   \a pgpuMetadata buffer is too small, required size is returned in \a bufferSize
  *         - \ref NVML_ERROR_INVALID_ARGUMENT    if \a bufferSize is NULL or \a device is invalid; if \a pgpuMetadata is NULL and the value of \a bufferSize is not 0.
  *         - \ref NVML_ERROR_NOT_SUPPORTED       if vGPU is not supported by the system
  *         - \ref NVML_ERROR_UNKNOWN             on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetPgpuMetadataString(nvmlDevice_t device, char *pgpuMetadata, unsigned int *bufferSize);
 
+/**
+ * Returns the vGPU Software scheduler logs.
+ * \a pSchedulerLog points to a caller-allocated structure to contain the logs. The number of elements returned will
+ * never exceed \a NVML_SCHEDULER_SW_MAX_LOG_ENTRIES.
+ *
+ * To get the entire logs, call the function atleast 5 times a second.
+ *
+ * For Pascal &tm; or newer fully supported devices.
+ *
+ * @param device                The identifier of the target \a device
+ * @param pSchedulerLog         Reference in which \a pSchedulerLog is written
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                   vGPU scheduler logs were successfully obtained
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT    if \a pSchedulerLog is NULL or \a device is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED       The API is not supported in current state or \a device not in vGPU host mode
+ *         - \ref NVML_ERROR_UNKNOWN             on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetVgpuSchedulerLog(nvmlDevice_t device, nvmlVgpuSchedulerLog_t *pSchedulerLog);
+
+/**
+ * Returns the vGPU scheduler state.
+ *
+ * For Pascal &tm; or newer fully supported devices.
+ *
+ * @param device                The identifier of the target \a device
+ * @param pSchedulerState       Reference in which \a pSchedulerState is returned
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                   vGPU scheduler state is successfully obtained
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT    if \a pSchedulerState is NULL or \a device is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED       The API is not supported in current state or \a device not in vGPU host mode
+ *         - \ref NVML_ERROR_UNKNOWN             on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetVgpuSchedulerState(nvmlDevice_t device, nvmlVgpuSchedulerGetState_t *pSchedulerState);
+
+/**
+ * Returns the vGPU scheduler capabilities.
+ * The list of supported vGPU schedulers returned in \a nvmlVgpuSchedulerCapabilities_t is from
+ * the NVML_VGPU_SCHEDULER_POLICY_*. This list enumerates the supported scheduler policies
+ * if the engine is Graphics type.
+ * The other values in \a nvmlVgpuSchedulerCapabilities_t are also applicable if the engine is
+ * Graphics type. For other engine types, it is BEST EFFORT policy.
+ * If ARR is supported and enabled, scheduling frequency and averaging factor are applicable
+ * else timeSlice is applicable.
+ *
+ * For Pascal &tm; or newer fully supported devices.
+ *
+ * @param device                The identifier of the target \a device
+ * @param pCapabilities         Reference in which \a pCapabilities is written
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                   vGPU scheduler capabilities were successfully obtained
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT    if \a pCapabilities is NULL or \a device is invalid
+ *         - \ref NVML_ERROR_NOT_SUPPORTED       The API is not supported in current state or \a device not in vGPU host mode
+ *         - \ref NVML_ERROR_UNKNOWN             on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceGetVgpuSchedulerCapabilities(nvmlDevice_t device, nvmlVgpuSchedulerCapabilities_t *pCapabilities);
+
+/**
+ * Sets the vGPU scheduler state.
+ *
+ * For Pascal &tm; or newer fully supported devices.
+ *
+ * The scheduler state change won't persist across module load/unload.
+ * Scheduler state and params will be allowed to set only when no VM is running.
+ * In \a nvmlVgpuSchedulerSetState_t, IFF enableARRMode=1 then
+ * provide avgFactorForARR and frequency as input. If enableARRMode is disabled
+ * then provide timeslice as input.
+ *
+ * @param device                The identifier of the target \a device
+ * @param pSchedulerState       vGPU \a pSchedulerState to set
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                  vGPU scheduler state has been successfully set
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT   if \a pSchedulerState is NULL or \a device is invalid
+ *         - \ref NVML_ERROR_RESET_REQUIRED     if setting \a pSchedulerState failed with fatal error,
+ *                                              reboot is required to overcome from this error.
+ *         - \ref NVML_ERROR_NOT_SUPPORTED      The API is not supported in current state or \a device not in vGPU host mode
+ *                                              or if any vGPU instance currently exists on the \a device
+ *         - \ref NVML_ERROR_UNKNOWN            on any unexpected error
+ */
+nvmlReturn_t DECLDIR nvmlDeviceSetVgpuSchedulerState(nvmlDevice_t device, nvmlVgpuSchedulerSetState_t *pSchedulerState);
+
 /*
  * Virtual GPU (vGPU) version
  *
  * The NVIDIA vGPU Manager and the guest drivers are tagged with a range of supported vGPU versions. This determines the range of NVIDIA guest driver versions that
  * are compatible for vGPU feature support with a given NVIDIA vGPU Manager. For vGPU feature support, the range of supported versions for the NVIDIA vGPU Manager
  * and the guest driver must overlap. Otherwise, the guest driver fails to load in the VM.
  *
@@ -8878,224 +9720,15 @@
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
  *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a migDevice or \a device is invalid
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
  *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
  */
 nvmlReturn_t DECLDIR nvmlDeviceGetDeviceHandleFromMigDeviceHandle(nvmlDevice_t migDevice, nvmlDevice_t *device);
 
-/**
- * Get the type of the GPU Bus (PCIe, PCI, ...)
- *
- * @param device                               The identifier of the target device
- * @param type                                 The PCI Bus type
- *
- * return
- *         - \ref NVML_SUCCESS                 if the bus \a type is successfully retreived
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \device is invalid or \type is NULL
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetBusType(nvmlDevice_t device, nvmlBusType_t *type);
-
-/**
- * Retrieve performance monitor samples from the associated subdevice.
- *
- * @param device
- * @param pDynamicPstatesInfo
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a pDynamicPstatesInfo has been set
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a pDynamicPstatesInfo is NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetDynamicPstatesInfo(nvmlDevice_t device, nvmlGpuDynamicPstatesInfo_t *pDynamicPstatesInfo);
-
-/**
- * Sets the speed of a specified fan.
- *
- * WARNING: This function changes the fan control policy to manual. It means that YOU have to monitor
- *          the temperature and adjust the fan speed accordingly.
- *          If you set the fan speed too low you can burn your GPU!
- *          Use nvmlDeviceSetDefaultFanSpeed_v2 to restore default control policy.
- *
- * For all cuda-capable discrete products with fans that are Maxwell or Newer.
- *
- * device                                The identifier of the target device
- * fan                                   The index of the fan, starting at zero
- * speed                                 The target speed of the fan [0-100] in % of max speed
- *
- * return
- *        NVML_SUCCESS                   if the fan speed has been set
- *        NVML_ERROR_UNINITIALIZED       if the library has not been successfully initialized
- *        NVML_ERROR_INVALID_ARGUMENT    if the device is not valid, or the speed is outside acceptable ranges,
- *                                              or if the fan index doesn't reference an actual fan.
- *        NVML_ERROR_NOT_SUPPORTED       if the device is older than Maxwell.
- *        NVML_ERROR_UNKNOWN             if there was an unexpected error.
- */
-nvmlReturn_t DECLDIR nvmlDeviceSetFanSpeed_v2(nvmlDevice_t device, unsigned int fan, unsigned int speed);
-
-/**
- * Retrieve the GPCCLK VF offset value
- * @param[in]   device                         The identifier of the target device
- * @param[out]  offset                         The retrieved GPCCLK VF offset value
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetGpcClkVfOffset(nvmlDevice_t device, int *offset);
-
-/**
- * Set the GPCCLK VF offset value
- * @param[in]   device                         The identifier of the target device
- * @param[in]   offset                         The GPCCLK VF offset value to set
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a offset has been set
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceSetGpcClkVfOffset(nvmlDevice_t device, int offset);
-
-/**
- * Retrieve the MemClk (Memory Clock) VF offset value.
- * @param[in]   device                         The identifier of the target device
- * @param[out]  offset                         The retrieved MemClk VF offset value
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetMemClkVfOffset(nvmlDevice_t device, int *offset);
-
-/**
- * Set the MemClk (Memory Clock) VF offset value. It requires elevated privileges.
- * @param[in]   device                         The identifier of the target device
- * @param[in]   offset                         The MemClk VF offset value to set
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a offset has been set
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceSetMemClkVfOffset(nvmlDevice_t device, int offset);
-
-/**
- * Retrieve min and max clocks of some clock domain for a given PState
- *
- * @param device                               The identifier of the target device
- * @param type                                 Clock domain
- * @param pstate                               PState to query
- * @param minClockMHz                          Reference in which to return min clock frequency
- * @param maxClockMHz                          Reference in which to return max clock frequency
- *
- * @return
- *         - \ref NVML_SUCCESS                 if everything worked
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device, \a type or \a pstate are invalid or both
- *                                                  \a minClockMHz and \a maxClockMHz are NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetMinMaxClockOfPState(nvmlDevice_t device, nvmlClockType_t type, nvmlPstates_t pstate,
-                                                      unsigned int * minClockMHz, unsigned int * maxClockMHz);
-
-/**
- * Get all supported Performance States (P-States) for the device.
- *
- * The returned array would contain a contiguous list of valid P-States supported by
- * the device. If the number of supported P-States is fewer than the size of the array
- * supplied missing elements would contain \a NVML_PSTATE_UNKNOWN.
- *
- * The number of elements in the returned list will never exceed \a NVML_MAX_GPU_PERF_PSTATES.
- *
- * @param device                               The identifier of the target device
- * @param pstates                              Container to return the list of performance states
- *                                             supported by device
- * @param size                                 Size of the supplied \a pstates array in bytes
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a pstates array has been retrieved
- *         - \ref NVML_ERROR_INSUFFICIENT_SIZE if the the container supplied was not large enough to
- *                                             hold the resulting list
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device or \a pstates is invalid
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support performance state readings
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetSupportedPerformanceStates(nvmlDevice_t device,
-                                                             nvmlPstates_t *pstates, unsigned int size);
-
-/**
- * Retrieve the GPCCLK min max VF offset value.
- * @param[in]   device                         The identifier of the target device
- * @param[out]  minOffset                      The retrieved GPCCLK VF min offset value
- * @param[out]  maxOffset                      The retrieved GPCCLK VF max offset value
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetGpcClkMinMaxVfOffset(nvmlDevice_t device,
-                                                       int *minOffset, int *maxOffset);
-
-/**
- * Retrieve the MemClk (Memory Clock) min max VF offset value.
- * @param[in]   device                         The identifier of the target device
- * @param[out]  minOffset                      The retrieved MemClk VF min offset value
- * @param[out]  maxOffset                      The retrieved MemClk VF max offset value
- *
- * @return
- *         - \ref NVML_SUCCESS                 if \a offset has been successfully queried
- *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
- *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a offset is NULL
- *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
- *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetMemClkMinMaxVfOffset(nvmlDevice_t device,
-                                                       int *minOffset, int *maxOffset);
-
-/**
- * Get fabric information associated with the device.
- *
- * %HOPPER_OR_NEWER%
- *
- * On Hopper + NVSwitch systems, GPU is registered with the NVIDIA Fabric Manager
- * Upon successful registration, the GPU is added to the NVLink fabric to enable
- * peer-to-peer communication.
- * This API reports the current state of the GPU in the NVLink fabric
- * along with other useful information.
- *
- * @param device                               The identifier of the target device
- * @param gpuFabricInfo                        Information about GPU fabric state
- *
- * @return
- *         - \ref NVML_SUCCESS                 Upon success
- *         - \ref NVML_ERROR_NOT_SUPPORTED     If \a device doesn't support gpu fabric
- */
-nvmlReturn_t DECLDIR nvmlDeviceGetGpuFabricInfo(nvmlDevice_t device, nvmlGpuFabricInfo_t *gpuFabricInfo);
-
-/** @} */
+/** @} */ // @defgroup nvmlMultiInstanceGPU
 
 /***************************************************************************************************/
 /** @defgroup GPM NVML GPM
  *  @{
  */
 /***************************************************************************************************/
 /** @defgroup nvmlGpmEnums GPM Enums
@@ -9329,66 +9962,53 @@
  *
  * @return
  *         - NVML_SUCCESS on success
  *         - Nonzero NVML_ERROR_? enum if there is an error in processing the query
  */
 nvmlReturn_t DECLDIR nvmlGpmQueryDeviceSupport(nvmlDevice_t device, nvmlGpmSupport_t *gpmSupport);
 
-/** @} */ // @defgroup nvmlGpmFunctions
-/** @} */ // @defgroup GPM
-
-/***************************************************************************************************/
-/** @defgroup nvmlDevice definitions related to Counter Collection Unit
- *  @{
- */
-/***************************************************************************************************/
-
-/* CCU Stream State */
-#define NVML_COUNTER_COLLECTION_UNIT_STREAM_STATE_DISABLE 0
-#define NVML_COUNTER_COLLECTION_UNIT_STREAM_STATE_ENABLE  1
-
+/* GPM Stream State */
 /**
- * Get counter collection unit stream state.
+ * Get GPM stream state.
  *
  * %HOPPER_OR_NEWER%
  * Supported on Linux, Windows TCC.
  *
  * @param device                               The identifier of the target device
- * @param state                                Returns counter collection unit stream state
- *                                             NVML_COUNTER_COLLECTION_UNIT_STREAM_STATE_DISABLE or
- *                                             NVML_COUNTER_COLLECTION_UNIT_STREAM_STATE_ENABLE
+ * @param state                                Returns GPM stream state
+ *                                             NVML_FEATURE_DISABLED or NVML_FEATURE_ENABLED
  *
  * @return
- *         - \ref NVML_SUCCESS                 if \a current counter collection unit stream state were successfully queried
+ *         - \ref NVML_SUCCESS                 if \a current GPM stream state were successfully queried
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
  *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a  device is invalid or \a state is NULL
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
  */
-nvmlReturn_t DECLDIR nvmlDeviceCcuGetStreamState(nvmlDevice_t device, unsigned int *state);
+nvmlReturn_t DECLDIR nvmlGpmQueryIfStreamingEnabled(nvmlDevice_t device, unsigned int *state);
 
 /**
- * Set counter collection unit stream state.
+ * Set GPM stream state.
  *
  * %HOPPER_OR_NEWER%
  * Supported on Linux, Windows TCC.
  *
  * @param device                               The identifier of the target device
- * @param state                                Counter collection unit stream state,
- *                                             NVML_COUNTER_COLLECTION_UNIT_STREAM_STATE_DISABLE or
- *                                             NVML_COUNTER_COLLECTION_UNIT_STREAM_STATE_ENABLE
+ * @param state                                GPM stream state,
+ *                                             NVML_FEATURE_DISABLED or NVML_FEATURE_ENABLED
  *
  * @return
- *         - \ref NVML_SUCCESS                 if \a current counter collection unit stream state is successfully set
+ *         - \ref NVML_SUCCESS                 if \a current GPM stream state is successfully set
  *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
  *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid
  *         - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
  */
-nvmlReturn_t DECLDIR nvmlDeviceCcuSetStreamState(nvmlDevice_t device, unsigned int state);
+nvmlReturn_t DECLDIR nvmlGpmSetStreamingEnabled(nvmlDevice_t device, unsigned int state);
 
-/** @} */ // @defgroup CCU
+/** @} */ // @defgroup nvmlGpmFunctions
+/** @} */ // @defgroup GPM
 
 #define NVML_NVLINK_POWER_STATE_HIGH_SPEED    0x0
 #define NVML_NVLINK_POWER_STATE_LOW           0x1
 
 #define NVML_NVLINK_LOW_POWER_THRESHOLD_MIN   0x1
 #define NVML_NVLINK_LOW_POWER_THRESHOLD_MAX   0x1FFF
 #define NVML_NVLINK_LOW_POWER_THRESHOLD_RESET 0xFFFFFFFF
@@ -9414,14 +10034,73 @@
  *        - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a Threshold is not within range
  *        - \ref NVML_ERROR_NOT_SUPPORTED     if this query is not supported by the device
  *
  **/
 nvmlReturn_t DECLDIR nvmlDeviceSetNvLinkDeviceLowPowerThreshold(nvmlDevice_t device, nvmlNvLinkPowerThres_t *info);
 
 /**
+ * Set the global nvlink bandwith mode
+ *
+ * @param nvlinkBwMode             nvlink bandwidth mode
+ * @return
+ *         - \ref NVML_SUCCESS                on success
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT if an invalid argument is provided
+ *         - \ref NVML_ERROR_IN_USE           if P2P object exists
+ *         - \ref NVML_ERROR_NOT_SUPPORTED    if GPU is not Hopper or newer architecture.
+ *         - \ref NVML_ERROR_NO_PERMISSION    if not root user
+ */
+nvmlReturn_t DECLDIR nvmlSystemSetNvlinkBwMode(unsigned int nvlinkBwMode);
+
+/**
+ * Get the global nvlink bandwith mode
+ *
+ * @param nvlinkBwMode             reference of nvlink bandwidth mode
+ * @return
+ *         - \ref NVML_SUCCESS                on success
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT if an invalid pointer is provided
+ *         - \ref NVML_ERROR_NOT_SUPPORTED    if GPU is not Hopper or newer architecture.
+ *         - \ref NVML_ERROR_NO_PERMISSION    if not root user
+ */
+nvmlReturn_t DECLDIR nvmlSystemGetNvlinkBwMode(unsigned int *nvlinkBwMode);
+
+/**
+ * Set new power limit of this device.
+ *
+ * For Kepler &tm; or newer fully supported devices.
+ * Requires root/admin permissions.
+ *
+ * See \ref nvmlDeviceGetPowerManagementLimitConstraints to check the allowed ranges of values.
+ *
+ * See \ref nvmlPowerValue_v2_t for more information on the struct.
+ *
+ * \note Limit is not persistent across reboots or driver unloads.
+ * Enable persistent mode to prevent driver from unloading when no application is using the device.
+ *
+ * This API replaces nvmlDeviceSetPowerManagementLimit. It can be used as a drop-in replacement for the older version.
+ *
+ * @param device                               The identifier of the target device
+ * @param powerValue                           Power management limit in milliwatts to set
+ *
+ * @return
+ *         - \ref NVML_SUCCESS                 if \a limit has been set
+ *         - \ref NVML_ERROR_UNINITIALIZED     if the library has not been successfully initialized
+ *         - \ref NVML_ERROR_INVALID_ARGUMENT  if \a device is invalid or \a powerValue is NULL or contains invalid values
+ *         - \ref NVML_ERROR_NOT_SUPPORTED     if the device does not support this feature
+ *         - \ref NVML_ERROR_GPU_IS_LOST       if the target GPU has fallen off the bus or is otherwise inaccessible
+ *         - \ref NVML_ERROR_UNKNOWN           on any unexpected error
+ *
+ * @see NVML_FI_DEV_POWER_AVERAGE 
+ * @see NVML_FI_DEV_POWER_INSTANT
+ * @see NVML_FI_DEV_POWER_MIN_LIMIT
+ * @see NVML_FI_DEV_POWER_MAX_LIMIT
+ * @see NVML_FI_DEV_POWER_CURRENT_LIMIT
+ */
+nvmlReturn_t DECLDIR nvmlDeviceSetPowerManagementLimit_v2(nvmlDevice_t device, nvmlPowerValue_v2_t *powerValue);
+
+/**
  * NVML API versioning support
  */
 
 #ifdef NVML_NO_UNVERSIONED_FUNC_DEFS
 nvmlReturn_t DECLDIR nvmlInit(void);
 nvmlReturn_t DECLDIR nvmlDeviceGetCount(unsigned int *deviceCount);
 nvmlReturn_t DECLDIR nvmlDeviceGetHandleByIndex(unsigned int index, nvmlDevice_t *device);
@@ -9440,15 +10119,14 @@
 nvmlReturn_t DECLDIR nvmlDeviceGetComputeRunningProcesses_v2(nvmlDevice_t device, unsigned int *infoCount, nvmlProcessInfo_v2_t *infos);
 nvmlReturn_t DECLDIR nvmlDeviceGetGraphicsRunningProcesses(nvmlDevice_t device, unsigned int *infoCount, nvmlProcessInfo_v1_t *infos);
 nvmlReturn_t DECLDIR nvmlDeviceGetGraphicsRunningProcesses_v2(nvmlDevice_t device, unsigned int *infoCount, nvmlProcessInfo_v2_t *infos);
 nvmlReturn_t DECLDIR nvmlDeviceGetMPSComputeRunningProcesses(nvmlDevice_t device, unsigned int *infoCount, nvmlProcessInfo_v1_t *infos);
 nvmlReturn_t DECLDIR nvmlDeviceGetMPSComputeRunningProcesses_v2(nvmlDevice_t device, unsigned int *infoCount, nvmlProcessInfo_v2_t *infos);
 nvmlReturn_t DECLDIR nvmlDeviceGetGpuInstancePossiblePlacements(nvmlDevice_t device, unsigned int profileId, nvmlGpuInstancePlacement_t *placements, unsigned int *count);
 nvmlReturn_t DECLDIR nvmlVgpuInstanceGetLicenseInfo(nvmlVgpuInstance_t vgpuInstance, nvmlVgpuLicenseInfo_t *licenseInfo);
-
 #endif // #ifdef NVML_NO_UNVERSIONED_FUNC_DEFS
 
 #if defined(NVML_NO_UNVERSIONED_FUNC_DEFS)
 // We don't define APIs to run new versions if this guard is present so there is
 // no need to undef
 #elif defined(__NVML_API_VERSION_INTERNAL)
 #undef nvmlDeviceGetGraphicsRunningProcesses
@@ -9466,14 +10144,15 @@
 #undef nvmlDeviceGetHandleByPciBusId
 #undef nvmlInit
 #undef nvmlBlacklistDeviceInfo_t
 #undef nvmlGetBlacklistDeviceCount
 #undef nvmlGetBlacklistDeviceInfoByIndex
 #undef nvmlDeviceGetGpuInstancePossiblePlacements
 #undef nvmlVgpuInstanceGetLicenseInfo
+#undef nvmlDeviceSetPowerManagementLimit
 
 #endif
 
 #ifdef __cplusplus
 }
 #endif
```

## Comparing `nvidia_nvml_dev_cu12-12.1.55.dist-info/License.txt` & `nvidia_nvml_dev_cu12-12.2.81.dist-info/License.txt`

 * *Files identical despite different names*

## Comparing `nvidia_nvml_dev_cu12-12.1.55.dist-info/METADATA` & `nvidia_nvml_dev_cu12-12.2.81.dist-info/METADATA`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nvidia-nvml-dev-cu12
-Version: 12.1.55
+Version: 12.2.81
 Summary: NVML native dev links, headers
 Home-page: https://developer.nvidia.com/cuda-zone
 Author: Nvidia CUDA Installer Team
 Author-email: cuda_installer@nvidia.com
 License: NVIDIA Proprietary Software
 Keywords: cuda,nvidia,runtime,machine learning,deep learning
 Classifier: Development Status :: 4 - Beta
```

## Comparing `nvidia_nvml_dev_cu12-12.1.55.dist-info/RECORD` & `nvidia_nvml_dev_cu12-12.2.81.dist-info/RECORD`

 * *Files 18% similar despite different names*

```diff
@@ -1,10 +1,9 @@
 nvidia/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 nvidia/nvml_dev/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 nvidia/nvml_dev/include/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
-nvidia/nvml_dev/include/nvml.h,sha256=jSXkLSn787yiiv-jZ6itvKiMm2JeAPO6Pbu4B8ioNqA,502957
-nvidia/nvml_dev/lib/x64/nvml.lib,sha256=WHxWYQfTiuxn-LE8ErAuiAKp_UnxgV2_EQuOzCQo6bE,83052
-nvidia_nvml_dev_cu12-12.1.55.dist-info/License.txt,sha256=rW9YU_ugyg0VnQ9Y1JrkmDDC-Mk_epJki5zpCttMbM0,59262
-nvidia_nvml_dev_cu12-12.1.55.dist-info/METADATA,sha256=n1cerROPL_DlSKlw-PgAPHnqA_YvfnfnKd-qyjlJWRs,1504
-nvidia_nvml_dev_cu12-12.1.55.dist-info/WHEEL,sha256=i9qQj8KaD8_YEW0Vc2oS56fKju23RkQ-FVz-QmzVakQ,98
-nvidia_nvml_dev_cu12-12.1.55.dist-info/top_level.txt,sha256=fTkAtiFuL16nUrB9ytDDtpytz2t0B4NvYTnRzwAhO14,7
-nvidia_nvml_dev_cu12-12.1.55.dist-info/RECORD,,
+nvidia/nvml_dev/include/nvml.h,sha256=qN0EXxg9v3MknRMFepwCCQeBzJ02SrJ1fucLzqpvUmE,535622
+nvidia_nvml_dev_cu12-12.2.81.dist-info/License.txt,sha256=rW9YU_ugyg0VnQ9Y1JrkmDDC-Mk_epJki5zpCttMbM0,59262
+nvidia_nvml_dev_cu12-12.2.81.dist-info/METADATA,sha256=xQcH-aWGv7KuD6sf2dwC488NOG74KTIjDqRWX9wEA3Y,1504
+nvidia_nvml_dev_cu12-12.2.81.dist-info/WHEEL,sha256=-kQi_VMfvRQozZJT7HUPMfY-5vLo0LVTmAylNJ3Ft98,106
+nvidia_nvml_dev_cu12-12.2.81.dist-info/top_level.txt,sha256=fTkAtiFuL16nUrB9ytDDtpytz2t0B4NvYTnRzwAhO14,7
+nvidia_nvml_dev_cu12-12.2.81.dist-info/RECORD,,
```

