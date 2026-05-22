# Cursor Website Clone (HTML + CSS)

A static clone of the Cursor website built using pure HTML and CSS.

The project was created to strengthen frontend fundamentals by recreating a production-style SaaS landing page without using JavaScript frameworks, component libraries, or CSS frameworks. The focus was on understanding layout systems, positioning, responsiveness concepts, and modern UI structure using only core web technologies.

## Live Demo

https://ashu73909.github.io/cursorWebPage-clone/

## Repository

https://github.com/ashu73909/cursorWebPage-clone

## Tech Stack

- HTML5
- CSS3
- Flexbox
- CSS Grid
- CSS Variables
- Git & GitHub
- GitHub Pages

## Features

- Multi-section landing page
- Flexbox and Grid based layouts
- Responsive container architecture
- Hero section with CTA
- Company logo showcase section
- Feature sections with text and images
- Testimonials section
- Changelog section
- About/Team section
- Recent Highlights section
- Call-to-action section
- Footer with multi-column navigation
- Consistent dark theme styling

## Recreated Sections

The following sections from the original Cursor website were recreated:

- Navigation Bar
- Hero Section
- Trusted Companies Section
- Feature Sections
- Testimonials Section
- Stay on the Frontier Cards Section
- Changelog Section
- About / Team Section
- Recent Highlights Section
- Call-to-Action Section
- Footer Section

## Layout Improvements & Learning Summary

While recreating the Cursor website, I explored how professional SaaS landing pages maintain visual balance across different screen sizes.

### Initial Challenge

Most sections originally relied on percentage-based widths. While this worked on standard screens, content could continue expanding on very large displays, reducing readability and making the layout feel less polished.

### Improvements Made

- Introduced reusable CSS variables for layout management
- Created a shared container sizing system
- Added `max-width` constraints to prevent content from growing indefinitely on large screens
- Centralized container styling for easier maintenance
- Studied layout patterns used by production SaaS websites such as Cursor and Mintlify
- Planned wrapper-container architecture for full-width background sections while keeping content centered

### Outcome

- More consistent spacing across sections
- Better readability on large monitors
- Cleaner and more maintainable CSS
- Improved understanding of responsive layout systems
- Practical experience with production-style container architecture

## Fonts Used

Primary font stack:

```css
Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif
```

Inter is commonly used in modern interfaces because of its readability and clean appearance.

## Color Palette

### Primary Colors

- Background: `rgb(21, 17, 1)`
- Primary Text: `#F7F7F4`
- Accent Color: `#F54E00`

### Secondary Colors

- Card Background: `#1A1A12`
- Border Color: `rgba(255, 255, 255, 0.08)`
- Muted Text: Reduced opacity of primary text

## What I Learned

- Structuring large HTML layouts
- Building reusable layout systems
- CSS Variables for maintainability
- Advanced CSS positioning techniques
- Real-world Flexbox usage
- Real-world CSS Grid usage
- Container and max-width architecture
- Replicating production-level UI designs
- Organizing assets and project structure
- Deploying static websites using GitHub Pages

## Project Structure

```text
cursorWebPage-clone/
│
├── index.html
├── style.css
├── assets/
│   ├── images/
│   └── icons/
│
└── README.md
```

## Future Improvements

- Complete responsive support using media queries
- Mobile navigation menu
- Accessibility improvements
- Performance optimization
- Better image optimization
- Additional hover and scroll animations
- Code refactoring and component-style organization
- Dark/Light theme toggle
- Pixel-perfect responsiveness across devices

## Screenshots

<img width="1919" height="906" alt="Cursor Clone Screenshot" src="https://github.com/user-attachments/assets/80c64bce-9e9f-4598-81d0-297e5da2bb0f" />

## Author

**Ashutosh Panday**