# PDF Merger

A simple Python script to merge multiple PDF files into a single PDF document.

## Description

This project demonstrates how to use `PyPDF2` to combine multiple PDF files into one merged output file.

## Features

- Merges multiple PDFs into a single file
- Prompts the user for the number of PDFs to merge
- Preserves the order of files entered by the user
- Writes the merged result to `merged-pdf.pdf`

## Requirements

- Python 3.x
- `PyPDF2` Python package

## Installation

1. Install Python 3 if it is not already installed.
2. Install the required package:

```bash
pip install PyPDF2
```

## Usage

Run the script from the project folder:

```bash
python PDFMerger.py
```

Follow the prompts:

1. Enter how many PDFs you want to merge.
2. Enter each PDF filename, including extension (for example: `document1.pdf`).

The merged file will be saved as `merged-pdf.pdf` in the same folder.

## Example

```text
How many pdfs do you want to merge?
2
Enter the name of pdf 1: first.pdf
Enter the name of pdf 2: second.pdf
```

Output:

- `merged-pdf.pdf`

## Notes

- Ensure the PDF files exist in the same directory or provide full paths.
- The script uses the order of the files entered by the user.
