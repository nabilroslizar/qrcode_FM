# QR Code Component

A clean and responsive QR code component built as a solution to the [Frontend Mentor QR code component challenge](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## 🚀 Live Demo

[View Live Demo](http://localhost:8000) (when running locally)

## 📱 Screenshot

![QR Code Component](./screenshot.jpg)

## ✨ Features

- **Responsive Design**: Works perfectly on all device sizes
- **Modern Typography**: Uses Google Fonts (Outfit) for clean, professional text
- **Accessible**: Proper semantic HTML and alt text for images
- **Clean Layout**: Centered card design with proper spacing and shadows
- **Cross-browser Compatible**: Works on all modern browsers

## 🛠️ Built With

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox
- **Google Fonts**: Outfit font family (400 & 700 weights)
- **Responsive Design**: Mobile-first approach

## 🎨 Design Specifications

### Typography
- **Heading**: Outfit Bold, 22px, 120% line height, 0px letter spacing
- **Body Text**: Outfit Regular, 15px, 140% line height, 0.2px letter spacing

### Colors
- **Background**: #d5e1ef (Light blue-gray)
- **Card Background**: #ffffff (White)
- **Heading Text**: #1f314f (Dark blue)
- **Body Text**: #68778d (Medium gray)

### Layout
- **Card Dimensions**: 320px × 499px
- **Border Radius**: 20px
- **Padding**: 16px
- **Image Border Radius**: 10px

## 📁 Project Structure

```
qrcode/
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── images/             # Image assets
│   └── image-qr-code.png
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Python 3 (for local development server)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd qrcode
   ```

2. **Start a local development server**
   ```bash
   python3 -m http.server 8000
   ```

3. **Open your browser**
   Navigate to `http://localhost:8000`

### Alternative Setup Options

- **VS Code Live Server**: Install the Live Server extension and right-click `index.html` → "Open with Live Server"
- **Direct File**: Simply double-click `index.html` to open in your default browser
- **Node.js**: Use `npx serve .` if you have Node.js installed

## 💡 Key Learnings

### CSS Flexbox Mastery
```css
body {
    background-color: #d5e1ef;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
}
```

### Google Fonts Integration
```html
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
```

### Responsive Image Handling
```css
img {
    border-radius: 10px;
    width: 100%;
    height: auto;
    max-width: 100%;
}
```

### Card Component Design
```css
.container {
    text-align: center;
    background-color: white;
    width: 320px;
    padding: 16px;
    margin: auto;
    border-radius: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
```

## 🎯 Challenges Solved

1. **Font Loading**: Switched from local font files to Google Fonts for better reliability
2. **Responsive Design**: Implemented flexible layout that works on all screen sizes
3. **Typography Matching**: Precisely matched Figma design specifications
4. **Cross-browser Compatibility**: Ensured consistent appearance across browsers

## 🔧 Technical Details

- **Box Model**: Used `box-sizing: border-box` for predictable sizing
- **Font Loading**: Optimized with `preconnect` for faster Google Fonts loading
- **Semantic HTML**: Proper use of heading hierarchy and alt text
- **CSS Organization**: Clean, maintainable stylesheet structure

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Nabil Roslizar**
- Frontend Mentor: [@nabilroslizar](https://www.frontendmentor.io/profile/nabilroslizar)
- GitHub: [@nabilroslizar](https://github.com/nabilroslizar)

## 🙏 Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io/) for providing this amazing challenge
- [Google Fonts](https://fonts.google.com/) for the beautiful Outfit font family
- The web development community for inspiration and best practices

---

⭐ **Star this repository if you found it helpful!**