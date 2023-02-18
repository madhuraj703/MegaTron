##  Project description

In this project, we developed a advanced NLP model using attention mechanism  which can provide instant Customer Support and resolve their queries. Where our model is even capable to retrain and productionize itself. It can be integrated in various domains like banking, insurance, online education, etc. depending on client's needs ,where client doesn't need to have any prior technical knowledge ,they just have to use it as a plug & play model. 

##  core Idea - Intent Classification

Intent classification is the automated categorization of text data based on customer goals.

In essence, an intent classifier automatically analyzes texts and categorizes them into intents such as Purchase, Downgrade, Unsubscribe, and Demo Request. This is useful to understand the intentions behind customer queries, automate processes, and gain valuable insights.

Ultimately, every customer interaction has a purpose, an aim, or intention. Whether they want to make a purchase, request more information, or unsubscribe, you should respond quickly to improve customer retention rates, loyalty and satisfaction.

##  ELMo Embeddings 

Embeddings from Language Models, or ELMo, is a type of deep contextualized word representation that models both (1) complex characteristics of word use (e.g., syntax and semantics), and (2) how these uses vary across linguistic contexts (i.e., to model polysemy). Word vectors are learned functions of the internal states of a deep bidirectional language model (biLM), which is pre-trained on a large text corpus.

ELMo architecture :

![Alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/03/output_YyJc8E.gif "ELMo architecture")

## DistilBERT

DistilBERT is a small, fast, cheap and light Transformer model based on the BERT architecture. Knowledge distillation is performed during the pre-training phase to reduce the size of a BERT model by 40%. To leverage the inductive biases learned by larger models during pre-training,  introduce a triple loss combining language modeling, distillation and cosine-distance losses.It has 40% less parameters than bert-base-uncased, runs 60% faster while preserving over 95% of BERT’s performances as measured on the GLUE language understanding benchmark.

DistilBERT performance comparison :

![Alt text](https://4.bp.blogspot.com/-v0xrp7eJRfM/Xr77DD85ObI/AAAAAAAADDY/KjIlWlFZExQA84VRDrMEMrB534euKAzlgCLcBGAsYHQ/s1600/NLP%2Bmodels.png "BERT variants performance comparision")
  
The Architecture of MegatronBot: -
![Alt Text](/architecture.png)

Below are some results: 

![Alt Text](/NewGIF.gif)
