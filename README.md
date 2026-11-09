# TTU Marketplace

**Buy, sell, and connect within the Texas Tech student community.**

**Course:** ENGR 1340 — Introduction to Engineering (Fall 2026)  
**Assignment:** Project 2 — Build Your Own Web App  
**Milestone:** 1 — Project Proposal, Repository Setup & Website Progress  
**Deadline:** November 9, 2026, 11:59 PM  
**Team name:** `Beta 4`  
**Figma prototype:** `will do that soon`  
**Live site (optional):** `incoming`

## About the Project

TTU Marketplace is a student-focused web application for buying and selling secondhand items within the Texas Tech University community. It brings textbooks, electronics, furniture, clothing, school supplies, and other student essentials into a marketplace designed around campus life.

Students currently use broad social platforms, group chats, and word of mouth to advertise items, which can make listings hard to find and exchanges difficult to coordinate. Student interviews also identified price disagreements, last-minute cancellations, and buyers who do not show up as problems. TTU Marketplace aims to make browsing, communication, and pickup planning more organized for TTU students.

**Project 2 goal:** Translate our team's Project 1 Figma designs into a multi-page website using semantic HTML5 and external CSS, while practicing accessibility, responsive design, Git/GitHub collaboration, and pull-request workflows.

## Milestone 1 — Project Proposal (Table 1)

| Required field | Team proposal |
|---|---|
| **App Name** | TTU Marketplace |
| **App Type** | Student-to-student campus marketplace (web app) |
| **Problem It Solves** | TTU students often depend on scattered group chats, social media, and word of mouth to find or sell used items. These channels can make it difficult to compare listings, communicate reliably, and coordinate exchanges. TTU Marketplace is designed to give TTU students a more organized place to browse items, contact sellers, and plan campus pickups. |
| **Page 1 — Home (`index.html`)** | Landing page that introduces TTU Marketplace, showcases categories and featured items, and helps students navigate to browsing, selling, or messaging. |
| **Page 2 — Browse Listings (`browse.html`)** | Content grid of item cards showing a title, photo, price, category, condition, and availability tag, with visible search, filter, and sort controls. |
| **Page 3 — Add Listing (`add-listing.html`)** | Data-entry page containing a labeled form for an item title, price, category, condition, description, and pickup details, with submit and cancel controls. |
| **Page 4 — Product Details (`product-details.html`)** | Detail page showing one listing's photos, item description, price, condition, category, seller information, and pickup preference, with Back, Edit, and Archive/Delete controls. |
| **Page 5 — Messages (`messages.html`)** | Buyer-seller messaging interface with a conversation list, message thread, reply field, and links to related item information. |
| **Page 6 — Profile (`profile.html`)** | Student profile view with account information, active and sold listings, and shortcuts to listing management. |
| **Key Interactive Feature 1** | **Browse and filter:** Product cards have a **View Details** link; a search field and category/condition/sort controls allow students to locate relevant listings (controls may initially be visual). |
| **Key Interactive Feature 2** | **Open listing details:** Clicking **View Details** on a product card navigates to `product-details.html`, which shows additional information and a link back to the grid. |
| **Key Interactive Feature 3** | **Create a listing:** The `add-listing.html` form uses labeled text, number, select, and textarea fields, visible focus styling, required-field validation, and Submit/Cancel controls. |
| **Key Interactive Feature 4** | **Contact a seller:** The **Message Seller** control navigates to `messages.html`, where a conversation and message composition UI are displayed. |
| **Key Interactive Feature 5** | **Save or manage an item:** A clearly labeled favorite/save control appears on listing cards; profile and detail pages include visible item-management actions. Persistent saving is a future enhancement unless implemented. |


## Figma-to-Website Implementation

Our HTML and CSS implementation will follow our Project 1 Figma prototype as closely as possible, including:

- **Layout and components:** Navigation, headers, product cards, forms, message panels, buttons, footers, spacing, and page structure.
- **Visual design:** Colors, fonts, typography hierarchy, images, icons, and other design elements.
- **Complete screen coverage:** All Figma-designed pages will have their own `.html` files, including any additional authentication, campus pickup, confirmation, settings, or request screens that appear in the finalized prototype.
- **Usability:** Working links between pages, active navigation states, labeled controls, and visible hover/focus states.
- **Responsiveness:** CSS layouts that adapt to desktop, tablet, and smaller mobile screens.

### Page-to-File Mapping

| Figma screen / page | Planned HTML file | Status |
|---|---|---|
| Home | `index.html` | In development |
| Browse Listings | `browse.html` | In development |
| Add Listing | `add-listing.html` | In development |
| Product Details | `product-details.html` | In development |
| Messages | `messages.html` | In development |
| Profile | `profile.html` | In development |
| **Additional Figma screens** | **Add one HTML filename per screen here** | Audit Project 1 Figma prototype |

*This table describes planned work, not a claim that these files already exist. Update statuses as the team pushes files to GitHub.*

## Technology and Standards

