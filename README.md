# Mobile Romandie Beer: Building up your infrastructure to train CoreML models on a big scale
2024-05-29

Felix Krause
(currently working on ContextSDK)

You can fine-tune on device (example: Photos app for faces)

Classifiers:
 - Decision tree
 - Logistic Regression
 - Random Forest

Using sklearn

-> convert to coreml_model

Apple not very up to date with the library.

Call Model.prediction

Apple allows to update ML models over the air (no need to wait for review)

MLModel.compileModel

MLFeatureProvider
