# International-Movie-Datawarehouse

Amongst so many lessons we have been learning during the pandemic, we mastered an impressive data architecture and business intelligence project. This project challenged us to process and integrate data coming in from a variety of sources - IMDb data, movie rating data from MovieLens, and The Numbers data. We utilized multiple features of the Talend and SQL server to optimize the complete ETL process

We then visualized the integrated data from our dimensional model in Tableau and PowerBI dashboards showcasing some core KPIs and metrics.

This project helped us understand the various challenges faced while building data integration pipelines and business intelligence applications. I wish to thank my teammates Johail Sherieff and Yash Lekhwani for collaborating with me while I prepare myself for a unique data journey.

To setup this project install the following softwares 

Talend Real-Time Data Platform 7.1

SQL server Developer Edition

Microsoft SQL server Management Studio

Tableau

PowerBI

Data is made publicly available by IMDB

1. Run following script in SSMS to setup the staging database
    
    The Number - stage tables.sql	
    
    stg imdb tables - core tables.sql	
    
    stg imdb tables expanded part 2.sql
    
    stg_ml_tables.sql
 
2. Open Talend and setup your database connections and input file connections

3. When the connections are successfull run the main job


Tableau Dashboards - 

https://public.tableau.com/profile/yash6973#!/vizhome/BoxOfficeAnalysis_1/FranchiseBoxOffice


https://public.tableau.com/profile/yash6973#!/vizhome/BoxOfficeAnalysis_2/DailyRank

https://public.tableau.com/profile/parag.bhingarkar#!/vizhome/TopCategoriesonIMDBwithratings/Dashboard1

Powerbi Report

![IMG_SS](https://github.com/ParagAB/International-Movie-Datawarehouse/blob/master/PowerBI%20SS.JPG?raw=true)

https://app.powerbi.com/reportEmbed?reportId=059f667b-ce86-4f9b-b2a4-bf75fee86414&autoAuth=true&ctid=a8eec281-aaa3-4dae-ac9b-9a398b9215e7&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXVzLW5vcnRoLWNlbnRyYWwtcmVkaXJlY3QuYW5hbHlzaXMud2luZG93cy5uZXQvIn0%3D
