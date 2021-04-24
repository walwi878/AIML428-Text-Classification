AIML428 Project - Sentiment-Analysis
William Wallace
17/04/21

This is the my project code for the AIML428 course. 
This code analyses the sentiment based on two datasets:

1) the stack-overflow.csv dataset consisting of Stack Overflow posts (text
   input) and the computer language that the post is about (class). This 
   dataset can be downloaded from here: https://archive.org/details/stackexchange

2) the complaints_cleaned_v10.csv dataset consisting of the description of 
   complaints about consumer financial products and services (text input)
   and the product that they were complaining about (class). This dataset 
   can be downloaded here: 
   https://catalog.data.gov/dataset/consumer-complaint-database


HOW TO RUN:

This code can be run by selecting the "Open in Colab" button at the 
top of the .ipynb file of this repository when opened in Github 
(https://github.com/walwi878/AIML428-Text-Classification).
In Google Colab, under the Runtime tab, select "Run all" if you want to 
run all of the text analysis methods, or ctrl-click the code-blocks that 
you want to run individually. 

NOTE: some code blocks can take upwards of minutes to run, notably
"Word2vec + regression", "Doc2vec + regression", and "Bag of Words" 
- especially for the large customer_complaints_v10 dataset. Be patient. 

The link to step 1 - the baseline classification system is here: 
https://colab.research.google.com/drive/1E8gLubbvawscMXcsH6dsVseo1kdj0Rrt#scrollTo=MS1BHGXPFxz0

The link to step 2 - apply the baseline system on a new dataset - is here:
https://colab.research.google.com/drive/1nx9zAwvIKjEntLCSvdmkdUiJ4IbcdKFO#scrollTo=vatrEDLkU62n

The link to step 3 - improve the accuracy - is here:
https://colab.research.google.com/drive/1nx9zAwvIKjEntLCSvdmkdUiJ4IbcdKFO#scrollTo=vatrEDLkU62n
