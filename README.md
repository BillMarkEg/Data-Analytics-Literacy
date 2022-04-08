# Data-Analytics-Literacy
## Understanding Data Cleaning and Preparation Techniques
<br> clean -> process -> extract insights -> visualize ur insights
#### genuine outliers 
<br> very high/low 
#### stats 
<br> describtive -> find dots eg. find more imp columns so it works to get specific columns 
<br> infer -> connect dots together (eg. getting correlation betweeb columns and so on so it works on many columns together and find relationships.)
#### notes 
<br> imputation -> repacement
<br> hot-deck technique -> leads to bias in data so not recommended 
<br> hot-deck to get lead/lag in null values. --> forwardfill / backwardfill
<br> imputation based on regression -> increase correlation  
<br> imputation based on average -> decrease correlation 
<br> univariable -> means one column 
<br> bivariable -> means two columns 
## Preparing Data for Analysis Using Spreadsheets and Python
#### dealing with outliers
<br> drop it -> if wrong values
<br> replace with min/max value -> if wrong values and its suitable to do here 
#### how to find outliers
<br> compare to avg | range | variance | std-dev - recommended --> if more/less than 3/-3   
#### check if there is outliers/not in Excel
<br> in Excel --> **BOX plot** diagrame that is based on inter quartile range to check if there outliers on collumn or not 
#### impute outliers with nulls then drop them
<br> so we standerdize data (scaling) -> make all points between -3 and 3 based on std-dev and mean (z-score) so in EXCEL -> standerdize (col,$mean,$std)
<br> then in another column if z-score (OR(col>3,col<-3 ),"" ,z ) or use if condition instead if OR (both work.)
<br> then check box plot after dropping outliers it will be good.
<br> after doing **standerzation scaling ** note that -> mean is close to 0 and std is close to 1.  
<br> getting **z-score** and making **box plot on** its values make it easier for us to see **outliers clearly** .
<br> to **remove outlers** we can drop them based on **z-score** | drop them by** IQR ** that is based on box plot method
#### concat dfs
<br> concat just put dfs side by side (axis = 1) or above each others (axis = 0)
<br> reset index to ensure both dfs has same order before concating them.
#### imputate using ML
<br> using logstic regression to predict missing values data
## Collecting Data to Extract Insights
<br> scaling  
<br> normalization 
<br> normalization makes calculating correlation straightforward.
#### binning data - > convert numerical data to categorical form
<br> can be binarization (result in 0 or 1) or discretization (multi var result (1,2,3) )
<br> Standardization and Normalization are important to put all of the features in the same scale.
<br> normalization ex min/max make all data between 0 and 1 
<br> Standardization make it between 3 and -3 foreg.
#### Big data
<br> **no random acess** means we just don't acess low scan we wanna acess many batches for processing 
<br> eventually consistent as there is delay till master node update data in replicas <horizental scaling eg. hdfs>
<br> but its instant update in vertical sys as just one machine get updated. <vertical scaling eg.dwh > 
 #### loading and processing data using relational-DB 
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
