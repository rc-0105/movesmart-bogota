# Skill Registry

**Delegator use only.** Any agent that launches sub-agents reads this registry to resolve compact rules, then injects them directly into sub-agent prompts. Sub-agents do NOT read this registry or individual SKILL.md files.

See `_shared/skill-resolver.md` for the full resolution protocol.

## User Skills

| Trigger | Skill | Path |
|---------|-------|------|
| UI/UX design, frontend interfaces | ui-ux-pro-max | C:\Users\Ricardo\.config\opencode\skills\ui-ux-pro-max\SKILL.md |
| Design, redesign, critique, polish, improve frontend | impeccable | C:\Users\Ricardo\.config\opencode\skills\impeccable\SKILL.md |
| Structure commits as deliverable work units | work-unit-commits | C:\Users\Ricardo\.config\opencode\skills\work-unit-commits\SKILL.md |
| Write warm, direct, human comments for PRs/issues | comment-writer | C:\Users\Ricardo\.config\opencode\skills\comment-writer\SKILL.md |
| Design documentation with progressive disclosure | cognitive-doc-design | C:\Users\Ricardo\.config\opencode\skills\cognitive-doc-design\SKILL.md |
| Split large PRs into chained/stacked PRs | gentle-ai-chained-pr | C:\Users\Ricardo\.config\opencode\skills\chained-pr\SKILL.md |
| Create a new AI agent skill | skill-creator | C:\Users\Ricardo\.config\opencode\skills\skill-creator\SKILL.md |
| SEO audit, technical SEO, Core Web Vitals | seo | C:\Users\Ricardo\.claude\skills\agentic-seo\SKILL.md |
| Design social media banners, ads, website heroes | ckm:banner-design | C:\Users\Ricardo\.claude\skills\ui-ux-pro-max-skill\.claude\skills\banner-design\SKILL.md |
| Brand voice, visual identity, messaging | ckm:brand | C:\Users\Ricardo\.claude\skills\ui-ux-pro-max-skill\.claude\skills\brand\SKILL.md |
| Logo generation, corporate identity program | ckm:design | C:\Users\Ricardo\.claude\skills\ui-ux-pro-max-skill\.claude\skills\design\SKILL.md |
| Design tokens, component specs, slide generation | ckm:design-system | C:\Users\Ricardo\.claude\skills\ui-ux-pro-max-skill\.claude\skills\design-system\SKILL.md |
| HTML presentations with Chart.js | ckm:slides | C:\Users\Ricardo\.claude\skills\ui-ux-pro-max-skill\.claude\skills\slides\SKILL.md |
| Beautiful UI with shadcn/ui, Tailwind, Radix | ckm:ui-styling | C:\Users\Ricardo\.claude\skills\ui-ux-pro-max-skill\.claude\skills\ui-styling\SKILL.md |
| Go tests, Bubbletea TUI testing | go-testing | C:\Users\Ricardo\.config\opencode\skills\go-testing\SKILL.md |
| Create GitHub PR, prepare changes for review | branch-pr | C:\Users\Ricardo\.config\opencode\skills\branch-pr\SKILL.md |
| Adversarial dual review, judgment day | judgment-day | C:\Users\Ricardo\.config\opencode\skills\judgment-day\SKILL.md |
| Create GitHub issue, report bug, request feature | issue-creation | C:\Users\Ricardo\.config\opencode\skills\issue-creation\SKILL.md |
| WhatsApp agent with Evolution API + n8n | whatsapp-agent-creator | C:\Users\Ricardo\.claude\skills\whatsapp-agent-creator\SKILL.md |

## Compact Rules

Pre-digested rules per skill. Delegators copy matching blocks into sub-agent prompts as `## Project Standards (auto-resolved)`.

### ui-ux-pro-max
- Search database of 67 styles, 161 color palettes, 57 font pairings
- Use 99 UX guidelines and 25 chart types across 16 stacks
- Trigger: UI/UX design, frontend interfaces

### impeccable
- Use for design, redesign, critique, audit, polish, clarify, optimize frontend
- Covers websites, landing pages, dashboards, product UI, components, forms, empty states
- Trigger: design redesign shape critique polish clarify improve

### work-unit-commits
- Structure commits as deliverable work units, not file-type batches
- Keep tests and docs beside the code they verify
- Trigger: commits, PRs, work units

### comment-writer
- Write warm, direct, human comments for PRs, issues, reviews, async collaboration
- Trigger: drafting feedback, review comments, maintainer replies

### cognitive-doc-design
- Reduce cognitive load through progressive disclosure, chunking, signposting
- Use tables, checklists, recognition over recall
- Trigger: guides, READMEs, RFCs, onboarding docs

### gentle-ai-chained-pr
- Split large PRs into chained/stacked under 400-line cognitive budget
- Trigger: PR exceeds 400 lines, chained PRs, stacked PRs

### skill-creator
- Create new AI agent skills following Agent Skills spec
- Trigger: create new skill, add agent instructions

### seo
- Deterministic LLM-first SEO audits for websites, blog posts, repos
- Run bundled scripts for evidence, return prioritized confidence-labeled fixes
- Trigger: SEO analysis, audit, technical SEO, Core Web Vitals

### ckm:banner-design
- Design banners for social media, ads, website heroes, print
- 22 styles: minimalist, gradient, bold typography, retro, glassmorphism, neon, duotone
- Platforms: Facebook, Twitter, LinkedIn, YouTube, Instagram, Google Ads

### ckm:brand
- Brand voice, visual identity, messaging frameworks
- Asset management, brand consistency, style guides
- Trigger: branded content, tone of voice, marketing assets

### ckm:design
- Comprehensive design: brand identity, design tokens, logo generation (55 styles)
- Corporate identity program (50 deliverables), HTML presentations
- Icon design (15 styles, SVG), social photos

### ckm:design-system
- Three-layer tokens: primitive → semantic → component
- CSS variables, spacing/typography scales, component specs
- Strategic slide creation

### ckm:slides
- Create strategic HTML presentations with Chart.js
- Use design tokens, responsive layouts, copywriting formulas
- Contextual slide strategies

### ckm:ui-styling
- Create beautiful accessible UIs with shadcn/ui (Radix UI + Tailwind)
- Tailwind CSS utility-first styling, canvas-based visual designs
- Dark mode, theming, accessible components (dialogs, dropdowns, forms, tables)

### go-testing
- Go testing patterns for Gentleman.Dots, Bubbletea TUI testing
- Use teatest for Go tests
- Trigger: Go tests, using teatest, adding test coverage

### branch-pr
- PR creation workflow following issue-first enforcement
- Trigger: creating pull request, opening PR, preparing changes for review

### judgment-day
- Parallel adversarial review with two independent blind judges
- Synthesize findings, apply fixes, re-judge until both pass or escalate
- Trigger: "judgment day", dual review, "que lo juzguen"

### issue-creation
- Issue creation workflow following issue-first enforcement
- Trigger: creating GitHub issue, reporting bug, requesting feature

### whatsapp-agent-creator
- Wizard for WhatsApp agents: Evolution API + n8n + Claude/OpenAI
- Produces n8n workflow, system prompt, .env.example
- Trigger: create WhatsApp agent, bot, whatsapp-agent

## Project Conventions

| File | Path | Notes |
|------|------|-------|
| AGENTS.md | C:\Users\Ricardo\.config\opencode\AGENTS.md | Senior Architect, GDE & MVP, 15+ years — rules, personality, tone |

Read the convention files listed above for project-specific patterns and rules.

---
*Skill registry generated: 2026-06-03*