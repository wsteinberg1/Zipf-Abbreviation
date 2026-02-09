# Zipf-Abbreviation
Analysis of English and German philosophical texts to verify Zipf's law of abbreviation. 


Execution:
The code blocks of the file should be run once each, in the given order.


Requirements:

Package versions
numpy==2.0.2
pandas==2.2.2
matplotlib==3.10.0
scipy==1.16.3
spacy==3.8.11

Only the spaCy tokenisers were used which come from the general spaCy version and not individual language models. Hence only the overall version is listed. 


Randomness:
A random seed 323423 was used to select the English texts. 
The program attempts to access texts using the URL format:
f"https://www.gutenberg.org/cache/epub/{book_id}/pg{book_id}.txt"
If this failed then the file was considered unaccessible. 
