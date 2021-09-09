# MY-FINAL-PROJECT
The Artificial Neural Network which I've created for my final project in Python language.
The symbols and the company names which the symbols refer to:
AAPL --> Apple
GOOGL--> Alphabet(Google) (GOOGL is for the Class A Stock of the company, it has taken into consideration in this project, I wanted to indicate so that no complexity may occur.)
MSFT --> Microsoft
FB-->Facebook
TSLA--> Tesla

I obtained all the data from the official web site of American NASDAQ index --> https://www.nasdaq.com

The predictions and some needed adaptations such as the number of epocs and the batch sizes etc. for the stocks of the 5 companies(Apple, Alphabet(Google),Microsoft, Facebook and Tesla) vary, however the main template is the same as it can be seen.

My prediction algorithm conists two basic steps:
  FIRST: I closed the data of the most 2 current days and I predicted the daily close/last transaction price of vthe the day before the most current day. And I evaluated the prediction performance using evaluation function of the layer structure of the ANN.
  SECOND: I closed the data only of the most current day and I predicted the daily close/last transaction price of that day and I evaluated the prediction performance using evaluation function of the layer structure of the ANN like I did at the first step.

 
  
   
