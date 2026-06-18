# Project: heymoko | Android Developer Portfolio

## Overview
A modern, framework-less portfolio website for an Android Developer (heymoko), featuring high-performance design, responsive layouts, and clean aesthetics.

## Project Outline
- **Entry Point:** `index.html`
- **Styling:** Embedded CSS in `index.html` (Baseline CSS features)
- **Frameworks:** None (Vanilla JS, Web Components)
- **Fonts:** 
  - `Bebas Neue`: Headings, Logo
  - `Poppins`: Body text
  - `Noto Sans KR`: Korean text
  - `Playfair Display`: Current nickname font (to be replaced)

## Current Change Plan: Update Nickname Font
### Purpose
Improve the readability of the nickname "moKo" displayed next to "유정모" in the hero section.

### Action Steps
1.  **Locate `.hero-nickname` class** in the `<style>` section of `index.html`.
2.  **Change `font-family`** from `'Playfair Display', serif` to `'Poppins', sans-serif`.
3.  **Remove `font-style: italic`** to provide a cleaner, more stable look.
4.  **Adjust `font-weight`** to `600` for better emphasis.
5.  **Set `text-transform: uppercase`** (optional, but might look good with Poppins) - I'll stick to a clean sans-serif first.
6.  **Verify the change** in the browser preview.
