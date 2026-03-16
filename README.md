# SEO Lighthouse Demo

This repository contains a small webpage that is intentionally poorly optimized for SEO.  
Your goal is to improve the page and increase the Lighthouse scores.

---

# Repository Contents

- `starter/index.html` — intentionally poor version to optimize
- `solution/index.html` — example of an optimized version that has a high SEO score
- `assets/` — images used in the page

---

# Setup

## 1. Clone the repository

Run the following commands in your terminal:


git clone https://github.com/vu-cs4289-26s/seo-demo.git

cd your-path/seo-demo


## 2. Start a local server

From the repository root (seo-demo) run:


python3 -m http.server 8000


This starts a simple local web server.

## 3. Open the webpage

Open this URL in an incognito window in **Chrome**:


http://localhost:8000/starter/index.html


---

# Running Lighthouse

1. Open the page in Chrome.
2. Right click anywhere on the page.
3. Click **Inspect**.
4. Open the **Lighthouse** tab in DevTools.
5. Select:
   - Performance
   - Accessibility
   - Best Practices
   - SEO
6. Click **Analyze page load**.

Lighthouse will generate a report with scores for each category.

---

# Challenge

Your goal is to improve the Lighthouse scores by editing:


starter/index.html


Try to maximize the **SEO score**, while also improving the other categories if possible.

You may modify:

- HTML structure
- metadata (title, meta tags)
- image attributes
- accessibility issues
- semantic HTML
- CSS and layout
- JavaScript behavior

Do **not**:

- create additional files
- delete most of the page to game the score

---

# Goal

Increase the Lighthouse scores as much as possible and be ready to explain:

- what changes you made
- why those changes improved the score
- which Lighthouse issues you fixed