
## 📌 Project Context

This project was inspired by a real-world business need. An HR consulting firm was struggling with a "master spreadsheet" that was difficult to maintain, prone to human error, and full of redundant data. I designed and implemented a centralized relational database to manage clients, projects, consultants, and payroll more efficiently.

## 📊 Key Achievements

* **Eliminated Data Redundancy**: Reduced data duplication by transitioning from a single flat file to a **normalized relational schema (up to 4NF)**.
* **Enhanced Scalability**: Designed a schema with **15 interconnected tables** that can handle growing numbers of clients, employees, and complex commission structures.
* **Business Logic Integration**: Implemented SQL logic to automate calculations for **Consultant Bonuses, Payroll, and Project Commissions**.

## 🛠 Tech Stack

* **Database**: MS Access / SQL (PostgreSQL compatible)
* **Modeling**: ERD (Entity-Relationship Diagram), Relational Schema Design
* **Documentation**: Normalization Analysis (1NF to 4NF), Data Dictionary

## 🔍 Database Design Highlights

1. **Normalization**: Performed a step-by-step decomposition to reach **4th Normal Form**, ensuring that non-key attributes are only dependent on the primary key and removing multi-valued dependencies.
2. **Entity Relationships**:
* Managed **Many-to-Many** relationships between Projects and Consultants through associative tables.
* Built a hierarchical structure for Clients and their specific Branch locations.


3. **Advanced Querying**: Developed complex SQL joins to generate:
* Monthly **Payroll Reports** combining Base Salary, Bonus, and Commissions.
* **Project Profitability** reports by linking time-sheets to client billing rates.



## 📂 Project Structure

* `Database_Final_Report.pdf`: Comprehensive documentation of the business rules, ERD, and normalization process.
* `SQL_Queries.sql`: DDL and DML scripts used to build and populate the database.
* `ERD_Diagram.png`: Visual representation of the database architecture.

---

### 💡 Tips for your GitHub Overview

Now that you have all three project descriptions in English, here is how you should organize them in your **Profile README** (the one that shows up on your main page):

1. **Lead with the CNN Project**: It shows high-level **Data Science/AI** skills.
2. **Follow with the HR Database**: It shows **Data Engineering/SQL** foundational skills.
3. **End with Amazon Prime**: It shows **Data Analysis/Visualization** skills.

**Next Step:** Would you like me to help you create a **"Skills" section with icons (badges)** for your main profile to make it look even more professional?
