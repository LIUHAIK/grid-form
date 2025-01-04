---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "MpChart 图表库"
  tagline: MpChart是一个包含各种类型图表的图表库，方便开发者快速实现图表UI，主要包括线形图、柱状图、饼状图、蜡烛图、气泡图、雷达图、瀑布图等自定义图表库。
  actions:
    - theme: brand
      text: 快速开始
      link: /guide/getting-started
    - theme: alt
      text: 在线文档
      link: /demo/designer
    - theme: alt
      text: 官方网站
      link: https://gitee.com/openharmony-tpc/ohos_mpchart
  image:
      src: /mpchartDemo.png
      alt: MpChart

features:
  - title: 可视化设计器
    details: 基于 <a target=_blank href="https://www.naiveui.com">Naive UI</a> 组件库，所见即所得
    icon:
      src: /rocket.svg
      width: 40
  - title: Naive UI
    details: 默认渲染器，支持设计器中的全部组件
    icon:
      src: /naive-ui.svg
      width: 33
  - title: Element Plus
    details: 使用优秀 <a target=_blank href="https://element-plus.org/">Element Plus</a> 组件库的渲染器
    icon:
      src: /element-plus.svg
      width: 40
  - title: Vant
    details: 适配移动终端的渲染器（<a target=_blank href="https://vant-ui.github.io">Vant4</a> 以上版本）
    icon:
      src: vant.png
      width: 40
    
---

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #18A058 30%, #00C9D7);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #18A058 50%, #00C9D7 50%);
  --vp-home-hero-image-filter: blur(44px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}

.VPFeatures .details a {
    text-decoration-line: underline;
    text-underline-offset: 2px;
}

@media (min-width: 960px) {
    .image-src {
        margin-top:10px;
        max-width: 440px !important;
    }
}
</style>
