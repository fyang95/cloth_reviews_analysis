# Simple Classifier

The goal of this challenge is to determine the rating people have made on a clothing product based on the review text. You will be given a dataset with features that include the content of the review (i.e. “this dress was great!”), the title, and some data on the people themselves, such as their age. Your goal will be twofold: firstly, determine the rating on a scale of 1-5 what the people gave; and secondly, determine whether or not the people recommended the product.

The basic idea is to use whichever features you want in order to determine the “Rating” and “Recommended IND” columns. The only restriction is that you must not use the “Rating” column to learn the “Recommended IND” values or vice versa.

# Some Constraints:

- Cannot use “Rating” to train model on “Recommended IND” or vice versa
- Solution must be in Python
- Can use sk-learn, keras, etc. but no libraries which build the architecture of the model for you

# After completing:

Please submit your Python code and instructions for how to run it (if required)
