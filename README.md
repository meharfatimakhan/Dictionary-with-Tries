# Dictionary with Tries

This code makes use of tries to create a dictionary. A list of words is given for which a dictionary is created. It uses the following functions:



### RecursiveInsert 

The function inserts a word in Trie. It does not insert a word if its prefix is already present in trie as a word


### LoadDictionary 

To load all the words given in “WordsList.txt”


### RecursivePrint 

It prints all the words present in the Trie


### RecursiveSearch 

It will take a word and return true if the word exists in the Trie andfalse otherwise


### SearchPrefix 

It takes a prefix string and prints all the words containing that prefix


### Recursive Delete 

It will be called from Destructor of your Trie and it will delete all the data without any memory leakage
