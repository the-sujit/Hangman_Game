Before you plan to start the game. Make sure you have following files in a single folder
1. Hangman_Game.ipynb
2. words.txt

The file Hangman_Game.ipynb contains the main block of code. While defining the "load_words()" function, make sure you have given appropriate path to the file "words.txt".

Execute the first block of code.
After that you have to call a function depending upon choice of your game. If you want to play the game with hints, call the function "hangman_with_hints". If you want to continue with normal game, call the function "hangman".

Number of chances you will get will be equal to the length of the word you are asked to guess. If you guessed any alphabet present in the secret word you will retain your chance; if you failed to guess any correct alphabet from the secret word you will loose the chance. If you manage to guess all the alphabets of the secret word without exhausting all the chances you will win. Else you loose.

In hangman with hints, when you guess any alphabet of the word correctly, you will be supplied with list of words which have the alphabet you guessed and also have same length as the secret word. In both versions, you will be given the list of available alphabets you can choose from.

Alright! You are set to play the game. Enjoy!
