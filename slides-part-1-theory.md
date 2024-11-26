---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Intro to Practical AI
info: |
  ## Intro to Practical AI

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

# Intro to Practical AI

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

---
layout: image
image: /ssa-ai.png
backgroundSize: contain
title: SSA AI Courses
---

<div class="absolute bottom-20 right-5">
  <a href="https://career.softserveinc.com/en-us/learning-and-certification/directions-ai">link</a>
</div>

---
layout: center
---

# What is AI?

# What is Generative AI?

# What is Practical AI?

---
layout: center
---

# What is Disruptive Technology?

---
layout: image
image: /timeline-of-tech-longterm.png
backgroundSize: contain
title: Timeline of Tech
---

---
layout: image
image: /timeline-of-tech-2000.png
backgroundSize: contain
title: Timeline of Tech 2000
---

---
layout: image
image: /tech-singularity.png
backgroundSize: contain
title: Singularity
---

---
layout: center
---

# What is AI?

# AI vs Non-AI?

---
layout: center
---

# AI vs Non-AI Applications

<div class="grid grid-cols-2 gap-4">
  <div>
    <h2 class="text-2xl font-bold mb-4">Non-AI</h2>
    <ul class="list-disc list-inside">
      <li>Fixed, rule-based logic</li>
      <li>Predictable outputs</li>
      <li>Manual updates required</li>
      <li>Limited to programmed scenarios</li>
      <li>Static behavior patterns</li>
    </ul>
  </div>
  <div>
    <h2 class="text-2xl font-bold mb-4">AI</h2>
    <ul class="list-disc list-inside">
      <li>Learning from data</li>
      <li>Adaptive responses</li>
      <li>Self-improving capabilities</li>
      <li>Handles unexpected scenarios</li>
      <li>Dynamic behavior patterns</li>
    </ul>
  </div>
</div>

---
layout: center
---

# AI Landscape

<div class="flex justify-center gap-4">
  <img src="/ai-landscape.png" class="h-80" />
  <img src="/ai-landscape-detailed.png" class="h-80" />
</div>

---
layout: center
---

# AI Conepts

<div class="flex grid-cols-2 gap-4">
  <img src="/ai-concepts.png" class="h-80" />
</div>

---
layout: center
---

# Neural Network

<div class="flex grid-cols-2 gap-4">
  <img src="/neural-network.png" class="h-80" />
</div>

---
layout: center
---

# AI models and human Abilities

---
layout: image
image: /human-ai.png
backgroundSize: contain
title: Human Abilities
---

---

# Types of Learning of AI Models

<div class="grid grid-cols-2 gap-4">
  <div>
    <h3>Supervised Learning</h3>
    <ul>
      <li>Learns from labeled data</li>
      <li>Predicts outcomes based on examples</li>
      <li>E.g., Image classification, spam detection</li>
    </ul>
  </div>

  <div>
    <h3>Unsupervised Learning</h3>
    <ul>
      <li>Finds patterns in unlabeled data</li>
      <li>Discovers hidden structures</li>
      <li>E.g., Clustering, anomaly detection</li>
    </ul>
  </div>

  <div>
    <h3>Reinforcement Learning</h3>
    <ul>
      <li>Learns through trial and error</li>
      <li>Maximizes rewards over time</li>
      <li>E.g., Game AI, robotics</li>
    </ul>
  </div>

  <div>
    <h3>Deep Learning</h3>
    <ul>
      <li>Uses neural networks with many layers</li>
      <li>Automatically learns features</li>
      <li>E.g., Computer vision, NLP</li>
    </ul>
  </div>
</div>

---
layout: image
image: /huggingface.png
backgroundSize: contain
title: Huggingface
---

---
layout: center
---

# Generative AI

---
layout: image
image: /gen-ai-explanation.png
backgroundSize: contain
title: Gen AI Explanation
---

---
layout: center
---

# Generating Myself

<img src="/myself-gen.png" class="h-80" />

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

# What is Software Engineering?

- Art
- Science
- Craft

---
layout: image
image: /art-science-craft-01.gif
title: Art, Science, Craft
---

---
layout: image
image: /art-science-craft-02.gif
title: Art, Science, Craft - Щось одне
---

---

# Why Craft?

- Algorithms
- Data Structures
- Programming Paradigms
- Software System Architectures
- Patterns, Principles, Practices
- Languages, Libraries, Frameworks
- Tools, Version Control Systems, CI/CD
- OS, Networks, Containers, Cloud Platforms

---
layout: center
---

# Main idea: no need to be creative or invent new knowledge, we need to learn and apply what has already been invented

---
layout: center
---

# What kind of work does AI handle best?

---
layout: center
---

# The AI Era in Software Engineering

---
layout: image
image: /ai-adoption-0-100-detailed.png
backgroundSize: contain
---

# Where are we now?

<style>
  h1 {
    color: black;
  }
  .slidev-layout {
    background-color: white;
  }
</style>

---
layout: image
image: /google-ai-code.png
backgroundSize: contain
---

