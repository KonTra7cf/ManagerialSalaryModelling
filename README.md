# Modeling and forecasting the volume of salaries for managerial positions in selected companies, listed on the Stock Exchange in Poland

---

## Short summary

This repo summarizes the contest work for the *2nd edition of the Business Intelligence Case Challenge (BICC)*, which aimed to forecast volume of salaries for managerial positions in selected companies, listed on the Stock Exchange in Poland. The work took joint **first place** in the contest. In order to achieve the most accurate forecasts, detailed data analyses were carried out and selection of appropriate regression model and optimal parameters was made.


The work was prepared in a team of three. **Visual Studio Code** environment was used to write the code.

---

## Agenda

* Installing & Importing libraries
* Data Preprocessing
  * Handling faulty data and name shortening
  * Creating a report (*ProfileReport*) and diving into alerts
  * Analysis of distribution of variables
  * Encoding qualitative variables
  * Imputing missing values
  * Outlier detection
* Modelling
  * Testing chosen models with hyperparameters (with *optuna* package)
  * Predicting values