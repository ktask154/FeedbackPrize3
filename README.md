# FeedbackPrize3  158(/2655)th solution
## Models
- deberta-v3-base

- deberta-v3-large

- deberta-xlarge

- deberta-v2-xlarge

## Main methods that worked
- Resolve encoding error
- add BERTopic text
- MultilabelStratifiedGroupKFold
- Pooler Output
  - Last Hedden State Output
    -  Mean Pooling
  - Hidden Layeers Output
    - CLS Layer Embeddings
    - Attention Pooling
- Layer Reinitializing
- Mixout
- Multi-sample dropout
- Adversarial training (FGM)
  - [paper](https://arxiv.org/pdf/1710.06081.pdf)



## Final Result
CV : 0.445740

Public LB : 0.438067

Private LB : 0.436347
