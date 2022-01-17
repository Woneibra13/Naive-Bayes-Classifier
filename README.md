# Naive-Bayes-Classifier Project
This projects selects the top positive and negative words from a collection of collection of 900 
positive movie reviews and 900 negatives ones.

# Approach
A frequency dictionnary was created for positive and negative words, and each of the words was given a frequency
score for positivity and negativity. The following formula was used: 

- Negativity score = log2(( word frequency in neg reviews * total reviews)/((word frequency in neg reviews + word frequency in pos reviews)* total negative words))
- Positivity score = log2(( word frequency in pos reviews * total reviews)/((word frequency in neg reviews + word frequency in pos reviews)* total positive words))
