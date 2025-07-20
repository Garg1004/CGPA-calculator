# 🎓 CGPA Calculator

A simple and interactive console-based C++ application to calculate **GPA (Grade Point Average)** and **CGPA (Cumulative Grade Point Average)**. This tool helps students efficiently compute their academic performance using subject credits and grade points.

---

## 📌 Features

- 📘 **GPA Calculation**: Input credit hours and grade points for each subject to get your GPA.
- 🎓 **CGPA Calculation**: Input GPA values from multiple semesters to compute your final CGPA.
- 📖 **Explanation**: Understand the methods and formulas used in the calculations.
- 🖥️ **Command-Line Interface**: Easy-to-use terminal-based interface for quick calculations.

---

## 🧮 Formula Used

- **GPA** = (Σ (Credit × Grade Point)) / (Σ Credit)
- **CGPA** = (Σ GPA of All Semesters) / (Number of Semesters)

---

## 🚀 How to Run

1. **Install a C++ compiler** (GCC, MinGW, or any C++ supported IDE).
2. **Clone the repository** or download the `.cpp` file.
3. **Compile and run** the program using your terminal or IDE.

### Using Terminal:
```bash
g++ cgpa_calculator.cpp -o cgpa_calculator
./cgpa_calculator
