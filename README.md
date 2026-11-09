
# TTU Marketplace

**Course:** ENGR 1340 - Introduction to Engineering  
**Project:** Project 2 - HTML & CSS Website Development  
**University:** Texas Tech University  
**Team:** Beta4  
**Milestone 1 Deadline:** November 9, 2026

## 1. Project Overview

TTU Marketplace is a student-to-student online marketplace designed specifically for the Texas Tech University community.

The platform allows students to discover, buy, and sell secondhand items such as textbooks, electronics, furniture, clothing, and school supplies.

The goal is to provide a convenient and student-focused platform where users can communicate with sellers, explore affordable products, and arrange campus pickups.

## 2. Project Proposal - Table 1

| Field | Description |
|---|---|
| App Name | TTU Marketplace |
| App Type | Student-to-Student Online Marketplace (E-commerce Web Application) |
| Problem It Solves | Texas Tech students often face difficulties finding affordable secondhand items and connecting with reliable buyers and sellers within the university community. TTU Marketplace provides a centralized platform where students can discover and sell items, communicate with other students, and arrange convenient campus pickups. |
| Page 1 - Home / Marketplace | The main landing page where students can search for items, browse categories, view featured listings, and navigate to other sections of the website. |
| Page 2 - Listing Details | Displays information about an item, including its image, price, condition, description, seller information, and available purchase-related actions. |
| Page 3 - Create Listing | Provides a form where students can enter an item's name, description, price, category, condition, and images to create a marketplace listing. |
| Page 4 - Messages | Provides a conversation interface where buyers and sellers can discuss products, ask questions, and coordinate campus pickups. |
| Page 5 - My Profile | Displays a student's profile information, active listings, selling history, and options for managing marketplace activities. |
| Page 6 - Manage Listing | Allows sellers to view listing information and engagement statistics and access options to edit, mark as sold, or delete an item. |

### Five Key Interactive Features

**Feature 1 - Search and Filtering**

A search bar allows students to enter keywords to find marketplace items. Category, price, and condition controls allow students to narrow down the displayed listings.

**Feature 2 - Product Cards and Details**

Product cards display an item image, name, price, category, and condition. Hovering over a card highlights it, while clicking the item title opens its detailed listing page.

**Feature 3 - Create Listing**

A Sell Item button opens a form where students can enter an item title, description, price, category, condition, and product images. The interface includes form fields and submission controls.

**Feature 4 - Student Messaging**

A Message Seller option opens the messaging interface, where students can view conversations, type messages, and select an option to arrange a campus pickup.

**Feature 5 - Listing Management**

The Manage Listing page displays a seller's item information and provides Edit Listing, Mark as Sold, and Delete Listing controls for managing the item.

These features describe the intended application behavior. During Milestone 1, certain interactive elements are visual-only and do not require backend functionality.

## 3. Figma Design

Our team originally developed the TTU Marketplace interface in Figma as part of Project 1.

Project 2 focuses on converting those designs into HTML5 and CSS while maintaining the original layouts, colors, typography, and visual consistency.

**Figma Prototype:**

https://www.figma.com/design/SULHIYdyHpElod5jiIvorg/TTU-Marketplace-%E2%80%93-Team-Wireframe?node-id=81-2

The final Figma prototype contains 16 screens distributed among six team members.

## 4. Website Pages and Team Responsibilities

| Team Member | Assigned Pages | HTML Files |
|---|---|---|
| Vincent | Home / Marketplace, Messages, Manage Listing, Listing Published | index.html, messages.html, manage-listing.html, listing-published.html |
| Hussein | Sign In, Create Account | sign-in.html, create-account.html |
| Jayden | Listing Details, Seller Profile | listing-details.html, seller-profile.html |
| Robert | My Profile, Saved Items | profile.html, saved.html |
| Franklin | Browse Map, Campus Pickup, Meetup Confirmation | browse-map.html, campus-pickup.html, meetup-confirmation.html |
| Matthew | Create Listing, Reviews, Settings | create-listing.html, reviews.html, settings.html |

Each team member is responsible for implementing their assigned Figma screens using semantic HTML and external CSS.

All pages should share consistent navigation, design elements, and accessibility features.

## 5. Project File Structure

