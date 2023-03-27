# Module-5-Challenge
-----------------------------------------------
# Background
In this project, I was given access to the results of an animal study of 249 mice who were identified to have squamous cell carcinoma (SCC). The pharmaceutical company, Pymaceuticals, Inc., has tasked me with using the data to compare their new cancer treatment, Capomulin, against the other treatment regimens.

# Instructions
This assignment is broken down into the following tasks:

  *Prepare the data.

  *Generate summary statistics.

  *Create bar charts and pie charts.

  *Calculate quartiles, find outliers, and create a box plot.

  *Create a line plot and a scatter plot.

  *Calculate correlation and regression.
  
  ### Prepare the Data
    *The datasets are merged into a single DataFrame. 
    
    *The number of mice are shown from the merged DataFrame. 
    
    *Each duplicate mice is found based on the Mouse ID and Timepoint. 
    
    *A clean DataFrame is created with the dropped duplicate mice. 
    
    *The number of mice are shown from the clean DataFrame.
    
  ### Generate summary statistics
    *DataFrame is grouped appropriately
    
    *The following summary statistics are calculated
      *Mean
      *Median
      *Variance
      *Standard Deviation
      *SEM

    *A new DataFrame is created usuing summary statistics
    
![image](https://user-images.githubusercontent.com/121142680/227995847-3838973f-5379-4f10-82af-ff1678931748.png)

    
  ### Create bar charts and pie charts
    *A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated.
    
    *A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot is generated.
![download](https://user-images.githubusercontent.com/121142680/227996964-a9ff1173-f898-4db3-beb7-d17680ac74b4.png)

    
    *A pie plot showing the distribution of female versus male mice using Pandas is generated.
    
    *A pie plot showing the distribution of female versus male mice using pyplot is generated.
    
   
![download](https://user-images.githubusercontent.com/121142680/227996844-ab6aa310-1431-4251-8709-c36e841b2ee9.png)


  ### Calculate quartiles, find outliers, and create a box plot.
    *A DatFrame that has the last timepoint for each mouse ID is created using groupby.
    
    *The index of the DataFrame is reset.
    
    *Retrieve the maximum timepoint for each mouse. 
    
    *The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list. 
    
    *An empty list is created to fill with tumor volume data. 
    
    *A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group 
    
    *A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group.
![download](https://user-images.githubusercontent.com/121142680/227997459-24b2ab88-9314-4b8c-9e81-bf4e5ab61c38.png)


  ### Create a line plot and a scatter plot.
    *A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin.
![download](https://user-images.githubusercontent.com/121142680/227997668-eb224fb2-b95e-4390-a849-573418eb5b13.png)

   
    *A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen.
 ![download](https://user-images.githubusercontent.com/121142680/227997711-aa6faf57-f098-4d96-bb32-034df086342c.png)
   
  ### Calculate correlation and regression.
    *The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen.
   ![download](https://user-images.githubusercontent.com/121142680/227997820-e7f53797-12c7-4954-a6a3-17bc7e1f3e98.png)   
