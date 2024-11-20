**This folder contains all the source code files**

**File list:**
   - 01_Credit_Card_Fraud_Detection_EDA.ipynb  -> Mounting the Google Drive and Exploratory Data Analysis
     - **Note: All the graphs generated in the section "EDA using dataprep" is not visible in the Github. But they are verywell visible in the Google Colab.**
   - 02_Credit_Card_Fraud_Detection_PreProcessing+Models+Output.ipynb -> After understanding of the data, the pre-processing of the data, different models devloped and the output comparison.

As the project requires more RAM, it is advisible to use **Google Colab for it with TPU v2-8** as Runtime Type.
Please refer to Dataset/Readme.md for the dataset downloading and storing in Google Drive.

**Note:** The pre-processing and model development file is combined becuase we had imbalanced classes in the dataset. To make that balanced, we used SMOTE during preprocessing and as a result, the dataset size grew from 337 MB to 5.8 GB. So, it is not good to store and load the 5.8 GB pre-processed dataset file considering the storage constraints.
