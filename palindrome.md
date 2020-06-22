### Way one

1) take the word 
2) split word up in to a list of each letter in the same order as they were in the word 
3) take the last letter in the list 
4) add it to a new list making it the first letter there 
5) loop through list 1 until it is empty
6) convert list 2 back in to string form 
7) compere if the new sequence of letters is identical to the imputed word
8) if yes palindrome, if no not palindrome 

### Way two 

1) take word
2) split word up in to a list of each letter in the same order as they were in the word 
3) count how many values in the list
4) if even number not palindrome 
5) if odd minus 1 then divide by 2, this number is now called x
6) take the last x values 
7) loop through them taking the last value and adding it to the front of a new list 
8) turn list in to string 
9) take first x values of original list, add to new list
10) turn them to string 
11) compere new string 1 and new string 2
12) if they are equal it is a palindrome, if they are not it is not a palindrome
