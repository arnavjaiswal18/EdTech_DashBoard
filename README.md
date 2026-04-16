# 🎓 EdTech Online Courses Analysis

A comprehensive Power BI analysis project focused on understanding viewership trends, course popularity, and instructor performance in the online education sector.

## 📊 Dashboard Overview

The project features a multi-faceted dashboard designed to provide actionable insights into the online learning ecosystem. It analyzes key metrics such as coarse type popularity, language distribution, and the impact of course duration on viewership.

### Key Visuals & Insights

- **Course Type Popularity**: A comparative analysis of individual courses versus specialized programs.
- **Skill Demand**: A word cloud visualizing high-demand skills like Python, Machine Learning, and Data Science.
- **Global Language Trends**: Breakdown of primary course languages, highlighting the dominance of English-language content.
- **Viewership Correlates**: 
    - **Subtitle Count**: Demonstrates the positive impact of multilingual accessibility on viewer numbers.
    - **Lecture Duration**: Analyzes the relationship between time commitment and audience engagement.
- **Instructor Performance**: Evaluation of instructors based on student ratings and average viewership.

## 🏗️ Data Model

The analysis is built upon a relational data model that optimizes performance and enables deep-dive filtering.

### Tables
1. **`Teachers`**: Stores metadata about instructors, including their categories, ratings, and sub-categories.
2. **`Online_Courses`**: Contains detailed course metrics such as duration (in hours), subtitle counts, skill counts, and language.

### Relationship
- The model implements a **One-to-Many relationship** between instructors and their respective courses, allowing for granular analysis of performance across different teaching categories.

---
*Created as part of the EdTech Data Analytics Initiative.*


---
*Created as part of the EdTech Data Analytics Initiative.*
