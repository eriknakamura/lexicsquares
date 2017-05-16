# Lexic Squares

The Basic Concept:

Imagine a list with every word in the English language. Now try and take that list and condense it into a shape that takes up the least amount of area when inscribed in a square.

EX.

Take this list with 6 words:
![alt tag](https://raw.githubusercontent.com/eriknakamura/lexicsquares/master/pics/wordListImg.png)

One method of condensing them is to overlap them:
![alt tag](https://raw.githubusercontent.com/eriknakamura/lexicsquares/master/pics/lexicsquares_example.png)

This creates a square that is 13x13 units large.

But there are many other ways in which words can be condensed. For example, the word "assign" already has the words "a", "as" and "ass" within it, so all those words are condensed into the space of only one word.

This square that contains the condensed words is called a lexic square.

There are more ways to condense words that involve detecting similarities in spelling, frequency of vowels, distribution of vowels, etc. 

But Why Condense?

To see who can create the best condensing algorithm. Also, lexic squares pose an interesting challenge that is the first step in understanding how to create an ideographic dictionary for a large group of words with various levels of connection. The basic lexic square format will group words based on how well they can fit together in a geometric space, however, other factors such as meaning, connotation, and associates can be applied to make some words have a higher affinity for one another. The scoring system would change to not just rank lexic squares by their size, but also by how closely words that are known to have similar meanings and/or connotations are to one another. This would create a map of words, a geometric ideographic dictionary of sorts, where one could find a word, and look around it to find other words that relate. The physical distance between words would be a measure of their association, as opposed to just a ranking that a traditional thesaurus would provide. 

The rules:

- All words from the given list MUST be used
- Words are given in a line-delineated .txt list.
- Answers are submitted in a line-delineated .txt where the first element is the dimensions of the lexic square, and each subsequent word has its coordinates in the square where the top left corner is (0,0). If you have a better way to submit answers, please submit it. Program for calculating score is still in the works, if you would like to help, please do.

The list:
- There are several lists to play with as of right now, a 100, 1000, and 3000 words list sourced from Education First at http://www.ef.edu/
- The list is all lower case
- Theoretically the list does not matter. Any list of unique character sequences can be condensed into a lexic square.
- I'm working on putting together some longer lists. 
- The Java application lexicSquareListEditing has some list editing features that DO NOT ALL WORK, the only feature on it I trust is the word and letter count features (option 4 in the menu).
- See the files for the lists.

Scoring:
- A few details on scoring can be found here: [Basic Lexic Square Scoring Theory]
- If you want to contribute to the scoring program, or have any suggestions as to how it should be implemented, please do. 



[Basic Lexic Square Scoring Theory]: https://github.com/eriknakamura/lexicsquares/blob/master/LexicSquareScoring.pdf
