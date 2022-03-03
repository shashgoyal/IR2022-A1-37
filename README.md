# name-IR2022-A1-GroupNo-37
Information retrieval Assignment 1

# Preprocessing : #
For preprocessing, firstly we read the entire text files and remove all the \n, meaning we remove the next line and replace it with " " so that all the text is present in a single line. 
Then we put all the words into lower case
after that we remove all stop words from the text and tokenize the string.
We remove all special characters and digits and punctuation marks from tokens etc.
After all this you are left with tokens of preprocessed data in the form of lists and dictionaries.

# Methodology : #
For methodology we save the name of the text file and the DocID in a dictionary and the tokens to their DocID in another dictionary. We then run loops and find out the dooc Id,s of the preprocessed input and ask the user for the operations input.
For X and Y: we return an intersection of two lists while comparing them from the start so that their order is maintained
For X or Y: we return an union of two lists while comparing them from the start so that their order is maintained
For X or not Y : We do the operations in an ordered format
For X and not Y: we do the same

Question 2:
For question 2 we make a nested dictionary in order to store the positional index of each and every word post preprocessing.
