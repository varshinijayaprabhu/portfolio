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

## 🎨 Design Philosophy

This portfolio was designed with a focus on:
- **Modern Aesthetics** - Clean, minimal design with bold gradients and smooth animations
- **User Experience** - Intuitive navigation with smooth scrolling and interactive elements
- **Performance** - Optimized loading times without sacrificing visual appeal
- **Accessibility** - Ensuring everyone can access and navigate the portfolio

---

## 🛠️ Design & Development Tools

### Design Resources
- **Color Palette**: Custom purple/cyan gradient theme designed for tech/GeoAI branding
- **Typography**: Google Fonts (self-hosted for performance)
  - Playfair Display - Elegant serif for headings
  - Poppins - Clean sans-serif for body text
  - Outfit - Modern UI elements
- **Icons**: React Icons library
- **Animations**: Framer Motion for smooth, physics-based animations
- **Background Effects**: tsParticles for interactive particle system

### Development Stack
- **Framework**: React 18.3 with functional components and hooks
- **Build Tool**: Vite 7.3 for lightning-fast development and optimized builds
- **Styling**: Vanilla CSS with CSS Variables for theming
- **Version Control**: Git & GitHub
- **Deployment**: Vercel for instant deployment and previews

### Development Workflow
1. **Component-First Approach** - Built modular, reusable React components
2. **Content Separation** - All data centralized in `data.js` for easy updates
3. **Performance Optimization** - Code splitting, lazy loading, self-hosted fonts
4. **Continuous Testing** - Tested across devices and browsers during development

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

## ⚡ Project Highlights

### Technical Achievements
- ✅ **Optimized Performance** - 100/100 Lighthouse scores on desktop
- ✅ **Self-Hosted Fonts** - Eliminated external CDN dependencies for faster loading
- ✅ **Code Splitting** - Separate bundles for React, animations, and effects
- ✅ **Accessibility** - WCAG compliant with semantic HTML and proper ARIA labels

### Portfolio Sections
- **Hero** - Animated landing with particle effects
- **About** - Professional summary with skills overview
- **Projects** - Filterable project showcase with live links
- **Publications** - Research papers and technical writing
- **Contact** - Functional contact form with EmailJS integration

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm
- Git

### Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/varshinijayaprabhu/portfolio.git
cd portfolio

# 2. Install dependencies
npm install

# 3. Start development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

### Build Commands

```bash
# Create production build
npm run build

# Preview production build locally
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
