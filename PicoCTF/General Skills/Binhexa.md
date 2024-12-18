2024-12-18
14:37
#easy #General_Skills

## Description
How well can you perfom basic binary operations?Start searching for the flag here `nc titan.picoctf.net 57401`

## Steps Taken
1. nc into machine
2. Perform a right shift of Binary Number 2 by 1 bits
	1. remove the last bit
3. Perform the operation on Binary Number 1&2
	1. only put a 1 if there is 1 in both numbers
4. Perform a left shift of Binary Number 1 by 1 bits
	1. add a zero to the end
5. Perform the operation on Binary Number 1x2
	1. multiple the numbers
6. Perform the operation on Binary Number 1+2
	1. add the numbers
7. Perform the operation on Binary Number 1|2
	1. if it has a 1 put a 1
8. Enter the results of the last operation in hexadecimal
	1. run last number through a [hexadecimal converter](https://www.rapidtables.com/convert/number)
9. Flag: **picoCTF{b1tw^3se_0p3eR@tI0n_su33essFuL_6862762d}**
