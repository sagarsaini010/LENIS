# 🌐 Animated Web Page with Lenis & ScrollTrigger

This project is a smooth-scrolling, animation-rich web page built using [Lenis](https://github.com/studio-freight/lenis) for buttery scroll behavior and [GSAP ScrollTrigger](https://gsap.com/docs/v3/Plugins/ScrollTrigger/) for dynamic, scroll-based animations. Designed to demonstrate frontend interactivity layered over clean backend logic.

## 🚀 Features

- ✨ Smooth scrolling powered by Lenis
- 🎯 Scroll-triggered animations using GSAP ScrollTrigger
- 📱 Responsive design with interactive UI elements
- 🧩 Modular code structure for easy scalability
- ⚙️ Optimized for performance and visual appeal


## 🛠️ Tech Stack

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Lenis            | Smooth scroll behavior           |
| GSAP + ScrollTrigger | Scroll-based animations     |
| HTML/CSS/JS      | Core structure and styling       |
| [Optional] Vite/Webpack | Bundling and dev server |

## 📂 Folder Structure
project-root/ ├── index.html ├── script.js  └── README.md


## 📦 Installation

# Clone the repo
git clone https://github.com/your-username/lenis-scrolltrigger-page.git

# Navigate into the project
cd lenis-scrolltrigger-page

# Open index.html in your browser

🧠 How It Works
- Lenis intercepts native scroll events and replaces them with a smoother experience.
- ScrollTrigger listens to scroll positions and triggers animations based on element visibility.
- Animations are defined in script.js using GSAP timelines and triggers.
🖼️ Sample Animation Snippe

gsap.registerPlugin(ScrollTrigger);

gsap.from(".section-title", {
  scrollTrigger: {
    trigger: ".section-title",
    start: "top 80%",
    toggleActions: "play none none reverse"
  },
  y: 50,
  opacity: 0,
  duration: 1
});

Absolutely, Sagar! Here's a polished README.md template tailored for your animated webpage using Lenis and GSAP ScrollTrigger. It highlights your backend mindset while showcasing frontend finesse:
# 🌐 Animated Web Page with Lenis & ScrollTrigger

This project is a smooth-scrolling, animation-rich web page built using [Lenis](https://github.com/studio-freight/lenis) for buttery scroll behavior and [GSAP ScrollTrigger](https://gsap.com/docs/v3/Plugins/ScrollTrigger/) for dynamic, scroll-based animations. Designed to demonstrate frontend interactivity layered over clean backend logic.

## 🚀 Features

- ✨ Smooth scrolling powered by Lenis
- 🎯 Scroll-triggered animations using GSAP ScrollTrigger
- 📱 Responsive design with interactive UI elements
- 🧩 Modular code structure for easy scalability
- ⚙️ Optimized for performance and visual appeal



## 🛠️ Tech Stack

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Lenis            | Smooth scroll behavior           |
| GSAP + ScrollTrigger | Scroll-based animations     |
| HTML/CSS/JS      | Core structure and styling       |
| [Optional] Vite/Webpack | Bundling and dev server |


🧠 How It Works
- Lenis intercepts native scroll events and replaces them with a smoother experience.
- ScrollTrigger listens to scroll positions and triggers animations based on element visibility.
- Animations are defined in script.js using GSAP timelines and triggers.
🖼️ Sample Animation Snippet
gsap.registerPlugin(ScrollTrigger);

gsap.from(".section-title", {
  scrollTrigger: {
    trigger: ".section-title",
    start: "top 80%",
    toggleActions: "play none none reverse"
  },
  y: 50,
  opacity: 0,
  duration: 1
});


📌 To-Do / Improvements
- Add more animation layers (parallax, staggered effects)
- Integrate backend API for dynamic content
- Deploy on GitHub Pages or Vercel
🙌 Acknowledgements
- Studio Freight for Lenis
- GSAP for ScrollTrigger
- Inspiration from modern portfolio sites and interactive landing pages
📬 Contact
Made with ❤️ by Sagar Saini


