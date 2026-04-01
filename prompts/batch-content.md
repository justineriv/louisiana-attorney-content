# Batch Content Prompt Template

Use this prompt to generate multiple pieces of content for Ikerd Law Firm in one go.

---

## Prompt

```
Generate the following content for Ikerd Law Firm (Lafayette, Louisiana). Follow all rules in CLAUDE.md for every piece.

For each item below, automatically research and determine the best primary keyword and 3-5 secondary keywords. List the chosen keywords before each piece of content.

---

1. [CONTENT TYPE: blog / service page / FAQ / social media]
   Topic: [TOPIC]
   Context: [ADDITIONAL DETAILS, or leave blank]

2. [CONTENT TYPE: blog / service page / FAQ / social media]
   Topic: [TOPIC]
   Context: [ADDITIONAL DETAILS, or leave blank]

3. [CONTENT TYPE: blog / service page / FAQ / social media]
   Topic: [TOPIC]
   Context: [ADDITIONAL DETAILS, or leave blank]

(Add as many as needed)

---

For each piece, deliver:
- The full content with proper header structure
- Meta title (under 60 characters)
- Meta description (150-160 characters with primary keyword and CTA)
- Schema markup (Article, FAQPage, or LegalService as appropriate)
- Suggested alt text for any images
- Internal links to relevant ikerdlaw.com pages
- Standard disclaimer

Save each piece of content as a separate .md file in the output/ folder using this naming convention:
- Blogs: output/blog-[short-topic-slug].md
- Service Pages: output/service-[short-topic-slug].md
- FAQs: output/faq-[short-topic-slug].md
- Social Media: output/social-[short-topic-slug].md

Each .md file should contain everything for that piece: keywords, full content, meta title, meta description, schema markup, alt text suggestions, internal links, and disclaimer.
```

---

## Example Usage

```
Generate the following content for Ikerd Law Firm (Lafayette, Louisiana). Follow all rules in CLAUDE.md for every piece.

For each item below, automatically research and determine the best primary keyword and 3-5 secondary keywords. List the chosen keywords before each piece of content.

---

1. Blog
   Topic: What to do after being arrested for DWI in Louisiana
   Context: Focus on the first 48 hours after arrest

2. Blog
   Topic: Understanding drug possession charges in Louisiana
   Context: Cover the difference between misdemeanor and felony charges

3. FAQ
   Topic: Expungement in Louisiana
   Context: 10 questions, focus on eligibility and the process

4. Service Page
   Topic: Car accident injuries
   Context: Emphasize dealing with insurance companies and when to hire a lawyer

5. Social Media
   Topic: Know your rights during a traffic stop
   Context: Facebook post, keep it educational

---

Save each piece of content as a separate .md file in the output/ folder:
- output/blog-dwi-arrest-louisiana.md
- output/blog-drug-possession-charges.md
- output/faq-expungement-louisiana.md
- output/service-car-accident-injuries.md
- output/social-traffic-stop-rights.md
```
