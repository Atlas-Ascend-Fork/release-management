# CANN 9.1.0-beta.1版本说明

## 版本下载地址

<a href="https://www.hiascend.com/cann/download?versionId=750&ids=d806%2Ch0501%2Ch0601%2Ch0702&currentTab=0">快速安装地址</a>
## 版本配套

**1、CANN与Ascend HDK版本配套关系**

|CANN版本  |  配套Ascend HDK版本| 
|--|--|
| [CANN 9.1.0-beta.1](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0-beta.1) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1)<br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2) <br> [Ascend HDK 25.5.1](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1) |

**2、 CANN组合包版本配套关系**

|ops版本  |配套toolkit版本  |  
|--|--|
|[ascend-cann-ops 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/) | [ascend-cann-toolkit 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/)|

**3、 CANN独立升级子包版本配套关系**
| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| [cann-ops-math 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/) | [v9.1.0-beta.1](https://gitcode.com/cann/ops-math/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| [cann-ops-nn 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/) | [v9.1.0-beta.1](https://gitcode.com/cann/ops-nn/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| [cann-ops-cv 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/) | [v9.1.0-beta.1](https://gitcode.com/cann/ops-cv/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| [cann-ops-transformer 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/) | [v9.1.0-beta.1](https://gitcode.com/cann/ops-transformer/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| [cann-hccl 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/) | [v9.1.0-beta.1](https://gitcode.com/cann/hccl/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| [cann-hixl 9.1.0-beta.1](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0-beta.1/) | [v9.1.0-beta.1](https://gitcode.com/cann/hixl/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |

**4、CANN开源子包版本配套关系**

| CANN子包版本                       | 版本源码标签                                                 | 配套CANN版本      |
| ---------------------------------- | ------------------------------------------------------------ | ----------------- |
| cann-opbase 9.1.0-beta.1           | [v9.1.0-beta.1](https://gitcode.com/cann/opbase/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-oam-tools 9.1.0-beta.1        | [v9.1.0-beta.1](https://gitcode.com/cann/oam-tools/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-asc-tools 9.1.0-beta.1        | [v9.1.0-beta.1](https://gitcode.com/cann/asc-tools/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-asc-devkit 9.1.0-beta.1       | [v9.1.0-beta.1](https://gitcode.com/cann/asc-devkit/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-pto-isa 9.1.0-beta.1          | [v9.1.0-beta.1](https://gitcode.com/cann/pto-isa/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-ge-compiler 9.1.0-beta.1      | [v9.1.0-beta.1](https://gitcode.com/cann/ge/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-ge-executor 9.1.0-beta.1      | [v9.1.0-beta.1](https://gitcode.com/cann/ge/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-graph-autofusion 9.1.0-beta.1 | [v9.1.0-beta.1](https://gitcode.com/cann/graph-autofusion/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-metadef 9.1.0-beta.1          | [v9.1.0-beta.1](https://gitcode.com/cann/metadef/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-dflow-executor 9.1.0-beta.1   | [v9.1.0-beta.1](https://gitcode.com/cann/ge/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-hcomm 9.1.0-beta.1            | [v9.1.0-beta.1](https://gitcode.com/cann/hcomm/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |
| cann-npu-runtime 9.1.0-beta.1      | [v9.1.0-beta.1](https://gitcode.com/cann/runtime/tags/v9.1.0-beta.1) | CANN 9.1.0-beta.1 |

子包独立升级的具体操作请参考[子包独立升级](#子包独立升级)。

## 关键特性

### 推理Decode阶段性能优化：npugraph_ex新增支持SuperKernel融合
基于aclgraph路径，提供了SuperKernel算子融合技术，在已编译的二进制代码基础上融合创建一个超级Kernel函数（简称SuperKernel），以调用子函数的方式调用多个其它内核函数，达到缩减调度开销、优化计算任务的目的，可提升推理Decode阶段性能（[!346](https://gitcode.com/cann/opbase/pull/346) ）。

### aclgraph场景下算子性能提升：支持非连续静态算子执行
新增支持非连续输入的静态算子执行。开启开关后将存在非连续输入的动态算子落盘编译为静态算子后执行，该机制可以提升aclgraph场景下Superkernel算子执行效率（[!64](https://gitcode.com/cann/graph-autofusion/pull/64) [!99](https://gitcode.com/cann/graph-autofusion/pull/99)）。
     
## 新增特性

### 算子库

#### opbase库
 - 新增支持非连续输入的静态算子执行。开启开关后将存在非连续输入的动态算子落盘编译为静态算子后执行，该机制可以提升aclgraph场景下Superkernel算子执行效率[!346](https://gitcode.com/cann/opbase/pull/346)）。

### 图引擎
- 支持aclgraph场景下开启SuperKernel功能（[!346](https://gitcode.com/cann/opbase/pull/346) ）。

## 删除和废弃特性
不涉及。

## 已知问题
不涉及。

## 已修复问题
不涉及。

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