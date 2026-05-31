- gradient descent
- back propagation
- attention
- muti layer preception
- fast forward
- Inference

------

Word embedding means

A "King" we can represent 
    - mame          - 1
    - leader        - 1
    - women         - 0
    - rich          - 1
    - tail          - 0
    - authority     - 1

Embeddings will form, when we train our large amount of text to transformer matrix computation, 
these embeddings will form between vectors.

two types of embeddings
- static embeddings
- contextual embeddings

transformer has the encoder & decoder

In your model, during training for each token, you will get static emebeded matrix in their internals and they have special metris like Wq, Wk, Wv

each a word will have a token
for bigger words like called it will split as
    - call - 1 token
    - ed - 1 token
        -------
            2 tokens
        --------


each word in sentence will get attention score

In attention
    - query
    - key
    - value

word1 -> attention score (dot_product) static emebedding +
word2 -> attention score (dot_product) static emebedding +
.
.
.
-------
context aware emebeding will form
-------

-------------------------------

what is transformer
    1           2           3       4     5     6   7   8       9       10          11          12
    I           am         the     boss   ,     I  am  your    company     simon   innovations   .
    |            |          |        |          
    \/           \/         \/     
    token1      token2      token3    .....
    +             +          +
    postion      postion     position
    vector       vector       vector
    
    

each word convert into token 

so 12 words can quivalent to 12-14 tokens. Depends on word size, if word size is more, then token size of word can increase

here position vector will be the representing position of each word into position form of vector

These final vectors will pass into attention and these will pass into feed forward network, and after repeatating attention + feed forward network for 100 times, then you will get final matrix, take last column then add with existing all word directory will get output then 
pass into soft max it will give probility of each word its also known as temperature, if temperature is low, then it will take the only high probaility output and return to the user with adding one word in response, same like that now existing words will pass into transformer and get other auto completition words...
