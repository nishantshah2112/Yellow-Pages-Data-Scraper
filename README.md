# Yellow Pages Data Scraper  

This Python script scrapes **Name**, **Work Description**, and **Phone Number** from **Yellow Pages Australia** for specified categories and locations, saving the data into an Excel file with separate sheets for each category.  

---

## Features  

- Multi-threaded scraping for faster data collection.  
- Handles pagination with a configurable `MAX_PAGES` limit.  
- Saves data in an organized Excel file.  
- Error handling for requests and missing data.  

---

## Requirements  

- Python 3.x  
- Libraries: `requests`, `beautifulsoup4`, `pandas`  

### Install Dependencies  

```bash  
pip install requests beautifulsoup4 pandas  
```  

---

## Usage  

1. Add or modify URLs and categories in the `urls_and_categories` list.  
2. Set the `MAX_PAGES` variable to limit pages to scrape.  
3. Run the script:  

   ```bash  
   python yellow_pages_scraper.py  
   ```  

4. The output file `yellow_pages_data_all_pages.xlsx` will contain the data in separate sheets by category.  

---

## Ethical Considerations  

- Respect Yellow Pages' **terms of service**.  
- **DO NOT misuse data** (e.g., phone numbers) for spam or unethical purposes.  
- Use the script only for **educational, research, or lawful purposes**.  

---

## Disclaimer  

This script is for educational purposes only. The author is not responsible for any misuse. Ensure compliance with laws and website terms.
