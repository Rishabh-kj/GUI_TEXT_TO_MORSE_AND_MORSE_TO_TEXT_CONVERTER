# GUI_TEXT_TO_MORSE_AND_MORSE_TO_TEXT_CONVERTER
This repository contains a Python program that converts text to Morse code and vice versa. The program utilizes **Object-Oriented Programming (OOP) principles** for **clear structure** and Tkinter for the **GUI (Graphical User Interface)**, making it easy to use.

**Features: -**
- _Text to Morse Converter_: Converts plain text into Morse code, with each character separated by a space and spaces between words represented by a '/'.
- _Morse to Text Converter_: Converts Morse code back into plain text, with spaces between Morse characters.

**OOP Implementation: -**
The program defines two main classes, Morse and Text, to handle conversions:
- Morse Class: Handles conversion from text to Morse code.
  -> Attributes: -
     - input: The input text string to be converted.
     - morsehashmap: A dictionary mapping each character to its Morse code representation.
     - output: The resulting Morse code string.
  -> Methods: -
     - input_to_morse():  Converts the input text to Morse code, returning an error message if unsupported characters are encountered.

- Text Class: Handles conversion from Morse code to text.
  -> Attributes: -
     - input: The input Morse code string to be converted.
     - texthashmap: A dictionary mapping each Morse code representation to its corresponding character.
     - output: The resulting plain text string.
  -> Methods: -
     - input_to_text(): Converts the input Morse code to plain text, returning an error message if invalid Morse code is encountered.

**GUI Implementation: -**
The graphical user interface (GUI) is implemented using the Tkinter library, providing a simple and intuitive interface for users.

![image](https://github.com/Rishabh-kj/GUI_TEXT_TO_MORSE_AND_MORSE_TO_TEXT_CONVERTER/assets/132807853/1101e509-0bf7-45fe-88f9-dab585538d81)

**Note:** Please ensure that you have Python and Tkinter installed on your system!
  
