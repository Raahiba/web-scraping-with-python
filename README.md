## Web scraping in python using BeautifulSoup
Web scraping is the process of extracting the data from websites using relevent Python libraries such as Requests and BeautifulSoup.
In this project the data is scraped from the webpage that conatains a [list of largest companies in India](https://en.wikipedia.org/wiki/List_of_largest_companies_in_India)

The project focuses on extracting tabular data from the webpage and organizing it into a structured format using Pandas.

### Tools and technologies used
* Python
* Requests
* BeautifulSoup
* Pandas
* Jupyter Notebook

### Project stratergy
The main steps followed in the project are :
* **Fetching the HTML page** - An HTTP 'GET' request was send to the website using 'Requests' library in python. The response recieved from the website was stored in response variable. A status code of 200 confirms that the request was successful.
* **Parsing the HTML content** - The HTML content of the page is parsed to extract relevnet information. The BeautifulSoup library was used to extract the required table from the webpage.
* **Extracting table headers and data** - The Table headers were extracted and stored in the list. By using the Pandas library, a DataFrame was created to store the extracted table headers as column names. Then the table rows were fetched and added as records or data entries in the DataFrame.
* **Creating and saving the DataFrame** - The extracted data was stored in the DataFrame for better structure and analysis. The final dataset was saved in the CSV format. 

