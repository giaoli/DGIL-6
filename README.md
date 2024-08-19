Interleukin-6 (IL-6) is a potent glycoprotein that regulates innate and adaptive immunity, along with metabolism. The expression and release of IL-6 is correlated with disease severity. As the production of IL-6, IL-6 inducing peptides are very important on the development of immunotherapy and diagnostic biomarkers for various diseases. Most existing IL-6 inducing peptide predictors used traditional machine learning and required perform feature selection with prior knowledge, and none of these methods considered the 3D structure of peptide sequences that is important for peptide function. In this study, we proposed an IL-6 inducing peptide prediction method (named DGIL-6) based on the 3D structure and graph neural network. The DGIL-6 represents a peptide sequence as a graph, where the amino acids are nodes and the adjacency matrix that represents the relationship between two nodes is computed based on the predicted residue contact graph of the peptide sequence. In addition to commonly used amino acid representation methods such as one-hot encoding and position encoding, a pre-trained model ESM-1b is utilized for extracting amino acid features as nodes’ features. For the graph of peptide sequence, a dual-channel approach is used to extract features by combining graph attention and graph convolutional network modules, which considers both node weights and information updates simultaneously. Finally, the two types of features are combined for the classification of IL-6 inducing peptides. A series of experimental results including the cross-validation experiments, independent test experiments, ablation experiments and visualization results have verified the effectiveness of the proposed method DGIL-6.![DGIL-6](https://github.com/user-attachments/assets/374da073-01e0-4638-a3c9-516f2760b6f0)
