Advanced GUI Calculator

A powerful, feature-rich calculator application built with **C++** and **Qt Framework**. Designed with an intuitive GUI, this calculator goes far beyond basic arithmetic—supporting scientific operations, unit conversions, and calculation history.

---


Features

Basic Functions
- Arithmetic: `+`, `-`, `×`, `÷`
- Bracketed expressions with proper operator precedence
- Error detection for invalid inputs

Scientific Calculator
- Trigonometric: `sin`, `cos`, `tan`, etc.
- Logarithmic and exponential functions
- Power and factorial
- Square root, inverse

Unit Conversion
- Length: meters, kilometers, feet, inches
- Weight: kilograms, grams, pounds, ounces
- Temperature: Celsius ↔ Fahrenheit ↔ Kelvin
- (Optional) Currency conversion via manual rate entry

History Tracking
- View previous calculations in a scrollable list
- Option to copy past results

UI Themes
- Light and Dark mode toggle

---

Built With

| Tech | Purpose |
|------|---------|
| C++ | Core logic and data handling |
| Qt | GUI framework |
| Qt Widgets | Interface elements |
| QStack/QList | History and memory functions |

---

Project Structure

```bash
AdvancedCalculator/
├── main.cpp
├── mainwindow.cpp
├── mainwindow.h
├── mainwindow.ui
├── converters.cpp
├── historymanager.cpp
├── assets/
│   └── icons/
└── README.md
```
---
**Getting Started**
Prerequisites

Make sure you have the following installed:

    Qt 5.12+ or Qt Creator IDE

    A C++ compiler (GCC, Clang, MSVC – with C++11 support)

    Git (optional but recommended)

Installation & Build Instructions
Option 1: Using Qt Creator (Recommended)

    Clone the repository:   git clone https://github.com/yourusername/Advanced-Qt-Calculator.git cd Advanced-Qt-Calculator

Open the .pro file in Qt Creator:

    File > Open File or Project > Select AdvancedCalculator.pro
    Click Configure Project and then Run (green triangle).



Click Configure Project and then Run (green triangle).

Option 2: Using Command Line

      git clone https://github.com/yourusername/Advanced-Qt-Calculator.git
      cd Advanced-Qt-Calculator
      qmake
      make
      ./AdvancedCalculator

---
❗ Troubleshooting
   If qmake is not found, ensure Qt is installed and added to your system PATH.
   On Windows, use mingw32-make instead of make if you're using the MinGW version of Qt.

👤 Author

**Muhammad Khuzaim**
Email: muhammadkhuzaim50@gmail.com
GitHub: github.com/khuzaim02  
      

    

 












