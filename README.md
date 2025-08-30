# Personal Portfolio Website

A responsive personal portfolio website showcasing skills, projects, and contact information with modern design and interactive features.

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design with smooth animations and transitions
- **Interactive Navigation**: Sticky header with smooth scrolling navigation
- **Animated Elements**: Scroll reveal animations and typing effect for dynamic content presentation
- **Contact Form**: Functional contact form with client-side validation
- **Portfolio Gallery**: Interactive project showcase with hover effects
- **Social Media Integration**: Links to various social media profiles

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS variables for theming
- **Animations**: ScrollReveal.js for scroll animations
- **Typography**: Typed.js for animated text effects
- **Icons**: Boxicons icon library
- **Backend**: PHP for form handling

## Project Structure

```
Portfolio-/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
├── images/             # Image assets
├── Documents/          # CV and documents
└── README.md          # Project documentation
```

## Sections

1. **Home**: Introduction with animated text and social media links
2. **About**: Personal information and background
3. **Services**: List of services and skills offered
4. **Portfolio**: Showcase of completed projects
5. **Contact**: Contact form and information

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Portfolio-
   ```

2. Open `index.html` in a web browser or serve through a local server

3. For full functionality (contact form), ensure PHP is configured on your server

## Form Validation

The contact form includes comprehensive client-side validation:
- Email format validation
- Phone number validation (10 digits)
- Message length validation (minimum 30 characters)
- Real-time error messaging

## Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: 767px and below
- Small mobile: 450px and below

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Performance Features

- Optimized images
- Efficient CSS animations
- Minimal JavaScript footprint
- Fast loading times

## Customization

To customize the portfolio for your own use:

1. Update personal information in `index.html`
2. Replace images in the `images/` directory
3. Modify color scheme in CSS variables (`:root` section in `style.css`)
4. Update social media links
5. Add your own projects to the portfolio section

## Contact Form Backend

The contact form is configured to work with PHP. Ensure your server supports PHP and update the form action URL in `index.html` as needed.

## License

This project is open source and available under the MIT License.

## Credits

- **Developer**: Nidhi Yadav
- **Icons**: Boxicons
- **Animations**: ScrollReveal.js, Typed.js