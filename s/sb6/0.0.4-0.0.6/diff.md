# Comparing `tmp/sb6-0.0.4.tar.gz` & `tmp/sb6-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sb6-0.0.4.tar", last modified: Sat Jun 17 13:04:26 2023, max compression
+gzip compressed data, was "sb6-0.0.6.tar", last modified: Wed Jun 28 15:19:16 2023, max compression
```

## Comparing `sb6-0.0.4.tar` & `sb6-0.0.6.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-17 13:04:26.340268 sb6-0.0.4/
--rw-rw-rw-   0        0        0     1067 2023-04-11 12:54:43.000000 sb6-0.0.4/LICENSE
--rw-rw-rw-   0        0        0      462 2023-06-17 13:04:26.339260 sb6-0.0.4/PKG-INFO
--rw-rw-rw-   0        0        0       69 2023-05-12 01:06:50.000000 sb6-0.0.4/README.md
--rw-rw-rw-   0        0        0       42 2023-06-17 13:04:26.340268 sb6-0.0.4/setup.cfg
--rw-rw-rw-   0        0        0      769 2023-06-17 13:04:13.000000 sb6-0.0.4/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-17 13:04:26.320739 sb6-0.0.4/src/
-drwxrwxrwx   0        0        0        0 2023-06-17 13:04:26.339260 sb6-0.0.4/src/sb6.egg-info/
--rw-rw-rw-   0        0        0      462 2023-06-17 13:04:26.000000 sb6-0.0.4/src/sb6.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      191 2023-06-17 13:04:26.000000 sb6-0.0.4/src/sb6.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-17 13:04:26.000000 sb6-0.0.4/src/sb6.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       52 2023-06-17 13:04:26.000000 sb6-0.0.4/src/sb6.egg-info/requires.txt
--rw-rw-rw-   0        0        0        4 2023-06-17 13:04:26.000000 sb6-0.0.4/src/sb6.egg-info/top_level.txt
--rw-rw-rw-   0        0        0   141676 2023-06-17 13:02:59.000000 sb6-0.0.4/src/sb6.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:19:16.684479 sb6-0.0.6/
+-rw-rw-rw-   0        0        0     1067 2023-04-11 12:54:43.000000 sb6-0.0.6/LICENSE
+-rw-rw-rw-   0        0        0      462 2023-06-28 15:19:16.683479 sb6-0.0.6/PKG-INFO
+-rw-rw-rw-   0        0        0       69 2023-05-12 01:06:50.000000 sb6-0.0.6/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 15:19:16.684479 sb6-0.0.6/setup.cfg
+-rw-rw-rw-   0        0        0      738 2023-06-28 15:16:09.000000 sb6-0.0.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:19:16.674479 sb6-0.0.6/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 15:19:16.683479 sb6-0.0.6/src/sb6.egg-info/
+-rw-rw-rw-   0        0        0      462 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      191 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       27 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        4 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0   150665 2023-06-28 15:17:16.000000 sb6-0.0.6/src/sb6.py
```

### Comparing `sb6-0.0.4/LICENSE` & `sb6-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `sb6-0.0.4/setup.py` & `sb6-0.0.6/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="sb6",
-    version="0.0.4",
+    version="0.0.6",
     description='chatbot',
     license='MIT',
     author="aiml department",
     author_email="aiml@gmail.com",
     long_description=long_description,
     long_description_content_type="text/markdown",
     packages=setuptools.find_packages(),
@@ -18,9 +18,9 @@
     py_modules=['sb6'],
     package_dir={'':'src'},
     classifiers=[
         "Programming Language :: Python :: 3",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent",
     ],
-    install_requires = ['openai','requests','gpt4free','opencv-python','scikit-learn']
+    install_requires = ['opencv-python','scikit-learn']
 )
```

### Comparing `sb6-0.0.4/src/sb6.py` & `sb6-0.0.6/src/sb6.py`

 * *Files 2% similar despite different names*

