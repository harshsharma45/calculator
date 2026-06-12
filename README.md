# calculator
# Simple Python GUI Calculator 🧮

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

A lightweight, functional graphical user interface (GUI) calculator built using Python's standard `tkinter` library. This project provides a clean, interactive way to perform basic arithmetic directly on your desktop.

## 🚀 Features

The calculator features a standard number pad layout and supports fundamental arithmetic logic.

| Operation | Symbol | Description |
| :--- | :---: | :--- |
| **Addition** | `+` | Adds two input integers together. |
| **Subtraction** | `-` | Subtracts the second integer from the first. |
| **Multiplication** | `*` | Multiplies two input integers. |
| **Division** | `/` | Divides the first integer by the second. |
| **Clear** | `clear` | Completely resets the input display. |

## 🛠️ Prerequisites

To run this application, you only need Python installed on your system.
* **Python 3.x**
* **Tkinter** (This comes pre-installed with standard Python distributions. Linux users may need to install it via their package manager, e.g., `sudo apt-get install python3-tk`).

## 💻 How to Run

**1. Clone the repository:**
```bash
git clone [https://github.com/harshsharma45/calculator.git](https://github.com/harshsharma45/calculator.git)

```

**2. Navigate to the project directory:**

```bash
cd calculator

```

**3. Run the Python script:**

```bash
python calculator.py

```

*(Note: If your main file is named differently, replace `calculator.py` with your exact filename).*

## 🏗️ Under the Hood

The application logic is broken down into four clear steps:

* **Step 1: Importing:** Loads the required modules from the `tkinter` library.
* **Step 2: GUI Interaction:** Initializes the root window, sets the dimensions to `500x500`, and adds a custom window title.
* **Step 3: Adding Inputs:** * Creates the main `Entry` box to display numbers.
* Maps buttons `0-9` to `lambda` functions for seamless input.
* Handles mathematical operations using global variables to store the state and values between button clicks.


* **Step 4: Mainloop:** Executes the application, keeping the window open and listening for user events.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://www.google.com/search?q=https://github.com/harshsharma45/calculator/issues).

## 📄 License

This project is open-source and available under the **Apache License 2.0**.
