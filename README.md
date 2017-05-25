# Sentence-Document_Similarity
This repo shows us how to check the similarity between a Sentence(query) and many Documents. The document with the best score as according to different models (BM_25, TFIDF, Doc2Vec, WMD) will be the actual document from where the query has been taken.

1. Extract the file from the squad_train_doc.json folder.
2. Load the JSON file.
3. Run all the models and implement the models using their method calls.
4. Compute the dataframe.
5. The final dataframe contains the comparison of first two questions of first two documents against all 442 docs and computes their similarity scores and one hot encoding values.
