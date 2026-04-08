# Louisiana Attorney Content - Ikerd Law Firm

Reusable rules and prompt templates for creating legal content for **Ikerd Law Firm** (Lafayette, Louisiana), focusing on **criminal defense** and **personal injury** practice areas.

## How to Use

1. **CLAUDE.md** contains all writing rules, tone guidelines, SEO requirements, accuracy standards, and the mandatory **Verification Gate**. This file is automatically loaded when using Claude Code in this repository.
2. **prompts/** contains ready-to-use prompt templates for different content types. Copy a template, fill in the bracketed placeholders, and use it to generate content.
3. **All generated content includes a Verification Report** — legal claims are traced to source statutes and confirmed current before delivery. See [Verification Gate](#verification-gate) below.

## Prompt Templates

| Template | Use For |
|----------|---------|
| [Batch Content](prompts/batch-content.md) | **Multiple pieces in one go (recommended)** |
| [Blog Post](prompts/blog-post.md) | Single blog article (1800-2000 words) |
| [Service Page](prompts/service-page.md) | Single practice area page |
| [FAQ Page](prompts/faq-page.md) | Single FAQ section |
| [Location Page](prompts/location-page.md) | Geo-targeted page for Acadiana cities |
| [Case Results](prompts/case-results.md) | Case outcomes and testimonials (E-E-A-T) |
| [Attorney Bio](prompts/attorney-bio.md) | Attorney biography page (E-E-A-T) |
| [Social Media](prompts/social-media.md) | Single social media post |

## Verification Gate

**All content produced in this repository is legally sensitive.** The client is a practicing attorney. False or outdated legal claims can result in lawsuits, bar complaints, and reputational harm.

Every piece of content automatically includes a **Verification Report** before delivery:
- Every legal claim is traced to a specific statute or source
- Every statute citation is confirmed current against Louisiana law
- Mandatory legal elements (damages caps, prescriptive periods, panel composition, etc.) are checked for inclusion
- Items that cannot be verified are flagged for human review
- Content with a **FAIL** verdict is not delivered until flagged items are resolved

This is not optional. It is not a separate step. It happens automatically as part of every content generation workflow. See the full Verification Gate rules in [CLAUDE.md](CLAUDE.md).

## Key Rules (Summary)

- No contractions, no em dashes, no cliche phrases
- No guarantees of legal outcomes
- Professional and compassionate tone
- All legal information must be verified for accuracy before delivery
- All content optimized for SEO, AI Overview, and schema markup
- Target location: Lafayette, Louisiana
- Disclaimer required immediately after the H1 header and at the end of every piece of content

See [CLAUDE.md](CLAUDE.md) for the complete ruleset.
