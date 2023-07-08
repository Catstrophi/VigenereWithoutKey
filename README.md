# VigenereWithoutKey
Solving for the vigenere cypher without key and original text


Vigenere Cipher Project Write Up:

Generally, explain your approaches to problem solving.
We mainly used shifting and repeated letters to find the key length. With the key length, we used frequency of each letter to find each key letter. To find the key length we first took every nth letter from the encrypted text and added every large number together and then dividing by the total amount of numbers to find the average of every large nth number. With this what ever nth number has the highest average, has the highest chance of being the key length. By adding every large number of every nth number, we are trying to track how long the key is, since the key is repeated to the length of text, so the most common patterns would be found. With the length we used frequency to find each letter of the key. We first start by taking from the first letter and then every key length from there we multiply the probability of each letter occurring in the encrypted text to the frequency of the letter in the English alphabet. And which every letter has the highest probability we take that number and put it in the ascii table and find the letter. Then for the next key letter we just shift one down, and we repeat that for the remaining letters.

What strategies did you use? Which ones did you end up abandoning?
We finished our code with mainly a statistical approach to this question. We many used the frequency of letter to help find the key letter and key length. We tried to use the greatest common divisor but that really didn’t work because the probability of error from that method was way to high.

What problems did you each help specifically solve?
I mainly solved the math and logic behind the shifting of the encrypted text, in which then we can take every nth letter, find the probability of the letter in the encrypted text and then later on help find each letter of the key.

What problems remain unsolved?
The main problem that is unsolved is how we can make this code work for shorter encrypted text. Because our code relies on probability is really hard to have a low error margin which shorter test.
