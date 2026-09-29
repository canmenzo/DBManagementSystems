# 🗃️ DB Management Systems

[![license](https://img.shields.io/github/license/canmenzo/DBManagementSystems)](LICENSE) ![coursework](https://img.shields.io/badge/coursework-archived-lightgrey) ![database](https://img.shields.io/badge/database-MySQL-4479A1?logo=mysql&logoColor=white)

Archived coursework: assignments and projects by Mehmet Can Ozmen for LIS5782 Database Management Systems at Florida State University (fall 2022). Covers modeling an organization's entities, attributes, relationships and constraints, building the database, and writing SQL against it. Mostly Word documents, with a few SQL and model files.

### ✨ What's in it
- 🧩 `practice task 1`, `practice task 2`, `pt4`, `pt5.docx`, `PT 6.docx`: entity and attribute analysis, ER diagrams and normalization exercises
- 🔎 `Practice Task 7*.docx`, `Practice Task 8.docx`: SQL queries, including joins and subqueries
- 🏗️ `Project 1.docx`, `Project1.graphml`, `Project 2.docx`: ER model of the case study and its relations in 3NF
- 🛠️ `project 3/`: MySQL Workbench model (`.mwb`), the source data (`.xlsx`) and the query script (`OzmenMehmetQuery.sql`)
- ✈️ `project 4/`: an air transport database (aircraft, carriers, routes, cities and more) as a MySQL/MariaDB dump, with a data dictionary and write-up

### 🚀 Opening it
- Open the `.docx` files in Word or LibreOffice, `Project1.graphml` in yEd, and the `.mwb` file in MySQL Workbench.
- Load the project 4 dump into MySQL or MariaDB. It starts with `use ozmenmehmet;`, so create that database first (or edit the line), then run `mysql -u <user> -p < "project 4/AirTransport P4.sql"`.

### 📄 License
MIT
