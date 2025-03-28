# 📐 Triangle Calculator

<div align="center">

![Triangle Calculator](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Language](https://img.shields.io/badge/Language-C-orange)

A powerful C program for calculating and analyzing triangle properties.

</div>

## 🎯 Problem Statement

This program solves the common problem of triangle analysis and classification. In geometry and engineering, it's often necessary to:
- Quickly determine the type of a triangle
- Calculate its properties (perimeter, area)
- Verify if given measurements can form a valid triangle
- Keep track of multiple triangle calculations

### Why This Solution?
- **Speed**: Automates complex geometric calculations
- **Accuracy**: Eliminates human error in triangle classification
- **Validation**: Ensures mathematical validity of triangle measurements
- **History**: Maintains a record of all calculations for future reference

## 🌟 Overview

Triangle Calculator is a comprehensive tool that performs various calculations and classifications of triangles based on their side lengths. It provides accurate results for triangle properties, classifications, and maintains a history of calculations.

## 🎯 Features

### Triangle Classification
- **By Sides:**
  - Equilateral (all sides equal)
  - Isosceles (two sides equal)
  - Scalene (all sides different)

- **By Angles:**
  - Right (one 90° angle)
  - Obtuse (one angle > 90°)
  - Acute (all angles < 90°)

### Mathematical Calculations
- Perimeter calculation
- Area calculation using Heron's formula
- Automatic side sorting for accurate classification
- Precise floating-point calculations

### Data Management
- CSV file history tracking
- Detailed operation logging
- Easy-to-read output format
- Persistent storage of calculations

### User Experience
- Clear input prompts
- Informative error messages
- Automatic input validation
- Instant results display

## 🛠️ Technical Details

### Dependencies
```c
#include <math.h>    // Mathematical functions
#include <stdio.h>   // Input/Output operations
#include <ctype.h>   // Character type functions
#include <stdlib.h>  // Standard library functions
```

### File Structure
```
├── Triangle_Calculator.c  // Main program file
├── intro.txt             // Program introduction
└── history.csv           // Calculation history
```

## 💻 Installation & Usage

### Prerequisites
- C compiler (gcc recommended)
- Basic understanding of triangle properties

### Compilation
```bash
gcc Triangle_Calculator.c -o Triangle_Calculator
```

### Execution
```bash
./Triangle_Calculator
```

### Input Format
- Enter three positive numbers representing side lengths
- Program will validate input automatically
- Results will be displayed and saved to history

## ⚠️ Input Validation Rules

1. All sides must be positive numbers
2. Must satisfy triangle inequality theorem:
   - a + b > c
   - b + c > a
   - a + c > b

## 📊 Output Format

```
Triangle Type: [EQUILATERAL/ISOSCELES/SCALENE] [RIGHT/OBTUSE/ACUTE]
Perimeter: [value] cm
Area: [value] cm²
```

## 🔄 History Tracking

Each calculation is saved to `history.csv` with:
- Timestamp
- Side lengths
- Perimeter
- Area
- Triangle classifications

## 🛡️ Error Handling

- Invalid numeric input detection
- Zero or negative length prevention
- Triangle inequality theorem validation
- File operation error handling

## 📝 Example Usage

```
Enter length of side A: 5
Enter length of side B: 5
Enter length of side C: 7

ISOSCELES ACUTE triangle
Perimeter = 17.00 cm
Area = 12.50 cm²
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 👤 Author

**Ali Nasr**
- GitHub: [www.github.com/aliashraf8]
- Email: [aliashraf8@outlook.com]

## 📄 License

<div align="center">
Made with ❤️ by Ali Nasr
</div> 