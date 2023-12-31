# KARTHIGAKM_PORTFOLIO
DATA SCIENCE PORTFOLIO
# [PROJECT 1: Youtube_Data_Harvesting_And_Warehousing](https://github.com/KarthigaKM/Youtube_Data_HarvestING-And-Warehousing)
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/Capture.PNG?raw=true)
## Overview:
  * The "YouTube Data Analysis with Streamlit and Data Warehousing" project involves building a simple user interface (UI) with Streamlit, retrieving data from the YouTube 
    API, storing it in a MongoDB data lake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app. The 
    project aims to provide valuable insights into YouTube channel performance and video details using interactive visualizations and SQL queries.
## Technologies Used:   
  * Python
  * Streamlit: For building the interactive web application.
  * MongodB : For storing extracted youtube datas ina data lake.
  * MYSQL : For Migrating stoed data into Data Warehouse.
  * Pandas : For data manipulation and preprocessing.
## Project Structure:
## Install and Import Necessary Libraries:
  * Ensure all required libraries, such as Streamlit, pymongo, and MySQL Connector, are installed and imported to set up the development environment.
## Develop Basic Streamlit Application:
  * Create a Streamlit web application with a user-friendly structure. Set the page configurations, title, and sidebar (menus) to enhance the app's aesthetics and 
    navigation.
## Establish API and Database Connections:
  * Establish connections to the YouTube API using an API key, connect to MongoDB using pymongo, and set up a connection with MySQL using MySQL Connector.
## Retrieve YouTube Data:
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/Displaying%20overall%20channel%20details.PNG?raw=true)
  * Create four separate functions to retrieve channel details, video IDs (using channel IDs), all video details, and comments' details for each video. Organize the 
    comments as arrays within their corresponding videos.
## Store Data in MongoDB:
  * Develop a function to store the retrieved data in MongoDB using appropriate queries.
## Channel Dropdown List:
  * Implement a function to allow users to store their input channels in a dropdown list for easy selection and analysis.
## Performance Queries:
 * Design a function to perform ten queries that assess the performance of all channels by conducting comparisons. Display the query results as dataframes when users 
   select a specific question.
## Migrate Data to MySQL:
 * Create a function to migrate the stored MongoDB data to MySQL using SQL queries.
## Display Data in Streamlit App:
  * Incorporate the code to display all the collected and analyzed data in the Streamlit app. Utilize interactive visualizations and user-friendly interfaces to present 
    insights effectively.
## Deployment:
  * The completed project can be deployed using Streamlit Sharing or any other hosting platform, allowing users to access the YouTube data analysis web application online.
## Future Enhancements:
  * Implementation of machine learning models for predictive analysis.
  * Incorporation of user authentication to allow personalized data exploration.


# [PROJECT 2: PhonePe Data Visualization](https://github.com/KarthigaKM/Phonepe-Data-Visualization) 
## Overview:
 * The "PhonePe Data Visualization using Streamlit, Plotly, Python" project aims to create an interactive and visually appealing data visualization dashboard to analyze and 
  explore PhonePe transaction data. It utilizes various technologies, including Python, Streamlit, Plotly, and MySQL, to present insights from the data.
## Technologies Used:
  * Python
  * Streamlit: For building the interactive web application.
  * Plotly: For creating visually appealing and interactive plots and charts.
  * Pandas: For data manipulation and preprocessing.
  * MySQL: For storing and managing the transaction data.
##  Project Structure:
  * The project consists of the following main components:
## Main Script (phonepe_main.py):
  * The main script is responsible for running the Streamlit web application.
  * It imports the necessary libraries and establishes a connection to the MySQL database.
  * The Streamlit interface allows users to navigate between different visualizations using the sidebar.
  * The dashboard is divided into two tabs: "Chart_Visualizations" and "Map_Visualizations".
## Chart Visualizations:
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/pie%20chart%20visual.PNG?raw=true)
  * The "Chart_Visualizations" tab contains six sub-tabs, each presenting specific transaction data visualizations for different states.
  * Users can select a state from the dropdown menu to view insights related to transaction types, user demographics, top transactions, and top users based on districts 
    and pincodes.
  * Plotly and Streamlit are used to create interactive pie charts and bar charts, allowing users to explore the data and understand transaction patterns.
## Map Visualizations:
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/Map%20visual.PNG?raw=true)
  * The "Map_Visualizations" tab consists of two sub-tabs, each displaying choropleth maps based on statewise transactions and user data.
  * The "Map of Statewise Transactions" presents a choropleth map showcasing transaction data by state.
  * The "Map of Statewise Users" displays a choropleth map indicating the number of users by state.
## Data Source:
  * The project uses a MySQL database to store and manage PhonePe transaction data.
  * GeoJSON data (states_india.geojson) is utilized to create the choropleth maps.
## Deployment:
  * The interactive dashboard is deployed using Streamlit Sharing, allowing users to access and explore PhonePe data visualizations with ease.
