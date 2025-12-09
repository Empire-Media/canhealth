# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Can Healthcare Supplier is a static single-page website for a healthcare product distributor (sister company to PB Pharma). The site is built with vanilla HTML, CSS, and JavaScript with no build process or dependencies.

## File Structure

- `index.html` - Main website file containing all HTML structure, embedded CSS styles, and JavaScript functionality
- `logo.jpg` - Company logo image

## Development

**Running the site locally:**
```bash
# Open directly in browser
xdg-open index.html

# OR serve with Python's built-in server
python3 -m http.server 8000
# Then navigate to http://localhost:8000
```

**Testing changes:**
Simply open or refresh `index.html` in a web browser. No build process required.

## Code Architecture

This is a single-page application with:

- **Embedded CSS** (lines 7-705): All styles are in a `<style>` tag within the `<head>`
- **HTML structure** (lines 708-908): Semantic sections including header, hero, about, services, products, contact, and footer
- **Embedded JavaScript** (lines 910-941): Client-side functionality for smooth scrolling, form handling, and CTA buttons

**Color scheme:**
- Primary blue: `#004D99`
- Accent yellow: `#FFC300`
- Dark backgrounds: `#1a1a1a`, `#0d0d0d`

**Key sections:**
- Header with sticky navigation
- Hero section with gradient background
- Licensed distributor information
- About section (25+ years experience through PB Pharma)
- Why choose us (3 cards)
- Services (3 cards for different client types)
- Working process (3 steps)
- Contact form with company details
- Footer

## JavaScript Functionality

All interactivity is handled by vanilla JavaScript at the bottom of `index.html`:

1. **Smooth scrolling** - Handles anchor link navigation
2. **Form submission** - Prevents default, shows alert, resets form
3. **CTA buttons** - Scroll to contact section on click

## Responsive Design

The site includes mobile-responsive CSS with a breakpoint at 768px (lines 670-705). Grid layouts collapse to single columns on smaller screens.

## Contact Information

- Email: info@canhealthcaresupplier.com
- Phone: (888) 555-5267
- Address: 123 Healthcare Avenue, Suite 500, Toronto, ON, Canada M5V 3A8

## Related Company

Sister company: PB Pharma Canada (pbpharma.com)
