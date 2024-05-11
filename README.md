# Protein Sequence Classification with ProtCNN

## Overview
This repository focuses on the classification of protein sequences into one of the protein family accessions based on the Pfam dataset. Proteins, complex biomolecules essential in various biological functions, consist of amino acids linked by peptide bonds. These sequences determine the protein's structure and function, which are pivotal in understanding molecular biology's core challenges.

The Pfam database provides a comprehensive collection of protein families along with their annotations and sequence alignments, making it an invaluable resource for this study.

## Problem Statement
The goal is to classify a protein's amino acid sequence into the correct protein family using deep learning techniques. This involves predicting the protein class based on its amino acid sequence as defined by the Pfam dataset.

## Model Description - ProtCNN
ProtCNN is a convolutional neural network inspired by the ResNet architecture, incorporating residual blocks and dilated convolutions. This design allows ProtCNN to have a larger receptive field without an increase in model parameters, making it highly efficient and scalable for large datasets like Pfam.

![ProtCNN Architecture](https://www.biorxiv.org/content/biorxiv/early/2019/07/15/626507/F6.large.jpg)

## Results
The ProtCNN model has demonstrated outstanding performance, surpassing current state-of-the-art techniques such as BLASTp for annotating protein sequences. This suggests that deep learning will be vital in future protein function prediction tools.

| Model   | Train Accuracy | Validation Accuracy | Test Accuracy |
|---------|----------------|---------------------|---------------|
| ProtCNN | 0.996          | 0.987               | 0.987         |

## Conclusion
The success of the ProtCNN model in classifying protein sequences illustrates the potential of deep learning in revolutionizing protein function prediction. Our findings advocate for the adoption of advanced neural network architectures in the scientific community, paving the way for more accurate and efficient computational biology tools.

## Reference
For further details on the architecture and performance of ProtCNN, please refer to the following publication: [BioRxiv Paper](https://www.biorxiv.org/content/10.1101/626507v4.full)
