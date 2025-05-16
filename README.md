# QR Code Generator

This is a simple Node.js command-line application that generates a QR code from a user-provided URL. It uses the `qr-image` package to create the QR code and `inquirer` for interactive CLI input. The entered URL is also saved to a text file.

## Features

- Prompts the user to enter a URL.
- Generates a QR code image (`qr_img.png`) from the URL.
- Saves the URL in a text file (`URL.txt`).

## Prerequisites

Ensure that [Node.js](https://nodejs.org/) is installed on your machine.

## Installation

1. Clone this repository or download the project files.

2. Open a terminal in the project directory.

3. Install the required packages:

```bash
npm install inquirer qr-image
```

## Usage

To run the project:

```bash
node index.js
```

1. You'll be prompted to enter a URL.
2. After entering the URL:
   - A QR code image will be generated and saved as `qr_img.png`.
   - The URL will also be saved in a file named `URL.txt`.

## Example

```bash
$ node index.js
? Type in your URL: https://example.com
The file has been saved!
```

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): For command-line prompts.
- [qr-image](https://www.npmjs.com/package/qr-image): To generate QR code images.
- Node's built-in `fs` module: To handle file writing.

## License

This project is open source and available under the [MIT License](LICENSE).
