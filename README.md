# Adewale Aloba

Designer who codes. Builder who ships. Lagos, Nigeria.

[artbyade.com](https://artbyade.com) · [LinkedIn](https://linkedin.com/in/adewale-aloba)

---

## About

I'm a senior digital designer with six years across brand identity, motion, 3D, UI/UX, and front-end development. I don't hand off. I design a system, write the code, and ship it. The work at the top of this profile is real projects, not concepts sitting in Figma.

Right now I'm Principal Designer at Parable VC in Dubai, taking on client work in parallel, and quietly building a design agency called Layout Studio. The goal with Layout Studio isn't to replicate the traditional model with a few AI tools bolted on. I'm thinking about the structure from scratch: what work AI should own, what humans need to stay responsible for, and what that means for pricing, team size, and client relationships.

The agentic AI question is live for me right now. I think most creative studios are making the wrong bet: they're using AI to go faster inside the existing structure. I'd rather ask what the structure should be when AI handles repeatable execution reliably. The interesting decisions are in direction, judgment, and what the client actually needs, not in production volume.

---

## Tools

### [motion-design-with-claude](https://github.com/LobzyJay/motion-design-with-claude)

Four Claude Code skills that give Claude the taste and tool knowledge to work alongside a senior motion designer. Covers the 12 principles, easing taxonomy, timing and spacing, AE scripting patterns, and Blender's bpy API. Wires directly into After Effects and Blender via MCP so Claude can execute live commands, not just write scripts you run yourself.

Skills: [`motion-design`](https://github.com/LobzyJay/motion-design-with-claude/tree/main/skills/motion-design) · [`aftereffects-motion`](https://github.com/LobzyJay/motion-design-with-claude/tree/main/skills/aftereffects-motion) · [`blender-motion`](https://github.com/LobzyJay/motion-design-with-claude/tree/main/skills/blender-motion) · [`motion-design-critique`](https://github.com/LobzyJay/motion-design-with-claude/tree/main/skills/motion-design-critique)

---

## Design Systems

### [agmb-design-system](https://github.com/LobzyJay/agmb-design-system)

A token-driven design system built for AG Mortgage Bank Plc, a CBN-licensed Nigerian Primary Mortgage Institution. 28 primitives, 24 canonical colour hexes, 11 motion tokens, and a bi-script type stack: Libre Baskerville for heritage gravitas, Elms Sans for modern utility. The reference set was ACI Worldwide, Stripe, and Mercury, not fintech-lite. Built in Next.js. Documented and surfaced at `/design`.

### [layoutstudio-design-system-](https://github.com/LobzyJay/layoutstudio-design-system-)

The source of truth for Layout Studio's own visual language. CSS custom properties, JSON design tokens, and grid templates (L01–L07) for decks, landing pages, and shipped product. Coolvetica for display headings, Founders Grotesk for body. Dark-first rhythm throughout. Built to be referenced by AI tools and Claude Design AI via live GitHub Pages URLs and anchor fragments.

### [Systemspec-website-redesign](https://github.com/LobzyJay/Systemspec-website-redesign)

A full rebuild of Systemspec Technology Solutions as three deliverables in one monorepo: marketing site, design system, and UI kit. The design system lives inside the marketing site at `/design/`. The UI kit is a separate app. Built in TypeScript/Next.js. Demonstrates how design system work and production site delivery can share the same repository without stepping on each other.

---

## Web Projects

### [agmb-website](https://github.com/LobzyJay/agmb-website)

Public marketing site for AG Mortgage Bank Plc. Twelve pages: home, mortgage products, calculator, about, insights, contact, and application start. Built with Eleventy 3.1.5 and GSAP ScrollTrigger for line-by-line heading entrances and scroll-reveal sections. GitHub Actions deploys to GitHub Pages on every push. Lives at lobzyjay.github.io/agmb-website.

### [Pacific-blue](https://github.com/LobzyJay/Pacific-blue)

Marketing site for Pacific Blue, an Australian renewable energy company. The centrepiece is a Three.js wind turbine scene: a GLB model with scroll-driven blade speed, fog, and a starfield. The turbine section locks sticky below the header as you scroll through content phases. Also has a 3.5-second loader, bento grid with animated counters that reset on scroll-away, and a Canvas particle footer. No build step.

### [Daily-Digest](https://github.com/LobzyJay/Daily-Digest)

A dark-first productivity dashboard modelled on a bento grid layout. Eight modules: inbox, job board aggregator with Google X-Ray ATS search, Pomodoro focus timer, news feeds, networking leads tracker, calendar, cold email composer, and activity log. Includes a Quiet Mode that strips the interface back to a minimal focus view. Single-page HTML/CSS/JS, no build step required.

### [Synexis-DeSCI](https://github.com/LobzyJay/Synexis-DeSCI)

Landing page concept for Synexis, a Decentralized Science project. Built in HTML, exploring how DeSci infrastructure might be communicated to an audience that isn't already in the space.

### [Moodboard-bento-builder](https://github.com/LobzyJay/Moodboard-bento-builder)

A browser-based bento grid tool for building and exporting moodboards. HTML.

### [Voltex](https://github.com/LobzyJay/Voltex)

A front-end build in HTML. In progress.

### [website-protoype](https://github.com/LobzyJay/website-protoype)

Early-stage website prototype. HTML.

### [Portfolio](https://github.com/LobzyJay/Portfolio)

Holding portfolio site while the main one is rebuilt. CSS-driven layout.

---

## Articles

### [Redesigning a 1992 Nigerian holding company's website with AI](https://www.artbyade.com/case-study/stsl/)

A build log for the STSL marketing site rebuild. Covers the thesis (editorial, not promotional), the two-layer token architecture, how a multi-agent Claude workflow handled the heavy lifting, and the sequence of bugs that surfaced once real users hit the live build. The honest version of shipping a quietly modern site for an audience that doesn't want to be marketed to.

---

## How I Think About Design and Code

Design and code are the same conversation for me. When I spec a component, I'm already thinking about how it renders. When I write CSS, I'm making design decisions. Keeping those two tracks separate adds lag, misses context, and produces worse work on both sides.

Brand identity is a system problem before it's an aesthetic problem. The question isn't what looks good. It's what holds together at scale: across applications, screen sizes, production constraints, and people who weren't in the original brief. I work out the rules first and let the visuals follow from them.

For early-stage clients, the designer-developer combination matters because there's no margin for miscommunication. A startup can't afford a two-week loop between spec and implementation for every component. When one person holds the full picture, decisions are faster and the output is more coherent.

The agentic question is the one I'm sitting with right now. If AI can handle execution reliably at the component and layout level, what does the senior designer's job actually become? My answer: the thing AI can't own is the judgment call about what the client needs versus what they asked for, the read on whether a brand direction is going to age badly, and the relationship that makes honest feedback possible. That's where I want to spend my time.

---

## Stack and Tools

| Design | Development |
|---|---|
| Figma, After Effects, Blender | HTML, CSS, JavaScript |
| Cinema 4D, Spline | Three.js, Canvas API, Matter.js |
| Premiere Pro, DaVinci Resolve | TypeScript, React (in progress) |
| Adobe Creative Suite | Claude Code, Lovable |

---

## Background

I started in design and got pulled toward code because I kept running into things I wanted to build that no developer was going to prioritise. Six years later the split is roughly 60/40: design direction and systems thinking on one side, front-end implementation on the other. The curiosity that drives the work is broader than either. I read across art, science, maths, finance, biology, and history, and that range shows up in the work. Different domains borrow from each other constantly. The best design decisions I've made came from thinking that started somewhere else entirely. Now I'm founding Layout Studio, which is the thing I want to build long enough to have an opinion about.

---

## Currently Building and Learning

- Three.js: scenes, GLB pipelines, scroll-driven animation
- React: moving from vanilla JS toward component-driven front-end work
- Blender scripting: Python automation for 3D pipeline tasks
- Agentic studio structure: what a creative studio looks like when AI owns execution (team model, pricing, client relationships)
- AGMB design system: extending token coverage and pattern library

---

## Reach

- [artbyade.com](https://artbyade.com)
- [LinkedIn](https://linkedin.com/in/adewale-aloba)
- Open to: freelance, full-time remote (UK, UAE, global tech), Web3 design and brand collaborations
