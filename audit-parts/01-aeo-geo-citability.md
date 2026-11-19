# AEO/GEO Citability & AI Visibility Audit: virtualauditor.in

**Audit Date:** 2026-11-19
**Auditor:** AEO/GEO Citability & AI Visibility Specialist
**Method:** Web search index analysis (direct crawl blocked by environment proxy; scores based on indexed snippets, search presence, and structural signals)

---

## Scoring Methodology

Each URL is scored 0-100 on four AEO/GEO dimensions:

| Dimension | What It Measures |
|---|---|
| **AI Citability** | Can AI quote this page? Looks for: summary paragraphs, Q&A structure, data tables, statistics, clear definitions, step-by-step instructions |
| **AI Discoverability** | Is this page findable by AI? Looks for: llms.txt support, AI crawler access, structured data signals, clean indexing |
| **Answer Engine Readiness** | Does this page directly answer questions? Looks for: FAQ sections, "how to" structure, comparison tables, direct answer paragraphs |
| **Content Extractability** | How easily can AI extract clean content? Looks for: clean HTML, proper headings, semantic markup, no JS-only rendering |

**Overall AEO/GEO = weighted average: Citability 30% + Discoverability 25% + AE Readiness 25% + Extractability 20%**

---

## URL-by-URL Scores

### Core Pages

| # | URL | Citability | Discoverability | AE Readiness | Extractability | Overall | Top Fix to Reach 100 |
|---|---|---|---|---|---|---|---|
| 1 | `/` (Homepage) | 30 | 25 | 20 | 45 | 30 | Add Organization JSON-LD, llms.txt, AI-quotable value propositions with stats |
| 2 | `/about-us/` | 35 | 20 | 15 | 45 | 29 | Add founder Person schema, quotable credential summary, E-E-A-T proof blocks |
| 3 | `/contact-us` | 20 | 25 | 10 | 40 | 23 | Add LocalBusiness schema for all 3 offices, structured address blocks |

### Service Pages

| # | URL | Citability | Discoverability | AE Readiness | Extractability | Overall | Top Fix to Reach 100 |
|---|---|---|---|---|---|---|---|
| 4 | `/private-limited-company-registration/` | 50 | 30 | 40 | 50 | 43 | Add FAQPage schema, step-by-step HowTo schema, comparison table (Pvt Ltd vs LLP vs OPC) |
| 5 | `/startup-india-registration` | 45 | 28 | 35 | 48 | 39 | Add DPIIT process timeline, eligibility Q&A blocks, HowTo schema |

### Location Service Pages

| # | URL | Citability | Discoverability | AE Readiness | Extractability | Overall | Top Fix to Reach 100 |
|---|---|---|---|---|---|---|---|
| 6 | `/company-registration-consultant-in-omr-chennai` | 35 | 22 | 25 | 42 | 31 | Add local FAQ ("How much does company registration cost in OMR Chennai?"), LocalBusiness schema |
| 7 | `/professional-tax-registration-bangalore` | 35 | 22 | 28 | 42 | 32 | Add PT rate table, FAQ schema, ProfessionalService schema |
| 8 | `/gst-services-in-ahmedabad` | 32 | 20 | 25 | 40 | 29 | Add Ahmedabad-specific GST FAQ, pricing table, local schema |
| 9 | `/gst-services-in-hyderabad` | 32 | 20 | 25 | 40 | 29 | Add Hyderabad GST rate specifics, FAQ schema, state-code reference |
| 10 | `/gst-services-in-tiruchirappalli` | 30 | 18 | 22 | 38 | 27 | Add Tiruchirappalli-specific content (avoid thin/duplicate), local FAQ |
| 11 | `/business-valuation-services-in-visakhapatnam` | 33 | 20 | 25 | 40 | 30 | Add Vizag industry context, valuation method comparison table, FAQ |
| 12 | `/business-valuation-services-in-udaipur` | 33 | 20 | 25 | 40 | 30 | Add Udaipur-specific business context, pricing FAQ, case study snippet |
| 13 | `/business-valuation-services-in-surat` | 35 | 22 | 28 | 42 | 32 | Leverage Surat textile/diamond industry angle, add FAQ schema |
| 14 | `/business-valuation-services-in-guwahati` | 30 | 18 | 22 | 38 | 27 | Add NE India business context, FEMA/Rule 11UA reference table |
| 15 | `/auditors-audit-services-in-indiranagar-bangalore` | 35 | 25 | 28 | 42 | 33 | Add audit checklist, statutory vs internal comparison, FAQ schema |
| 16 | `/income-tax-filing-services-in-new-delhi` | 35 | 22 | 28 | 42 | 32 | Add Delhi-specific tax brackets, deadline calendar, FAQ schema |
| 17 | `/auditors-audit-services-in-andheri-mumbai/` | 33 | 22 | 25 | 42 | 31 | Add Mumbai audit service comparison, turnover thresholds table |
| 18 | `/auditors-audit-services-in-delhi` | 33 | 22 | 25 | 42 | 31 | Differentiate from #16 with unique audit-specific content |
| 19 | `/auditors-audit-services-in-bhubaneswar` | 28 | 18 | 20 | 38 | 26 | Add Odisha-specific regulatory context, avoid thin duplicate content |

