# ETSANet
This repository contains the code for our  paper: Topic Sentiment Analysis Based on Deep Neural Network using Document Embedding Technique

## Datasets
1) Topic detection dataset is : Pang and Lee movie review dataset
B. Pang and L. Lee, “A Sentimental Education: Sentiment Analysis Using Subjectivity Summarization Based on Minimum Cuts,” arXiv:cs/0409058, Jan. 2004, [Online]. Available: http://arxiv.org/abs/cs/0409058

2) Sentiment Classification Dataset includes: 

   a) IMDB film review 
	 R. E., P. T. Pham, D. Huang, A. Y. Ng, and C. Potts, “Learning Word Vectors for Sentiment   Analysis,” Proc. 49th Annu. Meet. Assoc. Comput. Linguist. Hum. Lang. Technol. - Vol. 1, pp. 142–150, 2007. [Online]. Available: https://dl.acm.org/citation.cfm?id=2002491
	 
	 b) Sentiment140
	 A. Go, R. Bhayani, and L. Huang, “Twitter Sentiment Classification using Distant Supervision,” Processing, vol., pp. 1–6, 2009. [Online]. Available: https://www-cs-faculty.stanford.edu/people/alecmgo/papers/TwitterDistantSupervision09.pdf
	 
	 ## Requirements
	 1) Gensim
	 
	 2) pyLDAvis
	 
	 3) Spacy
	 
	 4) NLTK
	 
	 5) Niapy
	 
	 ## Description of files
	 
	 1) Preprocessing_Module.ipynb
	    Preprocessing the datasets
	    
	 2) Module_LDA.ipynb
	    Finding the best number of topics using Coherence Value, performing the LDA, and saving topics
	    
	 3) STRDF_Finding_Similar_Documents_using_Doc2vec.ipynb
	    Making Doc2vec models, concatenating Doc2vec Models, and finding semantically topic-related documents correspondinng to the topics 
	    
	 4) Sentiment_Classification_Hyperparameter_Optimization.ipynb
	    Hyperparameter tuning (hyperparameters of CNN-GRU including Number of filters, Kernel size, Pool size, Number of GRU units) using GWO-WOA, comparing with other metaheuristic optimizers, and classifying the Sentiments of documents using the CNN-GRU
	   
	 5) Classification_using_Other_Classifiers.ipynb
	   
	   Classifying semantically topic-related documents using different classifiers
	   
	
