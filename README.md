# Writing Profiency Classification Project

## Analysis-Notebooks 
  - The Analysis-Notebooks folder contains various Jupyter notebooks used for analyzing, comparing, and explaining the performance of our text classification models. These notebooks encompass different stages of our project, from   initial exploratory data analysis to model explainability techniques.
  - Contents of the Notebooks:
    * Exploratory Data Analysis (EDA): This notebook includes initial data exploration and visualization to understand the dataset's characteristics, distributions, and potential preprocessing needs.
    * Model Comparison: Detailed comparative analysis of between BERT and RoBERTa models, evaluating the performance as well as strengths and weaknesses of each model.
    * LIME Explainability: Utilizes LIME (Local Interpretable Model-agnostic Explanations) to interpret the predictions of our models. This notebook demonstrates how LIME can be used to highlight the most influential words or features providing insights into the model's decision-making process.
    * LLM Explainability: Uses a large language model (LLM) to justify the classifications of our text samples. The notebook feeds a sample text and its classification into the LLM, which then generates reasons for why the text was classified at that level. This lets us offer deeper and more contextually aware explanations compared to traditional methods.

## Data-Notebooks
  - The Data-Notebooks folder contains Jupyter notebooks focused on data preprocessing and extraction. These notebooks convert our raw data into formats suitable for analysis and model training.
  - Contents of the Notebooks:
      * Extract-OneStopEnglish: This notebook converts the raw data from the OneStopEnglish Corpus into a structured format.  
      * Extract_EFCAMDAT_XML_to_CSV: This notebook extracties data from the EFCAMDAT dataset, originally in XML format into CSV format followed by some feature engineering and brief EDA.
   
## Model-Notebooks
  - The Model-Notebooks folder contains Jupyter notebooks dedicated to building, training, and evaluating various transformer models on the OneStopEnglish and EFCAMDAT data. 
  - Contents of Notebooks:
    * EFCAMDAT-5Class-roBERTa-2step-3step.ipynb: Implements RoBERTa models with two-step and three-step training for classifying EFCAMDAT data into five classes.
    * EFCAMDAT-6Class-roBERTa-2step-3step.ipynb: Same as the 5-class version but focuses on classifying EFCAMDAT data into six classes.
    * EFCAMDAT-Clip-5Class-Augment-Models.ipynb: Uses clipping and data augmentation techniques to improve the performance of models classifying EFCAMDAT data into five classes.
    * EFCAMDAT-Clip-6Class-Augment-Models.ipynb: Same as the 5-class version but focuses on six-class classification with clipping and augmentation.
    * onestopenglish-Models.ipynb: Develops and evaluates models for classifying the OneStopEnglish dataset.

## Misc
  - The Misc folder contains various Jupyter notebooks used as a sandbox for testing and refining our feature extraction and modeling processes. Feel free to disregard these files.





