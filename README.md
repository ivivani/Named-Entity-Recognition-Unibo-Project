# Named Entity Recognition per la lingua italiana: fine-tuning di Italian BERT

# Descrizione
Questo progetto è stato svolto da Irene Vivani e Carolina Ajmone Marsan e proposto come prova finale del corso Modelli neurali per l'elaborazione del linguaggio naturale (laurea magistrale in Dati, metodi e modelli per le scienze linguistiche presso l'Università di Bologna). Il lavoro è stato svolto collaborativamente per mezzo del notebook Google Colab principale, [train.ipynb](Named-Entity-Recognition-Unibo-Project/train.ipynb), sperimentando diverse combinazioni di iperparametri prima di procedere con la fase di evaluation sul test set in [eval.ipynb](Named-Entity-Recognition-Unibo-Project/eval.ipynb).

L'obiettivo principale è consistito nell'analisi dello script [run_ner_no_trainer.py](https://github.com/huggingface/transformers/blob/main/examples/pytorch/token-classification/run_ner_no_trainer.py) e nella messa in pratica di quanto appreso durante il corso riguardo alle tecniche di fine-tuning.

In particolare, è stato utilizzato il modello pre-addestrato [dbmdz/bert-base-italian-cased](https://huggingface.co/dbmdz/bert-base-italian-cased), disponibile su HuggingFace. 
Per quanto riguarda il dataset, invece, è stato selezionato [Babelscape/wikineural](https://huggingface.co/datasets/Babelscape/wikineural), prodotto da Babelscape.

Si rimanda al Report presente tra i file di questo progetto per maggiori dettagli sugli strumenti utilizzati, le modifiche apportate allo script e i risultati ottenuti.

## Struttura
* Script:
  * project_run_ner_no_trainer.py
  * evaluation_run_ner_no_trainer.py
* Notebook:
  * train.ipynb
  * eval.ipynb
* Report:
  * Report_NER_Vivani_AjmoneMarsan.pdf
