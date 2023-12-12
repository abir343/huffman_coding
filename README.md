# Huffman-Coding-Project
This project contains the famous "Huffman Coding Algorithm" implemented using three main data structures : Min Heap, Hash Map and Binary Tree.

## What is Huffman Coding?

In computer science and information theory, a Huffman code is a particular type of optimal prefix code that is commonly used for lossless data compression. The process of finding or using such a code proceeds by means of Huffman coding, an algorithm developed by David A. Huffman while he was a Sc.D. student at MIT, and published in the 1952 paper "A Method for the Construction of Minimum-Redundancy Codes".

The output from Huffman's algorithm can be viewed as a variable-length code table for encoding a source symbol (such as a character in a file). The algorithm derives this table from the estimated probability or frequency of occurrence (weight) for each possible value of the source symbol. As in other entropy encoding methods, more common symbols are generally represented using fewer bits than less common symbols. Huffman's method can be efficiently implemented, finding a code in time linear to the number of input weights if these weights are sorted.

However, although optimal among methods encoding symbols separately, Huffman coding is not always optimal among all compression methods - it is replaced with arithmetic coding or asymmetric numeral systems if better compression ratio is required.

## The 'Implement Huffman Coding.ipynb' file contains the entire code in Python. 

There are 2 text files and a binary file. One is the Original text file of size 2 MB. The Binary file  is the compressed one with a size of 1.09 MB and it is again decompressed to give the other text file which is the exact replica of the original text file...


#### That's the magic of Huffman Coding.
