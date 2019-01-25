# Daily Poems Scrapper

## What is this?

This is a web scrapper that feeds on [http://poems.com/today.php] to get a poem (different everyday), and exports it to PDF.

## To-Do

- Create a PDF document using FPDF

## How to run

1. Execute `bootstrap.sh` to create the virtualenv folder and install dependencies
2. Execute `app.py` to get your poem

## What did I learn in this project?

- How to use virtual environments with `venv`
- How to use `requests` to get raw HTML from web pages
- How to use `BeautifulSoup` to wrangle data from HTML
- How to print in colors to the console
- How to generate a PDF document using `FPDF`