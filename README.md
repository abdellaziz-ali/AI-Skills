<p align="center">
  <h1 align="center">🧠 AI Skills Collection</h1>
  <p align="center">
    <strong>309 curated skills for AI coding agents — install once, use everywhere.</strong>
  </p>
  <p align="center">
    Works with Claude Code · Cursor · Cline · Copilot · Windsurf · Codex · Amp · and 40+ more
  </p>
</p>

---

## ⚡ Quick Install

**One command to install all 309 skills globally:**

```bash
npx skills@latest add abdellaziz-ali/AI-Skills -g --all
```

> This installs skills to `~/.agents/skills/` — available in **every project** automatically.

---

## 📖 What Are Skills?

Skills are `SKILL.md` instruction files that teach AI coding agents **how** to perform specific tasks — processes, constraints, examples, and templates baked into a portable format.

Instead of explaining your workflow every session, you install a skill once and your agent uses it forever.

```
~/.agents/skills/
├── tdd/SKILL.md                    ← Test-driven development process
├── systematic-debugging/SKILL.md   ← 4-phase debugging methodology
├── frontend-design/SKILL.md        ← UI/UX design principles
├── stripe-integration/SKILL.md     ← Payment flow patterns
└── ... (309 folders)
```

**You don't invoke skills manually.** Just describe your task naturally — the agent detects and applies the right skill:

| You Say | Skill That Activates |
|---------|---------------------|
| "Write tests for this module" | `tdd` |
| "Debug this crash" | `systematic-debugging` |
| "Create a PRD for this feature" | `to-prd` |
| "Redesign this UI" | `redesign-existing-projects` |
| "SEO audit this page" | `seo-audit` |

---

## 🗂️ Full Skill Catalog (309 Skills)

### 📋 Planning & Design (14)

| Skill | What It Does |
|-------|-------------|
| `grill-me` | Relentless clarifying questions before building |
| `to-prd` | Interactive interview → PRD as GitHub issue |
| `to-issues` | Breaks PRD into independent GitHub issues |
| `design-an-interface` | Generates 3-5 competing interface designs |
| `request-refactor-plan` | Detailed refactor plan with tiny commits |
| `discover` | Conversational discovery — scoping to deep interviews |
| `task-breakdown` | Decomposes specs into buildable tasks with dependencies |
| `brainstorming` | Socratic questioning for feature ideation |
| `writing-plans` | Multi-step implementation plans before code |
| `architecture-decision-records` | Document technical decisions as ADRs |
| `architecture-patterns` | Clean Architecture, Hexagonal, DDD patterns |
| `site-architecture` | Website page hierarchy and navigation planning |
| `domain-model` | DDD-style domain modeling |
| `ubiquitous-language` | Extract domain language glossary |

### 🧪 Testing & Quality (16)

| Skill | What It Does |
|-------|-------------|
| `tdd` | Strict red-green-refactor loop |
| `test-driven-development` | TDD workflow from Superpowers |
| `qa` | Full QA pass with issue breakdown |
| `triage-issue` | Investigate bug → file GitHub issue with fix plan |
| `e2e-testing-patterns` | Playwright & Cypress patterns |
| `javascript-testing-patterns` | Jest, Vitest, Testing Library |
| `python-testing-patterns` | pytest, fixtures, mocking |
| `webapp-testing` | Web application E2E testing |
| `bats-testing-patterns` | Bash script testing |
| `temporal-python-testing` | Temporal workflow tests |
| `web3-testing` | Smart contract testing (Hardhat/Foundry) |
| `llm-evaluation` | LLM output quality evaluation |
| `verification-before-completion` | Verify before claiming work is done |
| `data-quality-frameworks` | Great Expectations, dbt tests |
| `screen-reader-testing` | VoiceOver, NVDA, JAWS testing |
| `wcag-audit-patterns` | WCAG 2.2 accessibility audits |

### 🐛 Debugging (5)

| Skill | What It Does |
|-------|-------------|
| `systematic-debugging` | 4-phase methodology — no random changes |
| `debugging-strategies` | Profiling tools and root cause analysis |
| `parallel-debugging` | Competing hypotheses with evidence collection |
| `error-handling-patterns` | Exceptions, Result types, graceful degradation |
| `postmortem-writing` | Blameless postmortems with action items |

