# Random Color Generator

An interactive web application that allows users to generate and copy both HEX and RGB color codes. The project features two distinct color generators: a random HEX color generator and an RGB color generator with adjustable sliders.

## Features

### HEX Color Generator
- Generate random HEX color codes with a single click
- Display of the current HEX color value
- Copy HEX color code to clipboard
- Real-time background color update
- Visual feedback with button color changes

### RGB Color Generator
- Interactive sliders for Red, Green, and Blue values (0-255)
- Real-time RGB color code display
- Copy RGB color code to clipboard
- Dynamic background color updates
- Visual feedback with button color changes

## Project Structure

```
random-color-generator/
├── index.html
├── style.css
└── main.js
```

- **index.html**: Contains the HTML structure with containers for both color generators
- **style.css**: Handles the styling and layout of the application
- **main.js**: Implements the color generation and clipboard functionality

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)

## Usage

### HEX Color Generator
1. Click the "Create Hex Color" button to generate a random HEX color
2. Click "Copy To Clipboard" to copy the HEX color code
3. The background will update to display the generated color

### RGB Color Generator
1. Adjust the Red, Green, and Blue sliders to create your desired color
2. Click the "Create RGB Color" button to apply the color
3. Click "Copy To Clipboard" to copy the RGB color code
4. The background will update to display the selected color

## Styling

The application features a responsive design with:
- Split-screen layout for both color generators
- Minimum viewport height scaling
- Responsive padding and spacing
- Bold, easy-to-read color values
- Interactive buttons with hover states
