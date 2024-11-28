---
# Ви також можете просто почати з 'default'
theme: default
# випадкове зображення з кураторської колекції Unsplash від Anthony
# подобається? дивіться https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# деяка інформація про ваші слайди (підтримується markdown)
title: Практичний AI для бізнесу - частина 1
info: |
  ## Практичний AI для бізнесу - частина 1

# застосувати класи unocss до поточного слайду
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# перехід між слайдами: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# увімкнути синтаксис MDC: https://sli.dev/features/mdc
mdc: true
# робити знімок кожного слайду в огляді
overviewSnapshots: true
---

# Практичний AI для бізнесу - частина 1

В'ячеслав Колдовський

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
Останній блок коментарів кожного слайду буде розглядатися як нотатки до слайду. Він буде видимим та редагованим у режимі презентатора разом зі слайдом. [Дізнайтеся більше в документації](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-left
image: /vyacheslav-koldovskyy.png
---

# В'ячеслав Колдовський

- Кандидат наук, доцент
- 20+ років в ІТ
- Менеджер компетентностей [SoftServe Academy](https://career.softserveinc.com/uk-ua/learning-and-certification/)
- Сертифікований професійний архітектор Google Cloud
- Ентузіаст генеративного AI
- Блогер [t.me/programmingmentor](https://t.me/programmingmentor)
- Ютубер [youtube.com/c/programmingmentorua](https://www.youtube.com/c/programmingmentorua)

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
layout: center
---

# Руйнівні технології

---
layout: image-left
image: /timeline-of-tech-longterm.png
---

# Справа в тому, що зміни не просто відбуваються, вони прискорюються

---
layout: image
image: /disruptive-tech.png
---

---

# Військові ігри з LLM

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
layout: image
image: /ai-gen-ai.jpg
backgroundSize: contain
---

---
layout: image
image: /human-ai.png
backgroundSize: contain
---

---
layout: image
image: /discriminant-vs-generative.png
backgroundSize: contain
---

---
layout: center
---

# LLM - Великі Мовні Моделі

---
layout: center
---

# Чому Мовна Модель?

<img src="/why-language.png" class="h-80" />

---
layout: center
---

# Чому Велика?

<img src="/why-large.png" class="h-80" />

---
layout: center
---

# Трансформер

<img src="/transformer.png" class="h-80" />

---
layout: image
image: /ft-transformer.png
backgroundSize: contain
title: FT Трансформер
---

<div class="absolute bottom-20 right-5">
  <a href="https://ig.ft.com/generative-ai/">візуалізація</a>
</div>

---
layout: center
---

# Яка LLM найкраща?

---
layout: image
image: /chatbot-arena-overall.png
backgroundSize: contain
title: Загальний рейтинг Chatbot Arena
---

<div class="absolute bottom-20 right-5">
  <a href="https://lmarena.ai/">посилання</a>
</div>

---
layout: image
image: /chatbot-arena-coding.png
backgroundSize: contain
title: Рейтинг кодування Chatbot Arena
---

---
layout: center
---

# Мультимодальні LLM

<img src="/multimodal-llm.png" class="h-80" />

---
layout: center
---

# Використання та застосування LLM

- Генерація та узагальнення тексту
- Допомога з кодом та документацією
- Переклад мов
- Створення та редагування контенту
- Автоматизація підтримки клієнтів
- Аналіз даних та інсайти
- Освіта
- ... багато іншого

---
layout: center
---

# Обмеження LLM

- Галюцинації та фактичні неточності
- Обмеження контекстного вікна
- Обмеження навчальних даних
- Упередженість та етичні проблеми
- Високі обчислювальні витрати
- Обмежені знання в реальному часі

---
layout: center
---

# Це diffusion моделі, але теж генеративні

<img src="/avatar.png" class="h-80" />

---
layout: center
---

# Сюрприз! Я теж згенерований

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

# Groq

https://groq.com/

<img src="/groq.png" class="w-full" />

---

# Together AI

https://www.together.ai/

<img src="/together-ai.png" class="w-full" />

---

# Практика CV

<img src="/cv-practice.png" class="w-full" />

---

# Зробимо презентацію?

<img src="/gamma.png" class="w-full" />

---
layout: center
---

# А якщо зробити щось таке, що ми не вміємо в принципі?

---

# Згенеруємо пісню?

<img src="/suno.png" class="w-full" />

---

# Зробимо сайт чи програму?

<img src="/bolt.png" class="w-full" />


---
layout: end
---

# Дякую за увагу!

<img src="/qr.png" class="w-48 mx-auto mt-4" alt="QR Code">

https://programmingmentor.github.io/2024-slidev-ai-for-business-part-1/
