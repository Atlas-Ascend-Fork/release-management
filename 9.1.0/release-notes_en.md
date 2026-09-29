# CANN 9.1.0 Release Notes

<!-- md-trans-meta sourceCommit=unknown translatedAt=2026-08-19T01:52:56.678Z pushedAt=2026-08-19T09:00:39.420Z -->

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
    <td>9.1.0</td>
    <td><a href="https://www.hiascend.com/hardware/firmware-drivers?ids=d803%2C89dda9ba9de741349efa03687a487678%2C18%2CAArch64%2Conline_Yum">26.0.RC1</a></td>
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
      <th>26.1.0</th>
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

CANN 9.1.0 contains three combination packages: Toolkit, ops (the operator package), and NNAL (the acceleration library). The compatibility between the CANN combination packages and their subpackages is as follows. Six of the subpackages support independent upgrade, allowing users to install them flexibly based on their needs.

<table>
  <thead>
    <tr>
      <th>Package</th>
      <th>Subpackage</th>
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
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">ops</td>
      <td>cann-dvpp</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.1.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">NNAL</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.1.0">9.1.0</a></td>
      <td>Arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops and Toolkit Compatibility

The CANN ops package has been decoupled from Toolkit and supports independent upgrade. You can install it as needed.

|ops Version  |Compatible Toolkit Version  |
|--|--|
| [ascend-cann-ops 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.1.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.1.0)<br> [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.0.0) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |

### Compatibility of Independently Upgradable Subpackages in the CANN ops Package

