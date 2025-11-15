# Legacy International Child Care

A professional website for Legacy International Child Care, a bilingual childcare facility serving the Lehi, Utah community.

## Project Overview

This is a responsive, modern website showcasing Legacy International Child Care's mission, vision, services, and facilities. The site features:

- **Bilingual Support**: Full English/Spanish language toggle in the top-right corner
- **Hero Section**: Eye-catching intro with facility imagery
- **Services Section**: Highlights 6 key service areas with icons:
  - Bilingual Education
  - Montessori Methodology
  - Small Group Attention
  - Holistic Development
  - Healthy Nutrition
  - BrightWheel App Integration

- **Testimonials**: Parent reviews with avatar images
- **Facilities Gallery**: Showcase of the childcare facility
- **Contact Section**: Contact form, location details, and phone numbers
- **Calendly Integration**: "Schedule a Tour" button links directly to booking

## Features

- **Responsive Design**: Mobile-friendly layout that adapts to all screen sizes
- **Language Toggle**: Smooth switching between English and Spanish
- **Navigation Sidebar**: Easy access to all major sections
- **Modern Styling**: Uses custom CSS with color scheme:
  - Primary Red: #e3211e
  - Secondary Yellow: #f9c911
  - Accent Blue: #51adec
  - Success Green: #299c35

## File Structure

```
childcare/
├── index.html              # Main page with all content
├── assets/
│   ├── css/
│   │   ├── main.css       # Primary stylesheet
│   │   └── noscript.css   # Fallback styles
│   ├── js/
│   │   ├── jquery.min.js
│   │   ├── jquery.scrollex.min.js
│   │   ├── jquery.scrolly.min.js
│   │   ├── browser.min.js
│   │   ├── breakpoints.min.js
│   │   ├── util.js
│   │   └── main.js
│   ├── sass/              # Sass source files
│   └── webfonts/          # Font files
├── images/                # Hero, facility, and avatar images
├── generic.html           # Template for additional pages
├── elements.html          # Style guide/element reference
├── README.md              # This file
└── README.txt             # Original template readme

```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Responsive design with media queries
- **JavaScript**: jQuery for interactions and smooth scrolling
- **Font Awesome**: Icon library for feature icons
- **Responsive Framework**: Custom breakpoints for mobile, tablet, and desktop

## Customization

### Language Strings

All translatable text uses `data-en` and `data-es` attributes:

```html
<h2 data-en="Welcome" data-es="Bienvenido">Welcome</h2>
```

### Colors

Primary colors are defined as CSS variables in the `<style>` tag:

```css
:root {
  --primary: #e3211e;
  --secondary: #f9c911;
  --accent: #51adec;
  --success: #299c35;
}
```

### Contact Information

Update contact details in the "Get in Touch" section:
- Location: Lehi, Utah
- Email: Legacyinternationalut@gmail.com
- Spanish Phone: (801) 885-0343
- English Phone: (801) 885-6188
- Calendly Link: https://calendly.com/legacyinternationalut/30min

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive (iOS Safari, Chrome Mobile)
- IE11 fallback styles included

## License

Based on Hyperspace by HTML5 UP (html5up.net)
CCA 3.0 License - Free for personal and commercial use

## Credits

- **Template**: Hyperspace by HTML5 UP (@ajlkn)
- **Icons**: Font Awesome (fontawesome.io)
- **jQuery Plugins**: 
  - Scrollex (github.com/ajlkn/jquery.scrollex)
  - Responsive Tools (github.com/ajlkn/responsive-tools)
- **Framework**: jQuery (jquery.com)

---

*Last Updated: November 2024*
