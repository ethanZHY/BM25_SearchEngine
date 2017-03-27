# BM25_SearchEngine

A simple search engine based only on retrieval model BM25

(C) Composed by Ethan Zhang

# 1. Working Environment:
	  Python 3.6 + PyCharm CE


# 2. Text files:
	
	BM25_global warming potential.txt
  
	BM25_green power renewable energy.txt
  
	BM25_solar energy california.txt
  
	BM25_light bulb bulbs alternative alternatives.txt
  
	implementation.txt
  
	discussion.pdf
	
	raw folder is the corpus I built from previous works (see other repositories: crawler and invertedIndex)


All text file above can be generated by running the source code file below:


# 3. Source Code:

	BM25.py
  
	 Containg both indexing module and retrieval module
   
	 Output the rank, filename, score to a text file named BM25_<query>.txt
   
	 Works almost the same as lucene-based SE.
   
	 To compile and run, put the BM25.py and the raw folder at the same directory.
   
