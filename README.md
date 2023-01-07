# Counterfactual-Augmentation-CFA-

This repository provides details of the experimental code in this paper: Solving the class imbalance problem using a counterfactual method for data
augmentation.

The major novel focus of the current paper is on whether counterfactual methods from eXplainable AI (XAI) [1,2] can be used to solve the class imbalance and data augmentation problems to deliver better predictive performance of AI models. Unlike other oversampling techniques (e.g., SMOTE [3]), this method adaptively combines existing instances from the dataset, using actual feature-values rather than interpolating values between instances. We report Several experiments using four different classifiers and 25 datasets involving binary classes, which show that this Counterfactual Augmentation (CFA) method generates useful synthetic datapoints in the minority class. The experiments also show that CFA is competitive with many other oversampling methods, many of which are variants of SMOTE. The basis for CFA’s performance is discussed, along with the conditions under which it is likely to perform better or worse in future tests.

<img width="876" alt="Screen Shot 1443-11-17 at 2 46 10 PM" src="https://user-images.githubusercontent.com/121910491/211099498-90397061-caf4-45c0-ac44-8c19e5300015.png">

<h2>Datasets</h2>
The seven techniques were tested on a representative selection of 10 commonly-used UCI/ KEEL datasets [4, 5][], from which 25 dataset-variants were produced
(http://archive.ics.uci.edu/ml) (https://sci2s.ugr.es/keel/imbalanced.php) </br></br>

<h2>ML Classifiers</h2>
The seven techniques were tested with four different ML classifiers: including, Random Forest (RF), k-nearest neighbor (k-NN), Logistic Regression (LR), and Multilayer Perceptron (MLP) models.</br></br>

<h2>Experimental Results</h2>
<img width="455" alt="Screen Shot 1443-10-11 at 2 53 12 AM" src="https://user-images.githubusercontent.com/121910491/211099744-b9fa832f-237f-4d11-8443-83f85d0cf1a3.png">


<h2>References</h2>
[1] Keane, M. T., & Smyth, B. (2020). Good counterfactuals and where to find them: A case-based technique for generating counterfactuals for explainable AI (XAI). In Proceedings of the 28th international conference on case based reasoning (pp. 163–178). New York: Springer, http://dx.doi.org/10.1007/978-3-030-58342-2_11.</br></br>
[2] Smyth, B., & Keane, M. T. (2022). A few good counterfactuals: Generating interpretable, plausible and diverse counterfactual explanations. In Proceedings of the 30th international conference on case based reasoning (pp. 163–178). New York: Springer, https://arxiv.org/abs/2101.09056.</br></br>
[3] Chawla, N. V., Bowyer, K. W., Hall, L. O., & Kegelmeyer, W. P. (2002). SMOTE: Synthetic minority over-sampling technique. Journal of Artificial Intelligence Research, 16(1), 321–357. http://dx.doi.org/10.1613/jair.953.</br></br>
[4] Blake, C., & Merz, C. (1998). UCI Repository of Machine Learning Databases. Department of Information and Computer Science. Irvine, CA, USA: University of California, http://archive.ics.uci.edu/ml.</br></br>
[5] Alcalá-Fdez, J., Fernandez, A., Luengo, J., Derrac, J., García, S., Sánchez, L., & Herrera, F. (2011). KEEL data-mining software tool: Data set repository, integration of algorithms and experimental analysis framework. Journal of Multiple-Valued Logic and Soft Computing, 17, 255–287, https://sci2s.ugr.es/keel/pdf/keel/articulo/2011- KEEL-dataset-MVLSC.pdf.
