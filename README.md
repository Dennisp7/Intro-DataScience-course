# finalProjectReport 
This read me is meant to serve as a mini code book of sorts to help guide the viewer in understanding and locating key information throughout the analysis. This project is an exploratory data analysis of the survey results from a current experiment being run. In the repository, the research proposal of the original experiment is named ‘Research Paper_1.pdf’ and can be found in the ‘docs’ folder. This paper is unfinished as the study is still on-going. 


The exploratory data analysis is conducted with two documents: the analysis report, which is a detailed description of the analysis, and the rmd file containing the actual R code for the analysis. The analysis report is named ‘Final_Project_Report.docx’ and can also be found in the ‘docs’ folder.

The original experiment's survey dataset being examined is named “dataset_212.csv”. This file can be found in the 'data' folder. In order to preserve the information from the original dataset, I created a copy called “CopyOfdataset_212.csv,” which can also be found in the 'data' folder of the repository. 

All changes made to the data were stored in variables so that neither the original nor copied data sets were altered. For example, ‘df_copy’ and its variations, are variables that were created to read in the copy of the dataset and make data alterations. The variable ‘df_copy_recode’ and its variations, are used to house the recoding of specific variables within the dataset. For an in-depth description of all variables, please see the main_program rmd file, which is in the main repository page. One can also refer to the Final_Project_Report.docx in the docs folder for further descriptions.

All data visualizations can be found in the data visualizations folder.


There is also a knitted HTML version of the main_program rmd file. It was created by using the knit function in R studio located just above the tabs that display files you are working on. To view the file I uploaded, download this repository and click on the 'Copied_program.html' file.
