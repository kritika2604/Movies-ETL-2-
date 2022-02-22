# Movies-ETL

## Purpose:
Amazing Prime, is a platform for streaming movies and TV shows. Amazing prime want to build an algorithm to predict which low budget movies released will become popular so that they can buy the streaming rights.  For doing this, Amazing prime sponsored a hackathon and provided clean data and asking the participants to predict the popular movies. 


1: Write an ETL Function to Read Three Data Files

2: Extract and Transform the Wikipedia Data

3: Extract and Transform the Kaggle data

4: Create the Movie Database

## Data Resources:
- wikipedia-movies.json, 
- movies_metadata.csv, 
- ratings.csv

## Softwares: 
- Python, 
- Anaconda Navigator (Jupyter Notebook),
- PostgreSQL, and
- pgAdmin

## Results:
An ETL function was defined to read the three files - Wikipedia JSON, Kaggle Metadata and Movieslens csv and were converted to DataFrames. 

These DataFrames were then filtered out by the TV shows. 

After sorting and filtering the wiki data into more usable and without redundant information, it was then merged with kaggle data. 

### Data is now imported into postgreSQL data tables for use in the Hackathon. 
