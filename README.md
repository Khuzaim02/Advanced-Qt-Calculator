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

Getting Started
Prerequisites

    C++ compiler (supporting C++11 or newer)

    Qt 5.12+ or Qt Creator IDE

Build Instructions
