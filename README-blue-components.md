# Blue Theme Components

A comprehensive set of blue-themed UI components designed for modern web applications, perfect for 21st.dev's AI-powered UI tools.

## 🎨 What's Included

### Core Files
- `blue-theme.css` - Complete CSS framework with blue color palette and components
- `blue-components.html` - Interactive demo showcasing all components
- `README-blue-components.md` - This documentation file

### 🌊 Color Palette
- **Primary Blues**: 10 shades from light (`--blue-50`) to dark (`--blue-950`)
- **Semantic Variables**: `--primary-blue`, `--primary-blue-hover`, etc.
- **Utility Colors**: Background, text, and border variations

### 🔧 Components

#### Buttons
- **Primary**: Standard blue button with hover effects
- **Outline**: Transparent with blue border
- **Ghost**: Minimal styling, blue text
- **Soft**: Light blue background

#### Cards
- **Standard Card**: Clean white cards with blue accents
- **Header Card**: Cards with dedicated header sections
- **Hover Effects**: Subtle animations and shadows

#### Forms
- **Blue Inputs**: Text inputs with blue focus states
- **Form Labels**: Consistent typography
- **Validation Ready**: Easy to extend with validation styles

#### Navigation
- **Blue Navbar**: Professional navigation component
- **Responsive Design**: Mobile-friendly layout

#### Alerts & Badges
- **Info Alerts**: Blue-themed notification boxes
- **Status Badges**: Small labels for tagging content

### ✨ Features

1. **Responsive Design**: Mobile-first approach with breakpoints
2. **Accessibility**: Focus states and semantic HTML
3. **Interactive Effects**: Hover animations and click ripples
4. **CSS Variables**: Easy customization and theming
5. **Modern CSS**: Flexbox, Grid, and CSS custom properties

### 🚀 Quick Start

1. Include the CSS file:
```html
<link rel="stylesheet" href="blue-theme.css">
```

2. Use the classes in your HTML:
```html
<button class="btn-blue">Click me!</button>
<div class="card-blue">
  <div class="card-blue-title">Card Title</div>
  <div class="card-blue-content">Card content here...</div>
</div>
```

### 🎯 Usage Examples

#### Basic Button
```html
<button class="btn-blue">Primary Action</button>
<button class="btn-blue-outline">Secondary Action</button>
```

#### Card with Header
```html
<div class="card-blue">
  <div class="card-blue-header">
    <div class="card-blue-title">Title</div>
    <div class="card-blue-subtitle">Subtitle</div>
  </div>
  <div class="card-blue-content">
    <p>Your content here...</p>
  </div>
</div>
```

#### Form Input
```html
<div class="form-group">
  <label class="form-label" for="email">Email</label>
  <input type="email" id="email" class="input-blue" placeholder="Enter email">
</div>
```

### 🎨 Customization

The theme uses CSS custom properties, making it easy to customize:

```css
:root {
  --primary-blue: #your-custom-blue;
  --primary-blue-hover: #your-custom-hover;
  /* Customize other variables as needed */
}
```

### 📱 Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support required
- CSS Custom Properties support required

### 🔧 Integration with 21st.dev Tools
These components are designed to work seamlessly with:
- Magic MCP for AI-powered UI generation
- Component libraries and design systems
- Modern development workflows

### 📄 License
Created for 21st.dev - Better UI in the era of AI coding

---

**Demo**: Open `blue-components.html` in your browser to see all components in action!