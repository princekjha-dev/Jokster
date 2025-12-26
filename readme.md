# 😂 Jokster - Your Daily Dose of Laughter

A premium, cinematic joke application with a minimal and user-friendly interface. Built with vanilla JavaScript, featuring a sophisticated dark theme inspired by modern design principles.

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

### Core Functionality
- 🎲 **Random Joke Generator** - Get instant laughs with a single click
- 📁 **Category Filter** - Browse jokes by type (General, Programming, Knock-Knock, Dad Jokes)
- ⭐ **Favorites System** - Save your favorite jokes for later
- 🔍 **Search Favorites** - Quickly find saved jokes
- 📜 **View History** - See your recently viewed jokes
- 📊 **Statistics Tracking** - Track jokes viewed and favorites count

### Advanced Features
- 🔊 **Text-to-Speech** - Listen to jokes with customizable voices
- 📋 **Copy to Clipboard** - Share jokes easily
- 📱 **Share Functionality** - Native share support on compatible devices
- 👍👎 **Rating System** - Rate jokes with thumbs up/down
- ⌨️ **Keyboard Shortcuts** - Navigate with efficiency
- 💾 **Session Storage** - Data persists during your session

## 🎨 Design Philosophy

**Premium Cinematic Experience**
- Minimal, clean interface with maximum impact
- Dark theme optimized for comfortable viewing
- Smooth animations and transitions
- Apple-inspired design language
- Fully responsive across all devices

## 🚀 Quick Start

### Installation

1. Clone or download the repository:
```bash
git clone https://github.com/yourusername/jokster.git
cd jokster
```

2. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

That's it! No build process or dependencies required.

### File Structure
```
jokster/
│
├── index.html          # Main HTML structure
├── styles.css          # Premium cinematic styles
├── script.js           # Application logic
└── README.md           # Documentation
```

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Get a new random joke |
| `F` | Toggle favorite on current joke |
| `C` | Copy current joke to clipboard |
| `S` | Share current joke |
| `T` | Read joke aloud (Text-to-Speech) |
| `→` | Cycle to next category |
| `?` | Show keyboard shortcuts help |

## 🎯 Usage Guide

### Getting Started
1. **View a Joke**: Click "Get New Joke" or press `Enter`
2. **Filter by Category**: Use the category dropdown to filter jokes
3. **Add to Favorites**: Click the heart icon or press `F`
4. **Listen to Jokes**: Click the speaker icon to hear jokes read aloud

### Managing Favorites
- Click any joke in the favorites list to view it
- Use the search box to filter saved jokes
- Remove individual jokes with the × button
- Clear all favorites with "Clear All" button

### History
- Automatically tracks your last 10 viewed jokes
- Click any joke in history to view it again
- History resets when you close the browser

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** - ES6+ features
- **Web Speech API** - Text-to-Speech functionality
- **Clipboard API** - Copy functionality
- **Web Share API** - Native sharing

### Browser Support
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)

**Note**: Text-to-Speech and Share features may have limited support on older browsers.

### Data Storage
The app uses in-memory storage during your session:
- **Favorites**: Saved jokes (session-only)
- **History**: Recently viewed jokes (last 10)
- **Stats**: Jokes viewed count

All data is cleared when you close the browser tab.

## 🎨 Customization

### Changing Colors
Edit CSS variables in `styles.css`:

```css
:root {
    --accent: #0071e3;        /* Primary accent color */
    --success: #30d158;       /* Success messages */
    --danger: #ff453a;        /* Delete actions */
    --bg-main: #000000;       /* Main background */
    --bg-card: #1c1c1e;       /* Card background */
    /* ... more variables */
}
```

### Adding Jokes
Add new jokes to the `jokes` array in `script.js`:

```javascript
{
    "type": "general",
    "setup": "Your joke setup here?",
    "punchline": "Your punchline here!"
}
```

### Supported Categories
- `general` - General jokes
- `programming` - Programming/tech jokes
- `knock-knock` - Knock-knock jokes
- `dad` - Dad jokes

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/AmazingFeature`
3. **Commit your changes**: `git commit -m 'Add some AmazingFeature'`
4. **Push to the branch**: `git push origin feature/AmazingFeature`
5. **Open a Pull Request**

### Ideas for Contributions
- Add more jokes to the database
- Implement joke API integration
- Add new joke categories
- Improve accessibility features
- Create additional themes
- Add joke submission feature
- Implement social sharing features

## 📝 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2024 Jokster

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🐛 Known Issues

- Text-to-Speech voices may load slowly on first use
- Web Share API not supported on desktop browsers
- Session storage clears on browser close

## 🔮 Future Enhancements

- [ ] Persistent storage with localStorage option
- [ ] Dark/Light theme toggle
- [ ] Joke submission system
- [ ] Integration with joke APIs
- [ ] Daily joke notifications
- [ ] Joke categories expansion
- [ ] Multi-language support
- [ ] User accounts and cloud sync
- [ ] Joke rating analytics
- [ ] Social features

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/jokster/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/jokster/discussions)
- **Email**: support@jokster.app

## 🙏 Acknowledgments

- Icons by [Font Awesome](https://fontawesome.com/)
- Inspired by modern design principles from Apple, Spotify, and Netflix
- Joke database compiled from various public sources
- Built with ❤️ for the community

## 📊 Stats

- **Total Jokes**: 400+
- **Categories**: 4
- **File Size**: ~100KB (total)
- **Load Time**: < 1 second
- **No Dependencies**: Pure vanilla JavaScript

---

**Made with 😂 by the Jokster Team**

*Keep laughing, keep sharing!*