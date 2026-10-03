# 🧮 Calculator

A simple and elegant web calculator with a glassmorphism look over a black-and-white mountain background.

## 🔗 Live Demo

**👉 [https://miguellsouza.github.io/calculator/](https://miguellsouza.github.io/calculator/)**

## ✨ Features

- Basic operations: addition (`+`), subtraction (`-`), multiplication (`*`) and division (`/`)
- Decimal numbers with the dot (`.`) button
- **C** button to clear the display
- Backspace button to delete the last typed character
- **=** button to calculate the result
- Glass effect (`backdrop-filter: blur`) with a soft shadow

## 🛠️ Built With

- **HTML5**: page structure
- **CSS3**: styling (flexbox, `backdrop-filter`, `box-shadow`)
- **JavaScript**: calculator logic
- **[Font Awesome 7](https://fontawesome.com/)**: button icons

## 📁 Project Structure

```
calculator/
├── index.html                                      # Main page and script
├── estilizacaocalculadora.css                      # Calculator styles
├── background.jpg                                  # Original background image
├── background_upscayl_3x_upscayl-standard-4x.png   # High-resolution background (used in the CSS)
└── logo.webp                                       # Tab icon (favicon)
```

## 🚀 Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/miguellsouza/calculator.git
   ```
2. Enter the folder:
   ```bash
   cd calculator
   ```
3. Open `index.html` in your browser (just double-click it).

Nothing needs to be installed. The project runs directly in the browser. An internet connection is only needed to load the Font Awesome icons.

## 💡 Future Improvements

- Replace `eval()` with a safer expression parser
- Handle invalid expressions (e.g. `5++`) and division by zero
- Add keyboard support
- Include percentage, parentheses and calculation history
- Make the layout fully responsive for mobile devices

## 👤 Author

Made by [@miguellsouza](https://github.com/miguellsouza).
