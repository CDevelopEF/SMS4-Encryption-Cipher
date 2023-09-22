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

## Output Example
```
Key List:
rki = f12186f9
rki = 41662b61
rki = 5a6ab19a
rki = 7ba92077
rki = 367360f4
rki = 776a0c61
rki = b6bb89b3
rki = 24763151
rki = a520307c
rki = b7584dbd
rki = c30753ed
rki = 7ee55b57
rki = 6988608c
rki = 30d895b7
rki = 44ba14af
rki = 104495a1
rki = d120b428
rki = 73b55fa3
rki = cc874966
rki = 92244439
rki = e89e641f
rki = 98ca015a
rki = c7159060
rki = 99e1fd2e
rki = b79bd80c
rki = 1d2115b0
rki = 0e228aeb
rki = f1780c81
rki = 428d3654
rki = 62293496
rki = 01cf72e5
rki = 9124a012
--- Plain Text ---
Y[0] = 01234567
Y[1] = 89abcdef
Y[2] = fedcba98
Y[3] = 76543210
--- Encrypted Text ---
Y[0] = 681edf34
Y[1] = d206965e
Y[2] = 86b3e94f
Y[3] = 536e4246
--- Decrypt Text ---
Y[0] = 01234567
Y[1] = 89abcdef
Y[2] = fedcba98
Y[3] = 76543210
