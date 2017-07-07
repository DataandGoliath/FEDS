# FEDS
FEDS (Short for Flexible Encryption of Data Stores) and is a tool for encrypting data in a secure method. 
It utilizes a Dual Key, Dictionary Lookup based method which can secure anything in the ASCII range. 
The key is based on 4 operators:
C[#] 
R
E
S[a,b] 
These, before a colon, comprise KeyA and generate the table. After the colon, KeyB is used and encrypts the data through the table.
The system is similiar in its core to a Vigenere cipher, however, it holds a few differences, most namely the flexible table. By shuffling the order of the letters, traditional decryption efforts for Vigenere are rendered ineffective.
Furthermore, the more spacious alphabet of FEDS allows for more versitile and secure encryption, by rendering the formatting illegible in the ciphertext rather than preserving it, as the original Vigenere would.
