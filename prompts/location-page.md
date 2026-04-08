# Location Page Prompt Template

Use this prompt to generate geo-targeted landing pages for cities and towns across the Acadiana region and greater Louisiana.

---

## Prompt

```
Write a location-specific landing page for Ikerd Law Firm targeting [CITY, LOUISIANA].

Practice area focus: [PRACTICE AREA — e.g., Criminal Defense / Personal Injury / All Practice Areas]
Context: [ADDITIONAL INFORMATION — e.g., local court details, common case types in this area, distance from Lafayette]

Before writing, research and determine the best primary keyword and 3-5 secondary keywords for this location + practice area combination based on search intent and local competition. List the chosen keywords at the top of your output before the content.

Follow all rules in CLAUDE.md. Specifically:
- No contractions, no em dashes, no cliche phrases
- No outcome guarantees
- Professional and compassionate tone
- Verify all Louisiana statutes and legal information for accuracy
- Check for recent legislative amendments (especially those effective August 1, 2025) before writing
- Include all Mandatory Legal Elements from CLAUDE.md that apply to the practice area
- Complete the Pre-Publication Verification Checklist in CLAUDE.md before delivering

Location page guidelines:
- Lead with the specific city name and how Ikerd Law Firm serves that community
- Reference the local parish, courts, and relevant jurisdictional details for the target city
- Mention proximity to Lafayette and the firm's willingness to serve clients in this area
- Include locally relevant context (e.g., local highways for accident pages, local court processes)
- Do NOT duplicate content from other location pages — each page must have unique, city-specific content
- Avoid thin content. Provide substantive legal information relevant to residents of this city.

Deliver the following:
1. Full page content with proper H1/H2/H3 header structure
2. H1 format: "[Practice Area] Lawyer in [City], Louisiana" or similar natural variation
3. Louisiana-specific statutes, penalties, and legal processes relevant to the practice area
4. Meta title (under 60 characters) including city name and practice area
5. Meta description (150-160 characters with city name, primary keyword, and CTA)
6. Suggested alt text for any images referenced
7. JSON-LD LegalService schema markup with areaServed set to the target city
8. JSON-LD LocalBusiness (LegalService) schema for Ikerd Law Firm in Lafayette, LA (as defined in CLAUDE.md)
9. Internal links to related practice area pages on ikerdlaw.com
10. Google CID link in the contact/CTA section: https://www.google.com/maps?cid=5998055786498434610 (as a "View on Google Maps" hyperlink)
11. A clear call to action with contact information for Ikerd Law Firm
12. Include the standard disclaimer immediately after the H1 header and again at the end of the content
13. Completed Verification Report (per CLAUDE.md Verification Gate) appended at the end of the output file — every legal claim traced to its source statute and confirmed current

Save the output as: output/location-[city-slug]-[practice-area-slug].md
```

---

## Example Usage

```
Write a location-specific landing page for Ikerd Law Firm targeting Breaux Bridge, Louisiana.

Practice area focus: Criminal Defense
Context: Breaux Bridge is in St. Martin Parish, about 10 miles east of Lafayette. Many residents face charges in both St. Martin Parish and Lafayette Parish courts.

Follow all rules in CLAUDE.md...
```

---

## Suggested Target Cities (Acadiana Region)

- Breaux Bridge (St. Martin Parish)
- Scott (Lafayette Parish)
- Youngsville (Lafayette Parish)
- Broussard (Lafayette Parish)
- Carencro (Lafayette Parish)
- Crowley (Acadia Parish)
- Opelousas (St. Landry Parish)
- New Iberia (Iberia Parish)
- Abbeville (Vermilion Parish)
- Rayne (Acadia Parish)
- Eunice (St. Landry Parish / Acadia Parish)
- Ville Platte (Evangeline Parish)
- Jeanerette (Iberia Parish)
- Kaplan (Vermilion Parish)
