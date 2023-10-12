
<h1>Production Quality Control using Python program and Machine Learning Modelling </h1>

<h2>Description</h2>
This project is an excellent real-world problem, provided by Variass (An Electronics Manufacturing Service in the Netherlands), that involves first extracting required data from different datasets (sources) and then transform those as per requirement and finally loading those into a final destination (dataframe in this case). The interesting fact is this whole process is quite similar to the popular ETL pipeline process but has been done in Python. Variass  supplies  advanced electronics  parts  to  a wide  range of  industries.  An important part of their  manufacturing system  is  printed circuit board  assembly  (PCBA)  where  a very large variety  of  products  are  produced.  To  ensure  product  quality,  assembled  products  are inspected  via  an  automated  optical  inspection (AOI)  system.  The  inspection  system  can  identify different  types  of  defects,  and  raises  a  flag  once  a  product  is  marked  as  defective.  The products that are marked as defective are then inspected manually. The manual inspection is conclusive  and  may  validate  (true-positive)  or  invalidate  (false-positive)  the  defect.  The management believes that product characteristics have a strong influence on the defect rate and aims to better understand this impact in order to improve operational performance. In this project, firstly, we need to check the data that have been provided to us, clean the data where it is needed and make those data suitable to be used for further analysis.Then we need to determine the defect rates returned by the automated inspection (AOI) system on the overall and per defect type. We also need to find the true defect rates and false calls’ rate in this step. Finally, we need to develop a single prediction (machine-learning) model that predicts the defect rate per two specific defect types. We also need to split the data in two portions where 80% of the inspection data should be used for training and the rest 20% should be used for testing for validation. (The whole code file as a jupyter notebook file is available in the folder)
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

<p align="center">
Importing all necessary Libraries and ingesting the big dataset into Elasticsearch: <br/>
<img src="https://i.imgur.com/dUvnCpk.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
<br />
Importing data after aggreagtion via json and storing final transformed data into a final dataframe:  <br/>
<img src="https://i.imgur.com/7fFMmFA.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<img src="https://i.imgur.com/HobLI7u.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
<br />
Categorizing products based on profit margins and plotting histograms: <br/>
<img src="https://i.imgur.com/8D5gm2Q.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
<br />
Calculation of base-stock & number of boxes required and plotting correlation plot:  <br/>
<img src="https://i.imgur.com/QcJlumo.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
<br />
Identifying unique product couples based on correlation:  <br/>
<img src="https://i.imgur.com/CcmLu2v.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
<br />
Generating the final product list and allocating the products based on first method:  <br/>
<img src="https://i.imgur.com/bVXsmrF.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
<br />
Generating the final product list again and allocating the products based on second method:  <br/>
<img src="https://i.imgur.com/Kg73BUZ.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />
<br />
 Allocating the products based on third method (Optimization - Knapsack problem):  <br/>
<img src="https://i.imgur.com/27wYPJi.png" height="80%" width="80%" alt="Optimization using Elasticsearch and GurobiPy"/>
<br />

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
