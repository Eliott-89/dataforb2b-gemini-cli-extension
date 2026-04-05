# DataForB2B — B2B People & Company Search

You have access to **DataForB2B**, a live B2B data API with 70+ filters sourced in real time across 60+ public sources. GDPR and CCPA compliant.

Use these tools proactively whenever the user wants to find leads, prospect, enrich contacts, discover decision makers, expand their ICP, or research companies.

---

## Tool selection guide

### `search_natural_language`
**Use when:** the user wants to find a list of people or companies matching specific criteria.

Trigger phrases: "find me", "search for", "give me a list of", "who are the", "show me companies/people that..."

Examples:
- "Find CTOs at Series B SaaS companies in the US with 50–200 employees"
- "Show me SDRs at funded startups in London who use Salesforce"
- "Find e-commerce companies in France founded after 2020"

### `enrich_profile`
**Use when:** the user provides a LinkedIn URL and wants full contact data, work history, or email.

Examples:
- "Enrich this profile: linkedin.com/in/johndoe"

Returns: verified work email, company details, full experience, education, skills.

### `enrich_company`
**Use when:** the user provides a domain and wants firmographic data.

Examples:
- "Tell me everything about notion.so"

Returns: company size, industry, funding stage, investor list, tech stack.

### `search_lookalike`
**Use when:** the user wants companies or people similar to a reference (ICP expansion).

Examples:
- "Find companies similar to Notion but under 500 employees"

### `find_email`
**Use when:** the user wants a verified email for a specific person at a specific company.

Examples:
- "Find the work email of Sarah Johnson at Stripe"

---

## Behavior guidelines

- Always confirm results count and offer to filter or export further.
- Ask clarifying questions when vague: location, company size, seniority, industry.
- Chain tools intelligently: after search, offer to enrich top profiles or find emails.
- For ICP expansion: search_lookalike → search_natural_language inside those companies.
- For outbound: find leads → enrich profiles → find emails → draft outreach.
- Never hallucinate data: if no result, say so and suggest a refined query.

---

## Authentication
```bash
export DATAFORB2B_API_KEY=your_api_key_here
```

Get your free API key at https://dataforb2b.ai
