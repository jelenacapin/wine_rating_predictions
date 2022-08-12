# Using Supervised Learning & Natural Language Processing to Predict Wine Ratings 
### [BrainStation](https://brainstation.io) Capstone - Aug 2022
### Jelena Capin - [LinkedIn](https://www.linkedin.com/in/jelena-capin)

The goal of this project is to predict wine ratings based on reviews made by experts, in conjunction with several characteristics of the wine in review. This dataset represents reviews made by tasting experts for Wine Enthusiast Magazine. The data was scraped directly from Wine Enthusiast's [website](https://www.winemag.com/), by a Kaggle [user](https://www.kaggle.com/zynicide). The dataset can be found [here](https://www.kaggle.com/datasets/zynicide/wine-reviews?select=winemag-data-130k-v2.csv). 

### Problem Statement & Value Add:
Predicting wine scores can benefit those on the consumer side, as well as those on the supply side. If you're a wine collector, or if you're someone looking to purchase a pricier wine as a gift for a friend or a treat to yourself, having the ability to predict a wine's rating can help you make more informed decisions as a buyer. My capstone project focuses on the value this adds to producers and suppliers. On the supply side, wine producers, wine importers and distributors (agents), and retailers that sell wine would gain valuable insights before making costly decisions or large investments. Wine producers can predict wine ratings prior to production based on varietals, expected tannins, specific flavours, etc. Similarly, importers and distributors can predict an international wine's rating prior to agreeing to represent the wine in their domestic market. And finally, retailers, like the LCBO in Ontario, or small wine retailers across the U.S., can predict a wine's success prior to purchasing inventory. 

### Notebooks Folder:
I have merged all of my notebooks to a single notebook. You can find the complete notebook in the Notebooks folder. I plan to fit an ensemble learning model in the future. Once I complete that phase of the project, I will add those notebook(s) to this folder. 

### Data Folder:
Contents:

* `clean_train_data`: training set free of nulls and duplicates, target (points) included
* `clean_remainder_data`: remainder set free of nulls and duplicates, target (points) included
* `clean_validation_data`: validation set free of nulls and duplicates, target (points) included
* `clean_test_data`: test set free of nulls and duplicates, target (points) included

* `train_model_data`: encoded, vectorized, model-ready training data (unscaled), target (points) included
* `valid_model_data`: encoded, vectorized, model-ready validation data (unscaled), target (points) included
* `test_model_data`: encoded, vectorized, model-ready testing data (unscaled - transformed using training set), target (points) included
* `remainder_model_data`: encoded, vectorized, model-ready remainder data (unscaled), target (points) included
* `test_model_data2`: encoded, vectorizer, model-ready testing data (unscaled - transformed using remainder set), target (points) included
<br>
<br>
<br>
### Questions? Feedback? Contact me [here](https://www.linkedin.com/in/jelena-capin)
