# Prediction of Water Phases
This mini project was done during the *Machine Learning in Condensed and Soft Matter* course held at the Automn Semester 2022 at the University of Fribourg. The goal of this project is to build and compare different classifiers performance whose task is to predict the phase of the water given its temperature and pressure. Three classifiers will be compared:
1. Support Vector Machine
2. $k$-Nearest Neighbors
3. Multilayer Perceptron

---
To run the code in the Notebook, a *pipenv* virtual environment should be installed using `pipenv sync` or `pipenv install` after cloning the repository. The Notebook can then be run on a Jupyter Server with `pipenv run jupyter notebook`.
**Note** that the training of the last classifier, i.e. the multilayer perceptron, could be slower if no GPU are available.
