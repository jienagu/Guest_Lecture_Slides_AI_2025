# Viewing Guide for Guest Lecture Slides

## Quick Start

### Method 1: Direct Browser Viewing (Easiest)
1. Download or clone this repository
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge)
3. The presentation will load automatically

### Method 2: GitHub Pages (For Online Sharing)
1. Fork or clone this repository to your GitHub account
2. Go to repository Settings → Pages
3. Enable GitHub Pages from the main branch
4. Access at: `https://[yourusername].github.io/Guest_Lecture_Slides_AI_2025/`

### Method 3: Local Development Server
If you want to serve the slides locally with a web server:

```bash
# Using Python (Python 3)
python3 -m http.server 8000

# Using Node.js
npx http-server

# Then open: http://localhost:8000/index.html
```

## Navigation Controls

### Keyboard Shortcuts:
- **Arrow Keys** (← → ↑ ↓): Navigate between slides
- **Space**: Next slide
- **Shift + Space**: Previous slide
- **F**: Enter/exit fullscreen mode
- **Esc**: Slide overview mode
- **S**: Speaker notes view (if available)
- **?**: Show keyboard shortcuts help

### Mouse/Touch:
- Click on slide edges to navigate
- Swipe left/right on touch devices

## Presentation Tips

### Before Presenting:
1. ✅ Test the slides in the browser you'll use for presenting
2. ✅ Check that all content loads properly
3. ✅ Familiarize yourself with the navigation
4. ✅ Practice the timing for your presentation
5. ✅ Have the slides.md file as a backup reference

### During Presentation:
- Use arrow keys for smooth navigation
- Press F for fullscreen to maximize screen space
- Use Esc to get an overview if you need to jump to a specific slide
- Keep the slides.md file open in another tab for quick reference

### Customization:
To customize the appearance, edit the `<style>` section in `index.html`:
- Change colors, fonts, and spacing
- Adjust slide transitions
- Modify the theme (change the theme CSS link)

## Troubleshooting

### Slides don't load or look broken:
- Ensure you have an internet connection (for CDN resources)
- Try a different browser
- Check browser console for errors (F12)
- Use the slides.md as a fallback

### Navigation doesn't work:
- Make sure JavaScript is enabled in your browser
- Refresh the page
- Try using keyboard shortcuts instead of mouse clicks

### For Offline Use:
If you need to present without internet access:
1. Download Reveal.js library locally
2. Update the CSS and JS links in index.html to point to local files
3. Or use the slides.md file with a Markdown viewer

## Converting to Other Formats

See README.md for instructions on converting to:
- PDF
- PowerPoint (.pptx)
- Other presentation formats

## Support

For questions or issues:
1. Check the README.md for more detailed information
2. Refer to [Reveal.js documentation](https://revealjs.com/)
3. Open an issue in this repository
