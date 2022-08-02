ABSTRACT:


DATASET:
13 datasets with 17.5K, or 35K, or 3541 samples, 354 or 220 features, and 70 or 10 classes were used to compare the performance of different pairs of Dimensionality Reduction and Classification algorithms.
The folder 'Datasets' contains all these datasets.


CODE files:
There are 4 code files. 

baselinecf.ipynb - Baseline classification
lda_dr.ipynb - LDA using sklearn with 4 given classifiers
IsoMap_DR - Isomap using SKlearn with 4 given classifiers
sammontest.ipynb - Sammon mapping function (from Tom Pollard's repo) with 4 given classifiers

All these files contain a classifier block that takes the desired model from a list of classifiers. 
For experimentation, we used to keep the classifier we were working on in the list in the get_model() function 
and comment the other classifiers.


REPORT:
'final_report_dr03.pdf' is a detailed 20 page report explaining each dimensionality technique along with the pseudo-code.
The report also contains 40+ graphs of 10-fold accuracy and f1-score delivered by different combinations of DR techniques and sclassifiers.