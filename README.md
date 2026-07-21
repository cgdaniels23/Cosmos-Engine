# Cosmos Engine 🌌

A collection of original AI skills for people who don't code. Built on [Base44](https://base44.com). No setup, no technical knowledge, no configuration screens — just talk naturally and the skills handle the rest.

## What are these?

Each skill is a plain-English instruction set that powers an AI agent. You don't install apps, fill out forms, or remember commands. Just describe what you want in conversation:

- "Help me ask for a raise from $75k to $90k" → runs Salary Negotiation Coach
- "What do I text my match next?" → runs Dating App Wingman
- "Find all my subscriptions" → runs Subscription Audit
- "Fix my prompt: 'help me make my website better'" → runs Fix My Prompt
- "Help me decide between HubSpot, Pipedrive, and Salesforce" → runs Help Me Decide

Every skill is named after what people actually search for — not clever branding. Each skill surfaces one "holy shit" moment, recommends the next natural skill, and offers to share the result.

## Skills by Category

### 💰 Sales and Marketing Systems
**Sales Follow-Up** — Write follow up emails, set up follow up sequences, and track who's hot, who's warm, and who's going cold.
**Try it:** _"help me follow up with these 12 leads from my webinar"_
→ Chains to: Daily Focus

### 🤖 AI Agents for Real Work
**Meeting Notes** — Turn meeting chaos into clear action. Paste notes or transcript, get decisions, action items with owners and deadlines, open questions, and what was actually decided.
**Try it:** _"what did we decide? [paste meeting notes]"_
→ Chains to: Daily Focus

### ⚙️ Business Automation for Founders
**Daily Focus** — Plan your day in 2 minutes. Tell it what you're working on, what's blocking you, and what matters — it keeps you honest about what actually got done.
**Try it:** _"help me plan my day"_
→ Chains to: Meeting Notes

### 📝 Prompt Systems and Non-Technical AI Workflows
**Fix My Prompt** — Fix a fuzzy AI prompt and turn it into a clear one that actually gets you somewhere. Paste what you were about to ask ChatGPT, Claude, or any AI tool.
**Try it:** _"fix my prompt: 'help me make my website better'"_
→ Chains to: Prompt Templates

**Prompt Templates** — Create reusable prompt templates without learning a single technical concept. Describe what you want in plain English, get a structured template you can use over and over.
**Try it:** _"make me a prompt template for writing product descriptions"_
→ Chains to: Fix My Prompt

### 🏗️ Web Applications and Product Builds
**Scope My Idea** — Turn your app idea into a buildable spec. Features, priorities, what to build first, what to skip, and what the MVP actually looks like.
**Try it:** _"I want to build an app that connects dog owners with local dog walkers"_
→ Chains to: Sales Follow-Up

### 📊 Operator Dashboards and Decision Systems
**Help Me Decide** — Make hard decisions without second-guessing. Builds a weighted decision matrix that cuts through bias and analysis paralysis. For hiring, vendors, partnerships, even apartments.
**Try it:** _"help me decide between 3 job offers"_
→ Chains to: Scope My Idea

### 📢 Content, Traffic, and Skill Distribution
**Repurpose Content** — Take one piece of content and turn it into every format you need — Twitter thread, LinkedIn post, email newsletter, TikTok script, and more.
**Try it:** _"turn this blog post into a LinkedIn post and Twitter thread [paste text]"_
→ Chains to: Fix My Prompt

---

## 🔥 Flagship Skills

### 💰 Salary Negotiation Coach
Practice how to ask for a raise or negotiate a salary offer. Role-plays as your boss or hiring manager, coaches you through objections, researches market salary data, and gives you a script you can actually use.
**Try it:** _"help me ask for a raise from $75k to $90k"_
→ Chains to: Help Me Decide

### 💑 Dating App Wingman
Your dating app texting wingman. Paste a conversation and get advice on what to say next — works for any gender, any orientation, any app. Reads the vibe, spots red flags, helps you not blow it.
**Try it:** _"what do I text my match next? [paste conversation]"_
→ Chains to: Help Me Decide

### 💸 Subscription Audit
Find every subscription you're paying for, total the damage, and see what to cancel. Scans your email for recurring charges you forgot about. The "oh god I'm spending WHAT" moment, delivered.
**Try it:** _"find all my subscriptions"_
→ Chains to: Daily Focus

---

## Skill Chain Map

Every skill recommends the next one — creating a network effect where each skill is a discovery path to every other:

```
Fix My Prompt → Prompt Templates → Fix My Prompt
Meeting Notes → Daily Focus → Meeting Notes
Scope My Idea → Sales Follow-Up → Daily Focus
Help Me Decide → Scope My Idea
Repurpose Content → Fix My Prompt
Subscription Audit → Daily Focus
Salary Negotiation Coach → Help Me Decide
Dating App Wingman → Help Me Decide
```

## Getting Started

### Option 1: Clone the Superagent (easiest)
Get the template link from the author, click it, and you get your own AI agent with all skills pre-installed. Zero setup.

### Option 2: Upload skill files to your own agent
1. Download the skill folders from this repo
2. In your Base44 Superagent editor, go to Tools → Skills → Upload skill file
3. Upload any `.md` file and activate it

### Option 3: Copy the instructions
Each skill lives in its folder as a `SKILL.md` file — pure plain-English instructions. Copy any one into your AI agent's skills and it just works.

## Repository Structure

```
Cosmos-Engine/
├── README.md
├── LICENSE
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── skill-request.md
│   │   └── bug-report.md
│   └── workflows/
│       └── validate-skills.yml
├── skills/
│   ├── index.html
│   ├── sales-marketing-systems/
│   ├── ai-agents-for-real-work/
│   ├── business-automation-for-founders/
│   ├── prompt-systems/
│   ├── web-applications-product-builds/
│   ├── operator-dashboards/
│   └── content-traffic-skill-distribution/
├── salary-negotiation-coach/
│   └── SKILL.md
├── dating-app-wingman/
│   └── SKILL.md
├── subscription-audit/
│   └── SKILL.md
├── sales-follow-up/
│   └── SKILL.md
├── meeting-notes/
│   └── SKILL.md
├── daily-focus/
│   └── SKILL.md
├── prompt-templates/
│   └── SKILL.md
├── scope-my-idea/
│   └── SKILL.md
├── help-me-decide/
│   └── SKILL.md
├── repurpose-content/
│   └── SKILL.md
└── fix-my-prompt/
    └── SKILL.md
```

## About

Built by [Grant Daniels](https://github.com/cgdaniels23) using [Base44](https://base44.com). These are original skills — not derived from or based on any existing skill in the Base44 registry or third-party skill store.

## License

See the [LICENSE](LICENSE) file for details.
