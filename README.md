# Horiseon Refactor
## Refactor Homework BCS
- Web address:
- GitHub:

---

**Goal:**
Refactor the Horiseon website to meet accessibility standards
Structure the HTML to follow a logical structure
Add accessible alt attributes to all images
Heading attributes fall in sequential order
Create concise descriptive title

---

- Updated Title
- Created Header Tag
- Section for Hero image, moved image from css to html (reverted)
- Converted all div tags to either section, aside, or footer
- Changed duplicate h2 tag to h4
- Condensed down CSS to use direct child tags
- Added alt image tags (kept decorative images blank)
- Fixed ID tag for search-engine-optimization
- Reordered CSS sheet to simplify future edits
- Added notes to css sheet

---

Current challenge:
- Nav bar creates a space between header and hero when reduced below 1034px (resolved)
![Nav bar pushing down hero](navbar.jpg)

Solution: 
- Reverted changes to hero section to be a background on the css instead of image on html
![Nav bar flows into background](navbarfix.jpg)