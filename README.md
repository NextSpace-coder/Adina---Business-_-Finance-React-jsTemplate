# Digital Agency

A professional and modern React template designed for digital agencies, business consulting firms, and finance companies. This template provides comprehensive solutions for showcasing services, team, portfolio, and business information.

## Project Type

**Business Showcase / Digital Agency** - A comprehensive multi-page website template for professional services featuring service presentations, portfolio showcases, team profiles, and client testimonials.

## Key Features

- Modern responsive design for business and finance sectors
- Comprehensive service and portfolio showcases
- Professional team member profiles
- Client testimonials and case studies
- Multi-page navigation with detailed sections
- Contact forms and business information
- Blog system with article pages
- FAQ and support sections
- Video integration and interactive elements
- Mobile-first responsive design

## Technology Stack

- **Frontend Framework**: React 18+
- **Build Tool**: Vite 5.4+
- **Styling Solution**: CSS + Bootstrap 5.2+
- **Routing**: React Router Dom v6
- **Animation Libraries**: 
  - WOW.js v1.2.2
  - React CountUp v6.5.3
  - Parallax.js v3.1.0
- **UI Components**: 
  - React Slick v0.30.2
  - React Iframe v1.8.5
  - Reactjs Popup v2.0.6
  - Swiper v6.8.4
- **Additional Libraries**:
  - Yet Another React Lightbox v3.21.6
  - Imagesloaded v5.0.0
  - jQuery v3.6.0
- **Build Enhancement**: vite-tagger (custom build optimization)
- **Backend Ready**: Supabase integration configured

## Installation & Setup

1. **Install Dependencies**
   ```bash
   npm install
   # or
   pnpm install
   ```

2. **Development Server**
   ```bash
   npm run dev
   # or
   pnpm run dev
   ```
   The application will be available at `http://localhost:8080`

3. **Build for Production**
   ```bash
   npm run build
   # or
   pnpm run build
   ```

4. **Preview Production Build**
   ```bash
   npm run preview
   # or
   pnpm run preview
   ```

## Project Structure

```
src/
├── components/
│   ├── about/              # About sections (multiple variants)
│   ├── awards/             # Awards and achievements
│   ├── blogs/              # Blog components and sidebar
│   ├── brands/             # Brand/client showcases
│   ├── breadcrumb/         # Page navigation breadcrumbs
│   ├── business/           # Business-related sections
│   ├── choose/             # Why choose us sections
│   ├── contact/            # Contact forms and info
│   ├── counter_areas/      # Statistics counters
│   ├── cta/                # Call-to-action sections
│   ├── experience/         # Experience showcases
│   ├── faq/                # FAQ components
│   ├── footers/            # Footer variants
│   ├── headers/            # Header and navigation
│   ├── hero_sections/      # Hero/banner sections
│   ├── history/            # Company history
│   ├── impressions/        # Impression counters
│   ├── map/                # Map integrations
│   ├── portfolio/          # Portfolio showcases
│   ├── services/           # Service presentations
│   ├── subscribe/          # Newsletter subscription
│   ├── team/               # Team member profiles
│   ├── testimonials/       # Client testimonials
│   ├── video/              # Video sections
│   └── work/               # Work process sections
├── pages/                  # Page components
├── assets/                 # Images, fonts, styles
├── integrations/
│   └── supabase/          # Backend integration
└── main.jsx               # Application entry point
```

## Page Functionality

- **Homepage**: Complete business landing page with hero, services, portfolio, team, and testimonials
- **About**: Company information, history, and team details
- **Services**: Detailed service offerings and capabilities
- **Portfolio**: Project showcases and case studies
- **Team**: Team member profiles and expertise
- **Blog**: Article listings and individual blog posts
- **Contact**: Contact information, forms, and location
- **FAQ**: Frequently asked questions and support

## Customization Guide

### Content Customization
- **Service Data**: Update service information in component files
- **Team Profiles**: Modify team member details and photos
- **Portfolio Items**: Replace portfolio projects and descriptions
- **Company Information**: Update business details and contact info

### Styling Customization
- **Global Styles**: Modify main CSS files in assets
- **Component Styles**: Each component has dedicated styling
- **Bootstrap**: Customize Bootstrap variables and utilities
- **Animations**: Configure WOW.js and other animation settings

### Backend Integration
- **Supabase**: Pre-configured in `src/integrations/supabase/`
- **Contact Forms**: Ready for backend integration
- **Content Management**: Expandable for dynamic content

## Development Notes

- **Build Output**: Production files generated in `dist/` directory
- **ESLint**: Code linting configured for React best practices
- **Hot Reload**: Development server supports hot module replacement
- **Responsive Design**: Mobile-first approach with Bootstrap grid
- **SEO Ready**: Proper meta tags and semantic HTML structure

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design for all screen sizes

## License

This is a commercial template. Please ensure you have proper licensing for production use.