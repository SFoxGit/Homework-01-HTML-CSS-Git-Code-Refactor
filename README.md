# Horiseon Refactor
## Refactor BCS

**Author**

Shawn Fox

| [GitHub](https://github.com/SFoxGit) | [Email](sfoxss4@gmail.com) |

**Project Links:**

- Index displayed: [GitHub Pages](https://sfoxgit.github.io/horiseon_refactor/)
- GitHub: [SFoxGit](https://github.com/SFoxGit/horiseon_refactor)

---

**GitHub Cloning Instructions:**

- [Clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

**Optional Hosting Instructions**

- [Custom Domain For GitHub Pages](https://docs.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site)
- [DNS Basics for Google Cloud services](https://support.google.com/a/answer/48090?hl=en)

---

**Goal:**
- Refactor the Horiseon website to meet accessibility standards
- Structure the HTML to follow a logical structure
- Add accessible alt attributes to all images
- Heading attributes fall in sequential order
- Create concise descriptive title

---

**Summary of Actions:**
- Updated Title
- Created Header Tag
- ~~Section for Hero image, moved image from css to html~~ (reverted)
- Converted all div tags to either section, aside, or footer
- Changed duplicate h2 tag to h4
- Condensed down CSS to use direct child tags
- Added alt image tags 
- Fixed ID tag for search-engine-optimization
- Reordered CSS sheet to simplify future edits, CSS now flows the same as html
- Added notes to css sheet


---

**Challenge:**
- I attempted to move the hero image from the css to the html to then provide an alt tag for accessability
- Nav bar creates a space between header and hero when reduced below 1034px (resolved)

    ![Nav bar pushing down hero](assets/images/navbar.jpg)

**Solution:** 
- Moving the hero image was not necessary as it did not require an alt tag since it was not bringing value to those using accessability tools
- Reverted changes to hero section to be a background on the css instead of image on html

    ![Nav bar flows into background](assets/images/navbarfix.jpg)

---

**Challenge:**
- Is it better to change the default text color than to have 4 instances of white as the color selection?

**Solution:**
- Delete 4 lines of code to add 2 and 1 selector, I'm going to push a version with the white text commented out, then push a version with them fully deleted. I should have 3 versions at that point, one default black, one default white with manual white text commented out, and one default white without the 4 white text lines. 
- I believe the default white will be better for any kind of future changes to the site, as I assume any future additions would have a desired white text.

---

**Result:**
- Reduced CSS lines from 200 with no comments, down to 133 + 6 comment lines. 
- All goals achieved
- Site looks the same
- CSS cleaned up dramatically
- Improved function of links

---

**Final Thoughts:**

This was my first refactor, and I didn't anticipate it being this fun. I was thoroughly enjoying the problem solving aspects trying to clean up, organize, and reduce overall lines in the code. I really hope my attention to detail shines through with this. If you have any questions please contact me at either my [GitHub](https://github.com/SFoxGit/horiseon_refactor) or [email](mailto:sfoxss4@gmail.com).