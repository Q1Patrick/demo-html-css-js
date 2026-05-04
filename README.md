# Demo HTML/CSS/JS – Review Notes for a 2nd-Year Student

This repository collects HTML/CSS practice files (with a small amount of JS/media), built in a **learn-and-practice** style. This README helps you:

- Quickly understand what is in the repo.
- Open the right files for each topic.
- Review core concepts before new assignments/interviews/practice.

---

## 1) Review Goals

After reviewing this repo, you should be able to:

1. Build a basic static page using semantic HTML.
2. Style a UI using CSS (box model, selectors, pseudo-classes).
3. Create layouts with `position`, `z-index`, grid/flex, and responsive rules.
4. Build a simple navbar, mini portfolio, sticky nav, and a 404 page.
5. Organize files by topic for easier maintenance.

---

## 2) Repository Structure & What to Study

> Tip: Review from top to bottom in this order.

### `image/`
This folder contains beginner-to-intermediate practice files:

- `index.html`, `index1.html` ... `index14.html`: mixed HTML/CSS exercises.
- `navbar.html` + `navbar.css`: navbar practice.
- `portfolio.html` + `portfolio.css`: simple portfolio practice.
- `aboutMeSkill.html` + `aboutMeSkill.css`, `listMySkill.html` + `listmeSkill.css`: profile and skills-list practice.
- `practice.html`, `practice1.html`, `reworkpractice.html`: revision/rework exercises.
- Media files (`.png`, `.mp4`, `.mp3`) for image/video/audio embedding practice.

### `week2/`
Focuses on common week-2 web fundamentals:

- `Position.html` + `Position.css`: `static`, `relative`, `absolute`, `fixed`, `sticky`.
- `Z_index.html` + `Z_index.css`: stacking order.
- `PseudoClass.html` + `PseudoClass.css`: `:hover`, `:active`, `:focus`, etc.
- `3layoutGrid.html` + `3layoutGrid.css`: grid-based layout.
- `responsiveLayout.html` + `responsiveLayout.css`, `mobile.html` + `mobile.css`: responsive layout and media queries.
- `porfolioResponsive.html` + `porfolioResponsive.css`: responsive portfolio practice.

### `MyPorfolio/`
- `Portfolio.html` + `Portfolio.css`: a separate portfolio version for mini-project review.

### `Sticky/`
- `stickyNav.html` + `stickyNav.css`: sticky navigation practice.

### `rework/`
- `basic.html`, `nav1.html`, `nav1.css`: refactor/rebuild foundational exercises.

### `animation /`
- `notFound404.html` + `notFound404.css`: 404 page and basic animation practice.

> Note: This folder name includes a trailing space (`animation `). Use quotes in terminal commands.

---

## 3) Pre-Exam / Pre-Practice Knowledge Checklist

- [ ] Understand block vs inline vs inline-block.
- [ ] Explain the box model and `box-sizing: border-box`.
- [ ] Use `position` + `z-index` correctly.
- [ ] Build a basic navbar and hover states.
- [ ] Use common pseudo-classes correctly.
- [ ] Build layouts with Grid/Flex.
- [ ] Make pages responsive with media queries.
- [ ] Split HTML/CSS into clear modules.

---

## 4) Quick Local Run Guide

Since this project is mostly static files, use one of these:

### Option 1: Open `.html` directly
- Double-click an HTML file to open it in your browser.

### Option 2 (Recommended): Use Live Server (VS Code)
1. Install the **Live Server** extension.
2. Right-click an HTML file (for example, `week2/responsiveLayout.html`).
3. Choose **Open with Live Server**.

---

## 5) Effective Study Tips for a 2nd-Year Student

1. **Do not just read code** → edit and reload to see immediate results.
2. Focus on one big topic per session (for example, only Position).
3. After each session, write 3 short reflection lines: “What did I understand today?”
4. Sketch layouts on paper before coding when stuck.
5. Prefer clean, meaningful class names.

---

## 6) Extra Practice Tasks (Recommended)

- Build a one-page responsive CV.
- Build a navbar with a mobile hamburger menu.
- Build a simple landing page with 3 sections:
  - Hero
  - Features
  - Contact
- Improve the 404 page from `animation /notFound404.*`.

---

## 7) Preparation for Year 3

After you are confident with HTML/CSS, continue in this order:

1. JavaScript DOM + Events.
2. ES6+ (`let/const`, arrow functions, map/filter, modules).
3. Standard Git/GitHub workflow.
4. One frontend framework (React is a common choice).
5. Basic API/JSON usage and static deployment.

---

Good luck with your revision and keep coding consistently 💪
