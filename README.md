# **Jewellery Information Retrieval, Topic Modelling, and Summarisation Tool**


### Project Descriptions: Information Retrieval, Topic Modelling, and Summarisation

1. **Pre-process the dataset**. 
2. **Latent Semantic Indexing (LSI)**. 
    * Developed a Latent Semantic Indexing (LSI) model with functionality such that for each query, the LSI model retrieves the top 10 most similar reviews from the dataset. 
    * Empirically tuned the LSI model (weighting scheme and SVD dimensions) and showed the results of the best tuned models in a single graph. 
    
3. **Neural information retrieval**.
    * Developed a neural information retrieval model and compared its performance to the best-tuned LSI model. 
    * Developed an interactive interface that allows the user to type in their own query and to interact with the results.

4. **Topic modelling and visualisation of search results**.
    * Extended the neural information retrieval model to include topic modelling functionality. For this, I implemented and tuned a BERTopic model that, takes the top n search results and clusters them into topics (n can be user-defined or set to 50).
    * Evaluated the performance of the model using suitable evaluation metrics. 
    * Included functionality that enables the user to interactively visualise the topics and keywords.


5. **Summarisation of search results**.
    * Extended the neural information retrieval model to include summarisation of the top search results with user-selectable summarisation options, allowing for tailored content analysis and briefings.

