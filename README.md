# Sentiment Analysis on Genshin Impact Reviews with BERT
## Final Project Repository for Artificial Intelligence
Created by: Tiffany.W, Jocelin.W, Filbert.F, Daniel.P
## About
Genshin Impact, a recently popular online game application developed by miHoYo, has garnered widespread downloads across all the mobile and PC platforms.  With that said, there are a total of 4.4 million reviews written in the Google Play store itself. As the number of reviews for the game continues to grow rapidly, developers face the challenge of understanding past user feedback leading to the slow incorporation of meaningful insight into the game. In response to this challenge, we decided to conduct sentiment analysis on the english reviews for the Genshin Impact application found in the Google Play Store. The goal is for the model to be able to accurately predict the user sentiment towards the game which can be either negative, neutral or positive. This analysis utilized the Bidirectional Encoder Representations from Transformers (BERT) method to gauge user sentiment, aiming to provide a comprehensive record for developers.
## Folder Contents
Inside the FinalProject folder:
- GenshinBERTModelFinal.ipynb (model training and more)
- GenshinReview.csv (cleaned 4200 dataset without stopword removal) 
- ScriptGenshin.ipynb (to test the saved model)
- GenshinModel_save (folder containing the saved model)
Other files:
- output.csv (raw scraped 4k dataset)
- sentimental_model.ipnyb (for sentimental analysis)
- GenshinReviews1.csv (dataset with stopword removal for sentimental_model.ipnyb)
## Packages
Please pip install the following packages first before running the code:
- Pytorch
- Transformers
- Pandas
- Numpy
## Report
https://docs.google.com/document/d/17YzY8jhYLawIPg3yeTrP-JstdReMt9d5siwaStCksOs/edit?usp=sharing
## Video demo
https://youtu.be/n9C1-EYMwr0

