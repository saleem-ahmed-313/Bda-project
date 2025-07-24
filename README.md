# IPL Data Analysis with Apache Spark 🏏🔥

Welcome to the IPL Data Analysis project! This project uses **Apache Spark** to explore and understand data from the Indian Premier League (IPL).This project helps you find interesting insights about players, matches, and teams using big data tools.

---

## 🚀 About This Project

I work with IPL data from several CSV files, including ball-by-ball details, match info, player profiles, team details, and player performances. Using Spark’s fast processing, I analyze this data to find patterns and stories. I also create charts and graphs to make the results easy to understand.

---

## 🛠️ What You Will Find Here

- **Starting Spark:** I create a Spark session for IPL data analysis.
- **Defining Data:** I set up clear data schemas so the data loads correctly.
- **Loading IPL Data:** I read data from Amazon S3 storage.
- **Cleaning Data:** I remove invalid data like no-balls and wides to keep analysis accurate.
- **Adding New Features:** 
  - Running total of runs during matches
  - Classifying wins by big, medium, or small margin
  - Marking important deliveries (like wickets or big runs)
  - Adding player info like batting style and veteran status
- **Running SQL Queries:** Examples include:
  - Top batsmen by season 🏅
  - Best bowlers in powerplay overs 💨
  - Does winning the toss affect winning the match? ⚖️
  - Average scores at different venues and common ways players get out 📊
- **Visualizing Data:** I use Matplotlib and Seaborn to make clear and easy-to-read charts.

---

## 📦 Data Used

- **Ball_By_Ball.csv** — Ball-by-ball game details
- **Match.csv** — Match details including venue and outcome
- **Player.csv** — Player personal and playing info
- **Player_Match.csv** — Player stats for each match
- **Team.csv** — Team names and details

All data is loaded with defined data types for better accuracy and easier use.

---

## 💻 How to Use

1. Set up Spark on your computer or use a cloud service.
2. Connect to Amazon S3 where the IPL data is stored.
3. Run the PySpark scripts I have provided step by step.
4. Change queries or visualizations to answer your own questions.
5. Have fun learning cool things from the IPL data!

---

## 🙌 Ideas to Improve

Feel free to add your own analyses, use machine learning to predict matches, or explore deeper player stats. This project is open and ready for your ideas!

---

## 📬 Get in Touch

Questions, ideas, or feedback? Let’s talk cricket and data!

---

Thanks for checking out the IPL Data Analysis! 🏏💡  


---

*Made with PySpark by SALEEM AHMED
