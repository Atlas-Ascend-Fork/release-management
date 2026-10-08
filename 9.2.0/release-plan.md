# Release plan
|Stange name|Begin time|End time|
|:----------|:---------|:-------|
|Collect feature|2026/06/01|2026/06/30|
|Develop|2026/07/01|2026/09/24|
|Build|2026/09/25|2026/09/25|
|Test round 1|2026/09/26|2026/10/07|
|Test round 2|2026/10/08|2026/10/12|
|QA report|2026/10/13|2026/10/13|
|Release|2026/10/15|2026/10/15|

# Feture list
## 状态说明：discussion(方案讨论，需求未接受)，developing(开发中)，Testing(测试中)，Accepted(已验收)
|no|feature|status|sig|owner|
|:----|:---|:---|:--|:----|
|1|[Atlas A2系列产品 和 Atlas A3系列产品新增适配FusedSgd算子]()|Accepted|ops-nn|tangweiwei2|
|2|[Atlas A2/A3系列产品支持SituGlu、SituGluGrad和DequantSituQuant算子]()|Accepted|ops-nn|tangweiwei2|
|3|[Ascend 950PR/Ascend 950DT系列产品适配与场景支持SituGlu、SituGluGrad和SituMxQuant算子]()|Accepted|ops-nn|tangweiwei2|
|4|[Atlas A2/A3系列产品支持MsaIndexScore算子]()|Accepted|ops-transfomer|cc-z|
|5|[Atlas A2/A3系列产品支持MlaProlog算子增设RoPE计算操作开关并支持cache输入非连续]()|Accepted|ops-transfomer|cc-z|
|6|[Atlas A2/A3系列产品支持FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化]()|Accepted|ops-transfomer|cc-z|
|7|[Ascend 950PR/Ascend 950DT系列产品支持FusedInferAttentionScore算子的MLA模板非量化decode场景支持headNum<=128任意值泛化]()|Accepted|ops-transfomer|cc-z|