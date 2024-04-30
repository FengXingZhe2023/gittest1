---
title: 电子料/电子料仓
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
1. SN收料规则卡控
2. SN收料研发库支持Y560 (之前要求我们默认6100，要改成不同工厂默认库区不同)

要完成但是第二梯队的事项：
1. `SN收料`也要和`PO收料/杂收`一样，触发电子仓入库任务
   `电子料入库触发条件`改成检验合格后（详细讨论分析才行）
2. "质量中心"-"隔离品处置"-"隔离品异常反馈"提交不良分析申请单功能问题:1. 现有页面只能1个RID提交一张单子,适合产线成品    
    2.由电子料会出现同一个物料数量大,RID多的情况,如果按每个RID建一单实在费时费力.3.是否能改进现有页面增加多RID批量申请的功能
3. 电子料仓：建单只进电子仓101，智能货柜，业务实现将电子料上架到其他库位
   电子料仓入库任务，需要能够直接进到正确的目标库存
   
本人判断短期不做的事项：
1. 发料单:发料单欠料部分，自动生成新的发料单，有库存的物料明细保留在老单据。
