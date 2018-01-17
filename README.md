# hiten-p0
The Data was stores in C:/DSP folder and all subjprojects used this path to access the data
storing data in /user showed unicode error..
stopwords.txt is stored in default /bin location, thus can be directly accessed

#Project A was to count number of words.
The output should be case in-sensitive , thus all characters in Rdd was converted to lower case.
function top(40) creates a list of top most frequent words from sorted elements.

#Project B was to remove stop words.
Thus, stopwords variable was broadcsted and then filtered out from RDD

#Project C was to remove punctuation.
Python punctuation library was import
 x.lstrip(punctuation)) #remove leading punctuaion
 x.rstrip(punctuation)) #remove trailing punctuaion

#Project D

TF-IDF portion, consider a generalization of the key-value paradigm:
keep the words as keys in the RDD, but instead of a single count for the value, store an
array of counts (one for each document).

