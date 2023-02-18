##  Project description

we developed and implemented a sophisticated customer support system  that leveraged state-of-the-art Natural Language Processing (NLP) models for intent classification of customer queries. To improve the system's accuracy in resolving customer queries instantly, We utilized ELMo embeddings and DistilBERT fine-tuning. The project also involved web scraping to identify possible new solutions to customer queries, as well as text summarization. The system is designed to retrain and productionize itself, making it scalable and adaptable to different domains based on client requirements, which reduced the workload on customer service agents and improved operational efficiency. The advanced customer support system provided the edtech company with a competitive advantage in the market, leading to improved customer satisfaction and reduced customer churn, as well as optimizing resources.

##  core Idea - Intent Classification

Intent classification is a natural language processing (NLP) technique that identifies the intent or purpose behind a user's input, such as a question or command. This technique is commonly used in chatbots and virtual assistants to understand the user's request and provide a relevant response. Intent classification models are trained on large datasets of labeled examples and use machine learning algorithms to predict the intent of new user inputs.

### The Architecture of MegatronBot: -
![architecture](https://user-images.githubusercontent.com/108948595/219875511-28f09d6c-5546-4407-883b-78967947c597.png)

### Project Demo: -
![NewGIF](https://user-images.githubusercontent.com/108948595/219875683-76230189-7da5-4087-9d29-40e459e38a85.gif)

##  ELMo Embeddings 

ELMo (Embeddings from Language Models) is a type of deep contextualized word representation that is commonly used in natural language processing (NLP). Unlike traditional word embeddings that represent each word as a fixed vector, ELMo embeddings capture the meaning of words in context by incorporating information from surrounding words. ELMo is based on a deep bidirectional language model that is trained on a large corpus of text, such as Wikipedia or news articles. The resulting ELMo embeddings can be used to improve the performance of various NLP tasks, such as text classification, question answering, and named entity recognition. ELMo has been shown to outperform traditional word embeddings, such as Word2Vec and GloVe, on a wide range of NLP benchmarks.

ELMo architecture :

![Alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/03/output_YyJc8E.gif "ELMo architecture")

## DistilBERT

DistilBERT is a small and efficient Transformer model that is based on the BERT architecture. It is designed to be faster, cheaper, and lighter than BERT, while still retaining most of its performance. To achieve this, knowledge distillation is performed during the pre-training phase, which reduces the size of the model by 40%. To ensure that DistilBERT retains the inductive biases learned by larger models during pre-training, a triple loss is introduced, which combines language modeling, distillation, and cosine-distance losses. As a result, DistilBERT has 40% fewer parameters than the bert-base-uncased model and runs 60% faster, while preserving over 95% of BERT's performance on the GLUE language understanding benchmark.

DistilBERT performance comparison :

![Alt text](https://4.bp.blogspot.com/-v0xrp7eJRfM/Xr77DD85ObI/AAAAAAAADDY/KjIlWlFZExQA84VRDrMEMrB534euKAzlgCLcBGAsYHQ/s1600/NLP%2Bmodels.png "BERT variants performance comparision")

