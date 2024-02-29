# Drawing App

Welcome to the Drawing App! This is a simple web-based application written in JavaScript for creating pixel art. With this app, you can draw, fill colors, select tools, save and load your artwork, and undo changes. Below, you'll find a guide on how to use the app effectively.

## Getting Started

To get started, include the provided JavaScript code in your HTML file. The code consists of classes and functions necessary for the functionality of the Drawing App.

```html
<script src="pixel.js"></script>
```

## Usage

### Initializing the App

To initialize the Drawing App, call the `startPixelEditor()` function. You can pass optional parameters to customize the app's initial state, tools, and controls.

```javascript
const appElement = startPixelEditor({
  state: startState,  // Optional: Initial state of the app
  tools: baseTools,   // Optional: Custom tools
  controls: baseControls // Optional: Custom controls
});

document.body.appendChild(appElement); // Append the app to the DOM
```

### Tools

The app provides various tools for drawing and editing pixel art:

- **Draw Tool (🖌️)**: Use this tool to draw pixels on the canvas.
- **Fill Tool (🌈)**: Fill a continuous area with the selected color.
- **Rectangle Tool (🔲)**: Draw rectangles on the canvas.
- **Color Picker Tool (🎨)**: Select a color from the canvas.

### Controls

The app includes several controls for managing your artwork:

- **Tool Selector**: Choose the desired drawing tool from the dropdown menu.
- **Color Selector**: Select the color for drawing from the color picker.
- **Save Button (💾)**: Save your artwork as a PNG file.
- **Load Button (📁)**: Load an existing image to continue editing.
- **Undo Button (⮪)**: Undo the last action.

### Drawing

- **Mouse Interaction**: Use your mouse to draw, fill, or select pixels on the canvas.
- **Touch Interaction**: For touch-enabled devices, use your finger to interact with the canvas.

### Saving and Loading

- **Save Button (💾)**: Click this button to save your artwork as a PNG file.
- **Load Button (📁)**: Click this button to load an existing image for editing.

### Undoing Changes
 
- **Undo Button (⮪)**: Click this button to undo the last action performed.

## Customization

You can customize the app by modifying the initial state, adding custom tools, or creating new controls according to your requirements.

## Credits

This Drawing App is created using JavaScript and HTML. It utilizes various techniques such as canvas drawing, event handling, and DOM manipulation.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Thank you for using the Drawing App! If you have any questions or feedback, please feel free to contact us. Happy drawing! 🎨
