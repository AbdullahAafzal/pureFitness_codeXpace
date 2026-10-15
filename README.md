# Pure Fitness — Complete React Website

Responsive, premium single-page React website plus separate Contact, Privacy Policy, Terms & Conditions, and Cookie Policy routes. Built with React, Vite, Framer Motion and Lucide icons.

## Start

```bash
npm install
npm run dev
```

Production build: `npm run build`. For static SPA hosting, configure fallback routing to `index.html` (`public/_redirects` is included for Netlify).

## Editable content

- `src/data/siteData.js` — ALL website text, theme colors, programs, FAQs, contact email and legal text.
- `src/assets/images.js` — central image URLs and logo path.
- `public/assets/images/logo.png` — supplied Pure Fitness logo.
- `src/main.jsx` — React components and page routes.
- `src/styles/main.css` — visual design and responsive layout.

## Pages

- `/` — complete responsive landing page (including contact CTA section)
- `/contact` — email-only contact page
- `/privacy-policy` — Privacy Policy
- `/terms-and-conditions` — Terms & Conditions
- `/cookie-policy` — Cookie Policy (extra)

## Before publishing

1. Replace `CONTACT_EMAIL@example.com` with a verified business email in `src/data/siteData.js`. The email link only activates once configured.
2. Review and replace provisional Privacy, Terms and Cookies text with approved legal wording reflecting real site practices.
3. Confirm correct Pure Fitness brand authority and image/logo permissions. Images are externally hosted demo stock URLs until replaced.
4. Confirm any factual training-program claims and official brand copy.

No booking/payment features are claimed or connected. No live contact-form backend is needed because the stated requirement is email-only.
