# Ludo
A beautiful, feature-rich, and modern web-based Ludo game with multiplayer support, AI opponents, power-ups, and stunning visual effects.
# 🎲 Ludo Master Pro


## ✨ Features

### 🎮 Game Modes
- **Quick Game**: Start playing immediately with 2 or 4 players.
- **Custom Setup**: Configure players, AI difficulty, and game rules.
- **Online Multiplayer**: Play with friends using room codes (simulated).
- **Tournament Mode**: Bracket tournaments and survival challenges.
- **Offline Play**: Full functionality without internet connection.

### 🤖 Advanced AI
- **3 Difficulty Levels**: Easy, Medium, and Hard AI opponents.
- **Strategic Gameplay**: AI considers captures, safety, and optimal moves.
- **Dynamic Decision Making**: Context-aware move selection.

### ⚡ Power-ups System
- **🛡️ Shield**: Protect tokens from capture (3 turns)
- **⚡ Speed Boost**: Move twice per turn (2 turns)
- **🌟 Teleport**: Jump to any safe spot (1 use)
- **🔄 Token Swap**: Switch positions with opponents (1 use)
- **💨 Double Move**: Extra movement options
- **🎯 Precision Strike**: Enhanced capture abilities

### 🎨 Beautiful Design
- **Glassmorphism UI**: Modern glass-like interface elements
- **4 Stunning Themes**: Pastel, Vibrant, Dark, and Sunset
- **Smooth Animations**: 60fps animations with cubic-bezier transitions
- **Particle Effects**: Capture explosions, victory confetti, power-up collections
- **Responsive Design**: Perfect on desktop, tablet, and mobile

### 🌐 Progressive Web App (PWA)
- **Install as App**: Add to home screen on any device
- **Offline Support**: Play without internet connection
- **Push Notifications**: Game updates and reminders
- **Background Sync**: Save progress automatically

### 🎯 Advanced Features
- **Custom Rules**: Capture bonuses, time limits, team mode
- **Statistics Tracking**: Games played, win rates, captures
- **Data Import/Export**: Backup and restore game data
- **Accessibility**: Screen reader support, keyboard navigation
- **Performance Optimized**: Smooth gameplay on all devices

## 🚀 Quick Start

### Play Online
Visit the [live demo](https://shrutirajludo.vercel.app/)) and start playing immediately!

### Local Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ludo-master-pro.git
   cd ludo-master-pro
   ```

2. **Open in browser**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Or simply open index.html in your browser
   ```

3. **Install as PWA**
   - Open the game in your browser
   - Click "Install App" when prompted
   - Or use browser's "Add to Home Screen" option

## 🎮 How to Play

### Basic Rules
1. **Objective**: Get all 4 tokens from home to the finish area
2. **Movement**: Roll dice to move tokens around the board
3. **Starting**: Roll 6 to move tokens out of home
4. **Capturing**: Land on opponent's token to send it home
5. **Safety**: Safe spots (marked with ⭐) protect from capture
6. **Winning**: First player to get all tokens to finish wins

### Controls
- **🎲 Click/Tap Dice**: Roll dice
- **👆 Click Token**: Select and move token
- **⚡ Power-ups**: Long press tokens to use power-ups
- **⌨️ Keyboard Shortcuts**:
  - `Space`: Roll dice
  - `P`: Pause game
  - `R`: Restart game
  - `S`: Show statistics
  - `Esc`: Settings menu

### Power-up Strategy
- Collect power-ups by landing on glowing spots
- Use shields when vulnerable to captures
- Save teleports for emergency escapes
- Speed boosts are great for final sprints

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, CSS Custom Properties
- **Animations**: CSS Transforms, Keyframes, Web Animations API
- **PWA**: Service Worker, Web App Manifest, Cache API
- **APIs**: 
  - Wake Lock API (prevent screen sleep)
  - Vibration API (haptic feedback)
  - Battery API (power management)
  - Web Share API (share functionality)



## 🎨 Customization

### Themes
The game includes 4 built-in themes that can be easily extended:

```css
/* Add new theme */
.theme-ocean {
    --pastel-pink: #00CED1;
    --pastel-blue: #1E90FF;
    --pastel-green: #20B2AA;
    --pastel-yellow: #FFD700;
}
```

### Custom Rules
Modify game behavior through the settings:

```javascript
customRules: {
    captureBonus: true,      // Extra turn on capture
    powerUpsEnabled: true,   // Enable power-up system
    timeLimit: false,        // Turn time limits
    teamMode: false          // 2v2 team play
}
```

## 📊 Performance

- **First Paint**: < 1s
- **Interactive**: < 2s
- **60fps Animations**: Smooth on mobile devices
- **Memory Usage**: < 50MB typical
- **Battery Optimized**: Reduces effects on low battery

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Test thoroughly**
5. **Commit with clear messages**
   ```bash
   git commit -m "Add amazing feature"
   ```
6. **Push to your fork**
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request**

### Development Guidelines
- Follow existing code style
- Add comments for complex logic
- Test on multiple devices/browsers
- Ensure accessibility compliance
- Optimize for performance

## 🐛 Bug Reports

Found a bug? Please create an issue with:
- **Device/Browser**: What you're using
- **Steps to Reproduce**: How to trigger the bug
- **Expected vs Actual**: What should happen vs what happens
- **Screenshots**: If applicable

## 📝 Changelog

### v2.0.0 (Latest)
- ✨ Added power-ups system
- 🎨 New themes and visual effects
- 🌐 PWA support with offline play
- 🤖 Improved AI with 3 difficulty levels
- 📱 Better mobile experience
- ⚡ Performance optimizations

### v1.5.0
- 🎮 Tournament mode
- 📊 Statistics tracking
- 🎵 Sound effects and haptic feedback
- 🌙 Dark mode support

### v1.0.0
- 🎲 Core Ludo gameplay
- 🤖 Basic AI opponents
- 🎨 Beautiful UI design
- 📱 Responsive mobile support

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Font**: [Fredoka](https://fonts.google.com/specimen/Fredoka) by Google Fonts
- **Inspiration**: Classic Ludo board game
- **Icons**: Emoji characters for universal compatibility
- **Design**: Modern glassmorphism and neumorphism trends

## 🔗 Links

- **Live Demo**: [Play Now] (https://shrutirajludo.vercel.app/)
- **Report Issues**: [GitHub Issues](https://github.com/your-username/ludo-master-pro/issues)
- **Feature Requests**: [GitHub Discussions](https://github.com/your-username/ludo-master-pro/discussions)
- **Developer**: [Your Profile](https://github.com/your-username)

## 🌟 Show Your Support

If you enjoy Ludo Master Pro, please:
- ⭐ **Star this repository**
- 🍴 **Fork and contribute**
- 📱 **Share with friends**
- 🐛 **Report bugs**
- 💡 **Suggest features**

---

<div align="center">

**🎲 Made with ❤️ for Ludo lovers everywhere**



</div>
