  CalculatorApp
  This code is for a basic calculator application created using Java’s Swing framework. The app includes a 
  graphical user interface (GUI) with buttons for digits and operations. The user interacts with these buttons to 
  perform calculations.

  Key components:
  1.	GUI Components:
  A JFrame serves as the main window of the application.
  A JTextField is used to display the numbers and results of calculations.
  Various JButton objects represent calculator buttons (numbers, operations, clear, etc.).
  Two JRadioButton components control the on/off state of the calculator.

  2.	Actions:
  The actionPerformed method handles user interactions with the buttons. When a button is clicked, it 
  updates the text field or performs a calculation depending on the button's functionality.

  3.	Radio Button:
  onRadioButton and offRadioButton control the enabling/disabling of all buttons. When the calculator is 
  turned “off,” all buttons are disabled, and when it’s turned “on,” the buttons are enabled.

  4.	Operations: Number buttons (0-9) append digits to the text field.
  The buttonClear clears the display.
  The buttonDelete removes the last character from the display.
  Operations like addition, subtraction, multiplication, and division store the first number and operation in 
  variables.
  Upon pressing buttonEqual, the app performs the operation with the second number.
  The buttonSqrt, buttonSquare, buttonPercent and buttonReciprocal perform specific calculations on the 
  current number.


  5.	State Management: 
  The enable() and disable() methods manage the enabling and disabling of buttons when the calculator is 
  turned on or off, respectively.

  Please find Attached: 
	Calculator image in parent folder 
	Swing CalculatorApp Java file in src folder.
	


  -U23MTE1065 Ayomide John.
