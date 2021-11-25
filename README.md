# Scientific Articles Reads Predicition



## OVERVIEW
in this project I'll be building a linear regression model to predicit the popularity of scientific articles. 

## DATA
The data will be scraped form researchgate.net, it will include information about all publications from a single department. 
### source:
https://www.researchgate.net

### Description 
the scraped dataset will consist of a minimum of 2000 rows and 8 intial columns.

| col | Description | Type |
| --- | --- | --- |
| title | article's title | string 
| auther| auther name | string 
| abstract | abstract full-text  | string
| category| article, literature review, conference paper..etc | string
| date | date the article was puplished | date
| imageCount | number of images in preview | int
| full_text? | avilability of full text ( using download or Request full-text as keywords) | string
| reads | number of views (target variable)| int



## TOOLS  
- **Scraping:** beautifulsoup, selenium. 
- **Text Mining:** NLTK
- **Modeling:** scikit-learn 
