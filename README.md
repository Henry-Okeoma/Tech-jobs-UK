WEBSCRAPPING OF TECHNOLOGY JOBS & ANALYSIS IN THE UK.
This project was a collaborative effort involving a team comprising Business Analysts, Data Engineers, and Data Scientists. Here's an overview of the project's phases and challenges encountered:

The project commenced with team meetings where Business Analysts conducted requirements elicitation to understand the project's business objectives, scope, assumptions, and potential risks. This crucial phase involved gathering insights from key stakeholders.

Data Engineers took charge of identifying suitable job sites for web scraping, focusing on platforms where data collection was feasible.

Web scraping activities were carried out across various job sites, and the harvested data was consolidated within a PostgreSQL database.

Subsequently, Data Scientists imported the data from the PostgreSQL database into Jupyter Notebook for in-depth data analysis.

Challenges Encountered During Web Scraping and Data Analysis:
Incomplete Job Role Information: Many job listings lacked essential requirements and details.

Challenges in Web Scraping: - Several job sites posed difficulties in data extraction, potentially due to site structures or restrictions.

Data Integrity and Consistency: Issues arose regarding data integrity, inconsistencies, and variations in data quality.

Missing Values and Irrelevant Tech Roles: Some data points contained missing values, and certain job listings were unrelated to the project's objectives.

Non-Numeric Salary Representation: The salary feature contained non-numeric strings.

Special Characters in Data: Special characters within the data posed challenges during analysis and processing.

Project Details:
Business Analysts played a pivotal role in guiding the project, facilitating team meetings, and maintaining documentation through tools like Jira. Each team member actively participated in updating Jira with progress on their assigned tasks.

Initial data scraping efforts yielded unsuitable data. After extensive discussions, Data Engineers revisited the web scraping process to acquire additional data for consolidation.

Regular project meetings were conducted to monitor progress and gather feedback from stakeholders, ensuring alignment with project objectives.

To overcome challenges, particularly those related to job titles, Data Scientists applied 'IF' functions to filter and rename job titles effectively.

Comprehensive data cleaning and preprocessing measures were implemented to ensure the quality of the data and prevent the "garbage in, garbage out" scenario.

Data mining activities focused on uncovering relationships and insights within the dataset, enabling the team to derive valuable information from the collected data.
