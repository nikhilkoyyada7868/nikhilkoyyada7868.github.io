<div align="center">

# Product Portfolio — GitHub Pages Edition

### A lightweight, dependency-free portfolio for Nikhil Koyyada.

[![Live site](https://img.shields.io/badge/Open-Live_Site-111827?style=for-the-badge)](https://nikhilkoyyada7868.github.io)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)

</div>

## Overview

This repository powers my GitHub Pages portfolio. It presents my product profile, selected work, career experience, resume, and contact details in a fast single-page site with no framework or build step.

## What is included

- Hero introduction and product-management positioning
- About section connecting engineering, operations, and product experience
- Project highlights for VyapaarMitra, the WhatsApp Mood Tracker, and AI experiments
- Experience timeline
- Embedded/downloadable resume
- LinkedIn, GitHub, and email contact paths
- Scroll progress, intersection-based reveal effects, and responsive styling

## Why a no-build version?

The site intentionally uses plain HTML, CSS, and JavaScript. That keeps deployment transparent, load time small, and maintenance simple: GitHub Pages can serve the repository directly.

## Run locally

Clone the repository and serve the directory with any static file server:

```bash
git clone https://github.com/nikhilkoyyada7868/nikhilkoyyada7868.github.io.git
cd nikhilkoyyada7868.github.io
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

```text
index.html                  # Content, sections, and lightweight interactions
style.css                   # Visual system and responsive behavior
Nikhil Koyyada Resume.pdf  # Downloadable resume
*.jpeg                      # Profile imagery
```

## Related portfolio

For the newer React-based experience with deeper project cards and motion, see [ProductManagerPortfolio](https://github.com/nikhilkoyyada7868/ProductManagerPortfolio).
