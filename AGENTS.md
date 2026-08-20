# AGENTS.md

## Project Overview

This repository contains the website for **Edge of Chaos Collective**.

The site is a creative portfolio, publishing hub, and experimental space for several types of work:

- fiction and books
- music
- board games
- interactive game demonstrations
- related visual and multimedia projects

The website is built with **Quarto** and published through **GitHub Pages**.

Repository:

`edge-of-chaos-co/edgeofchaoscollective.github.io`

A custom domain will be connected to the GitHub Pages deployment.

---

## Core Goal

The website should present Edge of Chaos Collective as a coherent creative project rather than as a conventional blog, documentation site, academic website, or generic portfolio template.

The site should feel intentional, distinctive, editorial, and visually driven.

The experience should foreground the creative works themselves.

Do not allow default Quarto or Bootstrap styling to determine the visual identity of the site.

---

# Site Architecture

The primary navigation should contain:

- Home
- Stories
- Music
- Games
- About

The anticipated repository structure is approximately:

```text
/
├── AGENTS.md
├── _quarto.yml
├── index.qmd
├── about.qmd
├── styles.css
│
├── stories/
│   ├── index.qmd
│   └── <story-slug>/
│       ├── index.qmd
│       ├── cover.*
│       ├── *.epub
│       └── *.pdf
│
├── music/
│   ├── index.qmd
│   └── ...
│
├── games/
│   ├── index.qmd
│   └── <game-slug>/
│       ├── index.qmd
│       ├── manual.pdf
│       ├── images/
│       └── demo/
│
├── images/
│
└── docs/
    └── design-brief.md