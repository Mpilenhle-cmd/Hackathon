# Hackathon
Predicting the type of language in South Africa using machine learning


With the problem requiring us to differentiate the type of Language Each And every text is represented in.
The best option for this problem is to go for the Bag of word system for features, cause I believe every
word in a language is important, and as there are simillar words in the South African Language that are used 
by different languages. That means a use of ngrams can be really helpful.

The SVC Linear and the Naive Bayes show great perfomance, they actually stand out from others. I chose to investigate
further about their perfomance. I used the Grid Search to find the best C and best Gamma, I used alpha for the Naive Bayes. With a great perfomance from the SCV Linear it was not too well compared to the Naive Bayes of alpha 0.5. And with the use of tfidf Vector I manged to get rid of data with min_df of 2, and a max_df of 0.8 the perfomance really got better

Thus the best choice is the Naive Bayes So far
