## SecureSteg - Image Steganography System

SecureSteg is a Python-based desktop GUI application that lets you hide and extract secret messages within images using LSB (Least Significant Bit) technique. Designed with a clean and responsive interface, the tool helps users send covert messages securely without altering the image’s appearance.


## Overview

This project allows:
- Secret text embedding within images (encoding)
- Retrieving hidden messages from previously encoded images (decoding)

It uses **Tkinter** for the GUI and **Pillow (PIL)** for image processing.


## Features

- **Text Encoding**: Embed messages in PNG or JPEG images.
- **Message Decoding**: Retrieve hidden messages with a single click.
- **Interactive UI**: Simple and beginner-friendly interface.
- **Image Support**: Works best with PNG (lossless), but also supports JPG.
- **Modern Themes**: Styled with a subtle and neat color palette.


## Prerequisites

Make sure you have:

- Python **3.7 or later**
- Required libraries (install via pip):

```bash
pip install pillow

## How to Run

1. Launch the Application:
- python main.py

2. Encode a Message:
- Click "Choose Image" to load an image (PNG/JPG).
- Type your message in the provided input.
- Click "Encode Message" and save the output image.

3. Decode a Message:
- Load the encoded image using "Choose Image".
- Click "Decode Message" to reveal the secret message.


## Best Practices

- Prefer PNG format for accuracy and message preservation.
- Keep messages short — image space is limited.
- Do not use highly compressed formats (like WebP or heavily optimized JPGs).

## Project Structure

├── main.py                # Application script
├── README.md              # Project documentation
- Tkinter: Used for GUI
- Pillow (PIL): Used for encoding/decoding within image pixels

## Screenshots
![Main Interface]("C:\Users\Dell\Desktop\Image Steganography\Image-Steganography\Screenshot (4622).png")


## Acknowledgements
This project was developed as a part of cybersecurity exploration. The project aims to raise awareness about secure communication using modern steganography techniques.

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
