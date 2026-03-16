# Portfolio Website - Priya Bhanu

A professional Java Backend Developer portfolio, exactly like [varadbhogayata.github.io](https://varadbhogayata.github.io/).

**LinkedIn**: https://www.linkedin.com/in/bhanu-priya-0547673b7/

---

## 📁 Project Structure

```
portfolio/
├── index.html              # Main website
├── assets/
│   ├── css/style.css      # Styling with boxes
│   ├── js/main.js         # JavaScript
│   ├── images/            # 📷 Add project screenshots here
│   ├── resume.html        # 📄 Resume (convert to PDF)
│   └── resume.pdf         # ⚠️ YOUR RESUME PDF (after conversion)
└── README.md              # This file
```

---

## ⚠️ IMPORTANT: Create Your Resume PDF

### Method 1: Convert resume.html to PDF (Recommended)

1. **Open resume.html in browser**:
   ```bash
   xdg-open /home/bhanup/Main/Projects/portfolio/assets/resume.html
   ```
   Or double-click the file in your file manager.

2. **Print to PDF**:
   - Press `Ctrl + P` (Print)
   - Select **"Save as PDF"** as destination
   - Set margins to **None** or **Minimum**
   - Enable **Background graphics** (for colors)
   - Click **Save**
   - Save as: `resume.pdf` in the `assets/` folder

3. **Verify**:
   ```bash
   ls -lh /home/bhanup/Main/Projects/portfolio/assets/resume.pdf
   ```

### Method 2: Use Your Existing Resume

If you already have a resume PDF:
```bash
cp /path/to/your/resume.pdf /home/bhanup/Main/Projects/portfolio/assets/resume.pdf
```

---

## 📷 Add Project Images (Optional)

Your portfolio has beautiful gradient boxes with icons. To add actual screenshots:

1. **Prepare images** (600x400px recommended)
2. **Copy to folder**:
   ```bash
   cp your-screenshot.jpg /home/bhanup/Main/Projects/portfolio/assets/images/
   ```
3. **Update HTML** in `index.html` (see `assets/images/README.md`)

---

## 🚀 Deploy to GitHub Pages

### 1. Create Resume PDF First
Follow the steps above to create `resume.pdf`

### 2. Deploy
```bash
cd /home/bhanup/Main/Projects/portfolio

# Add all files including resume.pdf
git add .

# Commit
git commit -m "Complete portfolio with resume"

# Push
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to: https://github.com/Priya-Bhanu07/Priya-Bhanu07.github.io/settings/pages
2. **Branch**: Select `main`
3. **Folder**: `/ (root)`
4. Click **Save**

### 4. Wait 2-5 Minutes
Your site will be live at: **https://Priya-Bhanu07.github.io/**

---

## ✨ What's Included

### ✅ Your Professional Summary
> "Results-driven Java Backend Developer with 3 years of experience..."

### ✅ Technical Skills (4 Beautiful Boxes)
- **Languages & Frameworks**: Java 17, Spring Boot, Spring MVC, Hibernate, Microservices, JPA, Spring Security, Spring AI
- **Web & APIs**: RESTful APIs, JavaScript, HTML5, CSS, jQuery, AJAX, Bootstrap, React
- **DevOps & Cloud**: Docker, Kubernetes, AWS, CI/CD
- **Databases**: PostgreSQL, SQL Server

### ✅ Work Experience (3 Positions in Boxes)
1. **KOTT SOFTWARE** - Software Engineer (Oct 2023 – Jun 2025)
   - EASE Application project
   - All 5 accomplishments
   
2. **DAIVIKSOFT TECHNOLOGIES** - Software Engineer (Jun 2022 – Jun 2023)
   - Ritz-Carlton Yacht Collection project
   - All 4 accomplishments
   
3. **NEX-C INNOVATIONS** - Java Full Stack Intern
   - Professional development program
   - All accomplishments

### ✅ Technical Projects (3 Cards with Image Boxes)
1. **Order Assignment & Delivery Partner Service**
2. **Pickle Shop Backend**
3. **DSA Coding Practice Platform**

Each with:
- Icon/image placeholder (gradient box)
- Project description
- Key features (bullet points)
- Technologies used
- GitHub link

### ✅ Education
- **MCA** - Cochin University of Science and Technology (9.2 GPA)
- **BCA** - Asansol Girls' College (8.5 GPA)

### ✅ Contact Section
- Contact form
- Email, Location, Availability
- **GitHub**: https://github.com/Priya-Bhanu07
- **LinkedIn**: https://www.linkedin.com/in/bhanu-priya-0547673b7/

---

## 🎨 Design Features

- ✅ **Centered single-column layout** (like varadbhogayata.github.io)
- ✅ **Skills in beautiful boxes** with icons
- ✅ **Experience in bordered cards** with left accent
- ✅ **Projects with image placeholders** (gradient boxes with icons)
- ✅ **Professional color scheme** (Blue #0066cc)
- ✅ **Responsive design** (mobile, tablet, desktop)
- ✅ **Smooth scrolling** navigation
- ✅ **Hover effects** on cards and buttons
- ✅ **LinkedIn integrated** in hero, contact, and footer

---

## 🖥️ Preview Locally

```bash
cd /home/bhanup/Main/Projects/portfolio
python3 -m http.server 8000
```

Open: http://localhost:8000

Or simply open: `file:///home/bhanup/Main/Projects/portfolio/index.html`

---

## 📝 What to Update in index.html

### Email (Line 60, 300, 336)
Replace `priya@example.com` with your actual email.

### Phone (Optional - Line 306)
Update with your phone number.

---

## 📋 Deployment Checklist

- [ ] Resume PDF created from `assets/resume.html`
- [ ] Resume saved as `assets/resume.pdf`
- [ ] Email updated in contact section
- [ ] All experience matches your resume
- [ ] Projects are accurate
- [ ] Education is correct
- [ ] LinkedIn URL is correct: https://www.linkedin.com/in/bhanu-priya-0547673b7/
- [ ] GitHub URL is correct: https://github.com/Priya-Bhanu07
- [ ] Tested locally
- [ ] Pushed to GitHub
- [ ] GitHub Pages enabled
- [ ] Live site tested

---

## 🔧 Troubleshooting

**Resume download not working?**
- Check file is named exactly `resume.pdf` (lowercase)
- Verify it's in `assets/` folder
- Clear browser cache (Ctrl + Shift + R)

**Site not showing updates?**
- Wait 2-5 minutes after pushing
- Hard refresh: Ctrl + Shift + R

**GitHub Pages not working?**
- Repository must be: `Priya-Bhanu07.github.io`
- Repository must be **Public**
- Check Settings → Pages → Branch = `main`

---

## 📄 Resume Details

Your resume (`resume.html`) includes:

### Header
- Name: Priya Bhanu
- Title: Java Backend Developer
- Contact: Email, Phone, GitHub, LinkedIn

### Sections
1. **Professional Summary** - Your complete summary
2. **Technical Skills** - All 4 categories
3. **Work Experience** - All 3 positions with details
4. **Technical Projects** - All 3 projects
5. **Education** - MCA and BCA with GPAs

### To Edit Resume
1. Open `assets/resume.html` in a text editor
2. Update your details
3. Save and convert to PDF again

---

## 🎯 Key Features

| Section | Design |
|---------|--------|
| **Skills** | 4 boxes with icons and checkmarks |
| **Experience** | Cards with left border accent + project names |
| **Projects** | Gradient boxes with icons (can add images) |
| **Education** | Cards with GPA badges |
| **Contact** | Form + info cards + social links |
| **Resume** | Professional HTML → PDF format |

---

## 📧 Contact Links Updated

All sections now include your correct LinkedIn:
- **Hero section**: LinkedIn icon
- **Contact section**: LinkedIn button
- **Footer**: LinkedIn icon

URL: https://www.linkedin.com/in/bhanu-priya-0547673b7/

---

**Made with ❤️ by Priya Bhanu**

Inspired by: https://varadbhogayata.github.io/

**LinkedIn**: https://www.linkedin.com/in/bhanu-priya-0547673b7/

**GitHub**: https://github.com/Priya-Bhanu07
