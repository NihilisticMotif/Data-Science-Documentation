# Purpose of this Documentation.

Nowaday, the world is full of data. Data is the evidence of almost any phenomena. However, in order to use data effectively, one must analyze the data. Data science is the field which aims to utilize data in order to create the most optimized decision. In addition, data science also has a almost every field.

In general, a data analysis project follows 4 steps.
1.	Defining the purpose of the project.
2.	Collecting, organizing, visualizing and splitting related data into training and evaluating data. Sometimes, data analysis projects finish in this step, if the data representation can reach the goal of the project.
3.	Implementing, training and evaluating the machine learning algorithm. Then select the most suitable machine learning algorithm for the project.
4.	Interpret and utilize the result of the algorithm in order to achieve the purpose of the project.

I have learned and written documentation about mathematics, statistics, machine learning algorithm and other people's data science project in order to learn how to think in a rigorous way, how to utilize machine learning algorithm and how to interpret data. This understanding can be apply in various ways e.g. analysing data from website, creating AI art with unique art style, financial decision making etc.

# The Folder Structure

1. DataSet

2. Mathematics

3. MachineLearning_Algorithm

4. Project

4.1 ReverseEngineer_DataScience_Project

4.2 ReverseEngineer_Alternative_to_ML_Project

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
2. C: execute 

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


# Learning Advice for reading this documentation.

The 1st folder (DataSet) contains data set.

To anyone who are new to data science and want to start a project in this field, I reccomment you to read my 4th folder (Project) because you will find various useful idea for defining your project's goal, understanding the practical application of this field and you won't need to spend your time on learning unnecessary thing. 
* The 4.1th sub folder (ReverseEngineer_DataScience_Project) is about learning and implementing (reverse engineering) other people's data science project from Kaggle and Github with basic Python library such as Numpy, Pandas, Matplotlib and Math in order to understand how to do data science project. The 
* 4.2th sub folder (ReverseEngineer_Alternative_to_ML_Project) is about learning and implementing (reverse engineering) other people's non-machine learning based project.

For anyone who want to learn mathematics as a hobby and/or want a deeper understanding of data science, reading 2nd (Mathematics) and 3rd (MachineLearning_Algorithm) might be useful for you.

Some files inside this Repository are not finished and will be updated later. If there are something wrong and/or you have any recommended opinion about this lecture, you can contact me at my email (phuri.sott@gmail.com). For anyone who read my documentation, I hope that this documentation are beneficial for you.

Thank you for reading my lecture.
