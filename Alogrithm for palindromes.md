# Alogrithm for palindromes
To check if any word is a palindrome:
1. Count the number of letters in the string
   * if there is only one, it is a palindrome
   * if not, check that the first and last letters are the same.If not, it isn't a palindrome
   * If they are, it could be a palindrome so then get rid of those two letters and check that the new first and last letters are the same.If not, it isn't a palindrome. If it is then continue this process until you get to one letter or no letters.



### RACECAR:
To check if racecar is a palindrome
* Input racecar: it is more than one letter so continue to check the letters:
* Check that the first and last letter match: R and R, they match 
* Continue checking: A and A match
* C and C match
* There is only one letter (E) left therefore it is verified that RACECAR is a palindrome.

### DEFIED
To check if defied is a palindrome
* Input defied: it is more than one letter so continue to check the letters:
* Check that the first and last letter match: D and D, they match 
* Continue checking: E and E match
* F and I don't match therefore DEFIED is not a palindrome
