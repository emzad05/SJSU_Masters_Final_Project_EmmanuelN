# SJSU_Masters_Final_Project_EmmanuelN
My final project in my masters program in Electrical Engineering at San Jose State University, specializing in Machine Learning

## Relation Extraction in Biomedical Literature using Machine Learning Methods

### Abstract

Medical decisions concerning patient healthcare heavily rely on evidence-based medicine
from patient histories, clinical repositories, medical journals and medical databases.
Automated Information Extraction (IE) of disease-treatment relations and their classification
can significantly improve efficiency in medical decision support. Using the Machine Learning
(ML) task of Natural Language Processing (NLP), Relation Extraction (RE) from natural
language biomedical texts is performed in order to identify semantic relations between
diseases and treatments. Deep learning (DL) models are built and evaluated on classification
accuracy and F1-scores, finding that fine-tuned pretrained models perform best on classifying
the semantic relations between diseases and treatment entities.

Key Words: Healthcare, Machine Learning, Natural Language Processing, Relation
Extraction, Deep Learning


### Data Exploration and Preprocessing

The BioText [1, 2] dataset consists of annotated sentences
from titles and abstracts extracted from MEDLINE 2001.
Model development pipelines are built using the Google
Colab platform [3], running python on Jupyter notebooks,
and utilizing GPUs.
The texts are subsampled to only include sentences with
relevant relations. The relations are then categorically
encoded. The dataset is then shuffled and split into 80%
training and 20% test/validation.

### Model Development

  1. Long-short Term Models (LSTM)
  2. Fine-tuned Bidirectional Encoder Representations from Transformers (BERT) [4] model
  3. Fine-tuned BioBERT [5] model

### Conclusions

The RE task of distinguishing disease-treatment relations
is successfully performed on biomedical texts.
The fine-tuned BioBERT Model, pretrained on biomedical
corpuses performed the best.
Future work can extend the work and improve model
performance by using additional relevant datasets.
Consequently, implementation of best ML models would
result in efficient, automated medical decision support.


### References

[1] B. University of California, "The BioText Project,"
[Online]. Available:https://biotext.berkeley.edu/dis_treat_data.html. [Accessed 15 04 2022].

[2] B. Rosario and M. Hearst, "Classifying Semantic Relations in Bioscience Texts," ACL, 2004.

[3] Google, "Welcome To Colaboratory," [Online].Available:https://colab.research.google.com/. [Accessed 15 04 2022].

[4] Devlin et al, "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding," arXiv, 2018.

[5] J. L.ee et al, "BioBERT: a pre-trained biomedical language representation model for biomedical text mining," Bioinformatics, Sep 2019.
