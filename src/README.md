---
home: true
icon: home
title: 项目主页
heroImage:  /assets/image/store.jpg
bgImage: https://theme-hope-assets.vuejs.press/bg/6-light.svg
bgImageDark: https://theme-hope-assets.vuejs.press/bg/6-dark.svg
bgImageStyle:
  background-attachment: fixed
heroText: WMS Pro
tagline: Business with Demo
actions:
  - text: 总览
    icon: lightbulb
    link: ./demo/
    type: primary

  - text: 文档
    link: ./guide/

highlights:
  - header: FT模块化问题
    image: /assets/image/box.svg
    bgImage: https://theme-hope-assets.vuejs.press/bg/3-light.svg
    bgImageDark: https://theme-hope-assets.vuejs.press/bg/3-dark.svg
    features:
      - title: 收料部门
        icon: clipboard-check
        details: 胡林海
        link: ./ftProblems/materialsReceive

      - title: 电子料部门
        icon: /assets/icon/electronic.svg
        details: 王健、童寒、沈秋平
        link: ./ftProblems/electronicMaterials

      - title: 库存管理
        icon: clipboard-check
        details: 王伟峰、黄伟建、邵帅威、金佳国
        link: ./ftProblems/storeManage

      - title: 包装部门
        icon: box-archive
        details: 沈晓东、施潇俊、郑英、杜云霞、陈梦磊
        link: ./ftProblems/package

      - title: 销售订单及三方仓管理
        icon: clipboard-check
        details: 徐耿涛
        link: ./ftProblems/thirdDepart

      - title: SAP和MES库存管理
        icon: box-archive
        details: 陈国英
        link: ./ftProblems/ERP
      # highlights:
    #   - title: 运行 <code>pnpm create vuepress-theme-hope hope-project</code> 以创建一个新的主题项目。
    #   - title: 在已有项目根目录下运行 <code>pnpm create vuepress-theme-hope add .</code> 以在项目中添加主题。

  - header: iD&MS细分功能介绍
    description: 
    image: 
    bgImage: https://theme-hope-assets.vuejs.press/bg/2-light.svg
    bgImageDark: https://theme-hope-assets.vuejs.press/bg/2-dark.svg
    bgImageStyle:
      background-repeat: repeat
      background-size: initial
    features:
      - title: 收料
        icon: clipboard-check
        details: PO收料/杂收入库/SN收料/采购退货   /抽样方案/iqc基准书/抽验模板管理/IQC来料检验/MRB评审/复检管理
        link: https://theme-hope.vuejs.press/zh/guide/markdown/others.html#link-check

      - title: 库房管理
        icon: box-archive
        details: 库存汇总/库存明细/储位库存查询  /上架/储位移动/调拨/备料/现品票入库/退库接收/杂发出货/杂收入库
        link: https://theme-hope.vuejs.press/zh/guide/markdown/hint.html

      - title: 成品包装
        icon: bell
        details: 现品票入库/现品票拆零/成品包装/解除包装/箱拆零 /包装方案/批追物料装箱/包装认可书
        link: https://theme-hope.vuejs.press/zh/guide/markdown/alert.html

      - title: 成品出货
        icon: table-columns
        details: 交付工单模块/新发运管理/杂发出货  /成品拣货/装车/装车管理
        link: https://theme-hope.vuejs.press/zh/guide/markdown/tabs.html

      - title: 电子料
        icon: code
        details: 电子料入库任务/电子料出库任务/电子仓设备下发日志/电子料上架
        link: https://theme-hope.vuejs.press/zh/guide/markdown/code-tabs.html

      - title: 看板
        icon: align-center
        details: 物料拉动看板/库存成品看板/物料交易明细
        link: https://theme-hope.vuejs.press/zh/guide/markdown/align.html

      - title: 追溯
        icon: code
        details: 下行交易记录/上行交易记录/盘点
        link: https://theme-hope.vuejs.press/zh/guide/markdown/attrs.html

  - header: 解决方案
    description: 难点功能的解决方案示例。
    image: /assets/image/layout.svg
    bgImage: https://theme-hope-assets.vuejs.press/bg/5-light.svg
    bgImageDark: https://theme-hope-assets.vuejs.press/bg/5-dark.svg
    highlights:
      - title: SN收料
        icon: object-group
        details: 采购订单多行号的情况？ 卡控扫码异常的情况？
        link: https://theme-hope.vuejs.press/zh/guide/layout/

      - title: 备料看板
        icon: circle-half-stroke
        details: 看板任务的触发？ 子任务的形成？
        link: https://theme-hope.vuejs.press/zh/guide/interface/darkmode.html

      - title: 成品拆解
        icon: palette
        details: 现品票和箱号的管控？ 成品包装列表的查询速度？
        link: https://theme-hope.vuejs.press/zh/guide/interface/theme-color.html

      - title: 装车管理
        icon: person-chalkboard
        details: 三方仓的冲销和普通的冲销？ 冲销的速度，无法冲销的场景控制？
        link: https://theme-hope.vuejs.press/zh/guide/layout/slides

      - title: 盘点
        icon: person-chalkboard
        details: 盘点效率和真实性的控制？
        link: https://theme-hope.vuejs.press/zh/guide/layout/slides

  # - header: 新功能
  #   image: /assets/image/features.svg
  #   bgImage: https://theme-hope-assets.vuejs.press/bg/1-light.svg
  #   bgImageDark: https://theme-hope-assets.vuejs.press/bg/1-dark.svg
  #   features:
  #     - title: 浏览量与评论
  #       icon: comment-dots
  #       details: 配合 Waline 来开启阅读量统计与评论支持
  #       link: https://theme-hope.vuejs.press/zh/guide/feature/comment.html

  #     - title: 文章信息
  #       icon: circle-info
  #       details: 为你的文章添加作者、写作日期、预计阅读时间、字数统计等信息
  #       link: https://theme-hope.vuejs.press/zh/guide/feature/page-info.html

  #     - title: 文章加密
  #       icon: lock
  #       details: 你可以为你的特定页面或特定目录进行加密，以便陌生人不能随意访问它们
  #       link: https://theme-hope.vuejs.press/zh/guide/feature/encrypt.html

  #     - title: 搜索支持
  #       icon: search
  #       details: 支持 docsearch 和基于客户端的搜索
  #       link: https://theme-hope.vuejs.press/zh/guide/feature/search.html

  #     - title: 代码复制
  #       icon: copy
  #       details: 一键复制代码块中的代码
  #       link: https://theme-hope.vuejs.press/zh/guide/feature/copy-code.html

  #     - title: 图片预览
  #       icon: image
  #       details: 像相册一样允许你浏览、缩放并分享你的页面图片
  #       link: https://theme-hope.vuejs.press/zh/guide/feature/photo-swipe.html

  - header: VUE技术
    description: Vue写法变更，组合式、响应式？？
    image: /assets/image/blog.svg
    bgImage: https://theme-hope-assets.vuejs.press/bg/1-light.svg
    bgImageDark: https://theme-hope-assets.vuejs.press/bg/1-dark.svg
    highlights:
      - title: html/css/js/es6
        icon: blog
        details: js的dom操作？ es6新特性？
        link: https://theme-hope.vuejs.press/zh/guide/blog/intro.html

      - title: ajax/axios
        icon: home
        details: 跨域问题？拦截器？
        link: https://theme-hope.vuejs.press/zh/guide/blog/home.html

      - title: webpack/vite
        icon: home
        details: 不同打包方式
        link: https://theme-hope.vuejs.press/zh/guide/blog/blogger.html

      - title: vue2/vue3/ts
        icon: home
        details: 查询资料时常有不同写法，难以理解
        link: https://theme-hope.vuejs.press/zh/guide/blog/timeline.html

  # - header: 高级
  #   description: 增强站点与用户体验的高级功能
  #   image: /assets/image/advanced.svg
  #   bgImage: https://theme-hope-assets.vuejs.press/bg/4-light.svg
  #   bgImageDark: https://theme-hope-assets.vuejs.press/bg/4-dark.svg
  #   highlights:
  #     - title: SEO 增强
  #       icon: dumbbell
  #       details: 将最终生成的网页针对搜索引擎进行优化。
  #       link: https://theme-hope.vuejs.press/zh/guide/advanced/seo.html

  #     - title: Sitemap
  #       icon: sitemap
  #       details: 自动为你的网站生成 Sitemap
  #       link: https://theme-hope.vuejs.press/zh/guide/advanced/sitemap.html

  #     - title: Feed 支持
  #       icon: rss
  #       details: 生成你的 Feed，并通知你的用户订阅它
  #       link: https://theme-hope.vuejs.press/zh/guide/advanced/feed.html

  #     - title: PWA 支持
  #       icon: mobile-screen
  #       details: 让你的网站更像一个 APP
  #       link: https://theme-hope.vuejs.press/zh/guide/advanced/pwa.html

# copyright: false
# footer: 使用 <a href="https://theme-hope.vuejs.press/zh/" target="_blank">VuePress Theme Hope</a> 主题 | MIT 协议, 版权所有 © 2019-present Mr.Hope
# ---

# 这是项目主页的案例。你可以在这里放置你的主体内容。

# 想要使用此布局，你需要在页面 front matter 中设置 `home: true`。

# 配置项的相关说明详见 [项目主页配置](https://theme-hope.vuejs.press/zh/guide/layout/home/)。