### 💻 Code Development (20)

| Skill | What It Does |
|-------|-------------|
| `improve-codebase-architecture` | Find architectural improvement opportunities |
| `code-review-excellence` | Constructive code review practices |
| `requesting-code-review` | Prepare work for review |
| `receiving-code-review` | Handle review feedback with rigor |
| `review-chain` | Post-implementation fresh-eyes review |
| `migrate-to-shoehorn` | TypeScript test migration |
| `scaffold-exercises` | Create exercise/course structures |
| `changelog-generator` | Commits → human-readable changelogs |
| `changelog-automation` | Automated changelog from PRs/releases |
| `prompt-engineering-patterns` | Advanced LLM prompt techniques |
| `modern-javascript-patterns` | ES6+ async/await, destructuring, modules |
| `typescript-advanced-types` | Generics, conditional types, mapped types |
| `react-modernization` | Migrate React to latest versions |
| `react-state-management` | Redux Toolkit, Zustand, Jotai, React Query |
| `nextjs-app-router-patterns` | Next.js 14+ App Router, Server Components |
| `angular-migration` | AngularJS → Angular migration |
| `dependency-upgrade` | Major version upgrades with compatibility analysis |
| `openapi-spec-generation` | Generate OpenAPI 3.1 specs |
| `full-output-enforcement` | No lazy truncation — complete code output |
| `caveman` | Ultra-compressed communication (~75% fewer tokens) |

### 🐍 Python (16)

| Skill | What It Does |
|-------|-------------|
| `python-anti-patterns` | Common Python anti-patterns to avoid |
| `python-background-jobs` | Task queues, workers, event-driven |
| `python-code-style` | Linting, formatting, naming conventions |
| `python-configuration` | Environment variables, pydantic-settings |
| `python-design-patterns` | KISS, SoC, SRP, composition over inheritance |
| `python-error-handling` | Validation, exception hierarchies |
| `python-observability` | Structured logging, metrics, tracing |
| `python-packaging` | PyPI publishing, pyproject.toml |
| `python-performance-optimization` | cProfile, memory profilers |
| `python-project-structure` | Module organization, public APIs |
| `python-resilience` | Retries, backoff, timeouts |
| `python-resource-management` | Context managers, cleanup patterns |
| `python-type-safety` | Type hints, generics, protocols |
| `async-python-patterns` | asyncio, concurrent programming |
| `uv-package-manager` | Fast Python dependency management |

### ⚛️ React & Next.js (8)

| Skill | What It Does |
|-------|-------------|
| `vercel-react-best-practices` | Vercel Engineering performance patterns |
| `vercel-composition-patterns` | Component composition that scales |
| `vercel-react-view-transitions` | View Transition API in React |
| `nextjs-app-router-patterns` | App Router, streaming, parallel routes |
| `react-state-management` | Redux, Zustand, Jotai, React Query |
| `react-modernization` | Upgrade to latest React |
| `react-native-architecture` | Expo, navigation, native modules |
| `react-native-design` | RN styling, Reanimated animations |

### 🎨 UI/UX Design (18)

| Skill | What It Does |
|-------|-------------|
| `frontend-design` | Modern clean UI guidance |
| `high-end-visual-design` | Premium agency-level design |
| `design-taste-frontend` | Senior UI/UX engineering |
| `gpt-taste` | GSAP motion, editorial typography |
| `minimalist-ui` | Clean editorial interfaces |
| `industrial-brutalist-ui` | Raw mechanical brutalist aesthetic |
| `image-to-code` | Screenshot → pixel-perfect code |
| `redesign-existing-projects` | Upgrade existing sites to premium |
| `stitch-design-taste` | Semantic design system for Stitch |
| `design-system-patterns` | Design tokens, theming, components |
| `responsive-design` | Container queries, fluid typography |
| `interaction-design` | Microinteractions, motion, transitions |
| `visual-design-foundations` | Typography, color theory, spacing |
| `web-component-design` | React, Vue, Svelte component patterns |
| `web-design-guidelines` | Web Interface Guidelines compliance |
| `accessibility-compliance` | WCAG 2.2, inclusive design |
| `tailwind-design-system` | Tailwind CSS v4 design systems |
| `brand-guidelines` | Brand system enforcement |

