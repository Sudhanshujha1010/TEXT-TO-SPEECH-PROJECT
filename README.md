**Text-to-Speech Converter 🔊** --

A modern, responsive web application that converts text to speech using the browser's built-in Speech Synthesis API. Features a beautiful gradient interface and support for multiple voices.

![Text-to-Speech Converter](https://img.shields.io/badge/Status-Active-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**✨ Features**

- **🎵 Multiple Voice Selection**: Choose from various available system voices
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **🎨 Modern UI**: Beautiful gradient background with smooth animations
- **⚡ Real-time Processing**: Instant text-to-speech conversion
- **🔧 Easy to Use**: Simple, intuitive interface
- **🌐 Browser Compatible**: Works in all modern web browsers

**🖥️ Demo**

Simply type your text in the textarea, select a voice from the dropdown, and click the "Listen" button to hear your text spoken aloud!

**🚀 Quick Start**

### Prerequisites
- A modern web browser that supports the Speech Synthesis API
- No additional installations required!

### Installation

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/text-to-speech-converter.git
```

2. **Navigate to the project directory**:
```bash
cd text-to-speech-converter
```

3. **Open in browser**:
```bash
# Simply open index.html in your preferred browser
# Or use a local server (recommended)
python -m http.server 8000
# Then visit http://localhost:8000
```

**📁 Project Structure**

```
text-to-speech-converter/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet with modern design
├── script.js           # JavaScript functionality
├── Images/             # Image assets directory
│   ├── favicon.png     # Site favicon
│   ├── play.png        # Play button icon
│   └── dropdown.png    # Dropdown arrow icon
└── README.md          # Project documentation
```

**🎯 How to Use**

1. **Enter Text**: Type or paste the text you want to convert to speech in the textarea
2. **Select Voice**: Choose your preferred voice from the dropdown menu
3. **Listen**: Click the "Listen" button to hear your text spoken
4. **Repeat**: Modify text or voice selection and listen again

**🛠️ Technical Details**

**Technologies Used**
- **HTML5**: Structure and semantic markup
- **CSS3**: Modern styling with gradients and responsive design
- **JavaScript**: Speech Synthesis API integration and DOM manipulation

**Browser Support**
The Speech Synthesis API is supported in:
- ✅ Chrome 33+
- ✅ Firefox 49+
- ✅ Safari 7+
- ✅ Edge 14+
- ✅ Opera 21+

**Key Components**

#### HTML Structure
- Semantic HTML5 elements
- Accessible form controls
- Clean, minimal markup

#### CSS Features
- **Gradient Background**: Beautiful purple-to-pink gradient
- **Responsive Design**: Flexbox layout for perfect centering
- **Custom Styling**: Styled form elements with consistent theme
- **Modern Aesthetics**: Rounded corners, shadows, and smooth transitions

#### JavaScript Functionality
- **Voice Loading**: Dynamically loads available system voices
- **Voice Selection**: Allows users to choose different voices
- **Speech Control**: Handles text-to-speech conversion
- **Event Handling**: Responsive user interactions

**🎨 Customization**

### Changing Colors
Edit the CSS variables in `style.css`:
```css
.hero {
    background: linear-gradient(45deg, #010758, #490d61); /* Main gradient */
}

.hero h1 span {
    color: #ff2963; /* Accent color */
}

button {
    background: #ff2963; /* Button color */
}
```
**Adding Features**
The codebase is modular and easy to extend:
- Add speech rate control
- Include pitch adjustment
- Implement text highlighting during speech
- Add voice preview functionality

**🔧 Configuration**

### Voice Settings
You can modify the default voice selection in `script.js`:
```javascript
// Set default voice (currently uses first available voice)
speech.voice = voices[0];

// You can specify a preferred voice by name
// speech.voice = voices.find(voice => voice.name === 'Google UK English Male');
```

### Speech Parameters
Customize speech characteristics:
```javascript
speech.rate = 1;    // Speed (0.1 to 10)
speech.pitch = 1;   // Pitch (0 to 2)
speech.volume = 1;  // Volume (0 to 1)
```

## 🐛 Troubleshooting

### Common Issues

**No voices available:**
- Ensure your browser supports the Speech Synthesis API
- Try refreshing the page
- Check if your system has TTS voices installed

**Speech not working:**
- Verify your device's volume is turned up
- Ensure the browser has permission to use audio
- Try a different voice from the dropdown

**Styling issues:**
- Clear your browser cache
- Ensure all CSS files are loading properly
- Check browser developer tools for errors

**🤝 Contributing**

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit your changes**: `git commit -m 'Add amazing feature'`
4. **Push to the branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**
