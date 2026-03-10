# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static personal academic website for GitHub Pages. Portfolio site for research in population genetics, phylogenetics, biogeography, speciation, and evolutionary biology.

## Architecture

- **No build system** — plain HTML/CSS/JS static site, no bundler or framework
- **Root directory** (`/`): Final compiled site files (`index.html`, CSS, JS)
- **`/template/`**: Baseline templates and reference links (terminal.css framework, example portfolio sites)
- **`/CV/`**: CV source content (Apple Pages format — binary, not text-readable)
- **Deployment target**: GitHub Pages (static files served from root)

## Design Specifications

- **Aesthetic**: Minimalist, clean, professional. Content hierarchy and readability are paramount.
- **Color palette**: Neutral base (white/off-white backgrounds, dark text). Primary color accents (red, blue, yellow) for links, buttons, hover states, and section dividers.
- **CSS framework reference**: [terminal.css](https://github.com/Gioni06/terminal.css) — monospace/terminal aesthetic
- **Must be responsive**

## Content Pipeline

The CV in `/CV/2024_CV.pages` is the primary data source. Extract professional background, skills, publications, and research projects from it and map into HTML templates.
