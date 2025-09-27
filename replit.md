# Overview

This is a personal portfolio website for Muhammad Ghufran, a Full Stack Developer with expertise in React.js, WordPress, AI Integration, and modern web applications. The site showcases professional services, featured projects, client testimonials, and provides contact functionality. It's built as a modern, responsive single-page application with dark/light theme support and interactive animations.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Pure HTML/CSS/JavaScript SPA**: Built without frameworks for optimal performance and simplicity
- **Component-based structure**: Modular JavaScript with state management for interactive elements
- **CSS Custom Properties**: Comprehensive theming system supporting light/dark modes
- **Responsive Design**: Mobile-first approach with dedicated mobile navigation
- **Progressive Enhancement**: Core functionality works without JavaScript, enhanced with interactive features

## State Management
- **Centralized State Object**: Single state object managing application state including current role display, mobile menu status, and modal states
- **Event-driven Updates**: DOM manipulation through event listeners and state updates
- **Animation System**: Custom typing animation for role rotation and smooth transitions

## Styling Architecture
- **CSS Custom Properties**: Systematic color theming with HSL values for consistent design tokens
- **Utility-first Approach**: Reusable CSS classes for common patterns
- **Component Styling**: Scoped styles for major UI components (header, hero, cards, modals)
- **Theme Switching**: Runtime CSS custom property updates for instant theme changes

## Interactive Features
- **Typewriter Animation**: Dynamic text animation cycling through professional roles
- **Project Modal System**: Detailed project views with lazy-loaded content
- **Contact Form**: EmailJS integration for direct email functionality
- **Mobile Menu**: Touch-friendly navigation with smooth animations

## Performance Optimizations
- **Lazy Loading**: Deferred loading of non-critical components and images
- **Efficient DOM Updates**: Minimal DOM manipulation with targeted updates
- **CSS Transitions**: Hardware-accelerated animations for smooth performance
- **Image Optimization**: Optimized external image URLs with proper sizing

# External Dependencies

## CDN Libraries
- **Google Fonts**: Inter font family for typography consistency
- **Lucide Icons**: Comprehensive icon library loaded via CDN
- **EmailJS**: Client-side email service for contact form functionality

## Third-party Services
- **Unsplash**: External image hosting for project screenshots and backgrounds
- **EmailJS Service**: Email delivery system for contact form submissions

## Browser APIs
- **Local Storage**: Theme preference persistence
- **Intersection Observer**: Scroll-based animations and lazy loading
- **CSS Custom Properties**: Dynamic theming support

## Development Tools
- **Modern ES6+**: Arrow functions, template literals, destructuring
- **CSS Grid/Flexbox**: Modern layout systems for responsive design
- **Media Queries**: Responsive breakpoints for mobile/desktop optimization