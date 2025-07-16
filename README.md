# Similarity, Transformation and the Newly Found Invariance of Influence Functions
This repository contains the resources and code for our paper _Similarity, Transformation and the Newly Found Invariance of Influence Functions_ published at SCiL 2025.

<strong>Abstract:</strong>

Ensuring that semantic representations capture the actual meanings of sentences to the exclusion of extraneous features remains a difficult challenge despite the amazing performance of representations like sBERT. We compare and contrast the semantic-encoding behaviours of sentence embeddings as well as influence functions, a resurgent method in the field of language model interpretability, using meaning-preserving grammatical transformations. Under the two tasks of sentence similarity and a new task called entity invariance, we seek to understand how these two measures of semantics warp under surface-level syntactic changes. Invariance to meaning-preserving transformations is an important aspect in which sentence embeddings and influence functions seem to differ. Nevertheless, our experiments find that across all our tasks and transformations, sentence embeddings and influence functions are highly correlated. We conclude that there is evidence that influence functions point towards a deeper encoding of semantics.


## About

This repo contains the datasets used for the experiments. We used the [Kronfluence](https://github.com/pomonam/kronfluence) package in order to calculate the influence scores on GPT2. In addition, we used the sBERT models provided by the [SentenceTransformers](https://sbert.net/) package to calculate sentence embeddings.

## Citation

To do.
