# Project rules

This is a one-page static site: a personal reference for AI tools and the projects built with them.

## Structure
- Everything lives in `index.html` (HTML, CSS and JavaScript). No build step, no frameworks, no external scripts. Google Fonts is the only external resource.
- All content lives in the block marked `EDIT HERE`: `window.SITE`, `window.DEV`, `window.TOOLS` and `window.PROJECTS`. To add a tool or a project, copy an existing entry and change the text. Don’t touch the rendering code for content changes.
- The page has four sections, in this order: Toolkit, Projects, About this site, About the developer.

## Content rules
- Language: English. Use ’ (not ') for apostrophes inside text, so the JavaScript strings stay valid.
- A tool’s `status` is `in-use` or `exploring`. Its `source` is `mati`, `course` or `self`.
- Use only what the owner provided. Don’t invent tips, experience or results, and don’t mark a tool `in-use` unless she says she used it.

## Design rules
- Palette: #DE7272, #FFCA88, #FFF6A9, #B4E4D6, with ink #2b1f2e for text.
- Fonts: Bricolage Grotesque for headings, Instrument Sans for body text.
- Keep it responsive down to phone width, with visible keyboard focus.

## Privacy
- This repository is public. Never add customer names, employee names, phone numbers, API keys, or any real data from the factory project. Describe the factory generically.

## After every change
- Open `index.html` in the browser, check the console for errors, and check the page at phone width.
- Never remove existing content unless asked.
