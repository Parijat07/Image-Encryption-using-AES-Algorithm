This project aims to encrypt an image using the AES (Advanced Encryption Standard) algorithm to ensure secure transmission. AES is a symmetric encryption algorithm that employs a single key for both encryption and decryption. Unlike RSA, AES does not involve generating separate public and private keys. Instead, a secure key is chosen for encryption, and the same key is used for decryption.

The AES algorithm operates on blocks of data, typically 128 bits (16 bytes) in size. In this project, the image is divided into blocks, and each block is encrypted individually using AES with the chosen key. This process ensures that the encrypted image can only be decrypted using the same key.

By utilizing AES encryption, the image is effectively protected during transmission, preventing unauthorized access to its contents. AES is known for its strong security properties and is widely used in various applications where data confidentiality is paramount.


CLI modes for running the program:
1. For Encryotion
python imcrypt.py aes_en -i sq.png -p "smile"

2. For Decryption
python imcrypt.py aes_de -i sq.png -p "smile"
