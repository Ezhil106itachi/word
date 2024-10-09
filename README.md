# Repeated Words Finder

## Overview

The Repeated Words Finder is a simple web application that analyzes a given text and identifies words that appear more than once. It provides a count of each repeated word, making it useful for text analysis and understanding word frequency.

## Features

- **Case Insensitive**: The program treats words as identical regardless of their case (e.g., "This" and "this").
- **Word Frequency Count**: It counts how many times each word appears in the provided text.
- **Easy Integration**: The function can be easily reused with different texts for repeated word analysis.

## Technologies Used

- HTML
- JavaScript

## How to Use

1. **Open the HTML File**: Save the code as an `.html` file (e.g., `repeated_words_finder.html`) and open it in a web browser.
2. **View Results in Console**: The example text is provided in the code. Open your browser's developer console to see the output of repeated words and their counts.

## Code Explanation

- **Function Definition**: The `findRepeatedWords(text)` function takes a string input (`text`) and processes it to find repeated words.
  - **Text Processing**: The input text is converted to lowercase, and words are extracted using a regular expression.
  - **Word Counting**: An object (`wordCount`) is used to track the frequency of each word as the text is processed.
  - **Identifying Repeated Words**: The function creates another object (`repeatedWords`) that only includes words with a count greater than one.
- **Example Usage**: An example string is provided, and the function is called to demonstrate its functionality. The results are logged to the console.

## Customization

You can customize the following aspects of the program:

- **Input Text**: Change the `text` variable to analyze different strings.
- **Output Method**: Modify the output method to display results on the webpage instead of the console, if desired.

## Conclusion

This Repeated Words Finder serves as a straightforward example of string manipulation and frequency counting in JavaScript. Feel free to experiment with the code to enhance its functionality or integrate it into larger projects for text analysis!
