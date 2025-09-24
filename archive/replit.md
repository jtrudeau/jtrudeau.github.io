# Momentum Labs Logbook - Replit Setup

## Overview
This is a Jekyll-based static blog called "Momentum Labs Logbook" with a retro-futuristic theme inspired by DESY institute magnets in Hamburg. The site features a dark theme with blue, red, and yellow color palette and uses Space Grotesk and Orbitron fonts for a minimalist futuristic look.

## Project Setup - September 24, 2025
- **Source**: GitHub import of Jekyll static site
- **Language**: Ruby 3.1 with Jekyll
- **Environment**: Successfully configured for Replit
- **Host Configuration**: Serves on 0.0.0.0:5000 for proper proxy support

## Architecture
- **Static Site Generator**: Jekyll 3.10.0
- **Dependencies**: GitHub Pages gem bundle (98 gems total)
- **Styling**: Inline CSS in default layout with retro-futuristic design
- **Content**: Blog posts system with pagination support
- **Deployment**: Configured for autoscale deployment

## Current Features
- Hero section with "Hello, world" broadcast theme
- Blog post grid layout with neon-inspired cards
- Responsive design optimized for mobile
- RSS feed and sitemap generation
- Google Analytics integration (UA-43339302-11)
- Social media footer links

## Technical Configuration
- **Development Server**: `bundle exec jekyll serve --host 0.0.0.0 --port 5000 --livereload`
- **Build Command**: `bundle exec jekyll build`
- **Output Directory**: `_site/`
- **Config File**: `_config.yml`

## Content Structure
- Homepage: `index.html` (hero + latest posts)
- Layouts: `_layouts/default.html` (main template with embedded CSS)
- Posts: `_posts/` directory (currently empty - shows empty state)
- Config: `_config.yml` (site metadata and settings)

## Development Notes
- Site successfully loads with retro-futuristic design
- Empty state displayed for blog posts (no content yet)
- Minor warning about missing 'page' layout for 404.md (non-critical)
- LiveReload enabled for development
- All dependencies installed and working

## Deployment Status
- ✅ Development environment: Working perfectly
- ✅ Production deployment: Configured for autoscale
- ✅ Build process: Ready for deployment

## Next Steps for Content
When ready to add content, create blog posts in `_posts/` directory using Jekyll naming convention: `YYYY-MM-DD-title.md`