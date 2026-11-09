# CANN 9.2.2版本说明书（开发中）
<!-- npu="950,A3,910b,910,310p,310b" id1 -->
## 版本下载地址

<https://www.hiascend.com/cann/download>

## 版本配套说明

CANN软件版本配套表
<table style="text-align:center;">
  <tr>
    <th>CANN</th>
    <th>驱动版本（Ascend HDK）</th>
  </tr>
  <tr>
    <td>9.2.2</td>
    <td><a href="https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C22%2CAArch64%2Conline_Yum">26.2.RC1</a></td>
  </tr>
</table>

## 版本兼容性说明

CANN与Ascend HDK版本兼容
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
      <th colspan="7">驱动版本（Ascend HDK）</th>
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

## CANN软件包内部配套关系

### CANN组合配套关系

CANN 9.2.2包含Toolkit包、算子包（ops）、加速库（NNAL）3个组合包。CANN组合包与子包的配套关系如下，其中6个子包支持独立升级，用户可根据需求灵活安装。

<table>
  <thead>
    <tr>
      <th>CANN组合包</th>
      <th>子包名称</th>
      <th>子包版本号</th>
      <th>架构</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="24">Toolkit</td>
      <td>ascendnpu-ir</td>
      <td>2.0.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-acl-extend</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-as</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pypto</td>
      <td><a href="https://gitcode.com/cann/pypto/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">算子包（ops）</td>
      <td>cann-dvpp</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.2.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">加速库（NNAL）</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.2.2">9.2.2</a></td>
      <td>arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops与Toolkit配套关系

CANN ops包已与Toolkit解耦，支持独立升级，用户可根据使用需求灵活安装。

