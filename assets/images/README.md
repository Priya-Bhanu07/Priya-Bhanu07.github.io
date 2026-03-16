# How to Add Your Project Images

## 📷 Adding Screenshots to Your Portfolio

Your portfolio is set up with beautiful image placeholders. Here's how to add your actual project screenshots:

### Step 1: Prepare Your Images
- Take screenshots of your projects
- Recommended size: 600x400 pixels (or similar aspect ratio)
- Format: JPG or PNG
- Name them descriptively:
  - `order-delivery-service.jpg`
  - `pickle-shop-backend.jpg`
  - `dsa-platform.jpg`

### Step 2: Add Images to Folder
Copy your images to:
```
/home/bhanup/Main/Projects/portfolio/assets/images/
```

### Step 3: Update HTML (Optional - for actual images)
If you want to display actual images instead of placeholders, update `index.html`:

Find this section (around line 245):
```html
<div class="project-image-box">
    <div class="project-image-placeholder">
        <i class="fas fa-shipping-fast"></i>
    </div>
    <p class="project-image-note">📷 Add your project screenshot here</p>
</div>
```

Replace with:
```html
<div class="project-image-box">
    <img src="assets/images/order-delivery-service.jpg" alt="Order Delivery Service" class="project-screenshot">
</div>
```

### Step 4: Add CSS for Images (Optional)
Add this to `assets/css/style.css`:
```css
.project-screenshot {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 8px;
    display: block;
    margin: 0 auto 15px;
}
```

---

## 📄 Adding Your Resume

1. Export your resume as PDF
2. Name it: `resume.pdf`
3. Copy to: `assets/resume.pdf`

---

## Current Folder Structure

```
portfolio/
├── index.html
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   ├── images/          ← Add project screenshots here
│   │   └── (add your images)
│   └── resume.pdf       ← Add your resume here
└── README.md
```

---

## Tips for Great Screenshots

1. **Use high contrast** - Make sure text is readable
2. **Show key features** - Display the main functionality
3. **Consistent sizing** - Keep all images similar dimensions
4. **Compress images** - Keep file size under 500KB each
5. **Professional look** - Use clean browser windows without personal tabs/bookmarks

---

## Alternative: Keep Placeholders

The current design looks great with the icon placeholders! You can keep them as-is if you prefer not to add screenshots yet.

The gradient boxes with icons are:
- Modern and professional
- Fast loading
- Consistent appearance
- No maintenance needed
