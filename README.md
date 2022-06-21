# Abstractive Text Summarization using Seq2Seq, Transformers Models

NLP Project

Abstractive summarization is very hot topic and complex task in natural language processing field. Abstractive text summarization is task of  producing a concise and fluent summary while preserving the key information content and overall semantics of the text. This task is generally tackled by using encoder-decoder neural networks architectures. I have tried to address this problem by using two different approaches, Seq2Seq neural network and Transformers model. In Seq2Seq model, I have trained two models with different architecture one with only one lstm neural network in encoder part and second one with three lstm neural networks in the encoder part and the decoder network is same for both models. For evaluating these models, I have chosen very popular and robust evaluation metrics for text summarization task like bleu score, rouge score, meteor score and Bert score.  I have compared the results for both models and Transformer model outperforms the Seq2Seq2 models. and finally, I have done some error analysis to find out the peculiarities in generated summaries. 

