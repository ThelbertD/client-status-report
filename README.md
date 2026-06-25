# Client Status Reports

A single-file, zero-dependency web app for creating **branded, dated client status reports** — no install, no backend. Just open `index.html` in any browser, or use the live GitHub Pages link.

## Features

- **Multi-client manager** — create clients with their own branding (name, logo, primary/accent colors), then open each to build reports inside.
- **Dated reports** — click **Generate Report** to add a dated entry with four sections:
  - ✅ What We Did
  - 🔄 Pending
  - ⏭️ What's Next
  - 🚧 Blockers
- **Live summary** — per-section totals across all reports; click a stat to drill into every entry and jump to the report it belongs to.
- **Single-report PDF export** — print/export one report at a time with the client's branding (clean light theme for paper).
- **Local-first** — everything saves automatically to your browser (`localStorage`). **Backup/Restore** exports or imports all clients as JSON.
- **Polished dark UI** — animated aurora background, count-up stats, gradient accents, and full `prefers-reduced-motion` support.

## Usage

1. Open `index.html` in a browser (double-click, or use a local server) — or visit the live GitHub Pages site.
2. Fill in the **Client Branding** form and click **Create Client**.
3. Open the client card and click **Generate Report** to add dated reports.
4. Use the 🖨 button on a report to export it as a PDF.

**Live site:** https://thelbertd.github.io/client-status-report/

## Tech

Plain HTML / CSS / vanilla JS in one file. No build step, no dependencies. Data never leaves your browser.
