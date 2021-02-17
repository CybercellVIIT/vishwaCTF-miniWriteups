Title : yeeeeeet

Category : Cryptography

Description : yeet yeeted with yeet equals nothing.

Hints : None

Files : yeet.txt

Points : 100

Solves : 1

Flags : VishwaCTF{y33t_y33t_y33t}

## Solution 

1. As the description suggests yeet yeeted with yeet equals nothing. This can be interpreted as an xor function as a number xor itself is always zero. That was the clue given to solve the question
2. So all you have to do is xor the yeet.txt file with the binary of the word yeet and then convert the output back to text to get the flag.
