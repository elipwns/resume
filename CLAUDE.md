# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a single-page HTML resume hosted on GitHub Pages at https://elipwns.github.io/resume/. The entire resume is `index.html` — one self-contained file with inline CSS and no build step.

## Structure

- `index.html` — the resume, with all styles inline in `<style>` tags
- `_config.yml` — GitHub Pages config (Jekyll theme, not actively used since index.html overrides it)
- `notes.md` — scratch notes about resume content accuracy

## Deployment

Push to `main` — GitHub Pages auto-deploys. No build process needed.

## Print/PDF

The "Download PDF" button triggers `window.print()`. Print styles are defined in the `@media print` block in `index.html`.
