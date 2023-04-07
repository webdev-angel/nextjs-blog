---
title: 'From Chaos to Tech: My Journey'
date: '2023-03-10'
---

In July 2021, I was a homeless single mother, working 3 part-time jobs, and living a highly chaotic life. Due to the COVID pandemic, **I'd lost two jobs** the year before; I only got one of those jobs back, and I'd secured another job to replace the second lost job. ***It still wasn't enough***. I needed a change.

Next.js has two forms of pre-rendering: **Static Generation** and **Server-side Rendering**. The difference is in **when** it generates the HTML for a page.

- **Static Generation** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then _reused_ on each request.
- **Server-side Rendering** is the pre-rendering method that generates the HTML on **each request**.

Importantly, Next.js lets you **choose** which pre-rendering form to use for each page. You can create a "hybrid" Next.js app by using Static Generation for most pages and using Server-side Rendering for others.