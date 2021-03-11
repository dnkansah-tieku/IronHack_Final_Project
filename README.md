<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# IronHack_Final_Project



# Tree Volume Prediction


*[Dennis Nkasnah-Tieku]*

*[Data Analytics, Berlin, 11.03.2021]*


## Project Description
The project aims to predict the volume of forest tree species from a set of features. 

Dataset
The data was used during a module course work at the SGGW Poland. The data is coming from a few thousand stands located in some forest districts in the country. 

Data Cleaning
- Series of data processes were undertaken in the various columns to standardized the format
- The adress_forest was dropped because this will not play an important role in the prediction
- The species_rank_order was also dropped since this contains only one unique value
- Species_storey was also droppped since the information was almost the same as given by stand_structure 

**Analysis** 

- Plotted a correlation matrix
- Plotted  correlation graph of independent variables against the dependent variable 
- Visualizing with histograms to check distribution
- Spliting numerical and categorical data
- using only the numerical variables to determine how the prediction strength of the model
- Applied feature selection techniques
- Model application
- Model adjustment for best fit
- Model validation

Conclusion
- Height and basal area are the best predictions.
- It was an interesting observation that species age did not have much influence on the volume of wood product of the tree species. 
