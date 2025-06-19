# Image Gallery Lightbox

A modern image gallery with lightbox functionality and touch gestures. Perfect for showcasing portfolios, product images, or any collection of images with an elegant viewing experience.

## ✨ Features

- **Lightbox View**: Full-screen image viewing with overlay
- **Touch Gestures**: Swipe navigation on mobile devices
- **Keyboard Navigation**: Arrow keys and ESC for navigation
- **Responsive Grid**: Adaptive grid layout for all screen sizes
- **Smooth Animations**: Beautiful transitions and hover effects
- **Image Zoom**: Optional zoom functionality for detailed viewing
- **Accessible**: Built with ARIA labels and keyboard support
- **Lightweight**: Pure CSS and JavaScript, no dependencies

## 🚀 Live Demo

[View on CodePen](https://codepen.io/harmoncode/pen/KwpKxwj)

## 📁 Files

- `index.html` - Main HTML structure
- `style.css` - All styling and animations
- `script.js` - JavaScript functionality

## 🛠️ Usage

### Basic Implementation

```html
<div class="gallery">
    <div class="gallery-item">
        <img src="image1.jpg" alt="Image 1" data-lightbox="gallery">
    </div>
    <div class="gallery-item">
        <img src="image2.jpg" alt="Image 2" data-lightbox="gallery">
    </div>
    <!-- More images... -->
</div>

<div class="lightbox" id="lightbox">
    <div class="lightbox-content">
        <img src="" alt="" id="lightbox-img">
        <button class="close-btn">&times;</button>
        <button class="nav-btn prev">&lt;</button>
        <button class="nav-btn next">&gt;</button>
    </div>
</div>
```

### JavaScript Initialization

```javascript
// Initialize lightbox
const lightbox = new Lightbox({
    gallery: '.gallery',
    lightbox: '#lightbox',
    enableZoom: true,
    enableSwipe: true
});
```

## 🎨 Customization Options

- **Grid Layout**: Customize columns and spacing
- **Lightbox Style**: Modify overlay and image container
- **Animations**: Adjust transition effects
- **Navigation**: Customize navigation buttons
- **Colors**: Change theme colors and backgrounds

## ⚙️ Configuration

```javascript
const config = {
    enableZoom: true,        // Enable image zoom
    enableSwipe: true,       // Enable touch gestures
    animationDuration: 300,  // Animation duration (ms)
    showThumbnails: false,   // Show thumbnail navigation
    autoPlay: false,         // Auto-play slideshow
    autoPlayDelay: 3000      // Auto-play delay (ms)
};
```

## 📱 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- IE11+ ✅

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Created by

**HarmonCode** - [harmoncode.com](https://harmoncode.com)

---

⭐ If you find this useful, please give it a star! 