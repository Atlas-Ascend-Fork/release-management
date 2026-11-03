# CANN 9.2.0 Release Notes

<!-- md-trans-meta sourceCommit=unknown translatedAt=2026-10-21T10:57:14.217Z pushedAt=2026-10-23T01:45:08.406Z nl=2 -->

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
    <td>9.2.0</td>
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

## Internal Matching Relationships of CANN Software Packages

### CANN Combination Compatibility

CANN 9.2.0 contains three combined packages: Toolkit, ops (operator package), and NNAL (acceleration library). The following table lists the matching relationship between the CANN combined packages and their subpackages. Six of the subpackages support independent upgrade and can be flexibly installed as needed.

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
      <td rowspan="24">Toolkit</td>
      <td>ascendnpu-ir</td>
      <td>2.0.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-acl-extend</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-aoe</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-devkit</td>
      <td><a href="https://gitcode.com/cann/asc-devkit/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-asc-tools</td>
      <td><a href="https://gitcode.com/cann/asc-tools/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-bisheng-compiler</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-dflow-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-compiler</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ge-executor</td>
      <td><a href="https://gitcode.com/cann/ge/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-graph-autofusion</td>
      <td><a href="https://gitcode.com/cann/graph-autofusion/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hcomm</td>
      <td><a href="https://gitcode.com/cann/hcomm/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-metadef</td>
      <td><a href="https://gitcode.com/cann/metadef/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-ncs</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-npu-runtime</td>
      <td><a href="https://gitcode.com/cann/runtime/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-oam-tools</td>
      <td><a href="https://gitcode.com/cann/oam-tools/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-as</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pto-isa</td>
      <td><a href="https://gitcode.com/cann/pto-isa/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-pypto</td>
      <td><a href="https://gitcode.com/cann/pypto/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-simulator</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-tbe-tik</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>mindstudio-toolkit</td>
      <td>26.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>pyACL</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>test-ops</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="10">ops</td>
      <td>cann-dvpp</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-opbase</td>
      <td><a href="https://gitcode.com/cann/opbase/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-legacy</td>
      <td>9.2.0</td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hccl</td>
      <td><a href="https://gitcode.com/cann/hccl/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>cann-hixl</td>
      <td><a href="https://gitcode.com/cann/hixl/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-cv</td>
      <td><a href="https://gitcode.com/cann/ops-cv/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-math</td>
      <td><a href="https://gitcode.com/cann/ops-math/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-nn</td>
      <td><a href="https://gitcode.com/cann/ops-nn/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-transformer</td>
      <td><a href="https://gitcode.com/cann/ops-transformer/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>ops-ras</td>
      <td><a href="https://gitcode.com/cann/ops-ras/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td rowspan="2">NNAL</td>
      <td>atb</td>
      <td><a href="https://gitcode.com/cann/ascend-transformer-boost/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
    <tr>
      <td>sip</td>
      <td><a href="https://gitcode.com/cann/sip/tags/v9.2.0">9.2.0</a></td>
      <td>Arm/x86</td>
    </tr>
  </tbody>
</table>

### CANN ops and Toolkit Compatibility

The CANN ops package has been decoupled from Toolkit and supports independent upgrade. You can install it as needed.

