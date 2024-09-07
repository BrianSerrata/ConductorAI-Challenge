# ConductorAI Challenge

This repository contains a solution to the ConductorAI Challenge, including two main functions that answer Part 1 and Part 2 of the challenge. The challenge data is provided in PDF files located in the `Data/` folder.

## Running the Notebook

To run this project, you need to execute each cell in the Jupyter notebook **sequentially and in order**.

### Key Functions:

- **Part 1:**
    - Function: `get_highest_value_in_pdf(pdf_path)`
    - This function processes a given PDF and returns the highest value found in the PDF file for **Part 1** of the challenge.

- **Part 2:**
    - Function: `get_greatest_number_in_pdf(pdf_path)`
    - This function processes a given PDF and returns the greatest number found in the PDF file for **Part 2** of the challenge.

### Instructions:

1. **Execute All Helper Functions First:**
    - Before running the main functions (`get_highest_value_in_pdf()` or `get_greatest_number_in_pdf()`), make sure to run all the cells that define the **helper functions**.
    - These helper functions are essential for processing the data from the PDF files and ensuring the main functions work correctly.

2. **Run the Main Functions:**
    - After all helper functions are executed, you can run the two main functions with the appropriate `pdf_path`.

3. **Testing Other PDFs**
    - To test other pdfs, simply upload your pdf to the **Data** folder, and adjust `pdf_path` accordingly in the cells where            
      (`get_highest_value_in_pdf()` or `get_greatest_number_in_pdf()`) are run.

### Project Structure:

```plaintext
ConductorAI-Challenge/
│
├── Data/               # Folder containing the PDF data files
│   ├── example1.pdf
│   ├── example2.pdf
│   └── ...
├── ConductorAI-Challenge.ipynb   # Jupyter notebook with the solution
├── README.md           # This README file
└── .gitignore          # Gitignore file to exclude unnecessary files
