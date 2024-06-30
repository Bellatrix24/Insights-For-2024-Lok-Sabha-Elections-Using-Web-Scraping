# Lok Sabha Election 2024 Results Analysis
This project focuses on scraping election data from the Lok Sabha Election 2024 Results website to derive insights and perform analysis.

# Table of Contents
-  Overview
-  Technologies Used
-  Setup
-  Usage
-  Insights
-  Contributing
-  License
# Overview
The Lok Sabha Election 2024 Results Analysis project aims to extract, analyze, and visualize election data from the official results website. The data is scraped using Python's BeautifulSoup and requests libraries to gather constituency-wise election results. Insights are derived from this data to understand voting patterns, candidate performance, and other relevant metrics.

# Technologies Used
Python 3
Libraries:
requests
BeautifulSoup (bs4)
pandas
matplotlib (for basic visualizations)
seaborn (for advanced visualizations)
# Setup
## Clone the repository:
`git clone https://github.com/your_username/lok-sabha-election-2024-analysis.git
cd lok-sabha-election-2024-analysis`
## Install dependencies:
`pip install requests
pip install beautifulsoup4
pip install pandas
pip install matplotlib
pip install seaborn`
## Usage
Run the main jupiter notebook to scrape data and generate insights:


Explore the generated analysis and visualizations in the output.

# Insights
1.  Last 10 Candidates by Total Votes
  -  Displays the candidates with the lowest total votes in descending order.

2.  Top 10 Candidates by Total Votes
  -  Shows the candidates with the highest total votes in descending order.

3.  Top 50 Parties by Votes
  -  Bar chart representing the total votes garnered by the top 50 parties.

4.  Constituency with Lowest Voter Turnout
  -  Identifies the constituency with the lowest total voter turnout.

5. Comparison of Postal Votes vs EVM Votes
  -  Bar chart comparing the total number of postal votes and EVM votes.

6.  Winning Candidates by State (Top 50 Parties)
  -  Counts of winning candidates from the top 50 parties across states.

7.  Average % of Votes for Different Parties (Top 50 Parties)
  -  Bar chart showing the average percentage of votes received by each party from the top 50 parties.

8.  Distribution of % of Votes Received
  -  Histogram depicting the distribution of percentage of votes received.

9.  Top 20 Least Competitive Constituencies
  -  Bar chart displaying the constituencies with the largest vote margins, indicating least competitive races.

10.  Votes for Independent Candidates (Distribution of %)
  -  Histogram showing the distribution of percentage of votes received by independent candidates.

11.  State-wise Vote Distribution for Lowest Voted Party
  -  Pie chart illustrating the distribution of votes for the party with the least votes across states.

12.  State-wise Vote Distribution for Highest Voted Party
  -  Pie chart illustrating the distribution of votes for the party with the most votes across states
# Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
