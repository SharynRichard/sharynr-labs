# Lab: AI in Data - Build a United Nations Precipitation Data Dashboard with IBM Bob

This video shows you how to use IBM Bob to build an interactive United Nations precipitation data dashboard.

Analyzing global environmental data often requires turning raw, multi-year statistical records into intuitive, interactive visualizations. In this lab, you explore historical annual precipitation reported to the United Nations for 125 countries and territories over a 23-year period. You will build a modular Python web application featuring statistical trend modeling, mutual-exclusion filters, and dynamic multi-chart analytics using Panel, pandas, and Matplotlib — all without writing code by hand. IBM Bob handles the coding and architecture while you focus on data insights and application requirements.

To complete this lab, you need to sign up for an IBM Bob trial account. If you don't have a trial account, watch the Get started with IBM Bob video, and then follow the steps to sign up.

Choose a folder location for the lab work. In Bob, open a terminal window and change directory into that folder. Then execute the commands to create a project subfolder. Download the Precipitation CSV file into the new subfolder. When that's done, open the ai-in-data-precipitation folder in Bob.

Before you can build the dashboard, you need to create an isolated Python virtual environment and install the required data analysis and visualization libraries: Panel, pandas, NumPy, and Matplotlib. Prompt Bob to create the requirements text file and git ignore files, set up the virtual environment, install the dependencies, and verify that all packages import cleanly.

Now you are ready to create the shell application. This task prompts Bob to initialize Panel, construct two placeholder tabs for Data Explorer and Charts, assemble them into a top-level column with a title heading, and mark the layout servable. When Bob is done, start the Panel development server in the terminal to view the running shell application.

In this task, you prompt Bob to create the data processing python script to centralize all data loading, row-wise aggregation, linear trend slope computation, and helper query functions. When Bob is done, view the results to confirm the DataFrame shape of 125 rows by 25 columns, 61 negative-trend countries, and the top-5 country rankings.

Now you build the python script for the Data Explorer tab, and wire it into the application. This task prompts Bob to create an interactive data table with country search, year-based sorting and column filtering with mutual-exclusion logic, a toggle for negative-trend countries, and a statistics summary sidebar. When Bob is done, switch to the browser to test the reactive filtering and sorting. Type a name to filter by country, sort by year, filter by year, and show only countries with a negative trend.

In this task, you prompt Bob to write a python script to create charts containing four pure Matplotlib chart functions: a single-country annual bar chart, a top-5 23-year comparative line chart, a top-5 percentage share pie chart with an Other slice, and a single-country linear regression trend plot. Each function standardizes figure dimensions and manages memory cleanly. When Bob is done, view the results to confirm the functions return Matplotlib panes.

With the charting functions ready, you update the application to replace the Charts tab placeholder with an interactive visual analytics dashboard. This task prompts Bob to assemble static top-5 line and pie charts on the top row, a country selection dropdown, and reactive single-country bar and trend charts on the bottom row using Panel bind. When Bob is done, switch to your browser to view the updated Charts tab. The two charts on the top are static, and you can select different countries for the bottom two charts to inspect their annual trends.

The final task enhances the dashboard with presentation styling and layout polish. This task prompts Bob to configure the Fast design theme, inject custom CSS for bold, full-width responsive tab headers, add a descriptive subtitle, set minimum row heights on charts to prevent layout shift, and apply explicit contrast colors to the Data Explorer table. When Bob is done, refresh the browser to explore the stylistic changes to the completed dashboard.

In this lab, you built an interactive, modular data dashboard that explores United Nations precipitation data across 125 countries and territories. You used IBM Bob to implement data loading, linear regression trend modeling, mutual-exclusion filtering, and dynamic multi-view charts without writing boilerplate code by hand. Refer to the lab guide for complete details.