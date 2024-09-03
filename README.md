# Binary Classification of Mushrooms
my attempt and the august kaggle challenge. I decided to use catboost and lgbm
with a voting ensamble due to the capacity restraints of my gpu hours. 
Too many of my runs failed, but learned a lot. 
## Acknowledgement's
This was my first time using seaborn and exploring data. I gleaned a lot of my
insights from the following notebooks:
https://www.kaggle.com/competitions/playground-series-s4e8/discussion/524434
https://www.kaggle.com/competitions/playground-series-s4e8/discussion/527194

##Extra
With 3 million rows, It's impractical to really go through and scrub data 
sufficently, I think the approach of just assigning missing data with its own
label and letting the model's handle it is the best in this situation.
as to why catboost and lgbm over xgboost? It was mainly to learn about other gradient boost models and thier intricacies
