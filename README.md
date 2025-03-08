#Automation with Python

## Overview

This project automates an Excel sheet operation using Python. It reads an existing Excel file (`transactions.xlsx`), applies a 10% discount to values in the third column (assumed to be prices), and writes the corrected prices into a new column (fourth column). The modified data is then saved in a new Excel file (`transactions2.xlsx`).

## Requirements

To run this project, you will need the following:
- **Python 3.x**
- **openpyxl** library for working with Excel files

You can install the `openpyxl` library using pip:

```bash
pip install openpyxl
