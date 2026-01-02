# 📸 Passport Photo Grid Generator

A simple, privacy-focused web application that creates a 4×6 inch print layout containing six 2×2 inch passport photos. Perfect for printing passport photos at home or through online photo services.

## 🌐 Live Demo

**Try it now: <a href="https://ejohnson-dotnet.github.io/passport-photo-grid/" target="_blank">https://ejohnson-dotnet.github.io/passport-photo-grid/</a>**

No installation required - works directly in your browser!

![Passport Photo Grid Generator](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

- **Easy to Use**: Simple drag-and-drop or click-to-upload interface
- **Privacy First**: All processing happens in your browser - no uploads, no server storage
- **Square Photo Validation**: Automatic warning if uploaded photo is not square
- **Professional Layout**: Creates a standard 4×6 inch grid with six 2×2 inch photos
- **High Quality Output**: Generates print-ready JPEG files
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **No Installation Required**: Run directly in any modern web browser

## 🚀 How to Use

1. **Create Your Passport Photo**
   - Visit the [official U.S. passport photo tool](https://tsg.phototool.state.gov/photo)
   - Follow their guidelines for proper composition, lighting, and background
   - Download your compliant 2×2 inch passport photo

2. **Generate the Grid**
   - Open `index.html` in your web browser
   - Upload your passport photo by clicking the upload area or dragging and dropping
   - The grid will be automatically generated

3. **Download and Print**
   - Click the "Download 4×6 Grid" button
   - Print using services like Shutterfly, CVS Photo, Walgreens, or ezprints
   - Order a standard 4×6 inch print

4. **Cut Your Photos**
   - Once printed, carefully cut out each 2×2 inch photo
   - You'll have six photos - perfect for multiple applications or backups!

## 🛠️ Technologies Used

- HTML5 Canvas API for image processing
- Bootstrap 5 for modern, responsive UI
- Bootstrap Icons for visual elements
- Vanilla JavaScript (no dependencies required)
- CSS3 with gradient backgrounds and animations

## 📋 Photo Requirements

For best results, your uploaded photo should be:
- **Square dimensions** (e.g., 600×600 pixels, 2×2 inches)
- **JPEG or PNG format**
- **Compliant with passport photo standards** (proper lighting, background, positioning)

The application will warn you if your photo is not square, as non-square photos may appear distorted.

## 🔒 Privacy & Security

- **No Server Uploads**: All image processing happens locally in your browser
- **No Data Storage**: Photos are never stored or transmitted anywhere
- **No Analytics**: No tracking or data collection
- **Open Source**: All code is visible and can be audited

## 💻 Local Development

Simply open `index.html` in your web browser. No build process or server required!

For local development with live reload, you can use any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server

# Using VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

Then visit `http://localhost:8000` in your browser.

## 📱 Browser Compatibility

Works in all modern browsers that support:
- HTML5 Canvas API
- File API
- ES6 JavaScript

Tested on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- U.S. Department of State for the [official passport photo tool](https://tsg.phototool.state.gov/photo)
- Bootstrap team for the excellent UI framework
- All photo printing services that support standard 4×6 prints

## ⚠️ Disclaimer

This tool helps you create a print layout for passport photos. However, you are responsible for ensuring your photos meet all official passport photo requirements set by your country's passport agency. Always verify your photos comply with current regulations before submission.

---

Made with ❤️ for travelers and document applicants worldwide
