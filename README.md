<div align="center">

# 🚀 Modern Portfolio Template

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/kalkidevs/morden_portfolio)

**A high-performance, visually stunning portfolio template for Full-Stack Engineers and Creatives**

Built with Tailwind CSS for styling and GSAP for cinema-grade animations

[View Demo](https://developeryk.vercel.app/) · [Report Bug](https://github.com/kalkidevs/morden_portfolio/issues) · [Request Feature](https://github.com/kalkidevs/morden_portfolio/issues)

</div>

---

## 📖 About The Project

This repository contains the source code for a **modern, minimalist, and highly interactive** portfolio website. Designed to be lightweight yet powerful, it utilizes a **single-file architecture** that requires no complex build steps or bundlers.

Perfect for developers who want to showcase their work with a professional edge, featuring:
- Smooth transitions and scroll-based animations
- A dedicated resume section with download capability
- Hidden interactive Easter eggs to delight visitors
- Zero-dependency setup that runs instantly

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| ⚡ **Zero-Build Setup** | Runs instantly in any browser. No `npm install` or webpack required |
| 🎨 **Tailwind CSS** | Rapid, responsive styling using the CDN—no compilation needed |
| 🎬 **GSAP Animations** | Smooth scroll triggers, staggered reveals, and layout transitions |
| 📱 **Fully Responsive** | Optimized for mobile, tablet, and desktop devices |
| ☕ **Developer Mode** | Hidden Easter Egg featuring physics-based coffee rain animation |
| 📂 **Dynamic Project Grid** | Filterable project showcase powered by vanilla JavaScript |
| 📄 **Integrated Resume** | Dedicated CV section with download options |
| 🎯 **Performance Optimized** | Lightweight bundle with CDN-based dependencies |

---

## 🛠️ Built With

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

- **HTML5** - Semantic markup for accessibility
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **GSAP (GreenSock)** - Professional web animation library
- **Lucide Icons** - Beautiful & consistent iconography

---

## 🚀 Getting Started

Getting up and running is **extremely simple**. Since this project uses CDNs, you don't need Node.js or a package manager.

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)

### Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/kalkidevs/morden_portfolio.git
```

2. **Navigate to the project directory:**
```bash
   cd morden_portfolio
```

3. **Open `index.html`:**
   - Simply double-click `index.html` to open it in your default web browser
   - Or use a local server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code

**That's it!** 🎉 Your portfolio is now running locally.

---

## 📝 Usage & Customization

This template is designed to be **easily customizable**. All content is located within `index.html`.

### 1️⃣ Update Personal Information

Look for the **Navigation** and **Hero Section** comments in the code to replace placeholder text with your information:
```html
<!-- Replace with your name -->
<h1 class="text-5xl font-bold">Your Name</h1>

<!-- Update social links -->
<a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
<a href="https://github.com/yourusername">GitHub</a>
```

### 2️⃣ Modify Projects

Scroll down to the `<script>` tag at the bottom of the body. You will find a `projects` array. Modify the objects to reflect your own work:
```javascript
const projects = [
    {
        title: "Your Project Name",
        category: ["application", "backend"], // Categories for filtering
        desc: "A brief description of what you built and the problem it solves.",
        tags: ["React", "Node.js", "MongoDB"], // Tech stack tags
        color: "blue" // Accent color (blue, purple, green, orange)
    },
    {
        title: "Another Amazing Project",
        category: ["frontend", "design"],
        desc: "Showcase your design and frontend development skills.",
        tags: ["Vue.js", "Tailwind", "Figma"],
        color: "purple"
    },
    // Add more projects here...
];
```

### 3️⃣ Update Resume Link

Upload your resume PDF to the root folder (or host it online) and update the `href` attribute:
```html
<a href="path/to/YOUR_RESUME.pdf" target="_blank" download>
    Download Resume
</a>
```

### 4️⃣ Customize Colors & Styling

All styling uses Tailwind utility classes. To change colors, modify the class names:
```html
<!-- Change primary color from blue to purple -->
<button class="bg-purple-600 hover:bg-purple-700">Click Me</button>
```

---

## 🎨 Project Structure
```
morden_portfolio/
│
├── index.html          # Main HTML file (contains everything!)
├── README.md           # Project documentation
└── assets/             # Optional: Add images, resume PDF, etc.
    ├── resume.pdf
    └── images/
```

---

## 🌟 Screenshots

<div align="center">

### Desktop View
![Desktop View Placeholder](/assets/images/profile_view.png)

### Mobile View
![Mobile View Placeholder](https://via.placeholder.com/400x600/0891b2/ffffff?text=Mobile+View)

### Easter Egg: Developer Mode ☕
![Easter Egg Placeholder](/assets/images/dev_mode.png)

</div>

---

## 🎯 Roadmap

- [x] Single-file architecture
- [x] GSAP scroll animations
- [x] Hidden Easter egg feature
- [ ] Dark/Light mode toggle
- [ ] Contact form integration
- [ ] Blog section template
- [ ] Multi-page version
- [ ] CMS integration guide

See the [open issues](https://github.com/kalkidevs/morden_portfolio/issues) for a full list of proposed features and known issues.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🌟 Show Your Support

If you found this portfolio template helpful or if you're using it to build your own site, please give it a **Star** ⭐️! 

It helps others discover the project and motivates me to add more features.

<div align="center">

### ⭐️ Don't forget to star the repo! ⭐️

</div>

---

## 🤝 Contact & Connect

<div align="center">

**Yash Kushwaha**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yashkushwaha333)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kalkidevs)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Yashkushwaha65@gmail.com)

</div>

---

## 💡 Easter Egg Hunt

**Did you find the hidden feature?** ☕

> 🕵️ **Hint:** Try clicking the logo 5 times in a row and watch the magic happen!

Share your discovery on Twitter with `#ModernPortfolioTemplate` and tag me!

---

<div align="center">

**Made with ❤️ by Yash Kushwaha**

[⬆ Back to Top](#-modern-portfolio-template)

</div>