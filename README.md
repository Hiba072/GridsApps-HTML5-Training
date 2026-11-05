# NexaTech Solutions — HTML5 & CSS3 Training Project

## Grids Apps | Full Stack Development Internship

**Developer:** Hiba Abukaf  
**Training:** HTML5 & CSS3 Foundation Track  
**Project:** Responsive Multi-Page Corporate Website  
**Project Development:** Day 01 – Day 05

## Project Overview

NexaTech Solutions is a fictional technology company website developed as part of the Grids Apps Full Stack Development Internship.

The project demonstrates semantic HTML5, accessible content structure, multi-page navigation, HTML forms, native validation, tables, media integration, CSS styling, and responsive web design.

The website uses a consistent visual design system with reusable components, CSS variables, Flexbox, Grid, and media queries to support mobile, tablet, and desktop devices.

The final project consists of **10 main website pages**, along with a separate responsive debugging challenge.

## Technologies Used

- HTML5
- CSS3
- Semantic HTML
- CSS Selectors, Cascade, Specificity & Inheritance
- CSS Box Model and Box Sizing
- CSS Custom Properties (Variables)
- Flexbox and CSS Grid
- Media Queries
- Mobile-First Responsive Design
- HTML5 Native Form Validation
- Accessibility and Keyboard Focus Styling
- Chrome Developer Tools
- Git & GitHub
- Visual Studio Code

## Day 01 — HTML5 Fundamentals

The first training day focused on creating HTML5 documents and applying semantic structure.

### Implemented Features

- HTML5 document structure and metadata
- Semantic elements such as header, nav, main, section, article, and footer
- Heading hierarchy and organized content
- Navigation links and internal anchors
- Images with descriptive alternative text
- Personal developer profile

## Day 02 — Forms & Multi-Page Architecture

The second training day focused on developing connected website pages and implementing accessible forms.

### Implemented Features

- Connected multi-page website
- Contact form with labels and validation
- Registration form with 15+ fields
- Grouped form controls using fieldset and legend
- Different HTML input types
- Native validation using required, minlength, maxlength, and email input types
- Service and pricing comparison tables
- Blog listing and article detail
- Media gallery with captions and alternative text
- Relative paths and internal navigation

## Day 03 — CSS Foundations, Cascade & Box Model

The third training day focused on styling the existing HTML5 website using an external CSS stylesheet, creating a reusable design system, and understanding CSS cascade and specificity.

### Implemented Features

- External CSS stylesheet shared across website pages
- Reusable design tokens using CSS custom properties
- Consistent color palette, spacing, and border-radius values
- Global box-sizing using border-box
- Typography styling and readable text layouts
- Styled website header and navigation
- Hero sections with gradient backgrounds
- Reusable service cards and content cards
- Styled buttons with hover and focus states
- Form controls and registration form styling
- Blog and gallery card layouts
- Service comparison table styling
- Three-tier pricing cards with a highlighted recommended plan
- Consistent footer design
- CSS selector organization and specificity improvements

### CSS Debugging Practice

The CSS debugging exercise demonstrates how element, class, and ID selectors compete in the cascade.

It also covers how source order affects declarations with equal specificity and how browser DevTools can be used to inspect applied and overridden styles.

### Day 03 Deliverables

- External stylesheet: `css/style.css`
- Tokenized color palette and spacing system
- Styled header, hero sections, and cards
- No inline final CSS styles
- CSS specificity debugging practice
- Updated GitHub repository

## Day 04 — Flexbox, Grid & Responsive Design

The fourth training day focused on improving the website's responsiveness using mobile-first CSS layouts, Flexbox, Grid, and media queries.

### Implemented Features

- Responsive navigation bar using Flexbox
- Flexible navigation alignment and wrapping
- Responsive card layouts using CSS Grid
- Mobile-first layout improvements
- Media queries for different viewport widths
- Responsive service, blog, gallery, and pricing cards
- Flexible content widths and spacing
- Responsive typography and images
- Improved layout behavior on narrow screens
- Overflow prevention using flexible sizing
- Responsive design adjustments without CSS frameworks

### Responsive Navbar

The navigation system uses Flexbox to organize navigation links and adapt their arrangement according to the available screen width.

The mobile layout organizes links into a compact structure, while wider layouts provide more horizontal space.

### Responsive Card Grid

CSS Grid is used to create responsive card layouts.

The number of columns adjusts according to screen width, allowing cards to adapt rather than remain fixed at desktop dimensions.

The grid uses flexible sizing techniques including:

- `display: grid`
- `grid-template-columns`
- `repeat()`
- `auto-fit`
- `minmax()`
- `gap`

### Challenge C08 — Responsive Overflow Repair

A demonstration of horizontal overflow was created to practice identifying and repairing broken responsive layouts.

**Problem:**

A layout with fixed-width grid columns can exceed the available viewport width on smaller devices.

**Solution:**

Replace rigid column widths with a flexible grid using `auto-fit`, `minmax()`, and responsive sizing.

**Result:**

The repaired demonstration adapts its columns to the available space without page-level horizontal overflow at the tested viewport widths.

### Flexbox vs Grid

**Flexbox** is mainly used for one-dimensional layouts, such as navigation bars, button groups, and alignment of elements along one axis.

**CSS Grid** is mainly used for two-dimensional layouts, such as service cards, pricing cards, blog cards, and gallery grids.

