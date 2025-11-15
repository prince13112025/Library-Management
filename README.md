# 📚 Library Management System (Python CLI)

A simple command-line based **Library Management System** that allows users to select and open online resources for different programming books.
This script uses Python’s `webbrowser` module to launch educational links for selected topics.


---

## 🚀 Features

* Simple text-based user interface
* Lets users select:

  * **0** → Exit
  * **1** → Choose a book
* Opens relevant online resources automatically
* Includes options for:

  * C programming
  * Java
  * HTML
  * Python

---

## 📂 Project Structure

```
library managemnet.py
```

The entire program is contained in a single Python script.

---

## 🛠️ How It Works

### 1. Program Start

The script welcomes the user and prompts:

```
Enter the number either 0 or 1
0 → Exit
1 → Continue to book selection
```

### 2. Book Selection

If the user enters **1**, they can choose:

```
1 → C
2 → Java
3 → HTML
4 → Python
```

### 3. Opening Book Resources

Based on the selection, the script opens reputable learning resources using `webbrowser.open()`.

---

## 🔗 Links Used

| Book   | Website       |
| ------ | ------------- |
| C      | GeeksforGeeks |
| Java   | W3Schools     |
| HTML   | W3Schools     |
| Python | W3Schools     |

---

## ▶️ How to Run

1. Ensure you have **Python 3.x** installed.
2. Run the script:

```bash
python "library managemnet.py"
```

3. Follow the on-screen prompts.

---

## 📌 Requirements

* Python 3.x
* Internet connection (for opening websites)

---

## 🙋 Author Notes

This program is ideal for beginners learning:

* Python input/output
* Function handling
* Conditional statements
* Opening URLs with `webbrowser`