### 📱 Mobile (6)

| Skill | What It Does |
|-------|-------------|
| `mobile-ios-design` | iOS HIG and SwiftUI patterns |
| `mobile-android-design` | Material Design 3 and Jetpack Compose |
| `react-native-architecture` | Production React Native with Expo |
| `react-native-design` | RN styling and Reanimated |
| `vercel-react-native-skills` | React Native/Expo best practices |
| `aso-audit` | App Store / Google Play listing optimization |

### 🔐 Security (12)

| Skill | What It Does |
|-------|-------------|
| `auth-implementation-patterns` | JWT, OAuth2, session management, RBAC |
| `sast-configuration` | Static security scanning |
| `security-requirement-extraction` | Threats → actionable requirements |
| `stride-analysis-patterns` | STRIDE threat modeling |
| `attack-tree-construction` | Visualize threat paths |
| `threat-mitigation-mapping` | Map threats to controls |
| `solidity-security` | Smart contract security |
| `pci-compliance` | Payment card security |
| `gdpr-data-handling` | GDPR-compliant data handling |
| `secrets-management` | Vault, AWS Secrets Manager |
| `mtls-configuration` | Zero-trust mTLS |
| `k8s-security-policies` | Kubernetes RBAC and NetworkPolicy |

### 🔍 Reverse Engineering (4)

| Skill | What It Does |
|-------|-------------|
| `binary-analysis-patterns` | Disassembly, decompilation, CFG |
| `anti-reversing-techniques` | Anti-debug, obfuscation analysis |
| `memory-forensics` | RAM analysis with Volatility |
| `protocol-reverse-engineering` | Network protocol analysis |

### 🏗️ Backend & API (10)

| Skill | What It Does |
|-------|-------------|
| `api-design-principles` | REST & GraphQL API design |
| `fastapi-templates` | Production FastAPI projects |
| `nodejs-backend-patterns` | Express/Fastify, middleware, APIs |
| `dotnet-backend-patterns` | C#/.NET APIs, Entity Framework |
| `microservices-patterns` | Service boundaries, event-driven |
| `cqrs-implementation` | Command/Query separation |
| `saga-orchestration` | Distributed transactions |
| `event-store-design` | Event sourcing infrastructure |
| `projection-patterns` | Read models from event streams |
| `stripe-integration` | Payments, subscriptions, webhooks |

### 🗄️ Database (5)

| Skill | What It Does |
|-------|-------------|
| `postgresql-table-design` | PostgreSQL schema best practices |
| `sql-optimization-patterns` | Query optimization and indexing |
| `database-migration` | Zero-downtime migrations |
| `embedding-strategies` | Vector embeddings for RAG |
| `similarity-search-patterns` | Vector database search |

### 🤖 AI/ML (6)

| Skill | What It Does |
|-------|-------------|
| `rag-implementation` | RAG systems with vector DBs |
| `langchain-architecture` | LangChain 1.x and LangGraph |
| `langsmith-fetch` | Debug LangChain agents via traces |
| `llm-evaluation` | LLM output quality metrics |
| `ml-pipeline-workflow` | MLOps pipelines |
| `hybrid-search-implementation` | Vector + keyword search |
| `vector-index-tuning` | HNSW parameters, quantization |

### 🦀 Rust & Go (3)

| Skill | What It Does |
|-------|-------------|
| `rust-async-patterns` | Tokio, async traits, concurrency |
| `memory-safety-patterns` | RAII, ownership, smart pointers |
| `go-concurrency-patterns` | Goroutines, channels, sync |

### ☁️ DevOps & Infrastructure (20)

