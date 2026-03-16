# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and experience.

![Portfolio Preview](./preview.png)

## ✨ Features

- **Responsive Design** - Looks great on all devices (desktop, tablet, mobile)
- **Modern UI/UX** - Clean and professional design with smooth animations
- **Interactive Elements** - Hover effects, scroll animations, and 3D card tilts
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Smooth Scrolling** - Seamless navigation between sections
- **Contact Form** - Built-in form with validation
- **Dark/Light Theme Ready** - Easy to customize color scheme
- **SEO Optimized** - Meta tags and semantic HTML
- **Fast Performance** - Lightweight and optimized code

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # All styles
│   └── js/
│       └── main.js        # JavaScript functionality
└── README.md              # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com/) and log in
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository: `username.github.io` (replace `username` with your GitHub username)
   - For example: `Priya-Bhanu07.github.io`
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Your Files

**Option A: Using Git Command Line**

```bash
# Navigate to your portfolio directory
cd /path/to/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Portfolio website"

# Add your remote repository (replace with your repo URL)
git remote add origin https://github.com/Priya-Bhanu07/Priya-Bhanu07.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Web Interface**

1. In your repository, click **uploading an existing file**
2. Drag and drop all your files or click **choose your files**
3. Commit the changes with a message like "Initial commit"
4. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings**
2. Click on **Pages** in the left sidebar
3. Under **Source**, select:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
4. Click **Save**

### Step 4: Access Your Website

After a few minutes, your website will be live at:
```
https://Priya-Bhanu07.github.io/
```

## 🎨 Customization

### Update Personal Information

Open `index.html` and update:

1. **Name & Title** (lines 27-29):
```html
<h1 class="name">Your Name</h1>
<h2 class="title">Your Title</h2>
```

2. **Social Links** (lines 43-52):
```html
<a href="https://github.com/yourusername" target="_blank">
<a href="https://linkedin.com/in/yourprofile" target="_blank">
<a href="mailto:your@email.com">
```

3. **About Section** (lines 69-80):
   - Update the description text
   - Modify stats (years of experience, projects, etc.)

4. **Skills** (lines 95-130):
   - Add/remove skill tags as needed

5. **Projects** (lines 137-220):
   - Update project details
   - Add your project images
   - Link to live demos and GitHub repos

6. **Experience** (lines 227-275):
   - Add your work history
   - Update company names and dates

7. **Contact Info** (lines 285-320):
   - Update email and location

### Change Colors

Open `assets/css/style.css` and modify the CSS variables (lines 6-20):

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --primary-dark: #4f46e5;       /* Darker shade */
    --secondary-color: #ec4899;    /* Accent color */
    --text-primary: #1f2937;       /* Main text color */
    --text-secondary: #6b7280;     /* Secondary text */
    /* ... more variables */
}
```

### Add Your Profile Image

1. Add your image to `assets/images/` folder
2. Update the hero section in `index.html`:
```html
<div class="image-container">
    <img src="assets/images/your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

3. Add CSS for the image in `style.css`:
```css
.profile-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
}
```

## 🛠️ Local Development

### Preview Locally

Simply open `index.html` in your browser, or use a local server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
```

**Using VS Code:**
- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

Then visit `http://localhost:8000`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📧 Contact

For questions or feedback, reach out at: your@email.com

---

Made with ❤️ by [Priya Bhanu](https://github.com/Priya-Bhanu07)
