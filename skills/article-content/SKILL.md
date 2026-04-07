---
name: article-content
description: When the user wants to write, generate, or create article body content—blog post body, long-form content, how-to guide, listicle. Also use when the user mentions "write article," "article content," "blog post content," "article body," "long-form content creation," "generate article," "article draft," "how-to guide content," "listicle content," "information gain," or "content density." For single post page structure, schema, and SEO metadata, use article-page-generator. For blog index/listing page, use blog-page-generator. For short ad, landing, or email copy, use copywriting.
metadata:
  version: 1.4.0
---

# Content: Article Content

Guides creation of **article body content**—the actual text (intro, body, conclusion) for blog posts, guides, and long-form pieces. Focus on **what to write**. For **where it goes** (page structure, schema, metadata), see **article-page-generator**. For short conversion copy (ads, landing pages, CTAs), see **copywriting**.

**When invoking**: On **first use**, if helpful, open with 1–2 sentences on what this skill covers and why it matters, then provide the main output. On **subsequent use** or when the user asks to skip, go directly to the main output.

## Author Voice (Derived from Published Articles)

These patterns are drawn directly from the author's published articles on Medium (Coffeed). Apply them whenever writing or editing content for this author. The articles analysed: ADEOS agentic architecture, Model Context Protocol, Codename Goose, Engineering Drawing Standards for AI.

---

### How the author opens articles

The author never opens with a dramatic hook or a provocative question. Instead, they open by describing the current state of something — a tool, a system, a workflow — in plain terms, then reveal what is missing or what breaks down.

**Pattern**: State what exists and how it works → show where it stops working → introduce the subject as the answer.

Examples from published articles:
- "Most document extraction systems are built as pipelines. A fixed sequence of steps runs on every document... This works when documents are clean, consistent, and predictable. Engineering drawings are none of those."
- "Whether it is building an app, doing some research with citations... we can only get responses one at a time from ChatGPT. You write a prompt, get a response, and then follow up manually."
- "Engineering drawings are a language of their own. Without a shared language, each designer, manufacturer, or engineer could interpret a drawing differently."

**Do not open with**: statistics, rhetorical questions, bold claims, dramatic one-liners, or "In today's world..."

---

### How the author introduces technical concepts

- **One definition sentence first, then expand.** Never assume the reader knows the term. Example: "Model Context Protocol (MCP) is an open standard that connects LLMs to your data sources. In simpler terms, MCP works on top of a client-server architecture."
- **Use a concrete example immediately after the definition.** The example is always specific: a named file, a named tool, a named action. Example: "Say you have an Excel file in your local system and you want to get insights out of it. Claude's MCP lets you configure the Claude Desktop to access your Excel file."
- **Name the real components.** Not "the system" — "the Layout Detection Agent", "the title block", "the BOM table". Not "the model" — "GPT-4o", "Claude Desktop", "Goose". Specificity is non-negotiable.
- **Fold technical qualifiers into the sentence naturally.** Example: "Unlike traditional LLMs like ChatGPT or Claude, Goose works with goals, not just prompts." — the comparison is inside the sentence, not added as a separate clause.

---

### How the author structures body sections

The author uses a **component-by-component** or **step-by-step** structure for technical articles, not essay-style argumentation. Each section covers one named thing and explains what it does.

**For agent/system articles (like ADEOS, Goose):**
Each component gets its own section with this internal pattern:
- What it perceives (input)
- What it reasons about (decision)
- What it does (action)
- What it learns over time (improvement)

This Perceive → Reason → Act → Learn pattern recurs across the ADEOS article and reflects how the author thinks about agentic systems.

**For standards/reference articles (like Engineering Drawing Standards):**
Each standard gets its own named section. Within each, the author lists what the standard defines and gives specific examples (e.g. actual measurements, actual column names, actual ratio formats). No section ends with a general takeaway — the detail itself is the takeaway.

