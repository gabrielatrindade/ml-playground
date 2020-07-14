# 🤖 Machine Learning playground 🤹🏼‍♀️

This repository has my first projects and learnings in Machine Learning area. <br>
At the moment, most of my learnings are being on Surpevised Learning: Classification and Regression.

## Content

### 📚 Concepts
Concepts folder is to **learn theory or practice a specific method** through some data sample. It's *not* the goal make an end-to-end project, but just to learn a specific concept. <br>
Here you'll find some notes on regression and classification **metrics**, **cross-validation** in pratice, and handling **outliers**.

### 📊 Projects
As mensioned in the beginning, the projects here are from *Supervised Learning* problems, which means that the datasets is composed by features (X) and target (y). The algorithms will learn from the relationship between X and y.

My projects are classified in **Classification** or **Regression** problems. You can get a brief introduction or direct access to each project by expading the menu. <br>

Note: As a beginner, some of my projects were initially developed by following tutorials on the Internet, however, throughout the development of each project some 
learnings from *Concepts* were added to each one, when it was applicable.

#### Classification

<details>
  
  <summary> Iris Species </summary>

  <br>
  💐 <a href="https://github.com/gabrielatrindade/ml-playground/tree/master/projects/iris_species">Iris Species project</a> has the aim to <b>classify iris flowers among three species</b> (setosa, versicolor, or virginica) from the variables: sepal length, sepal width, petal length, petal width. Each class (species) has 50 observations, which means there are 50 records for setosa, 50 for versicolor and 50 for virginica. But, as some outliers were identified (4) in this project, they were removed, reducing the observations and turning the dataset into an imbalanced one. One important question to ask is: Would it really be necessary to remove these outliers?

  #### Dataset
  - Independent variables: sepal length, sepal width, peta length, petal width.
  - Dependent variable: target (iris species)

  The dataset was provided by sklearn.datasets.
  <hr>

</details>


<details>
  <summary> Spam Email </summary>
  
  <br>
  📧 <a href="https://github.com/gabrielatrindade/ml-playground/tree/master/projects/spam_email">Spam Email project</a> <b>classifies an email as spam (junk email) or ham (good email)</b> through email messages. The dataset contains 5572 observations, they are composed of Label (target) and EmailText (feature) variables. In this case, the EmailText will be converted into features that consist of the relative frequencies of occurring words. The model will then learn from the frequencies of each word in a spam or ham message.
    
  #### Dataset
  - Independent variable: EmailText
  - Dependent variable: Label
  
  Future work: before counting the occurrence of each word, clean the messages: remove punctuation and abbreviation.
  <hr>

</details>


<details>
  
  <summary> Titanic </summary>
  
  <br>
  🚢 <a href="https://github.com/gabrielatrindade/ml-playground/tree/master/projects/titanic">Titanic project</a> is one of the most common classification problems for beginners. In this project, we need to build a predictive model that <b>classifies whether a passenger will survive or not</b> based on their information (i.e. name, age, gender, socioeconomic class, etc.). In this project, I dealt with data cleaning, visualization, and feature engineering, as well as machine learning. The dataset is composed of 11 features that they are not prepared to immediately apply a machine learning model. Going through these features, plotting some graphs, understanding and making decisions about how to clean and fill them, categorizing and encoding them, is part of the process. In addition, I applied and plotted some metrics I learned to evaluate the algorithms, such as ROC, AUC, and accuracy.
  
  #### Dataset
  - Independent variables: PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fire, Cabin, Embarked
  - Dependent variable: Survived

  <hr>

</details>


#### Regression

<details>
<summary> Boston House Price </summary>
Boston House Price
</details>

<details>
<summary> Netflix Stock Prices </summary>
test
</details>

<details>
<summary> Pi </summary>
test
</details>

<details>
<summary> Wine Quality </summary>
test
</details>

### 📝 boilerplate.ipynb
A basic empty template for a Supervised Learning project. It consists of sections of the most common steps (and some code) that needs to be included in SL projects with little or no alteration.

## Stack
- Python: Sklearn, Pandas, Numpy, Scipy, Matplotlib, Seaborn
- Jupyter Notebook

## Future

- 📚 **Concepts**
- [ ] Learn how to define better hyperparameters
- [ ] Learn how to detect unnecessary features

- 📊 **Projects**
- [ ] Solve Unsurpevised Learning problems
- [ ] Work with tests
