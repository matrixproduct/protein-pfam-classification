# protein-pfam-classification
The aim of this project is to predict the protein family ([Pfam](https://https://en.wikipedia.org/wiki/Pfam) family) based on the protein amino-acid sequence.

It is a long standing problem in molecular biology, which has received a lot of renewed attention recently. The main idea of the most successful recent approaches is to apply deep learning models, especially developed for NLP tasks, such as CNN [1, 2], Transformer [3, 4] and  bidirectional LSTM [5].

In this project we employ the model developed in Ref.[5].

References:

1. "Using Deep Learning to Annotate the Protein Universe", M.L. Bileschi et.al., Nature Biotechnology, 40, 932–937 (2022), https://doi.org/10.1101/626507

2. "Convolutions are competitive with transformers for protein sequence pretraining", K K. Yang et. al., https://doi.org/10.1101/2022.05.19.492714

3. "Transforming the Language of Life: Transformer Neural Networks for Protein Prediction Tasks",
A. Nambiar, BCB '20: Proceedings of the 11th ACM International Conference on Bioinformatics, Computational Biology and Health Informatics, Article No.: 5, 1-8, (2020), https://doi.org/10.1145/3388440.3412467
4.  "Transformer Neural Networks Attending to BothSequence and Structure for Protein Prediction Tasks", A. Kabir and A. Shehu, https://arxiv.org/pdf/2206.11057.pdf

5. "Learning the protein language: Evolution, structure, and function", T. Bepler and B. Berger, Cell Systems 12, 654–669, (2021), https://doi.org/10.1016/j.cels.2021.05.017
