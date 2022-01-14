---
theme: default
title: ''
titleTemplate: '%s'
highlighter: 'shiki'
lineNumbers: true
fonts:
  sans: 'Noto sans TC'
  serif: 'Noto sans TC'
  mono: 'Fira Code'
colorSchema: 'dark'
class: 'text-center flex justify-center items-center font-serif'

github: 'https://github.com/kevinshu1995/'
website: 'https://kevinshu1995.github.io/'
blog: 'https://kevinshu1995.github.io/blog/'
joberfly: 'https://www.joberfly.com/'
linkedin: 'https://www.linkedin.com/in/kevin-hws/'
email: 'kevin.hsu.hws@gmail.com'
---

# 許文修．Kevin Hsu

前端 x 設計

<SocialLinks :configs="$slidev.configs"/>

---
layout: two-cols
class: "flex flex-col items-start justify-center"
---

<div class="flex justify-center w-full">
  <Avatar src="/avatar.jpeg" class="ring-4 ring-emerald-500"/>
</div>

::right::

<v-clicks>

# 前端工程師

-   工業設計系畢業，曾任平面設計
-   轉職前端將近兩年

</v-clicks>

<IconList class="mt-4"/>

---
layout: iframe-right
url: https://kevinshu1995.github.io/
class: "flex flex-col items-start justify-center"
---
<style>
iframe{
  @apply bg-white
}
</style>
# 個人網站

<v-clicks>

簡介、經歷、作品

- <logos-nuxt-icon/> Nuxt.js
- <logos-tailwindcss-icon/> Tailwindcss

<LinkWithArrow :href="$slidev.configs.website" class="text-xs text-gray-400 mt-4" text="Link" />

</v-clicks>

---
layout: iframe-left
url: https://www.joberfly.com/
class: "flex flex-col items-start justify-center"
---

<TitleWithBadge title="Joberfly" badge="專案"/>

<v-clicks>

智能履歷顧問平台

- <logos-nuxt-icon/> Nuxt.js
- <logos-tailwindcss-icon/> Tailwindcss、 <logos-bootstrap /> Bootstrap

<LinkWithArrow :href="$slidev.configs.joberfly" class="text-xs text-gray-400 mt-4" text="Link" />

</v-clicks>

---
layout: iframe-right
url: https://v2.tailwindcss.tw/
class: "flex flex-col items-start justify-center"
---

<TitleWithBadge title="社群參與" badge="線上"/>

<v-click>

透過社群參與來學習相關技術 & 認識各種大神

</v-click>

<ul>
  <li v-click>
    <a href="https://github.com/tailwindcss-tw/tailwindcss.com" target="_blank">
    <logos-tailwindcss-icon /> Tailwindcss.tw 協同翻譯 <Badge text="進行中-目前改版緩衝中" theme="bg-emerald-900" size="xs"/>
    </a>
  </li>
  <li v-click>
    <a href="https://material-design.hexschool.io/" target="_blank">
      <mdi-material-design/> Material Design 協同翻譯 <Badge text="已結束" theme="bg-emerald-900" size="xs"/>
    </a>
  </li>
  <li v-click>
    <a href="https://github.com/Rabbittee/leet-codes" target="_blank">
    <simple-icons-leetcode /> Leetcode 馬拉松 <Badge text="已暫停" theme="bg-emerald-900" size="xs"/>
    </a>
  </li>
</ul>

---
layout: iframe-right
url: https://pretending-app.vercel.app/#/worldClock
class: "flex flex-col items-start justify-center"
---

# Side Projects

<v-click>

- [iPhone Clock App (開發中...)](https://github.com/kevinshu1995/pretending-app)
- [公車動態時刻查詢應用服務 (開發中...)](https://github.com/kevinshu1995/f2e-bus)
- [JS 地下城](https://github.com/kevinshu1995/hex_jsDungeon)
- [SideBarToggleButtonOnTeachable](https://github.com/kevinshu1995/SideBarToggleButtonOnTeachable)
- [Sign up form](https://github.com/kevinshu1995/react-tailwind-sign-up-form)
- [Calculator app](https://github.com/kevinshu1995/react-calculator-app)
- [Tip calculator app](https://github.com/kevinshu1995/react-tip-calculator-app)
- [Testimonial grid section](https://github.com/kevinshu1995/react-testimonials-grid-section)

</v-click>
