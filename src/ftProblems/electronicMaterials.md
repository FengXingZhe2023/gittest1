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

*验收前完成*
<ul>
  <li>SN收料规则卡控</li>
  <li>SN收料研发库支持Y560 (之前要求我们默认6100，要改成不同工厂默认库区不同)</li>
</ul>

*验收后完成*

*开发包打包开发*
<ul>
  <li>`电子料入库触发条件`改成检验合格后(详细讨论分析才行)</li>
  <li>`SN收料`也要和`PO收料/杂收`一样，触发电子仓入库任务</li>
  <li>发料单欠料部分，自动生成新的发料单，有库存的物料明细保留在老单据。</li>
  <li>"质量中心"-"隔离品处置"-"隔离品异常反馈"提交不良分析申请单支持多个RID，特别对于电子料</li>
</ul>