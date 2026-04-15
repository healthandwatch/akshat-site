# Akshat's Mathematics Course Archives

A professional static portfolio website featuring course archives and mathematics resources.

## Site Structure

```
akshat-site/
├── index.html                 # Main homepage
├── courses/
│   ├── math120.html          # Abstract Algebra course page
│   ├── math121.html          # Linear Algebra course page
│   ├── math130.html          # Probability course page
│   └── math140.html          # Elementary Analysis course page
├── assets/
│   └── styles.css            # Main stylesheet
└── README.md                 # This file
```

## Features

- **Clean, Professional Design**: Inspired by academic portfolio websites
- **Responsive Layout**: Works on desktop, tablet, and mobile devices
- **Easy Navigation**: Simple navigation bar across all pages
- **Semantic HTML**: Well-structured, accessible HTML markup
- **Course Pages**: Dedicated pages for each course with overview, key concepts, and resources

## Customization

### Adding Your Information

1. **Update the homepage title and description** in `index.html`:
   - Change "Akshat" in the header
   - Update the hero section text

2. **Add course content** by editing individual course pages in `courses/`:
   - Add specific topics covered in each course
   - Include links to course materials, syllabi, or lecture notes
   - Add problem sets or assignments as needed

3. **Update course descriptions** in the course list:
   - Edit the descriptions in the `<ul class="course-list">` section on the homepage

4. **Modify the reading list** in the Additional Reading section:
   - Add or remove recommended books and resources

### Styling Changes

The entire site styling is controlled by `assets/styles.css`. You can:

- Change colors by modifying the hex codes (e.g., `#0066cc` for the blue accent color)
- Adjust fonts by modifying the `font-family` property
- Modify spacing by adjusting `margin` and `padding` values
- Change the layout by modifying the `max-width`, grid properties, or flexbox settings

### Adding New Pages

To add a new page (e.g., about, research, publications):

1. Create a new `.html` file
2. Copy the header and footer from an existing page
3. Update the navigation links in all files to include the new page
4. Add the page to the main `<ul class="nav-links">` in each file

## Hosting

This is a static website and can be hosted on:
- **GitHub Pages**: Simply enable GitHub Pages in your repository settings
- **Netlify**: Connect your GitHub repo to Netlify for automatic deployments
- **Any static hosting service**: AWS S3, Vercel, Firebase Hosting, etc.
- **Local server**: Use Python, Node.js, or any local server for local development

### Local Development

Run a local server to test the site:

**Python 3:**
```bash
python -m http.server 8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

Then visit `http://localhost:8000` in your browser.

## Future Enhancements

Consider adding:
- Downloadable course syllabi and materials
- Search functionality
- Blog section for mathematical insights
- Contact form
- PDF lecture notes
- Video playlists
- Interactive visualizations

## License

This website template is created for your use. Feel free to modify and redistribute as needed.

---

**Last Updated**: April 2024
