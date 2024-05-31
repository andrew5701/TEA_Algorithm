# Tiny Encryption Algorithm (Java Implementation)

This repository contains a Java implementation of the Tiny Encryption Algorithm (TEA). TEA is a block cipher known for its simplicity of description and implementation, typically operating on 64-bit blocks of plaintext.

## Files

- `TeaAlgorithm.java`: The main class implementing the TEA encryption and decryption methods.
- `HexMethods.java`: Utility methods for handling hexadecimal conversions.

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/andrew5701/tiny-encyrption-algorithm-java.git
    ```
2. Compile the Java files:
    ```bash
    javac TeaAlgorithm.java HexMethods.java
    ```
3. Run the TEA encryption/decryption:
    ```bash
    java TeaAlgorithm
    ```

## Functionality

- Takes a 64-bit block of plaintext and performs a round function 32 times to generate ciphertext.
- The plaintext is decrypted using the inverse of the round function.
- Includes methods for key generation and conversion between hexadecimal and binary.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This implementation is based on the TEA algorithm description by David Wheeler and Roger Needham.