| Skill | What It Does |
|-------|-------------|
| `github-actions-templates` | CI/CD with GitHub Actions |
| `gitlab-ci-patterns` | GitLab CI/CD pipelines |
| `deployment-pipeline-design` | Multi-stage deployment pipelines |
| `gitops-workflow` | ArgoCD and Flux for Kubernetes |
| `k8s-manifest-generator` | Production Kubernetes YAMLs |
| `helm-chart-scaffolding` | Helm chart design |
| `terraform-module-library` | Reusable Terraform modules |
| `cost-optimization` | Cloud cost optimization |
| `multi-cloud-architecture` | AWS + Azure + GCP patterns |
| `hybrid-cloud-networking` | VPN and dedicated connections |
| `prometheus-configuration` | Metrics collection and alerting |
| `grafana-dashboards` | Monitoring dashboards |
| `distributed-tracing` | Jaeger and Tempo tracing |
| `slo-implementation` | SLIs, SLOs, error budgets |
| `incident-runbook-templates` | Step-by-step recovery guides |
| `on-call-handoff-patterns` | Shift transitions |
| `istio-traffic-management` | Service mesh traffic policies |
| `linkerd-patterns` | Lightweight service mesh |
| `service-mesh-observability` | Mesh monitoring |
| `deploy-to-vercel` | Vercel deployment automation |

### 🔧 Tooling & Git (10)

| Skill | What It Does |
|-------|-------------|
| `setup-pre-commit` | Husky + lint-staged + Prettier |
| `git-guardrails-claude-code` | Block dangerous git commands |
| `git-advanced-workflows` | Rebase, cherry-pick, bisect, worktrees |
| `using-git-worktrees` | Isolated feature branches |
| `finishing-a-development-branch` | Merge, PR, or cleanup decisions |
| `block-no-verify-hook` | Prevent `--no-verify` bypasses |
| `shellcheck-configuration` | Shell script linting |
| `bash-defensive-patterns` | Production-grade shell scripts |
| `bazel-build-optimization` | Bazel builds for monorepos |
| `nx-workspace-patterns` | Nx monorepo configuration |

### 🔎 SEO (23)

| Skill | What It Does |
|-------|-------------|
| `seo` | Comprehensive full-site SEO analysis |
| `seo-audit` | Technical SEO audit |
| `seo-technical` | Crawlability, indexability, security |
| `seo-page` | Single-page deep analysis |
| `seo-content` | E-E-A-T and content quality |
| `seo-schema` | JSON-LD structured data |
| `seo-sitemap` | XML sitemap analysis/generation |
| `seo-images` | Image optimization for SEO |
| `seo-image-gen` | AI-generated SEO images |
| `seo-local` | Google Business Profile, NAP, citations |
| `seo-maps` | Geo-grid rank tracking, GBP audit |
| `seo-backlinks` | Backlink profile analysis |
| `seo-cluster` | SERP-based topic clustering |
| `seo-competitor-pages` | "X vs Y" comparison pages |
| `seo-plan` | Strategic SEO planning |
| `seo-programmatic` | Pages at scale from data |
| `seo-ecommerce` | Product SEO, Google Shopping |
| `seo-hreflang` | International/multilingual SEO |
| `seo-drift` | SEO regression monitoring |
| `seo-geo` | AI Overviews / GEO optimization |
| `seo-google` | Search Console, PageSpeed, CrUX |
| `seo-dataforseo` | Live SERP data via DataForSEO |
| `seo-sxo` | Search experience optimization |

### 📈 Marketing & Growth (30)

| Skill | What It Does |
|-------|-------------|
| `copywriting` | Homepage, landing page, pricing copy |
| `copy-editing` | Edit and improve existing copy |
| `content-strategy` | What content to create and why |
| `content-research-writer` | Research + citations + writing |
| `social-content` | LinkedIn, Twitter, TikTok content |
| `email-sequence` | Drip campaigns, nurture sequences |
| `cold-email` | B2B cold outreach that gets replies |
| `ad-creative` | Ad copy at scale for any platform |
| `paid-ads` | Google, Meta, LinkedIn campaigns |
| `competitive-ads-extractor` | Analyze competitor ads |
| `page-cro` | Landing page conversion optimization |
| `signup-flow-cro` | Registration flow optimization |
| `onboarding-cro` | Post-signup activation |
| `form-cro` | Form completion optimization |
| `popup-cro` | Modal/popup conversion optimization |
| `paywall-upgrade-cro` | In-app upgrade screens |
| `pricing-strategy` | Pricing, packaging, monetization |
| `ab-test-setup` | A/B test design and implementation |
| `analytics-tracking` | GA4, GTM, event tracking |
| `launch-strategy` | Product launch planning |
| `referral-program` | Referral/affiliate programs |
| `churn-prevention` | Cancel flows, save offers, dunning |
| `marketing-ideas` | Marketing inspiration and strategies |
| `marketing-psychology` | Cognitive bias, persuasion |
| `lead-magnets` | Ebooks, checklists, templates |
| `free-tool-strategy` | Free tools for lead gen |
| `directory-submissions` | Submit to startup directories |
| `programmatic-seo` | SEO pages at scale |
| `competitive-landscape` | Porter's Five Forces, positioning |
| `ai-seo` | Optimize for AI search engines |

