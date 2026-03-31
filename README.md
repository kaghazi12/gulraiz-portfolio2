# Gulraiz Portfolio

A beautiful, modern portfolio website built with React, Vite, and Tailwind CSS. Showcase your projects, skills, and get in touch with potential clients and employers.

## ✨ Features

- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Hero Section** - Stunning landing section to make a great first impression
- **About Section** - Share your background and expertise
- **Skills Section** - Highlight your technical and professional skills
- **Projects Section** - Display your best work with project showcases
- **Contact Section** - Easy way for visitors to reach out
- **Theme Toggle** - Light and dark mode support
- **Toast Notifications** - User-friendly notifications for interactions
- **Smooth Animations** - Star background and elegant transitions
- **Fast & Light** - Built with Vite for optimal performance

## 🚀 Tech Stack

- **Frontend Framework**: React 18.3
- **Build Tool**: Vite 5.3
- **Styling**: Tailwind CSS 4.1
- **UI Components**: Radix UI
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **Utilities**: clsx, tailwind-merge, class-variance-authority

## 📋 Prerequisites

- Node.js 18+ and npm (or yarn/pnpm)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd gulraiz-portfolio
```

2. Install dependencies:
```bash
npm install
```

## 💻 Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## 🏗️ Build

Build for production:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

## 📁 Project Structure

```
src/
├── components/          # Reusable React components
│   ├── AboutSection.jsx
│   ├── ContactSection.jsx
│   ├── Footer.jsx
│   ├── HeroSection.jsx
│   ├── Navbar.jsx
│   ├── ProjectsSection.jsx
│   ├── SkillsSection.jsx
│   ├── StarBackground.jsx
│   ├── ThemeToggle.jsx
│   └── ui/             # UI component library
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
├── pages/              # Page components
│   ├── Home.jsx
│   └── NotFound.jsx
├── assets/             # Images and static assets
├── App.jsx             # Main App component
├── main.jsx            # React entry point
└── index.css           # Global styles
```

## ⚙️ Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint to check code quality

## 🎨 Customization

### Adding Your Information
Update the content in the component files to reflect your:
- Personal information in `HeroSection.jsx`
- About details in `AboutSection.jsx`
- Skills in `SkillsSection.jsx`
- Projects in `ProjectsSection.jsx`
- Contact information in `ContactSection.jsx`

### Styling
The project uses Tailwind CSS for styling. Modify the configuration in `tailwind.config.js` to customize colors, fonts, and other design tokens.

## 📱 Responsive Design

The portfolio is fully responsive and tested on:
- Mobile devices (320px and up)
- Tablets (768px and up)
- Desktop screens (1024px and up)

## 🌙 Theme Support

Toggle between light and dark themes using the ThemeToggle component. Theme preferences are managed through React context.

## 🚀 Deployment

The portfolio can be deployed to any static hosting service:

### Netlify
```bash
npm run build
# Drag and drop the 'dist' folder to Netlify
```

### Vercel
```bash
vercel
```

### GitHub Pages
```bash
npm run build
# Push the 'dist' folder to your gh-pages branch
```

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. Pull requests are welcome!

## 📧 Contact

For questions or suggestions, feel free to reach out through the contact section on the website.

---

**Built with ❤️ using React and Vite**
