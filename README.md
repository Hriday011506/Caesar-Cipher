# Caesar Cipher 🔐

A Python implementation of the classic Caesar Cipher — one of the oldest and simplest encryption techniques. This project allows users to encode and decode messages by shifting each letter of the alphabet by a custom number of positions. It also preserves numbers, symbols, and spaces, making the cipher output more practical and readable.

---

## 📁 Files in This Project

- `main.py`: The main script that handles user input and runs the Caesar Cipher.
- `solution.py`: An alternate or earlier version of the cipher logic.
- `art.py`: Contains an ASCII art logo that displays when the program starts.

---

## 💡 What is Caesar Cipher?

The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet. It was famously used by Julius Caesar to send private messages.

For example, with a shift of 3:
- A → D  
- B → E  
- C → F  
... and so on.

After 'Z', it wraps around to 'A'.

---

## 🔧 Features

- Encode (encrypt) and Decode (decrypt) messages
- Accepts user-defined shift value
- Handles both uppercase and lowercase letters
- Ignores and retains numbers, punctuation, and spaces (e.g., `Hello 123!` → `Khoor 123!`)
- Keeps running until the user decides to exit
- Displays ASCII art at startup

---

## ▶️ How to Run

1. Clone the repository or download the files.
2. Make sure Python 3 is installed on your system.
3. Open your terminal or command prompt.
4. Navigate to the project folder.
5. Run the program:
```bash
python main.py
