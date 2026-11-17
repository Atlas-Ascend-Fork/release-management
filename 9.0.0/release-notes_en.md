# CANN 9.0.0 Release Notes

## Version Download Address

<a href="https://www.hiascend.com/en-sg/cann/download?versionId=731&ids=d806%2Ch0502%2Ch0601%2Ch0702">Quick Installation</a>

## Version Mapping

**1.Mapping between CANN and driver versions**

| CANN | Ascend HDK Version |
| -- | -- |
| [CANN 9.0.0](https://www.hiascend.com/en/cann/download?versionId=731&ids=d806%2Ch0502%2Ch0601%2Ch0702) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1) <br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2) <br> [Ascend HDK 25.5.1](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1)|
| [CANN 8.5.2](https://www.hiascend.com/en/cann/download?versionId=730&ids=d803%2Ch0501%2Ch0601%2Ch0702) | [Ascend HDK 26.0.RC1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+26.0.RC1) <br> [Ascend HDK 25.5.2 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.2) <br> [Ascend HDK 25.5.1 ](https://www.hiascend.com/hardware/firmware-drivers/community?product=4&model=32&cann=All&driver=Ascend+HDK+25.5.1)|

**2.CANN package mapping**

| ops Version | Matching Toolkit Version |
| -- | -- |
| [ascend-cann-ops 9.0.0](https://www.hiascend.com/en/cann/download?versionId=731&ids=d806%2Ch0502%2Ch0601%2Ch0702) | [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/en/cann/download?versionId=731&ids=d806%2Ch0502%2Ch0601%2Ch0702)<br>[ascend-cann-toolkit 8.5.2](https://www.hiascend.com/en/cann/download?versionId=730&ids=d803%2Ch0501%2Ch0601%2Ch0702) |
| [ascend-cann-ops 8.5.2](https://www.hiascend.com/en/cann/download?versionId=730&ids=d803%2Ch0501%2Ch0601%2Ch0702) | [ascend-cann-toolkit 9.0.0](https://www.hiascend.com/en/cann/download?versionId=731&ids=d806%2Ch0502%2Ch0601%2Ch0702) <br> [ascend-cann-toolkit 8.5.2](https://www.hiascend.com/en/cann/download?versionId=730&ids=d803%2Ch0501%2Ch0601%2Ch0702) |

**3.Matching Relationship of Independently Upgradable Subpackages within CANN ops**

| CANN subpackage version                                         | Version source code tag                                        | Matching CANN version                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| [cann-ops-math 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-math/tags/v9.0.0)     | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-nn 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-nn/tags/v9.0.0)        | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-cv 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-cv/tags/v9.0.0)        | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-ops-transformer 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/ops-transformer/tags/v9.0.0) | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hccl 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/hccl/tags/v9.0.0)          | CANN 9.0.0<br>CANN 8.5.2 |
| [cann-hixl 9.0.0](https://ascend.devcloud.huaweicloud.com/cann/run/software/9.0.0/) | [v9.0.0](https://gitcode.com/cann/hixl/tags/v9.0.0)          | CANN 9.0.0<br>CANN 8.5.2 |

**4.Matching Relationship of Open-Source Upgradable Subpackages within CANN ops**

| CANN subpackage version | Version source code tag | Matching CANN version |
| ---------------------------------- | ------------------------------------------------------------ | ----------------- |
| cann-opbase 9.0.0           | [v9.0.0](https://gitcode.com/cann/opbase/tags/v9.0.0) | CANN 9.0.0 |
| cann-oam-tools 9.0.0        | [v9.0.0](https://gitcode.com/cann/oam-tools/tags/v9.0.0)     | CANN 9.0.0   |
| cann-asc-tools 9.0.0        | [v9.0.0](https://gitcode.com/cann/asc-tools/tags/v9.0.0)     | CANN 9.0.0   |
| cann-asc-devkit 9.0.0       | [v9.0.0](https://gitcode.com/cann/asc-devkit/tags/v9.0.0)    | CANN 9.0.0   |
| cann-pto-isa 9.0.0          | [v9.0.0](https://gitcode.com/cann/pto-isa/tags/v9.0.0)       | CANN 9.0.0   |
| cann-ge-compiler 9.0.0      | [v9.0.0](https://gitcode.com/cann/ge/tags/v9.0.0)            | CANN 9.0.0   |
| cann-ge-executor 9.0.0      | [v9.0.0](https://gitcode.com/cann/ge/tags/v9.0.0)            | CANN 9.0.0   |
| cann-graph-autofusion 9.0.0 | [v9.0.0](https://gitcode.com/cann/graph-autofusion/tags/v9.0.0) | CANN 9.0.0 |
| cann-metadef 9.0.0          | [v9.0.0](https://gitcode.com/cann/metadef/tags/v9.0.0)       | CANN 9.0.0 |
| cann-dflow-executor 9.0.0   | [v9.0.0](https://gitcode.com/cann/ge/tags/v9.0.0)            | CANN 9.0.0 |
| cann-hcomm 9.0.0            | [v9.0.0](https://gitcode.com/cann/hcomm/tags/v9.0.0)         | CANN 9.0.0 |
| cann-npu-runtime 9.0.0      | [v9.0.0](https://gitcode.com/cann/runtime/tags/v9.0.0)     | CANN 9.0.0 |

For details about how to upgrade a subpackage independently, see [Upgrading a Subpackage Independently](#independent-subpackage-upgrades).

## Key Features

### Support for Ascend 950PR

CANN now supports Ascend 950PR (Atlas 350 accelerator cards) and has added the following key features: support for FP8/MxFP8/MxFP4, SIMD+SIMT hybrid programming for AscendC, and CCU communication acceleration for collective communication.

### Easier installation with apt and pip support and one-stop download

With the new apt and pip, installation modes now extend to four: conda, yum, apt, and pip. In addition, you can now download and install CANN in one stop, reducing the time required for obtaining and deploying software from 2 hours to 45 minutes. For details, see the [features](https://www.hiascend.com/en/cann/download).

### DeepSeek acceleration with DSA operator optimization and deterministic computation

On Atlas A2 and Atlas A3 products, DSA operators have further improved pipeline parallelism, enhancing SFAG operator performance by 2x-6x+ and boosting model efficiency by 1.5x+. The new deterministic computation capabilities deliver high result consistency. For details, see the [feature](https://gitcode.com/cann/ops-transformer/blob/9.0.0/attention/sparse_flash_attention_grad/docs/aclnnSparseFlashAttentionGrad.md).

### Multimodal acceleration with the new Block-wise Sparse Attention operator

The Atlas A2 and Atlas A3 products now support the Block-wise Sparse Attention (BSA) operator. Compared with generic Flash Attention, BSA reduces computation by 90% and speeds up execution 5x at 90% sparsity. For Wan2.2 and HunyuanVideo 1.5, the model performance is improved by 1.7x and 1.5x respectively when the sparsity rate is 70%. For details, visit [feature](https://gitcode.com/cann/ops-transformer/blob/9.0.0/attention/block_sparse_attention/README.md).

### Messaging acceleration with communication batching of HCCL

HCCL supports the batch communication combination mechanism (HcclGroupStart and HcclGroupEnd APIs) on Atlas A2 and Atlas A3 products. This mechanism allows multiple communication operations to be combined and submitted together, improving the execution efficiency in small-message and high-frequency communication scenarios. For details, visit [HcclGroupStart](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/latest/API/hcclug/hcclcpp_07_0063.html) and [HcclGroupEnd](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/latest/API/hcclug/hcclcpp_07_0064.html).

## New Features

### Common Modules

- CANN improves the usability of installation and deployment.
  - Added the apt-get and pip online installation methods.
  - Added the combined package to CANN. This package consists of the Ascend NPU driver and Toolkit, and supports one-click installation and installation by specifying the --whitelist parameter.
- Added the Ascend-cann-950-ops package to the CANN ops package to support Ascend 950PR operators.
- Adapted to different Ascend hardware products, and added OS compatibility.
  - Atlas 350 accelerator cards are supported, and veLinux 2.0 and Alinux 3 are adapted.
  - Atlas 200T A2 Box16 adapts to Ubuntu 22.04.5.
  - Atlas 800T A2, Atlas 800I A2, and Atlas 900 A2 PoDc adapted to UOS V25 (kernel 6.6).
  - Atlas 800I A2 adapted to AntOS (kernel 6.6).
  - Atlas 800T A3 and Atlas 900 A3 SuperPoD adapted to CTyunOS4-25.07 and UOS V25 (kernel 6.6).
- Added support for NumPy 2.x for CANN, allowing CANN to run with later versions of NumPy.

### Operator Library

#### ops-nn

- Open source LSTM operators:
  - [ThnnFusedLstmCellGrad operator] ([!793](https://gitcode.com/cann/ops-nn/pull/793)).
  - [SingleLayerLstmGrad operator ] ([!796](https://gitcode.com/cann/ops-nn/pull/796)).
  - [ThnnFusedLstmCell operator] ([!1999](https://gitcode.com/cann/ops-nn/pull/1999)).
- Low-bit operators and fused operators supported more data types, such as fp8/mxfp8/hifp8/mxfp4, and different quantization and combination modes, such as per-tensor/per-channel/per-token/per-group/per-block.
  - [Fully quantized fused operator: quant_batch_matmul_v4](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/matmul/quant_batch_matmul_v4/README.md).
  - [Fake-quantization fused operator: weight_quant_batch_matmul_v2](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/matmul/weight_quant_batch_matmul_v2/README.md).
  - [mx dynamic quantization operator: dynamic_mx_quant](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/quant/dynamic_mx_quant/README.md).
  - [Dynamic quantization operator of the non-mx type: dynamic_quant_v2](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/quant/dynamic_quant_v2/README.md).
  - [Dynamic quantization operator of the mx type: grouped_dynamic_mx_quant](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/quant/grouped_dynamic_mx_quant/README.md).
  - [Dynamic quantization operator of the non-mx type: grouped_dynamic_block_quant](https://gitcode.com/cann/ops-nn/blob/9.0.0-beta.1/quant/grouped_dynamic_block_quant/README.md).
- Open source operators supported Ascend 950PR:
  - Operator project adaptation([!450](https://gitcode.com/cann/ops-nn/pull/450)).
  - LogSigmoid([!1837](https://gitcode.com/cann/ops-nn/pull/1837)).
  - Norm class([!995](https://gitcode.com/cann/ops-nn/pull/995)).
  - SoftMax class([!1010](https://gitcode.com/cann/ops-nn/pull/1010)).
  - AvgPoolV2Grad([!1183](https://gitcode.com/cann/ops-nn/pull/1183)).
  - RmsNormQuant([!1057](https://gitcode.com/cann/ops-nn/pull/1057)).
- Ascend 950PR supported the Parallel Welford and ultra-long axis binary accumulation algorithms to improve the numerical stability and computing precision of Norm operators. This feature involves the following operators:
  - [LayerNormV4](https://gitcode.com/cann/ops-nn/tree/master/norm/layer_norm_v4).
  - [BatchNormV3](https://gitcode.com/cann/ops-nn/tree/master/norm/batch_norm_v3).
- The following MM fusion operators are added to Ascend 950PR:
  - [QuantBatchMatmulInplaceAdd] ([!1130](https://gitcode.com/cann/ops-nn/pull/1130)).
  - [TransposeQuantBatchMatmul] ([!1136](https://gitcode.com/cann/ops-nn/pull/1136)).
  - [DualLevelQuantBatchMatmul] ([!1141](https://gitcode.com/cann/ops-nn/pull/1141)).
- The QuantBatchMatmul operator supports the mxfp8 weightNz feature based on Ascend 950PR, improving the network inference performance([!1144](https://gitcode.com/cann/ops-nn/pull/1144)).
- The following SIMD/SIMT homogeneous programming operators are supported:
  - [MapIndex] ([#660](https://gitcode.com/cann/ops-nn/issues/660)).
  - [ScatterSub] ([#710](https://gitcode.com/cann/ops-nn/issues/710)).
  - [SegmentSum] ([#668](https://gitcode.com/cann/ops-nn/issues/668)).
  - [UnsortedSegmentMin] ([#656](https://gitcode.com/cann/ops-nn/issues/656)).
  - [opKTopPSampleV2] ([#658](https://gitcode.com/cann/ops-nn/issues/658)).
- Added the operator development sample for <<<>>> ([!620](https://gitcode.com/cann/ops-nn/pull/620)).
- Supported the generation of static libraries during compilation. The released independent NN component package contains the static library ([!391](https://gitcode.com/cann/ops-nn/pull/391)).
- Added the capability of compiling specific operator kernels based on templates ([#1097](https://gitcode.com/cann/ops-nn/issues/1097)).
- Provided best practices for programming MatMul, convolution, norm, and hash operators:
  - [MatMul Operator VCV Performance Optimization and Analysis](https://gitcode.com/cann/ops-nn/wiki/MatMul%E7%AE%97%E5%AD%90VCV%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E5%AE%9E%E8%B7%B5%E4%B8%8E%E6%95%88%E6%9E%9C%E5%88%86%E6%9E%90.md).
  - [MatMul Operator Performance Optimization and Analysis](https://gitcode.com/cann/ops-nn/wiki/MatMul%E7%AE%97%E5%AD%90%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E5%AE%9E%E8%B7%B5%E4%B8%8E%E6%95%88%E6%9E%9C%E5%88%86%E6%9E%90.md).
- LSTM/LSTMCell can be called through the aclnn APIs, which significantly reduces the compile time on the host when models that use LSTM operators, such as speech processing models, are called through PyTorch APIs.
- Optimized memory usage for index APIs such as aclnnScatter, aclnnScatterValue, and aclnnScatterAdd when dim!=-1. In model training or inference scenarios where the scatter or scatter_add API is used, there are obvious memory benefits when dim!=-1.

#### ops-transformer

- The capabilities of transformer-related operators on the Atlas A3 products are improved as follows:
  - [MC2 dispatch and combine operators supported directly driving RoCE through AI-V: moe_distribute_dispatch](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.1/mc2/moe_distribute_dispatch_v2/README.md).
  - [RoPE supports operator generalization mrope_section](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/posembedding/rope_with_sin_cos_cache/README.md).
  - [Enhanced BlockSparseAttention operator](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/attention/block_sparse_attention/README.md).
  - [Enhanced GroupedMatmulSwigluQuantV2 operator to support A4W4 dynamic tiling optimization](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/gmm/grouped_matmul_swiglu_quant_v2/README.md).
  - [Enhanced GroupedMatmul operator: A4W4 supports NZ transpose dynamic tiling optimization](https://gitcode.com/cann/ops-transformer/blob/9.0.0-beta.2/gmm/grouped_matmul/README.md).
- DSA operators supported deterministic computation. Operators such as SparseFlashAttentionGrad, LightningIndexerGrad, and DenseLightningIndexerGradKLLoss supported deterministic computation. For DeepSeek V3.2 model training, deterministic computation is enabled, and the attention part can ensure that the results of multiple executions with the same input are consistent.
- Added MatmulAllToAll and AllToAllMatmul operators. For models trained using Ulysses parallelism with ultra-long sequences of M-level, these operators can improve the model performance.
- GmmSwigluQuantV2 supported the i4 input and i8 output and dynamic tiling optimization for A4W4. Gmm A4W4 supported dynamic tiling optimization for NZ transpose.
- When MoE permutation RoutingMaps support BF16 tokens, fp32 probs are input. The MoeInitRoutingQuantV2 operator supported INT4 and SmoothQuant.
- The M-RoPE fused operator generalization mrope_section supported [16, 16, 16, 16] and [24, 20, 20], and the prefill performance of the mrope operator was optimized.
- The aclnnScatterPaKvCache supported the FIA operator in the NZ scenario. The model side can use the FIA operator to obtain the performance benefits of the NZ scenario.
- The basic APIs of the FAG SAMEAB and BN2 templates were optimized and rewritten. Compared with CANN 8.5.0, the generalization test performance is improved by more than 1% and 10% on average.
- The deterministic performance of FAG in certain scenarios (layout=BSND/BNSD/SBH, sparsemode=0/2/3, dtype=bfloat16, S1=S2) was optimized.
- The forward and backward Floyd attention operators (Fuse Floyd Attention/Fuse Floyd Attention Grad) were added. Compared with the small operator combination in the Floyd structure, 10 matmul operators are arranged in pipeline mode, improving the fusion performance by more than 30% and reducing the memory usage by more than 70%.
- The RingAttentionUpdate operator supported Ascend 950PR.

#### ops-cv

- Image operators supported Ascend 950PR, covering ResizeNearestNeighborV2, ResizeNearestNeighborV2Grad, UpsampleNearest, and UpsampleNearest3d ([!284](https://gitcode.com/cann/ops-cv/pull/284) [#97](https://gitcode.com/cann/ops-cv/issues/97) [#93](https://gitcode.com/cann/ops-cv/issues/93)).
- The CI enhanced the build and UT identification of Ascend 950PR ( [!281](https://gitcode.com/cann/ops-cv/pull/281),[!368](https://gitcode.com/cann/ops-cv/pull/368),[#105](https://gitcode.com/cann/ops-cv/issues/105)).
- Operator samples can be executed on the simulator. Sample compilation and execution verification can be performed without relying on real hardware, facilitating Ascend 950PR adaptation for pre-integration and regression testing ([!567](https://gitcode.com/cann/ops-cv/pull/567) [!397](https://gitcode.com/cann/ops-cv/pull/397)).
- The RoiPoolingWithArgMax and RoiPoolingGradWithArgMax operators were added to support the Ascend 950PR and enable the faster-rcnn model.
- CIou can be called through the aclnn API, and the mmcv function can be enabled on the Ascend 950PR.
- The Col2im operator was added to support the Ascend 950PR and enable the training of the BEVfusion model for intelligent driving.
- The Rasterizer operator was added to implement rasterization calculation. It calculates the minimum depth of each pixel and the corresponding patch index based on the 3D spatial points and surfaces. This operator can be used to improve the model performance in multi-modal 3D generation scenarios.

#### ops-math

- Mathematical operations, tensor transformation, and random number generation supported Ascend 950PR, covering Erfc, Sinh, Asin, Atanh, BitwiseXor, Asinh, Cosh, Scale, Tan, Acos, Acosh, and more([#599](https://gitcode.com/cann/ops-math/issues/599)).
- APIs such as aclnnMul, aclnnMuls, aclnnAdd, aclnnAdds, and aclnnSum supported discontinuous inputs, improving the performance of related APIs and optimizing the memory usage([!874](https://gitcode.com/cann/ops-math/pull/874)).
- Compared with Atlas A3, the Sort operator supported the UINT16, UINT32, and UINT64 types on Ascend 950PR. The average performance of data types supported by Atlas A3 is improved by more than 1.5 times on Ascend 950PR([#557](https://gitcode.com/cann/ops-math/pull/557) [#632](https://gitcode.com/cann/ops-math/pull/632)).
- The performance of discrete tensor transformation operators, including Pad, Transpose, and AsStrided ([#569](https://gitcode.com/cann/ops-math/issues/569) [#539](https://gitcode.com/cann/ops-math/pull/539) [#495](https://gitcode.com/cann/ops-math/pull/495)), is optimized.
- Operator samples can be executed on the simulator. This allows sample build and execution verification without depending on real hardware, facilitating joint commissioning and regression([!563](https://gitcode.com/cann/ops-math/pull/563) [!1215](https://gitcode.com/cann/ops-math/pull/1215))of Ascend 950PR adaptation.
- The operator project supported parallel kernel compilation([!779](https://gitcode.com/cann/ops-math/pull/779)).
- The operator project log was optimized([#192](https://gitcode.com/cann/ops-math/issues/192)).
- The operator CI supports incremental UT and smoke tests([!774](https://gitcode.com/cann/ops-math/pull/774) [!817](https://gitcode.com/cann/ops-math/pull/817)).
- The operator build script supported the export of precompiled files, which simplifies the locating of operator problems([#536](https://gitcode.com/cann/ops-math/issues/536)).
- Docker-based deployment was supported([!547](https://gitcode.com/cann/ops-math/pull/547)).
- The ChunkCat fusion operator was added. In the FSDP2 framework, this operator is required to merge weights during training. Compared with small operators, this operator reduces the memory usage by 30% and reduces the peak memory usage of the model, while improving the model performance.
- The aclnnDiv/aclnnDivs API supported mixed data types as inputs, optimizing the memory usage of the operator.
- The aclnn API for the logspace operator was added to improve the API usability.
- The aclnnReplicationPad3d API supported the bfloat16 data type, improving the API usability in multi-modal generation scenarios.
- The aclnnReplicationPad2dBackward API memory was optimized to reduce the peak memory usage and improve the operator usability.

#### opbase

- The basic framework library supports Ascend 950PR([#65](https://gitcode.com/cann/opbase/issues/65)).

### Communication Library

#### Collective Communication

- Communication operators supported Ascend 950PR, covering Allgather, AllgatherV, Allreduce, AlltoAll, AlltoAllV, Broadcast, Reduce, ReduceScatter, ReduceScatterV, Scatter and SendRecv ([\#106](https://gitcode.com/cann/hccl/pull/106)).
- With AI CPUs of Atlas A3 SuperPoDs, AlltoAll operators supported symmetric memory ([\#575](https://gitcode.com/cann/hcomm/pull/575)).
- With AI CPUs of Atlas A3 series products, ReduceScatter&AllReduce operators supported batch consistency ([\#483](https://gitcode.com/cann/hcomm/pull/483)).
- With ReduceScatter&AllReduce&AllGather&AlltoAll operators of Atlas A3 SuperPoDs, superkernel ([\#596](https://gitcode.com/cann/hcomm/pull/596)) between multiple machines was supported.
- Offline build was supported to improve the build friendliness ([\#126](https://gitcode.com/cann/hccl/pull/126)).
- On the Atlas A2 and Atlas A3 products, HCCL supported batch communication combination (HcclGroupStart and HcclGroupEnd APIs), which allows multiple communication operations to be combined and submitted for execution in a unified manner. This mechanism improves the execution efficiency in small-message and high-frequency communication scenarios and supports unified scheduling of multiple point-to-point communication operations.
- On the Atlas A2 products, AI CPU acceleration was supported for unilateral communication. In PD disaggregation scenarios, compared with the current host CPU scheduling mode, the performance of the AI CPU acceleration mode is improved by more than 50% when the size of the kvCache data pulled for inference is less than 128 KB.
- The performance of the cross-machine deterministic algorithm on the Atlas A2 products was optimized, improving the performance by 2x. Compared with the scenario where deterministic computation is not enabled, the deterioration is lower than 30%. In deterministic scenarios, there are obvious benefits.
- The Atlas A3 products supported the configuration of the HCCL expansion mode (such as AI CPU and AIV) by communicator, improving configuration flexibility.
- On the Atlas A3 products, the allreduce, allgather, reducescatter, and alltoall operators supported symmetric memory, improving the operator execution performance.
- On Atlas A3 products, the AllReduce and ReduceScatter operators supported batch consistency in AI CPU expansion mode.
- Supported deployment across multiple containers (without sharing the same NPU) on the same physical machine. During communicator initialization, a random port is selected. During multi-thread concurrent communication, contexts are isolated.
- Improved maintenance and test capabilities. For example, the output content of ErrorMsg was optimized, and time tracing was added to the AI CPU expansion.

#### Unilateral communication

- Unilateral communication: The Atlas A3 training products and Atlas A3 inference products supported the automatic link setup mode, and the connect API ([\#106](https://gitcode.com/cann/hixl/issues/106)) does not need to be explicitly called.
- Unilateral communication: The Atlas A3 training products and Atlas A3 inference products supported the global unified addressing mode for the fabric memory, and supported the direct KV cache transmission capability of D2rH using HCCS, improving the transmission efficiency ([\#33](https://gitcode.com/cann/hixl/issues/33)).

### Domain-Specific Acceleration Libraries

#### Ascend Transformer Boost (ATB)

- Core operators (such as Activation, MultiLatentAttention, and LayerNorm) supported Ascend 950PR.
- In the entire-graph offload mode, parameters of the plugin operator can be updated.

#### Ascend Signal Processing Boost

- The torch extension module was added to the SiP library. The C++ APIs can be bound to the Torch Library, and more than 40 operators, such as FFT, BLAS, and SOLVER, can be called using Python.
- The memory allocation and management mechanism was optimized. Resource pools facilitate efficient dynamic memory management. In FFT scenarios, handles are further reused, reducing resource waste and repeated resource application and release.

### Graph Engine

- ES graph construction provided samples ([!72](https://gitcode.com/cann/ge/pull/72) ,[!123](https://gitcode.com/cann/ge/pull/123)) for multiple scenarios.
- ES graph construction Readable Dump supported user-friendly display of subgraphs.
- Enhanced the custom pass for image modification. Added the capability of modifying images after the original image was optimized.
- Supported memory reuse for the continuous memory without padding in the multi-stream scenario of graph mode.
- ES graph construction supported the generation of valid overloaded C++ APIs([\#643](https://gitcode.com/cann/ge/pull/643))based on the consumption of historical prototypes.
- Supported code optimization in the operator-level core control scenarios([\#450](https://gitcode.com/cann/ge/pull/450)).
- When the output node of a model is deleted during graph fusion, the framework can identify and update the model output([\#434](https://gitcode.com/cann/ge/pull/434)).
- Optimized common subexpression elimination([\#622](https://gitcode.com/cann/ge/pull/622)).
- Provided the dump switch to enable L0 and L1 exception dump([\#398](https://gitcode.com/cann/ge/pull/398)).
- Optimized the error message([\#685](https://gitcode.com/cann/ge/pull/685)).
- Provided the following end-to-end samples: dynamic profiles([\#813](https://gitcode.com/cann/ge/pull/813))([\#685](https://gitcode.com/cann/ge/pull/685)), integrating custom operators into graphs([\#867](https://gitcode.com/cann/ge/pull/867)), and custom pass for fusing Matmul and Add into GEMM based on the graph API([\#1106](https://gitcode.com/cann/ge/pull/1106)).
- Optimized the compilation project([\#646](https://gitcode.com/cann/ge/pull/646))([\#890](https://gitcode.com/cann/ge/pull/890)).
- Deterministic and strong consistency configurations were supported: ge.deterministicLevel.
- Supported TensorMove elimination.
- In online scenarios, users can use the graph-level option ge.outputDatatype to specify the model output data type.
Removed the singleton and lock on the execution path to improve dispatch performance.

### Operator Programming

- Ascend 950PR supported the SIMD programming mode and provided more than [200 APIs](https://gitcode.com/cann/asc-devkit/tree/9.0.0/impl/basic_api/dav_c310) to ensure cross-generation compatibility, implementing smooth operator migration between Atlas A2 and Atlas A3 products.
- Ascend 950PR introduced the Reg-based programming mode and provided [more than 90 Reg-based programming APIs](https://gitcode.com/cann/asc-devkit/tree/9.0.0/impl/basic_api/reg_compute/dav_c310) for Reg data movement, basic arithmetic operations, reduction computation, and synchronization control.
- Atlas A2 products, Atlas A3 products, and Ascend 950PR supported [pure C APIs at the language extension layer](https://gitcode.com/cann/asc-devkit/tree/9.0.0/include/c_api), array-based memory allocation, and pointer-based computing APIs, providing native C programming experience.
- Ascend 950PR supported SIMD and SIMT hybrid programming and provided about 700 [SIMT APIs](https://gitcode.com/cann/asc-devkit/tree/9.0.0/include/simt_api), including basic APIs such as warp, atomic, basic mathematical computation, and type conversion.
- Ascend 950PR supported the CCU communication interfaces for high-level communication APIs and provided [mainstream communication primitives such as Allreduce, Allgather, Reducescatter, and AlltoAll](https://gitcode.com/cann/asc-devkit/tree/9.0.0/impl/adv_api/detail/hccl/impl/platform_v310) based on the CCU. The high-level Matmul API supported [matrix operations of MXFP4/8 low-bit data type](https://gitcode.com/cann/asc-devkit/blob/9.0.0/impl/adv_api/detail/matmul/mx_matmul_impl.h), reducing memory usage by half and magnifying the compute throughput.
- About 260 new and compatible samples were added for Ascend 950PR, including SIMT and SIMD samples (framework, basic APIs, high-level APIs, and best practices). The [sample directory structure](https://gitcode.com/cann/asc-devkit/pull/1223) was adjusted according to the programming model and sample type to improve the readability.
- Migrated the AscendC samples in the [Gitee sample repository](https://gitee.com/ascend/samples/tree/master/operator/ascendc) and the samples in the [AscendC high-level API repository](https://gitee.com/ascend/ascendc-api-adv/tree/master/examples) to the [asc-devkit repository](https://gitcode.com/cann/asc-devkit/tree/9.0.0/examples), and used the <<<>>> calling mode.
- Fusion compilation and <<<>>> calling supported the [CPU mode](https://gitcode.com/cann/asc-tools/pull/138) and [SIM simulation mode](https://gitcode.com/cann/asc-devkit/blob/9.0.0/cmake/asc/asc_modules/CMakeASCInformation.cmake).
- Worked with the BiSheng Compiler to optimize the fusion compilation performance.

### Virtual Instruction Set

- Supported the [Ascend Ascend 950PR instruction set](https://gitcode.com/cann/pto-isa/tree/master/include/pto/npu/a5), including element-wise, TileScalar, fixed pipeline, memory access, complex operations, convolution instructions, and quantization instructions, as well as the [CPU-SIM implementation](https://gitcode.com/cann/pto-isa/tree/master/include/pto/cpu) of the corresponding instructions.
- Added SDMA ([#493](https://gitcode.com/cann/pto-isa/pull/493)) and URMA ([#715](https://gitcode.com/cann/pto-isa/pull/715)) asynchronous communication instructions, and multi-device P2P/P2MP/semaphore synchronization instructions ([#17](https://gitcode.com/cann/pto-isa/pull/17)).
- Added the [CostModel of basic instructions](https://gitcode.com/cann/pto-isa/tree/master/include/pto/costmodel) for performance simulation.
- Added the debugging command TPRINT to print tile data in Vec, Mat, and Acc storage and tensor data in GM ([#31](https://gitcode.com/cann/pto-isa/pull/31), [#638](https://gitcode.com/cann/pto-isa/pull/638), [#725](https://gitcode.com/cann/pto-isa/pull/725)).
- Added the performance tuning commands TPUSH/TPOP ([#364](https://gitcode.com/cann/pto-isa/pull/364), [#431](https://gitcode.com/cann/pto-isa/pull/431), [#569](https://gitcode.com/cann/pto-isa/pull/569)) and TPREFETCH ([#73](https://gitcode.com/cann/pto-isa/pull/73), [#116](https://gitcode.com/cann/pto-isa/pull/116)).

### Runtime

- The runtime supported Ascend 950PR.
Enhanced usability
- The stream specification in the AclGraph scenario can be expanded to 64K, resolving issues such as insufficient resources for foundation models([\#461](https://gitcode.com/cann/runtime/pull/461)).
  - The event specifications in the AclGraph scenario can be expanded. The expansion depends only on the device memory([\#482](https://gitcode.com/cann/runtime/pull/482)).
  - Provided APIs for querying the package version number. The numeric version number and string version number are returned based on the package name. The APIs are as follows:
    - [aclError aclsysGetVersionStr(char *pkgName, char * versionStr)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclsysGetVersionStr.md)
    - [aclError aclsysGetVersionNum(char *pkgName,int32_t * versionNum)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclsysGetVersionNum.md)
  - The priority of a specified stream can be queried. The API is as follows:
    - [aclError aclrtStreamGetPriority(aclrtStream stream, uint32_t *priority)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtStreamGetPriority.md)
  - The flag set during stream creation can be queried. The API is as follows:
    - [aclError aclrtStreamGetFlags(aclrtStream stream, uint32_t *flags)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtStreamGetFlags.md)
  - The universally unique identifier (UUID) of a device can be obtained. The API is as follows:
    - [aclError aclrtDeviceGetUuid (int32_t deviceId, aclrtUuid *uuid)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtDeviceGetUuid.md)
  - The start address and size of the memory block to which the address to be queried belongs can be obtained. The API is as follows:
    - [aclError aclrtMemGetAddressRange(void *ptr, void **pbase, size_t *psize)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtMemGetAddressRange.md)
  - The parameters for strong consistency computing can be set and queried. The APIs are as follows:
    - [aclError aclrtSetSysParamOpt(aclSysParamOpt opt, int64_t value)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtSetSysParamOpt.md)
    - [aclError aclrtGetSysParamOpt(aclSysParamOpt opt, int64_t *value)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtGetSysParamOpt.md)
    - [aclError aclrtCtxSetSysParamOpt(aclSysParamOpt opt, int64_t value)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtCtxSetSysParamOpt.md)
    - [aclError aclrtCtxGetSysParamOpt(aclSysParamOpt opt, int64_t *value)](https://gitcode.com/cann/runtime/blob/9.0.0/docs/api_docs/aclrtCtxGetSysParamOpt.md)
- Released the runtime programming guide([\#1030](https://gitcode.com/cann/runtime/pull/1030)).
- Released the runtime Ascend 950PR documentation([\#1255](https://gitcode.com/cann/runtime/pull/1255)).

### Development and Maintenance Tools

#### Performance Tuning Tools

- msProf supported the aicore-metrics option to collect custom PMU metrics([\#136](https://gitcode.com/cann/oam-tools/pull/136)).
- The HCCL performance test tool supported the FP64 data type([\#122](https://gitcode.com/cann/oam-tools/pull/122)).

#### AMCT

- Supported the HIF8/FP8/FP4/MXFP8/MXFP4 quantization data types and the HIF8 OFMR quantization algorithm([\#20](https://gitcode.com/cann/amct/pull/20)).
- Supported the HIF8 quantile quantization algorithm([\#54](https://gitcode.com/cann/amct/pull/54)).

## Removed and Deprecated Features

### Operator Libraries

**The following APIs in the transformer library are marked as deprecated in CANN 9.0.0 and will be deleted in versions released after March 30, 2027.**

- The aclnnGroupedMatMulAllReduce API is deprecated and replaced with aclnnMatmulAllReduce.
- The aclnnGroupedMatmul, aclnnGroupedMatmulV2, aclnnGroupedMatmulV3, and aclnnGroupedMatmulV4 APIs are deprecated and replaced with aclnnGroupedMatmulV5.
- The aclnnFusedInferAttentionScore/aclnnFusedInferAttentionScoreV2/aclnnFusedInferAttentionScoreV3 API is deprecated and replaced with aclnnFusedInferAttentionScoreV4.
- The aclnnIncreFlashAttention/aclnnIncreFlashAttentionV2/aclnnIncreFlashAttentionV3 API is deprecated and replaced with aclnnIncreFlashAttentionV4.
- The aclnnPromptFlashAttention/aclnnPromptFlashAttentionV2 API is deprecated and replaced with aclnnPromptFlashAttentionV3.
- The aclnnMlaProlog/aclnnMlaPrologV2WeightNz API is deprecated and replaced with aclnnMlaPrologV3WeightNz.
- The aclnnMatmulAllReduceAddRmsNorm API is deprecated and replaced with aclnnMatmulAllReduce and aclnnAddRmsNorm.
- The aclnnQuantMatmulAllReduceAddRmsNorm API is deprecated and replaced with aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm.
- The aclnnWeightQuantMatmulAllReduceAddRmsNorm API is deprecated and replaced with aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm.
- The aclnnInplaceQuantMatmulAllReduceAddRmsNorm API is deprecated and replaced with aclnnQuantMatmulAllReduceV2 and aclnnAddRmsNorm.
- The aclnnInplaceMatmulAllReduceAddRmsNorm API is deprecated and replaced with aclnnMatmulAllReduce and aclnnAddRmsNorm.
- The aclnnInplaceWeightQuantMatmulAllReduceAddRmsNorm API is deprecated and replaced with aclnnWeightQuantMatmulAllReduce and aclnnAddRmsNorm.

### Model Compression Tool

The following features of the model compression tool are deprecated. The deprecated features will be deleted in versions later than CANN 9.0.0.

- NUQ
- Mixed precision
- Calibrated approximation
- int4 QAT
- All features of amct_mindspore

## Known Issues

Issue 1: For a model that uses the int64 operator in the communicator, when a link disconnection occurs, the time required for fast recovery increases from minutes to more than 10 minutes, affecting the MTTR. [Involved Version] CANN 9.0.0 [Impact] The int64 operator does not support the re-execution process and cannot be restored using the step-based fast recovery method. As a result, tasks cannot be re-executed under disconnections. [Workaround] Do not use the collective communication operator of int64 type. Instead, use operators of other types as temporary replacements.

Issue 2: During the recovery of a training job, the sendrecv operator is suspended. As a result, the process-level recovery fails, affecting the MTTR. [Involved Version] CANN 8.5.0 [Impact] In cross-SuperPoD scenarios, the sendrecv operator is occasionally suspended, and the fast recovery fails. [Workaround] In logical cross-SuperPoD scenarios, you can use the HCCS link to avoid this problem. Currently, no workaround is available for the physical cross-SuperPoD scenarios.

## Resolved Issues

The following issues have been fixed in version 9.0.0:

- Resolved the issue that the error message "ld.lld: error: undefined symbol: CheckLogLevel" is displayed during the build of CATLASS operators.
- Resolved the issue that the error code "EZ9999" is reported during the execution of the PadV3Grad operator on the Atlas 900 A2 hardware because the operator does not support the padding input of [16,16,16,16] format.
- Resolved the issue where the MatMul operator produced NaN results during matrix multiplication (32162, 4096)@(32162,32768).
- Resolved the issue that the FA operator consistently produced NaN values in the MIMO-V2 model during training under the MindSpeed-LLM framework.
- Resolved the issue that the aclnnQuantMatmul operator reported an error indicating that the shapes are inconsistent when the input is a slice parameter.
- Resolved the issue where the FAG operator caused model calling timeouts due to losing tail data in data tiling in the (1,32,641,128) no mask scenario.
- Resolved the issue where a cluster task failed because the HCCL communication was suspended when the reduce communication operator was used in an environment where two driver versions coexisted.

## Document Changes

### Environment Setup

Changed the CANN Quick Start to the "Environment Setup" section and renamed it CANN Quick Installation.

#### Ascend C Operator Development

- Added the introduction to SIMD and SIMT, and added the section for getting started with SIMT programming.
- Added the sections "AI Core SIMT Programming" and "Hybrid Programming of SIMD and SIMT" to the programming model in the programming guide.
- Added the section "AI Core SIMT Compilation" to the compilation and running section in the programming guide.
- Added the SIMT built-in keywords and C APIs at the SIMT language extension layer in the programming guide.
- Added the sections "SIMT Operator Implementation" and "SIMD and SIMT Hybrid Operator Implementation" to Operator Practice References.
- Added the section "SIMD and SIMT Operator Performance Optimization" to Operator Practice References.
- Added the section "SIMT APIs" to API Reference.
- Added the compatibility migration guide (migration from the 220x architecture to the 351x architecture).
- Added 90+ Reg programming APIs. Reg vector computation APIs are designed for the Regbase architecture. You can use these APIs to directly operate registers involved in vector computation on the chips, achieving greater flexibility and better performance.
- The Ascend community added a video zone for Ascend C operator development, specifically, the execution process of Cube and Vector operators.

#### Communication Operator Development

- Communication Operator Development was extracted from Huawei Collective Communication Library (HCCL) and released as an independent document under the programming guide.
- Added the section "AIV Communication Operator Development."

#### Application Development

Adjusted the level-1 directory by function and feature:

- Promoted the "Runtime Management" section to one level higher.
- Added the development guide for more runtime features, such as AscendCL graphs, multi-device programming, and inter-process communication.
- Moved the API call process description to the sections of specific functions and features.
- Distinguished built-in and custom operators in each single-operator calling section.
- Moved the media data processing and feature vector search functions to the "Dedicated Accelerator" section, and added the description of the random number generation function to this section.
- Split AscendCL API Reference by component into runtime APIs, GE APIs, DVPP APIs, and feature vector search APIs.

#### Graph Development

- Adjusted the outline: Integrated and restructured the content, and moved the development-state sections to the programming guide.
- Incorporated AutoFuse User Guide into the "AutoFuse" section of Graph Development.
- Added the section "Appendix > Session to GeSession Migration Guide" to Graph Development.
- Added the section "Programming Guide > Integrating a Triton Operator into a Graph".

### API Reference

#### GE APIs

- Classified APIs by language (C++, Python, and C). Python APIs are new to this documentation.
- Added "Model Management and Single-Operator Calling APIs" to the C APIs. The content comes from the original acl APIs.

#### HCCL

- Added the section "Configuring Resource Information Through Rank Table (Atlas 350 Accelerator Cards)" to the section "Reference > Cluster Information Configuration".
- Added the section "AIV Operator Development" to the section "Communication Operator Development".

#### Development Tools

- Changed Memory Leak Detection Tool (msLeaks) to Memory Analysis Tools.

## Fixed Vulnerabilities

For details about the fixed vulnerabilities in open-source and third-party software, see [here](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/latest/maintenref/refdoc/refer002.html).

## Independent Subpackage Upgrades

### Scenario

You can now upgrade subpackages on demand.

For example, if you have installed the Ascend-CANN-Toolkit and Ascend-CANN-ops packages of version a.b.c, and the communication library needs to be updated to version x.y.z, you can upgrade the cann-hixl subpackage independently. Replace a.b.c and x.y.z with the actual version numbers.

### Procedure

Before upgrading a subpackage, ensure that the Ascend-CANN-Toolkit and Ascend-CANN-ops packages of the matching version have been installed. If the packages are not installed, install them by referring to [this guide](https://www.hiascend.com/document/detail/en/CANNCommunityEdition/latest/softwareinst/instg/instg_0000.html?OS=openEuler&InstallType=netyum).

Subpackage upgrade paths must be the same as that of the main package. The upgrade operations of all subpackages are the same. The following uses cann-hixl\_x.y.z\_linux-aarch64.run as an example.

**Upgrade scenario 1:**

The Ascend-CANN-Toolkit and Ascend-CANN-ops packages are **installed in the default path** (that is, not using --install-path for installation).

```bash
chmod +x cann-hixl_x.y.z_linux-aarch64.run
./cann-hixl_x.y.z_linux-aarch64.run --upgrade
```

**Upgrade scenario 2:**

The Ascend-CANN-Toolkit and Ascend-CANN-ops packages are **installed in the specified path** /home/custom\_path (that is, specifying --install-path=/home/custom\_path during installation).

```bash
chmod +x cann-hixl_x.y.z_linux-aarch64.run
./cann-hixl_x.y.z_linux-aarch64.run --upgrade --install-path=/home/custom_path
```
