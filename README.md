# Portfolio Website

A modern, responsive portfolio website showcasing your expertise in data analytics, consulting, and AI context engineering.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic navigation
- **Performance Optimized**: Fast loading with efficient CSS and JavaScript
- **Accessible**: Built with semantic HTML and accessibility best practices

## Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Customization Guide

### 1. Personal Information
Edit `index.html` to update:
- **Name**: Replace "Your Name" throughout the file
- **Contact Information**: Update email, phone, and LinkedIn in the contact section
- **Professional Title**: Modify the hero subtitle
- **Bio**: Update the about section with your personal story

### 2. Experience Section
In the timeline section, update:
- Job titles and companies
- Date ranges
- Bullet points describing your achievements
- Add or remove timeline items as needed

### 3. Skills
Modify the skills grid to reflect your expertise:
- Update skill categories
- Add/remove specific technologies
- Change icons (using Font Awesome classes)

### 4. Projects
Update the projects showcase:
- Replace project titles and descriptions
- Update technology tags
- Add real project links
- Replace placeholder project images

### 5. Color Scheme
To change colors, edit `styles.css`:
- **Primary Blue**: `#2563eb` - Main brand color
- **Secondary Purple**: `#667eea` - Gradient accent
- **Text**: `#1f2937` - Primary text color
- **Light Background**: `#f8fafc` - Section backgrounds

### 6. Adding Your Photo
Replace the profile placeholder:
1. Add your photo to the project folder
2. In `index.html`, replace the `.profile-placeholder` div with:
```html
<img src="your-photo.jpg" alt="Your Name" class="profile-image">
```
3. Add CSS for `.profile-image` in `styles.css`

## External Dependencies

The website uses these CDN resources:
- **Font Awesome 6.0.0**: For icons
- **Google Fonts (Inter)**: For typography

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Getting Started

1. Download all files to a folder
2. Customize the content as described above
3. Open `index.html` in a web browser to preview
4. For deployment, upload all files to your web hosting service

## Deployment Options

- **GitHub Pages**: Free hosting for public repositories
- **Netlify**: Free tier with easy drag-and-drop deployment
- **Vercel**: Free hosting with automatic deployments
- **Traditional Web Hosting**: Upload files to any web server

## Tips for Success

1. **Keep Content Concise**: Use clear, impactful language
2. **Add Real Projects**: Include actual work samples with results
3. **Professional Email**: Use a professional email address
4. **Regular Updates**: Keep your portfolio current with new projects
5. **Test on Mobile**: Ensure everything works well on mobile devices

## SEO Optimization

To improve search engine visibility:
1. Add meta descriptions to the `<head>` section
2. Include relevant keywords in your content
3. Add alt tags to images
4. Consider adding a sitemap.xml

## Contact Form Integration

The contact form currently shows an alert. To make it functional:
1. Use a service like Formspree, Netlify Forms, or EmailJS
2. Update the form action and method attributes
3. Add proper backend handling for form submissions

---

**Need help customizing?** Feel free to reach out for assistance with modifications or additional features.