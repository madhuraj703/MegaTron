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

# MegatronBot - Let's Chat

MegatronBot is a fully fleged chatbot with easy to update, integrate with website, easy to deploy in any cloud services like AWS, GCP and azure with a capibility to work in production enviorment.Megatron accepts various formats of inputs you can give a text input, you can also give a Speech as a input.

## What is the need of ChatBot?

Megatron was build by the team of ineuron.ai where I have worked upon a task of Intent Classification and State Tracking.The need of the MegatronBot came as ineuron.ai has a overwhemling responses and queries asked by the student over their newly released courses, as their is a Skype Support team to clarify their queries always but they cant be available 24x7 hours due to this ineuron.ai wants to build a such a great solution where the user can clarify their queries anytime without waiting in a queue for hours.

## How I have apporached to such Solution?

Building a Megatron like ChatBot requires a huge amount of data and various state of the art components.So, the first task is to get a large data,The dataset was creatd by scaraping the queries and answers asked by students over a year to their Skype support team, the dataset include of 20k sentences which were transformed and added to CSV and json format.

I have tried many State of the art language models from BERT-large to DialoGPT to RoBERTa but got an awesome results over Distilled BERT Models with ELMO embeddings.The model then trained over the 20k queries after preprocessing then adding tokens like [SEP], [START], [END] and [EOS].
  
The Architecture of MegatronBot: -

<p align="center">
  <img width="1010" height="700" src="utils/Megatron-ChatBot@2x (1).png">
</p>


Below are some results: 

<p align = "center"><img align = "center" src = "utils/NewGIF.gif" /></p>
