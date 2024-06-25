# Data Sourcing Challenge

Welcome to the Data Sourcing Challenge repository. This project involves interacting with two APIs (New York Times API and The Movie Database API), merging their data, and preparing it for export.

## Assignment Overview

This challenge consists of three main parts, each building on the previous one:

### Part 1: Access the New York Times API

1. **Setup**: Ensure your API keys are stored in a `.env` file.
2. **Implementation**: Use the provided base URL and parameters to fetch movie reviews from the New York Times Article Search API.
3. **Handling Pagination**: Retrieve multiple pages of reviews (up to 200 reviews) and handle rate limits using a try-except clause.
4. **Data Transformation**: Convert JSON data into a Pandas DataFrame, extract movie titles, and prepare for the next API call.

### Part 2: Access The Movie Database API

1. **Query Preparation**: Construct URLs to search for movies and retrieve movie details from The Movie Database API.
2. **Retrieve Details**: Iterate through the list of movie titles, perform searches, fetch movie IDs, and retrieve detailed movie information.
3. **Rate Limit Management**: Manage API rate limits with delays and counters to ensure compliance.
4. **Data Processing**: Extract and structure movie details such as genres, languages, and countries into a DataFrame.

### Part 3: Merge and Clean the Data for Export

1. **Merge DataFrames**: Combine data from New York Times reviews and The Movie Database based on movie titles.
2. **Data Cleaning**:
   - Convert columns with list data (genres, languages, countries) into string format.
   - Remove unwanted characters from these columns.
   - Handle duplicates and reset index if necessary.
3. **Export**: Export cleaned and merged data to a CSV file without including the index.

## Usage

1. Clone this repository to your local machine.
2. Set up your API keys in a `.env` file following the provided format.
4. Execute the Python script sections as needed.
5. Review console outputs and generated CSV files for results.

## Author
Howard P. Dixon



