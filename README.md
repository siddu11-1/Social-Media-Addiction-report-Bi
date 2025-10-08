# Social-Media-Addiction-report-Bi
This Power BI project, titled “Social Media Insights Dashboard,” focuses on analyzing engagement metrics across multiple social media platforms.
It provides an interactive way to visualize trends in followers, engagement rate, audience distribution, and performance over time.

This is my first Power BI project, created to strengthen my skills in data analytics, visualization, and storytelling through data.

🎯 Objectives

Understand how social media engagement varies across locations and time.

Identify top-performing regions or categories.

Present data-driven insights through an interactive Power BI dashboard.

🧩 Features & Insights

📈 Followers Growth Analysis – Visual representation of follower count over time.

🌍 Location Insights – Interactive location filters to explore engagement by city or region.

🥇 Top Performers Visualization – Identify which locations have the most active audience.

🧮 Custom DAX Measures – Calculate engagement rate, follower growth, and averages.

🎨 Modern Dark-Themed Design – A sleek and professional dashboard layout inspired by LinkedIn branding.

🛠️ Tools & Technologies

Microsoft Power BI Desktop

Power Query for data transformation

DAX (Data Analysis Expressions) for calculations

Visualization Types: Bar chart, Pie chart, KPI cards, Slicers, and Map visuals

📂 Dataset Information:

The dataset contains metrics related to social media accounts such as:

Location

Followers

Connections

Engagements

Time Spent

(Dataset inspired by publicly available LinkedIn or Social Media company data for learning purposes.)

🧮 Sample DAX Measures
Total Followers = SUM('SocialMediaData'[Followers])
Total Connections = SUM('SocialMediaData'[Connections])
Average Engagement = AVERAGE('SocialMediaData'[Engagements])
Engagement Rate % = DIVIDE([Average Engagement], [Total Followers], 0)

📊 Dashboard Layout

Visual Components:

Top Left: Followers over time (bar chart)

Top Right: Location-based filters (button slicers)

Center: Social media platform logo

Bottom Left: Donut chart for percentage of followers by location

Bottom Right: Dual-axis graph comparing followers and connections

Each visual dynamically updates when filters are applied — offering clear insights into audience and engagement performance.

🚀 How to Use

Download the .pbit file (Social Media.pbit) from this repository.

Open it using Power BI Desktop.

Load or connect to your dataset (CSV or Excel).

Explore the visuals interactively!

💡 Learning Outcomes

Through this project, I learned how to:

Import, clean, and model data in Power BI

Create and apply DAX measures effectively

Design professional dashboards for storytelling

Build end-to-end data analytics projects

🧠 Future Enhancements

Integrate real-time data refresh from APIs

Add KPI comparison by platform (LinkedIn, Twitter, Instagram)

Include monthly or quarterly trend visuals

Publish to Power BI Service for public sharing

🙏 Acknowledgment

This being my first Power BI project, there may be areas for improvement — I truly appreciate any feedback or suggestions to help me grow as a data analyst.

🔗 Project Links

📂 GitHub Repository: https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships/code
📸 Dashboard Screenshot: Add your Power BI dashboard image here
