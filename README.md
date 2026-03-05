# health-insurance-prediction

This project was part of the Introduction to Data Science Class at the FCUP in Porto.

# Health Insurance Classification — Customer Targeting Model

Predicting whether customers of a US insurance company currently hold 
health insurance, based on demographic and financial attributes. The 
goal is to enable targeted outreach to uninsured individuals as 
potential health insurance customers.

## Business context

In the US, health insurance status is closely tied to financial 
security and access to healthcare. This project was developed for a 
broad insurance company seeking to identify uninsured customers within 
their existing client base, enabling data-driven outreach campaigns.

Model performance is ultimately measured not only by classification 
metrics but by whether the insights are actionable — i.e., whether 
targeted campaigns based on model outputs generate profit that offsets 
the cost of the intervention.

## Dataset

The dataset was provided by the company and contains the following 
customer attributes:

| Feature | Description |
|---------|-------------|
| Sex | Customer gender |
| Employment Status | Current employment situation |
| Income | Annual income |
| Marital Status | Marital situation |
| Housing Type | Type of housing (e.g. owned, rented) |
| Number of Vehicles | Vehicles owned |
| Age | Customer age |
| State of Residence | US state |
| Gas Usage | Household gas consumption |
| Number of Rooms | Rooms in household |
| Recent Move | Whether the customer recently moved |

## Project pipeline

1. **Data understanding** — exploration of distributions, feature 
   types, and initial quality assessment
2. **Data cleaning** — handling missing values, erroneous entries, and 
   inconsistencies
3. **Exploratory data analysis** — relationships between features and 
   insurance status
4. **Class imbalance handling** — evaluation of oversampling, 
   undersampling, and class-weighted approaches
5. **Modelling** — training and comparison of classification models
6. **Evaluation** — assessment using F1 score (primary), precision, 
   recall, and performance on unseen data

## Key considerations

- The dataset reflects the customer base of one specific company and 
  may not generalise to the broader US population
- Class imbalance in insurance coverage rates is explicitly addressed 
  in the modelling pipeline
- Demographic limitations in the data may introduce bias; results 
  should be interpreted with this in mind

## Repository structure

| File | Contents |
|---------------|----------|
| `notebook.ipynb` | Analysis and modelling notebook (ipynb) |
| `notebook.html` | Analysis and modelling notebook (html) |
| `customer.csv` | Data of the analysis |
| `README.md` | This file |
