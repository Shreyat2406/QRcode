# QR Code Generator

A simple Python tool to generate QR codes from URLs and save them as images.

## Features
- Input any URL to generate a QR code.
- Saves QR code as an image (`.png`) to a specified folder.
- Works locally on Windows, Mac, or Linux.

## Screenshots
![QR Code Example](qrcode.png)

## Tech Stack
- Python 3.x
- [qrcode](https://pypi.org/project/qrcode/)
- [Pillow](https://pypi.org/project/Pillow/) (for image handling)

## Setup & Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/qrcode-generator.git
   cd qrcode-generator
   
2. **Install dependencies**
pip install qrcode[pil]
Run the script
python qr_generator.py

3. **Enter a URL when prompted, and the QR code will be saved to your Desktop (or the path defined in file_path).**
