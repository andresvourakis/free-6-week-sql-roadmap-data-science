# Free 6-Week SQL Roadmap for Data Science & Data Analytics

[![Subscribe DS Newsletter](https://img.shields.io/badge/Subscribe-DS%20Newsletter-orange)](https://tobeadatascientist.substack.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/andresvourakis/)

I created this roadmap to guide you through mastering SQL basics in just **6 weeks** (or sooner if you have the time and are motivated) for free, focusing specifically on skills essential for aspiring **Data Scientists** or **Data Analysts**.

Here is what the roadmap looks like:

- **[Week 1](#week-1-learn-the-basics-of-sql-data-retrieval):** Learn the SQL basics and how to retrieve data.
- **[Week 2](#week-2-aggregations--group-by-summarizing-data):** Master aggregations and `GROUP BY` for data summarization.
- **[Week 3](#week-3-databases--joins-combining-data-sources):** Dive into relational databases and `JOINs` to combine datasets.
- **[Week 4](#week-4-learn-window-functions-optional-advanced-topic):** Learn Window Functions for advanced data manipulation.
- **[Week 5](#week-5-learn-to-use-ctes-and-sub-queries):** Advance your skills with CTEs and sub-queries for complex queries.
- **[Weeks 6-7](#weeks-6-7-build-your-own-projects-hands-on-practice):** Build your own projects to apply everything you've learned.

### Want to really learn SQL?
Then don't just watch the tutorials and read the articles, practice every step of the way to ensure you gain a good understanding of the different concepts. You can use this [online SQL server](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) by W3Schools to practice SQL commands without needing to install anything. I also share other great [resources](#practice-sql) at the bottom of this repository.

Alright, let’s get started! 🚀

## Week 1: Learn the Basics of SQL (Data Retrieval)

Your first week is about understanding what SQL is and learning how to retrieve data from a database, which is essential for Data Science & Analytics.

- **What is SQL?** [Youtube Video](https://www.youtube.com/watch?v=zsjvFFKOm3c)
- **Install MySQL**: [Youtube Video](https://www.youtube.com/watch?v=wgRwITQHszU)
- **Basic Commands**:
  - `SELECT` & `FROM`: [Youtube Video](https://www.youtube.com/watch?v=HYD8KjPB9F8)
  - `WHERE`: [Youtube Video](https://www.youtube.com/watch?v=MARn_mssG4A)

💡 **Tip:** You can start practicing what you just learned using the [online SQL server](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) by W3Schools.

## Week 2: Aggregations & GROUP BY (Summarizing Data)

In your second week, you'll learn how to summarize data for insights using aggregation functions. This is critical for creating reports and dashboards.

- **Aggregations (COUNT, SUM, AVG, MAX, MIN)**: [Youtube Video](https://www.youtube.com/watch?v=jcoJuc5e3RE)
- **Using GROUP BY (HAVING & WHERE)**: [Youtube Video](https://www.youtube.com/watch?v=nNrgRVIzeHg)

💡 **Tip:** When working with aggregations, start with smaller datasets to avoid performance issues and make debugging easier.


## Week 3: Databases & JOINs (Combining Data Sources)

Understanding relational databases and mastering `JOINs` to combine tables is key for more complex analysis in Data Science & Analytics.

- **What is a relational database?**: [Youtube Video](https://www.youtube.com/watch?v=OqjJjpjDRLc)
- **Introduction to JOINs**:
    - [Youtube Video](https://www.youtube.com/watch?v=9URM1_2S0ho)
    - [Article](https://www.atlassian.com/data/sql/sql-join-types-explained-visually)

💡 **Tip:** Practice `JOINs` with different types of datasets to understand how they combine data. Try to visualize what the result will look like before running the query.


## Week 4: Learn Window Functions (Optional Advanced Topic)

Now that you’ve mastered the basics of combining data with `JOINs`, you can take things to the next level by learning **window functions**. These are useful for performing calculations like ranking, running totals, or moving averages across subsets of data.

✋ **Note:** This section is more advanced. If you're still getting comfortable with basic SQL, feel free to skip this for now and return later.

- **What are Window Functions?** [Youtube Video](https://www.youtube.com/watch?v=xFeOVIIRyvQ)
- **Common Window Functions**:
  - `ROW_NUMBER()`, `RANK()` and `DENSE_RANK()`: [Youtube Video](https://www.youtube.com/watch?v=rIcB4zMYMas)
  - Window Functions Cheat sheet: [Article](https://www.datacamp.com/cheat-sheet/sql-window-functions-cheat-sheet)

💡 **Tip:** Check out how [5 real examples](https://tobeadatascientist.substack.com/p/5-powerful-ways-i-use-sql-window-functions) of how I use window functions as a Data Scientist in tech

## Week 5: Learn to use CTEs and sub-queries

In week 5, you’re now ready for multi-step queries. You’re really advancing in your SQL skills at this point, and you should be proud of yourself!

- **Learn about CTEs**: [Youtube Video](https://www.youtube.com/watch?v=_SanZ41uTlw)
- **Learn about sub-queries**: [Youtube Video](https://www.youtube.com/watch?v=GpC0XyiJPEo)

💡 **Tip:** When working with CTEs and sub-queries, break your queries down into smaller parts and test them individually before combining them.

## Weeks 6-7: Build Your Own Projects (Hands-on Practice)

Now that you have the foundational skills, it's time to apply them in real-world scenarios by working on projects.

- **Start with a guided project**: [Youtube Video](https://www.youtube.com/watch?v=JaUKDbCXMX4)
- **Ideas for your own projects**:
    1. **Customer Segmentation Analysis**
        - **Objective**: Analyze customer behavior and group them into segments based on purchasing habits.
        - **Dataset**: Use an open dataset like the [UCI Online Retail dataset](https://archive.ics.uci.edu/ml/datasets/online+retail) or any e-commerce dataset.
        - **Outcome**: Create distinct customer profiles (e.g., high-spenders, occasional buyers) and generate a report to inform marketing strategies.
        - **Difficulty**: Beginner to Intermediate

    2. **Movie Recommendation System (SQL-Based)**
        - **Objective**: Build a **simple** movie recommendation system based on user ratings.
        - **Dataset**: Use the [MovieLens dataset](https://grouplens.org/datasets/movielens/), which includes user ratings for movies.
        - **Outcome**: Generate a list of recommended movies based on user preferences and ratings patterns.
        - **Difficulty**: Intermediate to Advanced

💡 **Tip:** Take time to document your projects. Writing clear descriptions of the problem you’re solving and your approach will help solidify your understanding and build your portfolio.

## Practice SQL
Here are 5 great websites where you can practice SQL and keep your skills sharp

- [SQLZoo](https://sqlzoo.net/)
- [LeetCode](https://leetcode.com/problemset/database/)
- [HackerRank](https://www.hackerrank.com/domains/sql)
- [Mode Analytics SQL Tutorial](https://mode.com/sql-tutorial/)
- [W3Schools SQL Tutorial](https://www.w3schools.com/sql/)

💡 **Tip:** If you are unsure which one to choose, the [SQL 50](https://leetcode.com/studyplan/top-sql-50/) by LeetCode is usually a great starting point.

## Additional Data Science Resources

 Here are some more resources to help you on your Data Science journey:

1. 📚 **[Data Scientist Handbook](https://github.com/andresvourakis/data-scientist-handbook)**: A curated list of resources (Free & Paid) to help data scientists learn, grow, and break into the field of data science.
2. 💌 **[To Be a Data Scientist (Newsletter)](https://tobeadatascientist.substack.com/)**: Weekly insights to break into Data Science and advance your career (**Join 2K+ Data Science already accelerating their careers**).

If you have questions or feedback send me a message through [here](https://www.linkedin.com/in/andresvourakis/). Enjoy!