- **HTML5:** Separate `.html` files for each page, semantic landmarks (`header`, `nav`, `main`, `section`, and `footer`), and properly labeled forms.
- **CSS3:** All styles maintained in `css/styles.css`; common styling, design tokens, active navigation, button states, responsive grids, and media queries.
- **Accessibility:** Appropriate image `alt` text; keyboard-operable links and controls; visible focus indicators; meaningful labels; sufficient color contrast; and ARIA labels where native HTML does not already provide the necessary accessible name.
- **Git/GitHub:** One public team repository, individual member branches, descriptive commits, and pull requests for review and merging.
- **GitHub Pages:** Optional static-site deployment.
- **JavaScript:** Optional progressive enhancement for interactions 


## Repository Structure

```text
ttu-marketplace-beta4/
├── index.html
├── browse.html
├── add-listing.html
├── product-details.html
├── messages.html
├── profile.html
├── others.html      # Add each additional Figma screen
├── css/
│   └── styles.css              # Shared external stylesheet for all pages
├── images/                     # Images, logos, and icons
└── README.md
```

Each contributor will include an HTML comment naming the page author at the top of their own assigned HTML file. Every proposed page will be linked through the site navigation.

## Required Page Components

**Across every page**
- Consistent navigation bar with an active-page state.
- Consistent footer.
- Semantic HTML page structure.
- Shared external CSS file (`css/styles.css`).
- Functional navigation links, accessible labels, and responsive styling.

**Browse / content-grid page (`browse.html`)**
- A list/grid of item cards with item title, category, and status/availability tag.
- At least one button or link per card (such as **View Details**).
- At least one filter or sort control; visual-only functionality is acceptable at this milestone.

**Add Listing / data-entry page (`add-listing.html`)**
- A real HTML `<form>` with labeled inputs of multiple types and a Submit button.
- A Cancel or Back link to the listing page.
- CSS `:focus` / `:focus-visible` styling for fields.
- Forms do not need to persist information for Milestone 1.

**Product Details page (`product-details.html`)**
- Listing fields and at least one visual element (photo or category/status badge).
- Edit, Delete/Archive, and Back controls. Delete/Archive may be visual-only for now.

## Team Collaboration

Our group will work in **one public GitHub repository** named using the required format: `ttu-marketplace-beta4` (lowercase and hyphens, no spaces). Every teammate will be invited as a collaborator.

Each member will:
1. Create or use a separate branch named after themselves.
2. Make regular, meaningful commits with descriptive messages.
3. Push their assigned HTML page(s) and any shared CSS updates.
4. Open a pull request for review before merging major changes to `main`.
5. Provide a screenshot and a 150–200-word progress report describing the code they personally wrote.

### Contributors and Responsibilities

| Team member | Page(s) / responsibility | Branch |
|---|---|---|
| Vincent | Home and Messages (confirm exact Milestone 1 scope) | `[member branch]` |
| Hussein | `[Confirm assigned Figma screen(s)]` | `[member branch]` |
| Jayden | `[Confirm assigned Figma screen(s)]` | `[member branch]` |
| Robert | Profile Page / Saved Items | `[member branch]` |
| Franklin | Campus pickup / confirmation flow  | `[member branch]` |
| Matthew | `[Confirm assigned Figma screen(s)]` | `[member branch]` |


## Viewing the Website Locally

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Navigate to the other pages using the shared header links.

No backend or special installation is required for the initial static implementation.

## Milestone 1 Progress Checklist

- [ ] Finalize the proposal and page list to match **every page in Project 1 Figma**.
- [ ] Create the correctly named, public GitHub repository with `README.md`.
- [ ] Invite all contributors and establish individual branches.
- [ ] Commit each assigned `.html` page and put all CSS in `css/styles.css`.
- [ ] Implement the shared navigation bar, footer, and visual design.
- [ ] Build the required content grid, form, and detail page structures.
- [ ] Add semantic HTML, image alt text, accessible labels, and keyboard focus styles.
- [ ] Add responsive CSS and verify on different screen sizes.
- [ ] Check links between pages and compare each page to its Figma screen.
- [ ] Make multiple commits and use pull requests to demonstrate contributions.
- [ ] Add one current screenshot and a 150–200-word progress report for every team member.
- [ ] Document **three actual team meetings** in the supplied progress/meeting-log template (the template asks for three; the separate requirements document mentions fewer).
- [ ] Copy the proposal summary into the provided submission template and include the real GitHub URL.
- [ ] Have **one team member** submit the combined document to Canvas by **November 9, 2026, 11:59 PM**.

## Current Scope and Future Work

Milestone 1 prioritizes complete page coverage, recognizable Figma styling, accessible markup, responsive layout, and visible GitHub contributions. Controls such as filtering, favoriting, deleting, authentication, posting listings, and real-time messaging may initially be front-end demonstrations unless the team implements persistence and working logic.

Potential future enhancements include verified TTU sign-in, saved listings, searchable inventory, real messaging, notification preferences, and a structured campus pickup/confirmation experience.

---

*TTU Marketplace — ENGR 1340, Texas Tech University, Fall 2026.*