| CANN Subpackage Version                                      | Source Code Tag                                            | Compatible CANN Version                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------- |
| [cann-ops-math 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-math/tags/v9.1.0)      | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-nn 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-nn/tags/v9.1.0)        | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-cv 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-cv/tags/v9.1.0)        | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-transformer 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/ops-transformer/tags/v9.1.0) | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hccl 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/hccl/tags/v9.1.0)          | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hixl 9.1.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.1.0/) | [v9.1.0](https://gitcode.com/cann/hixl/tags/v9.1.0)          | CANN 9.1.0<br>CANN 9.0.0<br>CANN 8.5.2 |

For the specific operations of independent subpackage upgrade, see [Independent Subpackage Upgrade](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/910/softwareinst/instg/instg_0030.html).

## Key Features

- **<term>Ascend 950DT</term> now supported, providing higher bandwidth in training and decode inference tasks.**

- **For Atlas A2 products, Atlas A3 products, and <term>Ascend 950 products</term>, core operators such as SMLA and Mhc are added, with adaptation of multiple open-source models including DeepSeek V4, Qwen 3.6, Kimi-K2.6, and GLM5.2.**

- **Operator development documentation is now available from basics, advanced operations, to innovation. [View details](https://www.hiascend.com/en/developer/operator?tab=ascendc)**

- **For <term>Ascend 950 products</term>, SHMEM is the first to support AI Cores directly issuing MTE/UDMA/RDMA transfers, enabling UB and RoCE communication, with matching programming APIs provided. [View details](https://gitcode.com/cann/shmem/blob/master/README.md)**

- **For <term>Ascend 950 products</term>, CATLASS now supports the Tile components, providing MxFP8/MxFP4 quantization templates and a sample library. [View details](https://gitcode.com/cann/catlass/blob/master/README.md)**

- **The operator precision standard is open-sourced, implementing precision determination for floating-point computation operators through mixed tolerance metrics. [View details](https://gitcode.com/cann/opbase/blob/master/docs/en/ops_precision_standard/experimental_standard.md)**

## New Features

### Common Modules

- CPU performance tuning:

  - Toolkit adds the mindstudio-boost subpackage, which targets host-bound services and supports automatic core binding and resource isolation for key threads to tune performance ([!1](https://gitcode.com/Ascend/msboost/pull/1)).

- CANN adapts to different Ascend hardware products and adds OS compatibility support:

  - Atlas 350 accelerator cards adapt to Tlinux 3.3, Tlinux 4.4, and Anolis OS 8.9.

  - Atlas 950 SuperPoD and Atlas 850/850E adapt to openEuler 24.03 LTS SP4.

- CANN supports Python 3.14.* and supports running CANN on later Python versions.

- The new query_pkg_version.sh script allows you to query software version information of each component in one click.

### Operator Libraries

#### ops-math

- <term>Ascend 950PR/Ascend 950DT</term> adaptation and support:

  - Newly adapted operators

    - Diag ([!2185](https://gitcode.com/cann/ops-math/pull/2185))

    - Asin ([!2216](https://gitcode.com/cann/ops-math/pull/2216))

    - PadV2 ([!1562](https://gitcode.com/cann/ops-math/pull/1562))

    - Cross ([!2232](https://gitcode.com/cann/ops-math/pull/2232))

    - AngleV2 ([!2674](https://gitcode.com/cann/ops-math/pull/2674))

    - CdistGrad ([!2981](https://gitcode.com/cann/ops-math/pull/2981))

    - ReduceLogSum ([!2628](https://gitcode.com/cann/ops-math/pull/2628))

    - Complex ([!3742](https://gitcode.com/cann/ops-math/pull/3742))

    - AmpUpdateScale ([!3224](https://gitcode.com/cann/ops-math/pull/3224))

    - ReduceNansum ([!3153](https://gitcode.com/cann/ops-math/pull/3153))

    - Polar ([!2827](https://gitcode.com/cann/ops-math/pull/2827))

    - Atan2 ([!2315](https://gitcode.com/cann/ops-math/pull/2315))

    - LogAddExp ([!3150](https://gitcode.com/cann/ops-math/pull/3150))

  - New operator features

    - BitwiseOr and BitwiseXor support integer data types ([!2384](https://gitcode.com/cann/ops-math/pull/2384)).

    - The AddN operator supports aclnn API calls ([!2720](https://gitcode.com/cann/ops-math/pull/2720) [!3587](https://gitcode.com/cann/ops-math/pull/3587)).

    - The cholesky operator supports inputs with a large tail axis ([!2255](https://gitcode.com/cann/ops-math/pull/2255)).

    - The ReduceSum operator supports bool inputs ([!3014](https://gitcode.com/cann/ops-math/pull/3014)).

- Performance tuning

  - Sorting performance tuning for the Sort operator with a small axis ([!2985](https://gitcode.com/cann/ops-math/pull/2985)).

  - Generation performance tuning for random number operators ([!3590](https://gitcode.com/cann/ops-math/pull/3590)).

  - Performance tuning for the TopkV2 operator, improving computation efficiency with int64 indices ([!2564](https://gitcode.com/cann/ops-math/pull/2564)).

  - TopK operator memory and performance tuning with long sequences ([!3183](https://gitcode.com/cann/ops-math/pull/3183)).

  - AICPU operator performance tuning, covering ClipByValueV2 ([!2460](https://gitcode.com/cann/ops-math/pull/2460)), ConcatV2 ([!2395](https://gitcode.com/cann/ops-math/pull/2395)), and CumSum ([!2262](https://gitcode.com/cann/ops-math/pull/2262)).

- Operator API migration changes:

  - aclnnMatmulCompressDequant and its corresponding kernel files are migrated from the `math` repository to the `nn` repository ([!2728](https://gitcode.com/cann/ops-math/pull/2728)).<br>

#### ops-cv

- The following operators are newly adapted for <term>Ascend 950PR/Ascend 950DT</term>:<br>

  - Newly adapted operators<br>

    - GridSampler2DGrad ([!847](https://gitcode.com/cann/ops-cv/pull/847)).<br>

    - UpsampleNearestExact2d/3d ([!851](https://gitcode.com/cann/ops-cv/pull/851)).<br>

    - UpsampleNearestExactGrad ([!798](https://gitcode.com/cann/ops-cv/pull/798)).<br>

    - UpsampleTrilinear3d ([!927](https://gitcode.com/cann/ops-cv/pull/927)).<br>

    - CIoU ([!833](https://gitcode.com/cann/ops-cv/pull/833)).<br>

    - BlendFaceBgPartTwo ([!825](https://gitcode.com/cann/ops-cv/pull/825)).<br>

    - SpatialTransformer ([!698](https://gitcode.com/cann/ops-cv/pull/698)).<br>

    - adjust_saturation ([!696](https://gitcode.com/cann/ops-cv/pull/696)).<br>

    - scaleandtranslate ([!693](https://gitcode.com/cann/ops-cv/pull/693)).<br>

    - BoundingBoxEncode ([!1049](https://gitcode.com/cann/ops-cv/pull/1049)).<br>

    - NMSWithMask ([!560](https://gitcode.com/cann/ops-cv/pull/560)).<br>

    - ExtractGlimpseV2 and UpsampleBicubic2d ([!1039](https://gitcode.com/cann/ops-cv/pull/1039)).<br>

    - UpsampleNearestExact1d and its series of backward operators ([!830](https://gitcode.com/cann/ops-cv/pull/830) [!798](https://gitcode.com/cann/ops-cv/pull/798)).<br>

  - New operator features<br>

    - AIPP adds CSC color space conversion among multiple formats such as YUV420SP/U8, RGB888/U8, BGR888/U8, and XRGB8888/U8 ([!765](https://gitcode.com/cann/ops-cv/pull/765)), and adds dynamic AIPP path support ([!802](https://gitcode.com/cann/ops-cv/pull/802)).<br>

    - GridSample2D adds BF16 data type support ([!715](https://gitcode.com/cann/ops-cv/pull/715), [!751](https://gitcode.com/cann/ops-cv/pull/751)).<br>

- Performance tuning<br>

    - Performance tuning for the ResizeNearestNeighborV2 operator in NCHW format ([!822](https://gitcode.com/cann/ops-cv/pull/822)).<br>

    - Performance tuning for the GridSamplerGrad operator ([!946](https://gitcode.com/cann/ops-cv/pull/946)).<br>

#### opbase

- New features<br>

  - Supports float8/float6/float4 data types and documentation ([!298](https://gitcode.com/cann/opbase/pull/298), [!479](https://gitcode.com/cann/opbase/pull/479), [!486](https://gitcode.com/cann/opbase/pull/486)).<br>

  - The Reduce template supports mixed precision ([!255](https://gitcode.com/cann/opbase/pull/255)).<br>

  - Adds static support for non-contiguous input operators ([!346](https://gitcode.com/cann/opbase/pull/346), [!353](https://gitcode.com/cann/opbase/pull/353)).<br>

  - Enhances DFX of log APIs to support standardized log output ([!350](https://gitcode.com/cann/opbase/pull/350), [!448](https://gitcode.com/cann/opbase/pull/448), [!513](https://gitcode.com/cann/opbase/pull/513), [!299](https://gitcode.com/cann/opbase/pull/299)).<br>

- Performance tuning<br>

  - Enhances broadcasting non-contiguous tensors ([!317](https://gitcode.com/cann/opbase/pull/317)).<br>

  - Enhances incremental builds using `build.sh` by reusing the CMake cache to avoid repeated configuration ([!391](https://gitcode.com/cann/opbase/pull/391)).<br>

#### ops-nn

- Enhances convolution operator functionality and performance, optimizing multimodal networks without degrading memory usage ([!735](https://gitcode.com/cann/ops-nn/pull/735)):<br>

  - dX supports splitting W with ultra-large W inputs.<br>

  - dW supports enabling performance tuning for deterministic use cases.<br>

  - dX supports MM conversion in stride=kernel and fmap=kernel scenarios to improve performance.<br>

- New use case support for <term>Ascend 950PR/Ascend 950DT</term>:<br>

  - Introduces ops-tensor to optimize Cube-type operators based on a layered structure, reducing offset computation and code duplication ([!5036](https://gitcode.com/cann/ops-nn/pull/5036)).<br>

  - Improves low-bit operators to support precision compensation and optimize whole-network precision for RmsNormDynamicMxQuant ([!2894](https://gitcode.com/cann/ops-nn/pull/2894)), DynamicBlockMxQuant ([!1824](https://gitcode.com/cann/ops-nn/pull/1824)), and DualLevelQuantBatchMatmul ([!1141](https://gitcode.com/cann/ops-nn/pull/1141)).<br>

  - HardswishBackwardV2 ([!4817](https://gitcode.com/cann/ops-nn/pull/4817)) and SyncBatchNormGatherStatsWithCounts ([!5973](https://gitcode.com/cann/ops-nn/pull/5973)).

- nn repo engineering optimization:<br>

  - <term>Ascend 950PR/Ascend 950DT</term> supports static libraries ([!3623](https://gitcode.com/cann/ops-nn/pull/3623)).<br>

  - Optimizes the kernel configuration script ([!3330](https://gitcode.com/cann/ops-nn/pull/3330)).

- Enhances Cube-type operators for Atlas A2 products and Atlas A3 products, optimizing network performance and reducing memory usage in certain use cases:<br>

  - aclnnMatmulWeightNz performance tuning ([!5444](https://gitcode.com/cann/ops-nn/pull/5444)) ([!5105](https://gitcode.com/cann/ops-nn/pull/5105)).<br>

  - aclnnTransposeBatchMatmul removes the restriction of B x K < 65536 ([!4240](https://gitcode.com/cann/ops-nn/pull/4240)).<br>

  - Performance tuning for aclnnBatchMatmul in large-Batch small-MKN cases under the FP32 data type ([!6103](https://gitcode.com/cann/ops-nn/pull/6103)) ([!7264](https://gitcode.com/cann/ops-nn/pull/7264)).<br>

  - Cube operators support configuring out_dtype ([!4823](https://gitcode.com/cann/ops-nn/pull/4823)) ([!5481](https://gitcode.com/cann/ops-nn/pull/5481)) ([!5602](https://gitcode.com/cann/ops-nn/pull/5602)).<br>

  - Memory usage optimization for Cube operators ([!5356](https://gitcode.com/cann/ops-nn/pull/5356)) ([!5864](https://gitcode.com/cann/ops-nn/pull/5864)).<br>

- Operator API migration changes:

  - aclnnMatmulCompressDequant and its corresponding kernel files are migrated from the `math` repository to the `nn` repository ([!4166](https://gitcode.com/cann/ops-nn/pull/4166)).<br>

#### ops-transformer

**Attention (Attention/MLA)**

- Adds the SparseFlashMla (sparse FlashMLA) operator, and supports sparse attention KV merging to improve computation and memory access efficiency in long-sequence sparse attention use cases ([!6526](https://gitcode.com/cann/ops-transformer/pull/6526), [!6429](https://gitcode.com/cann/ops-transformer/pull/6429)).

- Adds the LightningIndexerV2 operator ([!5635](https://gitcode.com/cann/ops-transformer/pull/5635)).

- Adds the aclnnBlockSparseAttentionV2 API, and adapts to the FP8-quantized BlockSparseAttention operator. BlockSparseAttention supports performance improvements for FP8 and BSND input layout on A5. The quantized and non-quantized kernels of <term>Ascend 950PR/Ascend 950DT</term> forward/inference tasks support LSE outputs, and the BlockSparseAttentionGrad backward operator is newly added ([!4820](https://gitcode.com/cann/ops-transformer/pull/4820), [!6620](https://gitcode.com/cann/ops-transformer/pull/6620), [!6264](https://gitcode.com/cann/ops-transformer/pull/6264), [!6565](https://gitcode.com/cann/ops-transformer/pull/6565), [!6186](https://gitcode.com/cann/ops-transformer/pull/6186)).

- FusedInferAttentionScore supports LSE outputs, and AttentionUpdate supports sp128 on A2/A3 ([!5505](https://gitcode.com/cann/ops-transformer/pull/5505), [!5709](https://gitcode.com/cann/ops-transformer/pull/5709)).

- ScatterPaKvCache/GatherPaKvCache now support non-contiguous tensors on the first axis of the cache, and MlaProlog supports non-contiguous KVCache inputs ([!6214](https://gitcode.com/cann/ops-transformer/pull/6214), [!6442](https://gitcode.com/cann/ops-transformer/pull/6442)).

- RecurrentGatedDeltaRule supports non-contiguous first two axes of state, and SMLAG adds torch adaptation and new features ([!6288](https://gitcode.com/cann/ops-transformer/pull/6288), [!5916](https://gitcode.com/cann/ops-transformer/pull/5916)).

**MoE**

- MoeInitRoutingV3 supports DropPad in non-quantized tasks, and UnpermuteWithRoutingMap adds non-topk support for the N specification ([!5826](https://gitcode.com/cann/ops-transformer/pull/5826), [!5353](https://gitcode.com/cann/ops-transformer/pull/5353)).

- MegaMoe adds A2/A3 tiling, static tensor, and syncfunc functionality, and supplements A2/A3 kernels ([!6574](https://gitcode.com/cann/ops-transformer/pull/6574), [!3608](https://gitcode.com/cann/ops-transformer/pull/3608)).

**GMM (GroupedMatmul) quantization**

- GroupedMatmulFinalizeRouting adds deterministic support for W8A8 use cases on A5 ([!6289](https://gitcode.com/cann/ops-transformer/pull/6289)).

- GroupedMatmulSwigluQuantV2 adds WeightNz MxA8W4 data flow and MXFP4 weight NZ format support ([!5267](https://gitcode.com/cann/ops-transformer/pull/5267), [!5419](https://gitcode.com/cann/ops-transformer/pull/5419), [!5272](https://gitcode.com/cann/ops-transformer/pull/5272)).

- Enhances GMM and GMMAdd GlistType specifications ([!4844](https://gitcode.com/cann/ops-transformer/pull/4844), [!3725](https://gitcode.com/cann/ops-transformer/pull/3725)).

**MC2 (communication-computation fusion)**

- Adds the AllToAllMatmulV2 operator ([!6062](https://gitcode.com/cann/ops-transformer/pull/6062)).

- AllGatherMatmulV2 and AllToAllVGroupedMatmul/GroupedMatmulAllToAllV add `comm_mode` to support selecting the communication engine ([!5340](https://gitcode.com/cann/ops-transformer/pull/5340), [!6103](https://gitcode.com/cann/ops-transformer/pull/6103)).

- MatmulReduceScatterV2 adapts to AICPU communication ([!5515](https://gitcode.com/cann/ops-transformer/pull/5515)).

**Mhc**
The following operators are supported for the Atlas A2 products and Atlas A3 products:

- MhcPost ([!3670](https://gitcode.com/cann/ops-transformer/pull/3670))

- MhcPostBackward ([!4377](https://gitcode.com/cann/ops-transformer/pull/4377))

- MhcPreSinkhorn ([!5033](https://gitcode.com/cann/ops-transformer/pull/5033))

- MhcPreSinkhornBackward ([!4760](https://gitcode.com/cann/ops-transformer/pull/4760))

### Communication Libraries

#### Collective Communication (HCCL)

- Ascend 950PR supports the allGatherV/reduceScatterV operators in CCU use cases ([!303](https://gitcode.com/cann/hccl/pull/303), [!207](https://gitcode.com/cann/hccl/pull/207)).

- Ascend 950PR supports integrating communication operators into graphs in GE graph mode and aclGraph mode ([!183](https://gitcode.com/cann/hccl/pull/183), [!164](https://gitcode.com/cann/hccl/pull/164), [!296](https://gitcode.com/cann/hccl/pull/296)).

- Ascend 950PR supports N-second fast recovery, improving the reliability of collective communication operations ([!1126](https://gitcode.com/cann/hcomm/pull/1126), [!1609](https://gitcode.com/cann/hcomm/pull/1609), [!421](https://gitcode.com/cann/hccl/pull/421)).

- Ascend 950PR supports maintenance and testing capabilities such as task exception and profiling, allowing you to pinpoint issues quickly ([!937](https://gitcode.com/cann/hcomm/pull/937), [!1472](https://gitcode.com/cann/hcomm/pull/1472), [!267](https://gitcode.com/cann/hccl/pull/267), [!332](https://gitcode.com/cann/hccl/pull/332)).

- On Ascend 950PR, the HcclChannelAcquire API supports AIV directly issuing RoCE and URMA transfers, supporting custom development of MC2 operators ([!2032](https://gitcode.com/cann/hcomm/pull/2032)).

- On Atlas A2/A3 products, the multi-process-per-device capability now supports MC2 use cases ([!1880](https://gitcode.com/cann/hcomm/pull/1880)).

- On Atlas A2/A3 products, resource management is optimized in aclGraph use cases to support incremental refresh of communication resources ([!2405](https://gitcode.com/cann/hcomm/pull/2405), [!2502](https://gitcode.com/cann/hcomm/pull/2502)).

- On Atlas A2/A3 products, performance is enhanced in cross-SuperPoD use cases, and the ReduceScatter/AllGather operators support the cross-SuperPoD pipeline algorithm ([!2071](https://gitcode.com/cann/hcomm/pull/2071), [!1931](https://gitcode.com/cann/hcomm/pull/1931)).

- On Atlas A2/A3 products, communication is now supported for dual-machine back-to-back RoCE direct-connect models ([!2642](https://gitcode.com/cann/hcomm/pull/2642), [!3433](https://gitcode.com/cann/hcomm/pull/3433)).

- Atlas 350 accelerator cards support communication across PCIE SW ([!1799](https://gitcode.com/cann/hcomm/pull/1799), [!707](https://gitcode.com/cann/hccl/pull/707)), and operators such as AllReduce, ReduceScatter, AllGather, Reduce, Scatter, Alltoall, Alltoallv, Send, and Recv support communication.

#### HIXL

- Open underlying APIs: The Client-Server one-sided communication capabilities comprehensively improve link establishment specifications and performance. Deep optimization for batch small-buffer transfers effectively reduces on-chip memory use and communication resource overhead ([!138](https://gitcode.com/cann/hixl/issues/138)).

- HIXL network transport protocol extension: HIXL adds UBC, UBoE, and Host RoCE protocol support, fully covering D2D, D2rH, rH2D, and H2H data transfers across all use cases ([!37](https://gitcode.com/cann/hixl/issues/37)). For the protocol support list of different product forms, visit the [HIXL](https://gitcode.com/cann/hixl) community.

- HIXL intelligent link management upgrade: Automatic acquisition of communication resources and intelligent route selection ([!181](https://gitcode.com/cann/hixl/issues/181)) allow for simple, on-demand link establishment ([!245](https://gitcode.com/cann/hixl/issues/245)).

- HIXL programming API enhancement: Extends APIs for asynchronous link management ([!207](https://gitcode.com/cann/hixl/issues/207)) and batch query of transfer status ([!208](https://gitcode.com/cann/hixl/issues/208)), speeding up upper-layer service development.

### Graph Engine

- Supports recovery on Ascend 950DT.

- ge.autoMultistreamParallelMode adds the MainStream and LoadBalance options. Based on the Minimum Path Cover algorithm, it automatically partitions the compute nodes of a static shape model into the minimum number of logical streams to achieve multi-stream parallel acceleration.

- Adds the PortableOp operator type, which provides serialization and deserialization capabilities for custom operators in offline inference tasks.

- ATC and aclgrph APIs support setting the cluster configuration file path, which is used to generate offline OM models containing HCCL communication tasks, meeting the communicator configuration requirements in multi-device offline inference tasks.

### Domain-specific Acceleration Libraries

#### Ascend Transformer Boost (ATB)

- **Integration of core operators on Ascend 950PR/Ascend 950DT**

  Realizes GELU, LayerNorm, MatmulEinSum, RmsNormQuant, SwiGluQuant (ACLNN V2), linear dequantization, and supports communication operators such as AllGather/AllReduce/ReduceScatter ([!1994](https://gitcode.com/cann/ascend-transformer-boost/pull/1994), [!2089](https://gitcode.com/cann/ascend-transformer-boost/pull/2089), [!2090](https://gitcode.com/cann/ascend-transformer-boost/pull/2090), [!2060](https://gitcode.com/cann/ascend-transformer-boost/pull/2060), [!2097](https://gitcode.com/cann/ascend-transformer-boost/pull/2097), [!2103](https://gitcode.com/cann/ascend-transformer-boost/pull/2103), [!2091](https://gitcode.com/cann/ascend-transformer-boost/pull/2091)).

- **Attention/KV Cache inference enhancement**

  - Paged Attention: Upgrades FusedInferAttention V5 on <term>Ascend 950 products</term> ([!2069](https://gitcode.com/cann/ascend-transformer-boost/pull/2069)).

  - Paged Attention and Flash Attention now support the NORM_COMPRESS mask ([!2114](https://gitcode.com/cann/ascend-transformer-boost/pull/2114), [!2116](https://gitcode.com/cann/ascend-transformer-boost/pull/2116), [!2078](https://gitcode.com/cann/ascend-transformer-boost/pull/2078)).

  - MLA decode supports Sliding Window Attention (SWA).

  - ReshapeAndCache supports single-input single-output on <term>Ascend 950 products</term> ([!2065](https://gitcode.com/cann/ascend-transformer-boost/pull/2065)).

- **Independent compilation and ABI system of torch_atb**

  - torch_atb is decoupled from the main library for independent compilation, and the default output package ABI is switched to `cxx_abi_1` ([!2021](https://gitcode.com/cann/ascend-transformer-boost/pull/2021)).

  - Supports wheel naming convention and automatic torch detection/installation for the installation script. The installation and deployment pipeline is fully connected ([!2086](https://gitcode.com/cann/ascend-transformer-boost/pull/2086), [!2118](https://gitcode.com/cann/ascend-transformer-boost/pull/2118)).

#### Ascend Signal Processing Boost (SiP)

- The following operators are newly adapted on <term>Ascend 950PR/Ascend 950DT</term>:

  - FFT 1D C2C ([!69](https://gitcode.com/cann/sip/pull/69))

  - FFT 1D C2R ([!73](https://gitcode.com/cann/sip/pull/73))

  - FFT 1D R2C ([!73](https://gitcode.com/cann/sip/pull/73))

  - Hadamard ([!76](https://gitcode.com/cann/sip/pull/76))

### Runtime

Supports stream specification expansion for AclGraph on Ascend 950DT to resolve issues such as insufficient resources for AI models ([!2976](https://gitcode.com/cann/runtime/pull/2976)).

### Operator Programming

#### Key Features

- Debugging

  - The Ascend C framework basic APIs support NPU Check ([!1557](https://gitcode.com/cann/asc-devkit/pull/1557), [!1467](https://gitcode.com/cann/asc-devkit/pull/1467)), enhancing runtime validation for operators.

  - printf and reg dump printing are supported in SIMD VF ([!1605](https://gitcode.com/cann/asc-devkit/pull/1605)), providing debug printing and register data dumps.

  - <term>Ascend 950PR/Ascend 950DT</term> supports DumpTensor for L1 tensor data ([!2175](https://gitcode.com/cann/asc-devkit/pull/2175)), extending L1 data debugging support.

  - Adds optype_collector, a tool that can check for duplicate optype names ([!285](https://gitcode.com/cann/asc-tools/pull/285)).

- Build project

  - CMakeModule supports `CMAKE_<LANG>` options ([!2055](https://gitcode.com/cann/asc-devkit/pull/2055)).

- Basic APIs

  - Supports setting saturation overflow management for the ctrl register ([!2077](https://gitcode.com/cann/asc-devkit/pull/2077)).

- SIMT programming

  - Adds ld/st APIs ([!2058](https://gitcode.com/cann/asc-devkit/pull/2058)) and AddrSpace APIs ([!1597](https://gitcode.com/cann/asc-devkit/pull/1597)), extending SIMT memory access programming capabilities.

#### Sample Updates

- SIMD samples:

  - New best practice samples: Matmul+GELU fusion, datacopy optimization, bank conflict optimization, group_matmul quantized group matrix multiplication, and SIMT & SIMD high-performance programming ([!1814](https://gitcode.com/cann/asc-devkit/pull/1814), [!2137](https://gitcode.com/cann/asc-devkit/pull/2137), [!2141](https://gitcode.com/cann/asc-devkit/pull/2141), [!2166](https://gitcode.com/cann/asc-devkit/pull/2166), [!2363](https://gitcode.com/cann/asc-devkit/pull/2363)).

  - <term>Ascend 950PR/Ascend 950DT</term> new feature samples and compatibility sample rectification: loopmode data transfer, interleave vector computation, datacopy_gm2l1, loadmx (Load2DMX), mmad_mx, data_copy_pad, etc. ([!2336](https://gitcode.com/cann/asc-devkit/pull/2336), [!1899](https://gitcode.com/cann/asc-devkit/pull/1899), [!2124](https://gitcode.com/cann/asc-devkit/pull/2124)).

  - New RegBase basic samples: basic arithmetic, data type conversion, reduction, comparison, indexing, and other samples ([!1459](https://gitcode.com/cann/asc-devkit/pull/1459), [!1575](https://gitcode.com/cann/asc-devkit/pull/1575), [!2024](https://gitcode.com/cann/asc-devkit/pull/2024)).

  - Adds SIMD VF print samples and dump samples ([!2558](https://gitcode.com/cann/asc-devkit/pull/2558)).

  - New getting-started and best-practice samples for tensor APIs: Matmul quick start, data copy-in/-out, on-the-fly quantization on copy-out, and MX FP4 best practices ([!2553](https://gitcode.com/cann/asc-devkit/pull/2553)).

- SIMT samples:

  - New SIMT optimization feature samples: DCache access optimization sample ([!2453](https://gitcode.com/cann/asc-devkit/pull/2453)), transpose-based memory access coalescing and bank conflict sample ([!1753](https://gitcode.com/cann/asc-devkit/pull/1753)), and best-practice sample: improving transfer efficiency through type alignment ([!2297](https://gitcode.com/cann/asc-devkit/pull/2297)).

  - New SIMT functional feature samples: registering custom operators in PyTorch ([!2769](https://gitcode.com/cann/asc-devkit/pull/2769)), compilation-related samples (dynamic, static, separate compilation, etc.) ([!2356](https://gitcode.com/cann/asc-devkit/pull/2356)), profiling sample ([!1989](https://gitcode.com/cann/asc-devkit/pull/1989)), memory barrier feature sample ([!1923](https://gitcode.com/cann/asc-devkit/pull/1923)), Warp class feature sample ([!2876](https://gitcode.com/cann/asc-devkit/pull/2876)), simulator sample ([!2692](https://gitcode.com/cann/asc-devkit/pull/2692)), and kernel log sample ([!2131](https://gitcode.com/cann/asc-devkit/pull/2131)).

### PTO Virtual Instruction Set

- Basic Vector & Cube instructions:

  - Supports high-precision versions of Vector instructions ([!896](https://gitcode.com/cann/pto-isa/pull/896), [!782](https://gitcode.com/cann/pto-isa/pull/782), [!815](https://gitcode.com/cann/pto-isa/pull/815), [!717](https://gitcode.com/cann/pto-isa/pull/717), [!648](https://gitcode.com/cann/pto-isa/pull/648), [!695](https://gitcode.com/cann/pto-isa/pull/695)).

  - Supports transdata use cases ([!950](https://gitcode.com/cann/pto-isa/pull/950), [!977](https://gitcode.com/cann/pto-isa/pull/977)).

  - TSTORE and TLOAD support 3D convolution ([!904](https://gitcode.com/cann/pto-isa/pull/904), [!912](https://gitcode.com/cann/pto-isa/pull/912)).

  - Adds MGATHER/MSCATTER instructions ([!935](https://gitcode.com/cann/pto-isa/pull/935), [!1136](https://gitcode.com/cann/pto-isa/pull/1136), [!309](https://gitcode.com/cann/pto-isa/pull/309), [!889](https://gitcode.com/cann/pto-isa/pull/889)).

  - Reduce instructions support return values and corresponding indices ([!1124](https://gitcode.com/cann/pto-isa/pull/1124), [!928](https://gitcode.com/cann/pto-isa/pull/928)).

  - TQUANT supports MXFP8/MXFP4 quantization ([!1187](https://gitcode.com/cann/pto-isa/pull/1187), [!1143](https://gitcode.com/cann/pto-isa/pull/1143)).

  - Axis-merging instructions support type enhancement; TMOV/TEXTRACT/TINSERT support Vec-to-Vec ([!1196](https://gitcode.com/cann/pto-isa/pull/1196)).

- Communication instructions:

  - Adds CCU asynchronous communication instructions TGATHER, TBROADCAST, TSCATTER, and TREDUCE for <term>Ascend 950 products</term> ([!915](https://gitcode.com/cann/pto-isa/pull/915)).

  - Supports the all-core synchronization instruction SYNCALL ([!907](https://gitcode.com/cann/pto-isa/pull/907)).

  - Adds the asynchronous prefetch instruction ([!116](https://gitcode.com/cann/pto-isa/pull/116)).

  - TPUT_ASYNC and TGET_ASYNC add support for A5 URMA-based asynchronous communication ([!991](https://gitcode.com/cann/pto-isa/pull/991)).

- CostModel simulation:

  - Adds operator-level Costmodel on Atlas A2 products and Atlas A3 products, supporting output of operator performance, pipeline time, swimlane diagram, and other information ([!1004](https://gitcode.com/cann/pto-isa/pull/1004)).

  - Integrates the CCE Mock solution, supporting performance prediction for existing A2/A3 instructions ([!772](https://gitcode.com/cann/pto-isa/pull/772)).

- CPU-SIM: Adds CPU simulation instructions, like those for NPUs.

## Removed and Deprecated Features

### NOTE

- Deleted features are those that have been removed in the current version.

- Deprecated features are those marked as deprecated in the current version and will be removed in future versions.

- Replace `${install_path}` in this section with the CANN software installation path.

### Runtime

**The following directories, files, and APIs are marked as deprecated in CANN 9.1.0 and are planned for removal in versions after June 30, 2027.**

| Deprecated Directories, Files, and APIs | Replacement Directories, Files, and APIs |
| ------------------------ | ---------------------- |
| Header files in the `include/driver` directory | `pkg_inc/driver` directory |

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

| Deprecated Directories, Files, and APIs | Replacement Directories, Files, and APIs |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ${install_path}/ascend-toolkit/latest/runtime/include/acl | ${install_path}/cann/include/acl |
| ${install_path}/ascend-toolkit/latest/runtime/include/aclnn | ${install_path}/cann/include/aclnn |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph | ${install_path}/cann/include/graph |
| All header files under `${install_path}/cann/pkg_inc/runtime/runtime` will be removed | No related functionality will be provided in later versions |
| The rtGetC2cCtrlAddr API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_ffts.h`. | Replace with the aclrtGetHardwareSyncAddr API in `${install_path}/cann/include/acl/aclrt.h` |
| The rtFftsTaskLaunch and rtFftsTaskLaunchWithFlag APIs are deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_ffts.h`. | No related functionality will be provided in later versions |
| The rtBindHostPid, rtUnbindHostPid, rtProfSetProSwitch, rtQueryProcessHostPid, rtGetDeviceIdByGeModelIdx, rtGetExceptionRegInfo, rtGetMaxModelNum, rtLabelGoto, rtLabelGotoEx, rtProfilerConfig, rtProfilerInit, rtProfilerTrace, rtProfilingCommandHandle, rtProfRegisterCtrlCallback, rtSetDeviceIdByGeModelIdx, rtSetExceptCallback, rtSetMsprofReporterCallback, rtSetProfDirEx, and rtUnsetDeviceIdByGeModelIdx APIs are deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | No related functionality will be provided in later versions |
| The rtGetBinaryDeviceBaseAddr API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtBinaryGetDevAddress API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtGetTaskIdAndStreamID API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtGetThreadLastTaskId and aclrtStreamGetId APIs in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtLabelCreate, rtLabelCreateEx, rtLabelCreateExV2, and rtLabelCreateV2 APIs are deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtCreateLabel API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtLabelListCpy API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtCreateLabelList and aclrtDestroyLabelList APIs in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtLabelSet API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtSetLabel API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtLabelSwitchByIndex API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtSwitchLabelByIndex API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtProfilerTraceEx API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtProfTrace API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtRegDeviceStateCallbackEx API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtRegDeviceStateCallback API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtRegTaskFailCallbackByModule API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtSetExceptionInfoCallback API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtSetIpcMemorySuperPodPid API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtIpcMemImportPidInterServer API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtSetIpcNotifySuperPodPid API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtNotifySetImportPidInterServer API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtSetTaskAbortCallBack API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtSetTaskAbortCallBack API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtSetTaskFailCallback API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtSetExceptionInfoCallback API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtStreamGetMode API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtGetStreamAttribute API in `${install_path}/cann/include/acl/aclrt.h`. |
| The rtStreamSetMode API is deprecated in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h`. | Replace with the aclrtSetStreamFailureMode and aclrtSetStreamOverflowSwitch APIs in `${install_path}/cann/include/acl/aclrt.h`. |
| The aclsysGetCANNVersion API is deprecated in `${install_path}/ascend-toolkit/latest/include/acl/acl.h`. | Replace with the aclsysGetVersionStr and aclsysGetVersionNum APIs in `${install_path}/cann/include/acl/acl.h`. |
| libascendcl.so is deprecated in `${install_path}/ascend-toolkit/latest/lib64`. | Replace with the libacl_rt.so, libacl_mdl.so, and libacl_op_executor.so library files in `${install_path}/cann/lib64`. |

### Graph Engine

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

| Deprecated Directories                                       | Replacement Directories                                    |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| ${install_path}/ascend-toolkit/latest/runtime/include/graph  | ${install_path}/cann/include/graph                         |
| ${install_path}/ascend-toolkit/latest/compiler/python/func2graph | `func2graph` in the `${install_path}/cann/x86_64-linux/python` directory |

Starting from Ascend 950 products, the aclblas and aclop APIs are no longer recommended. They will be gradually deprecated in later versions. Migrate to the corresponding aclnn operator APIs.

### Operator Libraries

- **Incompatibility changes**: Control operators Identity, IdentityN, Rank, Shape, and ShapeN are migrated from ops-nn to ops-math. These operators are migrated from the `ops_proto_nn.h` and `es_nn` directories to the `ops_proto_math.h` and `es_math` directories. You need to update the related header file references ([!2333](https://gitcode.com/cann/ops-math/pull/2333), [!3995](https://gitcode.com/cann/ops-nn/pull/3995)).

**The following directories, files, and APIs are marked as deprecated in CANN 9.0.0 and will be removed in later versions after March 30, 2027.**

| Deprecated Directories, Files, and APIs                                       | Replacement Directories, Files, and APIs                           |
| ------------------------------------------------------------ | ------------------------------------------------ |
| aclnnGroupedMatMulAllReduce API                              | aclnnMatmulAllReduce                             |
| aclnnGroupedMatmul, aclnnGroupedMatmulV2, aclnnGroupedMatmulV3, and aclnnGroupedMatmulV4 APIs | aclnnGroupedMatmulV5                             |
| aclnnFusedInferAttentionScore, aclnnFusedInferAttentionScoreV2, and aclnnFusedInferAttentionScoreV3 APIs | aclnnFusedInferAttentionScoreV4                  |
| aclnnIncreFlashAttention, aclnnIncreFlashAttentionV2, and aclnnIncreFlashAttentionV3 APIs | aclnnIncreFlashAttentionV4                       |
| aclnnPromptFlashAttention and aclnnPromptFlashAttentionV2 APIs   | aclnnPromptFlashAttentionV3                      |
| aclnnMlaProlog and aclnnMlaPrologV2WeightNz APIs                 | aclnnMlaPrologV3WeightNz                         |
| aclnnMatmulAllReduceAddRmsNorm API                           | aclnnMatmulAllReduce and aclnnAddRmsNorm            |
| aclnnQuantMatmulAllReduceAddRmsNorm API                      | aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm     |
| aclnnWeightQuantMatmulAllReduceAddRmsNorm API (deprecated)            | aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm |
| aclnnInplaceQuantMatmulAllReduceAddRmsNorm API               | aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm     |
| aclnnInplaceMatmulAllReduceAddRmsNorm API                    | aclnnMatmulAllReduce and aclnnAddRmsNorm            |
| aclnnInplaceWeightQuantMatmulAllReduceAddRmsNorm API         | aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm |

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in later versions after December 30, 2026.**

Operators are split into component packages. Each independent component package of different operators contains multiple libraries and header files. In the following table, `${ops_project}` represents the actual cv, math, nn, transformer, and legacy.

| Deprecated Directories, Files, and APIs | Replacement Directories, Files, and APIs |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/*.h | ${install_path}/cann/opp/built-in/op_graph/inc/\${ops_project}_ops_proto.h |
| ${install_path}/ascend-toolkit/latest/lib64/libopapi.so | ${install_path}/cann/lib64/libopapi_\${ops_project}.so |
| aclnnGroupedMatMulAllReduce API | No replacement functionality |
| aclnnWeightQuantBatchMatmul API | aclnnWeightQuantBatchMatmulV3 API |
| aclnnQuantMatmul, aclnnQuantMatmulV2, aclnnQuantMatmulV3, and aclnnQuantMatmulV4 APIs | aclnnQuantMatmulV5 API |
| aclnnGroupedMatmul, aclnnGroupedMatmulV2, aclnnGroupedMatmulV3, and aclnnGroupedMatmulV4 APIs | aclnnGroupedMatmulV5 API |
| aclnnIncreFlashAttentionV2 and aclnnIncreFlashAttentionV3 APIs | aclnnIncreFlashAttentionV4 API |
| aclnnPromptFlashAttentionV2 API | aclnnPromptFlashAttentionV3 API |
| aclnnFusedInferAttentionScoreV2 and aclnnFusedInferAttentionScoreV3 APIs | aclnnFusedInferAttentionScoreV4 API |

### Acceleration Libraries

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

The following operator IRs are deprecated for the DVPP acceleration feature: Crop, CropAndResize, DecodeAndCropJpeg, DecodeJpeg, PadV3D, Resize, ResizeV2, ResizeBicubic, ResizeBilinearV2, ResizeNearestNeighborV2, ReverseV2, WarpPerspective, WarpAffineV2, AdjustContrast, AdjustHue, AdjustSaturation.

| Deprecated Directories, Files, and APIs | Replacement Directories, Files, and APIs |
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

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in later versions after December 30, 2026.**

| Deprecated Directories, Files, and APIs                                       | Replacement Directories, Files, and APIs                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| The profiling header files `aprof_pub.h`, `prof_api.h`, and `prof_common.h` are deprecated from the path `${install_path}/ascend-toolkit/latest/include/experiment/msprof/toolchain`. | The storage path of the profiling header files `aprof_pub.h`, `prof_api.h`, and `prof_common.h` is changed to `${install_path}/cann/pkg_inc/profiling`. |

### Diagnostics

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in later versions after December 30, 2026.**

| Deprecated Directories, Files, and APIs                                       | Replacement Directories, Files, and APIs                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Error Manager header file ${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h | Error Manager header file ${install_path}/cann/include/base/err_msg.h |
| REPORT_INNER_ERROR and REPORT_CALL_ERROR APIs in `${install_path}/ascend-toolkit/latest/include/experiment/metadef/common/util/error_manager/error_manager.h` | REPORT_INNER_ERR_MSG API                                     |
| REPORT_INPUT_ERROR and REPORT_ENV_ERROR APIs                     | REPORT_PREDEFINED_ERR_MSG API                                |
| Log header file ${install_path}/ascend-toolkit/latest/include/toolchain/slog.h | Log header file ${install_path}/cann/pkg_inc/base/dlog_pub.h       |
| Log header file ${install_path}/ascend-toolkit/latest/include/base/alog_pub.h | Log header file ${install_path}/cann/pkg_inc/base/dlog_pub.h       |
| AlogCheckDebugLevel API in `${install_path}/ascend-toolkit/latest/include/base/alog_pub.h` | CheckLogLevel API in `${install_path}/cann/pkg_inc/base/dlog_pub.h` |
| AlogRecord API in `${install_path}/ascend-toolkit/latest/include/base/alog_pub.h` | DlogRecord API in `${install_path}/cann/pkg_inc/base/dlog_pub.h` or wrapped macros such as dlog_error and dlog_warn |

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

## Documentation Changes

### Programming Guide

#### Ascend C Operator Development

- Optimized the "Quick Start" chapter:

  - Updated the Ascend C learning path.

  - Added a general description of heterogeneous systems and the programming model.

- Optimized and adjusted the SIMD programming model chapter in the *Programming Guide*, categorized by the dimensions of C API programming based on the language extension layer, tensor-based C++ programming, and Tpipe- and TQue-based programming.

- Added **SuperKernel** and **SIMT Cooperative Groups** sections under **Advanced Programming** in the *Programming Guide*.

- *Ascend C API* has undergone a large-scale restructuring. The changes are as follows:

  - The directory structure of data movement APIs and matrix computation APIs has been adjusted: closely related APIs are placed adjacent to each other. For example, the movement APIs related to matrix computation are placed under the matrix computation directory.

  - The API directory structure was organized by use cases: for example, matrix computation is divided into matrix computation copy-in, Mmad computation, and matrix computation copy-out.

  - For each type of APIs, necessary basics, concepts and principles, general constraints, key features, and other descriptions were added.

  - Added constraint descriptions and notes on special parameter values for each API.

  - Added an API appendix that includes a summary of API pipeline types, theoretical performance, and API boundary values.

- Added the tensor API reference. Tensor APIs are experimental and may be adjusted or improved in later versions, and backward compatibility is not guaranteed. You should pay attention to updates in later versions during use.

- Added documentation on matrix computation overview and computation fractal introduction ([!2533](https://gitcode.com/cann/asc-devkit/pull/2533)).

- Optimized the vector computation API documentation and added instruction constraints ([!2676](https://gitcode.com/cann/asc-devkit/pull/2676)).

- Added an overview of SIMD and SIMT hybrid programming performance optimization ([!2736](https://gitcode.com/cann/asc-devkit/pull/2736)).

- Built a VitePress documentation site for AscendC documentation preview ([!2547](https://gitcode.com/cann/asc-devkit/pull/2547)).

#### Communication Operator Development

- Added the "Programming Models and Concepts > CCU Programming Models and Concepts" section.

- Added the "Communication Operator Development > CCU Operator Development" section.

- Added the following APIs to the communication operator development APIs.

  - Added documentation about CCU kernel lifecycle and memory token management to control plane APIs.

  - Added CCU APIs to data plane APIs.

#### Graph Development

Added the following sections:

- Custom Pass Development > Modifying a Graph with a Custom Pass > Implementing a Pass Based on Pattern Matching (Python)

- Programming Guide > SuperKernel Fusion Scope Calibration

- Integrating Custom Operators into a Graph > Integrating Custom Operators into a Graph

### API Reference

#### GE APIs

- API Reference > Python APIs > pyatc API: Added the atc command-line tool for Python.

- Basic Data Structures and APIs of Graphs > options parameter description > ge.tiling_schedule_optimize: Modified the parameter level from the original global session level to all levels.

### Operator Libraries

- The "Operator Libraries > AI Framework Operator Support List" section from previous versions is now separated into an independent manual, *AI Framework Operator Support List*, newly added in this version.

- Added the "Operator Libraries > Operator APIs (torch_extension)" section.

- Added the RAS APIs section to "Operator APIs (aclnn)".

- Added a multi-platform migration guide for migrating the operators in the ops-cv library from Atlas A2 products to Ascend 950PR/Ascend 950DT.

### Communication Libraries

#### HCCL

References > Communication Operator Support List: Added the Ascend 950PR/Ascend 950DT support list.

### Domain-specific Acceleration Libraries

#### Ascend Transformer Boost (ATB)

- Added a test framework guide, supplementing the instructions on build and run dependencies for testframework ([!2120](https://gitcode.com/cann/ascend-transformer-boost/pull/2120)).

- Added instructions on how to determine the cxx_abi version ([!2121](https://gitcode.com/cann/ascend-transformer-boost/pull/2121)).

- Updated documentation links to CANN 9.1 and PyTorch 26.0.0 ([!2126](https://gitcode.com/cann/ascend-transformer-boost/pull/2126)).

- Corrected the ATB_BUILD_DEPENDENCY_PATH and ABI determination instructions, covering README/FAQ/test framework guide ([!2136](https://gitcode.com/cann/ascend-transformer-boost/pull/2136)).

### Development Tools

#### Ascend Tensor Compiler (ATC)

Parameter --framework: Added a note that the Caffe framework is no longer evolving in its current form, and model conversion availability is not guaranteed.

#### Ascend Model Compression Toolkit (AMCT)

Added the "LLM-based Quantization" chapter.

## Fixed Vulnerabilities

For details about the fixed vulnerabilities for open-source and third-party software in this version, see [Fixed Vulnerabilities](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/910/maintenref/refdoc/refer002.html).
