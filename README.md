# Text-Encryption-Decryption_Collatz

# 🔐 Text Encryption and Decryption using 2’s Complement and Collatz Conjecture

📘 This project was developed in a **Jupyter Notebook**, and it uses a GUI built with `tkinter`. The application demonstrates a novel approach to text encryption and decryption using 2’s complement logic combined with the Collatz conjecture.

This encryption tool applies a unique algorithm based on:
- **2’s Complement**
- **Collatz Conjecture**

It includes features such as:
- Time-based analysis (encryption/decryption)
- Character counting
- Visualization graphs
- GUI built using `tkinter`

---

## 🧠 How It Works

- The text is converted into Unicode values.
- Each value is transformed using a key and random offset.
- The 2’s complement of each value is computed.
- A specified number of **Collatz iterations** is applied.
- Final characters are mapped to printable symbols.

The decryption checks for correct key and reverses the encryption using stored mappings.

---

## 📦 Features

- Encrypt and Decrypt with user-defined key and iterations
- Tracks:
  - Encryption time
  - Decryption time
  - Character analysis
- Graphs:
  - Time taken for encryption/decryption
  - Repeated encryption attempts
- GUI built with `tkinter`

---

## 💻 Installation & Usage

1. **Clone or download this repository**:
   - Click the green **“Code”** button on this page.
   - Select **Download ZIP**, then extract it.
   - Or use Git:
     ```bash
     git clone https://github.com/yourusername/text-encryption-collatz.git
     ```

2. **Install required Python libraries**:
   ```bash
   pip install matplotlib numpy

3. **Open the project in Jupyter Notebook**:
  - Launch Jupyter Notebook:
       jupyter notebook
  - Open the file:
       text-encryption-decryption.ipynb

4. **Run the file**
