# coder-heroes-docs

Documentation for the Coder Heroes LMS Labs project

## CoderHeros homepage launch details (BL-461)

<!-- 1. Define the purpose of the epic.
   Purpose — Who it’s for and why you’re building it. The purpose needs to drive the features.

   The purpose should outline:
   - What problems this epic solves.
   - Who will use the features of the epic.
   - Why it’s important. -->

<!-- 2. Break the purpose down into features.
   Features — What you’re going to build or have already built.

   - Determine the feature requirements for the release. Every feature should support the overall purpose of the epic. -->

<!-- 3. Set the goals for the release criteria.
   Release Criteria — Goals for the release (e.g., functionality).

   Your goals should be:

   - Easy to understand.
   - Actionable.
   - Achievable.
   - Measurable. -->

<!-- 4. Determine the timeline.
   Timeline — A rough window for the release. -->

---

Push out a working website and get the first version of the web app live. It will primarily be a “homepage” but will include some basic functionality.

The existing website was built using SquareSpace and we should handle the basic features from that [site.](https://www.coderheroes.com/)

CoderHeroes needs a web app created to help with a number of functions with the first being an updated website. As the product is being built out, the stakeholder has requested that we implement a waitlist signup on the homepage.

---

### UX: Iterate design artifacts to include About and Services pages (BL-513 In Progress)

_Assignee: Danny Chui_
_Co-owner: Kevin Lee_

Iterate the Figma design artifacts for this product. The current state of Figma is for a complete version of the CoderHeroes app. This release is about a simplified version of the earliest features, so it’s okay for it to be simple. Pages to include:

- About:
  - About CoderHeroes
  - Terms & Conditions + Privacy Policy (these can both follow the same template)
  - Press Inquiries
- Services:
  - FAQ
  - Site Map

---

### UX: Create a new set of site fonts to be used on the app (BL-502 In Progress)

_Assignee: Conrad Klek_
_Co-owner: James Fincher_

During our stakeholder meeting with Brianne on June 30, she pointed out that the stylized font used in headers seemed a bit hard to read. She suggested that she really loved the Girls Who Code website, and they use Roboto as the font face across the entire site.

- Details:
  - Update the Figma user assets to reflect a new set of fonts for the site with Roboto fonts.
    - Model the asset model off of the Girls Who Code website.
  - Include a monospaced option for a code-like presentation of text, or to show actual text examples (like seen on the front page of the example website).
  - This ticket is only to update the assets in Figma.
    - Once the stakeholder approves of the changes, then we can apply the updated fonts to the entire mockup designs as well as on the web app itself.
- Notes:
  - Be selective about the amount of font weights and font types used in this asset guide because the more used, the more the site will have to load each time a visitor comes to the page.
    - The two fonts to be used are Roboto and Roboto Mono (both are available in Figma by default).
    - Consider using all caps, font size, and keep font weights to a minimum (maybe 3-4 at the most).

![alt text]()

<!-- put the photo added here -->

### BE: I want to find information that will tell me about CoderHeroes (BL-486 In Progress)

_Assignee: Kevin Lee_
_Co-owner: Danny Chui_

When I visit the CoderHeroes website, I want to find information that will tell me about CoderHeroes, so I can be informed about the program.

- Users:

  - Parent
  - Teacher

- Details:

  - Ensure that backend will allow site to function as expected.
  - Use the Figma mockups design as a guide for flow.
  - Work with frontend team to ensure that unused links are hidden for features/pages that are not ready to go live with this version.

- Notes:
  - Work with the product manager to bring up any substantial work that may need to be done, so we can create a new ticket to add to the epic.
  - The scope of this ticket is for small tuning of existing work that can be tweaked before launch. If it’s substantial work, we will need to separate it from this scope.

---

### Write and implement unit tests for homepage features (BL-466 Ready for Review)

_Assignee: Michael Subbarao_
_Co-owner: Dirk J Knibbe_

Implement a minimum of 3 tests to verify the case data is the expected shape and in the proper format.

---

### FE: I want to be able to express my interest in the program (BL-464 In Progress)

_Assignee: Landon Phillips_
_Co-owner: Reed Lauckern_

When I visit the CH website, I want to be able to express my interest in the program, so I can be kept in touch with updates.

- Users:

  - Parent
  - Teacher

- Details:
  - This will be a panel component to be displayed on all three pages for unauthenticated users, above the footer.
  - The Figma designs will need to be updated with this new panel.
  - Reference the original website for ideas on what is needed.
  - Ideally we will have a single form where a user can select if they are a parent or a teacher, with the former being the default.

**Note: be sure to use environment variables to key the private key separate from the JavaScript code.**

![alt text]()

<!-- put the photo added here -->

---

### FE: I want to find information that will tell me about CoderHeroes (BL-462 Ready for Review)

_Assignee: Kevin Lee_
_Co-owner: Danny Chui_

When I visit the CoderHeroes website, I want to find information that will tell me about CoderHeroes, so I can be informed about the program.

- Users:

  - Parent
  - Teacher

- Details:

  - A lot of development work has already been completed. The purpose of this ticket is to ensure that the site is clean, free of broken links, and incomplete features are hidden from view.
    - We will need to hide the instructor search section as that will be built out in a future epic.
  - Ensure that site looks and behaves as expected (responsiveness, design, etc.)
    - Use the Figma mockups design as a guide.
  - Hide links to features/pages that are not ready to go live with this version.
  - Add details for pages that should be complete.
    - Work with stakeholder to retrieve content, such as site terms and privacy policy.

- Notes:
  - Work with the product manager to bring up any substantial work that may need to be done, so we can create a new ticket to add to the epic.
    - The scope of this ticket is for small tuning of existing work that can be tweaked before launch. If it’s substantial work, we will need to separate it from this scope.

![alt text]()

<!-- put the photo added here -->
