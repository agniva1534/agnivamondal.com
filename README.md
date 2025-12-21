# Agniva Mondal - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Data Analyst and Healthcare & Pharma Analytics specialist.

## 🚀 Features

- **Fully Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Sections Included**:
  - Hero/Landing page with professional introduction
  - Projects showcase with 3 featured projects
  - Awards & Recognition section
  - Technical Skills with progress bars and categorized display
  - Contact form with social media links
- **Smooth Scrolling**: Enhanced navigation experience
- **Mobile-Friendly Menu**: Hamburger menu for mobile devices

## 📁 Project Structure

```
.
├── index.html          # Main HTML file (all sections included)
├── README.md          # This file
└── (Optional: Add images folder for custom images)
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript**: Interactive features and form handling
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 🚀 Getting Started

### Running Locally

1. **Clone or download this repository**
   ```bash
   cd "/Users/agniva1534/Documents/Purdue /Cursor"
   ```

2. **Open the website**
   - **Option 1**: Simply open `index.html` in your web browser
   - **Option 2**: Use a local server (recommended for development)
     ```bash
     # Using Python 3
     python3 -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```
   - Then navigate to `http://localhost:8000` in your browser

3. **That's it!** The website should now be running locally.

## 📝 Customization Guide

### Update Personal Information

1. **Email**: Search for `agniva.mondal@example.com` and replace with your actual email
2. **LinkedIn**: Update the LinkedIn URL in the contact section and footer
3. **GitHub**: Update GitHub links in project cards and footer
4. **Location**: Update location in contact section if needed

### Add Your Photo

Replace the placeholder icon in the hero section:
- Find the `<i class="fas fa-user-circle...">` element
- Replace with an `<img>` tag pointing to your photo:
  ```html
  <img src="images/profile-photo.jpg" alt="Agniva Mondal" class="w-72 h-72 rounded-full object-cover">
  ```

### Update Project Links

1. Find each project card's GitHub link
2. Replace `href="#"` with your actual GitHub repository URLs
3. Update project descriptions and technologies as needed

### Add Project Images

1. Create an `images` folder in the project root
2. Add your project screenshots
3. Replace the gradient divs in project cards with:
   ```html
   <img src="images/project1.jpg" alt="Project Name" class="h-48 w-full object-cover">
   ```

### Modify Colors

The website uses a navy/teal/white color scheme. To change colors:
- Search for `teal-600`, `teal-400`, etc. and replace with your preferred color
- Search for `slate-900`, `slate-600`, etc. for navy colors
- Tailwind color classes: `teal-*`, `slate-*`, `blue-*`, `indigo-*`, etc.

## 🌐 Deployment Options

### GitHub Pages (Free & Easy)

1. **Create a GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Select `main` branch as source
   - Click Save
   - Your site will be live at `https://yourusername.github.io/portfolio`

### Netlify (Recommended)

1. **Drag and Drop**
   - Go to [netlify.com](https://netlify.com)
   - Drag your project folder to the deploy area
   - Your site is live instantly!

2. **Via Git**
   - Connect your GitHub repository
   - Netlify will auto-deploy on every push

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

### Other Options

- **AWS S3 + CloudFront**: For enterprise-level hosting
- **Firebase Hosting**: Google's hosting solution
- **Surge.sh**: Simple static site hosting
- **GitLab Pages**: Similar to GitHub Pages

## 📧 Contact Form Setup

The contact form is currently frontend-only (shows an alert). To make it functional:

### Option 1: Formspree (Easiest)

1. Sign up at [formspree.io](https://formspree.io)
2. Get your form endpoint
3. Update the form action:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Option 2: EmailJS

1. Sign up at [emailjs.com](https://emailjs.com)
2. Follow their setup guide
3. Add their JavaScript SDK and configure

### Option 3: Backend Integration

- Set up a Node.js/Express backend
- Use Nodemailer or SendGrid for email sending
- Update form submission to POST to your API

## 🎨 Design Customization

### Typography

The website uses Inter font from Google Fonts. To change:
- Update the Google Fonts link in the `<head>` section
- Modify font-family in the CSS

### Spacing & Layout

- All spacing uses Tailwind's utility classes
- Modify padding/margin classes as needed
- Responsive breakpoints: `sm:`, `md:`, `lg:`, `xl:`

## ✅ Future Enhancements

Here are some suggestions for improving the portfolio:

1. **Add Real Project Images**: Replace placeholder gradients with actual screenshots
2. **Add Blog Section**: Share your thoughts on data analytics
3. **Add Resume Download**: PDF download button
4. **Add Dark Mode**: Toggle between light/dark themes
5. **Add Animations**: More advanced scroll animations (AOS.js, Framer Motion)
6. **Add Analytics**: Google Analytics or Plausible for visitor tracking
7. **Add SEO**: Meta tags, Open Graph tags, structured data
8. **Add Testimonials**: Client or professor testimonials
9. **Add Certifications**: Display your certifications and achievements
10. **Add Timeline**: Education and work experience timeline

## 🐛 Troubleshooting

### Images Not Loading
- Check file paths are correct
- Ensure images are in the right folder
- Use relative paths (e.g., `images/photo.jpg`)

### Styles Not Applying
- Check internet connection (Tailwind CDN requires internet)
- Clear browser cache
- Check browser console for errors

### Form Not Working
- Ensure JavaScript is enabled
- Check browser console for errors
- Verify form action URL if using a service

## 📄 License

This portfolio template is free to use and modify for personal or commercial projects.

## 🙏 Credits

- **Tailwind CSS**: [tailwindcss.com](https://tailwindcss.com)
- **Font Awesome**: [fontawesome.com](https://fontawesome.com)
- **Google Fonts**: [fonts.google.com](https://fonts.google.com)

## 📞 Support

If you have questions or need help customizing this portfolio, feel free to reach out!

---

**Built with ❤️ for Agniva Mondal**

*Last Updated: 2024*