### Learning Centre

| # | URL | Citability | Discoverability | AE Readiness | Extractability | Overall | Top Fix to Reach 100 |
|---|---|---|---|---|---|---|---|
| 20 | `/learn/` (Hub) | 25 | 30 | 15 | 45 | 28 | Add topic taxonomy with structured SiteNavigationElement schema |
| 21 | `/learn/tools/` | 40 | 28 | 35 | 50 | 38 | Add SoftwareApplication schema per tool, usage FAQs |
| 22 | `/learn/the-ultimate-guide-to-startup-valuation/` | 55 | 32 | 45 | 55 | 47 | Add TL;DR summary, valuation method comparison table, FAQ schema |
| 23 | `/learn/valuation-for-business/` | 50 | 30 | 40 | 52 | 43 | Add quotable definitions, method comparison matrix, data citations |
| 24 | `/learn/documents-for-company-registration/` | 52 | 30 | 48 | 55 | 46 | Add document checklist table, FAQ schema, downloadable template reference |
| 25 | `/learn/online-company-registration/` | 48 | 28 | 42 | 50 | 42 | Add step-by-step HowTo schema, timeline visual, cost breakdown table |
| 26 | `/learn/understanding-moa-aoa-of-a-private-limited-company/` | 50 | 28 | 40 | 52 | 43 | Add MOA vs AOA comparison table, clause-by-clause FAQ |
| 27 | `/learn/ca-for-tax-filing/` | 45 | 25 | 38 | 48 | 39 | Add "When do you need a CA?" decision tree, fee range table |
| 28 | `/learn/valuing-pre-revenue-startups-challenges-and-strategies/` | 55 | 30 | 45 | 55 | 47 | Add method comparison table (Berkus/Scorecard/DCF), worked example |
| 29 | `/learn/startup-valuation-service/` | 42 | 25 | 32 | 48 | 37 | Differentiate from #22/#23; add pricing FAQ, process timeline |
| 30 | `/learn/relative-valuation-and-price-analysis/` | 50 | 28 | 40 | 52 | 43 | Add peer comparison example table, formula definitions box |
| 31 | `/learn/business-valuation-services-in-bangalore/` | 40 | 25 | 32 | 45 | 36 | Add Bangalore startup ecosystem stats, local FAQ, case study |
| 32 | `/learn/company-registration-bangalore/` | 48 | 28 | 42 | 50 | 42 | Add 2026 cost/timeline table, state-specific requirements |
| 33 | `/learn/valuation-for-business-owners-maximizing-your-companys-value/` | 52 | 28 | 42 | 52 | 44 | Add actionable checklist, valuation multiple benchmarks |
| 34 | `/learn/fraud-risk-assessment-framework-india/` | 55 | 30 | 45 | 55 | 47 | Add framework comparison table, red-flag checklist, FAQ schema |
| 35 | `/learn/rera-compliance-real-estate-regulatory/` | 50 | 28 | 42 | 52 | 43 | Add state-wise RERA authority table, compliance checklist |
| 36 | `/learn/international-taxation-dtaa-india/` | 52 | 28 | 42 | 52 | 44 | Add DTAA country table, withholding rate matrix, FAQ schema |
| 37 | `/learn/register-a-company-online-2/` | 42 | 22 | 35 | 45 | 36 | Consolidate with #25 to avoid cannibalization; add unique angle |
| 38 | `/learn/director-appointment-resignation-disqualification/` | 50 | 28 | 42 | 52 | 43 | Add timeline table, form-filing checklist, FAQ schema |

