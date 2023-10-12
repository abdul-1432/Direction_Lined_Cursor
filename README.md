# Direction Lined Cursor

## Overview

Direction Lined Cursor is a lightweight JavaScript library that enhances the user experience by providing a customizable cursor with directional lines. This library is designed to be easily integrated into web projects, adding a visually appealing and interactive element to the cursor.

## Features

- **Directional Lines**: The cursor displays dynamic directional lines, indicating the movement direction.
- **Customizable Styles**: Easily customize the appearance of the cursor, including line colors, thickness, and length.
- **Responsive Design**: The library is responsive and works seamlessly across various screen sizes and devices.
- **Easy Integration**: Simple integration with just a few lines of code, making it suitable for both beginners and experienced developers.

## Getting Started

### Installation

You can install Direction Lined Cursor via npm:

```bash
npm install direction-lined-cursor
```

Or include the CDN in your HTML:

```HTML
<script src="https://cdn.jsdelivr.net/npm/direction-lined-cursor/dist/direction-lined-cursor.min.js"></script>
```

### Usage

1. Include the library in your HTML file:

```HTML
<script src="path/to/direction-lined-cursor.min.js"></script>
```

2. Initialize the cursor:

```javascript
const cursor = new DirectionLinedCursor();
cursor.init();
```

3. Customize the cursor (optional):

```javascript
const cursor = new DirectionLinedCursor({
  line Color: '#ff0000',
  line Width: 2,
  line length: 20,
});
cursor.init();
```

## Options

- **lineColor**: Color of the directional lines (default: '#000').
- **lineWidth**: Thickness of the lines (default: 1).
- **lineLength**: Length of the lines (default: 10).

## Example

```javascript
const cursor = new DirectionLinedCursor({
  line Color: '#00ff00',
  line Width: 3,
  line length: 15,
});
cursor.init();
```

## License

Direction Lined Cursor is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This library was inspired by the desire to add a modern and engaging cursor effect to web projects.
- Special thanks to the open-source community for their contributions and feedback.

Feel free to contribute, report issues, or suggest improvements!
