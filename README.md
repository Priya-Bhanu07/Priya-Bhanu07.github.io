# Portfolio Website

A modern, professional portfolio website inspired by top developer portfolios. Built with HTML, CSS, and JavaScript.

![Portfolio Preview](./preview.png)

## ✨ Features

- **Clean Professional Design** - Similar to varadbhogayata.github.io
- **Fully Responsive** - Works on all devices
- **7 Complete Sections**: Hero, About, Experience, Projects, Skills, Education, Contact
- **3 Featured Projects** - With detailed accomplishments
- **Resume Download** - Integrated in navbar, hero, and footer
- **Contact Form** - With validation
- **Smooth Animations** - Scroll reveal effects
- **Mobile Navigation** - Hamburger menu
- **SEO Optimized** - Meta tags and semantic HTML

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # All styles
│   ├── js/
│   │   └── main.js        # JavaScript functionality
│   └── resume.pdf         # YOUR RESUME (add this!)
├── README.md              # This file
└── .gitignore
```

## 📄 How to Add Your Resume

**IMPORTANT**: Add your resume PDF to make the download links work!

### Step 1: Prepare Your Resume
- Export/save your resume as a **PDF file**
- Name it: `resume.pdf`
- Keep file size under 2MB for faster loading

### Step 2: Add to Project
Copy your resume to the assets folder:
```
portfolio/assets/resume.pdf
```

### Step 3: Verify It Works
The resume download will work in 3 locations:
1. **Navigation bar** - "Resume" button (top right)
2. **Hero section** - "Download Resume" button
3. **Footer** - "Download Resume" button

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com/) and log in
2. Click **+** → **New repository**
3. Name: `username.github.io` (e.g., `Priya-Bhanu07.github.io`)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Your Files

**Option A: Using Git Command Line**

```bash
cd /home/bhanup/Main/Projects/portfolio

# Initialize git
git init

# Add all files (make sure to add your resume.pdf first!)
git add .

# Commit
git commit -m "Initial commit: Portfolio website"

# Add remote (replace with your username)
git remote add origin https://github.com/Priya-Bhanu07/Priya-Bhanu07.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Web Interface**

1. In your repository, click **uploading an existing file**
2. Drag and drop ALL files including your `resume.pdf`
3. Commit with message "Initial commit"
4. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to repository **Settings** → **Pages**
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**

### Step 4: Access Your Website

After 2-5 minutes, your site will be live at:
```
https://Priya-Bhanu07.github.io/
```

## 🎨 Customization Guide

### Update Personal Information

Open `index.html` and update:

1. **Hero Section** (lines 27-35):
```html
<h1 class="hero-name">YOUR NAME</h1>
<p class="hero-tagline">Your Title | Developer | etc</p>
```

2. **Social Links** (lines 43-52):
```html
<a href="https://github.com/Priya-Bhanu07" target="_blank">
<a href="https://linkedin.com/in/yourprofile" target="_blank">
<a href="mailto:your@email.com">
```

3. **About Section** (lines 60-75):
   - Update your bio
   - Modify highlights (years, projects, technologies)

4. **Experience** (lines 82-150):
   - Add your work history
   - Update company names, dates, accomplishments
   - Modify tech tags

5. **Projects** (lines 157-240):
   - Update the 3 featured projects
   - Each project has: title, description, accomplishments, tech stack
   - Add your GitHub links

6. **Skills** (lines 247-290):
   - Update skill categories
   - Add/remove technologies

7. **Education** (lines 297-330):
   - Add your degrees
   - Update university, year, GPA

8. **Contact** (lines 337-390):
   - Update email, location, phone

### Change Colors

Open `assets/css/style.css` and modify (lines 6-18):

```css
:root {
    --primary-color: #2563eb;      /* Main brand color (blue) */
    --primary-dark: #1d4ed8;       /* Darker shade */
    --text-primary: #0f172a;       /* Main text color */
    --text-secondary: #475569;     /* Secondary text */
    /* ... more variables */
}
```

### Add Profile Photo (Optional)

1. Add your photo to `assets/images/your-photo.jpg`
2. Update hero section in `index.html`:
```html
<div class="hero-image">
    <img src="assets/images/your-photo.jpg" alt="Your Name">
</div>
```

## 🛠️ Local Development

### Preview Locally

**Using Python:**
```bash
cd portfolio
python -m http.server 8000
```

**Using Node.js:**
```bash
npx http-server -p 8000
```

**Using VS Code:**
- Install "Live Server" extension
- Right-click `index.html` → "Open with Live Server"

Visit: `http://localhost:8000`

## 📱 Browser Support

- Chrome (latest) ✓
- Firefox (latest) ✓
- Safari (latest) ✓
- Edge (latest) ✓
- Mobile browsers ✓

## 📊 Sections Overview

| Section | Content |
|---------|---------|
| **Hero** | Name, tagline, CTAs, social links |
| **About** | Bio, highlights (experience, projects, tech) |
| **Experience** | Timeline with 3 positions, accomplishments |
| **Projects** | 3 featured projects with details |
| **Skills** | 4 categories (Frontend, Backend, Database, Tools) |
| **Education** | Degrees, universities, grades |
| **Contact** | Contact form + contact information |

## 🎯 Key Features Explained

### Resume Download
- Located in navbar, hero, and footer
- Downloads `assets/resume.pdf` when clicked
- Make sure to add your PDF file!

### Project Cards
- Each shows: title, description, accomplishments (bullet points), tech stack
- Links to live demo and GitHub
- Hover effect with shadow and border

### Experience Timeline
- Clean card design with left border accent
- Bullet points for accomplishments
- Tech tags at bottom

### Contact Form
- Client-side validation
- Success/error notifications
- Console logs form data (add backend integration as needed)

## 📝 Checklist Before Deploying

- [ ] Add `resume.pdf` to `assets/` folder
- [ ] Update all personal information in `index.html`
- [ ] Update social media links (GitHub, LinkedIn)
- [ ] Update email address
- [ ] Customize projects with your work
- [ ] Update experience with your history
- [ ] Test locally (`python -m http.server 8000`)
- [ ] Push to GitHub
- [ ] Enable GitHub Pages in settings
- [ ] Test live site

## 🤝 Contributing

Feel free to fork and customize this portfolio for your own use!

## 📧 Contact

For questions or feedback: priya@example.com

---

**Made with ❤️ by [Priya Bhanu](https://github.com/Priya-Bhanu07)**

Inspired by: [varadbhogayata.github.io](https://varadbhogayata.github.io/)
