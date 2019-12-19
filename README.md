# Human Resources Analytics

Data analysis project of the Data Mining course held at University of Pisa (Master's degree in Computer Science, fall/winter 2017). Equally relevant contributions to this project were made by [noobcode](https://github.com/noobcode) and [anferico](https://github.com/anferico).

The projects consists in the application of Data Mining techniques to an HR dataset about people working in a certain company. The goal of this project is to identify those employees that left their job and define their typical profile (based on parameters like level of satisfaction, promotions obtained, number of projects and so on). 

## Main modules of the project

This work includes four main parts:

1. **Data understanding**: data visualization, statistics and cleaning. Relative Jupyter notebooks can be found under the folders `data_understanding` and `More on data understanding`.

2. **Clustering**: application of the K-Means, DBSCAN and Hierarchical clustering algorithms to identify patterns among employees. The Jupyter notebooks for this task are all stored inside the `clustering` folder.

3. **Pattern mining and association rules**: frequent patterns and association rules extraction through the [Apriori](https://en.wikipedia.org/wiki/Apriori_algorithm) algorithm. Some of the rules are also used in the definition of a rule-based classifier. Source code can be found under the two folders `more_on_association_rules` and `association-rules-and-pattern-mining`.

4. **Binary classification**: definition and evaluation of different decision-tree models for the binary classification of employees (whether or not they left their job at the company). Implementations can be inspected by reading the Jupyter notebooks inside the `HR_classification` folder.

## Written report

A written report of the project is available in Italian ([report/Relazione_Unita.pdf](report/Relazione_Unita.pdf)).
