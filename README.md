<div align="center">
  
# 🚀 Parijat Dutta - Portfolio Website

### Modern Full Stack Developer Portfolio

[![React](https://img.shields.io/badge/React-18.3.1-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.11-38B2AC.svg)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-6.2.2-646CFF.svg)](https://vitejs.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

_A sleek, responsive portfolio showcasing Full Stack development expertise and AI/ML passion_

[View Live Demo](#) • [Report Bug](../../issues) • [Request Feature](../../issues)

</div>

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Quick Start](#-quick-start)
- [📁 Project Structure](#-project-structure)
- [🎨 Customization](#-customization)
- [🚀 Deployment](#-deployment)
- [🧪 Development](#-development)
- [📱 Browser Support](#-browser-support)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👤 Contact](#-contact)

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 **Design & UX**

- ✅ **Modern Design** - Clean, professional layout
- ✅ **Fully Responsive** - Mobile, tablet, desktop optimized
- ✅ **Dark Mode** - Complete theme switching support
- ✅ **Smooth Animations** - Fade-in effects & hover interactions
- ✅ **Custom Branding** - Blue-purple gradient design system

</td>
<td width="50%">

### ⚡ **Performance**

- ✅ **Lightning Fast** - Optimized Vite build
- ✅ **SEO Ready** - Meta tags & semantic HTML
- ✅ **Accessible** - WCAG compliant components
- ✅ **Type Safe** - Full TypeScript implementation
- ✅ **Modern Stack** - Latest React patterns

</td>
</tr>
</table>

### 📖 **Portfolio Sections**

| Section               | Description                                 | Status                   |
| --------------------- | ------------------------------------------- | ------------------------ |
| 🏠 **Hero**           | Name, title, contact with animated gradient | ✅ Complete              |
| 👨‍💻 **About**          | Professional summary and passion statement  | ✅ Complete              |
| 💼 **Experience**     | Work history with live project links        | ✅ Complete              |
| 🛠️ **Projects**       | Portfolio showcase with tech stacks         | ✅ Complete              |
| ⚡ **Skills**         | Categorized technical expertise             | ✅ Complete              |
| 🎓 **Education**      | Academic background and achievements        | ✅ Complete              |
| 🏆 **Certifications** | Professional certificates with verification | ✅ Complete              |
| 📊 **GitHub Stats**   | Contribution graphs and statistics          | 🔄 Ready for integration |

---

## 🛠️ Tech Stack

<div align="center">

### Frontend

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

### UI Components

![Radix UI](https://img.shields.io/badge/radix%20ui-161618.svg?style=for-the-badge&logo=radix-ui&logoColor=white)
![Lucide](https://img.shields.io/badge/Lucide-F56565?style=for-the-badge&logo=lucide&logoColor=white)

### Development Tools

![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)

</div>

---

## 🚀 Quick Start

### Prerequisites

Make sure you have the following installed:

- **Node.js** (v16 or higher) - [Download](https://nodejs.org/)
- **npm** / **yarn** / **pnpm** - Package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/portfolio-website.git
   cd portfolio-website
   ```

2. **Install dependencies**

   ```bash
   # Using npm
   npm install

   # Using yarn
   yarn install

   # Using pnpm
   pnpm install
   ```

3. **Start development server**

   ```bash
   # Using npm
   npm run dev

   # Using yarn
   yarn dev

   # Using pnpm
   pnpm dev
   ```

4. **Open in browser**
   ```
   🌐 Local:   http://localhost:5173
   🌐 Network: http://[your-ip]:5173
   ```

---

## 📁 Project Structure

```
📦 portfolio-website
├── 📂 public/
│   ├── 🖼️ placeholder.svg
│   └── 🤖 robots.txt
├── 📂 src/
│   ├── 📂 components/ui/        # 🎨 Reusable UI components
│   │   ├── 🏷️ badge.tsx
│   │   ├── 🔘 button.tsx
│   │   ├── 🃏 card.tsx
│   │   └── ... (40+ components)
│   ├── 📂 hooks/               # 🪝 Custom React hooks
│   ├── 📂 lib/                 # 🛠️ Utility functions
│   │   └── ⚙️ utils.ts
│   ├── 📂 pages/               # 📄 Page components
│   │   ├── 🏠 Index.tsx        # Portfolio homepage
│   │   └── ❌ NotFound.tsx
│   ├── 📱 App.tsx              # Main app component
│   ├── 🎨 index.css            # Global styles
│   └── 🚀 main.tsx             # App entry point
├── ⚙️ tailwind.config.ts       # Tailwind configuration
├── 📦 package.json
└── 📖 README.md
```

---

## 🎨 Customization

### 👤 Personal Information

Edit `src/pages/Index.tsx` to customize:

```typescript
// 📧 Contact Information
const contactInfo = {
  email: "your-email@gmail.com",
  phone: "+91 XXXXXXXXXX",
  location: "Your City, Country",
};

// 💼 Professional Experience
const experience = [
  {
    role: "Your Role",
    project: "Project Name",
    url: "https://your-project.com",
    timeline: "Start – End Date",
    tech: "Tech Stack",
    description: "What you accomplished",
  },
];
```

### 🎨 Design System

Customize colors in `src/index.css`:

```css
:root {
  /* 🎨 Brand Colors */
  --brand-500: 231 75% 65%; /* Primary brand color */
  --brand-600: 226 71% 40%; /* Darker variant */

  /* 🌈 Tech Stack Colors */
  --tech-react: 195 100% 42%;
  --tech-typescript: 211 60% 45%;
}
```

### 🧩 Components

All UI components are located in `src/components/ui/` and are:

- 🔒 **Type-safe** with TypeScript
- ♿ **Accessible** with Radix UI primitives
- 🎨 **Customizable** with Tailwind classes
- 📏 **Consistent** with the design system

---

## 🚀 Deployment

### 🏗️ Build for Production

```bash
npm run build
```

### 🌐 Deploy to Popular Platforms

<details>
<summary><strong>🟢 Netlify</strong></summary>

1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Deploy automatically on push

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/your-username/portfolio-website)

</details>

<details>
<summary><strong>▲ Vercel</strong></summary>

1. Connect your GitHub repository to Vercel
2. Framework preset: **Vite**
3. Deploy automatically on push

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/your-username/portfolio-website)

</details>

<details>
<summary><strong>📄 GitHub Pages</strong></summary>

1. Enable GitHub Pages in repository settings
2. Set source to **GitHub Actions**
3. The built files will be deployed automatically

</details>

---

## 🧪 Development

### 📋 Available Scripts

| Command              | Description                  |
| -------------------- | ---------------------------- |
| `npm run dev`        | 🚀 Start development server  |
| `npm run build`      | 🏗️ Build for production      |
| `npm run test`       | 🧪 Run test suite            |
| `npm run typecheck`  | 🔍 TypeScript validation     |
| `npm run format.fix` | ✨ Format code with Prettier |

### 🧪 Testing

```bash
# Run all tests
npm test

# Run tests in watch mode
npm test -- --watch
```

### 🔍 Type Checking

```bash
npm run typecheck
```

---

## 📱 Browser Support

| Browser    | Supported Versions |
| ---------- | ------------------ |
| 🌐 Chrome  | Latest ✅          |
| 🦊 Firefox | Latest ✅          |
| 🧭 Safari  | Latest ✅          |
| 🔷 Edge    | Latest ✅          |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🌿 **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. 📤 **Push** to the branch (`git push origin feature/amazing-feature`)
5. 🔄 **Open** a Pull Request

### 📝 Development Guidelines

- Follow the existing code style
- Add tests for new features
- Update documentation as needed
- Ensure all checks pass

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License - Feel free to use this project for your own portfolio!
```

---

## 👤 Contact

<div align="center">

### 🚀 **Parijat Dutta**

_Full Stack Developer • AI/ML Enthusiast_

[![Email](https://img.shields.io/badge/Email-parijatdutta100%40gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:parijatdutta100@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-%2B91%206360421661-green?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+916360421661)
[![Location](https://img.shields.io/badge/Location-Kolkata,%20India-blue?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Kolkata,India)

---

### 🌟 **Show your support**

Give a ⭐️ if this project helped you!

_Built with ❤️ using React, TypeScript, and Tailwind CSS_

</div>