|ops Version  |Compatible Toolkit Version  |
|--|--|
| [ascend-cann-ops 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br> [ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.1.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) | [ascend-cann-toolkit 9.2.0](https://www.hiascend.com/developer/download/community/result?module=cann&cann=9.2.0)<br>[ascend-cann-toolkit 9.1.X](https://www.hiascend.com/developer/download/community/result?module=cann)<br> [ascend-cann-toolkit 9.0.x](https://www.hiascend.com/developer/download/community/result?module=cann)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/developer/download/community/result?module=cann&cann=8.5.2) |

### Compatibility of Independently Upgradable Subpackages in the CANN ops Package

| CANN Subpackage Version                                                 | Source Code Tag                                                 | Compatible CANN Version                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------- |
| [cann-ops-math 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-math/tags/v9.2.0)      | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-nn 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-nn/tags/v9.2.0)        | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-cv 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-cv/tags/v9.2.0)        | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-ops-transformer 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/ops-transformer/tags/v9.2.0) | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hccl 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/hccl/tags/v9.2.0)          | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |
| [cann-hixl 9.2.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.2.0/) | [v9.2.0](https://gitcode.com/cann/hixl/tags/v9.2.0)          | CANN 9.2.0<br>CANN 9.1.x<br>CANN 9.0.x<br>CANN 8.5.2 |

For the specific operations of independent subpackage upgrade, see [Independent Subpackage Upgrade](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/softwareinst/instg/instg_0030.html). The ops subpackage version must be greater than or equal to the ops combined package version.

## Key Features

- **The CANN version mapping assistant is now available in the Ascend community. You can quickly find the matching upstream and downstream software. Click [here](https://www.hiascend.com/developer/download/compatibility) for details.**
<!-- npu="950" id1 -->
- **On <term>Ascend 950PR&950DT products</term>, operators such as Matmul, FA, SFA, and BSA support 8-bit low-precision computation. Operators such as Matmul, GroupedMatmul, and BSA further support 4-bit low-precision computation. This low-precision feature supports key parts of models like DeepSeek, GLM, and Kimi, including model weights, activations, KV cache, and attention. Click [here](https://gitcode.com/cann/docs/blob/9.2.0/docs/en/ops-lib/0_README.md) for details.**
<!-- end id1 -->
- **Fused operators such as KDA, SMLA, and MegaMoe further improve pipeline parallelism, improving the performance of models such as Kimi-K3 and GLM 5.2 by 20%. Click [here](https://gitcode.com/cann/ops-transformer/tree/9.2.0) for details.**

- **Forward and backward computations of sparse attention operators have been extended to cover key phases such as attention computation, sparse index selection, and gradient computation, supporting sparse training of large models. Click [here](https://gitcode.com/cann/ops-transformer/tree/9.2.0/attention) for details.**
<!-- npu="950" id2 -->
- **<term>Ascend 950PR&950DT products</term> support dispatch and combine operations in MoE training. Background communication is initiated by AIV directly driving URMA, and DualPipe scheduling enables parallel computation and communication during training. Click [here](https://gitcode.com/cann/ops-transformer/tree/9.2.0/mc2) for details.**
<!-- end id2 -->
<!-- npu="950" id3 -->
- **<term>Ascend 950PR&950DT products</term> support Engram distributed inference. Engram tables are offloaded to the host memory. The relay capability of URMA and Ubmem enables cross-device access to the remote host memory. Click [here](https://gitcode.com/cann/ops-transformer/tree/9.2.0/mc2) for details.**
<!-- end id3 -->
- **The new PyPTO Pro programming mode further empowers operator developers with hardware control. Click [here](https://gitcode.com/cann/pypto/blob/master/docs/en/guide/introduction.md) for details.**
<!-- npu="950" id4 -->
- **On <term>Ascend 950PR&950DT products</term>, CATLASS now supports Python-style kernel functions and provides an extensive sample library. Click [here](https://gitcode.com/cann/catlass/blob/master/README.md) for details.**
<!-- end id4 -->
- **Operators now support batch consistency computation. Click [here](https://gitcode.com/cann/ops-nn/blob/9.2.0/docs/en/context/batch_consistency.md) for details.**
- **Automatic fusion is now available for inductor routes. Operators such as view, Norm, elementwise, and Concat can be automatically identified and fused, improving model execution performance. Click [here](https://gitcode.com/cann/graph-autofusion/blob/master/docs/en/autofuse/introduction/enable_autofuse_inductor.md) for details.**

## New Features

### Common Modules

- CPU performance tuning:
  - The msboost adaptive core binding tool supports core binding based on NPU->CPU topology affinity ([!65](https://gitcode.com/Ascend/msboost/pull/65)).
  - msboost adds the KAOT OS configuration tuning plugin, which automatically tunes OS configurations to improve performance ([!88](https://gitcode.com/Ascend/msboost/pull/88)).
<!-- npu="950,A3" id5 -->
- CANN adapts to different Ascend hardware products and adds OS compatibility support:
  - The Atlas 900 A3 SuperPoD adapts to ctyunos-2-25.05 and Debian 12.0.
  - The Atlas 950 SuperPoD adapts to CCOS, Velinux, BCLinux, VesselOS, and MTOS.
  - The Atlas 850 SuperPoD and Atlas 850E SuperPoD adapt to Kylin V11.
<!-- end id5 -->
- PyACL has been open-sourced to the runtime repository. For details, see [runtime](https://gitcode.com/cann/runtime/tree/master/python).

### Operator Libraries

#### ops-math
<!-- npu="950" id6 -->
- Ascend 950PR&950DT product adaptation and support:

  - Newly added operators:

    - MatrixSetDiagV2, which supports replacing one or more diagonal elements of the input tensor ([!3961](https://gitcode.com/cann/ops-math/pull/3961)).
    - DropoutV3Grad, which provides the aclnnDropoutV3Grad API and supports computing the backward gradient based on mask and scale ([!4034](https://gitcode.com/cann/ops-math/pull/4034)).

  - Operator functionality enhancements:

    - The BitwiseAnd operator series adds support for the int8, uint8, uint32, and uint64 data types ([!5573](https://gitcode.com/cann/ops-math/pull/5573)).
    - WeightQuantPreprocess adds support for the A16W4 data flow, supporting compact layout conversion of INT4, FP4, and MXFP4 weights ([!4495](https://gitcode.com/cann/ops-math/pull/4495)).
    - ReduceSum and ReduceMean support batch consistency computation ([!3442](https://gitcode.com/cann/ops-math/pull/3442), [!3646](https://gitcode.com/cann/ops-math/pull/3646)).
    - aclnnAngleV2 supports non-contiguous input and output ([!4897](https://gitcode.com/cann/ops-math/pull/4897)).
    - NpuFormatCast adds support for ND-to-FRACTAL_NZ format conversion of the FLOAT4_E1M2 data type ([!3340](https://gitcode.com/cann/ops-math/pull/3340)).

  - Performance tuning:

    - Optimized the sorting performance of the Sort operator by adopting the ping-pong merge strategy ([!5809](https://gitcode.com/cann/ops-math/pull/5809)).
    - Optimized the sorting performance of the TopkV2 operator in small-axis scenarios ([!5939](https://gitcode.com/cann/ops-math/pull/5939)).
    - Optimized the Philox random number generation loop of the DropOutV3 operator to improve computation performance ([!5682](https://gitcode.com/cann/ops-math/pull/5682)).
    - Optimized the performance of the Cdist operator ([!5021](https://gitcode.com/cann/ops-math/pull/5021)).
    - Optimized bool input processing, large trailing-axis double buffering, and loop unrolling of the ConstantPadNd operator to improve padding performance ([!4629](https://gitcode.com/cann/ops-math/pull/4629)).
<!-- end id6 -->
<!-- npu="A3,910b" id7 -->
- Atlas A2 and Atlas A3 product adaptation and support:

  - Operator functionality enhancement:

    - aclnnAngleV2 supports non-contiguous input and output ([!4897](https://gitcode.com/cann/ops-math/pull/4897)).
<!-- end id7 -->

#### ops-cv
<!-- npu="950" id8 -->
- Ascend 950PR&950DT product adaptation and support:

  - Newly added operators:

    - BatchMultiClassNonMaxSuppression, which supports non-maximum suppression by batch and class ([!1176](https://gitcode.com/cann/ops-cv/pull/1176)).
    - CombinedNonMaxSuppression, which supports merging non-maximum suppression results across classes ([!1219](https://gitcode.com/cann/ops-cv/pull/1219)).
    - NonMaxSuppressionV7 ([!1293](https://gitcode.com/cann/ops-cv/pull/1293)).
    - SortedNMS, which supports non-maximum suppression on candidate boxes already sorted by score ([!1236](https://gitcode.com/cann/ops-cv/pull/1236)).
    - RotatedOverlaps, which supports computing the overlap area between two-dimensional rotated boxes ([!1339](https://gitcode.com/cann/ops-cv/pull/1339)).

  - Operator functionality enhancements:

    - CombinedNonMaxSuppression adds support for the FP16 data type and relaxes the iouThreshold value range and candidate box count limits ([!1627](https://gitcode.com/cann/ops-cv/pull/1627)).

  - Performance tuning:

    - CombinedNonMaxSuppression optimizes reduction, data movement, and workspace usage to improve object detection post-processing performance ([!1712](https://gitcode.com/cann/ops-cv/pull/1712)).
<!-- end id8 -->

#### opbase

- Newly added features:
  - The aclnn framework supports strong consistency and batch consistency configuration, and supports deterministic computation and consistency switches taking effect dynamically at the operator level ([!631](https://gitcode.com/cann/opbase/pull/631), [!643](https://gitcode.com/cann/opbase/pull/643)).
  - The reduce template supports batch consistency computation, providing corresponding tiling strategies and kernel scheduling capabilities ([!519](https://gitcode.com/cann/opbase/pull/519)).
  - The aclnn automatic framework supports PCIe passthrough operators, and the broadcast template adds PCIe passthrough scenario identification and scheduling support ([!741](https://gitcode.com/cann/opbase/pull/741), [!742](https://gitcode.com/cann/opbase/pull/742), [!788](https://gitcode.com/cann/opbase/pull/788)).
  - Graph mode aclnn fallback supports two-stage execution encompassing Prepare and Launch ([!740](https://gitcode.com/cann/opbase/pull/740)).
  - A framework for accessing external operator tasks is now available, allowing users to implement selection, tiling, and kernel dispatch on their own ([!962](https://gitcode.com/cann/opbase/pull/962)).
  - The aclnnReselectStaticKernelWithPath API is newly added, supporting loading static operator packages from a custom directory ([!598](https://gitcode.com/cann/opbase/pull/598)).
  - Loading of built-in AI CPU JSON operator packages is supported; custom AI CPU operator loading supports deriving the path from ASCEND_OPP_PATH/vendors ([!666](https://gitcode.com/cann/opbase/pull/666), [!698](https://gitcode.com/cann/opbase/pull/698)).
  - Building and publishing of software packages in DEB/RPM format is supported ([!678](https://gitcode.com/cann/opbase/pull/678)).
  - Added use case design and mixed tolerance design descriptions to the precision standard for open-source operators ([!508](https://gitcode.com/cann/opbase/pull/508)).
  - Enhanced the log maintainability and testability for aclnn framework cache scenarios ([!849](https://gitcode.com/cann/opbase/pull/849)).

- Performance tuning:
  - The ReduceProd template uses tree reduction in AR mode when reducing to a single element, optimizing cumulative multiplication performance ([!690](https://gitcode.com/cann/opbase/pull/690)).

#### ops-nn
<!-- npu="A3,910b" id9 -->
- Atlas A2 and Atlas A3 product adaptation and support:
  - Newly added operators:
    - FusedSgd, which fuses multiple fine-grained operations scattered in the SGD update process, such as gradient scaling, weight decay, momentum update, and parameter assignment, into a single NPU kernel for execution ([!6220](https://gitcode.com/cann/ops-nn/pull/6220)).
    - FusedAdamw, which fuses the AdamW optimizer and supports fusing operations such as parameter update, first-order/second-order momentum update, and gradient scaling of multiple parameter lists (params, grads, expAvgs, expAvgSqs, maxExpAvgSqs, stateSteps) into a single kernel for execution ([!7851](https://gitcode.com/cann/ops-nn/pull/7851)).
    - SituGlu, the SiTU gated linear unit activation function, which splits the input into gate and up halves along a specified dimension, and computes the output according to the SiTU formula ([!8651](https://gitcode.com/cann/ops-nn/pull/8651)).
    - SituGluGrad, the backward gradient computation of the SiTU gated linear unit activation function, which computes the gradient `grad_x` of the input `x` based on the upstream gradient `grad_y` and the forward input `x` ([!8651](https://gitcode.com/cann/ops-nn/pull/8651)).
    - DequantSituQuant, which adds dequant and quant operations before and after the Situ activation function to implement the DequantSituQuant computation of `x` ([!8798](https://gitcode.com/cann/ops-nn/pull/8798)).
    - MatmulEmuSplitWeight, which uses dual-path BF16 GEMM fusion to simulate FP32-precision matrix multiplication, splits the FP32 weight offline into high-bit BF16 and low-bit residual BF16, and performs two BF16 GEMMs with a linear combination during inference ([!9237](https://gitcode.com/cann/ops-nn/pull/9237)).
    - TurboQuant, which normalizes the KV latent of MLA by token and quantizes it into 4-bit codebook indices, and separately outputs the FLOAT16 L2 norm of each token for 4-bit compression of the KV cache ([!10996](https://gitcode.com/cann/ops-nn/pull/10996)).
  - Operator functionality enhancements:
    - aclnnAddmm/Baddbmm/AddmmWeightNz now support bias inputs that require broadcasting ([!8446](https://gitcode.com/cann/ops-nn/pull/8446), [!8784](https://gitcode.com/cann/ops-nn/pull/8784)).
    - aclnnMatmul now supports 8-dimensional inputs ([!8785](https://gitcode.com/cann/ops-nn/pull/8785)).
    - The MatMulV3 operator now provides an AL1 full-load single-core split-K template ([!7504](https://gitcode.com/cann/ops-nn/pull/7504)).
    - The torch_extension framework is newly added, bridging PyTorch APIs with the aclnn operator library through JIT compilation ([!5910](https://gitcode.com/cann/ops-nn/pull/5910)).
    - torch_extension supports independent compilation and packaging of a single operator. Single-operator implementations have been migrated to the operator directory, and the full package and single-operator packages can coexist in isolation ([!7315](https://gitcode.com/cann/ops-nn/pull/7315), [!7686](https://gitcode.com/cann/ops-nn/pull/7686)).
    - torch_extension supports custom operator package paths, which can be specified through ASCEND_CUSTOM_OPP_PATH and can automatically scan the vendors directory, while also supporting multi-vendor operator library lookup and deterministic computation ([!8023](https://gitcode.com/cann/ops-nn/pull/8023), [!8115](https://gitcode.com/cann/ops-nn/pull/8115)).
    - torch_extension exports the cann_ops_nn namespace for invocation in eager mode and graph mode ([!7941](https://gitcode.com/cann/ops-nn/pull/7941)).
<!-- end id9 -->
<!-- npu="950" id10 -->
- Ascend 950PR&950DT product adaptation and support:
  - Newly added operators:
    - SituGlu, the SiTU gated linear unit activation function. It splits the input into gate and up halves along a specified dimension and computes the output according to the SiTU formula ([!8651](https://gitcode.com/cann/ops-nn/pull/8651)).
    - SituGluGrad, the backward gradient computation of the SiTU gated linear unit activation function. It computes the gradient `grad_x` of the input `x` based on the upstream gradient `grad_y` and the forward input `x` ([!8651](https://gitcode.com/cann/ops-nn/pull/8651)).
    - SituMxQuant, which fuses the Situ activation function and dynamic MX (Microscaling) quantization into a single operator ([!8798](https://gitcode.com/cann/ops-nn/pull/8798)).
    - FusedSgd, which fuses multiple fine-grained operations scattered throughout the SGD update process, such as gradient scaling, weight decay, momentum update, and parameter assignment, into a single NPU kernel for execution ([!7877](https://gitcode.com/cann/ops-nn/pull/7877)).
    - FusedAdam, which implements the Adam optimizer functionality and supports multiple parameter lists (TensorList) to complete the functionality in a single call ([!8934](https://gitcode.com/cann/ops-nn/pull/8934)).
    - QuantMatmulActivationQuant, which fuses quantized matrix multiplication, activation, and dynamic quantization. It currently supports gelu and swiglu activations and MX quantization modes ([!7272](https://gitcode.com/cann/ops-nn/pull/7272)).
    - ExpandIntoJaggedPermute, which expands the permutation index of sparse data from the table dimension to the batch dimension, suitable for cases where sparse features have different batch sizes across different ranks ([!8583](https://gitcode.com/cann/ops-nn/pull/8583)).
  - Operator functionality enhancements:
    - QuantBatchMatmulV4 pseudo-quantization MX A8W4 and TCG A8W4 are adapted to Blaze ([!7921](https://gitcode.com/cann/ops-nn/pull/7921), [!9840](https://gitcode.com/cann/ops-nn/pull/9840)).
    - WeightQuantBatchMatmulV2 adds A16W8 ND per-channel and per-tensor Blaze execution paths ([!9877](https://gitcode.com/cann/ops-nn/pull/9877)).
    - Matmul non-quantization templates adapted to TensorAPI/Blaze: ASWT template, BatchMatmul basic template, and broadcast scenarios switch to Tensor APIs ([!2133](https://gitcode.com/cann/ops-nn/pull/2133), [!5087](https://gitcode.com/cann/ops-nn/pull/5087)), BatchMatmul StreamK template switches to Blaze ([!7731](https://gitcode.com/cann/ops-nn/pull/7731)), and the Blaze template is added for IterBatch ([!10543](https://gitcode.com/cann/ops-nn/pull/10543)).
    - QuantBatchMatmulV3 and Matmul support batch consistency computation: under the batch consistency level, StreamK is disabled, and the template selection of full A loading and single-core split-K is fixed under different M values ([!7705](https://gitcode.com/cann/ops-nn/pull/7705), [!11060](https://gitcode.com/cann/ops-nn/pull/11060)).
    - The torch_extension framework is newly added, bridging PyTorch APIs with the aclnn operator library through JIT compilation ([!5910](https://gitcode.com/cann/ops-nn/pull/5910)).
    - torch_extension supports independent compilation and packaging of a single operator. The single operator implementation is migrated to the operator directory, and the full package and single operator package can coexist in isolation ([!7315](https://gitcode.com/cann/ops-nn/pull/7315), [!7686](https://gitcode.com/cann/ops-nn/pull/7686)).
    - torch_extension supports custom operator package paths, which can be specified through ASCEND_CUSTOM_OPP_PATH and can automatically scan the vendors directory, while also supporting multi-vendor operator library lookup and deterministic computation ([!8023](https://gitcode.com/cann/ops-nn/pull/8023), [!8115](https://gitcode.com/cann/ops-nn/pull/8115)).
    - torch_extension exports the cann_ops_nn namespace for invocation in eager mode and graph mode ([!7941](https://gitcode.com/cann/ops-nn/pull/7941)).
  - Performance tuning:
    - QuantBatchMatmulV3 MX scenario tiling optimization, covering base block load balancing, full scale loading in L1, and 4-buffer selection ([!6498](https://gitcode.com/cann/ops-nn/pull/6498)).
    - QuantBatchMatmulV3 MX Basic API supports 3-buffer L1 ([!7237](https://gitcode.com/cann/ops-nn/pull/7237)).
    - QuantBatchMatmul StreamK benefit determination includes Fixpipe write-back overhead ([!9506](https://gitcode.com/cann/ops-nn/pull/9506)).
    - DepthwiseConv2d is split from the general convolution implementation into a dedicated template to optimize the scalar bound ([!5726](https://gitcode.com/cann/ops-nn/pull/5726)).
<!-- end id10 -->

#### ops-transformer
<!-- npu="A3,910b" id11 -->
- Atlas A2 and Atlas A3 product adaptation and support:
  - Newly added operators:
    - MsaIndexScore, supporting MSA sparse block importance scoring ([!9503](https://gitcode.com/cann/ops-transformer/pull/9503)).
    - GenericBlockSparseAttention, GenericBlockSparseAttentionGrad and the accompanying Metadata operators, supporting forward and backward attention computation at custom sparse block granularity ([!10628](https://gitcode.com/cann/ops-transformer/pull/10628), [!10657](https://gitcode.com/cann/ops-transformer/pull/10657), [!11003](https://gitcode.com/cann/ops-transformer/pull/11003), [!11499](https://gitcode.com/cann/ops-transformer/pull/11499)).
    - ChunkKdaFwd, supporting KDA chunked forward computation and BSND, BNSD, TND, and NTD input layouts ([!9979](https://gitcode.com/cann/ops-transformer/pull/9979)).
    - KeyPool and PoolKeyIndexer, supporting key compression and pooled sparse index selection respectively, fusing correlation scoring, TopK selection, and index expansion ([!11500](https://gitcode.com/cann/ops-transformer/pull/11500), [!11513](https://gitcode.com/cann/ops-transformer/pull/11513)).
    - LightningIndexerKLLoss, supporting fused KL divergence loss computation in training scenarios and providing a PyTorch API ([!9615](https://gitcode.com/cann/ops-transformer/pull/9615)).
    - InplacePartialRotaryMul, supporting in-place partial rotary position embedding computation ([!6085](https://gitcode.com/cann/ops-transformer/pull/6085)).
    - BlockAttentionResiduals, supporting forward computation of attention residuals ([!11161](https://gitcode.com/cann/ops-transformer/pull/11161)).
    - BlockAttentionResidualsGrad, supporting backward computation of attention residuals ([!11006](https://gitcode.com/cann/ops-transformer/pull/11006)).
  - Operator functionality enhancements:
    - SparseFlashMla supports sparse selection of the original KV in SWA scenarios, and extends the TopK range of CSA scenarios to 1 8192 ([!9384](https://gitcode.com/cann/ops-transformer/pull/9384), [!11899](https://gitcode.com/cann/ops-transformer/pull/11899), [!11919](https://gitcode.com/cann/ops-transformer/pull/11919)).
    - FusedInferAttentionScore in non-quantized MLA Decode scenarios supports any integer headNum from 1 to 128; the INT8/INT4 pseudo-quantization PageAttention scenario supports non-contiguous the first two axes of the KV cache, and supports non-contiguous scale/offset inputs in PerToken PA and PerTokenHead PA scenarios ([!9773](https://gitcode.com/cann/ops-transformer/pull/9773), [!11069](https://gitcode.com/cann/ops-transformer/pull/11069), [!10263](https://gitcode.com/cann/ops-transformer/pull/10263)).
    - MlaProlog supports non-contiguous first-axis input of the KV cache; the aclnnMlaPrologV4WeightNz API is newly added to control RoPE computation through the doRope parameter ([!10296](https://gitcode.com/cann/ops-transformer/pull/10296), [!9472](https://gitcode.com/cann/ops-transformer/pull/9472)).
    - MlaPreprocess supports non-contiguous first-axis input of kvCache and kvCacheRope ([!6442](https://gitcode.com/cann/ops-transformer/pull/6442)).
    - SparseFlashMlaGrad supports TopK generalization and specifies the actual valid sequence length through the seqused input; SparseLightningIndexerKLLossGrad supports the seqused input and extends the TopK range to 1 8192 ([!11087](https://gitcode.com/cann/ops-transformer/pull/11087), [!9367](https://gitcode.com/cann/ops-transformer/pull/9367), [!11504](https://gitcode.com/cann/ops-transformer/pull/11504)).
    - MixedQuantSparseFlashMla adds TurboQuant TQ4 compressed KV support on the CSA path ([!12425](https://gitcode.com/cann/ops-transformer/pull/12425), [!13418](https://gitcode.com/cann/ops-transformer/pull/13418)).
    - The KvQuantSparseFlashAttention operator adds TurboQuant TQ4 compressed KV support ([!12709](https://gitcode.com/cann/ops-transformer/pull/12709), [!13458](https://gitcode.com/cann/ops-transformer/pull/13458)).
    - RecurrentGatedDeltaRule supports FLOAT32 state input and output ([!5750](https://gitcode.com/cann/ops-transformer/pull/5750)).
    - MoeGatingTopK adds a Hash expert selection mode to obtain expert indices through a mapping table ([!6894](https://gitcode.com/cann/ops-transformer/pull/6894), [!7415](https://gitcode.com/cann/ops-transformer/pull/7415)).
    - MoeGatingTopK adds SqrtSoftplus normalization support ([!11117](https://gitcode.com/cann/ops-transformer/pull/11117)).
    - GroupedMatmul adds graph-mode transpose fusion to eliminate fusible Transpose/TransposeD nodes on the input side and reduce data movement ([!8546](https://gitcode.com/cann/ops-transformer/pull/8546)).
    - MegaMoe extends SiTU, SwiGLU-OAI, and SwiGLU-Step activation support ([!8868](https://gitcode.com/cann/ops-transformer/pull/8868)).
    - On Atlas A3 products, MegaMoe supports elastic scaling, and can skip the corresponding computation and communication through a disabled rank mask ([!9368](https://gitcode.com/cann/ops-transformer/pull/9368)).
    - On Atlas A3 products, AlltoAllvGroupedMatMul and GroupedMatMulAlltoAllv add an AIV communication path ([!11516](https://gitcode.com/cann/ops-transformer/pull/11516), [!11506](https://gitcode.com/cann/ops-transformer/pull/11506)).
    - RopeWithSinCosCacheV2 supports the M-RoPE scenario where mropeSection is [11,11,10] ([!7120](https://gitcode.com/cann/ops-transformer/pull/7120)).
    - MhcPost and MhcPostBackward improve PyTorch graph mode adaptation and support optional hRes input ([!10570](https://gitcode.com/cann/ops-transformer/pull/10570), [!10277](https://gitcode.com/cann/ops-transformer/pull/10277)).
    - MhcPre and MhcPreBackward add adaptation support ([!10035](https://gitcode.com/cann/ops-transformer/pull/10035), [!10049](https://gitcode.com/cann/ops-transformer/pull/10049)).
    - torch_extension supports per-operator independent compilation and customized subpackages, and adopts lazy compilation to compile the required operators on first call ([!9712](https://gitcode.com/cann/ops-transformer/pull/9712), [!8155](https://gitcode.com/cann/ops-transformer/pull/8155), [!9734](https://gitcode.com/cann/ops-transformer/pull/9734)).
    - torch_extension adds input parameter type validation before calling C++ APIs, providing error messages that include parameter names to facilitate locating call issues ([!11968](https://gitcode.com/cann/ops-transformer/pull/11968)).
  - Performance tuning:
    - On Atlas A3 products, MoeDistributeDispatchV2 optimizes hot expert load distribution and communication window layout, improving token sending load balancing and HCCS port distribution ([!9594](https://gitcode.com/cann/ops-transformer/pull/9594), [!10004](https://gitcode.com/cann/ops-transformer/pull/10004)).
<!-- end id11 -->
<!-- npu="950" id12 -->
- Ascend 950PR&950DT product adaptation and support:
  - Newly added operators:
    - GenericBlockSparseAttention, GenericBlockSparseAttentionGrad, and the accompanying Metadata operators. They support forward and backward attention computation with custom sparse block granularity ([!10628](https://gitcode.com/cann/ops-transformer/pull/10628), [!10657](https://gitcode.com/cann/ops-transformer/pull/10657), [!11003](https://gitcode.com/cann/ops-transformer/pull/11003), [!11499](https://gitcode.com/cann/ops-transformer/pull/11499)).
    - ChunkKdaFwd, which supports KDA chunked forward computation and BSND, BNSD, TND, and NTD input layouts ([!9979](https://gitcode.com/cann/ops-transformer/pull/9979)).
    - KeyPool and PoolKeyIndexer, which respectively support key compression and pooled sparse index selection, fusing correlation scoring, TopK selection, and index expansion ([!11500](https://gitcode.com/cann/ops-transformer/pull/11500), [!11513](https://gitcode.com/cann/ops-transformer/pull/11513)).
    - DenseLightningIndexerKLLossGrad, DenseLightningIndexerKLLossGradMetadata, and SparseFlashMlaSoftmaxL1Norm, which improve the dense LightningIndexer backward and loss computation capabilities ([!9237](https://gitcode.com/cann/ops-transformer/pull/9237), [!8956](https://gitcode.com/cann/ops-transformer/pull/8956)).
    - QuantFlashAttn, a fully quantized attention operator, and its accompanying Metadata APIs. They support MXFP8 quantization and HIFLOAT8 PerTensor quantization, and support MXFP8 FlashDecode ([!8968](https://gitcode.com/cann/ops-transformer/pull/8968), [!9573](https://gitcode.com/cann/ops-transformer/pull/9573), [!12516](https://gitcode.com/cann/ops-transformer/pull/12516)).
    - QuantSparseFlashMla and its supporting Metadata operators. They support SWA, CSA, and HCA fully quantized sparse MLA computation and LSE output ([!8499](https://gitcode.com/cann/ops-transformer/pull/8499), [!8760](https://gitcode.com/cann/ops-transformer/pull/8760), [!8762](https://gitcode.com/cann/ops-transformer/pull/8762), [!9167](https://gitcode.com/cann/ops-transformer/pull/9167)).
    - MoeInitRoutingV4 and MoeReRoutingV2, supporting TopK weight reordering synchronized with tokens; MoeInitRoutingV4 supports dynamically passing active_num in graph mode ([!6793](https://gitcode.com/cann/ops-transformer/pull/6793)).
    - AllGatherMatmulV3, supporting the fusion of URMA AllGather with MXFP8/MXFP4 quantized matrix multiplication, and providing the all_gather_quant_matmul PyTorch API ([!10643](https://gitcode.com/cann/ops-transformer/pull/10643)).
    - InplacePartialRotaryMul, supporting in-place partial rotary position embedding computation ([!6085](https://gitcode.com/cann/ops-transformer/pull/6085)).
    - QkvRmsNormRopeCacheWithKScale, fusing Q/K RMSNorm, RoPE/M-RoPE, quantization, and KV cache/K scale cache updates, and supporting M-RoPE MX quantization ([!7023](https://gitcode.com/cann/ops-transformer/pull/7023), [!8974](https://gitcode.com/cann/ops-transformer/pull/8974), [!10557](https://gitcode.com/cann/ops-transformer/pull/10557)).
    - UndGenQkvRmsNormRopeCache, fusing indirect concatenation of QKV in the understanding/generation stages, RMSNorm, MRoPE, and paged KV cache updates ([!9455](https://gitcode.com/cann/ops-transformer/pull/9455)).
    - InplacePartialRotaryMulGrad, supporting in-place gradient computation for partial rotary position embedding ([!6895](https://gitcode.com/cann/ops-transformer/pull/6895)).
    - ApplyRotaryPosEmbGrad, supporting Q/K dual-path RoPE gradient fusion ([!10684](https://gitcode.com/cann/ops-transformer/pull/10684)).
    - BlockAttentionResiduals, supporting forward computation of attention residuals ([!11161](https://gitcode.com/cann/ops-transformer/pull/11161)).
    - BlockAttentionResidualsGrad, supporting backward computation of attention residuals ([!11006](https://gitcode.com/cann/ops-transformer/pull/11006)).
  - Operator functionality enhancement:
    - MsaIndexScore adds support for the FP8 scenario and KV cache first-axis non-contiguous input ([!11876](https://gitcode.com/cann/ops-transformer/pull/11876)).
    - FusedInferAttentionScore in the non-quantized MLA Decode scenario supports any integer headNum from 1 to 128; the INT8/INT4 pseudo-quantization PageAttention scenario supports non-contiguous the first two axes of the KV cache, and supports non-contiguous scale/offset input in PerToken PA and PerTokenHead PA scenarios ([!9773](https://gitcode.com/cann/ops-transformer/pull/9773), [!11069](https://gitcode.com/cann/ops-transformer/pull/11069), [!10263](https://gitcode.com/cann/ops-transformer/pull/10263)).
    - MlaProlog supports non-contiguous first-axis input of the KV cache; the aclnnMlaPrologV4WeightNz API is newly added to control RoPE computation through the doRope parameter ([!10296](https://gitcode.com/cann/ops-transformer/pull/10296), [!9472](https://gitcode.com/cann/ops-transformer/pull/9472)).
    - BlockSparseAttentionGrad supports sparse block granularity that is an integer multiple of 16 ([!10188](https://gitcode.com/cann/ops-transformer/pull/10188)).
    - ChunkGatedDeltaRule adds product adaptation, supporting FLOAT32 state input and non-contiguous first two axes of initial_state ([!8318](https://gitcode.com/cann/ops-transformer/pull/8318), [!8738](https://gitcode.com/cann/ops-transformer/pull/8738), [!8711](https://gitcode.com/cann/ops-transformer/pull/8711)).
    - RecurrentGatedDeltaRule supports FLOAT32 state input and output ([!5750](https://gitcode.com/cann/ops-transformer/pull/5750)).
    - QuantLightningIndexerV2 adds MXFP8 and MXFP4 quantization support ([!9139](https://gitcode.com/cann/ops-transformer/pull/9139)).
    - MoeGatingTopK adds a Hash expert selection mode to obtain expert indices through a mapping table ([!6894](https://gitcode.com/cann/ops-transformer/pull/6894)).
    - MoeInitRoutingV3 supports marking and filtering invalid experts with expertIdx=-1 ([!9708](https://gitcode.com/cann/ops-transformer/pull/9708)).
    - GroupedMatmul adds graph-mode transpose fusion, eliminating fusible Transpose/TransposeD nodes on the input side to reduce data movement ([!8546](https://gitcode.com/cann/ops-transformer/pull/8546)).
    - GroupedMatmul's WeightNz MX quantization supports the "single input, multiple weights, single output" scenario, with the number of TensorLists for weights and corresponding scales expanded to 1024; the non-transposed weight scenario of MXFP8 WeightNz adds FRACTAL_NZ format weight quantization scale support ([!6739](https://gitcode.com/cann/ops-transformer/pull/6739), [!11848](https://gitcode.com/cann/ops-transformer/pull/11848), [!9728](https://gitcode.com/cann/ops-transformer/pull/9728)).
    - GroupedMatmulSwigluQuantV2 supports multi-weight Tensor input in the MX WeightNz scenario; the WeightND scenario relaxes the N-axis alignment constraint, with FP8 supporting 2-alignment and FP4 supporting 4-alignment ([!7302](https://gitcode.com/cann/ops-transformer/pull/7302), [!7662](https://gitcode.com/cann/ops-transformer/pull/7662)).
    - GroupedMatmulSwigluQuantV2 adds A8W8 PerToken WeightNz support, covering INT8, HIF8, FP8, and transposed/non-transposed weight inputs ([!9936](https://gitcode.com/cann/ops-transformer/pull/9936)).
    - GroupedMatmul adds INT8×INT4 (A8W4) and INT4×INT4 (A4W4) quantization support, and the WeightNz MX A8W4 scenario adds FLOAT4_E1M2 weight type support ([!9611](https://gitcode.com/cann/ops-transformer/pull/9611), [!8748](https://gitcode.com/cann/ops-transformer/pull/8748)).
    - GroupedMatmulActivationQuant adds MXFP4 input and FP4 quantization output support in the WeightNz scenario, extending the low-bit computation capability of matrix multiplication, activation, and quantization fusion ([!9279](https://gitcode.com/cann/ops-transformer/pull/9279)).
    - MegaMoe extends SiTU, SwiGLU-OAI, and SwiGLU-Step activation support, where SwiGLU-OAI and SwiGLU-Step are limited to the MTE communication path ([!9667](https://gitcode.com/cann/ops-transformer/pull/9667), [!9971](https://gitcode.com/cann/ops-transformer/pull/9971)).
    - MegaMoe supports shared experts and, under the MTE communication path, supports passing weights and quantization parameter TensorLists separately per expert ([!8822](https://gitcode.com/cann/ops-transformer/pull/8822), [!9493](https://gitcode.com/cann/ops-transformer/pull/9493)).
    - AllGatherMatmulV2 and MatmulReduceScatterV2 add MXFP4 quantization and corresponding graph-mode support ([!7193](https://gitcode.com/cann/ops-transformer/pull/7193), [!8596](https://gitcode.com/cann/ops-transformer/pull/8596), [!8844](https://gitcode.com/cann/ops-transformer/pull/8844), [!9240](https://gitcode.com/cann/ops-transformer/pull/9240)).
    - AllGatherMatmulV2 and MatmulReduceScatterV2 support non-transposed right matrix input in the MX quantization scenario ([!10488](https://gitcode.com/cann/ops-transformer/pull/10488), [!10617](https://gitcode.com/cann/ops-transformer/pull/10617)).
    - MoeEpDispatch and MoeEpCombine adopt the AIV direct-drive URMA communication method, support MoE training scenarios, and provide the ElasticBuffer API, dispatch routing information reuse, and support post-processing operators ([!7807](https://gitcode.com/cann/ops-transformer/pull/7807), [!7814](https://gitcode.com/cann/ops-transformer/pull/7814), [!9388](https://gitcode.com/cann/ops-transformer/pull/9388), [!10249](https://gitcode.com/cann/ops-transformer/pull/10249)).
    - Engram provides distributed table storage in host memory through ElasticBuffer, and works with EngramFetch and EngramFetchWait to implement indexed RDMA remote reads, asynchronous initiation, and waiting ([!7749](https://gitcode.com/cann/ops-transformer/pull/7749), [!7317](https://gitcode.com/cann/ops-transformer/pull/7317)).
    - Engram adds training forward and backward support, completing distributed table queries, cross-card gradient return, and per-entry sparse accumulation through the ElasticBuffer API, and supports outputting sparse gradients for optimizer updates ([!8914](https://gitcode.com/cann/ops-transformer/pull/8914), [!9179](https://gitcode.com/cann/ops-transformer/pull/9179), [!9308](https://gitcode.com/cann/ops-transformer/pull/9308)).
    - InplacePartialRotaryMul adds automatic differentiation support ([!8493](https://gitcode.com/cann/ops-transformer/pull/8493)).
    - MhcPost and MhcPostBackward improve PyTorch graph mode adaptation and support optional hRes input ([!10570](https://gitcode.com/cann/ops-transformer/pull/10570), [!10277](https://gitcode.com/cann/ops-transformer/pull/10277)).
    - MhcPre and MhcPreBackward add the aclnnMhcPreV2 and aclnnMhcPreBackwardV2 APIs, supporting the selection of FP32/HF32 Cube computation modes ([!9243](https://gitcode.com/cann/ops-transformer/pull/9243), [!12232](https://gitcode.com/cann/ops-transformer/pull/12232)).
    - MhcPreSinkhorn and MhcPreSinkhornBackward add TND format support and supplement GE graph mode adaptation for the forward and backward operators ([!10272](https://gitcode.com/cann/ops-transformer/pull/10272), [!9519](https://gitcode.com/cann/ops-transformer/pull/9519), [!8382](https://gitcode.com/cann/ops-transformer/pull/8382)).
    - torch_extension supports per-operator independent compilation and customized subpackages, and adopts lazy compilation to compile the required operators on first invocation ([!9712](https://gitcode.com/cann/ops-transformer/pull/9712), [!8155](https://gitcode.com/cann/ops-transformer/pull/8155), [!9734](https://gitcode.com/cann/ops-transformer/pull/9734)).
    - torch_extension adds input parameter type validation before calling C++ APIs, providing error messages that include parameter names to facilitate locating invocation issues ([!11968](https://gitcode.com/cann/ops-transformer/pull/11968)).
  - Performance tuning:
    - Performance tuning for the MLA scenario of KvQuantSparseFlashAttention, reducing Vector-side computation overhead ([!10428](https://gitcode.com/cann/ops-transformer/pull/10428)).
    - MoeInitRoutingV3 optimizes the performance of MXFP8 quantization, pass-through, and FP8 grouped quantization scenarios ([!9199](https://gitcode.com/cann/ops-transformer/pull/9199)).
    - Optimized the A8W4/A4W4 Wave pipeline scheduling of MegaMoe on the MTE communication path to improve the pipeline overlap efficiency of Dispatch, expert computation, and Combine ([!10092](https://gitcode.com/cann/ops-transformer/pull/10092), [!10319](https://gitcode.com/cann/ops-transformer/pull/10319), [!10302](https://gitcode.com/cann/ops-transformer/pull/10302)).
    - Optimized the computation pipeline of MhcPre and MhcPreBackward ([!9243](https://gitcode.com/cann/ops-transformer/pull/9243), [!12232](https://gitcode.com/cann/ops-transformer/pull/12232)).
<!-- end id12 -->

### Graph Engine

#### Graph Mode

- Added Python APIs for custom Pass development and custom operator development, supporting writing custom Passes and integrating custom operators in the Python environment. ([!4147](https://gitcode.com/cann/ge/pull/4147), [!4254](https://gitcode.com/cann/ge/pull/4254), [!4388](https://gitcode.com/cann/ge/pull/4388))
- Added a host CPU operator registration API, supporting custom host CPU operators integrated in constant folding optimization and scheduling during dynamic shape execution. ([!4481](https://gitcode.com/cann/ge/pull/4481), [!4538](https://gitcode.com/cann/ge/pull/4538), [!4918](https://gitcode.com/cann/ge/pull/4918))
- Added automatic multi-stream parallel optimization for dynamic shape, which can be enabled through ge.autoMultistreamParallelMode; ATC added the multi_stream_parallel_mode parameter, supporting enabling automatic multi-stream optimization in offline inference scenarios. ([!3781](https://gitcode.com/cann/ge/pull/3781), [!4184](https://gitcode.com/cann/ge/pull/4184), [!4301](https://gitcode.com/cann/ge/pull/4301))
- Optimized the usability of the RunGraphWithStreamAsync API. In static shape scenarios, when the user has not registered an external Allocator, automatic output memory allocation is also supported. ( [!3306](https://gitcode.com/cann/ge/pull/3306))
- Supported PCIe operator graph integration and provided the operator PCIe Through capability declaration. ([!430](https://gitcode.com/cann/metadef/pull/430), [!4394](https://gitcode.com/cann/ge/pull/4394))
- Added dynamic shape scheduling performance tuning in host input scenarios, performing Codegen fusion on operators that execute consecutively on the host CPU to further improve performance. ( [!3626](https://gitcode.com/cann/ge/pull/3626), [!4669](https://gitcode.com/cann/ge/pull/4669))

#### Automatic Fusion

- Added support for enabling automatic fusion in inductor, supporting view-type operators (transpose/slice/broadcast), generic Norm-type operators, elementwise-type operators, Concat operators, and CV fusion. ([!1654](https://gitcode.com/cann/graph-autofusion/pull/1654), [!1250](https://gitcode.com/cann/graph-autofusion/pull/1250), [!2689](https://gitcode.com/cann/ge/pull/2689), [!1626](https://gitcode.com/cann/graph-autofusion/pull/1626), [!1700](https://gitcode.com/cann/graph-autofusion/pull/1700))
- Added compilation performance tuning. ([!1799](https://gitcode.com/cann/graph-autofusion/pull/1799), [!1591](https://gitcode.com/cann/graph-autofusion/pull/1591))
- Improved the AscendLoopIR completeness. ([!1699](https://gitcode.com/cann/graph-autofusion/pull/1699), [!1749](https://gitcode.com/cann/graph-autofusion/pull/1749))
- Added support for NDDMA performance modeling and ATT modeling optimization. ([!1690](https://gitcode.com/cann/graph-autofusion/pull/1690), [!1792](https://gitcode.com/cann/graph-autofusion/pull/1792), [!1266](https://gitcode.com/cann/graph-autofusion/pull/1266), [!1460](https://gitcode.com/cann/graph-autofusion/pull/1460), [!1580](https://gitcode.com/cann/graph-autofusion/pull/1580), [!534](https://gitcode.com/cann/graph-autofusion/pull/534), [!1208](https://gitcode.com/cann/graph-autofusion/pull/1208))

### Operator Programming

#### Key Features
<!-- npu="950" id13 -->
- C APIs:
  - On <term>Ascend 950PR&950DT products</term>, this release adds the `asc_lock` and `asc_unlock` APIs ([!5216](https://gitcode.com/cann/asc-devkit/pull/5216)), and completes some APIs and their supported data types ([!5168](https://gitcode.com/cann/asc-devkit/pull/5168)).
<!-- end id13 -->
- Tensor APIs:
  - Adds the conv2D functionality ([!4239](https://gitcode.com/cann/asc-devkit/pull/4239)).
  - Adds the Dump functionality for extra-large tensors ([!6371](https://gitcode.com/cann/asc-devkit/pull/6371)).
<!-- npu="950" id14 -->
- SuperKernel:
  - Added SuperKernel support for the npugraph_ex path for <term>Ascend 950PR&950DT products</term> ([!430](https://gitcode.com/cann/graph-autofusion/pull/430)).
<!-- end id14 -->
- Basic APIs:
  - Ascend C supports dump, printf, and assert in FIFO mode within SIMD VF ([!4829](https://gitcode.com/cann/asc-devkit/pull/4829)).
- SIMT APIs:
  - Optimized API precision to support subnormal ([!6028](https://gitcode.com/cann/asc-devkit/pull/6028)).
- Communication APIs:
  - Added the AIN API, providing one-sided communication such as Put/Get/Signal/Flush based on symmetric windows and barrier synchronization capabilities ([!59](https://gitcode.com/cann/asc-comm/pull/59)).

#### Sample Updates

- C API samples:
  - Added 8 data movement scenario samples, 19 single-instruction reg samples, 7 matrix computation samples, 2 doublebuffer optimization samples, and 1 fused operator best practice sample ([!5346](https://gitcode.com/cann/asc-devkit/pull/5346)).
- Tensor API samples:
  - Added a convolution sample, supporting the conv2D functionality ([!4316](https://gitcode.com/cann/asc-devkit/pull/4316)).
  - Added samples such as bank_conflict, matmul_bias_fusion, matmul_split_k, conv2d_forward, and batch_matmul ([!6163](https://gitcode.com/cann/asc-devkit/pull/6163)).
  - Added a custom Op sample ([!6174](https://gitcode.com/cann/asc-devkit/pull/6174)).
- Communication API samples:
  - Added the AIN basic_ring sample, demonstrating point-to-point one-sided communication by the AIV Kernel calling Put/Get through the AIN API in a multi-card ring scenario ([!80](https://gitcode.com/cann/asc-comm/pull/80)).

<!-- npu="950" id15 -->
### PyPTO

#### Support for Developing Operators with PyPTO Pro on Ascend 950PR&950DT Products

- Newly added PyPTO Pro fused operator development APIs:
  - Generalization support for cube-side tile-granularity matrix movement and computation in quantized and non-quantized scenarios ([!5399](https://gitcode.com/cann/pypto/pull/5399), [!5439](https://gitcode.com/cann/pypto/pull/5399)).
  - Generalization support for vector-side tile-granularity data movement, with simultaneous support for three vector computation modes: SIMD RegBase, SIMT, and SIMD Tile ([!4925](https://gitcode.com/cann/pypto/pull/4925), [!5341](https://gitcode.com/cann/pypto/pull/5341), [!4946](https://gitcode.com/cann/pypto/pull/4946)).
  - Generalization support for Mix fused operator development and pipeline orchestration ([!4725](https://gitcode.com/cann/pypto/pull/4725), [!4925](https://gitcode.com/cann/pypto/pull/4925)).

- Newly added PyPTO Pro usability improvements:
  - Automatic intra-core synchronization ([!4725](https://gitcode.com/cann/pypto/pull/4725), [!6209](https://gitcode.com/cann/pypto/pull/6209)).
  - Automatic inter-core pipeline orchestration ([!4690](https://gitcode.com/cann/pypto/pull/4690), [!5332](https://gitcode.com/cann/pypto/pull/5332), [!6038](https://gitcode.com/cann/pypto/pull/6038)).

- Newly added PyPTO Pro operator network integration capabilities:
  - Direct invocation in eager mode ([!4695](https://gitcode.com/cann/pypto/pull/4695)).
  - aclGraph graph mode ([!4695](https://gitcode.com/cann/pypto/pull/4695)).
    - Generating operator binaries using the aclnn method in the ops-transformer repository ([!4695](https://gitcode.com/cann/pypto/pull/!4695), [!6614](https://gitcode.com/cann/pypto/pull/6614)).
    - Profiling data collection ([!6221](https://gitcode.com/cann/pypto/pull/6221), [!6306](https://gitcode.com/cann/pypto/pull/!6306), [!6634](https://gitcode.com/cann/pypto/pull/!6634)).
    - Memory out-of-bounds detection tool ([!5668](https://gitcode.com/cann/pypto/pull/5668)).
<!-- end id15 -->

#### Continuous Improvement of PyPTO Tensor Programming

- Newly added feature support:
  - IR refactoring: `@pypto.frontend.jit` has switched to the new IR by default ([!5152](https://gitcode.com/cann/pypto/pull/5152)).
  - If/For control flow statements support returning symbolic scalars (yield), and computation results within control flow can participate in subsequent computation and dynamic shape derivation ([!5465](https://gitcode.com/cann/pypto/pull/5465)).
  - Synchronizing the computation determinism level with torch_npu (0: off, 1: deterministic, 2: strong consistency). The JIT compilation entry automatically reads the torch_npu process-level setting and writes it into the compilation configuration, ensuring consistency between the coding side and torch_npu ([!5622](https://gitcode.com/cann/pypto/pull/5622)).

- Performance tuning:
  <!-- npu="950" id20 -->
  - The RadixSelect algorithm path of the TopK API on <term>Ascend 950PR&950DT products</term> is optimized by reducing the number of instructions to improve sorting performance ([!5239](https://gitcode.com/cann/pypto/pull/5239)).
  <!-- end id20 -->
  - A vector sorting algorithm is added to the pre-scheduling stage of out-of-order execution to reduce the number of L1 spills ([!5469](https://gitcode.com/cann/pypto/pull/5469)).

### Runtime

- Supports blocking debug mode for Kernel Launch and model execution ([!4247](https://gitcode.com/cann/runtime/pull/4247)).
- Supports ordered cross-stream execution of the same captured model in aclGraph ([!4479](https://gitcode.com/cann/runtime/pull/4479)).
- Added PCI Bus ID bidirectional query APIs: aclrtDeviceGetPCIBusId and aclrtDeviceGetByPCIBusId ([!4066](https://gitcode.com/cann/runtime/pull/4066)).
<!-- npu="950" id16 -->
### Communication Library

#### Collective Communication

- <term>Ascend 950PR&950DT products</term> support extending custom algorithms in the experimental directory, improving the ease of ecosystem extension ([!2734](https://gitcode.com/cann/hccl/pull/2734)).
- <term>Ascend 950PR&950DT products</term> support symmetric memory capability in URMA scenarios, allowing users to register symmetric windows through HcclCommSymWinRegister, improving the ease of operator algorithm implementation ([!2369](https://gitcode.com/cann/hcomm/pull/2369) and [!1195](https://gitcode.com/cann/hccl/pull/1195)).
- <term>Ascend 950PR&950DT products</term> support flexible CCU resource application, improving the flexibility of custom CCU operators ([!3367](https://gitcode.com/cann/hcomm/pull/3367)).
- <term>Ascend 950PR&950DT products</term> provide host NIC implementation extension capability, supporting flexible extension of hcomm API implementations ([!4257](https://gitcode.com/cann/hcomm/pull/4257)).

#### HIXL One-Sided Communication

- HIXL adds support for the UB_RTP transport protocol for data transfer between NPUs on the Ascend 950 platform ([!612](https://gitcode.com/cann/hixl/pull/612), [!818](https://gitcode.com/cann/hixl/pull/818)).
- HIXL supports multi-channel concurrent transmission to improve link bandwidth utilization ([!940](https://gitcode.com/cann/hixl/pull/940), [!1024](https://gitcode.com/cann/hixl/pull/1024), [!1026](https://gitcode.com/cann/hixl/pull/1026), [!1318](https://gitcode.com/cann/hixl/pull/1318)).
- HIXL supports configuring the maximum number of transfer tasks per batch and the maximum number of active channels to control communication resource overhead ([!1105](https://gitcode.com/cann/hixl/pull/1105), [!704](https://gitcode.com/cann/hixl/pull/704)).
- HIXL adds a transfer exception reporting mechanism to promptly detect underlying communication faults ([!681](https://gitcode.com/cann/hixl/pull/681), [!787](https://gitcode.com/cann/hixl/pull/787)).
- FabricMem mode supports AICPU unrolling optimization to further improve transfer performance ([!839](https://gitcode.com/cann/hixl/pull/839)).
- HIXL provides Python API capabilities, released externally as a wheel package ([!658](https://gitcode.com/cann/hixl/pull/658), [!903](https://gitcode.com/cann/hixl/pull/903)).

<!-- end id16 -->
### PTO Virtual Instruction Set

- Basic vector & cube instructions:
  - Newly added support for 64-bit data types ([!1711](https://gitcode.com/cann/pto-isa/pull/1711), [!1585](https://gitcode.com/cann/pto-isa/pull/1585), [!1428](https://gitcode.com/cann/pto-isa/pull/1428)).
  - TMOV/TEXTRACT/TINSERT newly added support for layout format conversion ([!1450](https://gitcode.com/cann/pto-isa/pull/1450), [!1459](https://gitcode.com/cann/pto-isa/pull/1459), [!1718](https://gitcode.com/cann/pto-isa/pull/1718)).
  - TPUSH/TPOP added support for odd splitting ([!1380](https://gitcode.com/cann/pto-isa/pull/1380)).
- Communication instructions:
  - TPUT_ASYNC and TGET_ASYNC added cross-machine RDMA communication capability for A5 based on the 1825 NIC ([!1374](https://gitcode.com/cann/pto-isa/pull/1374)).
  - Newly added TPUT_ASYNC_NOTIFY instruction ([!1516](https://gitcode.com/cann/pto-isa/pull/1516)).
- CostModel simulation: integrated full A2/A3 latency PTO ISA instruction performance prediction, achieving 90%+ for cycles prediction accuracy ([!1674](https://gitcode.com/cann/pto-isa/pull/1674)).
- CPU-SIM: newly added CPU simulation instructions synchronized with the NPU.

### PTOAS (PTO Assembler)

A new toolchain is added, supporting command-line compilation, PTO ISA specification compilation, Python binding, and script-based entry construction capabilities. Its main responsibilities are as follows:

  - Parse PTO bytecode files.
  - Verify PTO ISA structure, types, and target-related constraints.
  - Support processing key capabilities such as layout, address, and synchronization according to user-specified compilation options.
  - Emit callable code.

### Debugging and Analysis Tools

- Profiling supports collecting the number of page faults of a task ([!3279](https://gitcode.com/cann/runtime/pull/3279)).
- The aclrt APIs now additionally report profiling data such as memory size and copy direction ([!3644](https://gitcode.com/cann/runtime/pull/3644)).

### Diagnostics

- aicore err supports automatic parsing of error line numbers ([!4080](https://gitcode.com/cann/runtime/pull/4080)).

## Removed and Deprecated Features

### Description

- Deleted features are those that have been removed in the current version.
- Deprecated features are those marked as deprecated in the current version and will be removed in future versions.
- Replace `${install_path}` in this section with the CANN software installation path.

### Operator Programming

#### C APIs

- Deprecated all synchronous APIs ending with `_sync` ([!5789](https://gitcode.com/cann/asc-devkit/pull/5789)).
- Deprecated the v1 to v4 APIs and provided corresponding replacement APIs ([!3710](https://gitcode.com/cann/asc-devkit/pull/3710)).
- Deprecated the `asc_get_block_num` and `asc_get_block_idx` APIs, guiding users to use compiler keywords ([!5216](https://gitcode.com/cann/asc-devkit/pull/5216)).

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
| All header files in `${install_path}/cann/pkg_inc/runtime/runtime` the directory will be deprecated | No related functions will be provided in subsequent versions                                           |
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
| The rtRegTaskFailCallbackByModule API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtExceptionInfoCallbackRegister and aclrtExceptionInfoCallbackUnregister API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetIpcMemorySuperPodPid API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtIpcMemImportPidInterServer API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetIpcNotifySuperPodPid API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtNotifySetImportPidInterServer API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetTaskAbortCallBack API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtSetTaskAbortCallBack API in `${install_path}/cann/include/acl/aclrt.h` instead |
| The rtSetTaskFailCallback API in `${install_path}/ascend-toolkit/latest/toolkit/include/experiment/runtime/runtime/rt_base.h` | Use the aclrtExceptionInfoCallbackRegister and aclrtExceptionInfoCallbackUnregister API in `${install_path}/cann/include/acl/aclrt.h` instead |
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

Starting from Ascend 950PR&950DT products, the aclblas and aclop APIs are no longer recommended. They will be gradually deprecated in later versions. Migrate to the corresponding aclnn operator APIs.
<!-- end id17 -->
### Operator Libraries

- **Incompatible changes**:
  - The implementation and registration configuration of the kth_value, median, and nan_median operators have been migrated from ops-math to ops-nn. To use these operators, upgrade the ops-nn component accordingly ([!5809](https://gitcode.com/cann/ops-math/pull/5809), [!10728](https://gitcode.com/cann/ops-nn/pull/10728)). These operators have been migrated from the `ops_proto_math.h` and `es_math` directories to the `ops_proto_nn.h` and `es_nn` directories.
  - The RoiPooling operator is migrated from ops-cv to ops-nn. To use this operator, upgrade the ops-nn component accordingly to avoid prototype definition conflicts after the upgrade ([!1442](https://gitcode.com/cann/ops-cv/pull/1442), [!9609](https://gitcode.com/cann/ops-nn/pull/9609)). This operator is migrated from the `ops_proto_cv.h` and `es_cv` directories to the `ops_proto_nn.h` and `es_nn` directories.

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

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and are planned for removal in versions after December 30, 2026.**

Operators are split into component packages. Each independent operator component package contains multiple corresponding libraries and header files. In the following table, `${ops_project}` represents the actual cv, math, nn, transformer, and legacy.

| Deprecated Item | Replacement |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ${install_path}/ascend-toolkit/latest/opp/built-in/op_proto/inc/*.h | ${install_path}/cann/opp/built-in/op_graph/inc/\${ops_project}_ops_proto.h |
| ${install_path}/ascend-toolkit/latest/lib64/libopapi.so      | ${install_path}/cann/lib64/libopapi_\${ops_project}.so |
| aclnnGroupedMatMulAllReduce API                        | aclnnMatmulAllReduce                                                 |
| aclnnWeightQuantBatchMatmul API                        | aclnnWeightQuantBatchMatmulV3 API                      |
| aclnnQuantMatmul, aclnnQuantMatmulV2, aclnnQuantMatmulV3, and aclnnQuantMatmulV4 APIs | aclnnQuantMatmulV5 API                                 |
| aclnnGroupedMatmul, aclnnGroupedMatmulV2, aclnnGroupedMatmulV3, and aclnnGroupedMatmulV4 APIs | aclnnGroupedMatmulV5 API                               |
| aclnnIncreFlashAttentionV2 and aclnnIncreFlashAttentionV3 APIs | aclnnIncreFlashAttentionV4 API                         |
| aclnnPromptFlashAttentionV2 API                        | aclnnPromptFlashAttentionV3 API                        |
| aclnnFusedInferAttentionScoreV2 and aclnnFusedInferAttentionScoreV3 APIs | aclnnFusedInferAttentionScoreV4 API                    |

### Acceleration Libraries

**The following directories, files, and APIs are marked as deprecated in CANN 8.5.0 and will be removed in versions after December 30, 2026.**

The DVPP acceleration function used by the following operator IRs is deprecated: Crop, CropAndResize, DecodeAndCropJpeg, DecodeJpeg, PadV3D, Resize, ResizeV2, ResizeBicubic, ResizeBilinearV2, ResizeNearestNeighborV2, ReverseV2, WarpPerspective, WarpAffineV2, AdjustContrast, AdjustHue, AdjustSaturation.

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

**The following directories, files, and APIs are marked as deprecated in CANN 9.2.0 and will be removed in later versions after September 30, 2027.**

| Deprecated Item | Replacement |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|  Environment variable `ASCEND_SLOG_PRINT_TO_STDOUT` | Environment variable `ASCEND_LOG_PRINT_TO_STDOUT` |

<!-- npu="950,A3,910b" id18 -->
## Fixed Issues

The following issues are fixed in version 9.2.0:

- Fixed the issue where the HF32 attribute was not correctly passed to the bottom layer, causing performance degradation, when the NPU MM operators on Atlas A2 products, Atlas A3 products, and Ascend 950PR&950DT products were executed through the GE aclnn fallback callback path.
- Fixed the precision issue of the RMSNorm operator on Atlas A2 products and Atlas A3 products when the input shape exceeds the int32 maximum value.
- Fixed the issue where the `_deterministic_level` attribute was not inherited when the matmul operator fusion path on Atlas A2 products and Atlas A3 products was converted to matmulv2, causing the attributes of subsequent nodes to be lost.
- Fixed the issue where the fine-grained FSDP communication and computation pipeline was blocked due to host-side performance degradation of the Matmul operators on Atlas A2 products and Atlas A3 products, causing overall model performance degradation.
- Fixed the issue where the FAG operator occasionally failed to fully clear the pad in EOD scenarios.
- Fixed the issue where the orderStream graph rule validation failed when aclrGraph AICPU unrolling used the same stream for the HCCL main stream and the capture stream on Atlas A3 products.
- Fixed the issue where the AllGatherRingConcurrentDirect algorithm deadlocked when dispatching primary/standby stream tasks in large-scale clusters on Atlas A3 products.
- Fixed the issue where the RingMLAOperation API demo failed to run when importing environment variables from a non-mainline version on Atlas A2 and Atlas A3 products.
- Fixed the issue where `torch_npu.npu_format_cast` fell back from interception to aclop when the format and shape did not match on Atlas A2 and Atlas A3 products.
- (**Incompatible change**) Fixed the issue where the default values of the torch API parameters of the SparseFlashMLA operator were incorrect on Atlas A2 and Atlas A3 products (ori_mask_mode, cmp_mask_mode, ori_win_left, ori_win_right).
- Fixed the issue on Ascend 950PR&950DT products where, within the same process on the same card, the creation of a sub-communication domain failed when the rank size of the previously created communication domain was smaller than the rank size of the sub-communication domain to be created next.
<!-- end id18 -->

## Documentation Changes

### Programming Language

#### Ascend C Operator Development

- Added L2 cache partitioning optimization description ([!5418](https://gitcode.com/cann/asc-devkit/pull/5418)).
- Added usage description for new features of NPU architecture version 3510 ([!5265](https://gitcode.com/cann/asc-devkit/pull/5265)).
- Optimized and adjusted the "aclnn Operator Engineering Development" section by adding recommended reading paths, quick start, and other content ([!3929](https://gitcode.com/cann/asc-devkit/pull/3929)).
- Added the "Advanced Programming > Memory Model" section, introducing the concepts, principles, common issues, and solutions of cache consistency and memory consistency ([!5150](https://gitcode.com/cann/asc-devkit/pull/5150)).
- Added the "Tensor-Based C++ Programming" section ([!3187](https://gitcode.com/cann/asc-devkit/pull/3187)).
- Added the "Atomic Operation Instruction Optimization" section ([!4710](https://gitcode.com/cann/asc-devkit/pull/4710)).

#### PyPTO Operator Development

Added support for the PyPTO Pro development mode, supporting the tile-oriented programming model ([!4999](https://gitcode.com/cann/pypto/pull/4999), [!5093](https://gitcode.com/cann/pypto/pull/5093)).

#### Graph Development

- The "Custom Operator Graph Integration" section has undergone feature adjustments and structural reorganization.
- Optimized the "AutoFuse Automatic Fusion" section:
  - Reorganized the directory structure, added "Quick Start" and "Enabling AutoFuse" sections, and moved the detailed description of environment variables to the "Appendix" section.
  - The "Enabling AutoFuse" chapter introduces the automatic fusion enabling modes through two separate paths, and adds the fusion enabling method under the Inductor path.

### Compiler

#### PTOAS

Added the *PTOAS* document. For details, see [PTOAS](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/compiler/ptoas/overview/what_is_ptoas.md).

### Communication Library

#### HCCL Collective Communication Library

Optimized three fault cases in sections "Link Establishment Timeout", "notify_wait Timeout", and "Communication Domain Link Establishment Timeout Background" ([!2782](https://gitcode.com/cann/hccl/pull/2782)).

### API Reference
<!-- npu="950" id19 -->
#### Ascend C APIs

- The "C API" chapter was restructured for Ascend 950PR&950DT products, refining the directory structure, optimizing the internal structure of the documentation, and improving the API function descriptions, invocation examples, and constraint descriptions ([!5266](https://gitcode.com/cann/asc-devkit/pull/5266)).
- The "Tensor API" chapter improves the documentation for cube_compute_load/store, layout_structure, data_move, tensor_structure, and others ([!5134](https://gitcode.com/cann/asc-devkit/pull/5134)).
- Optimized the "SIMT APIs" chapter:
  - Added the UB reuse layout rule description ([!6077](https://gitcode.com/cann/asc-devkit/pull/6077)).
  - Updated the precision description of the math library APIs ([!6047](https://gitcode.com/cann/asc-devkit/pull/6047)).
  - Added grid_group and thread_group descriptions to the cooperative groups ([!4795](https://gitcode.com/cann/asc-devkit/pull/4795), [!5651](https://gitcode.com/cann/asc-devkit/pull/5651)).
  - Added the "SIMT Instruction Theoretical Performance Summary" chapter ([!5543](https://gitcode.com/cann/asc-devkit/pull/5543)).
  - Added integer conversion functions ([!5170](https://gitcode.com/cann/asc-devkit/pull/5170)).
  - Added compilation options used in SIMT programming scenarios ([!5035](https://gitcode.com/cann/asc-devkit/pull/5035)).
- Added the "CheckOpResSufficient" section ([!5766](https://gitcode.com/cann/asc-devkit/pull/5766)).
<!-- end id19 -->

#### PyPTO APIs

Added the PyPTO Pro API chapter ([!4991](https://gitcode.com/cann/pypto/pull/4991)).

#### Operator Library APIs

A new "NN APIs" section is added to "Operator Library > Operator APIs (torch_extension)" in the *Operator Library* document.

### Debugging and Analysis Tools

#### Performance Tuning Tool

- The directory structure is adjusted, with chapters flattened by the collection tool.
- The sections for Ascend PyTorch tuning tool, MindSpore tuning tool, collecting performance data using TensorFlow framework APIs, and collecting performance data using acl Python APIs are adjusted to be published in their respective source documents. The *Performance Tuning Tool* document retains jump links in its introduction.

#### Memory Analysis Tool

- Added a device memory OOM analysis item. When OOM occurs, dump the latest and maximum memory block information.
- Added support for collecting process device memory curves and full-card device memory curves.
- Added documentation for the host memory leak detection feature.

#### AMCT Model Compression Tool

Added the quantization features and API description for the [AMCT (acl)](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/devaids/amct/atlasamct_16_0301.html) scenario.

## Open Source Software Statement

For the open source software statement, see [Open Source Software Statement](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/maintenref/refdoc/refer003.html).

## Fixed Vulnerabilities

For details about the fixed vulnerabilities for open-source and third-party software in this version, see [Fixed Vulnerabilities](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/maintenref/refdoc/refer002.html).

## Virus Scan Report

For the virus scan report, see [Virus Scan Report](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/920/maintenref/refdoc/refer004.html).
