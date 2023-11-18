# COMP47490-Machine-Learning

This is a machine learning task based on pulsar data analysis. 



Task 1: Prepare a data quality plan for the dataset. Mark down all the features where there
are potential problems or data quality issues. Propose solutions to deal with the problems
identified. Explain why did you choose one solution over potentially many other. It is very
important to provide justification for your thinking in this part and to list potential solutions,
including the solution that will be implemented to clean the data. In particular, pay attention
to missing data and carefully address this issue. [15 marks]
Task 2: Normalise or Standardise your features as necessary. Carefully decide the
normalisation or standardisation technique used. [5 marks]
Task 3: Carefully decide the evaluation measure that is best suited to this application and
the dataset. Justify your choice -- What characteristics of the application and the dataset
made you decide the evaluation measure you chose. [5 marks]
Task 4: Compare a decision tree classifier, a kNN classifier and four SVM classifiers (one
each with "linear", "poly", "rbf" and "sigmoid" kernel) based on the evaluation measure
selected in Task 3. Carefully decide the evaluation methodology for this comparison (e.g.,
cross validation or a single train/validation/test split or other alternatives). Explore the
effect of different parameter settings on these classifiers and find the winner classifier/
parameter setting. Why do you think you got those comparison results? In particular, are
you surprised at the relative performance of "linear", "rbf" and "sigmoid" kernels? [25
marks]
Task 5: Based on a filter technique, identify the three most discriminative features and the
three least discriminative features in this dataset. Run the SVM classifiers with the four
kernels on the top three and the bottom three features. How do the results compare? [10
marks]
Task 6: Carefully identify the most discriminating features to predict the binary outcome of
the dataset using one wrapper feature selection technique. This should be done for each
of the decision tree, kNN and four SVM classifiers from part Task 4. Report and discuss
the differences between the feature subsets produced by the filter (Task 5) and the
wrapper technique. [15 marks]
Task 7: Compare the performance of different classifiers using the different feature
subsets found in Tasks 5 and 6 and compare it to the results on original dataset that you
reported in Task 4. Have the results improved or worsened after feature selection? Is the
relative performance of different classifiers and configuration settings in line with your
expectation? [10 marks]
Task 8: Plot the ROC curves for the "1" class and the different classification models. What
do you learn from this ROC curve? Which classifier/configuration is best suited for this
task? Are you satisfied with the performance? [15 marks]
Task 9: BONUS Question. This part is open-ended -- Take the exploration and the
discussion deeper than what is asked in the above questions and gain further insights into
(i) correlation of the various features with the target class, (ii) feature selection and feature
Page of 2 3
importance, (iii) relative performance of different classifiers (different kernels in case of
SVM) and different parameter settings w.r.t different evaluation measures and (iv) effect of
different ways of imputing missing values on the final performance of different classifiers.
