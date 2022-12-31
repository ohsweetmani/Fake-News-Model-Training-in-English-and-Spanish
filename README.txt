# Fake-News-Model-Training-in-English-and-Spanish

## Background
In today's world, there is an overwhelming amount of information being communicated via social media or news sites. There are even parody news sites that some may mistake as real, factual news sites. Sometimes, people will even deliberately spread misinformation for nefarious reasons like hurting a person's reputation. With how easy it is for people to spread misinformation online, it has become increasingly difficult to recognize the truth over 'fake news'. 

According to the Cambridge Dictionary, the definition of "fake news": 
> false stories that appear to be news, spread on the internet or using other media, usually created to influence political views or as a joke 

Given the prevalence of fake news, I wanted to try to building a model to detect fake news. I was also interested in fake news detection in languages other than English.  Since I am fluent in Spanish, I decided to also focus upon fake news detection in Spanish. 

## Navigation 
- Clean and Process: contains Original Datasets used and relevant code 
- Model Fit, Train, Test: contains cleaned & processed datasets, relevant code and plots of test results 

## Dataset Sources 
- English Dataset  Kaggle: https://www.kaggle.com/datasets/nopdev/real-and-fake-news-dataset 
- Spanish Dataset  IberLEF 2021 conference  https://github.com/jpposadas/FakeNewsCorpusSpanish

## Conclusions
In conclusion, English trained models outperformed Spanish trained models on average by 13%. For English model, the average accuracy was 82% while the Spanish model's average accuracy was 70%. The English trained models performed significantly better than the  Spanish trained models most likely because of the small amount of Spanish data to train the model on. The English dataset had about ten times as much data as the Spanish dataset. 

In the future, I would like to train the Spanish models on more data and try to achieve a similar accuracy level to English models. Furthermore, I would like to build an interactive application where you could see whether news was fake or real. You would be able to choose a model and feed in the contents of a newspaper article. The application would then tell you whether it was fake or real news along with the percent accuracy for the model. 

