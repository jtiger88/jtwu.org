# JT Wu Personal Website

A professional website for Jonathan "JT" Wu showcasing his work as a civic-minded entrepreneur and strategic finance advisor.

## Features

- **Modern Design**: Clean, professional layout with Princeton Orange accents
- **Responsive**: Mobile-first design that works on all devices  
- **SEO Optimized**: Meta tags, Open Graph, and structured data
- **Accessible**: WCAG compliant with proper focus states
- **Performance**: Optimized animations and loading states
- **Contact Form**: Enhanced form with validation (ready for backend integration)

## Deployment Options

### Option 1: GitHub + Vercel (Recommended)

1. **Create GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial website commit"
   git remote add origin https://github.com/YOUR_USERNAME/jtwu-website.git
   git push -u origin main
   ```

2. **Deploy to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Deploy automatically
   - Add custom domain in project settings

### Option 2: Netlify

1. **Deploy to Netlify**
   - Drag and drop your files to [netlify.com/drop](https://netlify.com/drop)
   - Or connect your GitHub repo for automatic deployments
   - Configure custom domain in site settings

### Option 3: Traditional Web Hosting

- Upload `jt-wu-website.html` as `index.html` to your web server
- Add any additional assets (images, etc.)
- Configure SSL certificate for HTTPS

## Setup Requirements

### Images Needed
- `jt-wu-professional.jpg` - Professional headshot (500x500px recommended)
- `jt-wu-og-image.jpg` - Social media sharing image (1200x630px)

### Contact Form Integration
The contact form is ready for backend integration. For production:

1. **Netlify Forms** (easiest):
   - Add `netlify` attribute to form tag
   - Forms automatically handled by Netlify

2. **Custom Backend**:
   - Replace the `setTimeout` in the form handler with actual API call
   - Uncomment the fetch code in the JavaScript

3. **Third-party Services**:
   - Formspree, EmailJS, or similar services
   - Just update the form action URL

## Customization

### Colors
Edit the CSS variables in the `<style>` section:
```css
:root {
    --navy: #1e3a5f;
    --slate: #4a5568;
    --princeton-orange: #ff6b35;
    --warm-gold: #d4a574;
    --light-gray: #f7fafc;
    --white: #ffffff;
}
```

### Content
All content sections are clearly marked in the HTML. Update text directly in the file or consider migrating to a CMS for easier updates.

### Analytics
Add Google Analytics by including the GA4 tracking code in the `<head>` section.

## Performance Tips

- Compress and optimize images before uploading
- Use WebP format for better compression
- Consider implementing lazy loading for images
- Enable compression on your web server

## Browser Support

- Chrome 60+
- Firefox 55+  
- Safari 12+
- Edge 79+

## Future Enhancements

- Blog integration with Markdown support
- CMS integration (Sanity, Contentful, etc.)
- Newsletter signup integration
- Speaking engagement calendar
- Portfolio/case study pages
- Multi-language support

## Maintenance

- Update content quarterly
- Review and refresh design annually
- Monitor performance with PageSpeed Insights
- Keep dependencies and hosting platform updated