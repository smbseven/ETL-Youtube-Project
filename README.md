#ETL-Youtube-Project

<h3>ETL Project based on Youtube data<h3>


As part of the ETL Challenge, we decided to work on a Youtube Dataset found in Kaggle.
The dataset is called ‘Trending YouTube Video Statistics’.  
YouTube maintains a list of the top trending videos on the platform  
In order to determine which videos are trending, YouTube uses a combination of factors including user interactions  
(number of views, shares, comments and likes)  

Project goal: Transform the given datasets to simplify queries based on tags, likes, dislikes, views & category id   


<h4>Project Overview<h4>  
 

The dataset includes two different files for nine countries (and counting) with the following structure:    
CSV File containing video id, name, comments, tags, etc.  
JSON File containing video category id and category title  
Originally we downloaded the files, however, during the exploration, we found out that Kaggle has an API that can be used to extract the data … (Which we used)  
You can find the dataset here:  
https://www.kaggle.com/datasnaek/youtube-new  


<h4>Instructions<h4>  

In order to simplify the flow of this project, we decided to create a single Jupyter Notebook.  
The Notebook contains the full workflow developed by the team. Complying with the approptiate ETL Structure.  

Extraction:  

- The first part of the project extracts data directly from Kaggle using an API  
- The second part of the project is designed to understand the received data and its characterization  

Trabsformation:  

- The third part of the project is the data transformation: getting the right data for the purpose of the exercise. Additionally, the presented data is cleaned,  
structured and formatted to comply with the normalization structure.  
- The fourth part of the project creates the respective dataframes within pandas to ensure that those dataframes match with the tables  

Loading:  

- The fifth part of the project was to design the DB Schemas, fof that we used Quick DBD to design the Schema and then, we programed entirely the database  
using pandas.  
- The sixth part of the project was to test our plan based on multiple queries that would show the data usability and purpose once it was formatted

Challenges:  

- Our initial goal was to integrate multiple countries to try and figure out if there were any matching trends within them, however, coding proved to be  
extremely complicated, and, although we did try to clean the respective datasets, considering the time given and the extent of the cleansing required  
we decided to stick to one country and develop the full process. As is shown, we decided to work with UK's dataset.  


<h4>Contributors<h4>  

1. Flores, Carlos: https://github.com/catu099  
3. Mejía, Sergio: https://github.com/smbseven  
4. Vázquez, Luz Del Cármen: https://github.com/luzvazgal  
5. Vicario, Liliana: https://github.com/raciv65  
  

<h4>Tools Used<h4>  
  Kaggle - Dataset  
  Jupyter Notebook - Coding  
  Github - Version management and integration  
  Quick DBD - Schema design  
  Postgres - SQL Database  
  
  Tool selection:  
  
  The only tool discussion happened at the Database level, considerng that we had a CSV file and a JSON file, we weren't really sure whether to use MongoDB  
  of PostgreSQL, however, since all of our data is structured, it was evident that SQL would give us the best possible structure for the project and a cleaner,   
  quicker output for the project.  
  
