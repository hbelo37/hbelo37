# Hey, I'm Harsh 👋

> **Turning noise into GTM signal** — Product Manager @ SMARTe

---

## 🧠 What I Do

I work at the intersection of **B2B data**, **AI tooling**, and **go-to-market intelligence**.

At [SMARTe](https://smarte.io), I own the app layer that transforms raw B2B data into actionable signals for sales and GTM teams. I've shipped billing systems, AI-powered features, and the core intelligence layer — and I prototype the things I spec.

---

## 🚀 Things I've Shipped

### 🤖 NLP → Filters Engine
Natural language → structured JSON filter arrays for B2B prospecting. Type like a human, get precision results.
- **Stack**: Python · Groq API (`llama-3.3-70b-versatile`) · FastAPI
- **V1 → V2**: Migrated from vector similarity (SentenceTransformer) to full schema injection for dramatically better accuracy
- **Details**: Per-filter confidence scoring (S2/S3 signals) · headcount range logic · keyword bleed detection · stop word filtering
- **Bonus**: Built a TOON format optimization achieving ~23–25% token reduction for stakeholder demos

---

### 🧩 Context Center (SMARTe AI Agent Platform)
Designed the intelligence configuration layer for SMARTe's AI-driven GTM outreach agents.
- Structured four-section architecture: Company Info · Products & Services · Competitive Intelligence · CRM Permissions
- Multi-product support: one company → multiple products, each with its own context profile
- Deliberate exclusion of ICP/Personas from context to maintain "context purity" in agent prompts
- Benchmarked competitor coverage across Apollo, ZoomInfo, Clay, Cognism, and Lusha

---

### 🕷️ Domain Intelligence Scraper
Standalone scraper that extracts up to 15 company intelligence fields from any domain.
- **Stack**: Python · `httpx` · `BeautifulSoup4` · Groq LLM API · `python-dotenv`
- **Extracts**: LinkedIn/social URLs · ICP · tech partnerships · pain points · value proposition · and more
- Free-tier LLM pipeline — no paid APIs needed

---

### 💳 Usage-Based Billing & Credit System
Built the pricing and billing layer for SMARTe's LLM-powered features.
- Designed the credit system architecture for metered AI feature usage
- Led the transition from flat pricing to usage-based pricing
- Standardized billing across product lines and launched Website Visitors feature

---

### 📊 Account Scoring API
REST API that scores companies against an ideal customer profile.
- **Endpoint**: `/score` — takes company domains + ICP parameters, returns fit scores
- Used internally for GTM prioritization workflows

---

### 🥗 DietX
Meal planning web app — because eating well shouldn't require a spreadsheet.
- **Stack**: Vite + React · Groq SDK · Vercel
- **Live**: [diet-x-ashy.vercel.app](https://diet-x-ashy.vercel.app/)
- **Recent**: Shipped meal swap with browser-side LLM calls via Groq SDK (`dangerouslyAllowBrowser`)

---

### 📡 gtm-signals *(WIP)*
Open-source GTM agent that aggregates buying intent signals from free sources.
- **Stack**: Next.js · FastAPI · LangGraph
- **Design**: Pluggable LLM providers (Ollama, Groq, Claude, OpenAI via BYOK)
- Intent: make signal aggregation accessible without expensive intent data subscriptions

---

## 🧰 Tech I Work With

**Languages & Frameworks**
`Python` `JavaScript` `React` `Vite` `Next.js` `FastAPI`

**AI / LLM**
`Groq API` `Anthropic Claude` `LangGraph` `llama-3.3-70b` `Prompt Engineering` `Structured Outputs`

**Data & Scraping**
`httpx` `BeautifulSoup4` `SentenceTransformer`

**Tools & Platforms**
`Vercel` `Git` `n8n` `Figma`

---

## 💡 What Drives Me

```
GTM Intelligence       ████████████████████  Making sales data actually useful
LLM / AI Tooling       ██████████████████░░  Structured outputs, agents, pipelines
Product Craft          ████████████████░░░░  Spec it, build it, ship it
Open Source            ██████████░░░░░░░░░░  Tools that GTM teams can self-host
```

---

## 📌 A Few Things About Me

- 🏗️ PM by title, builder by habit — I prototype the things I spec
- 🎯 Obsessed with converting messy B2B data into usable, actionable signal
- 🤖 Deep in LLM tooling — especially structured output reliability and agent context design
- 📍 Based in Maharashtra, India

---

## 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harsh-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/)

---

*Last updated: April 2026*
