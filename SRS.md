# Software Requirement Specification

## Table of Contents
-  [1. Introduction](#1-introduction)
    

## 1. Introduction 

In today's dynamic and rapidly evolving job market, the need for accurate and up-to-date information on salary expectations has never been more critical. Job seekers, career changers, and employers alike rely on precise salary predictions to make
informed decisions. The "WORTHIFY.ME" project emerges as a solution to
address this pressing need by providing a versatile and data-driven platform for
predicting salaries and exploring salary trends. In this introduction, we will
elucidate the significance of this project, identify the gaps in current available
solutions, and outline the structure of this report. Salary expectations play a pivotal role in career decisions, job negotiations, and
industry benchmarks.

Individuals seeking employment, considering a career change, or negotiating their compensation packages require reliable tools to understand how
their qualifications and experience align with industry standards. Employers, on the
other hand, need insights into competitive salaries to attract and retain top talent. While salary data is available from various sources, existing solutions often lack
precision and relevance, leading to ambiguity in salary negotiations and workforce
management. 

The "WORTHIFY.ME" project strives to fill this void by providing a
robust platform that harnesses data-driven methodologies to offer accurate salary
predictions. Moreover, its "Explore" function visualizes comprehensive salary
trends based on real-world data, delivering invaluable insights to users, be they
professionals or organizations. Current available solutions for salary prediction and exploration frequently fall short in several key aspects. Many rely on outdated or generic data sources that do not adequately reflect the rapidly changing job market dynamics. As a result, the predictions generated often lack accuracy and relevance. Additionally, user-friendliness and accessibility are often compromised, making it challenging for non-technical users to obtain actionable insights. 

The "WORTHIFY.ME" projectrecognizes and addresses these gaps by leveraging the latest data from the StackOverflow Developers Survey 2023, coupled with a user-friendly interface for anintuitive experience. This project aspires to bridge the disparity between available
solutions and the practical needs of individuals and organizations in the modern
workforce.

This report aims to provide a comprehensive overview of the "WORTHIFY.ME:
Salary Predictor" project. In subsequent sections, we will delve into the project's
features, methodology, results, challenges, and future improvements. By the end of
this report, readers will gain a thorough understanding of how this project not only
addresses the existing gaps in salary prediction and exploration but also offers
valuable insights that can significantly impact career decisions and workforce
management. From the Predict function that assists in individual salary expectations
to the Explore function that provides a broader view of salary trends, this project
holds the potential to redefine how professionals navigate the ever-evolving
landscape of career opportunities and compensation


# Software Requirement Specification

## Table of Contents
-  [1. Introduction](#1-introduction)
    

## 1. Introduction 

In today's dynamic and rapidly evolving job market, the need for accurate and up-to-date information on salary expectations has never been more critical. Job seekers, career changers, and employers alike rely on precise salary predictions to make
informed decisions. The "WORTHIFY.ME" project emerges as a solution to
address this pressing need by providing a versatile and data-driven platform for
predicting salaries and exploring salary trends. In this introduction, we will
elucidate the significance of this project, identify the gaps in current available
solutions, and outline the structure of this report. Salary expectations play a pivotal role in career decisions, job negotiations, and
industry benchmarks.

Individuals seeking employment, considering a career change, or negotiating their compensation packages require reliable tools to understand how
their qualifications and experience align with industry standards. Employers, on the
other hand, need insights into competitive salaries to attract and retain top talent. While salary data is available from various sources, existing solutions often lack
precision and relevance, leading to ambiguity in salary negotiations and workforce
management. 

The "WORTHIFY.ME" project strives to fill this void by providing a
robust platform that harnesses data-driven methodologies to offer accurate salary
predictions. Moreover, its "Explore" function visualizes comprehensive salary
trends based on real-world data, delivering invaluable insights to users, be they
professionals or organizations. Current available solutions for salary prediction and exploration frequently fall short in several key aspects. Many rely on outdated or generic data sources that do not adequately reflect the rapidly changing job market dynamics. As a result, the predictions generated often lack accuracy and relevance. Additionally, user-friendliness and accessibility are often compromised, making it challenging for non-technical users to obtain actionable insights. 

The "WORTHIFY.ME" projectrecognizes and addresses these gaps by leveraging the latest data from the StackOverflow Developers Survey 2023, coupled with a user-friendly interface for anintuitive experience. This project aspires to bridge the disparity between available
solutions and the practical needs of individuals and organizations in the modern
workforce.

This report aims to provide a comprehensive overview of the "WORTHIFY.ME:
Salary Predictor" project. In subsequent sections, we will delve into the project's
features, methodology, results, challenges, and future improvements. By the end of
this report, readers will gain a thorough understanding of how this project not only
addresses the existing gaps in salary prediction and exploration but also offers
valuable insights that can significantly impact career decisions and workforce
management. From the Predict function that assists in individual salary expectations
to the Explore function that provides a broader view of salary trends, this project
holds the potential to redefine how professionals navigate the ever-evolving
landscape of career opportunities and compensation


##Implementation
###4.1 Methodology
	4.1.1 Objective
Clearly define the goals of the salary prediction system (e.g., predict future employee salaries based on various factors).
	4.1.2 Scope
Determine the extent of the project, including features, functionalities, data sources, and integration points.
	4.1.3 Feasible Methodologies
•	Data Collection
The data was collected in form of a csv file provided by Stack Overflow in a survey i.e. Stack Overflow Developers Survey 2023. Collected relevant data for training and testing the model, including historical salary data, job descriptions, experience levels, education, and other related features. 
•	Data Preprocessing
Cleaned and pre-processed the raw data. Handled missing values, encoded categorical variables, scaled numerical features, and split the dataset into training and testing sets.
•	Feature Engineering
Created new features or modify existing ones to enhance the predictive power of the model. This might include transforming data, creating interaction terms, or extracting relevant information.
•	Implemented the core of the AI/ML model. 

       Common algorithms: Linear regression, decision tree, SVMs, etc.

•	Training
Trained the model using the training dataset. This involves feeding the data through the chosen algorithm and adjusting the model parameters to minimize the difference between predicted and actual salaries.
•	Evaluation
Assessed the model's performance using a separate testing dataset. Common evaluation metrics for regression tasks like salary prediction include Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), etc.
•	Hyperparameter Tuning
Optimized the model's hyperparameters to improve performance. This involved techniques such as grid search, random search, or more advanced methods like Bayesian optimization.
•	Model Deployment
Once the model was trained and evaluated satisfactorily, deployed it for making predictions. This can be in the form of an API, a web application, or integration with other systems.


 
#4.2 Testing OR Verification Plan
Ensuring Functionality and Reliability
In the "WORTHIFY.ME: Salary Predictor" project, the testing and verification plan plays a pivotal role in validating the system's functionality, reliability, and accuracy.
•	4.2.1 Test Case Title
The testing process is structured around specific test cases, each with a unique title that reflects its purpose and scope. These test cases are meticulously designed to evaluate various aspects of the "WORTHIFY.ME" system. They serve to ensure that the project meets predefined criteria for success. 
Some of the key test cases include:
1.	T01: Salary Prediction Accuracy - 
This test case assesses the accuracy of salary predictions made by the "Predict" function. It involves providing known inputs and comparing the system's predictions with actual salary data. 

2.	T02: Data Source Reliability - 
Ensuring that the data collected from the Stack Overflow Developers Survey 2023 is reliable and that it has been accurately cleaned and processed. 

3.	T03: User Interface Usability - 
Evaluating the user interface's ease of use, accessibility, and responsiveness. This test case ensures that users can interact with the "Predict" and "Explore" functions smoothly. 

•	4.2.2 Test Condition
Each test case is executed under specific conditions that mirror real-world scenarios and use cases. Defining these conditions is critical to assess the system's behaviour accurately. 
Some of the conditions that are considered include:
1.	T01: Salary Prediction Accuracy - 
Test conditions may vary based on factors like the country of work, education level, and years of experience provided as input. 

2.	T02: Data Source Reliability - 
Conditions involve verifying thea quality of data, including factors like missing values, outliers, and data inconsistency.

3.	T03: User Interface Usability - 
Test conditions encompass various devices and screen sizes, ensuring that the user interface is compatible with a broad range of platforms.

•	4.2.3 System Behaviour
Some examples of expected system behaviour include:
1.	T01: Salary Prediction Accuracy -
 The system should provide salary predictions that closely align with the actual salary data for the provided inputs.
 
2.	T02: Data Source Reliability - 
The system should exhibit data cleaning and preprocessing processes that ensure data quality and accuracy. 

3.	T03: User Interface Usability - 
The user interface should be intuitive, responsive, and accessible, providing a seamless user experience.

•	4.2.4 Expected Result
Some expected results include:
1.	T01: Salary Prediction Accuracy - 
The system's salary predictions should be within a certain margin of error when compared to the actual salary data. 

2.	T02: Data Source Reliability -
 Data cleaning and preprocessing procedures should eliminate data inconsistencies, resulting in high-quality data. 
 
3.	T03: User Interface Usability - 
Users should be able to navigate and interact with the user interface without encountering usability issues. These well-defined test cases and their associated conditions and expected outcomes are pivotal in validating the system's performance and reliability. By adhering to this plan, the project can confidently move forward and provide users with accurate and dependable salary predictions and data exploration capabilities.

###4.3 Quality Assurance
•	4.3.1 Purpose
Quality assurance in the "WORTHIFY.ME" project involves adhering to established certifications and guidelines that govern best practices and quality standards. 
•	4.3.2 Scope
The QA system will be used by the QA team in the project to manage, execute, and report on testing activities throughout the software development lifecycle.
•	4.3.3 Reference Components
o	GDPR Compliance:
 In terms of data privacy and security, the project adheres to the General Data Protection Regulation (GDPR) guidelines. GDPR compliance ensures that user data is handled responsibly and that stringent privacy protections are in place. 

o	Software Development Best Practices:
 Quality assurance encompasses software development best practices, such as code review processes, version control, and continuous integration. These practices ensure that the software component of the project is developed and maintained to the standard.

o	Usability and Accessibility Guidelines: 
The user interface design is in accordance with usability and accessibility guidelines to provide an optimal user experience. Guidelines such as WCAG (Web Content Accessibility Guidelines) are followed to ensure that the user interface is accessible to a broad range of users, including those with disabilities.

o	Testing and Verification Standards:
The project employs testing standards outlined by ISO and IEEE for quality assurance and verification. This ensures that the testing processes are systematic and reliable.
o	Data Quality Control: 
Quality assurance measures include stringent data quality control processes. These processes are essential in maintaining the integrity and reliability of the data used in the "WORTHIFY.ME" project. Data is subject to thorough validation, cleaning, and preprocessing to eliminate inconsistencies and errors. 

o	Project Review and Evaluation: 
Quality assurance is an ongoing process that includes regular project review and evaluation. This ensures that the project aligns with predefined quality standards and that any deviations are addressed promptly. 

o	Quality assurance in the "WORTHIFY.ME: 
Salary Predictor" project is not just a one-time effort but an integral part of project management and development. By adhering to these certifications and guidelines, the project maintains a high standard of quality, ensuring user data security, accurate salary predictions, and a seamless user experience. This concludes the section on quality assurance, which is fundamental in ensuring that the "WORTHIFY.ME: Salary Predictor" project operates at the highest level of excellence and reliability.




