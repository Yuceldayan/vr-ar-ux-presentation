# The Evolution of VR/AR Headsets and Their User Experience

A single-page interactive presentation tracing how virtual and augmented reality
headsets developed between 1968 and 2024, and the user-experience problems these
devices still have not solved.

**Live:** https://yuceldayan.github.io/vr-ar-ux-presentation/

---

## Contents

**Timeline** — Starts with Sutherland's 1968 head-mounted display and moves
through 1995, 2012, 2016, 2018, 2019, 2020, 2022, 2023 and 2024, each era with
its own imagery.

**UX problems** — The issues headsets have yet to overcome, taken one at a time:
ergonomics and weight, balance disturbance, physical discomfort, cluttered
interfaces, lens and vision limitations, audio, language support, connection
drops, privacy and cost.

## How it was built

One `index.html` (88 KB) and a hand-written `styles.css` (16 KB). No framework:
the layout, transitions and responsive behaviour are all plain CSS. More than
thirty images are served as `webp`, `avif`, `png` and `jpg`, chosen per image to
keep the page light.

```
.
├── index.html      the whole presentation
├── styles.css      layout, typography, transitions
└── images/         30+ assets (webp / avif / png / jpg)
```

## Running

No build step. Open `index.html` in a browser, or visit the live link above.

## My role

**Sole developer.** The research, the writing, the image selection, and the
design and coding of the site are all mine.

## License

MIT
