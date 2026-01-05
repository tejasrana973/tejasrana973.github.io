# tejasrana973.github.io

Personal academic website for PhD applications. Static HTML/CSS with MathJax for mathematical typesetting.

**Live URL:** https://tejasrana973.github.io/

## Deployment

This repository is configured for GitHub Pages:

1. Create a new repository on GitHub named `tejasrana973.github.io`
2. Clone this repository or push these files to the new repo
3. Go to **Settings → Pages** in your GitHub repository
4. Under "Source", select the `main` branch and `/ (root)` folder
5. Click Save — the site will be live at `https://tejasrana973.github.io/` within a few minutes

### Updating the Site

1. Edit the HTML/CSS files directly
2. Commit your changes to the `main` branch
3. Push to GitHub — the site updates automatically (usually within 1-2 minutes)

## File Structure

```
tejasrana973.github.io/
├── index.html              # Home page
├── cv.html                 # Curriculum Vitae
├── thesis/
│   └── index.html          # Master's thesis summary (with MathJax)
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   ├── img/
│   │   └── profile.jpg     # Profile photo (replace with your photo)
│   └── plots/
│       ├── plot1.png       # Thesis figure 1 (replace with actual plot)
│       └── plot2.png       # Thesis figure 2 (replace with actual plot)
├── assets/your_cv.pdf      # Downloadable CV (replace with actual PDF)
├── README.md               # This file
└── LICENSE                 # MIT License (optional)
```

## Customization Checklist

### Before Publishing

- [ ] Replace `assets/img/profile.jpg` with your professional photo
- [ ] Replace `assets/your_cv.pdf` with your actual CV
- [ ] Update placeholder text in `index.html` (About section)
- [ ] Update placeholder entries in `cv.html` (education, experience, publications)
- [ ] Replace thesis plots in `assets/plots/` with your actual figures
- [ ] Update thesis content in `thesis/index.html`
- [ ] Update the obfuscated email in `index.html` footer:
  ```html
  <p class="contact-text">For contact: your.actual.name [at] gmail [dot] com</p>
  ```
  **Note:** Do not use `mailto:` links — the obfuscated format helps prevent spam.

### Adding a PDF Thesis

When your thesis is complete:

1. Add the PDF to `thesis/thesis.pdf`
2. Add a download link in `thesis/index.html`:
   ```html
   <a href="thesis.pdf" class="download-link" download>Download Full Thesis (PDF)</a>
   ```

## Technical Notes

- **Math Rendering:** Uses MathJax 3 via CDN. Inline math: `\( ... \)`, display math: `$$ ... $$`
- **Fonts:** System fonts (no external font loading)
- **Max Width:** Content is constrained to 900px for readability
- **Responsive:** Layout adapts to mobile screens
- **Accessibility:** Semantic HTML, skip links, alt text on images

## Contact

The contact email on this site is intentionally obfuscated (`yourname [at] gmail [dot] com`) to reduce spam. Replace with your actual email when ready to publish.

---

*Last updated: December 2024*
