# worldcup-database
A relational database project that tracks World Cup match data using PostgreSQL and Bash scripting. Built as part of the freeCodeCamp Relational Database Certification, this project stores match results, teams, and generates insightful stats using SQL queries — from top scorers to champions. ⚽📊

# 🌍 World Cup Database

This project is part of the freeCodeCamp Relational Database Certification.

It uses PostgreSQL and Bash to store and query World Cup match data from 2014 and 2018.

## 📁 Files

- `games.csv` – Match data
- `insert_data.sh` – Script to insert data into the database
- `queries.sh` – Script to query data
- `worldcup.sql` – Database dump

## 🚀 How to Use

```bash
psql -U postgres < worldcup.sql      # Recreate the database
chmod +x insert_data.sh queries.sh  # Make scripts executable
./insert_data.sh                    # Insert match and team data
./queries.sh                        # Run queries and see output
