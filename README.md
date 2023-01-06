# Counterfactual-Augmentation-CFA-

This repository provides details of the experimental code in this paper: Solving the class imbalance problem using a counterfactual method for data
augmentation.

The major novel focus of the current paper is on whether counterfactual methods from eXplainable AI (XAI) can be used to solve the class imbalance and data augmentation problems to deliver better predictive performance of AI models. Unlike other oversampling techniques, this method adaptively combines existing instances from the dataset, using actual feature-values rather than interpolating values between instances. We report Several experiments using four different classifiers and 25 datasets involving binary classes, which show that this Counterfactual Augmentation (CFA) method generates useful synthetic datapoints in the minority class. The experiments also show that CFA is competitive with many other oversampling methods, many of which are variants of SMOTE. The basis for CFA’s performance is discussed, along with the conditions under which it is likely to perform better or worse in future tests.

<img width="876" alt="Screen Shot 1443-11-17 at 2 46 10 PM" src="https://user-images.githubusercontent.com/121910491/211099498-90397061-caf4-45c0-ac44-8c19e5300015.png">
