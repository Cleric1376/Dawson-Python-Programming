# Michael Dawson Python Programming
Michael Dawson Python Programming

Chapter 4, task 1
Solved with a For loop

Chapter 4, task 1b
same problem solved with a While Loop

Chapter 4, task 2
Solved with indexing trick "[: : -1]"

Chapter 4, task 2b
same problem solved with a While Loop

Chapter 4, task 3
solved

Chapter 4, task 4
solved

Chapter 5, task 1
solved with a While Loop and two lists, the first (alist) contains words, the second(new_list) is empty
each iteration we'll take a random word from the alist, to add in new_list, and delete it from alist
so after all iterations our alist will be empty and condition of While loop will become False

Chapter 5, task 1(second version)
solved with a For Loop, indexing, and an append method feature that adds new item to the end of list
each iteration we'll make a random number which we intend to use as an index number, then we use append method which
adds the randomly choosen word from list to the end of list, at the end of the iteration we delete the first randomly
choosen word, that's why at the begining of new iteration we have the same number of words in the list

Chapter 5, task 2
solved with a While Loop for Main User's Menu and the second While Loop inside the first for sub
menu to distribute points to specified characteristics. For redistribution of points and setting points to initial state,
it was used the dictionary method "dictionary.update(another_dictionary)"

Chapter 5 task 3 was solved by creating a dictionary, a While Loop for creating a popup game menu and defensive technique (as shown by Dawson). Defensive technique is before any alteration of dictionary we check if the key really exists by expression ( if son_name in dictionary.keys()).

Chapter 5 task 4 Improved version of previous program, now "Who's your father" is able to print a name of grandfather. Other functionality are the same as in previous task 3. Solved with a creation of dictionary key based on dictionary value (grandfather = family[grandson], so we make a key from a value). Plus used dictionary.get() method to avoid errors.
