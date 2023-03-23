
# Scraping NLP Research Papers 



This project involves web scraping the Stanford Natural Language Processing (NLP) Group publications page to extract information such as authors, venue, and published year. The extracted information is then cleaned and analyzed to obtain insights about the publications and their authors.

## Dependencies:

To run the code in this repository, you will need the following dependencies:

* Python 3.x
* requests library
* BeautifulSoup library
* pandas library
* matplotlib library

You can install the requests and BeautifulSoup libraries using pip:

```bash
  pip install requests BeautifulSoup matplotlib pandas
```



## Web Scraping:

The Requests library is used to send an HTTP request to the webpage and retrieve the HTML content. The Beautiful Soup library is then used to parse the HTML content and extract the required information. The data is extracted using HTML tags and classes and then stored in a Pandas DataFrame.

## Data Preprocessing :

Once the data was scraped, we used the Pandas library to preprocess the data. We grouped the publications based on the year, venue, and authors to get a better understanding of the trends in the field. We also deleted unnecessary rows from the dataset to make it more manageable.

## Data analysis :

We performed data analysis using various statistical methods provided by Pandas. We found the maximum number of publications done by a single author and the maximum number of publications in a particular venue. We also analyzed the relationship between the number of authors per publication , number of publication per year and number of publication per venue. 


## Data Visualization:

The Matplotlib and Seaborn libraries are used to create various visualizations of the data. A bar plot is used to show the number of publications by venue and a line plot is used to show the number of publications over time. Scatter plot is used to show the relationship between the number of authors and venues per publication .

## Conclusion:

The analysis and visualization of the data provide insights into the publications and their authors. The most prolific authors and venues are identified and the trend of publications over time is visualized. The relationship between the number of authors per publication , number of venues ,and published date is also explored. This information can be useful for researchers and publishers in the field of Natural Language Processing.
