# responsive-portfolio
# Lab 3 – Responsive Portfolio (Flexbox, Grid, Media Queries, Animations)

A one-page responsive portfolio built on the Lab 2 project.

## Files
- `index.html` – Header, Hero, About, Skills, Projects, Contact, Footer
- `style.css` – all styles (mobile first), commented by section
- `images/profile.svg` – profile picture

## What is used
- **Flexbox:** header, nav, hero (text left, image right), form, footer
- **Grid:** skills and project cards
- **Media queries:** mobile-first, with breakpoints at 600px and 900px
- **Relative units:** rem, %, vw
- **Animations:** fade-in on sections, colour-changing "Full Stack Developer" text
- **Hover effects:** nav links, buttons and cards, smoothed with transitions and transforms

## How to see the responsive behaviour
Open `index.html` in a browser, press F12, turn on the device toolbar, and resize the window.

| Screen | Width | Layout |
|---|---|---|
| Mobile | below 600px | Everything stacked, 1 grid column, hero text above image |
| Tablet | 600px and above | Header in one row, 2 grid columns |
| Desktop | 900px and above | Hero text left and image right, 3 grid columns |

Breakpoints tested: 375px, 768px, 1280px.
