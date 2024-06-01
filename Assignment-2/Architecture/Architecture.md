# C4 MODEL
## We are utilizing the C4 MODEL to represent architecture involves:

Employing hierarchical abstractions (software systems, containers, components, and code).
Employing hierarchical diagrams (system context, containers, components, and code).
Ensuring independence from notation.
Ensuring independence from specific tools.

The C4 MODEL prioritizes abstraction in depicting software architecture, aligning with how architects and developers conceptualize and create software. Its minimalistic approach, with a concise set of abstractions and diagram types, facilitates easy comprehension and application. we're not obligated to utilize all four levels of diagrams; often, just the System Context and Container diagrams suffice for most software development teams.





## CONTAINER DIAGRAM

This UML diagram represents the architecture of the "WORTHIFY.ME: Salary Predictor" system using containers to show how different parts of the system interact with each other. Here’s an explanation of each component and their relationships:
 
### Components:
 
1. Web Container (`<<WebContainer>>`):
   - Web Server: Handles HTTP requests and responses. It interacts with the user's web browser.
   - Web Browser: The client interface where users make requests to the web server and receive responses.
 
2. Application Container (`<<AppContainer>>`):
   - Application Server: The core server that handles application logic. It receives requests from the web server, processes them, and returns the responses.
   - Machine Learning Server: Performs the machine learning tasks, such as making salary predictions based on input data from the application server.
 
3. Data Container (`<<DataContainer>>`):
   - Data Processing Server: Manages data processing tasks, which may include cleaning, transforming, and preparing data for use by other components of the system.
 
4. Database Container (`<<DatabaseContainer>>`):
   - Database Server: Stores and retrieves data as requested by the application server or data processing server.
 
### Relationships and Interactions:
 
1. Web Browser and Web Server:
   - The web browser sends HTTP requests to the web server.
   - The web server processes these requests and sends back HTTP responses.
 
2. Web Server and Application Server:
   - The web server forwards user requests to the application server.
   - The application server processes these requests, which might include predicting salaries, and sends the responses back to the web server.
 
3. Application Server and Machine Learning Server:
   - The application server requests predictions from the machine learning server.
   - The machine learning server processes these requests using its prediction models and sends the results back to the application server.
 
4. Application Server and Data Processing Server:
   - The application server retrieves data from the data processing server as needed.
 
5. Data Processing Server and Database Server:
   - The data processing server requests raw data from the database server.
   - The database server retrieves the requested data and sends it back to the data processing server.
 
6. Application Server and Database Server:
   - The application server directly retrieves data from the database server when necessary.
 
### Data Flow:
 
- User Requests: The user makes a request through the web browser.
- Web Server Handling: The web server forwards this request to the application server.
- Application Logic: The application server processes the request, possibly interacting with the machine learning server for predictions or with the data processing server/database server for data.
- Response Generation: The application server generates a response and sends it back through the web server to the user's web browser.
 
This diagram illustrates the modular structure of the "WORTHIFY.ME: Salary Predictor" system, showing how different servers and components work together to provide the desired functionality.


![MicrosoftTeams-image (34)](https://github.com/SWENGG4Y2024/SWENGG4Y2024_Team9/assets/63072170/ef67410c-85ab-45ed-99a1-853b19fc3623)


## CONTEXT DIAGRAM

This UML diagram represents the interaction and flow of data within a system named "WORTHIFY.ME: Salary Predictor." Here’s an explanation of each component and their relationships:
 
### Components:
 
1. User:
   - The person who interacts with the system.
   - They can use two main functions: Predict Salary and Explore Salary Trends.
 
2. WORTHIFY.ME: Salary Predictor:
   - The central system that provides salary prediction and exploration services.
   - It has three main sub-components:
     - Predict Salary: A function used to predict the salary based on input data.
     - Explore Salary Trends: A function used to explore various salary trends.
     - Data Collection: A process of collecting data from external sources.
 
3. External Data Sources:
   - Stack Overflow Developers Survey 2023: One of the data sources used for retrieving information.
   - Job Search Platforms: Another data source from which data is retrieved for salary prediction and trends analysis.
 
### Relationships and Interactions:
 
1. User to WORTHIFY.ME: Salary Predictor:
   - The user interacts with the system.
   - The user can utilize the "Predict Salary" function and the "Explore Salary Trends" function.
2. WORTHIFY.ME: Salary Predictor to External Data Sources**:
   - The system retrieves data from external sources to provide accurate predictions and trends.
   - Stack Overflow Developers Survey 2023**: Data is collected from this survey.
   - Job Search Platforms: Data is also collected from various job search platforms.
 
3. Internal Interactions within WORTHIFY.ME: Salary Predictor:
   - The "Predict Salary" and "Explore Salary Trends" functions likely utilize the data collected by the "Data Collection" component to perform their respective operations.
 
### Data Flow:
 
- The system integrates with external data sources to retrieve relevant information, which is then used to perform salary predictions and explore trends.
- The user accesses these functionalities directly through the WORTHIFY.ME system.
 
This diagram illustrates how the WORTHIFY.ME system functions as a bridge between the user and external data sources to provide valuable insights regarding salaries.

![MicrosoftTeams-image (35)](https://github.com/SWENGG4Y2024/SWENGG4Y2024_Team9/assets/63072170/18d4d493-576a-4005-b11d-83b519808076)








