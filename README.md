
# PubMed Scraper for Pharmaceutical/Biotech Authors

This project uses the PubMed API to search for articles and extract detailed information, particularly focusing on articles authored by individuals affiliated with pharmaceutical, biotech, or related industries. The results are then saved into a CSV file, with data such as article metadata, non-academic authors, company affiliations, and corresponding author email addresses.


## Project Overview

The script allows you to:

Search PubMed using a given query.
    Fetch articles that match the query and extract relevant metadata.
    Identify non-academic authors and those affiliated with pharmaceutical/biotech companies.
    Save the extracted data to a CSV file.
This project is primarily aimed at scraping PubMed articles related to the pharmaceutical and biotech industries by filtering out non-academic authors and company affiliations.


## Features

- **Pagination**: The orders table uses pagination to display a fixed number of rows per page, ensuring usability and performance.
- **Sorting**: Allows sorting on the current page for columns like date, time spent, order value, and commission.
- **Responsive**Fully responsive to adapt seamlessly across devices including desktops, tablets, and mobile phones.
- **Server and Client Components**: Demonstrates the use of both server and client components for optimal performance and flexibility.
- **Tailwind CSS**: Used for consistent and efficient styling across all components.

- **Google Ai** Used the Gemini Ai to assist the User for difficulites and chat support to ralated topics.
- **Deployment** Deployed on Vercel for fast and reliable hosting.


## Usage

Once the dependencies are installed, you can use the script by running the main.py file.


## Command Line Usage:
Copy

`pip install -r requirements.txt`

**python main.py <query> [-d] [-f <filename>]
<query>**: The search term you want to query PubMed with (e.g., "cancer immunotherapy").

**-d** or --debug: Optional flag to print debug information for troubleshooting.

**-f** <filename>: Optional flag to specify a filename where the results will be saved as a CSV file. If not specified, the results will be printed to the console.



## Example Commands
**Command Demo**: 

python main.py "cancer immunotherapy"

python main.py "pharmaceutical research" -d

python main.py "biotech" -f biotech_articles.csv





