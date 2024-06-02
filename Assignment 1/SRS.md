# Software Requirement Specification
## Table of Contents

1. [Introduction](#1-introduction)

   1.1 [Purpose](#11-purpose)
   1.2 [Intended Audience](#12-intended-audience)
   1.3 [Intended Use](#13-intended-use)
   1.4 [Scope](#14-scope)
   1.5 [Definitions, Acronyms, and Abbreviations](#15-definitions-acronyms-and-abbreviations)
2. [Overall Description](#2-overall-description)

   2.1 [Product Perspective](#21-product-perspective)
   2.2 [Product Features](#22-product-features)
   2.3 [User Classes and Characteristics](#23-user-classes-and-characteristics)
   2.4 [Operating Environment](#24-operating-environment)
   2.5 [Design and Implementation Constraints](#25-design-and-implementation-constraints)
   2.6 [User Documentation](#26-user-documentation)
   2.7 [Assumptions and Dependencies](#27-assumptions-and-dependencies)
3. [System Features](#3-system-features)

   3.1 [Admin Features](#31-admin-features)
   3.2 [User Features](#32-user-features)
   3.3 [Content Creator Features](#33-content-creator-features)
4. [Functional Requirements](#4-functional-requirements)

   4.1 [User Interface Requirements](#41-user-interface-requirements)
   4.2 [Hardware Interface Requirements](#42-hardware-interface-requirements)
   4.3 [Software Interface Requirements](#43-software-interface-requirements)
   4.4 [Communication Interface Requirements](#44-communication-interface-requirements)
5. [Non-Functional Requirements](#5-non-functional-requirements)

   5.1 [Performance Requirements](#51-performance-requirements)
   5.2 [Safety Requirements](#52-safety-requirements)
   5.3 [Security Requirements](#53-security-requirements)
   5.4 [Software Quality Attributes](#54-software-quality-attributes)


---

## 1. Introduction

### 1.1 Purpose
The purpose of the "WORTHIFY.ME: Salary Predictor" project is to create a data-driven platform for predicting salaries and exploring salary trends based on various parameters such as country of work, education level, and years of experience. This platform aims to provide accurate and up-to-date information to help job seekers, career changers, and employers make informed decisions.

### 1.2 Intended Audience
This document is intended for:
- Developers and Engineers
- Project Managers
- Stakeholders
- QA Team
- End Users

### 1.3 Intended Use
The "WORTHIFY.ME" platform will be used to:
- Predict individual salaries based on input parameters.
- Explore salary trends across different demographics and geographies.
- Provide insights for job seekers, employers, and career advisors.

### 1.4 Scope
The scope of this project includes:
- Development of a web-based application.
- Implementation of machine learning algorithms for salary prediction.
- Creation of data visualizations to explore salary trends.
- Ensuring user-friendly interaction and accessibility on various devices.

### 1.5 Definitions, Acronyms, and Abbreviations
- **API**: Application Programming Interface
- **UI**: User Interface
- **ML**: Machine Learning
- **GDPR**: General Data Protection Regulation
- **UX**: User Experience

---

## 2. Overall Description

### 2.1 Product Perspective
The "WORTHIFY.ME: Salary Predictor" is a standalone web-based application that leverages data from the Stack Overflow Developers Survey 2023. It utilizes machine learning algorithms to provide accurate salary predictions and visualize salary trends.

### 2.2 Product Features
- **Predict Function**: Allows users to input parameters and receive salary predictions.
- **Explore Function**: Provides data visualizations of salary trends.
- **User Management**: Admin functionalities for user management and data oversight.
- **Data Security**: Ensures GDPR compliance and data privacy.

### 2.3 User Classes and Characteristics
- **Admins**: Manage users and oversee data integrity.
- **General Users**: Access prediction and exploration features.
- **Content Creators**: Add and manage content related to salary trends and career advice.

### 2.4 Operating Environment
The application will be deployed on a web server and accessible via modern web browsers on desktop and mobile devices. The system will be compatible with Windows, macOS, Linux, iOS, and Android operating systems.

### 2.5 Design and Implementation Constraints
- **Software Constraints**: Must use compatible programming languages and libraries (e.g., Python for ML, JavaScript for frontend).
- **Data Source Reliability**: Must ensure the Stack Overflow Developers Survey 2023 data is accurately cleaned and processed.
- **Hardware Constraints**: The system must be optimized for performance on standard server configurations.

### 2.6 User Documentation
User documentation will include:
- User Manuals
- FAQs
- Tutorials and Guides
- API Documentation for Developers

### 2.7 Assumptions and Dependencies
- Reliable internet connection for accessing the web application.
- Users have basic knowledge of web navigation and data entry.
- Dependencies on third-party libraries and frameworks (e.g., TensorFlow, D3.js).

---

## 3. System Features

### 3.1 Admin Features
- **User Management**: Create, update, delete, and manage user accounts.
- **Data Oversight**: Monitor and ensure data integrity and security.
- **System Configuration**: Manage system settings and configurations.

### 3.2 User Features
- **Salary Prediction**: Input personal data to receive salary predictions.
- **Explore Trends**: Access and interact with data visualizations.
- **Account Management**: Create and manage personal user accounts.

### 3.3 Content Creator Features
- **Content Creation**: Add and manage articles, guides, and resources related to salary trends and career advice.
- **Content Editing**: Update and edit existing content.
- **Content Deletion**: Remove outdated or irrelevant content.

---

## 4. Functional Requirements

### 4.1 User Interface Requirements
- **Interactive Elements**: Buttons and forms must be easily clickable on both computers and mobile devices.
- **Responsive Design**: The interface must adapt to different screen sizes and resolutions.
- **Accessibility**: Ensure the interface is accessible to users with disabilities (e.g., screen readers, keyboard navigation).

### 4.2 Hardware Interface Requirements
- **Server Specifications**: The system should run on servers with adequate CPU, memory, and storage capacities.
- **Device Compatibility**: Ensure compatibility with desktop computers, tablets, and smartphones.

### 4.3 Software Interface Requirements
- **API Integration**: The system must provide and consume APIs for data exchange.
- **Database Management**: Use a reliable database system for storing user and prediction data.
- **Authentication**: Implement secure user authentication mechanisms.

### 4.4 Communication Interface Requirements
- **Web Communication**: Ensure secure communication over HTTPS.
- **Email Notifications**: Implement email notifications for user activities and updates.

---

## 5. Non-Functional Requirements

### 5.1 Performance Requirements
- **Response Time**: The system should provide responses within 2 seconds for standard queries.
- **Scalability**: The system should handle up to 10,000 concurrent users without performance degradation.
- **Load Time**: The application should load fully within 5 seconds on a standard broadband connection.

### 5.2 Safety Requirements
- **Data Backup**: Regular backups of the database to prevent data loss.
- **Disaster Recovery**: Implement a disaster recovery plan to restore services within 24 hours.
- **Data Integrity**: Ensure data integrity through validation checks and redundancy mechanisms.

### 5.3 Security Requirements
- **Data Encryption**: Encrypt sensitive data both in transit and at rest.
- **Access Control**: Implement role-based access control to restrict sensitive operations.
- **Audit Logging**: Maintain logs of user activities for security audits.

### 5.4 Software Quality Attributes
- **Reliability**: Ensure the system operates reliably with minimal downtime.
- **Maintainability**: Code should be modular and well-documented to facilitate maintenance.
- **Usability**: The system should be user-friendly with clear navigation and help resources.
- **Portability**: The application should be portable across different environments with minimal configuration.
- **Scalability**: The system should be designed to scale horizontally to accommodate growing user base and data volume.
- **Interoperability**: Ensure the application can work with other systems and data sources through well-defined interfaces.

---
