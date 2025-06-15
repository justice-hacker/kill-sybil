# kill-sybil

A mysterious interactive web experience featuring puppet and todd characters in a haunting digital landscape.

## 🌐 Live Site

Visit the experience at: [https://www.kill-sybil.xyz/](https://www.kill-sybil.xyz/)

## 📋 Description

kill-sybil is an atmospheric web project that presents an interactive scene with clickable SVG characters positioned against a background image. The project features a minimalist design with hover effects and responsive positioning that adapts to different screen sizes.

## 🎨 Features

- **Interactive SVG Characters**: Two main characters - "puppet" and "todd" - that respond to hover with glowing effects
- **Responsive Design**: Automatically adjusts character positioning and sizing for mobile and desktop views
- **Mysterious Atmosphere**: Dark background with carefully positioned interactive elements
- **Social Media Integration**: Links to relevant Twitter/X posts and profiles
- **Clean, Minimal Code**: Pure HTML/CSS/JavaScript with no external dependencies

## 🗂️ Project Structure

```
kill-sybil/
├── index.html          # Main HTML file with embedded styles and scripts
├── puppet.svg          # Large puppet character SVG (397x189)
├── todd.svg           # Small todd character SVG (141x41)
├── background.jpg     # Background image (not included in repo)
├── justa_bera.png     # Cult icon image (not included in repo)
└── README.md          # This file
```

## 🚀 Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/kill-sybil.git
   ```

2. Add the required image assets:

   - `background.jpg` - Main background image
   - `justa_bera.png` - Cult icon image

3. Open `index.html` in a web browser or serve it through a web server.

## 💻 Technical Details

### Responsive Behavior

- **Desktop**: Full-width background with proportionally sized characters
- **Mobile** (≤768px): Background anchored to left-bottom, larger character sizes for better touch interaction

### Character Positioning

The JavaScript dynamically positions characters based on:

- Original canvas dimensions: 3840x2160
- Puppet position: ~(820, 1900)
- Todd position: ~(130, 210)

### Hover Effects

- **Puppet & Todd**: Drop shadow glow effect (#919191)
- **Cult icon**: Inverts to black on hover

## 🔗 External Links

The project links to specific Twitter/X posts:

- Puppet: [@BeraPuppets status](https://x.com/BeraPuppets/status/1910668863496143122)
- Todd: [@Justa_Bera status](https://x.com/Justa_Bera/status/1929241099387773312)
- Cult icon: [@Justa_Bera profile](https://x.com/Justa_Bera)

## 🎯 Browser Support

- Modern browsers with SVG support
- CSS transitions and transforms
- JavaScript ES6+
