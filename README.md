# SecureSteg - Image Steganography System

SecureSteg is a Python-based desktop GUI application that lets you hide and extract secret messages within images using the **LSB (Least Significant Bit)** technique. Designed with a clean and responsive interface, the tool helps users send covert messages securely without altering the image’s appearance.

---

##  Overview

This project allows:
- Secret text embedding within images (encoding)
- Retrieving hidden messages from previously encoded images (decoding)

It uses **Tkinter** for the GUI and **Pillow (PIL)** for image processing.

---

##  Features

- **Text Encoding**: Embed messages in PNG or JPEG images.
- **Message Decoding**: Retrieve hidden messages with a single click.
- **Interactive UI**: Simple and beginner-friendly interface.
- **Image Support**: Works best with PNG (lossless), but also supports JPG.
- **Modern Themes**: Styled with a subtle and neat color palette.

---

##  Prerequisites

Make sure you have:

- Python **3.7 or later**
- Required libraries (install via pip):

```bash
pip install pillow
```

---

##  How to Run the Application

Follow these simple steps to get started with SecureSteg:

###  1. Launch the Application
Open your terminal or command prompt and run:

```bash
python main.py
```

###  2. Encode a Message
- Click **“Choose Image”** to load a PNG or JPG image.
- Type your **secret message** into the input field.
- Click **“Encode Message”** and save the encoded image to your system.

###  3. Decode a Message
- Load the **encoded image** using **“Choose Image”**.
- Click **“Decode Message”** to reveal and read the hidden message.

---

###  Tips for Best Results
-  Prefer **PNG format** for better accuracy (it's lossless).
-  Keep messages **short**, since embedding capacity is limited.
-  Avoid **compressed formats** like WebP or overly optimized JPGs.

---

##  Project Structure

```
main.py            # Application script
README.md          # Project documentation

Dependencies:
- Tkinter          # Used for GUI
- Pillow (PIL)     # Used for encoding/decoding within image pixels
```

---

##  Screenshots

### Main Interface
![image alt](https://github.com/TaniaTabassum-22/Image-Steganography/blob/main/Home_Page.png?raw=true)

---

##  Acknowledgements

This project was developed as a part of cybersecurity exploration. The project aims to raise awareness about secure communication using modern steganography techniques.

---

##  License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
