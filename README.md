# 🌐 HTML Exercises — Weeks 2, 3 & 4

**Instructors:** Amra Abazi Feta & Lorik Limani

> A hands-on, project-based HTML course where students build a **real personal portfolio website** from scratch — week by week, lesson by lesson.

---

## 🎯 Course Overview

This module spans **3 weeks** of guided HTML exercises. By the end, you will have built a complete, semantic, accessible portfolio website using only HTML — exactly like professional developers do.

| Week | Focus | Key Topics |
|------|-------|------------|
| [Week 2](#week-2--foundation) | Foundation | Document structure, text, lists, links, images |
| [Week 3](#week-3--structure) | Structure | Tables, forms, semantic HTML, meta tags |
| [Week 4](#week-4--advanced--final) | Advanced & Final | Multimedia, iframes, accessibility, best practices |

---

## 📁 Project Structure

Each week builds on the previous one. You will work on a single `index.html` file throughout the course, adding new features each week.

```
your-portfolio/
├── index.html         ← Your main file (built over 3 weeks)
└── images/
    └── profile.jpg    ← Your profile photo
```

---

## Week 2 — Foundation

> **Goal:** Create your first HTML page with structure, text, and formatted content.

### Lessons

**Lesson 1 — What is HTML?**
- HTML document structure: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
- How tags work: opening, closing, and self-closing tags
- The `<meta charset>`, `<title>`, and `<viewport>` tags

**Lesson 2 — Text and Headings**
- Heading levels `<h1>` through `<h6>` (use only **one** `<h1>` per page!)
- Paragraph tags `<p>`
- Inline formatting: `<strong>`, `<em>`, `<mark>`, `<del>`, `<small>`
- Line breaks `<br>` and horizontal rules `<hr>`

**Lesson 3 — Lists**
- Unordered lists `<ul>` with `<li>` items
- Ordered lists `<ol>` with `<li>` items
- Nested lists (lists inside lists)

**Lesson 4 — Links and Images**
- Anchor tags `<a href="">` with `target="_blank"` and `mailto:` links
- Images `<img src="" alt="">` with width/height control
- Making images into clickable links

### ✏️ Week 2 Exercises

| # | Exercise | What You Build |
|---|----------|----------------|
| 1 | Create Your HTML File | A working `index.html` with the base structure |
| 2 | Build Text Content | Your name, About Me section with formatted text |
| 3 | Add Lists | Skills list (unordered) + Learning steps (ordered) |
| 4 | Links & Images | Profile photo, 3+ links including email and external |

### ✅ Week 2 Checklist
- [ ] Page has exactly ONE `<h1>` tag
- [ ] At least 3 `<h2>` sections
- [ ] `<strong>` and `<em>` tags used
- [ ] Both a `<ul>` and an `<ol>` present
- [ ] At least one working link
- [ ] An image with `alt` text

---

## Week 3 — Structure

> **Goal:** Add a projects table, a contact form, and restructure the page using semantic HTML5 tags.

### Lessons

**Lesson 1 — HTML Tables**
- Table structure: `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
- Merging cells with `colspan` and `rowspan`
- ⚠️ Use tables for **data** only — not for page layout

**Lesson 2 — HTML Forms**
- The `<form>` element with `action` and `method` attributes
- Input types: `text`, `email`, `password`, `number`, `date`, `checkbox`, `radio`, `submit`
- Labels: always pair `<label for="">` with `<input id="">`
- Textarea and dropdown `<select>` with `<option>` items
- The `required` attribute for browser-side validation

**Lesson 3 — Semantic HTML**
- Semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- Anchor links using `id` attributes (`<a href="#about">`)
- Full page restructure with semantic layout

**Lesson 4 — HTML Entities & Meta Tags**
- Common entities: `&copy;`, `&amp;`, `&lt;`, `&gt;`, `&nbsp;`, `&mdash;`
- SEO meta tags: `description`, `keywords`, `author`
- Updating the `<title>` with your name

### ✏️ Week 3 Exercises

| # | Exercise | What You Build |
|---|----------|----------------|
| 1 | Projects Table | A 3-column table listing your projects |
| 2 | Contact Form | Full form with labels, inputs, dropdown, and textarea |
| 3 | Semantic Restructure | Wrap page in `<header>`, `<main>`, `<section>`, `<footer>` |
| 4 | Head Section Polish | Meta tags, author, description, updated title |

### ✅ Week 3 Checklist
- [ ] Page has `<header>`, `<main>`, and `<footer>`
- [ ] Each section has a unique `id`
- [ ] Nav links jump to sections (anchor links work)
- [ ] Projects table has `<thead>` and `<tbody>`
- [ ] All form inputs have associated `<label>` tags
- [ ] Footer uses `&copy;` symbol
- [ ] Meta `description` tag is written

---

## Week 4 — Advanced & Final

> **Goal:** Add multimedia, iframes, and accessibility improvements. Complete your full portfolio in HTML.

### Lessons

**Lesson 1 — Audio and Video**
- `<video>` with `controls`, `autoplay`, `muted`, `loop`, `poster`
- `<audio>` with `controls` and multiple `<source>` fallbacks
- Always provide multiple formats (MP4 + WebM, MP3 + OGG)

**Lesson 2 — Embedding with `<iframe>`**
- Embedding YouTube videos (use `embed/VIDEO_ID` format)
- Embedding Google Maps (Share → Embed a map)
- Always add a descriptive `title` attribute to iframes
- 🔒 Only embed content from trusted sources

**Lesson 3 — Accessibility (a11y)**
- ARIA attributes: `aria-label`, `aria-hidden`, `role`, `aria-required`, `aria-expanded`
- Keyboard navigation with `tabindex`
- Skip navigation links (`<a href="#main">Skip to main content</a>`)
- Color contrast requirements (WCAG 4.5:1 minimum)
- `lang` attribute on `<html>` tag

**Lesson 4 — Advanced HTML Elements**
- `<details>` / `<summary>` for native accordions (no JavaScript!)
- `<blockquote>` and `<cite>` for quotations
- `<code>`, `<pre>`, `<kbd>` for displaying code and keyboard keys
- `<figure>` and `<figcaption>` for semantic image captions
- `<datalist>` for searchable input suggestions
- `<progress>` and `<meter>` for skill bars

**Lesson 5 — Best Practices & Validation**
- HTML best practices (lowercase tags, close all tags, semantic structure)
- W3C Markup Validator: [validator.w3.org](https://validator.w3.org)
- Code commenting conventions

### ✏️ Week 4 Exercises

| # | Exercise | What You Build |
|---|----------|----------------|
| 1 | Media Section | Video or embedded YouTube + `<iframe>` |
| 2 | YouTube & Maps | Embedded YouTube tutorial + Google Maps in Contact |
| 3 | Accessibility Audit | ARIA labels, skip links, `lang`, keyboard nav |
| 4 | Advanced Elements | `<figure>`, `<details>`, `<progress>`, `<blockquote>` |

---

## 🏆 Final Portfolio Challenge

Your completed portfolio must include **all** of the following:

| Section | Requirements |
|---------|-------------|
| **Structure** | Semantic `<header>`, `<nav>`, `<main>`, `<footer>` with anchor links |
| **About** | `<h1>` name, profile photo in `<figure>`, bio with `<strong>` & `<em>`, `<blockquote>`, `<details>` |
| **Skills** | Unordered list + `<progress>` bars for at least 3 skills |
| **Projects** | Full table (`<thead>` + `<tbody>`) with 3+ projects and links |
| **Media** | Embedded YouTube video with `title` attribute |
| **Contact** | Form with labels, text, email, textarea, datalist/select, and submit button |
| **Footer** | `&copy;` copyright, year, your name |
| **Head** | `charset`, `viewport`, `description`, `author` meta tags + descriptive `<title>` |

**Bonus:**
- ✅ Validate at [validator.w3.org](https://validator.w3.org) with zero errors
- ✅ Full keyboard navigation (Tab key only)
- ✅ All images have meaningful `alt` text

---

## 🔧 Tools & Resources

| Tool | Purpose |
|------|---------|
| [VS Code](https://code.visualstudio.com/) | Recommended code editor |
| [validator.w3.org](https://validator.w3.org) | HTML validation |
| [webaim.org/resources/contrastchecker](https://webaim.org/resources/contrastchecker/) | Color contrast checker |
| **VS Code Extension:** HTML CSS Support | Autocomplete for HTML & CSS |
| **VS Code Extension:** Auto Rename Tag | Auto-updates closing tags |

---

## 📚 Topics at a Glance

<details>
<summary><strong>Week 2 — Foundation</strong></summary>

- HTML document structure, DOCTYPE, head, body  
- Headings h1–h6, paragraphs, line breaks  
- Text formatting: strong, em, mark, del, small  
- Ordered and unordered lists, nested lists  
- Links with anchor tags, href, target, mailto  
- Images with img, src, alt, width, height  

</details>

<details>
<summary><strong>Week 3 — Structure</strong></summary>

- HTML Tables with thead, tbody, tr, th, td  
- Cell merging with colspan and rowspan  
- Forms: input types, labels, textarea, select  
- Form validation with required attribute  
- Semantic HTML5 tags: header, nav, main, section, article, aside, footer  
- Anchor links and page navigation with id  
- HTML Entities and Meta tags  

</details>

<details>
<summary><strong>Week 4 — Advanced</strong></summary>

- Video and audio elements with multiple sources  
- Embedding content with iframes (YouTube, Google Maps)  
- Accessibility: ARIA roles, aria-label, aria-hidden, keyboard nav  
- Advanced elements: details, summary, figure, figcaption, progress, meter, datalist  
- Code display: code, pre, kbd  
- HTML best practices and W3C validation  

</details>

---

## 🚀 What's Next?

You now have the **structure**. Next step: **CSS** — make your portfolio beautiful!

---

*Built with ❤️ by students learning web development.*
