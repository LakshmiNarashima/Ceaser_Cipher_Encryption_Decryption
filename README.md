# PRODIGY_CS_01

# Caesar Cipher Encryption/Decryption

## Description
This program implements the Caesar Cipher, a simple encryption technique that shifts the letters of a message by a specified number of positions in the alphabet. It allows users to either encrypt or decrypt messages.

## Features
- Encrypt messages using a specified shift value.
- Decrypt messages that were previously encrypted with the same shift value.
- Supports both uppercase and lowercase letters while leaving non-alphabetic characters unchanged.

## Requirements
- A C++ compiler (e.g., g++, clang++)
- Standard C++ libraries

## How to Compile
1. Save the code in a file named `caesar_cipher.cpp`.
2. Open a terminal and navigate to the directory where the file is saved.
3. Compile the program using the following command:
   ```
   g++ caesar_cipher.cpp -o caesar_cipher
   ```

## How to Run
After compiling, you can run the program with:
```
./caesar_cipher
```

## Usage
1. The program will prompt you to choose whether to encrypt or decrypt a message. Enter `E` for encryption or `D` for decryption.
2. Enter the message you want to process.
3. Enter the shift value (an integer). For example, a shift of `3` means each letter will be moved three positions forward in the alphabet.
4. The program will output the encrypted or decrypted message based on your choice.

## Example
### Encrypting
```
Would you like to (E)ncrypt or (D)ecrypt? E
Enter the message: Hello, World!
Enter the shift value: 3
Encrypted Message: Khoor, Zruog!
```

### Decrypting
```
Would you like to (E)ncrypt or (D)ecrypt? D
Enter the message: Khoor, Zruog!
Enter the shift value: 3
Decrypted Message: Hello, World!
```

## Limitations
- The program does not handle negative shift values in a special way; it simply shifts letters backwards.
- Non-alphabetical characters are not modified.

## License
This project is open-source and available for personal or educational use.

