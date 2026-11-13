# CANN 9.2.1 Release Notes
<!-- npu="950,A3,910b,910,310p,310b" id1 -->
<!-- md-trans-meta sourceCommit=unknown translatedAt=2026-11-06T09:45:34.860Z pushedAt=2026-11-09T12:26:31.030Z nl=2 -->

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
    <td>9.2.1</td>
    <td><a href="https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C22%2CAArch64%2Conline_Yum">26.2.RC1</a></td>
  </tr>
</table>

## Version Compatibility

CANN and Ascend HDK Version Compatibility
<table style="table-layout: fixed; width: 900px; text-align:center;">
  <colgroup>
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
  </colgroup>
  <thead>
    <tr>
      <th rowspan="3">CANN</th>
      <th colspan="7">Driver Version (Ascend HDK)</th>
    </tr>
    <tr>
      <th>25.0.X</th>
      <th>25.2.X</th>
      <th>25.3.X</th>
      <th>25.5.X</th>
      <th>26.0.RC1/25.7.RC1</th>
      <th>26.1.1</th>
      <th>26.2.RC1</th>
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
      <td>Y</td>
    </tr>
     <tr>
      <td>9.2.X</td>
      <td>N</td>
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

CANN 9.2.0 contains three combined packages: Toolkit, ops (operator package), and NNAL (acceleration library). The following table lists the matching relationship between the CANN combined packages and their subpackages. You can upgrade six subpackages independently as needed.

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
      <td rowspan="24">Toolkit</td>
      <td>ascendnpu-ir</td>
      <td>2.0.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-acl-extend</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-as</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pypto</td>
      <td><a href="https://gitcode.com/cann/pypto/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">ops</td>
      <td>cann-dvpp</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.2.1</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">NNAL</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.2.1">9.2.1</a></td>
      <td>Arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops and Toolkit Compatibility

The CANN ops package has been decoupled from Toolkit and supports independent upgrade. You can install it as needed.

