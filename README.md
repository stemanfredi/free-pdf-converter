# Free PDF Converter - Landing Page

A simple, clean landing page for the Free PDF Converter Windows desktop application.

## Overview

This is a static website designed to promote and distribute a free, portable PDF converter tool for Windows 10/11. The tool converts between PDF and Microsoft Office formats (DOCX, XLSX, PPTX).

## Features

- **Clean, Modern Design**: Matches the provided reference image with red/coral color scheme
- **Responsive Layout**: Works on desktop, tablet, and mobile devices
- **Two Main Pages**: Home page and dedicated download page
- **Static Site**: No server-side dependencies, pure HTML/CSS/JavaScript
- **SEO Friendly**: Semantic HTML structure with proper meta tags

## File Structure

```
├── index.html          # Home page
├── download.html       # Download page
├── css/
│   └── styles.css      # All styling
├── js/
│   └── main.js         # Interactive functionality
├── assets/             # Placeholder for .exe file
└── README.md           # This file
```

## Key Messaging

The site emphasizes that the PDF converter is:
- **100% Free** - No trials, subscriptions, or hidden costs
- **Fully Portable** - No installation required, runs from anywhere
- **Windows 10/11 Compatible** - Modern Windows support
- **Privacy-Focused** - All conversions happen offline
- **Lightweight** - Single executable file

## Supported Conversions

- PDF → DOCX (Word)
- PDF → XLSX (Excel) 
- PDF → PPTX (PowerPoint)
- DOCX → PDF
- XLSX → PDF
- PPTX → PDF

## Setup Instructions

1. **No Build Process Required** - This is a static site
2. **Local Testing**: Simply open `index.html` in a web browser
3. **Web Hosting**: Upload all files to any web server or static hosting service
4. **Add .exe File**: Place your executable in the `assets/` folder and update the download links

## Customization

### Adding the .exe File

1. Place your `pdf-converter.exe` file in the `assets/` folder
2. Update the download buttons in both HTML files to link to `assets/pdf-converter.exe`
3. Update file size and version information in `download.html`

### Updating Content

- **Colors**: Modify the CSS variables in `styles.css`
- **Text**: Edit the HTML files directly
- **Images**: Add to `assets/` folder and reference in HTML

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- All modern mobile browsers

## Performance

- **Lightweight**: ~50KB total (excluding .exe file)
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **Mobile Optimized**: Responsive design with touch-friendly interactions

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox/Grid
- **Vanilla JavaScript**: No frameworks or dependencies
- **Google Fonts**: Inter font family
- **CSS Animations**: Smooth transitions and hover effects

## Future Enhancements

When you're ready to add the .exe file:

1. Replace the `handleDownload()` function in `main.js` with actual download logic
2. Update file information in the download page
3. Consider adding download analytics if needed
4. Add virus scan certificates or security badges if desired

## License

This landing page template is provided as-is for your Free PDF Converter project.
