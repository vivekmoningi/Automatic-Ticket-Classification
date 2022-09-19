# Automatic-Ticket-Classification

Building a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue by doing topic modelling on the .json data provided by the company. Since this data is not labelled, need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

* Credit card / Prepaid card

* Bank account services

* Theft/Dispute reporting

* Mortgages/loans

* Others

#### Model Building

Using 4 Models to test accuracy and using best model to define the model.

1. Logistic Regression

2. Decision Trees

3. Random Forest

4. Naive Bayes

Logistic Regression did best with 93% accuracy.