|ops Version  |Compatible Toolkit Version  |
|--|--|
| [ascend-cann-ops 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |

### Compatibility of Independently Upgradable Subpackages in the CANN ops Package

| CANN Subpackage Version                                                 | Version Source Tag                                                 | Compatible CANN Version                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.2.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.1/) | [v9.2.1](https://gitcode.com/cann/ops-math/tags/v9.2.1)      | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-nn 9.2.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.1/) | [v9.2.1](https://gitcode.com/cann/ops-nn/tags/v9.2.1)        | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-cv 9.2.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.1/) | [v9.2.1](https://gitcode.com/cann/ops-cv/tags/v9.2.1)        | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-transformer 9.2.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.1/) | [v9.2.1](https://gitcode.com/cann/ops-transformer/tags/v9.2.1) | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hccl 9.2.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.1/) | [v9.2.1](https://gitcode.com/cann/hccl/tags/v9.2.1)          | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hixl 9.2.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.1/) | [v9.2.1](https://gitcode.com/cann/hixl/tags/v9.2.1)          | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |

For details about independent subpackage upgrade, see [Independent Subpackage Upgrade](https://www.hiascend.com/en/document/detail/CANNCommunityEdition/920/softwareinst/instg/instg_0030.html). The ops subpackage version must be greater than or equal to the ops combination package version.

## Removed and Deprecated Features

### Description

- Deleted features are those that have been removed in the current version.
- Deprecated features are those marked as deprecated in the current version and will be removed in future releases.
- Replace `${install_path}` in this section with the CANN software installation path.

### Operator Programming

#### C APIs

- Deprecated all synchronous APIs ending with `_sync`. ([!5789](https://gitcode.com/cann/asc-devkit/pull/5789))
- Deprecated the v1-v4 APIs and provided alternative APIs. ([!3710](https://gitcode.com/cann/asc-devkit/pull/3710))
- Deprecated the `asc_get_block_num` and `asc_get_block_idx` APIs and prompted users to use compiler keywords. ([!5216](https://gitcode.com/cann/asc-devkit/pull/5216))

### Runtime

**The following directories, files, and APIs are marked as deprecated in CANN 9.2.0 and are planned for removal in versions after September 30, 2027.**

| Deprecated Item   | Replacement |
| ------------------------------- | ------------------------------------------------------------------------- |
| aclrtGetVersion                 | aclsysGetVersionNum aclsysGetVersionStr                                   |
| aclrtMemcpyAsyncWithCondition   | aclrtMemcpyAsync                                                          |
| aclrtSetExceptionInfoCallback   | aclrtExceptionInfoCallbackRegister  aclrtExceptionInfoCallbackUnregister  |

**The following directories, files, and APIs are marked as deprecated in CANN 9.1.0 and are planned for removal in versions after June 30, 2027.**

| Deprecated Item   | Replacement |
| ------------------------ | ---------------------- |
| Header files in the `include/driver` directory | `pkg_inc/driver` directory     |

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

| Deprecated Item                                       | Replacement                                       |
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
<!-- npu="950" id17 -->
### Graph Engine

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

| Deprecated Directory                                                   | Replacement Directory                                                 |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                         |
| ${install_path}/ascend-toolkit/latest/compiler/python/func2graph | `func2graph` in the `${install_path}/cann/x86_64-linux/python` directory |

Starting from Ascend 950PR&950DT products, the aclblas and aclop APIs are not recommended. They will be gradually deprecated in future releases. You are advised to use the corresponding aclnn operator APIs.
<!-- end id17 -->
### Operator Libraries

- **Incompatibility changes**:
  - The implementation and registration configuration of the kth_value, median, and nan_median operators have been migrated from ops-math to ops-nn. To use these operators, upgrade the ops-nn component accordingly ([!5809](https://gitcode.com/cann/ops-math/pull/5809), [!10728](https://gitcode.com/cann/ops-nn/pull/10728)). These operators were migrated from the `ops_proto_math.h` and `es_math` directories to the `ops_proto_nn.h` and `es_nn` directories.
  - The RoiPooling operator has been migrated from ops-cv to ops-nn. To use this operator, upgrade the ops-nn component accordingly to avoid prototype definition conflicts after the upgrade ([!1442](https://gitcode.com/cann/ops-cv/pull/1442), [!9609](https://gitcode.com/cann/ops-nn/pull/9609)). This operator was migrated from the `ops_proto_cv.h` and `es_cv` directories to the `ops_proto_nn.h` and `es_nn` directories.

**The following directories, files, and APIs are marked as deprecated in CANN 9.0.0 and will be removed in later versions after March 30, 2027.**

| Deprecated Item                                       | Replacement                           |
| ------------------------------------------------------------ | ------------------------------------------------ |
| aclnnGroupedMatMulAllReduce API                              | aclnnMatmulAllReduce                             |
| aclnnGroupedMatmul, aclnnGroupedMatmulV2, aclnnGroupedMatmulV3, and aclnnGroupedMatmulV4 APIs | aclnnGroupedMatmulV5                             |
| aclnnFusedInferAttentionScore, aclnnFusedInferAttentionScoreV2, and aclnnFusedInferAttentionScoreV3 APIs | aclnnFusedInferAttentionScoreV4                  |
| aclnnIncreFlashAttention, aclnnIncreFlashAttentionV2, and aclnnIncreFlashAttentionV3 APIs | aclnnIncreFlashAttentionV4                       |
| aclnnPromptFlashAttention and aclnnPromptFlashAttentionV2 APIs   | aclnnPromptFlashAttentionV3                      |
| aclnnMlaProlog and aclnnMlaPrologV2WeightNz APIs                 | aclnnMlaPrologV3WeightNz                         |
| aclnnMatmulAllReduceAddRmsNorm API                           | aclnnMatmulAllReduce and aclnnAddRmsNorm            |
| aclnnQuantMatmulAllReduceAddRmsNorm API                      | aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm     |
| aclnnWeightQuantMatmulAllReduceAddRmsNorm API            | aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm |
| aclnnInplaceQuantMatmulAllReduceAddRmsNorm API               | aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm     |
| aclnnInplaceMatmulAllReduceAddRmsNorm API                    | aclnnMatmulAllReduce and aclnnAddRmsNorm            |
| aclnnInplaceWeightQuantMatmulAllReduceAddRmsNorm API         | aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm |

### Acceleration Libraries

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

The following operator IRs are deprecated for the DVPP acceleration feature: Crop, CropAndResize, DecodeAndCropJpeg, DecodeJpeg, PadV3D, Resize, ResizeV2, ResizeBicubic, ResizeBilinearV2, ResizeNearestNeighborV2, ReverseV2, WarpPerspective , WarpAffineV2, AdjustContrast, AdjustHue, AdjustSaturation.

| Deprecated Item                                       | Replacement      |
| ------------------------------------------------------------ | --------------------------- |
| The AdjustBrightness operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustBrightness API |
| The AdjustBrightnessV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustBrightness API |
| The AdjustContrastWithMean operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustContrast API   |
| The AdjustSaturationV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppAdjustSaturation API |
| The GaussianBlur operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppGaussianBlur API     |
| The ImgCrop operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppCrop API             |
| The RgbToGrayscale operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppRgbToGrayscale API   |
| The Rotate operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h | acldvppRotate API           |
| The CropAndResizeV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h | acldvppCropAndResize API    |
| The ImgToTensor operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h | acldvppImgToTensor API      |
| The NormalizeV2 operator IR will be deprecated from ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h | acldvppNormalize API        |

### Debugging and Analysis Tools

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

| Deprecated Item                                       | Replacement                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| The profiling header files `aprof_pub.h`, `prof_api.h`, and `prof_common.h` are deprecated from `${install_path}/ascend-toolkit/latest/include/experiment/msprof/toolchain` | The profiling header files `aprof_pub.h`, `prof_api.h`, and `prof_common.h` are moved to `${install_path}/cann/pkg_inc/profiling` |

### Diagnostics

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

| Deprecated Item                                       | Replacement                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Error Manager header file ${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h | Error Manager header file ${install_path}/cann/include/base/err_msg.h |
| REPORT_INNER_ERROR and REPORT_CALL_ERROR APIs in ${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h | REPORT_INNER_ERR_MSG API                                     |
| REPORT_INPUT_ERROR and REPORT_ENV_ERROR APIs                     | REPORT_PREDEFINED_ERR_MSG API                                |
| Log header file ${install_path}/ascend-toolkit/latest/include/toolchain/slog.h | Log header file ${install_path}/cann/pkg_inc/base/dlog_pub.h       |
| Log header file ${install_path}/ascend-toolkit/latest/include/base/alog_pub.h | Log header file ${install_path}/cann/pkg_inc/base/dlog_pub.h       |
| AlogCheckDebugLevel API in `${install_path}/ascend-toolkit/latest/include/base/alog_pub.h` | CheckLogLevel API in `${install_path}/cann/pkg_inc/base/dlog_pub.h` |
| AlogRecord API in `${install_path}/ascend-toolkit/latest/include/base/alog_pub.h` | DlogRecord API in `${install_path}/cann/pkg_inc/base/dlog_pub.h`, or the wrapped macros such as dlog_error and dlog_warn |

**The following directories, files, and APIs are marked as deprecated in CANN 9.2.0 and will be removed in versions after September 30, 2027.**

| Deprecated Item | Replacement |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ASCEND_SLOG_PRINT_TO_STDOUT environment variable | ASCEND_LOG_PRINT_TO_STDOUT environment variable |
<!-- end id1 -->
<!-- npu="950,A3,910b" id11 -->
## Fixed Issues

The following issues have been fixed in version 9.2.1:
<!-- npu="A3,910b" id2 -->
- Fixed the issue where the NPUs of Atlas A2 products and Atlas A3 products lacked validation when the output tensor shape dimensions were invalid. ([!13774](https://gitcode.com/cann/ops-transformer/pull/13774))
<!-- end id2 -->
<!-- npu="950" id3 -->
- Fixed the issue where using EPLB and mooncake in inference tasks on Ascend 950PR&950DT products caused link establishment timeout. ([!6139](https://gitcode.com/cann/comm/pull/6139/discuss))
- Added a description of the impact of inconsistent MTU configuration on the 1825 switch on inference and training functions for Ascend 950PR&950DT products. ([!1425](https://gitcode.com/cann/hixl/pull/1425))
<!-- end id3 -->
<!-- npu="A3,910b" id4 -->
- Fixed the issue where the logic error in inf value computation in the CdistGrad operator boundary on the NPUs of Atlas A2 products and Atlas A3 products caused precision failure. ([!6518](https://gitcode.com/cann/ops-math/pull/6518))
<!-- end id4 -->
<!-- npu="950" id5 -->
- Fixed the AICORE ERROR issue caused by empty copy in some use cases when executing the chunk_gated_delta_rule single operator based on the OOM package on Ascend 950PR&950DT products. ([!13612](https://gitcode.com/cann/ops-transformer/pull/13612))
- Fixed the issue where the allgatherv operator on Ascend 950PR&950DT products incorrectly determined `recv_displacements` when its size was `0` in graph mode, causing the operator to stop execution. ([!3624](https://gitcode.com/cann/hccl/pull/3624/discuss))
<!-- end id5 -->
<!-- npu="A3,910b" id6 -->
- Fixed the precision issue of the conv3d_backprop_input_v2 operator on the NPUs of Atlas A2 products and Atlas A3 products when computing fp32 data through the Vector solution in large-shape use cases, where the L2 error against the dual golden references exceeded the threshold. ([!12180](https://gitcode.com/cann/ops-nn/pull/12180))
<!-- end id6 -->
<!-- npu="950" id7 -->
- Fixed the issue where some operators reported errors when using framework automatic deduction due to the removal of ShapeRange deduction on Ascend 950PR&950DT products. ([!1041](https://gitcode.com/cann/opbase/pull/1041), [!5482](https://gitcode.com/cann/ge/pull/5482))
<!-- end id7 -->
<!-- npu="910b" id8 -->
- Fixed the issue where the ReduceScatter operator on Atlas A2 products could probably hang due to missing pre-synchronization when deterministic computation and the pipeline algorithm were enabled. ([!6056](https://gitcode.com/cann/hcomm/pull/6056))
<!-- end id8 -->
<!-- npu="950" id9 -->
- Fixed the issue where the SparseFlashMla/QuantSparseFlashMla/MixedQuantSparseFlashMla/KvQuantSparseFlashAttention operators on Ascend 950PR&950DT products used illegal event ID 8 during physical address preprocessing. ([!13775](https://gitcode.com/cann/ops-transformer/pull/13775), [!14183](https://gitcode.com/cann/ops-transformer/pull/14183))
- Fixed the precision issue caused by the difference of bitwise_or inside and outside the fused kernel on Ascend 950PR&950DT products. ([!2536](https://gitcode.com/cann/graph-autofusion/pull/2536))
<!-- end id9 -->
<!-- end id11 -->
<!-- npu="950,A3,910b,910,310p,310b" id10 -->
## Open Source Software Notices

For details, see [Open Source Software Notices](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/maintenref/refdoc/refer003.html).

## Fixed Vulnerabilities

For details about the fixed vulnerabilities for open-source and third-party software in this version, see [Fixed Vulnerabilities](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/maintenref/refdoc/refer002.html).

## Virus Scan Reports

For details, see [Virus Scan Reports](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/maintenref/refdoc/refer004.html).
<!-- end id10 -->