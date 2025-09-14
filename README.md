# IROS 2025 Workshop - Website

Interactive website for "Generalized Retargeting for Dexterous Manipulation" workshop presentation.

🌐 **Live at:** https://daisydai008.github.io/iros-workshop-website/

## 📁 Repository Structure

```
iros-workshop-website/
├── index.html              # Main website page
├── style.css               # Website styling
├── assets/
│   ├── downloads/
│   │   └── poster.pdf      # Workshop poster for download
│   ├── images/             # Images and figures
│   │   ├── logos/          # DexRobot logos
│   │   └── *.jpg/png       # Figures from poster
│   └── videos/             # Demo videos (optional)
└── README.md               # This file
```

## 🚀 Quick Start

### 1. Deploy to GitHub Pages

1. Push this repository to GitHub:
   ```bash
   git remote add origin https://github.com/daisydai008/iros-workshop-website.git
   git branch -M main
   git push -u origin main
   ```

2. Enable GitHub Pages:
   - Go to Settings → Pages
   - Source: Deploy from branch
   - Branch: main
   - Folder: / (root)
   - Save

3. Your site will be live at: https://daisydai008.github.io/iros-workshop-website/

### 2. Add Your Videos

Replace the placeholder video IDs in `index.html`:

```html
<!-- Find and replace these -->
YOUR_VIDEO_ID_1
YOUR_VIDEO_ID_2
YOUR_VIDEO_ID_3
```

With your actual YouTube video IDs:
```html
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>
```

### 3. Update Contact Information

Edit line ~198 in `index.html`:
```html
<p class="contact-email">📧 your.email@example.com</p>
```

## 📝 Content Updates

### Adding New Sections

Add a new section to `index.html`:
```html
<section id="new-section" class="section">
    <div class="container">
        <h2 class="section-title">Your Title</h2>
        <!-- Your content -->
    </div>
</section>
```

### Updating Poster PDF

When the poster is updated:
1. Get the new PDF from the poster repository
2. Copy to `assets/downloads/poster.pdf`
3. Commit and push

## 🎨 Customization

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --dexrobot-color: #26b7c1;  /* Teal accent */
    --dexrobot-title: #0c383b;  /* Dark teal */
}
```

### Fonts
Currently using Inter font. To change, edit in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont" rel="stylesheet">
```

## 🔗 Related Repository

**Poster Source (LaTeX):** [iros-workshop](https://github.com/daisydai008/iros-workshop)
- Contains LaTeX source files
- Syncs with Overleaf
- Generates poster.pdf

## 📊 Workflow

```
1. Edit poster in Overleaf/LaTeX repo
2. Compile poster.pdf
3. Copy PDF to this website repo
4. Push changes
5. GitHub Pages auto-deploys
```

## 🤝 Sponsorship

This research is sponsored by [DexRobot](https://www.dexrobot.com).

## 📄 License

Academic use only. Please cite our work if used in research.

---
*IROS 2025 Workshop on Dexterous Manipulation*