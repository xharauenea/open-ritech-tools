---
# try also 'default' to start simple
theme: geist
transition: fade
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Open Ritech - Tools
info: |
  ## Open Ritech - Tools
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
layout: center
class: text-center
---

# Open Ritech
Our tools open to everyone

<!-- Welcome tone: Emphasize "open to everyone" - these are free, open-source tools built by developers for developers -->

---
layout: center
transition: fade
class: text-center
---

# Our Tools

<div class="grid grid-cols-6 gap-8 mt-12">
  <div v-click class="col-span-2">
    <h3 class="font-bold">TechDebtGPT</h3>
    <p class="text-sm text-gray-400">AI-Driven Project Intelligence</p>
  </div>
  <div v-click class="col-span-2">
    <h3 class="font-bold">CodeWave</h3>
    <p class="text-sm text-gray-400">Commit Intelligence</p>
  </div>
  <div v-click class="col-span-2">
    <h3 class="font-bold">MainSight</h3>
    <p class="text-sm text-gray-400">Maintenance Predictor</p>
  </div>
  <div v-click class="col-span-3">
    <h3 class="font-bold">ArchDoc Generator</h3>
    <p class="text-sm text-gray-400">Architecture Docs</p>
  </div>
  <div v-click class="col-span-3">
    <h3 class="font-bold">PR Agent</h3>
    <p class="text-sm text-gray-400">Pull Request Analysis</p>
  </div>
</div>

<!-- Pace the v-clicks: Let each tool name appear before moving to the next. Pause briefly after all 5 are visible -->

---
layout: center
---

# TechDebtGPT

<p class="text-xl text-gray-400 mb-8">One Glance. Many Insights.</p>

<p class="text-lg max-w-2xl mx-auto">
AI-driven visibility into technical debt, team performance, and project health
</p>

<div class="mt-12 text-sm text-blue-400">

