# Nichole Manansala – Portfolio

A static HTML/CSS portfolio website, ready to deploy on **GitHub Pages**.

## Files

```
index.html   – Main HTML structure
style.css    – All styles
script.js    – Mobile nav toggle + scroll behavior
```

## How to deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `nichole-portfolio`)
2. Upload all three files (`index.html`, `style.css`, `script.js`) to the repository
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose the `main` branch and `/ (root)` folder
6. Click **Save**
7. Your site will be live at: `https://yourusername.github.io/nichole-portfolio/`

## Adding your photos

To replace the placeholder boxes with your actual photos:

1. Add your image files to the repo (e.g. `hero-photo.jpg`, `about-photo.jpg`)
2. In `index.html`, replace the `<div class="hero-img-placeholder">` block with:
   ```html
   <img src="hero-photo.jpg" alt="Nichole Manansala" style="width:100%;border-radius:12px;" />
   ```
3. Do the same for the about section placeholder.

## Customization

- **Colors**: Edit the CSS variables at the top of `style.css` under `:root`
- **Content**: All text and project info is in `index.html`
- **Fonts**: Currently using Google Fonts (Playfair Display + Inter)
