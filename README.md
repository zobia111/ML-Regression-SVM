(A) Linear Regression:


1- How many steps will the algorithm take in 2 epochs if your training data consists of 1000 datapoints and you are using SGD?

2- Write the stochastic gradient descent update rules for  𝑤(j) and 𝑏 for LASSO regression.

3- Plot the loss curves for the following training configurations:

50 epochs, no regularization, η=0.01
50 epochs, no regularization, η=0.001
50 epochs, L1 regularization, η=0.001, λ=1
50 epochs, L1 regularization, η=0.001, λ=0.1
50 epochs, L1 regularization, η=0.001, λ=0.001

4- Plot the coefficient magnitudes for the three LASSO regularized models as line plots. Use log(λ) on the x-axis and coefficient values on the y-axis.

5- Compute and report the test loss for each training configuration. Report the loss values to at least five decimal places.

(B) Support Vector Machines:


1- Pick two digits from the MNIST dataset and create a subset containing only those digits. Randomly divide the data into training and test sets (70%-30% split).

2- Train an SVM classifier with a linear kernel on the training data and fine-tune the cost parameter C using cross-validation. What is the highest cross-validation accuracy and the corresponding C value?

3- Report precision, recall, and accuracy values of the linear kernel SVM classifier on both training and test data.

4- Perform SVM classification using the RBF kernel. Tune the parameters 𝐶 and 𝛾 using cross-validation. What is the best cross-validation accuracy and the corresponding 𝐶 and 
γ values?

5- Re-train the RBF kernel SVM classifier on the full training data using the best parameter pair and classify the test data. Report precision, recall, F1, and accuracy values for both training and test data.
