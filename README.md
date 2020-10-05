# iris_svm_classification

This is a little project that I did to practice building a Support Vector Machine (SVM) model. The goal was to use the well-known scikit-learn iris data set to build an SVM model that would classifiy irises based on sepal and petal length and width measurements. I learned from the documentation that one set of irises in the data set is linearly separable from the other two, but the remaining two are not linearly separable from each other; thus, I expect that the SVM model I build will be able to separate one iris species from the other two, and the remaining two will probably have a couple of misclassifications between them. I indeed found this to be the case.

This project was done with Python 3.0 and Jupyter Notebook. I used the scikit-learn iris data set, and utilized Pandas, NumPy, Matplotlib, and the scikit-learn packages model_selection, preprocessing, and svm in my analysis. So long as you have Jupyter Notebook and the named packages installed, the project should run on your machine.
The project itself has been included as iris_classification.ipynb.