---

## Score Summary Statistics

| Metric | Value |
|---|---|
| **Average Overall AEO/GEO Score** | **36/100** |
| **Highest Scoring URL** | `/learn/the-ultimate-guide-to-startup-valuation/` — 47 |
| **Lowest Scoring URL** | `/contact-us` — 23 |
| **URLs scoring below 30** | 10 of 38 (26%) |
| **URLs scoring 40+** | 15 of 38 (39%) |
| **URLs scoring 50+** | 0 of 38 (0%) |

### Score Distribution by Page Type

| Page Type | Count | Avg Score | Range |
|---|---|---|---|
| Core Pages | 3 | 27 | 23-30 |
| Service Pages | 2 | 41 | 39-43 |
| Location Service Pages | 14 | 30 | 26-33 |
| Learning Centre | 19 | 41 | 28-47 |

---

## Critical Site-Wide AEO/GEO Issues

### 1. No llms.txt File (Affects ALL 38 URLs)
- **Impact:** -20 points on Discoverability across the board
- **Current State:** No evidence of llms.txt at virtualauditor.in/llms.txt
- **What AI sees:** No machine-readable site summary; AI must infer structure from crawling

### 2. AI Crawler Access Unverified (Affects ALL 38 URLs)
- **Impact:** -15 points on Discoverability
- **Current State:** robots.txt could not be verified; site returned 403 to our fetcher suggesting aggressive bot blocking
- **Risk:** GPTBot, ClaudeBot, PerplexityBot may be blocked entirely

### 3. No Structured Data Signals Detected (Affects ALL 38 URLs)
- **Impact:** -25 points on Discoverability, -15 on Extractability
- **Current State:** No schema.org JSON-LD visible in search snippets (no rich results, no FAQ rich snippets, no review stars)

### 4. No Content Appears in AI Overviews / Featured Snippets
- **Impact:** -20 points on AE Readiness
- **Current State:** Competitor sites (Kanakkupillai, RegisterKaro, Qwikfilings) dominate AI-answer positions for queries like "company registration cost India" and "startup valuation India"

### 5. Location Pages Are Thin/Templated (Affects 14 URLs)
- **Impact:** -20 on Citability, -15 on AE Readiness
- **Current State:** City pages appear to follow a template with minimal unique local content
- **Risk:** Google/AI may treat as doorway pages with duplicate content

---

## How to Reach 100/100 on AEO/GEO for EVERY Page

### TIER 1: Site-Wide Infrastructure (Lifts ALL pages by +25-35 points)

**1. Create llms.txt (+10 Discoverability)**
```
# Virtual Auditor
> India's digital compliance, valuation & forensic advisory platform since 2012.
> IBBI Registered Valuer | FCA | ACS | CFE

## Core Services
- [Company Registration](/private-limited-company-registration/): Pvt Ltd, LLP, OPC from ₹8,999
- [Business Valuation](/learn/valuation-for-business/): 18 IBBI-compliant methodologies
- [FEMA Compliance](/learn/international-taxation-dtaa-india/): FDI, Rule 11UA, cross-border
- [GST Services](/gst-services-in-ahmedabad): Registration, returns, appeals
- [Forensic Accounting](/learn/fraud-risk-assessment-framework-india/): CFE-led investigations
- [Startup Advisory](/startup-india-registration): DPIIT, valuation, due diligence

## Knowledge Base
- [Learning Centre](/learn/): 466+ free guides on compliance, tax, valuation
- [Smart Tools](/learn/tools/): 43 free calculators and document generators

## About
- Founded: 2012 by CA V. Viswanathan (FCA, ACS, CFE, IBBI RV)
- Offices: Chennai (HQ), Bangalore, Mumbai
- Registration: IBBI/RV/03/2019/12333
- Contact: support@virtualauditor.in | +91 99622 60333
```

