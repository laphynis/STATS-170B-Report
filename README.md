# STATS 170B - Social Media & Crime
Demonstration of our STATS 170B project on crime count and social media sentiment.


## Data Files
**testing_set.csv** - This .csv file contains the observations used for our testing and validation to compare results against other algorithms.

**doc2vecembeds.csv** - This .csv file contains the embeddings of the social media data collected from Reddit. Using doc2vec, the embeddings for each observation are converted into 384-length vectors.

**finalPred.csv** - This file contains the true crime count and the predictions of the models based on the testing set.

## Models
**XGBCensusmodel.json** - The optimized XGBoost regressor model trained only on census data.

**XGBEmbedmodel.json** - The optimized XGBoost regressor model trained only on the embedded social media data.

**XGBCombinedmodel.json** - The optimized XGBoost regressor model trained on the combined census and social media data.

## Other files
**finalizedModels.ipynb** - Our notebook that contains the code which demonstrates what we did in our project and our results.

**project.html** - A .html version of the notebook where all output cells are already shown.

## How to run the project demonstration
All the data has been preprocessed beforehand, so the demonstration can be run through the notebook finalizedModels.ipynb.
