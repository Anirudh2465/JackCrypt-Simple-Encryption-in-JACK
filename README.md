# ***🔐 JACK XOR Encryption***

A simple yet intriguing encryption project developed in the JACK language, demonstrating XOR-based encryption and decryption. The project showcases basic cryptographic principles with a custom key generator, message encryption, and decryption using XOR bitwise operations!

## **🌟 Features**


  Random Key Generation: Uses a custom pseudorandom number generator for creating unique encryption keys.
  
  XOR Encryption and Decryption: Encrypt and decrypt a message with a randomly generated key, ensuring basic message security.
  
  JACK Language Implementation: Utilizes JACK for core functionality, ideal for projects in the Nand2Tetris course.



## **📂 Project Structure**


  Main.jack: Core encryption/decryption functions with a pseudorandom generator.

  Random.jack: Contains the pseudorandom number generator using linear congruential generation.



## **🔑 Core Functions**


generateKey(message): Generates a random key based on message length.

xor1(message, key): XORs each character of the message with the key.

encrypt(message, key): Calls xor1() for encryption.

decrypt(ciphertext, key): Calls xor1() for decryption, reversing the process.
