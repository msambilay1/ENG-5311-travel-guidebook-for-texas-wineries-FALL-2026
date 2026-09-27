# Texas Hill Country Winery Travel Guidebook
## Accessibility & Universal Design Quality Checklist (WCAG 2.1 AA Aligned)

**Project Repository:** `ENG-5311-travel-guidebook-for-texas-wineries-FALL-2026`  

---

### **1. Structural Markup & Typographic Hierarchy**

- [ ] **True Structural Headings:** All section headings use explicit Markdown tags (`# H1`, `## H2`, `### H3`) or heading style application rather than manual bolding or size overrides, ensuring screen readers build an accurate document map.
- [ ] **Typographic Contrast Thresholds:** Headings and subheadings maintain at least a **2-point size difference** between levels to establish clear visual contrast rather than conflict.
- [ ] **Typeface Functionality:** Headings utilize a crisp **Sans-Serif font** (Epilogue, Roboto) for digital clarity, while body prose uses a highly legible **Serif font** (Times New Roman, Cambria).
- [ ] **Font Sizing Minimums:** Body text is set to a minimum of **10–12pt** across all formats; fine print below 10pt is strictly prohibited to prevent legibility barriers.
- [ ] **Line Spacing & Leading:** Paragraph leading is set comfortably (1.2–1.5 line spacing) with adequate paragraph spacing so ascenders and descenders do not overlap.
- [ ] **Proximity & Alignment:** Body paragraphs are **left-aligned** (never centered or fully justified) to maintain a clean reading margin. Headings are positioned noticeably closer to the text they introduce than to the preceding section.

---

### **2. Color Contrast & Spectrum Inclusion**

- [ ] **WCAG Contrast Ratios:** All body text meets or exceeds the **4.5:1 contrast ratio** against its background.
- [ ] **Colorblindness Avoidance:** Visuals, maps, and callout boxes avoid relying on **red-green or blue-yellow color pairs**.
- [ ] **Redundant Encoding:** Any color-coded information (such as price tiers, tasting room availability, or wine sweetness scales) is accompanied by explicit text labels, icons, or patterns.

---

### **3. Visual Assets, Maps & Image Accessibility**

- [ ] **Descriptive ALT Text:** Every visual asset uploaded to `Assets/Images` (vineyard photos, wine bottle labels, screenshots) and `Assets/Maps` includes a corresponding line in the image-captions.md file.
- [ ] **Functional Image Captions:** All figures feature a caption placed **directly beneath the image**.
- [ ] **Preceding Text Introduction:** Every photo, map, and diagram is explicitly introduced and discussed in prose *before* it appears on the page.
- [ ] **Source Attribution:** All borrowed maps, weather graphics, or promotional imagery include formal APA source citations in the figure caption.

---

### **4. Table Mechanics**

- [ ] **Numerical Alignment:** Numerical data (prices, tasting fees, hours) is **right-aligned or decimal-aligned**, while text descriptions are **left-aligned**.
- [ ] **Table Titles & Placement:** Table titles are placed **above the table**.

---

### **5. Navigation, Cognitive Load & Plain Language**

- [ ] **Task-Oriented Headings:** Headings use action-oriented phrasing (e.g., *"Planning Your Fredericksburg Tasting Tour"*) rather than static, function-oriented labels (e.g., *"Locations"*).
- [ ] **Group Accessibility Details:** Winery profiles explicitly detail ADA accessibility features (wheelchair ramps, accessible restrooms, paved walkways, seating, bus/van parking) to support group travel planning.
