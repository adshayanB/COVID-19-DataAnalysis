# COVID-19 Analysis Project
This project harnesses John Hopkins Univeristy Covid-19 Data (Updated Daily).<br/>
Data can be found here: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series <br/>
Other data sources used in this project are saved as csv and stored in the repo <br/><br/>
This project is broken into three parts:<br/>
       &nbsp;&nbsp;&nbsp;  1. COVID -19 Data Analysis<br/>
       &nbsp;&nbsp;&nbsp;  2. COVID -19 Dashboard<br/>
       &nbsp;&nbsp;&nbsp;  3. Cases/Deaths Prediction (Machine Learning)<br/><br/>
Frameworks/Technologies Used: Pandas, NumPy, Prophet, Matplotlib, Plotly, Viola
     
## COVID-19 Data Analysis 
Used Pandas, Plotly and Matplotlib to anaylze Canadian and Worldwide Covid Data <br/>

Key Features:<br/>
       &nbsp;&nbsp;&nbsp;  1. Confrimed Cases in Canada<br/>
       &nbsp;&nbsp;&nbsp;  2. Confirmed Cases by Province/Territory<br/>
       &nbsp;&nbsp;&nbsp;  3. Interactive World Map of Confirmed Cases <br/>
      Other Features Include - List of Total Cases Per Province/Territory,  Confrimed Cases Per Province/Territory, Interactive World Map of Cases Per 1M people
      


## COVID-19 Dashboard
This dashboard consists of interactive plots where you can query for various country data built using Pandas, NumPy, Prophet, Follium, Plotly and Matplotlib
Used Facebook's Prophet to forecast growth using Johns Hopkins time series data. <br/>
Key Features:<br/>
       &nbsp;&nbsp;&nbsp;  1. Interactive Graph that plots top n (an integer) worse hit country<br/>
       &nbsp;&nbsp;&nbsp;  2. Interactive Graph that plots cases vs deaths for desired country<br/>
       &nbsp;&nbsp;&nbsp;  3. Interactive World Map of Confirmed Cases <br/>
       &nbsp;&nbsp;&nbsp;  4. A machine learning model that predicts future cases & deaths and subsequently plots the predicted data <br/>
      


# To view the dashboard on your local machine:
Clone the Repo and install the required libraries.
Then run voila COVID-19 Dashboard.ipynb --strip_sources =True --theme=dark in your terminal.

