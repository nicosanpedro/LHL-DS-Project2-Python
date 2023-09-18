# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
1. Collect data using APIs with or without token for authentication.
2. Apply data mining techniques to parse through JSON files.
3. Connect and build a database using SQLite3 on Jupyter Notebook.
4. Analyze the collected data and perform Linear Regression Analysis.

## Process
### I. Analyze what is being asked.
1. Review the instructions and itemized the goal.
   
### II. Collect Data
1. Connect with city bikes API and collect bike stations in Toronto where there are relatively large number of bike stations.
2. Create a Foursquare and Yelp Account to acquire API tokens.
3. Connect to Foursquare and Yelp API and query about restaurants and the desired POIs.
4. Save the final collected data as dataframes within the notebook.
5. Export the final dataframes into a pickle file for other notebook's usage.
   
### III. Data Mining & EDA
1. Convert the JSON file into dictionaries.
2. Collect and review relevant dictionary keys that can be used later.
3. Convert the dictionary into a dataframe.
4. When a feature is needed, simply take the feature off from the dataframe instead of parsing through a for loop.
   
### IV. Build a Database
1. Declare and initialize SQLite3 connection into an object.
2. Declare and initialize SQLite3 querry cursor into an object.
3. Create a table template by sotring the querry as a string in a variable.
   - 3.1 Set table name
   - 3.2 Set the data type
   - 3.3 Set the constraints
4. Take all unique rows from all datframes and copy it into the designated table for each dataframe.
   
### V. Linear Regression Model
1. import all all the necessary libraries.
2. Select the feature to be used for the model.
3. Perform a Linear regression.
4. Print and analyze the results.
5. Create a scatterplot to visualize the datasets used.

## Results
1. Yelp has provided more features for each API call; however, Foursquare provided restaurants that are half as closer to the bike stations.
2. There is no linear relationship between the distance of the restaurants to the number of bikes available in each station.
3. Free Yelp API is very limited to 500 calls.
   
## Challenges 
1. Lack of realted documentation or study materials on how to use Yelp's API.

## Future Goals
1. Be on time.
