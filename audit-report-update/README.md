# Allan K. – Accessibility Portfolio

Two demo projects for my Upwork portfolio. Plain HTML, CSS and JavaScript, no frameworks.

| Folder | What it is |
|---|---|
| `accessibility-case-study/` | Before-and-after WCAG 2.2 fix of a fictional bakery site. `index.html` is the case study, `before.html` is the broken page, `after.html` is the fixed page. |
| `accessible-landing-page/` | Responsive, accessible landing page for a fictional tour company (keyboard menu, FAQ accordion, accessible booking form, dark mode). |
| `sample-audit-report/` | A sample WCAG 2.2 AA audit report of the bakery "before" page: 18 prioritised findings with fixes, contrast table and fix plan. Includes a downloadable PDF. |

---

## Step 1: Fill in your real test scores (10 minutes)

Do this before publishing. Never put numbers you didn't measure in front of clients.

1. Open `accessibility-case-study/before.html` in Chrome.
2. Right-click → **Inspect** → **Lighthouse** tab → tick only **Accessibility** → **Analyze page load**. Write down the score.
3. Do the same for `after.html`.
4. Install the free **WAVE** browser extension and run it on both pages. Write down the number of **Errors**.
5. Open `accessibility-case-study/index.html` in a text editor, find the `TODO (Allan)` comment and replace the `XX` values with your real numbers.
6. Take screenshots of both Lighthouse results. You'll use them as Upwork portfolio images.

The "How I tested" section mentions the NVDA screen reader. NVDA is free for Windows (nvaccess.org). Spend 15 minutes trying both pages with it so you can talk about it honestly with clients, or delete that line.

## Step 2: Publish free on GitHub Pages

1. Sign in to github.com (your account is already linked to Upwork).
2. Click **New repository**, name it `accessibility-portfolio`, make it **Public**, click **Create**.
3. Click **uploading an existing file**, drag in both folders and this README, then **Commit changes**.
4. Go to **Settings → Pages**. Under "Branch", choose `main` and `/ (root)`, then **Save**.
5. After 1–2 minutes your pages are live at:
   - `https://YOUR-USERNAME.github.io/accessibility-portfolio/accessibility-case-study/`
   - `https://YOUR-USERNAME.github.io/accessibility-portfolio/accessible-landing-page/`

## Step 3: Add them to Upwork

Profile → **Portfolio** → **+** for each project:

**Project 1 title:** Website Accessibility Audit & Fix (WCAG 2.2 AA) – Case Study
- Role: Front-end developer & accessibility tester
- Description: Audited a small business homepage and fixed 16 accessibility issues: colour contrast, alt text, keyboard navigation, focus states, form labels and errors, heading structure and more. Includes before/after Lighthouse and WAVE results.
- Skills: Web Accessibility, Web Content Accessibility Guidelines, Accessibility Testing, HTML5, CSS
- Images: your Lighthouse before/after screenshots + a screenshot of the issues table
- Link: your GitHub Pages case study URL

**Project 2 title:** Accessible, Responsive Landing Page (HTML/CSS/JS)
- Role: Front-end developer
- Description: Mobile-first landing page built to WCAG 2.2 AA: keyboard-friendly menu, accessible FAQ accordion, booking form with clear error messages, dark mode and reduced-motion support. No frameworks.
- Skills: Landing Page, Responsive Design, Front-End Development, JavaScript, Web Accessibility
- Images: desktop and mobile screenshots
- Link: your GitHub Pages landing page URL

**Project 3 title:** Sample Website Accessibility Audit Report (WCAG 2.2 AA)
- Role: Accessibility auditor
- Description: A full sample of the audit report clients receive: plain-English summary, test scores, 18 findings rated Critical to Minor, each with the WCAG rule, who it affects and a code fix, plus a contrast table and a phased fix plan with time estimates.
- Skills: Web Accessibility, Accessibility Testing, Web Content Accessibility Guidelines, Website Audit
- Images: screenshots of the report's cover, summary and a findings page (or upload the PDF)
- Link: `https://allankoaik.github.io/accessibility-portfolio/sample-audit-report/`

## Notes
- Both businesses are fictional, and the pages say so. Photos load from Unsplash.
- The "Hire me on Upwork" link in the case study points to your Upwork profile.
