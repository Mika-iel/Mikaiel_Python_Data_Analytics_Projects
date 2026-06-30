# Countries of the World Web Scraping Project

## Overview

This project demonstrates the process of extracting structured data from a webpage using Python web scraping techniques. The webpage contains information about countries around the world, including country names, capitals, population, and land area.

The objective was to collect unstructured web data, extract relevant information from HTML elements, and transform it into a structured dataset using Python libraries.

The website page this data was scraped from:
https://www.scrapethissite.com/pages/simple/

## Tools Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Jupyter Notebook


## Web Scraping Process

### Extracting Website Data

* A request was sent to the webpage using the Requests library.
* The returned HTML content was parsed using BeautifulSoup.
* HTML elements were inspected to identify patterns and locate the required information.

### Data Extraction

The following information was extracted:

* Country name
* Capital city
* Population
* Area (km²)

* HTML tags and CSS classes were used to locate the relevant information:
  - Country names were extracted from the country-name class.
  - Capital cities were extracted from the country-capital class.
  - Population values were extracted from the country-population class.
  - Area values were extracted from the country-area class.

### Data Transformation

* Extracted values were stored in Python lists.
* The scraped information was converted into a Pandas DataFrame.
* The final structured dataset was exported as a CSV file for further use.


## Final Output

The final dataset contains structured information for countries around the world, transforming webpage content into an analysis-ready format.


# Improvements

Future improvements could include:

* Cleaning and converting population and area columns into numerical data types.
* Adding analysis and visualisations after collecting the data.
