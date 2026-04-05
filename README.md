# DataForB2B — Gemini CLI Extension

> The first B2B lead generation and people search extension for Gemini CLI. Find leads, enrich profiles, discover decision makers, and get verified emails — directly from your terminal.

---

## What is DataForB2B?

[DataForB2B](https://dataforb2b.ai) is a **live B2B data API** that gives you access to comprehensive people and company data with **60+ search filters**, sourced in real time across 20+ public data points (job boards, funding databases, company websites, press releases, and more).

Use cases:
- **Sales teams** — find and enrich high-quality leads that match your ICP
- **Recruiters** — source candidates by job title, skills, location, experience, and more
- **AI builders** — power your AI agents with real-time B2B data
- **Investors** — identify founders and companies with specific funding stages and track records

This Gemini CLI extension brings all of DataForB2B's capabilities directly into your terminal — no code required.

---

## Install

gemini extensions install https://github.com/Eliott-89/dataforb2b-gemini-cli-extension

Gemini CLI will open your browser to authenticate with your DataForB2B account. Sign in and click Authorize — that's it. No API key to manage. No config files to edit.

---

## Authentication

This extension uses OAuth 2.0. On first use:

1. Run the install command above or type /mcp auth dataforb2b inside Gemini CLI
2. Your browser opens on app.dataforb2b.ai/mcp/authorize
3. Click Authorize Access
4. Gemini CLI is now connected

Tokens are stored securely on your machine and refreshed automatically.

---

## Available Tools

### search_natural_language
Search for **people or companies** using plain English — no query syntax needed.

Examples:
- Find me CTOs at Series B SaaS companies in the US with 50-200 employees
- Find SDRs at funded startups in London who use Salesforce
- Show me e-commerce companies in France with 10-50 employees founded after 2018

Powered by 60+ filters: job title, skills, company size, location, funding stage, industry, years of experience, tech stack, GitHub, languages, certifications, and more.

### enrich_profile
Enrich any **professional profile URL** with verified contact data, full work history, skills, and education.

Example: Enrich this profile: https://dataforb2b.ai

Returns: verified work email, company details, full experience, education, skills, social links.

### enrich_company
Get detailed **company intelligence** from a domain or company URL.

Examples:
- Tell me everything about notion.so
- Enrich this company: https://dataforb2b.ai

Returns: company size, industry, funding stage, location, tech stack, description, and more.

### search_lookalike
Find **companies or people similar** to a given profile — perfect for ICP expansion.

Examples:
- Find companies similar to Notion
- Find people similar to this profile URL

### find_email
Find a **verified professional email** from a name and company.

Example: Find the work email of John Smith at Stripe

Returns verified email with 98% accuracy, sourced in real time.

---

## Example Prompts

- Find VP of Sales at B2B SaaS companies with 50-200 employees in the US
- Get me the decision makers at OpenAI — CEO, CTO, CRO
- Find funded startups in Paris in the AI space, less than 3 years old
- Enrich this profile and find their email: https://dataforb2b.ai
- Find 10 companies similar to Salesforce but smaller (under 500 employees)
- Who are the top recruiters at Google in the UK?

---

## Pricing

| Plan | Credits | Price |
|---|---|---|
| Starter | 3,000 / month | $49/month |
| Premium | 10,000 / month | $150/month |
| Pro | 40,000 / month | $450/month |
| Enterprise | Unlimited | Custom |

Start for free at https://dataforb2b.ai

---

## Compliance

- GDPR Compliant — full compliance with European data protection regulations
- CCPA Compliant — California Consumer Privacy Act standards
- Publicly available data — all data sourced ethically from public sources

---

## About DataForB2B

DataForB2B is a people and company search API built for sales, recruiting, and AI teams. One API for all B2B data — 60+ people filters, 50+ company filters, real-time enrichment, verified emails, and agentic search.

- Website: https://dataforb2b.ai
- LinkedIn: [https://www.linkedin.com/company/dataforb2b](https://www.linkedin.com/company/data-for-b2b/ )
- Contact: https://dataforb2b.ai/contact

---

## Related Keywords

b2b lead generation · people search api · company search api · contact enrichment · profile enrichment · sales prospecting · email finder · b2b data · lead enrichment · icp targeting · b2b prospecting tool · sales intelligence · recruiting api · decision maker search · gemini cli extension · mcp server
