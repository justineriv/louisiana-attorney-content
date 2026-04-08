# Attorney Bio Prompt Template

Use this prompt to generate attorney biography pages for Ikerd Law Firm. Attorney bio pages are a core E-E-A-T signal that establishes expertise, experience, authoritativeness, and trustworthiness.

---

## Prompt

```
Write an attorney biography page for Ikerd Law Firm (Lafayette, Louisiana).

Attorney name: [FULL NAME — e.g., Chad Ikerd]
Title/role: [e.g., Founder and Managing Attorney]
Practice area focus: [PRIMARY PRACTICE AREAS]
Background information provided: [LIST ALL DETAILS PROVIDED — education, bar admissions, years of experience, notable achievements, community involvement, professional memberships, etc. If details are not provided, create a framework with placeholders.]

Context: [ADDITIONAL INFORMATION — e.g., specific tone preferences, aspects of their career to emphasize, any quotes or personal statements from the attorney]

Follow all rules in CLAUDE.md. Specifically:
- No contractions, no em dashes, no cliche phrases
- No outcome guarantees
- Professional and compassionate tone
- Verify any legal credentials, bar memberships, or court admissions mentioned for accuracy
- Complete the Pre-Publication Verification Checklist in CLAUDE.md before delivering

Attorney bio guidelines:
- Write in third person
- Lead with the attorney's commitment to their clients and practice areas
- Include education, bar admissions, and professional credentials
- Mention years of experience and areas of focus
- Include community involvement and professional memberships if provided
- Humanize the attorney without being informal — show who they are beyond the courtroom
- Do NOT fabricate credentials, achievements, awards, or affiliations. If specific details were not provided, mark sections with [ATTORNEY TO PROVIDE] placeholders.
- Include a professional headshot alt text suggestion
- Reference the firm's location in Lafayette and service to the Acadiana community

Deliver the following:
1. Full page content with proper H1/H2/H3 header structure
2. H1 format: "[Attorney Name] — [Title] at Ikerd Law Firm"
3. Meta title (under 60 characters) including attorney name
4. Meta description (150-160 characters with attorney name, practice areas, and CTA)
5. Suggested alt text for attorney headshot
6. JSON-LD Person schema markup with attorney credentials
7. JSON-LD LocalBusiness (LegalService) schema for Ikerd Law Firm in Lafayette, LA (as defined in CLAUDE.md)
8. Internal links to related practice area pages on ikerdlaw.com
9. Google CID link in the contact/CTA section: https://www.google.com/maps?cid=5998055786498434610 (as a "View on Google Maps" hyperlink)
10. A clear call to action with contact information for Ikerd Law Firm
11. If any legal claims are made (e.g., referencing specific courts, bar admissions, or legal credentials), include a completed Verification Report (per CLAUDE.md Verification Gate)

Save the output as: output/bio-[attorney-name-slug].md
```

---

## Example Usage

```
Write an attorney biography page for Ikerd Law Firm (Lafayette, Louisiana).

Attorney name: Chad Ikerd
Title/role: Founder and Managing Attorney
Practice area focus: Criminal Defense, Personal Injury
Background information provided:
- Juris Doctor from [Law School — ATTORNEY TO PROVIDE]
- Licensed to practice in all Louisiana state courts
- [X] years of experience in criminal defense and personal injury
- Member of the Lafayette Bar Association
- Active in the Lafayette community

Context: Emphasize his dedication to defending the rights of everyday people in Lafayette and the Acadiana region. Approachable but authoritative tone.

Follow all rules in CLAUDE.md...
```
