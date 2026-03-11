# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub profile README repository (`kamau-mbugua/kamau-mbugua`). The sole purpose is to render a styled profile page on the GitHub user profile at github.com/kamau-mbugua.

## Repository Structure

The entire repository consists of a single `README.md` file written in HTML-flavored GitHub Markdown. There is no application code, build system, test suite, or dependencies.

## Key Details

- The README uses HTML (`<p>`, `<h1>`, `<h3>`, `<a>`, `<img>`, `<table>`) for layout and alignment — not pure Markdown
- Dynamic images are pulled from external services: github-readme-stats, github-readme-streak-stats, github-profile-trophy, shields.io badges, komarev profile counter, and wakatime
- All badge/stat URLs reference the username `kamau-mbugua` — keep this consistent when editing
- The profile highlights: GDE (Cloud, AI, Infrastructure), Riverbank Solutions Ltd, fintech/payments expertise, and mobile development (Kotlin, Java, Dart/Flutter)
- The README includes sections: About, Experience table, Connect links, Languages & Tools (categorized), Notable Projects (grid), GitHub Stats, Achievements, GDE Highlights, Education

## Editing Guidelines

- Preview changes on GitHub directly, as the HTML-centered layout won't render correctly in standard Markdown previewers
- Maintain the existing section order and `<p align="center">` formatting pattern
- When adding new technology badges, follow the existing shields.io format: `https://img.shields.io/badge/{LABEL}-{COLOR}?style=for-the-badge&logo={LOGO}&logoColor=white`
