# Quantifying Water Crisis in South Sudan Through Journey of Salva Dut
 This story is part of the Data Studio class by Jonathan Soma at Columbia Journalism School.

The prompt for this project was to build an ambitious story using something we had not used before. I tried my hand at two things:
-narrative using a profile
-scrollytelling

The research was done as part of final project for the seminar class, Conflict and OSINT reporting, taught by Professors Azmat (amazing pro max) Khan and Haley (supremely talented) Willis. Yes, I fangirl about them a lot and brag about knowing them.

### What I Aimed to Accomplish
This story aims to show the gap in the understanding of the water crisis in South Sudan which is the newest country in the world. The story builds upon the life-experience-based profile of Salva Dut, who was part of the 'Lost Boys of Sudan' - a group of refugee children/youngsters from war-torn Sudan. After having lived for more than a decade with the belief that he had lost his parents, a hand-written letter from a distant cousin informed him that his father was alive and undergoing treatment for a water-borne disease that was avoidable with clean drinking water access. He started a non-profit that started digging wells to bridge that gap. After having dug over 614 wells, the non-profit has made a difference in the lives of thousands of people. 

But it is not enough progress for the South Sudanese population that is wrestling with water shortage, violence, volatile tribal power dynamics, and dependence on international aid for monetary needs.

### Findings
Globally, easy access to clean drinking water has improved by 4 percentage points between 2015 and 2020, according to a joint release issued in 2021 by the World Health Organization and UNICEF. 

Despite those advances, the number of rural South Sudan residents who have to walk more than 30 minutes to access clean drinking water has actually increased in the same period, according to an analysis of the data released by the two organizations. 

As a majority of the South Sudanese population live in rural areas, it is a cause for concern that a growing number of them have to walk for clean drinking water.

Therefore, even though it seems like the access to clean drinking water has increased, the number of people who have to walk to the source for more than 30 minutes has increased. 

<img width="772" alt="Screenshot 2023-07-07 at 3 20 21 PM" src="https://github.com/ShalakaS/water-crisis-salva-dut/assets/8871052/97428419-32c8-4c9b-8e8b-bdc59b8cddb8">

### Data Collection Process
The data was drawn from excel sheets published by Joint Monitoring Program (JMP) by UNICEF and WHO. They publish global data on Water Supply, Sanitation and Hygiene (WASH).

They have a section for South Sudan. I took data directly from the portal.

### Overview of the Data Analysis Process
I got the data of wells dug by Dut's non-profit from their Rochester, NY-based office. 

The WASH data was divided by rural-urban population, level of contamination, and time needed to get access (including walking to the source, wait, and back). I isolated the data for the rural population first. 

I first made grouped bars of rural population, grouped as per the access time and plotted over years. But it looked too crowded. So I chose stacked bars to show the very visible change in the number of people who have to spend more than 30 minutes to access clean drinking water. 

### New Skills and Lessons Learned
Making a statement about increase in access to a facility, purely based on raw numbers, is not a good idea. More often than not, the people behind the number have a different story to tell. 

I learned to **look at the shape of data** in different perspectives in this process. After joining data from two sections, I could tell the difference in access over time. 

I also learned to build **scrollytelling** using JavaScript's Scrollama library. 

I also used ChatGPT to learn how to use the **folium** library in Python to build maps directly in HTML and change the base layers.


![ezgif com-gif-maker](https://github.com/ShalakaS/water-crisis-salva-dut/assets/8871052/844bd1b8-4187-4cc5-a4cb-a1622ad4ba5e)


### Future of This Project
I wish to find the people most impacted by this gap and learn from them, their experience of water collection and the impact it has on their life. 

Aside from the Director of the Irrigation Department, I would like to hear back from the WASH cluster head and get more granular data that will help me identify where this impact is felt the most. It will also be insightful to see the average distance between a drinking water source - bore well, hand pump, and overhead tanks - and households it serves. 

Groundwater tables-related data will add a layer of understanding of the future. 

Humanising this data further would only provide more insight into the real extent of the problem. 
