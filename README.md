# Stock Portfolio Dashboard with Dash

This project takes a Thinkorswim data export and turns it into a Dash Dashboard. <br>
If you wish to run the project using your own data (not the data in the excel files in this repo), the **monitor > Activity and Positions** table in **Thinkorswim** needs to match the screenshot. <br>

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
Click on the **_book_ icon > _Export to file...** on the _Position Statement_ line to export the necessary data. Take note of the columns. They should be in that order. 
![image](https://user-images.githubusercontent.com/53913862/204095032-0433164b-d7da-4645-b0f9-2a88f615fae7.png)


