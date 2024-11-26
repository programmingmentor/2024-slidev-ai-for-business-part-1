---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Як досягти 1000x продуктивності з AI?
info: |
  ## Як досягти 1000x продуктивності з AI?

# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# Practical Intro to Prompt Engineering

Vyacheslav Koldovskyy

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-left
image: /vyacheslav-koldovskyy.png
---

# Vyacheslav Koldovskyy

- Ph.D, Assoc. Professor
- 20+ years in IT
- SoftServe Academy Competence Manager
- Certified Google Cloud Professional Architect
- Practical AI Enthusiast
- Blogger [t.me/programmingmentor](https://t.me/programmingmentor)
- Youtuber [youtube.com/c/programmingmentorua](https://www.youtube.com/c/programmingmentorua)

<div class="m-6 flex gap-2 fixed bottom-12 right-0 flex-col items-end">
  <a href="https://www.youtube.com/c/programmingmentorua">
    <div class="h-8 w-8">
      <img src="/pm-logo.jpg" class="h-full w-full rounded-full"/>
    </div>
  </a>
</div>

<style>
  a {
    text-decoration: none;
    border: 2.4px solid transparent;
  }
  a:hover {
    border-color: var(--slidev-theme-primary);
  }
</style>

---
layout: image
image: /ssa-ai.png
backgroundSize: contain
title: SSA AI Courses
---

---
layout: image-left
image: /1000x.png
---

# Що значить 1000x продуктивності?

- Замість 1000 годин - 1 година
- Замість 30 днів - 43 хвилини
- Замість 1 робочого дня - 30 секунд

---
layout: center
---

# Чи це взагалі колись траплялося?

---
layout: image-left
image: /how-we-travel.png
---

# Як ми подорожували раніше і робимо це зараз?

---
layout: image-left
image: /how-we-get-news.webp
---

# Як ми отримували новини раніше і робимо це зараз?

---
layout: image-left
image: /how-we-communicate.webp
---

# Як ми спілкувалися раніше і робимо це зараз?

---
layout: image-left
image: /how-we-learn.webp
---

# Як ми вчилися раніше і робимо це зараз?

---
layout: image-left
image: /timeline-of-tech-longterm.png
---

# Справа в тому, що зміни не просто відбуваються, вони прискорюються

---

# Wargaming LLM

<div class="flex gap-4">
  <div class="flex-1">
    <img src="/softserve-nato-01.png" class="w-full" />
  </div>
  <div class="flex-1">
    <img src="/softserve-nato-02.png" class="w-full" />
  </div>
</div>

---
layout: center
---

# Що ми маємо на увазі під AI зараз?

---
layout: center
---

# LLM - Large Language Models

---
layout: center
---

# Why Language Model?

<img src="/why-language.png" class="h-80" />

---
layout: center
---

# Why Large?

<img src="/why-large.png" class="h-80" />

---
layout: center
---

# Transformer

<img src="/transformer.png" class="h-80" />

---
layout: image
image: /ft-transformer.png
backgroundSize: contain
title: FT Transformer
---

<div class="absolute bottom-20 right-5">
  <a href="https://ig.ft.com/generative-ai/">visualization</a>
</div>

---
layout: center
---

# Which LLM is the best?

---
layout: image
image: /chatbot-arena-overall.png
backgroundSize: contain
title: Chatbot Arena Overall
---

<div class="absolute bottom-20 right-5">
  <a href="https://lmarena.ai/">link</a>
</div>

---
layout: image
image: /chatbot-arena-coding.png
backgroundSize: contain
title: Chatbot Arena Coding
---

---
layout: center
---

# Multimodal LLM

<img src="/multimodal-llm.png" class="h-80" />

---
layout: center
---

# LLM Usage & Applications

- Text Generation & Summarization
- Code Assistance & Documentation
- Language Translation
- Content Creation & Editing
- Customer Support Automation
- Data Analysis & Insights
- Education
- ... much more

---
layout: center
---

# LLM Limitations

- Hallucinations & Factual Inaccuracies
- Context Window Constraints
- Training Data Cutoff
- Bias & Ethical Concerns
- High Computational Costs
- Limited Real-time Knowledge

---
layout: center
---

# Сам собі фотограф

<img src="/myself-gen.png" class="h-80" />

---
layout: center
---

# Чи можуть моделі мислити?

<img src="/think.png" class="w-full" />

---
layout: center
---

# Запит (prompt)

<img src="/prompt.png" class="w-full" />

---
layout: center
---

# Системний запит (system prompt)

<img src="/system-prompt.png" class="w-full" />

---

# Prompt Engineering Guide

https://www.promptingguide.ai/

---

# Groq

https://groq.com/

<img src="/groq.png" class="w-full" />

---

# Together AI

https://www.together.ai/

<img src="/together-ai.png" class="w-full" />

---

# Feedback practice

<img src="/fun-feedback.png" class="w-full" />

---

# 1. Chain of Thought

- Guide the model through step-by-step reasoning
- "Let's solve this step by step..."
- Helps with complex problem solving
- Improves accuracy and reliability

---

# 2. Few-Shot Learning

- Provide examples before the main task
- Format: Example 1 → Result 1, Example 2 → Result 2
- Creates a pattern for the model to follow
- Especially useful for specific formats or styles

---

# 3. Role Prompting

- Assign a specific role to the AI
- "Act as a senior software engineer..."
- Helps frame the context
- Gets more specialized responses

---

# 4. Temperature Control

- Adjust creativity vs. precision
- Lower (0.0-0.3): More focused, factual
- Higher (0.7-1.0): More creative, varied
- Choose based on task requirements

---

# 5. System Instructions

- Set clear boundaries and context
- Define behavior and limitations
- Establish response format
- Guide overall interaction style

---

# 6. Zero-Shot Prompting

- Direct questions without examples
- Clear, specific instructions
- Works well for straightforward tasks
- Requires precise wording

---

# 7. Task Decomposition

- Break complex tasks into smaller parts
- Solve incrementally
- Reduces errors
- Improves manageability

---

# 8. Constrained Output

- Specify exact response format
- Use JSON, CSV, or other structures
- Ensures consistent outputs
- Easier to parse and process

---

# 9. Iterative Refinement

- Start broad, then refine
- Ask for improvements or modifications
- Build upon previous responses
- Polish until satisfactory

---

# 10. Context Stacking

- Layer multiple contexts
- Combine different techniques
- Build comprehensive prompts
- Achieve more nuanced results

---
layout: end
---

# Thank you for your attention!
