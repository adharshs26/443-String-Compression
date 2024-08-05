The compress function compresses a list of characters chars in place using a two-pointer approach. 
It uses the read pointer to scan through the array and count consecutive repeating characters, while the write pointer keeps track of where to write the compressed characters and their counts. 
For each group of consecutive characters, it writes the character to the write position. If the group has more than one character, it also writes the count of characters as digits. 
After processing all characters, the function returns the new length of the array, reflecting the length of the compressed portion. 
This method efficiently compresses the array with a time complexity of O(n) and constant extra space.