**For how-to/tool articles (like Goose, MCP):**
The author walks through the tool in the order a user would encounter it: what it is, how to install or configure it, how to use it, what happens when you do. Screenshots and code blocks are included. Real prompts used by the author are quoted directly.

---

### Sentence and paragraph patterns

- **Paragraphs are 2–4 sentences.** One idea per paragraph. No paragraph serves as a transition filler.
- **Short declarative sentences land key points.** After a few explanatory sentences, the insight is compressed into one clean line. Example: "In this environment, a static pipeline breaks down." This is used for emphasis, not dramatic effect.
- **Contrast is folded into complete sentences.** Both the observation and the contrast are complete sentences — no fragments. Example: "This works when documents are clean, consistent, and predictable. Engineering drawings are none of those." — not "Engineering drawings? None of those."
- **No em dashes.** Rewrite as two sentences or use a comma.
- **No sentence fragments as beats.** Avoid: "And it works." / "That's it." / "Simple." / "Not anymore."
- **Lists are used only when enumerating real items** — steps, components, column names, feature names. Lists are not used to summarise prose arguments. When the author uses a list, each item is a real thing with a real name.
- **Technical terms are introduced once and then used consistently.** The term is not swapped for a synonym mid-article. "BOM table" stays "BOM table" throughout — not "parts list" later.

---

### Conclusion pattern

The author ends with one of two approaches, sometimes both:

1. **Zoom out to the bigger implication.** Restate what the tool or system enables in one or two sentences that are broader than the article's scope. Example: "Engineering document intelligence is not a data extraction problem. It is a decision problem."
2. **Open question to the reader.** Invite the reader to share their own use case. Example: "How would you use Goose to streamline your workflow?" or "What use cases are you putting MCP to? Let's discuss in the comments."

The conclusion does not summarise the article point by point. It does not start with "In conclusion" or "To summarise." It does not end with a strong call to action or a product pitch.

---

### Tone

- Practical and neutral. The writing explains without advising or preaching.
- The author writes as someone who has used the tool or built the system — not as someone who has read about it. This comes through in the specificity: real prompts, real file names, real UI labels.
- No hype language: not "game-changer", "revolutionary", "cutting-edge", "powerful", "exciting".
- No corporate filler: not "leverage", "robust", "seamless", "synergy", "transformative".
- No AI tell-tale phrases: not "delve into", "it's worth noting", "navigate", "foster", "underscore", "it is important to note".
- Advice language is avoided: not "you should", "make sure to", "best practice is to", "it is recommended".

---

### What makes this author's writing distinctive

Three things separate this author's writing from generic technical content:

1. **The limitation is always stated honestly.** Every article includes at least one place where the tool or system does not work well, or where the user needs to watch out. This is not buried — it is part of the main body.
2. **The author writes from use, not from documentation.** The examples are things the author has actually done: prompts they typed, files they processed, outputs they received. This makes the article feel like a practitioner's notes, not a product overview.
3. **Structure follows the subject, not a template.** Agent articles use Perceive → Reason → Act → Learn. Standards articles list each standard and its specifics. How-to articles follow the install → configure → use → result sequence. The structure changes based on what the content actually is.

---

### Examples — good and avoid

**Good (ADEOS article — opening):**
"Most document extraction systems are built as pipelines. A fixed sequence of steps runs on every document: preprocess, detect layout, run OCR, extract fields, export data. This works when documents are clean, consistent, and predictable. Engineering drawings are none of those."

**Good (MCP article — concept introduction):**
"Model Context Protocol (MCP) is an open standard that connects LLMs to your data sources. Say you have an Excel file in your local system and you want to get insights out of it. Claude's MCP lets you configure the Claude Desktop to access your Excel file."

**Good (Goose article — contrast sentence):**
"Unlike traditional LLMs like ChatGPT or Claude, Goose works with goals, not just prompts."

**Good (ADEOS article — conclusion):**
"Engineering document intelligence is not a data extraction problem. It is a decision problem."

