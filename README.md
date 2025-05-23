# Modern React Portfolio

A professional portfolio website built with React, Styled Components, Framer Motion, and React Icons.

## Features

- Modern and clean design with engaging animations
- Fully responsive layout for all device sizes
- Interactive UI with smooth transitions and effects
- Detailed project showcases with filtering capabilities
- Advanced skill presentation with categorization and proficiency levels
- Comprehensive about section with tabbed content
- Contact form with validation
- Modular component structure for easy customization

## Technologies Used

- **React:** A JavaScript library for building user interfaces
- **Styled Components:** For component-based styling with CSS-in-JS
- **Framer Motion:** For smooth animations and transitions
- **React Icons:** For high-quality icons
- **React Scroll:** For smooth scrolling navigation

## Project Structure

```
src/
├── components/
│   ├── Navbar.js
│   ├── Hero.js
│   ├── About.js
│   ├── Skills.js
│   ├── Projects.js
│   ├── Contact.js
│   └── Footer.js
├── App.js
├── App.css
├── index.js
└── index.css
```

## Getting Started

### Prerequisites

- Node.js and npm installed on your computer

### Installation

1. Clone this repository:
```
git clone https://github.com/yourusername/react-portfolio.git
```

2. Navigate to the project directory:
```
cd react-portfolio
```

3. Install dependencies:
```
npm install
```

4. Start the development server:
```
npm start
```

5. Open your browser and visit `http://localhost:3000`

## Customization

### Personal Information

Edit the content in each component to reflect your personal information:

- Update your name, title, and description in `Hero.js`
- Modify your bio, education, and experience in `About.js`
- Customize your skills and proficiency levels in `Skills.js`
- Add your own projects with details in `Projects.js`
- Update contact information in `Contact.js`

### Styling

The portfolio uses CSS variables for easy styling customization. Edit the `:root` section in `App.css`:

```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #4b5563;
  --accent-color: #f59e0b;
  --text-color: #1f2937;
  --bg-color: #ffffff;
  --bg-light: #f3f4f6;
  --bg-dark: #111827;
}
```

### Adding Projects

Add your projects to the `projectsData` array in `Projects.js`:

```jsx
const projectsData = [
  {
    id: 1,
    title: 'Project Name',
    category: 'web', // web, app, or design
    image: 'path/to/image.jpg',
    description: 'Project description',
    client: 'Client Name',
    duration: 'Duration',
    technologies: ['Tech1', 'Tech2'],
    features: [
      'Feature 1',
      'Feature 2',
      'Feature 3'
    ],
    liveDemoLink: 'https://example.com',
    githubLink: 'https://github.com/yourusername/project',
  },
  // More projects...
];
```

### Contact Form

The contact form is set up to show success messages but doesn't actually send emails. To make it functional:

1. Create a backend service (using Node.js, Express, etc.) to handle form submissions
2. Modify the `handleSubmit` function in `Contact.js` to send data to your backend
3. Implement email sending functionality in your backend

## Deployment

You can deploy this portfolio to various hosting platforms:

### GitHub Pages

1. Install `gh-pages` package:
```
npm install --save gh-pages
```

2. Add these to your `package.json`:
```json
"homepage": "https://yourusername.github.io/react-portfolio",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

3. Deploy:
```
npm run deploy
```

### Netlify or Vercel

1. Create an account on [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/)
2. Connect your GitHub repository
3. Follow the platform's instructions for deployment

## License

This project is available under the MIT License.

## Acknowledgements

- React team for the amazing library
- Styled Components for the styling solution
- Framer Motion for the animation capabilities #   t e s t - l a n d i n g - p a g e  
 #   t e s t - l a n d i n g - p a g e  
 