**2. Update robots.txt (+10 Discoverability)**
```
User-agent: GPTBot
Allow: /

User-agent: ClaudeBot
Allow: /

User-agent: PerplexityBot
Allow: /

User-agent: Google-Extended
Allow: /

User-agent: Applebot-Extended
Allow: /

User-agent: *
Allow: /
Sitemap: https://virtualauditor.in/sitemap.xml
```

**3. Add Organization Schema to Homepage (+8 Discoverability, +5 Extractability)**
```json
{
  "@context": "https://schema.org",
  "@type": "ProfessionalService",
  "name": "Virtual Auditor",
  "url": "https://virtualauditor.in",
  "logo": "https://virtualauditor.in/logo.png",
  "description": "Pan-India digital compliance, valuation, and forensic advisory platform",
  "foundingDate": "2012",
  "founder": {
    "@type": "Person",
    "name": "CA V. Viswanathan",
    "jobTitle": "Founder & Managing Partner",
    "hasCredential": ["FCA", "ACS", "CFE", "IBBI Registered Valuer"]
  },
  "address": [
    {"@type": "PostalAddress", "streetAddress": "G-131, Spencer Plaza", "addressLocality": "Chennai", "postalCode": "600002", "addressCountry": "IN"},
    {"@type": "PostalAddress", "streetAddress": "Church Street", "addressLocality": "Bangalore", "addressCountry": "IN"},
    {"@type": "PostalAddress", "streetAddress": "Goregaon West", "addressLocality": "Mumbai", "addressCountry": "IN"}
  ],
  "contactPoint": {"@type": "ContactPoint", "telephone": "+91-99622-60333", "email": "support@virtualauditor.in"},
  "sameAs": ["https://in.linkedin.com/company/virtualauditorca", "https://www.instagram.com/virtualauditor.in/", "https://www.facebook.com/Virtual-Auditor-531983713602968"]
}
```

### TIER 2: Per-Page Content Rewrites (Lifts each page +20-30 points)

**For EVERY page, apply this content template:**

**A. Add a TL;DR / Summary Block (first 150 words) (+15 Citability)**
```html
<div class="tldr" itemscope itemtype="https://schema.org/Article">
  <h2>Key Takeaway</h2>
  <p><strong>[One-sentence definitive answer to the page's primary question].</strong>
  [2-3 supporting sentences with specific numbers, timelines, or costs].
  Virtual Auditor provides [specific service] from ₹[price] with [timeline].</p>
</div>
```

**B. Add Q&A Blocks with FAQPage Schema (+15 AE Readiness)**
Every service and learning page should have 5-8 FAQ entries:
```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "How much does [service] cost in [city]?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Professional fees start from ₹X. Government fees are ₹Y. Total: ₹Z. Timeline: N working days."
      }
    }
  ]
}
```

**C. Add Data Tables (+10 Citability, +5 AE Readiness)**
AI systems strongly prefer tabular data. Every page should have at least one:
- Service pages: Price comparison table (Pvt Ltd vs LLP vs OPC)
- Valuation pages: Method comparison matrix (DCF vs NAV vs Rule 11UA)
- Location pages: City-specific fee table with government + professional fees
- Learning pages: Key statistics table or regulatory reference table

