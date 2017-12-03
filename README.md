Supplementary files supporting the TACL paper: Guillem Collell and Marie-Francine Moens (2018) "Learning Representations Specialized in Spatial Knowledge: Leveraging Language and Vision", TACL


# Files provided:

spatial_1016.txt: human annotated wors pairs ranked by spatial similarity (see Similarity task in the paper)

spatial_emb-LANG.csv: trained linguistic embeddings (initialized with GloVe)
spatial_emb-VIS.csv: trained visual embeddings (initialized with VGG-128)

**Notice that the words present in our trained embeddings is limited to those that appear in our training data (hence those that were not trained/updated do not appear as they are identical to their original VGG-128 or GloVe vectors). Notice also that not all these vectors have received the same amount of training, i.e., some words (e.g., 'hat', 'man', etc.) appear more frequently than others and have been thus trained further. 
