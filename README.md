# Apple iPhone 15 Pro – Interactive Web Experience

A high-fidelity, Apple-inspired interactive web experience showcasing the **iPhone 15 Pro**. This project focuses on **advanced UI animation, 3D rendering, and smooth user interaction**, combining **GSAP**, **React Three Fiber**, and **modern frontend architecture** to deliver a premium, product-level presentation.

This project was developed by following a **tutorial from the YouTube channel *JavaScript Mastery***, which itself was created using the **visual design and inspiration of the Apple website**. The purpose of this project is **educational and portfolio-oriented**, showcasing advanced frontend techniques used in modern, animation-heavy web experiences.

![apple](https://github.com/user-attachments/assets/de5426e7-116a-4371-bc1e-afaa02028926)

---

## 📌 Project Context & Attribution

* **Tutorial Source:**  
  JavaScript Mastery (YouTube)

* **Design Inspiration:**  
  Apple iPhone 15 Pro Page (Original website design)

* **Project Purpose:**  
  Learning and demonstrating:
  * 3D rendering in the browser with React Three Fiber
  * Advanced GSAP + ScrollTrigger synchronization
  * Dynamic video carousel management
  * Performance monitoring with Sentry

> [!IMPORTANT]  
> This project is **not an original product design**.  
> It is an **educational implementation** intended to practice and demonstrate frontend engineering skills based on an existing tutorial and design reference.

---

## ✨ Features

- **Apple-style Hero Section**
  - Responsive video source switching (desktop / mobile)
  - GSAP-powered entrance animations

- **Animated Highlights Carousel**
  - Smooth horizontal video transitions
  - Scroll-triggered playback
  - Custom progress indicators synchronized with video duration
  - Play / Pause / Replay controls

- **Interactive 3D iPhone Model**
  - Real-time 3D rendering with **React Three Fiber**
  - Color and size switching
  - Orbit controls with rotation state tracking
  - Seamless animated transitions between model views

- **Advanced Animations**
  - GSAP + ScrollTrigger integration
  - Timeline-based transitions
  - Precise video ↔ animation synchronization

- **Performance & Monitoring**
  - Integrated **Sentry Profiler** for performance tracking
  - Lazy loading with `Suspense`

---

## 🧠 Technical Highlights

- Complex state coordination for multimedia playback
- Manual GSAP ticker synchronization with HTML5 video
- Multi-view 3D scene management using `@react-three/drei/View`
- Physically-based lighting and environment reflections
- Clean separation of concerns between UI, animation, and 3D logic

---

## 🛠 Tech Stack

### Frontend
- **React**
- **Vite**
- **Tailwind CSS**

### Animation
- **GSAP**
- **GSAP ScrollTrigger**
- **@gsap/react**

### 3D & Graphics
- **Three.js**
- **@react-three/fiber**
- **@react-three/drei**

### Performance & Monitoring
- **Sentry (Profiler & Error Tracking)**

---

## 📁 Project Structure
```
src/
├── components/
│   ├── Hero.jsx
│   ├── Highlights.jsx
│   ├── VideoCarousel.jsx
│   ├── Model.jsx
│   ├── ModelView.jsx
│   ├── IPhone.jsx
│   ├── Lights.jsx
│   ├── Loader.jsx
│   └── Navbar.jsx
├── constants/
│   └── index.js
└── utils/
    ├── animations.js
    └── index.js
```

---

## 🚀 Getting Started

### Installation
```bash
git clone https://github.com/SALVADORPOETA/Apple-web-sm.git
cd Apple-web-sm
npm install
```

### Run the project
```bash
npm run dev
```

Open your browser at:
```
http://localhost:5173
```

---

## 🎥 3D Model Attribution

**Model:** Apple iPhone 15 Pro Max Black  
**Author:** Polyman  
**Source:** Sketchfab  
**License:** CC BY 4.0  
[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

---

## 📌 Design & UX Goals

- Replicate Apple's product-launch visual language
- Prioritize smooth motion and cinematic transitions
- Emphasize interaction over static presentation
- Maintain high performance despite heavy animation and 3D rendering

---

## 📈 Performance Considerations

- Lazy-loaded 3D assets with `Suspense`
- Optimized GSAP timelines
- Controlled re-renders using `useRef`
- Sentry profiling for runtime analysis

---

## 👨🏽‍💻 Developer

**Salvador Martínez**  
Full-Stack Developer | Frontend & 3D Web Enthusiast

- GitHub: [https://github.com/SALVADORPOETA](https://github.com/SALVADORPOETA)
- LinkedIn: [https://www.linkedin.com/in/salvador-martinez-sm/](https://www.linkedin.com/in/salvador-martinez-sm/)

---

## 📄 License

This project is for **educational and portfolio purposes only**.  
Apple and iPhone are trademarks of Apple Inc.  
This project is not affiliated with or endorsed by Apple.

---

## ⭐ If you like this project

Consider starring the repository and connecting with me on LinkedIn.  
Feedback and collaboration opportunities are always welcome.
