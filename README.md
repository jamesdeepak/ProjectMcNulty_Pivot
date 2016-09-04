# Project McNulty

#### Team 1 (Deepak Gautam, Justin Chien, Saniya Jesupaul and Jeff Coggshall)

## Pivot: Change the way you see companies

Pivot is an app for prospective venture capitalist/investors who are planning to invest in a new startup. Our app basically lets the user input current charecteristics of the startup they are trying to invest in and help them see the success prediction for that company. 

Our Output gives recommendation in the two different ways:
    1) Probability of each Outcome for the company in future 
        i)   Close/Bankrupt/Dissolve
        ii)  Operational
        iii) Acquired
        iv)  IPO
    2) A numerical Score/Rating between 1-100 
       (if company is 100% predicted to go to IPO then score = 100
        if company is 100% predicted to go Bankrupt/Dissolve then score = 0 
       )
    
Our app is in the initial phase, so we let the user choose only information such as Total Investment in the start up until this point, Time between startup's Start Date and its first investment, Time Between first and last investment, Types of VCs who have invested in the startups in the past (We do this by VC Tier as of 2015) etc. For now, We either set fixed values for other information of the start up or give median values (esp. for glassdoor ratings). We already have a system built up which takes the actual values for the start up, however, for the demo flask purposes we are allowing user to input only few variables. 

#### Tools Used
    sci-kit learn 
    flask
    d3 
    Sql
    BeautifulSoup

#### Data Sources
    Glassdoor
    Angel List
    CrunchBase 
    Wikipedia
    Forbes
    

