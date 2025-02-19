# ✨ Makeover UI – Open Source React Animations & Stylish Components

**Makeover UI** is an **open-source** React component library focused on **animations, dynamic text effects**, and **modern UI elements**. Designed for developers who want to create visually stunning and interactive web experiences without reinventing the wheel.

---

## 🌟 Features

- 🎬 **Prebuilt Animations** – Effortless motion components to enhance UI/UX.
- 📝 **Text Effects** – Stunning text animations like wave, typewriter, and glitch.
- 🎨 **Stylish Components** – Cards, buttons, badges, and more with a modern design touch.
- 🌍 **Responsive & Accessible** – Built to work on all devices, following WCAG standards.
- ⚡ **Lightweight & Fast** – Optimized performance with minimal overhead.
- 💡 **Customizable** – Easily adaptable to your project’s branding.
- 👐 **Open Source** – Community-driven and MIT licensed.

---

## 📦 Installation

```bash
npm install makeover-ui
# or
yarn add makeover-ui
```

---

## 🚀 Quick Start

```jsx
import React from 'react';
import { AnimatedText, FadeIn, Card, BouncingButton } from 'makeover-ui';

const App = () => (
  <div>
    <AnimatedText text="Makeover UI is Live!" effect="wave" />

    <FadeIn delay={300}>
      <Card title="Stylish Card">
        <p>Build modern interfaces with Makeover UI.</p>
      </Card>
    </FadeIn>

    <BouncingButton onClick={() => alert('Button Clicked!')}>
      Click Me
    </BouncingButton>
  </div>
);

export default App;
```

---

## 🧩 Components

### 🎬 **Animation Components**
- `FadeIn` – Smooth fade-in animation.
- `SlideIn` – Slide elements from any direction.
- `ZoomIn` – Zoom effects for impactful content.
- `HoverEffect` – Animated hover states for interactivity.
- `Pulse` – Continuous pulsing effect for emphasis.

### 📝 **Text Effects**
- `AnimatedText` – Effects: **wave, typewriter, glitch, bounce**.
- `TextLoop` – Rotating text effect for headlines.
- `GradientText` – Dynamic gradient-filled text animation.

### 💡 **UI Components**
- `Card` – Customizable card component with shadows and animations.
- `BouncingButton` – Clickable button with bounce animation.
- `GlassCard` – Frosted glassmorphism effect.
- `ImageHover` – Zoom-in and hover effects for images.
- `Badge` – Labels with animation and hover styles.

---

## 🎨 Customization & Theming

You can easily customize colors, sizes, and effects using props or wrap your app with the **ThemeProvider**.

```jsx
import { ThemeProvider } from 'makeover-ui';

const theme = {
  primaryColor: '#4ECDC4',
  secondaryColor: '#FF6B6B',
  borderRadius: '12px',
};

<ThemeProvider theme={theme}>
  <App />
</ThemeProvider>;
```

Or customize individual components:

```jsx
<AnimatedText
  text="Hello World"
  effect="glitch"
  color="#E63946"
  fontSize="2rem"
/>
```

---

## 🧪 Testing

```bash
npm test
```

The library uses **Jest** and **React Testing Library** for unit and integration tests.

---

## 🤝 Contributing

We ❤️ contributions! Help us make **Makeover UI** even better.

### 📋 How to Contribute

1. **Fork** the repo.
2. Create your feature branch:  
   `git checkout -b feature/awesome-feature`
3. **Commit** your changes:  
   `git commit -m "Add new awesome feature"`
4. **Push** to the branch:  
   `git push origin feature/awesome-feature`
5. **Open a Pull Request** 🚀

### 💡 Ideas for Contribution

- New animation components
- More text effects
- Performance improvements
- Bug fixes
- Documentation updates

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) — feel free to use it in your commercial and non-commercial projects.

---

## 🌐 Community

- 💬 **Questions & Discussions?** – [GitHub Discussions](#)
- 🐛 **Report Bugs** – [GitHub Issues](#)
- ⭐ **Star the Repo** if you find it helpful!

---

## 📧 Contact

💌 **Support & Questions**: support@businessmakeover.co.uk

