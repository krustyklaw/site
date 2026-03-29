# KrustyKlaw Website Implementation

The website for **KrustyKlaw** has been built to provide a premium, high-converting download experience. It's fully optimized for static hosting on GitHub Pages.

## ✨ Key Features
- **Modern UI Design**: Inspired by the application screenshot with a clean "Glassmorphism" effect, Inter typography, and terracotta branding.
- **Cross-Platform Links**: Integrated download buttons for Windows and Linux, with a "Coming Soon" state for macOS.
- **Vite Setup**: Fast, modern build process that produces highly optimized static assets.
- **Automated Deployment**: Includes a GitHub Actions workflow (`deploy.yml`) to automatically update the site when pushing to `main`.

## 🛠 Project Structure
- `index.html`: Main landing page with SEO meta tags and direct download links.
- `style.css`: Custom premium CSS styling (terracotta theme).
- `public/app-screenshot.png`: High-fidelity mockup generated to showcase the app interface.
- `vite.config.js`: Configuration for relative paths (essential for GitHub Pages).
- `.github/workflows/deploy.yml`: Workflow script for automated deployment.

## 🚀 Next Steps
1. **GitHub Setup**: Initialize a repository and push these files to the `main` branch.
2. **Pages Settings**: Go to Repository Settings -> Pages and set "Source" to "GitHub Actions".
3. **Mac Binary**: Update the macOS link in `index.html` when the binary is ready.
