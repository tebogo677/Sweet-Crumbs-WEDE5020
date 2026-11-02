# Sweet Crumbs Bakery Website Project

## Project Title
Sweet Crumbs Bakery Website

## Student Information
- Student name: ______________________________
- Student number: ____________________________
- Module: WEDE5020 – Web Development (Introduction)
- Date: _____________________________________

## Project Overview
Sweet Crumbs Bakery is a fictional local bakery created for the web development project. The website provides information about the bakery, its products, enquiry process and contact details.

## Website Goals and Objectives
- Present the bakery professionally online.
- Make products easy to find.
- Allow visitors to submit an enquiry.
- Provide clear contact information.
- Create a responsive and accessible five-page website.

## Key Features and Functionality
- Five linked HTML pages.
- Consistent navigation menu.
- Product and service information.
- Enquiry form with basic JavaScript validation/demo response.
- External CSS stylesheet shared by all pages.
- Responsive desktop, tablet and mobile layouts.
- Responsive images using flexible sizing.
- Original SVG graphics created for the project.

## Sitemap
Home (index.html)
├── About Us (about.html)
├── Products (products.html)
├── Enquiry (enquiry.html)
└── Contact (contact.html)

## Folder Structure
- index.html
- about.html
- products.html
- enquiry.html
- contact.html
- css/style.css
- js/script.js
- robots.txt
- sitemap.xml
- images/cake.svg
- images/cupcake.svg
- images/pastry.svg

## Part 2: CSS Styling and Responsive Design

### External stylesheet
All five HTML pages link to the shared external stylesheet `css/style.css`. This keeps the design consistent across the website and reduces repeated CSS code.

### Default styling
A CSS reset is used to remove default browser margin and padding. The stylesheet also sets the main font family, font size, line height, text colour, background colour and responsive image behaviour.

### Typography
Typography uses Arial/Helvetica with different sizes and weights for headings, paragraphs, navigation and supporting text. `rem`, `clamp()` and letter spacing are used where appropriate for readable and responsive text.

### Layout
CSS Grid is used for the hero section, content sections and product/card layouts. Flexbox is used for the navigation, button groups and map placeholder. The desktop layout uses multiple columns where suitable.

### Decoration and colour
The website uses a consistent bakery-inspired colour scheme with pink, burgundy, white and light neutral backgrounds. Cards use borders, rounded corners and shadows to create visual separation.

### Pseudo-classes
The stylesheet uses `:hover`, `:focus` and `:active` pseudo-classes for navigation links, buttons and form controls. These provide visual feedback when users interact with the website.

### Responsive design
Two responsive breakpoints are included:
- Tablet: `max-width: 900px`
- Mobile: `max-width: 600px`

The layouts change from multiple columns to fewer columns and finally single-column layouts on mobile. Navigation, buttons, spacing and heading sizes are also adjusted for smaller screens.

### Responsive images
Images use `max-width: 100%` and `height: auto` so that they scale down without overflowing their containers.

## Part 2 Changelog
- v1.0: Created five-page HTML website structure.
- v1.1: Added navigation and semantic page sections.
- v1.2: Added initial CSS styling and responsive layout.
- v1.3: Added enquiry form interaction and original SVG assets.
- v1.4: Refined the shared external stylesheet for Part 2.
- v1.5: Added detailed typography styles, responsive Grid/Flexbox layouts, decorative styling, hover/focus/active pseudo-classes, tablet/mobile breakpoints and responsive image rules.
- v1.6: Updated the README with Part 2 implementation details and testing evidence placeholders.

## Part 2 Testing Evidence
The website should be tested using browser developer tools at desktop, tablet and mobile widths.

### Desktop screenshot
[Insert screenshot of the website at desktop width here.]

### Tablet screenshot
[Insert screenshot of the website at tablet width here.]

### Mobile screenshot
[Insert screenshot of the website at mobile width here.]

## GitHub
Regular descriptive commits should be used when updating the project. Push the final HTML, CSS, JavaScript, image files and README to the GitHub repository before submission.

## Part 3: Functionality and SEO

