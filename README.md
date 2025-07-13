🔗 **Project Name: Skill_Salary_Job_Insights**
🔧 Tools: ***Microsoft Excel, Power Query, PivotTables, DAX***
📅 Data Year: 2023
🎓 Role: Student 

👋** Introduction**
As a student passionate about data, I created this project to dive into the data science job market and uncover what skills matter most when it comes to salary and job roles. Inspired by *Luke Barousse’s* fantastic work, I used Excel to analyze real-world job data and build insights into what drives higher pay in the field of data.

🎓 This project was a hands-on learning experience to sharpen my skills in Power Query, PivotTables, DAX, and more—all while discovering valuable career insights!

❓** Questions I Explored**
To guide my analysis, I asked:

💼 ***Do more skills lead to better pay?

🌎 What’s the average salary for data jobs in different regions?

🧠 What are the top in-demand skills for data professionals?

💰 What is the salary impact of the top 10 most common skills?***

🧰** Excel Skills I Used**
*Skill	Description*
📊 *Pivot Tables*	Summarized complex data efficiently
📈 *Pivot Charts*	Visualized trends and comparisons
💪 *Power Pivot*	Built data models and connected tables
🔍 *Power Query*	Cleaned and transformed raw data
🧮 *DAX (Data Analysis Expressions)*	Created custom metrics like median salary

📂 **Dataset Details**
I used a dataset of **real 2023 data science jobs**—including:

👨‍💼 **Job Titles**

💰 **Salary (Yearly Avg)**

📍 **Location**

🛠️ **Required Skills**

🔗* Dataset provided via Luke Barousse’s Excel course*

🔍 1️⃣ ***Do More Skills = Higher Pay?***
Using **Power Query**, I:

Extracted job data and skill sets

Cleaned the text, removed extra spaces, and fixed column types

Then I analyzed the relationship between the number of skills listed and the average salary for each job.

💡 **Insights**
📈 Positive correlation: Jobs requiring more skills tend to pay more

👨‍🔬 Roles like Senior Data Scientist offer higher salaries due to specialized skill demands

🧾 Jobs like Business Analyst had fewer skills and lower pay

🤔 **So What?**
The more relevant skills you master, the higher your potential earning power!



🌎 2️⃣ **Salaries by Region**
Using ***PivotTables and DAX***, I calculated the median salaries across locations, especially focusing on:

`=CALCULATE(
    MEDIAN(data_jobs_all[salary_year_avg]),
    data_jobs_all[job_country] = "United States"
)`

💡 **Insights**
💼 Senior Data Engineers and Data Scientists had top salaries globally

🇺🇸 **U.S.**-based roles paid significantly more than those elsewhere

🧑‍💻 U.S. tech hubs likely drive this salary gap

🤔 ***So What?***
Location matters! Knowing regional trends helps you plan where to work or negotiate better.


🧠 3️⃣ ***Top Skills in Data Roles***
With _Power Pivot_, I joined the jobs and skills tables and built a strong data model.

💡***Insights***
💻 **SQL** and **Python** are the most in-demand skills

☁️ Skills like **AWS** and **Azure** are rising fast due to cloud adoption

📊 Data viz tools like **Tableau** and **Power BI*8 also appear often

🤔 ***So What?***
Learning popular tools like Python, SQL, and cloud platforms can help you stay competitive and job-ready.

💸 4️⃣ **Salary vs. Top 10 Skills**
I used PivotCharts to compare median salary and skill likelihood (% use) for the top 10 skills:

📊 **Clustered Columns for Salary

📈 Line Chart for Skill Likelihood (with markers)**

🤔 **So What?**
Prioritize learning high-value skills if you want to land higher-paying roles in the tech space!

🧾 ***Conclusion***
As a student diving into the world of data, this project taught me how to:

Build a clean data model

Use Excel's most powerful tools: Power Query, PivotTables, DAX

Understand how skills and location affect salary outcomes

🙏 Huge thanks to ***Luke Barousse*** for his inspiring dataset and guidance throughout this journey!




