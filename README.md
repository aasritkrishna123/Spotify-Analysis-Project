# 🎵 Spotify Listening Analytics Dashboard (Power BI Project)

This project presents an **interactive Spotify Listening Analytics Dashboard** built entirely using **Power BI** to analyze listening behavior, album consumption, artist engagement, track performance, and user listening patterns.

The dashboard transforms Spotify listening history into **actionable insights** using advanced DAX calculations, interactive visuals, dynamic filters, drill-through, drill-down, and drill-up functionality.

This project is highly relevant for **Data Analyst, Business Intelligence Analyst, Power BI Developer, and Product Analytics roles**.

---

## 🎯 Project Objectives

- Analyze **album, artist, and track listening trends**
- Compare **Latest Year (LY) vs Previous Year (PY)** performance
- Identify the **most played albums, artists, and tracks**
- Analyze listening behavior across **weekdays and weekends**
- Identify **peak listening hours and days**
- Understand the relationship between **listening time and track frequency**
- Provide detailed track-level information through an interactive grid
- Enable users to explore data using **Drill Down, Drill Up, and Drill Through**

---

## 🧩 Problem Statement

In the digital music industry, understanding listening behavior is important for identifying user preferences, engagement patterns, and content performance.

The objective of this project is to develop an **interactive Power BI dashboard** that analyzes Spotify listening history to understand how users consume albums, artists, and tracks over time.

The dashboard provides insights into **listening trends, year-over-year growth, weekday vs weekend behavior, peak listening periods, and track engagement**, helping transform raw listening history into meaningful analytical insights.

---

## 📦 Dataset / Domain Overview

The Spotify listening dataset contains detailed information about individual listening events.

Key fields include:

- `spotify_track_uri` – Unique Spotify track identifier
- `ts` – Timestamp when the track stopped playing
- `platform` – Platform used for listening
- `ms_played` – Duration for which the track was played
- `track_name` – Track name
- `artist_name` – Artist name
- `album_name` – Album name
- `reason_start` – Reason why the track started
- `reason_end` – Reason why the track stopped
- `shuffle` – Indicates whether shuffle mode was enabled
- `skipped` – Indicates whether the track was skipped

These fields were used to analyze **listening behavior, engagement, content popularity, and listening patterns**.

---

## 🧠 Dashboard Workflow

### 🔹 1. Requirement Gathering

- Analyzed the business requirements
- Identified required KPIs and analytical views
- Defined requirements for Albums, Artists, Tracks, Listening Patterns, and Details Grid

### 🔹 2. Data Understanding & Preparation

- Reviewed Spotify listening history and domain definitions
- Prepared timestamp and listening-duration fields
- Created required analytical attributes for time-based analysis
- Structured the data for album, artist, and track analysis

### 🔹 3. Data Modeling

- Created an optimized Power BI data model
- Organized fields to support interactive analysis
- Designed the model to support hierarchical navigation and detailed exploration

### 🔹 4. Advanced DAX Calculations

Developed DAX calculations for:

- Latest Year (LY)
- Previous Year (PY)
- Year-over-Year (YoY) comparison
- YoY Growth %
- Total Albums Played
- Total Artists Played
- Total Tracks Played
- Average Listening Time
- Track Frequency
- Weekday vs Weekend analysis
- Time-based listening analysis
- Top N album, artist, and track analysis

### 🔹 5. Dashboard Development

Developed multiple interactive analytical views:

- **Albums Analysis**
- **Artists Analysis**
- **Tracks Analysis**
- **Listening Patterns**
- **Details Grid**

Implemented interactive filters for:

- Year
- Platform
- Shuffle
- Skipped Status

---

## 📊 Dashboard Pages

### 🔹 1. Albums Analysis

The Albums section analyzes album listening behavior over time.

Key analysis includes:

- Total Albums Played Over Time
- Albums Played by Year
- Weekday vs Weekend Album Listening
- Top 5 Albums
- Latest Year vs Previous Year
- YoY Growth Analysis

The dashboard tracks changes in album consumption across different years and identifies the most frequently played albums.

---

### 🔹 2. Artists Analysis

The Artists section focuses on artist engagement and listening diversity.

Key analysis includes:

- Total Artists Played Over Time
- Artists Played by Year
- Weekday vs Weekend Artist Listening
- Top 5 Artists
- Latest Year vs Previous Year
- YoY Growth Analysis

This helps identify the artists that receive the highest listening engagement and how artist diversity changes over time.

---

### 🔹 3. Tracks Analysis

The Tracks section provides detailed insights into track-level listening behavior.

Key analysis includes:

- Total Tracks Played Over Time
- Tracks Played by Year
- Weekday vs Weekend Track Listening
- Top 5 Tracks
- Latest Year vs Previous Year
- YoY Growth Analysis

This view helps identify frequently played tracks and changes in track consumption over time.

---

### 🔹 4. Listening Patterns

The Listening Patterns page focuses on **when and how music is consumed**.

Key analysis includes:

- Listening Hours by Day
- Hourly Listening Heat Map
- Total Listening Activity by Hour
- Average Listening Time vs Track Frequency
- Quadrant Analysis

The scatter plot categorizes tracks into four groups:

- **High Frequency & High Listening Time** – Highly engaging tracks
- **Low Frequency & High Listening Time** – Niche but impactful tracks
- **High Frequency & Low Listening Time** – Short and frequently played tracks
- **Low Frequency & Low Listening Time** – Less popular tracks

---

### 🔹 5. Details Grid

The Details Grid provides a structured view of detailed Spotify listening information.

The grid supports:

- Album Name
- Artist Name
- Track Name
- Number of Albums
- Number of Artists
- Number of Tracks
- Milliseconds Played
- Average Listening Time

Advanced Power BI navigation features were implemented to allow users to move from summarized views into detailed underlying information.

---

## 🔍 Advanced Power BI Features

### 🔹 Drill Through

Implemented **Drill Through functionality** to allow users to move from summary-level analysis to detailed track-level information.

This enables users to investigate the underlying data behind specific albums, artists, or tracks.

### 🔹 Drill Down & Drill Up

Implemented hierarchical navigation using:

- **Drill Down**
- **Drill Up**

This allows users to move between different levels of analysis and explore listening behavior in greater detail.

### 🔹 Dynamic Filtering

Users can dynamically filter the dashboard using:

- Year
- Platform
- Shuffle
- Skipped

This provides a flexible way to analyze listening behavior based on different user and playback conditions.

---

## 📊 Key Insights (Dashboard Findings)

### 🔹 Overall Listening Overview

- The dataset contains approximately **7,907 albums, 4,112 artists, and 13,665 tracks** in the detailed analysis.
- The dashboard provides a complete view of listening activity across albums, artists, and tracks.
- Average listening time is approximately **2.14 minutes** in the detailed view.

### 🔹 Album Performance

- The latest year shows **1,802 albums played**, compared with **2,258 albums in the previous year**, representing approximately **20.19% YoY decline**.
- **The Beatles** are the leading album contributor in the Top 5 Albums analysis, with **1,987 album plays**.
- Other highly played albums include **Past Masters, Abbey Road, The Wall, and Revolver**.

### 🔹 Artist Performance

- The latest year records **1,058 artists played**, compared with **1,400 in the previous year**, representing approximately **24.43% decline**.
- **The Beatles** are the most frequently played artist, with approximately **12.9K plays**.
- Other highly engaged artists include **The Killers, John Mayer, Bob Dylan, and Paul McCartney**.

### 🔹 Track Performance

- The latest year records approximately **3,508 tracks played**, compared with **3,916 tracks in the previous year**, representing approximately **10.42% decline**.
- The Top 5 Tracks analysis identifies the most frequently played tracks based on listening frequency.
- Track-level analysis helps distinguish frequently played content from tracks with longer average listening duration.

### 🔹 Listening Time Patterns

- Listening activity is strongest during **late-night and early-morning hours**, with the highest activity visible around **12 AM and 1 AM**.
- The listening heat map highlights variations in listening behavior across different days and hours.
- Evening and late-night periods show substantial listening activity.

### 🔹 Listening Frequency vs Duration

- The scatter plot shows that tracks with higher listening frequency are concentrated around relatively short average listening durations.
- A smaller group of tracks combines **high frequency with high listening time**, representing particularly strong engagement.
- The quadrant analysis provides a useful way to distinguish highly engaging tracks from less frequently consumed content.

### 🔹 Platform & Playback Behavior

- Interactive filters for **platform, shuffle, and skipped status** allow listening behavior to be analyzed under different playback conditions.
- This makes it possible to compare listening patterns across different consumption behaviors and platforms.

---

## 💡 Business / Analytical Recommendations

### 1️⃣ Understand Listener Preferences

Use frequently played albums, artists, and tracks to identify strong content preferences and improve personalized recommendations.

### 2️⃣ Focus on High-Engagement Content

Prioritize tracks that demonstrate both **high listening frequency and high listening duration**, as these represent stronger engagement.

### 3️⃣ Leverage Listening-Time Patterns

Listening activity peaks during specific hours, particularly around late-night periods. These patterns can support better timing for personalized recommendations and engagement campaigns.

### 4️⃣ Monitor Content Diversity

The decline in the number of albums and artists between the latest and previous year can be monitored to understand whether listening behavior is becoming more concentrated around familiar content.

### 5️⃣ Use Detailed Drill-Through Analysis

The drill-through and detailed grid capabilities can help investigate individual tracks and understand the underlying factors behind listening behavior.

---

## 🛠️ Tools & Technologies Used

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Advanced DAX Calculations**
- **Data Visualization**
- **Drill Through**
- **Drill Down**
- **Drill Up**
- **Interactive Filters & Slicers**
- **Heat Map Analysis**
- **Scatter Plot & Quadrant Analysis**

---

## 📸 Dashboard Preview
![Spotify Analytics Project](https://github.com/aasritkrishna123/Logistics-Dashboard/blob/main/ChatGPT%20Image.png)

---