**Avoid:**
- "This is a game-changer for teams looking to leverage AI capabilities."
- "It's worth noting that the pipeline has some limitations worth exploring."
- "In conclusion, Goose offers a robust and seamless agentic experience."
- "That's it." / "And it works." / "Simple as that." — fragments used as emphasis
- Opening with a statistic or rhetorical question the article has not yet earned

## Scope

- **Article body**: Introduction, body sections, conclusion, CTA
- **Content structure**: Hook, QAE pattern, paragraph length, scannability
- **Word count**: By article type and search intent
- **Writing frameworks**: AIDA, PAS, BAB applied to articles
- **GEO elements**: TL;DR, Key Takeaways, answer-first

## Article Types & Word Count (2025)

**Quality over length**: Google prioritizes comprehensive coverage of search intent, not word count. Match length to topic depth and intent.

| Type | Word count | Use case |
|------|------------|----------|
| **News / announcements** | 300–600 | Product updates, breaking news, FAQs |
| **Short-form** | 500–800 | Landing pages, product pages (scannable) |
| **Standard articles / how-tos** | 1,000–1,500 | Single topic; actionable; listicles |
| **Listicles** | 1,200–2,000 | "Top 10," "Best X"; numbered lists boost CTR ~70% |
| **Cluster articles** | 800–2,500 | Subtopic; links to pillar |
| **Pillar / cornerstone** | 2,000–3,500+ | Comprehensive; cluster hub; 6–12 sections |
| **Competitive keywords** | 1,800–2,500 | Page-one SEO posts avg ~2,400 words |

**Intent-based** (Google 2025): Validate 1,200–2,000; Explore 2,000–3,500; Compare 600–1,200; Do 900–1,500; Know 300–800. Informational ~40% longer than transactional.

**Avoid**: Under 300 words (thin); over 7,000 (often underperforms due to reduced focus).

## Content Creation Workflow

### Factual Accuracy and Technical Context

Before writing articles that reference a specific system, architecture, product, or technical implementation, **verify the details first**. Do not reconstruct how something works from a general description or idea brief alone.

- If the article idea includes a real-world example (e.g. "Delivery Hero uses two LLM calls"), **research the actual implementation** before writing. The idea brief may summarise or paraphrase incorrectly.
- Use web search to confirm: what the system does, how each component works, and what the correct technical terms are.
- Do not infer missing technical details from the surrounding narrative. If a step is unclear, look it up.
- When the idea brief conflicts with verified sources, follow the verified sources and note the discrepancy if useful.

**Why this matters**: A detail like "two LLM calls" could mean two separate models, a teacher-student fine-tuning setup, or a validation loop. Each leads to a different article. Getting it wrong undermines the credibility of everything around it.

### Four Inputs

Article content rests on **four inputs**. See **article-page-generator** for full workflow.

| Input | Purpose |
|-------|---------|
| **Product** | Connection, features, CTA placement |
| **Keywords** | Target keyword, primary/secondary |
| **Article intent** | Informational, commercial, transactional |
| **Competitor articles** | Structure to adopt, content gaps, length target |

### Information Gain (Content Density Over Word Count)

**Information gain** = net new information a page provides beyond what exists in top-ranking results. Google evaluates unique value, not comprehensiveness. Content density (unique entities, data points, insights per 100 words) matters more than word count. Skyscraper Technique (longer = better) no longer differentiates; AI made comprehensiveness cheap.

**Four sources of information gain**:
- **Counter-narratives**: Why "best practice" fails in certain contexts; evidence-backed
- **Temporal freshness**: Data or developments after competitors' content and LLM cutoff
- **SME perspectives**: Direct quotes, practitioner experience; not repackaged advice
- **Proprietary data**: Original surveys, internal benchmarks, user behavior patterns

