<div align="center">

# 🧮 NOVA PRO CALCULATOR
### *Next-Generation, All-in-One Scientific, Financial & Daily Utility Computation Suite*

[![Platform](https://img.shields.io/badge/Platform-Web%20Browser-blue.svg?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/jayprakashkkk/NOVA-PRO-Calculator)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/jayprakashkkk/NOVA-PRO-Calculator)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/jayprakashkkk/NOVA-PRO-Calculator)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/jayprakashkkk/NOVA-PRO-Calculator)
[![Responsive](https://img.shields.io/badge/Responsive-100%25%20Fullscreen-green?style=for-the-badge&logo=responsive&logoColor=white)](https://github.com/jayprakashkkk/NOVA-PRO-Calculator)
[![License](https://img.shields.io/badge/License-MIT-purple.svg?style=for-the-badge)](LICENSE)

<br/>

**Nova Pro Calculator** is a precision-engineered, ultra-responsive web application uniting **8 powerful calculation engines** into one seamless, distraction-free cyber interface. Designed for students, software engineers, accountants, and everyday users who demand speed, mathematical accuracy, and visual elegance.

[Key Features](#-key-features) • [Calculator Modules](#-calculator-modules) • [Keyboard Shortcuts](#-keyboard-shortcuts-reference) • [Tech Stack](#-technology-stack) • [Quick Start](#-quick-start) • [Project Structure](#-project-structure)

---

</div>

## 📑 Table of Contents

- [Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🔬 Calculator Modules](#-calculator-modules)
  - [1. Basic Calculator (`# Basic`)](#1-basic-calculator--basic)
  - [2. Scientific Engine (`∑ Scientific`)](#2-scientific-engine--scientific)
  - [3. Live Currency Converter (`⇄ Currency`)](#3-live-currency-converter--currency)
  - [4. Multi-Unit Converter (`⚖ Unit Converter`)](#4-multi-unit-converter--unit-converter)
  - [5. GST Tax Calculator (`₹ GST`)](#5-gst-tax-calculator--gst)
  - [6. EMI Loan Calculator (`▦ EMI`)](#6-emi-loan-calculator--emi)
  - [7. Interest Calculator (`% Interest`)](#7-interest-calculator--interest)
  - [8. Retail Discount Calculator (`% Discount`)](#8-retail-discount-calculator--discount)
- [⌨️ Keyboard Shortcuts Reference](#-keyboard-shortcuts-reference)
- [🛠️ Technology Stack](#-technology-stack)
- [🚀 Quick Start (Local Setup)](#-quick-start)
- [📂 Project Structure](#-project-structure)
- [🎨 Design & UX Principles](#-design--ux-principles)
- [🤝 Contributing & License](#-license--author)

---

## 🌟 Overview

Standard operating system calculators are often either overly simplified or clunky to use. **Nova Pro Calculator** bridges this gap by delivering:
- **Instant Mode Switching**: Switch between basic math, advanced trigonometry, currency conversions, loan EMIs, and GST tax calculations in a single click.
- **Zero Dependencies**: Pure HTML5, modern CSS variables, and vanilla ES6+ JavaScript. No bloated frameworks, zero tracking, and instant sub-millisecond load times.
- **100% Edge-to-Edge Responsive Layout**: Thoughtfully crafted to adapt fluidly across widescreen monitors, laptops, tablets, and handheld smartphones.

---

## ✨ Key Features

- **⚡ 8-in-1 Versatile Computing Hub**: All your mathematical, financial, scientific, and metric conversion needs housed within a single unified workspace.
- **💾 Memory Register Operations**: Full support for standard memory calculations (`MC`, `MR`, `M+`, `M-`) for compounding numbers on the fly.
- **📜 Calculation History & Tape View**: Real-time tape log tracking past equations and answers so you never lose intermediate computations.
- **🌙 Cyber Dark Aesthetics**: Ergonomic high-contrast dark palette (`#10111a` and `#1b1e2b`) with vibrant purple accents (`#8975ff`) to prevent eye fatigue during late-night study or work sessions.
- **⌨️ Comprehensive Keyboard Navigation**: Type calculations naturally using your physical numpad and keyboard.
- **📱 Touch & Haptic Optimized**: Fast touch-action optimization with zero tap delay on mobile and tablet touchscreens.

---

## 🔬 Calculator Modules

```
                    ┌───────────────────────────────┐
                    │     NOVA PRO CALCULATOR       │
                    └──────────────┬────────────────┘
                                   │
      ┌─────────────┬──────────────┼──────────────┬─────────────┐
      ▼             ▼              ▼              ▼             ▼
┌───────────┐ ┌───────────┐  ┌───────────┐  ┌───────────┐ ┌───────────┐
│   Basic   │ │Scientific │  │ Currency  │  │   Unit    │ │ Financial │
│Arithmetic │ │Trig & Log │  │Exchange   │  │Converter  │ │GST/EMI/Int│
└───────────┘ └───────────┘  └───────────┘  └───────────┘ └───────────┘
```

### 1. Basic Calculator (`# Basic`)
- Standard 4-function arithmetic operations: Addition ($+$), Subtraction ($-$), Multiplication ($\times$), and Division ($\div$).
- Continuous chain evaluations and percentage operations ($\%$).
- Single-character Backspace (`⌫`) and Complete Reset (`AC`).

### 2. Scientific Engine (`∑ Scientific`)
- **Trigonometry**: Sine (`sin`), Cosine (`cos`), Tangent (`tan`) and inverse functions in Degree / Radian modes.
- **Logarithms & Exponentials**: Natural logarithm (`ln`), Base-10 logarithm (`log`), Exponential powers ($e^x$, $10^x$).
- **Powers & Roots**: Square ($x^2$), Cube ($x^3$), Custom exponent ($x^y$), Square root ($\sqrt{x}$), Cube root ($\sqrt[3]{x}$).
- **Mathematical Constants**: High-precision $\pi$ (Pi) and $e$ (Euler's number).
- **Factorial & Negation**: Factorial ($n!$) calculations and positive/negative sign toggle ($\pm$).

### 3. Live Currency Converter (`⇄ Currency`)
- Rapid conversions between major global and regional currencies (USD, INR, EUR, GBP, JPY, AUD, CAD, etc.).
- Intuitive bi-directional exchange rate computation with manual rate adjustment capability.

### 4. Multi-Unit Converter (`⚖ Unit Converter`)
Comprehensive conversion matrix supporting:
- **Length**: Meters, Kilometers, Centimeters, Millimeters, Miles, Yards, Feet, Inches.
- **Mass / Weight**: Kilograms, Grams, Milligrams, Metric Tons, Pounds, Ounces.
- **Temperature**: Celsius ($^\circ\text{C}$), Fahrenheit ($^\circ\text{F}$), Kelvin ($\text{K}$).
- **Digital Storage**: Bits, Bytes, KB, MB, GB, TB.
- **Speed & Time**: km/h, mph, m/s, Seconds, Minutes, Hours, Days.

### 5. GST Tax Calculator (`₹ GST`)
- Tailored for Indian Goods and Services Tax (GST) accounting.
- **Exclusive / Inclusive** pricing calculation toggles.
- Preset GST slab selectors: `3%`, `5%`, `12%`, `18%`, and `28%`.
- Detailed breakdown displaying **Net Price**, **CGST (Central GST)**, **SGST (State GST)**, and **Gross Total Amount**.

### 6. EMI Loan Calculator (`▦ EMI`)
- Plan home loans, personal loans, vehicle financing, and educational debts.
- Inputs for **Loan Principal Amount**, **Annual Interest Rate (%)**, and **Tenure** (Months or Years).
- Instant breakdown showing:
  - **Monthly EMI Payment**
  - **Total Interest Payable**
  - **Total Amount (Principal + Interest)**

### 7. Interest Calculator (`% Interest`)
- Toggle between **Simple Interest** ($SI = \frac{P \times R \times T}{100}$) and **Compound Interest** ($A = P(1 + \frac{r}{n})^{nt}$).
- Compounding frequency configurations (Annually, Semi-Annually, Quarterly, Monthly).

### 8. Retail Discount Calculator (`% Discount`)
- Instant computation for sale discounts and clearance items.
- Enter original listing price and discount percentage.
- Returns exact **Savings Amount** and **Final Discounted Price**.

---

## ⌨️ Keyboard Shortcuts Reference

| Key Stroke | Action / Function |
| :--- | :--- |
| `0` – `9` | Enter numbers |
| `.` | Enter decimal point |
| `+`, `-`, `*`, `/` | Addition, Subtraction, Multiplication, Division |
| `Enter` or `=` | Calculate Result (`=`) |
| `Backspace` | Erase last entered digit (`⌫`) |
| `Escape` or `c` / `C` | All Clear (`AC`) |
| `%` | Percentage calculation |
| `(`, `)` | Parentheses grouping |

---

## 🛠️ Technology Stack

- **HTML5**: Semantic document structure, accessible ARIA roles, modern viewports.
- **CSS3**: Custom CSS Properties (CSS Variables), Flexbox & CSS Grid, fluid responsive breakpoints, backdrop filters, hardware-accelerated transitions.
- **Vanilla JavaScript (ES6+)**: Pure client-side mathematical logic, precision rounding algorithms, DOM event delegation, and state caching.

---

## 🚀 Quick Start

No package managers, build steps, or local server installations are needed!

### Method 1: Direct File Launch
1. Clone the repository:
   ```bash
   git clone https://github.com/jayprakashkkk/NOVA-PRO-Calculator.git
   cd NOVA-PRO-Calculator
   ```
2. Open the calculator directly in your favorite web browser:
   - **macOS**:
     ```bash
     open Calculator/index.html
     ```
   - **Windows**:
     ```bash
     start Calculator/index.html
     ```
   - **Linux**:
     ```bash
     xdg-open Calculator/index.html
     ```

### Method 2: Local HTTP Server (Optional)
```bash
# Using Python 3
python3 -m http.server 8080

# Using Node.js
npx serve .
```
Then navigate to `http://localhost:8080/Calculator/index.html` in your browser.

---

## 📂 Project Structure

```
NOVA-PRO-Calculator/
├── Calculator/
│   └── index.html       # Complete application (HTML markup, styling & JS logic)
├── LICENSE              # MIT Open-Source License
└── README.md            # Comprehensive project documentation
```

---

## 🎨 Design & UX Principles

- **Fluid Edge-to-Edge Responsiveness**: No awkward horizontal scrollbars or cramped layouts. The calculator gracefully scales across mobile screens, iPads, and ultrawide desktop monitors.
- **High Visual Contrast**: Purposefully selected contrast ratios to guarantee readability in bright sunlight and pitch-dark environments.
- **Zero Latency Feedback**: Immediate UI response upon button press, with visual active states and smooth transitions.

---

## 📄 License & Author

Developed with ❤️ by **[Jay Prakash](https://github.com/jayprakashkkk)**.

Released under the **MIT License**. You are free to use, modify, and distribute this software for personal and commercial projects.
