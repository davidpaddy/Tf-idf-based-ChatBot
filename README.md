# TF-IDF Based Chatbot that makes use of a retrieval mechanism
In the dynamic world of Natural Language Processing (NLP), chatbots have emerged as indispensable tools for various tasks, from customer support to personal assistants. Among the many approaches to building chatbots, the TF-IDF (Term Frequency-Inverse Document Frequency) based retrieval method stands out for its simplicity and effectiveness.

When a user inputs a query, the chatbot processes the text and computes the TF-IDF scores for each word against its knowledge base (corpus). It then retrieves the most relevant response based on the highest cumulative TF-IDF scores. In essence, the chatbot is "finding" the most relevant pre-defined answer by measuring the importance of each word in the user's query relative to its knowledge.

The corpus is built on top of an extremely versatile dataset found in Hugging Face's Python Library. 
Here's a link to the dataset: https://huggingface.co/datasets/tatsu-lab/alpaca
