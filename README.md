[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6574722&assignment_repo_type=AssignmentRepo)
# Applied Statistics Project

This repo contains information and data for your project. You need to work inside this GitHub repo.

For those who are not familar with this project and what it does let me explain it to you. Moreover I would like to explain what I thought and why I did some things the way I did :)

# What the project does
Basically this project tries to assist a insurance company and a a estate agents company. So the raw data for this project included several columns. The most important one is the **median_house_value**, based on that is the column **price_category** which indicates if the median_house_value is above or below 150,000$.

This project follows the Data Science Lifecylcle. 

1. Plan
2. Data
3. Model
4. Deployment (will not be covered in this project

To sum it up, the data for both models needs to be reviewed, cleaned, splitted and analyzed. Afterwards the modeling can start.

On the one hand there is the regression project which has the goal to predict the median_house_value based on the available variables. In the project several models are made and compared. Moreover they are analyzed with the training and the test data set. So that it can be performed that the model works on both dataset equally good and is not only fitted on the training dataset.

Note for the regression notebook
> To be honest, it took my quite a while to understand everything and in which order which steps need to be excecuted. My first attempts were made in the **regression** notebook, which got very big due to some iterations and problems I had. Thats is why I created two more notebooks with the aim to bring in the basics in the right order for the statsmodels and scikit learn analysis. The **regression** notebook covers the creation of several models, more detailed analysis, feature engineering, but also some steps in the wrong order and errors which I could not solve on my own. In the other two notebooks I have only created one model in each notebook.

Moreover the Lasso regression, Natural Spline as well as the Feature selection is made in this project.

On the other hand there is the classification project, this project has created several models to predict wheather the price_category if above or below. Also several models are created and compared here. Moreover they are analyzed with the training and the test data set. So that it can be performed that the model works on both dataset equally good and is not only fitted on the training dataset.

Note for the regression notebook
> To be honest, it took my quite a while to understand everything and in which order which steps need to be excecuted. My first attempts were made in the **classification** notebook, which got very big due to some iterations and problems I had. Thats is why I created one more notebooks with the aim to bring in the basics in the right order for the statsmodels and scikit learn analysis. The **classification** notebook covers the creation of several models, more detailed analysis, but also some steps in the wrong order and errors which I could not solve on my own. In the other notebook I have only created one model in each notebook.


# Why the project is useful

The model covers all the steps from the Data Science lifecylcle. Therefore this project helps beginners (like me :)) to get started with data analysis/applied statistics in python.

Moreover the models might assist the above mentioned companies on their decisions for their business model. Even thought I only achieved my self set goal on the classification. For the regression I could not achieve my own goal.


# How users can get started with the project

Feel free to have a look on my notebooks, maybe I can help you on some points. Feel free to ask my for support :)

Moreover if you find any problems/mistakes in the code, please contact me or create pull requests.

For example for my part with the Natural Splines I do not get why my natural spline is missing almost all of the data ... I tried it with a degree of 1 and 2 but in both cases I only receive errors. And for those errors I do not know hoe to solve/remove them. So if you have an idea, I would be very happy to hear from you :) 


# Who maintains and contributes to the project

The project is mainted so far by myself. Moreover I am (so far) the only one who made contributions to the project.
The project was created based on the documents and examples I got from my course Applied Statistics from my Master's degree in Data Science.




## Task description of the project

### Allgemeine Rahmenbedingungen für das Projekt

- Das Projekt soll mit Hilfe von mehreren **Jupyter Notebooks** (.ipynb-Datei) in Python umgesetzt werden. Die Markdown-Erklärungen können in deutscher oder englischer Sprache verfasst werden.
- Das gesamte Vorgehen soll sich weitgehend an der Logik des Data-Science-Lifecycle-Modells (siehe S. 5) orientieren. Deployment muss nicht behandelt werden.
- Das Projekt muss zwingend von Beginn an mit GitHub umgesetzt werden.
- Das Projekt soll in Form eines Jupyter Books in GitHub dargestellt werden.
- Auszüge des Notebooks werden am Prüfungstag vorgestellt und besprochen (weitere Hinweise folgen).

### Inhalte der Projektarbeit

Folgende Inhalte müssen zwingend behandelt werden (es ist jeweils wichtig, das Vorgehen, die Methode und die gewonnenen Erkenntnisse zu beschreiben):

### Datenaufbereitung

- Daten einlesen, bereinigen und transformieren (data splitting beachten). In Kombination mit EDA Durchführung von Feature Engineering.

### Deskriptive Statistik

- Nutzung geeigneter Lagemaße und Streuungsmaße für die Analyse von mindestens 2 numerischen und 1 kategorialen Variablen.

### Exploratory Data Analysis (EDA)

- Nutzung geeigneter Visualisierungen für die ausführliche Analyse von mindestens 4 Variablen.
- Beschreibung der Erkenntnisse
- Durchführung von Feature Engineering

### Korrelationsanalysen
- Untersuchung von Korrelationen

### Statistische Modelle

Alle Modelle sollen sowohl mit Statsmodels als auch mit scikit-learn umgesetzt werden. In scikit-learn muss die Preprocessing-pipeline verwendet werden.

- Es muss eine Regression mit mehreren Modellen (mit OLS Regression, Natural Spline und Lasso Regression) und eine Klassifikation (nur mit Logistischer Regression) umgesetzt werden (entsprechend der Vorgehensweise mit Trainings- und Testdaten).
- Durchführung von "Regression Diagnostics".
- Bei der Lasso Regression soll der optimale Hyperparameter Lambda mit k-fold-crossvalidation ermittelt werden.


