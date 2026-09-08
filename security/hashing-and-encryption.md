# Encryption

- The process of converting readable text to ciphertext using an algorithm and a key.
- text -> encryption -> ciphertext

# Decryption

- The process of converting the ciphertext back to readable text.
- ciphertext -> decryption -> text

# Hashing

- Process of converting data into a fixed-size value.

\*\* Note - Encryption is reversible if you possess the key and hashing is not reversible

# Salt

- random data added to the hashing data to make it unique per user

- we do not use fast hashing like SHA-256 because it makes brute force faster so we use slow algorithms like bcrypt, scrypt, argon2

- Without a salt, if two users have the exact same password (like Password123), they will have the exact same hash value. Hackers use pre-computed tables of hashes (called rainbow tables) to crack these common passwords instantly.
