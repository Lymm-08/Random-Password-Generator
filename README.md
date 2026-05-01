```markdown
# Random Password Generator 🔐

Python project to generate customized random passwords.  
Now with a **graphical interface (Tkinter)** and also a **terminal (CLI)** option.

---

## ✨ Features
- Choose password length
- Include letters, numbers, and symbols
- Save passwords to a `.txt` file
- History of generated passwords
- Copy password to clipboard

---

## 🚀 How to Run

### 1. Create and activate virtual environment
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1   # on PowerShell
```

### 2. Install dependencies
```bash
pip install pyperclip
```

### 3. Run the program
```bash
python main.py
```

## 🎞️ Demonstration

![Demonstração do programa](GeradorSenhasAleatorias/imagens/demo.gif)
---

## 📊 Example Usage (Graphical Interface)
1. Enter the desired password length.  
2. Select whether to include letters, numbers, and symbols.  
3. Click **Generate Password**.  
4. Use the buttons to save, copy, or view history.  

---

## 📟 Example Usage (Terminal/CLI)
```
=== Random Password Generator ===
Enter password length: 12
Include letters? (y/n): y
Include numbers? (y/n): y
Include symbols? (y/n): n

Your generated password is:
a9BfK2LmQwXz
```

---

## 🔮 Next Steps
- Improve graphical interface (colors, styles, responsiveness).
- Add option to choose where to save the file.
- Create a PyQt version for a more advanced interface.
- Implement password export in different formats (JSON, CSV).
```
