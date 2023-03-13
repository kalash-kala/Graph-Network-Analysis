# Graph Network Analysis

## What I have used in this project :

- Selenium for Web Scraping
- Spacy for Named Entity Recognition (NER)
- Pandas to store the characters, the Source - Target Relationship between the characters and the weights associated with them
- Pickle to store the entire Acts and Scenes dictionary in the system so that we don’t have to web scrape again and again
- Netwrokx to plot the Relationship Graph between Characters

## Aim of the project :

- To understand the dynamics of Characters in the Merchant of Venice. I have done this for the entire Drama, but this can also be extended to Scene wise analysis if one wishes to understand how the dynamics is built among the characters
- To find an application of Named Entity Recognition in identifying character names
- To get comfortable with web scraping using selenium

<aside>
🗨️ If you are interested in only the Graph Analytics part then you can directly use the preprocessed file that I have created by web scraping. You can directly use read_csv() function for the character.csv file , for the “All acts and scenes Dictionary” you need to used the pickle load() function

</aside>

The MOV.html file contains the PYVIS graph that was created from the Graph Analysis