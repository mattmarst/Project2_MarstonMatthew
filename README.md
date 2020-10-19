# Project-2

## Hangman Description
The hangman program begins by choosing an encrypted word from a preset list, and creates a list with each letter as an element. It then establishes word length, lives, and correct guesses variables. It also creates lists for letters used and current word. While the user has more than one life and the word length is greater than the correct number of guesses, the program countinually asks for input letters. Before doing so the program tells the user their lives count, letters they've guessed, what the word looks like with the letters they've guessed, and whether or not the letter they guessed is in the word or if they have guessed it already. If the user guesses all letters correctly the program congratulates them and displays the word in both encrypted and decrypted form using the decrypt function below.

## Decrypt Description
The Decrypt function decrypts words used in the hangman program. It initially, creates a cypher list with each letter of the encrypted word as an element, and a plain list that will be used later on. It then examines each letter in its ascii form and adds or subtracts 1 from each depending on its position in the word. The ascii value is then converted to its character form and is appended to the plain list. Finally, it converts the plain list to a string and returns it. 
