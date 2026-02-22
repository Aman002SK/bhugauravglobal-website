# BHU Gaurav Global Website

A modern, responsive website for BHU Gaurav Global - a non-governmental, not-for-profit organization committed to peace, prosperity, and harmony.

## Features

- 📱 **Fully Responsive** - Works on all devices (mobile, tablet, desktop)
- 🎨 **Modern Design** - Clean and elegant UI/UX
- ⚡ **No Framework** - Pure HTML, CSS, and JavaScript
- 🚀 **Fast Loading** - Optimized performance
- ♿ **Accessible** - WCAG compliant

## Website Sections

1. **Navigation Bar** - Sticky navigation with mobile menu
2. **Hero Section** - Eye-catching banner with call-to-action
3. **About Us** - Organization overview with four pillars
4. **Vision & Mission** - Mission statement and values
5. **Founders Section** - Team member profiles
6. **Contact Section** - Contact information and inquiry form link
7. **Social Media** - Links to all social platforms
8. **Footer** - Copyright and organization info

## Setup Instructions

### 1. Replace Images
Create an `images/` folder in the project root and add:
- `logo.png` - Organization logo
- `founder1.jpg` - Prakash Pradhan's photo
- `founder2.jpg` - Mithilesh Kumar Rai's photo
- `founder3.jpg` - Kishori Bandana's photo
- `events.jpg` - Events image (optional)

Download images from: [Google Drive](https://drive.google.com/drive/u/2/folders/1S49Odp4nG9TFAll8zxAVuEcWCISSreSp)

### 2. Deploy Options

#### Option A: GitHub Pages (Free)
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Website will be live at `https://yourusername.github.io/bhugauravglobal-website`

#### Option B: GoDaddy Domain
1. Point your GoDaddy domain `bhugauravglobal.in` to your hosting
2. Upload files via FTP or GitHub Pages
3. Website will be live at `https://bhugauravglobal.in`

#### Option C: Netlify (Recommended for simplicity)
1. Connect GitHub repository to Netlify
2. Set build command (none needed - static site)
3. Deploy automatically on every push

### 3. Customize Content
Edit `index.html` to:
- Update founder names and designations
- Add more team members
- Modify colors in `styles.css` (`:root` variables)
- Update social media links
- Update contact information

### 4. Color Customization
Edit `:root` variables in `styles.css`:
```css
--primary-color: #2c5aa0;      /* Main blue */
--secondary-color: #f39c12;    /* Gold accent */
--dark-color: #1a1a1a;         /* Dark text */
--light-color: #f8f9fa;        /* Light background */
