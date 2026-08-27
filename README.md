# Single-Page Semantic HTML CV by Kunal Guhagarkar

A clean, modern, and accessible single-page web CV built with HTML5 semantic elements, essential SEO metadata, Open Graph (OG) social tags, and browser favicon integration. Designed to serve as a clean document tree ready for styling with modern CSS.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Submission Criteria Verification](#submission-criteria-verification)
- [File Architecture](#file-architecture)
- [HTML Document Outline](#html-document-outline)
- [Quick Start](#quick-start)
- [Next Steps & Enhancements](#next-steps--enhancements)
- [License](#license)

---

## Project Overview

This project implements a standard personal resume/CV using semantically meaningful HTML markup. It prioritizes Accessibility (a11y), Search Engine Optimization (SEO), and clean structural hierarchy, ensuring search engine crawlers and screen readers can parse the content seamlessly.

---

## Key Features

- **Semantic Layout:** Structured using landmark HTML5 elements (`<header>`, `<main>`, `<section>`, `<address>`) for clean navigation and accessibility.
- **SEO & Social Optimization:** Comprehensive `<head>` configuration containing metadata, viewports, and Open Graph tags for optimized link previews on platforms like LinkedIn and Twitter.
- **Favicon Support:** Standardized `<link>` tags for browser tab identity.
- **Form-Ready Structure:** Organizes skills, education, certifications, and developer details in modular sections ready for CSS layout frameworks (Flexbox, CSS Grid, Tailwind CSS).

---

## Submission Criteria Verification

| Requirement | Implementation Details | Status |
| :--- | :--- | :---: |
| **Semantic HTML** | Uses `<header>`, `<main>`, `<section>`, `<address>`, `<h1>`–`<h4>`, and contextual tags (`<p>`, `<a>`, `<b>`, `<i>`). | ✅ Passed |
| **Single-page Layout** | All professional sections (Intro, Skills, Education, Certifications) are combined seamlessly on one page. | ✅ Passed |
| **SEO Meta Tags** | `charset="UTF-8"`, `viewport`, `author`, `description`, and `<title>` defined in `<head>`. | ✅ Passed |
| **Open Graph (OG) Tags** | `og:type`, `og:title`, and `og:description` meta properties configured. | ✅ Passed |
| **Favicon Integration** | `<link rel="shortcut icon" href="./images/Kunal.png" type="image/png" />` configured. | ✅ Passed |

---

## File Architecture

```text
.
├── index.html        # Main semantic HTML CV page
├── style.css         # Linked stylesheet (ready for CSS implementation)
└── images/
    └── Kunal.png     # Favicon asset
```

---

## HTML Document Outline

``` text
Document (index.html)
 ├── <head>
 │    ├── Meta (UTF-8, Viewport, Author, Description)
 │    ├── Open Graph Tags (type, title, description)
 │    ├── Favicon Link
 │    └── Page Title
 └── <body>
      ├── <header>
      │    ├── Name & Title (h1, h3)
      │    ├── Contact Address (<address>)
      │    └── Social / Email Links (div.links-container)
      └── <main>
           ├── <section id="intro-container"> (Professional Summary)
           ├── <section id="skill-container"> (Frontend, Backend, DB, UI/UX, Tools)
           ├── <section id="education-container"> (MCA & BSc IT Qualifications)
           └── <section id="certification-container"> (META Certifications)
```
---

## Quick Start

1. Clone the repository:

    ``` bash
    git clone [https://github.com/KunalGuhagarkar/semantic-html-cv.git](https://github.com/KunalGuhagarkar/semantic-html-cv.git)
    cd semantic-html-cv
    ```

2. Run locally:
    Open index.html in any web browser, or launch it using VS Code's Live Server extension.

---

## Next Steps & Enhancements

- CSS Styling: Apply visual formatting via CSS Grid or Flexbox in style.css.

- Extended OG Tags: Add an og:image meta property to display a visual snippet when sharing link previews on social platforms.

- Accessibility Audit: Validate with Lighthouse or WAVE tools for WCAG compliance.

---

## License

Distributed under the MIT License.