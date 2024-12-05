# -web-scraping-and-data-analysis-project
For this module in Deliverable 1, I followed the steps to scrape the Mars News website as required.

For Deliverable 2, in step 3, I used ChatGPT to help create a list of rows using the following code:
for row in rows:
    columns = row.find_all('td') 
    row_data = [col.text.strip() for col in columns]
    data.append(row_data)
    
ChatGPT also assisted me in creating the plot to identify the coldest and hottest months.    
