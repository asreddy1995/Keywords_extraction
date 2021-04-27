# Keywords_extraction
This dataset contains 7 columns: id, year, title, even_type, pdf_name, abstract and paper_text. We are mainly interested in the paper_text which includes both the title and the abstract.
TF-IDF stands for Text Frequency Inverse Document Frequency. The importance of each word increases in proportion to the number of times a word appears in the document (Text Frequency – TF) but is offset by the frequency of the word in the corpus (Inverse Document Frequency – IDF).

Using the tf-idf weighting scheme, the keywords are the words with the highest TF-IDF score. For this task, I’ll first use the CountVectorizer method in Scikit-learn to create a vocabulary and generate the word count:
