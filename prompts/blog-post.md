# Blog Post Prompt Template

Use this prompt to generate a blog post for Ikerd Law Firm.

---

## Output Format

Every blog post output must follow this two-part structure:

### Part 1 — Content

The full article, delivered in this order:

1. **Keywords** — Primary keyword and 3-5 secondary keywords listed at the top
2. **Meta title** (under 60 characters)
3. **Meta description** (150-160 characters with primary keyword and CTA)
4. **H1 title**
5. **Disclaimer** (immediately after H1)
6. **Article body** — Full content with proper H2/H3 header structure, internal links embedded naturally within the text
7. **FAQ section** — Always placed as the last section of the article body, before the closing CTA
8. **CTA and closing disclaimer**

### Part 2 — SEO

A clearly separated section at the end of the file, after the content:

1. **WordPress Tags** (5-8 tags relevant to the topic)
2. **WordPress Category** (1-2 categories)
3. **Image Alt Text Suggestions** — Descriptive, keyword-relevant alt text for all images referenced in the content
4. **Schema Markup:**
   - JSON-LD Article schema
   - JSON-LD FAQPage schema for the FAQ section
   - JSON-LD LocalBusiness (LegalService) schema for Ikerd Law Firm in Lafayette, LA (as defined in CLAUDE.md)
5. **Google CID Link:** https://www.google.com/maps?cid=5998055786498434610 (for the contact/CTA section, as a "View on Google Maps" hyperlink)
6. **Verification Report** (per CLAUDE.md Verification Gate) — every legal claim traced to its source statute and confirmed current

---

## Prompt

```
Write a blog post for Ikerd Law Firm (Lafayette, Louisiana) about [TOPIC].

Context: [ADDITIONAL INFORMATION ABOUT THE TOPIC - e.g., recent law changes, specific angles to cover, client notes, or relevant details]
Word count: [1800-2000 or specify]

Before writing, research and determine the best primary keyword and 3-5 secondary keywords for this topic based on search intent, relevance to Lafayette, Louisiana, and the practice area.

Follow all rules in CLAUDE.md. Specifically:
- No contractions, no em dashes, no cliche phrases
- No outcome guarantees
- Professional and compassionate tone
- Verify all Louisiana statutes and legal information for accuracy
- Check for recent legislative amendments (especially those effective August 1, 2025) before writing
- Target Lafayette, Louisiana for local SEO
- For medical malpractice topics: MUST include the $500,000 damages cap (La. R.S. 40:1231.2), the PCF future medical care exception, the Medical Review Panel requirement (three licensed health care providers, not "physicians"), the prescriptive period, and the expanded LMMA scope (Act 342, effective August 1, 2025)
- For personal injury topics: MUST include the prescriptive period (La. C.C. Art. 3492), comparative fault (La. C.C. Art. 2323), and relevant damages categories
- For criminal defense topics: MUST include accurate statutory citations, current penalty ranges, and any recent legislative amendments
- Complete the Pre-Publication Verification Checklist in CLAUDE.md before delivering

Use the output format defined in this template:
- Part 1 (Content): Keywords, meta title, meta description, H1, disclaimer, article body with internal links inline, FAQ section last, closing CTA and disclaimer
- Part 2 (SEO): WordPress tags (5-8), category (1-2), image alt suggestions, all schema markup (Article, FAQPage, LocalBusiness), Google CID link, Verification Report
```

---

## Example Usage

```
Write a blog post for Ikerd Law Firm (Lafayette, Louisiana) about what to do after being charged with a DWI in Louisiana.

Context: Louisiana recently updated DWI penalties for repeat offenders. Focus on what someone should do in the first 24-48 hours after an arrest.
Word count: 1800

Follow all rules in CLAUDE.md...
```

---

## Example Output Structure

```markdown
## Keywords
- Primary: [keyword]
- Secondary: [keyword], [keyword], [keyword]

## Meta Title
[Under 60 characters]

## Meta Description
[150-160 characters]

---

# [H1 Title]

**Disclaimer:** This content is for informational purposes only and does not constitute legal advice...

[Article body with H2/H3 sections, internal links woven into the text naturally]

## Frequently Asked Questions

### [Question 1]
[Answer]

### [Question 2]
[Answer]

...

## Contact Ikerd Law Firm Today

[Closing CTA with contact info]

**Disclaimer:** This content is for informational purposes only...

---
---

# SEO

## WordPress Tags
1. [tag]
2. [tag]
3. [tag]
4. [tag]
5. [tag]

## WordPress Category
1. [category]

## Image Alt Text Suggestions
- Image 1: [descriptive alt text]
- Image 2: [descriptive alt text]

## Schema Markup

### Article Schema
{JSON-LD}

### FAQPage Schema
{JSON-LD}

### LocalBusiness Schema
{JSON-LD}

## Google CID Link
https://www.google.com/maps?cid=5998055786498434610
Use as: [View on Google Maps](https://www.google.com/maps?cid=5998055786498434610)

---

## VERIFICATION REPORT
[Per CLAUDE.md Verification Gate format]
```
