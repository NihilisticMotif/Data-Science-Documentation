# Purpose of this Documentation.

Nowaday, the world is full of data. Data is the evidence of almost any phenomena. However, in order to use data effectively, one must analyze the data. Data science is the field which aims to utilize data in order to create the most optimized decision. In addition, data science also has a almost every field.

In general, a data analysis project follows 4 steps.
1.	Defining the purpose of the project.
2.	Collecting, organizing, visualizing and splitting related data into training and evaluating data. Sometimes, data analysis projects finish in this step, if the data representation can reach the goal of the project.
3.	Implementing, training and evaluating the machine learning algorithm. Then select the most suitable machine learning algorithm for the project.
4.	Interpret and utilize the result of the algorithm in order to achieve the purpose of the project.

I have learned and written documentation about mathematics, statistics, machine learning algorithm and other people's data science project in order to practice how to utilize machine learning algorithm and how to interpret data. I also implement various types of algorithm e.g. ML algorithms, ML technique, linear algebra operation, statistical calculation etc and conpare my own implementation with Python libraries. This understanding can be apply in various ways e.g. analysing data from website, creating AI art with unique art style, financial decision making, physics simulation etc.

# The Folder Structure

1. DataSet
* This folder contains only data set.

2. Mathematics
* This folder contains mathematical notation, concept, theorem, example of the application of those concept and the Python implementation. This folder does not contains proof of the theorem because proof is rarely used practically in this field, except in some research fields.
* Mathematical fields in this folder includes Linear Algebra, Calculus, Precalculus and Statistics.

3. ML_Algorithm
* This folder contains the Python implementation (e.g. My own implementation, SKLearn implementation etc.), explaination and related mathematical expression of various type of ML algorithms (e.g. linear regression, logistic regression, gradient descent etc.)

4. ML_Technique
* This folder contains the explanation and implementation of various machine learning approach in order to solve common ML problem, such as how to deal with over/under fitting?, how to deal with missing value?, how to evaluate the accuracy of different type of ML algorithm? How to deal with sparse feature? etc.

5. Project
* This folder contains my own explanation and implementation of other people's project from Kaggle and Github.

# Learning Advice for reading this documentation.

To anyone who are new to data science and want to start a project in this field, I reccomment you to read my 5th folder (Project) because you will find various useful idea for defining your project's goal, understanding the practical application of this field and you won't need to spend your time on learning unnecessary thing. 

For anyone who want a deeper understanding of data science, reading 2nd (Mathematics), 3rd (ML_Algorithm) and 4th (ML_Technique) might be useful for you.

Some files inside this Repository are not finished and will be updated later. If there are something wrong and/or you have any recommended opinion about this lecture, you can contact me at my email (phuri.sott@gmail.com). For anyone who read my documentation, I hope that this documentation are beneficial for you.

Thank you for reading my lecture.

# How to connect Google Colab with Github?

I use Google Colab as an IDE for this documentation.

Note
* C = open Google Colab
* G = open Github
* Warning: Check if both files in C and G have the same path.

How to copy the Google Drive folder into Github?
1. Download the folder into the local computer
2. Upload it into Github.

How to update Github, when the file is edited?
1. C: Edit ‘A’ file
2. C: Copy filename ‘A’ in Google Drive
3. G: [T] 
4. G: Paste filename ‘A’
5. G: Copy path name of the file ‘A’ # the input have only one Data-Science-Documentation
6. G: Delete that file
7. C: [File] => [Save a copy in GitHub]
8. C: Repository: NihilisticMotif/Data-Science-Documentation
9. C: File path: str(paste path name of the file ‘A’)+‘/’+ ‘A’
10. C: [OK]

How to update Github, when the file is deleted?
1. C: Copy filename ‘A’ in Google Drive
2. G: [T] 
3. G: Paste filename ‘A’
4. G: Delete that file
5. C: Delete that file

How to update Github, when the file is created?
1. C: Create and edit file ‘A’
2. C: execute Python code

`

from google.colab import drive

drive.mount('/content/drive')

`

3. C: Click folder symbol on the left side. This symbol will indicate the folder structure of the project. 
4. C: Copy path name from the left side of the screen of the file ‘A’ 
5. C: [File] => [Save a copy in GitHub]
6. C: Repository: NihilisticMotif/Data-Science-Documentation
7. C: File path: str(paste path name of the file ‘A’)+‘/’+ ‘A’ # do not have something similar to '/content/drive/MyDrive/' as the input
8. C: [OK]
