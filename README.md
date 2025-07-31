# SQL Learning Log

## Week 1: Basics & Queries (2nd July 2025)

**Topics Covered:**  
- Introduction to SQL and relational databases  
- SELECT statements and filtering with WHERE  
- Sorting results using ORDER BY  
- Basic aggregate functions: COUNT, SUM, AVG  

**What I Learned / Notes:**  
- Already comfortable with basic queries and filtering.  
- Practiced on various sample datasets.  

**Projects / Practice:**  
- Created SQL queries for employee and sales datasets.  
- Explored basic data retrieval and aggregation.


## Week 2: Joins & Advanced Filtering (7th July 2025)

**Topics Covered:**  
- INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN  
- Using aliases and subqueries  
- Filtering with IN, BETWEEN, LIKE  

**What I Learned / Notes:**  
- Confident with joining tables and writing subqueries.  
- Applied advanced filters for complex queries.

**Projects / Practice:**  
- Joined multiple tables to analyze sales by region.  
- Built nested queries to extract specific data slices.


## Week 3: Aggregations & Grouping (14th July 2025)

**Topics Covered:**  
- GROUP BY and HAVING clauses  
- Aggregate functions: COUNT, SUM, AVG, MIN, MAX  
- Combining GROUP BY with JOINs  

**What I Learned / Notes:**  
- Skilled at grouping data and filtering aggregated results.  
- Used HAVING clauses to refine grouped queries.

**Projects / Practice:**  
- Generated reports summarizing sales and employee performance.  
- Worked with grouped data on customer purchase behavior.

## Week 4: Data Manipulation & Optimization (2th July 2025)

**Topics Covered:**  
- INSERT, UPDATE, DELETE commands  
- Creating and modifying tables: CREATE, ALTER, DROP  
- Basics of indexes and query optimization  

**What I Plan to Learn / Practice:**  
- Improve skills on data modification and table management.  
- Explore query optimization and indexing strategies.  

**Projects / Practice:**  
- Plan to design small database schema and manipulate data.  
- Will experiment with indexing for performance boosts.



#  Python Basics – Data Engineer Learning Journey

##  Topics I've Learned So Far (4th July 2025):

- Variables and Data Types
- Input and Output
- Arithmetic Operations
- Conditional Statements (if/else)
- String formatting (f-strings)
- List and Dictionaries 
- If-else statements                       

## Topics I learned on 3rd July 2025:

- For loops 
- Def functions 
- OS Module 
- Practiced some tasks for the above mentioned topics (Link:https://github.com/krishna22-ops/Practice-Task)

## Topics I learned on 9th July 2025:

- Pandas {Need to practice more}
- NumPy {Need to practice more}
- Create a dataframe using list and dictionaries 
- Import a csv file and read it

## Topics I learned on 15th July 2025:

- Basic Attributes (shape, index, columns, dtypes)
- Functions (max, min, len, round, type)
- Methods (describe, info, head, tails)
- Select a single column using [] and dot(.)
- Using the dot may not work in some cases, so we have to use it as a string.

# Decided to make another SQL Project based on real world data for practice.
- Created this project to practice working with real-world-style relational data.
- Focused on analyzing BMW car sales and dealership performance.
- Includes both basic and advanced SQL queries, such as:
   - Top-selling model per dealership
   - Cars sold by BMW Premier
   - All electric cars sold
- Built using two tables: bmw_sales and dealership.
- Dataset includes fields like model, fuel type, price, mileage, year, and dealership info.
- Used MySQL for database setup and querying.
- Applied core SQL skills including:
  - JOIN, GROUP BY, HAVING, ORDER BY
  - CTEs and Window Function
- Shows how the relationship between vehicle inventory and dealership data might work in real-world scenarios.


# Took a break for a week and now back to studying 
- I took a week-long break and now I’m back to studying. During this time, I realized it might be more practical to begin with Data Engineering rather than aiming directly for a Data Scientist role for my first internship. So, I’ve decided to focus on learning the tools and skills necessary to become a data engineer.
- After browsing the internet for hours, I decided to:
   - Start learning Data Engineering basics focusing on ETL concepts.
   - Created a 4-task learning plan covering ETL, pipelines, cloud basics, and a mini project in Notion.
   - Compiled useful resources and made a PDF study guide.
   - Planning to tackle tasks step-by-step, focusing on quality over speed.

# What I learned today (29th July 2025):
- Today's plan was to learn basic concepts of ETL (Extract, Transform and Load). Used libraries like Pandas to write simple scripts.
- Learned another term called ElT (Extract, Load and Transform) which is different from ETL.
  - In ETL, the order is extract, transform and load and the transformation part happens in a processing environment
  - In ELT, the order is extract, load and transform where the transformation part happens in a warehouse or a data warehouse.
- Understood the AWS (Amazon Web Service) concepts.
  - A cloud platfrom which offering different types of services.
  - Amazon S3 (Simple Storage Service) stores objects in a bucket (like a folder and files, folder being the bucket and files being the objects)
    - It has different storage classes for cost optimization based on usage.
  - Realized that AWS supports both ETL and ELT workflows through its cloud tools, making it popular for data engineering projects.
- Next Steps:
Planning to keep improving my AWS skills and build more ETL/ELT pipelines using Python and cloud tools.

# What I learned today (31st July 2025):
- Researched AWS courses and started the AWS Skill Builder course
- Explored Cloud Computing Essentials and its core concepts
- Learned about Amazon EC2 (Elastic Compute Cloud) — how it lets you run applications and websites without needing your own hardware
- Understood Availability Zones (AZ) as groups of data centers with independent power and infrastructure
- Discovered that if one AZ goes down, others continue to operate, ensuring high availability
- Learned why AZs are important for data engineering and building fault-tolerant pipelines
- Gained insight into EC2 instances, virtual servers, and different instance types
