# Pyshield

## Overview

- **Pyshield** is a Python tool designed to obfuscate Python scripts by encoding and encrypting them. It allows you to transform your Python code into an obfuscated form, which can help in hiding the logic of the script and potentially evade basic static analysis.

## Features

- **Python Code Obfuscation:** Converts Python code into a base64-encoded and XOR-encrypted format to make it harder to understand.
- **Simple CLI Interface:** Provides an easy-to-use command-line interface for inputting code and generating obfuscated output.
- **Customizable Output:** Allows specifying the output file name for the obfuscated code.
- **Base64 Encoding & XOR Encryption:** Utilizes base64 encoding combined with XOR encryption for added obfuscation.


1. **Run the Script:**

    ```bash
    python3 Pyshield.py
    ```

```
Welcome to Pyfuscator!
Enter your python code to obfuscate (leave empty for program path): 
Enter your python program path: hello.py
Enter your obfuscated program name (default obfuscate.py): hello-obf.py
Obfuscated program has been saved as hello-obf.py 
```

2. **Enter Input Parameters:**

   - **Python Code:** Enter the Python code you wish to obfuscate directly or provide the path to a Python script file.
   - **Obfuscated Program Name:** Specify the name of the output file for the obfuscated code (default is `obfuscate.py`).

3. **Output File:** The obfuscated Python code will be saved in the specified output file.

## Requirements

- Python 3.x
- `colorama` module

## Installation

Ensure you have the required dependencies:

```bash
pip3 install colorama
```

## Example

Run the script:

```bash
python3 Pyshield.py
```

When prompted:

```
Enter your python code to obfuscate (leave empty for program path):
Enter your python program path:
Enter your obfuscated program name (default obfuscate.py):
```

The script will generate an obfuscated Python file with the name you specified.