[techdebtgpt.com](https://techdebtgpt.com)

</div>

<!--
Main value: Dashboard shows everything at a glance - no setup, no workflow change
Note: TechDebtGPT is the only SaaS product; others are open-source tools
-->

---
layout: center
---

# Why TechDebtGPT?

<v-click>
  <div class="text-2xl font-bold text-blue-400 mb-8">
    Instant insights without changing your workflow
  </div>
</v-click>

<v-clicks>

- **Five critical metrics** in one dashboard: PRs, speed, coverage, impact, debt

- **Team intelligence** identifies bottlenecks and quality issues

- **Security-first** - no code storage, seamless integration

</v-clicks>

<!--
Key point: "Without changing workflow" - connects via GitHub, no code access needed
Use case: Team discovers 40% of PRs bottlenecked by single reviewer within first week
-->

---
layout: center
transition: fade
---

# CodeWave

<p class="text-xl text-gray-400 mb-8">AI-Powered Commit Intelligence</p>

<p class="text-lg max-w-2xl mx-auto">
Multi-agent system that analyzes git commits through collaborative AI discussions
</p>

<div class="mt-12 text-sm text-blue-400">

[CodeWave - Github](https://github.com/techdebtgpt/codewave)

</div>

<!--
Main value: Multi-agent discussion reveals insights single AI would miss
Think: 5 perspectives debating your code, not just one opinion
-->

---
layout: center
---

# Why CodeWave?

<v-click>
<div class="text-2xl font-bold text-blue-400 mb-8">
Understand the real impact of code changes
</div>
</v-click>


<v-clicks>

- **5 AI agents** discuss your commit across 3 rounds

- **Interactive HTML reports** with quality metrics

- **Perfect for code reviews** and team learning

</v-clicks>

<!--
Key point: 3 rounds of AI discussion mean deeper analysis than typical AI reviews
Use case: Junior dev's commit reviewed from security, performance, maintainability, testing, and architecture angles
-->

---
layout: center
---

# MainSight

<p class="text-xl text-gray-400 mb-8">Maintenance Degradation Predictor</p>

<p class="text-lg max-w-2xl mx-auto">
Machine learning that forecasts which files need refactoring
</p>

<div class="mt-12 text-sm text-blue-400">

[MainSight - Github](https://github.com/techdebtgpt/maintsight)

</div>

<!--
Main value: Predictive, not reactive - catch problems before they become emergencies
ML trained on real git history patterns to predict degradation
-->

---
layout: center
---

# Why MaintSight?

<v-click>
<div class="text-2xl font-bold text-blue-400 mb-8">
Catch technical debt before it catches you
</div>
</v-click>

<v-clicks>

- **In-house model** analyzes your git history

- **Scores files** by degradation risk

- **Prioritize refactoring** work with confidence

</v-clicks>

<!--
Key point: In-house model means it learns YOUR codebase patterns, not generic rules
Use case: Identified UserAuth.java would degrade 6 months before it became critical bug source
-->

---
layout: center
transition: fade
---

# ArchDoc Generator

<p class="text-xl text-gray-400 mb-8">Automated Architecture Documentation</p>

<p class="text-lg max-w-2xl mx-auto">
8 specialized AI agents that analyze your codebase and generate comprehensive architecture docs
</p>

<div class="mt-12 text-sm text-blue-400">

[ArchDoc - Github](https://github.com/techdebtgpt/architecture-doc-generator)

</div>

<!--
Main value: 8 specialized agents = comprehensive docs without manual effort
Emphasize: Supports 17+ languages, generates C4 models automatically
-->

---
layout: center
---

# Why ArchDoc Generator?

<v-click>
<div class="text-2xl font-bold text-blue-400 mb-8">
Never write architecture docs manually again
</div>
</v-click>

<v-clicks>

- **Supports 17+ languages** out of the box

- **Generates C4 models** and health dashboards

- **Perfect for understanding** and knowledge transfer

</v-clicks>

<!--
Key point: "Never write architecture docs manually again" - saves weeks of work
Use case: New developer onboarded by reading generated docs instead of 2-week shadowing period
-->

---
layout: center
---

# PR Agent

<p class="text-xl text-gray-400 mb-8">Automated Pull Request Analysis</p>

<p class="text-lg max-w-2xl mx-auto">
AI-powered tool that reviews PRs for quality, security, and best practices
</p>

<div class="mt-12 text-sm text-blue-400">

[PRAgent - Github](https://github.com/techdebtgpt/pr-agent)

</div>

<!--
Main value: Context-aware reviews using your architecture docs (unlike generic AI code reviewers)
Works as CLI or GitHub Action for flexibility
-->

---
layout: center
---

# Why PR Agent?

<v-click>
<div class="text-2xl font-bold text-blue-400 mb-8">
Catch issues before they hit production
</div>
</v-click>

<v-clicks>

- **Works as CLI tool** or GitHub Action

- **File-level risk scoring** and recommendations

- **Uses your architecture docs** for context-aware reviews

</v-clicks>

<!--
Key point: Integration with ArchDoc Generator means it understands YOUR architecture patterns
Use case: Caught security vulnerability in auth flow because it understood the project's auth architecture
-->

---
layout: center
class: text-center
---

# Try Them Out!
All tools are open source and available on GitHub

- [https://techdebtgpt.com](https://techdebtgpt.com)
- [https://github.com/techdebtgpt/codewave](https://github.com/techdebtgpt/codewave)
- [https://github.com/techdebtgpt/maintsight](https://github.com/techdebtgpt/maintsight)
- [https://github.com/techdebtgpt/architecture-doc-generator](https://github.com/techdebtgpt/architecture-doc-generator)
- [https://github.com/techdebtgpt/pr-agent](https://github.com/techdebtgpt/pr-agent)

<Note class="absolute bottom-5 left-5 text-2xl">
Questions?
</Note>

<!--
Call to action: Encourage trying the tools - they're all free and open source
Mention: TechDebtGPT at top is the SaaS offering, rest are GitHub repos to clone
-->

