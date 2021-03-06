# practice-python
A collection of practice exercises I have completed from MIT 6.00.1X and www.practicepython.org

## MIT 6.00.1X
### [Hangman](https://github.com/Doanvin/practice-python/tree/master/MIT%206.00.1X/ps3)
### [Word Game (run ps4b.py)](https://github.com/Doanvin/practice-python/tree/master/MIT%206.00.1X/ps4)
#### The rules of the game are as follows:

Dealing

* A player is dealt a hand of n letters chosen at random (assume n=7 for now).

* The player arranges the hand into as many words as they want out of the letters, using each letter at most once.

* Some letters may remain unused (these won't be scored).

Scoring

* The score for the hand is the sum of the scores for each word formed.

* The score for a word is the sum of the points for letters in the word, multiplied by the length of the word, plus 50 points if all n letters are used on the first word created.

* Letters are scored as in Scrabble; A is worth 1, B is worth 3, C is worth 3, D is worth 2, E is worth 1, and so on. We have defined the dictionary SCRABBLE_LETTER_VALUES that maps each lowercase letter to its Scrabble letter value.

* For example, 'weed' would be worth 32 points ((4+1+1+2) for the four letters, then multiply by len('weed') to get (4+1+1+2)*4 = 32). Be sure to check that the hand actually has 1 'w', 2 'e's, and 1 'd' before scoring the word!

* As another example, if n=7 and you make the word 'waybill' on the first try, it would be worth 155 points (the base score for 'waybill' is (4+1+4+3+1+1+1)*7=105, plus an additional 50 point bonus for using all n letters).

## Practice-Python.org
### [Bull Cow Game](https://github.com/Doanvin/practice-python/blob/master/org/18.py)
#### Rules
* A 4-digit number is randomly generated, try to guess it. 
* For every digit you guessed correctly in the correct place, you have a “cow”. 
* For every digit you guessed correctly in the wrong place you have a “bull”. 
* Every time you make a guess you will be told how many “cows” and “bulls” you have. 
* Once the user guesses the correct number, the game is over. 
* The number of guessed you took will be printed at the end.
### [Basic Web Scraping](https://github.com/Doanvin/practice-python/blob/master/org/21.py)
