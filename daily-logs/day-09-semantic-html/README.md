# Day 9: Semantic HTML 

**Date:** August 2, 2025

## 📝 Topics Covered Today

* **What is Semantic HTML?** : Understanding the importance of using HTML elements that convey meaning about their content.
* **`<header>` and `<footer>`** : Using these for introductory/navigational content and concluding content, respectively.
* **`<nav>`** : Specifically for navigation links.
* **`<main>`** : The main content of the document.
* **`<section>` and `<article>`** (3:20:00): Structuring content into meaningful, standalone blocks.
* **`<aside>`** : For content that is tangentially related to the main content.

## 💡 Key Concepts & Takeaways

* **Semantic HTML improves accessibility, SEO, and readability:** It gives meaning to your page's structure beyond just visual layout.
* **`<header>`:** Contains introductory content or navigational links.
* **`<nav>`:** Used for primary navigation blocks.
* **`<main>`:** Contains the dominant content of the `<body>`. There should only be one per document.
* **`<section>`:** A standalone section that has a logical grouping of content, often with its own heading.
* **`<article>`:** Represents independent, self-contained content (like a blog post, news article, or individual project description). Can be nested within `section`.
* **`<footer>`:** Contains information about its containing element (e.g., copyright, author, contact info).
* **Replace generic `div`s:** Where a more specific semantic tag exists, use it.

## 💻 Daily Exercises & Code Examples

Here are the small, isolated practice files created today:

* **[Semantic Layout Demo](./exercises/semantic-layout-demo.html)**: Practice structuring a page with header, nav, main, section, footer.
* **[Article and Aside Usage](./exercises/article-aside-usage.html)**: Demonstrating specific semantic tags.

## 🏗️ Portfolio Project Progress

Today, I performed a major refactor of my portfolio's HTML structure, making it semantically meaningful.

* Replaced generic `div`s with `header`, `nav`, `main`, `section`, and `footer` across all three pages (`index.html`, `projects.html`, `contact.html`).
* Ensured the navigation was correctly nested within the `<nav>` tag, typically inside the `<header>`.

**[View Today's Portfolio Project File (index.html)](../../project/index.html)**
**[View Today's Portfolio Project File (projects.html)](../../project/projects.html)**
**[View Today's Portfolio Project File (contact.html)](../../project/contact.html)**

---

## 🤔 Daily Reflection

Today was a huge step in understanding professional HTML development! Shifting from just using `div`s to semantic tags feels much more logical and robust. It's clear how this improves not only how search engines interpret my site but also how assistive technologies will navigate it. This refactoring process really helped solidify my understanding of page structure.

**Challenges/Questions:**
* No challenges everything run smoothly

**Next Steps:**
* Prepare for Day 10, focusing on tables and scientific elements.

---

**[< Back to Main Log README](../../README.md)**