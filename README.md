# 📄 A brief introduction to the data

The data is from the IMDb website, a website that has a record of every movie or series. The data contains the top 250 movies, every movie has info such as title, rate, release year, and certification. You can take a look at the IMDb page [here](https://www.imdb.com/chart/top/).

# 🛠 Used Tools

I used Power BI to analyze and visualize the data. I imported the data with Power BI through the get data from the web feature. We can use it from (Home >> Get Data >> Web). This feature allows you to import data from a web page.
![import data from a web page feature](https://github.com/user-attachments/assets/7fd9ede5-88d5-461a-bb10-46f964611e8f)

# 📅 The data in Power BI

I did the ETL process through Power Query. We can see the final form of the data in the Table View tab.
![the data in table view](https://github.com/user-attachments/assets/c28754d1-0124-4129-9309-e7e169de3ab0)

# 📊 Dashboard

As we can see, the dashboard view is eye-friendly and very related to the IMDb website.
![dashboard](https://github.com/user-attachments/assets/7857c775-e8dd-4515-9ab5-1f94746e6422)

# 🧮 Some Measures

![Measures](https://github.com/user-attachments/assets/3316df18-4f7f-479f-b50c-7bff907f1408)

**Count of Movies:** 250 <br>
**Minimum Rating:** 8/10 <br>
**Average Rating:** 8.31/10 <br>
**Maximum Rating:** 9.30/10 <br>

# 📈 Count of Movies through the years

I used a **Bar Chart**. I know that a common chart with a time series is a **Line Chart** but it looks clearer with a **Bar Chart**.

![Count of Movies through the years - bar chart](https://github.com/user-attachments/assets/dd94166e-a882-4ddc-ad90-dd27d17b5acb)

It seems that the 2000s have the highest number of top movies. But on the year level, the 1995 year has the highest number of top movies with 8 movies.

![the 1995 year has the highest number of top movies](https://github.com/user-attachments/assets/05333291-fe26-41e2-b7e3-b45302f254a5)

# 🗃 Movies Certifications

I used a **Treemap** to visualize this kind of categorical data. We can use a **Pie Chart** but a **Treemap** seems clearer with more than 4 types of certifications. I found out that the most common certification is **R** with 103 movies.
![image](https://github.com/user-attachments/assets/3f273aca-dd95-4a4b-8213-ba4056637231)

# 🔎 Movies with Details

I used a **Table** to show movies with their details. <br>
![image](https://github.com/user-attachments/assets/9484be55-8fca-433c-aaee-76996fdf7d22)

Let's try to select a specific year from the **Bar Chart** of **Count of Movies By Year** to see the year movies details.
![image](https://github.com/user-attachments/assets/4f1fea32-9487-4497-af3d-a64a694a7f5d)
As we can see, I selected the 2004 year for example. The **Table** shows the movies that were released this year with their details. The top movie is **Eternal Sunshine of the Spotless Mind**, It has **R** certification and got **8.30/10** Rate. <br>
From the dashboard measures, the 2004 year has 7 of the top 250 movies, the minimum rating is 8, the average rating is 8.14 and the maximum rating is 8.30. 3 of the top 7 movies that year have **R** certification, 2 of the 7 have **PG-13** certification and 2 of the 7 have **PG** certification.

# 🖼 Overall

We can use this dashboard to choose a good movie to watch at the weekend 😁.
