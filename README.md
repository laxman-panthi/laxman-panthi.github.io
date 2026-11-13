# Laxman Panthi — Personal Website & Portfolio (`laxman-panthi.github.io`)

Production portfolio and architecture showcase for **Laxman Panthi**, Senior Data Scientist & AI/ML Architect.

Live URL: **https://laxman-panthi.github.io**

---

## ⚡ Architecture & Tech Overview
- **Zero Build Step / Blazing Fast**: Pure modern semantic HTML5, modular CSS design tokens, and lightweight vanilla JavaScript.
- **Dark / Light Theme Engine**: Real-time theme toggle persisted via `localStorage` with OS preference fallback.
- **Mobile Responsive**: Fully responsive grid layout across mobile, tablet, and ultra-wide displays.
- **GitHub Pages Ready**: Includes `.nojekyll` and `.github/workflows/deploy.yml` for automated GitHub Pages continuous deployment.

---

## 🚀 How to Deploy to GitHub Pages

1. **Create the repository on GitHub**:
   - Repository Name: `laxman-panthi.github.io`
   - Visibility: **Public**

2. **Initialize and Push**:
   ```bash
   cd laxman-panthi.github.io
   git init
   git branch -M main
   git add .
   git commit -m "feat: initial production portfolio release"
   git remote add origin https://github.com/laxman-panthi/laxman-panthi.github.io.git
   git push -u origin main
   ```

3. **Verify GitHub Pages Settings**:
   - Go to your repository on GitHub: **Settings > Pages**
   - Under **Build and deployment > Source**:
     - Select **GitHub Actions** (the included `.github/workflows/deploy.yml` handles deployment automatically), OR
     - Select **Deploy from a branch** -> `main` branch -> `/ (root)`.
   - Your website will immediately be live at `https://laxman-panthi.github.io`!

---

## 🛠️ Local Preview

You can preview the site locally using any standard static server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js npx
npx serve .
```

Then open `http://localhost:8000` in your browser.
