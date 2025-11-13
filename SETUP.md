# Setup Guide

This guide will help you set up and run the Awesome AI Tools project locally.

## 📋 Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Git installed on your computer
- Python 3 (for local server) or any other HTTP server

## 🚀 Quick Start

### Option 1: View Locally (Recommended)

1. **Clone the Repository**
   ```bash
   git clone https://github.com/maysunyoung/awesome-ai-tools.git
   cd awesome-ai-tools
   ```

2. **Start a Local Server**
   
   Using Python 3:
   ```bash
   python3 -m http.server 8000
   ```
   
   Or using Python 2:
   ```bash
   python -m SimpleHTTPServer 8000
   ```
   
   Or using Node.js (if you have it installed):
   ```bash
   npx http-server -p 8000
   ```

3. **Open in Browser**
   
   Navigate to: `http://localhost:8000/index.html`

### Option 2: Direct File Access

Simply open `index.html` directly in your browser by double-clicking the file.

**Note**: Some features may not work properly when opening files directly due to browser security restrictions.

### Option 3: GitHub Pages

The project can be deployed to GitHub Pages for free hosting:

1. Fork the repository
2. Go to Settings → Pages
3. Select the main branch as source
4. Your site will be available at `https://yourusername.github.io/awesome-ai-tools/`

## 📁 Project Structure

```
awesome-ai-tools/
├── index.html              # Main landing page
├── styles.css              # Styling and animations
├── script.js               # Interactive features
├── README.md               # Main documentation
├── CONTRIBUTING.md         # Contribution guidelines
├── CHANGELOG.md            # Version history
├── SETUP.md               # This file
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions deployment
├── 2024/                  # Archived tools from 2024
├── Art.md                 # Art generation tools
├── Audio.md               # Audio tools
├── Automation.md          # Automation tools
├── Business.md            # Business tools
├── Code.md                # Developer tools
├── Image.md               # Image tools
├── Miscellaneous.md       # Other tools
├── Productivity.md        # Productivity tools
├── Text.md                # Text generation tools
└── Video.md               # Video tools
```

## 🎨 Features

### Landing Page
- Modern dark theme design
- Search functionality
- Category browsing
- Featured tools section
- Responsive layout
- Smooth animations

### Documentation
- Comprehensive tool list
- Organized by category
- Pricing information
- Tool descriptions
- Easy navigation

## 🛠️ Development

### Making Changes

1. **Edit HTML**
   - Modify `index.html` for structure changes
   - Add new sections or update content

2. **Update Styles**
   - Edit `styles.css` for design changes
   - Customize colors, fonts, or layouts

3. **Add Functionality**
   - Modify `script.js` for new features
   - Add interactive elements

4. **Update Tool Lists**
   - Edit category `.md` files to add tools
   - Update both category file and `README.md`

### Testing

1. **Local Testing**
   ```bash
   python3 -m http.server 8000
   ```
   Open `http://localhost:8000/index.html`

2. **Check Responsiveness**
   - Test on different screen sizes
   - Use browser developer tools
   - Check mobile devices

3. **Verify Links**
   - Ensure all tool links work
   - Check internal navigation
   - Validate external URLs

## 🚢 Deployment

### GitHub Pages (Automatic)

The project includes a GitHub Actions workflow that automatically deploys to GitHub Pages when you push to the main branch.

### Manual Deployment

1. **Build** (if needed)
   - No build step required for this project
   - All files are static HTML/CSS/JS

2. **Deploy**
   - Upload files to your hosting provider
   - Or use GitHub Pages, Netlify, Vercel, etc.

## 🔧 Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary: #6366f1;
    --secondary: #8b5cf6;
    --accent: #ec4899;
    /* ... more colors */
}
```

### Content

- Update tool descriptions in `.md` files
- Modify hero text in `index.html`
- Change category names and icons

### Layout

- Adjust grid columns in CSS
- Modify spacing and padding
- Change breakpoints for responsive design

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🐛 Troubleshooting

### Page Not Loading
- Check if the server is running
- Verify the correct port (8000)
- Clear browser cache

### Styles Not Applying
- Ensure `styles.css` is in the same directory
- Check browser console for errors
- Verify CSS file path in HTML

### JavaScript Not Working
- Check browser console for errors
- Ensure `script.js` is loaded
- Verify file paths

## 📞 Support

If you encounter issues:

1. Check existing GitHub issues
2. Create a new issue with details
3. Provide browser and OS information
4. Include error messages if any

## 🎉 Next Steps

- Explore the tool categories
- Add your favorite AI tools
- Contribute to the project
- Share with others

---

**Happy Exploring! 🚀**

