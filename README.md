# Social Proof Section

A responsive social proof section built as a solution to the [Frontend Mentor "Social proof section" challenge](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). The section combines a marketing headline, a set of star-rating badges, and three customer testimonial cards to build trust and credibility on a landing page.

![Design preview](./design/desktop-preview.jpg)

## Overview

### The Challenge

Build the section so that users can:

- View the optimal layout for the component depending on their device's screen size
- See hover/focus states for all interactive elements

### Layout

- **Headline & copy** — bold marketing statement with supporting paragraph
- **Rating badges** — three horizontal cards, each showing a 5-star rating and the platform it was rated on (Reviews, Report Guru, BestTech)
- **Testimonial cards** — three customer quotes, each with an avatar, name, "Verified Buyer" label, and review text

On mobile, sections stack vertically (headline → ratings → testimonials). On desktop, the headline and rating badges sit side by side above the row of testimonial cards, with the middle and right testimonial cards offset vertically for visual rhythm.

## Built With

- Semantic HTML5 markup
- CSS3 — Flexbox and/or CSS Grid for layout
- Mobile-first responsive workflow
- Google Fonts: [League Spartan](https://fonts.google.com/specimen/League+Spartan) (weights 400, 500, 700)

## Design Reference

| | Value |
|---|---|
| Mobile design width | 375px |
| Desktop design width | 1440px |
| Primary — Very Dark Magenta | `hsl(300, 43%, 22%)` |
| Primary — Soft Pink | `hsl(333, 80%, 67%)` |
| Neutral — Dark Grayish Magenta | `hsl(303, 10%, 53%)` |
| Neutral — Light Grayish Magenta | `hsl(300, 24%, 96%)` |
| Neutral — White | `hsl(0, 0%, 100%)` |
| Body font size | 15px |

Full details are available in [`style-guide.md`](./style-guide.md), and static reference designs are in the [`design/`](./design) folder.

## Project Structure

```
social-proof-section/
├── index.html
├── style.css
├── images/
│   ├── bg-pattern-top-desktop.svg
│   ├── bg-pattern-top-mobile.svg
│   ├── bg-pattern-bottom-desktop.svg
│   ├── bg-pattern-bottom-mobile.svg
│   ├── icon-star.svg
│   ├── image-colton.jpg
│   ├── image-irene.jpg
│   ├── image-anne.jpg
│   └── favicon-32x32.png
├── design/
│   ├── mobile-design.jpg
│   └── desktop-design.jpg
└── style-guide.md
```

## Getting Started

This is a static HTML/CSS project with no build step.

1. Clone the repository.
2. Open `index.html` in your browser, or serve the folder with a local dev server (e.g. VS Code "Live Server") for the best experience.

## Links

- Solution URL: _add your repo URL here_
- Live Site URL: _add your deployed URL here_

## Author

- Frontend Mentor — [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

- Challenge by [Frontend Mentor](https://www.frontendmentor.io)