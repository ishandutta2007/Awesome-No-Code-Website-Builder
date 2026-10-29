# Awesome-No-Code-Website-Builder

# Top No-Code Website Builder Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Visual Page Editing, Drag-and-Drop Design & Self-Hosted Site Builders*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **No-Code Website Builders**. These tools enable designers, marketers, and founders to create professional websites through visual interfaces—dragging blocks, styling elements, and publishing without writing code.

**Examples** include Shopify Online Store Editor, Webflow, Squarespace, Wix, Framer, WordPress Gutenberg, Elementor, PageFly, Shogun, and GemPages (the category leaders).

**Open-source emphasis**: No-Code Website Builder is a domain where open-source tooling is **surprisingly mature for static site generation and visual editing**. **Silex** is the strongest active project—a non-profit-backed Webflow alternative with GrapesJS-based editing, clean HTML/CSS export, and self-hosting via Docker or Node.js . **OpenPage** offers a JSON-first visual builder with AI generation and MIT licensing, explicitly designed as a self-hosted Framer/Lovable alternative . **Webstudio** provides an advanced visual development platform with AGPL licensing and headless CMS connectivity . **Instatic** delivers a full CMS with visual editing and static output, built by the team behind Motion.page . For WordPress, **Marfilo** and **PixeBuilder** offer lightweight GPL-licensed page builders . The gap remains in enterprise-grade ecommerce integration (Shopify-specific builders) and AI-native generation at the polish level of Framer.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Shopify Online Store Editor](https://www.shopify.com/)**  
  Shopify's native theme editor for customizing storefronts with sections, blocks, and theme settings; limited to Shopify-hosted stores but deeply integrated with commerce features.

- **[Webflow](https://webflow.com/)**  
  Visual development platform with a designer that generates clean HTML/CSS/JS; supports CMS, ecommerce, and hosting; the industry benchmark for design fidelity in a no-code builder.

- **[Squarespace](https://www.squarespace.com/)**  
  All-in-one website builder with polished templates and drag-and-drop editing; strong for portfolios, blogs, and small business sites.

- **[Wix](https://www.wix.com/)**  
  Popular website builder with Wix Editor and Wix Studio for agencies; extensive template library and app market.

- **[Framer](https://www.framer.com/)**  
  Design-first website builder with AI-powered generation, responsive breakpoints, and CMS; popular for marketing sites and portfolios.

- **[WordPress Gutenberg](https://wordpress.org/gutenberg/)**  
  WordPress's native block editor for content creation; extensible via block plugins and full-site editing in modern themes.

- **[Elementor](https://elementor.com/)**  
  Leading WordPress page builder with drag-and-drop editing, template library, and theme builder; free version plus Pro tiers.

- **[PageFly](https://pagefly.io/)**  
  Shopify page builder app for creating landing pages, product pages, and blog layouts with drag-and-drop editing.

- **[Shogun](https://getshogun.com/)**  
  Page builder for ecommerce (Shopify, BigCommerce) with visual editing and A/B testing; now part of Yotpo.

- **[GemPages](https://gempages.net/)**  
  Shopify page builder with conversion-focused templates, drag-and-drop editor, and AI-assisted design.

## Open-Source GitHub Projects

### Visual Site Builders (Self-Hosted)

- **[Silex](https://github.com/silexlabs/Silex)**  
  The most established open-source **Webflow alternative** (AGPL-3.0, ~1,844 GitHub stars, active since 2009); GrapesJS-based drag-and-drop editor with HTML/CSS/JS editors, static HTML export, CMS integration via GraphQL (WordPress, Strapi, Squidex), 11ty compatibility, and self-hosting via Docker or Node.js . **Non-profit backed** by Silex Labs—no subscriptions, no tracking, no premium tier; all features included . Desktop app (alpha) adds offline editing with built-in MCP server for AI-assisted design .

- **[OpenPage](https://github.com/buildingopen/openpage)**  
  Open-source website builder with visual drag-and-drop editor, AI site generation (Gemini API), and **JSON-first architecture** (MIT) . Ships with 19 block types and 42 layout variants, 10 theme presets, and standalone HTML export. **Explicitly positioned as a self-hosted alternative to Framer, Lovable, and v0**, with clean Git diffs for version control and a structured API for agent-editable sites . React 19 + TypeScript + Tailwind stack; deploy to Vercel or self-host.

- **[Webstudio](https://github.com/webstudio-is/webstudio)**  
  Open-source visual development platform positioned as a **Webflow alternative** (AGPL-3.0 for core); connects to any headless CMS, supports all CSS properties, and can be hosted anywhere . Core is fully open-source; optional animation SDK package is proprietary under a separate EULA .

- **[Instatic](https://github.com/CoreBunch/Instatic)**  
  Open-source **agentic self-hosted visual CMS** positioned as an alternative to Webflow, Framer, and WordPress . Features visual editing, static page generation (baked to disk on publish), a plugin system with QuickJS-WASM sandboxing, audit logs, and form data ownership. Built by the team behind Motion.page and Core Framework; requires Bun and SQLite (default) or Postgres .

### WordPress Page Builders

- **[Marfilo](https://alternativeto.net/software/marfilo/about/)**  
  Free visual drag-and-drop page builder for WordPress (GPL-2.0); publishes **plain HTML and a single stylesheet**, with 95 modules and no Pro tier . Lightweight and WYSIWYG-focused.

- **[PixeBuilder](https://wp-packages.org/packages/wp-plugin/pixebuilder)**  
  Free drag-and-drop page builder plugin for WordPress (v1.1.2); click-to-edit in place or side panel; clean pages that load only what they use .

### Niche & Emerging

- **[Nitropage](https://www.npmjs.com/package/create-nitropage)**  
  Free, open-source, self-hostable alternative to Squarespace and Wix; building blocks written in SolidJS with HMR support . Early-stage (v0.67.2).

- **[Autonnel](https://buildhop.io/discover/autonnel)**  
  Open-source AI-native funnel builder for ecommerce (Apache-2.0); generates landing, checkout, and upsell pages from prompts; connects to Shopify, WooCommerce, or Picocart . **Very early-stage** (published October 2026).

### Additional Strong Open-Source Options

- **Andami** — MIT-licensed visual page builder framework for Next.js with Sanity CMS backend; optimized for portfolio/brand sites; single-maintainer studio tool (not enterprise-supported) .
- **Easyblocks** — Open-source page builder framework with visual editor and backend flexibility; requires integration work rather than drop-in deployment .
- **No open-source Shopify page builder exists** — The Shopify App Store's page builder category (PageFly, Shogun, GemPages) is entirely commercial; no open-source equivalent replicates their deep Shopify integration.

**Frameworks for building custom systems**: For **general-purpose site building**, Silex provides the most mature, non-profit-backed foundation with static export and CMS integration . For **AI-assisted generation**, OpenPage offers JSON-first architecture with Gemini integration . For **WordPress**, Marfilo or PixeBuilder provide lightweight GPL alternatives . For **Next.js developers**, Andami or Instatic provide code-first foundations . No open-source builder matches Webflow's design fidelity or Shopify's ecommerce integration out of the box.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- No-code website builders handling user content and published sites must consider security (XSS prevention in visual editors, plugin sandboxing), accessibility (WCAG compliance for generated output), and hosting reliability.
- **Open-source no-code builders are mature for static sites and WordPress**—Silex and OpenPage provide production-ready visual editing with clean export, and Marfilo/PixeBuilder serve WordPress users. However, **Shopify-specific page builders are entirely commercial**, and no open-source project matches Framer's AI generation polish or Webflow's design fidelity. Organizations requiring ecommerce-optimized builders should evaluate commercial apps.
- Verify license terms for commercial use; Silex uses AGPL-3.0 , OpenPage uses MIT , Webstudio core uses AGPL-3.0 with proprietary animation SDK , and Marfilo/PixeBuilder use GPL .

---

**Made for web designers, marketers, founders, and self-hosting enthusiasts.**  
Let's make no-code website building more open, but with clear eyes about the ecommerce integration gap that remains.
