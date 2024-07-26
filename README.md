To create an image encryption and decryption program, we start by importing the PIL and NumPy libraries for image processing and mathematical operations.
The `encrypt_image` function opens an image, converts it to a NumPy array, shifts each pixel's value by a specified key, wraps the values using modulo 256, and saves the encrypted image. 
The `decrypt_image` function does the reverse, subtracting the key from each pixel value to restore the original image.
The `main` function handles user interaction. It prompts the user to choose encryption or decryption, then asks for the image path, output directory, and key. 
Based on the user's choice, it calls the appropriate function (`encrypt_image` or `decrypt_image`). Invalid choices result in an error message. 
The `main` function is executed when the script runs, facilitating user interaction and image processing. This program offers a simple method to encrypt and decrypt images using a key-based technique.
