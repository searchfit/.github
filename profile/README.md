<p align="center">
  <img src="logo.svg" alt="SearchFIT" width="200" />
</p>

# SearchFIT

**The AI-powered SEO & content platform that helps brands grow organic traffic, track AI visibility, and optimize their entire web presence.**

[SearchFIT](https://searchfit.ai) is a full-stack SEO platform that combines AI content generation, technical auditing, AI search tracking, and multi-channel publishing into a single workspace. It goes beyond content — it's an end-to-end system for modern search visibility.

---

## Platform Overview

### [AI Content Engine](https://searchfit.ai)

- **Keyword-driven content generation** — Target specific keywords and topics with long-form, search-optimized articles
- **Batch generation at scale** — Produce dozens or hundreds of posts from a topic list or CSV
- **Content calendar** — Auto-generate 30 days of content with intelligent scheduling
- **Internal linking** — Automatic interlink detection and suggestion between pages
- **Featured image generation** — AI-generated images via Nano Banana or sourced from Unsplash
- **Writing profiles** — Custom writing style profiles to match your brand voice
- **Content versioning** — Full version history with diff tracking and rollback
- **Publish-ready output** — Structured headings, frontmatter metadata, and clean markdown/MDX

### [AI Visibility Tracking](https://searchfit.ai)

- **AI search monitoring** — Track how your brand is mentioned across ChatGPT, Claude, Perplexity, Gemini, and other AI providers
- **Visibility scoring** — Time-series visibility scores with trend analysis (powered by TimescaleDB)
- **Competitor analysis** — See who else gets mentioned alongside your brand in AI responses
- **Sentiment analysis** — Understand how AI models perceive and describe your brand
- **Share of voice** — Measure your brand's presence vs. competitors across AI providers
- **Market segment tracking** — Understand which segments and categories your brand appears in
- **AI-generated insights** — Automated strengths, opportunities, threats, and trend detection

### [Technical SEO Audit](https://searchfit.ai)

- **Full website crawl** — Crawl your entire site and build a page inventory with content analysis
- **Link graph analysis** — Map internal and external links, detect broken links and redirects
- **Asset optimization** — Analyze images, scripts, and resources for size, compression, and alt text
- **Issue detection** — Categorized issues by severity (SEO, performance, accessibility, content)
- **Scoring system** — Overall site health score with breakdowns per category
- **Historical snapshots** — Track audit scores over time to measure improvement

### [Google Search Console & Analytics](https://searchfit.ai)

- **GSC data sync** — Automatic daily ingestion of clicks, impressions, CTR, and position data
- **Query and page performance** — Filter by country, device, date range
- **Domain rating tracking** — Monitor DR/UR from multiple sources
- **Referring domain analysis** — Track backlink sources, domain ratings, and link status
- **Backlink inventory** — Full backlink tracking with doFollow/noFollow classification

### [Content Translation & Localization](https://searchfit.ai)

- **Multi-language content generation** — Generate content in multiple locales from a single source
- **Translation sync status** — Track which translations are synced, stale, or pending
- **Translation glossary** — Brand-specific term glossary with "do not translate" support
- **Content version tracking** — Keep source and translated versions in sync

### [Site Pages & Opportunities](https://searchfit.ai)

- **Page inventory** — Crawled index of all site pages with metadata, word count, and indexability
- **Optimization suggestions** — Per-page recommendations with impact scoring
- **Page refresh** — AI-powered content refresh for existing pages
- **Opportunity engine** — Aggregated opportunities from audits, AI tracking, GSC data, and Reddit scans

### [Reddit Intelligence](https://searchfit.ai)

- **Keyword generation** — AI-generated Reddit keywords relevant to your brand
- **Reddit scanning** — Monitor Reddit for brand mentions, competitor discussions, and topical threads
- **Opportunity extraction** — Turn Reddit signals into content and engagement opportunities

### [Media Library](https://searchfit.ai)

- **Asset management** — Upload, organize, and manage images and media with folder structure
- **Usage tracking** — See where each media asset is used across content and products
- **Storage monitoring** — Track storage usage per workspace and brand
- **CDN delivery** — Assets served via Cloudflare R2 with thumbnail generation

### [Publishing & Integrations](https://searchfit.ai)

- **WordPress plugin** — Official plugin on WordPress.org with full CRUD API, webhook support, and auto-publishing
- **Shopify integration** — Connect and sync content with Shopify stores
- **Webflow integration** — Publish content directly to Webflow
- **REST API** — Secure API with key-based auth for custom integrations
- **Embeddable widget** — Drop-in widget for any website

### [Workspace & Collaboration](https://searchfit.ai)

- **Multi-workspace** — Manage multiple organizations with separate billing
- **Multi-brand** — Run multiple brands/domains under one workspace
- **Role-based access** — Team permissions and workspace controls
- **Task management** — Built-in task system with tagging for SEO workflows
- **Activity logging** — Full audit trail of all platform actions
- **Notifications** — In-app notifications for scan completions, budget alerts, and team activity

### [Billing & Cost Management](https://searchfit.ai)

- **Credit system** — Pay-per-use credits for AI operations with transparent cost tracking
- **Usage dashboards** — Daily rollups of AI credits, API calls, and content generated
- **Budget controls** — Set monthly budgets with alert thresholds per workspace or brand
- **Stripe billing** — Subscription plans with monthly/yearly pricing

### [Reporting](https://searchfit.ai)

- **Public reports** — Shareable, unlockable SEO reports per domain
- **PDF export** — Generate and download branded PDF reports
- **Programmatic SEO pages** — Auto-generated company profiles and comparison pages

---

## Feature Comparison

### vs. Traditional SEO Tools (Ahrefs, Semrush, Moz)

| Capability | Ahrefs / Semrush | [SearchFIT](https://searchfit.ai) |
|---|---|---|
| Keyword research | Yes | Yes |
| Backlink analysis | Yes | Yes |
| Technical site audit | Yes | Yes |
| Rank tracking (Google) | Yes | Via GSC integration |
| AI content generation | No | Yes — full pipeline |
| AI visibility tracking | No | Yes — ChatGPT, Claude, Perplexity, Gemini |
| Content calendar & scheduling | No | Yes |
| Auto-publishing to CMS | No | Yes — WordPress, Shopify, Webflow |
| Content translation | No | Yes — multi-locale with glossary |
| Reddit monitoring | No | Yes — keyword scanning + opportunity extraction |
| Media asset management | No | Yes |
| Writing style profiles | No | Yes |
| Credit-based cost tracking | N/A | Yes — per-operation cost visibility |

### vs. AI Content Tools (Jasper, SurferSEO, Frase)

| Capability | Jasper / Surfer / Frase | [SearchFIT](https://searchfit.ai) |
|---|---|---|
| AI content generation | Yes | Yes |
| SEO content optimization | Yes | Yes |
| Technical site audit | No | Yes |
| AI search visibility tracking | No | Yes |
| Google Search Console integration | No | Yes |
| Backlink analysis | No | Yes |
| Auto-publish to WordPress/Shopify | Limited | Yes — full CRUD with official plugins |
| Batch content at scale (100s) | Limited | Yes |
| Reddit intelligence | No | Yes |
| Content translation pipeline | No | Yes |
| Full workspace/multi-brand | No | Yes |

### vs. AI Visibility Tools (Profound, Otterly, Peec)

| Capability | AI Visibility Tools | [SearchFIT](https://searchfit.ai) |
|---|---|---|
| AI mention tracking | Yes | Yes |
| Multi-provider monitoring | Yes | Yes — ChatGPT, Claude, Perplexity, Gemini |
| Competitor share of voice | Yes | Yes |
| Sentiment analysis | Some | Yes |
| Content generation | No | Yes — full SEO content pipeline |
| Technical SEO audit | No | Yes |
| GSC analytics | No | Yes |
| Publishing integrations | No | Yes |
| E-commerce SEO | No | Yes |
| All-in-one platform | No | Yes |

---

## Get Started

Visit [searchfit.ai](https://searchfit.ai) to start optimizing your search presence.

---

## Awesome AI SEO & Content

A curated list of resources across the AI SEO, content, and search visibility ecosystem.

### Concepts & Frameworks

- **Answer Engine Optimization (AEO)** — Optimizing content to appear in AI-generated answers (ChatGPT, Perplexity, Gemini)
- **Generative Engine Optimization (GEO)** — Academic framework for optimizing content for LLM-based search engines
- **E-E-A-T** — Google's Experience, Expertise, Authoritativeness, and Trustworthiness quality guidelines
- **Topical Authority** — Building depth and breadth of coverage on a subject to signal expertise to search engines
- **Semantic SEO** — Structuring content around entities and relationships rather than just keywords
- **Programmatic SEO** — Generating large volumes of targeted pages from structured data and templates
- **Search Intent Mapping** — Classifying queries as informational, navigational, transactional, or commercial
- **Content Velocity** — The rate at which quality content is published, a key factor in organic growth
- **Share of Voice (SOV)** — Measuring brand visibility as a percentage of total mentions in a category
- **RAG (Retrieval-Augmented Generation)** — Combining vector search with LLMs for grounded content generation

### Standards & Protocols

- [Schema.org](https://schema.org) — Structured data vocabulary used by Google, Bing, and AI search engines
- [OpenGraph Protocol](https://ogp.me) — Metadata standard for social sharing and rich previews
- [robots.txt](https://developers.google.com/search/docs/crawling-indexing/robots/intro) — Standard for controlling crawler access to your site
- [XML Sitemaps](https://sitemaps.org) — Protocol for informing search engines about crawlable pages
- [Hreflang](https://developers.google.com/search/docs/specialty/international/localized-versions) — Standard for specifying language and regional targeting
- [Core Web Vitals](https://web.dev/vitals/) — Google's metrics for page experience (LCP, INP, CLS)
- [MCP (Model Context Protocol)](https://modelcontextprotocol.io) — Open protocol for connecting AI models to external tools and data

### AI Models & APIs for Content

- [OpenAI API](https://platform.openai.com) — GPT-4o, o3, and GPT-4.1 for content generation and analysis
- [Anthropic Claude](https://anthropic.com) — Claude 4 family for long-form writing, analysis, and coding
- [Google Gemini](https://ai.google.dev) — Multimodal AI for content, images, and search integration
- [Perplexity API](https://docs.perplexity.ai) — AI search API with real-time web grounding
- [Cohere](https://cohere.com) — Enterprise NLP with RAG and reranking capabilities
- [Vercel AI SDK](https://sdk.vercel.ai) — Unified TypeScript SDK for building AI-powered applications
- [LangChain](https://langchain.com) — Framework for building LLM-powered applications and agents
- [LlamaIndex](https://llamaindex.ai) — Data framework for connecting LLMs to external data sources

### Open-Source Tools

- [Screaming Frog](https://screamingfrog.co.uk) — Website crawler for technical SEO audits
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/) — Google's open-source tool for page quality audits
- [Puppeteer](https://pptr.dev) — Headless Chrome for crawling and rendering JavaScript-heavy sites
- [Playwright](https://playwright.dev) — Cross-browser automation for testing and scraping
- [pgvector](https://github.com/pgvector/pgvector) — Open-source vector similarity search for PostgreSQL
- [TimescaleDB](https://timescale.com) — Time-series extension for PostgreSQL, useful for tracking metrics over time
- [Drizzle ORM](https://orm.drizzle.team) — TypeScript ORM for type-safe database operations
- [React Email](https://react.email) — Build emails with React components
- [MDX](https://mdxjs.com) — Markdown with JSX for interactive content publishing

### Data Sources & APIs

- [Google Search Console API](https://developers.google.com/webmaster-tools/v1/api_reference_index) — Query performance, indexing status, and crawl data
- [Google Trends API](https://trends.google.com) — Search interest data over time and by region
- [Reddit API](https://www.reddit.com/dev/api/) — Access posts, comments, and subreddit data for content intelligence
- [SerpAPI](https://serpapi.com) — Structured SERP data from Google, Bing, and other engines
- [DataForSEO](https://dataforseo.com) — SEO data APIs for keywords, SERPs, backlinks, and on-page analysis
- [Cloudflare R2](https://developers.cloudflare.com/r2/) — S3-compatible object storage with zero egress fees
- [Unsplash API](https://unsplash.com/developers) — Free high-resolution images for content

### Content Publishing Platforms

- [WordPress](https://wordpress.org) — Open-source CMS powering 40%+ of the web
- [Webflow](https://webflow.com) — Visual web design and CMS platform
- [Shopify](https://shopify.com) — E-commerce platform with blog and content capabilities
- [Ghost](https://ghost.org) — Open-source publishing platform for content creators
- [Next.js](https://nextjs.org) — React framework commonly used for content-heavy sites with SSG/SSR
- [Astro](https://astro.build) — Content-focused static site generator with island architecture
- [Contentful](https://contentful.com) — Headless CMS for omnichannel content delivery
- [Sanity](https://sanity.io) — Composable content platform with real-time collaboration

### Keyword Research & Search Intelligence

- [Google Search Console](https://search.google.com/search-console) — Free search performance data from Google
- [Google Trends](https://trends.google.com) — Search trend analysis and comparison
- [AnswerThePublic](https://answerthepublic.com) — Visual keyword research from autocomplete data
- [AlsoAsked](https://alsoasked.com) — People Also Asked question mapping
- [Exploding Topics](https://explodingtopics.com) — Trending topics before they peak
- [SparkToro](https://sparktoro.com) — Audience research and intelligence
- [Keyword Insights](https://keywordinsights.ai) — AI-powered keyword clustering and search intent classification

### Analytics & Monitoring

- [Google Analytics](https://analytics.google.com) — Web analytics for traffic, conversions, and user behavior
- [PostHog](https://posthog.com) — Open-source product analytics with session replay and feature flags
- [Plausible](https://plausible.io) — Privacy-friendly, lightweight web analytics
- [Hotjar](https://hotjar.com) — Heatmaps, recordings, and user feedback
- [Sentry](https://sentry.io) — Error tracking and performance monitoring
- [Fathom](https://usefathom.com) — Simple, privacy-first website analytics

### Background Jobs & Automation

- [Trigger.dev](https://trigger.dev) — Background job infrastructure for long-running AI and data tasks
- [Inngest](https://inngest.com) — Event-driven functions for background processing
- [Temporal](https://temporal.io) — Durable workflow orchestration for complex pipelines
- [n8n](https://n8n.io) — Open-source workflow automation with AI integrations
- [Make](https://make.com) — Visual automation platform connecting apps and APIs
- [Zapier](https://zapier.com) — No-code automation connecting 5,000+ apps

### Newsletters & Blogs

- [SEOFOMO](https://seofomo.co) — Weekly SEO newsletter by Aleyda Solis
- [Detailed.com](https://detailed.com) — SEO newsletter with niche site analysis
- [Search Engine Journal](https://searchenginejournal.com) — SEO news, guides, and how-tos
- [Search Engine Land](https://searchengineland.com) — Search marketing news and analysis
- [Ahrefs Blog](https://ahrefs.com/blog) — In-depth SEO tutorials and case studies
- [Backlinko](https://backlinko.com) — SEO training and link building strategies
- [Kevin Indig's Growth Memo](https://kevin-indig.com) — SEO and growth strategy newsletter
- [Marie Haynes](https://mariehaynes.com) — Google algorithm updates and E-E-A-T analysis
- [Eli Schwartz](https://elischwartz.co) — Product-led SEO insights
- [The AI Exchange](https://theaiexchange.com) — Newsletter covering AI tools and workflows

### Podcasts

- [Search Off the Record](https://developers.google.com/search/podcasts/search-off-the-record) — Google's official search podcast
- [Authority Hacker](https://authorityhacker.com/podcast/) — SEO and affiliate marketing strategies
- [Niche Pursuits](https://nichepursuits.com/podcast/) — Niche sites, SEO, and online business
- [SEO Rant](https://morrdy.com/podcast/) — Hot takes and debates on SEO topics
- [Latent Space](https://latent.space) — Technical AI podcast covering LLMs, agents, and infrastructure

### Communities

- [r/SEO](https://reddit.com/r/SEO) — Reddit community for SEO discussion
- [r/bigseo](https://reddit.com/r/bigseo) — Reddit community for advanced SEO professionals
- [Traffic Think Tank](https://trafficthinktank.com) — Premium community for SEO professionals
- [Superpath](https://superpath.co) — Community for content marketers
- [Women in Tech SEO](https://womenintechseo.com) — Community and conference for women in SEO

### Conferences & Events

- [BrightonSEO](https://brightonseo.com) — Largest dedicated SEO conference
- [MozCon](https://moz.com/mozcon) — Annual SEO and digital marketing conference
- [SearchLove](https://searchlove.distilled.net) — Search and content marketing conference
- [SMX (Search Marketing Expo)](https://searchmarketingexpo.com) — Conference on search marketing and PPC
- [AI Engineer Summit](https://ai.engineer) — Conference on building with AI, LLMs, and agents

### Research & Papers

- [Generative Engine Optimization (GEO)](https://arxiv.org/abs/2311.09735) — Princeton/Georgia Tech paper on optimizing for AI search
- [Retrieval-Augmented Generation (RAG)](https://arxiv.org/abs/2005.11401) — Foundational paper on combining retrieval with generation
- [Google Search Quality Evaluator Guidelines](https://guidelines.raterhub.com/) — Google's full quality rater handbook
- [Web Content Accessibility Guidelines (WCAG)](https://w3.org/WAI/standards-guidelines/wcag/) — Accessibility standards that impact SEO

---

## Get Started

Visit [searchfit.ai](https://searchfit.ai) to start optimizing your search presence.

---

<sub>Built by the team behind [PADISO](https://padiso.ai) and [CAPITALY](https://capitaly.ai).</sub>
