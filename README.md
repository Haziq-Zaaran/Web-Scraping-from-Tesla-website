# Web Scraping: Tesla Blog Scraper

Project overview
This project demonstrates my ability to extract structured data from websites using Microsoft Excel's built-in web scraping capabilities. Specifically, it scrapes blog posts from Tesla's website, extracting key details directly into an Excel spreadsheet. The extracted data includes:
•	Headline: Title of the blog post.
•	Date Posted: The publication date of the post.
•	Summary: A brief description of the post content.
•	Link: URL to the full blog post.

This method showcase an alternative to traditional scripting languages, leveraging the power and accessibility of Excel for web scraping tasks.

## Problem Statements
Lithium Company has commissioned me to extract and summarize data from the Tesla website (https://www.tesla.com/), specifically focusing on blog content. The objective is to gather key insights from each post, including the headline, publication date, a concise summary, a detailed description, and a direct link to the original article.
The extracted data is presented in CSV format.
Features
Scrapes tesla’s blog for:
•	Blog headlines.
•	Publication dates.
•	Summaries.
•	Links to full posts.

---

## Tech Stack

- **Microsoft Excel**:
    - `ExtractHTML` and `ExtractXML` functions: For web scraping.
    - Formulae (e.g., `CONCATENATE`): For data manipulation and link construction.

---

## How It Works
1. **Web Query Setup**: Configured Excel's web query feature to target Tesla's blog page.
2. **Data Extraction**: Used `ExtractHTML` and `ExtractXML` functions to parse the HTML structure and extract specific elements (headlines, dates, summaries, and partial URLs) using appropriate CSS selectors or XPath expressions.
3. **Link Construction**: Employed Excel's `CONCATENATE` function to combine the extracted partial URLs with the base Tesla website address, creating complete and functional hyperlinks.
4. **Data Organization**: Formatted the extracted data within the Excel spreadsheet, organizing it into columns for headlines, dates, summaries, and links.

---

## Example Output

*(Include a screenshot of your Excel spreadsheet showing the extracted data)*
![Screenshot 2025-03-16 023730](https://github.com/user-attachments/assets/eb8bfc09-007d-4b6c-8ba7-b9b882b94ae0)


---

## Setup Instructions
1.  **Open Microsoft Excel**.
2.  **Navigate to the Data Tab**: Click on "Data" in the Excel ribbon.
3.  **Get External Data**: Choose the option to "Get External Data" -> "From Web."
4.  **Enter URL**: Input the URL of Tesla's blog (https://www.tesla.com) into the address bar and press Enter.
5.  **Select Data**: Choose the table or specific elements you want to import, using the `ExtractHTML` and `ExtractXML` functions to refine the extraction.
6.  **Load Data**: Load the data into your spreadsheet and use formulas to clean and format the output as needed.
  
**Note:** The exact steps may vary slightly depending on your version of Excel.

---

## Future Improvements
- Automate the scraping process with VBA scripts for scheduled data updates.
- Implement error handling to gracefully manage changes in the website structure.
- Create a user-friendly interface within Excel for easier data extraction and manipulation.

---

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