Both layout systems are used according to the structure and requirements of each component.

### Responsive Testing

The following viewport widths are used for responsive testing:

| Device Type | Viewport Width |
|---|---|
| Mobile | 375px |
| Tablet | 768px |
| Desktop | 1440px |

Browser Developer Tools are used to inspect layout behavior, navigation, and potential overflow problems.

## Day 05 — HTML/CSS Project Delivery

The fifth training day focuses on completing and presenting the responsive corporate website, reviewing accessibility, verifying project integration, and preparing the final GitHub submission.

### Final Website Integration

The project includes the following main pages:

| Page | Description |
|---|---|
| `index.html` | Corporate landing page with hero, services, and featured content |
| `about.html` | Company overview, mission, vision, and values |
| `services.html` | Digital services, comparison table, and pricing plans |
| `blog.html` | Blog listing with technology articles |
| `blog-detail.html` | Complete article with related content |
| `contact.html` | Contact form with HTML5 validation |
| `registration.html` | Client registration form with grouped controls |
| `gallery.html` | Media gallery with images and captions |
| `profile.html` | Developer biography, skills, education, and training |
| `faq.html` | Frequently asked questions using HTML5 details and summary elements |

### FAQ Page

The FAQ page was designed as an additional main website page to satisfy the final project's 10+ page requirement.

It includes:

- General questions about NexaTech Solutions
- Questions about digital development and technology
- Pricing and registration information
- Expandable answers using `<details>` and `<summary>`
- Keyboard-accessible interactive elements
- Responsive styling with the existing design system
- Links to related pages and services

The FAQ interactions work without JavaScript.

### Integration & Accessibility Review

The final review focuses on:

- Consistent navigation across all pages
- Correct internal links and relative file paths
- Reusable header, navigation, and footer styles
- Semantic HTML structure
- Descriptive alternative text for images
- Accessible form labels and grouped controls
- Visible keyboard focus states
- Responsive images and typography
- Layout adaptation across different screen widths
- No unintended horizontal page overflow

### Peer QA

Peer quality assurance is part of the final delivery process.

The review includes checking page navigation, responsive layouts, form validation, image loading, accessibility, and visual consistency.

Any identified problems should be documented and corrected before the final submission.

### Live Code Explanation

The final presentation includes explaining:

- HTML5 semantic structure
- External CSS stylesheets
- CSS variables and reusable design tokens
- Cascade and specificity
- CSS Box Model
- Flexbox and Grid layout choices
- Mobile-first responsive design
- Media queries
- Overflow debugging
- Accessibility and keyboard focus states

### Final Project Deliverables

- 10+ responsive website pages
- Updated README documentation
- Mobile, tablet, and desktop screenshots
- Responsive Navbar and Card Grid
- C08 overflow repair demonstration
- Peer QA review
- Live project demonstration
- Trainer rubric review
- Final GitHub repository update

## Project Structure

```text
01-HTML5/
├── index.html
├── profile.html
├── about.html
├── services.html
├── blog.html
├── blog-detail.html
├── contact.html
├── registration.html
├── gallery.html
├── faq.html
├── c08-overflow.html
├── css/
│   ├── style.css
│   └── c08.css
├── images/
├── screenshots/
│   ├── mobile.png
│   ├── tablet.png
│   └── desktop.png
└── README.md
```

## HTML5 Challenges

| Challenge | Description |
|---|---|
| H01 | Profile & Biography |
| H02 | Company Landing Structure |
| H03 | Blog System Markup |
| H04 | Registration Form |
| H05 | Pricing Comparison |
| H06 | Media & Gallery |

## CSS3 Challenges

| Challenge | Description |
|---|---|
| Day 03 | CSS Specificity Debugging |
| Day 04 | Responsive Navbar |
| Day 04 | Responsive Card Grid |
| C08 | Responsive Overflow Repair |
| Day 05 | Website Integration & Delivery |

## Accessibility Practices

- Semantic HTML5 elements
- Logical heading hierarchy
- Descriptive alternative text for images
- Form labels connected to inputs
- Fieldset and legend for grouped controls
- Appropriate table headers and captions
- Navigation using meaningful links
- Visible keyboard focus styles
- Readable typography and consistent spacing
- Responsive layouts supporting different viewport sizes
- Native HTML5 interactive elements

## How to Run

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a browser or use the Live Server extension.
4. Navigate through the website using the main navigation menu.
5. Verify that the external CSS stylesheet loads correctly.
6. Test the contact and registration forms using fictional data.
7. Open Chrome Developer Tools.
8. Enable Device Toolbar using `Ctrl + Shift + M`.
9. Test the website at mobile, tablet, and desktop viewport widths.
10. Open `c08-overflow.html` to view the responsive overflow repair demonstration.
11. Visit `faq.html` to explore the expandable FAQ sections.

## Important Notes

This is an educational HTML5 and CSS3 project. NexaTech Solutions is a fictional company.

The website uses CSS3 without Bootstrap, Tailwind CSS, or other CSS frameworks.

The contact and registration forms demonstrate browser-side validation only. They do not create real accounts, send messages, or store submitted information.

Do not enter real passwords or sensitive personal information.

All website pricing plans are fictional and are provided for educational purposes.

## Author

**Hiba Abukaf**  
Computer Science Student — Birzeit University  
Full Stack Development Intern — Grids Apps

**GitHub:** https://github.com/Hiba072/GridsApps-HTML5-Training