# ⌨️ TypeTogether

**The Communal Digital Typewriter**

TypeTogether is a collaborative web-based typewriter where users share a single, ever-evolving document. Type alongside others in real-time, continue where someone else left off, or start a fresh page—all with the nostalgic charm of a vintage typewriter.

![TypeTogether Banner](https://img.shields.io/badge/status-live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Features

- 🖋️ **Communal Writing** - Share a single document with all visitors
- 💾 **Auto-Save & Sync** - Your words are automatically saved and synchronized
- 🎨 **Vintage Aesthetics** - Retro-futuristic typewriter design with authentic paper texture
- 🔊 **Typewriter Sound Effects** - Toggle realistic typing sounds
- ✨ **Visual Effects** - See floating letters as you type
- 📄 **Multiple Pages** - Create new pages or browse previous collaborative works
- 📱 **Responsive Design** - Works beautifully on desktop and mobile
- ⚡ **Real-Time Updates** - See contributions from other writers appear live

## 🚀 Demo

**[Try TypeTogether Live](#)** *(Add your GitHub Pages link here)*

## 🛠️ Installation

### Quick Start

1. Clone this repository:
```bash
git clone https://github.com/yourusername/typetogether.git
cd typetogether
```

2. Open `index.html` in your browser:
```bash
open index.html
# or
python -m http.server 8000
# or
npx serve
```

3. Start typing!

### Deploy to GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Select **main** branch as source
4. Your site will be live at `https://yourusername.github.io/typetogether`

## 📖 How It Works

TypeTogether uses the browser's persistent storage API to enable real-time collaboration:

- **Shared State**: All users read from and write to the same shared storage
- **Auto-Sync**: Content synchronizes every 3 seconds
- **Conflict Resolution**: Last-write-wins strategy for simplicity
- **Page System**: Create multiple collaborative documents

## 🎨 Design Philosophy

TypeTogether combines:
- **Brutalist aesthetics** with bold, functional design
- **Retro-futuristic** elements that honor vintage typewriters
- **Minimalist interactions** that feel authentic and mechanical
- **Atmospheric details** like paper texture, grain overlay, and shadows

### Typography
- **Courier Prime** - Body text (authentic typewriter font)
- **Special Elite** - Headers (vintage typewriter aesthetic)
- **IBM Plex Mono** - UI elements (modern monospace)

### Color Palette
- Ink Black: `#1a1a1a`
- Paper White: `#f4f1e8`
- Ribbon Red: `#c1272d`
- Metal Gray: `#4a4a4a`
- Brass Gold: `#b8860b`

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions
- Export to PDF/TXT functionality
- User avatars/cursors for live collaboration
- Rich text formatting options
- Theme customization
- Sound effect variations
- Archive/browse old pages interface
- Private rooms/channels

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by vintage typewriters and the beauty of analog writing
- Font: [Courier Prime](https://fonts.google.com/specimen/Courier+Prime) by Alan Dague-Greene
- Font: [Special Elite](https://fonts.google.com/specimen/Special+Elite) by Astigmatic

## 📧 Contact

Have questions or suggestions? Open an issue or reach out!

---

**Made with ❤️ for writers, dreamers, and collaborative storytellers**

*Type together, create together.*
