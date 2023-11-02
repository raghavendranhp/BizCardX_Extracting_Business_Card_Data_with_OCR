# Cardify: Business Card Data Extraction and Management

Cardify is a Streamlit application that simplifies the process of extracting and managing business card data.  
With Cardify, users can easily upload business card images, extract relevant information using OCR, and manage the extracted data efficiently.

## Problem Statement

The traditional method of manually entering data from business cards can be time-consuming and error-prone.  
Cardify addresses this problem by providing an automated solution for extracting and organizing business card information.  
Users can upload images of business cards, and the application extracts essential details such as name, designation, contact information, and more.

## Project Overview

Cardify offers the following key features:

- **Data Extraction**: Upload a business card image, and Cardify will use OCR to extract information, including the individual's name, designation, contact details, and more.

- **Database Management**: The extracted data can be saved to a database for easy retrieval and management. Users can add, update, delete, and retrieve business card data.

- **Streamlit GUI**: The project utilizes the Streamlit framework to create an interactive and user-friendly interface for both data extraction and database management.

- **EasyOCR Integration**: Cardify leverages the EasyOCR library for efficient text extraction from images.

## Technologies Used

- Python
- Streamlit
- EasyOCR
- SQLite (for the database)
- SQLAlchemy (for database operations)

## Project Flow

The project follows a structured flow:

1. **Data Extraction**: Users upload a business card image, and the application extracts the relevant information.

2. **Display**: The extracted data is displayed in a clear and organized manner in the Streamlit GUI.

3. **Database Integration**: The extracted information is saved in an SQLite database, allowing users to manage and retrieve data easily.

4. **Data Management**: Users can update or delete records, and the application provides options for deleting all records in the database.

## Deployment (Using Streamlit Cloud)

To deploy Cardify using Streamlit Cloud, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/raghavendranhp/Cardify_Extracting_Business_Card_Data_and_Management.git
  
2.Install the required Python packages  
3.Deploy the Streamlit app on Streamlit Cloud by using the Streamlit CLI.  
4.Access the deployed application--[open app](https://raghavendranhpprojectbizcardx.streamlit.app/)

## Business Values/Insights
**Efficiency:**  
Cardify improves the efficiency of data entry tasks, reducing manual effort and human errors.

**Centralized Database:**  
Businesses can maintain a centralized database of business card data, making it easy to access and update contact information.

**User-Friendly:**  
The application provides a simple and intuitive interface, making it accessible to users with varying technical backgrounds.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow our Contributing Guidelines.

## License
This project is licensed under the MIT License.

## App URL
Open Application:https://raghavendranhpprojectbizcardx.streamlit.app/

## Author
Raghavendran S,  
Aspiring Data Scientist,  
Linkedin:[View Profile](https://www.linkedin.com/in/raghavendransundararajan/),  
raghavendranhp@gmail.com,  
Happy Analyzing!

