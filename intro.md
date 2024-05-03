# Introdcution

## Breaking down texts

```mermaid
graph TD;
    Text --> Token;
    Token --> Embedding;
    Embedding --> Vector;
    Vector --> SimilarityMeasure
    Vector --> VectorDatabase;
    Embedding --> Transformers;
```

## Modelling

- *Attention* captures context.
- *Billions* of parameters.
- **Huge** training data.
- Training is **expensive** and requires specialized hardware.
- optionally Instruction tuning
- RLHF to incorporate *human feedback*.

### Improvements by user / customer
- Prompt 'engineering'
- Use *RAG* to add data sources to context
- Fine-tuning of model

## Limitations

- Math / logic / reasoning
- Training data:
    - Bias
    - Cut-off date
- Censorship by some vendors
- Hallicunation
- computationally expensive
- Ethics and copyright issues
