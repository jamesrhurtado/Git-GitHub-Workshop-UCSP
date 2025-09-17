# 🎨 Theme System Documentation

## Overview
This project now includes an advanced theme system that transforms the user interface with stunning visual themes! Users can easily switch between different themes using the dropdown selector in the top-right corner.

## Available Themes

### 🎨 Default Theme
- Clean, modern design with gray and blue accents
- Professional appearance suitable for all audiences
- Excellent readability and accessibility

### 🕹️ 80s Retro Theme
- Neon colors and synthwave aesthetics
- Animated gradient backgrounds
- Miami Vice inspired color palette
- Scanning line effects on cards
- Press Start 2P and Orbitron fonts

### 💻 Terminal Classic Theme
- Classic VT100 terminal appearance
- Green-on-black color scheme
- Monospace Courier New font
- Blinking cursor animation in header
- Scan line overlay effect
- Command prompt styling

### ✏️ Hand-Sketched Theme
- Hand-drawn, doodle-like appearance
- Rotated cards for playful effect
- Kalam handwritten font
- Paper texture backgrounds
- Colorful accent elements
- Sketch-style borders and shadows

### ⚙️ Steampunk Theme
- Victorian-era meets industrial design
- Brass and copper color palette
- Spinning gear animations
- Georgia serif fonts
- Rich textures and shadows
- Mechanical aesthetic elements

### 🧙 Fantasy Realm Theme
- Mystical and magical design
- Purple and lavender color scheme
- Sparkling particle effects
- Creepster and Georgia fonts
- Glowing text effects
- Enchanted visual elements

## Features

### 🎯 Theme Selector
- **Location**: Fixed position in the top-right corner
- **Accessibility**: Keyboard navigation support (Enter/Space keys)
- **Persistence**: Selected theme is saved in localStorage
- **Visual Feedback**: Smooth transitions and hover effects

### 🔄 Smooth Transitions
- Elegant fade transitions when switching themes
- Theme change notifications with themed styling
- Responsive animations and hover effects
- Reduced motion support for accessibility

### 📱 Responsive Design
- Mobile-friendly theme selector
- Adaptive layouts for different screen sizes
- Touch-friendly controls
- Maintained readability across devices

### ♿ Accessibility Features
- High contrast ratios maintained across all themes
- Keyboard navigation support
- Focus indicators for interactive elements
- Reduced motion preferences respected
- Screen reader friendly structure

## Technical Implementation

### File Structure
```
├── index.njk                 # Main HTML template with theme selector
├── _includes/
│   └── participant.njk       # Participant card template with theme classes
└── assets/css/
    └── themes.css           # Comprehensive theme styles
```

### Theme System Architecture
- **Data Attribute**: Uses `data-theme` on the `<html>` element
- **CSS Selectors**: Theme-specific rules using attribute selectors
- **JavaScript**: Vanilla JS for theme switching and persistence
- **Local Storage**: Remembers user's theme preference

### Custom Properties
Each theme defines specific CSS custom properties and rules for:
- Background colors and patterns
- Text colors and shadows
- Border styles and animations
- Font families and weights
- Special effects and transitions

## Usage Instructions

1. **Selecting a Theme**: Click the theme dropdown in the top-right corner
2. **Theme Persistence**: Your choice is automatically saved
3. **Keyboard Access**: Use Tab to focus the selector, then Enter/Space to activate
4. **Mobile Usage**: Tap the selector on mobile devices

## Browser Support
- Modern browsers with CSS custom properties support
- Graceful degradation for older browsers
- Progressive enhancement approach
- Cross-platform compatibility

## Performance Considerations
- Efficient CSS organization with minimal redundancy
- Smooth animations using CSS transforms
- Optimized font loading with Google Fonts display swap
- Minimal JavaScript for theme switching logic

## Future Enhancements
- Theme preview thumbnails
- Custom theme builder
- Import/export theme configurations
- Additional theme variations
- System theme detection (dark/light mode)

---

**Created as part of the UCSP & GitHub Workshop**  
*Transform your interface, express your creativity!* 🚀
