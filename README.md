# gpt-2_training

## <Main Reference>
Let's reproduce GPT-2 (124M)

    by Andrej Karpathy
    
    https://www.youtube.com/watch?v=l8pRSuU81PU&t=9948s



## <Directories>
build-nanogpt
->  repo cloned from Andrej Karpathy 

    https://github.com/karpathy/build-nanogpt
    
    and processed

gpt-2
->  repo directly cloned from OpenAI for reference

    https://github.com/openai/gpt-2



## <Other References>
As Andrej mentioned in his video, original gpt-2 uses TensorFlow code that we may be harder to use for now. Hence, Codes in build-nanogpt are re-built in PyTorch.
(HuggingFace Transformers Library as a reference)


Tokenlized with Tiktoken.


Tiny Shakespeare dataset (for development) and fineweb edu 10B dataset (for training & validation) are used.

HellaSwag dataset is used for evaluation.

