# Release plan （开发中）
|Stange name|Begin time|End time|
|:----------|:---------|:-------|
|Collect feature|2026/08/01|2026/08/05|
|Develop|2026/08/06|2026/08/18|
|Build|2026/08/19|2026/08/19|
|Test round 1|2026/08/20|2026/08/25|
|Test round 2|2026/08/27|2026/08/27|
|QA report|2026/08/28|2026/08/28|
|Release|2026/08/31|2026/08/31|

# Feture list
## 状态说明：discussion(方案讨论，需求未接受)，developing(开发中)，Testing(测试中)，Accepted(已验收)
|no|feature|status|sig|owner|
|:----|:---|:---|:--|:----|
|1|[Atlas A2/A3系列产品支持SituGlu、SituGluGrad和DequantSituQuant算子](https://gitcode.com/cann/ops-nn/pull/8651) ([!8798](https://gitcode.com/cann/ops-nn/pull/8798))|Accepted|ops-nn|tangweiwei2|
|2|[Ascend 950PR/Ascend 950DT系列产品适配与场景支持SituGlu、SituGluGrad和SituMxQuant算子](https://gitcode.com/cann/ops-nn/pull/8651) ([!8798](https://gitcode.com/cann/ops-nn/pull/8798))|Accepted|ops-nn|tangweiwei2|
|3|[Atlas A2/A3系列产品支持MsaIndexScore算子](https://gitcode.com/cann/ops-transformer/pull/9503)|Accepted|ops-transfomer|cc-z|
|4|[Atlas A2/A3系列产品支持MlaProlog算子增设RoPE计算操作开关并支持cache输入非连续](https://gitcode.com/cann/ops-transformer/pull/10296) ([!9472](https://gitcode.com/cann/ops-transformer/pull/9472))|Accepted|ops-transfomer|cc-z|
|5|[Atlas A2/A3系列产品支持FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化](https://gitcode.com/cann/ops-transformer/pull/9773)|Accepted|ops-transfomer|cc-z|
|6|[Ascend 950PR/Ascend 950DT系列产品支持FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化](https://gitcode.com/cann/ops-transformer/pull/9773)|Accepted|ops-transfomer|cc-z|
