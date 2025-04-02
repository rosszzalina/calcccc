# Calculator

This is a simple calculator application built using JavaFX. It supports basic arithmetic operations such as addition, subtraction, multiplication, division, square root, percentage, and more. The app provides a graphical user interface (GUI) for easy interaction.

## Features
- **Basic Arithmetic Operations**: Addition (`+`), Subtraction (`-`), Multiplication (`x`), Division (`/`).
- **Special Operations**: Square root (`√`), Percentage (`%`), Plus/Minus toggle (`+/-`).
- **Number Input**: Buttons for digits (0-9).
- **Clear Function**: The "AC" button to reset the calculator.
- **History and Error Handling**: The app handles errors like division by zero and square root of negative numbers.
- **Menu Options**: Clear calculator history and Close the app from the "File" menu.

## Requirements
- **Java 11 or higher** (for JavaFX)
- **JavaFX SDK** (required for building and running the application)
- **IDE**: IntelliJ IDEA, Eclipse, or any IDE with JavaFX support

## Setup and Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/calculator-app.git
    cd calculator-app
    ```

2. **Install JavaFX SDK**:
    - Download JavaFX SDK from [https://openjfx.io/](https://openjfx.io/).
    - Set up JavaFX SDK in your project settings (add the JavaFX libraries to the build path in your IDE).

3. **Run the Application**:
    - Ensure you have the correct environment variables set up for JavaFX.
    - Build and run the application from your IDE or use the following command to run it from the terminal:
    ```bash
    java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -jar CalculatorApp.jar
    ```

4. **Run the Calculator**:
    - After running the application, you will see the calculator window with buttons for numbers, operations, and a display field to show results.
    - Use the buttons to perform calculations.

## Project Structure

- **src/**: Contains all Java source files.
  - **com.example.calc.Calculator**: The model for the calculator, which contains the logic for the calculations.
      1. Basic Arithmetic Operations
      2. Advanced Features
      3. Error Handling
      4. GUI Interface
      5. Reset and Backspace
      6. Help Menu
  - **com.example.calc.CalculatorController**: The controller class that handles UI events (button clicks) and updates the UI.
      1. Class Declaration
      2. Instance Variables
      3. Digit Button Handlers
      4. Operator Handlers
      5. Equal Button Handler
      6. Expression Calculation
  - **com.example.calc.CalculatorApplication**: The entry point for the application that loads the FXML UI and initializes the controller.

- **resources/**: Contains the FXML file for the layout.
  - **calculator.fxml**: The FXML file that defines the calculator’s UI layout.

## Usage

- **Performing Calculations**: Click the numeric buttons (0-9) and operation buttons (+, -, *, /) to enter your calculation.
- **Special Functions**:
  - **Square Root** (`√`): Click the square root button to calculate the square root of the number.
  - **Percentage** (`%`): Click the percentage button to convert the number into a percentage.
  - **Plus/Minus Toggle** (`+/-`): Flip the sign of the number.
  - **Clear** (`AC`): Click to reset the calculator display.
- **Result**: After entering a calculation, click the equals button (`=`) to display the result.

## Screenshots

![Снимок экрана (7)](https://github.com/user-attachments/assets/9145a106-f5ec-455b-b15d-9e9bdae3eea2)

## Key Learning Features
- Understanding JavaFX Basics
- Handling Events in JavaFX
- MVC Design Pattern
- Building and Running a JavaFX Application
- UI Design for a Calculator
- Handling Errors in User Input
- Working with FXML
- Deployment and Running the Application
- Version Control
- Creating Documentation
- Debugging
- Designing and Implementing Functions
