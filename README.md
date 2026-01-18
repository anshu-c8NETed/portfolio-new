# 🚀 Anshu Raj - Portfolio

A cutting-edge, developer-themed portfolio showcasing full-stack development expertise with stunning 3D graphics, smooth animations, and a cyberpunk aesthetic.


## ✨ Features

### 🎨 Visual Design
- **Cyberpunk Aesthetic** - Dark theme with neon accents (green, blue, purple)
- **Custom Cursor** - Interactive arrow cursor with section-based color changes (desktop only)
- **3D Graphics** - Three.js powered helmet model with particle systems
- **Smooth Animations** - GSAP-powered scroll animations and transitions
- **Responsive Design** - Fully optimized for mobile, tablet, and desktop

### 🛠️ Technical Highlights
- **React 18** - Modern component architecture with hooks
- **Three.js & React Three Fiber** - 3D web graphics and WebGL
- **GSAP & ScrollTrigger** - Professional-grade animations
- **Lenis** - Smooth scroll implementation
- **Tailwind CSS** - Utility-first styling with custom theme
- **Vite** - Lightning-fast build tool

### 📱 Sections
1. **Hero** - Dynamic intro with 3D helmet, tech stack carousel, and stats
2. **Service Summary** - Animated skill showcase with parallax effects
3. **Services** - Detailed service offerings with sticky scroll
4. **About** - Personal introduction with achievements and tech arsenal
5. **Works** - Featured projects with hover previews
6. **Contact** - Multiple contact methods with animated marquee

## 🎯 Key Animations

- **Loading Screen** - Custom progress bar with shimmer effects
- **Scroll-Triggered Reveals** - Staggered fade-ins for content
- **Magnetic Buttons** - Interactive hover effects on CTAs
- **Parallax Text** - Dynamic text movement on scroll
- **Image Reveals** - Clip-path animations for photos
- **Hover Previews** - Project image follows cursor (desktop)

## 📁 Project Structure

```
portfolio/
├── public/
│   ├── assets/
│   │   └── projects/          # Project images
│   ├── images/                # Profile images
│   └── resume/                # Resume PDF
├── src/
│   ├── components/
│   │   ├── AnimatedHeaderSection.jsx
│   │   ├── AnimatedTextLines.jsx
│   │   ├── CustomCursor.jsx
│   │   └── Marquee.jsx
│   ├── sections/
│   │   ├── Hero.jsx
│   │   ├── ServiceSummary.jsx
│   │   ├── Services.jsx
│   │   ├── About.jsx
│   │   ├── Works.jsx
│   │   ├── ContactSummary.jsx
│   │   ├── Contact.jsx
│   │   └── Navbar.jsx
│   ├── constants/
│   │   └── index.js           # Site data & content
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css              # Global styles & theme
└── package.json
```

## 🎨 Customization

### Theme Colors

```css
--color-primary: #0a0a0a;      /* Background */
--color-accent: #00ff88;        /* Neon green */
--color-accent-blue: #00d4ff;   /* Neon blue */
--color-accent-purple: #b77bff; /* Neon purple */
```

### Fonts
Three custom fonts are used:
- **Syne** - Display headings
- **Space Grotesk** - Body text
- **JetBrains Mono** - Code/mono elements

## 📦 Dependencies

### Core
- `react` - UI framework
- `react-dom` - React renderer
- `vite` - Build tool

### Animation & 3D
- `gsap` - Animation library
- `three` - 3D graphics
- `@react-three/drei` - React Three Fiber helpers
- `@react-three/fiber` - React renderer for Three.js
- `lenis` - Smooth scroll

### UI & Icons
- `@iconify/react` - Icon system
- `react-scroll` - Smooth scroll navigation
- `react-responsive` - Responsive utilities

## 🎯 Performance Optimizations

- **Code Splitting** - Dynamic imports for heavy components
- **Image Optimization** - Lazy loading and proper formats
- **3D Model Optimization** - Efficient geometry and materials
- **Animation Performance** - GPU-accelerated transforms
- **Mobile Optimizations** - Disabled 3D on mobile, simplified animations

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

**Note:** Custom cursor and some animations are disabled on mobile for performance.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contact

- **Email** - rajanshu2123@gmail.com
- **GitHub** - [@anshu-c8NETed](https://github.com/anshu-c8NETed)
- **LinkedIn** - [anshu-raj-tech](https://www.linkedin.com/in/anshu-raj-tech)
- **LeetCode** - [@anshxu](https://leetcode.com/u/anshxu)

## 🙏 Acknowledgments

- 3D Model from [Khronos glTF Sample Models](https://github.com/KhronosGroup/glTF-Sample-Models)
- Inspired by modern developer portfolios
- Built with passion for clean code and great UX

---

**Made with 💚 and ☕ by Anshu Raj**

*If you found this helpful, consider giving it a ⭐!*
