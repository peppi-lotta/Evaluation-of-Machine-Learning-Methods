# Evaluation-of-Machine-Learning-Methods

Modern machine learning techniques provide invaluable tools for a wide range of application areas. However, they are pretty much useless if we can not trust that they can really carry out the tasks they are supposed to take care of or do they work at all, reflected by the old saying: "If you cannot measure it, you cannot improve it". This course first covers the background theory and assumptions behind standard approaches for statistical estimation of prediction performance for machine learning based artificial intelligence methods, such as independently and identically distributed (IID) sample of data, law of large numbers and its generalization for arbitrary estimators as well as cases in which the law does not hold. We then cover the basic resampling techniques, such as hold-out and cross-validation for prediction performance estimation or for model selection, and nested cross-validation for carrying out both of them simultaneously. The course also present a general framework for designing more sophisticated performance estimands indicating how well the AI system will perform given that the training data and new data is known a priori to differ from each other in a specific way. Practical and representative examples of this types of estimands are considered from the fields of chemoinformatics, medical informatics, geoinformatics and bioinformatics. Namely, we pose questions like how well a machine learning model generalizes to new types of measurements, such as to new data from new patients in contrast to new data from the same patients already observed in the training data, and provide group or subject level hold-out or cross-validation schemes for answering such questions. With spatial cross-validation techniques, we estimate how well a geospatial model predicts to new data known a priori to be at least a certain distance away from the geographically closest measurement in the training data. Further, we introduce cross-validation techniques for answering different kinds of of specific cold start prediction settings for learning problems with pairwise data, such as prediction of drug-target or protein-protein interaction strengths, customer-product recommendations, etc. For example the following four cases, predicting the interaction strength for new drug-target pairs of which both the drug and target component are encountered in the training data as part of some other drug-target pairs, only the drug has been encountered but not the target, only the target is encountered but not the drug, or neither the drug nor the target have been encountered, are very different problems and hence require completely different prediction performance estimation schemes. All of the cases considered in the course are based on recent research results by our group or other groups with the same interests.