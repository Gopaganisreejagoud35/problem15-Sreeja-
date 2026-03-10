# problem15-Sreeja-
This program finds the top 10 most frequent words in a file.
First, it reads the file line by line using BufferedReader.
Each word is stored in a HashMap, where the word is the key and the value is its frequency count.
If the word already exists in the map, its count is increased by 1. Otherwise, it is added with count 1.
After counting all words, the map entries are converted into a list and sorted by frequency in descending order.
Finally, the program prints the top 10 words with the highest frequency.
