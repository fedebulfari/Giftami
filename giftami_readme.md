# 🎁 Giftami

[![Netlify Status](https://api.netlify.com/api/v1/badges/d956a7ed-b432-44c8-968c-7c587e5efb4d/deploy-status)](https://app.netlify.com/projects/giftami/deploys)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript|110](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

**Giftami** is a lightweight, fast, and interactive web application designed to make gift planning, curation, and sharing effortless. Built with a zero-dependency, single-file architecture, it delivers a seamless user experience straight from the browser.

🌐 **Live Demo:** [https://giftami.netlify.app](https://giftami.netlify.app)

---

## 1. ✨ Features

- **⚡ Zero-Build Single-File Architecture:** Entirely self-contained within `index.html`—no complex build pipelines, bundlers, or external dependencies required.
- **🎨 Modern & Responsive UI:** Crafted for a smooth user experience across desktop, tablet, and mobile devices.
- **🚀 Instant Load Times:** Optimized static delivery hosted on Netlify's global CDN.
- **🔒 Privacy-First & Client-Side:** Runs directly in the user's browser for instant interactions.

---

## 2. 📁 Project Structure

```text
Giftami/
├── index.html      # Main application file (contains structure, styles, and logic)
├── netlify.toml    # Netlify deployment and routing configuration
└── README.md       # Project documentation
```

---

## 3. 🚀 Getting Started

Because **Giftami** is built without external build tools, running it locally takes seconds.

### 3.1. Prerequisites

All you need is a modern web browser (Chrome, Firefox, Safari, or Edge).

### 3.2. Local Development

1. **Clone or download the repository:**
   ```bash
   git clone https://github.com/your-username/Giftami.git
   cd Giftami
   ```

2. **Launch the application:**
   - Simply double-click `index.html` to open it in your browser, **OR**
   - Serve it locally using a lightweight development server:
     ```bash
     # Using Python
     python3 -m http.server 8000

     # Using Node.js (npx)
     npx serve .
     ```
   - Open `http://localhost:8000` in your browser.

---

## 4. 🌐 Deployment

This project is pre-configured for one-click deployment on **Netlify** via the included `netlify.toml` file.

To deploy your own instance:
1. Push this repository to GitHub, GitLab, or Bitbucket.
2. Import the project into [Netlify](https://app.netlify.com/).
3. Netlify will automatically detect the `netlify.toml` settings and publish the root directory.

---

## 5. 🛠️ Customizing

Since all code resides in `index.html`:
- **Styles:** Locate the `<style>` block or Tailwind configuration in the `<head>` to adjust colors, typography, and layout.
- **Logic:** Locate the `<script>` tag at the bottom of the file to customize application features, state management, or data.

---

## 6. 📄 License

This project is open-source and available under the [MIT License](LICENSE).