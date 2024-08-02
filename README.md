# PythonCodeFormatter - @T7C

## Introduction

PythonCodeFormatter is a versatile tool designed for formatting and analyzing Python code. This tool utilizes `autopep8` for code formatting and offers functionality to export formatted code to various formats including images, Word documents, and Markdown. It also provides insights into code dependencies, complexity, and unused code segments.

## Features

- **Code Formatting:** Automatically formats Python code using `autopep8`.
- **File Saving:** Save formatted code to `.txt`, `.docx`, or `.md` files.
- **Export to Image:** Export formatted code as an image using a headless Chrome browser.
- **Code Analysis:** Analyze code to identify dependencies, calculate cyclomatic complexity, and detect unused code segments.
- **Detailed Reporting:** Generate detailed reports on the number of classes, functions, and variables in the code.

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/lysandraBars/python-code-formatter.git
    cd python-code-formatter
    ```
    
## Usage

1. **Run the script:**

    ```sh
    python pyformat.py
    ```

2. **Input Code:**

    - Enter your Python code in the terminal. Press `Ctrl+D` (Linux/Mac) or `Ctrl+Z` followed by `Enter` (Windows) to end code input.

3. **Post-Formatting Options:**

    - Press `c` to copy the formatted code to the clipboard.
    - Press `s` to save the formatted code to a file.
    - Press `p` to export the code as an image or Word document.

4. **Export Options:**

    - **Image:** Press `i` to export the code as an image.
    - **Word Document:** Press `w` to export the code as a Word document.

5. **Exit:** Press `q` to exit the program.

## Notes

- **Chrome Installation:** Exporting code as an image requires Chrome and `webdriver_manager` for automatic driver management.
- **Performance:** Exporting code as an image may take time depending on the code size and system performance.

## Common Issues

- **File Saving Errors:** Check file permissions and path validity.
- **Clipboard Copy Errors:** Ensure `pyperclip` is properly installed and functioning.
- **Image Export Errors:** Verify that Chrome and the Chrome driver are correctly installed.

## Logging

- Errors and notifications are logged in `code_formatter.log` in the same directory as the script.

## Dependencies

- `autopep8`
- `pyperclip`
- `pygments`
- `selenium`
- `webdriver_manager`
- `radon`
- `rich`
- `docx`


## Contact

- Gmail: tranminhtan4953@gmail.com
- Telegram: t.me/tanbaycu

## Documentation

- [autopep8](https://pypi.org/project/autopep8/)
- [pyperclip](https://pypi.org/project/pyperclip/)
- [pygments](https://pygments.org/)
- [selenium](https://www.selenium.dev/)
- [webdriver_manager](https://pypi.org/project/webdriver-manager/)
- [radon](https://radon.readthedocs.io/)
- [rich](https://rich.readthedocs.io/)
- [docx](https://python-docx.readthedocs.io/)

