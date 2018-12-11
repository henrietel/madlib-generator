# madlib-generator
This is a toolbox for a madlib generator. It takes in string inputs with words to be filled in and returns with randomly chosen words from a chosen dictionary of words. It consists of functions for word replacement, fixing capitalization, and storing and removing punctuations. These functions can be used seperately on strings or combined to act as a madlib generator.
The functions and test_functions modules have more information on exactly how the code works.
 
Grammar Tools: 
- remember_punc: Stores punctuations at end of a string.
- remember_ends: Stores the last punctuation of a string.
- remove_ends: Removes the last punctuation of the string.
- cap_sentences: Fixes capitalization for characters following an indicated punctuation.
- fix_all_caps: Fixes capitalization for strings containing the normal sentence endings "!", "?", and ".".
    
Madlib Tools:
- choose_num: Randomly chooses a number within given bounds. Returns integer as a string.
- replace_words: Replaces indicated words with a randomly selected number word in a list from genre dictionary. 
- madlib: A function to fill in madlibs.


Happy Madlibbing!!
