---
layout: post
title:  "🎮 Exploring Video Game Ratings with the IGDB API: A Data Science Tutorial"
author: "Honghan Wang" 
description: "Explore how to collect and analyze video game ratings data using the IGDB API. This guide walks you through the steps of setting up an API, curating a custom dataset, and uncovering what factors contribute to a game’s success. Perfect for data science students and gaming enthusiasts interested in understanding the data behind high-rated games"
image: https://st5.depositphotos.com/12985790/65069/i/600/depositphotos_650690186-stock-photo-side-view-indian-player-headphones.jpg
---

# **Unveiling Trends in Video Games: Interactive Exploration with Streamlit**

## **Introduction**

The video game industry has come a long way since its early days, evolving into one of the most dynamic and innovative entertainment sectors. Every year, thousands of games are released across a wide variety of platforms and genres, each competing for the attention of players worldwide. But have you ever wondered which genres dominate the charts or how platform trends have shifted over time?

These are not just casual questions—they reflect broader patterns in consumer preferences, technological advancements, and industry strategies. However, finding answers can be tricky without the right tools. That’s where data analysis comes in.

For this project, I worked with a dataset of video games to uncover insights about trends in genres, platforms, and ratings. But instead of burying these findings in static graphs or lengthy code snippets, I took it a step further and built an **interactive Streamlit app**. Whether you’re a gaming enthusiast, developer, or data explorer, this app lets you dive into the dataset and uncover your own insights, no coding required!

---

## **About the Dataset**

Before we get into the insights, let’s take a quick look at the dataset. This curated collection of video game data contains information about thousands of games across various genres, platforms, and years. Here are some key variables included in the dataset:

| **Variable**       | **Description**                                      | **Type**       |
|---------------------|------------------------------------------------------|----------------|
| `name`             | Title of the video game                              | String         |
| `rating`           | Average user rating for the game                     | Float          |
| `platforms`        | Platforms the game is available on (e.g., PC, Xbox)  | String         |
| `genres`           | Genres the game belongs to (e.g., Action, RPG)       | String         |
| `release_date`     | Date the game was released                           | Date           |
| `year`             | Year extracted from the release date                | Integer        |

This dataset gives us a unique opportunity to analyze not just the games themselves but also broader trends across the gaming industry. For those interested in exploring the raw data, the cleaned dataset is available in my [GitHub repository](https://github.com/LucasW-BYU/Post-2-Video-Rating.git)) under the name `igdb_games_clean_data_sorted.csv`.

---

## **Motivating Questions**

The gaming industry is vast, but this project focuses on answering two key questions:
1. **Which genres are home to the top-rated games?**  
2. **How has platform popularity evolved over time?**

By tackling these questions, we can gain a better understanding of what makes certain games or platforms successful. These insights can be useful for developers, publishers, and even players curious about industry trends.

---

## **Key Insights**

### **1. Which Genres Dominate Top-Rated Games?**

Genres play a significant role in shaping a game's appeal. Some genres thrive because they offer action-packed gameplay, while others captivate audiences with immersive storytelling. Using this dataset, I explored the genres that consistently receive the highest ratings.

Here’s a sneak peek: **Action** and **RPG** games dominate the charts. Below is a bar chart showcasing the top 10 highest-rated games in the **Action** genre.

![Bar Chart of Top-Rated Action Games]({{site.url}}{{site.baseurl}}/assets/images/newplot%20(3).png)

#### **What This Tells Us**
- Titles like *Lizards Must Die* and *Grand Theft Auto V* consistently rank highly, demonstrating the universal appeal of action games.
- RPGs like *The Witcher 3* stand out for their immersive storytelling and character-driven gameplay.

This analysis highlights how certain genres cater to specific player preferences, whether it’s the adrenaline of action games or the depth of RPGs.

---

### **2. Platform Popularity Over the Years**

Platforms are the gateway to gaming. From the golden days of Nintendo and PlayStation to the rise of PC gaming, platforms have played a crucial role in defining how games are experienced. Using the dataset, I analyzed platform trends over time.

The line chart below shows how platform popularity has shifted between 2000 and 2020.

![Line Chart of Platform Popularity]({{site.url}}{{site.baseurl}}/assets/images/newplot%20(4).png)

#### **Key Observations**
- **Nintendo platforms** experienced a surge in popularity between 2010 and 2015, driven by the success of consoles like the Nintendo Switch and DS.
- **PC gaming** has seen steady growth, bolstered by platforms like Steam and advancements in hardware.
- **PlayStation and Xbox platforms** remain consistent favorites, showcasing their strong foothold in the gaming industry.

These trends provide valuable insights into how technology, accessibility, and consumer preferences drive changes in the industry.

---

## **Streamlit App: Explore the Data Yourself**

The insights shared above are just the tip of the iceberg. With so much data to explore, I wanted to create a tool that would make it easy for anyone to uncover trends. Enter the **Streamlit app**: an interactive platform that lets you filter, visualize, and analyze video game data without writing a single line of code.

### **Purpose**
The app is designed for users of all skill levels. Whether you’re a data scientist, game developer, or just someone curious about video game trends, the app lets you interact with the data in meaningful ways.

### **Features**
1. **Genre and Year Filters**:
   - Select specific genres like Action, RPG, or Simulation.
   - Narrow down your analysis to a specific year range (e.g., 2000–2020).
2. **Interactive Visualizations**:
   - **Bar Chart**: View the top-rated games for any genre you choose.
   - **Line Chart**: Explore how platform popularity trends over time.
3. **Dataset Exploration**:
   - Search and browse the dataset directly within the app.
4. **Download Option**:
   - Export the filtered dataset as a CSV file for offline use.

### **What Can You Do with the App?**
- Find the top 10 rated games in any genre.
- Analyze how the popularity of platforms like Nintendo or PC has changed over the years.
- Use filters to tailor the visualizations to your specific interests.

Ready to dive in? You can access the app [here](https://new-video-game-app-app-3pvt7xamzfk2zhh9oyznnx.streamlit.app/).

---

## **Conclusion**

This project demonstrates how data analysis can uncover valuable insights about the gaming industry. From identifying the genres that produce the top-rated games to tracking platform trends over time, the findings provide a glimpse into what makes the industry tick.

But there’s so much more to explore. What trends will you uncover? Challenge yourself to dive into the data using the Streamlit app, and feel free to share your discoveries!

For those interested in replicating or building upon this project, you can find the code and dataset in my [GitHub repository](https://github.com/LucasW-BYU/new-video-game-streamlit-app.git).

---

## **Interactive Features Recap**

Here’s a quick rundown of what the app offers:
1. **Input Widgets**: Filters for genres and year ranges.
2. **Tabs**: Separate sections for top-rated games and platform trends.
3. **Interactive Charts**: Dynamic visualizations that update based on your inputs.
4. **Expandable Dataset Table**: Dive into the filtered data for deeper exploration.
5. **Download Button**: Export data for offline analysis.

---

## **Resources**
- **App**: [Streamlit App Link](https://new-video-game-app-app-3pvt7xamzfk2zhh9oyznnx.streamlit.app/)
- **Code**: [GitHub Repository Link](#)
