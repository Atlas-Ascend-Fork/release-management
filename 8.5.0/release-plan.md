# Release plan
|Stange name|Begin time|End time|
|:----------|:---------|:-------|
|Collect feature|2025/10/15|2025/10/30|
|Develop|2025/10/20|2025/12/05|
|Build|2025/12/06|2025/12/07|
|Test round 1|2025/12/08|2025/12/13|
|Test round 2|2025/12/15|2025/12/20|
|Test round 3|2025/12/22|2025/12/27|
|QA report|2025/12/29|2025/12/29|
|Release|2025/12/30|2025/12/30|

# Feture list
## 状态说明：discussion(方案讨论，需求未接受)，developing(开发中)，Testing(测试中)，Accepted(已验收)
|no|feature|status|sig|owner|
|:----|:---|:---|:--|:----|
|1|[MC2算子支持更大通信域](https://gitcode.com/cann/ops-transformer/issues/60)|Accepted|sig-ops-transformer|YuZhengzhong|
|2|[MLA非量化场景泛化能力增强](https://gitcode.com/cann/ops-transformer/issues/65)|Accepted|sig-ops-transformer|mabing1118|
|3|[ops-nn仓编译构建能力增强和代码结构优化](https://gitcode.com/cann/ops-nn/issues/44)|Accepted|sig-ops-nn|yangyang016|
|4|[ops-math仓编译构建能力增强和代码结构优化](https://gitcode.com/cann/ops-math/issues/72)|Accepted|sig-ops-basic|zhou-qilong|
|5|[ops-cv仓编译构建能力增强和代码结构优化](https://gitcode.com/cann/ops-cv/issues/3)|Accepted|sig-ops-basic|zhou-qilong|
|6|[ops-transformer仓编译构建能力增强和代码结构优化](https://gitcode.com/cann/ops-transformer/issues/69)|Accepted|sig-ops-transformer|YuZhengzhong|
|7|[opbase代码结构优化](https://gitcode.com/cann/opbase/issues/5)|Accepted|sig-ops-basic|zhou-qilong|
|8|[Matmul算子支持4选2稀疏量化能力](https://gitcode.com/cann/ops-nn/issues/45)|Accepted|sig-ops-nn|tangweiwei2|
|9|[Ascend-transformer-boost仓算子工程易用性提升]()|Accepted|sig-aal|nino888|
|10|[CATLASS仓新增FA、Matmul类算子样例]()|Accepted|sig-catlass|hanru-xu|
|11|[ops-nn仓：Index/Norm/Conv类算子在确定性计算场景下的性能优化]()|Accepted|sig-ops-nn|zhangyuxiang0119|
|12|[ops-nn仓：Matmul类算子新增量化格式支持能力以及性能优化增强]()|Accepted|sig-ops-nn|zhangyuxiang0119|
|13|[ops-math仓：新增math类算子cholesky功能实现]()|Accepted|sig-ops-nn|tangyanfeng|
|14|[增强GMMSwigluQuant算子支持weight tensorList场景下功能泛化]()|Accepted|sig-ops-transformer|cc-z|
|15|[增强FA正反向算子TND场景下增加接口功能泛化]()|Accepted|sig-ops-transformer|cc-z|
|16|[增强FAG算子在TND场景和确定性场景下性能表现]()|Accepted|sig-ops-transformer|cc-z|