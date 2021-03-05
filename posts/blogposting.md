---
title: 'Writing Blog Posts with Meta Data in Next JS'
date: '2021-03-04'
---

Writing blog posts is: **extremely simple** in Next.js. The only important thing is you need to utilize **Gray Matter** and **.md files**. Just to take up some space here is some stuff from a tutorial.

- **Static Generation** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then _reused_ on each request.
- **Server-side Rendering** is the pre-rendering method that generates the HTML on **each request**.

Importantly, Next.js lets you **choose** which pre-rendering form to use for each page. You can create a "hybrid" Next.js app by using Static Generation for most pages and using Server-side Rendering for others.
