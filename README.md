# Tip Calculator

This project is a simple tip calculator built using React. It allows users to calculate the tip amount based on the bill amount and two separate service ratings. The calculated tip is displayed along with the total amount to be paid.

## Getting Started

To use the tip calculator, follow these steps:

1. Clone the repository or download the project files.

2. Make sure you have Node.js installed on your machine.

3. Open the project directory in your preferred code editor.

4. Install the dependencies by running the following command in the terminal:

   ```shell
   npm install
   ```

5. Start the development server:

   ```shell
   npm start
   ```

6. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to access the tip calculator.

## Usage

Once you have the tip calculator running, you can follow these steps to calculate the tip:

1. Enter the bill amount in the input field labeled "How much was the bill?"

2. Select a rating for the first question, "How did you like the service?" from the drop-down list.

3. Select a rating for the second question, "How did your friend like the service?" from the drop-down list.

4. The calculated tip amount and the total bill with tip will be displayed below.

5. To reset the inputs and start over, click the "Reset" button.

## Project Structure

The project consists of the following files:

- `App.js`: The main component that renders the `TipCalculator` component.
- `style.css`: CSS file for styling the components.
- `TipCalculator.js`: The main tip calculator component that manages the state and renders other components.
- `Title.js`: Component that renders the title of the tip calculator.
- `BillInput.js`: Component that renders the input field for the bill amount.
- `SelectPercentage.js`: Component that renders the rating selection drop-downs.
- `Output.js`: Component that displays the calculated tip and total bill.
- `Reset.js`: Component that renders the reset button.

## Customization

You can customize the tip percentages and the corresponding labels in the `SelectPercentage` component by modifying the options in the `select` element.

## License

This project is licensed under the MIT License. Feel free to modify and use it according to your needs.

