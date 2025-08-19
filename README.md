# Digital Clock ⏰

A beautiful, modern digital clock web application with animated background elements and glassmorphism design.

## 🌟 Features

- **Real-time Digital Clock**: Displays current time in 12-hour format with AM/PM indicator
- **Modern Design**: Glassmorphism effect with backdrop blur and transparency
- **Animated Background**: Floating geometric shapes with smooth animations
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Clean Interface**: Minimalist design with elegant typography

## 🎨 Design Highlights

- **Glassmorphism Effect**: Semi-transparent clock container with blur effect
- **Gradient Animations**: Colorful floating shapes with continuous movement
- **Typography**: Consolas font for a clean, monospace appearance
- **Color Scheme**: Dark theme with vibrant accent colors

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Enjoy your beautiful digital clock!

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd Clock

# Open in browser
open index.html
```

## 📁 Project Structure

```
Clock/
├── index.html          # Main HTML file
├── script.js           # JavaScript functionality
├── CSS/
│   └── style.css      # Styling and animations
└── README.md          # Project documentation
```

## 🔧 How It Works

### HTML Structure
- Simple semantic structure with a clock container
- Time elements for hours, minutes, seconds, and AM/PM indicator

### JavaScript Functionality
- `showTime()` function updates the clock every second
- Handles 12-hour format conversion
- Adds leading zeros for single-digit numbers
- Updates DOM elements with current time

### CSS Styling
- **Background**: Dark theme with animated gradient shapes
- **Clock Container**: Glassmorphism effect with backdrop filter
- **Animations**: Floating shapes with vertical movement
- **Responsive**: Media queries for mobile optimization

## 📱 Responsive Design

The clock is fully responsive and adapts to different screen sizes:
- **Desktop**: Large clock display with full animations
- **Mobile**: Optimized layout with adjusted font sizes and positioning

## 🎯 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🛠️ Customization

You can easily customize the clock by modifying:

### Colors
Edit the gradient colors in `style.css`:
```css
background: linear-gradient(#f9d924,#ff2c24); /* Yellow to red */
background: linear-gradient(#01d6ff,#0f24f9); /* Cyan to blue */
```

### Animation Speed
Adjust the animation duration:
```css
animation: animate 5s ease-in-out infinite; /* Change 5s to desired speed */
```

### Clock Size
Modify the clock dimensions:
```css
.clock {
    width: 700px;  /* Adjust width */
    height: 250px; /* Adjust height */
}
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📞 Support

If you have any questions or need help, please open an issue in the repository.

---

**Enjoy your beautiful digital clock! ⏰✨**
