# CSS Animated Loader

A visually engaging CSS-based animated loader that features rotating dots with glowing effects. This loader is created using only HTML and CSS, making it lightweight and easy to integrate into any project.

## Demo

![image](https://github.com/user-attachments/assets/9ee0df8d-900d-4e00-bc72-980380136af0)


## Features

- **Pure CSS Animation**: No JavaScript required.
- **Background Animation**: The background continuously changes hue to create a dynamic effect.
- **Loader with Rotating Dots**: Multiple dots rotate around a central point, with glowing effects.
- **Responsive Design**: The loader is centered both vertically and horizontally, making it perfect for loading screens on different devices.

## Technologies Used

- **HTML**
- **CSS**
  - Flexbox for centering the loader
  - Keyframe animations for both the loader and the background

## Getting Started

To get started with this animated loader, follow the steps below.

### Prerequisites

You'll need a code editor and a basic understanding of HTML and CSS.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/css-animated-loader.git

How It Works

    Background Animation: The background color changes using the hue-rotate CSS filter, giving it a dynamic look.

    css

@keyframes animatebg {
    0% {
        filter: hue-rotate(0deg);
    }
    100% {
        filter: hue-rotate(360deg);
    }
}

Loader Animation: The loader consists of multiple span elements, each representing a dot. These dots rotate and shrink using the scale and rotate properties, creating the loading effect.

css

section .loader span::before {
    animation: animate 2s linear infinite;
}

Glow Effect: Each dot has a glowing effect created using the box-shadow property.

css

    box-shadow: 0 0 10px #00ff0a, 0 0 20px #00ff0a, 0 0 40px #00ff0a;

Customization

You can easily customize the loader by modifying the following:

    Dot Color: Change the color in the background and box-shadow properties.
    Animation Speed: Adjust the animation-duration values for both the dots and the background.
    Number of Dots: Add or remove span elements in the HTML to change the number of rotating dots.

Contributing

Feel free to fork this project and submit pull requests for new features or improvements. All contributions are welcome!
License

This project is open source and available under the MIT License. 


Make sure to adjust the URL for cloning and include any specific demo images or additional customization details you might want to add.
