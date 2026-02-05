<div align="center">
  
# 🚀 Portfolio Website

### Modern, High-Performance Portfolio for GeoAI Full Stack Developer

[![Lighthouse Performance](https://img.shields.io/badge/Performance-100%25-success?style=for-the-badge&logo=lighthouse)](https://developers.google.com/web/tools/lighthouse)
[![Lighthouse Accessibility](https://img.shields.io/badge/Accessibility-100%25-success?style=for-the-badge&logo=lighthouse)](https://developers.google.com/web/tools/lighthouse)
[![React](https://img.shields.io/badge/React-18.3-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-7.3-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

[**Live Demo**](https://your-portfolio.vercel.app) · [**Report Bug**](../../issues) · [**Request Feature**](../../issues)

</div>

---

## ✨ Features

- 🎯 **Perfect Lighthouse Scores** - 100/100 Performance & Accessibility on Desktop
- 🎨 **Modern Design** - Sleek dark theme with purple/cyan gradient accents
- ⚡ **Lightning Fast** - Optimized with Vite, code splitting, and self-hosted fonts
- 🎭 **Interactive Animations** - Smooth transitions with Framer Motion and particles.js
- 📱 **Fully Responsive** - Seamless experience across all devices
- ♿ **Accessibility First** - WCAG compliant with semantic HTML and ARIA labels
- 🔍 **SEO Optimized** - Meta tags, structured data, and sitemap ready

---

## 🎬 Preview

<div align="center">
  <img src="https://via.placeholder.com/800x450/1d1836/915eff?text=Portfolio+Preview" alt="Portfolio Preview" width="800"/>
  
  *Clean, modern design with smooth animations and interactive elements*
</div>

---

## 🛠️ Tech Stack

### Core
![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=flat-square&logo=react)
![Vite](https://img.shields.io/badge/Vite-7.3.1-646CFF?style=flat-square&logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript)

### Styling
![CSS3](https://img.shields.io/badge/CSS3-Modern-1572B6?style=flat-square&logo=css3)
![Fontsource](https://img.shields.io/badge/Fonts-Self--Hosted-000000?style=flat-square)

### Libraries
![Framer Motion](https://img.shields.io/badge/Framer_Motion-Animations-0055FF?style=flat-square&logo=framer)
![tsParticles](https://img.shields.io/badge/tsParticles-Effects-000000?style=flat-square)
![Lottie](https://img.shields.io/badge/Lottie-React-00DDB3?style=flat-square)
![EmailJS](https://img.shields.io/badge/EmailJS-Contact_Form-DD0031?style=flat-square)

### Build & Deployment
![ESBuild](https://img.shields.io/badge/ESBuild-Bundler-FFCF00?style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-Deploy-000000?style=flat-square&logo=vercel)

---

## 📊 Performance Metrics

### Lighthouse Scores (Desktop)

| Metric | Score | Details |
|--------|-------|---------|
| 🚀 **Performance** | **100/100** | Optimized assets, code splitting, self-hosted fonts |
| ♿ **Accessibility** | **100/100** | WCAG compliant, semantic HTML, ARIA labels |
| ✅ **Best Practices** | **100/100** | Modern standards, secure headers |
| 🔍 **SEO** | **100/100** | Meta tags, structured data, sitemap |

### Core Web Vitals

| Metric | Value | Status |
|--------|-------|--------|
| **FCP** (First Contentful Paint) | < 1.0s | ✅ Excellent |
| **LCP** (Largest Contentful Paint) | < 1.5s | ✅ Excellent |
| **CLS** (Cumulative Layout Shift) | < 0.1 | ✅ Excellent |
| **SI** (Speed Index) | < 1.5s | ✅ Excellent |
| **TBT** (Total Blocking Time) | < 50ms | ✅ Excellent |

### Optimization Techniques

- ✅ Self-hosted WOFF2 fonts (eliminated external DNS lookups)
- ✅ Aggressive code splitting (React, animations, particles separate chunks)
- ✅ Critical CSS inlined in HTML
- ✅ Lazy loading for non-critical components
- ✅ Optimized images and assets
- ✅ Minified and compressed JavaScript/CSS

---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and npm/yarn installed
- Git for version control

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```
   
   Open [http://localhost:5173](http://localhost:5173) in your browser

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview production build**
   ```bash
   npm run preview
   ```

---

## 📁 Project Structure

```
portfolio/
├── public/
│   └── robots.txt          # SEO configuration
├── src/
│   ├── components/         # React components
│   │   ├── Hero.jsx       # Landing section
│   │   ├── About.jsx      # About section
│   │   ├── Skills.jsx     # Skills showcase
│   │   ├── Projects.jsx   # Project portfolio
│   │   ├── Publications.jsx # Research papers
│   │   ├── Contact.jsx    # Contact form
│   │   ├── Navbar.jsx     # Navigation bar
│   │   ├── Footer.jsx     # Footer section
│   │   └── InteractiveBackground.jsx # Particle effects
│   ├── assets/            # Images and media
│   ├── data.js            # Content data (projects, skills, etc.)
│   ├── index.css          # Global styles & design system
│   ├── App.jsx            # Main app component
│   └── main.jsx           # Application entry point
├── index.html             # HTML template with critical CSS
├── vite.config.js         # Vite configuration
├── package.json           # Dependencies
└── PROCESS.md             # Development process documentation
```

---

## 🎨 Design System

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| **Primary Purple** | `#915eff` | Primary brand color, CTAs |
| **Accent Cyan** | `#22d3ee` | Accents, links, highlights |
| **Dark Background** | `#050816` | Main background |
| **Card Background** | `#1d1836` | Section backgrounds |
| **Text Primary** | `#ffffff` | Headings, main text |
| **Text Secondary** | `#e0e7ff` | Descriptions, body text |

### Typography

- **Headings**: Playfair Display (serif)
- **Body**: Poppins (sans-serif)
- **UI Elements**: Outfit (sans-serif)

All fonts self-hosted for optimal performance.

---

## 📝 Customization Guide

### Update Personal Information

Edit `src/data.js` to customize:
- Your name and title
- Skills and expertise
- Projects and portfolio items
- Publications and research
- Social media links

### Modify Colors

Edit CSS variables in `src/index.css`:
```css
:root {
  --primary: #915eff;
  --accent-cyan: #22d3ee;
  --bg-primary: #050816;
  /* ... more variables */
}
```

### Add/Remove Sections

Components are modular. Simply import/remove from `src/App.jsx`:
```jsx
import Hero from './components/Hero'
import About from './components/About'
// Add or remove as needed
```

---

## 🌐 Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

2. **Deploy on Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Vercel auto-detects Vite
   - Click Deploy!

### Alternative: Deploy to Netlify

1. Build the project: `npm run build`
2. Drag and drop the `dist` folder to [Netlify Drop](https://app.netlify.com/drop)

---

## 📄 Documentation

- [**PROCESS.md**](./PROCESS.md) - Detailed development process, architecture decisions, and challenges
- [**Vite Documentation**](https://vitejs.dev/) - Build tool documentation
- [**React Documentation**](https://react.dev/) - React framework guide

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Your Name**

- Website: [your-portfolio.vercel.app](https://your-portfolio.vercel.app)
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

---

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- [Framer Motion](https://www.framer.com/motion/) for smooth animations
- [tsParticles](https://particles.js.org/) for interactive particle effects
- [EmailJS](https://www.emailjs.com/) for contact form functionality
- [Fontsource](https://fontsource.org/) for self-hosted fonts
- The React and Vite communities for excellent tooling

---

<div align="center">

### ⭐ Star this repo if you found it helpful!

**Made with ❤️ using React + Vite**

</div>
