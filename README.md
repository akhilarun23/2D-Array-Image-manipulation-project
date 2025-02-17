#2D Arrays: Image Manipulation Project
  # Image Processing with 2D Arrays

## Overview
This project is a Java-based application that allows users to modify images and create new ones using 2D arrays. The project is divided into two sections:

1. **Image Transformations**
   - Stretching the image horizontally
   - Shrinking the image vertically
   - Negating colors
   - Applying color filters
   - Inverting the image

2. **Image Creation and Manipulation**
   - Generating an image with random pixels
   - Placing a rectangle in the image
   - Randomly placing multiple rectangles

## How Images Work in Java
Images consist of **pixels**, which are individual points containing color information. Each pixel has four components:
- **Red (R)**
- **Green (G)**
- **Blue (B)**
- **Alpha (A)** (transparency level)

Each component has a value between **0 and 255**. In Java, images are handled using the `BufferedImage` class, where each pixel is represented as an integer storing its RGBA values in hexadecimal format.

## Implementation Details
This project involves extracting pixel values from a `BufferedImage` and storing them in a **2D array** for manipulation. Provided utility methods handle:
- **Converting images to 2D arrays and vice versa**
- **Extracting RGBA values from pixel integers**

Your task is to implement functions that modify the 2D array to achieve the desired image transformations.

## Getting Started
### Prerequisites
- Java Development Kit (JDK 8 or later)
- An IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)

### Clone the Repository
```sh
git clone https://github.com/yourusername/image-processing-java.git
cd image-processing-java
```

### Run the Project
Compile and run the Java program using:
```sh
javac Main.java
java Main
```

## Features
### Image Transformations
- **Stretch Horizontally**: Doubles the width of the image while maintaining proportions.
- **Shrink Vertically**: Reduces the height by half.
- **Negate Colors**: Inverts the RGB values of each pixel.
- **Apply Color Filter**: Applies a selected color filter (e.g., red, green, blue).
- **Invert Image**: Creates a mirrored version of the original image.

### Image Creation
- **Random Pixels**: Generates an image filled with randomly colored pixels.
- **Rectangle Placement**: Adds a rectangle to the image at a specified location.
- **Multiple Rectangles**: Randomly places several rectangles throughout the image.

## Contribution
Feel free to contribute by submitting a pull request! If you find a bug or have a suggestion, open an issue.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

