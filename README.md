https://apinkcalculator.netlify.app

# My Little Calculator

A simple, interactive web-based calculator designed to perform basic addition operations. This project demonstrates clean, modular code, intuitive design, and efficient interaction between HTML, CSS, and JavaScript.

## Features

- **Responsive and Intuitive UI**: A clean, user-friendly interface styled with CSS for a modern look.
- **Real-Time Calculation**: Updates and displays the result dynamically upon user input.
- **Interactive Button Feedback**: Buttons include hover effects for enhanced UX.
- **Error Prevention**: Ensures inputs are numeric and handles cases gracefully.

## Technologies Used

- **HTML5**: For structuring the calculator interface.
- **CSS3**: To style and enhance the aesthetics of the app.
- **JavaScript (ES6)**: Implements dynamic functionalities like form handling and result calculation.
- **Responsive Design**: Ensures proper display across various screen sizes.

## Demo

### Screenshot
<img width="356" alt="Screenshot 2024-12-16 at 14 48 55" src="https://github.com/user-attachments/assets/d9cd1557-6ecb-4b0b-9845-71fba575e004" />


### Live Demo
https://apinkcalculator.netlify.app

## Installation and Setup

1. Clone the repository:
   ```bash
   https://github.com/soniathephoenix/calculator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd my-little-calculator
   ```
3. Open the `index.html` file in your preferred web browser:
   ```bash
   open index.html
   ```

## How to Use

1. Enter the first number in the "First Number" field.
2. Enter the second number in the "Second Number" field.
3. Click the **"Add numbers"** button.
4. The result of the addition will display below the form.

## Code Highlights

- **Event Handling**: The `submit` event is captured and processed dynamically to prevent default behavior, ensuring the application is smooth and user-friendly.
- **Dynamic Updates**: The result is computed and updated in real time using DOM manipulation.
- **Type Conversion**: Ensures user input is treated as numbers, avoiding string concatenation issues.

### Example Code Snippet
```javascript
form.addEventListener('submit', function(e) {
    e.preventDefault();
    const numOneVal = Number(numOneInput.value); 
    const numTwoVal = Number(numTwoInput.value);
    resultText.innerText = `${numOneVal} + ${numTwoVal} = ${numOneVal + numTwoVal}`;
});
```

## Future Improvements

- **Additional Operations**: Include subtraction, multiplication, and division.
- **Validation Messages**: Provide user feedback for invalid inputs.
- **Enhanced UI**: Add animations and transitions for a polished look.
- **Unit Tests**: Integrate testing frameworks to validate functionality.


## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.

## 📧 Contact

- **LinkedIn**: https://www.linkedin.com/in/sonia-pires-467625184/
- **Email**: [Your Email Address](mailto:soniacodesloads@gmail.com)
