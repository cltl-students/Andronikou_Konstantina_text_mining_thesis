# Automatic Retrieval Of Topics Using Topic Modeling Techniques From Customer Conversations In The Airline Domain

This thesis project focuses on the implementation of automatic retrieval of topics using topic modeling techniques from customer conversations in the airline domain. The main idea of a topic modeling task is to produce a concise summary highlighting the most common topics from a corpus of thousands of documents. Retrieving the information within the conversational data between a customer and an agent can provide in-depth insight into the passenger’s satisfaction or issues. This project implemented three different topic modeling methods, LDA (Blei et al., 2003), NMF (Lee and Seung, 1999) and BERTopic (Grootendorst, 2020). A comparative analysis and evaluation of the results was conducted in terms of predictive performance and topic quality. This thesis project was in collaboration with the company Underlined.


## Thesis project by Konstantina Andronikou for the master's degree in "Linguistics: Text Mining", VU Amsterdam (2021-2022).

This project was supervised by Dr. Ilia Markov and Gabriele Catanese. 

A greater explanation of this procedure can be found in the thesis report [**Thesis**](https://github.com/cltl-students/Andronikou_Konstantina_text_mining_thesis/blob/main/Andronikou_Konstantina_MA_Thesis.pdf)

### FOLDERS 

This repository [**Andronikou_Konstantina_text_mining_thesis**](https://github.com/cltl-students/Andronikou_Konstantina_text_mining_thesis) consists of the following folders:

## Data
* `example_data.json` Example data based on the original dataset provide for this project.
* `readme.md` This readme includes information related to the original data.
## Pre-processing
* `pre-processing.ipynb` This notebook is responsible for pre-processesing the data. 
* `readme.md` This readme includes information related to the pre-processing procedure.
## Topic Models 
* `LDA.ipynb` This notebook carries out the training process of a Latent Dirichlet allocation (LDA) topic model.
* `NMF.ipynb` This notebook carries out the training process of a Non-Negative Matrix Factorization (NMF)  topic model.
* `BERTopic.ipynb` This notebook carries out the training process of BERTopic.
* `create_embeddings.ipynb` For error analysis this project created an embedded space. This notebook carries out the process of creating an embedded space.
* `error_analysis.ipynb` This note is responsible for the error analysis based on pairwise cosine similarity.
* `readme.md` This readme includes information related to the topic models and the error analysis.
## Prerequisites

The requirements to run the provided code can be found in  [requirements.txt](https://github.com/cltl-students/Andronikou_Konstantina_text_mining_thesis/blob/main/requirements.txt)

## References 

D. D. Lee and H. S. Seung. Learning the parts of objects by non-negative matrix
factorization. Nature, 401(6755):788–791, 1999.

D. M. Blei, A. Y. Ng, and M. I. Jordan. Latent dirichlet allocation. Journal of machine
Learning research, 3(Jan):993–1022, 2003.

M. Grootendorst. Bertopic. 2020. URL https://maartengr.github.io/BERTopic/.
