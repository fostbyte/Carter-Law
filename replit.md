# CarterLaw25 Professional Legal Website

## Overview

CarterLaw25 is a static HTML/CSS website for a professional law firm offering comprehensive legal services. The site showcases the firm's expertise across multiple practice areas including Personal Injury, Family Law, Estate Planning, Business Law, Criminal Defense, and Real Estate Law. Built as a modern, responsive website optimized for client engagement and professional presentation, it features dedicated service pages, contact functionality, and client review integration.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The website follows a traditional multi-page HTML structure with shared CSS styling and navigation components. Key architectural decisions include:

**Static Site Structure**: Pure HTML/CSS implementation without JavaScript frameworks, chosen for simplicity, fast loading times, and compatibility with GitHub Pages hosting. This approach provides excellent SEO performance and minimal maintenance overhead.

**Responsive Design System**: CSS-based responsive layout using Flexbox and CSS Grid, ensuring optimal viewing across desktop, tablet, and mobile devices. The design system uses CSS custom properties (variables) for consistent theming and easy maintenance.

**Component-Based Styling**: Modular CSS architecture with reusable components for buttons, forms, cards, and navigation elements. This promotes consistency across pages and simplifies future updates.

### Page Structure
- **Homepage (index.html)**: Central hub with hero section, about summary, services overview, reviews, and contact information
- **Contact Page (contact.html)**: Dedicated contact form and business information
- **Service Pages**: Individual pages for each practice area located in `/services/` directory
- **Shared Navigation**: Consistent header navigation across all pages with active state management

### Design Patterns
**Professional Legal Theme**: Navy blue and gold color scheme conveys trust and professionalism typical of legal services. Typography combines serif headers (Playfair Display) for elegance with sans-serif body text (Inter) for readability.

**Content Hierarchy**: Clear information architecture with service-specific landing pages, each following a consistent template pattern with hero sections, service details, and call-to-action elements.

**Mobile-First Approach**: Responsive breakpoints ensure functionality across all device sizes, critical for client accessibility and search engine optimization.

## External Dependencies

### Third-Party Services
- **Google Fonts**: Playfair Display and Inter font families for professional typography
- **Font Awesome**: Icon library (v6.4.0) for consistent iconography across service pages and navigation
- **CDN Delivery**: External CSS libraries loaded via CDN for performance and reliability

### Asset Management
- **CSS Framework**: Custom CSS framework stored in `/assets/css/styles.css`
- **Image Placeholders**: SVG placeholders referenced for hero images and visual content
- **Cross-Page Navigation**: Relative linking structure for seamless navigation between service pages and main site sections

### Contact Integration
- **Form Handling**: Contact form configured for POST method (requires backend integration for functionality)
- **Phone Integration**: Click-to-call functionality using tel: protocol for mobile users
- **Location Services**: Prepared structure for Google Maps integration (placeholder implementation)

The architecture prioritizes professional presentation, user experience, and search engine optimization while maintaining simplicity for easy content updates and hosting flexibility.