<h3>ETL-Youtube-Project</h3>

<h4>ETL Project based on Youtube data</h4>  


As part of the ETL Challenge, we decided to work on a Youtube Dataset found in Kaggle.
The dataset is called <strong>‘Trending YouTube Video Statistics’</strong>.  
YouTube maintains a list of the top trending videos on the platform.  
In order to determine which videos are trending, YouTube uses a combination of factors including user interactions  
(number of views, shares, comments and likes)  

The challenge is that although the datasets exists, it is very difficult for the common user to get a sense of the information because everything is presented on a table, tags are integrated in a single field separated via a "|" and they are not exploitable.  

Project goal: Transform the given datasets to simplify user consumption through queries based on tags, likes, dislikes, views & category id   


<h4>Project Overview</h4>  
 

The dataset includes two different files for nine countries (and counting) with the following structure:    
<ul>
 <li>CSV File containing video id, name, comments, tags, etc.</li>  
<li>JSON File containing video category id and category title</li>  
<li>Originally we downloaded the files, however, during the exploration, we found out that Kaggle has an API that can be used to extract the data … (Which we used)</li>  
<li>You can find the dataset here: https://www.kaggle.com/datasnaek/youtube-new</li>  
</ul>

<h4>Instructions</h4>  

In order to simplify the flow of this project, we decided to create a single Jupyter Notebook.  
The Notebook contains the full workflow developed by the team. Complying with the approptiate ETL Structure.  

<h4>Extraction:</h4>  

<ul>
 <li> The first part of the project extracts data directly from Kaggle using an API  </li>
<li>The second part of the project is designed to understand the received data and its characterization </li>
 </ul>

<h4>Trabsformation:</h4>  

<ul>
<li>The third part of the project is the data transformation: getting the right data for the purpose of the exercise. Additionally, the presented data is cleaned, structured and formatted to comply with the normalization structure. </li>  
<li>The fourth part of the project creates the respective dataframes within pandas to ensure that those dataframes match with the tables</li> 
</ul>

<h4>Loading:</h4>  

<ul>
<li>The fifth part of the project was to design the DB Schemas, fof that we used Quick DBD to design the Schema and then, we programed entirely the database using pandas.</li>  
<li>The sixth part of the project was to test our plan based on multiple queries that would show the data usability and purpose once it was formatted</li>
 </ul>

<h4>Challenges:</h4> 

Our initial goal was to integrate multiple countries to try and figure out if there were any matching trends within them, however, coding proved to be extremely complicated, and, although we did try to clean the respective datasets, considering the time given and the extent of the cleansing required. We decided to stick to one country and develop the full process. As is shown, we decided to work with UK's dataset.  

<h4>Contributors</h4>  

1. Flores, Carlos: https://github.com/catu099  
3. Mejía, Sergio: https://github.com/smbseven  
4. Vázquez, Luz Del Cármen: https://github.com/luzvazgal  
5. Vicario, Liliana: https://github.com/raciv65  
  

<h4>Tools Used</h4>  
- Kaggle: Dataset  
- Jupyter Notebook: Coding  
- Github: Version management and integration  
- Quick DBD: Schema design  
- Postgres: SQL Database  
  
  <h5>Tool selection:</h5>  
  
  The only tool discussion happened at the Database level, considering that we had a CSV file and a JSON file, we weren't really sure whether to use MongoDB  
  or PostgreSQL, however, since all of our data is structured and in fact, there is a lot of shared data, normalizing through SQL would give us the best   
  possible structure for the project and a cleaner, quicker output for the project.   
  
  
  <h4>Files</h4>  
 
 Within the present repository, the reader will find the following files / folders:
 <ul>
 <li>.ipynb_checkpoints - Jupyter notebooks used by the team members to start testing different hypothesis of the data </li> 
 <li>.DS_Store - Datasets and Dataframes  </li>
 <li>DB Documentadion.pdf - Database Schema</li>  
 <li>DB design.png - Database Schema diagram </li> 
 <li>ExtractandExploringData3.ipynb - Full project code with comments </li>
 </ul>
 
 
 
  
