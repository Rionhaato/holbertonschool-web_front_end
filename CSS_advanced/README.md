# CSS Advanced

This project contains the CSS deliverables for the Holberton School `CSS_advanced` module. The work styles the **Techium** website progressively, starting from basic variables and typography, then moving into layout, navigation, cards, dark sections, buttons, and transitions.

The project is organized as a task-by-task stylesheet sequence. Each file builds on the previous one and reflects a specific checkpoint from the project instructions.

## Project Goals

This section focuses on applying advanced CSS concepts to a realistic multi-section landing page.

Main objectives:

- Define and reuse CSS custom properties
- Build a typographic system with scalable font sizes, line heights, and font weights
- Normalize browser defaults with `normalize.css`
- Use pseudo-classes and pseudo-elements
- Create reusable layout utilities for containers, rows, and columns
- Style navigation, buttons, service cards, work cards, testimonials, and footer content
- Implement dark theme sections with variable overrides
- Add transitions and hover effects for interactive components

## Technologies Used

- HTML5
- CSS3
- CSS custom properties
- `normalize.css` v8.0.1
- Inline SVG icons

## Directory Structure

### Stylesheets

The `styles/` directory contains the incremental task files:

- `1-style.css` to `32-style.css`

Each stylesheet represents one task milestone. The sequence is important because each file extends the previous one.

### Images

The `images/` directory contains the assets used by the Techium layout:

- `favicon.jpg`
- `logo-black.png`
- `logo-white.png`
- `pic-about-01.jpg`
- `pic-work-01.jpg`
- `pic-work-02.jpg`
- `pic-work-03.jpg`
- `pic-article-01.jpg`
- `pic-article-02.jpg`
- `pic-article-03.jpg`
- `pic-person-01.jpg`
- `pic-person-02.jpg`
- `pic-person-03.jpg`

Some earlier placeholder image files were also preserved for continuity with the original workspace.

## What The Stylesheets Cover

### Tasks 1 to 4

- Smooth scrolling
- Base text colors
- Hidden utility class
- Custom properties for colors
- Base and title font-family variables

### Tasks 5 to 8

- Font size variables
- Root font scaling
- Font weight variables
- Google Fonts integration
- Line-height variables

### Tasks 9 to 12

- Link decoration reset
- Section header alignment
- Section tagline formatting
- Section title variables and typography

### Tasks 13 to 16

- Link pseudo-classes
- Browser normalization
- Universal `box-sizing`
- Fixed-width centered container

### Tasks 17 to 20

- Section and footer spacing
- Navbar customization
- Grid layout with rows and columns
- Row clearing with pseudo-elements

### Tasks 21 to 24

- Shared `col-` selector cleanup
- Dark section theme with variable overrides
- Footer and social icon dark-theme fixes
- Service card background and hover states

### Tasks 25 to 28

- Button variables and hover styling
- Testimonial avatar and citation styling
- Hero section sizing and spacing
- Header and logo positioning

### Tasks 29 to 32

- Navigation hover indicator using `::before`
- Work card overlays
- Decorative quote mark on testimonials
- Transitions and transforms for buttons, navigation, and work cards

## Final Styled Components

By the end of the project, the stylesheet sequence supports:

- Header with positioned logo and horizontal navigation
- Hero section with large title and call-to-action button
- Services cards with hover background change
- Work cards with image overlays and hover transitions
- About section layout with columns
- Latest news cards
- Testimonial cards with circular avatars and decorative quote marks
- Contact section with centered call-to-action
- Footer with address, social links, and policy navigation
- Dark themed sections using `data-section-theme="dark"`

## Important CSS Concepts Demonstrated

### CSS variables

The project uses custom properties extensively for:

- colors
- fonts
- font sizes
- font weights
- spacing
- transitions
- button styling
- navigation styling

This makes the design more maintainable and consistent.

### Pseudo-classes and pseudo-elements

Examples used in this project include:

- `:link`
- `:visited`
- `:hover`
- `:active`
- `::before`
- `::after`

These are used for link states, decorative effects, clearing floats, and navigation hover bars.

### Grid system with floats

Before flexbox or grid is introduced, the layout is built using:

- `.row`
- `.col-1-2`
- `.col-1-3`
- float-based columns
- clearfix with `.row::after`

### Theme overrides

Dark sections are implemented by redefining custom properties inside:

```css
[data-section-theme="dark"]
```

This approach changes colors without rewriting every component rule.

### Transitions and transforms

The project adds lightweight motion using:

- `transition`
- `transform: scale(...)`
- hover overlays
- animated navigation indicators

## How To Use

Open the project root and link the required stylesheet in the HTML file being tested.

Example:

```html
<link rel="stylesheet" href="styles/32-style.css">
```

This will apply the most complete version of the stylesheet sequence.

## Notes

- Intermediate files intentionally reflect each task step rather than a single optimized production stylesheet.
- Some tasks explicitly do not require W3C validation.
- The final sequence was completed in order from `1-style.css` through `32-style.css`.

## Author

Holberton School student project for the **Techium CSS Advanced** module.
