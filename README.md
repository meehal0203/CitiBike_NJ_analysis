# New Jersey and Hoboken CitiBike Analysis

![image](https://github.com/meehal0203/CitiBike_NJ_analysis/assets/146681542/87321675-1a08-4e5a-b3b6-4f3ba6eb4249)

I have been tasked with evaluating the largest bike-sharing program in the United States and will generate regular reports for city officials looking to publicize and improve the city program, looking specifically at data regarding user ride start/ end times and ride durations. Key differences between those riders who are 'members'(pay a monthly or annual subscription and can use any bike for 45 minutes at a time) and those who are 'casual' will be highlighted. 

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process, so the first task on the job is to build a set of data reports to provide the answers. I have chosen to focus on the CitiBike data from the New Jersey area, Jersey City and Hoboken, just west of Manhattan. which has 82 stations and riders have access to over 27,000 bikes(including those in NYC).

## Pre-processing the data

The CitBike NJ Trip History Data is publicly available and I read the 12 monthly csv files for each month of 2023 into a Jupyter Notebook in order to clean and concatenate the data before performing analysis using Tableau. After checking for and cleaning missing and duplicate values, I checked the data types and discovered that several needed to be changed in order to aid analysis
![image](https://github.com/meehal0203/CitiBike_NJ_analysis/assets/146681542/cbff4a97-ea2b-46ee-a63e-03f763c5c4b0)
After merging and cleaning all datasets I was ready for analysis suing this data:

I wanted to answer the following questions:

* Which stations are the busiest for starting and ending rides?
  ![image](https://github.com/meehal0203/CitiBike_NJ_analysis/assets/146681542/4579cdc2-7fc4-4daa-989d-fd242ed0b11f)

* What days of the week are busiest?
![image](https://github.com/meehal0203/CitiBike_NJ_analysis/assets/146681542/f1b1dbed-72a1-4b57-9165-7f79d57970d3)


* What time of day are CitiBikes most frequently used?
![image](https://github.com/meehal0203/CitiBike_NJ_analysis/assets/146681542/75a68893-5c3d-4a87-9352-767156840947)

* What are the differences in the riding behavior of CitiBike 'members' -  who pay an annual or monthly fee and have unlimited use of the bikes for 45 minutes at a time and the 'casual' members who don't have a subscription,pay to unlock the bicycles each time and then pay by the minute.
![image](https://github.com/meehal0203/CitiBike_NJ_analysis/assets/146681542/3b26e3bb-9c49-4706-bca4-ee31a1529593)


* Which variety of bike, electric or classic, do these member types prefer?
![image](https://github.com/meehal0203/CitiBike_NJ_analysis/assets/146681542/07b46181-ef96-43d8-950b-f8560d66322e)

These visualizations will be used to design a dashboard for each phenomenon accompanied by an analysis explaining why the phenomenon may be occurring.

A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top will be created.

The audience for this presentation will be city officials, public administrators, and heads of New York City municipal departments. The analysis will be presented in a way that is focused, concise, easy to understand, and visually compelling. Visualizations will be colorful enough to be included in press releases, and thoughtful enough to inform programmatic changes.


Full analysis can be found on my Tableau Public: https://public.tableau.com/views/NJCitiBikeAnalysisFinal/CitibikeNewJerseyAnalysis2023?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link



Stack Overflow, tutoring and BCS Learning Assistant were used to complete this assignment
