# 🎬 SQLflix  

SQLflix is a **quiz-based, fun problem-solving project** built with **T-SQL** on **SQL Server (SSMS)**.  
Instead of just dry queries, SQLflix challenges you with interesting **movie-themed SQL puzzles** — like *"Which actor had the most successful debut?"* or *"Which genre rules the box office?"*  

---

## 📂 Project Structure  

- **Database**: `SQLflix`  
- **Schema**: Includes 5 main tables  
  - `Movies` → Movie details (title, year, genre, etc.)  
  - `Actors` → Actor details (name, birth year, nationality)  
  - `Movie_Cast` → Many-to-many relationship between Movies & Actors (with role info)  
  - `Box_Office` → Financial data (budget, revenue)  
  - `Ratings` → User ratings & reviews  

---

## 🗄️ Database Schema (ERD)  

The schema defines relationships between movies, actors, and their box office/ratings data.  

---

## ⚙️ Setup Instructions  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Tar9922/SQLflix.git
   cd SQLflix