### JavaScript functionality added
- Product search filters the product cards by product name.
- Product sorting supports featured order, price low-to-high, price high-to-low and alphabetical order.
- Product cards link directly to the enquiry form with the selected product pre-filled.
- Product FAQs use accessible HTML disclosure elements.
- The enquiry form validates required fields, checks the chosen date is not in the past, and calculates an illustrative starting-price estimate using the listed starting prices (cake R450, cupcake box R180, pastry box R150).
- The contact form validates the visitor's name, email, message type and full message.
- Both forms prepare a message using a `mailto:` link. They do not send, store, or process submissions on a server. The email address is fictional for this project.
- The Contact page uses Leaflet with OpenStreetMap tiles to show general Johannesburg and Pretoria service areas. Markers are approximate city-area points, not verified shop entrances. Internet access is required for the external map library and map tiles.

### SEO work
- Added page-specific titles, descriptions, keyword metadata and robots metadata to each HTML page.
- Reviewed heading hierarchy, internal links, image alternative text and mobile responsiveness.
- Added `robots.txt` and `sitemap.xml`.
- The canonical links and sitemap currently use `https://example.com` as a placeholder. Replace this with the real deployed website address before publishing/submitting.
- Suggested keyword themes: custom cakes, celebration cakes, cupcakes, pastry boxes, bakery Johannesburg and bakery Pretoria. These are suggested phrases, not the result of a formal keyword-volume tool.
- Suggested off-page SEO: create accurate business listings and social profiles only if the bakery becomes a real business, ask for genuine reviews, and link to the site from relevant local pages. The current bakery and contact details are fictional, so do not publish them as a real business.
- Performance/security: use compressed assets, HTTPS hosting, accessible forms and current browser testing. The external Leaflet and OpenStreetMap resources require internet access.

### Part 3 testing checklist
- [ ] Search for a product and confirm non-matching cards disappear.
- [ ] Test each sorting option.
- [ ] Open an enquiry link from a product card and check the product is selected.
- [ ] Submit empty/invalid enquiry fields and confirm validation appears.
- [ ] Change product and quantity and check the starting-price estimate updates.
- [ ] Submit a valid enquiry and confirm the email draft is prepared (if a mail app is configured).
- [ ] Test contact form required fields, email validation and email draft.
- [ ] Check the map loads online and both markers open popups; check fallback links if blocked.
- [ ] Test all pages at desktop, tablet and mobile widths.
- [ ] Replace example.com in canonical tags, robots.txt and sitemap.xml after deployment.
- [ ] Add screenshots of successful tests and any Part 2 feedback corrections requested by the lecturer.

## Part 3 Changelog
- v1.7: Improved page-specific SEO titles and meta descriptions, added keyword/robots metadata and technical sitemap files.
- v1.8: Added product search, product sorting, direct product enquiry links and FAQ disclosures.
- v1.9: Improved enquiry form validation and added starting-price estimates and date checks.
- v2.0: Added contact form validation and email-draft composition using mailto links.
- v2.1: Added Leaflet/OpenStreetMap map for approximate Johannesburg and Pretoria service areas.
- v2.2: Documented Part 3 features, limitations and testing checklist in README.

## Deployment and GitHub submission
1. Push the full project folder to your GitHub repository using descriptive commit messages, for example: `Add product search and sorting`, `Improve enquiry form validation`, `Add SEO sitemap and robots file`.
2. Deploy the static site using GitHub Pages or Netlify.
3. After deployment, replace `example.com` in each canonical tag, `robots.txt` and `sitemap.xml` with the actual live domain.
4. Open every page on the live website and test the forms, links and map.
5. Submit the GitHub repository URL (and live website URL if requested) through the LMS.

## References
- Mozilla Developer Network (MDN). (n.d.). *HTML, CSS and JavaScript documentation*. Available at: https://developer.mozilla.org/ (Accessed: 18 September 2026).
- World Wide Web Consortium (W3C). (n.d.). *Web standards and accessibility resources*. Available at: https://www.w3.org/ (Accessed: 18 September 2026).
- Leaflet. (n.d.). *Leaflet documentation*. Available at: https://leafletjs.com/ (Accessed: 2 November 2026).
- OpenStreetMap contributors. (n.d.). *OpenStreetMap*. Available at: https://www.openstreetmap.org/ (Accessed: 2 November 2026).
- Sitemap protocol. (n.d.). *Sitemaps XML format*. Available at: https://www.sitemaps.org/protocol.html (Accessed: 2 November 2026).
- Original SVG graphics: created specifically for this student project.
Netlify website address https://venerable-muffin-6b0c50.netlify.app/
https://github.com/tebogo677/Sweet-Crumbs-WEDE5020
