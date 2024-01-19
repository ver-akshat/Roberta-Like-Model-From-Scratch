### Creating a Roberta like model from scratch
I will use BPE Tokenizer from transformers linrary to train the tokenizer and 
load it in a new Roberta like model i.e the model will use my tokenizer, this model is 
Roberta like since it has no NSP task and has MLM task only and the architecture of this is
similar to DistilBERT so its faster and has good inference time than Robert
