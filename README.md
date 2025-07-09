# Maria Ivanova - Developer Portfolio

A modern, responsive portfolio website built with React, Vite, and Tailwind CSS. Features smooth animations, dark mode support, and a clean, minimalistic design.

## 🚀 Features

- **Modern Design**: Clean and minimalistic UI with smooth animations
- **Dark Mode**: Toggle between light and dark themes
- **Responsive**: Fully responsive design that works on all devices
- **Smooth Animations**: Powered by Framer Motion for engaging interactions
- **Fast Performance**: Built with Vite for optimal development and build performance
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 🛠️ Tech Stack

- **Frontend**: React 19, Vite
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Font**: Inter (Google Fonts)

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd portfolio1
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🏗️ Build for Production

```bash
npm run build
```

## 🚀 Deploy to GitHub Pages

This project is configured to automatically deploy to GitHub Pages using GitHub Actions.

### Automatic Deployment

1. Push your code to the `main` or `master` branch
2. The GitHub Actions workflow will automatically:
   - Build the project
   - Deploy to GitHub Pages
   - Make it available at `https://yourusername.github.io/portfolio1/`

### Manual Setup (if needed)

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the sidebar
3. Under "Source", select "GitHub Actions"
4. The workflow will automatically deploy on every push to main/master

### Important Notes

- The site will be available at `https://yourusername.github.io/portfolio1/`
- Make sure your repository is public (or you have GitHub Pro for private repos)
- The first deployment may take a few minutes to complete

## 📁 Project Structure

```
src/
├── components/
│   ├── Header.jsx      # Navigation and dark mode toggle
│   ├── Hero.jsx        # Hero section with introduction
│   ├── About.jsx       # About section with personal info
│   ├── Skills.jsx      # Skills and technologies
│   ├── Projects.jsx    # Featured projects showcase
│   └── Contact.jsx     # Contact form and information
├── App.jsx             # Main application component
├── main.jsx           # Application entry point
└── index.css          # Global styles and Tailwind imports
```

## 🎨 Customization

### Personal Information
Update the following files to customize your portfolio:

- **Hero.jsx**: Change the name, title, and description
- **About.jsx**: Update personal information and bio
- **Skills.jsx**: Modify skills and proficiency levels
- **Projects.jsx**: Add your own projects with descriptions and links
- **Contact.jsx**: Update contact information and social links

### Styling
- Modify `tailwind.config.js` for theme customization
- Update `src/index.css` for custom styles
- Change colors and gradients in component files

## 📱 Sections

1. **Header**: Navigation menu with smooth scrolling and dark mode toggle
2. **Hero**: Introduction with call-to-action buttons and social links
3. **About**: Personal information and background story
4. **Skills**: Technical skills with animated progress bars
5. **Projects**: Showcase of featured projects with descriptions
6. **Contact**: Contact form and contact information

## 🌟 Key Features

- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Intersection Observer**: Animations trigger when sections come into view
- **Hover Effects**: Interactive elements with smooth hover animations
- **Mobile Responsive**: Optimized for all screen sizes
- **Accessibility**: Proper ARIA labels and keyboard navigation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

Built with ❤️ using React and Vite
