## 📊 SQL Project: Movie Database Query Collection

Welcome to the **SQL Movie Database Queries** repository! This project contains a wide range of SQL queries written for practicing and mastering SQL on a sample **Movie Database**. It covers everything from basic SELECT statements to advanced subqueries, joins, common table expressions (CTEs), and performance analytics.

---

### 📁 Dataset Tables Used:

* `MOVIES` – Contains movie metadata like title, studio, industry, release year, IMDB rating, etc.
* `FINANCIALS` – Contains financial data such as budget, revenue, profit, currency, and unit.
* `ACTORS` – Contains actor details including name and birth year.
* `MOVIE_ACTOR` – Mapping between movies and actors.
* `LANGUAGES` – Contains supported languages for movies.

---

### 🧠 Topics Covered:

#### 🔹 **Basic Queries**

* Bollywood vs Hollywood movie filtering
* Search by title (e.g. THOR, AVENGERS)
* Ratings filters (e.g. > 9, BETWEEN 6 AND 8)
* NULL and NOT NULL checks

#### 🔹 **Aggregation & Grouping**

* Count of movies by industry and year
* Grouping movies by release year with conditions
* Distinct values (e.g. studios, industries)

#### 🔹 **Sorting & Limiting**

* Top-N queries (e.g. Top 5 Bollywood movies by IMDB rating)
* Offset queries (e.g. 2nd highest-rated movie)
* Order by release year or revenue

#### 🔹 **Joins**

* INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN
* Join across 2 or more tables (e.g. movies + financials + languages)

#### 🔹 **Subqueries**

* Scalar subqueries (e.g. average IMDB rating)
* Correlated subqueries (e.g. count of movies per actor)
* IN, ANY, ALL operators
* Movies with rating greater than all Marvel movies

#### 🔹 **CTEs (Common Table Expressions)**

* Filter actors by age
* Calculate profit using CTEs
* Extract high-profit Hollywood movies released after 2000

#### 🔹 **Advanced Concepts**

* Calculating percentage profit
* Using `CASE` to normalize units (e.g. converting to millions)
* Grouping movies by actor and generating lists with `GROUP_CONCAT`
* Extracting 6th highest rating using `LIMIT OFFSET`
* Union queries for oldest and youngest actors

---

### ✅ Sample Highlights:

* **Query #39**: Movie-level financial report with calculated profit
* **Query #42**: Profit normalization using CASE (handling thousands, billions, etc.)
* **Query #44**: Actor movie list and count using GROUP\_CONCAT
* **Query #57**: Profit % filter + rating comparison with subqueries
* **Query #60**: Youngest & oldest actors using UNION

---

### 📚 Useful Concepts Practiced

* Filtering with `WHERE`, `LIKE`, `IN`, `BETWEEN`
* Aggregation with `COUNT`, `AVG`, `MAX`, `MIN`, `STDDEV`
* Table joins and foreign key logic
* CTEs and subqueries
* Formatting and reporting

---


