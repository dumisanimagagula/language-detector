# Language Detector

![Language Detector](https://img.shields.io/badge/Python-3.6%20%7C%203.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue)

## Overview

The **Language Detector** is a Python project that utilizes the `langdetect` module to identify the language of text input. This can be extremely helpful when you have text data but are unsure of the language it's written in. The project provides a simple Graphical User Interface (GUI) built with tkinter, featuring labels, buttons, and an entry field. Users can input text, and upon clicking the "Check Language" button, the program will use the `langdetect` module to determine the language and display the result in the GUI.

Please note that the results returned by `langdetect` are in abbreviated language codes. For example, if you input English text, you will see 'en' as the return value.

## Prerequisites

Before running the project, ensure you have the `langdetect` module installed. You can install it using pip:

```bash
pip install langdetect
```

## Usage
1. Clone or download this repository to your local machine.

2. Open a terminal and navigate to the project directory.

3. Run the app.py script:

```bash
python app.py
```
4. The GUI will appear, titled "Language Detector."

5. Enter the text you want to detect the language for in the provided entry field.

5. Click the "Check Language" button.

6. The detected language code will be displayed on the GUI

## Dependencies
- `langdetect`: A Python module for language detection. You can install it using pip.

**Enjoy language detection with ease!** If you have any questions or encounter issues, feel free to reach out. Contributions and feedback are welcome.