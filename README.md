# Sentiment Analysis for miRNA::Gene Interaction Extraction

This repository contains an integrative sentiment analysis model designed to extract sentences from biomedical literature that demonstrate interactions between miRNAs and genes. 
The analysis leverages BioBERT, a domain-specific BERT model, to gain a deeper understanding of these interactions.

The repository utilizes three distinct transformer-based models to generate sentence embeddings, capturing the semantic intricacies of miRNA::gene relationships. 
Additionally, a variety of machine learning and deep learning approaches are applied, including traditional classifiers like Logistic Regression, SVM, and Random Forest, 
as well as more advanced architectures such as GRU, CNN, and LSTM. 
These models are further refined through fine-tuning to enhance performance and accuracy.

###  Set up the project in a virtual conda environment

1. If you have `conda` installed, create the environment using the provided `environment.yml`:

   ```bash
   conda env create -f environment.yml
   conda activate mirna_gene_SA_bert

2. Clone the repository:

   ```bash
   git clone https://github.com/zacharopoulou/mirna_gene_SA_bert.git
   cd mirna_gene_SA_bert
And activate the virtual environment as described above.

3. Data and Results

   The train, test, and evaluation sets for the sentiment analysis task are located in the data directory.

   The results of the scripts, including the trained models, can be accessed on Zenodo. The models and other files are uploaded there for easy download and usage.