## Future Enhancements:
  * Integration of real-time data updates to ensure up-to-date insights.
  * Incorporating machine learning models for predictive analytics.
  * Enhancing the user interface with more customization options and filters.


# [Project 3: Extracting Business Card Data with OCR](https://github.com/KarthigaKM/BIZCARDX-PROJECT)
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/bizcard%20home.PNG?raw=true)
## Overview:
   This portfolio project aims to build a Streamlit web application that allows users to upload images of business cards, extract relevant information using OCR (Optical 
   Character Recognition), and store the extracted data in a MySQL database.
## Technologies Used:
   * Streamlit: For building the user interface and web application.
   * EasyOCR: To perform Optical Character Recognition on business card images.
   * MySQL: As the database to store the extracted business card data.
   * Pandas: For data manipulation and handling the extracted data in a DataFrame.
   * Matplotlib: For image processing and displaying the uploaded business card with highlighted text.
   * OpenCV: To process and manipulate images.
## Project Structure:
## Setting Page Configurations: 
   Configuring Streamlit's page settings, including title, icon, layout, and sidebar options.
## Option Menus:
   * Creating a sidebar with options for the Home, Upload and Extract, and Modify sections.
## Home Section:
   * Displaying an overview of the project, including project title, technologies used, and a brief project description.
## Upload and Extract Section:
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/BIZCARD%20UPLOADS.PNG?raw=true)
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/BIZCARD%20EXTRACT.PNG?raw=true)
   * Allowing users to upload an image of a business card.
   * Using the EasyOCR library to extract text data from the uploaded image.
   * Displaying the uploaded image with highlighted text using OpenCV and Matplotlib.
   * Extracting relevant information from the extracted text, such as company name, card holder name, designation, mobile number, email, website, area, city, state, and 
     pin code.
   * Storing the extracted data in a Pandas DataFrame.
## Store Section:
   * Connecting to a MySQL database using the mysql.connector library.
   * Creating a table named "Business_Cards" if it doesn't exist to store the extracted business card data.
   * Storing the data from the Pandas DataFrame into the MySQL database.
## Modify Section:
![](https://github.com/KarthigaKM/KARTHIGAKM_PORTFOLIO/blob/main/biz%20delete.PNG?raw=true)
   * Providing options to update and delete existing data in the database.
   * Displaying a dropdown to select the card holder name to update.
   * Allowing users to modify the data for the selected business card and committing the changes to the database.
   * Displaying a dropdown to select the card holder name to delete.
   * Confirming the deletion of the selected card and deleting the data from the database.
## Technologies Used:
   * Streamlit: For building the user interface and web application.
   * EasyOCR: To perform Optical Character Recognition on business card images.
   * MySQL: As the database to store the extracted business card data.
   * Pandas: For data manipulation and handling the extracted data in a DataFrame.
   * Matplotlib: For image processing and displaying the uploaded business card with highlighted text.
   * OpenCV: To process and manipulate images.
## Future Enhancement:
   * User Authentication: Implement user authentication and user accounts to allow multiple users to access the application securely. 
   * Improved OCR Accuracy: Explore and experiment with other OCR libraries or models to improve the accuracy of text extraction from business card images.


# [Project 4: Complaint Management System Project in Python](https://github.com/KarthigaKM/Complaint-Management-System-Project-in-Python)
## Overview:
   * The "Complaint Management System" is a Python-based system that allows users to register, log in, submit complaints, track complaint status, and update complaint details. The project utilizes the MySQL database to store user information and complaint data.
## Key Features:
   * User Registration: Users can register with a unique username and password. User data is stored in the MySQL database.
   * User Login: Registered users can log in using their credentials to access the system.
   * Complaint Submission: Logged-in users can submit multiple complaints, each with a description. The complaints are stored in the database with a default status of "Pending."
   * Complaint Status Tracking: Users can view the status of their submitted complaints, showing the complaint ID, description, and status (e.g., "Pending").
   * Complaint Resolution: Users can update the description of their submitted complaints. The updated descriptions are stored in the database.
## Project Structure:
   * The project is organized into several functions, each handling specific functionalities of the system:
## Database Initialization: 
   * Connects to the MySQL database and creates two tables: "users" to store user information and "complaints" to store complaint data.
## User Registration: 
   * Registers users by accepting a username and password. The user data is stored in the "users" table.
## User Login: 
   * Allows registered users to log in by providing their username and password. The function returns the user ID upon successful login.
## Complaint Submission: 
   * Allows users to submit complaints. The function accepts the user ID and the complaint description and stores the complaint data in the "complaints" table with a default status of "Pending."
## Complaint Status Tracking: 
   * Retrieves all complaints submitted by a specific user and displays their complaint ID, description, and status.
## Complaint Resolution: 
   * Allows users to update the description of their submitted complaints. The updated description is stored in the "complaints" table.
## Main Program: 
   * Handles the overall flow of the Complaint Management System. It includes options for user registration, login, submitting complaints, tracking complaint status, updating complaint status, and logging out.
## Future Enhancement:
   *  Display this in User Interface application like Streamlit
