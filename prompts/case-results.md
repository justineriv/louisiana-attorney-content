# Case Results Prompt Template

Use this prompt to generate case results and testimonial content for Ikerd Law Firm. This content type is a strong E-E-A-T signal that demonstrates real experience and expertise.

---

## Important Legal and Ethical Notes

- **Never fabricate case results.** All results must be based on real outcomes provided by the attorney. If the attorney has not provided specific case details, this template should be used to create the page structure and framework only, with placeholders for the attorney to fill in.
- **Never guarantee similar outcomes.** Every case result must be accompanied by a disclaimer that past results do not guarantee future outcomes.
- **Protect client confidentiality.** Do not include client names or identifying details unless the client has given written consent. Use general descriptions (e.g., "a Lafayette resident" or "a local business owner").
- **Follow Louisiana Rules of Professional Conduct** regarding attorney advertising (Rules 7.1 through 7.5). All statements about results must be truthful and not misleading.

---

## Prompt

```
Write a case results page for Ikerd Law Firm (Lafayette, Louisiana).

Practice area: [PRACTICE AREA — Criminal Defense / Personal Injury / Medical Malpractice]
Case results provided by attorney: [LIST THE ACTUAL CASE OUTCOMES PROVIDED — e.g., "DWI charge reduced to reckless operation", "Settled car accident case for $X", etc. If none provided, create a framework/template page the attorney can populate.]

Context: [ADDITIONAL INFORMATION — e.g., specific types of cases to highlight, any client testimonials approved for use]

Follow all rules in CLAUDE.md. Specifically:
- No contractions, no em dashes, no cliche phrases
- No outcome guarantees — this is especially critical on case results pages
- Professional and compassionate tone
- Verify all Louisiana statutes and legal information for accuracy
- Include all Mandatory Legal Elements from CLAUDE.md that apply
- Complete the Pre-Publication Verification Checklist in CLAUDE.md before delivering

Case results page guidelines:
- Each result should include: practice area, brief situation description, the legal challenge, and the outcome achieved
- Do NOT include client names or identifying information unless explicitly approved
- Every case result must be followed by a disclaimer: "Past results do not guarantee future outcomes. Every case is unique."
- Include a prominent page-level disclaimer about results varying by case
- Frame results to demonstrate the firm's experience and approach, not to promise outcomes
- If no real case results are provided, create the page framework with clear placeholder sections marked [ATTORNEY TO PROVIDE] so the attorney knows exactly what to fill in

Deliver the following:
1. Full page content with proper H1/H2/H3 header structure
2. Meta title (under 60 characters)
3. Meta description (150-160 characters with primary keyword and CTA)
4. Suggested alt text for any images referenced
5. JSON-LD LegalService schema markup
6. JSON-LD LocalBusiness (LegalService) schema for Ikerd Law Firm in Lafayette, LA (as defined in CLAUDE.md)
7. Internal links to related practice area pages on ikerdlaw.com
8. Google CID link in the contact/CTA section: https://www.google.com/maps?cid=5998055786498434610 (as a "View on Google Maps" hyperlink)
9. A clear call to action with contact information for Ikerd Law Firm
10. Include the standard disclaimer immediately after the H1 header and again at the end of the content
11. Include a results-specific disclaimer: "Past results do not guarantee future outcomes. Every case depends on its own facts and circumstances."
12. Completed Verification Report (per CLAUDE.md Verification Gate) appended at the end of the output file — every legal claim traced to its source statute and confirmed current

Save the output as: output/case-results-[practice-area-slug].md
```

---

## Example Usage

```
Write a case results page for Ikerd Law Firm (Lafayette, Louisiana).

Practice area: Criminal Defense
Case results provided by attorney:
- DWI first offense: charge reduced to reckless operation
- Felony drug possession: case dismissed after successful suppression motion
- Domestic violence charge: not guilty verdict at trial
- Probation violation: successfully argued against revocation, client continued probation with modified terms

Context: Highlight the variety of criminal defense work the firm handles. No client names.

Follow all rules in CLAUDE.md...
```
