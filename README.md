# team_jv
190N Final Project


__Purpose__:\
Collect packet capture data from video streaming sites
Store relevant pcap data features in a dataframe 
Learn a model (random forest classifier) to solve classifier problem between the sites


__Collect Data__:\
Use Anime_preprocess_and_train_model
- Run all cells of this file up until the docker commands
- You might need to change the link of the video depending on which video you want to collect data on
- Running experiments should produce files in the repesctive directory
- Run the docker command on the given file to convert it into a pcap flow list csv


__Extracting Features__:\
Use feature_extraction.ipynb
- Change the files in the list to match the path of the csv files created in the previous step
- One set of files from one site should go in the first list and the second set from a different website will go in the second list
- Change the string for labels depending on the label that you want for the classes
- Run the RandomForestClassifier() functions and then the trustee cell to get the model analysis
