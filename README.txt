
1. An explanation of your algorithm and why it works.

I read the needle and haystack files and check if the files are empty  or not. I then use the bad character algorithm to get the matches as stated in the assignment. First i fill the bcs array with the length of the needle in the bcHereustics method. I cross check the characters of the needle with the wildcard and i calculate the length of the shift thereafter. The needle is shifted to align it with the character causing the mismatch in the haystack and the rightmost character in the needle is  matched with the corresponding character in the haystack. 
2. How to compile your program (ie. javac *.java)

java Oblig3.java
java Oblig3 <needle file> <text/ haystack file>

3. Which file includes the main-method
Oblig3.java
4. Any assumptions you have made when implementing the assignment
 I’ve not implemented anything to do with case of the haystack or the needle (case sensitive). 

5. Any peculiarities about your implementation
There are no known peculiarities.
6. The status of your delivery (what works and what does not)
The algorithm works as expected.
7. Give credit if your code is heavily influenced by some source (ie. teachingmaterial)
I’ve used material presented in the lectures notes.
