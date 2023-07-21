# KARTHIGAKM_PORTFOLIO
DATA SCIENCE PORTFOLIO
# [PROJECT 1: Youtube_Data_Harvesting_And_Warehousing](https://github.com/KarthigaKM/Youtube_Data_HarvestING-And-Warehousing)
# Overview:
  * The "YouTube Data Analysis with Streamlit and Data Warehousing" project involves building a simple user interface (UI) with Streamlit, retrieving data from the YouTube 
    API, storing it in a MongoDB data lake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app. The 
    project aims to provide valuable insights into YouTube channel performance and video details using interactive visualizations and SQL queries.
# Technologies Used:   
  * Python
  * Streamlit: For building the interactive web application.
  * MongodB : For storing extracted youtube datas ina data lake.
  * MYSQL : For Migrating stoed data into Data Warehouse.
# Steps:
# Install and Import Necessary Libraries:
  * Ensure all required libraries, such as Streamlit, pymongo, and MySQL Connector, are installed and imported to set up the development environment.
# Develop Basic Streamlit Application:
  * Create a Streamlit web application with a user-friendly structure. Set the page configurations, title, and sidebar (menus) to enhance the app's aesthetics and 
    navigation.
# Establish API and Database Connections:
  * Establish connections to the YouTube API using an API key, connect to MongoDB using pymongo, and set up a connection with MySQL using MySQL Connector.

# Retrieve YouTube Data:
  * Create four separate functions to retrieve channel details, video IDs (using channel IDs), all video details, and comments' details for each video. Organize the 
    comments as arrays within their corresponding videos.
# Store Data in MongoDB:
  * Develop a function to store the retrieved data in MongoDB using appropriate queries.
# Channel Dropdown List:
  * Implement a function to allow users to store their input channels in a dropdown list for easy selection and analysis.
# Performance Queries:
 * Design a function to perform ten queries that assess the performance of all channels by conducting comparisons. Display the query results as dataframes when users select 
   a specific question.
# Migrate Data to MySQL:
 * Create a function to migrate the stored MongoDB data to MySQL using SQL queries.
# Display Data in Streamlit App:
  * Incorporate the code to display all the collected and analyzed data in the Streamlit app. Utilize interactive visualizations and user-friendly interfaces to present 
    insights effectively.
# Deployment:
  * The completed project can be deployed using Streamlit Sharing or any other hosting platform, allowing users to access the YouTube data analysis web application online.
# Future Enhancements:
  * Implementation of machine learning models for predictive analysis.
  * Incorporation of user authentication to allow personalized data exploration.

# PROJECT 2: PhonePe Data Visualization 
# Project Overview:
 * The "PhonePe Data Visualization using Streamlit, Plotly, Python" project aims to create an interactive and visually appealing data visualization dashboard to analyze and 
  explore PhonePe transaction data. It utilizes various technologies, including Python, Streamlit, Plotly, and MySQL, to present insights from the data.
# Technologies Used:
  * Python
  * Streamlit: For building the interactive web application.
  * Plotly: For creating visually appealing and interactive plots and charts.
  * Pandas: For data manipulation and preprocessing.
  * MySQL: For storing and managing the transaction data.
#  Project Structure:
* The project consists of the following main components:
# Main Script (phonepe_main.py):
* The main script is responsible for running the Streamlit web application.
* It imports the necessary libraries and establishes a connection to the MySQL database.
* The Streamlit interface allows users to navigate between different visualizations using the sidebar.
* The dashboard is divided into two tabs: "Chart_Visualizations" and "Map_Visualizations".
# Chart Visualizations:
* The "Chart_Visualizations" tab contains six sub-tabs, each presenting specific transaction data visualizations for different states.
* Users can select a state from the dropdown menu to view insights related to transaction types, user demographics, top transactions, and top users based on districts and 
  pincodes.
* Plotly and Streamlit are used to create interactive pie charts and bar charts, allowing users to explore the data and understand transaction patterns.
# Map Visualizations:
* The "Map_Visualizations" tab consists of two sub-tabs, each displaying choropleth maps based on statewise transactions and user data.
* The "Map of Statewise Transactions" presents a choropleth map showcasing transaction data by state.
* The "Map of Statewise Users" displays a choropleth map indicating the number of users by state.
# Data Source:
* The project uses a MySQL database to store and manage PhonePe transaction data.
* GeoJSON data (states_india.geojson) is utilized to create the choropleth maps.
# Deployment:
* The interactive dashboard is deployed using Streamlit Sharing, allowing users to access and explore PhonePe data visualizations with ease.
# Future Enhancements:
* Integration of real-time data updates to ensure up-to-date insights.
* Incorporating machine learning models for predictive analytics.
* Enhancing the user interface with more customization options and filters.
