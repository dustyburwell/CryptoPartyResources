# Definitions Cheat Sheet

##### Encrypt
To obscure information (some text, a file, an image, etc) such that anyone looking at it would be unable to distinguish it from random bits.

##### Decrypt
To convert encrypted information back into its original form.

##### Cipher
An algorithm for encrypting and decrypting information.

##### Key
A random, often secret, set of bits that a cipher uses as part of its algorithm to encrypt information.

Keys allow us to all use the same encryption algorithm while getting different results.

##### Public and Private Key
A type of encryption that uses a public, shared, key and an private, unshared, key.

Anyone with the public key can encrypt a message that only the person with the private key can decrypt.

##### Signing - With Public and Private Keys
To use a private key to create a signature that can be verified with the corresponding public key.

##### Hashing
To convert information into an irreversible, but reliable, obscured form, otherwise known as a hash. Hashing the same information will result in the same hash value every time.

For example, passwords should be hashed before being stored in a database. This makes them safer should the database be hacked. We can also use hashes to ensure that a file we retrieved from the Internet hasn’t been modified from the author’s original.

##### TNO - Trust No One
A security philosophy in which you trust no person or company to control keys for decryption except for yourself.

No sensitive information should leave your computer unless it’s encrypted first. This level of security is typically acheived using systems that are end-to-end encrypted.
