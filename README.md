# Cryptic v4.0 💖
Cryptic is a cryptography project  that encrypts and decrypts your files of all extensions (txt, js, png...) in AES-256 CBC Mode. Cryptic works with a password chosen by the user and with an initialization vector (IV) generated by the program.

# Use 💻
## Installation
```bash
git clone https://github.com/deo7/Cryptic.git
cd Cryptic
pip install -r requirements.txt
```

## Run
Windows :
```
python Cryptic.py [-h] [-e] [-d] [-i] [-c]
```

Linux :
```
python3 Cryptic.py [-h] [-e] [-d] [-i] [-c]
```


The program creates a file 'AES_IV.txt' containing the initialization vector (IV) used for the AES encryption of THIS file (and only this file, a file encryption -> a new IV generated). The IV is a 128 byte block uses by AES-256 CBC Mode for encryption.<br />
AES_IV.txt file :


- WARNING : If you decrypt your file with an incorrect password / IV, you will get errors and incorrect decryption.


To conclude, here is a table that resume the encryption and the decryption of 'test.txt' :

| Original file content | Encrypted file content (with my password and my IV) | Decrypted file content |
| :---                  |     :---:                                           |                   ---: |
| Hello world !         | ßCï‰€å2µÄ£ËÅPð                                    | Hello world !          |

# Other 📚
<p align="center">
  <img src="https://img.shields.io/github/stars/deo7/Cryptic?style=for-the-badge&color=yellow">
  <img src="https://img.shields.io/badge/Version-4-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/deo7/Cryptic?style=for-the-badge&color=red"><br />
  <img src="https://img.shields.io/badge/Author-Déodorant%237144-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/Written%20In-Python-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Lines of codes-277-brown?style=for-the-badge">
</p>