## Solution Approached:
## 1. Question-Answering (QA) model
  Question-answering model is composed of three sources: the question, the context and the answer. 
  The model inputs are the question and the context and the model output is the answer. In most cases, but not all, 
  the answer is contained in the context

## 2. Using search engine to produce the context
  The context can for the question can be very big as we are dealing with 40k papers. Henceforth we use Okapi BM25.
  
## 3. From (context, question) to answer with transformers
  We here use a pretrained transformer model in order to answer the query more precisely and close to context of the query asked.
  
  
  
