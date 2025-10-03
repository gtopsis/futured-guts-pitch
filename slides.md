---
theme: default
title: Smart Student Grouping Platform
class: text-center
drawings:
  persist: false
mdc: true
colorSchema: light
---

<style>
.slidev-layout {
  background: white !important;
  color: black !important;
}
</style>

# Smart Student Grouping

AI-Powered Team Formation for Educators

<div class="pt-8 text-lg text-black opacity-75">
Optimizing collaborative learning through intelligent student grouping
</div>

<div class="pt-16 text-lg text-black font-semibold">
GUTs - Generative <span style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">Untrained</span> Transformers
</div>

<div class="pt-4 text-base text-black">
Marcelo Mollaj | Giorgos Topsis
</div>

---

# The Problem

Teachers **manually** or **randomly** grouping students

<div class="pt-8" />

- Difficult to balance multiple criteria simultaneously
- Random or intuition-based grouping leads to imbalanced teams
- Hard to track what works and replicate successful groupings
- Results in poor team dynamics and frustrated students

---
layout: two-cols
layoutClass: gap-12
---

# Solution

Our platform uses **AI** to **intelligently** group students based on **customizable** questionnaires

<div class="pt-8" />

Flow:

1. Create Questionnaire & Set Weights

2. Students Respond

3. AI Grouping

4. Review & Adjust

<div class="pt-8 text-sm opacity-75">
Example: Educational treasure hunt with problem-solving: 5, teamwork: 4, creativity: 3, leadership: 2
</div>

::right::

<div class="pt-8">

```mermaid {scale: 0.6}
flowchart TD
    T[👩‍🏫 Teacher] --> QC[Questionnaire Creation<br/>AI Assisted or Manual]
    QC --> DIST[Share and Distribute<br/>QR Code or Link or Print]
   
    ST[👨‍🎓 Students] --> DIST
    DIST --> RESP[Student Response<br/>Fill and Submit]
   
    RESP --> AI[AI Processing<br/>Analyze and Generate Groups]
    T --> AI
    AI --> GR[Optimized Groups]
   
    GR --> T
```

</div>

---
layout: center
class: text-center
---

# Demo

<div class="text-6xl my-8">
💻
</div>

<div class="text-xl">
Let's see the platform in action
</div>
