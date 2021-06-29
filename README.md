# File-Compression-Calculator
## OVERVIEW
This project takes the frequncies of the various chracters as input. It then calculates the codes of each individual chracter by using Huffman EnCoding and prefix codes.
it then displays the frequencies of each and every character in the **PREORDER TRAVERSAL** of the constructed Tree.
It then calculates the **Compression Ratio** achieved after application of Huffman Encoding Algorithm.
## THEORY
* When the distribution of characters are **not even**, then we can use **Huffman Encoding**, so that we can reduce the total number of bits to save each character.
* We will use **Prefix Codes** inorder to make unique Encoding and Decoding Possible.
* The character which is having the **Highest Frequency** is represented with the **Least** number of bits.
### PREFIX CODE
* It means that if we are using any pattern to represent any character, then that pattern should not be a prefix of any other character.

## DATA STRUCTURES USED
1. Min Heap
2. Arrays
3. Trees

## COMPLEXITY ANALYSIS
* Time Complexity: O(n * log(n))
* Space Complexity: O(n)

 Here n represents number of characters entered.
 
 ## CONCLUSION
 The max **Compression Ratio** Achieved is around 50 Percent.
 
 ![image](https://github.com/sumnandi/MINOR-PROJECT-SWE5302-/blob/main/File%20Compression%20Output.PNG)
