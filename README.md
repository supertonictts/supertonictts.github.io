# Text-to-Speech Research Demo Page

A clean, professional website to showcase your text-to-speech research thesis. This demo page allows you to present your methodology, share audio samples, and compare your results with other TTS approaches.

## Features

- Responsive design that works on desktop and mobile devices
- Audio comparison sections for easy A/B testing
- Results visualization with tables and charts
- Downloadable paper link section
- Clean, professional academic styling
- Sticky navigation menu with active section highlighting
- "Back to Top" button for easy navigation
- Automatic favicon using an emoji
- GitHub Actions workflow for automatic deployment
- Local preview script

## Getting Started

### Prerequisites

- A GitHub account (for hosting via GitHub Pages)
- Your text-to-speech audio samples
- Research images/diagrams (optional)

### Setup and Customization

1. **Fork or clone this repository**

2. **Customize the content:**
   - Edit `index.html` to update the text with your actual research information
   - Replace the placeholder texts in each section with your thesis content
   - Update the results table with your actual evaluation metrics

3. **Add your audio samples:**
   - Add your audio samples to the `/audio` directory
   - Update the audio `src` attributes in `index.html` to point to your files
   - Format recommended: MP3 files (best compatibility across browsers)

4. **Add your images (optional):**
   - Add your methodology diagrams and charts to the `/images` directory
   - Update the image `src` attributes in `index.html`

5. **Update links:**
   - Update the GitHub repository link in the footer
   - Add your university affiliation link
   - Add your contact information
   - Link to your research paper PDF if available

### Running Locally

For a quick preview of your site before deploying:

```bash
# Make the preview script executable (if not already)
chmod +x preview.sh

# Run the preview script
./preview.sh
```

This will start a local web server, and you can view the site at http://localhost:8000.

### Publishing to GitHub Pages

1. Push your changes to GitHub

2. The included GitHub Actions workflow will automatically deploy your site to the `gh-pages` branch

3. Enable GitHub Pages in your repository settings:
   - Go to your repository settings
   - Scroll down to the GitHub Pages section
   - Select the `gh-pages` branch as the source
   - Click Save

4. Your site will be published at `https://yourusername.github.io/repository-name/`

## Directory Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── preview.sh          # Local preview script
├── README.md           # This file
├── .github/            # GitHub configuration
│   └── workflows/      # GitHub Actions workflows
│       └── deploy.yml  # Deployment workflow
├── audio/              # Directory for audio samples
│   ├── README.md       # Guidelines for audio files
│   ├── our-method-sample1.mp3
│   ├── baseline-a-sample1.mp3
│   └── ...
└── images/             # Directory for images and diagrams
    ├── README.md       # Guidelines for images
    ├── methodology-diagram.png
    ├── results-chart.png
    └── ...
```

## Customization Tips

- **Colors**: Modify the CSS variables in the `:root` selector in `styles.css` to match your institution's colors
- **Fonts**: Change the font-family in the `body` selector in `styles.css`
- **Adding sections**: Copy an existing section structure in `index.html` and modify as needed
- **Additional comparisons**: Duplicate the `.comparison-group` div structure to add more audio comparisons

## Browser Compatibility

This demo page works with all modern browsers:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers on iOS and Android

## License

This project is open-source and available for academic use.

## Acknowledgments

- Font Awesome for icons
- Your thesis advisor and research team

---

For questions or support, please open an issue on this repository. 