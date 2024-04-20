---
title: 原材料/半成品采购
icon: /assets/icon/store.svg
order: 4
category:
  - 使用指南
tag:
  - 禁用

navbar: false
sidebar: false

breadcrumb: false
pageInfo: false
contributors: false
editLink: false
lastUpdated: false
prev: false
next: false
comment: false
footer: false

backtotop: false
---

# 密码加密的文章

本人判断要快速完成的事项：
1.PO收料购物车 及 PO收料明细页面 (看情谊可能要做，不是特别确定)
  `实物收货单` 要和 `上架单据号` 对应存档: 当前一张收货单，要对应很多物料交易明细中`业务类型`-`标签上架`的单据号。
  `实物收货单` 要和 `上架单据号` 对应存档: 当前一张收货单，要对应很多物料交易明细中`业务类型`-`PO收料制码`的单据号。

要完成但是第二梯队的事项：
1. PO收料按单据上行 
2. 被拆分标签无法快速查出采购订单
  当收料员判断`某标签的实物`需要退货，需要告诉采购哪个采购订单，目前需要追溯`母标签`才能看到采购订单号。
3. `SN收料`也要和`PO收料/杂收`一样，触发电子仓入库任务
   `电子料入库触发条件`改成检验合格后（详细讨论分析才行）

本人判断短期不做的事项：
