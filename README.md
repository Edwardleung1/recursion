# recursion
Define a recursive function isEven corresponding to this description. The function should accept a single parameter (a positive
, whole number) and return a Boolean.

Test it on 50 and 75. See how it behaves on -1. Why? Can you think of a way to fix this?

The reason it is n-2 because it is taking the number and substracting 2 until it is either a zero or an one, therefore giving 
us a true or false answer.

It does this by going back to the top of the function with the number that was inputed initially but 2 less than before and it 
will keep doing that until the number is 1 or 0 and then it will be able to return the boolean true or false (even or odd).
