# Sai Teja Portfolio

A modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS.

## 🚀 Live Demo

Visit the live site: [https://yourusername.github.io/sai-teja-portfolio](https://yourusername.github.io/sai-teja-portfolio)

## Features

- 🌙 Dark/Light mode toggle
- 📱 Fully responsive design
- ⚡ Fast and optimized
- 🎨 Modern UI with smooth animations
- 📄 Downloadable resume
- ☁️ Cloud computing themed design
- 🚀 Deployed on GitHub Pages

## Sections

- **Home** - Welcome section with animated cloud computing theme
- **About** - Personal introduction and education details
- **Skills** - Technical skills showcase
- **Projects** - Featured projects with live demos
- **Experience** - Professional internship experience
- **Certifications** - Professional certifications
- **Contact** - Contact form and social links

## Technologies Used

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Lucide React (for icons)

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sai-teja-portfolio.git
cd sai-teja-portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

## Building for Production

```bash
npm run build
```

## Deployment to GitHub Pages

### Automatic Deployment (Recommended)

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

1. **Create a new repository** on GitHub
2. **Push your code** to the repository:
```bash
git remote add origin https://github.com/yourusername/sai-teja-portfolio.git
git branch -M main
git push -u origin main
```

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "GitHub Actions"

4. **Update the repository name** in `vite.config.ts` and `package.json`:
   - Replace `/sai-teja-portfolio/` with your actual repository name
   - Update the homepage URL in `package.json`

5. **Push changes** - GitHub Actions will automatically build and deploy

### Manual Deployment

You can also deploy manually using:

```bash
npm run deploy
```

## Important Notes for GitHub Pages

1. **Repository Name**: Make sure to update the base path in `vite.config.ts` to match your repository name
2. **Homepage URL**: Update the homepage in `package.json` with your actual GitHub Pages URL
3. **Assets**: All assets use relative paths for compatibility

## Project Structure

```
src/
├── components/          # React components
│   ├── About.tsx
│   ├── Certifications.tsx
│   ├── Contact.tsx
│   ├── Footer.tsx
│   ├── Hero.tsx
│   ├── Internships.tsx
│   ├── Navigation.tsx
│   ├── Projects.tsx
│   └── Skills.tsx
├── App.tsx             # Main App component
├── main.tsx           # Entry point
└── index.css          # Global styles

public/
├── Saiteja_resume1.pdf # Resume file
└── .nojekyll          # GitHub Pages configuration
```

## Customization

### Personal Information

Update the following files with your personal information:

- `src/components/Hero.tsx` - Name and introduction
- `src/components/About.tsx` - About section and education
- `src/components/Skills.tsx` - Technical skills
- `src/components/Projects.tsx` - Your projects
- `src/components/Internships.tsx` - Work experience
- `src/components/Certifications.tsx` - Your certifications
- `src/components/Contact.tsx` - Contact information and social links

### Resume

Replace `public/Saiteja_resume1.pdf` with your own resume file.

### Repository Configuration

1. Update `vite.config.ts`:
```typescript
base: process.env.NODE_ENV === 'production' ? '/your-repo-name/' : '/',
```

2. Update `package.json`:
```json
"homepage": "https://yourusername.github.io/your-repo-name"
```

### Styling

The project uses Tailwind CSS for styling. You can customize:

- Colors in `tailwind.config.js`
- Animations in `src/index.css`
- Component styles in individual component files

## Troubleshooting

### Common GitHub Pages Issues

1. **Blank page after deployment**:
   - Check that the base path in `vite.config.ts` matches your repository name
   - Ensure GitHub Pages is enabled in repository settings

2. **Assets not loading**:
   - Verify all asset paths are relative
   - Check the build output in the `dist` folder

3. **404 errors**:
   - Make sure `.nojekyll` file exists in the public folder
   - Check that the homepage URL is correct

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Sai Teja - [chsaitej67@gmail.com](mailto:chsaitej67@gmail.com)

Project Link: [https://github.com/yourusername/sai-teja-portfolio](https://github.com/yourusername/sai-teja-portfolio)