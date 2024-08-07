# Historical Weather Data API

## Project Description

This project involves building a Flask-based API that serves historical weather data. The API allows users to retrieve weather information from various weather stations for specific dates or years. The application includes a simple web interface to display available weather stations and their data.

## Process

1. **Set Up Flask Application:**
   - Initialize a Flask application to handle HTTP requests and serve web pages.

2. **Create Routes:**
   - **Home Route (`/`):** Displays a list of weather stations.
   - **Station Data Route (`/api/<station>/<date>`):** Returns temperature data for a specific station and date.
   - **All Data Route (`/api/<station>`):** Returns all weather data for a specific station.
   - **Yearly Data Route (`/api/yearly/<station>/<year>`):** Returns weather data for a specific station and year.

3. **Read Data:**
   - Load weather data from CSV files into Pandas DataFrames.
   - Extract relevant information and format it for API responses.

4. **Serve Data:**
   - Convert data to JSON format and serve it through Flask routes.
   - Render an HTML page with a table of weather stations.

## Technology Used

- **Flask:** Web framework for building the API and serving web pages.
- **Pandas:** Data manipulation library for reading and processing weather data from CSV files.
- **HTML:** For creating a simple web interface to display the weather stations.

## What I Learned

- **API Development:**
  - Gained experience in creating RESTful APIs using Flask.
  - Learned how to handle different types of HTTP requests and format responses in JSON.

- **Data Handling:**
  - Improved skills in using Pandas for data manipulation and extraction from CSV files.
  - Gained insights into handling large datasets and filtering data based on user inputs.

- **Web Development:**
  - Developed a basic HTML page to interact with the Flask application and display data.

## Future Insights

- **Enhancements:**
  - Implement authentication and authorization for accessing the API.
  - Add more advanced query capabilities, such as filtering by multiple parameters.

- **Performance Improvements:**
  - Optimize data loading and processing for large datasets.
  - Consider caching frequently accessed data to improve response times.

- **User Interface:**
  - Develop a more interactive web interface with search and filter options for users.
  - Implement visualizations to display historical weather trends and statistics.

Feel free to explore the code and run the application locally:
- `main.py` for the Flask application and API routes.
- `index.html` for the web interface displaying weather stations.