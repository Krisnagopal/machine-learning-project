
<h1>Production Quality Control using Python program and Machine Learning Modelling </h1>

<h2>Description</h2>
This project is an excellent real-world problem, provided by Variass (An Electronics Manufacturing Service in the Netherlands), that involves first extracting required data from different datasets (sources) and then transform those as per requirement and finally loading those into a final destination (dataframe in this case). The interesting fact is this whole process is quite similar to the popular ETL pipeline process but has been done in Python. Variass  supplies  advanced electronics  parts  to  a wide  range of  industries.  An important part of their  manufacturing system  is  printed circuit board  assembly  (PCBA)  where  a very large variety  of  products  are  produced.  To  ensure  product  quality,  assembled  products  are inspected  via  an  automated  optical  inspection (AOI)  system.  The  inspection  system  can  identify different  types  of  defects,  and  raises  a  flag  once  a  product  is  marked  as  defective.  The products that are marked as defective are then inspected manually. The manual inspection is conclusive  and  may  validate  (true-positive)  or  invalidate  (false-positive)  the  defect.  The management believes that product characteristics have a strong influence on the defect rate and aims to better understand this impact in order to improve operational performance. In this project, firstly, we need to check the data that have been provided to us, clean the data where it is needed and make those data suitable to be used for further analysis.Then we need to determine the defect rates returned by the automated inspection (AOI) system on the overall and per defect type. We also need to find the true defect rates and false calls’ rate in this step. Finally, we need to develop a single prediction (machine-learning) model that predicts the defect rate per two specific defect types. We also need to split the data in two portions where 80% of the inspection data should be used for training and the rest 20% should be used for testing for validation. (The whole code file as a STORY in a jupyter notebook file is available in the folder)
<br />


<h2>Languages and Platform Used</h2>

- <b>Python 3 </b> 
- <b>Jupyter Notebook </b>

<h2>Tools and Libraries Used</h2>

- <b>Pandas for Dataframe operations and Numeric calculations </b>
- <b>NumPy for Numeric calculations </b>
- <b>Matplotlib & Seaborn for visualization (plotting charts) </b>
- <b>Scikit-learn for implementing machine learning and statistical modelling </b>

<h2>Program walk-through:</h2>

<h3>1. Data Cleaning and Preparation:</h3>
<p align="left">
Importing all necessary Libraries and all the datasets: <br/>
<img src="https://i.imgur.com/PVRnbLW.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />

We start with fisrt two datasets - order data and last year defect data. We clean and transform these data as required: <br/>
<img src="https://i.imgur.com/yhjKURV.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />

Then we work with other two datasets - VPL codes and alternatives data. We clean and transform (merging & grouping) these data as required: <br/>
<img src="https://i.imgur.com/2CRzgkq.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
Cleaning and transform is completed and we are ready for starting with the analysis.

<h3>2. Estimation of Defect Rates:</h3>
<p align="left">
In this section, we will estimate the defect rates per defect types and per VPL package code, true defect rates and also false call rates - all detected by the AOI: <br/>
<img src="https://i.imgur.com/UtUPYkB.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />

<h3>3. Prediction and Performance Reporting:</h3>
<p align="left">
In this part, we will first prepare our data for developing a model to determine if there is any relationship between the defect rates of two defect types - 'Shift' and 'Rotate' and the physical specifications: <br/>
<img src="https://i.imgur.com/fk0jdEG.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<img src="https://i.imgur.com/nd56chX.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
We are now ready with our conclusion! (check the jupyter notebook file) 
 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
