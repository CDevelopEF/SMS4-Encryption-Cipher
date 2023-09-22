# SMS4 Encryption Algorithm

This repository contains a C implementation of the SMS4 encryption algorithm. SMS4 is a widely used symmetric key block cipher algorithm in wireless networks.

## Usage

1. Clone the repository to your local machine.
2. Compile the code using a C compiler. For example, you can use GCC:
   ```sh
   gcc sms4.c -o sms4
./sms4

## Algorithm Details
The SMS4 encryption algorithm involves key expansion and encryption/decryption phases. It uses a master key and plain text to produce encrypted text.

## Key Expansion
The master key is expanded to generate a round key list.
Encryption/Decryption
The algorithm processes the input plain text and generates encrypted text.
For decryption, it can also be used to reverse the process and obtain the original plain text.
Example
The example provided in the code demonstrates the encryption and decryption of a sample plain text using the SMS4 algorithm with a predefined master key.

## References
[SMS4 Specification](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjdkLC-lL-BAxWBHuwKHTHcAXgQFnoECA0QAQ&url=https%3A%2F%2Feprint.iacr.org%2F2008%2F329.pdf&usg=AOvVaw3b9fIJEqxovXzax4mrcAOh&opi=89978449)
[SMS4 Algorithm](https://en.wikipedia.org/wiki/SMS4)
