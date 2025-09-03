# SCT_AD_001
# Simple Calculator App 🔢

A basic calculator app built with Flutter that performs fundamental arithmetic operations.

## Features ✨

* **Addition**, **Subtraction**, **Multiplication**, and **Division**.
* Clean and user-friendly interface.
* Real-time display of input and results.

## Screenshots 📱



## Getting Started ▶️

### Prerequisites

* **Flutter SDK**: [Install Flutter](https://flutter.dev/docs/get-started/install)
* **A code editor**: VS Code or Android Studio with Flutter and Dart plugins.

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/flutter-calculator.git](https://github.com/yourusername/flutter-calculator.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd flutter-calculator
    ```
3.  Install dependencies:
    ```bash
    flutter pub get
    ```

### Running the App

1.  Connect a device or start an emulator.
2.  Run the app from your terminal:
    ```bash
    flutter run
    ```
    Or, run it from your IDE.

## Code Structure 📁

The main logic resides in `lib/main.dart`.

* **`_CalculatorHomePageState`**: Manages the app's state, including the current numbers and the operation.
* **`_buttonPressed`**: Handles all button click events and performs the necessary calculations.
* **`_buildButton`**: A helper widget to create the calculator's buttons consistently.

