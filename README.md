# Portfolio Website

A modern, responsive portfolio website built with Vue.js 3, TypeScript, and Vite. This website showcases my experience, projects, and skills as a full-stack developer.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Fast Performance**: Built with Vite for optimal loading speeds
- **Type Safety**: Written in TypeScript for better code quality
- **SEO Optimized**: Structured for good search engine visibility
- **Easy to Customize**: Well-organized code structure for easy modifications

## 🛠️ Technologies Used

- **Frontend**: Vue.js 3 + Composition API
- **Language**: TypeScript
- **Build Tool**: Vite
- **Styling**: CSS3 with CSS Variables
- **Routing**: Vue Router
- **State Management**: Pinia
- **Testing**: Vitest + Cypress
- **Deployment**: Vercel + GitHub Pages

## 📁 Project Structure

```
src/
├── components/          # Reusable Vue components
├── views/              # Page components
│   ├── HomeView.vue    # Landing page
│   ├── AboutView.vue   # About me page
│   ├── ExperienceView.vue # Professional experience
│   ├── ProjectsView.vue   # Projects showcase
│   └── ContactView.vue    # Contact information
├── router/             # Vue Router configuration
├── stores/             # Pinia stores
├── assets/             # Static assets
└── main.ts            # Application entry point
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v20 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/lonelyneutrin0/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🧪 Testing

```bash
# Run unit tests
npm run test:unit

# Run e2e tests
npm run test:e2e

# Run e2e tests in development mode
npm run test:e2e:dev
```

## 🏗️ Building for Production

```bash
# Build the project
npm run build

# Preview the build
npm run preview
```

## 🚀 Deployment

### Deploy to Vercel

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy to Vercel**
   ```bash
   npm run deploy:vercel
   ```

### Deploy to GitHub Pages

1. **Using GitHub Actions (Automatic)**
   - Push to the `main` branch
   - GitHub Actions will automatically build and deploy

2. **Manual Deployment**
   ```bash
   npm run deploy
   ```

## 🎨 Customization

### Personal Information

1. **Update personal details** in the following files:
   - `src/views/HomeView.vue` - Hero section
   - `src/views/AboutView.vue` - About information
   - `src/views/ContactView.vue` - Contact details

2. **Add your projects** in `src/views/ProjectsView.vue`

3. **Update experience** in `src/views/ExperienceView.vue`

### Styling

- **Colors**: Modify CSS variables in `src/assets/base.css`
- **Layout**: Update component styles as needed
- **Images**: Replace placeholder images with your own

### Configuration

- **Base URL**: Update `vite.config.ts` for your repository name
- **Site Title**: Update `index.html` and add meta tags

## 📝 Environment Variables

Create a `.env` file for environment-specific configuration:

```env
VITE_SITE_URL=https://yourusername.github.io/portfolio
VITE_CONTACT_EMAIL=your.email@example.com
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

Feel free to reach out if you have any questions or suggestions!

- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn](https://linkedin.com/in/yourusername)
- **GitHub**: [Your GitHub](https://github.com/yourusername)

---

⭐ Star this repository if you found it helpful!
