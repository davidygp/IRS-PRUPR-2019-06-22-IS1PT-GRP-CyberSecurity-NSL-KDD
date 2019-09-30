# SECTION 1 : PROJECT TITLE
CyberSecurity NSL-KDD

<img width="812" alt="welcome" src="https://user-images.githubusercontent.com/31118924/65891611-66949c80-e3d7-11e9-86b5-91252ed57ed8.PNG">

# SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
For this assignment, the team decided to work on the NSL-KDD dataset (network security related) as it is widely documented with a large amount of samples that mimic real scenarios. With the sizable dataset, the team was able to apply different algorithms to analyse their effectiveness in classifying the data. We utilised techniques for feature selection such as Principal Component Analysis to prepare the data, and then applied classification algorithms such as Decision Tree, Random Forest, K-Nearest Neighbours, Isolation Forest. Through this project, the team learned how to practically prepare and partition data, and also on how to build ensemble/hybrid models.

# SECTION 3 : CREDITS / PROJECT CONTRIBUTION
| Official Full Name | Student ID (MTech Applicable)| Work Items (Who Did What) | Email (Optional) |
| :---: | :---: | :---: | :---: |
| DAI YIRUI | A0195167U | Business idea generation, PCA, Clustering | e0384798@u.nus.edu |
| DONG MEIRONG | A0195346W | Business idea generation, Grid search, Project report | e0384977@u.nus.edu |
| LIM CHONG SENG HERMANN | A0195392U	| Business idea generation, Isolation forest	| e0385023@u.nus.edu |
| YAM GUI PENG DAVID | A0195315A	| Business idea generation, Ensemble methods, Metrics, Project report | e0384946@u.nus.edu |


# SECTION 4 : USER GUIDE
[ 1 ] To run Jupyter Notebook 

$ git clone https://github.com/davidygp/IRS-PRUPR-2019-06-22-IS1PT-GRP-CyberSecurity-NSL-KDD

  (Ensure Anaconda is installed)
  
$ pip install imbalanced-learn numpy pandas sklearn pickle joblib tensorflow

$ cd ./IRS-PRUPR-2019-06-22-IS1PT-GRP-CyberSecurity-NSL-KDD/

$ jupyter notebook

  (open up NSL-KDD-Multiclass_Classification.ipynb)
  
  (open up NSL-KDD-Multiple_Binaryclass_Classification.ipynb)

# SECTION 5 : PROJECT REPORT / PAPER
https://github.com/davidygp/IRS-PRUPR-2019-06-22-IS1PT-GRP-CyberSecurity-NSL-KDD/blob/master/ProjectReport/Report.pdf

Recommended Sections for Project Report / Paper:
- Executive Summary
- Introduction into Dataset
- Description of Dataset
- Data Processing
- Results
- Limitations of datasets 
- Conclusion
- Appendix

# SECTION 6 : MISCELLANEOUS
Attack Types.csv
- The Attack Types and the corresponding Attack Category

Field Names.csv
- The Field Names and the corresponding Data Type (continuous/ symbolic)

KDDTrain+.txt
- The NSL-KDD Train Dataset

KDDTest+.txt
- The NSL-KDD Test Dataset

NSL-KDD-Multiclass_Classification.html/NSL-KDD-Multiple_Binaryclass_Classification.html
- HTML saved files of the jupyter notebook outputs

Cyber Dataset.csv/Cyber Dataset.hdf5
- Artifacts of the NN Training Model
