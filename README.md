<div align="center">

# 🌐 MeshBase 

### The AI content infrastructure for modern teams

**Describe it in plain English. Ship a production website.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-meshbaseny.github.io-6d5efc?style=for-the-badge)](https://meshbaseny.github.io/meshbase-platform/)
[![Website](https://img.shields.io/badge/Product-meshbase.io-17c7e6?style=for-the-badge)](https://meshbase.io)
[![Built with](https://img.shields.io/badge/Built_with-HTML_%2B_CSS_%2B_JS-22d3a5?style=for-the-badge)](#-tech-stack)
[![Deploy](https://img.shields.io/badge/Hosted_on-GitHub_Pages-171515?style=for-the-badge&logo=github)](https://pages.github.com/)

**🔗 Live page → [meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/)**
**🚀 Product → [meshbase.io](https://meshbase.io)**

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Live Links](#-live-links)
- [What Is MeshBase?](#-what-is-meshbase)
- [Feature Highlights](#-feature-highlights)
- [Why This Landing Page Exists](#-why-this-landing-page-exists)
- [Page Anatomy](#-page-anatomy)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started Locally](#-getting-started-locally)
- [Deploying to GitHub Pages](#-deploying-to-github-pages)
- [Using a Custom Domain](#-using-a-custom-domain)
- [Customization Guide](#-customization-guide)
- [Design System](#-design-system)
- [Performance & Accessibility](#-performance--accessibility)
- [SEO & Social Sharing](#-seo--social-sharing)
- [Browser Support](#-browser-support)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [FAQ](#-faq)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 🎯 Overview

This repository contains the source for the **MeshBase marketing landing page** — a single, self-contained HTML document that presents MeshBase, the AI content infrastructure platform, to the world. It is designed to be beautiful, elegant, modern, and fast, and it is engineered to deploy on GitHub Pages with zero build tooling.

The page is live right now at **[https://meshbaseny.github.io/meshbase-platform/](https://meshbaseny.github.io/meshbase-platform/)**, and the product it describes lives at **[https://meshbase.io](https://meshbase.io)**. If you want the short version of what you are looking at: it is one `index.html` file, no framework, no bundler, no dependencies to install, and it renders a full marketing site with a hero, a live prompt demo, nine feature cards, deep-dive product sections, a comparison table, an FAQ accordion, and a call-to-action band. Open it in a browser and it just works.

The rest of this document explains what MeshBase is, how the landing page is built, how to run it locally, how to deploy it, and how to make it your own. It is intentionally thorough so that a future maintainer — or you, six months from now — can pick this repository up and understand every decision without having to reverse-engineer the CSS.

---

## 🔗 Live Links

| Resource | URL | Description |
|---|---|---|
| **Live landing page** | [meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/) | The deployed GitHub Pages build of this repository. |
| **MeshBase product** | [meshbase.io](https://meshbase.io) | The MeshBase platform itself — sign up and start building. |
| **Start building free** | [meshbase.io](https://meshbase.io) | Free to start, no credit card required, live site in under two minutes. |

Bookmark the two that matter: the demo at **[meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/)** shows the page in action, and **[meshbase.io](https://meshbase.io)** is where the actual product lives. Every "Start free" button on the landing page is meant to point at [meshbase.io](https://meshbase.io).

---

## 🧠 What Is MeshBase?

MeshBase is an AI-powered platform that turns a plain-English description of what you want into a real, production-ready web application. You describe your project — a portfolio, a company blog, a landing page for a launch, an online store — and the system scaffolds genuine **Next.js** code, complete with server components, routing, styling, a headless CMS, APIs, and team collaboration tools. No dragging boxes around a canvas, no writing boilerplate configuration, no assembling half a dozen separate SaaS subscriptions by hand.

The tagline says it plainly: **"The AI content infrastructure for modern teams."** MeshBase positions itself as a unified solution that replaces roughly six separate tools — a site builder, a headless CMS, a media host with a CDN, a team task board, an access-control layer, and an API gateway — with a single platform where everything shares one data model, one permission system, and one bill. The three words it leads with are **SSR**, **SEO-ready**, and **infinite scale**.

What makes this more than a novelty is that the output is not a throwaway prototype. Because MeshBase generates a server-rendered Next.js foundation, the sites it produces are production artifacts an engineering team would be happy to inherit. They render on the server for a fast time-to-first-byte, they emit clean meta tags and structured data so search engines can index them properly, and they routinely land Lighthouse scores around 98. The AI does the heavy lifting of assembly; you keep the quality and the control. You can learn much more, and try it yourself, at **[meshbase.io](https://meshbase.io)**.

### Who it is for

MeshBase is built for creators, designers, and teams who want production-quality results without living in a terminal. Independent creators use it to launch portfolios, blogs, and storefronts that look hand-built and rank well, without hiring a developer. Design and content teams use it to give writers a genuinely pleasant editor, give designers control over the output, and give everyone a shared board and clear roles. Developers and startups use it to get a real Next.js codebase and structured, API-first content from day one — ship the marketing site in minutes, then point a mobile app or storefront at the same content store, and scale without re-platforming later.

---

## ✨ Feature Highlights

The landing page in this repository describes the full MeshBase platform. These are the capabilities it presents, each rendered as a card with its own gradient icon and feature tags:

- **AI Builder Agent** — Describe your project in plain language and the agent scaffolds real Next.js code — server components, routing, and styling included — then keeps refining in conversation until it deploys exactly the way you pictured it.
- **Server-rendered architecture** — A Next.js foundation delivers proper meta tags, structured data, and a fast time-to-first-byte out of the box, with pages that are fully indexable and Lighthouse scores around 98.
- **Headless CMS** — Default and fully custom content types with dynamic fields (repeaters, references, relations), a block-based rich editor with slash-menu commands for video, images, and tables, plus multi-cursor collaboration and draft history.
- **Team Kanban** — A built-in board with TODO, DOING, and DONE columns, priority tagging, and work-in-progress tracking, all living right beside the content it refers to.
- **Media Library** — CDN-hosted assets with automatic optimization, global delivery, on-the-fly responsive transformations, and signed access for sensitive files.
- **Role-based access control** — Editor, Contributor, and Viewer roles with sensible permission guardrails, so you can hand out access generously without worrying about who can break the homepage.
- **Project APIs** — Clean REST and GraphQL endpoints for reading and mutating content, plus typed SDKs across six programming languages so engineers get autocomplete and compile-time safety.
- **Ship & scale** — Go from prompt to a live, publicly reachable site in under two minutes, on an architecture built to serve your millionth visitor as easily as your first.
- **Content that travels** — Structured, API-first content that is never trapped inside one page — reuse the same entries across web, app, email, and social from a single source of truth.

Every one of these is explained in more depth on the page itself, and in full detail at **[meshbase.io](https://meshbase.io)**.

---

## 🤔 Why This Landing Page Exists

A product is only as strong as the first thirty seconds a visitor spends with it. The goal of this page is to communicate, quickly and beautifully, what MeshBase does and why it is different — and then to get the visitor to **[meshbase.io](https://meshbase.io)** to try it.

The page is written to make one argument clearly: any single feature MeshBase offers can be matched by some existing tool, but almost nobody matches the whole set read together. When your builder, CMS, media host, task board, permissions, and API all descend from one platform, the failure modes of integration simply stop existing. There is no webhook that silently stops firing at 2 a.m., no content that is "published" in one system and invisible in another, no per-seat charge on a tool half the team stopped using. That coherence is the product, and the page is structured to lead a reader to that realization.

It is deployed as a static site because a marketing page should be fast, cheap, and impossible to break. GitHub Pages serves it for free from this repository, the live result is at **[meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/)**, and there is no server to patch, no database to back up, and no build pipeline to babysit.

---

## 🧩 Page Anatomy

The single `index.html` is organized top-to-bottom into clearly commented sections. Knowing the order helps when you want to edit or reorder them:

1. **Sticky navigation** — A glass-morphism header with the MeshBase wordmark, section anchors, a "Sign in" ghost button, and a gradient "Start free" call to action. It gains a subtle shadow once you scroll.
2. **Hero** — The headline "Describe it in plain English. Ship a production website.", a supporting paragraph, two call-to-action buttons, and a trust line ("No credit card required · Live site in under 2 minutes · Free to start").
3. **Prompt demo card** — A browser-chrome mock showing a plain-English prompt turning into a grid of generated outputs (Next.js pages, Headless CMS, REST + GraphQL, media, SEO metadata, deploy).
4. **Stats row** — Four headline numbers: ~98 Lighthouse, 6→1 tools replaced, under 2 minutes to live, six typed SDK languages.
5. **Platform intro** — Prose explaining how MeshBase unifies a stack most teams assemble by hand.
6. **"Replace the stack"** — A visual list of the six subscriptions MeshBase consolidates into one.
7. **Feature grid** — Nine cards covering every capability listed above, each with a colorful gradient icon.
8. **How it works** — Four numbered steps from "Describe your idea" to "Publish & connect", plus explanatory prose.
9. **Deep dives** — Three alternating feature/visual rows: the CMS editor (with live multi-cursor tags), the Kanban workflow board, and the API layer (with a syntax-highlighted code sample).
10. **Pull quote** — A short, punchy testimonial-style line.
11. **Templates** — Five quick-start template cards: Portfolio, Blog, Business Website, Landing Page, Online Store.
12. **Comparison table** — MeshBase versus a site-builder-plus-plugins approach versus a hand-rolled stack.
13. **Who it's for** — Three audience cards: independent creators, design and content teams, developers and startups.
14. **Philosophy** — A longer-form section arguing why MeshBase is "content infrastructure," not "another builder."
15. **FAQ** — Seven expandable questions covering coding requirements, output, SEO, APIs, collaboration, speed, and cost.
16. **Call-to-action band** — A bold gradient panel with the final "Start building free" prompt pointing to [meshbase.io](https://meshbase.io).
17. **Footer** — Brand blurb, three link columns, copyright, and SSR / SEO-ready / infinite-scale badges.

---

## 🛠 Tech Stack

This project is deliberately minimal. The entire site is:

- **HTML5** — Semantic, single-file markup.
- **CSS3** — Custom properties (CSS variables) for theming, CSS grid and flexbox for layout, `conic-gradient` and `linear-gradient` for the visual flourishes, and `backdrop-filter` for the glass navigation. No preprocessor, no utility framework.
- **Vanilla JavaScript** — A tiny amount, with no libraries: a scroll listener that toggles the navigation shadow, and an `IntersectionObserver` that fades sections in as they enter the viewport.
- **Google Fonts** — `Sora` for display headings and `Inter` for body text, loaded from the Google Fonts CDN.

There is **no build step**. There is nothing to `npm install`. The file you edit is the file that ships. That is the whole point — a landing page should never be the most fragile thing in your infrastructure, and this one never will be.

---

## 📁 Project Structure

```
meshbase-platform/
├── index.html      # The entire landing page — markup, styles, and script in one file
├── .nojekyll       # Tells GitHub Pages to skip Jekyll processing (optional but safe)
├── CNAME           # (Optional) Your custom domain, e.g. meshbase.io
└── README.md       # This file
```

That is genuinely all of it. The single-file approach means there are no relative-path surprises, no missing-asset 404s, and no MIME-type misconfigurations to debug. If you later add images or split the CSS out, create an `assets/` folder and reference it with relative paths — GitHub Pages serves whatever is in the repository root of your chosen branch.

---

## 💻 Getting Started Locally

Because there is no build step, "running" the project locally is as simple as opening the file. There are three easy ways:

**Option 1 — Just open it.** Double-click `index.html`, or drag it into a browser tab. Everything works from the `file://` protocol, though a couple of niceties (like some font-loading behavior) are smoother over HTTP.

**Option 2 — Python's built-in server.** From the repository folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

**Option 3 — Node's `serve` package.** If you have Node installed:

```bash
npx serve .
```

Then open the URL it prints (usually `http://localhost:3000`).

Any of these serves the page identically to how GitHub Pages will serve it at **[meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/)**. Edit `index.html`, refresh the browser, and you will see your changes immediately.

---

## 🚀 Deploying to GitHub Pages

This repository is already configured to publish to **[https://meshbaseny.github.io/meshbase-platform/](https://meshbaseny.github.io/meshbase-platform/)**. If you fork it or start fresh, here is the full process:

1. **Push your code** to a GitHub repository. The `index.html` must live at the repository root (or in a `/docs` folder if you prefer — you will select that below).
2. **Open the repository on GitHub** and go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose your branch (usually `main`) and the folder (`/root` if `index.html` is at the top level, or `/docs` if you moved it there).
5. Click **Save**. GitHub will build and publish the site within a minute or two.
6. Your page will be live at `https://<your-username>.github.io/<repository-name>/`. For this project, that is **[meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/)**.

The included `.nojekyll` file tells GitHub Pages not to run the content through Jekyll. This project does not need Jekyll, and the flag prevents Pages from ignoring any files or folders whose names begin with an underscore — a small insurance policy that costs nothing.

Every time you push a change to the published branch, GitHub Pages automatically rebuilds and redeploys. There is no manual deploy command and no CI configuration required.

---

## 🌍 Using a Custom Domain

If you want the landing page to live on a custom domain rather than the `github.io` subdomain, GitHub Pages supports that directly:

1. Add a file named `CNAME` (all caps, no extension) to the repository root containing only your domain, for example:

   ```
   meshbase.io
   ```

2. In **Settings → Pages → Custom domain**, enter the same domain and save.
3. At your DNS provider, point the domain at GitHub Pages. For an apex domain like `meshbase.io`, create `A` records to GitHub's Pages IP addresses; for a `www` subdomain, create a `CNAME` record pointing to `<your-username>.github.io`.
4. Once DNS propagates, enable **Enforce HTTPS** in the Pages settings.

Note that the real MeshBase product already lives at **[meshbase.io](https://meshbase.io)**, so this repository's demo is served from **[meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/)**. Only point a custom domain here if you control it and want it to serve this page.

---

## 🎨 Customization Guide

Almost everything visual is controlled by CSS custom properties defined in the `:root` block at the top of the `<style>` section. You rarely need to hunt through the markup to change the look.

**Change the color palette.** Edit the variables in `:root`. The key ones are:

```css
--violet: #6d5efc;   /* primary brand color */
--cyan:   #17c7e6;   /* secondary accent    */
--mint:   #22d3a5;   /* success / positive  */
--coral:  #ff6b6b;   /* warm accent         */
--amber:  #ffb020;   /* highlight           */
--ink:    #16132b;   /* main text           */
--bg:     #fbfaff;   /* page background     */
```

The gradients (`--grad-hero`, `--grad-warm`, `--grad-mint`, `--grad-pink`) are built from these, so changing a base color ripples through the hero text, buttons, icons, and CTA band automatically.

**Change the copy.** All text is plain HTML inside clearly labeled section comments (for example, `<!-- ================= HERO ================= -->`). Search for the heading you want to change and edit it in place.

**Point the buttons at your links.** Every call-to-action currently uses placeholder anchors (`href="#start"` and `href="#"`). Replace those with `https://meshbase.io` — or your sign-up and sign-in URLs — so visitors land in the right place. A quick find-and-replace of `href="#"` is the fastest way to wire them all up.

**Reorder or remove sections.** Each `<section>` is self-contained. Cut and paste a whole `<section>...</section>` block to reorder, or delete one you do not need. The layout will reflow cleanly because nothing is absolutely positioned relative to another section.

**Edit the cards.** Feature cards live in the `.cards` grid; template cards in `.tmpl`; audience cards reuse the `.card` class. Copy an existing card block, change the icon SVG, heading, paragraph, and tags, and it will match the rest automatically.

**Swap the fonts.** Change the Google Fonts `<link>` in the `<head>` and update the `font-family` declarations for `body` and headings.

---

## 🧱 Design System

The page is built on a small, consistent set of primitives so that edits stay visually coherent:

- **Radius scale** — `--radius: 22px` for large cards and panels, `--radius-sm: 14px` for smaller elements, and `100px` for pills and badges.
- **Shadow scale** — Three tiers (`--shadow-sm`, `--shadow`, `--shadow-lg`) using soft, violet-tinted shadows rather than flat black, which keeps the bright aesthetic from feeling heavy.
- **Typography** — `Sora` (600–800 weight) for headings with tight negative letter-spacing; `Inter` (400–600) for body at a comfortable 1.68 line-height.
- **Spacing rhythm** — Sections use consistent vertical padding that collapses gracefully on small screens.
- **Motion** — A single reveal animation (fade up + slight translate) applied via the `.reveal` class and triggered by `IntersectionObserver`, with a small staggered delay so groups of cards cascade rather than pop in all at once.
- **Decorative background** — Blurred gradient "aurora" blobs and a masked grid sit behind the content at `z-index: -1/-2`, adding depth without distracting from the copy.

---

## ⚡ Performance & Accessibility

The page is fast by construction: one HTML file, no framework runtime, no image payloads beyond inline SVG icons, and only two font families. Fonts are preconnected in the `<head>` to shave a round trip, and the JavaScript is a few lines that run after parse.

On the accessibility side, the markup uses semantic elements (`header`, `nav`, `section`, `footer`, `details`/`summary` for the FAQ), meaningful heading order, sufficient color contrast for body text, and focusable, keyboard-operable controls. The FAQ accordion is built from native `<details>` elements, so it works without JavaScript and is screen-reader friendly out of the box. If you add imagery, remember to include descriptive `alt` text.

---

## 🔍 SEO & Social Sharing

The `<head>` includes a descriptive `<title>`, a meta description, a theme color, and a full set of Open Graph and Twitter Card tags so the page previews nicely when shared on social platforms or in chat apps. Update the `og:url` to your deployed URL — **[https://meshbaseny.github.io/meshbase-platform/](https://meshbaseny.github.io/meshbase-platform/)** — and consider adding an `og:image` pointing to a 1200×630 preview image for the best-looking link cards.

Because the page is a plain static document with server-friendly markup, search engines index it without any special handling. For the product's own SEO story — server-side rendering, structured data, and Lighthouse scores around 98 — see [meshbase.io](https://meshbase.io).

---

## 🌐 Browser Support

The page targets modern evergreen browsers: recent versions of Chrome, Edge, Firefox, and Safari. It uses `backdrop-filter`, CSS `conic-gradient`, CSS custom properties, and `IntersectionObserver`, all of which are widely supported. In older browsers that lack `backdrop-filter`, the navigation simply falls back to a solid translucent background, and everything remains fully readable and usable.

---

## 🗺 Roadmap

Ideas for extending this landing page over time:

- Add a dark-mode variant driven by `prefers-color-scheme` and a toggle.
- Generate and wire in an `og:image` social preview card.
- Add a lightweight, privacy-friendly analytics snippet.
- Break out a `blog/` or `changelog/` section as additional static pages.
- Localize the copy for additional languages.
- Add subtle scroll-linked animations to the hero demo card.

None of these are required — the page is complete and shippable as-is — but they are natural next steps if you want to grow it.

---

## 🤝 Contributing

Contributions are welcome. Because the project is a single file with no build step, the workflow is refreshingly simple:

1. Fork the repository.
2. Create a branch: `git checkout -b my-improvement`.
3. Edit `index.html` and preview locally (see [Getting Started Locally](#-getting-started-locally)).
4. Commit with a clear message and open a pull request describing what you changed and why.

Please keep the single-file, dependency-free philosophy intact unless there is a compelling reason to add tooling. Match the existing code style, reuse the design-system variables rather than hard-coding new colors, and test your change at mobile, tablet, and desktop widths before submitting.

---

## ❓ FAQ

**Do I need to know how to code to edit this page?**
No. The copy is plain HTML with clearly labeled sections — you can change text, links, and colors with basic find-and-replace. Deeper layout changes benefit from some HTML/CSS familiarity, but nothing advanced.

**Is there a build step or framework?**
No. It is a single static `index.html` with inline CSS and a few lines of vanilla JavaScript. There is nothing to install and nothing to compile.

**Where is the page deployed?**
On GitHub Pages, at **[https://meshbaseny.github.io/meshbase-platform/](https://meshbaseny.github.io/meshbase-platform/)**.

**Where do I sign up for the actual MeshBase product?**
At **[meshbase.io](https://meshbase.io)** — it is free to start, with no credit card required.

**Can I use this template for my own project?**
Yes, subject to the license below. Swap the copy, colors, and links for your own brand.

**How do I point the buttons at the real site?**
Replace the placeholder `href="#"` and `href="#start"` anchors with `https://meshbase.io` or your own URLs.

**Will it work on mobile?**
Yes. The layout is fully responsive, collapsing the multi-column grids to single columns and hiding the desktop nav links on small screens.

---

## 📄 License

This landing page source is released under the **MIT License**. You are free to use, copy, modify, and distribute it, including for commercial purposes, provided you include the original copyright and license notice. See the `LICENSE` file for the full text (add one if it is not present).

The **MeshBase** name, logo, and the MeshBase product itself are property of MeshBase and are not covered by this license. Learn more at [meshbase.io](https://meshbase.io).

---

## 🙏 Acknowledgements

- Typefaces: [Sora](https://fonts.google.com/specimen/Sora) and [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts.
- Hosting: [GitHub Pages](https://pages.github.com/).
- Product: [MeshBase](https://meshbase.io) — the AI content infrastructure for modern teams.

---

<div align="center">

### Ready to build?

**Describe your idea. Ship it today.**

[![Start free](https://img.shields.io/badge/Start_building_free-meshbase.io-6d5efc?style=for-the-badge)](https://meshbase.io)
[![View live demo](https://img.shields.io/badge/View_live_demo-meshbaseny.github.io-17c7e6?style=for-the-badge)](https://meshbaseny.github.io/meshbase-platform/)

*SSR · SEO-ready · Infinite scale*

Made with care for **[meshbase.io](https://meshbase.io)** · Live at **[meshbaseny.github.io/meshbase-platform](https://meshbaseny.github.io/meshbase-platform/)**

</div>

