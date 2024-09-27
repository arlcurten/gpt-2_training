# gpt-2_training

## Main Reference
### Let's reproduce GPT-2 (124M)  
&nbsp;&nbsp;&nbsp;&nbsp; by Andrej Karpathy  
&nbsp;&nbsp;&nbsp;&nbsp; [https://www.youtube.com/watch?v=l8pRSuU81PU&t=9948s](https://www.youtube.com/watch?v=l8pRSuU81PU&t=9948s)



## Directories
### build-nanogpt
->  repo cloned from Andrej Karpathy  
&nbsp;&nbsp;&nbsp;&nbsp; [https://github.com/karpathy/build-nanogpt](https://github.com/karpathy/build-nanogpt)  
&nbsp;&nbsp;&nbsp;&nbsp; and became the major workspace

### gpt-2
->  repo directly cloned from OpenAI for reference  
&nbsp;&nbsp;&nbsp;&nbsp; [https://github.com/openai/gpt-2](https://github.com/openai/gpt-2)



## Other References
* As Andrej mentioned in his video, original gpt-2 uses TensorFlow code that we may be harder to use for now. Hence, Codes in "build-nanogpt" are re-built in PyTorch.  
(with [HuggingFace Transformers Library](https://github.com/huggingface/transformers/blob/main/src/transformers/models/gpt2/modeling_gpt2.py) as a reference)  
* Tokenlized with Tiktoken.  
* Tiny Shakespeare dataset (for development) and fineweb edu 10B dataset (for training & validation) are used.  
* HellaSwag dataset is used for evaluation.  
