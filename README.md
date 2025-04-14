# Predicting and Understanding Turn-Taking Behavior in Open-Ended Group Activities in Virtual Reality

## Repository Structure
The repository contains code for labeling turn-transition categories from the extracted audio data processed from ENGAGE (`behavior_labeling.ipynb`). In it, we also provide code scaffolding for visualizing turn-transition labeling that was used for creating Figure 2 in the paper.

Additionally, we also include code used for modeling and training the four machine learning models (i.e., logistic regression, MLP classifier, random foreset classifier, gradient boosting classifier) for the three prediction tasks related to turn-taking behaviors. The noteworks used for buliding and evaluating the models are called `turn_taking_vs_continuing.ipynb`, `next_speaker_prediction.ipynb`, and `timing_prediction.ipynb`, respectively. 

## Access to data
Due to IRB restrictions, the dataset used for the paper cannot be made public. Request for access to the dataset should be made to the authors directly.