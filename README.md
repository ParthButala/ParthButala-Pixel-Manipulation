# ParthButala-Pixel-Manipulation
Overview:
This program performs basic image encryption and decryption by manipulating the color channels of each pixel. It achieves encryption by swapping the red and blue channels, effectively obscuring the image data. The process is fully reversible, allowing for decryption by restoring the original channel positions.

Key Features:
Image Encryption:
The program encrypts images by swapping the red and blue channels of each pixel, resulting in a visually altered image that hides the original data.

Image Decryption:
It decrypts the image by reversing the red-blue channel swap, ensuring the original image is fully restored without any data loss.

User Input:
Users provide the file path for the input image, the destination path for the encrypted or decrypted image, and an optional key (not yet implemented).
Requirements:
Python 3.x
Pillow library (pip install pillow)
How It Works:
Encryption:
The program reads the input image, swaps the red and blue channels of each pixel, and saves the modified image.

Decryption:
It restores the original image by swapping the red and blue channels back to their original positions.
