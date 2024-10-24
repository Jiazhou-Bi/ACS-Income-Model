# ACS-Income-Model

## Overview
This project aims to build a predictive model for personal total income using various demographic attributes, such as marital status, occupation, and residing state. We explored three popular machine learning algorithms: Random Forest, Linear Regression, and Extreme Gradient Boosting. Ultimately, Extreme Gradient Boosting was selected due to its superior predictive performance. While the model achieved a high R-squared value, it also exhibited a high Mean Squared Error, indicating challenges in accurately predicting all data points. For more details, please read the [paper.pdf](paper/paper.pdf).

## Prerequisites
**IMPORTANT** The scripts **DOES NOT** support Python 3.13 at the moment due to incompatible packages.

You will need to have a IPUMS API KEY to initiate an extraction request for the raw data. You can get your key at [IPUMS_API_KEY](https://account.ipums.org/api_keys). You will also need to install the ipumspy package for your python in order to run the data extraction script. You can run the following command in your terminal:

    pip install ipumspy

Alternatively, you can go to [IPUMS_OFFICIAL_WEBSITE](https://usa.ipums.org/usa/index.shtml) and manually extract your data.

## File Structure
The repo is structured as:

-   `data/raw_data` contains the raw data as obtained from ipums through IPUMS API.
-   `data/analysis_data` contains the cleaned dataset that was constructed.
-   `model` contains fitted models. 
-   `other` contains relevant literature, details about LLM chat interactions, and sketches.
-   `paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper. 
-   `scripts` contains the Python scripts used to simulate, download and clean data.

## Contact The Authors
If you have any questions, comments, suggestions, or concerns regarding this project, please feel free to contact Justin (Jiazhou Bi) at [justin.bi@mail.utoronto.ca](mailto:justin.bi@mail.utoronto.ca) or Weiyang Li at [weiyang.li@mail.utoronto.ca](mailto:weiyang.li@mail.utoronto.ca).