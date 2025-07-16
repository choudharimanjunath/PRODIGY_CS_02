🖼️ Image Encryption & Decryption Tool
This is a simple Python-based tool that allows users to encrypt and decrypt images by manipulating pixel values. 
The encryption is done using a basic key-based mathematical operation applied to each pixel's RGB values.

🔐 Features
Encrypts images by shifting RGB values with a user-provided key.
Decrypts encrypted images using the same key.
Supports both RGB and RGBA (transparency) images.
Displays the original, encrypted, and decrypted images for visual comparison.
CLI-based interaction; lightweight and easy to use.

⚙️ How It Works
Each pixel's RGB components are modified using:

Encrypted = (Original + Key) % 256
Decrypted = (Encrypted - Key) % 256
The alpha channel (transparency) is preserved during processing.

🛠 Requirements
Python 3.x
Pillow library: pip install pillow
