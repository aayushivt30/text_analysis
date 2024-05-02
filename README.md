# text_analysis
This repository deals with analysis of feedbacks from customer
##Preprocessing is completed in the 2 steps

1.Feedbacks contain many languages so fisrt convert all feedbacks into english it is done in translate.ipynb

2.Removing special characters,numbers and blank rows is done in remove_charaters.ipynb

3.Intial number of feedbacks were : 15,120 after preprocessing : 14,550 saved to finalized_data.csv

4.KNN is performed with K=3,5,7

5. Ship-wise distribution is conducted and analysed using word cloud

6. text analysis is done using VADER and roberta model and compared. Roberta is more efficient and gives more accurate results than vader.  