|ops版本  |配套toolkit版本  |
|--|--|
| [ascend-cann-ops 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.2.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |

### CANN ops组合包内可独立升级子包配套关系

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.2.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.2/) | [v9.2.2](https://gitcode.com/cann/ops-math/tags/v9.2.2)      | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-nn 9.2.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.2/) | [v9.2.2](https://gitcode.com/cann/ops-nn/tags/v9.2.2)        | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-cv 9.2.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.2/) | [v9.2.2](https://gitcode.com/cann/ops-cv/tags/v9.2.2)        | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-transformer 9.2.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.2/) | [v9.2.2](https://gitcode.com/cann/ops-transformer/tags/v9.2.2) | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hccl 9.2.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.2/) | [v9.2.2](https://gitcode.com/cann/hccl/tags/v9.2.2)          | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hixl 9.2.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.2/) | [v9.2.2](https://gitcode.com/cann/hixl/tags/v9.2.2)          | CANN 9.2.x<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |

子包独立升级的具体操作请参考[子包独立升级](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/softwareinst/instg/instg_0030.html)。要求ops子包版本>=ops组合包版本。

## 删除和废弃特性

### 说明

- 删除特性为当前版本已删除的特性。
- 废弃特性为当前版本标记为废弃的特性，未来版本即将下线的特性。
- 本节中的${install_path}请替换为CANN软件安装路径。

### 算子编程

#### C API

- 废弃所有以`_sync`结尾的同步接口（[!5789](https://gitcode.com/cann/asc-devkit/pull/5789)）。
- 废弃v1～v4接口，并提供对应的替代接口（[!3710](https://gitcode.com/cann/asc-devkit/pull/3710)）。
- 废弃`asc_get_block_num`和`asc_get_block_idx`接口，指引用户使用编译器关键字（[!5216](https://gitcode.com/cann/asc-devkit/pull/5216)）。

### 运行时

**以下目录、文件和接口等在CANN 9.2.0中被标记为废弃，计划在2027.9.30之后的版本删除。**

| 废弃的目录、文件和接口   | 替换的目录、文件和接口 |
| ------------------------------- | ------------------------------------------------------------------------- |
| aclrtGetVersion                 | aclsysGetVersionNum aclsysGetVersionStr                                   |
| aclrtMemcpyAsyncWithCondition   | aclrtMemcpyAsync                                                          |
| aclrtSetExceptionInfoCallback   | aclrtExceptionInfoCallbackRegister  aclrtExceptionInfoCallbackUnregister  |

**以下目录、文件和接口等在CANN 9.1.0中被标记为废弃，计划在2027.6.30之后的版本删除。**

| 废弃的目录、文件和接口   | 替换的目录、文件和接口 |
| ------------------------ | ---------------------- |
| include/driver目录头文件 | pkg_inc/driver目录     |

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，计划在2026.12.30之后的版本删除。**

| 废弃的目录、文件和接口                                       | 替换的目录、文件和接口                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ${install_path}/ascend-toolkit/latest/runtime/include/acl    | ${install_path}/cann/include/acl                             |
| ${install_path}/ascend-toolkit/latest/runtime/include/aclnn  | ${install_path}/cann/include/aclnn                           |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                           |
| ${install_path}/cann/pkg_inc/runtime/runtime目录下的所有头文件将下线 | 后续不提供相关功能                                           |
| rtGetC2cCtrlAddr接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_ffts.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtGetHardwareSyncAddr接口替换 |
| rtFftsTaskLaunch和rtFftsTaskLaunchWithFlag接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_ffts.h中废弃 | 后续不提供相关功能                                           |
| rtBindHostPid、rtUnbindHostPid、rtProfSetProSwitch、rtQueryProcessHostPid、rtGetDeviceIdByGeModelIdx、rtGetExceptionRegInfo、rtGetMaxModelNum、rtLabelGoto、rtLabelGotoEx、rtProfilerConfig、rtProfilerInit、rtProfilerTrace、rtProfilingCommandHandle、rtProfRegisterCtrlCallback、rtSetDeviceIdByGeModelIdx、rtSetExceptCallback、rtSetMsprofReporterCallback、rtSetProfDirEx、rtUnsetDeviceIdByGeModelIdx接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 后续不提供相关功能                                           |
| rtGetBinaryDeviceBaseAddr接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtBinaryGetDevAddress接口替换 |
| rtGetTaskIdAndStreamID接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtGetThreadLastTaskId和aclrtStreamGetId接口替换 |
| rtLabelCreate、rtLabelCreateEx、rtLabelCreateExV2、rtLabelCreateV2接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtCreateLabel接口替换 |
| rtLabelListCpy接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtCreateLabelList和aclrtDestroyLabelList接口替换 |
| rtLabelSet接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetLabel接口替换 |
| rtLabelSwitchByIndex接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSwitchLabelByIndex接口替换 |
| rtProfilerTraceEx接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtProfTrace接口替换 |
| rtRegDeviceStateCallbackEx接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtRegDeviceStateCallback接口替换 |
| rtRegTaskFailCallbackByModule接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetExceptionInfoCallback接口替换 |
| rtSetIpcMemorySuperPodPid接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中aclrtIpcMemImportPidInterServer接口替换 |
| rtSetIpcNotifySuperPodPid接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtNotifySetImportPidInterServer接口替换 |
| rtSetTaskAbortCallBack接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetTaskAbortCallBack接口替换 |
| rtSetTaskFailCallback接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetExceptionInfoCallback接口替换 |
| rtStreamGetMode接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtGetStreamAttribute接口替换 |
| rtStreamSetMode接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetStreamFailureMode和aclrtSetStreamOverflowSwitch接口替换 |
| aclsysGetCANNVersion接口从${install_path}/ascend-toolkit/latest/include/acl/acl.h中废弃 | 使用${install_path}/cann/include/acl/acl.h中的aclsysGetVersionStr和aclsysGetVersionNum接口替换 |
| libascendcl.so从${install_path}/ascend-toolkit/latest/lib64中废弃 | 使用${install_path}/cann/lib64中的libacl_rt.so、libacl_mdl.so、libacl_op_executor.so库文件替换 |
<!-- npu="950" id17 -->
### 图引擎

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，计划在2026.12.30之后的版本删除。**

| 废弃的目录                                                   | 替换的目录                                                 |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                         |
| ${install_path}/ascend-toolkit/latest/compiler/python/func2graph | ${install_path}/cann/x86_64-linux/python目录下的func2graph |

自Ascend 950PR&950DT系列产品开始，aclblas和aclop接口不推荐使用，后续版本将逐步废弃，建议迁移至对应的aclnn算子接口。
<!-- end id17 -->
### 算子库

- **不兼容变更**：
  - kth_value、median和nan_median算子的实现与注册配置由ops-math迁移至ops-nn，使用相关算子需配套升级ops-nn组件（[!5809](https://gitcode.com/cann/ops-math/pull/5809)、[!10728](https://gitcode.com/cann/ops-nn/pull/10728)），这些算子从`ops_proto_math.h`和`es_math`目录迁移到`ops_proto_nn.h`和`es_nn`目录。
  - RoiPooling算子由ops-cv迁移至ops-nn，使用相关算子需配套升级ops-nn组件，避免升级后原型定义冲突（[!1442](https://gitcode.com/cann/ops-cv/pull/1442)、[!9609](https://gitcode.com/cann/ops-nn/pull/9609)），这些算子从`ops_proto_cv.h`和`es_cv`目录迁移到`ops_proto_nn.h`和`es_nn`目录。

**以下目录、文件和接口等在CANN 9.0.0中被标记为废弃，将在2027.3.30之后的版本删除**

| 废弃的目录、文件和接口                                       | 替换的目录、文件和接口                           |
| ------------------------------------------------------------ | ------------------------------------------------ |
| aclnnGroupedMatMulAllReduce接口                              | aclnnMatmulAllReduce                             |
| aclnnGroupedMatmul、aclnnGroupedMatmulV2、aclnnGroupedMatmulV3、aclnnGroupedMatmulV4接口 | aclnnGroupedMatmulV5                             |
| aclnnFusedInferAttentionScore、aclnnFusedInferAttentionScoreV2、aclnnFusedInferAttentionScoreV3接口 | aclnnFusedInferAttentionScoreV4                  |
| aclnnIncreFlashAttention、aclnnIncreFlashAttentionV2、aclnnIncreFlashAttentionV3接口 | aclnnIncreFlashAttentionV4                       |
| aclnnPromptFlashAttention、aclnnPromptFlashAttentionV2接口   | aclnnPromptFlashAttentionV3                      |
| aclnnMlaProlog、aclnnMlaPrologV2WeightNz接口                 | aclnnMlaPrologV3WeightNz                         |
| aclnnMatmulAllReduceAddRmsNorm接口                           | aclnnMatmulAllReduce和aclnnAddRmsNorm            |
| aclnnQuantMatmulAllReduceAddRmsNorm接口                      | aclnnQuantMatmulAllReduceV2和aclnnAddRmsNorm     |
| aclnnWeightQuantMatmulAllReduceAddRmsNorm接口废弃            | aclnnWeightQuantMatmulAllReduce和aclnnAddRmsNorm |
| aclnnInplaceQuantMatmulAllReduceAddRmsNorm接口               | aclnnQuantMatmulAllReduceV2和aclnnAddRmsNorm     |
| aclnnInplaceMatmulAllReduceAddRmsNorm接口                    | aclnnMatmulAllReduce和aclnnAddRmsNorm            |
| aclnnInplaceWeightQuantMatmulAllReduceAddRmsNorm接口         | aclnnWeightQuantMatmulAllReduce和aclnnAddRmsNorm |

### 加速库

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，将在2026.12.30之后的版本删除**

如下算子IR废弃使用的DVPP加速功能：Crop、CropAndResize、DecodeAndCropJpeg、DecodeJpeg、PadV3D、Resize、ResizeV2、ResizeBicubic、ResizeBilinearV2、ResizeNearestNeighborV2、ReverseV2、WarpPerspective、WarpAffineV2、AdjustContrast、AdjustHue、AdjustSaturation。

| 废弃的目录、文件和接口                                       | 替换的目录、文件和接口      |
| ------------------------------------------------------------ | --------------------------- |
| AdjustBrightness算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppAdjustBrightness接口 |
| AdjustBrightnessV2算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppAdjustBrightness接口 |
| AdjustContrastWithMean算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppAdjustContrast接口   |
| AdjustSaturationV2算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppAdjustSaturation接口 |
| GaussianBlur算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppGaussianBlur接口     |
| ImgCrop算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppCrop接口             |
| RgbToGrayscale算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppRgbToGrayscale接口   |
| Rotate算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image.h中废弃 | acldvppRotate接口           |
| CropAndResizeV2算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h中废弃 | acldvppCropAndResize接口    |
| ImgToTensor算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h中废弃 | acldvppImgToTensor接口      |
| NormalizeV2算子IR将从${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/image_ops.h中废弃 | acldvppNormalize接口        |

### 调试与分析工具

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，将在2026.12.30之后的版本删除**

| 废弃的目录、文件和接口                                       | 替换的目录、文件和接口                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 将Profiling头文件aprof_pub.h、prof_api.h、prof_common.h从${install_path}/ascend-toolkit/latest/include/experiment/msprof/toolchain路径下废弃 | Profiling头文件aprof_pub.h、prof_api.h、prof_common.h存放路径变更为${install_path}/cann/pkg_inc/profiling |

### 维测能力

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，将在2026.12.30之后的版本删除**

| 废弃的目录、文件和接口                                       | 替换的目录、文件和接口                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Error Manager头文件${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h | Error Manager头文件${install_path}/cann/include/base/err_msg.h |
| ${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h中的REPORT_INNER_ERROR和REPORT_CALL_ERROR接口 | REPORT_INNER_ERR_MSG接口                                     |
| REPORT_INPUT_ERROR、REPORT_ENV_ERROR接口                     | REPORT_PREDEFINED_ERR_MSG接口                                |
| 日志头文件${install_path}/ascend-toolkit/latest/include/toolchain/slog.h | 日志头文件${install_path}/cann/pkg_inc/base/dlog_pub.h       |
| 日志头文件${install_path}/ascend-toolkit/latest/include/base/alog_pub.h | 日志头文件${install_path}/cann/pkg_inc/base/dlog_pub.h       |
| ${install_path}/ascend-toolkit/latest/include/base/alog_pub.h中的AlogCheckDebugLevel接口 | ${install_path}/cann/pkg_inc/base/dlog_pub.h中的CheckLogLevel接口 |
| ${install_path}/ascend-toolkit/latest/include/base/alog_pub.h中的AlogRecord接口 | ${install_path}/cann/pkg_inc/base/dlog_pub.h中的DlogRecord接口或封装的dlog_error、dlog_warn等宏 |

**以下目录、文件和接口等在CANN 9.2.0中被标记为废弃，将在2027.9.30之后的版本删除**

| 废弃的目录、文件和接口                                       | 替换的目录、文件和接口                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ASCEND_SLOG_PRINT_TO_STDOUT环境变量 | ASCEND_LOG_PRINT_TO_STDOUT环境变量 |
<!-- end id1 -->

## 已修复问题

以下问题在9.2.2版本修复：
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品mc2多卡用例torch-extension接口重复编译导致建链超时的问题([!14186](https://gitcode.com/cann/ops-transformer/pull/14186))。	
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品splitd算子输出datatype推导异常导致的算子执行异常问题([!6777](https://gitcode.com/cann/ops-math/pull/6777))。	
- 修复Ascend 950DT系列产品aclrtMemcpyBatchAsync入参numBatches≥2048执行失败问题([!5888](https://gitcode.com/cann/runtime/pull/5888))。	
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品Engram forward 算子图优化阶段数据排布变换导致的算子精度问题([!7040](https://gitcode.com/cann/pypto/pull/7040))。	
- 修复Atlas A2系列产品、Atlas A3系列产品推理服务下同一地址多次注册，MR泄漏的问题([!6373](https://gitcode.com/cann/hcomm/pull/6373))。	
- 修复Atlas A2系列产品、Atlas A3系列产品推理服务执行 sleep 拆除 KV 传输链路时，进程异常退出问题([!6182](https://gitcode.com/cann/hcomm/pull/6182))。	
- 修复Ascend 950DT/PR系列产品CMO任务在PROFILING呈现上与老形态不一致的问题([!6027](https://gitcode.com/cann/runtime/pull/6027))。	
- 修复Ascend 950DT/PR系列产品HIXL单边通信纯URMA流程因为选错EID导致建链不通的问题([!1423](https://gitcode.com/cann/hixl/pull/1423))。	
- 修复Ascend 950DT系列产品aclnnEmbeddingRenorm算子精度问题([!13397](https://gitcode.com/cann/ops-nn/pull/13397))。	
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品，SK任务启动核数异常时，边界场景获取event task有效核数失效的问题([!2587](https://gitcode.com/cann/graph-autofusion/pull/2587))。	
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品block_sparse_attention blockSparseMask超大shape时导致的uint32_t回绕导致的精度问题([!15196](https://gitcode.com/cann/ops-transformer/pull/15196))。	
- 修复Atlas A2系列产品allreduce确定性pipeline算法,  在1k数据量下数据切分对齐错误的问题([!6259](https://gitcode.com/cann/hcomm/pull/6259))。	
- 修复Ascend 950PR&950DT系列产品的Batchsendrecv算子在CCU通信域时部分卡下算子时建链超时的问题([!3803](https://gitcode.com/cann/hccl/pull/3803))。	
- 修复Ascend 950DT/PR系列产品，在host侧网口down时，rootinfo有host侧roce，跑单机内的集合通信业务通信域初始化失败问题([!6416](https://gitcode.com/cann/hcomm/pull/6416))。	
- 修复Atlas 推理系列产品上运行 DecoderModel Prefill 时，AllGatherV 的 HCCL CCL buffer 申请失败，导致该算子及后续图节点执行失败([!2366](https://gitcode.com/cann/ascend-transformer-boost/pull/2366))。	
- 修复Atlas A2系列产品NB算法在数据量切换时，前后Slice变化时仍复用同一FFTS子图导致子图复用失败的问题([!6442](https://gitcode.com/cann/hcomm/pull/6442))。	
- 修复Atlas A2 训练系列产品和Atlas A2 推理系列产品engram正向算子精度异常的问题([!2046](https://gitcode.com/cann/pto-isa/pull/2046))。	
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品，在host hcomm子包版本9.1.0，device hcomm子包版本9.2.0场景，RPING socket建链失败问题([!6475](https://gitcode.com/cann/hcomm/pull/6475))。	
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品算子写法采用 if 语句中存在值依赖导致框架 segment fault 的问题([!7392](https://gitcode.com/cann/pypto/pull/7392))。	
- 修复Atlas A2系列产品和Atlas A3系列产品，FIA_SINK自定义算子性能劣化的问题([!7231](https://gitcode.com/cann/asc-devkit/pull/7231))。	
- 修复Atlas A2系列产品，Group特性中缺少对Direct类型链路的判断导致AICPU侧尝试解析未申请的Notify资源引发报错的问题([!6235](https://gitcode.com/cann/hcomm/pull/6235))。	
- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品 AICPU算子缓存未持有protobuf内存，算子执行时UAF导致coredump的问题([!82695](https://gitcode.com/cann/canndev/pull/82695)、[!1126](https://gitcode.com/cann/opbase/pull/1126))。	
- 修复Ascend 950DT/PR系列产品LI/LI v2/QLI v2算子分页偏移计算乘法结果溢出的问题([!15304](https://gitcode.com/cann/ops-transformer/pull/15304))。	
- 修复Ascend 950DT/PR系列产品FIA/QFA算子FP8量化场景偶现精度失败问题([!15028](https://gitcode.com/cann/ops-transformer/pull/15028))。	
- 修复Ascend 950DT/PR系列产品MoeFusedTopK算子aclnn场景部分用例失败的问题([!15019](https://gitcode.com/cann/ops-transformer/pull/15019))。	
## 开源软件声明

开源软件声明请查看[开源软件声明](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/maintenref/refdoc/refer003.html)。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/maintenref/refdoc/refer002.html)。

## 病毒扫描报告

病毒扫描报告请查看[病毒扫描报告](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/maintenref/refdoc/refer004.html)。
<!-- end id10 -->