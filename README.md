# Simple-Calculator Explanation about JavaScript
**1.	Defining the Calculator Class:**
        
        •	The Calculator class represents the calculator logic and functionality.
        
        •	The constructor takes two parameters: previousTextElement and currentTextElement, which are the elements used to display the previous and current calculations.

**2.	Basic Operations**:
        
        •	clear(): Clears the current calculation.
        
        •	delete(): Removes the last digit from the current calculation.
        
        •	appendNumber(number): Appends the provided number to the current calculation.
        
        •	chooseOperation(operation): Handles the user's choice of arithmetic operation.
        
        •	compute(): Performs the arithmetic computation based on the selected operation.

**3.	Displaying Results:**
        
        •	getDisplayNumber(number): Formats the number for display with a specified number of decimal digits.
        
        •	updateDisplay(): Updates the displayed numbers and operation on the calculator screen.

**4.	Event Listeners:**
        
        •	Event listeners are added to number buttons, operation buttons, the equals button, and the clear/delete buttons.
        
        •	These event listeners call the appropriate methods of the Calculator class and update the display accordingly.

**5.	Initialization:**
        
        •	DOM elements are selected using document.querySelector() and stored in variables.
        
        •	An instance of the Calculator class is created, passing the appropriate DOM elements to it.

**6.	Looping Through Buttons:**
        
        •	The forEach() method is used to loop through number buttons and operation buttons.
        
        •	Event listeners are added to these buttons to handle user input.

**7.	Handling Calculation and Display Updates:**
        
        •	When a number or operation button is clicked, the corresponding methods of the Calculator class are called to update the calculation and display.

**8.	Updating the Display**:
        
        •	After each user interaction, the updateDisplay() method is ca lled to update the displayed numbers and operation on the       calculator screen.
