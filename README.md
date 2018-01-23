# Velo-PBSS-2012
8 instances are in the excel file “instance_velo.xlsx”:
The state of each station is shown in sheet Graph, including the station ID, initial inventory level and the number of docking slots of each station.
Set N as the number of stations. The TraveTime and Distance sheets are N×N matrix, which indicate the average travel time and travel distances among stations respectively.
Three vehicles with capacity are employed showing in the sheet named vehicle. The initial position at the beginning of the first repositioning period is set to the station with ID=3.
The rest sheets are original user demands obtained on 8 different days. We got 48 sets of users' demand data from the system because the system recorded the state of all stations by the time unit of half hour. So the data in the orig_user_demand sheet is a 48×N matrix, presenting user demands of N stations at each time unit in a whole day from 0:00 to 23:59. 
