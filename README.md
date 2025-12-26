# Bernardo - Personal Branding Website

A professional personal branding website for digital communication and learning strategy consulting.

## Overview

This is a modern, responsive landing page built with Tailwind CSS and Lucide Icons, designed to showcase expertise in digital communication, instructional design, and online learning strategies.

## Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Tailwind CSS** - Utility-first CSS framework for rapid development
- **Lucide Icons** - Beautiful, consistent icon set
- **Section Navigation** - Smooth scrolling between sections
- **Contact Form** - Ready-to-integrate contact form

## Project Structure

```
bernardo-website/
├── index.html              # Main HTML file
├── assets/
│   ├── images/            # Image assets (add your photos here)
│   ├── css/               # Custom CSS files (if needed)
│   └── js/                # Custom JavaScript files (if needed)
└── README.md              # This file
```

## Getting Started

### Option 1: Open Directly
Simply open `index.html` in your web browser to view the website locally.

### Option 2: Use a Local Server
For a better development experience, use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server

# Using VS Code Live Server extension
Right-click index.html → Open with Live Server
```

Then visit `http://localhost:8000` in your browser.

## Customization Guide

### 1. Replace Placeholder Content

#### Profile Photo
- Add your professional photo to `assets/images/`
- Replace the placeholder div in the Hero section (line ~88) with:
```html
<img src="assets/images/your-photo.jpg" alt="Bernardo" class="w-64 h-64 rounded-full shadow-2xl border-4 border-secondary object-cover">
```

#### Email Address
- Update the contact email (line ~308):
```html
<a href="mailto:your_email@example.com" ...>
```

#### Social Media Links
- Update footer links (line ~327):
```html
<a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
<a href="https://twitter.com/yourhandle">Twitter</a>
<a href="https://researchgate.net/profile/yourprofile">ResearchGate</a>
```

### 2. Color Scheme

The website uses a custom color palette defined in the Tailwind config:

- **Primary** (Royal Blue): `#1D4ED8`
- **Secondary** (Coral Orange): `#F97316`
- **Dark Background**: `#020617`
- **Light Background**: `#F8FAFC`

To change colors, edit the Tailwind config in `index.html` (line ~17).

### 3. Content Sections

- **Hero** (line ~58): Main headline and call-to-action
- **Social Proof** (line ~101): Certifications and credentials
- **Services** (line ~127): Three main service offerings
- **About** (line ~191): Expertise and credentials
- **Testimonials** (line ~227): Client testimonials
- **Contact** (line ~261): Contact form and CTA

### 4. Contact Form

The contact form is currently a front-end only placeholder. To make it functional, you'll need to:

#### Option A: Use a Form Service
- **Netlify Forms** (if hosting on Netlify): Add `data-netlify="true"` to the form tag
- **Formspree**: Add `action="https://formspree.io/f/your-id"` to the form tag
- **EmailJS**: Integrate with JavaScript for client-side email sending

#### Option B: Backend Integration
Connect to your own backend API or serverless function to handle form submissions.

## Deployment

### Deploy to Netlify
1. Create account at [netlify.com](https://netlify.com)
2. Drag and drop the `bernardo-website` folder
3. Your site is live!

### Deploy to Vercel
```bash
npx vercel
```

### Deploy to GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select your branch and save

### Deploy to Any Static Host
Simply upload all files to your hosting provider (the website is 100% static HTML/CSS/JS).

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Dependencies

All dependencies are loaded via CDN:
- **Tailwind CSS**: v3.x (via cdn.tailwindcss.com)
- **Lucide Icons**: Latest (via unpkg.com)
- **Inter Font**: Latest (via Google Fonts)

No build process or npm installation required!

## Future Enhancements

Consider adding:
- [ ] Mobile hamburger menu for navigation
- [ ] Dark mode toggle
- [ ] Blog section
- [ ] Portfolio/case studies section
- [ ] Animated statistics/metrics
- [ ] Newsletter signup
- [ ] Multi-language support
- [ ] SEO optimization (meta tags, structured data)
- [ ] Google Analytics integration

## Performance Tips

1. Optimize images before uploading (use WebP format)
2. Consider self-hosting Tailwind CSS for production
3. Add proper meta tags for SEO
4. Implement lazy loading for images
5. Consider moving to a build system (Next.js, Vite) for better optimization

## License

This project is private and proprietary.

## Support

For questions or support, contact Bernardo directly.

---

Built with care for digital communication excellence.
