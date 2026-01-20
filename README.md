# Assignment 1: Introduction to Data Visualization with UNESCO Heritage Sites
**Due Date:** January 26th, 11:55 PM

## Objective
In this assignment, you’ll get started with Tableau to explore and visualize data. Using the UNESCO World Heritage Sites (2021) dataset, you will create basic visualizations to answer specific questions and propose your own questions for further exploration. This assignment will help you practice creating simple visualizations and interpreting the results.

## Instructions

### Getting Started with Tableau
- Install [public version of Tableau](https://www.tableau.com/products/public/download), it is free (create an account using your sfu email).
- You can watch a [Tableau Tutorial](https://www.youtube.com/watch?v=9uBtK6j_QgA&ab_channel=LearnitTraining) to learn more details based on the main concepts we covered during the lab session. 
- The dataset you will be using contains columns such as site name, country, year of designation, and site category (Cultural, Natural, or Mixed). You can directly access the dataset via [this link](https://github.com/SIAT-IAT-355/A1-Tableau-Intro/blob/main/data/UNESCO_Sites_Data.csv). The dataset is also available in the Canvas Files section and on the Discord server.
- Download the dataset and open it in Tableau. Take some time to explore the Tableau interface, including drag-and-drop functionality, chart types, and the data pane.

### 1. Answer the Following Questions Using Visualizations:

#### Prompts:
1. **Country Analysis 🌎**
   - Create a simple **bar chart** to visualize the number of sites per country. Sort the chart in descending order to easily identify the country with the most designations.
   - Create a **map chart** to show the geographic distribution of all the sites. The map should be interactive, allowing users to hover over a country to view the number of sites it has.
   
2. **Site Category Analysis 🏛️🌳**
   - Create a **pie chart** that displays the distribution of site categories. The chart should clearly show the proportion of Cultural, Natural, and Mixed sites.
   - Go back to the **map chart** you created in Prompt 1. Edit the tooltip so that when you hover over a country, it not only shows the total number of sites but also the breakdown of categories within that country (e.g., "10 Cultural, 3 Natural"). This will add a deeper layer of information to your map.
   
3. **Temporal and Regional Analysis 📅**
   - Create a **line chart** that tracks the number of new site designations over time. First, you will need to derive the decade from the Date_Inscribed field. The chart should then show the trend of site designations over each decade, making it easy to identify peak periods.
   - Create a new visualization (e.g., a bar chart or table) to answer the following question: What was the total area of new site designations in each decade, broken down by region? Use the Area_Hectares field for this calculation and be mindful of any missing or invalid data.

> **Tip:** Don’t worry if this is your first time using Tableau. Focus on practicing how to build simple visualizations step by step. Ask questions on Discord :)

### 2. Reflect on Your Findings
- After you create each visualization, take a moment to describe what you observe. 
- Write a brief summary (2-3 sentences) of the patterns or insights you can identify from each chart or map. For example, you might notice which countries have the most heritage sites or trends over time.

### 3. Propose Two Questions of Your Own
- Now that you have explored the dataset, think of **two additional questions** that you can answer using Tableau.
- For each question:
  - Clearly state the question you want to explore.
  - Create a visualization to answer that question using Tableau (tip: you might create a few different map visualizations).
  - Write a brief explanation (2-3 sentences) of what your visualization shows and why it’s important or interesting.

### 4. Submission Instructions

- You need a summary document in **PDF format** to write a brief response for each visualization.
- In your summary document, please include a **screenshot or image of each visualization** and **a brief written response** summarizing your findings for each visualization.
- Place your Tableau Workbook (`.twb` or `.twbx`) and the summary document (PDF) inside a folder.
- You also need to record a short video (**no longer than 3 minutes**) explaining your findings in this project:
   - Walk through your visualizations to show your final work.
   - Explain how you created each visualization, including any challenges you encountered.
   - Describe the key insights you learned about the UNESCO World Heritage Site dataset from completing this assignment.
   - This video presentation doesn't have to be anything fancy. Just make sure you're audible.
   - **Note:** This is to ensure you've understood what you've done along the way. You might ask AI for help, but we don't want you to just copy-paste everything.
- Zip the folder and upload the zipped file to the **Assignment 1** submission page on Canvas.
- Ensure that your Tableau Workbook and summary document are correctly named as:
  - **Tableau Workbook:** `IAT355_Assignment1_FirstNameLastName.twbx`
  - **Summary Document:** `IAT355_Assignment1_FirstNameLastName.pdf`
  - **Summary Video:** `IAT355_Assignment1_FirstNameLastName.mp4` (`mp4` or any other video format)

## Some tips:
- Start simple! Focus on learning how to create basic bar charts, pie charts, and maps.
- Use Tableau’s drag-and-drop interface to experiment with different chart types.
- Don’t be afraid to explore different ways to present the data—this is your opportunity to get comfortable with Tableau.
