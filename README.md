## This questions are due next discussion section (Week6).

1. Describe the Biology of your project? (one paragraph max).  
      In my project, I will be analyzing microridge curviness from existing microridge coordinate data. Microridges are small ridges formed by actin protrusions on the surface of skin cells which are thought to function in mucus retention. These microridges are imaged on the surface of zebrafish skin cells by using LifeAct-GFP transgenic lines, which will make the microridges fluorescent. Another member of the lab took these images and has a program that deconvolutes this data and turns it into a series of coordinates for each ridge. I will be using these existing coordinates to perform some measure of curviness on each ridge and return this data as an excel file.
      
2. Describe the kind of data that you think you will be handling (one paragraph max).  
      I will most likely be handling data about microridge development, with multiple time points that have each have coordinates for every microridge in multiple cells. The data will be in multiple csv files, each of which contains the data for a single cell. I will most likely be analyzing data about microridge development, but this program should also be useful for many different experiments that have been done by that grad student and also be useful in the future.
      
3. What would you like to do with that data? (one paragraph max).  
      I would like to use a mathematical analysis on the data to get the curviness of each ridge. I could either try to get the second derivative of the ridge coordinates and take an average, or do something simpler like dividing the length by the distance between the ridge endpoints, or something else. I would research it online. If I finished that early, I would also want to graph the results.
      
4. What will be the output? (one paragraph max).  
      The output will be an excel or csv file with the curviness number for each ridge. I might also give the average for each cell. The data would all be outputted in a single csv or excel file, even though the input will be many csv files.
      
5. Is there any computational tool, package, etc. you would like to use? What would you do with that? For instance, you could mention shell scripts with `sed` or `awk` and will change the format of a table by replacing `,` with tabs. 
Also, you could mention tools that we haven’t seen in class yet but you herd that may be useful for your project. 
For instance, you could say 
***I will use the package “GenomeGraphs” implement in the R software to visualize genome data***. (a few sentences max).  

      I would like to use R as the programming language. Other than that I don't have any specific ideas.

6. What is your biggest concern regarding your project? (a few sentences max).
      My biggest concern is figuring out what sort of math to do and implementing this math, especially since the raw data is just coordinates. 
      

## Grade Discussion 5 (week5): 20/20 Nice work!!! :thumbsup:

| **Rubric** | **5pt** | **4pt** | **3pt** | **2pt** | **1pt** |
| --- | ---| --- | --- | --- | --- |
| In-Lab work | **X** | | | |
| Questions | **X** | | | |
| Project README.md | **X** | | | |
| Challenges - Timely Submission | **X** | | | |

