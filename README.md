# 🧮 Scientific Calculator using Python & Tkinter

This project is a GUI-based **Scientific Calculator** built with **Python** and **Tkinter**. It supports both basic arithmetic operations and scientific functions such as sine, cosine, tangent, square root, and exponentiation.

## 📸 Screenshot
> *(You can add a screenshot here of the calculator UI)*
![Screenshot (599)](https://github.com/user-attachments/assets/f8f35d57-4fb1-48fd-a29a-c7fd9c919d77)

## 🚀 Features

✅ User-friendly GUI  
✅ Basic operations: `+`, `-`, `*`, `/`, `=`, `C`, `⌫`  
✅ Decimal support  
✅ Scientific operations:
- `sin(x)`, `cos(x)`, `tan(x)` — accepts degrees
- `sqrt(x)` — square root
- `^` — exponentiation (`x^y`)
- `%` — percentage

## 🛠️ Technologies Used

- **Python 3.x**
- **Tkinter** (built-in GUI library in Python)
- **math** module

## 📂 Folder Structure
```
ScientificCalculator/
│
├── calculator.py # Main calculator code
├── README.md # Project documentation
```

## ▶️ Getting Started

### Prerequisites
Make sure Python 3 is installed. You can download it from [python.org](https://www.python.org/).

### Run the Project

```bash
python calculator.py
```
This will open a window with a fully functional scientific calculator.
## 🧠 How It Works

- All inputs are displayed in a **Tkinter `Entry` widget**.
- Buttons are dynamically placed using a **grid layout**.
- Clicking buttons appends values to the display or performs functions like `sqrt`, `sin`, etc.
- Trigonometric functions take input in **degrees** and convert them to **radians** internally using the `math` module.

## 🧼 Error Handling

- Handles invalid input with a user-friendly **"Error"** message.
- Prevents application crashes due to **math domain errors** or **invalid expressions** using `try-except` blocks.

## 👩‍💻 Author

**PVN Devaki**  
📧 [devakipvn@gmail.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/pvndevaki) 

## 📄 License

This project is open-source and available under the **[MIT License](LICENSE)**.


