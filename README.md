# QR Code Generator

A simple Python tool to generate QR codes from URLs and save them as images.

## Features
- Input any URL to generate a QR code.
- Saves QR code as an image (`.png`) to a specified folder.
- Works locally on Windows, Mac, or Linux.

## Screenshots
<img width="579" height="107" alt="image" src="https://github.com/user-attachments/assets/a0709c10-d276-477a-9a25-2cd922c6b64c" />
<img width="643" height="607" alt="image" src="https://github.com/user-attachments/assets/7fb0ccd2-3646-4e07-a6a3-1255d21e4646" />


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
