# E-commerce-database-management
Creating a database and a management system for a E-commerce company using R, SQL, GITHub

Overview

This extensive project is designed to simulate a real-world e-commerce data environment. You will engage in end-to-end data management, from database design to data analysis and reporting. The
project involves using SQLite for database management, GitHub Actions for automation, and Quarto with R for data analysis and reporting.

Objectives
• Develop a thorough understanding of relational database design and management.
• Gain proficiency in automating data-related tasks with GitHub Actions.
• Enhance skills in data analysis and report generation using R and Quarto.

Part 1: Database Design and Implementation (30%)

Task 1.1: E-R Diagram Design
• Objective: Design a detailed Entity-Relationship (E-R) diagram for an e-commerce database. You can try to replicate the workflow of any e-commerce store that you have used and
understand the workflows involved.
• Suggested Entities: Products, Customers, Orders, Order Details, Transactions, Suppliers, Categories, Ads.
• Relationships: Include one-to-many, many-to-many relationships, self-referencing relationships, and any necessary associative entities by thinking of the processes involved in an e-commerce transaction.
• Deliverable: A database diagram should with the Chen notation that clearly indicates primary keys, foreign keys, and cardinalities. All assumptions should be stated and provided as text. Relationships are expected to be shown using relationship sets.

Task 1.2: SQL Database Schema Creation
• Objective: Translate the E-R diagram into a functional SQL database schema.
• Requirements: Create tables with appropriate data types, constraints, primary and foreign keys. Index essential columns for performance optimization. Explain how you derived the physical schema of the database for each table that you are going to create.
• Normalization: Ensure the schema is normalized up to at least 3NF to eliminate data redundancy.

Part 2: Data Generation and Management (25%)

Task 2.1: Synthetic Data Generation
• Objective: Generate synthetic data that realistically simulates an e-commerce environment.
• Requirements: Use R to generate data. Ensure data for entities like Customers and Orders reflects realistic patterns and distributions. You can use an LLM to provide you pathways to generate data based on the description of your entity. Provide full prompt sequence.

Task 2.2: Data Import and Quality Assurance
• Objective: Populate your SQL database with generated data and ensure data quality.
• Requirements: Script the data import process. Implement checks for data quality and integrity, such as validation of email formats, checking for duplicate entries, and ensuring referential integrity.

Part 3: Data Pipeline Generation (25%)

Task 3.1: GitHub Repository and Workflow Setup
• Objective: Show how you used a GitHub repository to manage and version-control your project.
• Requirements: Include your database file, scripts, and any other necessary documents as part of the repo.

Task 3.2: GitHub Actions for Continuous Integration
• Objective: Automate data validation, database updates, and basic data analysis tasks using GitHub Actions.
• Requirements: Set up workflows that trigger on specific events like push or pull requests. Implement actions that perform tasks like running data validation scripts, updating the database with new data, and automatically running basic data analysis scripts.

Part 4: Data Analysis and Reporting with Quarto in R (20%)

Task 4.1: Advanced Data Analysis in R
• Objective: Conduct advanced data analysis on your e-commerce data.
• Analysis Areas: Graphs related with any quantitative insight that should be time dependent and can be updated using the data pipeline.
• Requirements: Use R packages like dplyr, ggplot2, and tidyr for data manipulation and visualization.

Task 4.2: Comprehensive Reporting with Quarto
• Objective: Create an in-depth report presenting your data analysis findings.
• Requirements: Your report should include data visualizations and any other statistical insights with clear narratives explaining the implications of your findings. The report should be in a format suitable for non-technical stakeholders.



