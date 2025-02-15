#  Portfolio Website

A clean, responsive portfolio website built with HTML, CSS, and JavaScript. Features a modern design with smooth animations, dark/light mode toggle, and mobile-friendly layout.

## Features

- Responsive design that works on all devices
- Dark/light mode toggle with persistent preference
- Smooth scroll navigation
- CSS animations and transitions
- Project showcase with filterable categories
- Contact form
- SEO optimized
- Accessible design

## Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Styles and animations
├── js/
│   └── main.js        # JavaScript functionality
└── images/            # Project and profile images
```

## Setup

1. Clone or download this repository
2. Replace the placeholder content in `index.html` with your personal information
3. Add your own projects to the projects array in `main.js`
4. Replace placeholder images in the `images` directory with your own
5. Deploy to your preferred hosting service

## Customization

### Colors and Theme
You can customize the colors by modifying the CSS variables in `style.css`:

```css
:root {
    --bg-primary: #ffffff;
    --bg-secondary: #f8f9fa;
    --text-primary: #333333;
    --accent-color: #007bff;
    /* ... other variables ... */
}
```

### Projects
Add or modify projects by editing the projects array in `main.js`:

```javascript
const projects = [
    {
        title: 'Project Name',
        description: 'Project description',
        image: 'path/to/image.jpg',
        tags: ['Tag1', 'Tag2'],
        link: 'project-url'
    },
    // ... more projects ...
];
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use this template for your personal portfolio!
