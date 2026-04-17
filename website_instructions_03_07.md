# Carly Miller — Personal Website Instructions for Claude Code

## How to use this file
Upload this file to Claude Code and say:
> "Build me a personal website using the instructions and content in this file."

To make changes later, update the relevant section below and say:
> "Update my website based on the revised instructions file."

---

## 1. DESIGN REFERENCE

Model the overall layout and aesthetic after a hybrid of:
- https://withad.am/ (bold stacked hero type, full-viewport layout, scroll animations)
- https://www.shelbygrossman.com/ (academic tone, clean publication lists, structured sections)

Key design qualities to match:
- Clean, minimal academic style
- Serif font for headings, sans-serif for body text
- Horizontal top nav with name on left, links on right
- Single-column centered layout, max ~720px wide
- Sections separated by thin horizontal rules
- Dark editorial palette (near-black background, warm off-white text, slate blue accents)

---

## 2. DESIGN CUSTOMIZATIONS
> Edit this section to change the look of your site

- **Background color:** Near-black (#0e0e0e)
- **Text color:** Warm off-white (#f0ece4)
- **Accent / nav color:** Slate blue (#7a9fc2)
- **Display/heading font:** DM Serif Display (serif) — from Google Fonts
- **Body font:** DM Sans (sans-serif) — from Google Fonts
- **Italic accent font:** Instrument Serif — from Google Fonts
- **Section header font:** Space Grotesk 700 — from Google Fonts (used for About, Research, Investigations, Talks, Contact headers)
- **Max content width:** 720px, centered
- **Photo size:** 240px wide, 320px tall, positioned right side of hero section
- **Photo shape:** Slight border-radius (4px), no circle crop
- **Photo crop:** object-position center 15% (crops slightly below top to show face clearly)
- **Photo file:** img_website.jpeg (embedded as base64 in current mockup; use file reference when building with Claude Code)

### Secondary / meta text style (pub dates, talk dates, talk descriptions, tags, footer links)
- **Color:** Slate blue (#7a9fc2)
- **Font-weight:** 800
- **Font-size:** slightly larger than default (0.88rem–1rem depending on element)

### Navigation links
- **Font-size:** 0.95rem
- **Font-weight:** 700
- **Color:** Warm off-white (#f0ece4) — full brightness, not muted
- **Hover color:** Slate blue (#7a9fc2)

### Hero display text
- **Font-size:** clamp(2.4rem, 7.2vw, 7.2rem) — scales to fill full viewport width
- **Layout:** Full width, no max-width constraint on hero section

### Tags (e.g. "Influence Operations", "AI Safety Evals")
- **Color:** Slate blue (#7a9fc2)
- **Border:** 1px solid slate blue
- **Font-size:** 0.78rem

---

## 3. SITE STRUCTURE & NAVIGATION
> Edit to add, remove, or rename sections

Navigation links (in order):
1. About
2. Research
3. Investigations
4. Talks
5. Contact

---

## 4. CONTENT

### Hero / Intro
**Name:** Carly Miller

**Hero display text (stacked lines):**
Hi, I'm Carly — / I analyze harms, / design safeguards, and / measure what's / actually working.
*(slate blue italic accent on "what's actually working")*

**Hero sub-text (below display, larger white text):**
I'm focused on building technical solutions for high-stakes content moderation decisions. To do this, I investigate where enforcement breaks down into policy standards and frameworks. My background is with traditional social media platforms, and most recently, in developing methodologies for AI safety evaluations. My work has been cited by the New York Times Editorial Board and published in the Journal of Online Trust and Safety, Lawfare, and Brookings. 

**Photo:** [ADD PHOTO FILENAME HERE — e.g. photo.jpg]
> Place your photo file in the same folder as index.html

---

### About
Born and raised in the Bay Area. Outside of thinking about Trust and Safety, I enjoy all the classic Bay Area things — cycling, hiking, and trail running.

---

### Research & White Papers

- "Burden of Proof: Lessons Learned from Regulators from the Oversight Board's Implementation Work," Journal of Online Trust and Safety. (Feb 2024). [ADD PDF LINK]
- "Memes, Magnets and Microchips: Narrative Dynamics Around COVID-19 Vaccines," Virality Project. (April 2022). [ADD PDF LINK]
- "Playing Both Sides: Russian State Media Coverage of the #BlackLivesMatter Movement," The International Journal of Press/Politics. (Feb 2022).
- "Can Congress Mandate Meaningful Transparency for Tech Platforms?" TechStream. (June 2021).
- "Facebook, It's Time to Put the Rules in One Place," Lawfare. (March 2021).
- "The Long Fuse: Misinformation and the 2020 Election," Election Integrity Partnership, Policy Chapter Lead. (March 2021).
- "Telling China's Story: The Chinese Communist Party's Campaign to Shape Global Narratives," Stanford Internet Observatory. (July 2020). [ADD PDF LINK]

---

### Threat Investigation Reports

- "Staying Current: An Investigation into a Now-Suspended Facebook Network Promoting the Palestinian Democratic Reform Current." (Feb 2021). [ADD PDF LINK]
- "Hacked and Hoaxed: Tactics of an Iran-Linked Operation to Influence Black Lives Matter Narratives on Twitter." (Oct 2020). [ADD LINK]
- "Sockpuppets Spin COVID Yarns: An Analysis of PRC-Attributed June 2020 Twitter Takedown." (June 2020). [ADD PDF LINK]
- "Blame it on Iran, Qatar, and Turkey: An Analysis of a Twitter and Facebook Operation Linked to Egypt, the UAE, and Saudi Arabia." (April 2020). [ADD PDF LINK]
- "The World Is Swimming in a Sea of Rumors: Influence Operations Associated with El Fagr Newspaper (Egypt)." (April 2020). [ADD PDF LINK]
- "Analysis of Twitter Takedown of State-Backed Operation Attributed to Saudi Arabian Digital Marketing Firm Smaat." (Dec 2019). [ADD PDF LINK]

---

### Invited Talks

- **TrustCon** (July 2024) — "Burden of Proof: Lessons Learned from Regulators from the Oversight Board's Implementation Work." Presented key findings from our paper on tracking impact of Oversight Board recommendations.
- **RightsCon** (June 2021) — "Ballots, Bots, and BS: How to Restore Trust in American Elections." Spoke alongside Secretary of State Jocelyn Benson and Commissioner Thomas Hicks about misinformation during the 2020 US election.
- **Election Integrity Partnership** (March 2021) — "The Long Fuse: Misinformation and the 2020 Election." Presented key findings as lead of the policy chapter of the EIP report.
- **Hoover Institution** (July 2020) — "Telling China's Story: The Chinese Communist Party's Campaign to Shape Global Narratives." Presented to over 900 participants on the full spectrum of Chinese influence operations.
- **Stanford Cyber Policy Center** (Jan 2020) — "Monitoring Disinformation in Taiwan: Evidence from the Lead Up to the 2020 Election." Represented the Stanford Internet Observatory at CPC's seminar series.

---

### Contact / Footer
- **Location:** San Francisco, CA
- **Email:** [ADD YOUR DEDICATED GMAIL — do NOT use your Berkeley email or any primary personal email. Create a separate Gmail for public-facing contact, e.g. carlymiller.work@gmail.com]
- **Contact method:** Use a Formspree contact form (already built into the HTML) so your email is never exposed publicly. Sign up at formspree.io and replace YOUR_FORM_ID in the HTML with your actual form ID.
- **LinkedIn:** [ADD URL or leave blank]
- **CV:** [ADD PDF LINK or leave blank]

---

## 5. CHANGE LOG
> Keep a running log of changes you've asked Claude Code to make

| Date | Change Requested |
|------|-----------------|
| —         | Initial build                                          |
| Session 1 | Switched to dark background (#0e0e0e)                  |
| Session 1 | Added photo (img_website.jpeg) to hero section         |
| Session 1 | Changed accent color to slate blue (#7a9fc2)            |
| Session 1 | Adjusted photo crop to show face higher (center 15%)   |
| Session 1 | Adopted hybrid layout: Adam bold hero + Shelby lists   |
| Session 2 | Reverted hero display text back to original "a trust & safety practitioner focused on adversarial networks & AI safety" |
| Session 3 | Updated hero to: "I analyze harms, design safeguards, and measure what's actually working" |
| Session 3 | Added NYT Editorial Board citation to hero sub-text |
| Session 3 | Rewrote hero sub-text to reflect 6+ years, policy standards, AI safety pivot |
| Session 3 | Made hero sub-text larger (1.08rem) and white with slate blue left border |
| Session 4 | Hero display text made full viewport width (removed max-width, increased font clamp to 7.2vw) |
| Session 4 | Tags changed to slate blue (color + border) |
| Session 4 | All secondary/meta text (pub dates, talk dates, talk descriptions, footer links) changed to slate blue, font-weight 800, larger size |
| Session 4 | Section header font switched to Space Grotesk 700 for visible bold weight |
| Session 4 | Nav links made larger (0.95rem), bold (700), and full white for readability |


