
# Early Detection of Parkinson's Disease

Any disease in the human body is tough. Parkinson's disease is also one of them. Many of us don't know about this disease and its symptoms unless we know someone who has it. Early Detection of this disease is important. they say it doesn't have any cure. Some of its symptoms are weakening of the central nervous system, tremors, slowed movement, freezing, rigidity, and shuffling steps. 

Motivation:
there are these people who are facing a lack of balance in movement from the moment they suffer from this disease, not able to even dress, not able to even pick a glass of water, it would be very difficult for them and for their loved ones. Writing about its definition and symptoms won't do any justice to the people who are suffering from this. This project of detection of Parkison's disease using machine learning libraries is a little motivation I got from these people who despite every obstacle they have in life still doing their job so well.


## Tech Stack
I used UCI ML Parkinsons dataset which has 24 columns and 195 records. This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD.

## Preprocessing Analysis
![image](https://github.com/Mahak-G/Parkinson-Analysis/assets/56362610/b90ea0d1-6da4-4c57-8cbc-9005fc1e3504)

In this project, we will use the XGBClassifier from the xgboost library, RandomForestClassifier from sklearn.ensemble, SVC from sklearn.svm and Artificial Neutral Network(ANN) model that will contain two hidden layers and one output layer. Finally, we compare all these four models and check which works better.

## Result Analysis
![image](https://github.com/Mahak-G/Parkinson-Analysis/assets/56362610/3e10899f-c791-43dd-b446-0180a1ecdced)





