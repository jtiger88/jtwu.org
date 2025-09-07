# JT Wu Personal Website - Claude Context

## Project Overview
Professional website for Jonathan "JT" Wu, showcasing his work as a civic-minded entrepreneur and strategic finance advisor. The current implementation has evolved significantly from the original brief into a sophisticated magnolia-themed design.

## Current Design & Branding
**Color Palette** (evolved from original Princeton Orange):
- `--magnolia-cream: #faf8f5` (main background)
- `--warm-gold: #c9a876`
- `--sage-green: #8a9a8b`
- `--dark-sage: #5d6b5e`
- `--charcoal: #3a3d3a`
- `--accent-gold: #b8965d`

**Typography**: Playfair Display (headings) + Inter (body) - maintained from original brief

**Key Design Features**:
- Beautiful magnolia SVG pattern in hero background with botanical decorative elements
- Sophisticated logo hover effects with grayscale/opacity transitions and translateY animations
- Clean, professional layout with subtle botanical touches throughout
- Mobile-responsive design with backdrop-filter blur effects

## Tech Stack
- Static HTML/CSS/JavaScript (index.html)
- Modern responsive design with CSS custom properties
- Ready for deployment on Vercel/Netlify

## Key Files
- Main website: `index.html` 
- Additional pages: `about.html`, `advisory.html`, `contact.html`
- Design documentation: `DESIGN_CHECKPOINT.md`
- Original brief reference: `../Website Schema/Jtwu Website Brief.pdf`

## Design Evolution
**Original Brief** (in Website Schema folder):
- Navy/Slate/White with Princeton Orange accents
- Clean serif + sans serif pairing
- Focus on credibility and cross-sector impact

**Current Implementation**:
- Magnolia/sage botanical theme (ties to "Magnolia Prospect" advisory brand)
- Enhanced with decorative SVG magnolia patterns
- Sophisticated hover interactions
- More elegant and distinctive than typical corporate designs

## Development Notes
- Images needed: `jt-wu-professional.jpg` (500x500px), `jt-wu-og-image.jpg` (1200x630px)
- Contact form ready for backend integration (currently uses setTimeout mock)
- SEO optimized with structured data for Jonathan "JT" Wu
- WCAG compliant accessibility with proper focus states
- Current layout is approved and should be maintained

## Recent Updates (Latest Session)
**About Page Layout Redesign - Willkie-Inspired Professional Presentation:**
- **Mobile Profile Layout**: Implemented Willkie-style mobile About page with clean profile header featuring photo next to name/title, contact details with icons (📍 📧 🔗 🎓 📄), and bio text below - maintaining beloved hero section above
- **Desktop Bio Structure**: Updated desktop bio section to match Willkie professional layout with photo/contact sidebar on left (1fr), name/title info on right (2fr), creating cleaner professional presentation
- **Contact Icons Integration**: Added contact icons throughout mobile version replacing text labels ("Email:" → ✉️) for cleaner, modern aesthetic 
- **vCard Download**: Integrated vCard download button with document icon for professional networking functionality
- **Layout Debugging**: Resolved mobile layout conflicts, logo overflow issues, and hero section integration problems through careful grid restructuring
- **Grid Optimization**: Fixed organizations grid to prevent overflow on mobile with proper max-width constraints and reduced gap spacing
- **Responsive Integration**: Ensured mobile profile section works seamlessly below existing hero sections without breaking magnolia theme or animations

**CRITICAL LESSONS LEARNED FROM MISTAKES:**
- **NEVER hide hero sections** - User explicitly loves the hero sections ("Rooted in Georgia. Engaged Globally.") and wants them maintained across all pages
- **Test changes incrementally** - Made too many changes at once, breaking the bio content visibility and layout completely
- **Always preserve working functionality** - When user says something works, don't break it while trying to improve other parts
- **Mobile layout complexity** - Adding custom mobile profile sections created conflicts with existing bio content - simpler approaches work better
- **Desktop vs Mobile separation** - When user asks for desktop changes, focus ONLY on desktop without touching mobile layouts
- **Communication clarity** - User wanted Willkie-style improvements, not complete replacement of existing functional layouts

**Latest Updates (Current Session):**
- **Mobile Logo Layout Fixes (Sept 2024)**: Fixed mobile layout issues across homepage and About page where organization logos were spilling off right side of screen
- **About Page Mobile Optimization**: Reduced gap from 2rem to 1.5rem, added container constraints (`max-width: 100%`, `padding: 0 1rem`), reduced logo sizing (100px vs 140px width), optimized padding and min-height
- **Homepage Mobile Consistency**: Applied same mobile alignment improvements to match About page - reduced logo sizing (100px width, 50px height), added container constraints, consistent mobile experience
- **Standard Workflow Established**: Push changes immediately after implementation for live review on Vercel

**Previous Updates:**
- **Mobile Navigation**: Standardized hamburger menu with proper alignment (`left: 0` on pseudo-elements), solid `var(--magnolia-cream)` background, backdrop-filter blur, rounded corners, and consistent font sizing across all pages
- **Hero Section Spacing**: Fixed white bar gaps by updating hero padding to `8rem 0 5rem` for proper spacing below fixed navigation
- **Mobile Typography**: Added missing `font-size: 2.2rem` to mobile hero titles on About page, removed font-size overrides from mobile nav links to match Home page behavior
- **Animation Integration**: Successfully integrated magnolia leaf SVG patterns and fadeInUp animations across About, Advisory, and Contact pages to match homepage aesthetic
- **Notion Integration**: Added Finance Sprint advisory offering section to Advisory page with tasteful callout styling
- **Live Notion Link**: Connected Finance Sprint CTA button to live Notion page (https://striped-hammer-336.notion.site/Finance-Sprint-Unlock-What-s-Next-26697b8c04828057b527f33ee3275754) with target="_blank" for seamless user experience
- **Brand Assets**: Created custom Notion header banner using correct brand fonts (Playfair Display for titles, Inter for body) and magnolia theme colors, saved as `finance-sprint-notion-banner.png` in Website Schema folder
- **Dedicated Finance Sprint Page**: Created comprehensive `finance-sprint.html` with full content conversion from Notion to magnolia aesthetic, including hero section, process breakdown, case study cards with testimonials, and clear CTAs for booking
- **Enhanced Advisory Hero CTAs**: Added prominent dual-button CTA in Advisory hero section featuring "Strategic Advisory" consultation and "Founder Jumpstart" Finance Sprint options with structured styling (label/title/details format)  
- **CTA Button Optimization**: Refined button sizing and typography for consistent single-line text layout across desktop (320px-350px width) and mobile (340px max-width) with proper spacing and hover effects
- **Case Study Cards**: Implemented responsive 3-column desktop layout for Finance Sprint case studies (Liberty Home Co., JLC Inc., Aether Group) with company details, results, and client testimonials in balanced grid format

## Content Structure (per original brief)
- Hero: "Capital & Community. Strategy with Purpose."
- About: "Rooted in Georgia. Engaged Globally. Driven by Impact."
- Advisory Work: Magnolia Prospect white-glove services
- Civic Leadership: Preface nonprofit, Gwinnett Library System
- Ventures: AAVM, Korean/Chinese American Voices, etc.
- Speaking & Media opportunities
- Contact form and social links

## Deployment Status
- **Git Repository**: https://github.com/jtiger88/jtwu.org.git
- **Live Site**: Deployed on Vercel (auto-deploys from GitHub main branch)
- **Domain**: jtwu.org (per meta tags)
- **Workflow**: Standard practice is to push changes immediately after implementation for live review