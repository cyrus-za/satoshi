---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=2072&auto=format&fit=crop
# some information about your slides (markdown enabled)
title: Pieter Venter - Satoshi Energy
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: 'text-center'
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
highlighter: shiki
lineNumbers: false
---

# Pieter Venter
Engineering Leadership & Innovation

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/satoshienergy" target="_blank" alt="Satoshi Energy GitHub" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
transition: fade-out
---

# Presentation Overview

- 🚀 **Introduction** - Engineering Leadership & Innovation
- 💼 **Professional Journey** - 15+ Years of Software Engineering Excellence
- 📈 **Recent Leadership Experience** - Scaling Teams and Systems
- 🎓 **Educational Foundation** - Technical Expertise & Business Acumen
- 🎯 **Five-Year Vision** - Growth and Innovation Path
- ⚡ **Why Satoshi Energy** - Alignment and Contribution
- 🤝 **Thank You** - Looking Forward to Collaboration

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

---
layout: two-cols
---

# Professional Journey

<v-clicks>

- **13+ Years** in Engineering
- **10+ Years** in Leadership Roles
- **15+ Projects** Successfully Delivered
- Focus on Sustainable Growth & Innovation
- Strong Background in:
  - Platform Architecture
  - Developer Experience (DX)
  - Cross-functional Leadership
  - AI & Automation Systems

</v-clicks>

::right::

<div class="ml-4">
  <div v-click class="mt-12 flex items-center justify-center">
    <div class="text-5xl font-bold text-blue-500">60%</div>
    <div class="ml-2">Year-over-Year<br/>Productivity Increase</div>
  </div>
  <div v-click class="mt-8 flex items-center justify-center">
    <div class="text-5xl font-bold text-green-500">64%</div>
    <div class="ml-2">Improved Development<br/>Turnaround Time</div>
  </div>
  <div v-click class="mt-8 flex items-center justify-center">
    <div class="text-5xl font-bold text-purple-500">5K+</div>
    <div class="ml-2">Customer Data Points<br/>Processed via API</div>
  </div>
</div>

---
layout: default
---

# Recent Leadership Experience

<div class="grid grid-cols-2 gap-4 mt-4">
<div v-click>

## Principal Engineer
### Invisible Technologies

- Scaled engineering team from 12 to 32 members
- Architected systems crucial for $100M ARR
- Implemented Kubernetes infrastructure
- Led cross-functional alignment initiatives
- Developed AI-driven Process Engine
- Cultural anchor during rapid scaling

</div>
<div v-click>

## Senior Engineer
### Mana

- Platform architecture leadership
- Enhanced developer experience (DX)
- Added Monitoring & Observability
- Added CI/CD pipeline
- Built a RAG system
- Proactive problem-solving approach

</div>
</div>

---
layout: center
class: "text-center"
---

# Educational Foundation

<div class="grid grid-cols-2 gap-12 mt-12">
<div v-click class="text-left">

## Academic Background
- BComm Management Sciences
- Double Major:
  - Financial Management
  - Information Systems
- Stellenbosch University

</div>
<div v-click class="text-left">

## Technical Skills
- Systems Architecture
- Python, TypeScript, SQL
- AI/ML Integration
- Business Analytics
- Scalable Solutions

</div>
</div>

---
layout: default
---

# Five-Year Vision

```mermaid {scale: 0.9}
mindmap
  root((Career Growth))
    Lead Scalable Solutions
      AI Integration
      Web3 Development
      Financial Systems
    Strategic Leadership
      Team Mentorship
      Technical Oversight
      Delegation Framework
    Cultural Impact
      Collaborative Environment
      Transparent Processes
      Innovation Focus
    Work-Life Balance
      Sustainable Growth
      Personal Development
      Family Goals
```

---
layout: two-cols
class: gap-8
---

# Why Satoshi Energy?

<v-clicks>

- Innovative Energy-Bitcoin Synergy
- Cross-disciplinary Platform Development
- Spec-driven Development Culture
- Clear Communication Values
- Balanced Technical Approach

</v-clicks>

::right::

<div v-click class="mt-4">

# What I Bring

- Scaling Experience
- Infrastructure Optimization
- Cross-team Collaboration
- AI Integration
- Event-driven Architecture

</div>

---
layout: center
class: text-center
---

# Thank You

<div class="text-xl text-gray-500 mt-4">
Looking forward to contributing to Satoshi Energy's mission
</div>

<div v-click class="mt-12">
  <div class="text-sm opacity-50">Contact Information</div>
  <div class="text-xl mt-2">
    <carbon-email class="inline-block mr-2"/> Available Upon Request
  </div>
</div>

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
