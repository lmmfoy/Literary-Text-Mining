# Work for McGill's "LLCU 612: Literary Text Mining" graduate seminar

In this class we learned to compile and prepare for analysis a variety of types of digital texts, use text analysis and statistical software to study them, and produce visualizations from analytic and statistical data. We learned to think algorithmically about digital texts, navigate between close and distant reading practices, and explored different digital methodologies. 

##### Tools used: #####
 * Languages used: Python, HTML, CSS
 * Libraries: Natural Language Toolkit (NLTK), NumPy, Matplotlib, Beautiful Soup, urllib.request, scikit, Gensim
 * Environments: Voyant Tools, Juypter Notebooks, ObservableHQ
    
##### Skills learned: #####

* Web scraping
* Compiling and corpus pre-processing a corpus (cleaning, format conversion, etc.) 
* Working with texts (text processing, tokenization, determining word frequency, using stoplists, normalization of terms using stemming and lemmatization)
* Working with results (Distribution of terms, building concordances, analyzing collocates and correlations, finding Ngrams)
* Visualization using graphs, lexical dispersion plots, multidimensional scaling, dendrograms, word clouds, network graphing, etc.
* Topic modelling
* Sentiment analysis 
* Parts-of-speech tagging, named entity recognition, and semantic analysis
* Document similarity, identification of authors based on use of language (using sentence length, document term matrix, TF-IDF values, cosine similarity)
* Mapping words in a text (word sense lookups, recursive searching for hyponyms, etc.)
  

## Main project: Text Mining Female Masculinity in Sixteenth and Seventeenth-Century Britain
See **Text Mining Female Masculinity in Early Modern Britain.ipynb**, and associated appendixes: **Appendix A - Corpus Summary & Ordering the Corpus.ipynb** and **Appendix B - Corpus Normalization.ipynb**. 

I explored gender fluidity in sixteenth and seventeenth-century Britain using a corpus of just over 1000 texts from the period. I created this corpus using 25,368 texts from Early English Books Online (EEBO), Eighteenth Century Collections Online (ECCO), and Evans Early American Imprints, and filtered them using key words/phrases and dates. I organized and cleaned these texts, and standardized spelling as much as possible. I then created dictionaries of concordances (a method of exploring the context of key words and phrases, by showing the words and the passages around them), and graphed collocates (words that appear in proximity to the specified key word or phrase). I went on to perform sentiment analysis on the texts to gain some insight into whether references to my key words/phrases were negative or positive, and tracked how this sentiment changed over time.
