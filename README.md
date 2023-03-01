# Airline Statistics Dashboard

## Introduction

As a result of my participation in Alcon Big Data workshops, I have created a data analysis project using Tableau and Alteryx. Through these workshops, I learned how to effectively analyze large datasets and derive insights that are actionable and impactful.

For this project, I focused on analyzing Airline Carriers Dataset, using **Alteryx** for data preparation and **Tableau** for data visualization.

## Business Requirements

```
Hello,  

My name is Sally and starting from next year I will be responsible for cooperation with airlines and airports. That is why I’m interested in Airline On-Time Statistics and Delay Causes dashboard which I’m going to present to Director of the Bureau of Transportation Statistics on monthly basis. We will start with USA data, in future we would like to add China and Japan as well, so make sure, that you will add possibilities to switch country if needed.  

The main idea of dashboard is to know where and when airlines encounter delays, why and how to minimize the time of the delays. I wish to have an overview of all the airlines, but the dashboard should provide us the possibility to analyze specifically the delayed flights and perform root-cause analytics. 

On the main page I need to have an overview over all airline’s operators (carriers), and their performance over time (monthly granularity):  

I want to know the number of flights per each airline operator and here I want to see only the top 10 with a full name and code of the carrier as well. I want to know how many delays each airline operator had.  
I want to see some KPI’s about delays: 
total amount of flights and canceled, delayed flights YTD 
average delay in minutes 
the longest delay 
Pareto analysis of delayed flights delayed by over 1 hour (Running sum of flights delayed by over 1 hour with number of delayed flights by over an 1 hour, YTD)  
% of flights that had delay caused by carrier or other reason 
share of on-time arrival to delayed arrivals, and the share of causes of not on-time arrivals 
What is the day of the week with the highest numbers of delayed flights?  
What is the top 5 arrival airports with the highest percentage share between delayed flights and all flights?  
Make sure it is possible to filter by year/quarter/month, carrier, country, state, airport levels, on time/not on time arrivals. So that I have an adapted view compared to the depth of the analysis required. 

It will be my first dashboard, so I’m open to new ideas and your suggestions.  

Unfortunately, I have data for only for couple of last months. I know that the structure of the files is not the same. I will try to speak with Master Data Team lead to have it in one format. 

Best regards, 

Sally :) 

Cooperation Manager in BTS 
```

## Dashboard

<div class='tableauPlaceholder' id='viz1677705432552' style='position: relative'><noscript><a href='#'><img alt='Dashboard BTS ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Al&#47;Alcon_BTS&#47;DashboardBTS&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Alcon_BTS&#47;DashboardBTS' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Al&#47;Alcon_BTS&#47;DashboardBTS&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>     

[Tableau Public link](https://public.tableau.com/views/Alcon_BTS/DashboardBTS?:language=en-US&:display_count=n&:origin=viz_share_link)
