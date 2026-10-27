# CANN 9.1.0版本说明

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
    <td>9.1.0</td>
    <td><a href="https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C18%2CAArch64%2Conline_Yum">26.0.RC1</a></td>
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
    <col style="width: 150px">
  </colgroup>
  <thead>
    <tr>
      <th rowspan="3">CANN</th>
      <th colspan="5">驱动版本（Ascend HDK）</th>
    </tr>
    <tr>
      <th>25.0.X</th>
      <th>25.2.X</th>
      <th>25.3.X</th>
      <th>25.5.X</th>
      <th>26.0.RC1/25.7.RC1</th>
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
    </tr>
    <tr>
      <td>9.0.X</td>
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
    </tr>
  </tbody>
</table>

## CANN软件包内部配套关系

### CANN组合配套关系

CANN 9.1.0包含Toolkit包、算子包（ops）、加速库（NNAL）3个组合包，CANN组合包与子包的配套关系如下。其中6个子包支持独立升级，用户可根据需求灵活安装。

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
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">算子包（ops）</td>
      <td>cann-dvpp</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.1.0</td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">加速库（NNAL）</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.1.0">9.1.0</a></td>
      <td>arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops与Toolkit配套关系
CANN ops包已与Toolkit解耦，支持独立升级，用户可根据使用需求灵活安装。

|ops版本  |配套toolkit版本  |
|--|--|
| [ascend-cann-ops 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |


### CANN ops组合包内可独立升级子包配套关系

| CANN子包版本                                                 | 版本源码标签                                                 | 配套CANN版本                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-math/tags/v9.1.0)      | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-nn 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-nn/tags/v9.1.0)        | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-cv 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-cv/tags/v9.1.0)        | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-transformer 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-transformer/tags/v9.1.0) | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hccl 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/hccl/tags/v9.1.0)          | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hixl 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/hixl/tags/v9.1.0)          | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |

子包独立升级的具体操作请参考[子包独立升级](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/softwareinst/instg/instg_0030.html)。

## 关键特性

- **新增支持<term>Ascend 950DT</term>产品，在训练和Decode推理场景下，提供更高带宽能力。**

- **基于Atlas A2 系列产品、Atlas A3 系列产品和<term>Ascend 950 系列产品</term>，新增核心算子SMLA、mHC等，支持DeepSeekV4、Qwen3.6、Kimi-K2.6、GLM5.2等多个开源模型适配。**

