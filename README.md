# Toxic Comment Classification
This project aims to detect different types of of toxicity like threats, obscenity, insults, and identity-based hate on online platforms. The dataset of comments comes from Wikipedia’s talk page edits. The methods discussed in this project will hopefully help online discussion become more productive and respectful.

*Disclaimer: the dataset for this competition contains text that may be considered profane, vulgar, or offensive.*

I tried three models for this task. First model is a Naive-Bayes- SVM model. Naive Bayes uses bag of words model and thus not consider context. But this simple model gives 97.7% accuracy. Next I also tried a LSTM based deep model. I tried training embedding vectors as well as using Glove embeddings. Glove embeddings work better and improve the accuracy slightly. And lastly, since both these methods are very different I tried stacking both the models which improved the results even further. Here is the link to the GitHub repo.
