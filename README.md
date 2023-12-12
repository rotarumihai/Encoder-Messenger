# Message Mixer Inc. Encryption Service

Message Mixer Inc. provides a message-encryption service that transforms input text using various ciphers. This service offers three encryption methods:

1. **Caesar Cipher:**
   - Characters of the input message are shifted alphabetically by a given amount.
   - To use: `node message-mixer.js caesar [amount]`

2. **Symbol Cipher:**
   - Select characters from the input message are replaced with visually similar symbols.
   - To use: `node message-mixer.js symbol`

3. **Reverse Cipher:**
   - Each word of the input message is reversed in place.
   - To use: `node message-mixer.js reverse`

## Usage

To encrypt a message, run the following command in the terminal:

```bash
node message-mixer.js [method] [amount]
   
