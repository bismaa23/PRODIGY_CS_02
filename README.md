# Pixel Manipulation For Image Encryption Tool

This Python script (`PRODIGY_CS_02(Image encryption).py`) allows you to encrypt and decrypt images using pixel manipulation techniques.

## Requirements

- Python 3.x
- PIL (Python Imaging Library)

## How It Works

### Encryption Process:

1. **Running the Script:**
   - Start the script in a Python environment.

2. **Input Image Path:**
   - Provide the file path of the image you want to encrypt.

3. **Provide Encryption Key:**
   - Enter an integer key between 0 and 255. This key will modify the RGB values of each pixel in the image.

4. **Encryption Procedure:**
   - The script applies an XOR operation to each pixel's RGB values using the encryption key.
   - The resulting encrypted image is saved as `encrypted_image.png`.

### Decryption Process:

1. **Decryption Option:**
   - After encryption, you can choose to decrypt the image using the same encryption key.

2. **Enter Decryption Key:**
   - Input the same key used during encryption.

3. **Decryption Procedure:**
   - The script reverses the XOR operation on each pixel to restore the original RGB values.
   - The decrypted image is saved as `decrypted_image.png`.

## Usage

1. **Setup:**
   - Ensure Python is installed on your system.
   - Install the PIL library using `pip install pillow` if it's not already installed.

2. **Running the Script:**
   - Open a terminal or command prompt.
   - Navigate to the directory containing `PRODIGY_CS_02(Image encryption).py`.
   - Execute the script using `python PRODIGY_CS_02(Image encryption).py`.

## Example

Assume you have an image named `image.jpg` located in the same directory as your script. Here’s how you would encrypt and decrypt it:

```bash
python PRODIGY_CS_02(Image encryption).py

Enter the path to the image file: image.jpg
Enter an integer key between 0 and 255: 123
Image encrypted successfully. Encrypted image saved as: encrypted_image.png

Do you want to decrypt the image? (yes/no): yes
Enter the decryption key (same as encryption key): 123
Image decrypted successfully. Decrypted image saved as: decrypted_image.png

## Notes:

- **Image File Path:** Ensure the image file path provided is correct and accessible from the script's location.

- **Encryption Key:** Use an integer key between 0 and 255 for both encryption and decryption operations. Remember to use the same key for decryption that was used for encryption.

- **Output Images:** The script saves the encrypted and decrypted images as `encrypted_image.png` and `decrypted_image.png`, respectively, in the same directory as the script.



