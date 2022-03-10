# TASK 1

Write a simple function that takes a string as its argument and returns true if it's palindrome and false otherwise (Note: a palindrom is a word that reads the same in both directions, such as "MADAM" or "TOOT". You should not use function such String.Reverse.)

# TASK 2

Simulate the Game "Rock, Paper, Scissors" Create a function which simulates the game "rock, paper, scissors". The function takes the input of both players (rock, paper or scissors), first parameter from first player, second from second player. The function returns the result as such:

"Player 1 wins" "Player 2 wins" "TIE" (if both inputs are the same) The rules of rock, paper, scissors, if not known:

Both players have to say either "rock", "paper" or "scissors" at the same time. Rock beats scissors, paper beats rock, scissors beat paper. Examples rps("rock", "paper") ➞ "Player 2 wins"

rps("paper", "rock") ➞ "Player 1 wins"

rps("paper", "scissors") ➞ "Player 2 wins"

rps("scissors", "scissors") ➞ "TIE"

rps("scissors", "paper") ➞ "Player 1 wins"

# TASK 3

Given an integer, return "odd" if the sum of all odd digits is greater than the sum of all even digits. Return "even" if the sum of even digits is greater than the sum of odd digits, and "equal" if both sums are the same.

Examples

oddsVsEvens(97428) ➞ "odd"

// odd = 16 (9+7)

// even = 14 (4+2+8)

oddsVsEvens(81961) ➞ "even"

// odd = 11 (1+9+1)

// even = 14 (8+6)

oddsVsEvens(54870) ➞ "equal"

// odd = 12 (5+7)

// even = 12 (4+8+0)
