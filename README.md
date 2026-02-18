# Personal Profile Website

A modern, responsive personal profile and portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## 🚀 Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and form validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Smooth Animations**: Scroll-triggered animations and transitions
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 📁 File Structure

```
personal-profile-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Download/Clone**: Save all files to a folder on your computer
2. **Open**: Double-click `index.html` or open it in your web browser
3. **Customize**: Edit the content in `index.html` to personalize your information
4. **Deploy**: Upload the files to any web hosting service

## ✏️ Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Full Stack Developer & Designer</p>
```

#### About Section
```html
<p>I'm a passionate developer with a love for creating meaningful digital experiences...</p>
```

#### Skills
```html
<span class="skill-item">HTML5</span>
<span class="skill-item">CSS3</span>
<!-- Add/remove skills as needed -->
```

#### Projects
```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description...</p>
    <!-- Update project details -->
</div>
```

#### Contact Information
```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Country</span>
```

### Colors and Styling

Edit `styles.css` to customize colors, fonts, and overall appearance:

#### Primary Colors
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #ffd89b;
}
```

#### Fonts
```css
body {
    font-family: 'Inter', sans-serif; /* Change to your preferred font */
}
```

### Profile Picture

Replace the placeholder icon with your actual profile picture:

1. Add your image to the project folder
2. Update the hero section in `index.html`:
```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-photo">
</div>
```
3. Add CSS for the image in `styles.css`:
```css
.profile-photo {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify (Free)
1. Drag and drop your project folder to [netlify.com](https://netlify.com)
2. Get instant live URL

### Vercel (Free)
1. Connect your GitHub repository to [vercel.com](https://vercel.com)
2. Automatic deployment on every push

### Traditional Hosting
Upload files via FTP to any web hosting service

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 767px and below

## 🎨 Design Features

- **Gradient Backgrounds**: Modern gradient combinations
- **Card-based Layout**: Clean, organized content presentation
- **Hover Effects**: Interactive elements with smooth transitions
- **Typography**: Professional font hierarchy and spacing
- **Shadows**: Subtle depth and modern feel

## 🔧 Technical Features

- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Variables**: Easy color and style management
- **Intersection Observer**: Performance-optimized animations
- **Form Validation**: Client-side input validation
- **Smooth Scrolling**: Enhanced user experience

## 📧 Contact Form

The contact form includes:
- Name, email, subject, and message fields
- Client-side validation
- Success/error notifications
- Form reset after submission

**Note**: The form currently shows a success message. To make it functional, you'll need to:
1. Add a backend service (Formspree, Netlify Forms, etc.)
2. Update the form action and method attributes
3. Or integrate with your preferred form handling service

## 🚀 Performance Tips

- Optimize images before adding them
- Minify CSS and JavaScript for production
- Use a CDN for external resources
- Enable gzip compression on your server

## 🐛 Troubleshooting

### Common Issues

1. **Fonts not loading**: Check internet connection for Google Fonts
2. **Icons not showing**: Ensure Font Awesome CDN is accessible
3. **Layout broken**: Check if all CSS and JS files are in the same folder

### Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve this template.

## 📞 Support

If you need help customizing or have questions:
1. Check the customization guide above
2. Review the code comments
3. Open an issue in the repository

---

**Happy coding! 🎉**

Your personal profile website is ready to showcase your skills and experience to the world! 