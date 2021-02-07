# Title
FENAS: Flexible and Expressive Neural Architecture Search

## Author
Ramakanth Pasunuru, Mohit Bansal

## Abstract
Architecture search is the automatic process of designing the model or cell structure that is optimal for the given dataset or task. Recently, this approach has shown good improvements in terms of performance (tested on language modeling and image classification) with reasonable training speed using a weight sharing-based approach called Efficient Neural Architecture Search (ENAS). In this work, we propose a novel architecture search algorithm called Flexible and Expressible Neural Architecture Search (FENAS), with more flexible and expressible search space than ENAS, in terms of more activation functions, input edges, and atomic operations. Also, our FENAS approach is able to reproduce the well-known LSTM and GRU architectures (unlike ENAS), and is also able to initialize with them for finding architectures more efficiently. We explore this extended search space via evolutionary search and show that FENAS performs significantly better on several popular text classification tasks and performs similar to ENAS on standard language model benchmark. Further, we present ablations and analyses on our FENAS approach.

## Bib
@inproceedings{pasunuru-bansal-2020-fenas,
    title = "{FENAS}: Flexible and Expressive Neural Architecture Search",
    author = "Pasunuru, Ramakanth  and
      Bansal, Mohit",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2020",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.findings-emnlp.258",
    doi = "10.18653/v1/2020.findings-emnlp.258",
    pages = "2869--2876",
    abstract = "Architecture search is the automatic process of designing the model or cell structure that is optimal for the given dataset or task. Recently, this approach has shown good improvements in terms of performance (tested on language modeling and image classification) with reasonable training speed using a weight sharing-based approach called Efficient Neural Architecture Search (ENAS). In this work, we propose a novel architecture search algorithm called Flexible and Expressible Neural Architecture Search (FENAS), with more flexible and expressible search space than ENAS, in terms of more activation functions, input edges, and atomic operations. Also, our FENAS approach is able to reproduce the well-known LSTM and GRU architectures (unlike ENAS), and is also able to initialize with them for finding architectures more efficiently. We explore this extended search space via evolutionary search and show that FENAS performs significantly better on several popular text classification tasks and performs similar to ENAS on standard language model benchmark. Further, we present ablations and analyses on our FENAS approach.",
}