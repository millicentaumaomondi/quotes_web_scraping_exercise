# Web Scraping Practise Exercise

This project demonstrates web scraping using Python to collect quotes from [quotes.toscrape.com](https://quotes.toscrape.com/), save them to a CSV file, and then read the dataset.

## Project Structure

- `scraper_python.py` — Scrapes quotes from the website and saves them to `scraped_quotes.csv`.
- `scraped_quotes.csv` — The dataset containing scraped quotes, authors, and tags.
- `read_dataset.py` — Reads and analyzes the CSV dataset using pandas.
- `requirements.txt` — Lists required Python packages.

## Setup
1. **Create a virtual environment:**

   - **Mac/Linux:**
     ```sh
     python3 -m venv venv
     source venv/bin/activate
     ```
   - **Windows:**
     ```sh
     python -m venv venv
     venv\Scripts\activate
     ```

2. **Install dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

3. **Run the scraper:**

   ```sh
   python scraper_python.py
   ```

   This will create/update `scraped_quotes.csv`.

4. **Analyze the dataset:**

   ```sh
   python read_dataset.py
   ```

## Requirements

- Python 3.x
- See `requirements.txt` for required packages.

## Notes

- The scraper targets [quotes.toscrape.com](https://quotes.toscrape.com/).
- The dataset includes quote text, author, and tags.

## License

This project is for educational purposes.