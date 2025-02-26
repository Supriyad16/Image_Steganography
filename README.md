# Secure Data Hiding in Image Using Steganography

The project is a GUI-based Image Steganography tool built using Python, Tkinter, and PIL (Pillow). It allows users to hide text inside images (encoding) and extract hidden text from images (decoding) using LSB (Least Significant Bit) Steganography.

# Features

📂 Select an image to encode or decode.

🔏 Hide a secret message inside an image.

🔓 Extract hidden text from an encoded image.

🎨 User-friendly GUI built with Tkinter.

# Requirements

    Python 3.x
    
    Pillow (PIL)
    
    Tkinter (built into Python by default)

To install dependencies, run: pip install pillow

# Steps

**Encoding (Hiding Text in an Image)**

    Click "Encode" in the GUI.
    
    Select an image file (.png, .jpg, .jpeg).
    
    Enter the secret message.
    
    Save the encoded image.
    
**Decoding (Extracting Hidden Text from an Image)**

    Click "Decode" in the GUI.
    
    Select an image with a hidden message.
    
    The extracted text will be displayed.
    

# Notes

    The tool works best with PNG images to avoid quality loss.
    
    Large messages may increase the file size significantly.
    
    Ensure the encoded image is saved properly to retrieve hidden data
    
# License

This project is open-source under the MIT License. See the LICENSE file for details.

# Author

👤 Supriya D
