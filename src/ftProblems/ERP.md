---
title: ERP上行/追溯
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
1. Z35退货和销售退货能够关单时候一次上行
2. PO收料按单据上行 
3. 收发存报表优化
4. 装车关单与SAP上行时间不一致，需优化时间记录逻辑
5. 1.盘点扫描A库位，实物是B库位的，结果显示库位差异
   2.盘点导出要把，货架和标签合在一起
:::important
6. 有些调拨没有进入上行队列
:::
要完成但是第二梯队的事项：
1. 被拆分标签无法快速查出采购订单
   当收料员判断`某标签的实物`需要退货，需要告诉采购哪个采购订单，目前需要追溯`母标签`才能看到采购订单号。
2. 月日导出数据都采取2位
   ![](/assets/image/export.png)
3. 1.盘点按物料建模板自动带出该物料有的库区
   ![](/assets/image/pd01.png)
   2.扫描系统外的，目前扫不进，需要扫进去

本人判断短期不做的事项：
1. 打印不要强关联账号，要求电脑不同账号可以直接打印，打印模板变更为线上模板

********************************* 5月现场问题 *************************************
```md
01、5月6日 单据号:42817406 没有进入上行队列 
```md