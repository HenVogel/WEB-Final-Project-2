# Caesar Cipher - Encrypt/Decrypt Web Application

This project implements a simple Caesar Cipher web application that allows users to encrypt and decrypt messages using the Caesar Cipher algorithm. The Caesar Cipher is a substitution cipher where each letter in the plaintext is replaced by a letter some fixed number of positions down or up the alphabet.

## Features

- **Encrypt a Message**: Shift letters to the right (encrypt the message).
- **Decrypt a Message**: Shift letters to the left (decrypt the message).
- **Customizable Shift**: Choose a shift number between 0 and 25.
- **Message Input**: Enter any string of text (including spaces and punctuation).
- **Dynamic Result**: The result (encrypted or decrypted message) is displayed instantly when you click the button.

## How It Works

1. **User Input**: 
    - The user enters a message they want to encrypt or decrypt.
    - The user specifies a shift number (between 0 and 25).
    - The user selects the shift direction (right for encryption, left for decryption).
    
2. **Processing**:
    - The application processes each character in the message.
    - Letters are shifted based on the selected direction and shift value.
    - Non-letter characters (such as spaces and punctuation) are not modified.
    
3. **Result**:
    - The encrypted or decrypted message is displayed immediately on the page.

## Files

- **index.html**: The main HTML file that contains the structure of the page and embedded JavaScript code for cipher logic.
- **styles.css** (optional): CSS for page styling (if you wish to separate the styles into a different file).

## Usage

1. Open `index.html` in your browser to access the Caesar Cipher web application.
2. Enter your message in the "Enter your message" field.
3. Specify the number of shifts in the "Shift Number" field (valid values are between 0 and 25).
4. Select the direction of the shift from the "Shift Direction" dropdown:
   - **Right (Encrypt)**: Use this option to encrypt the message.
   - **Left (Decrypt)**: Use this option to decrypt the message.
5. Click the "Encrypt/Decrypt" button to see the result immediately below the button.

## Example

### Encrypting a Message:
- **Message**: `Hello, World!`
- **Shift Number**: `3`
- **Shift Direction**: `Right (Encrypt)`
- **Result**: `KHOOR, ZRUOG!`

### Decrypting a Message:
- **Message**: `KHOOR, ZRUOG!`
- **Shift Number**: `3`
- **Shift Direction**: `Left (Decrypt)`
- **Result**: `HELLO, WORLD!`

## Technologies Used

- **HTML**: For the structure and layout of the page.
- **CSS**: For basic styling and layout of the page.
- **JavaScript**: For implementing the Caesar Cipher logic and handling user input dynamically.

## Author
- Henry Vogel
