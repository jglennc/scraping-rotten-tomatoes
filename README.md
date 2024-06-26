# Scraping Rotten Tomatoes
### Case Description
'Rotten Tomatoes' is a review aggregation website

![](/images/rotten_tomatoes_heading.png)

**The goal** is to extract the informations of each movies as seen in the picture below:

![](/images/data_example.png)

**Note: The number of scraped data should be 140 as what the title suggest**

Data to be scraped:
1. Title
1. Year
1. Score
1. The Critics Consensus
1. Director
1. Cast
1. Synopsis

### Project requirements
* Python version: Python v.3

* Python libraries:

    * pandas
    * requests
    * beautifulsoup

## Data Extraction
[Scraping process can be seen in the jupyter notebook file (click here to open the jupyter notebook)](./scraping-rotten-tomatoes.ipynb)


dataframe containing scraped data:

![](/images/scraped_dataframe.png)

## Exported Data

The scraped data is exported to these files:

* [movies_info.csv](./movies_info.csv)

* [movies_info.xlsx](./movies_info.xlsx)
