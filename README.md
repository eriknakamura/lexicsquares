# Lexic Squares

The Basic Concept:

Imagine a list with every word in the English language. Now try and take that list and condense it into a shape that takes up the least amount of area when inscribed in a square.

EX.

Take this list with 6 words:
![alt tag](https://raw.githubusercontent.com/eriknakamura/lexicsquares/master/wordListImg.png)

One method of condensing them is to overlap them:
![alt tag](https://raw.githubusercontent.com/eriknakamura/lexicsquares/master/lexicsquares_example.png)

This creates a square that is 13x13 units large.

But there are many other ways in which words can be condensed. For example, the word "assign" already has the words "a", "as" and "ass" within it, so all those words are condensed into the space of only one word.

This square that contains the condensed words is called a lexic square. 

The rules:

- All words from the given list MUST be used
- Words are given in a line-delineated .txt list.
- Answers are submitted in a line-delineated .txt where the first element is the dimensions of the lexic square, and each subsequent word has its coordinates in the square where the top left corner is (0,0). If you have a better way to submit answers, please submit it. Program for calculating score is still in the works, if you would like to help, please do.

The list:
- The list is provided by http://www.mieliestronk.com/
- The list is all lower case
- Theoretically the list does not matter. Any list of unique character sequences can be condensed into a lexic square.
- The current official list is in NOT in American spelling, but again, this does not effect anything. A good lexic square algorithm should be able to produce a lexic square when fed any list.

Scoring:
- A few details on scoring can be found here: [Basic Lexic Square Scoring Theory]
- If you want to contribute to the scoring program, or have any suggestions as to how it should be implemented, please do. 



[Basic Lexic Square Scoring Theory]: https://github.com/eriknakamura/lexicsquares/blob/master/LexicSquareScoring.pdf
