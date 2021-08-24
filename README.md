# Cryptocurrencies  
  
### Summary:  

The goal of the project is to identify potential cryptocurrency investment opportunities for the Accountability Accounting investment bank.  Accountability Accounting want to know what cryptcurrencies are available for investment and wants to know how best to group them to create classifications for the potential investments.  
  
The data were loaded onto a Pandas dataframe and processed to prepare the data for principal component analysis and K means clustering.  
PCA analysis reduced the data to 3 features.  
A plot of number of clusters against the inertia for the model run for each cluster number (elbow plot) indicated that either 4 or 5 clusters were appropriate.  4 clusters was used for K means clustering.  

The results of the clustering were used to plot the total coins mined (scaled) and total available coins (scaled) to illustrate the opportunity set.    
  
### Data:  

THe data for the analysis is a .csv file containing 1,252 cryptocurrencies- both active and inactive.  

