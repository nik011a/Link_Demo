the testing of the models is doen in result file if you want to test the models locally without doing preprocessing

the preprocesing with lower string,stop word removal and lemmatization is done in Link file
first overall state of data is evaluated and then the preprocessing is done
data didnt seem to be missing since we checked for shortest or empty rows.
dataset was well balanced
lemmatisation was used instead of stemming with the aim of reducing words however based on text result 
a limited number of words were affected and some were affected negatively like US

in Untitled grid search was performed and with those results the models were created

Svm outperformed Random forest in almost all metrics  and had a good overall balance
Lematization affected performance only slightly but cost a lot in pre processing time

the class from which i load data to untitled was to large so only the models are uploaded
******notebook shows only latest runs some of the choices were made on previous resulsts***


Dataset was downloaded directly frum python library wich didnt provide a link but kaggle/huggingface provided similar dataset
https://huggingface.co/datasets/sh0416/ag_news




