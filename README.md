# Hangman

Primitive realisation of well-known game Hangman as a problem set of the course
"MITx: 6.00.1x Introduction to Computer Science and Programming Using Python" at edx.org.


Compatibility: Python 3.4+.


The game is interactive and intended to be lauched in a console.
It reads a set of secret words from the included words.txt file.

A user should enter guess letter to move forward.

The final function hangman() has been implemented via three helper functions:

— isWordGuessed(secretWord, lettersGuessed):
  '''
  secretWord: string, the word the user is guessing
  lettersGuessed: list, what letters have been guessed so far
  returns: boolean, True if all the letters of secretWord are in lettersGuessed;
  False otherwise
  '''

— getGuessedWord(secretWord, lettersGuessed):
    '''
    secretWord: string, the word the user is guessing
    lettersGuessed: list, what letters have been guessed so far
    returns: string, comprised of letters and underscores that represents
    what letters in secretWord have been guessed so far.
    '''

— getAvailableLetters(lettersGuessed):
  '''
  lettersGuessed: list, what letters have been guessed so far
  returns: string, comprised of letters that represents what letters have not
  yet been guessed.
  '''