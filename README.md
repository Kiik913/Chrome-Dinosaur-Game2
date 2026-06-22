# Chrome Dinosaur Game

A simple embedded version of the classic Chrome Dinosaur Game.

## Overview

This project displays the famous Chrome Dino Game inside a responsive iframe. The game automatically scales to fit different screen sizes while maintaining its aspect ratio.

## Features

- Responsive layout
- Lightweight and fast
- Easy to embed into websites
- Works on desktop and mobile browsers
- No additional dependencies required

## Demo

The game is loaded from:

https://elgoog.im/dinosaur-game/

## Project Structure

```text
project/
│
├── index.html
└── README.md
```

## Installation

1. Download or clone the repository.

```bash
git clone https://github.com/yourusername/chrome-dinosaur-game.git
```

2. Open the project folder.

3. Launch `index.html` in your browser.

## Code Example

```html
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe
    src="https://elgoog.im/dinosaur-game/"
    width="100%"
    frameborder="0"
    scrolling="no"
    allowfullscreen
    loading="lazy"
    style="position:absolute;top:0;left:0;width:100%;height:100%;"
  ></iframe>
</div>
```

## Customization

You can:

- Change the iframe height ratio
- Add custom styling
- Place the game inside cards or containers
- Add fullscreen support
- Integrate it into larger web projects

## Browser Support

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari
- Opera

## License

This project is intended for educational and personal use.

## Author

Kavyant Kumar

---

Made with ❤️ using HTML and embedded web content.
