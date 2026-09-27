# Texas Hill Country Winery Travel Guidebook
## Accessibility & Universal Design Quality Checklist (WCAG 2.1 AA Aligned)

**Project Repository:** `ENG-5311-travel-guidebook-for-texas-wineries-FALL-2026`  
**Target Deliverable:** All-in-One Travel Guidebook for Texas Hill Country Vineyards  
**Governance Framework:** WCAG 2.1 AA Standards, Section 508, Plain Writing Act of 2010, & Course Document Design Principles (CRAP)

---

### **1. Structural Markup & Typographic Hierarchy**
*Responsibility: Production/Layout Editor (Seth Huskey) & Writers*

- [ ] **True Structural Headings:** All section headings use explicit Markdown tags (`# H1`, `## H2`, `### H3`) rather than manual bolding or size overrides, ensuring screen readers build an accurate document map [159, 181-182].
- [ ] **Typographic Contrast Thresholds:** Headings and subheadings maintain at least a **4-point size difference** between levels (e.g., 20pt title, 16pt H1, 12pt body prose) to establish clear visual contrast rather than conflict [110, 121].
- [ ] **Typeface Functionality:** Headings utilize a crisp **Sans-Serif font** (e.g., Arial, Calibri) for digital clarity, while body prose uses a highly legible **Serif font** (e.g., Georgia) or clean sans-serif with a strong x-height [111, 312-313].
- [ ] **Font Sizing Minimums:** Body text is set to a minimum of **10–12pt** across all formats; fine print below 10pt is strictly prohibited to prevent legibility barriers [313].
- [ ] **Line Spacing & Leading:** Paragraph leading is set comfortably (1.2–1.5 line spacing) with adequate paragraph spacing so ascenders and descenders do not overlap [330, 338].
- [ ] **Proximity & Alignment:** Body paragraphs are **left-aligned** (never centered or fully justified) to maintain a clean reading margin [114, 122]. Headings are positioned noticeably closer to the text they introduce than to the preceding section [117].

---

### **2. Color Contrast & Spectrum Inclusion**
*Responsibility: Production/Layout Editor (Seth Huskey) & Research Asset Team*

- [ ] **WCAG Contrast Ratios:** All body text meets or exceeds the **4.5:1 contrast ratio** against its background (e.g., dark charcoal/black text on a light gray `#F8F9FA` or white background) [112, 128, 317-318].
- [ ] **Colorblindness Avoidance:** Visuals, maps, and callout boxes avoid relying on **red-green or blue-yellow color pairs**, ensuring status indicators and regional map keys remain distinct for colorblind readers [112, 128, 323].
- [ ] **Redundant Encoding:** Color is **never the sole carrier of meaning**. Any color-coded information (such as price tiers, tasting room availability, or wine sweetness scales) is accompanied by explicit text labels, icons, or patterns [127, 225].

---

### **3. Visual Assets, Maps & Image Accessibility**
*Responsibility: Wine Catalog Writer (Marcela Montoya) & Researcher (Burke De Boer)*

- [ ] **Descriptive ALT Text:** Every visual asset uploaded to `Assets/Images` (vineyard photos, wine bottle labels, screenshots) and `Assets/Maps` includes a corresponding `.alt.txt` file containing descriptive **Alternative Text** for screen readers [139, 175, 289].
- [ ] **Functional Image Captions:** All figures feature a numbered caption placed **directly beneath the image** (e.g., *Figure 1: Map of Fredericksburg Wine Road 290*) [75, 165].
- [ ] **Preceding Text Introduction:** Every photo, map, and diagram is explicitly introduced and discussed in prose *before* it appears on the page [68, 74, 88].
- [ ] **Image Borders & Framing:** Visual assets with light or white edges feature a subtle **1–2pt dark border** to prevent the graphic from bleeding into the background prose [291].
- [ ] **Source Attribution:** All borrowed maps, weather graphics, or promotional imagery include formal APA source citations in the figure caption [77, 87, 142].

---

### **4. Table Mechanics & Data Usability**
*Responsibility: Wine Catalog Writer (Marcela Montoya) & Destination Writer (Christine Devenny)*

- [ ] **No "Data Monsters":** Comparison tables (e.g., vineyard amenities, operating hours, pricing) are concise and focused, avoiding unwieldy spreadsheets [68].
- [ ] **Header-Level Units:** Measurement units (e.g., `$`, `mm`, `mi`, `% ABV`) are specified in column headers rather than repeated in every cell [69, 80].
- [ ] **Numerical Alignment:** Numerical data (prices, tasting fees, hours) is **right-aligned or decimal-aligned**, while text descriptions are **left-aligned** [69, 79].
- [ ] **Table Titles & Placement:** Table titles are placed **above the table**, numbered sequentially, and cross-referenced in running prose [67, 79].

---

### **5. Navigation, Cognitive Load & Plain Language**
*Responsibility: Destination Writer (Christine Devenny) & Repo Manager (Marielle Sambilay)*

- [ ] **Task-Oriented Headings:** Headings use action-oriented phrasing (e.g., *"Planning Your Fredericksburg Tasting Tour"*) rather than static, function-oriented labels (e.g., *"Locations"*) [136-137].
- [ ] **Progressive Disclosure:** Section introductions begin with a brief **Practitioner’s Takeaway or Summary Box** (100 words or less) before diving into detailed destination logistics [189, 212-214].
- [ ] **Scannable Parallel Lists:** Information items are formatted into vertical bulleted lists with parallel grammatical phrasing and complete lead-in sentences ending in colons [123-124].
- [ ] **Group Accessibility Details:** Winery profiles explicitly detail ADA accessibility features (wheelchair ramps, accessible restrooms, paved walkways, seating, bus/van parking) to support group travel planning [96, 168].

---

### **6. Repository & Docs-as-Code Quality Gates**
*Responsibility: GitHub Repository Manager (Marielle Sambilay)*

- [ ] **Clean Markdown Syntax:** All Markdown content passes linter checks without broken link syntax or missing image paths [184, 187].
- [ ] **Version Control Tracking:** Accessibility revisions and style updates are logged in the repository commit history and noted in the `Style Sheet` change log [233].
- [ ] **Cross-Platform Render Validation:** The guidebook layout is tested across desktop screens, mobile displays, and plain-text screen readers before merging into `Main` [280-281].
