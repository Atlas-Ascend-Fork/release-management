# CANN 9.2.0版本说明书（开发中）

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
    <td>9.2.0</td>
    <td><a href="https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C22%2CAArch64%2Conline_Yum">26.2.RC1</a></td>
  </tr>
</table>

## 版本兼容性说明

CANN与Ascend HDK版本兼容
<table style="table-layout: fixed; width: 750px; text-align:center;">
  <colgroup>
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
    <col style="width: 150px">
  </colgroup>
  <thead>
    <tr>
      <th rowspan="3">CANN</th>
      <th colspan="6">驱动版本（Ascend HDK）</th>
    </tr>
    <tr>
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
    </tr>
    <tr>
      <td>9.0.X</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
    <tr>
      <td>9.1.X</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
     <tr>
      <td>9.2.0</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
      <td>Y</td>
    </tr>
  </tbody>
</table>

## CANN软件包内部配套关系

### CANN组合配套关系

CANN 9.2.0包含Toolkit包、算子包（ops）、加速库（NNAL）3个组合包，CANN组合包与子包的配套关系如下。其中6个子包支持独立升级，用户可根据需求灵活安装。

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
      <td>1.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-acl-extend</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-as</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>   
    <tr>
      <td>cann-pypto</td>
      <td><a href="https://gitcode.com/cann/pypto/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>    
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">算子包（ops）</td>
      <td>cann-dvpp</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.2.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">加速库（NNAL）</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.2.0">9.2.0</a></td>
      <td>arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops与Toolkit配套关系
CANN ops包已与Toolkit解耦，支持独立升级，用户可根据使用需求灵活安装。

|ops版本  |配套toolkit版本  |
|--|--|
| [ascend-cann-ops 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br> [ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |


### CANN ops组合包内可独立升级子包配套关系

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-math/tags/v9.2.0)      | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-nn 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-nn/tags/v9.2.0)        | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-cv 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-cv/tags/v9.2.0)        | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-transformer 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-transformer/tags/v9.2.0) | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hccl 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/hccl/tags/v9.2.0)          | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hixl 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/hixl/tags/v9.2.0)          | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |

子包独立升级的具体操作请参考[子包独立升级](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/softwareinst/instg/instg_0030.html)。

## 关键特性

