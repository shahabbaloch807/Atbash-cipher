Atbash Cipher

A simple Python implementation of the classical Atbash Cipher.

Description

The Atbash Cipher is a substitution cipher that reverses the alphabet:

· A ↔ Z, B ↔ Y, C ↔ X, and so on...
· The same function works for both encryption and decryption
· Preserves case (uppercase/lowercase)
· Keeps non-alphabetic characters unchanged (spaces, numbers, punctuation)

Features
· ✅ Handles both uppercase and lowercase
· ✅ Preserves spaces and special characters
· ✅ Same function for encryption and decryption

How It Works

· Uppercase letters: A(65) → Z(90), B(66) → Y(89), etc.
· Lowercase letters: a(97) → z(122), b(98) → y(121), etc.
· Non-letters: Remain unchanged

The cipher uses the formula: base + (25 - (ord(char) - base)) where base is 65 for uppercase and 97 for lowercase.
