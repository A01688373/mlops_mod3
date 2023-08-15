# Deliverable: Refactoring

Instructor: Carlos Mejia
Student: Gabriela Sánchez

This deliverable must comply with the following guidelines:

1. Documented code (docstrings)
2. Annotations on functions
3. Linting and formatting (this is done automatically with pre-commits)
4. Cookiecutter directory structure
    - Creation of at least 6 directories:
        > predictor or classifier: depending on your project, this folder will be used to predict or classify input data.
        > models: folder to save the trained models
        > preprocess: folder to house the modules to preprocess the data, commonly the Custom Transformers
        > load: folder for the module used to instantiate the download and load of data
        > train: folder for the module used to instantiate the training model
        > data: folder to store data sets temporarily
        > main.py file (or whatever you like to call it), which allows you to test all your code from one place. Take this file as a reference.
5. Use of Object Oriented Programming
    - Modularization of code to be able to be instantiated from other scripts using classes.
    - Use of Custom Transformers
    - Data pipeline that uses Custom Transformers