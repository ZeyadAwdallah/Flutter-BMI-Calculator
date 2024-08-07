# BMI Calculator Flutter App Documentation

## Overview

The BMI Calculator is a Flutter application designed to compute and display the Body Mass Index (BMI) based on user input. This app provides an easy-to-use interface to calculate BMI and interpret the results according to standard BMI categories.

## Features

- **Input Fields**: Allows users to enter their weight and height.
- **BMI Calculation**: Computes BMI based on the input values.
- **BMI Interpretation**: Displays the BMI result along with a description of the BMI category (e.g., Underweight, Normal weight, Overweight, Obesity).
- **Responsive Design**: Adapts to different screen sizes and orientations.

## Components

### 1. User Interface

- **Input Fields**:
  - **Weight**: A text field for entering weight in kilograms.
  - **Height**: A text field for entering height in centimeters.
- **Calculate Button**: Triggers the BMI calculation.
- **Result Display**:
  - Shows the calculated BMI value.
  - Provides a description based on the BMI value.
- **Styling**: Utilizes Flutter's `Container`, `TextField`, `Text`, and `Button` widgets with custom styling to ensure a clean and user-friendly interface.

### 2. BMI Calculation Logic

- **Formula**:
  - Converts height from centimeters to meters.
  - Uses the formula: BMI = weight (kg) / (height (m) * height (m)).
- **Validation**:
  - Checks for valid input values (e.g., non-negative numbers).
  - Handles potential errors such as division by zero if height is zero.

### 3. State Management

- **State Handling**: Manages input values and results using Flutter’s `StatefulWidget` and `State` classes.
- **Error Handling**: Displays error messages for invalid inputs or calculation issues.

### 4. Flutter Implementation

- **Widgets**:
  - **`TextField`**: For user input (weight and height).
  - **`ElevatedButton`**: To trigger BMI calculation.
  - **`Text`**: To display results and interpretations.
- **Layout**:
  - Utilizes Flutter layout widgets like `Column`, `Row`, and `Center` to arrange the UI components.
- **Styling**:
  - Applies basic styling for padding, margins, and text formatting to enhance the visual appeal.

## Usage

1. **Launch the App**: Open the BMI Calculator app on your Flutter-supported device.
2. **Enter Details**: Input your weight in kilograms and height in centimeters into the respective fields.
3. **Calculate BMI**: Tap the “Calculate” button to compute your BMI.
4. **View Results**: The app will display your BMI along with a description of your BMI category.

## Installation

To run the BMI Calculator app:

1. **Clone the Repository**: Clone the app repository to your local machine.
2. **Install Dependencies**: Navigate to the project directory and run `flutter pub get` to install required dependencies.
3. **Run the App**: Use `flutter run` to build and run the app on your device or emulator.