- **算子开发场景资料上线，提供入门、进阶、深度创新多路径参考资料。[点击查看详情](https://www.hiascend.com/cn/developer/operator?tab=ascendc)**

- **基于<term>Ascend 950 系列产品</term>，SHMEM首发支持AICore直驱MTE/UDMA/RDMA，开启UB和RoCE通信，并配套提供编程接口。[点击查看详情](https://gitcode.com/cann/shmem/blob/master/README.md)**

- **基于<term>Ascend 950 系列产品</term>，CATLASS新增支持Tile组件，提供丰富的MxFP8/MxFP4量化模板及样例库。[点击查看详情](https://gitcode.com/cann/catlass/blob/master/README.md)**

- **算子精度标准开源，通过混合容差指标实现浮点计算类算子的精度判定。[点击查看详情](https://gitcode.com/cann/opbase/blob/9.1.0/docs/zh/ops_precision_standard/experimental_standard.md)**

## 新增特性

### 公共模块

- CPU性能调优：
  - Toolkit新增mindstudio-boost子包，面向HostBound业务场景，支持对关键线程自动化绑核与资源隔离，实现性能调优([!1](https://gitcode.com/Ascend/msboost/pull/1))。
- CANN适配不同昇腾硬件产品，新增OS兼容性支持：
  - Atlas 350 加速卡适配Tlinux 3.3、Tlinux 4.4、Anolis OS 8.9。
  - Atlas 950 SuperPoD、Atlas 850/850E 适配 openEuler 24.03 lts sp4。
- CANN支持Python 3.14.*版本，支持CANN在高版本Python下运行。
- 提供query_pkg_version.sh软件版本信息查询脚本，一键查询各组件的版本信息。

### 算子库

#### ops-math库

- <term>Ascend 950PR/Ascend 950DT</term>适配与场景支持：
  - 新增适配以下算子
    - Diag（[!2185](https://gitcode.com/cann/ops-math/pull/2185)）。
    - Asin（[!2216](https://gitcode.com/cann/ops-math/pull/2216)）。
    - PadV2（[!1562](https://gitcode.com/cann/ops-math/pull/1562)）。
    - Cross（[!2232](https://gitcode.com/cann/ops-math/pull/2232)）。
    - AngleV2（[!2674](https://gitcode.com/cann/ops-math/pull/2674)）。
    - CdistGrad（[!2981](https://gitcode.com/cann/ops-math/pull/2981)）。
    - ReduceLogSum（[!2628](https://gitcode.com/cann/ops-math/pull/2628)）。
    - Complex（[!3742](https://gitcode.com/cann/ops-math/pull/3742)）。
    - AmpUpdateScale（[!3224](https://gitcode.com/cann/ops-math/pull/3224)）。
    - ReduceNansum（[!3153](https://gitcode.com/cann/ops-math/pull/3153)）。
    - Polar（[!2827](https://gitcode.com/cann/ops-math/pull/2827)）。
    - Atan2（[!2315](https://gitcode.com/cann/ops-math/pull/2315)）。
    - LogAddExp（[!3150](https://gitcode.com/cann/ops-math/pull/3150)）。
  - 算子新增特性支持
    - BitwiseOr/BitwiseXor支持整型数据类型（[!2384](https://gitcode.com/cann/ops-math/pull/2384)）。
    - AddN算子支持aclnn接口调用（[!2720](https://gitcode.com/cann/ops-math/pull/2720) [!3587](https://gitcode.com/cann/ops-math/pull/3587)）。
    - cholesky算子支持大尾轴场景输入（[!2255](https://gitcode.com/cann/ops-math/pull/2255)）。
    - ReduceSum算子支持bool输入（[!3014](https://gitcode.com/cann/ops-math/pull/3014)）。

- 性能优化：
  - Sort算子小轴场景排序性能优化([!2985](https://gitcode.com/cann/ops-math/pull/2985))。
  - 随机数算子生成性能优化([!3590](https://gitcode.com/cann/ops-math/pull/3590))。
  - TopkV2算子性能优化，提升int64索引场景计算效率([!2564](https://gitcode.com/cann/ops-math/pull/2564))。
  - TopK算子长序列场景显存、性能优化（[!3183](https://gitcode.com/cann/ops-math/pull/3183)）。
  - AICPU算子性能优化，覆盖ClipByValueV2([!2460](https://gitcode.com/cann/ops-math/pull/2460))、ConcatV2([!2395](https://gitcode.com/cann/ops-math/pull/2395))、CumSum([!2262](https://gitcode.com/cann/ops-math/pull/2262))。

- 算子接口迁移变更：
  - aclnnMatmulCompressDequant 及其对应的kernel文件由math仓迁移至nn仓([!2728](https://gitcode.com/cann/ops-math/pull/2728))。<br>

#### ops-cv库
- <term>Ascend 950PR/Ascend 950DT</term>新增适配以下算子：<br>
  - 新增适配以下算子：<br>
    - GridSampler2DGrad算子([!847](https://gitcode.com/cann/ops-cv/pull/847))。<br>
    - UpsampleNearestExact2d/3d算子([!851](https://gitcode.com/cann/ops-cv/pull/851))。<br>
    - UpsampleNearestExactGrad算子([!798](https://gitcode.com/cann/ops-cv/pull/798))。<br>
    - UpsampleTrilinear3d算子([!927](https://gitcode.com/cann/ops-cv/pull/927))。<br>
    - CIoU算子([!833](https://gitcode.com/cann/ops-cv/pull/833))。<br>
    - BlendFaceBgPartTwo算子([!825](https://gitcode.com/cann/ops-cv/pull/825))。<br>
    - SpatialTransformer算子([!698](https://gitcode.com/cann/ops-cv/pull/698))。<br>
    - adjust_saturation算子([!696](https://gitcode.com/cann/ops-cv/pull/696))。<br>
    - scaleandtranslate算子([!693](https://gitcode.com/cann/ops-cv/pull/693))。<br>
    - BoundingBoxEncode算子([!1049](https://gitcode.com/cann/ops-cv/pull/1049))。<br>
    - NMSWithMask算子([!560](https://gitcode.com/cann/ops-cv/pull/560))。<br>
    - ExtractGlimpseV2、UpsampleBicubic2d算子([!1039](https://gitcode.com/cann/ops-cv/pull/1039))。<br>
    - UpsampleNearestExact1d及系列反向算子([!830](https://gitcode.com/cann/ops-cv/pull/830) [!798](https://gitcode.com/cann/ops-cv/pull/798))。<br>
  - 算子新增特性支持：<br>
    - AIPP新增CSC色域转换能力，支持YUV420SP/U8、RGB888/U8、BGR888/U8、XRGB8888/U8等多种格式之间的色域转换([!765](https://gitcode.com/cann/ops-cv/pull/765))，并新增动态AIPP通路支持[!802](https://gitcode.com/cann/ops-cv/pull/802)）。<br>
    - GridSample2D算子新增BF16数据类型支持([!715](https://gitcode.com/cann/ops-cv/pull/715) [!751](https://gitcode.com/cann/ops-cv/pull/751))。<br>
- 性能优化：<br>
    - ResizeNearestNeighborV2算子NCHW格式性能优化([!822](https://gitcode.com/cann/ops-cv/pull/822))。<br>
    - GridSamplerGrad算子性能优化([!946](https://gitcode.com/cann/ops-cv/pull/946))。<br>

#### opbase库
- 新增特性：<br>
  - 支持float8/float6/float4数据类型及资料([!298](https://gitcode.com/cann/opbase/pull/298)、[!479](https://gitcode.com/cann/opbase/pull/479)、[!486](https://gitcode.com/cann/opbase/pull/486))。<br>
  - reduce模板支持混合精度([!255](https://gitcode.com/cann/opbase/pull/255))。<br>
  - 新增非连续输入算子静态支持([!346](https://gitcode.com/cann/opbase/pull/346)、[!353](https://gitcode.com/cann/opbase/pull/353))。<br>
  - 日志接口DFX能力增强，支持日志输出标准化([!350](https://gitcode.com/cann/opbase/pull/350)、[!448](https://gitcode.com/cann/opbase/pull/448)、[!513](https://gitcode.com/cann/opbase/pull/513)、[!299](https://gitcode.com/cann/opbase/pull/299))。<br>
- 性能优化：<br>
  - broadcast非连续tensor性能优化([!317](https://gitcode.com/cann/opbase/pull/317))。<br>
  - 优化build.sh增量编译性能，复用CMake缓存避免重复配置([!391](https://gitcode.com/cann/opbase/pull/391))。<br>

#### ops-nn库
- 卷积算子功能性能优化，优化多模态网络性能，内存占用不劣化([!735](https://gitcode.com/cann/ops-nn/pull/735))：<br>
  - dX支持超大W输入场景对W切分。<br>
  - dW支持确定性场景下开启性能优化特性。<br>
  - dX支持stride=kernel和fmap=kernel场景转MM，优化性能。<br>
- <term>Ascend 950PR/Ascend 950DT</term>新场景支持：<br>
  - 引入ops-tensor，基于分层结构优化Cube类算子，减少偏移量计算和代码重复率([!5036](https://gitcode.com/cann/ops-nn/pull/5036))。<br>
  - 完善低bit类算子，支持精度补偿，优化整网精度RmsNormDynamicMxQuant([!2894](https://gitcode.com/cann/ops-nn/pull/2894))，DynamicBlockMxQuant([!1824](https://gitcode.com/cann/ops-nn/pull/1824))，DualLevelQuantBatchMatmul([!1141](https://gitcode.com/cann/ops-nn/pull/1141))。<br>
  - HardswishBackwardV2([!4817](https://gitcode.com/cann/ops-nn/pull/4817))、SyncBatchNormGatherStatsWithCounts([!5973](https://gitcode.com/cann/ops-nn/pull/5973))。
- nn仓工程优化：<br>
  - <term>Ascend 950PR/Ascend 950DT</term>支持静态库([!3623](https://gitcode.com/cann/ops-nn/pull/3623))。<br>
  - kernel配置脚本优化([!3330](https://gitcode.com/cann/ops-nn/pull/3330))。
- Atlas A2系列产品和Atlas A3系列产品的Cube类算子能力增强，优化网络性能并减少部分场景的内存占用：<br>
  - aclnnMatmulWeightNz性能优化([!5444](https://gitcode.com/cann/ops-nn/pull/5444))([!5105](https://gitcode.com/cann/ops-nn/pull/5105))。<br>
  - aclnnTransposeBatchMatmul放开B*K < 65536的限制([!4240](https://gitcode.com/cann/ops-nn/pull/4240))。<br>
  - aclnnBatchMatmul FP32数据类型下大Batch小MKN场景性能优化([!6103](https://gitcode.com/cann/ops-nn/pull/6103))([!7264](https://gitcode.com/cann/ops-nn/pull/7264))。<br>
  - Cube类算子支持配置out_dtype([!4823](https://gitcode.com/cann/ops-nn/pull/4823))([!5481](https://gitcode.com/cann/ops-nn/pull/5481))([!5602](https://gitcode.com/cann/ops-nn/pull/5602))。<br>
  - Cube类算子内存占用优化([!5356](https://gitcode.com/cann/ops-nn/pull/5356))([!5864](https://gitcode.com/cann/ops-nn/pull/5864))。<br>
- 算子接口迁移变更：
  - aclnnMatmulCompressDequant 及其对应的kernel文件由math仓迁移至nn仓([!4166](https://gitcode.com/cann/ops-nn/pull/4166))。<br>

#### ops-transformer库

**注意力（Attention/MLA）类**
- 新增SparseFlashMla（稀疏FlashMLA）算子，并支持稀疏注意力KV合并，提升长序列稀疏注意力场景的计算与访存效率([!6526](https://gitcode.com/cann/ops-transformer/pull/6526)、[!6429](https://gitcode.com/cann/ops-transformer/pull/6429))。
- 新增LightningIndexerV2算子([!5635](https://gitcode.com/cann/ops-transformer/pull/5635))。
- 新增aclnnBlockSparseAttentionV2接口，适配FP8量化的BlockSparseAttention算子；BlockSparseAttention在A5上支持FP8场景性能改进与BSND输入排布，<term>Ascend 950PR/Ascend 950DT</term>正向/推理的量化与非量化kernel支持LSE输出，并新增BlockSparseAttentionGrad反向算子([!4820](https://gitcode.com/cann/ops-transformer/pull/4820)、[!6620](https://gitcode.com/cann/ops-transformer/pull/6620)、[!6264](https://gitcode.com/cann/ops-transformer/pull/6264)、[!6565](https://gitcode.com/cann/ops-transformer/pull/6565)、[!6186](https://gitcode.com/cann/ops-transformer/pull/6186))。
- FusedInferAttentionScore支持LSE输出，AttentionUpdate在A2/A3支持sp128([!5505](https://gitcode.com/cann/ops-transformer/pull/5505)、[!5709](https://gitcode.com/cann/ops-transformer/pull/5709))。
- ScatterPaKvCache/GatherPaKvCache新增cache首轴非连续tensor支持，MlaProlog支持KVCache非连续输入([!6214](https://gitcode.com/cann/ops-transformer/pull/6214)、[!6442](https://gitcode.com/cann/ops-transformer/pull/6442))。
- RecurrentGatedDeltaRule支持state前两轴非连续，SMLAG新增torch适配及新特性支持([!6288](https://gitcode.com/cann/ops-transformer/pull/6288)、[!5916](https://gitcode.com/cann/ops-transformer/pull/5916))。

**MoE类**
- MoeInitRoutingV3非量化场景支持DropPad，UnpermuteWithRoutingMap新增N规格non-topk支持([!5826](https://gitcode.com/cann/ops-transformer/pull/5826)、[!5353](https://gitcode.com/cann/ops-transformer/pull/5353))。
- MegaMoe新增A2/A3 Tiling、静态tensor及syncfunc功能，并补充A2/A3 kernel([!6574](https://gitcode.com/cann/ops-transformer/pull/6574)、[!3608](https://gitcode.com/cann/ops-transformer/pull/3608))。

**GMM（GroupedMatmul）量化类**
- GroupedMatmulFinalizeRouting在A5上新增W8A8场景的确定性支持([!6289](https://gitcode.com/cann/ops-transformer/pull/6289))。
- GroupedMatmulSwigluQuantV2新增WeightNz MxA8W4数据流及MXFP4权重NZ格式支持([!5267](https://gitcode.com/cann/ops-transformer/pull/5267)、[!5419](https://gitcode.com/cann/ops-transformer/pull/5419)、[!5272](https://gitcode.com/cann/ops-transformer/pull/5272))。
- GMM和GMMAdd GlistType规格增强([!4844](https://gitcode.com/cann/ops-transformer/pull/4844)、[!3725](https://gitcode.com/cann/ops-transformer/pull/3725))。

**MC2（通信-计算融合）类**
- 新增AllToAllMatmulV2算子([!6062](https://gitcode.com/cann/ops-transformer/pull/6062))。
- AllGatherMatmulV2、AllToAllVGroupedMatmul/GroupedMatmulAllToAllV增加comm_mode通信引擎参数，支持选择通信引擎([!5340](https://gitcode.com/cann/ops-transformer/pull/5340)、[!6103](https://gitcode.com/cann/ops-transformer/pull/6103))。
- MatmulReduceScatterV2适配AICPU通信([!5515](https://gitcode.com/cann/ops-transformer/pull/5515))。

**Mhc类**
针对Atlas A2系列产品和Atlas A3系列产品新增支持以下算子：
- MhcPost算子([!3670](https://gitcode.com/cann/ops-transformer/pull/3670))。
- MhcPostBackward算子([!4377](https://gitcode.com/cann/ops-transformer/pull/4377))。
- MhcPreSinkhorn算子([!5033](https://gitcode.com/cann/ops-transformer/pull/5033))。
- MhcPreSinkhornBackward算子([!4760](https://gitcode.com/cann/ops-transformer/pull/4760))。

### 通信库

#### 集合通信
- Ascend 950PR支持CCU场景的allGatherV/reduceScatterV算子([!303](https://gitcode.com/cann/hccl/pull/303) [!207](https://gitcode.com/cann/hccl/pull/207))。
- Ascend 950PR支持GE图模式&aclGraph模式下的通信算子入图([!183](https://gitcode.com/cann/hccl/pull/183) [!164](https://gitcode.com/cann/hccl/pull/164) [!296](https://gitcode.com/cann/hccl/pull/296))。
- Ascend 950PR支持N秒快恢能力，提升集合通信运行可靠性([!1126](https://gitcode.com/cann/hcomm/pull/1126) [!1609](https://gitcode.com/cann/hcomm/pull/1609) [!421](https://gitcode.com/cann/hccl/pull/421))。
- Ascend 950PR支持taskexception&profiling等维测能力，提升问题定位易用性([!937](https://gitcode.com/cann/hcomm/pull/937) [!1472](https://gitcode.com/cann/hcomm/pull/1472) [!267](https://gitcode.com/cann/hccl/pull/267) [!332](https://gitcode.com/cann/hccl/pull/332))。
- Ascend 950PR上，HcclChannelAcquire接口支持AIV直驱RoCE和URMA能力，支撑通算融合算子的自定义开发([!2032](https://gitcode.com/cann/hcomm/pull/2032))。
- Atlas A2/A3系列产品上，单卡多进程能力新增支持MC2场景([!1880](https://gitcode.com/cann/hcomm/pull/1880))。
- Atlas A2/A3系列产品上，aclGraph场景下资源管理优化，支撑通信资源增量刷新([!2405](https://gitcode.com/cann/hcomm/pull/2405) [!2502](https://gitcode.com/cann/hcomm/pull/2502))。
- Atlas A2/A3系列产品上，跨超节点场景性能优化，ReduceScatter/AllGather算子支持跨超pipeline算法([!2071](https://gitcode.com/cann/hcomm/pull/2071) [!1931](https://gitcode.com/cann/hcomm/pull/1931))。
- Atlas A2/A3系列产品上新增支持双机背靠背RoCE直连机型通信([!2642](https://gitcode.com/cann/hcomm/pull/2642) [!3433](https://gitcode.com/cann/hcomm/pull/3433))。
- Atlas 350 加速卡支持跨PCIE SW进行通信([!1799](https://gitcode.com/cann/hcomm/pull/1799) [!707](https://gitcode.com/cann/hccl/pull/707))，AllReduce、ReduceScatter、AllGather、Reduce、Scatter、Alltoall、Alltoallv、Send、Recv等算子支持通信。

#### 单边通信
- HIXL 底层通信接口开放：构建 Client-Server 模式单边通信能力，全面提升建链规格与建链性能。针对批量小 Buffer 传输场景深度优化，有效降低片上内存占用与通信资源开销（[!138](https://gitcode.com/cann/hixl/issues/138)）。
- HIXL 网络传输协议扩展：单边通信新增 UBC、UBoE、Host RoCE 协议支持，完整覆盖 D2D、D2rH、rH2D、H2H 全场景数据传输（[!37](https://gitcode.com/cann/hixl/issues/37)），不同产品形态的协议支持清单可查阅[HIXL](https://gitcode.com/cann/hixl)社区。
- HIXL 智能链路管理升级：实现通信资源自动获取及智能路由选择（[!181](https://gitcode.com/cann/hixl/issues/181)），支持按需建链（[!245](https://gitcode.com/cann/hixl/issues/245)），简化使用流程，提升易用性。
- HIXL 编程 API 能力增强：扩展异步链路管理（[!207](https://gitcode.com/cann/hixl/issues/207)）、传输状态批量查询（[!208](https://gitcode.com/cann/hixl/issues/208)）两类接口，丰富异步编程范式，提升上层业务开发效率。

### 图引擎
- 支持Ascend 950DT形态图引擎能力恢复。
- ge.autoMultistreamParallelMode新增MainStream和LoadBalance选项，基于最小路径覆盖算法将静态Shape模型的计算节点自动划分至最少逻辑流，实现多流并行加速。
- 新增PortableOp算子类型，面向离线推理场景提供自定义算子的序列化与反序列化能力。
- ATC和aclgrph接口支持集群配置文件路径设置，用于生成含有HCCL通信任务的离线OM模型，满足多卡离线推理场景下的通信域配置需求。

### 领域加速库

#### Ascend Transformer Boost加速库

- **在Ascend 950PR/Ascend 950DT上接入核心算子**
  批量落地GELU、LayerNorm、MatmulEinSum、RmsNormQuant、SwiGluQuant（ACLNN V2）、Linear反量化，以及支持AllGather/AllReduce/ReduceScatter等通信算子（[!1994](https://gitcode.com/cann/ascend-transformer-boost/pull/1994) 、[!2089](https://gitcode.com/cann/ascend-transformer-boost/pull/2089) 、[!2090](https://gitcode.com/cann/ascend-transformer-boost/pull/2090) 、[!2060](https://gitcode.com/cann/ascend-transformer-boost/pull/2060) 、[!2097](https://gitcode.com/cann/ascend-transformer-boost/pull/2097) 、[!2103](https://gitcode.com/cann/ascend-transformer-boost/pull/2103) 、[!2091](https://gitcode.com/cann/ascend-transformer-boost/pull/2091)）。

- **Attention/KV Cache推理增强**
  - Paged Attention在<term>Ascend 950 系列产品</term>上升级FusedInferAttention V5（[!2069](https://gitcode.com/cann/ascend-transformer-boost/pull/2069)）。
  - Paged Attention / Flash Attention新增NORM_COMPRESS掩码[!2114](https://gitcode.com/cann/ascend-transformer-boost/pull/2114) 、[!2116](https://gitcode.com/cann/ascend-transformer-boost/pull/2116)、[!2078](https://gitcode.com/cann/ascend-transformer-boost/pull/2078)）。
  - MLA decode支持SWA滑动窗口。
  - ReshapeAndCache在<term>Ascend 950 系列产品</term>上支持单入单出（[!2065](https://gitcode.com/cann/ascend-transformer-boost/pull/2065)）。

- **torch_atb 独立编译与 ABI 体系**
  - torch_atb从主库解耦独立编译，默认出包ABI切换cxx_abi_1（[!2021](https://gitcode.com/cann/ascend-transformer-boost/pull/2021) ）。
  - wheel命名规范、安装脚本自动检测/安装torch，安装部署链路打通（[!2086](https://gitcode.com/cann/ascend-transformer-boost/pull/2086) 、[!2118](https://gitcode.com/cann/ascend-transformer-boost/pull/2118)）。

#### Ascend Signal Processing Boost加速库
- 在<term>Ascend 950PR/Ascend 950DT</term>上新增适配以下算子：
  - FFT 1D C2C算子（[!69](https://gitcode.com/cann/sip/pull/69)）。
  - FFT 1D C2R算子（[!73](https://gitcode.com/cann/sip/pull/73)）。
  - FFT 1D R2C算子（[!73](https://gitcode.com/cann/sip/pull/73)）。
  - Hadamard算子（[!76](https://gitcode.com/cann/sip/pull/76)）。

### 运行时

支持Ascend 950DT的AclGraph场景stream规格扩充，解决大模型资源不足等问题([!2976](https://gitcode.com/cann/runtime/pull/2976))。

###  算子编程

#### 关键特性

- 维测能力：
  - Ascend C框架基础API支持NPU Check（[!1557](https://gitcode.com/cann/asc-devkit/pull/1557) 、[!1467](https://gitcode.com/cann/asc-devkit/pull/1467)），增强算子运行时校验能力。
  - SIMD VF内支持printf和reg dump打印（[!1605](https://gitcode.com/cann/asc-devkit/pull/1605)），提供调试打印和寄存器数据dump能力。
  - <term>Ascend 950PR/Ascend 950DT</term>支持L1 Tensor数据的DumpTensor（[!2175](https://gitcode.com/cann/asc-devkit/pull/2175)），扩展L1层数据调试支持。
  - 新增optype_collector工具，支持检查optype重名（[!285](https://gitcode.com/cann/asc-tools/pull/285)）。
- 编译工程
  - 编译工程CMakeModule支持CMAKE_\<LANG\>编译选项（[!2055](https://gitcode.com/cann/asc-devkit/pull/2055)）。
- 基础API
  - 支持设置ctrl寄存器的饱和溢出管理（[!2077](https://gitcode.com/cann/asc-devkit/pull/2077)）。
- SIMT编程
  - 新增ld/st接口（[!2058](https://gitcode.com/cann/asc-devkit/pull/2058)）和AddrSpace类接口（[!1597](https://gitcode.com/cann/asc-devkit/pull/1597)），丰富SIMT内存访问编程能力。

#### 样例更新

- SIMD样例：
  - 新增最佳实践样例：matmul+gelu融合、datacopy优化、bank冲突优化、group_matmul量化组矩阵乘、simt&simd高性能编程（[!1814](https://gitcode.com/cann/asc-devkit/pull/1814) 、[!2137](https://gitcode.com/cann/asc-devkit/pull/2137) 、[!2141](https://gitcode.com/cann/asc-devkit/pull/2141)、 [!2166](https://gitcode.com/cann/asc-devkit/pull/2166) 、[!2363](https://gitcode.com/cann/asc-devkit/pull/2363)）。
  - 新增<term>Ascend 950PR/Ascend 950DT</term>新特性样例及兼容性样例整改：loopmode数据搬运、interleave矢量计算、datacopy_gm2l1、loadmx（Load2DMX）、mmad_mx、data_copy_pad等（[!2336](https://gitcode.com/cann/asc-devkit/pull/2336) 、[!1899](https://gitcode.com/cann/asc-devkit/pull/1899) 、[!2124](https://gitcode.com/cann/asc-devkit/pull/2124)）。
  - 新增RegBase基础样例：基础算术、数据类型转换、归约、比较、索引等样例（[!1459](https://gitcode.com/cann/asc-devkit/pull/1459) 、[!1575](https://gitcode.com/cann/asc-devkit/pull/1575) 、[!2024](https://gitcode.com/cann/asc-devkit/pull/2024)）。
  - 新增SIMD VF print样例和dump样例（[!2558](https://gitcode.com/cann/asc-devkit/pull/2558)）。
  - 新增Tensor API入门及最佳实践样例：Matmul入门、数据搬入搬出、搬出随路量化、MX FP4最佳实践（[!2553](https://gitcode.com/cann/asc-devkit/pull/2553)）。
- SIMT样例：
  - 新增SIMT优化特性样例：DCache访问优化样例（[!2453](https://gitcode.com/cann/asc-devkit/pull/2453)）、基于transpose的仿存合并和bank冲突样例（[!1753](https://gitcode.com/cann/asc-devkit/pull/1753)）、最佳实践样例：通过类型对齐提升搬运效率（[!2297](https://gitcode.com/cann/asc-devkit/pull/2297)）。
  - 新增SIMT功能特性样例：pytorch注册自定义算子（[!2769](https://gitcode.com/cann/asc-devkit/pull/2769)）、编译相关样例（动态、静态、分离编译等）（[!2356](https://gitcode.com/cann/asc-devkit/pull/2356)）、profiling样例（[!1989](https://gitcode.com/cann/asc-devkit/pull/1989)）、内存屏障特性样例（[!1923](https://gitcode.com/cann/asc-devkit/pull/1923)）、Warp类特性样例（[!2876](https://gitcode.com/cann/asc-devkit/pull/2876)）、simulator样例（[!2692](https://gitcode.com/cann/asc-devkit/pull/2692)）、kernel log样例（[!2131](https://gitcode.com/cann/asc-devkit/pull/2131)）。

### PTO虚拟指令集

- 基础Vector&Cube指令：
  - 支持Vector类指令的高精度版本（[!896](https://gitcode.com/cann/pto-isa/pull/896)、[!782](https://gitcode.com/cann/pto-isa/pull/782), [!815](https://gitcode.com/cann/pto-isa/pull/815)、[!717](https://gitcode.com/cann/pto-isa/pull/717)、[!648](https://gitcode.com/cann/pto-isa/pull/648)、[!695](https://gitcode.com/cann/pto-isa/pull/695)）。
  - 新增transdata场景支持（[!950](https://gitcode.com/cann/pto-isa/pull/950)、[!977](https://gitcode.com/cann/pto-isa/pull/977)）。
  - TSTORE、TLOAD支持卷积3D（[!904](https://gitcode.com/cann/pto-isa/pull/904)、[!912](https://gitcode.com/cann/pto-isa/pull/912)）。
  - 新增MGATHER/MSCATTER指令（[!935](https://gitcode.com/cann/pto-isa/pull/935)、[!1136](https://gitcode.com/cann/pto-isa/pull/1136)、[!309](https://gitcode.com/cann/pto-isa/pull/309)、[!889](https://gitcode.com/cann/pto-isa/pull/889)）。
  - Reduce类指令支持返回值及对应索引（[!1124](https://gitcode.com/cann/pto-isa/pull/1124)、[!928](https://gitcode.com/cann/pto-isa/pull/928)）。
  - TQUANT支持MXFP8/MXFP4量化（[!1187](https://gitcode.com/cann/pto-isa/pull/1187)、[!1143](https://gitcode.com/cann/pto-isa/pull/1143)）。
  - 合轴类指令支持类型增强，TMOV/TEXTRACT/TINSERT支持Vec到Vec（[!1196](https://gitcode.com/cann/pto-isa/pull/1196)）。

- 通信类指令：
  - 新增<term>Ascend 950 系列产品</term>的CCU异步通信类指令TGATHER、TBROADCAST、TSCATTER、TREDUCE（[!915](https://gitcode.com/cann/pto-isa/pull/915)）。
  - 支持全核同步指令SYNCALL（[!907](https://gitcode.com/cann/pto-isa/pull/907)）。
  - 新增异步prefetch指令（[!116](https://gitcode.com/cann/pto-isa/pull/116)）。
  - TPUT_ASYNC、TGET_ASYNC增加A5基于URMA的异步通信能力（[!991](https://gitcode.com/cann/pto-isa/pull/991)）。

- CostModel仿真：
  - 在Atlas A2 系列产品和Atlas A3 系列产品上新增算子级Costmodel，支持输出算子性能、Pipeline时间、泳道图等信息（[!1004](https://gitcode.com/cann/pto-isa/pull/1004)）。
  - 接入CCE Mock方案，支持A2A3已有指令性能预测（[!772](https://gitcode.com/cann/pto-isa/pull/772)）。

- CPU-SIM：随NPU同步新增CPU仿真指令。

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

- **不兼容变更**：控制类算子Identity、IdentityN、Rank、Shape和ShapeN从ops-nn迁移至ops-math。这些算子从`ops_proto_nn.h`和`es_nn`目录迁移到`ops_proto_math.h`和`es_math`目录，用户需更新相关头文件引用（[!2333](https://gitcode.com/cann/ops-math/pull/2333)、[!3995](https://gitcode.com/cann/ops-nn/pull/3995)）。

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
| aclnnGroupedMatMulAllReduce接口                              | 无可替换功能                                                 |
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

### 模型压缩工具

模型压缩工具以下特性在CANN 9.0.0标记为废弃，在当前版本已经删除。
- 非均匀量化。
- 自动混合精度。
- 近似校准。
- int4量化感知训练。
- amct_mindspore所有特性。


## 已知问题

问题现象：算子aclnnMatmulCompressDequant的输入参数deqScale的值为inf/-inf时，其精度详情中显示有inf或nan
【引入版本】CANN 8.5.0
【缺陷影响】测试特殊构造用例触发，非新算子引入，且实际量化场景下不会有deqScale为-inf和inf场景，当前版本影响可控
【规避方案】实际量化场景下不会有deqScale为-inf和inf场景

## 已修复问题

以下问题在9.1.0版本修复：

- 修复了QuantBatchMatmulV3算子在Atlas推理系列产品上，编译时指定AUTO_SYNC=false导致算子读写冲突的问题。
- 针对Atlas A2系列产品和Atlas A3系列产品，修复了MatmulReduceScatterV2算子在M小于512场景下，flag位清零过快导致其他卡检测不到，最终超时的问题。
- 修复了Atlas A2系列产品的大EP场景下，D节点注入片上内存多bit故障，无法进入快速恢复流程的问题。
- 修复了4k卡训练任务在500+step后，随机step位置概率性出现的通信超时问题。
- 修复了PD分离场景，decode频繁任务中断重启导致的refill积压问题。
- 修复了开源仓用户自定义算子和内置算子IR原型重名不生效的问题。
- 修复了aclnnAddmv算子压测偶现coredump的问题。
- 修复了万卡任务拉起时异常报错的问题。
- 修复了aclgraph场景特定shape下，MatMulV3性能比MatMulV2差的问题。
- 修复了fused_quant_mat_mul场景存在的精度问题。
- 修复了BatchMatmulV2在特定bias场景下存在的精度问题。
- 修复了FAG算子短序列GQA、NoMask场景存在的精度问题。

## 文档变更说明

### 编程指南

#### Ascend C算子开发

- 优化“入门教程”章节：
  - 更新Ascend C学习路径。
  - 新增异构系统和编程模型概括性描述。
- “编程指南”中SIMD编程模型章节进行优化调整，按照基于语言扩展层C API编程、基于Tensor的C++编程、基于Tpipe和TQue编程的维度进行分类。
- “编程指南”新增高级编程 > SuperKernel、高级编程 > SIMT协作组章节。
- 对《Ascend C API》进行了大规模重构，变更点如下：
  - 对数据搬运API和矩阵计算API等进行了目录结构调整：相关性强的API放置在临近位置，比如将矩阵计算相关的搬运接口放置在矩阵计算目录下。
  - 按照场景进行API的目录结构组织：比如矩阵计算分为矩阵计算的搬入、Mmad计算、矩阵计算的搬出。
  - 针对一类API增加必要的背景知识、概念原理介绍、通用的约束、关键特性等说明。
  - 针对每一个API补充约束说明、参数特殊值相关说明。
  - 新增API附录，附录中包含API流水类型汇总、理论性能汇总、接口边界值汇总等。
- 新增Tensor API参考文档。Tensor API接口为试验接口，在后续版本中可能会调整或改进，不保证后续兼容性。请开发者在使用过程中关注后续版本更新。
- 新增矩阵计算概述和计算分形介绍的文档（[!2533](https://gitcode.com/cann/asc-devkit/pull/2533)）。
- 优化矢量计算API文档，补充指令约束等（[!2676](https://gitcode.com/cann/asc-devkit/pull/2676)）。
- 增加SIMD与SIMT混合编程性能优化概述（[!2736](https://gitcode.com/cann/asc-devkit/pull/2736)）。
- 搭建VitePress文档站点，提供AscendC资料预览功能（[!2547](https://gitcode.com/cann/asc-devkit/pull/2547)）。

#### 通信算子开发

- 新增“编程模型与概念 > CCU编程模型与概念”章节。
- 新增“通信算子开发 > CCU算子开发”章节。
- 通信算子开发API新增以下接口。
  - 控制面接口 > CCU Kernel生命周期与内存Token管理。
  - 数据面接口 > CCU接口。

#### 图开发

新增以下章节：

- 自定义Pass开发 > 使用自定义Pass修改Graph > 基于Pattern匹配实现Pass（Python）。
- 编程指南 > SuperKernel融合范围标定。
- 自定义算子入图 > 自定义算子入图。

### API参考

#### GE图引擎 API

- 接口参考 > Python语言接口 > pyatc接口：新增Python场景的atc命令行工具。
- 图基础数据结构和接口 > options参数名说明 > ge.tiling_schedule_optimize：修改该参数级别，由原来global session级修改为all所有级别。

### 算子库

- 将历史版本中“算子库 > AI框架算子支持清单”章节独立出来，在当前版本新增《AI框架算子支持清单》手册。
- 新增“算子库 > 算子接口（torch_extension）”章节。
- “算子接口（aclnn）”新增RAS类接口章节。
- ops-cv库新增算子多平台迁移指南文档，指导开发者将算子从Atlas A2 系列产品迁移至Ascend 950PR/Ascend 950DT。

### 通信库

#### HCCL集合通信库

相关参考 > 通信算子支持度清单：新增“Ascend 950PR/Ascend 950 DT”支持度清单。

### 领域加速库

#### Ascend Transformer Boost加速库

- 新增测试框架指南，补充testframework编译运行依赖使用说明（[!2120](https://gitcode.com/cann/ascend-transformer-boost/pull/2120)）。
- 补充cxx_abi版本判断方法说明（[!2121](https://gitcode.com/cann/ascend-transformer-boost/pull/2121)）。
- 更新文档链接至CANN 9.1和PyTorch 26.0.0（[!2126](https://gitcode.com/cann/ascend-transformer-boost/pull/2126)）。
- 修正ATB_BUILD_DEPENDENCY_PATH及ABI判断说明，覆盖README/FAQ/测试框架指南（[!2136](https://gitcode.com/cann/ascend-transformer-boost/pull/2136)）。

### 开发工具

#### ATC离线模型编译工具

参数说明--framework：补充说明Caffe框架在当前形态已不再演进，转模型不保证可用性的说明。

#### AMCT模型压缩工具

新增“基于LLM的量化”章节。

## 漏洞修补列表

版本开源及第三方软件漏洞修复情况详见[漏洞修补列表](https://www.hiascend.com/document/detail/zh/CANNCommunityEdition/910/maintenref/refdoc/refer002.html)。
