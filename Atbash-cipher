atbash_cipher(text):
    result = ""
    for char in text:
        if char.isalpha():
            if char.isupper():
                result += chr(65 + (25 - (ord(char) - 65)))  # A-Z
            else:
                result += chr(97 + (25 - (ord(char) - 97)))  # a-z
        else:
            result += char  # Keep non-letters unchanged
    return result

User input
text = input("Enter text to encrypt/decrypt: ")
output = atbash_cipher(text)

print("Output:", output)

