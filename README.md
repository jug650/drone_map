# Guide on Where to Fly Your Drone

## 1\. Intro

This website is intended to consolidate, into one location, all the information that someone need to operate their UAS legally and safely. In recent years, there had been a lot of confusion on what procedures the average person must follow to legally operate their UAS. With the increasing popularity of the consumer UAS's available, it was clear that the FAA needed to develop a new set of regulations to establish how the public would be allowed to operate their aircraft in proceeding forward in the future. 

This increasing popularity has also caused an increase in public concern over safety and privacy. FAA data shows that the largest concentration of registered UAS hobbyist live in urban environments. In such settings, it is very likely that there could be an incident of concern.

For both of these reasons, the FAA released their new policy on UAS operations referred to as Part 107. This website discusses these policies, provides tools to help someone find a place to fly, local clubs, and external resources to allow them to research the topic further if they so desire.  

## 2\. Data Sources

1. The template for the web design is in the Bootstrap Format and this particular template was derived from a template from [StartBootstrap.com](). While the overall flow of the website is similar to there design, the website sections and visual appearance are intended to convey a theme of UAS flying and aerial photography.

2. The data for the FAA Part 107 policies is from [FAA.gov]() and [KnowBeforeYouFly.org](). Additionally, a spreadsheet from the FAA was collected which showed how many registered recreational UAS pilots were registered in each zip code in the United States. That file was then joined with a shapefile from the Oregon Explorer Library that contained each zip code in Oregon using QGIS. The join was used in order to create a map that showed the distribution of recreational registered pilot in a respective zip code. The intent was to illustrate how the use of drones likely increases in populated areas. Once this was completed, the shapefile was then converted into a GEOJSON in order to overlay onto a basemap layer.

3. The AirMap was integrated by inserting their designated URL which contained the baselayer and additional functionality, such as the location tool and the popup data window. Next the additional coding was added to provide a link to the appropriate location if the user decides they would like to download their mobile based app.

4. The AMA map was integrated by using the code that had been previously used by [KnowBeforeYouFly.org](). Which was simply the same process as the AirMap, format the appropriate coding to pull the map and its features from the appropriate URL location.

5. Finally, the jpegs were located online at [Skypixel.com]().

   ​

   - An introduction to your final project (3 pages and double spaced). You might describe the project purpose, data source, map elements,  map libraries, and other issues you think are necessary to inform your audience of;
   - The decision process you went through when deciding how to serve the different layers;
   - A functionality summary of the web mapping. You are required to explain each function using **a screenshot of  the map and a concomitant brief description**. This summary could be something similar to a walkthrough handout I demonstrated in lecture. 
   - The things you learned in this project that will be most valuable to you in your professional or academic career.

6. **Source code** that contains all the files (html, js, css, and data) used to make the web mapping application.

Please compress the cover letter, project report, and the source code in a zipped package, and submit it to a dropbox in Canvas **(by 5:00pm on March 19th)**. 

## 3\. Presentation and peer review

Academics often attend conferences where they share their discoveries and browse the work of others to gain new ideas and offer feedback. on March 22nd, we will hold a final presentation meeting at 361 Strand Hall. Each team (made up of an individual or pair) is asked to present their final project in 8 minutes. And there will be a F&A session in 2 to 3 minutes.  During the final presentation, each student will need to review all final projects and submit your review notes.

## 4\. Bonus

The final project has a bonus session to encourage you to understand and further contribute to the open source community. If you complete **all the three tasks** listed below, you will earn the bonus credits:

1. Publish your web map in an Internet accessible server. This server could be your google cloud platform, the course map server at `http://www.mapio.us`, or others.
2. Share your source code on GitHub.
3. Convert your project report into a **README.md** file and share to the front page of your GitHub repository.

## 5\. Timeline

1. **Submit your project proposal by 5:00pm on Feb 10th**. The proposal should at least contain the project topic, potential audience, and the possible data sources.
2. Each project team will hold a project meeting with the instructor Bo Zhao to detail the proposal during the week Feb 13th to 17th.
3. The instructor and the TA will help each team look for data, map libraries and fine-tune the web map interface design. Each team will have one month to work on the final project.
4. Please compress the cover letter, project report, and the source code in a zipped package, and submit it to a dropbox in Canvas **by 5:00pm on March 19th.** (if you want to get the bonus credit, you will need to complete the requirements for the bonus by this deadline as well.)
5. **On March 22th (Wednesday) 12:00pm to 1:50pm**, we will hold a final project presentation meeting at 361 strand hall.
6. You will need to submit **peer review notes** for each project right after the presentation meeting. 

> **Note:** The requirements to the final project may be slightly changed according the progress of this course. The final requirements are subject to the instructor's notification.