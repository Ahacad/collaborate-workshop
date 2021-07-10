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

> *All you need is ... GitHub* <sup>[^1]</sup> <sup>[^2]</sup>

<div class="grid grid-cols-2">
<div class=" mt-3 h-10 w-10"><Tweet id="1407731478096756739" /></div>
<div class=" mt-3 h-10 w-10"><Tweet id="1413226453450244098" /></div>
</div>

<div class="absolute bottom-10 text-xs"> 

- [[1] *All You Need Is Love*](https://www.wikiwand.com/en/All_You_Need_Is_Love)
- [[2] *Attention is all you need*](https://papers.nips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)

</div>

---


<img class="mt-10" src="/images/github-1.png"/>
<Space />

- use GitHub well!
    - commit conventions: https://www.conventionalcommits.org/en/v1.0.0/
  - projects: manage issues and PRs, milestones & sprints
  - issues: submit your ideas!
  - prs: code review & CICD
  - discussions
  - wiki: write knowledge down
  - actions(CICD)

DEMO: (based on https://github.com/CLDXiang/today-frontend/)

---

## Commit conventions

<div class="mt-16"/>

- [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/): `<type>[optional scope]: <description>`
- [Angular commit conventions](https://gist.github.com/brianclements/841ea7bffdb01346392c)
- 没有官方标准，但是有些工具可以利用 commit message: https://github.com/conventional-changelog/standard-version

- 切分 commits，每一个 commit 做一件事

---

## Branch strategy
<Space />

<div class="grid grid-cols-2"> 

<div > <img src="/images/gitflow.png" class="h-80"/> <div class="ml-22  text-sm">git flow </div></div>

<div class="mt-10">

- [GitKraken: What is the best Git branch strategy? GitFlow vs. GitHub flow vs. GitLab flow](https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy)
- [Paul Hammant: what is your branching model?](https://paulhammant.com/2013/12/04/what_is_your_branching_model/)
- choose one!

</div>

</div>

---

## Projects

<Space />

<img src="/images/projects.png" class="h-80"/>

---

## Actions

<Space />

<img src="/images/actions.png" class="h-80"/>

---

## you actually need more

<Space />
<div class="mt-10"/>

(personal suggestions)

tools:
- IM: [Slack](https://slack.com/) & [telegram](https://telegram.org/)
- calendar: [Google Calendar](https://calendar.google.com/)
- maillist
- ...

- formatting tools (eslint, prettier, .editorconfig, gofmt ...)
- good [scripts and CI](https://github.com/Ahacad/collaborate-workshop/actions/workflows/release.yml) will save you tons of time!
- ...
- extend GitHub and have better DevOps tools (ZenHub, ...)

---
layout: section
---

# Roadmap

<Space />
<TOC count=3 />

---
layout: default-5
---

## 唠叨

<Space />

- what we want to achieve: 任务明确、沟通顺畅、文档记录
- what we want to achieve: 学到知识、交到朋友、做出一些贡献
- what are we doing: Web 开发
  - what you can learn <span class="text-pink-900">(web, servers, SE)</span> and what you can hardly learn <span class="text-pink-900">(how to write a web server? how to write a frontend framework?)</span>
  - what we can do <span class="text-pink-900">(make our life better)</span> and what we cannot <span class="text-pink-900">(write something so awesome that everyone will use)</span>
  - 已经有成熟经验和解决方案，一边学习一边建造
