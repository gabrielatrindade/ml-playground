# 🤖 Machine Learning playground 🤹🏼‍♀️

This repository contains my first projects and learnings in Machine Learning area. <br>
At the moment, most of my learnings are being on Surpevised Learning: Classification and Regression.

## Content

### 📚 Concepts
Concepts folder is to **learning theory or practice a specific method** through some data sample. It's *not* the goal make an end-to-end project, but just to learn a specific concept. <br>
Here you'll find some notes on regression and classification **metrics**, **cross-validation** in pratice, and handling **outliers**.

### 📊 Projects
As commented at the beginning, the projects here are from *Supervised Learning* problems, which means that the datasets is composed by features (X) and target (y). The algorithms will learn from the relationship between X and y.

My projects are classified in **Classification** or **Regression** problems. You can get a brief introduction or direct access to each project by expading the menu. <br>

Note: As a beginner, some of my projects were initially developed by following tutorials on the Internet, however, throughout the development of each project some 
learnings from *Concepts* were added to each one, when it was applicable.

#### Classification

<details>
<summary> Iris Species </summary>

<br>
💐 <a href="https://github.com/gabrielatrindade/ml-playground/tree/master/projects/iris_species">Iris Species project</a>
have the aim to <b>classify iris flowers among three species</b> (setosa, versicolor, or virginica) from the variables: sepal length, sepal width, peta length, petal width. Each class (species) has 50 observations, i.e. there are 50 records for setosa, 50 for versicolor and 50 for virginica. But, as some outliers were identified (4) in this project, they were removed, reducing the observations and turning the dataset into an imbalanced one. One important question to make is: Would it really be necessary to remove these outliers?

#### Dataset
- Independent variables: sepal length, sepal width, peta length, petal width.
- Dependent variable: target (iris species)

The dataset was provided by sklearn.datasets.
<hr>

</details>

<details>
<summary> Spam Email </summary>
test
</details>

<details>
<summary> Titanic </summary>
test
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
A basic empty template for a Supervised Learning project. It consists of sections of the most common steps (and some code) that need to be included in SL projects with little or no alteration.

## Stack
- Python
- Jupyter Notebook

## Future

- 📚 **Concepts**
- [ ] Learn how to define better hyperparameters
- [ ] Learn how to detect unnecessary features

- 📊 **Projects**
- [ ] Solve Unsurpevised Learning problems
- [ ] Work with tests
