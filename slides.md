---
theme: shibainu
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
highlighter: shiki
---

# How to collaborate

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Let's GoStudy it <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: section
---

# Table of contents

<Space />

<TOC />

---
layout: section
---

# Roadmap

<Space />

<TOC count=1 />


---
layout: default-3
---

# [Soft Skills](https://www.amazon.com/Soft-Skills-software-developers-manual/dp/1617292397) <span class="text-base"><sup>[1]</sup></span>

<img src="/images/softskills.jpg" class="h-40"/>
<div class="mt-5" />

- stay online and communicate with others
- be friendly: [contributor covenant code of conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/)
- don't be afraid to ask questions: [Raymond how to ask questions the smart way](http://www.catb.org/~esr/faqs/smart-questions.html)
- share your ideas and insights
- make friends and enjoy
- 流程 -> 行为 -> 氛围 -> 文化 (you'll like it, or hate it)



<div class="absolute bottom-10 text-xs"> 

- [[1] 10 soft skills](https://hackernoon.com/10-soft-skills-every-developer-needs-66f0cdcfd3f7)

</div>

---
layout: section
---

# Roadmap

<Space />

<TOC count=2 />


---

DEMO: (based on https://github.com/CLDXiang/today-frontend/)

---

## Drafts

- 任务明确、沟通顺畅、文档记录 

use GitHub well!

- soft skills:
  - be friendly [code of conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/)
  - don't be afraid to ask {raymond how to ask question}
  - share your insights
  - make friends and enjoy
- all you need is GitHub
  - https://twitter.com/i/status/1407731478096756739
  - personal: have good commits
  - collaborating:
    - issues, prs, @someone
    - commit conventions https://www.conventionalcommits.org/en/v1.0.0/
  - code reievw
    - there will be problems
  - wiki: 知识沉淀 (IM 是不适合的)
  - milestones (1-week & 2-week) and sprints (longer)
  - a calendar will help you (Google Calendar, ZenHub)
  - be online (respond in time, on slack)
- DSN
  - what are we doing: Web app
    - web app has sofisticated solutions, but we are trying to find out our way of doing it
    - what we can learn and what we cannot
    - what we can do and what we cannot
  - what is our goal: learning
    - learning by doing and collaborating (that is good)
    - share your ideas, readings and feelings
    - 想做但是不知道怎么做：communicate! && 内部分享

