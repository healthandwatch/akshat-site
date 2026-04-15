# Akshat's Professional Portfolio Website

A professional academic portfolio website for a research student at UC Irvine, styled similarly to faculty portfolio websites like that of Professor Anton Gorodetski at UC Irvine Math Department.

## Site Structure

```
akshat-site/
├── index.html                 # Main homepage with hero, bio, and tiles
├── publications.html          # Publications and research
├── resume.html                # CV and resume
├── contact.html               # Contact information
├── courses/
│   ├── index.html            # Courses landing page
│   ├── math120.html          # Abstract Algebra course page
│   ├── math121.html          # Linear Algebra course page
│   ├── math130.html          # Probability course page
│   └── math140.html          # Elementary Analysis course page
├── assets/
│   └── styles.css            # Main stylesheet
└── README.md                 # This file
```

## Features

✨ **Professional Design** - Inspired by academic portfolio websites like your professor's
- Dark navigation bar with uppercase links
- Hero section with name and title
- Two-column welcome section with bio and profile image
- Tile-based navigation for major sections
- Social media links section
- Responsive and mobile-friendly

📱 **Responsive Layout** - Works seamlessly on desktop, tablet, and mobile devices

🎓 **Academic Focus** - Designed for research students and academics with:
- Course/class pages
- Publications section
- Resume/CV page
- Contact information
- Professional color scheme and typography

🔗 **Easy Navigation** - Consistent navigation across all pages with highlighted active links

## Homepage Sections

1. **Hero Section** - Your name and title as a research student
2. **Welcome Section** - Bio and profile picture with research interests
3. **Navigation Tiles** - Quick links to Classes, Publications, Resume, and Contact
4. **Social Media** - Links to UC Irvine Math Department social profiles

## Customization Guide

### Update Your Profile

Edit `index.html` to customize:
- Your name in the hero section (`<h1>`)
- Your title/affiliation in the subtitle
- Your bio in the welcome section
- Profile picture (currently using SVG placeholder)

### Add Your Profile Image

Replace the SVG placeholder in `index.html` with your own image:

```html
<div class="profile-image">
    <img src="path/to/your/photo.jpg" alt="Your Name">
</div>
```

### Add Course Materials

For each course page (e.g., `courses/math120.html`):
- Add specific topics covered
- Link to lecture notes or syllabi
- Include problem sets or assignments
- Add reading recommendations

### Update Social Links

Edit the social section in `index.html`:
- Replace UCI Math Twitter link with your own
- Add or remove social media links as needed

### Customize Colors

Main colors in `assets/styles.css`:
- Blue accent: `#0066cc`
- Dark gray: `#333`
- Light background: `#f5f5f5`

Change these hex codes to match your preferences.

### Add More Pages

To add new pages (e.g., research, teaching):
1. Create a new `.html` file (e.g., `research.html`)
2. Copy the header/footer from an existing page
3. Update navigation links in all files
4. Add to the main navigation bar

## Styling Details

The site uses:
- **Font**: Helvetica Neue / Arial (clean, professional)
- **Layout**: CSS Grid and Flexbox for responsive design
- **Navigation**: Dark fixed header with sticky positioning
- **Tiles**: Card-based layout for featured sections
- **Typography**: Uppercase navigation, serif course titles, clean body text

## Hosting

This is a static website and can be hosted on:
- **GitHub Pages** - Enable in repository settings (free)
- **Netlify** - Connect your GitHub repo for automatic deployments
- **Vercel** - Modern static hosting with great performance
- **AWS S3** - Scalable cloud hosting
- **Firebase Hosting** - Google's static hosting solution
- **Local server** - Python or Node.js for local testing

### Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository → Settings → Pages
3. Select `main` branch as source
4. Your site will be available at `https://yourusername.github.io/akshat-site`

### Local Development

Run a local server to test:

**Python 3:**
```bash
cd /path/to/akshat-site
python -m http.server 8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

Then visit `http://localhost:8000` in your browser.

**Node.js (http-server):**
```bash
npm install -g http-server
http-server
```

## Design Inspiration

This site is styled after professional academic portfolio websites like:
- UCI Math Department faculty profiles
- University research sites
- Professional academic portfolios

Key design elements:
- Professional typography
- Minimalist color scheme
- Clear information hierarchy
- Mobile-responsive layout
- Academic aesthetic

## Customization Tips

1. **Add your actual photo** - Replace the SVG avatar with your headshot
2. **Update your bio** - Tailor the "Welcome" section to your research interests
3. **Add publications** - Fill in your actual research papers and preprints
4. **Update course descriptions** - Add details specific to your courses
5. **Add contact methods** - Include email, office hours, location details
6. **Add CV/Resume** - Link to or embed your actual resume
7. **Social media** - Update with your actual social profiles

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Sizes & Performance

- Total CSS: ~8KB
- HTML pages: ~3-4KB each
- No external dependencies (pure HTML/CSS)
- Fast loading times
- Mobile-friendly performance

## Future Enhancements

Consider adding:
- In-depth research page with preprints
- Teaching philosophy statement
- Student recommendations/testimonials
- Mathematics blog or insights
- Interactive visualizations
- PDF CV download
- Newsletter signup
- Search functionality
- Dark mode toggle

## License

This portfolio website template is created for your personal use. Feel free to modify and customize as needed.

---

**Created**: April 2024
**Last Updated**: April 2024

For questions or support with customization, refer to the inline comments in the CSS file or HTML pages.

