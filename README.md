# Mission_to_Mars

## Overview of Challenge

This is a data analysis projects that focuses on web-scraping and data analysis for a Mission to Mars. I am helping Robin scrape, organize, analyze, and visualize the data.

This project consists of 2 technical deliverables:
* Deliverable 1: Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database. The Jupyter Notebook for Deliverable 1 can be found here: [Deliverable 1](https://github.com/Kcav18/Mission_to_Mars/blob/main/mars_data_challenge_part_1.ipynb)
* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table. The Jupyter Notebook for Deliverable 2 can be found here: [Deliverable 2](https://github.com/Kcav18/Mission_to_Mars/blob/main/mars_data_challenge_part_2.ipynb)

### The Questions and Answers that are part of Deliverable 2 are below:

1. How many months exist on Mars? **12**

2. How many Martian (and not Earth) days worth of data exist in the scraped dataset? **1867**

3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? Get the answer by averaging the minimum daily temperature of all the months. Plot the results as a bar chart. 

* **The coldest month is Month 3 with a temperature of -83.307292.**
* **The warmest month is Month 8 with a temperature of -68.382979.**

Bar Chart for Question 3 is below:

![Temperature by Month on Mars](https://github.com/Kcav18/Mission_to_Mars/blob/main/mars_temp_barchart.png)


4. Which months have the lowest and the highest atmospheric pressure on Mars? Get the answer by averaging the daily atmospheric pressure of all the months. Plot the results as a bar chart.

* **Month 6 has the lowest atmospheric pressure (745.054422).**  
* **Month 9 has the highest atmospheric pressure (913.305970).**

Bar Chart for Question 4 is below:

![Average Pressure in Each Month](https://github.com/Kcav18/Mission_to_Mars/blob/main/mars_avpressure_barchart.png)

5. About how many terrestrial (Earth) days exist in a Martian year? That is, in the time that Mars circles the Sun once, how many days elapse on Earth? Visually estimate the result by plotting the daily minimum temperature. **There are approximately 686 Earth Days in one Martian Year.**

The chart below visualizes this result by plotting the daily minimum temperature:

![Terrestrial Days in a Martian Year](https://github.com/Kcav18/Mission_to_Mars/blob/main/terrestrial_dates.png)

Export the DataFrame to a CSV file. [**The csv can be found by clicking here.**](https://github.com/Kcav18/Mission_to_Mars/blob/main/mars_temperature.csv)
