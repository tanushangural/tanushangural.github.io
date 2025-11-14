# Tanush Angural - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Designed to showcase your skills, experience, projects, and provide a way for potential employers or clients to get in touch.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Dark Theme**: Easy on the eyes with a modern dark color scheme
- **Interactive Elements**: Smooth scrolling, animated sections, and hover effects
- **Contact Form**: Built-in contact form for easy communication
- **Social Links**: Quick links to GitHub, LinkedIn, and email
- **Resume Download**: Direct download link for your resume PDF

## 📁 Project Structure

```
Portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── Tanush_Angural_Resume.pdf  # Your resume (update as needed)
```

## 🚀 Deploying to GitHub Pages

Follow these steps to host your portfolio on GitHub Pages for **FREE**:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: If your username is `tanushangural`, name it `tanushangural.github.io`
   - This special naming makes it your personal GitHub Pages site
4. Make sure the repository is **Public**
5. Click "Create repository"

### Step 2: Push Your Code to GitHub

Open your terminal in the Portfolio folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote (replace with your URL)
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Scroll down and click "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"

### Step 4: Access Your Website

Your portfolio will be live at: `https://yourusername.github.io`

It may take a few minutes for the site to go live. Once it's ready, you can share this URL on your resume, LinkedIn, and with potential employers!

## ✏️ Customization Guide

Before deploying, make sure to customize the website with your information:

### 1. Update Personal Information (`index.html`)

Replace the following placeholder information:

- **Name**: Already set to "Tanush Angural"
- **Social Links**: 
  - Line 39-41: Update GitHub, LinkedIn, and Email links
  - Line 137-139: Update the same links in the footer
- **Email**: Replace `your.email@example.com` with your actual email
- **Profile Description**: Update the "About Me" section (lines 49-56)

### 2. Update Skills (`index.html`)

Edit the skills section (lines 70-113) to reflect your actual skills and technologies.

### 3. Update Experience (`index.html`)

Replace the placeholder experience entries (lines 120-145) with your actual work experience.

### 4. Update Projects (`index.html`)

Customize the project cards (lines 153-210) with your real projects:
- Project names and descriptions
- Technologies used
- GitHub repository links
- Live demo links

### 5. Update Contact Information (`index.html`)

Update the contact section (lines 218-250) with your:
- Email address
- LinkedIn profile URL
- GitHub profile URL

### 6. Add Your Resume

Make sure your resume PDF is named `Tanush_Angural_Resume.pdf` or update the filename in line 62 of `index.html`.

### 7. Customize Colors (Optional)

If you want different colors, edit the CSS variables in `styles.css` (lines 7-15):

```css
:root {
    --primary-color: #3b82f6;     /* Main accent color */
    --secondary-color: #8b5cf6;   /* Secondary accent */
    --accent-color: #10b981;      /* Additional accent */
    /* ... other colors ... */
}
```

## 🎨 Design Features

- **Gradient Effects**: Modern gradient backgrounds and text
- **Smooth Animations**: Fade-in effects and hover animations
- **Responsive Navigation**: Mobile-friendly hamburger menu
- **Card Layouts**: Clean card designs for projects and skills
- **Timeline View**: Professional timeline for experience
- **Interactive Forms**: Functional contact form

## 📱 Mobile Responsive

The website is fully responsive and works great on:
- Desktop computers (1200px+)
- Tablets (768px - 1199px)
- Mobile phones (up to 767px)

## 🔧 Advanced Features (Optional)

### Adding Email Functionality

The contact form currently shows an alert. To make it send actual emails:

1. Sign up for [EmailJS](https://www.emailjs.com/) (free)
2. Follow their setup guide
3. Uncomment and configure the EmailJS code in `script.js` (lines 61-66)

### Adding Google Analytics

To track visitors:

1. Get a Google Analytics ID
2. Add the tracking script before `</head>` in `index.html`

## 🆘 Troubleshooting

**Website not loading?**
- Wait 5-10 minutes after pushing to GitHub
- Check GitHub Pages settings are enabled
- Make sure `index.html` is in the root directory

**Images not showing?**
- Make sure all image paths are correct
- Use relative paths (e.g., `./image.jpg`)

**Contact form not working?**
- The basic form shows an alert - integrate EmailJS for real functionality

## 📄 License

Feel free to use this template for your personal portfolio. No attribution required!

## 🤝 Support

If you need help customizing or deploying your portfolio:
- Check GitHub Pages [documentation](https://docs.github.com/en/pages)
- Review HTML/CSS/JavaScript basics if needed
- Search for specific issues online

## 🎯 Next Steps

1. Customize all content with your information
2. Add your actual projects and links
3. Test locally by opening `index.html` in a browser
4. Deploy to GitHub Pages
5. Share your portfolio URL everywhere!

---

**Built with ❤️ for showcasing your amazing work!**
