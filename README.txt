# SE762_Group10 Weather Reporter using UiPath
This is an RPA bot that retrives and stores the maximum and minimum temprature for a given town following day. In adddtion our RPA bot will notify users weather warnings for a specific area.


## How to run
1. Clone this repo or download the zip file.
2. Open the project in UiPath Studio. This RPA bot was created and tested on  UiPath Academic Alliance Studio version 2021.10.7. There may be unexpected errors when using other versions.
3. Install Google Chrome and its UiPath extension. Follow the instructions: https://docs.uipath.com/studio/standalone/2023.4/user-guide/extension-for-chrome
4. Open the file Weather_Reporter_Sequence.xaml for the weather aggregator
5. Open the file Weather_Warning_Sequence.xaml for the warning system
6. Click Run/Debug (ensure that the excel application is not in use before running the sequences)

A Google chrome browser will open and begin its process. Please do not interrupt the process or move the mouse during the process, otherwise, it will end the process. The process will be completed when the browser is closed.

Open data.xlsx to view data. 

## How to change configurations
- The data.xlsx is the key to changing the configurations
- sheet1 contains all the towns we want to search for (If you'd like to scrape more towns, add them to this sheet. The name should match the entry on metservice: https://www.metservice.com/towns-cities ).
- sheet2 stores all the data we have collected, e.g minimum/maximum temperature for a given town
- sheet3 contains emails for users who want to receive the weather warnings (To test out the warning bot, feel free to append your email to this sheet).
- sheet4 contains all of the regions that will be checked for weather warnings.

## Meet the team
INFOSYS300/SOFTENG762
- Aden Ing
- Angelo Tangonan
- Aryan Godhania
- Hanyong Zhang
- Kendrick Ng
- Ojas Madaan
- Sam Tian
- Stanley Wu

## Github
View the git repository here: https://github.com/OjasMadaan/SE762_Group10
