# Kalkulatorek 🧮

A modern, web-based calculator application built with HTML, CSS (Tailwind), and vanilla JavaScript.

![Calculator Screenshot](https://github.com/user-attachments/assets/5f1d6d6f-e788-4ac6-b430-c00490505228)

## Features

- ✅ Basic arithmetic operations (addition, subtraction, multiplication, division)
- ✅ Clear (C) and All Clear (AC) functions
- ✅ Responsive text sizing based on input length
- ✅ Clean, modern design with Tailwind CSS
- ✅ Visual feedback and error handling

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic web server (for local development)

### Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Koloqs/kalkulatorek.git
   cd kalkulatorek
   ```

2. **Open in browser:**
   - **Option 1**: Simply open `index.html` in your browser
   - **Option 2**: Use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Navigate to:** `http://localhost:8000`

## How to Use

1. **Basic Operations:**
   - Click number buttons (0-9) to input numbers
   - Click operator buttons (+, -, ×, ÷) for operations
   - Click equals (=) to calculate the result

2. **Clear Functions:**
   - **C**: Clear the last entered character
   - **AC**: Clear all and reset the calculator

3. **Decimal Numbers:**
   - Click the decimal point (.) to enter decimal numbers

## Project Structure

```
kalkulatorek/
├── index.html      # Main HTML file
├── input.css       # Tailwind CSS input file
├── output.css      # Compiled Tailwind CSS
├── README.md       # This file
└── opinion.md      # Project evaluation and recommendations
```

## Technology Stack

- **HTML5**: Structure and semantics
- **CSS3**: Styling with Tailwind CSS framework
- **JavaScript**: Calculator logic and interactivity
- **Tailwind CSS**: Utility-first CSS framework

## Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## Known Issues

- Security concern: Uses `eval()` for calculations (see [opinion.md](opinion.md))
- No keyboard support
- Limited accessibility features
- No advanced calculator functions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Replace `eval()` with safer math parser
- [ ] Add keyboard support
- [ ] Implement memory functions (M+, M-, MR, MC)
- [ ] Add calculation history
- [ ] Improve accessibility (ARIA labels, screen reader support)
- [ ] Add advanced operations (√, %, x², etc.)
- [ ] Dark/light theme toggle
- [ ] Mobile responsive improvements
- [ ] Unit tests

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Created by [Koloqs](https://github.com/Koloqs)

## Acknowledgments

- Tailwind CSS for the excellent utility-first CSS framework
- Modern web standards for making calculator development accessible

---

⭐ If you found this project helpful, please give it a star!