### 💼 Business & Sales (10)

| Skill | What It Does |
|-------|-------------|
| `sales-enablement` | Pitch decks, one-pagers, demo scripts |
| `competitor-alternatives` | "Alternative to X" pages |
| `competitor-profiling` | Research competitors from URLs |
| `customer-research` | ICP research, VOC, review mining |
| `product-marketing-context` | Positioning and audience context |
| `revops` | Revenue operations, lead lifecycle |
| `market-sizing-analysis` | TAM/SAM/SOM calculations |
| `startup-financial-modeling` | 3-5 year financial projections |
| `startup-metrics-framework` | SaaS metrics, unit economics |
| `team-composition-analysis` | Hiring plans, compensation |

### 📄 Documents & Office (7)

| Skill | What It Does |
|-------|-------------|
| `pdf` | Extract, merge, split, fill PDFs |
| `docx` | Word docs with tracked changes |
| `pptx` | Slide decks, layouts, speaker notes |
| `xlsx` | Formulas, pivot tables, charts |
| `doc-coauthoring` | Collaborative writing with AI |
| `edit-article` | Restructure and tighten articles |
| `employment-contract-templates` | Employment agreements, HR docs |

### 🎮 Game Development (2)

| Skill | What It Does |
|-------|-------------|
| `godot-gdscript-patterns` | Godot 4 GDScript patterns |
| `unity-ecs-patterns` | Unity ECS with DOTS and Burst |

### ⛓️ Web3 & Blockchain (4)

| Skill | What It Does |
|-------|-------------|
| `solidity-security` | Smart contract security |
| `web3-testing` | Hardhat/Foundry testing |
| `defi-protocol-templates` | DeFi staking, AMMs, governance |
| `nft-standards` | ERC-721, ERC-1155 implementations |

### 📊 Data Engineering (5)

| Skill | What It Does |
|-------|-------------|
| `airflow-dag-patterns` | Apache Airflow DAGs |
| `dbt-transformation-patterns` | dbt analytics engineering |
| `spark-optimization` | Apache Spark optimization |
| `data-quality-frameworks` | Great Expectations, data contracts |
| `data-storytelling` | Data → compelling narratives |

### 💰 Finance (3)

| Skill | What It Does |
|-------|-------------|
| `backtesting-frameworks` | Trading strategy backtesting |
| `risk-metrics-calculation` | VaR, Sharpe, drawdown analysis |
| `billing-automation` | Recurring payments, invoicing |

### 🎬 Media (5)

| Skill | What It Does |
|-------|-------------|
| `image` | AI image generation for marketing |
| `image-enhancer` | Screenshot quality enhancement |
| `video` | AI video production workflows |
| `youtube` | YouTube channel optimization |
| `youtube-downloader` | Download YouTube videos |

### 🤝 Multi-Agent Orchestration (10)

| Skill | What It Does |
|-------|-------------|
| `agent-room` | Multi-agent debate or poll |
| `dispatching-parallel-agents` | Parallel independent tasks |
| `subagent-driven-development` | Execute plans with subagents |
| `executing-plans` | Execute implementation plans |
| `task-coordination-strategies` | Decompose and coordinate work |
| `team-composition-patterns` | Optimal agent team design |
| `team-communication-protocols` | Structured agent messaging |
| `parallel-feature-development` | Multi-agent file ownership |
| `multi-reviewer-patterns` | Parallel code reviews |
| `navigate` | Multi-phase workflow orchestration |

