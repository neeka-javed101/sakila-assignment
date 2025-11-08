# Sakila Assignment

**Author:** Neeka Javeed  
**Date:** 2025-11-08  

---

## Description
This assignment uses the **Sakila database** to perform SQL-like queries in **R** using the `data.table` package. The tasks involve **data filtering, aggregation, joining, and visualization**. All steps are implemented in R scripts, and **Git** is used for version control.  

---

## Folder Structure
- `data/` : Contains all CSV files from the Sakila database tables (`film.csv`, `customer.csv`, `payment.csv`, etc.).  
- `scripts/` : Contains R scripts for all assignment tasks.  

 **Assignment Tasks**

1. Display films with rating "PG" and rental duration > 5 days 
   - Filters films based on rating and rental duration.  

2. Average rental rate of films grouped by rating 
   - Calculates mean rental rate for each rating category.  

3. Count total number of films in each language 
   - Aggregates films by language and shows counts.  

4. List customers’ names and their store
   - Shows full customer names and associated store IDs.  

5. Display payment amount, date, and staff member  
   - Joins `payment` and `staff` tables to display transaction details.  

6. Find films that are not rented 
   - Identifies films with no rentals by comparing `inventory` and `rental` tables.  

7. Plot top languages by film count 
   - Visualizes the top 10 languages with the most films using a bar chart.  ---

## Git Usage
- **Version Control:** All assignment files are tracked using Git.  
- **Repository:** A remote repository is hosted on GitHub for backup and sharing.  
- **Commits:** Each significant change, including adding scripts, CSV files, and this README, is committed with descriptive messages.  

Commands used:
```bash
git init
git add .
git commit -m "Initial commit: Sakila assignment with R scripts and CSVs"
git remote add origin https://github.com/neekajaved123/sakila-assignment.git
git push -u origin main

