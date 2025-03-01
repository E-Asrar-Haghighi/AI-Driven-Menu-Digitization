# Automating Menu Digitization using Generative AI

## Overview

This project is part of an initiative to **automate menu digitization** using Generative AI. The goal is to convert menu images into structured Excel files, enabling seamless uploads into digital platforms. This enhances efficiency, reduces manual data entry errors, and accelerates the onboarding process for restaurant partners.

## Features

- Converts PDF files to images for easier processing.
- Uses AI-powered OCR for accurate text extraction from images.
- Converts menu data into a structured Excel format.
- Supports batch processing for multiple images in a directory.
- Handles multiple image formats (JPG, PNG, etc.).
- Ensures data accuracy and consistency.

## Installation

### Requirements

Ensure you have the following dependencies installed:

```bash
pip install openpyxl
```

If using Google Colab, install required libraries using:

```bash
!pip install openpyxl
```

## Usage

### Convert Images to Excel

Run the `Image_to_Ecxel_GenAI.ipynb` notebook to extract text from images and save it in an Excel file.

```python
from Image_to_Ecxel_GenAI import images_to_excel
images_to_excel("path/to/image/folder", "output.xlsx")
```

## Notes

- Ensure the images are stored in the correct directory before running the script.
- Supports multiple formats like PNG, JPG.
- Exception handling is included to skip unreadable files.
- Standardized formatting ensures seamless integration with digital menus.

## License

This project is licensed under the MIT License.

## Author

Created by Ebrahim Asrarhaghighi as a practice of RAG, AI Agents and Generative AI with Python and OpenAI 2025 course from Udemy

