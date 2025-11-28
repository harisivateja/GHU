# Centralized Student Dashboard - Presentation Website

A beautiful, fully responsive static website showcasing the Centralized Student Dashboard project for Horizon State University. Built with pure HTML, inline CSS, and minimal JavaScript - no frameworks, no build tools, ready to deploy!

## 🚀 Quick Start

### Run Locally
1. Simply open `index.html` in any modern web browser
2. No server required - works directly from file system
3. All assets are self-contained in the project directory

### Deploy to GitHub Pages
1. Create a new repository on GitHub
2. Upload all files maintaining the directory structure:
   ```
   /
   ├── index.html
   ├── problem.html
   ├── research.html
   ├── solution.html
   ├── architecture.html
   ├── data.html
   ├── dashboard.html
   ├── ethics.html
   ├── lessons.html
   ├── appendix.html
   ├── images/
   │   ├── (your generated images here)
   └── README.md
   ```
3. Go to Repository Settings → Pages
4. Select Source: `main` branch, `/` (root) folder
5. Save and wait 1-2 minutes
6. Your site will be live at: `https://[username].github.io/[repo-name]/`

## 📁 Project Structure

### HTML Pages (10 total)
- **index.html** - Home/Cover with Executive Summary
- **problem.html** - Problem Context & Stakeholders
- **research.html** - Research & Insights
- **solution.html** - Proposed Solution & Key Features
- **architecture.html** - Enterprise Architecture & Data Flow
- **data.html** - Data Design & ER Diagram
- **dashboard.html** - Dashboard Insights & Screenshots
- **ethics.html** - Ethical & Social Considerations
- **lessons.html** - Lessons Learned & Team Reflection
- **appendix.html** - Resources & Team Information

### Images Directory
Place your generated/extracted images in `/images/`:
- `architecture-diagram.png` - Three-tier architecture
- `er-diagram.png` - Entity Relationship Diagram
- `dashboard-main.png` - Main dashboard screenshot (from live site)
- `dashboard-profile.png` - Student 360° profile screenshot (from live site)
- `hero-*.png` - Additional AI-generated images (see AI-IMAGE-PROMPTS.txt)

## ✏️ Customization

### Updating Content
1. **Executive Summary**: Edit content in `index.html` (lines 200-230)
2. **Team Information**: Update footer in all pages (search for "Team" section)
3. **Links**: Update dashboard URL and other links as needed
4. **Last Updated Date**: Change footer date in all pages

### Color Customization
All pages use CSS variables defined in the `:root` selector:
```css
--color-primary: #0d9488;    /* Teal */
--color-secondary: #1e3a8a;   /* Navy */
--color-accent: #06b6d4;      /* Cyan */
```
Change these values in each page's `<style>` section for consistent theming.

### Adding Images
1. Save images to `/images/` directory
2. Reference in HTML: `<img src="./images/your-image.png" alt="Description">`
3. Recommended formats: PNG for diagrams, JPG for photos
4. Optimize images to <500KB each for faster loading

## 🖼️ Image Placement Guide

### Required Images
1. **Architecture Diagram** (`architecture.html`)
   - Extract from your project report
   - Shows three-tier architecture (Frontend, Backend, Database)
   
2. **ER Diagram** (`data.html`)
   - Extract from your project report
   - Shows six entities and their relationships

3. **Dashboard Screenshots** (`dashboard.html`)
   - Take screenshots from https://harisivasaiteja.github.io/Studentdashboard/
   - Capture main dashboard view with KPIs and charts
   - Capture Student 360° profile view
   
4. **Hero/Feature Images** (optional)
   - Use AI image prompts provided in AI-IMAGE-PROMPTS.txt
   - Generate via DALL-E, Midjourney, or similar tools
   - Place in hero sections for visual appeal

## 🎨 Design Features

- **Responsive Design**: Mobile-first, works on all devices
- **Dark Mode**: Toggle available on every page (state persists)
- **Smooth Animations**: Fade-in, hover effects, transitions
- **Sticky Navigation**: Always accessible while scrolling
- **Lightbox Gallery**: Click images to view enlarged
- **Accessibility**: Semantic HTML, keyboard navigation, alt text

## 📊 For Presentation (5 Minutes, 5 Speakers)

Use the website as your visual aid:
1. **Speaker 1 (0:30)**: Navigate to `problem.html` - Explain the challenge
2. **Speaker 2 (1:00)**: Navigate to `solution.html` - Present our approach
3. **Speaker 3 (1:00)**: Navigate to `data.html` - Show data model
4. **Speaker 4 (2:00)**: Navigate to `dashboard.html` - Demo live dashboard, discuss insights
5. **Speaker 5 (0:30)**: Navigate to `lessons.html` + `appendix.html` - Wrap up & next steps

Detailed script available in `PRESENTATION-SCRIPT.txt`

## ✅ Pre-Launch Checklist

Before going live, verify:
- [ ] All images placed in `/images/` directory
- [ ] All internal links working (test navigation between pages)
- [ ] Live dashboard link correct: https://harisivasaiteja.github.io/Studentdashboard/
- [ ] Team member names spelled correctly
- [ ] Dark mode toggle working on all pages
- [ ] Responsive design tested (mobile, tablet, desktop)
- [ ] All pages load without errors
- [ ] "Last Updated" date current

## 🔧 Troubleshooting

**Images not loading?**
- Check file paths are relative: `./images/filename.png`
- Verify image files exist in `/images/` directory
- Check file extensions match (case-sensitive on some servers)

**Navigation not working?**
- Ensure all HTML files are in the root directory
- Check mobile menu toggle (hamburger icon) on small screens

**Dark mode not saving?**
- Ensure browser allows localStorage
- Clear browser cache and try again

## 📝 Technical Details

- **No external dependencies**: Everything is self-contained
- **Google Fonts**: Inter (body) + Poppins (headings)
- **Total size**: ~100KB (HTML + CSS), <5MB with images
- **Browser support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Load time**: <2 seconds on average connection

## 👥 Team

**Group 20 - QuadraMind**
- Shashank Manchikatla
- Hari Siva Sai Teja Mogali
- Manindra Porandla
- Manohar Naidu Talari
- Sandeep Thota

## 📄 License

© 2025 Group 20 - QuadraMind. Created for academic presentation purposes.

---

**Questions?** Review the `QA-CHECKLIST.txt` for common issues and solutions.