<div class="absolute bottom-20 right-5">
  <a href="https://www.pcmag.com/news/ai-now-writes-over-25-percent-of-code-at-google">link</a>
</div>

---
layout: center
---

# Where LLM in SDLC?

---
layout: image
image: /sdlc.png
backgroundSize: contain
title: SDLC
---

---
layout: center
---

# What do we do during requirements analysis and design?

<v-click>
  Documents, diagrams, etc.
</v-click>

---
layout: image
image: /diagram-mermeid.gif
backgroundSize: contain
title: Mermeid
---

---
layout: center
---

# What about implementation?

---
layout: image
image: /gh-copilot.png
backgroundSize: contain
title: GitHub Copilot
---

---
layout: image
image: /gh-copilot-error.png
backgroundSize: contain
title: GitHub Copilot Error
---

---
layout: image
image: /gh-copilot-public-code.png
backgroundSize: contain
title: GitHub Copilot Public Code
---

---
layout: image
image: /copilot-in-github.gif
backgroundSize: contain
title: Copilot in GitHub
---

---
layout: image
image: /ms-ai-improves-ai.gif
backgroundSize: contain
title: MS Copilot Optimization
---

---
layout: image
image: /cursor-ide.png
backgroundSize: contain
title: Cursor IDE
---

---
layout: center
---

# Cursor IDE Benefits

<v-clicks>

- Built-in AI assistant powered by GPT-4
- AI-powered code generation and refactoring
- Intelligent code completion
- Code explanation and documentation
- Fast search and codebase navigation
- Integration with popular version control systems
- Support for multiple programming languages
- Free for personal use

</v-clicks>

---
layout: image
image: /cursor-ide-codegen.gif
backgroundSize: contain
title: Cursor IDE Code Generation
---

---
layout: center
---

# How to Make it Beautiful?

---
layout: image
image: /v0-dev.gif
backgroundSize: contain
title: v0.dev
---

<!--
https://v0.dev/chat/90t1YNyiuqQ?b=b_tECxpRUgJb8
-->

---
layout: center
---

# Code Reviews?

<v-click>
  CodeRabbit
</v-click>

---
layout: image
image: /coderabbit.gif
backgroundSize: contain
title: CodeRabbit
---

---
layout: center
---

# Agents

---
layout: image
image: /matrix-agents.png
backgroundSize: contain
title: Matrix Agents
---

---
layout: image
image: /software-agents.png
backgroundSize: contain
title: Software Agents with Rivet
---

---
layout: image
image: /openai-swarm.png
backgroundSize: contain
title: OpenAI Swarm
---

---
layout: image
image: /anthropic-computer-use.png
backgroundSize: contain
title: Anthropic Computer Use
---

---
layout: center
---

# SWE Bench

---
layout: image
image: /swe-bench.png
backgroundSize: contain
title: SWE Bench
---

---
layout: image
image: /bolt.new.gif
backgroundSize: contain
title: Bolt.new
---

---
layout: center
---

# Black Swan Effect

---
layout: image
image: /no-game-engine.png
backgroundSize: contain
title: No Game Engine
---

---
layout: center
---

# Assisted vs Augmented

<div class="grid grid-cols-2 gap-4">
  <div>
    <h2 class="text-2xl font-bold mb-4">AI Assisted</h2>
    <ul class="list-disc list-inside">
      <li>AI as a support tool</li>
      <li>Developer controls the process</li>
      <li>AI generates code on request</li>
      <li>Limited AI autonomy</li>
      <li>Focus on individual tasks</li>
    </ul>
  </div>
  <div>
    <h2 class="text-2xl font-bold mb-4">AI Augmented</h2>
    <ul class="list-disc list-inside">
      <li>AI as an active partner</li>
      <li>Human-AI collaboration</li>
      <li>AI proactively suggests solutions</li>
      <li>High AI autonomy</li>
      <li>Comprehensive development approach</li>
    </ul>
  </div>
</div>

---
layout: center
---

# Implementation Insights

---

# API Selection & Integration

- Evaluate available LLM APIs and their capabilities
- Compare pricing models and usage quotas
- Assess API documentation and support
- Consider API reliability and performance metrics

---

# Prompt Engineering

- Design effective prompts for desired outcomes
- Implement prompt templates and validation
- Handle API responses and error cases
- Optimize token usage and costs
- Test prompt consistency and reliability

---

# Cost Management

- API usage monitoring and optimization
- Request caching strategies
- Rate limiting implementation
- Fallback handling
- Budget tracking and alerts

---

# Security Best Practices

- API key management and rotation
- Input sanitization and validation
- Output content filtering
- User data protection
- Request/response logging

---

# Risk Mitigation

- API availability monitoring
- Response quality assessment
- Content moderation strategy
- Fallback mechanisms
- Regular performance reviews

---

# Implementation Guidelines

- Start with proof of concept
- Implement proper error handling
- Cache frequently used responses
- Monitor API usage and costs
- Maintain prompt engineering documentation

---
layout: end
---

# Thank you for your attention!
