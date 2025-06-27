🛡️ Caesar Cipher

  A simple Python implementation of the classic Caesar Cipher encryption technique. The program allows you to encode or decode messages by shifting letters in   the alphabet by a specified amount.

📜 How It Works

  This script uses a basic substitution cipher where each letter in the input message is shifted by a fixed number of positions in the alphabet.

  Encode: Shifts each letter forward in the alphabet.

  Decode: Shifts each letter backward in the alphabet.

  Non-alphabetic characters (e.g. numbers, symbols, spaces) are preserved as-is.

🧠 Features

  Encode and decode messages using Caesar Cipher logic.

  Handles inputs with symbols, numbers, or spaces.

  Looping feature lets you run the program multiple times without restarting manually.

  Includes an ASCII art logo (from art.py module).

▶️ Getting Started

  1. Clone the repository or copy the code into your local Python environment.

  2. Ensure you have an art.py file containing the ASCII logo (or comment out import art and the print(art.logo) line if not needed).

  3. Run the script:

  python caesar_cipher.py

  4. Follow the on-screen prompts to encode or decode your messages.

📌 Example

  Type 'encode' to encrypt, type 'decode' to decrypt:
  encode
  Type your message:
  hello world!
  Type the shift number:
  5
  Here is the encoded result: mjqqt btwqi!


🔁 Future Improvements (TODOs)
 
 Handle uppercase letters.

 Add GUI for better interaction.

 Integrate command-line arguments for non-interactive use.

 Include input validation for incorrect shift values or directions.

