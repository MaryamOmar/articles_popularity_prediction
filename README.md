# Scientific Articles Reads Predicition


## TEAM
- Maryam Omar 
- Sara Altamimi @saraaltamimi12

## OVERVIEW
in this project I'll be building a linear regression model to predicit the popularity of scientific articles. 

## DATA
The data will be scraped form researchgate.net, it will include information about all publications from a single department. I chose the department of social sciences from Loughborough University, becuase they have a solid number of publications and many different authers. 

### source:
https://www.researchgate.net/institution/Loughborough_University/department/Department_of_Social_Sciences/publications

### Description 
the scraped dataset will consist of 1,365 rows and 10 intial columns.

| col | Description | Type |
| --- | --- | --- |
| title | article's title | string 
| auther| auther name | string 
| abstract | abstract full-text  | string
| category| article, literature review, conference paper..etc | string
| date_published | date the article was puplished | date
| date_added | date the article was uploaded to researchgate | date
| figuersCount | number of images in preview | int
| full_text? | avilability of full text ( using download or Request full-text as keywords) | string
| citation | number of times that paper was cited | int
| reads | number of views (target variable)| int



## TOOLS  
- **Scraping:** beautifulsoup, selenium. 
- **Text Mining:** NLTK
- **Modeling:** scikit-learn 
