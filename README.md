# Olympics-dataanalysis
Olympics Data Analysis - 120 Years of Sporting Excellence
The "Olympics Data Analysis" project delves into 120 years of rich and diverse Olympic history, exploring the evolution of sporting excellence on the global stage. This comprehensive data analysis initiative brings together a team of passionate data scientists, sports enthusiasts, and historians to unravel the trends, triumphs, and transformations that have defined the Olympic Games.

heroku link : https://olym-b7f7dbc5ca33.herokuapp.com/

Data Loading and Preprocessing:

The project starts by importing necessary libraries such as Streamlit, Pandas, Plotly, Seaborn, and Matplotlib.
Two CSV files are read: 'athlete_events.csv' and 'noc_regions.csv', presumably containing data about Olympic athletes and country regions respectively.
A title is set for the main page using st.title.
Sidebar and User Menu:

A sidebar is created using st.sidebar for navigation and quick access to different sections.
A radio button menu (Medal tally, Overall-analysis, Country-wise analysis, Athlete-wise analysis) allows users to select the type of analysis they want to perform.
Data Display:

The original DataFrame (df) is displayed using st.dataframe.
Medal Tally Analysis:

If the user selects "Medal tally", they can select a specific year and country to view the medal tally for that combination.
The medal tally is displayed using st.table.
Overall Analysis:

If the user selects "Overall-analysis", various statistics about the Olympics are displayed, including the number of editions, host cities, sports, events, athletes, and participating nations.
Line charts are used to visualize the number of participating nations, events, athletes, and sports over different editions of the Olympics.
A heatmap is used to show the number of events in each sport over different years.
Country-wise Analysis:

If the user selects "Country-wise analysis", they can choose a specific country to analyze.
A line chart is used to display the country's medal tally over the years.
A heatmap displays the sports in which the selected country excels.
A table shows the most successful athletes from the selected country.
Athlete-wise Analysis:

If the user selects "Athlete-wise analysis", various distributions and visualizations related to athletes are displayed.
Distribution plots are created to show the age distribution of overall athletes and medalists.
Distribution plots for age are shown for gold and silver medalists in different sports.
A scatter plot compares the height and weight of athletes, colored by medal and gender.
A line chart shows the participation of men and women in the Olympics over the years.
Overall, this project seems to be a comprehensive analysis and visualization tool for exploring various aspects of Olympic data, including medal tallies, athlete performance, country participation, and more. It utilizes Streamlit to create an interactive web application that allows users to interact with and explore the data visually.
