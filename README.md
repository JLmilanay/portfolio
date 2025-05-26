# John Lloyd Cuya Milanay - Portfolio Website

A modern, responsive portfolio website showcasing the skills, experience, and projects of John Lloyd Cuya Milanay, an aspiring IT professional and web developer.

## Features

- Responsive design using Bootstrap 5
- Modern UI with smooth animations
- Dark/Light mode toggle
- Interactive skill bars
- Project showcase with hover effects
- Contact form
- Smooth scrolling navigation
- Typing animation effect
- Timeline layout for experience and education
- Social media integration

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Font Awesome Icons
- AOS (Animate On Scroll) Library

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Custom styles
├── js/
│   └── main.js        # JavaScript functionality
├── images/            # Project images and assets
└── assets/           # Additional assets (resume, etc.)
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio
   ```

3. Open `index.html` in your web browser to view the website.

## Customization

### Adding Projects
To add new projects, add a new card in the projects section of `index.html`:

```html
<div class="col-md-4 mb-4" data-aos="fade-up">
    <div class="card project-card">
        <img src="images/your-project.jpg" class="card-img-top" alt="Project Name">
        <div class="card-body">
            <h5 class="card-title">Project Name</h5>
            <p class="card-text">Project description.</p>
            <a href="#" class="btn btn-primary">View Project</a>
        </div>
    </div>
</div>
```

### Modifying Skills
Update the skills section in `index.html` to reflect your current skills and proficiency levels.

### Changing Colors
The color scheme can be modified by updating the CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #007bff;
    --secondary-color: #6c757d;
    --dark-color: #343a40;
    --light-color: #f8f9fa;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

John Lloyd Cuya Milanay
- Email: johnlloydmilanay7@gmail.com
- Phone: 09491229548 