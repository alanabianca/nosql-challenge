# nosql-challenge
This project is a NoSQL MongoDB database creation and analysis, using the Python library PyMongo. It analyzes a database containing food safety ratings and information form restuarants in the UK. 

### Database Setup
The project begins by importing the necessary libraries, such as pandas and pymongo.
The dataset is loaded from the CSV file (establishments.json) into a NoSQL DataFrame using MongoDB.
### Database Updates:
This portion of the challenge uses the file NoSQL_setup_starter.ipynb.
Several updates are made to the dataframe:
- Adding a new restaurant entry for Penang Flavours
- Discovering the BusinessTypeID for "Restaurant/Cafe/Canteen"
- Editing the Penang Flavours document to reflect the correct BusinessTypeID (1)
- Deleting all restuarants located in Dover
- Changing the data types for latitude, longitude, and the Rating Value
### Exploratory Analysis:
This portion of the challenge uses the file NoSQL_analysis_starter.ipynb.
It uses the database created in the previous file to analyze the data, answering the following questions:
1. Which establishments have a hygiene score equal to 20?
    - 41 documents are found, the first is displayed
2. Which establishments in London have a Rating Value greater than or equal to 4?
    - 33 documents are found, the first is displayed
3. What are the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    - The top resturants are displayed
4. How many establishments in each Local Authority area have a hygiene score of 0? 
    - Results are sorted from highest to lowest, and the top ten local authority areas are displayed
    
# Table of Contents:
- [Introduction](#introduction)
- [Usage](#usage)
- [Acknowledgements](#acknowledgemnets)
- [Authors](#authors)

# Usage:<a name="usage"></a>
Run the code at the top of NoSQL_setup_starter.ipynb in your terminal.
Run NoSQL_setup_starter.ipynb
Run NoSQL_anaysis_starter.ipynb

# Acknowledgments:<a name="acknowledgements"></a>
### Data Source: 
- Data provided by Data Analytics bootcamp and Ariel Gamino.
### Libraries and Framework:
- PyMongo
- Pandas
- Pprint
### Code Support:
- UT Austin The Data Analytics and Visualization Bootcamp: https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-DATA-PT-08-2023-U-LOLC/-/tree/main
- Ask BCS

# Authors:<a name="authors"></a>
- Alana Castellano

