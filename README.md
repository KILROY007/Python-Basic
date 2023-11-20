# Movie Filtering and PDF Generation

## Project Overview

This project involves filtering a dataset of movies based on various criteria and generating a PDF report for the filtered results. The dataset is stored in a CSV file (`movies_initial.csv`), and the filtering is done based on language, country, IMDb rating, and overall rating.

### Classes

#### `generatePdf`

- Responsible for creating a PDF document using the ReportLab library.
- The `createPdf` method takes a list of data and a heading, then generates a PDF file with the specified heading and content.

#### `filterOptions`

- Handles the filtering of movies based on different criteria.
- Methods include `filterByLanguage`, `filterByCountry`, `ImdbRatingGreaterThan7`, and `RatingGreaterThan1000`.

### Instructions

Follow these steps to run the program:

1. **Install Required Libraries:**
    ```bash
    pip install reportlab
    ```

2. **Prepare the Dataset:**
    - Ensure that the dataset (`movies_initial.csv`) is available and contains the necessary information (title, language, country, IMDb rating, rating).

3. **Run the Script:**
    ```bash
    python script_name.py
    ```
   Replace `script_name.py` with the actual name of your Python script.

4. **Interact with the Program:**
    - Follow the on-screen instructions to choose the filtering criteria.
    - Enter the required information when prompted (language, country, etc.).

5. **View Generated PDFs:**
    - The program will generate PDF files based on the chosen criteria.
    - PDFs will be named according to the filtering criteria (e.g., "Filtered by English.pdf").

6. **Exit the Program:**
    - Choose option 5 to exit the program.

### Additional Notes

- Ensure that the CSV file (`movies_initial.csv`) is correctly formatted with headers like "title," "language," "country," "imdbRating," and "rating."
- The generated PDF files will be saved in the same directory as the script.

Feel free to customize the code and adapt it to your specific needs.
