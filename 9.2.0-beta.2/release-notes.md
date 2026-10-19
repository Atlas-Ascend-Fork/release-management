# CANN 9.2.0-beta.2版本说明

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
    <td>9.2.0-beta.2</td>
    <td><a href="https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C22%2CAArch64%2Conline_Yum">26.1.1</a></td>
  </tr>
</table>

## CANN软件包内部配套关系

### CANN组合配套关系

CANN 9.2.0-beta.2包含Toolkit包、算子包（ops）、加速库（NNAL）3个组合包，CANN组合包与子包的配套关系如下。

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
      <td rowspan="22">Toolkit</td>
      <td>ascendnpu-ir</td>
      <td>1.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-acl-extend</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">算子包（ops）</td>
      <td>cann-dvpp</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.2.0-beta.2</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">加速库（NNAL）</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.2.0-beta.2">9.2.0-beta.2</a></td>
      <td>arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops与Toolkit配套关系

| ops版本                                                      | 配套toolkit版本                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [ascend-cann-ops 9.2.0-beta.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0-beta.2) | [ascend-cann-toolkit 9.2.0-beta.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0-beta.2) |

### CANN ops组合包内可独立升级子包配套关系

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| [cann-ops-math 9.2.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.2/) | [v9.2.0-beta.2](https://gitcode.com/cann/ops-math/tags/v9.2.0-beta.2) | CANN 9.2.0-beta.2 |
| [cann-ops-nn 9.2.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.2/) | [v9.2.0-beta.2](https://gitcode.com/cann/ops-nn/tags/v9.2.0-beta.2) | CANN 9.2.0-beta.2 |
| [cann-ops-cv 9.2.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.2/) | [v9.2.0-beta.2](https://gitcode.com/cann/ops-cv/tags/v9.2.0-beta.2) | CANN 9.2.0-beta.2 |
| [cann-ops-transformer 9.2.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.2/) | [v9.2.0-beta.2](https://gitcode.com/cann/ops-transformer/tags/v9.2.0-beta.2) | CANN 9.2.0-beta.2 |
| [cann-hccl 9.2.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.2/) | [v9.2.0-beta.2](https://gitcode.com/cann/hccl/tags/v9.2.0-beta.2) | CANN 9.2.0-beta.2 |
| [cann-hixl 9.2.0-beta.2](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0-beta.2/) | [v9.2.0-beta.2](https://gitcode.com/cann/hixl/tags/v9.2.0-beta.2) | CANN 9.2.0-beta.2 |

子包独立升级的具体操作请参考[子包独立升级](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/softwareinst/instg/instg_0030.html)。

## 关键特性

- **新增支持KDA、situ等融合算子，支持Kimi K3模型性能优化。点击[查看详情](https://gitcode.com/cann/ops-transformer/blob/9.2.0-beta.2/attention/chunk_kda_fwd/README.md)。**

## 新增特性

### ops-nn库

- Atlas A2 训练系列产品/Atlas A2 推理系列产品 和 Atlas A3 训练系列产品/Atlas A3 推理系列产品适配与场景支持：
  - 新增适配以下算子
    - SituGlu （[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - SituGluGrad（[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - DequantSituQuant （[!8798](https://gitcode.com/cann/ops-nn/pull/8798)）。
- Ascend 950PR/Ascend 950DT系列产品适配与场景支持：
  - 新增适配以下算子
    - SituGlu （[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - SituGluGrad（[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - SituMxQuant （[!8798](https://gitcode.com/cann/ops-nn/pull/8798)）。

### ops-transformer库

<!-- npu="A3,910b" id2 -->
- <term>Atlas A2系列产品</term>和<term>Atlas A3系列产品</term>适配与场景支持：
  - 新增 MsaIndexScore 算子（[!9503](https://gitcode.com/cann/ops-transformer/pull/9503)）。
  - 新增 ChunkKdaFwd 算子（[!9979](https://gitcode.com/cann/ops-transformer/pull/9979)）。
  - MlaProlog算子增设RoPE计算操作开关并支持cache输入非连续（[!10296](https://gitcode.com/cann/ops-transformer/pull/10296)）（[!9472](https://gitcode.com/cann/ops-transformer/pull/9472)）。
  - FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化（[!9773](https://gitcode.com/cann/ops-transformer/pull/9773)）。
  - MegaMoe算子新增支持situ，swigluoai，swiglustep等激活类型（[!8868](https://gitcode.com/cann/ops-transformer/pull/8868)）。
  - 新增MinimaxSparseAttention算子（[!10628](https://gitcode.com/cann/ops-transformer/pull/10628)）。
  - FusedInferAttentionScore算子的MLA模板支持非连续（[!10114](https://gitcode.com/cann/ops-transformer/pull/10114)）。
  - FusedInferAttentionScore算子支持cache首轴非连续（[!6399](https://gitcode.com/cann/ops-transformer/pull/6399)）。
  - FusedInferAttentionScore算子splitfuse支持BNBD格式，性能更友好，对标vllm生态（[!10353](https://gitcode.com/cann/ops-transformer/pull/10353)）。
<!-- end id2 -->
<!-- npu="950" id1 -->
- <term>Ascend 950PR&Ascend 950DT系列产品</term>适配与场景支持：
  - FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化（[!9773](https://gitcode.com/cann/ops-transformer/pull/9773)）。
  - 新增MinimaxSparseAttention算子decode q gather kv（[!10628](https://gitcode.com/cann/ops-transformer/pull/10628)）。
  - MinimaxSparseAttention算子decode q gather kv支持FP8量化（[!11183](https://gitcode.com/cann/ops-transformer/pull/11183)）。
  - FusedInferAttentionScore算子的MLA模板支持headNum<=128任意值泛化（[!11069](https://gitcode.com/cann/ops-transformer/pull/11069)）。
  - BlockSparseAttention算子稀疏支持叠加量化mxfp4（[!8474](https://gitcode.com/cann/ops-transformer/pull/8474)）。
  - BlockSparseAttention算子稀疏支持block粒度小于128、16对齐（[!9148](https://gitcode.com/cann/ops-transformer/pull/9148)）。
  - BlockSparseAttention算子fp8量化性能增强（[!11145](https://gitcode.com/cann/ops-transformer/pull/11145)）。
<!-- end id1 -->

## 删除和废弃特性

### 说明

- 删除特性为当前版本已删除的特性。
- 废弃特性为当前版本标记为废弃特性，未来版本即将下线的特性。
- 本节中的${install_path}请替换为CANN软件安装路径。

### 运行时

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
| rtSetTaskAbortCallBack接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetDeviceTaskAbortCallback接口替换，回调类型使用aclrtDeviceTaskAbortCallback |
| rtSetTaskFailCallback接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetExceptionInfoCallback接口替换 |
| rtStreamGetMode接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtGetStreamAttribute接口替换 |
| rtStreamSetMode接口从${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h中废弃 | 使用${install_path}/cann/include/acl/aclrt.h中的aclrtSetStreamFailureMode和aclrtSetStreamOverflowSwitch接口替换 |
| aclsysGetCANNVersion接口从${install_path}/ascend-toolkit/latest/include/acl/acl.h中废弃 | 使用${install_path}/cann/include/acl/acl.h中的aclsysGetVersionStr和aclsysGetVersionNum接口替换 |
| libascendcl.so从${install_path}/ascend-toolkit/latest/lib64中废弃 | 使用${install_path}/cann/lib64中的libacl_rt.so、libacl_mdl.so、libacl_op_executor.so库文件替换 |

### 图引擎

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，计划在2026.12.30之后的版本删除。**

| 废弃的目录                                                   | 替换的目录                                                 |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                         |
| ${install_path}/ascend-toolkit/latest/compiler/python/func2graph | ${install_path}/cann/x86_64-linux/python目录下的func2graph |

自Ascend 950 系列产品开始，aclblas和aclop接口不推荐使用，后续版本将逐步废弃，建议迁移至对应的aclnn算子接口。

### 算子库

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


**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，计划在2026.12.30之后的版本删除。**

其中算子被拆分成了组件包，不同的算子独立组件包均包含多个对应的库和头文件，下表中${ops_project}表示实际的cv、math、nn、transformer和legacy。

| 废弃的目录、文件和接口                                       | 替换的目录、文件和接口                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/*.h | ${install_path}/cann/opp/built-in/op_graph/inc/\${ops_project}_ops_proto.h |
| ${install_path}/ascend-toolkit/latest/lib64/libopapi.so      | ${install_path}/cann/lib64/libopapi_\${ops_project}.so |
| aclnnGroupedMatMulAllReduce接口                              | aclnnMatmulAllReduce接口                                                 |
| aclnnWeightQuantBatchMatmul接口                              | aclnnWeightQuantBatchMatmulV3接口                            |
| aclnnQuantMatmul、aclnnQuantMatmulV2、aclnnQuantMatmulV3和aclnnQuantMatmulV4接口 | aclnnQuantMatmulV5接口                                       |
| aclnnGroupedMatmul、aclnnGroupedMatmulV2、aclnnGroupedMatmulV3、aclnnGroupedMatmulV4接口 | aclnnGroupedMatmulV5接口                                     |
| aclnnIncreFlashAttentionV2和aclnnIncreFlashAttentionV3接口   | aclnnIncreFlashAttentionV4接口                               |
| aclnnPromptFlashAttentionV2接口                              | aclnnPromptFlashAttentionV3接口                              |
| aclnnFusedInferAttentionScoreV2和aclnnFusedInferAttentionScoreV3接口 | aclnnFusedInferAttentionScoreV4接口                          |


### 加速库

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，将在2026.12.30之后的版本删除**

如下算子IR废弃使用的DVPP加速功能：Crop、CropAndResize、DecodeAndCropJpeg、DecodeJpeg、PadV3D、Resize、ResizeV2、ResizeBicubic、ResizeBilinearV2、ResizeNearestNeighborV2、ReverseV2、WarpPerspective 、WarpAffineV2、AdjustContrast、AdjustHue、AdjustSaturation。

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
| E5、E6、E7、E8 开头的错误码将在 ${install_path}/ascend-toolkit/latest/conf/error_manager/error_code.json 中废弃，如若代码中仍使用这些错误码，会上报失败 |
| 相应功能错误码使用opbase仓内错误码接口宏替换 ${install_path}/ascend-toolkit/latest/include/op_common/log/log.h |

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/maintenref/refdoc/refer002.html)。