**Avoid consensus content**: Restating common facts across top 10 results = zero information gain. Audit SERP before writing; list the "consensus layer"; identify gaps (unanswered questions, outdated data, underserved segments). Lead with what is new; structure answer-first.

**Density check**: Count unique data points, original insights, specific claims. If ratio of new information to word count is low, cut filler. High-density content (800-1,500 words with 3+ original points) often outperforms long rehashed guides.

### TL;DR or Key Takeaways (GEO)

Choose one; place after intro. Content with these elements is cited ~35% more by AI.

| Format | Spec |
|--------|------|
| **TL;DR** | 50–100 word bold summary paragraph |
| **Key Takeaways** | 5–7 bullet points |

See **generative-engine-optimization** for full GEO strategy.

### Introduction

**Length**: 40–120 words; 2–3 paragraphs. Readers decide in ~8 seconds; hook must work instantly.

| Element | Guideline |
|---------|-----------|
| **Hook** | First 1–2 sentences: pain point, stat, or question; curiosity gap; specific data or contrarian fact |
| **Primary keyword** | In first 100 words |
| **Expectations** | Set what reader will learn |

**Hook types**: "You're doing X wrong"; "97% of Y…"; bold question; challenge assumption. Well-crafted hooks boost CTR 30–50%.

### Body

| Element | Guideline |
|---------|-----------|
| **QAE pattern** | Question (H2) → Answer (2 sentences) → Evidence (data, examples, lists) |
| **Answer-first** | Direct answer in first 40–60 words after each H2 |
| **Answer blocks** | 100–200 words per section; direct answer + context + evidence |
| **Paragraph length** | 40–80 words; 2–4 sentences; avoid walls of text |
| **Break long blocks** | Lists, H3s, images, callout boxes every 2–3 paragraphs |
| **Scannability** | Front-load key info (F-pattern); **bold** key phrases; one idea per paragraph |

**Long-form (1,000+ words)**: Place engagement hooks every 500–600 words; mix 40–50% explanatory text, 20–25% examples, 10–15% data, 5–10% visuals.

### Conclusion

**Summary** + **CTA**: newsletter signup, related content, **product** (link to product/feature when relevant). Product-linked content ties to product naturally.

### Product Connection

Articles should tie to the product (problem it solves, features, use cases). Avoid purely generic content. Link to product/feature pages naturally in conclusion or when context fits.

## Writing Frameworks

Apply **copywriting** frameworks to article structure. See **copywriting** for full PAS, AIDA, BAB.

| Framework | Article use |
|-----------|-------------|
| **AIDA** | Intro (Attention); body (Interest, Desire); conclusion (Action/CTA) |
| **PAS** | How-to guides: Problem in intro; Agitation in body; Solution throughout |
| **BAB** | Case studies, transformation: Before → After → Bridge |

**Choose by audience**: AIDA for ready-to-buy; PAS for pain-driven; BAB for transformation seekers.

## Article Headlines

See **copywriting** for headline formulas (How to, Number, Problem→Solution). For article titles specifically:

- **Length**: 50–60 chars; see **title-tag**
- **Primary keyword** near start
- **Numbers** and power words boost CTR ~36%

## References & Citations

| Scenario | Practice |
|----------|----------|
| **Data or statistics** | Cite inline (e.g. "According to [Source](url), 72% of…") or in References section |
| **Expert quotes** | Attribute; link to source |
| **Reference section** | For 5+ citations; list at end before Related posts |
| **Format** | Inline links preferred; numbered refs [1], [2] for academic-style |

See **eeat-signals** for E-E-A-T, author bio, citations, YMYL.

## Content Quality

| Element | Guideline |
|---------|-----------|
| **Readability** | Grade 8–10 (Flesch-Kincaid); short sentences, clear language |
| **Depth** | Match type; comprehensive coverage over padding |
| **Originality** | Unique angle, data, examples; avoid thin or rehashed content |
| **Information gain** | What does this add that top 10 results don't? Counter-narrative, fresh data, SME quote, or proprietary insight |
| **E-E-A-T** | Author bio, citations, expert quotes — see **eeat-signals** |