```text
TTU_Markekplace-Beta4/
|
|-- index.html
|-- messages.html
|-- manage-listing.html
|-- listing-published.html
|
|-- sign-in.html
|-- create-account.html
|
|-- listing-details.html
|-- seller-profile.html
|
|-- profile.html
|-- saved.html
|
|-- browse-map.html
|-- campus-pickup.html
|-- meetup-confirmation.html
|
|-- create-listing.html
|-- reviews.html
|-- settings.html
|
|-- css/
|   |-- styles.css
|
|-- images/
|   |-- macbook.png
|   |-- textbook.png
|   |-- chair.png
|   |-- fridge.png
|   |-- hoodie.png
|   |-- additional-assets/
|
|-- README.md
```

The file structure represents the planned organization of the complete website. Each page is implemented in its own HTML file.

## 6. Technologies Used

### HTML5

Used to create the structure and content of the website, including navigation bars, forms, product cards, messaging interfaces, and page sections.

### CSS3

Used to style the website, including colors, typography, spacing, buttons, responsive grids, and layouts.

All styling is maintained in the shared `css/styles.css` file.

### Git and GitHub

Used for version control, collaboration, branching, commits, and pull requests.

### Figma

Used to design the original interface and guide the HTML/CSS implementation.

## 7. Design and Accessibility Standards

The website follows these development practices:

- Semantic HTML5 elements, including header, nav, main, section, and footer.
- Consistent navigation and footer across pages.
- External CSS styling.
- Descriptive alt text for product images.
- Accessible labels for form inputs.
- Keyboard focus indicators.
- Responsive layouts using CSS media queries.
- Consistent colors, spacing, and typography.
- Page-specific CSS classes to minimize styling conflicts.

### Design Colors

| Color | Hex Value |
|---|---|
| TTU Red | #CC0D14 |
| Dark Background | #1F1F24 |
| Main Text | #121214 |
| Muted Text | #737880 |
| Light Background | #F5F5F7 |
| Borders | #E0E3E8 |

## 8. GitHub Collaboration

Our team uses GitHub to coordinate individual contributions.

The development workflow includes:

1. Cloning the shared repository.
2. Creating or switching to an individual development branch.
3. Implementing assigned HTML pages.
4. Adding CSS styling in the shared stylesheet.
5. Making regular commits with descriptive messages.
6. Pushing changes to GitHub.
7. Reviewing and merging completed work through pull requests.

Each team member includes an identifying HTML comment near the beginning of their assigned files.

Example:

```html
<!-- Vincent - Home / Marketplace Page -->
```

### Example Commit Messages

```bash
git commit -m "Create homepage HTML structure"
git commit -m "Add marketplace navigation and search"
git commit -m "Build featured product cards"
git commit -m "Style messaging interface"
git commit -m "Implement manage listing page"
git commit -m "Improve responsive page layouts"
```

## 9. Running the Website Locally

To view the project locally:

1. Clone or download the GitHub repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a web browser or use the Live Server extension.
4. Navigate between the available website pages using the navigation links.

No backend installation or database setup is required for Milestone 1.

## 10. Milestone 1 Development Scope

Milestone 1 focuses on demonstrating implementation progress by converting the team's Figma screens into HTML and CSS.

The required development work includes:

- Creating the individual HTML pages.
- Implementing the primary page layouts.
- Applying external CSS styling.
- Adding navigation between pages.
- Using accessible HTML elements.
- Demonstrating responsive design.
- Committing and pushing development progress to GitHub.

Some features, including authentication, live messaging, search filtering, and database-backed listing management, are planned for future development.

The current milestone emphasizes frontend structure, styling, teamwork, and version control rather than a fully operational marketplace.

## 11. Future Improvements

Planned improvements include:

- Working student authentication.
- Functional product search and filtering.
- Creating and storing marketplace listings.
- Persistent favorites and saved items.
- Real-time messaging between buyers and sellers.
- Functional listing editing and deletion.
- Listing status updates.
- Improved mobile responsiveness.
- Additional accessibility testing.
- Backend and database integration.

## 12. Repository

**GitHub Repository:**

https://github.com/vincent-iyegbuye/TTU_Markekplace-Beta4

**Project:** TTU Marketplace  
**Institution:** Texas Tech University  
**Course:** ENGR 1340  
**Academic Year:** 2026