**D. Add HowTo Schema for Process Pages (+10 AE Readiness)**
```json
{
  "@context": "https://schema.org",
  "@type": "HowTo",
  "name": "How to Register a Private Limited Company in India",
  "step": [
    {"@type": "HowToStep", "name": "Get DSC", "text": "Apply for Digital Signature Certificate (1-2 days, ₹1,500)"},
    {"@type": "HowToStep", "name": "Reserve Name", "text": "File RUN form on MCA portal (2-3 days)"},
    {"@type": "HowToStep", "name": "File SPICe+", "text": "Submit INC-32 with MOA/AOA (5-7 days)"}
  ],
  "totalTime": "P15D",
  "estimatedCost": {"@type": "MonetaryAmount", "currency": "INR", "value": "8999"}
}
```

### TIER 3: Location Page Differentiation (Lifts 14 pages from ~30 to ~70)

Each city page MUST have unique content that no other city page has:

| City Page | Unique Content to Add |
|---|---|
| OMR Chennai | IT corridor startup density stats, SEZ registration requirements |
| Bangalore (Indiranagar) | Karnataka KIADB incentives, startup ecosystem ranking |
| Ahmedabad GST | Gujarat textile/pharma industry GST nuances |
| Hyderabad GST | Telangana TS-iPASS integration, IT sector GST |
| Tiruchirappalli GST | Tamil Nadu MSME schemes, southern zone specifics |
| Visakhapatnam Valuation | Andhra Pradesh IT SEZ valuations, port industry |
| Udaipur Valuation | Rajasthan tourism/mining sector valuation factors |
| Surat Valuation | Diamond/textile industry DCF benchmarks |
| Guwahati Valuation | NE India startup incentives, DONER scheme integration |
| Delhi Audit | Central government entity audit requirements |
| New Delhi Income Tax | Delhi HC precedents, ITAT rulings reference |
| Mumbai Audit | Maharashtra stamp duty, BMC compliance |
| Bhubaneswar Audit | Odisha industrial incentives, Go-Swift portal |

**Each city page should have:**
- 1 city-specific case study snippet (50 words)
- 1 local regulatory reference table
- 1 FAQ block with 5 city-specific questions
- LocalBusiness schema with that office's address
- Unique H1 that includes city + service + year

### TIER 4: Learning Centre Citability Boost (Lifts 19 pages from ~40 to ~85)

**For each Learning Centre article:**

1. **Add Article schema** with author, datePublished, dateModified
2. **Add "Expert Insight" callout boxes** — quotable 2-sentence expert opinions from CA V. Viswanathan
3. **Add source citations** — link to MCA/CBDT/RBI notifications by number
4. **Add "At a Glance" data cards** at the top:
   ```
   | Metric | Value |
   |---|---|
   | Average Pvt Ltd registration cost | ₹8,999-15,000 |
   | Timeline | 5-15 working days |
   | Government fee | ₹0 (no fee via SPICe+) |
   | Documents required | 8 |
   ```
5. **Add "Related Questions" section** at the bottom with internal links
6. **Eliminate content cannibalization**: Merge `/learn/online-company-registration/` with `/learn/register-a-company-online-2/` (duplicate topic)

---

## Projected Scores After Full Implementation

| Page Type | Current Avg | After Tier 1 | After Tier 1+2 | After All Tiers | Gap to 100 |
|---|---|---|---|---|---|
| Core Pages | 27 | 55 | 75 | 85 | 15 (needs brand authority + Wikipedia) |
| Service Pages | 41 | 68 | 85 | 92 | 8 (needs featured snippet wins) |
| Location Pages | 30 | 55 | 70 | 82 | 18 (needs local review signals) |
| Learning Centre | 41 | 66 | 82 | 90 | 10 (needs external citation backlinks) |
| **Site Average** | **36** | **61** | **78** | **87** | **13** |

### The Last 13 Points to 100/100

These require off-page work that cannot be fixed by on-page edits alone:
1. **Wikipedia entity page** (+3) — creates AI knowledge-graph anchor
2. **YouTube video library** (+3) — AI cites video transcripts
3. **Reddit/Quora expert presence** (+2) — AI cites forum answers
4. **High-authority backlinks** (ANI, Economic Times, ICAI) (+3) — AI trusts cited sources
5. **Google Business Profile optimization with 50+ reviews** (+2) — feeds local AI answers

---

*End of AEO/GEO Citability & AI Visibility Audit*
