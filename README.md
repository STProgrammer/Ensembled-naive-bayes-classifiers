# Answer to graded assignment 2 in DTE-2501 (AI Methods and Applications) about ensemble methods by Abdullah Karagøz

In this assignment I test ensemble methods in classification. The ensemble methods use Gassian Naïve Bayes classifiers.Int

The goal is to test and show how a simple Gaussian Naïve Bayes classifier performs when used as stand alone versus used with ensemble method.

I first built all the classes and functions. Then uploading, testing and comparing was easy, so uploaded 5 different datasets including Iris dataset and report the performance results using Gaussian NB classifier and using ensembled method with Gaussian NB classifiers.

I built the classifiers and ensemble methods self, but compared results using my classes with using libraries from Scikit-learn libraries. I haven't used Scikit-learn in my classes. Scikit-learn classes are used only to compare.

Since teachers didn't allow using Numpy I didn't use Numpy in my code. The only place I used Numpy is when preparing train and test set to Scikit-learn libraries, as it needs Numpy as argument. The API of the classes I built looks a bit similar to Scikit-learn, but they're far from same. My intention wasn't to build classes with same API as classes from Scikit-learn.

**I have build 3 classes and 2 functions.**

**The classes are:**

-   Gaussian Naïve Bayes classifier: The class only accepts data with numerical attributes. The classes must be turned into integers starting from 0.
-   Ensemble Naïve Bayes classifier: The class accepts Gaussian Naïve Bayes classifiers I built. It uses two methods: majority voting and probability aggregation.
-   Metrics class: A class with static functions that calculate Cross Entropy Loss, accuracy and F1 score.

**The functions are:**

-   Testing function: Testing all the classifiers, both single and ensemble methods, using both majority voting and probability aggregation. It tests Gaussian Naïve Bayes classifier and ensemble classifier from Scikit-learn too just for comparieon.Then it prints and compares the results using metrics like mean Cross Entropy Loss, F1 score and accuracy.
-   Plotting function: This is testing only the ensemble methods, majority voting, probability aggregation, and class from Scikit-learn. It compares from 0 to N number of classifiers how perofrmance changes when you increase number of classifiers in the ensemble method.

In the code I have first built the classes and functions mentioned above. Then I have uploaded datasets and tested them.
