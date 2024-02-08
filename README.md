# **Jewellery Information Retrieval, Topic Modelling, and Summarisation Tool**


### Task Descriptions: Information Retrieval, Topic Modelling, and Summarisation

1. **Pre-process the dataset**. 
2. **Latent Semantic Indexing (LSI)**. 
    * Develop a Latent Semantic Indexing (LSI) model. Develop functionality such that for each query, the LSI model retrieves the top 10 most similar reviews from the dataset. 
    * Empirically tune the LSI model (weighting scheme and SVD dimensions) and present the results. Show the results of the best tuned models in a single graph. 
    
3. **Neural information retrieval**.
    * Develop a neural information retrieval model and compare its performance to the best-tuned LSI model from Task 2. 
    * Develop an interactive interface that will allow the user to type in their own query and to interact with the results.

4. **Topic modelling and visualisation of search results**.
    * Extend Task 3 to include topic modelling functionality. For this, implement and tune a topic model (e.g. Latent Dirichlet Allocation (LDA), Gensim, BERTopic) that, takes the top n search results and clusters them into topics (n can be user-defined or set to 50). Evaluate the performance of the model using suitable evaluation metrics. For each query, you will have the topics of its top n results.
    * Add functionality that will enable the user to interactively visualise the topics and keywords.


5. **Summarisation of search results**.
    * Extend Task 3 to include an approach (either neural or non-neural) that takes the top 10 search results and summarises them. Evaluate the performance of the model using suitable evaluation metrics and the target summaries. 
    * Add extra functionality to enable the user to choose which results to summarise.
