# LLMs-predicting-corrosion-inhibitor-effectiveness-in-acid-solutions
leveraging large language models (llms) for predicting corrosion inhibitor effectiveness in acid solutions
Molecule Dataset Analysis and Prediction of Efficiency
This repository contains the analysis and prediction of molecular data with a focus on predicting efficiency using various machine learning models and exploring the application of large language models (LLMs) in this domain.

Project Overview
The project involves cleaning and normalizing a collection of molecular datasets, including:

Jaguar Data (jaguar_data_normalized.xlsx)
Pharmacological Data (pharmacological_data_normalized.xlsx)
Topological Data (topological_data_normalized.xlsx)
Physico-Chemical Data (physico_chemical_data_normalized.xlsx)
MOPAC Quantum Data (mopac_quantum_data_normalized.xlsx)
After cleaning the missing values, the data is analyzed to calculate the correlation between each dataset and molecular efficiency.

Machine Learning Models Used
XGBoost: After testing several models, XGBoost was found to perform the best on the jaguar data for predicting efficiency.
Gradient Boosting and RandomForest were also tested and compared with XGBoost.
Next Steps
I plan to explore the use of Large Language Models (LLMs) such as T5, GPT-2, and BART to predict efficiency on molecular data. The initial results using the GPT-2 model were less effective compared to XGBoost, but I plan to further test and compare more advanced LLMs for better performance.
