# CANN 9.1.1 Release Notes

<!-- md-trans-meta sourceCommit=unknown translatedAt=2026-08-31T11:39:25.704Z pushedAt=2026-09-01T03:10:19.641Z -->

## Version Download Address

<https://www.hiascend.com/en/cann/download>

## Version Mapping

CANN Software Version Mapping Table
<table style="text-align:center;">
  <tr>
    <th>CANN</th>
    <th>Driver Version (Ascend HDK)</th>
  </tr>
  <tr>
    <td>9.1.1</td>
    <td><a href="https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C22%2CAArch64%2Conline_Yum">26.1.1</a></td>
  </tr>
</table>

## Version Compatibility

CANN and Ascend HDK Version Compatibility
<table style="table-layout: fixed; width: 750px; text-align:center;">
  <colgroup>
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
  </colgroup>
  <thead>
    <tr>
      <th rowspan="3">CANN</th>
      <th colspan="6">Driver Version (Ascend HDK)</th>
    </tr>
    <tr>
      <th>25.0.X</th>
      <th>25.2.X</th>
      <th>25.3.X</th>
      <th>25.5.X</th>
      <th>26.0.RC1/25.7.RC1</th>
      <th>26.1.1</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>8.5.2</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
    <tr>
      <td>9.0.X</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
    <tr>
      <td>9.1.X</td>
      <td>N</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
  </tbody>
</table>

## Internal Matching Relationships of CANN Software Packages

### CANN Combination Compatibility

CANN 9.1.1 contains three combined packages: Toolkit, ops (operator package), and NNAL (acceleration library). The following table lists the matching relationship between the CANN combined packages and their subpackages. You can upgrade six subpackages independently as needed.

<table>
  <thead>
    <tr>
      <th>CANN Combined Package</th>
      <th>Subpackage Name</th>
      <th>Subpackage Version</th>
      <th>Architecture</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="22">Toolkit</td>
      <td>ascendnpu-ir</td>
      <td>1.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-acl-extend</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">ops</td>
      <td>cann-dvpp</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.1.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">NNAL</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.1.1">9.1.1</a></td>
      <td>Arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops and Toolkit Compatibility
The CANN ops package has been decoupled from Toolkit and supports independent upgrade. You can install it as needed.

