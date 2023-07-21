# KARTHIGAKM_PORTFOLIO
DATA SCIENCE PORTFOLIO
# [PROJECT 1: Youtube_Data_Harvesting_And_Warehousing](https://github.com/KarthigaKM/Youtube_Data_HarvestING-And-Warehousing)
* Overview:  Building a simple UI with Streamlit, retrieving data from the YouTube API, storing it in a MongoDB data lake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app. 
* steps:  
 * Install and Import all neccessary libraries. 
 * Develop basic streamlit with a required structure and set page cofigurations, title , sidebar(Menus) ,etc..
 * Make connections with youtube api using api key , with mongodb using pymongo and with mysql using Mysql connection.
 * Create 4 seperate functions to retrieve channel Details, video ids(using channel_id), all video details, comments's Details of each videos.
 * Here I've created a seperate function to keep comments of all videos inside their corresponding videos as a "comments" array.
 * Then created a function to store retrieved datas in mongodb by mongodb quries 
 * After that, created a function to store all the user inputs's channel in a Dropdown list. 
 * Function for 10 queries which defines the performance of all channels using comparision and display an answer as a dataframe when user selected the qestion.
 * created a function to migrate stored mongodb datas to Mysql by mysql querying. 
 * Added code to display everything in a streamlit app.
