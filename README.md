# Stock Portfolio Dashboard with Dash

This project takes a Thinkorswim data export and turns it into a Dash Dashboard. <br>
The columns in the **monitor > Activity and Positions** table in Thinkorswim need to match the screenshot. 
There are 3 excel exports included in the repo you can use to run this project. 

This repo has 5 files
1. PortfolioAnalysisPlotly.ipynb: This notebook is the official notebook you will need to run the project
2. PA_Dev.ipynb: Development/Scrap notebook that was left as an FYI
3. yyyy-mm-dd-PositionStatement.csv (X3): ThinkorSwim export files that are used to create the dashboard

Useful Resources: 

[Simple Dashboard with Plotly and Dash](https://towardsdatascience.com/create-a-simple-dashboard-with-plotly-dash-8f385ba1dd6d) <br>
[Dash Documentation on Tabs](https://dash.plotly.com/dash-core-components/tabs) <br>
[SP500 Sector Weights](https://www.spglobal.com/spdji/en/indices/equity/sp-500/#data)  <br>
[Creating subplots on Dash](https://community.plotly.com/t/solved-how-to-create-subplots-using-plotly-express/52418)


## High Level Architecture
![ThinkorswimDash](https://user-images.githubusercontent.com/53913862/204049273-37558f92-8aae-42ab-b0f7-6723bf23f690.png)

## Thinkorswim export view
![image](https://user-images.githubusercontent.com/53913862/204049237-b5a4cf27-a592-4e24-9524-8a799a5d34cf.png)


