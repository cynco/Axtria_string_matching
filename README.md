## Fuzzy string matching exercise   

I used 4 different algorithms to match test strings to a set of reference strings and give a confidence score.  

The results are written out to the Excel workbook.   

The algorithm that gave the best results was the 4th one.  
It uses Sentence Similarity Based on Semantic Nets and Corpus Statistics.   
This implementation is built with Python and Natural Language Tool Kit (NLTK).   
The Semantic Net referred to in the paper is Wordnet and the Corpus Statistics are from the Brown Corpus,   
both of which are available using NLTK's corpus API.  

It is by Sujit Pal, with inspiration from published work by 
Yuhua Li, David McLean, Zuhair A. Bandar, James D. O’Shea, and Keeley Crockett.   
Learn more: http://sujitpal.blogspot.com/2014/12/semantic-similarity-for-short-sentences.html
