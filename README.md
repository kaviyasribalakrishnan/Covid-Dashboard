# Welcome to covid Dashboard
  
This application fetches the covid related data from **Twitter** and other websites.  
      	1.	**District wise Covid cases** count is fetched from an **api** and 		   extracted for particular number of days (**date_from**, **date_to can** be used to change  the user defined time frame)  
	      2. **Resources** for covid ie. Oxygen,remdesivir,plasma and other medicines are **fetched** from **twitter using twitter api**  
	      3. **Helpline** numbers for each region is fetched for a website and stored as csv which is then merged with **district wise covid cases** count  
	      4. All the resources contacts for covid is merged with district wise data  
	      5. **Percentage growth** for city wise, state wise and overall country wise is calculated.  
  

## Requirements

        1. Python ide (py version 3.9.1)  
        2. Twitter api Access keys and secret keys  
        3. tweepy package  
        4. pandas package  
        5. geotext package  
  For more details refer requirements.txt

## Execution :

        1. Run the main.py file - this is the main file that contains the link to Dashboard and functions files  
        2. user can change the path to store the csv file as user need.  
        3. conf.py - user can change the values of the variables as required by the user.  
        4. Functions.py - contains the functions that is executed from covid_Dashboard class  
        5. Covid Dashboard.py - Once the runs the project the main function will call the Covid_Dashboard class and functions are executed
