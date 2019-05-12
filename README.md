# 2019_cmb_fintech
2019招行fintech精英训练营线上赛  
第二题基于收支记录判断借贷意愿baseline(a榜：0.74151 b榜：0.74242)
## 赛题描述
手机APP的首页首屏，是流量最大的页面，对应页面资源极其珍贵。现要将借钱卡片投放到首页，展现给最有点击意愿（借钱意愿）的用户。请基于用户真实的历史收支数据来预测未来一段时间内用户是否会点击借钱卡片。

其中，收支数据是指用户的交易数据，覆盖收入、支出、本人资金往来等各种类型。本赛题需依据用户的收支数据，预测一周内（20190307至20190313）目标用户点击借钱卡片的概率。
## 评测指标
AUC的全称是Area under the Curve of ROC，即ROC曲线下方的面积。在机器学习领域，AUC值常被用来评价一个二分类模型的训练效果。

本题将根据参赛选手提交的预测结果计算AUC，四舍五入精确到小数点后5位。
## 解决方案
见notebook
