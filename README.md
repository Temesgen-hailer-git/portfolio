

# 🌟 Temesgen Haile - Personal Portfolio Website

> A modern, responsive personal portfolio website showcasing expertise in Clinical Pharmacy and AI enthusiasm, built with vanilla HTML and CSS.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://temesgenhaile.netlify.app)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge)](https://github.com/Temesgen-hailer-git/portfolio.git)

---

## 📋 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📱 Responsive Design](#-responsive-design)
- [🏗️ Project Structure](#️-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🌐 Deployment Instructions](#-deployment-instructions)
- [🎨 Customization](#-customization)
- [🔧 Maintenance](#-maintenance)
- [📞 Support & Contact](#-support--contact)
- [📄 License](#-license)

---

## 🎯 Project Overview

This is a professional personal portfolio website for **Temesgen Haile**, a Senior Clinical Pharmacist with Public Health specialization. The website showcases professional background, educational credentials, technical skills, and personal interests in a clean, modern design.

### 🎯 Purpose
- Professional online presence for career opportunities
- Showcase clinical pharmacy expertise and AI interests
- Demonstrate web development skills with vanilla technologies
- Provide easy contact methods for networking and collaboration

---

## ✨ Features

### 🏠 **Hero Section**
- Eye-catching animated introduction
- Professional profile image
- Clear value proposition: "Clinical Pharmacist | AI Enthusiast"
- Call-to-action button for immediate contact

### 👤 **About Section**
- Comprehensive professional summary
- Interactive highlight cards with hover effects:
  - 💊 Medication Counseling
  - 🚛 Supply Chain Management
  - 👨‍🏫 Pharmaceutical Marketing
  - 🔬 Training & Education
- Downloadable CV functionality

### 🎓 **Education Section**
- Detailed educational background
- Interactive cards with graduation icons
- **Master's in General Public Health** (GMBC, 2022)
- **BSc in Clinical Pharmacy** (Gamby Medical College, 2021)
- Hover animations and smooth transitions

### 💻 **Skills Section**
- Categorized technical competencies:
  - **Web Technologies**: HTML, CSS, Python
  - **Software Tools**: Microsoft Office, DAGU, STATA
  - **Healthcare Systems**: Medical Records, Data Analysis
- Interactive skill boxes with hover effects

### 🎯 **Interests Section**
- Personal and professional interests:
  - 🤖 **Artificial Intelligence** in healthcare
  - 📚 **Continuous Learning** in pharmaceutical developments
  - 🥾 **Outdoor Activities** for work-life balance
- Modern card-based layout with engaging descriptions

### 📞 **Contact Section**
- **Contact Information**:
  - 📍 Location: Addis Ababa, Ethiopia
  - 📞 Phone: +251 912759033
  - 📧 Email: temash2017@gmail.com
- **Interactive Contact Form**:
  - Name, Email, and Message fields
  - Form validation
  - Professional styling

### 🎨 **Design Features**
- **Smooth scrolling navigation**
- **Gradient backgrounds and animations**
- **Responsive image handling**
- **Professional color scheme**
- **Font Awesome icons integration**
- **Google Fonts (Inter) integration**

---

## 🛠️ Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure & Content | HTML5 |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling & Animations | CSS3 |
| ![Font Awesome](https://img.shields.io/badge/Font%20Awesome-339AF0?style=flat-square&logo=fontawesome&logoColor=white) | Icons | 6.0.0 |
| ![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=flat-square&logo=google&logoColor=white) | Typography | Inter Font Family |

### 🎨 **Design Principles**
- **Progressive Enhancement**: Enhanced experience on larger screens
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Performance**: Optimized images and minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic structure

---

## 📱 Responsive Design

### 📐 **Breakpoints**
```css
- Mobile: < 768px (Primary focus)
- Tablet: 768px - 1024px
- Desktop: > 1024px
- Large Desktop: > 1200px
```

### 🔧 **Responsive Features**
- **CSS Grid & Flexbox**: Modern layout systems for flexible designs
- **Clamp() Functions**: Fluid typography that scales smoothly
- **CSS Custom Properties**: Consistent theming across all screen sizes
- **Touch-Optimized**: Button sizes and spacing optimized for mobile devices

---

## 🏗️ Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── style.css              # Main stylesheet
├── README.md              # Project documentation
├── image/                 # Image assets directory
│   ├── image_5.png       # Profile/hero image
│   ├── image_6.png       # About section image
│   └── CV-TM.pdf         # Downloadable CV
└── attached_assets/       # Development files
    ├── index_*.html      # HTML backup/versions
    └── style_*.css       # CSS backup/versions
```

---

## 🚀 Getting Started

### ⚡ **Quick Start**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Temesgen-hailer-git/portfolio.git
   cd portfolio
   ```

2. **Open locally**:
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
   ```bash
   

3. **View in browser**:
   - Navigate to `http://localhost:52330/portfolio`
   - The site will be fully functional locally

### 📋 **Prerequisites**
- Modern web browser (Chrome, Firefox, Edge)
- Internet connection (for Google Fonts and Font Awesome CDN)
- Text editor for customization (VS Code, Sublime Text, etc.)

---

## 🌐 Deployment Instructions

### 🌐 **GitHub Pages Deployment**
1. **Push to GitHub Repository**:
   ```bash
   git add .
   git commit -m "Deploy portfolio website"
   git push origin main
   ```
   Repository: [https://github.com/Temesgen-hailer-git/portfolio.git]


### 🌐 **Netlify Deployment (Recommended)**
2. **Deploy via Netlify**:
   - Go to [https://app.netlify.com](https://app.netlify.com)
   - Click **"Add new site" → "Import from GitHub"**
   - Connect your repository and deploy
   - **Live Site**: [https://temesgenhaile.netlify.app]


---

## 🎨 Customization

### 👤 **Personal Information**
Update your details in `index.html`:
```html
<!-- Hero Section -->
<h1>Hello, I'M [Your Name]</h1>
<p>[Your Profession] | [Your Specialization]</p>

<!-- Contact Information -->
<div class="info-item">
  <i class="fas fa-map-marker-alt"></i>
  <span>[Your Location]</span>
</div>
<div class="info-item">
  <i class="fas fa-phone"></i>
  <span>[Your Phone]</span>
</div>
<div class="info-item">
  <i class="fas fa-envelope"></i>
  <span>[Your Email]</span>
</div>
```

### 🎨 **Color Theme Customization**
Modify colors in `style.css` by editing the `:root` section:
```css
:root {
  --primary: #2c5282;        /* Main blue color */
  --secondary: #00a86b;      /* Green accent */
  --accent: #e53e3e;         /* Red accent */
  --light: #f7fafc;          /* Light background */
  --dark: #2d3748;           /* Dark text */
  --white: #fff;             /* White background */
  --hover-primary: #4299e1;  /* Hover blue */
  --hover-secondary: #38a169; /* Hover green */
}
```

### 📷 **Images and Assets**
1. **Profile Images**: Replace images in the `/image` directory
   - `image_5.png` - Hero section profile image
   - `image_6.png` - About section image
   - `CV-TM.pdf` - Your CV file

2. **Image Optimization Tips**:
   - Use optimized PNG or WebP formats
   - Recommended sizes: 400x400px for profile images
   - Compress images for faster loading

### 📑 **Content Sections**
#### **Add New Sections**:
```html
<!-- New Section Template -->
<section id="new-section" class="new-section">
  <h2>Section Title</h2>
  <div class="section-content">
    <!-- Your content here -->
  </div>
</section>
```

#### **Modify Existing Sections**:
- **Education**: Update degrees, institutions, and years
- **Skills**: Add/remove skills and categories
- **Interests**: Customize personal interests and descriptions

### 🎭 **Advanced Customizations**

#### **Add Animations**:
```css
.fade-in {
  opacity: 0;
  animation: fadeIn 1s ease-in forwards;
}


#### **Custom Fonts**:
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

---

## 🔧 Maintenance

### 📊 **Performance Optimization**
- **Image Compression**: Regularly optimize images using tools like TinyPNG
- **CSS Minification**: Minify CSS for production deployment
- **CDN Updates**: Keep Font Awesome and Google Fonts updated

### 🔄 **Regular Updates**
- **Content Refresh**: Update professional information quarterly
- **Security**: Monitor and update external CDN links
- **Browser Testing**: Test across different browsers periodically

### 📱 **Mobile Testing**
```bash
# Use browser dev tools to test different screen sizes
# Test on actual devices when possible
# Verify touch interactions work properly
```

---

## 📞 Support & Contact

### 🤝 **Get Help**
Have questions or need assistance with your portfolio?

- 📧 **Email**: [temash2017@gmail.com](mailto:temash2017@gmail.com)
- 📞 **Phone**: [+251 912759033]
- 📍 **GitHub**: [Portfolio Repository](https://github.com/Temesgen-hailer-git/portfolio.git)
- 🌐 **Live Site**: [temesgenhaile.netlify.app](https://temesgenhaile.netlify.app)

### 💡 **Feature Requests**
Found a bug or want to suggest improvements?
1. Open an issue on GitHub
2. Include detailed description and screenshots
3. Specify browser and device information

### 🎯 **Professional Services**
Interested in hiring Temesgen for:
- Clinical pharmacy consultation
- Healthcare technology projects
- AI applications in healthcare
- Public health research collaboration

---

## 📄 License

### 📜 **MIT License**
```
Copyright (c) 2025 Temesgen Haile


### 🎨 **Attribution**
- Icons provided by [Font Awesome](https://fontawesome.com/)
- Fonts provided by [Google Fonts](https://fonts.google.com/)
- Built with ❤️ using vanilla HTML & CSS

---

### 🚀 **Ready to Deploy Your Portfolio?**

[![Deploy to Netlify](https://img.shields.io/badge/Deploy%20to-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://app.netlify.com/start/deploy?repository=https://github.com/Temesgen-hailer-git/portfolio)

[![Deploy to Vercel](https://img.shields.io/badge/Deploy%20to-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/import/project?template=https://github.com/Temesgen-hailer-git/portfolio)

---

**⭐ Star this repository if it helped you build your portfolio!**

**🔄 Fork this repository to create your own version!**

---

*Built with passion by [Temesgen Haile](https://temesgenhaile.netlify.app) - Clinical Pharmacist & AI Enthusiast*


