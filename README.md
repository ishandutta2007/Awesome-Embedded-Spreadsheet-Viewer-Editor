# Awesome-Embedded-Spreadsheet-Viewer-Editor

## Top Embedded Spreadsheet Viewer & Editor Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on In-App Excel-Like Editing, Formula Engines & White-Label Workbook Components*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded Spreadsheet Viewer & Editor**. These tools let you drop a spreadsheet surface directly into your product—covering everything from read-only data grids with Excel-like display to full workbook engines with formula calculation, XLSX import/export, and multi-user collaboration.

**Examples** include SpreadJS, Syncfusion Essential JS 2 Spreadsheet, Handsontable, AG Grid, Jspreadsheet, Luckysheet/Univer, x-spreadsheet, and DHTMLX Spreadsheet (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted spreadsheet components, open-source formula engines, and community-driven grid libraries—ideal for product teams seeking to avoid per-developer licensing that compounds across engineering headcount. The open-source landscape splits into **full spreadsheet engines** (Univer, Luckysheet) with workbook semantics, and **grid libraries with spreadsheet behavior** (Jspreadsheet CE, x-spreadsheet) that cover editing without full Excel parity [citation:1][citation:2].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[SpreadJS (GrapeCity)](https://www.grapecity.com.cn/developer/spreadjs)** | **The most Excel-compatible commercial spreadsheet component.** Canvas rendering with sparse arrays for millions of cells, **90%+ Excel function compatibility**, 513 calculation formulas, and high-fidelity import/export. Plugin ecosystem covers reporting, pivot tables (500K rows in 600ms), Gantt, and AI. Production-proven by UFIDA, Kingdee, and JD Logistics [citation:1]. | Developer license: **¥9,800** (individual); **¥29,400** (4-developer team). Deployment: **¥22,000 per domain/IP**; optional plugins ¥13,800–59,600 [citation:9]. | No free tier; trial via sales |
| **[Syncfusion Essential JS 2 Spreadsheet](https://www.syncfusion.com/)** | Full spreadsheet component within a 140+ component suite. Supports formulas, multiple sheets, charts, conditional formatting, and Excel import/export. **Community License is free** for companies under $1M revenue, ≤5 developers, ≤10 employees, and ≤$3M raised [citation:10]. | Suite: **$1,199/developer/year** (5-developer minimum = $5,995/year); Grid alone: $959 [citation:10]. | **Free (Community License)**: qualifying small companies; otherwise paid per-developer |
| **[Handsontable](https://handsontable.com/)** | **Excel-style editing component focused on familiar spreadsheet interaction.** Strong keyboard navigation, copy/paste workflows, cell validation, and formulas via HyperFormula. Best for CRUD screens, data-entry workflows, and pricing matrices rather than full workbook applications [citation:2][citation:15]. | Standard: **$999/developer**; Priority: $1,299; Enterprise: custom. **Free hobby license** for non-commercial projects [citation:12]. | **45-day full-feature trial** (no credit card); free hobby license for personal use |
| **[AG Grid](https://www.ag-grid.com/)** | **High-performance data grid with spreadsheet-like features in Enterprise tier.** Range selection, fill handle, clipboard, formulas, pivoting, server-side row model, and Excel export. **Primarily a data grid, not a full spreadsheet engine**—choose when large row counts and complex grid operations matter more than workbook parity [citation:2][citation:15]. | Community: **Free** (MIT); Enterprise: **$999/developer**; Enterprise Bundle with Charts: $1,498 . | **Free (Community)**: core grid features; **30-day Enterprise trial** |
| **[Jspreadsheet (Pro)](https://jspreadsheet.com/)** | Lightweight JavaScript spreadsheet with classic web spreadsheet UI. Community Edition is open-source; Pro adds advanced features and extensions. Supports worksheets, formulas, clipboard, fill handle, validations, and import/export [citation:15]. | Quote-only (Pro/extension pricing) | **Free (Community Edition)** available |
| **[DHTMLX Spreadsheet](https://dhtmlx.com/)** | Spreadsheet component within the DHTMLX UI suite. **No additional deployment fees** for end-user applications; SaaS license is fixed-price for life. One-time purchase with optional support renewal [citation:13]. | Company: **$2,499** (project-based); DevTeam: $3,999; Unlim: $9,499 . | **30-day PRO trial**; startup program offers 70% discount |
| **[Webix Spreadsheet](https://webix.com/)** | Spreadsheet widget within the Webix JS UI library. Pack pricing includes PRO library, one year of updates, and support. Complex widgets include source code . | Company: **$2,499**; DevTeam: $3,999; Unlim: $9,499 . | No free tier for PRO; trial via Webix |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Univer](https://github.com/dream-num/univer)** | [![Stars](https://img.shields.io/github/stars/dream-num/univer?style=social&color=white)](https://github.com/dream-num/univer/stargazers) | **The successor to Luckysheet and the most ambitious open-source spreadsheet framework.** Apache-2.0, TypeScript, **10,633 stars**. Full-stack framework for creating and editing spreadsheets on both web and server. **AI-native** with Univer MCP for natural-language spreadsheet control. Supports collaboration, XLSX import/export, and a plugin architecture. **Luckysheet 3.x was renamed to Univer**—existing Luckysheet users should migrate [citation:4][citation:6]. **Best for teams wanting a modern, actively developed open-source spreadsheet engine with AI capabilities.** |
| **[Jspreadsheet CE](https://github.com/jspreadsheet/ce)** | [![Stars](https://img.shields.io/github/stars/jspreadsheet/ce?style=social&color=white)](https://github.com/jspreadsheet/ce/stargazers) | **Lightweight open-source JavaScript spreadsheet with 7,130 stars.** Community Edition of Jspreadsheet. Creates interactive data grids with spreadsheet controls—formulas, clipboard, fill handle, validations, and filters. **Best for simple embedded spreadsheet needs** where a full workbook engine isn't required. Pro version adds advanced features [citation:5][citation:15]. |
| **[x-spreadsheet](https://github.com/myliang/x-spreadsheet)** | [![Stars](https://img.shields.io/github/stars/myliang/x-spreadsheet?style=social&color=white)](https://github.com/myliang/x-spreadsheet/stargazers) | **Web-based JavaScript spreadsheet with 15k stars.** Lightweight and simple to embed. **Project has been migrated to `@wolf-table/table`**—the original repo is no longer the active development target. **Best for legacy projects already using it**, but new projects should evaluate Univer or the wolf-table successor [citation:7]. |
| **[Spindle](https://github.com/b32n/spindle)** | [![Stars](https://img.shields.io/github/stars/b32n/spindle?style=social&color=white)](https://github.com/b32n/spindle/stargazers) | **Forever-free open-source spreadsheet, docs, and slides libraries for React.** Optimized for performance and bundle size. Spreadsheet features: virtual scrolling, **146 formula functions with dynamic arrays**, formula autocomplete, sparse data storage, and **CSV/XLSX import/export**. Real-time collaboration via Yjs CRDT with live cursors and offline persistence. **Best for React teams wanting a modern, forever-free alternative to commercial suites** [citation:3]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Luckysheet](https://github.com/mengshukeji/Luckysheet)** | — | **Legacy open-source spreadsheet now superseded by Univer.** Online spreadsheet with Excel-like features, plugins (Luckyexcel for import, chartMix for charts), and multiple framework wrappers (Vue, React). **No longer the primary development target**—use Univer for new projects [citation:4]. |

**Frameworks for building custom systems**: Choose **SpreadJS** for the highest Excel compatibility and proven enterprise deployment [citation:1], **Syncfusion** for a broad UI suite with a generous free tier for small companies [citation:10], **Handsontable** for fast Excel-like editing in CRUD workflows [citation:2], and **Univer** for a modern, AI-native open-source engine with active development [citation:6] —evaluating licensing (per-developer vs. per-domain vs. free) against your actual deployment model.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Embedded spreadsheet components process potentially sensitive data and execute formulas in the browser; enforce proper input validation and consider sandboxing for untrusted content.
- **Licensing models vary dramatically and can surprise teams at deployment.** **SpreadJS requires both developer licenses AND deployment licenses**—a single domain costs **¥22,000 on top of developer seats**, and SaaS deployment is quoted separately [citation:9]. **Syncfusion's Community License is genuinely free** for companies under $1M revenue with ≤5 developers, but the full suite costs **$5,995/year minimum** for paying teams [citation:10]. **Handsontable is per-developer** ($999) with a free hobby license for non-commercial use [citation:12]. **Open-source options have different trade-offs**: Univer is Apache-2.0 and actively developed [citation:6], Jspreadsheet CE is lightweight but less feature-complete [citation:5], and x-spreadsheet has been migrated to a successor project [citation:7]. **Validate deployment licensing terms** (per-domain, per-SaaS-platform, or per-developer) against your actual product architecture before committing.

---

**Made for product engineers, frontend teams, and developers building in-app spreadsheet capabilities.**  
Let's make embedded spreadsheet components more open, predictable, and product-friendly.
