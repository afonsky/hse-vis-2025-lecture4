---
theme: seriph
addons:
  - "@twitwi/slidev-addon-ultracharger"
addonsConfig:
  ultracharger:
    inlineSvg:
      markersWorkaround: false
    disable:
      - metaFooter
      - tocFooter

background: /perplexity_eye.jpeg
highlighter: shiki
routerMode: hash
lineNumbers: false

class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
# transition: slide-down
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true

# css: unocss
title: Научная визуализация данных
subtitle: Лекция 4. Зрительное восприятие и цвет
date: 29/11/2025
venue: ФКН ВШЭ
author: Алексей Болдырев
---

<br>
<br>

# <span style="font-size:28.0pt" v-html="$slidev.configs.title?.replaceAll(' ', '<br/>')"></span>
# <span style="font-size:24.0pt" v-html="$slidev.configs.subtitle?.replaceAll(' ', '<br/>')"></span>
# <span style="font-size:18.0pt" v-html="$slidev.configs.author?.replaceAll(' ', '<br/>')"></span>

<span style="font-size:18.0pt" v-html="$slidev.configs.date?.replaceAll(' ', '<br/>')"></span>

<div>
<br>
<br>
<span style="color:#b3b3b3ff; font-size: 11px; float: right;">Изображение: Midjourney 6.0. Запрос "Human eye at the center connecting visual perception, color, and data visualization"
</span>
</div>


<style>
  :deep(footer) { padding-bottom: 3em !important; }
</style>

<!--
NB: This demo uses a custom syntax (using preparser extensions), with all the @@@@.
-->

---
src: ./slides/0_outline.md
---

---
src: ./slides/0_intro.md
---

---
src: ./slides/2_comparison.md
---

---
src: ./slides/3_color.md
---

---
src: ./slides/0_end.md
---