|ops Version  |Compatible Toolkit Version  |
|--|--|
| [ascend-cann-ops 9.1.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.1) | [ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |


### Compatibility of Independently Upgradable Subpackages in the CANN ops Package

| CANN Subpackage Version                                                 | Version Source Tag                                                 | Compatible CANN Version                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.1.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.1/) | [v9.1.1](https://gitcode.com/cann/ops-math/tags/v9.1.1)      | CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-nn 9.1.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.1/) | [v9.1.1](https://gitcode.com/cann/ops-nn/tags/v9.1.1)        | CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-cv 9.1.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.1/) | [v9.1.1](https://gitcode.com/cann/ops-cv/tags/v9.1.1)        | CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-transformer 9.1.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.1/) | [v9.1.1](https://gitcode.com/cann/ops-transformer/tags/v9.1.1) | CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hccl 9.1.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.1/) | [v9.1.1](https://gitcode.com/cann/hccl/tags/v9.1.1)          | CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hixl 9.1.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.1/) | [v9.1.1](https://gitcode.com/cann/hixl/tags/v9.1.1)          | CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |

For the specific operations of independent subpackage upgrade, see [Independent Subpackage Upgrade](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/910/softwareinst/instg/instg_0030.html).

## Removed and Deprecated Features

### NOTE

- Deleted features are those that have been removed in the current version.
- Deprecated features are those marked as deprecated in the current version and will be removed in future versions.
- Replace `${install_path}` in this section with the CANN software installation path.

### Runtime

**The following directories, files, and APIs are marked as deprecated in CANN 9.1.0 and are planned for removal in versions after June 30, 2027.**

| Deprecated Item   | Replacement |
| ------------------------ | ---------------------- |
| Header files in the `include/driver` directory | `pkg_inc/driver` directory     |

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

| Deprecated Item                                       | Replacement                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ${install_path}/ascend-toolkit/latest/runtime/include/acl    | ${install_path}/cann/include/acl                             |
| ${install_path}/ascend-toolkit/latest/runtime/include/aclnn  | ${install_path}/cann/include/aclnn                           |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                           |
| All header files in `${install_path}/cann/pkg_inc/runtime/runtime` directory | No related functions will be provided in subsequent versions                                           |
| The rtGetC2cCtrlAddr API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_ffts.h` | Use the aclrtGetHardwareSyncAddr API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtFftsTaskLaunch and rtFftsTaskLaunchWithFlag APIs in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_ffts.h` | No related functions will be provided in subsequent versions                                           |
| The rtBindHostPid, rtUnbindHostPid, rtProfSetProSwitch, rtQueryProcessHostPid, rtGetDeviceIdByGeModelIdx, rtGetExceptionRegInfo, rtGetMaxModelNum, rtLabelGoto, rtLabelGotoEx, rtProfilerConfig, rtProfilerInit, rtProfilerTrace, rtProfilingCommandHandle, rtProfRegisterCtrlCallback, rtSetDeviceIdByGeModelIdx, rtSetExceptCallback, rtSetMsprofReporterCallback, rtSetProfDirEx, and rtUnsetDeviceIdByGeModelIdx APIs in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | No related functions will be provided in subsequent versions                                           |
| The rtGetBinaryDeviceBaseAddr API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtBinaryGetDevAddress API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtGetTaskIdAndStreamID API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtGetThreadLastTaskId and aclrtStreamGetId APIs in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtLabelCreate, rtLabelCreateEx, rtLabelCreateExV2, and rtLabelCreateV2 APIs in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtCreateLabel API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtLabelListCpy API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtCreateLabelList and aclrtDestroyLabelList APIs in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtLabelSet API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtSetLabel API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtLabelSwitchByIndex API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtSwitchLabelByIndex API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtProfilerTraceEx API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtProfTrace API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtRegDeviceStateCallbackEx API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtRegDeviceStateCallback API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtRegTaskFailCallbackByModule API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtSetExceptionInfoCallback API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetIpcMemorySuperPodPid API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtIpcMemImportPidInterServer API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetIpcNotifySuperPodPid API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtNotifySetImportPidInterServer API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetTaskAbortCallBack API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtSetTaskAbortCallBack API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetTaskFailCallback API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtSetExceptionInfoCallback API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtStreamGetMode API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtGetStreamAttribute API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtStreamSetMode API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtSetStreamFailureMode and aclrtSetStreamOverflowSwitch APIs in `${install_path}/cann/include/acl/aclrt.h` instead |
| The aclsysGetCANNVersion API in `${install_path}/ascend-toolkit/latest/include/acl/acl.h` | Use the aclsysGetVersionStr and aclsysGetVersionNum APIs in `${install_path}/cann/include/acl/acl.h` instead |
| libascendcl.so in `${install_path}/ascend-toolkit/latest/lib64` | Use the libacl_rt.so, libacl_mdl.so, and libacl_op_executor.so in `${install_path}/cann/lib64` instead |

### Graph Engine

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

| Deprecated Directory                                                   | Replacement Directory                                                 |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                         |
| ${install_path}/ascend-toolkit/latest/compiler/python/func2graph | `func2graph` in the `${install_path}/cann/x86_64-linux/python` directory |

Starting from Ascend 950, the aclblas and aclop APIs are no longer recommended. They will be gradually deprecated in later versions. Migrate to the corresponding aclnn operator APIs.

### Operator Libraries

- **Incompatibility changes**: Control operators Identity, IdentityN, Rank, Shape, and ShapeN are migrated from ops-nn to ops-math. These operators are migrated from the `ops_proto_nn.h` and `es_nn` directories to the `ops_proto_math.h` and `es_math` directories. You need to update the related header file references ([!2333](https://gitcode.com/cann/ops-math/pull/2333), [!3995](https://gitcode.com/cann/ops-nn/pull/3995)).

**The following directories, files, and APIs are marked as deprecated in CANN 9.0.0 and will be removed in later versions after March 30, 2027.**

| Deprecated Item | Replacement Item |
| ------------------------------------------------------------ | ------------------------------------------------ |
| aclnnGroupedMatMulAllReduce API | aclnnMatmulAllReduce |
| aclnnGroupedMatmul, aclnnGroupedMatmulV2, aclnnGroupedMatmulV3, and aclnnGroupedMatmulV4 APIs | aclnnGroupedMatmulV5 |
| aclnnFusedInferAttentionScore, aclnnFusedInferAttentionScoreV2, and aclnnFusedInferAttentionScoreV3 APIs | aclnnFusedInferAttentionScoreV4 |
| aclnnIncreFlashAttention, aclnnIncreFlashAttentionV2, and aclnnIncreFlashAttentionV3 APIs | aclnnIncreFlashAttentionV4 |
| aclnnPromptFlashAttention and aclnnPromptFlashAttentionV2 APIs | aclnnPromptFlashAttentionV3 |
| aclnnMlaProlog and aclnnMlaPrologV2WeightNz APIs | aclnnMlaPrologV3WeightNz |
| aclnnMatmulAllReduceAddRmsNorm API | aclnnMatmulAllReduce and aclnnAddRmsNorm |
| aclnnQuantMatmulAllReduceAddRmsNorm API | aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm |
| aclnnWeightQuantMatmulAllReduceAddRmsNorm API | aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm |
| aclnnInplaceQuantMatmulAllReduceAddRmsNorm API | aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm |
| aclnnInplaceMatmulAllReduceAddRmsNorm API | aclnnMatmulAllReduce and aclnnAddRmsNorm |
| aclnnInplaceWeightQuantMatmulAllReduceAddRmsNorm API | aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm |

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

Operators are split into component packages. Each independent component package of different operators contains multiple libraries and header files. In the following table, `${ops_project}` represents the actual cv, math, nn, transformer, and legacy.

| Deprecated Item | Replacement Item |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/*.h | ${install_path}/cann/opp/built-in/op_graph/inc/\${ops_project}_ops_proto.h |
| ${install_path}/ascend-toolkit/latest/lib64/libopapi.so | ${install_path}/cann/lib64/libopapi_\${ops_project}.so |
| aclnnGroupedMatMulAllReduce API | No replacement available |
| aclnnWeightQuantBatchMatmul API | aclnnWeightQuantBatchMatmulV3 API |
| aclnnQuantMatmul, aclnnQuantMatmulV2, aclnnQuantMatmulV3, and aclnnQuantMatmulV4 APIs | aclnnQuantMatmulV5 API |
| aclnnGroupedMatmul, aclnnGroupedMatmulV2, aclnnGroupedMatmulV3, and aclnnGroupedMatmulV4 APIs | aclnnGroupedMatmulV5 API |
| aclnnIncreFlashAttentionV2 and aclnnIncreFlashAttentionV3 APIs | aclnnIncreFlashAttentionV4 API |
| aclnnPromptFlashAttentionV2 API | aclnnPromptFlashAttentionV3 API |
| aclnnFusedInferAttentionScoreV2 and aclnnFusedInferAttentionScoreV3 APIs | aclnnFusedInferAttentionScoreV4 API |


### Acceleration Libraries

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

The following operator IRs are deprecated for the DVPP acceleration feature: Crop, CropAndResize, DecodeAndCropJpeg, DecodeJpeg, PadV3D, Resize, ResizeV2, ResizeBicubic, ResizeBilinearV2, ResizeNearestNeighborV2, ReverseV2, WarpPerspective , WarpAffineV2, AdjustContrast, AdjustHue, AdjustSaturation.

| Deprecated Item | Replacement Item |
| ------------------------------------------------------------ | --------------------------- |
| The AdjustBrightness operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustBrightness API |
| The AdjustBrightnessV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustBrightness API |
| The AdjustContrastWithMean operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustContrast API |
| The AdjustSaturationV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustSaturation API |
| The GaussianBlur operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppGaussianBlur API |
| The ImgCrop operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppCrop API |
| The RgbToGrayscale operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppRgbToGrayscale API |
| The Rotate operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppRotate API |
| The CropAndResizeV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h | acldvppCropAndResize API |
| The ImgToTensor operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h | acldvppImgToTensor API |
| The NormalizeV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h | acldvppNormalize API |

### Debugging and Analysis Tools

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

| Deprecated Item | Replacement Item |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| The profiling header files `aprof_pub.h`, `prof_api.h`, and `prof_common.h` are deprecated from `${install_path}/ascend-toolkit/latest/include/experiment/msprof/toolchain` | The profiling header files `aprof_pub.h`, `prof_api.h`, and `prof_common.h` are moved to `${install_path}/cann/pkg_inc/profiling` |

### Diagnostics

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

| Deprecated Item | Replacement Item |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Error Manager header file ${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h | Error Manager header file ${install_path}/cann/include/base/err_msg.h |
| REPORT_INNER_ERROR and REPORT_CALL_ERROR APIs in ${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h | REPORT_INNER_ERR_MSG API |
| REPORT_INPUT_ERROR and REPORT_ENV_ERROR APIs | REPORT_PREDEFINED_ERR_MSG API |
| Log header file ${install_path}/ascend-toolkit/latest/include/toolchain/slog.h | Log header file ${install_path}/cann/pkg_inc/base/dlog_pub.h |
| Log header file ${install_path}/ascend-toolkit/latest/include/base/alog_pub.h | Log header file ${install_path}/cann/pkg_inc/base/dlog_pub.h |
| AlogCheckDebugLevel API in `${install_path}/ascend-toolkit/latest/include/base/alog_pub.h` | CheckLogLevel API in `${install_path}/cann/pkg_inc/base/dlog_pub.h` |
| AlogRecord API in `${install_path}/ascend-toolkit/latest/include/base/alog_pub.h` | DlogRecord API in `${install_path}/cann/pkg_inc/base/dlog_pub.h`, or the wrapped macros such as dlog_error and dlog_warn |

### Model Compression Toolkit

The following features of the Model Compression Toolkit are marked as deprecated in CANN 9.0.0 and have been removed in this version.
- Non-uniform quantization
- Automatic mixed precision
- Approximate calibration
- int4 quantization-aware training
- All amct_mindspore features


## Known Issues

Symptom: When the value of the input parameter deqScale of the operator aclnnMatmulCompressDequant is `inf`/`-inf`, `inf` or `nan` is displayed in its precision details.
[Introduced in] CANN 8.5.0
[Impact] Triggered by specially constructed test cases, not introduced by a new operator, and in actual quantization tasks there is no case where deqScale is `-inf` or `inf`. The impact is controllable in the current version.
[Workaround] In actual quantization tasks, there is no case where deqScale is `-inf` or `inf`.

## Fixed Issues

The following issues are fixed in version 9.1.1:
- Fixed the issue where the HF32 attribute was not correctly passed to the bottom layer, causing performance degradation, when the MM operators on Atlas A2 and Atlas A3 products and Ascend 950 NPUs were executed through the GE aclnn fallback callback path.
- Fixed the precision error issue of the RmsNorm operator on Atlas A2 and Atlas A3 products when the input shape exceeds the int32 maximum value.
- Fixed the issue where the `_deterministic_level` attribute was not inherited when the Matmul operator fusion path on Atlas A2 and Atlas A3 products was converted to Matmul v2, causing the attributes of subsequent nodes to be lost.
- Fixed the issue where the fine-grained FSDP communication and computation pipeline was blocked under host-side performance degradation of the Matmul operators on Atlas A2 and Atlas A3 products, causing overall model performance degradation.
- Fixed the issue where the FAG operator occasionally failed to fully clear the pad in EOD use cases.
- Fixed the issue where the orderStream graph rule validation failed when aclgraph AICPU expansion used the same stream for the HCCL main stream and the capture stream on Atlas A3 products.
- Fixed the issue where the AllGatherRingConcurrentDirect algorithm deadlocked when dispatching primary/standby stream tasks in large-scale clusters on Atlas A3 products.
- Fixed the issue where the RingMLAOperation API demo failed to run when importing environment variables from a non-mainline version on Atlas A2 and Atlas A3 products.
- Fixed the issue where `torch_npu.npu_format_cast` fell back from interception to aclop when the format and shape did not match on Atlas A2 and Atlas A3 products.
- (Incompatible change) Fixed the issue that the default values of `pri_mask_mode` and `cmp_ori_win_right` for the SparseFlashMLA operator's torch API in Atlas A2 and A3 products.

The following issues are fixed in version 9.1.0:
- Fixed the issue where the QuantBatchMatmulV3 operator on Atlas inference products caused read/write conflicts when `AUTO_SYNC=false` was specified during compilation.
- For Atlas A2 products and Atlas A3 products, fixed the issue where the MatmulReduceScatterV2 operator cleared the flag bit too quickly in cases with M less than 512, causing other devices to fail to detect it and eventually time out.
- Fixed the issue where, with MoE EP on Atlas A2 products, multi-bit faults injected into the on-chip memory of a D node prevented entry into the quick recovery process.
- Fixed the issue where communication timeout occurred probabilistically at random step positions after 500+ steps in a 4k-device training task.
- Fixed the refill backlog issue caused by frequent task interruption and restart of decode in PD disaggregation.
- Fixed the issue where the IR prototype name conflict between user-defined custom operators and built-in operators in the open-source repository caused the IR prototype name not to take effect.
- Fixed the issue where the aclnnAddmv operator occasionally triggered core dump during load testing.
- Fixed the issue where an exception was reported when a 10,000-device task was launched.
- Fixed the issue where MatMulV3 performance was worse than MatMulV2 for specific shapes in aclgraph use cases.
- Fixed the precision issues for fused_quant_mat_mul.
- Fixed the precision issues of BatchMatmulV2 with specific bias.
- Fixed the precision issues of the FAG operator with short-sequence GQA and NoMask.

## Fixed Vulnerabilities

For details about the fixed vulnerabilities for open-source and third-party software in this version, see [Fixed Vulnerabilities](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/910/maintenref/refdoc/refer002.html).
