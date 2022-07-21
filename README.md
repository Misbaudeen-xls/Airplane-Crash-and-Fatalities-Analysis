Airplane Crash and Fatalities Analysis(1908-2009).


INTRODUCTION: The Analysis of Airplane crash and fatalities dataset was given as a capstone Project for Microsoft #ASUU30DaysOfLearning. The dataset is a CSV file that contains information about the occurrence of plane crash and fatalities all over the world from 1908–2009. It has 13 columns and 5,268rows.

DATA SOURCE:This Dataset was created on Kaggle in September 2016 but the original version was hosted by Open Data by Socrata at: https://opendata.socrata.com/Government/Airplane-Crashes-and-Fatalities-Since-1908/q2te-8cvq (no longer available). The dataset contains data of airplane accidents involving civil, commercial and military transport worldwide from 1908-09-17 to 2009-06-08.
The Data can be accessed from this link https://aka.ms/30DLDATGitHubRepo.

DATA CLEANING:Here is where the big work is. Getting the data ready for proper bending and mending. First things first. I sourced the data from the web using the Microsoft Excel Power Query ![New step 1](https://user-images.githubusercontent.com/107483782/180100186-0b5fa208-52b0-4021-aeb0-20c0b9bbc9c9.jpg)

After loading the data, the next thing is to transform the data. I removed the unnecessary columns i won't be working on.![Step 2](https://user-images.githubusercontent.com/107483782/180100656-cea64143-1b67-4740-9e60-c28e3552ad49.jpg)


Next thing i did was to have a separate columns for the year, month and date respectively.![AStep 3](https://user-images.githubusercontent.com/107483782/180101696-c24bad95-ce17-4413-a104-108082f9a025.jpg)


I noticed there were rows there with null as values, so i replaced them all of them.![AStep 5](https://user-images.githubusercontent.com/107483782/180102081-ecf56a75-6dd8-43d1-8aaa-b9c657f255c5.jpg)


I needed to sort out the major causes of the Plane crash column, so i created a custom column by writing a little bit of M-Language using text contains such that any sentence that contains snow, fog, lightning, weather and so on will go under weather.(I did same for other causes of Plane crash) ![AStep6](https://user-images.githubusercontent.com/107483782/180102701-bc3b27a1-a683-4905-8f4d-ff72daf3f2b8.jpg)


I created a custom column to get the Total Death of Air Passengers and Crews.![AStep7](https://user-images.githubusercontent.com/107483782/180104210-aec848c2-cae7-419f-b701-1f7a317c221f.jpg)


Created another custom column to get the Total Survivors of Aboard.![New step 8](https://user-images.githubusercontent.com/107483782/180144773-671d793b-20ad-42f0-995f-140f85625194.jpg)


Using Delimiter feature, I separated the Countries from the Location column.![image](https://user-images.githubusercontent.com/107483782/180145151-0d966198-05a6-4845-92ff-66ce2e582692.png)
 
After cleaning the Data, I achieved this and loaded it on Power BI for further analysis.![Finished job](https://user-images.githubusercontent.com/107483782/180147893-5e5dabd6-b001-4c2f-8d8d-918e08bdeb07.jpg)

DATA ANALYSIS AND VISUALIZATIONS:
The Fatalities Analysis. ![DATA VISUALIZATION 1](https://user-images.githubusercontent.com/107483782/180150612-11507513-01af-47f3-9f54-79f0f2c9f86c.jpg)



The Aboard Analysis.

![image](https://user-images.githubusercontent.com/107483782/180151049-241cfc95-648a-4a61-b0dc-26f6948022cf.png)




The Dashboard.

![DATA VISUALIZATION 3](https://user-images.githubusercontent.com/107483782/180153190-be166da5-bf5a-4361-bc2b-107fad91799d.jpg)



THE INSIGHTS:

=> The highest number of Plane crash survivors was seen in the year 1999.

=> The Major cause of Plane crash over the years is as a result of Structural failure.

=> The Airline that recorded the most Fatalities over the years is Aeroflot.

=> The highest number of Fatalities occurred in the year 1972.

=> The month of December recorded the highest number of Aboard.


THE RECOMMENDATIONS:

=> Good maintenance saves: Airlines should ensure that their Aircraft are getting proper maintenance and servicing before flying the planes.

=> Flying the planes when the weather is not clear is not advisable. Ensure that the sky is very clear and healthy for Airplanes before flying them.

=> When the Plane makes an unsual sound, it's advisable for the Pilot to get back to the ground and see what's making the sound in the engine.



