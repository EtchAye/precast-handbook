# PRECAST Handbook Website

A professional medical handbook for health professionals involved in cancer surgery prehabilitation programs.

## Current Chapters

| Chapter | Title | File |
|---------|-------|------|
| 5 | Anaemia | `anaemia.html` |
| 6 | Diabetes | `diabetes.html` |
| 7 | Frailty | `frailty.html` |
| 8 | Nutritional Prehabilitation | `nutrition.html` |

## How to Add a New Chapter

### Step 1: Prepare your content
Write your chapter in Markdown format following the PRECAST chapter structure:
- Chapter Overview
- Learning Objectives
- Key Clinical Recommendations
- Numbered Sections (Introduction, Epidemiology, Screening, Investigations, Treatment, etc.)
- Clinical Decision Pathway
- Summary and Key Points
- References

### Step 2: Create a new HTML page
1. Copy `anaemia.html` or `diabetes.html` as your template
2. Rename it (e.g., `cardiac.html`, `respiratory.html`, `nutrition.html`)
3. Update the `<title>` tag and `<meta name="description">` tag
4. Change the chapter number in the header
5. Replace all content sections with your new chapter content
6. Update the navigation links at the top and bottom of the page

### Step 3: Update the Table of Contents (index.html)
1. Open `index.html`
2. Find the "Table of Contents" section
3. Add a new chapter card following the existing pattern
4. Update: chapter number, title, description, tags, and `href` link
5. Update the chapter count in the badge (e.g., "3 chapters available")

### Step 4: Update navigation in all chapter pages
Add a link to the new chapter in the sticky navigation bar of each existing chapter page.

### Step 5: Deploy
Re-deploy the `/precast_handbook_site/` folder to publish changes.

## File Naming Conventions
- Lowercase, hyphen-separated: `cardiac-optimisation.html`
- Chapter numbers are sequential: next chapter is **Chapter 9**
- Keep this README updated with the chapter list

## Chapter Colour Coding
- Chapter 5 (Anaemia): Teal (`teal-600` / `teal-700`)
- Chapter 6 (Diabetes): Navy (`navy-700` / `navy-800`)
- Chapter 7 (Frailty): Violet (`violet-700` / `violet-800`)
- Chapter 8 (Nutrition): Emerald (`emerald-700` / `emerald-800`)
- Future chapters: Use other professional colours (e.g., indigo, purple, slate)

## Source Content
All content is drawn from the [Prep-4-Cancer Surgery Toolkit](https://prep4cancersurgery.org.au/), developed by Peter MacCallum Cancer Centre in collaboration with Western & Central Melbourne Integrated Cancer Services (WCMICS).
