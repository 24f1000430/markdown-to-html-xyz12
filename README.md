# Markdown Viewer with Tabs and Live Word Count

## Overview
This is a lightweight web app that lets you:
- Edit Markdown in a source editor
- Preview the rendered HTML
- See a live-updating word count

It introduces tabs (HTML and Source) within the element with id `#markdown-tabs`, and displays the live word count in `#markdown-word-count`.

## Setup
- No build tools required.
- Open `index.html` directly in a modern web browser.
- Internet access is required to load the following CDNs:
  - marked (Markdown parser)
  - DOMPurify (sanitization)

## Usage
- Type your Markdown in the "Source" tab.
- Click the "HTML" tab to see the rendered result.
- The word count at the top right updates as you type.
- Shortcut: Press Ctrl/Cmd + Enter to toggle between tabs.

## Improvements in Round 2
- Added a tab bar with id `#markdown-tabs` containing two buttons: "HTML" and "Source".
- Implemented panel switching so only one of the two views (rendered HTML or markdown source) is visible at a time.
- Added the live word counter displayed in `#markdown-word-count`, which updates on every keystroke.
- Ensured the preview is rendered and sanitized on input and when switching to the HTML tab.