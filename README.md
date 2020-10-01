# Topic-Modeling-BERT-LDA
Topic modeling with BERT, LDA and Clustering. Latent Dirichlet Allocation(LDA) probabilistic topic assignment and pre-trained sentence embeddings from BERT/RoBERTa.


Model explanation
LDA for probabilistic topic assignment vector.
BERT for sentence embedding vector.
Concatenated both LDA and BERT vector with a weight hyperparameter to balance the relative importance of information from each source.
Use autoencoders to learn a lower dimensional latent space representation of the concatenated vector.(Why auto encoders why not pca. PCA is linear transformation of vectors and AE are non linear.
The assumption is that the concatenated vector should have manifold shape in higher dimensional space.
Used clustering on the latent space representations to get topics.
![]

Data pipeline(From development to deployment)