### Read Time Targeting

When a target read time is specified (e.g. "3–4 min read"), use it to set word count before writing.

| Read time | Approximate word count |
|-----------|----------------------|
| 2–3 min | 500–750 words |
| 3–4 min | 750–1,000 words |
| 4–5 min | 1,000–1,250 words |
| 5–6 min | 1,250–1,500 words |

Average reading speed: ~250 words per minute. Count the draft after writing and trim or expand to fit the target range. Do not pad with restatements or add sections that repeat a prior point just to hit a word count.

### No Vague Sentences

Every sentence must carry a specific, concrete claim. Remove or rewrite sentences that gesture at a point without making one.

**Signs of a vague sentence**:
- It could apply to almost any topic without modification ("complexity compounds", "the math works against you", "trust is hard to build")
- It restates the previous sentence in different words
- It uses a consequence or outcome without explaining the mechanism ("and that makes it harder to scale")

**Fix**: Replace with a specific number, a named example, a concrete mechanism, or cut the sentence entirely.

| Vague | Specific |
|-------|----------|
| "Every step you add is another place the math works against you." | "A 20-step process with 95% per-step reliability succeeds only 36% of the time end-to-end." |
| "Failures become harder to debug." | "When a self-directing agent reroutes itself mid-task, reconstructing what it decided and why is a separate engineering problem." |
| "Trust in AI has changed." | "Trust in fully autonomous AI agents dropped from 43% to 27% in 12 months, per CIO survey data." |

## Content Audit Checklist

When auditing or optimizing article content:

| Dimension | Check |
|-----------|-------|
| **Hook** | Intro opens with pain point, stat, or question? |
| **Keyword in first 100 words** | Primary keyword present? |
| **QAE pattern** | H2s as questions? Answer-first (40–60 words) in each section? |
| **Word count** | Matches type? (300–600 news, 1,000–2,500 cluster, 2,500+ pillar) |
| **Read time** | If a target read time was given, does word count fall in range? |
| **Paragraph length** | 40–80 words per paragraph? No walls of text? |
| **Vague sentences** | Any sentence that could apply to any topic without modification? Cut or rewrite with a specific claim. |
| **Technical accuracy** | Any real-world system or implementation referenced? Verified against sources before writing? |
| **Product connection** | Ties to product? Natural links to features/pricing? |
| **CTA** | Placement (conclusion, mid-article); clarity; product link |
| **References** | Data/stats cited? Reference section for 5+ citations? |
| **Gaps** | What do top-ranking articles cover that this misses? |
| **Information gain** | At least one of: counter-narrative, fresh data, SME perspective, proprietary data? Or consensus rehash? |

See **competitor-research** for competitor analysis; **article-page-generator** for page structure and metadata.

## AI-Assisted Content

When content is AI-assisted: **human review** before publish; **verify facts** and add citations; **original insights** or data; avoid generic phrasing. See **eeat-signals** for E-E-A-T and AI content guidance.

## Output Format

- **Outline** (H2s with keyword placement)
- **TL;DR or Key Takeaways** (if SEO-driven)
- **Introduction** (hook + keyword)
- **Body** sections (QAE, answer-first)
- **Conclusion** (summary + CTA)
- **CTA copy** options

## Related Skills

- **article-page-generator**: Page structure, schema, metadata, layout; content goes here
- **copywriting**: Frameworks (PAS, AIDA, BAB); headline formulas; short conversion copy
- **content-marketing**: Article Orientations; content types
- **eeat-signals**: E-E-A-T; author bio; citations; citations format
- **keyword-research**: Keyword basis; search intent
- **competitor-research**: Content gaps; structure to adopt; SERP audit for information gain
- **content-optimization**: H2 keywords; Multimedia (tables, lists); keyword density
- **generative-engine-optimization**: GEO strategy; AI citation
