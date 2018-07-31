# Teach-a-Neural-Network-to-Read-Handwriting
# ABSTRACT 

I have created a Handwritten digit recognition using Machine Learning. Neural networks and deep learning are two success stories in modern artificial intelligence. They’ve led to major advances in image recognition, automatic text generation, and even in self-driving cars. To get involved with this exciting field, you should start with a manageable dataset. The **MNIST Handwritten Digit Classification Challenge** is the classic entry point. Image data is generally harder to work with than “flat” relational data. The MNIST data is beginner-friendly and is small enough to fit on one computer. Handwriting recognition doesn’t need high computational power.

# I used Random Forest for it!!

# What is Random Forest?? 
1) Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks, that operate    by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes          (classification) or mean prediction (regression) of the individual trees. Random decision forests correct for decision trees' habit of  overfitting to their training set.

2) The first algorithm for random decision forests was created by Tin Kam Ho using the random subspace method, which, in Ho's formulation,    is a way to implement the "stochastic discrimination" approach to classification proposed by Eugene Kleinberg.

3) An extension of the algorithm was developed by Leo Breiman and Adele Cutler, and "Random Forests" is their trademark.The extension        combines Breiman's "bagging" idea and random selection of features, introduced first by Ho and later independently by Amit and Geman in    order to construct a collection of decision trees with controlled variance.
 
  
# Where we Use Random Forest?? 

The random forest algorithm is used in a lot of different fields, like Banking, Stock Market, Medicine and E-Commerce. In Banking it is used for example to detect customers who will use the bank's services more frequently than others and repay their debt in time.

# Why I used Random Forest??
1) The accuracy score is the only true measure of their relative performance, though there may be prior art that indicates which type of      classifier from the many available might be better on your type of data if you are lucky.
2) Random Forest Classifier:	96.82%.
3) I would say, the choice depends very much on what data you have and what is your purpose. A few "rules of thumb". 
4) Random Forest works well with a mixture of numerical and categorical features. When features are on the various scales, it is also        fine. Roughly speaking, with Random Forest you can use data as they are. SVM maximizes the "margin" and thus relies on the concept of      "distance" between different points. It is up to you to decide if "distance" is meaningful. As a consequence, one-hot encoding for        categorical features is a must-do. Further, min-max or other scaling is highly recommended at preprocessing step.
# REQUIREMENTS 
1) Python 3.5 +
2) Scikit-Learn (latest version)
3) Numpy (+ mkl for Windows)
4) Matplotlib
5) Scipy
# Usage
1. Download the four MNIST dataset files from this link:
       [(http://yann.lecun.com/exdb/mnist/)]
 
2. Unzip and place the files in the dataset folder inside the MNIST_Dataset_Loader folder under each ML Algorithm folder i.e :

KNN
|_ MNIST_Dataset_Loader
   |_ dataset
      |_ train-images-idx3-ubyte
      |_ train-labels-idx1-ubyte
      |_ t10k-images-idx3-ubyte
      |_ t10k-labels-idx1-ubyte
Do for RFC folders and you should be good to go. 
3. To run the code, navigate to one of the directories for which you want to run the code using command prompt:
  [(cd 1. Random Forest Classifier/)]
  and then run the file "RFC.py" as follows:
  [(python RFC.py)]
  This will run the code and all the print statements will be logged into the "summary.log" file.

NOTE: If you want to see the output to print on the Command prompt, just comment out line 16, 17, 18, 106 and 107 and hence you will get all the prints on the screen.

Alternatively, you can also use PyCharm to run the code and run the ".py" file in there.
4. To run the code, you don't need to provide in the MNIST dataset as it'll be downloaded automatically.
   or download it from-> http://yann.lecun.com/exdb/mnist/
   
#  Advantage

1)open source and continously developed.

2)good visualization tools.

3)scalability and portability.

4)steeper learning curve to become good at it.

5)implies solid knowledge of math.

# ScreenShots

Teach-a-Neural-Network-to-Read-Handwriting/Code Output.PNG

