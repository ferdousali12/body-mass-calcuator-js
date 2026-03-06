# Day 12: BMI Calculator (JavaScript)

A lightweight, functional Body Mass Index (BMI) calculator built using HTML, CSS, and Vanilla JavaScript. This project focuses on handling user input, performing mathematical conversions, and dynamic DOM updates.

## 🚀 Features
- **Imperial to Metric Conversion**: Automatically converts Height (Feet/Inches) and Weight into the metric system for calculation.
- **Dynamic Feedback**: Displays the BMI score alongside the corresponding health category (Underweight, Normal, Overweight, Obese).
- **Form Validation**: Ensures all fields are filled before performing calculations.

## 🧮 The Logic
The calculator uses the standard BMI formula:
$$BMI = \frac{weight (kg)}{height (m)^2}$$

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)

## 📝 Lessons Learned
- Preventing default form submission behavior using `e.preventDefault()`.
- Parsing strings into integers and floats for accurate calculations.
- Using `toFixed(2)` to keep the output clean and user-friendly.
