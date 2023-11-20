Movie Filtering and PDF Generation
Project Overview
This project involves filtering a dataset of movies based on various criteria and generating a PDF report for the filtered results. The dataset is stored in a CSV file (movies_initial.csv), and the filtering is done based on language, country, IMDb rating, and overall rating.

The program consists of two main classes:

generatePdf:

This class is responsible for creating a PDF document using the ReportLab library.
The createPdf method takes a list of data and a heading, then generates a PDF file with the specified heading and content.
filterOptions:

This class handles the filtering of movies based on different criteria.
Methods include filterByLanguage, filterByCountry, ImdbRatingGreaterThan7, and RatingGreaterThan1000.
The main script (main()) provides a user interface to interact with the program. Users can choose to filter movies based on language, country, IMDb rating greater than 7, or overall rating greater than 1000. The filtered results are then used to generate a PDF report.
