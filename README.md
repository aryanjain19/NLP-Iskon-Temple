# NLP-Iskon-Temple
### Overview
The aim of this project was to scrap tourists reveiws of Eskon Temple Bangalore from various websites and setup sentiment analysis on the scrapped data to ease drawing out insights from the reveiws and help temple management to act accordingly.  
### Process followed - 
#### Scrapping 
- Scrapped all tourist reviews from about 10 major websites.
- **The positive reveiws greatly outnumbered the negative reviews**, therefore, inorder to balance the positve to negative reviews ratio, some data was duplicated, and some negative reviews about the temples that were based on similar theme were also scrapped.

#### Cleaning and bringing uniformity
- It was found that the reviews collected were written in **multiple languages, mainly including English, Hindi and Kannad. Also, many reviews were written in Hinglish** (Hindi words were written with english alphabets).
All of these reviews were converted to English (and a smart way was found to convert Hinglish to English).

#### Standard NLP and sentimental models (such as Random Forest, XGBoost, SVM and Linears Regression) were implemented to ease drawing concusions and help temple management with future review analysis.

