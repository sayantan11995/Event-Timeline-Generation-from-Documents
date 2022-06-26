# Event-Timeline-Generation-from-Documents

All files are experimented in Google Colab Notebook

1. bert_event_extraction.ipynb
=> used for extracting events from list of sentences using BERT

2. tag_creation.ipynb
=> used for generating knowledge based tags using three methods

3. unsupervised_coref_resolution.ipynb
=> used to perform the event coreference resolution using several unsupervised techniques

4. supervised_coref_resolution.ipynb
=> used to perform the event coreference resolution using supervised mention pair model

5. full_system_eval.ipynb
=> used to perform full system evaluation (the classification is done using SVM). To use GAN-BERT as classifier you need to setup GANBERT environment from https://github.com/crux82/ganbert-pytorch

6. comparison_TLS.ipynb
=> used to compare the event timeline output with TLS approach. To run this code you need to setup TLS environment from https://github.com/complementizer/news-tls
