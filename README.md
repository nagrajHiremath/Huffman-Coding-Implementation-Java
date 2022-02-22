## Huffman-Coding-Implementation-Java
*  Implemented Huffman Coding in java and tested with Word file.
*  Get the result of data compression rate.
*  Data Struchers Used – Greedy Algorithms, Priority Queue, Hash Map, and Recursion.

## Steps to test
* Create orignal.txt file in files folder
* Run test.java
* It will shows all frequency of characters and Huffman codes.
* final result of compression in percentage will shows.

## Sample Output
```
----- Test.java START -----
* Loading the file...DONE
* Builiding Huffman Tree and Code Tables... DONE

============= Word Frequency =============
a occurs 8 times
b occurs 1 times
c occurs 1 times
s occurs 13 times
d occurs 3 times
e occurs 1 times
h occurs 14 times
j occurs 4 times
\n occurs 1 times
k occurs 1 times

========== Huffman Code for each character =============
a: 00
b: 011010
c: 01001
s: 10
d: 0101
e: 01100
h: 11
\n: 011011
j: 0111
k: 01000

* Encoding the text... DONE
* Decoding the encoded text... DONE

========== RESULT ==========
Original string cost = 329 bits
Encoded  string cost = 125 bits
% reduction = 62.00607902735562

----- Test DONE -----
```
