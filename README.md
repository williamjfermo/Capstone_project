# Capstone Project:  Running with honor
This project is a part of the [Flatiron](http://https://flatironschool.com/) for Data Science
#### -- Project Status: [Ongoing]

## Project Intro/Objective
Find cheaters through marathon data. Use the tools I learned in data science to help race organizers preserve the integrity of earning a Marathon medal.  Currently major marathons do not employ an anomaly detection system to remove cheaters from results.

### Methods Used
* Webscraping
* Exploratory Data Analysis
* Data Visualization 
* Research


### Technologies
* Python
* Tableau
* Beautifulsoup  
* Webscraping
* Pandas
* Jupyter


## Project Description
Use of data analysis on Chicago Marathon 2019 data collected from [Chicago Marathon website](https://www.chicagomarathon.com/) Collected all data encompassing over 40,000 runners.   Used tableau for data visualization and data analysis  Hope to find cheaters exploring marathon data and make a model that will detect runners for marathon organizations.  Hoping to submit my results and model to major marathons for their usage.

## Needs of this project

- Sourcing data
- data exploration/descriptive statistics
- data processing/cleaning
- tableau
- findings
- writeup/reporting

## DATA
- CSV files are included in the data folder  
-  Webscraping code will not be included but all relevevant data is included in data folder.
-  Data was collected of all finishers from the 2019 Chicago Marathon and 2019 Houston Marathon.
- Data includes the following info:  
        - Name  
        - Bib  
        - Age  
        - Age Group  
        - Sex/Gender 
        - Place Overal  
        - Start time  
        - Finish time  
        - Time of day(5k,10k,15k,20k,half,25k,30k,finish)  
        - Time (5k,10k,15k,20k,half,25k,30k,finish)  
        - Min/Mile(5k,10k,15k,20k,half,25k,30k,finish) 

## Getting Started

1. Marathon data webscraped from [Chicago Marathon website](https://www.chicagomarathon.com/) 
2. Used Beautifulsoup to webscrape data  
3. Used pandas to clean and combine datasets
4.  EDA was done on data
4. Tableau was used on data for analysis and visuals
5.  Code a model that will identify cheaters in Houston Marathon 2019 data set

 

## Featured Notebooks
* [EDA notebook](https://github.com/williamjfermo/Capstone_project/blob/master/EDA_notebook.ipynb)
* [Cleaning data notebook](https://github.com/williamjfermo/Capstone_project/blob/master/Cleaning_data.ipynb)
* [Pandas model to find cheaters](https://github.com/williamjfermo/Capstone_project/blob/master/Pandas_model_to_find_cheaters.ipynb)
* [Canva Presentation](https://www.canva.com/design/DADs-cn8jr4/m-NpeWzqlykStYGNV03quQ/view?utm_content=DADs-cn8jr4&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)
* [Tableau results](https://public.tableau.com/profile/william.fermo#!/vizhome/Final_project_15754699642510/Allrunners)


## Analysis
* 4 types of ways people cheat  
    - Missed Timings mats  
    - Course cutters  
    - Bib mule  
    - Bib swap  
* Missing Timing mats found that a significant reason a large number of people missed matts was due to having clothing over bib
* Course cutters found that their times are significantly faster then their normal average pace
* Bib mule was able to narrow down results by finding people with all same timing splits throughout the race and only including Boston Marathon qualifying times.
* Bib swap is difficult to quantify without some form of image recognition

## Recomendations
* Flag Runners  
    Anomaly system should be implemented.  Results analyzed and those offenders should be removed from results.
* Missing splits  
    Remind people not to cover bibs or wear bibs on shorts.
* Facial Recognition  
    Current technology just ID's photos of bib numbers.  Facial recognition would eliminate a lot of these problems.
* Contact Major Marathons  
  Share my results to major marthons and hopefully bring back the honor to running a marathon and recieving that medal.
## Future Improvements

- Current model was Heuristic simple python model  Would hope to make a machine learning model with more data.   




## Contributing Members
William Fermo  



## Contact
* William Fermo [Email](williamjfermo@gmail.com)


