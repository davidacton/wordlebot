# wordlebot
Python wordle playing bot

The excellent Wordle game by Josh Wardle can be found here: https://www.powerlanguage.co.uk/wordle/

This is just a simple Wordle bot. It works by establishing all the 'ratings' for the remaining possible solutions that match, and minimizing the size of any one
collection of them. So for example, if your guess receives a rating of '.y..g', you can filter the list of possible solutions to all those words that would
have the same rating if used as guesses. Each round you want to maximize the number of words removed from the list of possible solutions.
