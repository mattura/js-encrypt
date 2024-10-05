# js-encrypt
Encrypt / Decrypt using JS Web Crypto API functions

## Encrypt

1) Create a new key pair
2) Specify a password
3) The public key and password are both used to encrypt an AES key
4) The AES key is used to encrypt the JSON data
5) Transmit the encrypted data - it includes encrypted keys, salt, iv, and encrypted data

## Decrypt

1) Input the encrypted data - must include the above items
2) Use the password to decrypt
3) If the password is forgotten, use the private key to decrypt