### 🛠️ Meta Skills (8)

| Skill | What It Does |
|-------|-------------|
| `skill-creator` | Benchmark + draft new skills |
| `write-a-skill` | Proper skill structure and bundling |
| `find-skills` | Search public skill marketplaces |
| `using-superpowers` | Discover and use available skills |
| `writing-skills` | Create/edit/verify skills |
| `context-engineering-collection` | Context management for agents |
| `context-driven-development` | Project context artifacts |
| `evaluation-methodology` | Skill quality measurement |

### 🧰 Miscellaneous (16)

| Skill | What It Does |
|-------|-------------|
| `domain-name-brainstormer` | Product names + domain availability |
| `tailored-resume-generator` | Job-tailored resumes |
| `twitter-algorithm-optimizer` | Optimize tweets for reach |
| `file-organizer` | Intelligent file organization |
| `invoice-organizer` | Auto-organize invoices for tax |
| `lead-research-assistant` | Find leads for your product |
| `raffle-winner-picker` | Random winner selection |
| `meeting-insights-analyzer` | Meeting transcript analysis |
| `developer-growth-analysis` | Coding pattern analysis |
| `obsidian-vault` | Obsidian note management |
| `slack-gif-creator` | Animated GIFs for Slack |
| `connect` / `connect-apps` | Connect to Gmail, Slack, GitHub, etc. |
| `canvas-design` | Static visual art and posters |
| `algorithmic-art` | Generative art with p5.js |
| `internal-comms` | Status reports, leadership updates |
| `hads` | Human-and-AI-friendly documentation |

---

## 🖥️ Supported Agents

These skills work with **45+ AI coding agents** including:

| Agent | Auto-Loads Global Skills |
|-------|------------------------|
| **Claude Code** | ✅ `~/.agents/skills/` |
| **Cursor** | ✅ `~/.agents/skills/` |
| **Cline** | ✅ `~/.agents/skills/` |
| **Windsurf** | ✅ `~/.agents/skills/` |
| **Codex** | ✅ `~/.agents/skills/` |
| **Amp** | ✅ `~/.agents/skills/` |
| **Augment** | ✅ `~/.agents/skills/` |
| **CodeBuddy** | ✅ `~/.agents/skills/` |
| **VS Code Copilot** | ⚠️ Project-level `.github/skills/` |

### For VS Code Copilot Users

Copilot reads project-level skills. Copy the `skills/` folder into your project:

```bash
# From your project root
cp -r ~/.agents/skills .github/skills

# Or on Windows
xcopy "%USERPROFILE%\.agents\skills" ".github\skills" /E /I
```

---

## 📦 Sources & Credits

All skills are aggregated from these open-source repositories:

| Repository | Count | Focus |
|-----------|-------|-------|
| [mattpocock/skills](https://github.com/mattpocock/skills) | 21 | Planning, TDD, QA, PRD |
| [anthropics/skills](https://github.com/anthropics/skills) | 18 | Official Anthropic skills |
| [obra/superpowers](https://github.com/obra/superpowers) | 14 | Debugging, brainstorming, TDD |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | 7 | React, Next.js, Vercel |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 28 | Community skills collection |
| [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | 23 | Full SEO suite |
| [AgriciDaniel/claude-youtube](https://github.com/AgriciDaniel/claude-youtube) | 1 | YouTube optimization |
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 20+ | Marketing & CRO |
| [hungv47/meta-skills](https://github.com/hungv47/meta-skills) | 5 | Multi-agent orchestration |
| [wshobson/agents](https://github.com/wshobson/agents) | 70+ | Python, JS, Rust, Go, security, DevOps |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 9 | Design taste & visual quality |

---

## 🔄 Maintenance

```bash
# Update all skills
npx skills@latest update -g

# Remove all skills
npx skills@latest remove -g --all

# Add a single skill
npx skills@latest add abdellaziz-ali/AI-Skills/tdd -g
```

## 📝 Create Your Own Skill

```bash
npx skills@latest init my-custom-skill
```

Then use the `write-a-skill` or `skill-creator` skill to help you draft it.

---

## 📜 License

Individual skills retain their original licenses from their respective source repositories.
