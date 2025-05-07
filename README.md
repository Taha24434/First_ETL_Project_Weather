# First_ETL_Project_Weather
Extracting Weather data and storing information for further analysis (Automated)

This is broken down into multiple steps
1- create a .log file and a shell script using touch
$touch rx_poc.log ; touch rx_poc.sh
it is important to add the command '#! /bin/bash' to the begining of the .sh file
2- create a variable to store the name of the city we want to extract the temperature for
City=Casablanca
$curl -s wttr.in/$city?T --output weather_reporrt

# the rx_poc.log file will be used to store data extracted from the website "www.wttn.in"
# headers will be added under which the year, month, day, observed temperature, and forecasted temperature are stored
in the shell prompt this can be done using:
