# These notbooks were used to scrape the web, merge databases, clean data and analyze/visualize regression analysis

  1. open the Jupyter notebook: scrape_web_obesity
  >> this will scrape locations of the YMCA per state by having selenium enter the zipcodes (opened from a pickle file) for a state
  >> The only thing you need to set is :
  >> + change the path where your pickle file of zipcodes is located
  >> + enter the state initials
 
  
  2. Next, open the Jupyter notebook merge_data_obesity
  >> Here, you will open 3 data frame (pickled files), clean and merge them into one big data frame for analysis
  >> + change the path where your pickle files are located
  
  3. Finally, open the last jupyter notebook analyze_data_obesity
  >> Here, you will open the big data frame that was created and saved in the merge_data_obesity notebook. Then you will visualize the data and create a regression model using the following techniques:
  
  + linear regression 
  + Lasso regularization 
  + cross validation
  
   >> +  only need to change the path where your pickle file is located and run
 
