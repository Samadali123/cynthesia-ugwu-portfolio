# Cynthia Ugwu — Website Clone

A frontend recreation of [Cynthia Ugwu's](https://cynthiaugwu.com) personal portfolio website, built with vanilla HTML, CSS, and JavaScript. The goal was to study and replicate the layout, typography choices, and scroll-driven animation style of a well-designed creative portfolio — no React, no build tools, just clean markup and hand-written animation code.

Deployed on GitHub Pages.

## What's Inside

The site is a single-page layout (`index.html`) with sections covering a hero/intro, character showcase, phone mockup displays, and a footer. All images and custom fonts are included in the repo — no external asset dependencies beyond the animation libraries.

**Typography**
Uses the GeneralSans font family — both Regular and Medium weights are loaded locally from `.otf` files rather than pulling from Google Fonts, which keeps the font rendering consistent and avoids FOUT.

**Animations**
JavaScript handles the scroll-triggered animations and any interactive effects on the page. The animation style follows the original site's feel — subtle, timed reveals as sections come into view rather than anything flashy.

**Responsiveness**
The layout was updated to be responsive across screen sizes — the last commit on the repo specifically addresses responsiveness fixes.


## Project Structure

cynthesia-ugwu-website/
├── index.html              # Full single-page markup
├── style.css               # All layout and animation styles
├── script.js               # Scroll animations and interactions
├── GeneralSans-Regular.otf # Custom font — regular weight
├── GeneralSans-Medium.otf  # Custom font — medium weight
├── character.png           # Character/illustration asset
├── cynthia.png             # Hero image
├── darkphone.png           # Phone mockup — dark
├── whitphone.png           # Phone mockup — white
├── girl image.png          # Section image
├── fav                     # Favicon file
└── favlogo.zip             # Favicon source assets


## Getting Started

No setup needed. Clone and open directly in a browser.

bash
git clone https://github.com/Samadali123/cynthesia-ugwu-website.git
cd cynthesia-ugwu-website
open index.html


Or visit the live deployment on [GitHub Pages](https://samadali123.github.io/cynthesia-ugwu-website).

## What I Learned From This

Recreating someone else's polished site is a different kind of challenge compared to building from scratch. You have a reference to match but no access to the source — so you're making decisions about how to achieve the same visual result with your own approach. The typography pairing, the spacing ratios, and getting scroll animations to feel right (not snappy, not sluggish) are all things you only notice when you're trying to replicate them exactly.

## Tech Stack

HTML · CSS · Vanilla JS · GeneralSans Font Gsap Locomotive scrollTrigger 
