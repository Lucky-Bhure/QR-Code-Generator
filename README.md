#QR Code Generator
<hr>

QR Code Generator project utilizes Node.js and several npm packages to create a simple command-line application that prompts the user to input a URL. It then generates a QR code image based on the provided URL and saves both the URL and the QR code image to separate files.

Here's a breakdown of the project components:

1. **Inquirer npm package**: This package is used to interactively prompt the user for input. In this case, it prompts the user to type in a URL.

2. **qr-image npm package**: This package is used to generate QR code images based on the user-provided URL. The URL is encoded into a QR code image, which can be saved as a file.

3. **Native fs module**: The built-in `fs` module in Node.js is used to interact with the file system. It's used here to write the URL to a text file (`URL.txt`) and to save the generated QR code image as a PNG file (`qr_img.png`).

4. **Promises and Error Handling**: Promises are used to handle asynchronous operations such as reading user input and writing files. Error handling is implemented to catch and handle any potential errors that may occur during file operations.
