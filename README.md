# Huntington Beach Chamber of Commerce

A responsive website for the Huntington Beach Chamber of Commerce, built as a WDD 231 class project.

## Pages

- **Home** (`index.html`) - Landing page with events, membership benefits, and company spotlights
- **Directory** (`directory.html`) - Browse local business members with grid/list views
- **Join** (`join.html`) - Membership application with tiered plans
- **Discover** (`discover.html`) - Explore attractions and areas around Huntington Beach
- **Thank You** (`thankyou.html`) - Confirmation page after form submission

## Project Structure

```
chamber/
├── data/
│   ├── members.json       # Business member directory data
│   └── areas.json         # Local areas/attractions data
├── images/                # Site images, icons, and SVGs
├── scripts/
│   ├── areas.js           # Renders discover page areas
│   ├── date.js            # Footer date/year display
│   ├── form.js            # Form handling
│   ├── members.js         # Directory member cards
│   ├── messages.js        # Visitor messages/banners
│   ├── modals.js          # Membership tier modals
│   ├── navigation.js      # Hamburger menu toggle
│   └── spotlight.js       # Homepage spotlight cards
├── styles/
│   ├── normalize.css      # CSS reset
│   ├── directory.css      # Base styles
│   ├── directory-medium.css # Medium breakpoint
│   └── directory-large.css  # Large breakpoint
├── index.html
├── directory.html
├── discover.html
├── join.html
└── thankyou.html
```

## Technologies

- HTML5, CSS3, vanilla JavaScript
- Responsive design with mobile-first approach
- Google Fonts (Playfair Display, Lato)
- JSON data files for dynamic content

## Author

Carson Landvatter
