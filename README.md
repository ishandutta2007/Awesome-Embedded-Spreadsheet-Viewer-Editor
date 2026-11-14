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
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global spreadsheet software and developer UI component ecosystem represents an estimated **$11.5B to $14B+** market, supported by a rapid 14–16% CAGR across developer construction tools and data grid SDKs. The sector exhibits **moderate fragmentation with specialized concentration**: while dominant office productivity suites (Microsoft Excel, Google Sheets) command the general end-user sphere, the embedded/in-app developer component space is contested between specialized high-scale UI component giants (Syncfusion, MESCIUS/GrapeCity), dedicated performance grid leaders (AG Grid, Handsontable), and an expanding cohort of modern open-source engines (Univer, Jspreadsheet).

## SaaS/Hosted Platforms

| Product | Company Scale (Revenue / Valuation) | Pricing (Starting) | Free Tier / Trial Limits | Description |
|---------|-------------------------------------|-------------------|--------------------------|-------------|
| **[Syncfusion Essential JS 2 Spreadsheet](https://www.syncfusion.com/)** | **~$176M – $200M+** ARR; 2,000+ employees (Bootstrapped / Private) | **$1,199/developer/year** (5-developer team minimum: $5,995/year); or **$959/developer/year** (Grid-only package) | **Free (Community License)**: Full commercial access for companies with <$1M annual gross revenue, ≤5 developers, and ≤10 employees; otherwise standard 30-day evaluation trial | Full spreadsheet component within a 140+ component suite. Supports formulas, multiple sheets, charts, conditional formatting, and Excel import/export. [citation:10] |
| **[SpreadJS (MESCIUS / GrapeCity)](https://www.grapecity.com.cn/developer/spreadjs)** | **~$50M – $100M+** estimated global revenue; 400+ employees (Private equity backed by iSigma Capital) | **$1,999/developer/year** (includes 1 Developer license + 1 annual Hostname deployment + Designer App; China direct: **¥9,800/dev**) | **30-day full-featured free trial**; permanent free tier not available for commercial production | **The most Excel-compatible commercial spreadsheet component.** Canvas rendering with sparse arrays for millions of cells, **90%+ Excel function compatibility**, 513 calculation formulas, and high-fidelity import/export. Plugin ecosystem covers reporting, pivot tables (500K rows in 600ms), Gantt, and AI. Production-proven by UFIDA, Kingdee, and JD Logistics [citation:1]. |
| **[AG Grid](https://www.ag-grid.com/)** | **~£25M (~$32M) EBITDA** / **£10M–£50M ARR**; Enterprise buyout backed by Adelis Equity Partners | **$999/developer** (Enterprise perpetual license with 1 year support); Enterprise Bundle with Integrated Charts: **$1,498/developer** | **Free forever (Community Edition)**: MIT-licensed core grid; Enterprise features include **30-day evaluation trial** (unrestricted features, evaluation purposes only) | **High-performance data grid with spreadsheet-like features in Enterprise tier.** Range selection, fill handle, clipboard, formulas, pivoting, server-side row model, and Excel export. **Primarily a data grid, not a full spreadsheet engine**—choose when large row counts and complex grid operations matter more than workbook parity [citation:2][citation:15]. |
| **[Webix Spreadsheet](https://webix.com/)** | **~$15.1M** ARR; ~130–150 employees (XB Software / Private) | **$2,499** one-time purchase (Company Pack for 1 project, 1 dev); DevTeam Pack: **$3,999**; Unlimited Pack: **$9,499** | **30-day full-featured Pro trial** (technical support included); Webix Standard (GPLv3) is free for open-source projects only and excludes complex widgets like Spreadsheet | Spreadsheet widget within the Webix JS UI library. Pack pricing includes PRO library, one year of updates, and support. Complex widgets include source code. |
| **[DHTMLX Spreadsheet](https://dhtmlx.com/)** | **~$1M – $5M** estimated ARR; 10–50 employees (Dinamenta, UAB / Private) | **$2,499** one-time purchase (Company license for 1 project, 1 dev); DevTeam: **$3,999** (up to 5 devs); Unlimited: **$9,499** | **30-day full-featured Pro trial** (`@dhx/trial-spreadsheet` evaluation only); Community Edition is free forever under GPLv2 for open-source apps only | Spreadsheet component within the DHTMLX UI suite. **No additional deployment fees** for end-user applications; SaaS license is fixed-price for life. One-time purchase with optional support renewal [citation:13]. |
| **[Handsontable](https://handsontable.com/)** | **~$1M – $3M** ARR; ~15–20 employees (Handsoncode / Bootstrapped) | **$999/developer/year** (Standard plan); Priority: **$1,299/developer/year**; Enterprise custom | **45-day full-feature trial** (no credit card required); **Free forever Hobby License** for non-commercial and open-source use | **Excel-style editing component focused on familiar spreadsheet interaction.** Strong keyboard navigation, copy/paste workflows, cell validation, and formulas via HyperFormula. Best for CRUD screens, data-entry workflows, and pricing matrices rather than full workbook applications [citation:2][citation:15]. |
| **[Jspreadsheet (Pro)](https://jspreadsheet.com/)** | **<$1M** estimated ARR; niche developer team (Boutique / Self-funded) | **$49/month** (Standard plan per feature) or **$199/month** (Enterprise plan with Formula Pro & XLSX import/export) | **Free forever (Community Edition)**: MIT-licensed base grid; Pro includes **30-day evaluation trial** (and unlimited evaluation on `localhost`) | Lightweight JavaScript spreadsheet with classic web spreadsheet UI. Community Edition is open-source; Pro adds advanced features and extensions. Supports worksheets, formulas, clipboard, fill handle, validations, and import/export [citation:15]. |

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
