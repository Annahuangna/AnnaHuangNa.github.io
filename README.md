# Personal Portfolio ⚡️ 

> [(https://annahuangna.github.io/)]

![GitHub stars](https://img.shields.io/github/stars/Annahuangna/AnnaHuangNa.github.io) 
![GitHub forks](https://img.shields.io/github/forks/Annahuangna/AnnaHuangNa.github.io)
[![Maintenance](https://img.shields.io/badge/maintained-yes-green.svg)](https://github.com/AnnaHuangNa/AnnaHuangNa.github.io/commits/master)
[![Website shields.io](https://img.shields.io/badge/website-up-yellow)](http://AnnaHuangNa.github.io/)
[![Ask Me Anything !](https://img.shields.io/badge/ask%20me-linkedin-1abc9c.svg)](https://www.linkedin.com/in/na“anna”-huang-7821b632b)
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

### Website Preview
<p align="center"> 
  <kbd>
    <a href="https://annahuangna.github.io/" target="_blank"><img src="examples/Anna preview.gif">
  </a>
  </kbd>
</p>

:star: Star me on GitHub — it helps!

# PROJECT TITLE: Anna's Personal Website
#### Video Demo:  <https://youtu.be/1skxdLdnwn8?si=-71rRA-YdnxIsjU9>
#### Description: Anna's Personal Website is a comprehensive digital portfolio that showcases my professional journey as an educator and technology integrator. Built as a responsive single-page application, this website serves as a dynamic platform to present my teaching philosophy, educational projects, technical skills, and professional background. The site combines aesthetic design with functional excellence, demonstrating my commitment to bridging digital innovation with educational practices.
## File Structure and Technical Implementation
### Tools Used 🛠️
* [<b>GitHub Pages</b>](https://create-react-app.dev/docs/deployment/#github-pages) - To host my static website (HTML, CSS, JS).
* [<b>Materialize</b>](https://materializecss.com/) - A CSS framework to get Google's Material Design components.
* [<b>Typed.js</b>](https://mattboldt.com/demos/typed-js/) - JavaScript Library

### Core HTML Structure (index.html)

The main HTML file implements a sophisticated single-page architecture with clearly defined sections:

#### Head Section & Meta Configuration:
- Comprehensive meta tags for SEO optimization, including Open Graph protocols for social media sharing.
- Google Analytics integration for visitor tracking and performance monitoring.
- Materialize CSS framework via CDN for consistent Material Design components.
- Custom favicon set for multiple devices and browsers.
- Viewport configuration for responsive behavior across all screen sizes.

#### Navigation System:
The site features a three-tier navigation approach:
- **Desktop Navigation**: Fixed side navigation panel with profile image and section links.
- **Mobile Navigation**: Collapsible hamburger menu for smaller screens.
- **Active State Management**: Visual indicators for the current section with smooth scrolling.

#### Section Architecture:
- **Hero Section**: Features Typed.js animation for dynamic text effects and social media links.
- **About Section**: Personal introduction with teaching philosophy.
- **Experience Section**: Professional timeline with detailed role descriptions.
- **Projects Section**: Interactive card-based project showcase with hover effects.
- **Skills Section**: Categorized technical and educational tool proficiency.
- **Education Section**: Academic background with relevant coursework.
- **Contact Section**: Multiple contact methods with integrated action buttons.

### Custom Styling (style.css)
The custom CSS extends and customizes the Materialize framework with several key design decisions:

#### Profile Image Styling:
I chose a teal-tinged border to complement the overall color scheme while creating visual separation from the navigation background. The negative margin ensures proper alignment within the fixed navigation panel.#### Color Scheme Strategy. After testing multiple palettes, I selected:
Primary: #008073 (teal) for brand consistency

Secondary: #004d40 (dark teal) for links and accents

Background: #F0F4F8 (light blue-gray) for reduced eye strain

Text: #333333 for optimal readability

This palette conveys professionalism while maintaining visual interest, with sufficient contrast for accessibility.
### Interactive Elements
Social media buttons with hover transformations and brand-specific colors

Project cards with reveal functionality for additional details

Smooth transitions and hover effects throughout the interface

Responsive grid system that adapts from mobile to desktop layouts

### Typography Hierarchy
Primary fonts: System font stack for optimal performance

Font weights: Ranging from 200 (light) for headings to 400/600 for body text

### JavaScript Functionality
#### Typed.js Integration:The typing animation immediately engages visitors while efficiently communicating my professional identities. I tested several animation libraries but chose Typed.js for its natural typing rhythm and lightweight implementation.
### Project Showcase Design
#### The project cards implement a reveal pattern that balances information density with clean design:
- **Progressive Disclosure: Essential information on the front, detailed specifications on reveal
- **Visual Consistency: Uniform card dimensions with appropriate image aspect ratios
- **Action-Oriented: Clear call-to-action buttons for project exploration
- **Tool Integration: Demonstration videos, live links, and documentation access
### Performance Optimization: 
#### Recognizing the importance of loading speed, particularly for educational contexts with varying internet quality, I implemented several optimizations:
- **CDN Hosting: Materialize and Font Awesome loaded via CDN for faster delivery
- **Image Optimization: Appropriate sizing and compression for all project images
- **Minimal Dependencies: Limited external libraries to essential functionality
- **Efficient Selectors: CSS structured for optimal rendering performance
