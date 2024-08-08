#BERT Model Implementation 

Task:
The idea for this project was taken from the Languages and Dialects of Italy (ITDI) task that was
designed for the VarDial Evaluation Campaign 2022. The task is to build a classification model that
differentiates among 11 regional languages and varieties of dialects (Piedmontese, Venetian, Sicilian,
Neapolitan, Emilian- Romagnol, Tarantino, Sardinian, Ligurian, Friulian, Ladin, Lombard) in Italy.
We plan on using the same data-set that has been used for this task in the Vardial 2022 Campaign,
which is a Wikipedia dump and hence preprocessing of this data will also be a major part of our task.


Baseline Models for Comparison:
The Italian language identification task is a fairly recent project and no papers have been published
yet. The Transformer models like pretrained BERT (Devlin et al., 2019) were used to better
understand languages and have been proven to give great results for other languages previously. Since
there are no state of the art baseline models that are previously achieved for this task that can be
reproduced, we wanted to implement a BERT model and observe the results.
