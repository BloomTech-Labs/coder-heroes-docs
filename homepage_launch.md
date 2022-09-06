## BL-461 - CoderHeros homepage launch details

The main goal of this epic is to push out a working website and get the first version of the web app live. It will primarily be a “homepage” but will include some basic functionality. The [existing website](https://www.coderheroes.com/) was built using [SquareSpace](https://www.squarespace.com/) and we should handle the basic features from that site.

- [BL-462](#bl-462---fe-i-want-to-find-information-that-will-tell-me-about-coderheroes) - FE: I want to find information that will tell me about CoderHeroes
- [BL-464](#bl-464---fe-i-want-to-be-able-to-express-my-interest-in-the-program) - FE: I want to be able to express my interest in the program
- [BL-465](#bl-465---update-product-doc-repository-to-include-homepage-launch-details) - Update product doc repository to include homepage launch details
- [BL-466](#bl-466---write-and-implement-unit-tests-for-homepage-features) - Write and implement unit tests for homepage features
- [BL-486](#bl-486---be-i-want-to-find-information-that-will-tell-me-about-coderheroes) - BE: I want to find information that will tell me about CoderHeroes
- [BL-502](#bl-502---ux-create-a-new-set-of-site-fonts-to-be-used-on-the-app) - UX: Create a new set of site fonts to be used on the app
- [BL-513](#bl-513---ux-iterate-design-artifacts-to-include-about-and-services-pages) - UX: Iterate design artifacts to include About and Services pages

---

### BL-462 - FE: I want to find information that will tell me about CoderHeroes

_Assignee: Kevin Lee_ - _Co-owner: Danny Chui_

[GitHub](https://github.com/BloomTech-Labs/coder-heroes-fe/tree/BL-462-fe-i-want-to-find-information-that-will-tell-me-about-coder-heroes) [Loom Video](https://www.loom.com/share/4da11d9222ab46bf895c779b25e1a2b6)

**The scope of this ticket is for small tuning of existing work that can be tweaked before launch.**

When consumers visit the CoderHeroes website, they can find information that will tell them about CoderHeroes, so they can be informed about the program.

- Details:
  - A lot of development work has already been completed. The purpose of this ticket was to ensure that the site is clean, free of broken links, and incomplete features are hidden from view.
    - We have hide the instructor search section as that will be built out in a future epic.
  - Ensured that site looks and behaves as expected (responsiveness, design, etc.). Used the Figma mockups design as a guide.
  - Added details for pages that should be complete.
    - Worked with stakeholder to retrieve content, such as site terms and privacy policy.

### BL-464 - FE: I want to be able to express my interest in the program

_Assignee: Landon Phillips_ - _Co-owner: Reed Lauckern_

[GitHub](https://github.com/BloomTech-Labs/coder-heroes-fe/tree/BL-464-fe-i-want-to-be-able-to-express-my-interest-in-the-program) [Loom Video]()

When a consumer visits the CoderHero website, they should be able to express their interest in the program, so that they can be kept in touch with updates.

- Details:
  - This will be a panel component to be displayed on all three pages for unauthenticated users, above the footer.
  - The Figma designs will need to be updated with this new panel.
  - Reference the original website for ideas on what is needed.
  - Ideally we will have a single form where a user can select if they are a parent or a teacher, with the former being the default.

### BL-465 - Update product doc repository to include homepage launch details

_Assignee: Rebecca Stone_ - _Co-owner: Tony Kordysh_

[Loom Video](https://www.loom.com/share/f566d6b893964be28ea51ddd8bcdbfb6)

Make updates to the product documentation [repository](https://github.com/BloomTech-Labs/coder-heroes-docs) based on the changes of this epic.

### BL-466 - Write and implement unit tests for homepage features

_Assignee: Michael Subbarao_ - _Co-owner: Dirk J Knibbe_

[GitHub](https://github.com/BloomTech-Labs/coder-heroes-fe/tree/BL-466-write-and-implement-unit-tests-for-homepage-features) [Loom Video](https://www.loom.com/share/52a8dc1220ca4f05a79ebe0faf0bdedb)

Implemented at least 3 tests to verify the case data is the expected shape and in the proper format.

### BL-486 - BE: I want to find information that will tell me about CoderHeroes

_Assignee: Kevin Lee_ - _Co-owner: Danny Chui_

[GitHub]() [Loom Video]()

**The scope of this ticket is for small tuning of existing work that can be tweaked before launch.**

When A consumer visits the CoderHeroes website, they should be able to find information that will tell them about CoderHeroes, that way they can be informed about the program.

- Details:
  - Ensured that backend will allow site to function as expected.
  - Used the Figma mockups design as a guide for flow.
  - Working with frontend team to ensure that unused links are hidden for features/pages that are not ready to go live with this version.

### BL-502 - UX: Create a new set of site fonts to be used on the app

_Assignee: Conrad Klek_ - _Co-owner: James Fincher_

[Figma](https://www.figma.com/file/7VBR8i7t3nbdmUp15ELqCG/CoderHeroes-Figma?node-id=0%3A1)

**This ticket is only to update the assets in Figma. Once the stakeholder approves of the changes, then we can apply the updated fonts to the entire mockup designs as well as on the web app itself.**

During our stakeholder meeting with Brianne on June 30, she pointed out that the stylized font used in headers seemed a bit hard to read. She stated that she really loved the [Girls Who Code](https://girlswhocode.com/) website, and they use Roboto as the font face across the entire site.

Including a monospaced option for a code-like presentation of text, or to show actual text examples (like seen on the front page of the example website). We were selective about the amount of font weights and font types used in this asset guide because the more used, the more the site will have to load each time a visitor comes to the page.

- The two fonts to be used are Roboto and Roboto Mono (both are available in Figma by default).
- Consider using all caps, font size, and keep font weights to a minimum (maybe 3-4 at the most).

### BL-513 - UX: Iterate design artifacts to include About and Services pages

[Figma](https://www.figma.com/file/7VBR8i7t3nbdmUp15ELqCG/CoderHeroes-Figma?node-id=309%3A56733)

_Assignee: Danny Chui_ - _Co-owner: Kevin Lee_, _Savannah Maxwell_

Iterate the Figma design artifacts for this product. The current state of Figma is for a complete version of the CoderHeroes app. This release is about a simplified version of the earliest features.

Pages to include:

- About:
  - About CoderHeroes
  - Terms & Conditions + Privacy Policy (these can both follow the same template)
  - Press Inquiries
- Services:
  - FAQ
  - Site Map

---
