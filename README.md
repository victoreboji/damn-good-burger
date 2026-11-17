# Damn Good Burger

A restaurant website I am building to practice HTML, CSS, and frontend development. The design uses green, purple, white, and black branding with matching food photography.

## Project status

Work in progress. The homepage, food menu, sides, shakes, and footer are built. The current page uses HTML and CSS without JavaScript functionality.

## Features so far

- Sticky header with a restaurant logo and navigation links.
- Storefront hero image, introductory text, and a View Menu link.
- Separate Our Menu, Sides, and Shakes sections.
- Menu cards with food images, prices, and expandable descriptions using native HTML `details` and `summary` elements.
- Flexbox layouts with wrapping and evenly distributed menu cards.
- Footer with opening hours, a clickable phone number, and social media icons.
- Image alternative text, accessible social link labels, and visible keyboard focus styling on menu summaries.
- Page title, description, and viewport metadata.

## Core Updates

- Defined `--brand-green` as a shared CSS custom property for the menu headings, reservation button, and footer headings.
- Added hover effects to menu cards so visitors get visual feedback as they browse.
- Built a responsive reservation request form and linked it from **Reserve** in the header. The form is ready for a future submission handler so the restaurant can receive requests and confirm availability.
- Updated the restaurant logo to link to `#home`, so clicking it returns visitors to the top of the homepage.

## Built with

- HTML — page structure, content, links, and expandable menu details.
- CSS — layout, colors, spacing, typography, hover effects, and focus styling.
- Git and GitHub — version control and project storage.
- VS Code — code editing and local preview with Live Server.

The expandable menu descriptions work without JavaScript because `details` and `summary` provide that behavior in the browser.

## Project structure

```text
damn-good-burger/
├── index.html       # Website structure and content
├── README.md        # Project documentation
├── css/
│   └── styles.css   # Website styling
├── images/         # Food photography, logo, and hero image
├── logos/          # Social media SVG icons
└── js/
    └── script.js   # Reserved for future JavaScript work; not linked in the page
```

## View locally

1. Open the project folder in VS Code.
2. With the Live Server extension installed, right-click `index.html` and choose **Open with Live Server**.
3. View the website in your browser.

You can also open `index.html` directly in a browser; no build step or package installation is required.

## What I am practicing

- Semantic HTML elements and parent/child relationships.
- Classes, IDs, and CSS selectors.
- The box model: width, padding, borders, and margins.
- Flexbox alignment, wrapping, gaps, and spacing.
- Relative units such as `rem` and `vh`.
- Image sizing and background images.
- Basic accessibility and keyboard interaction.
- Saving and sharing progress with Git and GitHub.

## Still to do

- Connect the reservation form to a submission handler so the restaurant can receive requests and confirm availability.
- Build the Reviews section and connect it to the header navigation.
- Replace social media homepage placeholders with actual restaurant profile URLs.
- Confirm restaurant contact information, hours, menu prices, ingredient claims, and allergen information before public use.
- Test and refine the layout on smaller screens, especially the header and navigation.
- Continue accessibility checks and add JavaScript only when a feature needs it.

## Assets and content

The project includes AI-generated food and storefront imagery created for this learning project. Restaurant details and menu content are project content and should be verified before use for a real business.

### Social media icon credits

The Instagram, X (Twitter), and Facebook SVG icons in `logos/` are from [Font Awesome Free 7.3.1](https://fontawesome.com/), by Fonticons, Inc. Copyright 2026 Fonticons, Inc.

- SVG icons are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
- See the [Font Awesome Free license and attribution requirements](https://fontawesome.com/license/free).
- The original attribution and license comments are preserved inside the SVG files and should remain intact.
- Brand logos are trademarks of their respective owners. They are used to represent their social platforms and do not imply endorsement.

This README will be updated as the website grows.
