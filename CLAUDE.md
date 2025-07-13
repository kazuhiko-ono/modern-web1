# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Multi-page website for a learning support company (toiee Lab certified partner) offering "Beyond Learning" seminars and consultation services.

## Project Structure

```
/
├── index.html              # Homepage with hero and service overview
├── about.html              # Company info and philosophy
├── services.html           # Services overview page
├── seminars/               # Individual seminar detail pages
│   ├── creative-question.html
│   ├── leadership.html
│   ├── communication.html
│   ├── goodself.html
│   ├── means-purpose.html
│   ├── meta-memory.html
│   ├── reflection.html
│   ├── reading.html
│   └── mental-model.html
├── consultation.html       # Individual consultation details
├── testimonials.html       # Case studies and customer voices
├── faq.html               # Frequently asked questions
├── contact.html           # Contact and application forms
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
└── favicon.ico
```

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **CSS Framework**: Tailwind CSS (CDN)
- **Animations**: AOS + Animate.css
- **Icons**: Lucide icons
- **Fonts**: Google Fonts (Japanese support)
- **Images**: Unsplash.com

## Design System

- **Colors**: 
  - Primary: Soft Navy (#2563EB)
  - Accent: Light Blue (#60A5FA), Soft Pink (#F9A8D4), Light Green (#86EFAC)
  - Background: White (#FFFFFF), Light Gray (#F8FAFC)
- **Design**: Apple-inspired minimal with warm elements
- **Responsive**: Mobile-first approach

## Development Commands

- Open any HTML file directly in browser for testing
- Use browser dev tools for responsive testing
- Validate HTML using W3C validator
- Test forms functionality manually

## SEO Requirements

- Semantic HTML structure (header, nav, main, section, article, footer)
- Meta tags for description, keywords, og:image
- Alt attributes for all images
- Proper heading hierarchy (H1-H6)
- Structured data implementation