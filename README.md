# A2 Bias in Data
Name: Daniel White

Date: November 1st, 2018

## Goal
The purpose of the assignment is to assess bias amongst countries based on the number of Wikipedia articles written about political figures. The analysis assesses both the number of articles and the quality of those articles using the ORES API. Several tables and charts are created to assess which countries may be overrepresented and which may be underrepresented. The analysis is performed in the accompanying Jupyter notebook entitiled 'hcds-a2-bias'.


## Resources used
This analysis was prepared using Python 3.5 running in a Jupyter Notebook environment. The documentation for each can be found below:

Python: https://docs.python.org/3.5/

Jupyter Notebook: http://jupyter-notebook.readthedocs.io/en/latest/

The Jupyter notebook primarily uses the following Python packages:

* requests
* json
* pandas
* numpy
* matplotlib

The documentation can be found on their respective documentation pages.

## API Documentation

The assignment collects article quality data using the ORES API which is located here: https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context_revid_model

Additional background information on the API is also available here: https://ores.wikimedia.org/

## Assignment Data

The csv file containing the processed data is located in the data/ folder and is named wiki_article_quality_population_data.csv. The columsn and data types are listed below.

|Column | Value |
|-------|-------|
|article_name   |	string|
|article_quality	| string|
|country|	string|
|revision_id|	string|
|population|	string|
|high_quality|	int (indicator)|

The data folder also contains the raw population data (WPDS\_2018\_Data.csv) and the Wikipedia page data (page_data.csv).

The data are available for download:

Population Data - https://www.dropbox.com/s/5u7sy1xt7g0oi2c/WPDS_2018_data.csv?dl=0
Wikipedia Page Data - https://figshare.com/articles/Untitled_Item/5513449

## License
The assignment code is released under the MIT License.
