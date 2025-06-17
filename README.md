# Design Better Landing Page

A minimalist landing page built with Vite and Tailwind CSS.

## 🚀 Features

- Modern and clean design
- Fully responsive layout
- Custom CSS components and variables
- Built with Vite for fast development
- Tailwind CSS for utility-first styling

## 🛠️ Technologies

- Vite v6.3.5
- Tailwind CSS v4.1.8
- CSS Custom Properties for theming
- HTML5 & Modern CSS

## 🏗️ Project Structure

```
VITE_TAILWIND/
├── src/
│   ├── components.css    # Custom component styles
│   ├── variables.css     # CSS custom properties
│   ├── style.css        # Main stylesheet
│   └── main.js          # JavaScript entry point
├── public/
│   ├── logo.png         # Site logo
│   └── Apple_Logo_0.svg # Download button icon
├── index.html           # Main HTML file
├── vite.config.js       # Vite configuration
└── package.json         # Project dependencies
```

## 🚦 Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development server:
   ```bash
   npm run dev
   ```
4. Build for production:
   ```bash
   npm run build
   ```

## 🎨 Customization

The project uses CSS custom properties for theming. You can modify colors in `src/variables.css`:

```css
:root {
  --primary: #000000;
  --primary-light: #1f1f1f;
  --secondary: #ffffff;
  --secondary-light: #f5f5f5;
  /* ...other variables */
}
```

## 📝 License

© 2023 EAFC Fleron - All rights reserved
