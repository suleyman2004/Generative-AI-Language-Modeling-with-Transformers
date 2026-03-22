This course is approximately 7 hours long and divided into two modules. You can complete one module weekly or at your own pace.

Week 1 - Module 1: Fundamental Concepts of Transformer Architecture

In module 1, you will learn positional encoding, which consists of a series of sine and cosine waves. This enables you to incorporate information about the position of each embedding within the sequence using PyTorch. 

As you delve into this module, you will explore the concepts of self-attention mechanisms that employ the query, key, and value matrices. You can apply the attention mechanism to word embeddings and sequences. This process helps capture contextual relationships between words. You will also learn about the language modeling and self-attention mechanisms that generate the query, key, and value using the input word embeddings and learnable parameters.

Additionally, you will explore scaled dot-product in attention mechanisms with multiple heads and how the transformer architecture enhances the efficiency of attention mechanisms. You will also learn to implement a series of encoder layer instances in PyTorch. 

As you delve into this module, you will learn how transformer-based models are used for text classification, how to create the text pipeline and model, and how to train the model.

Week 2 - Module 2: Advanced Concepts of Transformer Architecture

In Module 2, you will explore decoders and their use of decoder models for text generation. Further, you will learn the architecture of decoder-only Generative Pretained Transformers (GPT), the training process of GPT models, and how the model is useful for generating text. 

As you progress in this module, you will learn about bidirectional encoder representations from transformers (BERT) that use an encoder-only architecture. Additionally, it allows the processing of entire text sequences simultaneously, theoretically enhancing its understanding of the context and nuances within the text. However, masked language modeling (MLM) involves randomly masking the input tokens and training BERT to predict the original masked tokens.

You’ll also learn to train BERT models using next-sentence prediction (NSP) tasks and how to fine-tune BERT for a downstream task. However, this module leverages data preparation for preprocessing using tokenization, masking, and creating training-ready input for BERT-specific training tasks such as MLM and NSP.

This module enables you to explore the encoder and decoder transformer architecture and explain how the model can be used to generate translations. Further, you will use an encoder-decoder model for translation tasks using PyTorch and then train the model to generate German-to-English translations.
