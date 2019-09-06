# NFL Player Profiles with Arrest records
The purpose of this project is to identify NFL player arrest records and their demographic player records. 
We are also asking: "Which team drafted the most players with arrest records during the period 2000 -2017?"
    
## The Process:
We analyzed all the available arrest records from Kaggle NFL Arrests 2000 - 2017.
A record of reported NFL Arrests with details about Crime, Team and Player. 
 
## Extract:

Original Data Sources include
    
   * Web Scraping: 'html' from https://www.kaggle.com/patrickmurphy/nfl-arrests
   * pull: 'json' from https://www.kaggle.com/zynicide/nfl-football-player-stats#profiles_1512362725.022629.json
    
   * Create dataframe from NFL Arrests csv file
   * Choose columns wanted from original dataframe
   * Rename columns
    
   * Create dataframe from .json file nfl profiles 
    
## Transform: (Data Cleanup & Analysis)
   * Clean nfl arrests by saving only the 1st instance of a player name and removing duplicate entries.
   
   * Clean nfl profiles. Duplicate players removed from the profile section
    
   * All na files filled with not applicable 
    
## Load:




### This repo contains the collaborative work. 
### You will find the following:

### Resources Folder

### Output Folder
   * NFL_Players.ipynb
 