```diff
@@ -805,15 +805,15 @@
 ce() - Candidate Elimination 
 nbnos() - Naive Bayesian Classifier for numbers automatic: Compute the accuracy of the classifier, considering few test data sets
 nbother() - Naive Bayesian Classifier for numbers manual 
 nbtext() - Naive Bayesian Classifier for text :Assuming a set of documents that need to be classified : Calculate the accuracy, precision, and recall for your data set.
 svm() - Demonstrate the working of SVM classifier for a suitable data set
     """
     def enjoysportdataset():
-        print("""
+        print(r"""
 enjoysport.csv
         
 sky,airtemp,humidity,wind,water,forcast,enjoysport
 sunny,warm,normal,strong,warm,same,yes
 sunny,warm,high,strong,warm,same,yes
 rainy,cold,high,strong,warm,change,no
 sunny,warm,high,strong,cool,change,yes
@@ -1069,15 +1069,15 @@
     - subtables(data, col, delete): creates subtables for a given column in the dataset.
     - entropy(S): calculates the entropy of a set of data.
     - compute_gain(data, col): calculates the information gain for a given column in the dataset.
     - build_tree(data, features): builds a decision tree using the ID3 algorithm.
     - print_tree(node, level): prints the decision tree to the console.
     - classify(node, x_test, features): classifies a test instance using the decision tree.
         """
-        print("""
+        print(r"""
 import math 
 import csv
 
 def load_csv(filename):
 	lines=csv.reader(open(filename,"r"))
 	dataset=list(lines)
 	headers=dataset.pop(0)
@@ -1189,15 +1189,15 @@
       Demonstrate the working of the Random forest algorithm. Use an appropriate data set for building and apply this knowledge to classify a new sample.
       Random Forest is a popular machine learning algorithm that belongs to the category of ensemble learning methods. 
       It is widely used for both classification and regression tasks.
 
     In Random Forest, multiple decision trees are trained on different subsets of the training data, using a technique called "bootstrap aggregating" or "bagging." 
     Each tree is trained independently, and the final prediction is obtained by aggregating the predictions of all the individual trees.
         """
-        print("""
+        print(r"""
 from sklearn.datasets import load_iris
 iris = load_iris()
 X = iris.data
 y = iris.target
 
 from sklearn.model_selection import train_test_split
 X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.3, random_state=42)
@@ -1252,15 +1252,15 @@
         """
       k-Nearest Neighbors (k-NN) is a supervised machine learning algorithm used for both classification and regression tasks. 
       It is a non-parametric algorithm that makes predictions based on the similarity between a new data point and its k nearest neighbors in the feature space.
       When a new data point is given, the algorithm calculates the distance between that point and all the data points in the training set. 
       The distance metric used is typically Euclidean distance, although other metrics can also be used.
       For classification, the predicted class label for the new data point is determined by majority voting among its k nearest neighbors
         """
-        print("""
+        print(r"""
 import pandas as pd
 data = pd.read_csv('Iris.csv')
 X = data.iloc[:, :-1].values
 y = data.iloc[:, -1].values
 
 from sklearn.model_selection import train_test_split
 X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.3, random_state=42)
@@ -1289,15 +1289,15 @@
     It organizes data into rows and columns, similar to a table or spreadsheet, and provides various methods and operations for data manipulation.
     GaussianMixture is a class in scikit-learn, a popular machine learning library in Python. It is used to model data using a Gaussian Mixture Model (GMM). 
     GMM is a probabilistic model that assumes the data points are generated from a mixture of Gaussian distributions. 
     It is commonly used for clustering tasks where the goal is to assign data points to different clusters based on their statistical properties.
     EM algorithm, short for Expectation-Maximization algorithm, is an iterative algorithm used to estimate the parameters of statistical models when there are hidden or unobserved variables involved. 
     It is commonly used in unsupervised learning tasks such as clustering, where the goal is to find latent patterns or groupings in the data.
         """
-        print("""
+        print(r"""
 from sklearn.datasets import load_iris
 import pandas as pd
 dataset = load_iris()
 x = pd.DataFrame(dataset.data, columns=['sepal_length', 'sepal_width', 'petal_length', 'petal_width'])
 y = pd.DataFrame(dataset.target, columns=['Targets'])
 
 import numpy as np
@@ -1359,14 +1359,168 @@
 y_cluster_gmm=gmm.predict(xs)
 print('The accuracy score of EM: ',sm.accuracy_score(y,y_cluster_gmm))
 plt.subplot(1,3,3)
 plt.scatter(X.Petal_Length,X.Petal_Width,c=colormap[y_cluster_gmm],s=40)
 plt.title("GMM Classification")
 '''
         """)
+        
+    def pp():
+        """
+        Data Cleaning - Identifying and Deleting Duplicate Rows:
+            The program removes duplicate rows from the housing DataFrame using the drop_duplicates() function.
+            The resulting DataFrame with duplicates removed is stored in the housing_cleaned variable.
+        Data Integration - Identifying and Deleting Columns with a Single Value:
+            The program identifies columns in the housing_cleaned DataFrame that have only one unique value.
+            It appends these columns to the columns_to_drop list.
+            The identified columns are then dropped from the DataFrame using the drop() function.
+            DataFrame that have only one unique value means finding columns where all the values are the same throughout the entire column. 
+            In other words, these columns provide no meaningful variation or information because they have only one distinct value.
+        Data Transformation - Preprocessing Pipeline:
+            First, the program creates two lists: num_attribs to store the names of numerical columns and cat_attribs to store the names of categorical columns.
+            Next, two separate pipelines are created. The num_pipeline is responsible for handling numerical data, while the cat_pipeline handles categorical data.
+            In the num_pipeline, missing values in numerical columns are filled using the median strategy. Then, the features in the numerical columns are scaled using a technique called standardization, which makes them easier to compare and interpret.
+            In the cat_pipeline, categorical features are encoded. First, ordinal encoding is applied, which assigns numeric labels to the categories while preserving any order or hierarchy that may exist. Then, one-hot encoding is performed,
+            creating binary columns for each category to represent their presence or absence in each sample.
+            To apply these pipelines to the respective columns, a ColumnTransformer called full_pipeline is created. 
+            It takes the num_pipeline for numerical columns and the cat_pipeline for categorical columns.
+        """
+        print(r"""
+import pandas as pd
+from sklearn.impute import SimpleImputer
+from sklearn.preprocessing import StandardScaler, OrdinalEncoder, OneHotEncoder
+from sklearn.compose import ColumnTransformer
+from sklearn.pipeline import Pipeline
+housing = pd.read_csv('housing.csv')
+
+# Data Cleaning - Identifying and Deleting Duplicate Rows
+housing_cleaned = housing.drop_duplicates()
+print("Number of rows after removing duplicates:", len(housing_cleaned))
+
+# Data Integration - Identifying and Deleting Columns with a Single Value
+columns_to_drop = []
+for column in housing_cleaned.columns:
+    if housing_cleaned[column].nunique() == 1:
+        columns_to_drop.append(column)
+housing_integrated = housing_cleaned.drop(columns=columns_to_drop)
+print("Columns after removing single-valued columns:")
+print(housing_integrated.columns)
+
+# Data Transformation - Preprocessing Pipeline
+num_attribs = list(housing_integrated.select_dtypes(include=['float64', 'int64']))
+cat_attribs = list(housing_integrated.select_dtypes(include=['object']))
+num_pipeline = Pipeline([
+    ('imputer', SimpleImputer(strategy="median")),
+    ('std_scaler', StandardScaler()),
+])
+cat_pipeline = Pipeline([
+    ('ordinal_encoder', OrdinalEncoder()),
+    ('one_hot_encoder', OneHotEncoder()),
+])
+full_pipeline = ColumnTransformer([
+    ("num", num_pipeline, num_attribs),
+    ("cat", cat_pipeline, cat_attribs),
+])
+housing_preprocessed = full_pipeline.fit_transform(housing_integrated)
+print("Preprocessed data shape:", housing_preprocessed.shape)
+        """)
+        
+    def ec():
+        """
+        Ensemble learning is a machine learning technique that combines the predictions of multiple individual models, known as base models or weak 
+        learners, to make more accurate and robust predictions.  
+        Voting: Each base classifier gets one vote, and the class with the majority of votes is chosen as the final prediction. This can be further classified into majority voting (simple voting)
+        Averaging: The predictions of each base classifier are averaged to produce the final prediction.
+        Stacking: In this approach, the predictions of base classifiers are used as input features for a meta-classifier. The meta-classifier learns to combine these predictions and make the final decision.
+        """
+        print(r"""
+from sklearn.datasets import make_moons
+from sklearn.model_selection import train_test_split
+from sklearn.ensemble import VotingClassifier
+from sklearn.linear_model import LogisticRegression
+from sklearn.ensemble import RandomForestClassifier
+from sklearn.svm import SVC
+from sklearn.metrics import accuracy_score
+X, y = make_moons(n_samples=100, noise=0.15)
+X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.3, random_state=42)
+log_clf = LogisticRegression()
+rnd_clf = RandomForestClassifier()
+svm_clf = SVC()
+voting_clf = VotingClassifier(estimators=[('lr', log_clf), ('rf', rnd_clf), ('svm', svm_clf)], voting='hard')
+voting_clf.fit(X_train, y_train)
+y_pred_voting = voting_clf.predict(X_test)
+print("Voting Classifier Accuracy:", accuracy_score(y_test, y_pred_voting))
+
+
+'''
+from sklearn.datasets import load_iris
+from sklearn.model_selection import train_test_split
+from sklearn.ensemble import VotingClassifier
+from sklearn.linear_model import LogisticRegression
+from sklearn.ensemble import RandomForestClassifier
+from sklearn.svm import SVC
+from sklearn.metrics import accuracy_score
+iris = load_iris()
+X_train, X_test, y_train, y_test = train_test_split(iris['data'], iris['target'], test_size=0.3, random_state=42)
+
+log_clf = LogisticRegression()
+rnd_clf = RandomForestClassifier()
+svm_clf = SVC()
+
+voting_clf = VotingClassifier(estimators=[('lr', log_clf), ('rf', rnd_clf), ('svm', svm_clf)], voting='hard')
+voting_clf.fit(X_train, y_train)
+y_pred_voting = voting_clf.predict(X_test)
+print("Voting Classifier Accuracy:", accuracy_score(y_test, y_pred_voting))
+
+
+tree_clf = DecisionTreeClassifier()
+knn_clf = KNeighborsClassifier()
+svm_clf = SVC()
+'''
+        """)
+        
+    def bn():
+        """
+        A Bayesian network is a graphical model that represents the relationships between variables using nodes and arrows. 
+        Each node represents a variable, and the arrows show how the variables influence each other. 
+        It helps us understand how the variables are connected and allows us to make predictions or decisions by using probabilities and updating our beliefs based on new evidence. 
+        Overall, it's a way to visually represent and analyze complex systems using probabilities and logical connections.
+        
+        """
+        print(r"""
+import numpy as np
+import pandas as pd
+from pgmpy.models import BayesianModel
+from pgmpy.estimators import MaximumLikelihoodEstimator
+from pgmpy.inference import VariableElimination
+
+heart_disease = pd.read_csv('heart.csv')
+heart_disease = heart_disease.replace('?', np.nan)
+
+# Define the Bayesian network structure
+model = BayesianModel([
+    ('age', 'trestbps'), ('age', 'fbs'), ('sex', 'trestbps'), ('exang', 'trestbps'),
+    ('trestbps', 'heartdisease'), ('fbs', 'heartdisease'), ('heartdisease', 'restecg'),
+    ('heartdisease', 'thalach'), ('heartdisease', 'chol')
+]) 
+model.fit(heart_disease, estimator=MaximumLikelihoodEstimator)
+
+# Perform inference with Bayesian Network
+heart_disease_infer = VariableElimination(model)  
+
+# Calculate probability of Heart Disease given Age=63
+q = heart_disease_infer.query(variables=['heartdisease'], evidence={'age': 63})
+print(q)
+
+q = heart_disease_infer.query(variables=['heartdisease'], evidence={'chol': 233})  # cholesterol
+print(q)
+
+q = HeartDisease_infer.query(variables=['heartdisease'], evidence={'age': 63, 'sex' :1,'trestbps':130})
+print(q)
+        """)
 
 class mlfull():
     """
 pg1() : FIND-S : Finding a Maximally Specific (0) Hypothesis  
     Implement and demonstrate the FIND-S algorithm for finding the most specific hypothesis based on a given set of training data samples. 
     Read the training data from a .CSV file and show the output for test cases. 
     Develop an interactive program by Compareing the result by implementing LIST THEN ELIMINATE algorithm. 
@@ -1394,17 +1548,18 @@
 pg8() : Construct aBayesian network considering medical data. 
     Use this model to demonstrate the diagnosis of heart patients using standard Heart Disease Data Set.
     
 pg9() : Demonstrate the working of EM algorithm to cluster a set of data stored in a .CSV file.
 
 pg10() : Demonstrate the working of SVM classifier for a suitable data set
 
-knn() :  Write a program to implement k-Nearest Neighbour algorithm to classify the iris data set. 
+pg11() :  Write a program to implement k-Nearest Neighbour algorithm to classify the iris data set. 
     Print both correct and wrong predictions. Java/Python ML library classes can be used for this problem.
     
+pg12() : Write a program Ensembling of Classifiers for moon or iris dataset 
     """
     def pg1():
         """
     FIND-S: FINDING A MAXIMALLY SPECIFIC HYPOTHESIS
     1. Initialize h to the most specific hypothesis in H
     2. For each positive training instance x
             For each attribute constraint a, in h
@@ -1850,30 +2005,30 @@
 '''
 import pandas as pd
 import numpy as np
 # import bayespy as bp
 import warnings 
 warnings.filterwarnings('ignore')
 
-heart_disease=pd.read_csv("data7_heart.csv")
+heart_disease=pd.read_csv("heart.csv")
 # print(heart_disease)
 print('Columns in the dataset')
 for col in heart_disease.columns: 
     print(col) 
     
 from pgmpy.models import BayesianModel
 from pgmpy.estimators import MaximumLikelihoodEstimator
 model=BayesianModel([('age','trestbps'), ('age', 'fbs'), ('sex', 'trestbps'), ('exang',
 'trestbps'),('trestbps','heartdisease'),('fbs','heartdisease'),('heartdisease','restecg'),
 ('heartdisease','thalach'), ('heartdisease','chol')])
 model.fit(heart_disease, estimator=MaximumLikelihoodEstimator)
 
 from pgmpy.inference import VariableElimination
 HeartDisease_infer = VariableElimination(model)
-q = HeartDisease_infer.query(variables=['heartdisease'], evidence={'age': 1, 'sex' :0,'trestbps':150})
+q = HeartDisease_infer.query(variables=['heartdisease'], evidence={'age': 63, 'sex' :1,'trestbps':130})
 print(q)
         """)
         
     def pg9():
         """
         Demonstrate the working of EM algorithm to cluster a set of data stored in a .CSV file.
         """
@@ -1999,15 +2154,15 @@
 y_pred = clf.predict(X_test)
 
 # Calculate accuracy of the classifier
 accuracy = accuracy_score(y_test, y_pred)
 print("Accuracy:", accuracy)
         """)
         
-    def knn():
+    def pg11():
         print(r"""
 from sklearn.model_selection import train_test_split
 from sklearn.neighbors import KNeighborsClassifier
 from sklearn.metrics import classification_report,confusion_matrix
 from sklearn import datasets
 
 iris=datasets.load_iris()
@@ -2019,15 +2174,34 @@
 y_pred=classifier.predict(x_test)
 
 print('Confusion matrix is as follows')
 print(confusion_matrix(y_test,y_pred))
 print('Accuracy Matrics')
 print(classification_report(y_test,y_pred))
         """)
-        
+    
+    def pg12():
+        print(r"""
+from sklearn.datasets import make_moons
+from sklearn.model_selection import train_test_split
+from sklearn.ensemble import VotingClassifier
+from sklearn.linear_model import LogisticRegression
+from sklearn.ensemble import RandomForestClassifier
+from sklearn.svm import SVC
+from sklearn.metrics import accuracy_score
+X, y = make_moons(n_samples=100, noise=0.15)
+X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.3, random_state=42)
+log_clf = LogisticRegression()
+rnd_clf = RandomForestClassifier()
+svm_clf = SVC()
+voting_clf = VotingClassifier(estimators=[('lr', log_clf), ('rf', rnd_clf), ('svm', svm_clf)], voting='hard')
+voting_clf.fit(X_train, y_train)
+y_pred_voting = voting_clf.predict(X_test)
+print("Voting Classifier Accuracy:", accuracy_score(y_test, y_pred_voting))
+        """)
         
 class mad:
     """
 visitingcard() :
     Create an application to design aVisiting Card. The Visiting card should have a company logo at the top right corner. 
     The company name should be displayed in Capital letters, aligned to the center.
     Information like the name of the employee, job title, phone number, address, email, fax and the website address isto be displayed.
```

