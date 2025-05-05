# Chatbot for AirExpress FAQ

This project implement simple yet effective chatbot that answers related to airline ticket booking, using natural language processing (NLP) techniques.

## Overview

AirExpress chatbot is trained on a real FAQ dataset from an airlain company. It uses __NLTK__ library to clean (lowering, remove punctuation, stopword filtering) and tokenize data. Moreover, it uses __TF-IDF__ vectorization to convert text data into numerical vectors and than retrieve the most relevant answer to a user’s question due to __Cosine similarity__.

### Technologies Used: 
- Python 3
- Pandas & NumPy
- NLTK
- Scikit-learn (TfidfVectorizer & cosine similarity)


### Example: 
You:Hi

Helper: You can make a new booking by any of the following methods Buy a seat Online at www.airindiaexpress.in Walk into any of Air India Express' airport or city offices to purchase over the counter. Visit one of our approved Travel Agents. You can also book through our 24x7 Call Centre @ 0091-44-40013001

You:infant

Helper: The same procedure has to be applied as is applicable for booking an adult. Infant must be booked with the accompanying adult. The date of birth has to be filled in while making the booking.

You:meal

Helper: You can pre-book your on-board meal 24 hours prior to the departure of your flight.

You:drinks ?

Helper: Air India Express offers pre-set meals varying from hot meals to wholesome snacks to fresh cut fruits (in addition to soft beverages/ tea/ coffee) which can be purchased in advance. We also provide free complimentary snack box with tea/ coffee.

You:bb

Have a good day!
