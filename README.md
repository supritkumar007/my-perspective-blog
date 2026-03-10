# My Perspective - Personal Blog Website

A modern, responsive blogging platform designed to share insights on technology, design, and software engineering.

![My Perspective Blog]

## Project Demo Video

Watch a walkthrough of the blog website:

https://github.com/user-attachments/assets/my-perspective-blog.mp4
## Features

- **Responsive Grid Layout**: 3-column grid for blog posts that adapts seamlessly to mobile devices
- **Interactive Hover Effects**: Blog cards with "lift-up" animation and depth-enhancing shadows
- **Dynamic Hero Section**: Visually striking hero area with gradient overlay
- **Smooth Animations**: Content fades in on page load for polished UX
- **Mobile-First Navigation**: Collapsible navbar optimized for all screen sizes
- **Modern Typography**: Google Fonts 'Outfit' integration
- **Bootstrap 5.3**: Rapid prototyping with pre-built components

## Technologies Used

- **HTML5** - Semantic content structuring
- **CSS3** - Custom styling, Flexbox & Grid layouts, animations
- **Bootstrap 5.3.2** - Responsive grid system and UI components
- **Google Fonts** - Modern typography with 'Outfit' font family

## Project Structure

```
assignment1/
├── index.html          # Main HTML file
├── style.css           # Custom styles and animations
├── project_report.md   # Detailed project documentation
└── README.md           # This file
```

## Key Design Elements

### Blog Cards
- Uniform height using Bootstrap's `h-100` class
- Smooth hover transitions with cubic-bezier timing
- Subtle image zoom effect on hover
- Stretched links for better UX

### Hero Section
- Gradient overlay for text readability
- Fade-in animations on page load
- Call-to-action button with rounded pill styling

### Color Scheme
- Primary: Bootstrap Blue
- Success: Green for Web Development badges
- Info: Light blue for Software Engineering
- Warning: Yellow for MERN Stack content
- Danger: Red for Testing fundamentals

## Responsive Breakpoints

- **Desktop**: 3 columns (≥992px)
- **Tablet**: 2 columns (≥768px)
- **Mobile**: 1 column (<768px)

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for CDN resources: Bootstrap & Google Fonts)

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd assignment1
```

2. Open `index.html` in your browser:
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

3. Or use a local development server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve
```

## Learning Outcomes

- Mobile-first responsive design principles
- Component-based architecture thinking
- CSS animation and transition techniques
- Bootstrap framework utilization
- Flexbox and Grid layout mastery
- Micro-interactions and UX enhancements

## Future Enhancements

- Dynamic content loading from JSON/API
- Backend integration for blog management
- Comment system implementation
- Dark mode toggle
- Search functionality
- Category filtering

##  License

This project is created for educational purposes.

