

# Pixel Manipulation for Image Encryption
This project is an advanced tool for encrypting and decrypting images using pixel manipulation techniques. Users can choose between different encryption algorithms and provide custom keys for securing their images. The tool is implemented in Python and utilizes the Pillow library for image processing.

# Features
-->Multiple Encryption Algorithms: Choose between XOR-based encryption and key addition-based encryption.

-->Command-line Interface: User-friendly interface for specifying input/output file paths, keys, and encryption algorithms.

-->Progress Indication: Real-time progress bar to show the status of encryption/decryption for large images.

-->Error Handling: Detailed error messages and validation for file paths and types.

-->Cross-Platform: Works on any platform with Python support.

#Installation

Clone the repository:

git clone https://github.com/yourusername/pixel-manipulation-encryption.git
cd pixel-manipulation-encryption
Install the required libraries:
pip install pillow tqdm

# Usage
The tool can be used from the command line. Below are examples of how to encrypt and decrypt an image:
Encrypt an Image
python pixel_manipulation.py encrypt <input_image_path> <output_image_path> <key> --algorithm <algorithm>

Example:
python pixel_manipulation.py encrypt images/input.jpg images/encrypted.jpg 50 --algorithm xor

Decrypt an Image
python pixel_manipulation.py decrypt <input_image_path> <output_image_path> <key> --algorithm <algorithm>
Example:
python pixel_manipulation.py decrypt images/encrypted.jpg images/decrypted.jpg 50 --algorithm xor


Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

