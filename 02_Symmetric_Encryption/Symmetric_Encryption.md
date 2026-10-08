# Symmetric Encryption

## 1. Introduction

Encryption is used to protect data by converting readable information into an unreadable form.

The original data is called plaintext, and the encrypted data is called ciphertext.

A key is used during the encryption and decryption process.

## 2. What is Symmetric Encryption?

Symmetric encryption is a type of encryption that uses the same key for both encryption and decryption.

The basic process is:

Plaintext → Encryption + Key → Ciphertext

Ciphertext → Decryption + Same Key → Plaintext

The sender and receiver must both have the same secret key.

## 3. Main Challenge

The main challenge with symmetric encryption is key distribution.

The key must be shared securely between the sender and receiver. If an attacker gets the key, they may be able to decrypt the protected data.

## 4. AES

AES stands for Advanced Encryption Standard.

It is a widely used symmetric encryption algorithm.

AES supports key sizes of:

- 128 bits
- 192 bits
- 256 bits

For example, AES-256 uses a 256-bit key.

## 5. Example

A simple example of symmetric encryption is:

Message → Encrypt with secret key → Encrypted data

Encrypted data → Decrypt with the same secret key → Original message

The important point is that the same secret key is used on both sides.

## 6. Security Importance

Symmetric encryption can help protect the confidentiality of sensitive information.

It is commonly used to protect data when the communicating parties can securely establish or exchange a secret key.