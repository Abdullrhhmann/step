
# Step - Coming Soon Page

A modern, Gen Z-inspired coming soon page for Step startup.

## 📁 Project Structure

```
Step/
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── assets/
│   └── images/
│       ├── hero.jpg    # Place your hero background image here
│       └── logo.png    # Place your Step logo here
└── README.md          # This file
```

## 🎨 Design Features

- **Full-screen hero image** with subtle Ken Burns zoom animation
- **Vibrant gradient overlay** (blue → purple → pink) for modern Gen Z aesthetic
- **Glassmorphism "Coming Soon" badge** with backdrop blur effect
- **Smooth animations**: Fade-in-up for text, floating logo effect
- **Responsive typography** using CSS clamp() for fluid scaling
- **Mobile-first design** that works perfectly on all devices
- **Accessibility features**: Reduced motion support, high contrast mode, keyboard navigation

## 🚀 Setup Instructions

1. **Add your images:**
   - Place your hero background image as `assets/images/hero.jpg`
   - Place your Step logo as `assets/images/logo.png`
   
   > **Note:** If your images have different names or formats (like .png for hero or .svg for logo), update the file paths in:
   > - Line 55 in `styles.css` for hero image
   > - Line 23 in `index.html` for logo

2. **Open the page:**
   - Simply open `index.html` in your browser
   - Or use a local server for best results

## 🎨 Customization

### Change Colors
Edit the CSS variables in `styles.css` (lines 16-22):
```css
:root {
    --color-accent-primary: #3B82F6;    /* Blue */
    --color-accent-secondary: #8B5CF6;  /* Purple */
    --color-accent-tertiary: #EC4899;   /* Pink */
}
```

### Adjust Gradient Overlay
Modify lines 78-84 in `styles.css` to change the gradient colors and opacity.

### Update Text
Edit `index.html` lines 27-28 to change the brand name or slogan.

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## 🎯 What's Included

✅ Modern Gen Z design aesthetic  
✅ Smooth entrance animations  
✅ Responsive design (mobile to desktop)  
✅ Accessibility features  
✅ Glassmorphism effects  
✅ Gradient overlays  
✅ Clean, semantic HTML  

---

**Ready to launch?** Just add your hero image and logo to get started!
