# Closest_sentences-from-different-languages-with-laser-embedding

This project constructs two text file which one of them is German and the other one is Portuguese.

Requirements:
laserembeddings: pip install laserembeddings
PyTorch

Method:
Two files are used, one containing German sentences and the other containing Portuguese sentences.
Laser embeddings are used to extract one vector per sentence.
PyTorch’s off-the-shelf cosine similarity function is used to extract pairwise similarity between the sentences.
The top-k most similar sentence pairs are selected and written to a tab-separated file with k lines. 
The German sentence is written first, followed by the Portuguese sentence.
