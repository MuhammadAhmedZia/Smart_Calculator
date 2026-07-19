🧮 Smart Conditional Calculator

A clean, modern, and rule-enforcing calculator web application built using HTML5, CSS3, and Vanilla JavaScript. Unlike standard calculators, this application strictly enforces logical and mathematical constraints on inputs before performing operations.

🚀 Live Demo

Simply download the repository and open calculator.html in any modern web browser to run the app.

🎯 Strict Rules Enforced

To ensure logical data processing, the calculator operates under three strict mathematical rules:

Value Dominance Constraint: The first value must always be greater than or equal to the second value:


$$Value_1 \ge Value_2$$


If this condition is violated (e.g., $Value_1 = 5$ and $Value_2 = 10$), the calculation is blocked, and an error message is displayed.

Strict Numeric Validation: Only valid numeric values are accepted:


$$Value \in \mathbb{R}$$


Empty inputs or non-numeric characters (e.g., alphabets or special characters) are automatically filtered out, prompting a strict input error state.

Division by Zero Prevention: The system prevents the mathematically undefined state of dividing a real number by zero:


$$\frac{Value_1}{Value_2} = \text{Undefined} \quad \text{for} \quad Value_2 = 0$$


If the division operator (/) is selected and the second value is set to 0, the operation is aborted with a protective error alert.

✨ Key Features

Modern Minimal UI: Built with a clean cards layout, elegant drop shadows, responsive layouts, and native focus states.

Dynamic Feedback Boxes:

🟢 Green Box: Displays successful mathematical outputs.

🔴 Red Box: Notifies the user of validation or rule-breaking errors.

Precision Management: Built-in protection against JavaScript's floating-point precision issues (e.g., avoiding calculations like $0.1 + 0.2 = 0.300000000004$ by automatically rounding up to 4 decimal places where necessary).

Fully Responsive: Works seamlessly on both mobile screens and desktop screens.

🛠️ Built With

HTML5: Semantic markup structure.

CSS3: Custom properties (CSS variables), CSS Grid for the buttons layout, and dynamic transitions.

JavaScript (ES6+): Vanilla script handling form state, real-time validation, and arithmetic evaluation.

📂 Installation & Usage

1. Clone the repository

git clone https://github.com/your-username/smart-conditional-calculator.git


2. Navigate to the project folder

cd smart-conditional-calculator


3. Run the application

Simply double-click the calculator.html file or open it in your preferred web browser.
