# Vigenere CTF Write Up

The challenge gives us the following information.

Key: "CYLAB" 
Message: "rgnoDVD{O0NU_WQ3_G1G3O3T3_A1AH3S_f85729e7}"

From the title of the challenge we can assume the encryption method of this ciphertext is the Vigenere cipher. The Vigenere Cipher can be decrypted
with the use of online decoding tool dcode. With the key decoding the ciphertext is as easy as plugging it into the tool. The vigenere cipher is also 
easy to decode with a known plaintext attack. Using the plaintext "picoCTF{" which is the format used for all flags, the vigenere cipher can be decoded
without having the key.


![[VigenereDcode.png]]
![[Vigenere-Known-Plaintext.png]]


picoCTF{D0NT_US3_V1G3N3R3_C1PH3R_d85729g7}
