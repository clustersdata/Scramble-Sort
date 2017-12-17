# Scramble-Sort

Scramble Sort

Description

In this problem you will be given a series of lists containing both words and numbers. The goal is to sort these lists in such a way that all words are in alphabetical order and all numbers are in numerical order. Furthermore, if the nth element in the list is a number it must remain a number, and if it is a word it must remain a word.

Input

The input will contain multiple lists, one per line. Each element of the list will be separated by a comma followed a space, and the list will be terminated by a period. The input will be terminated by a line containing only a single period.

Output

For each list in the input, output the scramble sorted list, separating each element of the list with a comma followed by a space, and ending the list with a period.
Sample Input

0.
banana, strawberry, OrAnGe.
Banana, StRaWbErRy, orange.
10, 8, 6, 4, 2, 0.
x, 30, -20, z, 1000, 1, Y.
50, 7, kitten, puppy, 2, orangutan, 52, -100, bird, worm, 7, beetle.
.

Sample Output

0.
banana, OrAnGe, strawberry.
Banana, orange, StRaWbErRy.
0, 2, 4, 6, 8, 10.
x, -20, 1, Y, 30, 1000, z.
-100, 2, beetle, bird, 7, kitten, 7, 50, orangutan, puppy, 52, worm.
