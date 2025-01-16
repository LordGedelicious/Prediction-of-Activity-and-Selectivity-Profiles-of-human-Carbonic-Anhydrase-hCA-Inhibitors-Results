
# Prediction of Activity and Selectivity Profiles of human Carbonic Anhydrase (hCA) Inhibitors Results

This repository contains Gede Prasidha Bhawarnawa's thesis titled 'Prediction of Activity and Selectivity Profiles of human Carbonic Anhydrase (hCA) Inhibitors using Tree-Based and Neural Network Based Models'. The thesis presents the results of predictive modeling for hCA inhibitors. It was completed as a requirement for the Computer Science/Informatics Undergraduate Program at Bandung Institute of Technology.

## Repository Structure

    .
    ├── docs                        # Thesis file
    │   ├── thesis.pdf   
    ├── src                         # Source code for all experimentations                  
    │   ├── Isoform II
    │   |   ├── ExtraTrees Experimentation.ipynb
    │   |   ├── XGBoost Experimentation.ipynb
    │   |   ├── ...
    │   ├── Isoform IX
    │   |   ├── ExtraTrees Experimentation.ipynb
    │   |   ├── XGBoost Experimentation.ipynb
    │   |   ├── ...
    │   ├── Isoform XII
    │   |   ├── ExtraTrees Experimentation.ipynb
    │   |   ├── XGBoost Experimentation.ipynb
    │   |   ├── ...
    │   ├── Interpretation Experiment
    │   |   ├── NCART Interpretation Experimentation Isoform II.ipynb
    │   |   ├── ...
    │   |   ├── XGBoost Interpretation Experimentation Isoform II.ipynb
    │   |   ├── ...
    │   ├── Selectivity Profile Experiment
    │   |   ├── Selectivity Profile Experimentation Isoform II vs IX.ipynb
    │   |   ├── Selectivity Profile Experimentation Isoform II vs XII.ipynb
    ├── performance-results         # Performance metrics of base and tuned models                   
    │   ├── ExtraTrees.xlsx        
    │   ├── XGBoost.xlsx           
    │   ├── ...           
    ├── best-hyperparameter-set     # Best hyperparameter set for each model from HPO results                   
    │   ├── ExtraTrees.xlsx        
    │   ├── XGBoost.xlsx            
    │   ├── ...          
    ├── hypothesis-testing          # Hypothesis testing results between tuned and base model for each model                   
    │   ├── ExtraTrees.xlsx        
    │   ├── XGBoost.xlsx            
    │   ├── ...
    ├── hypothesis-testing          # Hypothesis testing results between tuned and base model for each model                   
    │   ├── ExtraTrees.xlsx        
    │   ├── XGBoost.xlsx            
    │   ├── ...   
    ├── selectivity-profile         # Selectivity profile testing results
    │   ├── II and IX.xlsx        
    │   ├── II and XII.xlsx 
    ├── feature-importance          # Feature importance results for XGBoost and NCART
    │   ├── II.xlsx        
    │   ├── IX.xlsx
    │   ├── XII.xlsx                 
    └── misc                        # Other files
    │   ├── Best Models per Dataset Variation.xlsx        


## Authors

- [Gede Prasidha Bhawarnawa](https://www.github.com/lordgedelicious) Email: gede.prasidha@gmail.com




