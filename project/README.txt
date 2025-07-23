////////////////////////////// Tiny Encryption Algorithm (TEA) //////////////////////////////

This read-me file provides a detailed guide on how to execute the TEA (Tiny Encryption Algorithm) encryption/decryption program for image files.

1. Adding the Needed Files to Run the Program
Programming Language: The program is written in Python, so you can use VS Code or any other Python3 compatible Integrated Development Environment (IDE).
File Setup:
Using VS Code, open the folder where you want to add all the files via the file explorer.
Add the TEAcryptoooo.py file along with any image you prefer (e.g., Aqsa.bmp).

/////////////////////////////////////////////////////////////////////////////////////////////
2. Running the Code
Opening the Terminal:

In VS Code, open a new terminal window by navigating to Terminal > New Terminal.
Executing the Program:

Run the following command in the terminal to start the program:
my code 

python TEAcryptoooo.py
////////////////////////////////////////////////////////////////////////////////////////// 
3. Interacting with the Program
Key Input
Prompt: The program will prompt you to enter a key.
Format: The key should be a 32-hexadecimal string.
Example: 1234123456785678abcdabcdefefefef
Validation: The key should be entered in string format. The program will validate the length and format of the key and will prompt you to re-enter it if it's incorrect.
Initializing Vector (IV) for CBC Mode
Prompt: If you select CBC mode, the program will prompt you to enter an IV (Initialization Vector).
Format: The IV should be a 16-hexadecimal string.
Example: 1122334455667788
Validation: The IV should be entered in string format. The program will validate the length and format of the IV and will prompt you to re-enter it if it's incorrect.
Image Path
Prompt: The program will ask you to enter the file path for the image you want to encrypt and decrypt.
Format:
If the image is within the directory where the script is located, simply enter the image file name along with the file type.
Example: Aqsa.bmp
If the image is in another location, provide the full path to the image file.
Example: "C:\Users\odysh\Downloads\Aqsa.bmp"

////////////////////////////////////////////////////////////////////////////////////////////
4. Expected Output
Encryption and Decryption:

The program will encrypt the provided image and save the encrypted image.
The program will then decrypt the encrypted image and save the decrypted image.
Output Files:

ECB Mode:
Encrypted image file: ecb_encrypted_image.png
Decrypted image file: ecb_decrypted_image.png
CBC Mode:
Encrypted image file: cbc_encrypted_image.png
Decrypted image file: cbc_decrypted_image.png
Location: The encrypted and decrypted images will be saved in the same directory as the script, or you can specify a different path if required.
/////////////////////////////////////////////////////////////////////////////////////////////

Summary
By following this guide, you will be able to:

Set up and add the necessary files to your project directory.
Run the TEA encryption/decryption program using a Python-compatible IDE.
Interact with the program to provide keys, IVs, and image paths.
Obtain encrypted and decrypted images using the TEA algorithm in either ECB or CBC modes.
Ensure that you provide the correct format for keys, IVs, and image paths to avoid validation errors.
The program will help you secure your images with encryption and allow you to verify the results by decrypting the images.






