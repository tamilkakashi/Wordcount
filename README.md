# Wordcount
Overview
This project is a simple web-based application that identifies and counts repeated words in a given text. It uses JavaScript to process the text, track word occurrences, and display the results in the console.

Features
Word Frequency Analysis: Analyzes the provided text to identify which words are repeated.
Case Insensitivity: Treats words with different casing (e.g., "Test" and "test") as the same.
Console Output: Displays the results in the console for easy viewing.
Prerequisites
A modern web browser (e.g., Chrome, Firefox) to run the HTML file.
Basic knowledge of JavaScript for understanding the code logic.
How to Use
Clone the Repository: Download or clone this repository to your local machine.
Open the HTML File: Open index.html (or whatever you name it) in a web browser.
View Results: Open the browser's developer console (usually by right-clicking and selecting "Inspect" or pressing F12) to see the output of repeated words.
Code Structure
HTML:

Contains a <script> tag where the JavaScript code is implemented.
JavaScript:

The findRepeatedWords function processes the input text to:
Convert the text to lowercase.
Extract words using a regular expression.
Count the occurrences of each word.
Identify and return words that appear more than once.
Customization
Input Text: Change the value of the text variable to analyze different strings.
Regex Adjustments: Modify the regular expression in the match method to customize word extraction (e.g., to include hyphenated words).
License
This project is open-source and available for personal or educational use. Feel free to modify and expand upon it!

Acknowledgments
This application serves as a practical example of string manipulation and data analysis using JavaScript.
