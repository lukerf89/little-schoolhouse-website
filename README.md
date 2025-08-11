# Little Schoolhouse Website

A static website supporting Arkansas homeschool families with resources, community connections, and Arkansas LEARNS Act guidance.

## Project Overview

The Little Schoolhouse website serves Arkansas homeschool families by providing:
- Practical curriculum planning resources
- Arkansas LEARNS Act guidance and application help
- Community connection opportunities
- Family story sharing and encouragement

## Website Structure

```
/
├── index.html              # Homepage - Our story and overview
├── curriculum.html         # Curriculum planning resources
├── arkansas.html          # Arkansas LEARNS Act guide
├── community.html         # Community connections
├── css/
│   └── styles.css         # Main stylesheet with prairie design
├── js/
│   └── main.js           # JavaScript for navigation and interactions
├── images/               # Image assets (placeholder directory)
└── README.md            # This file
```

## Design Features

### Visual Design
- **Theme**: Prairie schoolhouse aesthetic with American primitive design
- **Colors**: Cream (#FAF6F0), wood tones (#8B6F47), vintage typography
- **Typography**: Georgia and Baskerville serif fonts for warm, authentic feel
- **Layout**: Mobile-first responsive design optimized for rural internet

### Technical Features
- Static HTML/CSS/JavaScript (no backend required)
- Netlify Forms integration for contact forms and email signups
- Mobile-responsive navigation with hamburger menu
- Smooth scrolling and accessibility features
- Form validation and user feedback
- Search engine optimized with proper meta tags

## Key Components

### Navigation
- Header: Little Schoolhouse | Our Story | Arkansas Guide | Community | Survey
- Mobile-responsive hamburger menu
- Survey CTA button prominently featured

### Contact Forms
All forms are configured for Netlify Forms:
- Contact form on homepage
- Email newsletter signups throughout site
- Community story sharing form
- Curriculum-specific newsletter signup

### Email Integration Points
Multiple opportunities for email list building:
- Homepage hero newsletter signup
- Page-specific newsletter forms
- Footer newsletter signup
- Contact forms with email capture

## Deployment Instructions

### Option 1: Netlify (Recommended)
1. Push this repository to GitHub
2. Connect GitHub repository to Netlify
3. Deploy settings:
   - Build command: (leave empty for static site)
   - Publish directory: `/` (root directory)
4. Forms will automatically work with Netlify Forms

### Option 2: Manual Upload
1. Upload all files to your web hosting service
2. Ensure proper file structure is maintained
3. Contact forms will need alternative service (FormSpree, etc.)

## Configuration Needed

### Before Going Live
1. **Update Survey Links**: Replace all instances of `https://forms.gle/YOUR_FORM_ID` with actual Google Form URL
2. **Email Address**: Confirm `luke@little-schoolhouse.com` is active
3. **Contact Forms**: Test all Netlify forms after deployment
4. **SEO**: Review meta descriptions and titles for each page
5. **Analytics**: Add Google Analytics code if desired

### Google Forms Integration
The site includes multiple references to a 5-minute survey. Create a Google Form and replace:
- Navigation survey button
- Multiple survey CTA sections
- Footer survey links

## Content Management

### Adding New Content
- **Blog Posts**: Can be added as new HTML pages following the existing template structure
- **Resources**: Additional resources can be added to curriculum.html or as new pages
- **Community Spotlights**: Can be integrated into community.html

### Updating Information
- **LEARNS Act Info**: arkansas.html should be updated as legislation changes
- **Community Groups**: community.html regional sections should be updated periodically
- **Curriculum Reviews**: curriculum.html can be expanded with new reviews and resources

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Graceful degradation for older browsers
- No JavaScript dependencies for core functionality

## Performance

- Optimized for rural internet connections
- Lightweight CSS and JavaScript
- No external dependencies except Google Fonts (fails gracefully)
- Images optimized and lazy-loaded

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (when added)
- Keyboard navigation support
- Screen reader compatible
- High contrast color scheme

## Future Enhancements

Potential future additions:
- Blog/article section
- Resource library with downloadable PDFs
- Event calendar integration
- Photo gallery of community events
- Testimonials section
- Arkansas homeschool directory

## Contact Information

**Website Owner**: Luke Freeman  
**Email**: luke@little-schoolhouse.com  
**Purpose**: Supporting Arkansas homeschool families

## License

This website is created for the Freeman family's Little Schoolhouse project. Content and code can be used as reference for other homeschool support websites.

---

*Made with love in Arkansas* ❤️