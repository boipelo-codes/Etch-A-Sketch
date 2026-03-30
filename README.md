# 🎨 Etch-A-Sketch Drawing Pad

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://your-username.github.io/etch-a-sketch)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A classic Etch-A-Sketch drawing application that allows users to create pixel art by hovering over a customizable grid. Built as part of [The Odin Project](https://www.theodinproject.com/) curriculum.

![Etch-A-Sketch Demo](/screenshots/image.png)

## ✨ Features

- **🎮 Interactive Grid**: Hover over squares to draw, just like a real Etch-A-Sketch
- **📏 Customizable Size**: Create grids from 1x1 up to 100x100 squares
- **🌈 Rainbow Mode**: Draw with random RGB colors for vibrant, colorful art
- **⚫ Progressive Darkening**: Each interaction darkens squares by 10% (fully black after 10 hovers)
- **🗑️ Clear Canvas**: Reset your drawing with a single click
- **📱 Responsive Design**: Works on desktop, tablet, and mobile devices
- **🎨 Multiple Drawing Modes**:
  - **Normal Mode**: Classic black drawing
  - **Rainbow Mode**: Random colors on every hover
  - **Darken Mode**: Progressive darkening effect

## 🚀 Live Demo

Check out the live version here: [Etch-A-Sketch Demo](https://your-username.github.io/etch-a-sketch)

## 🛠️ Technologies Used

- **HTML5** - Structure and layout
- **CSS3** - Styling, animations, and Flexbox layout
- **JavaScript (ES6+)** - Dynamic grid generation and interactive features

## 📋 Requirements Met

This project fulfills all requirements from The Odin Project:

- ✅ 16x16 grid of square divs created with JavaScript
- ✅ Dynamic grid generation (no hardcoded divs)
- ✅ Flexbox-based layout (no CSS Grid)
- ✅ Hover effects that change square colors
- ✅ New grid button with user input (1-100 squares per side)
- ✅ Maintains consistent total grid size when resizing
- ✅ Extra credit: Random RGB colors
- ✅ Extra credit: Progressive darkening effect

## 🎯 How to Use

1. **Draw**: Simply hover your mouse over any square in the grid
2. **Change Grid Size**: Click "New Grid" and enter a number between 1-100
3. **Clear Drawing**: Click "Clear Canvas" to erase everything
4. **Switch Modes**:
   - Click "Normal Mode" for standard black drawing
   - Click "Rainbow Mode" for random colors
   - Click "Darken Mode" for progressive darkening

## 💻 Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/etch-a-sketch.git
```
## 🎨 Customization

You can easily customize the drawing experience:

- **Change default grid size**: Modify `this.gridSize = 16` in the constructor
- **Adjust darkening speed**: Change the `0.1` value in the darken mode logic
- **Modify container size**: Update the `.grid-container` width/height in CSS

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [The Odin Project](https://www.theodinproject.com/) for the project inspiration and curriculum
- All contributors and users who provide feedback and suggestions

## 📧 Contact

Your Name - Boipelo Ngakane

Project Link: [https://github.com/boipelo-codes/etch-a-sketch](https://github.com/boipelo-codes/etch-a-sketch)