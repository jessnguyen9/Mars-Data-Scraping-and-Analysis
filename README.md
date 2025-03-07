# Mars Data Scraping and Analysis

## Overview
This project focuses on web scraping and data analysis to gather and analyze Mars-related data. The project is divided into two main deliverables:
1. **Scraping Mars News Titles and Previews:** Automating the process of extracting news headlines and preview texts from a Mars news website to provide valuable insights on the latest discoveries and research related to Mars.
2. **Scraping and Analyzing Mars Weather Data:** Extracting and analyzing Mars weather data, including temperature and atmospheric pressure, to better understand the climate conditions on Mars. This data is used to answer key questions about Mars' months, the coldest and warmest months, and atmospheric pressure patterns.

## Tools & Techniques Used
**Splinter:** automates the browsing process, allowing us to navigate through the pages and fetch the necessary data.

**BeautifulSoup:** allows us to easily extract specific elements from a web page, such as text or table data, and transform it into a structured format that can be used for analysis.

**Pandas:** used to manipulate and analyze the scraped data. In this project, it is used for answering key questions related to the Mars weather data.

**Matplotlib:** used to plot bar charts and visually represent the analyzed data, such as the coldest and warmest months on Mars and the atmospheric pressure trends.

**Data Scraping and Cleaning:** involves extracting raw data from the websites, followed by cleaning and structuring the data for analysis. In the first deliverable, news titles and previews are stored in dictionaries, while in the second deliverable, weather data is scraped from an HTML table and organized into a list for further analysis.

## Deliverables:
**Deliverable 1: Scrape Titles and Preview Text from Mars News**
- **Objective:** Automate the process of extracting Mars news headlines and preview texts from the Mars news site.
- **Result:** A Python list containing dictionaries of the news titles and preview texts from the Mars news site.

**Deliverable 2: Scrape and Analyze Mars Weather Data**
- **Objective:** Extract and analyze Mars weather data, including temperature and atmospheric pressure, to answer various questions about Mars' climate.
- **Result:** Analysis of Mars' months, coldest and warmest months, and atmospheric pressure patterns. The data is visualized in bar charts to highlight trends in temperature and atmospheric pressure over different months.

![Average temp by month](https://github.com/user-attachments/assets/3c46afe0-ea8a-429d-a010-c571e012a695)

The data showed a significant fluctuation in temperature across Martian months:
- **Coldest Month:** The third month of Mars’ year is the coldest, with an average temperature of -83.31°C.
- **Warmest Month:** The eighth month is the warmest, with an average temperature of -68.38°C. These findings highlight the extreme temperatures experienced on Mars, even in its warmest month.

![Average pressure by month](https://github.com/user-attachments/assets/71207811-2a6f-4cf5-8f30-31e5e4f3236f)

The dataset also provided insights into atmospheric pressure:
- **Highest Pressure:** The ninth month experiences the highest atmospheric pressure.
- **Lowest Pressure:** The sixth month has the lowest atmospheric pressure. This insight is critical for understanding the seasonal variations on Mars and how these might impact surface conditions.

The analysis of Martian temperature data over Earth days revealed an interesting observation about Mars' orbit. By examining the temperature data trends, it was estimated that a Martian year is approximately 687 Earth days, confirming known information about Mars' longer orbit around the Sun compared to Earth.

## Conclusion
This project demonstrates the application of web scraping, data cleaning, and analysis techniques to uncover valuable insights about Mars’ climate. Through the use of Python libraries like Splinter, BeautifulSoup, Pandas, and Matplotlib, trends in temperature and atmospheric pressure were effectively analyzed. The findings reveal fascinating patterns of Martian weather, highlighting the extreme temperature differences and seasonal variations in atmospheric pressure, which are crucial for understanding the planet's environment.
