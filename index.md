---
# https://vitepress.dev/reference/default-theme-home-page
layout: home
titleTemplate: false

hero:
  name: OHOS Dev
  text: OpenHarmony 开发者社区
  tagline: 非官方阵地，为 OpenHarmony 的未来而创建，Peace & Love
  image:
    src: /images/logo.svg
    alt: OHOS Dev
  actions:
    - theme: brand
      text: 项目概览
      link: /project/
    - theme: alt
      text: 项目规范
      link: /devguide

features:
  - icon: 🚄
    title: 共建
    details: 更多的开发者参与 OHOS 开源应用软件的共建
  - icon: 🏆
    title: 生态和影响力
    details: 扩大 OHOS 系统和应用软件的生态和影响力
  - icon: 🌍
    title: 国产化
    details: OHOS 在未来的国产化技术覆盖领域中全面绽放
---

<!-- 由于 home 布局没有 Markdown 的样式，所以要手动添加一个样式 -->
<div class="vp-doc external-link-icon-enabled container">

## 起源

> 组织创建于：2023-02-27

展望 2023，前有B站大佬 [@Diemit](https://space.bilibili.com/1570309)、[@AlgoIdeas](https://space.bilibili.com/36549646) 和 [@Wathinst](https://space.bilibili.com/384743347) 移植 OpenHarmony 到小米6、一加6T、PocoF1 等旧手机上（详情参见此处：[awesome-ohos-org](https://gitee.com/ohos-dev/awesome-ohos-org)），后有 [OpenHarmony 上 PC](https://mp.weixin.qq.com/s/486o6HZyvi0jqyivPnr6lQ)的重磅消息，也许 OpenHarmony 的发展注定会成为国产化技术中的重要一环。

OpenHarmony 正在茁壮成长，虽然从 API9 开始拥有完备的应用开发体系，但是开源应用软件却少之又少，我认为其中一个主要原因在于目前官方支持和三方移植适配的标准系统开发板太少且价格高昂，如果没有廉价的开发板或其他代替方案（如旧手机移植），没有开发者参与开源软件的共建，那么 OpenHarmony 的整个生态依旧残缺不全...

随着时间的推移，2023 年 HDC 大会的召开，HarmonyOS Next 预览版的发布，似乎更明确了下一步的方向，相信在不久的将来，我们能看到一个焕然一新的开源鸿蒙生态，OpenHarmony 未来已来！

## 联系
<ProjectCards class="cards" :projects="projects" />

<script setup lang="ts">
    import ProjectCards from "@/components/ProjectCards.vue"
    import FOHLogo from "./public/images/logo.svg"
    import projects from './contacts.ts'
</script>

<style lang="scss">
    .cards {
        margin-top: 16px;
    }
</style>
</div>
