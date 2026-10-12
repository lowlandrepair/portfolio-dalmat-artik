# 🎨 Dalmat Artik - 3D Animated Portfolio

A visually immersive and interactive **personal portfolio website**, showcasing business websites and digital projects through a dynamic 3D experience. Built by Dalmat Artik to demonstrate creative web development skills.

## 🌐 Live Demo
View the portfolio at: [https://lowlandrepair.github.io/portfolio-dalmat-artik/](https://lowlandrepair.github.io/portfolio-dalmat-artik/)

## ✨ Features

- **3D Interactive Experience** - Scroll-based 3D animations powered by Three.js
- **Smooth Animations** - GSAP and ScrollTrigger for cinematic transitions
- **Responsive Design** - Optimized for all devices and screen sizes
- **Modern UI/UX** - Clean, intuitive interface with elegant interactions
- **Business Portfolio** - Showcases business website development projects

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Core functionality
- **Three.js** - 3D rendering and scene management
- **GSAP** - High-performance animations
- **ScrollTrigger** - Scroll-based animation triggers

## 📂 Project Structure

```
portfolio-dalmat-artik/
├── index.html          # Main HTML file
├── index.css           # Styles
├── index.js            # JavaScript bundles
├── addcards.js         # Project cards configuration
├── head/               # Icons and manifests
├── icons/              # Pixel art icons
├── images/             # Project images
├── models/             # 3D models (GLB)
├── sounds/             # Audio effects
├── textures/           # Material textures
└── README.md           # This file
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/lowlandrepair/portfolio-dalmat-artik.git
   cd portfolio-dalmat-artik
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
     ```bash
     # Using Python
     python -m http.server 8080

     # Using Node.js
     npx http-server -p 8080
     ```

3. **Visit the site**
   - Navigate to `http://localhost:8080`

## 🎨 Customization

### Update Personal Information
Edit the following in `index.html`:
- Name and location in the About section
- Social media links
- Project descriptions in `addcards.js`

### Update Projects
Edit `addcards.js` to add, remove, or modify project cards:
```javascript
{
  id: 0,
  name: "Your Project",
  description: "Project description",
  image: "images/projects/your-image.png",
  tags: ["javascript", "html", "css"],
  liveview: null, // Set to URL or null for static
  alt: "Alt text for accessibility"
}
```

### Update Profile Picture
Replace `skills-profile-picture.png` with your own image.

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## ⚠️ Important Notes

- **3D Models**: The 3D character and environment models were purchased from a third-party marketplace. This project focuses on frontend development and animation integration.
- **Static Live View**: The "Live View" buttons are for demonstration purposes only and do not navigate to external sites.

## 👨‍💻 Author

**Dalmat Artik**
- Business Website Developer & Digital Artist
- Based in Kosova
- 🐙 GitHub: [@lowlandrepair](https://github.com/lowlandrepair)
- 📧 Email: dalmat.repair@gmail.com

## 📄 License

This project is for personal portfolio use. The 3D models and assets have their own licensing terms from their respective creators.

---

Built with ❤️ by Dalmat Artik

