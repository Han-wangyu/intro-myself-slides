---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
background: /bg.png
# some information about your slides, markdown enabled
title: 新人分享会 - 韩王宇
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# 新人分享会

Newcomer sharing meeting

<!-- <div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div> -->

<div class="abs-br m-24 text-2xl">
<span>
By waynehan(韩王宇)
</span>
</div>

<div class="abs-br m-6 flex gap-2">
  <!-- <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button> -->
  <a href="https://github.com/Han-Wangyu" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
首页
-->

---
layout: image-right
image: suzhou.png
transition: fade-out
---

# 个人介绍

<!-- Slidev is a slides maker and presenter designed for developers, consist of the following features -->

<!-- - 📝 **Text-based** - focus on the content with Markdown, and then style them later
- 🎨 **Themable** - theme can be shared and used with npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embedding Vue components to enhance your expressions
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export into PDF, PPTX, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage -->

- ⏳**出生年月**：2002.11
- 🏠**籍贯**：江苏苏州
- 🔮**MBTI**：ISFP(内向/实感/感性/感知, 探险家)
- 🏫**毕业院校**：南京信息工程大学 大三 数据科学与大数据技术
- 💟**兴趣爱好**：科技产品资讯/民谣歌曲/开源新技术

<!-- <br>
<br>

Read more about [Why Slidev?](https://sli.dev/guide/why) -->

家乡：江南何处好，乐居在吴江

- 60分钟到上海城区，90分钟可达杭州城区
- 长三角生态绿色一体化发展示范区，两家本土世界五百强
- 古城区保护 / 苏州工业园区

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
个人介绍
-->

---
transition: slide-up
level: 2
---

# 成长经历

<!-- Hover on the bottom-left corner to see the navigation's controls panel, [learn more](https://sli.dev/guide/navigation.html) -->
长期热爱 / 耐心规划 / 感恩机遇 / 虚心复盘

## 关键时间点

<!-- |     |     |
| --- | --- |
| <kbd>right</kbd> / <kbd>space</kbd>| next animation or slide |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd> | previous slide |
| <kbd>down</kbd> | next slide | -->
<v-clicks every="2">

- 2018.9 加入高中的NOIp队，<span class="opacity-50">但[成绩平平](https://mp.weixin.qq.com/s/VJEu94zoSVr3qAq42Ezq9g)</span>
- 2021.6 写代码很有意思，我要报计算机专业
- 2021.8 通过综合评价提前批次进入大学，<span class="opacity-50">但调剂了</span>
- 2022.8 转专业成功
- 2023.1 Laravel ➡️ 前端
- 2023.2 [Vue开源小工具](https://github.com/Han-wangyu/prescription-generator)
- 2024.4.9 第一次投[简历](/韩王宇_前端开发实习生_南京信息工程大学.pdf)，<span class="opacity-50">后经历了10次失败的面试经历</span>
- 2024.4.30 14:15 笙哥打电话捞我面试
- 2024.5.17 offer

</v-clicks>

<!--
成长经历
-->

---

# 项目经历

- [discord-clone](https://github.com/Han-wangyu/discord-clone)
  - 项目介绍: 参考海外交流平台 [Discord](https://discord.com/) 的社区型聊天程序开发，全面支持语音、视频和文字通信。允许用户新建或 通过邀请链接加入群组中进行实时通信，包括完整的权限管理机制和实时删除或编辑消息。
  - 技术栈: <span v-mark.circle.red>Next.js 13</span> + React + TypeScript + Socket.io + Prisma + Tailwind CSS + React Hook Form
- [apple-website-clone](https://iphone15pro-clone-five.vercel.app/)
  - 项目介绍: 参考 [iPhone 15 Pro 官网](https://www.apple.com/iphone-15-pro/)开发，重点实现了复杂的动画效果和手机 3D 模型预览。
  - 技术栈: React + <span v-mark.circle.red>Three.js</span> + React Three Fiber + React Three Drei + <span v-mark.circle.red>GSAP</span> + <span v-mark.circle.red>Sentry</span> + Tailwind CSS
- [deliveroo-clone](https://github.com/Han-wangyu/deliveroo-clone)
  - 项目介绍: 参考海外知名订餐 App [Diliveroo](https://deliveroo.hk/zh/) 界面的移动端开发项目。
  - 技术栈: <span v-mark.circle.red>React Native</span> + Expo Router + Zustand + React Native Reanimated

<!--
项目经历
-->

---

# 学习前端的方式

- **技术博主**: [Traversy Media](https://www.youtube.com/@TraversyMedia)；[Fireship](https://www.youtube.com/@Fireship)；[Code with Antonio](https://www.youtube.com/@codewithantonio)；[Josh tried Coding](https://www.youtube.com/@joshtriedcoding)
- **基础知识**：[javascript.info](https://javascript.info/)
- **开源资讯**：[hackernewsletter](https://www.bilibili.com/video/BV1QD421g7UZ)；[Best of Javascript](https://bestofjs.org/)

喜欢前端的原因：
- **社区活跃**：Atwood定律
- **成就感更强**：所见即所得

想在这次实习机会中获得的：
- **提升技能，学习前辈的思维方式和经验**：主动热情 / “问前先想” / 充分利用已有资源
- **了解项目的研发流程**：CI/CD / 研发工具 / 业务重点
- **留用机会**：不畏难 / 融入团队 / 主动争取表现空间

<!--
学习前端的方式
-->

---
layout: center
class: text-center
---

# 谢谢大家

<!--
谢谢大家
-->
