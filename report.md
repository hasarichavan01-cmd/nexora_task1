# Week 1 Task Report: Transforming Wireframes into Static Web Pages

## Project
**Nexora – Digital Experiences Landing Page**

## Objective
The task was completed by translating a common landing-page wireframe structure into a semantic, responsive static website using HTML5 and CSS3. No original wireframe image was attached to the task brief, so a clean agency-style landing page concept was used as the reference layout.

## Design decisions
- Used a warm off-white background, dark typography and purple accents to create a clear visual hierarchy.
- Selected Manrope for headings and DM Sans for body text to keep headings distinctive and paragraphs readable.
- Kept the header simple, with a brand area, primary navigation and a clear contact action.
- Used a two-column hero section to balance the main message and a CSS-built abstract illustration.
- Grouped services into three cards and presented the workflow as four numbered steps.
- Used consistent spacing, rounded corners and subtle borders to create visual consistency.

## HTML structure
The page uses semantic elements including `header`, `nav`, `main`, `section`, `article` and `footer`. Heading levels communicate the content hierarchy. Navigation links point to page sections, and the contact action uses an email link.

## CSS and responsive strategy
The stylesheet uses CSS custom properties for reusable colors, CSS Grid for major content layouts, Flexbox for navigation and alignment, and `clamp()` for responsive heading sizes. Media queries at 850px and 640px adapt the layout for tablets and mobile devices. The service cards stack vertically on small screens, navigation wraps, and the about and hero sections switch to a single-column layout. A reduced-motion preference is also respected.

## Challenges and solutions
1. **Balancing the hero layout:** The text and illustration needed similar visual weight. A two-column grid and controlled illustration dimensions provide balance on desktop.
2. **Small-screen layout:** Multi-column sections would become cramped on phones. Media queries change them to one or two columns as appropriate.
3. **Consistent styling:** Repeated colors and spacing can become difficult to maintain. CSS custom properties centralize the main theme values.
4. **Illustration without image assets:** The hero and about visuals are made from CSS shapes, gradients and borders, avoiding dependency on external image files.

## Testing checklist
- [x] Semantic HTML structure included
- [x] Navigation links target page sections
- [x] Desktop layout uses grid and flex layouts
- [x] Tablet and mobile breakpoints included
- [x] Viewport meta tag included
- [x] Reduced-motion preference supported
- [ ] Verify at 1440px, 1024px, 768px, 390px and 320px in a browser
- [ ] Replace the sample brand and email address if a different client identity is required

## How to run
Keep `index.html` and `style.css` in the same folder, then open `index.html` in a modern browser. An internet connection is only needed to load the optional Google Fonts; fallback fonts are provided by the browser.
