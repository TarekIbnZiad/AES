# AES
Implementing the AES encryption/decryption algorithms using C++ as a part of CSE432: Computer Security undergarduate course in Computer and Systems Engineering Department, Faculty of Engineering, ASU. 

Plain text and key is read from .txt files and they are in hexadecimal format. Every file contains 16 byte, bytes are separated by spaces.

The project will be run through cmd as follows: 

> AES.exe encrypt plaintext.txt key.txt newciphertext.txt

> AES.exe decrypt newciphertext.txt key.txt newplaintext.txt
 
Where:

1 - AES.exe :- The executable file 

2 - encrypt:- The encryption function

3 - decrypt:- The decryption function

4 - plaintext.txt:- The original plaintext file

5 - key.txt:- The key file 

6 - newciphertext.txt:- The output file from encryption 

7 - newplaintext.txt:- The output file from decryption 
