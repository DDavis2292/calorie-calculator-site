# Husky Boy Health — Calorie Tracker

## Project Overview
A mobile-first calorie tracking web app built for Web Dev 2 at KVCC (Winter 2026). Vanilla HTML, CSS, and JavaScript — no frameworks.

## Pages
- `index.html` — Dashboard
- `calculator.html` — Calorie Calculator (form to calculate daily calories & macros)
- `food-log.html` — Food Log (progress ring, meal sections, food search)
- `activity-log.html` — Activity Log
- `recipes.html` — Recipes
- `about.html` — About

## Tech Stack
- Vanilla HTML / CSS / JS
- Google Fonts: Roboto, Rubik Bubbles
- JS entry point: `./js/main.js`

## Color Palette (CSS variables in `:root`)
- `--cream-accent` / `--cream-nav-accent`: `#fee3c9`
- `--blue-accent` / `--blue-nav-accent`: `#1F2937`
- `--orange-accent` / `--orange-nav-accent`: `#b24225`
- `--card-black`: `#2d2d2d`
- `--input-black`: `#1e1e1e`

## Layout
- Fixed top header (`position: fixed`, `z-index: 100`) with hamburger menu that slides in from the right
- Fixed bottom mobile nav (`position: fixed`, `bottom: 0`, `height: 70px`)
- `body` is `display: flex; flex-direction: column; min-height: 100vh`
- `main` uses `flex: 1` to fill remaining space, `padding: 100px 25px 80px 25px`

## CSS Conventions
- Form cards use `.form-card` with `display: flex; flex-direction: column; gap: 15px`
- Form groups use `.form-group` with `display: flex; flex-direction: column`
- Use `.form-group > label` (child combinator) to avoid affecting nested labels like radio buttons
- Radio buttons use `.radio-group` > `.radio-option` wrappers for layout control

## How the User Likes to Work
- Walk them through things and explain concepts so they can do it themselves
- Don't make code changes without being asked — explain first, let them do it
- Keep explanations clear and direct — they are a student learning as they go
