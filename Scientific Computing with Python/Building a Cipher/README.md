# 🔐 Vigenère Cipher Encryption & Decryption Tool 🛠️

This Python script demonstrates the **Vigenère Cipher**, a classic encryption technique that uses a keyword to encode or decode a message. The script includes functions for both **encryption** and **decryption**. ✨


## 📋 How It Works

1. **Input Message**: Provide the text you want to encrypt or decrypt.
2. **Custom Key**: Use a custom key (e.g., `'python'`) to encode or decode the message.
3. **Encryption**: The `encrypt` function transforms plain text into cipher text.
4. **Decryption**: The `decrypt` function reverses the process to retrieve the original message.


## 🌟 Key Features

- 🔑 **Custom Key Support**: Use any keyword for encryption/decryption.
- 🔤 **Handles Non-Letter Characters**: Ignores spaces, punctuation, and special characters.
- 🔄 **Bidirectional**: Encrypts and decrypts messages seamlessly.
- 📚 **Modular Code**: Easy-to-read functions for reuse in other projects.



## 🚀 Example Output

```plaintext
Encrypted text: mrttaqrhknsw ih puggrur
Key: python

Decrypted text: meet me at the park
```
## 🛠️ Code Breakdown

1.  **Vigenère Function** :
    
    *   Handles both encryption (`direction=1`) and decryption (`direction=-1`).
    *   Iterates through each character of the message and applies the Vigenère algorithm.
2.  **Encrypt & Decrypt Functions** :
    
    *   Wrapper functions for simplicity.


## 🌍 Try It Yourself!

1.  Clone this repository.
2.  Run the script in your Python environment.
3.  Experiment with different messages and keys to see how the cipher works! 🧪



Happy Coding! ✨💻  
Decrypt secrets and explore the power of cryptography with this simple yet powerful tool! 🔑🔍