## DNA Splicing Classification Using Machine Learning

Project Overview
This project aims to classify DNA sequences into exon-intron (EI), intron-exon (IE), and non-splice (N) categories using advanced machine learning techniques. It utilizes models such as Logistic Regression, Random Forest, and Deep Neural Networks to analyze and predict patterns in DNA sequences, aiding in the understanding of gene expression and the identification of genetic mutations.

Dataset
The data used in this project comes from the UCI Machine Learning Repository and includes 3,175 DNA sequences, each 60 nucleotides long. The sequences are classified into three categories: EI, IE, and non-splice.

Models Used
Logistic Regression
Random Forest
Deep Neural Networks
Each model's performance was evaluated based on accuracy, precision, recall, and F1-score metrics.

Features
One-Hot Encoding: Transforms nucleotide sequences into binary vectors.
K-mer Frequency Analysis: Counts the occurrences of k-length substrings in the sequences, providing a comprehensive feature set for model training.
Performance
The models demonstrated strong predictive performance, with Random Forest achieving the highest scores across all metrics.
