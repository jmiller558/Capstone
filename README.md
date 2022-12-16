# Capstone

### Project Name: 
* #### SuperPlan: Forecasting and Demand Planning 

### Team Name: 
* #### Estrella Ndrianasy, Jesse Miller, Jyoti Kumari, Kanika Mahajan, Kevin Lu

## Project Overview: 

* #### Demand planning is the process of planning demand for a product or service in order to facilitate decisions about inventory levels, production capacities, staffing, and more. Demand planning is considered an essential step in supply chain planning.

## Project Objectives

* #### Our project leverages the M5 Competition’s Walmart sales dataset, which covers several stores in multiple states in the US. The M5 is one of the most well-known forecasting competitions in the field of demand planning.We explore top performing models from the M5, particularly LightGBM, and state-of-the-art deep learning models like Temporal Fusion Transformer against industry standards such as Triple Exponential Smoothing, in order to provide key insights to business users including: 
    * Which aggregation levels do the models forecast best?
    * Are the models effective at capturing price/promo changes?
    * And do the model perform well in common business scenarios not covered by the M5?
    
 
## Implementation

### EDA:
  - [Exploratory Data Analysis](https://github.com/jmiller558/Capstone/blob/main/Inventory-Planner-EDA.ipynb)

### Models:

 1) Baseline Models
    - [Exponential Smoothing](https://github.com/jmiller558/Capstone/blob/main/Exponential_Smoothing_Final.ipynb)
    - [Weekly forecast - Exponential Smoothing](https://github.com/jmiller558/Capstone/blob/main/Weekly_Exponential_Smoothing_Final.ipynb)

2) LightGBM
    - [LightGBM](https://github.com/jmiller558/Capstone/blob/4c1cd356471c6aee73814b5c189fae4eb68694a8/LightGBM_Final.ipynb)
    - [LightGBM - Weekly](https://github.com/jmiller558/Capstone/blob/62a8b1ae91561209b3ad08018608fcb66d147856/Weekly_LightGBM_Final.ipynb)
   
3) TFT
   - [TFT](https://github.com/jmiller558/Capstone/blob/62a8b1ae91561209b3ad08018608fcb66d147856/TFT_Final.ipynb)
   - [TFT - Weekly](https://github.com/jmiller558/Capstone/blob/main/Weekly_TFT_Final.ipynb)
   
### Evaluation Script:
   - [Evaluation Script](https://github.com/jmiller558/Capstone/blob/main/Evaluation.ipynb)

### Website link:
   - [Berkeley Intranet project link](https://www.ischool.berkeley.edu/projects/2022/superplan-forecasting-and-demand-planning)

### References:
   - the following repository was leveraged heavily in the development of our LightGBM model: https://github.com/monsaraida/kaggle-m5-forecasting-accuracy-4th-place
