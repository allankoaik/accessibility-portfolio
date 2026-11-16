# Accessibility Portfolio

Two front-end projects that show how to build websites everyone can use, including people who rely on keyboards, screen readers, zoom or high contrast. Both are written in plain HTML, CSS and JavaScript with no frameworks or build step, and target **WCAG 2.2 Level AA**.

**Live demos**

- [Accessibility case study: Seabreeze Bakery](https://allankoaik.github.io/accessibility-portfolio/accessibility-case-study/)
- [Accessible landing page: Reefline Island Tours](https://allankoaik.github.io/accessibility-portfolio/accessible-landing-page/)

---

## 1. Accessibility case study: Seabreeze Bakery

A before-and-after remediation of a typical small business homepage. The "before" page looks fine at a glance but has the accessibility problems found on many real sites. The "after" page keeps the same design and content and is rebuilt to meet WCAG 2.2 AA.

| Page | Description |
|---|---|
| [`index.html`](accessibility-case-study/index.html) | The case study: results, issues found, fixes and testing approach |
| [`before.html`](accessibility-case-study/before.html) | The original, inaccessible page |
| [`after.html`](accessibility-case-study/after.html) | The fixed page |

**16 issues fixed**, including:

- **Colour contrast:** worst text contrast improved from 1.6:1 to 6.3:1 (the minimum is 4.5:1)
- **Keyboard access:** clickable `<div>`s replaced with real buttons and links, a visible focus ring, and a skip link
- **Screen readers:** alt text, page language and title, a logical heading structure and landmarks
- **Forms:** visible labels, `autocomplete`, and specific error messages with a focused error summary
- **Mobile menu:** a labelled button with `aria-expanded` that closes with Escape
- **Motion:** auto-rotating reviews now have pause, previous and next controls, and respect reduced-motion settings
- **Zoom and touch:** pinch-zoom re-enabled, text that scales, and 44×44px touch targets
- **Status messages:** a pop-up `alert()` replaced with a polite live-region announcement

## 2. Accessible landing page: Reefline Island Tours

A mobile-first, responsive landing page for a tour company, built accessibly from the start.

- Keyboard-friendly navigation and mobile menu
- Accessible FAQ accordion
- Booking form with clear labels and error messages
- Dark mode (follows the system setting)
- Reduced-motion support
- Semantic HTML with landmarks and a logical heading structure

## Testing

- Lighthouse and axe DevTools
- WAVE
- Keyboard-only navigation
- NVDA screen reader
- Mobile and 200% zoom checks

## Running locally

No installation needed. Clone the repository and open any `index.html` file in a browser:

```bash
git clone https://github.com/allankoaik/accessibility-portfolio.git
```

## Built with

HTML5 · CSS3 · Vanilla JavaScript · WAI-ARIA

## Notes

Seabreeze Bakery and Reefline Island Tours are fictional businesses created for these demos. Photos are from [Unsplash](https://unsplash.com).

## Author

**Allan K.**, front-end developer focused on web accessibility.
Available for accessibility audits and fixes on HTML, WordPress, Shopify and Wix sites: [hire me on Upwork](https://www.upwork.com/freelancers/~01d9e8d935bae67b07).
