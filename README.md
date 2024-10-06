# Text Cipher Project

Welcome to the **Text Cipher Project**! This fun and interactive tool allows you to encrypt and decrypt messages using the classic Caesar cipher method. Just input your message and shift number, and let the magic happen!

## 🎮 Overview

In this project, you can:
- Encrypt text by shifting letters a specified number of places down the alphabet.
- Decrypt text by reversing the shift.
- Handle symbols, spaces, and numbers seamlessly.

## 📂 Project Structure

To run the project smoothly, please ensure all files are stored in a single folder. Here’s how the project is structured:

```
/TextCipher
│
├── caesarcipher.py   # The main cipher logic.
└── art.py             # Contains the ASCII art logo.
```

## 📄 Files Description

### 1. `caesarcipher.py`
This file contains the main logic for encoding and decoding messages using the Caesar cipher. It includes user interaction to input text and shift values.

### 2. `art.py`
This file holds the ASCII art used to create a visually appealing logo for the project.

## 🛠️ How to Run the Project

1. **Download the Project Files**:
   - Create a folder called `TextCipher`.
   - Place `caesarcipher.py` and `art.py` inside this folder.

2. **Run the Project**:
   - Open your terminal or command prompt.
   - Navigate to the `TextCipher` directory.
   - Run the command:
     ```bash
     python caesarcipher.py
     ```

## 🔍 Sample Output

Here’s a glimpse of how the project works:

```
  ,adPPYba, ,adPPYYba,  ,adPPYba, ,adPPYba, ,adPPYYba, 8b,dPPYba,  
a8"     "" ""     `Y8 a8P_____88 I8[    "" ""     `Y8 88P'   "Y8  
8b         ,adPPPPP88 8PP"""""""  `"Y8ba,  ,adPPPPP88 88          
"8a,   ,aa 88,    ,88 "8b,   ,aa aa    ]8I 88,    ,88 88          
 `"Ybbd8"' `"8bbdP"Y8  `"Ybbd8"' `"YbbdP"' `"8bbdP"Y8 88   

Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
3
Here is the encoded result: khoor zruog
Type 'yes' if you want to go again. Otherwise type 'no':
no
Good Bye
```

## 🎉 Fun Fact

Did you know that the Caesar cipher is named after Julius Caesar, who is said to have used this method to communicate with his generals? It’s one of the simplest and most well-known encryption techniques. While it's not secure by modern standards, it’s a great starting point for learning about cryptography!

---

Happy encoding and decoding the fun messages in your group chat! If you have any questions or suggestions, feel free to reach out. 

*Created with ❤️ by Somanath Nemilidinne*
