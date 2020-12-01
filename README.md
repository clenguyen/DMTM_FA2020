# Data Mining and Text Mining Final Project 
CAP4770.01 | Fall 2020 | Florida Polytechnic University
Cindy Nguyen | Isabel Zimmerman | Luiz Gustavo Fagundes Malpele

### Project Description:
This project provides text mining and analysis from COVID-19 tweets found in [this dataset](https://www.kaggle.com/datatattle/coronavirus-tweets). This analysis utilizes tf-idf, LDA, and n-grams in order to create a better understanding of the feelings towards the novel coronavirus from March 16, 2020 to April 14, 2020. Conclusions include that the sentiment is largely regionally based. Future work on this project could explore sentiment drift further into the year. 

### Data
The data pulled from Kaggle dataset [here](https://www.kaggle.com/datatattle/coronavirus-tweets) offers:
- `User_name`: deidentified as a number
- `Time`: dates in the form of DD-MM-YYYY dates
- `Location`: self-identified user location from twitter bio
- `text`: the tweet itself

For this analysis, the primary analysis uses  `text` to gather a sentiment overview. This data is stripped of punctuation, other tagged users, excape characters, and links in order to ensure data quality. 

### Team members: 

- [Isabel Zimmerman](mailto:izimmerman5298@floridapoly.edu)
- [Cindy Nguyen](mailto:cnguyen5356@floridapoly.edu)
- [Luiz Gustavo Fagundes Malpele](mailto:lfagundesmalpele664@floridapoly.edu)


