# 🌍 World Cup Database
A relational database project that tracks World Cup match data using PostgreSQL and Bash scripting.This project stores match results, teams, and generates insightful stats using SQL queries — from top scorers to champions. ⚽📊

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
```

---
## Screen Shots
![Screenshot 2025-06-21 130949](https://github.com/user-attachments/assets/d34c494a-53c6-4d46-aa22-d254a5838b9a)


