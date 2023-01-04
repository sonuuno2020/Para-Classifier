# Para-Classifier

Replicate PubMed200 research paper - https://arxiv.org/pdf/1612.05251.pdf
Implemented the model with some minor changes in this paper - https://arxiv.org/pdf/1710.06071.pdf

* Instead of using Glove embedding - 
--> Universal sentence encoder 
--> BERT embeddings
* inplace of `SGD` optimizer `Adam` is used.

And for some layers filter unit is temperd for faster calculations

Achived accuracy 
for 20k dataset - 88%
for 200k dataset - 90%
