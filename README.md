# python
Python exercises

This code implements 2 versions of 6.00 word game. This game is a lot like Scrabble or Words With Friends.
Letters are dealt to players, who then construct one or more words out of their letters. 
Each valid word receives a score, based on the length of the word and the letters in that word.

The rules of the game are as follows:

Dealing

        A player is dealt a hand of n letters chosen at random (assume n=7 for now).

        The player arranges the hand into as many words as they want out of the letters, using each letter at most once.

        Some letters may remain unused (these won't be scored).

Scoring

        The score for the hand is the sum of the scores for each word formed.

        The score for a word is the sum of the points for letters in the word, multiplied by the length of the word, plus 50 points if all n letters are used on the first word created.

        Letters are scored as in Scrabble. 
        
The first version lets the player play by himself, while the second version allows the computer to play as well. 
