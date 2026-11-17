# CANN 9.0.1版本说明

## 版本下载地址
<a href="https://www.hiascend.com/cann/download?versionId=745&ids=d806%2Ch0501%2Ch0601%2Ch0702&currentTab=0">快速安装地址</a>
## 版本配套

**1、CANN与Ascend HDK版本配套关系**

|CANN版本  |  配套Ascend HDK版本| 
|--|--|
| [CANN 9.0.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.1) | [Ascend HDK 26.0.RC3 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC3)<br> [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1)<br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2)  <br> [Ascend HDK 25.5.1](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1) |
| [CANN 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1)<br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2)  <br> [Ascend HDK 25.5.1](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1) |
| [CANN 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1) <br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2) <br> [Ascend HDK 25.5.1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1)|


**2、 CANN组合包版本配套关系**

|ops版本  |配套toolkit版本  |  
|--|--|
| [ascend-cann-ops 9.0.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.1) | [ascend-cann-toolkit 9.0.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.1)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [ascend-cann-toolkit 9.0.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.1)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.0.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.1)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |

**3、 CANN独立升级子包版本配套关系**

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| cann-ops-math 9.0.1| [v9.0.1](https://gitcode.com/cann/ops-math/tags/v9.0.1)      | CANN 9.0.1<br> CANN 9.0.0<br> CANN 8.5.2 |
| cann-ops-nn 9.0.1 | [v9.0.1](https://gitcode.com/cann/ops-nn/tags/v9.0.1)        | CANN 9.0.1<br> CANN 9.0.0<br> CANN 8.5.2 |
| cann-ops-cv 9.0.1 | [v9.0.1](https://gitcode.com/cann/ops-cv/tags/v9.0.1)        | CANN 9.0.1<br> CANN 9.0.0<br> CANN 8.5.2 |
| cann-ops-transformer 9.0.1 | [v9.0.1](https://gitcode.com/cann/ops-transformer/tags/v9.0.1) | CANN 9.0.1<br> CANN 9.0.0<br> CANN 8.5.2 |
| cann-hccl 9.0.1 | [v9.0.1](https://gitcode.com/cann/hccl/tags/v9.0.1)          | CANN 9.0.1<br> CANN 9.0.0<br> CANN 8.5.2 |
| cann-hixl 9.0.1 | [v9.0.1](https://gitcode.com/cann/hixl/tags/v9.0.1)          | CANN 9.0.1<br> CANN 9.0.0<br> CANN 8.5.2 |

**4、CANN开源子包版本配套关系**

| CANN子包版本                       | 版本源码标签                                                 | 配套CANN版本      |
| ---------------------------------- | ------------------------------------------------------------ | ----------------- |
| cann-opbase 9.0.1           | [v9.0.1](https://gitcode.com/cann/opbase/tags/v9.0.1)        | CANN 9.0.1   |
| cann-oam-tools 9.0.1        | [v9.0.1](https://gitcode.com/cann/oam-tools/tags/v9.0.1)     | CANN 9.0.1   |
| cann-asc-tools 9.0.1        | [v9.0.1](https://gitcode.com/cann/asc-tools/tags/v9.0.1)     | CANN 9.0.1   |
| cann-asc-devkit 9.0.1       | [v9.0.1](https://gitcode.com/cann/asc-devkit/tags/v9.0.1)    | CANN 9.0.1   |
| cann-pto-isa 9.0.1          | [v9.0.1](https://gitcode.com/cann/pto-isa/tags/v9.0.1)       | CANN 9.0.1   |
| cann-ge-compiler 9.0.1      | [v9.0.1](https://gitcode.com/cann/ge/tags/v9.0.1)            | CANN 9.0.1   |
| cann-ge-executor 9.0.1      | [v9.0.1](https://gitcode.com/cann/ge/tags/v9.0.1)            | CANN 9.0.1   |
| cann-graph-autofusion 9.0.1 | [v9.0.1](https://gitcode.com/cann/graph-autofusion/tags/v9.0.1) | CANN 9.0.1   |
| cann-metadef 9.0.1          | [v9.0.1](https://gitcode.com/cann/metadef/tags/v9.0.1)       | CANN 9.0.1   |
| cann-dflow-executor 9.0.1   | [v9.0.1](https://gitcode.com/cann/ge/tags/v9.0.1)            | CANN 9.0.1   |
| cann-hcomm 9.0.1            | [v9.0.1](https://gitcode.com/cann/hcomm/tags/v9.0.1)         | CANN 9.0.1   |
| cann-npu-runtime 9.0.1      | [v9.0.1](https://gitcode.com/cann/runtime/tags/v9.0.1)     | CANN 9.0.1   |

子包独立升级的具体操作请参考[子包独立升级](#子包独立升级)。

## 删除和废弃特性

### 算子库

**transformer库以下接口在CANN 9.0.0中被标记为废弃，将在2027年3月30日之后的版本删除**
- aclnnGroupedMatMulAllReduce接口废弃，替换为：aclnnMatmulAllReduce。
- aclnnGroupedMatmul/aclnnGroupedMatmulV2/aclnnGroupedMatmulV3/aclnnGroupedMatmulV4接口废弃，替换为：aclnnGroupedMatmulV5。
- aclnnFusedInferAttentionScore/aclnnFusedInferAttentionScoreV2/aclnnFusedInferAttentionScoreV3接口废弃，替换为：aclnnFusedInferAttentionScoreV4。
- aclnnIncreFlashAttention/aclnnIncreFlashAttentionV2/aclnnIncreFlashAttentionV3接口废弃，替换为：aclnnIncreFlashAttentionV4。
- aclnnPromptFlashAttention/aclnnPromptFlashAttentionV2接口废弃，替换为：aclnnPromptFlashAttentionV3。
- aclnnMlaProlog/aclnnMlaPrologV2WeightNz接口废弃，替换为：aclnnMlaPrologV3WeightNz。
- aclnnMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnMatmulAllReduce和aclnnAddRmsNorm。
- aclnnQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnQuantMatmulAllReduceV2和aclnnAddRmsNorm。
- aclnnWeightQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnWeightQuantMatmulAllReduce和aclnnAddRmsNorm。
- aclnnInplaceQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnQuantMatmulAllReduceV2和aclnnAddRmsNorm。
- aclnnInplaceMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnMatmulAllReduce和aclnnAddRmsNorm。
- aclnnInplaceWeightQuantMatmulAllReduceAddRmsNorm接口废弃，替换为：aclnnWeightQuantMatmulAllReduce和aclnnAddRmsNorm。

### 模型压缩工具

模型压缩工具以下特性标记为废弃，废弃的特性将在CANN 9.0.0之后的版本删除。
- 非均匀量化
- 自动混合精度
- 近似校准
- int4量化感知训练
- amct_mindspore所有特性

## 已修复问题

- 修复了Atlas A2系列产品的大EP场景下，D节点注入片上内存多bit故障，无法进入快速恢复流程的问题。
- 修复了4k卡训练任务在500+step后随机step位置概率性出现的通信超时问题。
- 修复了PD分离场景，decode频繁挂掉重启导致的refill积压问题。
- 修复了开源仓客户自定义算子和内置算子IR原型重名不生效的问题。
- 修复了aclnnAddmv算子压测偶现coredump的问题。
- 修复了万卡任务拉起报错的问题。
- 修复了aclgraph场景特定shape下MatMulV3性能比MatMulV2差的问题。
- 修复了fused_quant_mat_mul场景存在的精度问题。
- 修复了BatchMatmulV2在特定bias场景下存在的精度问题。
- 修复了FAG算子短序列GQA、NoMask场景存在的精度问题。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/900/maintenref/refdoc/refer002.html)。

## 子包独立升级

### 使用场景

子包独立升级提供了灵活的按需升级功能。

使用场景举例：某用户已安装了a.b.c版本的组合包Ascend-cann-toolkit和Ascend-cann-ops，由于业务需要，要求将单边通信库能力更新至x.y.z版本，此时，可通过独立升级子包cann-hixl来实现。其中a.b.c和x.y.z请替换为实际版本号。

### 操作步骤

升级子包前，请确保已安装配套版本的组合包Ascend-cann-toolkit和Ascend-cann-ops。如未安装，请参考《[CANN 软件安装](https://hiascend.com/document/redirect/CannCommunityInstSoftware)》进行安装。

子包的升级路径应与组合包的安装路径保持一致。所有子包的升级操作相同，以下以升级 cann-hixl\_x.y.z\_linux-aarch64.run 为例进行说明。

**升级场景一：**

**组合包**Ascend-cann-toolkit和Ascend-cann-ops**安装在默认路径下**（即安装时未使用“--install-path”参数）

```bash
chmod +x cann-hixl_x.y.z_linux-aarch64.run 
./cann-hixl_x.y.z_linux-aarch64.run --upgrade
```

**升级场景二：**

**组合包**Ascend-cann-toolkit和Ascend-cann-ops**安装在指定路径**“/home/custom\_path”（即安装时指定“--install-path=/home/custom\_path”）

```bash
chmod +x cann-hixl_x.y.z_linux-aarch64.run
./cann-hixl_x.y.z_linux-aarch64.run --upgrade --install-path=/home/custom_path
```