- **昇腾社区上线CANN版本配套查询助手，用户可快速获取CANN与上下游软件配套关系，点击[查看详情](https://www.hiascend.com/developer/download/compatibility)。**
- **昇腾社区上线固件与驱动（HDK）快速安装页面，自动匹配产品型号与软件包，提高开发者选包效率，点击[查看详情](https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C19%2CAArch64%2Conline_Yum)。**
- **新增支持KDA、situ等融合算子，支持Kimi K3模型性能优化。点击[查看详情](https://gitcode.com/cann/ops-transformer/blob/9.2.0-beta.2/attention/chunk_kda_fwd/README.md)。**

## 新增特性

### 算子库

#### ops-math库

- <term>Ascend 950PR/Ascend 950DT</term>适配与场景支持：
  - 新增适配以下算子
    - MatrixSetDiagV2，支持替换输入张量的单条或多条对角线元素（[!3961](https://gitcode.com/cann/ops-math/pull/3961)）。
    - DropoutV3Grad，提供aclnnDropoutV3Grad接口，支持根据mask和scale计算反向梯度（[!4034](https://gitcode.com/cann/ops-math/pull/4034)）。
  - 算子新增特性支持
    - BitwiseAnd系列算子新增int8、uint8、uint32和uint64数据类型支持（[!5573](https://gitcode.com/cann/ops-math/pull/5573)）。
    - WeightQuantPreprocess新增A16W4数据流支持，支持INT4、FP4和MXFP4权重的紧凑排布转换（[!4495](https://gitcode.com/cann/ops-math/pull/4495)）。

- 算子新增特性支持：
  - ReduceSum、ReduceMean支持Batch一致性计算（[!3442](https://gitcode.com/cann/ops-math/pull/3442)、[!3646](https://gitcode.com/cann/ops-math/pull/3646)）。
  - aclnnAngleV2支持非连续输入和输出（[!4897](https://gitcode.com/cann/ops-math/pull/4897)）。
  - NpuFormatCast新增FLOAT4_E1M2数据类型的ND到FRACTAL_NZ格式转换支持（[!3340](https://gitcode.com/cann/ops-math/pull/3340)）。

- 性能优化：
  - Sort算子排序性能优化，采用ping-pong merge策略（[!5809](https://gitcode.com/cann/ops-math/pull/5809)）。
  - TopkV2算子小轴场景排序性能优化（[!5939](https://gitcode.com/cann/ops-math/pull/5939)）。
  - DropOutV3算子优化Philox随机数生成循环，提升计算性能（[!5682](https://gitcode.com/cann/ops-math/pull/5682)）。
  - Cdist算子性能优化（[!5021](https://gitcode.com/cann/ops-math/pull/5021)）。
  - ConstantPadNd算子优化bool输入处理、大尾轴双缓冲和循环展开，提升填充性能（[!4629](https://gitcode.com/cann/ops-math/pull/4629)）。

#### ops-cv库

- <term>Ascend 950PR/Ascend 950DT</term>适配与场景支持：
  - 新增适配以下算子
    - BatchMultiClassNonMaxSuppression，支持按batch和类别执行非极大值抑制（[!1176](https://gitcode.com/cann/ops-cv/pull/1176)）。
    - CombinedNonMaxSuppression，支持合并各类别的非极大值抑制结果（[!1219](https://gitcode.com/cann/ops-cv/pull/1219)）。
    - NonMaxSuppressionV7（[!1293](https://gitcode.com/cann/ops-cv/pull/1293)）。
    - SortedNMS，支持对已按分数排序的候选框执行非极大值抑制（[!1236](https://gitcode.com/cann/ops-cv/pull/1236)）。
    - RotatedOverlaps，支持计算二维旋转框之间的交叠面积（[!1339](https://gitcode.com/cann/ops-cv/pull/1339)）。
  - 算子新增特性支持
    - CombinedNonMaxSuppression新增FP16数据类型支持，放宽iouThreshold值域及候选框数量限制（[!1627](https://gitcode.com/cann/ops-cv/pull/1627)）。

- 性能优化：
  - CombinedNonMaxSuppression优化归约、数据搬运和workspace使用，提升目标检测后处理性能（[!1712](https://gitcode.com/cann/ops-cv/pull/1712)）。

#### opbase库

- 新增特性：
  - ACLNN框架支持强一致性与Batch一致性配置，并支持确定性计算与一致性开关在算子级动态生效（[!631](https://gitcode.com/cann/opbase/pull/631)、[!643](https://gitcode.com/cann/opbase/pull/643)）。
  - Reduce模板支持Batch一致性计算，提供相应的tiling切分策略和kernel调度能力（[!519](https://gitcode.com/cann/opbase/pull/519)）。
  - ACLNN自动框架支持PCIe直通算子，broadcast模板增加PCIe直通场景识别与调度支持（[!741](https://gitcode.com/cann/opbase/pull/741)、[!742](https://gitcode.com/cann/opbase/pull/742)、[!788](https://gitcode.com/cann/opbase/pull/788)）。
  - 图模式ACLNN Fallback支持Prepare与Launch两阶段执行（[!740](https://gitcode.com/cann/opbase/pull/740)）。
  - 新增外部算子任务接入框架，支持实现方自行完成实现选择、tiling与kernel下发（[!962](https://gitcode.com/cann/opbase/pull/962)）。
  - 新增aclnnReselectStaticKernelWithPath接口，支持从自定义目录加载静态算子包（[!598](https://gitcode.com/cann/opbase/pull/598)）。
  - 支持内置AICPU JSON算子包加载；自定义AICPU算子加载支持从ASCEND_OPP_PATH/vendors推导路径（[!666](https://gitcode.com/cann/opbase/pull/666)、[!698](https://gitcode.com/cann/opbase/pull/698)）。
  - 支持DEB/RPM格式的软件包构建与发布（[!678](https://gitcode.com/cann/opbase/pull/678)）。
  - 开源算子精度标准增加用例设计与混合容差设计说明（[!508](https://gitcode.com/cann/opbase/pull/508)）。
  - 增强ACLNN框架缓存场景的日志维测能力（[!849](https://gitcode.com/cann/opbase/pull/849)）。

- 性能优化：
  - ReduceProd模板在AR模式归约为单个元素的场景采用树形归约，优化累乘性能（[!690](https://gitcode.com/cann/opbase/pull/690)）。

#### ops-nn库

- Atlas A2 训练系列产品/Atlas A2 推理系列产品 和 Atlas A3 训练系列产品/Atlas A3 推理系列产品适配与场景支持：
  - 新增适配以下算子
    - FusedSgd（[!6220](https://gitcode.com/cann/ops-nn/pull/6220)）。
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

#### ops-transformer库

- Atlas A2 训练系列产品/Atlas A2 推理系列产品 和 Atlas A3 训练系列产品/Atlas A3 推理系列产品适配与场景支持：
  - 新增 MsaIndexScore 算子（[!9503](https://gitcode.com/cann/ops-transformer/pull/9503)）。
  - 新增 ChunkKdaFwd 算子（[!9979](https://gitcode.com/cann/ops-transformer/pull/9979)）。
  - MlaProlog算子增设RoPE计算操作开关并支持cache输入非连续（[!10296](https://gitcode.com/cann/ops-transformer/pull/10296)）（[!9472](https://gitcode.com/cann/ops-transformer/pull/9472)）。
  - FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化（[!9773](https://gitcode.com/cann/ops-transformer/pull/9773)）。
  - MegaMoe算子新增支持situ，swigluoai，swiglustep等激活类型（[!8868](https://gitcode.com/cann/ops-transformer/pull/8868)）。
  - 新增GenericBlockSparseAttentionMetadata算子（[!10657](https://gitcode.com/cann/ops-transformer/pull/10657)）。
  - SparseFlashMla算子topk泛化（[!11899](https://gitcode.com/cann/ops-transformer/pull/11899)）。
  - SparseFlashMla算子SWA稀疏ori_kv支持（[!9384](https://gitcode.com/cann/ops-transformer/pull/9384)）。
  - RopeWithSinCosCache算子支持[11,11,10]（[!7120](https://gitcode.com/cann/ops-transformer/pull/7120)）。
  - 新增BlockAttentionResiduals正向算子（[!11161](https://gitcode.com/cann/ops-transformer/pull/11161)）。
  - 新增BlockAttentionResiduals反向算子（[!11006](https://gitcode.com/cann/ops-transformer/pull/11006)）。
  - 新增InplacePartialRotaryMul算子，支持原地部分旋转乘法操作（[!6085](https://gitcode.com/cann/ops-transformer/pull/6085)）。
- Ascend 950PR/Ascend 950DT系列产品适配与场景支持：
  - FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化（[!9773](https://gitcode.com/cann/ops-transformer/pull/9773)）。
  - 新增GenericBlockSparseAttentionMetadata算子（[!10657](https://gitcode.com/cann/ops-transformer/pull/10657)）。
  - 新增BlockAttentionResiduals正向算子（[!11161](https://gitcode.com/cann/ops-transformer/pull/11161)）。
  - 新增BlockAttentionResiduals反向算子（[!11006](https://gitcode.com/cann/ops-transformer/pull/11006)）。
  - KvQuantSparseFlashAttentionMla算子性能优化（[!10428](https://gitcode.com/cann/ops-transformer/pull/10428)）。
  - 新增InplacePartialRotaryMul算子，支持原地部分旋转乘法操作（[!6085](https://gitcode.com/cann/ops-transformer/pull/6085)）。

### 图引擎

- 新增自定义Pass开发和自定义算子开发的Python API，支持在Python环境下编写自定义Pass及接入自定义算子。
- 新增Host CPU算子注册接口，支持自定义Host CPU算子接入常量折叠优化及动态Shape执行时调度。([!4481](https://gitcode.com/cann/ge/pull/4481)、[!4538](https://gitcode.com/cann/ge/pull/4538)、[!4918](https://gitcode.com/cann/ge/pull/4918))
- 新增动态Shape自动多流并行优化，可通过ge.autoMultistreamParallelMode开启；ATC新增multi_stream_parallel_mode参数，支持离线推理场景开启自动多流优化。([!3781](https://gitcode.com/cann/ge/pull/3781)、[!4184](https://gitcode.com/cann/ge/pull/4184)、[!4301](https://gitcode.com/cann/ge/pull/4301))
- 优化RunGraphWithStreamAsync接口易用性，静态Shape场景下用户未注册外置Allocator时，也支持自动分配输出内存。( [!3306](https://gitcode.com/cann/ge/pull/3306))
- 支持PCIe算子入图，并提供算子声明PCIe Through能力。([!430](https://gitcode.com/cann/metadef/pull/430)、[!4394](https://gitcode.com/cann/ge/pull/4394))
- 新增Host输入场景下的动态Shape调度性能优化，对连续在Host CPU上执行的算子进行Codegen融合，进一步提升性能。( [!3626](https://gitcode.com/cann/ge/pull/3626)、[!4669](https://gitcode.com/cann/ge/pull/4669))

## 删除和废弃特性

### 说明

- 删除特性为当前版本已删除的特性。
- 废弃特性为当前版本标记为废弃特性，未来版本即将下线的特性。
- 本节中的${install_path}请替换为CANN软件安装路径。

### 通信库

#### 集合通信
- Ascend 950PR支持HCCL Tuner Plugin功能，支持用户灵活控制算法选择策略([!2602](https://gitcode.com/cann/hccl/pull/2602))。
- Ascend 950PR支持在experimental目录扩展自定义算法，提升生态扩展易用性([!2734](https://gitcode.com/cann/hccl/pull/2734)) 。
- Ascend 950PR支持URMA场景下的对称内存能力，支持用户通过 HcclCommSymWinRegister 注册对称窗口，提升算子算法实现易用性([!2369](https://gitcode.com/cann/hcomm/pull/2369) [!1195](https://gitcode.com/cann/hccl/pull/1195))。
- Ascend 950PR支持CCU资源灵活申请，提升自定义CCU算子灵活性([!3367](https://gitcode.com/cann/hcomm/pull/3367))。
- Ascend 950PR提供 Host 网卡实现扩展能力，支持灵活扩展hcomm接口实现([!4257](https://gitcode.com/cann/hcomm/pull/4257)) 。

### 运行时

- 开源Pyacl, acl接口Python版本，便于直接使用Python语言开发应用程序（[!4635](https://gitcode.com/cann/runtime/pull/4635)）。
- 支持 Kernel Launch 和模型执行的阻塞调试模式（[!4247](https://gitcode.com/cann/runtime/pull/4247)）。
- 支持 ACL Graph同一捕获模型跨流执行有序（[!4479](https://gitcode.com/cann/runtime/pull/4479)）。
- 新增 PCI Bus ID 双向查询接口：aclrtDeviceGetPCIBusId、aclrtDeviceGetByPCIBusId（[!4066](https://gitcode.com/cann/runtime/pull/4066)）。

**以下目录、文件和接口等在CANN 9.2.0中被标记为废弃，计划在2027.9.30之后的版本删除。**

| 废弃的目录、文件和接口   | 替换的目录、文件和接口 |
| ------------------------------- | ------------------------------------------------------------------------- |
| aclrtGetVersion                 | aclsysGetVersionNu  aclsysGetVersionStr                                   |
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

### 图引擎

**以下目录、文件和接口等在CANN 8.5.0中被标记为废弃，计划在2026.12.30之后的版本删除。**

| 废弃的目录                                                   | 替换的目录                                                 |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                         |
| ${install_path}/ascend-toolkit/latest/compiler/python/func2graph | ${install_path}/cann/x86_64-linux/python目录下的func2graph |

自Ascend 950 系列产品开始，aclblas和aclop接口不推荐使用，后续版本将逐步废弃，建议迁移至对应的aclnn算子接口。

### 算子库

- **不兼容变更**：
  - 控制类算子Identity、IdentityN、Rank、Shape和ShapeN从ops-nn迁移至ops-math。这些算子从`ops_proto_nn.h`和`es_nn`目录迁移到`ops_proto_math.h`和`es_math`目录，用户需更新相关头文件引用（[!2333](https://gitcode.com/cann/ops-math/pull/2333)、[!3995](https://gitcode.com/cann/ops-nn/pull/3995)）。
  - kth_value、median和nan_median算子的实现与注册配置由ops-math迁移至ops-nn，使用相关算子需配套升级ops-nn组件（[!5809](https://gitcode.com/cann/ops-math/pull/5809)、[!10728](https://gitcode.com/cann/ops-nn/pull/10728)），这些算子从`ops_proto_math.h`和`es_math`目录迁移到`ops_proto_nn.h`和`es_nn`目录。
  - RoiPooling算子由ops-cv迁移至ops-nn，使用相关算子需配套升级ops-nn组件，避免升级后原型定义冲突（[!1442](https://gitcode.com/cann/ops-cv/pull/1442)、[!9609](https://gitcode.com/cann/ops-nn/pull/9609)），这些算子从`ops_proto_cv.h`和`es_cv`目录迁移到`ops_proto_nn.h`和`es_nn`目录。

**以目录、文件和接口等在CANN 9.0.0中被标记为废弃，将在2027.3.30之后的版本删除**

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
| aclnnGroupedMatMulAllReduce接口                              | aclnnMatmulAllReduce                                                 |
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

**ASCEND_SLOG_PRINT_TO_STDOUT环境变量在本版本标记为废弃，将在2027年9月30日之后的版本删除，替换为：ASCEND_LOG_PRINT_TO_STDOUT **

## 已修复问题

以下问题在9.2.0版本修复：
- 修复 Atlas A2和Atlas A3系列产品及Ascend 950系列NPU MM 算子通过 GE aclnn fallback 回调执行场景下的 HF32 属性未正确传递至底层导致性能不达预期的问题。 
- 修复 Atlas A2和Atlas A3系列产品RmsNorm算子在输入shape超过int32最大值有精度误差的问题。
- 修复 Atlas A2和Atlas A3系列产品 matmul 算子融合通路转为 matmulv2 场景下的 _deterministic_level 属性未继承导致后续节点属性丢失的问题。
- 修复 Atlas A2和Atlas A3系列产品 matmul 算子 host 端性能劣化场景下的 FSDP 通信与计算细粒度流水受阻导致模型整体性能下降的问题。
- 修复FAG算子在EOD场景下存在偶现清空pad不完整的问题。
- 修复Atlas A3系列产品 aclgraph aicpu展开HCCL主流和capture主流为同一条stream时，orderStream图规则校验失败的问题。
- 修复Atlas A3系列产品 AllGatherRingConcurrentDirect算法在大集群规模场景下，主从流任务下发死锁的问题。
- 修复Atlas A2和Atlas A3系列产品导入非主线版本环境变量时RingMLAOperation接口demo运行失败问题。
- 修复Atlas A2和Atlas A3系列产品torch_npu.npu_format_cast接口format和shape不匹配的场景下，从拦截fallback到aclop的问题。
- （**不兼容变更**）修复 Atlas A2和Atlas A3系列产品SparseFlashMLA算子torch接口参数默认值错误的问题（ori_mask_mode、cmp_mask_mode、ori_win_left、ori_win_right）。


## 开源软件声明

开源软件声明请查看[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/maintenref/refdoc/refer002.html)。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/maintenref/refdoc/refer002.html)。
