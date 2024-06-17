
# website-data-extractor

A Python project to scrape payment gateways and social media links from websites and store the data into mysql.



## Requirements
- Python 3.x
- MySQL

 **Install necessary libraries:**
```bash
pip install requests beautifulsoup4 mysql-connector-python
```
**MySQL Database Setup:**
    - Run the provided SQL script to create the database and table.

**Configure MySQL Connection:**
    - Update the `store_data_in_db` function in the `source_code.ipynb` file with your MySQL credentials.

**Run the python file:**
- Add the websites you want to scrape to the `sites` list .
- Run the python code in any jupyter notebook

- The script scrapes websites for:
  - Social media links
  - Tech stack
  - Meta title
  - Meta description
  - Payment gateways

- Extracted data is stored in a MySQL database as:
  <img width="596" alt="Screenshot 2024-06-17 171653" src="https://github.com/Aman-Gautam1/website-data-extractor/assets/84891232/da2046f9-6d5c-4f9e-9c61-d31f9b5e0097">



