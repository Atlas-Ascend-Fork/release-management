# CANN 9.2.0版本说明书

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
      <td>9.2.0</td>
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

CANN 9.2.0包含Toolkit包、算子包（ops）、加速库（NNAL）3个组合包。CANN组合包与子包的配套关系如下，其中6个子包支持独立升级，用户可根据需求灵活安装。

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
| [ascend-cann-ops 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br> [ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |

### CANN ops组合包内可独立升级子包配套关系

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-math/tags/v9.2.0)      | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-nn 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-nn/tags/v9.2.0)        | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-cv 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-cv/tags/v9.2.0)        | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-transformer 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-transformer/tags/v9.2.0) | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hccl 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/hccl/tags/v9.2.0)          | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hixl 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/hixl/tags/v9.2.0)          | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |

子包独立升级的具体操作请参考[子包独立升级](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/softwareinst/instg/instg_0030.html)。要求ops子包版本>=ops组合包版本。

## 关键特性

- **昇腾社区上线CANN版本配套查询助手，用户可快速获取CANN与上下游软件配套关系，点击[查看详情](https://www.hiascend.com/developer/download/compatibility)。**
<!-- npu="950" id1 -->
- **基于<term>Ascend 950PR&950DT系列产品</term>，Matmul、FA、SFA、BSA等算子支持8bit低精度计算，Matmul、GroupedMatmul、BSA等进一步支持4bit低精度计算，低精能力全面覆盖Deepseek、GLM、Kimi等模型权重、激活、KV Cache和Attention等关键路径，点击[查看详情](https://gitcode.com/cann/docs/blob/9.2.0/docs/zh/ops-lib/0_README.md)。**
<!-- end id1 -->
- **KDA、SMLA、MegaMoe等融合算子进一步提升流水并行度，支持Kimi-K3、GLM5.2等模型性能提升20%，点击[查看详情](https://gitcode.com/cann/ops-transformer/tree/9.2.0)。**

- **扩展稀疏Attention系列算子的正反向计算能力，覆盖注意力计算、稀疏索引选择与梯度计算等关键环节，支撑大模型稀疏训练，点击[查看详情](https://gitcode.com/cann/ops-transformer/tree/9.2.0/attention)。**
<!-- npu="950" id2 -->
- **基于<term>Ascend 950PR&950DT系列产品</term>，支持MoE训练场景的Dispatch、Combine，通过AIV直驱URMA发起后台通信，配合DualPipe调度，实现训练中计算与通信的并行，点击[查看详情](https://gitcode.com/cann/ops-transformer/tree/9.2.0/mc2)。**
<!-- end id2 -->
<!-- npu="950" id3 -->
- **基于<term>Ascend 950PR&950DT系列产品</term>，支持Engram分布式推理，将Engram表卸载（offload）至Host内存，通过URMA与Ubmem的接力能力，实现跨卡访问远端Host内存，点击[查看详情](https://gitcode.com/cann/ops-transformer/tree/9.2.0/mc2)。**
<!-- end id3 -->
- **PyPTO新增PyPTO Pro编程模式，为算子开发者进一步提供硬件的控制力，点击[查看详情](https://gitcode.com/cann/pypto/blob/master/docs/zh/guide/introduction.md)。**
<!-- npu="950" id4 -->
- **基于<term>Ascend 950PR&950DT系列产品</term>，CATLASS新增支持Python风格核函数，提供丰富的样例库，点击[查看详情](https://gitcode.com/cann/catlass/blob/master/README.md)。**
<!-- end id4 -->
- **算子新增支持Batch一致性计算能力，点击[查看详情](https://gitcode.com/cann/ops-nn/blob/9.2.0/docs/zh/context/batch_consistency.md)。**

- **新增支持inductor路线的自动融合能力，自动识别并融合view、Norm、elementwise、Concat等算子，提升模型执行性能，点击[查看详情](https://gitcode.com/cann/graph-autofusion/blob/master/docs/zh/autofuse/introduction/enable_autofuse_inductor.md)。**

## 新增特性

### 公共模块

- CPU性能调优：
  - msboost自适应绑核工具支持按照NPU->CPU 拓扑亲和性绑核([!65](https://gitcode.com/Ascend/msboost/pull/65))。
  - msboost新增KAOT OS配置调优插件，通过对OS配置进行自动化调优，实现性能优化([!88](https://gitcode.com/Ascend/msboost/pull/88))。
<!-- npu="950,A3" id5 -->
- CANN适配不同昇腾硬件产品，新增OS兼容性支持：
  - Atlas 900 A3 SuperPoD超节点适配ctyunos-2-25.05、Debian12.0。
  - Atlas 950 SuperPoD超节点适配CCOS、Velinux、BCLinux、VesselOS、MTOS。
  - Atlas 850超节点、Atlas 850E超节点适配 Kylin V11。
<!-- end id5 -->
- PyACL开源至runtime，详细信息请见[runtime](https://gitcode.com/cann/runtime/tree/master/python)。

### 算子库

#### ops-math库
<!-- npu="950" id6 -->
- Ascend 950PR&950DT系列产品适配与场景支持：

  - 新增算子：

    - MatrixSetDiagV2，支持替换输入张量的单条或多条对角线元素（[!3961](https://gitcode.com/cann/ops-math/pull/3961)）。
    - DropoutV3Grad，提供aclnnDropoutV3Grad接口，支持根据mask和scale计算反向梯度（[!4034](https://gitcode.com/cann/ops-math/pull/4034)）。

  - 算子功能增强：

    - BitwiseAnd系列算子新增int8、uint8、uint32和uint64数据类型支持（[!5573](https://gitcode.com/cann/ops-math/pull/5573)）。
    - WeightQuantPreprocess新增A16W4数据流支持，支持INT4、FP4和MXFP4权重的紧凑排布转换（[!4495](https://gitcode.com/cann/ops-math/pull/4495)）。
    - ReduceSum、ReduceMean支持Batch一致性计算（[!3442](https://gitcode.com/cann/ops-math/pull/3442)、[!3646](https://gitcode.com/cann/ops-math/pull/3646)）。
    - aclnnAngleV2支持非连续输入和输出（[!4897](https://gitcode.com/cann/ops-math/pull/4897)）。
    - NpuFormatCast新增FLOAT4_E1M2数据类型的ND到FRACTAL_NZ格式转换支持（[!3340](https://gitcode.com/cann/ops-math/pull/3340)）。

  - 性能优化：

    - Sort算子排序性能优化，采用ping-pong merge策略（[!5809](https://gitcode.com/cann/ops-math/pull/5809)）。
    - TopkV2算子小轴场景排序性能优化（[!5939](https://gitcode.com/cann/ops-math/pull/5939)）。
    - DropOutV3算子优化Philox随机数生成循环，提升计算性能（[!5682](https://gitcode.com/cann/ops-math/pull/5682)）。
    - Cdist算子性能优化（[!5021](https://gitcode.com/cann/ops-math/pull/5021)）。
    - ConstantPadNd算子优化bool输入处理、大尾轴双缓冲和循环展开，提升填充性能（[!4629](https://gitcode.com/cann/ops-math/pull/4629)）。
<!-- end id6 -->
<!-- npu="A3,910b" id7 -->
- Atlas A2系列产品和Atlas A3系列产品适配与场景支持：

  - 算子功能增强：

    - aclnnAngleV2支持非连续输入和输出（[!4897](https://gitcode.com/cann/ops-math/pull/4897)）。
<!-- end id7 -->

#### ops-cv库
<!-- npu="950" id8 -->
- Ascend 950PR&950DT系列产品适配与场景支持：

  - 新增算子：

    - BatchMultiClassNonMaxSuppression，支持按Batch和类别执行非极大值抑制（[!1176](https://gitcode.com/cann/ops-cv/pull/1176)）。
    - CombinedNonMaxSuppression，支持合并各类别的非极大值抑制结果（[!1219](https://gitcode.com/cann/ops-cv/pull/1219)）。
    - NonMaxSuppressionV7（[!1293](https://gitcode.com/cann/ops-cv/pull/1293)）。
    - SortedNMS，支持对已按分数排序的候选框执行非极大值抑制（[!1236](https://gitcode.com/cann/ops-cv/pull/1236)）。
    - RotatedOverlaps，支持计算二维旋转框之间的交叠面积（[!1339](https://gitcode.com/cann/ops-cv/pull/1339)）。

  - 算子功能增强：

    - CombinedNonMaxSuppression新增FP16数据类型支持，放宽iouThreshold值域及候选框数量限制（[!1627](https://gitcode.com/cann/ops-cv/pull/1627)）。

  - 性能优化：

    - CombinedNonMaxSuppression优化归约、数据搬运和workspace使用，提升目标检测后处理性能（[!1712](https://gitcode.com/cann/ops-cv/pull/1712)）。
<!-- end id8 -->

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
<!-- npu="A3,910b" id9 -->
- Atlas A2系列产品和Atlas A3系列产品适配与场景支持：
  - 新增算子：
    - FusedSgd，将SGD更新过程中分散的梯度缩放、权重衰减、动量更新、参数赋值等多个细粒度操作融合为单个NPU Kernel执行（[!6220](https://gitcode.com/cann/ops-nn/pull/6220)）。
    - FusedAdamw，融合AdamW优化器，支持将多组参数列表（params、grads、expAvgs、expAvgSqs、maxExpAvgSqs、stateSteps）的参数更新、一阶/二阶动量更新、梯度缩放等操作融合为单个Kernel执行（[!7851](https://gitcode.com/cann/ops-nn/pull/7851)）。
    - SituGlu，SiTU门控线性单元（SiTU Gated Linear Unit）激活函数，将输入沿指定维度切分为门控（gate）与上路径（up）两半并按SiTU公式计算输出（[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - SituGluGrad，SiTU门控线性单元激活函数的反向梯度计算，根据上游梯度grad_y和前向输入x计算输入x的梯度grad_x（[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - DequantSituQuant，在Situ激活函数前后添加dequant和quant操作，实现x的DequantSituQuant计算（[!8798](https://gitcode.com/cann/ops-nn/pull/8798)）。
    - MatmulEmuSplitWeight，使用双路BF16 GEMM融合模拟FP32精度矩阵乘法，离线将FP32权重拆分为高位BF16与低位残差BF16，推理阶段执行两次BF16 GEMM并做线性组合（[!9237](https://gitcode.com/cann/ops-nn/pull/9237)）。
  - 算子功能增强：
    - aclnnAddmm/Baddbmm/AddmmWeightNz 支持需要broadcast的bias输入（[!8446](https://gitcode.com/cann/ops-nn/pull/8446)、[!8784](https://gitcode.com/cann/ops-nn/pull/8784)）。
    - aclnnMatmul新增支持8维度输入（[!8785](https://gitcode.com/cann/ops-nn/pull/8785)）。
    - MatMulV3算子新增AL1全载单核切K模板（[!7504](https://gitcode.com/cann/ops-nn/pull/7504)）。
    - torch_extension框架新增，通过JIT编译将PyTorch接口与ACLNN算子库桥接（[!5910](https://gitcode.com/cann/ops-nn/pull/5910)）。
    - torch_extension支持单算子独立编译与打包，单算子实现迁移至算子目录，整包与单算子包可隔离共存（[!7315](https://gitcode.com/cann/ops-nn/pull/7315)、[!7686](https://gitcode.com/cann/ops-nn/pull/7686)）。
    - torch_extension支持自定义算子包路径，可通过ASCEND_CUSTOM_OPP_PATH指定并自动扫描vendors目录，同时支持多vendor算子库查找与确定性计算（[!8023](https://gitcode.com/cann/ops-nn/pull/8023)、[!8115](https://gitcode.com/cann/ops-nn/pull/8115)）。
    - torch_extension导出cann_ops_nn命名空间供eager模式与图模式调用（[!7941](https://gitcode.com/cann/ops-nn/pull/7941)）。
<!-- end id9 -->
<!-- npu="950" id10 -->
- Ascend 950PR&950DT系列产品适配与场景支持：
  - 新增算子：
    - SituGlu，SiTU门控线性单元（SiTU Gated Linear Unit）激活函数，将输入沿指定维度切分为门控（gate）与上路径（up）两半并按SiTU公式计算输出（[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - SituGluGrad，SiTU门控线性单元激活函数的反向梯度计算，根据上游梯度grad_y和前向输入x计算输入x的梯度grad_x（[!8651](https://gitcode.com/cann/ops-nn/pull/8651)）。
    - SituMxQuant，将Situ激活函数与动态MX（Microscaling）量化融合为一个算子（[!8798](https://gitcode.com/cann/ops-nn/pull/8798)）。
    - FusedSgd，将SGD更新过程中分散的梯度缩放、权重衰减、动量更新、参数赋值等多个细粒度操作融合为单个NPU Kernel执行（[!7877](https://gitcode.com/cann/ops-nn/pull/7877)）。
    - FusedAdam，实现Adam优化器功能，支持多组参数列表（TensorList）一次调用完成Adam优化器功能（[!8934](https://gitcode.com/cann/ops-nn/pull/8934)）。
    - QuantMatmulActivationQuant，融合量化的矩阵乘、激活以及动态量化，当前支持gelu、swiglu激活和MX量化模式（[!7272](https://gitcode.com/cann/ops-nn/pull/7272)）。
    - ExpandIntoJaggedPermute，将稀疏数据置换索引从表维度扩展到批次维度，适用于稀疏特征在不同rank中具有不同批次大小的情况（[!8583](https://gitcode.com/cann/ops-nn/pull/8583)）。
  - 算子功能增强：
    - QuantBatchMatmulV4伪量化MX A8W4、TCG A8W4适配Blaze（[!7921](https://gitcode.com/cann/ops-nn/pull/7921)、[!9840](https://gitcode.com/cann/ops-nn/pull/9840)）。
    - WeightQuantBatchMatmulV2新增A16W8 ND per-channel、per-tensor的Blaze执行路径（[!9877](https://gitcode.com/cann/ops-nn/pull/9877)）。
    - Matmul非量化模板适配TensorAPI/Blaze：ASWT模板、BatchMatmul基础模板及broadcast场景切换TensorAPI（[!2133](https://gitcode.com/cann/ops-nn/pull/2133)、[!5087](https://gitcode.com/cann/ops-nn/pull/5087)），BatchMatmul StreamK模板切换Blaze（[!7731](https://gitcode.com/cann/ops-nn/pull/7731)），IterBatch场景新增Blaze模板（[!10543](https://gitcode.com/cann/ops-nn/pull/10543)）。
    - QuantBatchMatmulV3与Matmul支持Batch一致性：Batch一致性等级下关闭StreamK，并在不同M下固定A全载与单核切K的模板选择（[!7705](https://gitcode.com/cann/ops-nn/pull/7705)、[!11060](https://gitcode.com/cann/ops-nn/pull/11060)）。
    - torch_extension框架新增，通过JIT编译将PyTorch接口与ACLNN算子库桥接（[!5910](https://gitcode.com/cann/ops-nn/pull/5910)）。
    - torch_extension支持单算子独立编译与打包，单算子实现迁移至算子目录，整包与单算子包可隔离共存（[!7315](https://gitcode.com/cann/ops-nn/pull/7315)、[!7686](https://gitcode.com/cann/ops-nn/pull/7686)）。
    - torch_extension支持自定义算子包路径，可通过ASCEND_CUSTOM_OPP_PATH指定并自动扫描vendors目录，同时支持多vendor算子库查找与确定性计算（[!8023](https://gitcode.com/cann/ops-nn/pull/8023)、[!8115](https://gitcode.com/cann/ops-nn/pull/8115)）。
    - torch_extension导出cann_ops_nn命名空间供eager模式与图模式调用（[!7941](https://gitcode.com/cann/ops-nn/pull/7941)）。
  - 性能优化：
    - QuantBatchMatmulV3 MX场景优化tiling，覆盖base block负载均衡、scale在L1全载和4-buffer选择（[!6498](https://gitcode.com/cann/ops-nn/pull/6498)）。
    - QuantBatchMatmulV3 MX Basic API支持3-buffer L1（[!7237](https://gitcode.com/cann/ops-nn/pull/7237)）。
    - QuantBatchMatmul StreamK收益判断计入Fixpipe写回开销（[!9506](https://gitcode.com/cann/ops-nn/pull/9506)）。
    - DepthwiseConv2d从卷积通用实现中拆出专用模板，优化scalar bound（[!5726](https://gitcode.com/cann/ops-nn/pull/5726)）。
<!-- end id10 -->

#### ops-transformer库
<!-- npu="A3,910b" id11 -->
- Atlas A2系列产品和Atlas A3系列产品适配与场景支持：
  - 新增算子：
    - MsaIndexScore，支持MSA稀疏块重要性评分（[!9503](https://gitcode.com/cann/ops-transformer/pull/9503)）。
    - GenericBlockSparseAttention、GenericBlockSparseAttentionGrad及配套Metadata算子，支持自定义稀疏块粒度的注意力正反向计算（[!10628](https://gitcode.com/cann/ops-transformer/pull/10628)、[!10657](https://gitcode.com/cann/ops-transformer/pull/10657)、[!11003](https://gitcode.com/cann/ops-transformer/pull/11003)、[!11499](https://gitcode.com/cann/ops-transformer/pull/11499)）。
    - ChunkKdaFwd，支持KDA分块正向计算及BSND、BNSD、TND、NTD输入布局（[!9979](https://gitcode.com/cann/ops-transformer/pull/9979)）。
    - KeyPool和PoolKeyIndexer，分别支持Key压缩与池化稀疏索引选择，融合相关性评分、TopK选择和索引展开（[!11500](https://gitcode.com/cann/ops-transformer/pull/11500)、[!11513](https://gitcode.com/cann/ops-transformer/pull/11513)）。
    - LightningIndexerKLLoss，支持训练场景的KL散度损失融合计算，并提供PyTorch接口（[!9615](https://gitcode.com/cann/ops-transformer/pull/9615)）。
    - InplacePartialRotaryMul，支持原地部分旋转位置编码计算（[!6085](https://gitcode.com/cann/ops-transformer/pull/6085)）。
    - BlockAttentionResiduals，支持注意力残差的正向计算（[!11161](https://gitcode.com/cann/ops-transformer/pull/11161)）。
    - BlockAttentionResidualsGrad，支持注意力残差的反向计算（[!11006](https://gitcode.com/cann/ops-transformer/pull/11006)）。
  - 算子功能增强：
    - SparseFlashMla支持SWA场景下对原始KV进行稀疏选择，并将CSA场景的TopK范围扩展至1～8192（[!9384](https://gitcode.com/cann/ops-transformer/pull/9384)、[!11899](https://gitcode.com/cann/ops-transformer/pull/11899)、[!11919](https://gitcode.com/cann/ops-transformer/pull/11919)）。
    - FusedInferAttentionScore的非量化MLA Decode场景支持headNum为1～128的任意整数；INT8/INT4伪量化PageAttention场景支持KV Cache前两轴非连续，并支持PerToken PA、PerTokenHead PA场景的scale/offset非连续输入（[!9773](https://gitcode.com/cann/ops-transformer/pull/9773)、[!11069](https://gitcode.com/cann/ops-transformer/pull/11069)、[!10263](https://gitcode.com/cann/ops-transformer/pull/10263)）。
    - MlaProlog系列支持KV Cache首轴非连续输入；新增aclnnMlaPrologV4WeightNz接口，通过doRope参数控制RoPE计算（[!10296](https://gitcode.com/cann/ops-transformer/pull/10296)、[!9472](https://gitcode.com/cann/ops-transformer/pull/9472)）。
    - MlaPreprocess支持kvCache、kvCacheRope首轴非连续输入（[!6442](https://gitcode.com/cann/ops-transformer/pull/6442)）。
    - SparseFlashMlaGrad支持TopK泛化及通过seqused输入指定实际有效序列长度；SparseLightningIndexerKLLossGrad支持seqused输入，并将TopK范围扩展至1～8192（[!11087](https://gitcode.com/cann/ops-transformer/pull/11087)、[!9367](https://gitcode.com/cann/ops-transformer/pull/9367)、[!11504](https://gitcode.com/cann/ops-transformer/pull/11504)）。
    - MixedQuantSparseFlashMla在CSA路径新增TurboQuant TQ4压缩KV支持（[!12425](https://gitcode.com/cann/ops-transformer/pull/12425)）。
    - RecurrentGatedDeltaRule支持FLOAT32状态输入输出（[!5750](https://gitcode.com/cann/ops-transformer/pull/5750)）。
    - MoeGatingTopK新增Hash专家选择模式，通过映射表获取专家索引（[!6894](https://gitcode.com/cann/ops-transformer/pull/6894)、[!7415](https://gitcode.com/cann/ops-transformer/pull/7415)）。
    - MoeGatingTopK新增SqrtSoftplus归一化支持（[!11117](https://gitcode.com/cann/ops-transformer/pull/11117)）。
    - GroupedMatmul新增图模式转置融合，消除输入侧可融合的Transpose/TransposeD节点，减少数据搬运（[!8546](https://gitcode.com/cann/ops-transformer/pull/8546)）。
    - MegaMoe扩展SiTU、SwiGLU-OAI和SwiGLU-Step激活支持（[!8868](https://gitcode.com/cann/ops-transformer/pull/8868)）。
    - Atlas A3系列产品上MegaMoe支持弹性扩缩容，可通过失能rank掩码跳过相应计算与通信（[!9368](https://gitcode.com/cann/ops-transformer/pull/9368)）。
    - Atlas A3系列产品上AlltoAllvGroupedMatMul和GroupedMatMulAlltoAllv新增AIV通信路径（[!11516](https://gitcode.com/cann/ops-transformer/pull/11516)、[!11506](https://gitcode.com/cann/ops-transformer/pull/11506)）。
    - RopeWithSinCosCacheV2支持mropeSection为[11,11,10]的M-RoPE场景（[!7120](https://gitcode.com/cann/ops-transformer/pull/7120)）。
    - MhcPost和MhcPostBackward完善PyTorch图模式适配，支持可选hRes输入（[!10570](https://gitcode.com/cann/ops-transformer/pull/10570)、[!10277](https://gitcode.com/cann/ops-transformer/pull/10277)）。
    - MhcPre和MhcPreBackward新增适配支持（[!10035](https://gitcode.com/cann/ops-transformer/pull/10035)、[!10049](https://gitcode.com/cann/ops-transformer/pull/10049)）。
    - torch_extension支持按算子独立编译和定制子包，并采用延迟编译，在首次调用时编译所需算子（[!9712](https://gitcode.com/cann/ops-transformer/pull/9712)、[!8155](https://gitcode.com/cann/ops-transformer/pull/8155)、[!9734](https://gitcode.com/cann/ops-transformer/pull/9734)）。
    - torch_extension新增调用C++接口前的入参类型校验，提供包含参数名称的错误提示，便于定位调用问题（[!11968](https://gitcode.com/cann/ops-transformer/pull/11968)）。
  - 性能优化：
    - Atlas A3系列产品上MoeDistributeDispatchV2优化热点专家负载分配和通信窗口布局，改善Token发送负载均衡及HCCS端口分布（[!9594](https://gitcode.com/cann/ops-transformer/pull/9594)、[!10004](https://gitcode.com/cann/ops-transformer/pull/10004)）。
<!-- end id11 -->
<!-- npu="950" id12 -->
- Ascend 950PR&950DT系列产品适配与场景支持：
  - 新增算子：
    - GenericBlockSparseAttention、GenericBlockSparseAttentionGrad及配套Metadata算子，支持自定义稀疏块粒度的注意力正反向计算（[!10628](https://gitcode.com/cann/ops-transformer/pull/10628)、[!10657](https://gitcode.com/cann/ops-transformer/pull/10657)、[!11003](https://gitcode.com/cann/ops-transformer/pull/11003)、[!11499](https://gitcode.com/cann/ops-transformer/pull/11499)）。
    - ChunkKdaFwd，支持KDA分块正向计算及BSND、BNSD、TND、NTD输入布局（[!9979](https://gitcode.com/cann/ops-transformer/pull/9979)）。
    - KeyPool和PoolKeyIndexer，分别支持Key压缩与池化稀疏索引选择，融合相关性评分、TopK选择和索引展开（[!11500](https://gitcode.com/cann/ops-transformer/pull/11500)、[!11513](https://gitcode.com/cann/ops-transformer/pull/11513)）。
    - DenseLightningIndexerKLLossGrad、DenseLightningIndexerKLLossGradMetadata和SparseFlashMlaSoftmaxL1Norm，完善稠密LightningIndexer反向及损失计算能力（[!9237](https://gitcode.com/cann/ops-transformer/pull/9237)、[!8956](https://gitcode.com/cann/ops-transformer/pull/8956)）。
    - QuantFlashAttn全量化注意力算子及配套Metadata接口，支持MXFP8量化和HIFLOAT8 PerTensor量化，并支持MXFP8 FlashDecode（[!8968](https://gitcode.com/cann/ops-transformer/pull/8968)、[!9573](https://gitcode.com/cann/ops-transformer/pull/9573)、[!12516](https://gitcode.com/cann/ops-transformer/pull/12516)）。
    - QuantSparseFlashMla及配套Metadata算子，支持SWA、CSA、HCA全量化稀疏MLA计算及LSE输出（[!8499](https://gitcode.com/cann/ops-transformer/pull/8499)、[!8760](https://gitcode.com/cann/ops-transformer/pull/8760)、[!8762](https://gitcode.com/cann/ops-transformer/pull/8762)、[!9167](https://gitcode.com/cann/ops-transformer/pull/9167)）。
    - MoeInitRoutingV4和MoeReRoutingV2，支持TopK权重随Token同步重排；MoeInitRoutingV4支持图模式下动态传入active_num（[!6793](https://gitcode.com/cann/ops-transformer/pull/6793)）。
    - AllGatherMatmulV3，支持URMA AllGather与MXFP8/MXFP4量化矩阵乘融合，并提供all_gather_quant_matmul PyTorch接口（[!10643](https://gitcode.com/cann/ops-transformer/pull/10643)）。
    - InplacePartialRotaryMul，支持原地部分旋转位置编码计算（[!6085](https://gitcode.com/cann/ops-transformer/pull/6085)）。
    - QkvRmsNormRopeCacheWithKScale，融合Q/K RMSNorm、RoPE/M-RoPE、量化及KV Cache/K scale Cache更新，并支持M-RoPE MX量化（[!7023](https://gitcode.com/cann/ops-transformer/pull/7023)、[!8974](https://gitcode.com/cann/ops-transformer/pull/8974)、[!10557](https://gitcode.com/cann/ops-transformer/pull/10557)）。
    - UndGenQkvRmsNormRopeCache，融合理解/生成阶段QKV的间接拼接、RMSNorm、MRoPE与分页KV Cache更新（[!9455](https://gitcode.com/cann/ops-transformer/pull/9455)）。
    - InplacePartialRotaryMulGrad，支持部分旋转位置编码原地梯度计算（[!6895](https://gitcode.com/cann/ops-transformer/pull/6895)）。
    - ApplyRotaryPosEmbGrad，支持Q/K双路RoPE梯度融合（[!10684](https://gitcode.com/cann/ops-transformer/pull/10684)）。
    - BlockAttentionResiduals，支持注意力残差的正向计算（[!11161](https://gitcode.com/cann/ops-transformer/pull/11161)）。
    - BlockAttentionResidualsGrad，支持注意力残差的反向计算（[!11006](https://gitcode.com/cann/ops-transformer/pull/11006)）。
  - 算子功能增强：
    - MsaIndexScore新增FP8场景及KV Cache首轴非连续输入支持（[!11876](https://gitcode.com/cann/ops-transformer/pull/11876)）。
    - FusedInferAttentionScore的非量化MLA Decode场景支持headNum为1～128的任意整数；INT8/INT4伪量化PageAttention场景支持KV Cache前两轴非连续，并支持PerToken PA、PerTokenHead PA场景的scale/offset非连续输入（[!9773](https://gitcode.com/cann/ops-transformer/pull/9773)、[!11069](https://gitcode.com/cann/ops-transformer/pull/11069)、[!10263](https://gitcode.com/cann/ops-transformer/pull/10263)）。
    - MlaProlog系列支持KV Cache首轴非连续输入；新增aclnnMlaPrologV4WeightNz接口，通过doRope参数控制RoPE计算（[!10296](https://gitcode.com/cann/ops-transformer/pull/10296)、[!9472](https://gitcode.com/cann/ops-transformer/pull/9472)）。
    - BlockSparseAttentionGrad支持稀疏块粒度为16的整数倍（[!10188](https://gitcode.com/cann/ops-transformer/pull/10188)）。
    - ChunkGatedDeltaRule新增产品适配，支持FLOAT32状态输入及initial_state前两轴非连续（[!8318](https://gitcode.com/cann/ops-transformer/pull/8318)、[!8738](https://gitcode.com/cann/ops-transformer/pull/8738)、[!8711](https://gitcode.com/cann/ops-transformer/pull/8711)）。
    - RecurrentGatedDeltaRule支持FLOAT32状态输入输出（[!5750](https://gitcode.com/cann/ops-transformer/pull/5750)）。
    - QuantLightningIndexerV2新增MXFP8、MXFP4量化支持（[!9139](https://gitcode.com/cann/ops-transformer/pull/9139)）。
    - MoeGatingTopK新增Hash专家选择模式，通过映射表获取专家索引（[!6894](https://gitcode.com/cann/ops-transformer/pull/6894)）。
    - MoeInitRoutingV3支持以expertIdx=-1标记并过滤无效专家（[!9708](https://gitcode.com/cann/ops-transformer/pull/9708)）。
    - GroupedMatmul新增图模式转置融合，消除输入侧可融合的Transpose/TransposeD节点，减少数据搬运（[!8546](https://gitcode.com/cann/ops-transformer/pull/8546)）。
    - GroupedMatmul的WeightNz MX量化支持“单输入、多权重、单输出”场景，权重及对应scale的TensorList数量扩展至1024；MXFP8 WeightNz的非转置权重场景新增FRACTAL_NZ格式的权重量化scale支持（[!6739](https://gitcode.com/cann/ops-transformer/pull/6739)、[!11848](https://gitcode.com/cann/ops-transformer/pull/11848)、[!9728](https://gitcode.com/cann/ops-transformer/pull/9728)）。
    - GroupedMatmulSwigluQuantV2在MX WeightNz场景支持多权重Tensor输入；WeightND场景放宽N轴对齐约束，FP8支持2对齐、FP4支持4对齐（[!7302](https://gitcode.com/cann/ops-transformer/pull/7302)、[!7662](https://gitcode.com/cann/ops-transformer/pull/7662)）。
    - GroupedMatmulSwigluQuantV2新增A8W8 PerToken WeightNz支持，覆盖INT8、HIF8、FP8及权重转置/非转置输入（[!9936](https://gitcode.com/cann/ops-transformer/pull/9936)）。
    - GroupedMatmul新增INT8×INT4（A8W4）和INT4×INT4（A4W4）量化支持，WeightNz MX A8W4场景新增FLOAT4_E1M2权重类型支持（[!9611](https://gitcode.com/cann/ops-transformer/pull/9611)、[!8748](https://gitcode.com/cann/ops-transformer/pull/8748)）。
    - GroupedMatmulActivationQuant在WeightNz场景新增MXFP4输入与FP4量化输出支持，扩展矩阵乘、激活与量化融合的低比特计算能力（[!9279](https://gitcode.com/cann/ops-transformer/pull/9279)）。
    - MegaMoe扩展SiTU、SwiGLU-OAI和SwiGLU-Step激活支持，其中SwiGLU-OAI和SwiGLU-Step限MTE通信路径（[!9667](https://gitcode.com/cann/ops-transformer/pull/9667)、[!9971](https://gitcode.com/cann/ops-transformer/pull/9971)）。
    - MegaMoe支持共享专家，并在MTE通信路径下支持按专家分别传入权重及量化参数TensorList（[!8822](https://gitcode.com/cann/ops-transformer/pull/8822)、[!9493](https://gitcode.com/cann/ops-transformer/pull/9493)）。
    - AllGatherMatmulV2和MatmulReduceScatterV2新增MXFP4量化及对应图模式支持（[!7193](https://gitcode.com/cann/ops-transformer/pull/7193)、[!8596](https://gitcode.com/cann/ops-transformer/pull/8596)、[!8844](https://gitcode.com/cann/ops-transformer/pull/8844)、[!9240](https://gitcode.com/cann/ops-transformer/pull/9240)）。
    - AllGatherMatmulV2和MatmulReduceScatterV2在MX量化场景支持右矩阵非转置输入（[!10488](https://gitcode.com/cann/ops-transformer/pull/10488)、[!10617](https://gitcode.com/cann/ops-transformer/pull/10617)）。
    - MoeEpDispatch和MoeEpCombine采用AIV直驱URMA的通信方式，支持MoE训练场景，提供ElasticBuffer接口、Dispatch路由信息复用及配套后处理算子（[!7807](https://gitcode.com/cann/ops-transformer/pull/7807)、[!7814](https://gitcode.com/cann/ops-transformer/pull/7814)、[!9388](https://gitcode.com/cann/ops-transformer/pull/9388)、[!10249](https://gitcode.com/cann/ops-transformer/pull/10249)）。
    - Engram通过ElasticBuffer提供主机内存中的分布式表存储，配套EngramFetch和EngramFetchWait实现按索引RDMA远端读取、异步发起与等待（[!7749](https://gitcode.com/cann/ops-transformer/pull/7749)、[!7317](https://gitcode.com/cann/ops-transformer/pull/7317)）。
    - Engram新增训练正反向支持，通过ElasticBuffer接口完成分布式表查询、跨卡梯度回传和按表项稀疏累加，支持输出稀疏梯度用于优化器更新（[!8914](https://gitcode.com/cann/ops-transformer/pull/8914)、[!9179](https://gitcode.com/cann/ops-transformer/pull/9179)、[!9308](https://gitcode.com/cann/ops-transformer/pull/9308)）。
    - InplacePartialRotaryMul新增自动微分支持（[!8493](https://gitcode.com/cann/ops-transformer/pull/8493)）。
    - MhcPost和MhcPostBackward完善PyTorch图模式适配，支持可选hRes输入（[!10570](https://gitcode.com/cann/ops-transformer/pull/10570)、[!10277](https://gitcode.com/cann/ops-transformer/pull/10277)）。
    - MhcPre和MhcPreBackward新增aclnnMhcPreV2和aclnnMhcPreBackwardV2接口，支持选择FP32/HF32 Cube计算模式（[!9243](https://gitcode.com/cann/ops-transformer/pull/9243)、[!12232](https://gitcode.com/cann/ops-transformer/pull/12232)）。
    - MhcPreSinkhorn和MhcPreSinkhornBackward新增TND格式支持，并补充正反向算子的GE图模式适配（[!10272](https://gitcode.com/cann/ops-transformer/pull/10272)、[!9519](https://gitcode.com/cann/ops-transformer/pull/9519)、[!8382](https://gitcode.com/cann/ops-transformer/pull/8382)）。
    - torch_extension支持按算子独立编译和定制子包，并采用延迟编译，在首次调用时编译所需算子（[!9712](https://gitcode.com/cann/ops-transformer/pull/9712)、[!8155](https://gitcode.com/cann/ops-transformer/pull/8155)、[!9734](https://gitcode.com/cann/ops-transformer/pull/9734)）。
    - torch_extension新增调用C++接口前的入参类型校验，提供包含参数名称的错误提示，便于定位调用问题（[!11968](https://gitcode.com/cann/ops-transformer/pull/11968)）。
  - 性能优化：
    - KvQuantSparseFlashAttention的MLA场景性能优化，减少Vector侧计算开销（[!10428](https://gitcode.com/cann/ops-transformer/pull/10428)）。
    - MoeInitRoutingV3优化MXFP8量化、透传和FP8分组量化场景性能（[!9199](https://gitcode.com/cann/ops-transformer/pull/9199)）。
    - 优化MegaMoe在MTE通信路径下的A8W4/A4W4 Wave流水调度，提高Dispatch、专家计算与Combine的流水重叠效率（[!10092](https://gitcode.com/cann/ops-transformer/pull/10092)、[!10319](https://gitcode.com/cann/ops-transformer/pull/10319)、[!10302](https://gitcode.com/cann/ops-transformer/pull/10302)）。
    - 优化MhcPre和MhcPreBackward的计算流水（[!9243](https://gitcode.com/cann/ops-transformer/pull/9243)、[!12232](https://gitcode.com/cann/ops-transformer/pull/12232)）。
<!-- end id12 -->

### 图引擎

#### 图模式

- 新增自定义Pass开发和自定义算子开发的Python API，支持在Python环境下编写自定义Pass及接入自定义算子。([!4147](https://gitcode.com/cann/ge/pull/4147)、[!4254](https://gitcode.com/cann/ge/pull/4254)、[!4388](https://gitcode.com/cann/ge/pull/4388))
- 新增Host CPU算子注册接口，支持自定义Host CPU算子接入常量折叠优化及动态Shape执行时调度。([!4481](https://gitcode.com/cann/ge/pull/4481)、[!4538](https://gitcode.com/cann/ge/pull/4538)、[!4918](https://gitcode.com/cann/ge/pull/4918))
- 新增动态Shape自动多流并行优化，可通过ge.autoMultistreamParallelMode开启；ATC新增multi_stream_parallel_mode参数，支持离线推理场景开启自动多流优化。([!3781](https://gitcode.com/cann/ge/pull/3781)、[!4184](https://gitcode.com/cann/ge/pull/4184)、[!4301](https://gitcode.com/cann/ge/pull/4301))
- 优化RunGraphWithStreamAsync接口易用性，静态Shape场景下用户未注册外置Allocator时，也支持自动分配输出内存。( [!3306](https://gitcode.com/cann/ge/pull/3306))
- 支持PCIe算子入图，并提供算子声明PCIe Through能力。([!430](https://gitcode.com/cann/metadef/pull/430)、[!4394](https://gitcode.com/cann/ge/pull/4394))
- 新增Host输入场景下的动态Shape调度性能优化，对连续在Host CPU上执行的算子进行Codegen融合，进一步提升性能。( [!3626](https://gitcode.com/cann/ge/pull/3626)、[!4669](https://gitcode.com/cann/ge/pull/4669))

#### 自动融合

- 新增支持inductor开启自动融合能力，支持view类算子（transpose/slice/broadcast）、泛Norm类算子、elementwise类算子、Concat算子、CV融合。([!1654](https://gitcode.com/cann/graph-autofusion/pull/1654)、[!1250](https://gitcode.com/cann/graph-autofusion/pull/1250)、[!2689](https://gitcode.com/cann/ge/pull/2689)、[!1626](https://gitcode.com/cann/graph-autofusion/pull/1626)、[!1700](https://gitcode.com/cann/graph-autofusion/pull/1700))
- 新增编译性能优化。([!1799](https://gitcode.com/cann/graph-autofusion/pull/1799)、[!1591](https://gitcode.com/cann/graph-autofusion/pull/1591))
- 补齐AscendLoopIR完备度。([!1699](https://gitcode.com/cann/graph-autofusion/pull/1699)、[!1749](https://gitcode.com/cann/graph-autofusion/pull/1749))
- 新增支持NDDMA性能建模，ATT建模优化。([!1690](https://gitcode.com/cann/graph-autofusion/pull/1690)、[!1792](https://gitcode.com/cann/graph-autofusion/pull/1792)、[!1266](https://gitcode.com/cann/graph-autofusion/pull/1266)、[!1460](https://gitcode.com/cann/graph-autofusion/pull/1460)、[!1580](https://gitcode.com/cann/graph-autofusion/pull/1580)、[!534](https://gitcode.com/cann/graph-autofusion/pull/534)、[!1208](https://gitcode.com/cann/graph-autofusion/pull/1208))

### 算子编程

#### 关键特性
<!-- npu="950" id13 -->
- C API：
  - <term>Ascend 950PR&950DT系列产品</term>新增`asc_lock`和`asc_unlock`接口（[!5216](https://gitcode.com/cann/asc-devkit/pull/5216)），并补全部分接口及接口支持的数据类型（[!5168](https://gitcode.com/cann/asc-devkit/pull/5168)）。
<!-- end id13 -->
- Tensor API：
  - 新增conv2D功能（[!4239](https://gitcode.com/cann/asc-devkit/pull/4239)）。
  - 新增超大Tensor的Dump功能（[!6371](https://gitcode.com/cann/asc-devkit/pull/6371)）。
<!-- npu="950" id14 -->
- SuperKernel：
  - 支持<term>Ascend 950PR&950DT系列产品</term>npugraph_ex路径的SuperKernel功能（[!430](https://gitcode.com/cann/graph-autofusion/pull/430)）。
<!-- end id14 -->
- 基础API：
  - Ascend C支持SIMD VF内FIFO方式的dump、printf和assert（[!4829](https://gitcode.com/cann/asc-devkit/pull/4829)）。
- SIMT API：
  - 优化API精度，支持subnormal（[!6028](https://gitcode.com/cann/asc-devkit/pull/6028)）。
- 通信API：
  - 新增AIN接口，提供基于对称window的Put/Get/Signal/Flush等单边通信及barrier同步能力（[!59](https://gitcode.com/cann/asc-comm/pull/59)）。

#### 样例更新

- C API样例：
  - 新增8个搬运场景样例、19个单指令reg样例、7个矩阵计算样例、2个doublebuffer优化样例和1个融合算子最佳实践样例（[!5346](https://gitcode.com/cann/asc-devkit/pull/5346)）。
- Tensor API样例：
  - 新增卷积样例，配套conv2D功能（[!4316](https://gitcode.com/cann/asc-devkit/pull/4316)）。
  - 新增bank_conflict、matmul_bias_fusion、matmul_split_k、conv2d_forward、batch_matmul等样例（[!6163](https://gitcode.com/cann/asc-devkit/pull/6163)）。
  - 新增自定义Op样例（[!6174](https://gitcode.com/cann/asc-devkit/pull/6174)）。
- 通信API样例：
  - 新增AIN的basic_ring样例，演示多卡环形场景下AIV Kernel通过AIN接口调用Put/Get进行点对点单边通信（[!80](https://gitcode.com/cann/asc-comm/pull/80)）。

<!-- npu="950" id15 -->
### PyPTO

#### 支持Ascend 950PR&950DT系列产品上使用PyPTO Pro开发算子

- 新增PyPTO Pro融合算子开发接口
  - 泛化支持量化、非量化场景的Cube侧Tile粒度的矩阵的搬运、计算（[!5399](https://gitcode.com/cann/pypto/pull/5399)、[!5439](https://gitcode.com/cann/pypto/pull/5399)）。
  - 泛化支持Vector侧Tile粒度的数据搬运，同时支持SIMD RegBase & SIMT & SIMD Tile三种Vector计算方式（[!4925](https://gitcode.com/cann/pypto/pull/4925)、[!5341](https://gitcode.com/cann/pypto/pull/5341)、[!4946](https://gitcode.com/cann/pypto/pull/4946)）。
  - 泛化支持Mix融合算子开发和流水编排（[!4725](https://gitcode.com/cann/pypto/pull/4725)、[!4925](https://gitcode.com/cann/pypto/pull/4925)）。

- 新增PyPTO Pro易用性提升
  - 支持自动核内同步（[!4725](https://gitcode.com/cann/pypto/pull/4725)、[!6209](https://gitcode.com/cann/pypto/pull/6209)）。
  - 支持自动核间流水编排（[!4690](https://gitcode.com/cann/pypto/pull/4690)、[!5332](https://gitcode.com/cann/pypto/pull/5332)、[!6038](https://gitcode.com/cann/pypto/pull/6038)）。

- 新增PyPTO Pro算子网络接入能力
  - 支持eager模式直调（[!4695](https://gitcode.com/cann/pypto/pull/4695)）。
  - 支持aclGraph入图（[!4695](https://gitcode.com/cann/pypto/pull/4695)）。
    - 在ops-transformer仓支持aclnn方式生成算子二进制（[!4695](https://gitcode.com/cann/pypto/pull/!4695)、[!6614](https://gitcode.com/cann/pypto/pull/6614)）。
    - 支持profiling数据采集（[!6221](https://gitcode.com/cann/pypto/pull/6221)、[!6306](https://gitcode.com/cann/pypto/pull/!6306)、[!6634](https://gitcode.com/cann/pypto/pull/!6634)）。
    - 支持内存越界检测工具（[!5668](https://gitcode.com/cann/pypto/pull/5668)）。
<!-- end id15 -->

#### PyPTO Tensor编程方式持续完善

- 新增功能支持
  - IR重构，`@pypto.frontend.jit` 已默认切换为新IR（[!5152](https://gitcode.com/cann/pypto/pull/5152)）。
  - If/For控制流语句支持返回符号化标量（yield），控制流内计算结果可参与后续计算与动态Shape推导（[!5465](https://gitcode.com/cann/pypto/pull/5465)）。
  - 支持与torch_npu同步计算确定性等级（0关闭、1确定性、2强一致性），JIT编译入口自动读取torch_npu进程级设置并写入编译配置，保证编码侧与torch_npu一致（[!5622](https://gitcode.com/cann/pypto/pull/5622)）。

- 性能优化：
  <!-- npu="950" id20 -->
  - TopK API在<term>Ascend 950PR&950DT系列产品</term>上的RadixSelect算法路径优化，通过缩减指令数提升排序性能（[!5239](https://gitcode.com/cann/pypto/pull/5239)）。
  <!-- end id20 -->
  - 乱序调度预调度阶段新增向量排序算法，减少L1 spill次数（[!5469](https://gitcode.com/cann/pypto/pull/5469)）。

### 运行时

- 支持Kernel Launch和模型执行的阻塞调试模式（[!4247](https://gitcode.com/cann/runtime/pull/4247)）。
- 支持ACL Graph同一捕获模型跨流执行有序（[!4479](https://gitcode.com/cann/runtime/pull/4479)）。
- 新增PCI Bus ID双向查询接口：aclrtDeviceGetPCIBusId、aclrtDeviceGetByPCIBusId（[!4066](https://gitcode.com/cann/runtime/pull/4066)）。
<!-- npu="950" id16 -->
### 通信库

#### 集合通信

- <term>Ascend 950PR&950DT系列产品</term>支持在experimental目录扩展自定义算法，提升生态扩展易用性([!2734](https://gitcode.com/cann/hccl/pull/2734))。
- <term>Ascend 950PR&950DT系列产品</term>支持URMA场景下的对称内存能力，支持用户通过 HcclCommSymWinRegister 注册对称窗口，提升算子算法实现易用性([!2369](https://gitcode.com/cann/hcomm/pull/2369) [!1195](https://gitcode.com/cann/hccl/pull/1195))。
- <term>Ascend 950PR&950DT系列产品</term>支持CCU资源灵活申请，提升自定义CCU算子灵活性([!3367](https://gitcode.com/cann/hcomm/pull/3367))。
- <term>Ascend 950PR&950DT系列产品</term>提供 Host 网卡实现扩展能力，支持灵活扩展hcomm接口实现([!4257](https://gitcode.com/cann/hcomm/pull/4257))。

#### HIXL单边通信

- HIXL新增UB_RTP传输协议支持，用于昇腾950平台NPU之间的数据传输([!612](https://gitcode.com/cann/hixl/pull/612)、[!818](https://gitcode.com/cann/hixl/pull/818))。
- HIXL支持多Channel并发传输，提升链路带宽利用率([!940](https://gitcode.com/cann/hixl/pull/940)、[!1024](https://gitcode.com/cann/hixl/pull/1024)、[!1026](https://gitcode.com/cann/hixl/pull/1026)、[!1318](https://gitcode.com/cann/hixl/pull/1318))。
- HIXL支持配置每批次最大传输任务数与最大活跃Channel数量，管控通信资源开销([!1105](https://gitcode.com/cann/hixl/pull/1105)、[!704](https://gitcode.com/cann/hixl/pull/704))。
- HIXL新增传输异常上报机制，可及时感知底层通信故障([!681](https://gitcode.com/cann/hixl/pull/681)、[!787](https://gitcode.com/cann/hixl/pull/787))。
- FabricMem模式支持AI CPU展开优化，进一步提升传输性能([!839](https://gitcode.com/cann/hixl/pull/839))。
- HIXL提供Python API能力，以wheel安装包对外发布([!658](https://gitcode.com/cann/hixl/pull/658)、[!903](https://gitcode.com/cann/hixl/pull/903))。

<!-- end id16 -->
### PTO虚拟指令集

- 基础Vector&Cube指令：
  - 新增支持64位数据类型（[!1711](https://gitcode.com/cann/pto-isa/pull/1711)、[!1585](https://gitcode.com/cann/pto-isa/pull/1585)、[!1428](https://gitcode.com/cann/pto-isa/pull/1428)）。
  - TMOV/TEXTRACT/TINSERT新增支持布局格式转换（[!1450](https://gitcode.com/cann/pto-isa/pull/1450)、[!1459](https://gitcode.com/cann/pto-isa/pull/1459)、[!1718](https://gitcode.com/cann/pto-isa/pull/1718)）。
  - TPUSH/TPOP新增奇数切分（[!1380](https://gitcode.com/cann/pto-isa/pull/1380)）。
- 通信类指令：
  - TPUT_ASYNC、TGET_ASYNC增加A5基于1825网卡的跨机RDMA通信能力（[!1374](https://gitcode.com/cann/pto-isa/pull/1374)）。
  - 新增TPUT_ASYNC_NOTIFY指令（[!1516](https://gitcode.com/cann/pto-isa/pull/1516)）。
- CostModel仿真：接入A2A3全量耗时PTO ISA指令性能预测，实现cycles 90%+预测准确度（[!1674](https://gitcode.com/cann/pto-isa/pull/1674)）。
- CPU-SIM：随NPU同步新增CPU仿真指令。

### PTOAS(PTO汇编器)

新增工具链，支持命令行编译，PTO ISA规范编译，Python绑定和脚本构造入口能力，主要职责：

  - 解析PTO字节码文件。
  - 验证PTO ISA结构、类型和目标相关约束。
  - 支持根据用户指定编译选项处理布局、地址和同步等关键能力。
  - Emit可调用代码。

### 调试与分析工具

- Profiling支持采集task的page fault次数（[!3279](https://gitcode.com/cann/runtime/pull/3279)）。
- aclrt接口补充上报内存大小、拷贝方向等profiling数据（[!3644](https://gitcode.com/cann/runtime/pull/3644)）。

### 维测能力

- aicore err支持自动解析错误行号（[!4080](https://gitcode.com/cann/runtime/pull/4080)）。

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

<!-- npu="950,A3,910b" id18 -->
## 已修复问题

以下问题在9.2.0版本修复：

- 修复Atlas A2系列产品、Atlas A3系列产品和Ascend 950PR&950DT系列产品NPU MM算子通过GE aclnn fallback回调执行场景下的HF32属性未正确传递至底层导致性能不达预期的问题。
- 修复Atlas A2系列产品和Atlas A3系列产品RmsNorm算子在输入shape超过int32最大值有精度误差的问题。
- 修复Atlas A2系列产品和Atlas A3系列产品matmul算子融合通路转为matmulv2场景下的_deterministic_level属性未继承导致后续节点属性丢失的问题。
- 修复Atlas A2系列产品和Atlas A3系列产品matmul算子Host端性能劣化场景下的FSDP通信与计算细粒度流水受阻导致模型整体性能下降的问题。
- 修复FAG算子在EOD场景下存在偶现清空pad不完整的问题。
- 修复Atlas A3系列产品aclgraph aicpu展开HCCL主流和capture主流为同一条stream时，orderStream图规则校验失败的问题。
- 修复Atlas A3系列产品AllGatherRingConcurrentDirect算法在大集群规模场景下，主从流任务下发死锁的问题。
- 修复Atlas A2系列产品和Atlas A3系列产品导入非主线版本环境变量时RingMLAOperation接口demo运行失败问题。
- 修复Atlas A2系列产品和Atlas A3系列产品torch_npu.npu_format_cast接口format和shape不匹配的场景下，从拦截fallback到aclop的问题。
- （**不兼容变更**）修复Atlas A2系列产品和Atlas A3系列产品SparseFlashMLA算子torch接口参数默认值错误的问题（ori_mask_mode、cmp_mask_mode、ori_win_left、ori_win_right）。
- 修复Ascend 950PR&950DT系列产品同一个卡同一个进程下，前一次创建成功的通信域ranksize比接下来要创建子通信域的ranksize小的时候导致子通信域创建失败问题。
<!-- end id18 -->

## 文档变更说明

### 编程语言

#### Ascend C算子开发

- 补充L2 Cache切分优化说明（[!5418](https://gitcode.com/cann/asc-devkit/pull/5418)）。
- 新增NPU架构版本3510新特性使用说明（[!5265](https://gitcode.com/cann/asc-devkit/pull/5265)）。
- “Aclnn算子工程化开发”章节进行优化调整，增加推荐阅读路径、快速入门等内容（[!3929](https://gitcode.com/cann/asc-devkit/pull/3929)）。
- 新增“高级编程 > 内存模型”章节，介绍缓存一致性和内存一致性的概念、原理、常见问题和解决方案等内容（[!5150](https://gitcode.com/cann/asc-devkit/pull/5150)）。
- 新增“基于Tensor的C++编程”章节（[!3187](https://gitcode.com/cann/asc-devkit/pull/3187)）。
- 新增“原子操作指令优化”章节（[!4710](https://gitcode.com/cann/asc-devkit/pull/4710)）。

#### PyPTO算子开发

新增支持PyPTO Pro开发模式，支持面向Tile操作的Tile编程模型（[!4999](https://gitcode.com/cann/pypto/pull/4999)、[!5093](https://gitcode.com/cann/pypto/pull/5093)）。

#### 图开发

- “自定义算子入图”章节进行特性调整和目录结构调整。
- 优化“AutoFuse自动融合”章节：
  - 调整目录结构，新增“快速入门”、“启用AutoFuse”章节，环境变量的详细说明移至“附录”章节。
  - “启用AutoFuse”章节分两条路径分别介绍自动融合的开启模式，新增Inductor路径下的融合开启方式。

### 编译器

#### PTOAS

新增《PTOAS》文档，详细信息请见[PTOAS](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/compiler/ptoas/overview/what_is_ptoas.md)。

### 通信库

#### HCCL集合通信库

优化三个故障案例：“建链超时”、“notify_wait超时”和“通信域建联超时问题背景”章节（[!2782](https://gitcode.com/cann/hccl/pull/2782)）。

### API参考
<!-- npu="950" id19 -->
#### Ascend C API

- “C API”章节重构Ascend 950PR&950DT系列产品资料，细化目录结构和优化资料内部结构，完善接口功能说明、调用示例和约束说明（[!5266](https://gitcode.com/cann/asc-devkit/pull/5266)）。
- “Tensor API”章节完善cube_compute_load/store、layout_structure、data_move、tensor_structure等资料（[!5134](https://gitcode.com/cann/asc-devkit/pull/5134)）。
- 优化“SIMT API”章节：
  - 补充UB复用排布规则说明（[!6077](https://gitcode.com/cann/asc-devkit/pull/6077)）。
  - 数学库接口更新精度说明（[!6047](https://gitcode.com/cann/asc-devkit/pull/6047)）。
  - 协作组增加grid_group、thread_group说明（[!4795](https://gitcode.com/cann/asc-devkit/pull/4795)、[!5651](https://gitcode.com/cann/asc-devkit/pull/5651)）。
  - 新增“SIMT指令理论性能汇总”章节（[!5543](https://gitcode.com/cann/asc-devkit/pull/5543)）。
  - 新增整型转换函数（[!5170](https://gitcode.com/cann/asc-devkit/pull/5170)）。
  - 新增SIMT编程场景使用的编译选项（[!5035](https://gitcode.com/cann/asc-devkit/pull/5035)）。
- 新增“CheckOpResSufficient”章节（[!5766](https://gitcode.com/cann/asc-devkit/pull/5766)）。
<!-- end id19 -->

#### PyPTO API

新增PyPTO Pro API章节（[!4991](https://gitcode.com/cann/pypto/pull/4991)）。

#### 算子库API

《算子库》手册“算子库 > 算子接口（torch_extension）”新增“NN类接口”章节。

### 调试与分析工具

#### 性能调优工具

- 目录结构调整，以采集工具为粒度平铺章节。
- Ascend PyTorch调优工具、MindSpore调优工具、使用TensorFlow框架接口采集性能数据、使用acl Python接口采集性能数据章节调整至各自源文档发布，《性能调优工具》手册在简介中保留跳转链接。

#### 内存分析工具

- 新增显存OOM分析项，发生OOM时dump最新和最大内存块信息。
- 支持采集进程显存曲线和整卡显存曲线。
- 新增host内存泄漏检测功能资料。

#### AMCT模型压缩工具

新增[AMCT（acl）](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/devaids/amct/atlasamct_16_0301.html)场景下的量化特性以及接口说明。

## 开源软件声明

开源软件声明请查看[开源软件声明](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/maintenref/refdoc/refer003.html)。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/maintenref/refdoc/refer002.html)。

## 病毒扫描报告

病毒扫描报告请查看[病毒扫描报告](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/920/maintenref/refdoc/refer004.html)。
