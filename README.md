# MarkdownTools

A browser-first Markdown utility suite inspired by the public MarkdownTools information architecture and interaction patterns.

## Included

- Responsive tool directory with 34 routes
- Live Markdown editor and viewer
- Markdown rendering with headings, links, images, lists, task lists, tables, code fences, blockquotes, and inline formatting
- Word count, TOC, checklist, frontmatter, callout, collapsible section, image, Mermaid, footnote, list, and linter utilities
- CSV/JSON/table conversions
- Markdown export formats for HTML, plain text, Slack, Confluence, Jira, Notion, and email HTML
- Markdown diff and print-to-PDF workflow

Everything runs in the browser. No server-side upload or account is required.

## Run locally

```bash
python3 -m http.server 4173
```

Open `http://127.0.0.1:4173/`.

## Structure

- `index.html` — app shell and navigation
- `styles.css` — responsive visual system
- `app.js` — SPA routes, tool catalog, Markdown renderer, and tool logic

This implementation is a clean-room reconstruction of publicly observable layout and feature behavior; it does not copy source code or private implementation details from the reference site.
