# term-dict
Creation of term dictionary LIWC

This project aims to process and analyze comments using natural language processing (NLP) techniques. The analysis primarily focuses on author comments in scientific articles, involving data cleaning, transformation, Word2Vec model generation, and building synonym dictionaries for various term categories.

#Project Structure
##Libraries Used
The project utilizes several R libraries, including:

* dplyr: For data manipulation.
*  tidyr: For tidying data.
* tidytext: For text manipulation.
* stringr: For string operations.
* tm: For text mining.
* quanteda and quanteda.dictionaries: For text analysis and dictionary usage.
* readr: For reading files.
* h2o: For machine learning and NLP models.

## Generating the Word2Vec Model
A Word2Vec model is generated using the h2o library to find synonyms and other relationships between words in the comments.

## Finding and Selecting Synonyms
Word2Vec models are used to find synonyms for terms in the dictionary, and relevant synonyms are manually selected.
