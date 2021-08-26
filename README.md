# **My 1<sup>st</sup> #100DaysOfData Challenge**
In this repository I will track my first challenge of #100daysofdata, using as a summary of my activities, the books I read, the courses I take and the projects I make.

| Projects |
| -------- |
| 1. [**Zoopla London Houses Price Prediction from Scratch**](https://github.com/diequies/zoopla_houses) |
| 2. [**Building A Recommendation System For Cognitive Exercises and Training Programs**](https://omdena.com/projects/cognitive-exercises/) |

| Courses and Certifications |
| ------------------------- |
| 1. [**2021 Python for Machine Learning & Data Science**](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/) |

| Books and Papers |
| ---------------- |
| 1. [**Python Data Science Handbook**](https://jakevdp.github.io/PythonDataScienceHandbook/) |

---

### **Day 56 of #100DaysOfData Challenge**

Less time to code today, but I spent the whole time at **Omdena** project solving some structural problems. Also I started to look to the main code, but so far, it looks too complicated. I definitely need to learn coding skills.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). While doing the documentation, specifically the pipeline to generate the data, I realized that it was too complicated, too many code files and not with the correct flow. So I spent the day re-structuring the code and making a smooth pipeline, now it is much easier to explain and therefore easier to go through. Tomorrow I will try to complete the documentation.

---

### **Day 55 of #100DaysOfData Challenge**

Today I managed to not only progress in **Omdena** project, but also to take back again my personal project on London house prices prediction. It is being difficult to find the time, but I should manage it better.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Main focus for todays has been to solve a bug I had in my task code and then keep going with the documentation. As I see it, I believe that it should be finished by today or tomorrow.
2. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Definitely I need to start documenting my project. Every time I take it back, I need at least 30 mins to remind myself how it was working. My main issue now is the *Overpass Turbo API*, it is not meant to be used for too many requests and gives me error too frequently. I have to find an alternative.

---

### **Day 54 of #100DaysOfData Challenge**

The main point today was to adapt some feedback I had for my **Omdena** task and then start creating documentation. I learn today that the notebooks are very useful to show your work but from coding point of view, it is difficult to keep the flow and when someone else wants to run the same code, either they follow the same order or it wouldn't work. I should move to script and OOP.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Main task today, documentation, it is boring but it is useful to review the code, detect problems and also bad quality in the code. I should work in improve the quality of my code, probably reviewing other **Omdena** people's code would help me with that.

---

### **Day 53 of #100DaysOfData Challenge**

The focus of today was **Omdena** project, but I managed to get some time also to see some videos of the python course. I need to start to distribute the time again between all four items.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I finalized the last deliverable of my task, meaningful synthetic data. From now I have to complete the documentation and then I will try to move on to support other tasks and try to learn. This is the last sprint.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). Today I have also completed the Logistic Regression module, it covered not only the normal Logistic Regression, but also multi-class classification with Logistic Regression. The logic of consecutive algorithms is really interesting.

---

### **Day 52 of #100DaysOfData Challenge**

Today was a mostly relaxing day, although I still spent some hours in **Omdena** project to progress it. 

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I almost finished the code to generate meaningful data and started the one to assign names for demo exercises. But in the meeting with the client, some assumptions changed and I will have to address them now.

---

### **Day 51 of #100DaysOfData Challenge**

Today we had a sort of alignment sprint, being my first project in this industry it is very insightful for me to see how different are the processes and management. Again, and probably until my task finishes, I will keep focus in **Omdena**.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I kept progress in my code to generate meaningful data. The code is nothing special but it uses a big variety of functions. I have to generate controlled random values with loads of constraints. My plan is to finish tomorrow or at least before the end of the weekend. 

---

### **Day 50 of #100DaysOfData Challenge**

Midway of the challenge, I believe I was expecting more progress but with 14 holidays in between and working full time in another job, it has been really difficult. Today I could spend most of the day coding for our **Omdena** project, which is important to learn.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Yesterday I finalize my clustering code, I believe it is not very orthodox, but I fulfills the objective I had. As I wanted a specific number of clusters, I had to diverge from what was the most accurate. But now I am moving to create historical data with those clusters, I have good expectatives about this.

---

### **Day 49 of #100DaysOfData Challenge**

I focused today on the clustering problem to generate meaningful data for our **Omdena** project. I couldn't spend time in other parts of my objectives, but I could learn limitation and difficulties of cluster algorithms.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). My plan was to find a number of clusters and be able to represent them using t-SNE, but I end up doing something completely different. First t-SNE does not give you components, therefore it is not possible to explain or understand the logic behind. Also, when I tried to do clusters using demographic and geographic data, I found that they were, at least initially, incompatible. If I used geographical data, the cluster had worse defined demographic characteristics and a meaningless spatial distribution. To have a quick solution, I have conducted an initial clustering with demographics and a second one with geographic data. It is not ideal but it worked quickly, if I had I would have study the spatial distances and tried to optimize the algorithm to use. 

---

### **Day 48 of #100DaysOfData Challenge**

Today I just worked on **Omdena** project, we had some feedback about the database and also I wanted to progress with the clustering code. Now it really feels like we are in the last weeks of the project and we have some pressure to finish at least a first prototype

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today, the most interesting I did was start with the clustering code. I plan to test different algorithms and also I had the challenge to find a good way to visualize the clusters. Today I fixed this last point, using *t-distributed Stochastic Neighbor Embedding* (*TSNE*) I can reduce the dimensions to fit in a 2D or 3D plot. I tried also *PCA* and *NMF* but the  result is not as good, the clusters were not clearly visible. Also I tried K-Means algorithm for clustering, but before digging a bit more, the results do not look very reliable. Tomorrow I hope I can try other algorithms.

---

### **Day 47 of #100DaysOfData Challenge**

Today I just worked on **Omdena** project, I had not much time to spend in Data Science. But, it has been a useful time. We have had two meetings to organize and then I started a new important sub-task.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). As I said, today I moved to a new part of the data generation. Now I am trying to generate meaningful data, to do so,  have started by finding clusters in users data. I plan to apply some different cluster algorithms and compare the results and then try to visualize the results using PCA (Principal Component Analysis).

---

### **Day 46 of #100DaysOfData Challenge**

Finally I had the chance to re-start my side project of London houses pricing, not without difficulties... Also I keep the progress with **Omdena** project at the end of the 5th week.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Now I have started to document the process we have followed to generate the data. It is the first time I have to create software documentation, new thing to learn. So far *Markdown* code is being really useful.
2. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). The first day coming back to this project after some weeks. First point I have realized is that my comments were not enough, I needed too much time reviewing the code to get up to speed. If I were someone out of the code, it would be impossible for me to work on that code. Another issue I had today is involving *GitHub*. Before holidays I commited I huge amount of updates, including a *CSV* file of more than 100MB, which is not permitted by *GitHub*. I found myself in a roundabout where I couldn't push my changes but also I couldn't un-commit the change. I had to start again almost a new repository to solve this issue, but the lesson is, commit small changes and with care.

---

### **Day 45 of #100DaysOfData Challenge**

Another productive day working mainly in SQL for **Omdena** project. Sadly I have not been able to progress in any of my side projects, I need to make an effort to distribute the time.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today we have finalized the database setup, created the VIEWs, which was something new for me. After too many time spent in management of the task, I need to engage with coding, otherwise I will never learn.

---

### **Day 44 of #100DaysOfData Challenge**

Today has been a very productive day, I coded a lot, not only in Python but also in SQL, and mainly for the **Omdena** project. Hopefully as part of the ramping up, I re-start also my personal project of London house pricing.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today we have completed the sub-task related with MySQL database. I have almost zero knowledge on SQL and it has helped me to learn. I will try to finish MySQL by today. We still have to create MySQL views, which is something I have no idea.

---

### **Day 43 of #100DaysOfData Challenge**

Lately I am struggling to spend time in other things than the **Omdena** project, I guess it is because we are in the highest moment of the sub-task, but I need to find time to progress on the other items.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I have been correcting some code and I had some issues with an apply function. I need to review why an apply function gives the error of too many values, in my understanding it just gets one value.

---

### **Day 42 of #100DaysOfData Challenge**

Another busy day. I have been focused completely on **Omdena** project, mainly organizing and refining the mid-term presentation.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Even though I have been focused in non-coding stuff, I could start the correction of part of my code. Some assumptions changed and they affect to this code, now I understand how useful is to code in a modular way with functions. I need to learn to code with OOP.

---

### **Day 41 of #100DaysOfData Challenge**

I had to spend the day understanding and creating with other colleagues of the **Omdena** project, the mid-term document. We have completed half of the term for the project, 4 weeks, and we have to present to the partner our progress towards the planned derivables.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). My assigned task is more than half way completed, during these days I am trying to progress as much as possible to completed and be able to move to other tasks. Hopefully I can join some of the machine learning groups before finishing the project.

---

### **Day 31 to 40 of #100DaysOfData Challenge**

Unfortunatelly the holidays had come to its end, and now I am back to work. During this days I kept focusing on **Omdena**'s project and also had some time to progress in the course. 

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). During these days we have had a lot of progress on data generation task. We have finalized the initial data sets generation, a total of 17 tables, and now we are moving to the next step. As a deliverable we have to create a synthetic database in MySQL, we have started to created the hosting (in AWS) and its structure. And now and for the next days we have to modify the code to populate the MySQL database instead of just output a CSV. I will take this opportunity to practice database creation and maintenance in MySQL.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). During these 9 days I have completed the next modules:
   - Data cleaning adn feature enginering: The course goes over some of the most common techniques to deal with missing values, with outliers, normalize the values, etc.
   - Cross validation: In this module, the course introduces cross validation techniques using scikit learn. Even though it doesn't go through to the most up to date and best cross validation methods, it is more than enough to fully understand the purpose and the technique.

---

### **Day 30 of #100DaysOfData Challenge**

As I am still on holidays, my time for data science is reserved to **Omdena**'s project. If I can I will try to progress in other areas as well.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today was quite challenging to keep up with the feedback to our initial data sets generated. Organize the sub-tasks, give the feedback to the appropriate people takes most of the time. But actualy is the best way forwards, with this organization the team is confident to work in the same direction and the progress is better.

---

### **Day 23 to 29 of #100DaysOfData Challenge**

I have been on holidays from day 23 and I will still be until the day 39. But I kept doing at least something related to Data Science all these days, I have been working mainly in **Omdena**'s project to keep up with my commitment.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). During this week I have been focused organizing the task I have been assigned, to generate synthetic data. As it is the first step, we need to have an initial output to allow the rest of teams to start working. The challenging point is that there are many rules to comply but very little information from the company, but during the week we have improve a lot. Currently we have some initial data sets and outlined most of the rest of data sets. For next week we should complete all the outlines and have a data set for most.

---

### **Day 22 of #100DaysOfData Challenge**

Again not a coding day and also, not a great day for my data science progression. I am about to go on holidays and, even though I will keep working on **Omdena**'s project, I will stop almost anything else to enjoy a couple of weeks of holidays.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). After the new and better understanding of the problem to solve, we have decided to pivot the data acquisition task. The main reason is that we have determined that it is not possible to create a training data set because we do not have the list of items to recommend. Therefore, now the objective is generate a data set for testing and demo the API. It needs to be realistic and with some logic and limitations, but it does not need to be real. Tomorrow I will finish to draft the first data set and create the document to explain it.

---

### **Day 21 of #100DaysOfData Challenge**

Not a coding day, sometimes there is more progress when we don't touch any code... More discussions today to clarify and frame **Omdena**'s project and also some videos to complete linear regression module.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). The main activity today has been to prepare the meeting with NESTRE and then to try to extract as much information as we could. It is being really complicated to find the best way forwards, it feels that every time we have a meeting everything changes and we need to start over. But it feels we are closer now, tomorrow I will summarize everything and try to create sub-tasks for better organization.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). Today I finished the linear regression module. Hopefully I can apply this new knowledge in my personal project soon. We have learn then next types of regression:
   - Univariate and multivariate simple regression: This is the most basic way to do regressions, just a line that tries to find the best fit for the targe variable using all the features.
   - Polynomial regression: In this regression type we increase the features by adding relations between features and higher grade features. Very interesting but dangerous to overfit.
   - Lasso, Ridge and Elastic Net regressions: To handle the overfitting problem we add a correction factor (depends on the type, we use a different type of factor or a combination) that will add noise, so we can handle better new data.

---

### **Day 20 of #100DaysOfData Challenge**

Another day focused on **Omdena**'s project; I know this weekend I will not be able to work as much, so I am trying to increase the work to meet the weekly hours I committed.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I have finalized the EDA I was conducting in the Lumosity data set. I could find some interesting insight valuable when we have to prepare our own data set. I had some difficulties dealing with outliers and other modifications on a feature that contains a high level of granularity, for example, game results, including all game types. Tomorrow we have another Q&A meeting with Nestre to finalize framing the problem. Also I will summarize my findings on the EDA and post them to Slack.

---

### **Day 19 of #100DaysOfData Challenge**

Day fully focused on **Omdena**'s project, basically trying to perform EDA to the best data set we have found. I did not have time to spend in any other of my "tasks".

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I started again EDA activity on the Lumosity data set. In some way, it was good to lose the initial notebook as now I am doing it better from the beginning. Today I made the main DataFrame merging the three originals and dealt with missing values. Also, I found that the values of a feature I want to compare had loads of outliers, therefore I removed them. For tomorrow I want to normalize the values so they are comparable.

---

### **Day 18 of #100DaysOfData Challenge**

First contact with GitHub as a collaborator in a collective project. Today I had to learn how to create new branches and how to push my work without overwriting others work.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I started the EDA on the only data set we could find. This is my first non-guided EDA, and I have to say that it is difficult to decide where and how to start. So far, it is a bit of a mess, but I could find some interesting points. The only drawback is that I have to correct it to allow other people to understand it. Also, as my first adventure in GitHub collaboration I deleted my own notebook, and unfortunately, I will need to start again tomorrow.

---

### **Day 17 of #100DaysOfData Challenge**

Thanks to communication, today, we improved our understanding of Nestre requirements. Communication is always a key in team working and more in inter-companies working. In addition, some more progress in house pricing prediction, a new method, less API intensive.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). The method I am using to get the closest tube station and the walking time between the station and the house is to select the two smallest euclidian distances (using coordinates) between the house coordinates and a list of all stations coordinates. Then to confirm the closest and find the walking time, I am using the [*MapBox API*](https://www.mapbox.com/), which is more dynamic and allows more and higher frequency requests.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today we had an insightful meeting, Nestre started to share a bit more information, which made the things clearer. Unfortunately, with this new information, the model and data set that we outlined changed slightly, so now we have to re-study. Also, I presented the task in front of the people, it was good, but I got no feedback.

---

### **Day 16 of #100DaysOfData Challenge**

Preparation day for the first weekly update, as a task leader I need to report what we have done so far. Also I am trying to find alternatives for my personal project, instead of relying too much on API such as [*Overpass Turbo API*](https://overpass-turbo.eu).

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Because of the limitation in requests of [*Overpass Turbo API*](https://overpass-turbo.eu), I need to find an alternative to be able to find the closest station and its walking distance in time for around 20k houses. My plan is instead of request the information regarding the closest train stations to the API a will create a list of the tube stations with the cordinates and pick the 2-3 closest for each house, and then request to an API this walking distance information using coordinates.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I had to prepare the presentation of my task's progress, it is being quite difficult as the steps are really unclear and the progress has been very limited. But I will try to explain progress and challenges with the objective of increase our understanding with Nestre.

---

### **Day 15 of #100DaysOfData Challenge**

I have started to outline the expected data set for **Omdena**'s project and shared it with the team. So far, it is pretty disorienting, but I feel now that very slowly, things are getting more clear. Also, I keep progressing in my personal project of house pricing prediction.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). I have started to study the next step in this project, to calculate the walking time to go from the house to the closest station. I will use a different API that also connects with *OpenStreetMap*, called [*OpenStreetMap Routing Machine API*](http://project-osrm.org/). It looks quite straightforward; I have already started to review the documentation and almost have the expected output with a few lines of code. Tomorrow I plan to finalise this part of the code to identify the closest tube station and input the walking time.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today's main focus was to present the data set sample I outlined to the team and ask the questions that came up to Nestre. In addition, Nestre shared the wire-frame of their app to clarify a bit their requirements, and of course, it generated more questions to add. Based on their replies, I expect to progress tomorrow with the data set outline.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). During the last two days, I have finalised the *Numpy* chapter, and I have learned a lot, about the essential functions and some whys that are very insightful. However, at the end of the chapter, there are more complex functions and explanations that I found less useful, although it seems just the introduction to the next chapter about *Pandas*.
4. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). Today I have started the regression module, it is the longest one, so probably it will take some days to cover it. But, I am very interested in it because even though I have already studied them, my personal project will probably be the first time I put them into practice.

---

### **Day 14 of #100DaysOfData Challenge**

Another day spent on **Omdena**'s project, trying to put in order ideas. My main roadblock with the data-set acquisition is that I am not really sure of what comes next.

1. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). My main task now is to acquire or generate a data-set as input for the models, or at least find the way. The initial steps are to outline the required data-set and find possible sources. We are seeing two fundamental roadblocks to accomplish those points, the lack of data and details from Nestre and my lack of skills and knowledge to understand what comes next. My plan for tomorrow is to ask my questions to Nestre and share my outline to get feedback.

---

### **Day 13 of #100DaysOfData Challenge**

Today I found difficult to spend time in my Data Science project of life but as a minimum I had 2h working on **Omdena** project and just a little bit on my house pricing project. 

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). I am a little bit stuck with [*Overpass Turbo API*](https://overpass-turbo.eu), as it seems it is giving me problems because of too many attempts. I am trying different ways, like sleep time to wait between requests. Tomorrow I will keep trying other methods.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today we made a clear statement of the task we have been assigned, data-set acquisition, and specified the different methods we believe we can use to solve the task. While we wait for the data from the partner to decide the best approach, I will start looking for information and a baseline for each.

---

### **Day 12 of #100DaysOfData Challenge**

Quite an intense day today. We had our first team meeting with **Omdena**, I still feel pretty lost, but it is improving. Also, I made the first step forwards on Overpass Turbo API, although still far from what I want.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Today, I had almost no time to invest in this project but, still, I have managed to make some progress using [*Overpass Turbo API*](https://overpass-turbo.eu). I can get now, for each house, using its coordinates, the tube stations within a specific range. The loop is relatively slow, and also I am still playing with the API timeouts. Currently, I am waiting 1 second per request, but I guess I will need to increase that. Once I get the stations related to each house, I have to find a way to estimate its walking distance and select the shortest one. I believe I won't be able to do it with Overpass Turbo API, but I am sure that there are resources out there to do it.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today, we had our first team meeting, and I wish I was more participative and that we could get more output from it. However I could improve my problem understanding and could suggest one task. This task is to create the dataset via survey, it is quite simple from a Data Science point of view, but it requires time and some research to avoid bias and get the required output. Tomorrow I will draft a path and some possible sub-tasks to propose.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). I keep going with the *NumPy* chapter, now it is going deeper, and it is showing how to do fancy indexing, binning or sorting using *NumPy*. Slow progress, but progress it is.
4. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). I completed the capstone exercise, where we had to use what we have learnt so far from *NumPy*, *Pandas*, *Matplotlib* and *Seaborn*. It was not so difficult but very useful to settle the previous work.

---

### **Day 11 of #100DaysOfData Challenge**

Another day of reading general Data Science articles suggested by **Omdena**, I am also trying to frame the problem myself, but I feel inexperience. I could start the second phase of my house pricing prediction project and continue reading and watching the course, quite a productive day.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). The objective of this new phase is to add more information and features related to the location of the house, such as walking distance to the closest tube station, the density of supermarkets/shops/restaurants, etc. To do so, I will use [*Overpass Turbo API*](https://overpass-turbo.eu), which is an open-source data filtering tool that uses OpenStreetMap data. So far, I am finding the query language a little bit complex, but I am now getting used. Tomorrow I want to extract at least the details of the tube stations in a range of 2km.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today, apart from keeping reading and trying to catch up on knowledge with my peers, I have started to frame the problem we need to solve. Tomorrow I will continue, and we will have a meeting to share our ideas and repeat the activity altogether again. The purpose will be to define the first tasks and hopefully some subtasks.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). I continued with the *NumPy* chapter, I am learning now the importance of vectorization and how it can improve the efficiency and speed of our code. Also, it explains the main aggregation and arithmetic functions, and the use of mask arrays.
4. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). After some days not being able to watch more videos of the course, I managed to finish the *seaborn* library module. Nothing entirely new, but quite useful to better understand how it works and some not straightforward functions. The following module is a capstone project for visualization to check what we have learnt so far.

---

### **Day 10 of #100DaysOfData Challenge**

Even though I was focused today to gain knowledge for **Omdena**'s project, I also managed to finalise Zoopla data extraction on my personal project for house pricing prediction. Additionally, as every day, I spend some time reading the book.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). I have finalised data extraction and processing from Zoopla. It has been very tedious, mainly because web scrapping was very slow; I was scrapping information from more than 50k houses (and therefore webpages). Also, the quality of the data encoded was relatively low, and I had to complement it using complex pattern extraction. I am sure that with NLP techniques, it would be much easier. The next step is to add information about the location of the house. I am thinking of something like the closest station, supermarket, etc. and the distance in time.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/). Today I have been reviewing articles and papers provided by **Omdena** and some shared by the team collaborators. I could also find an interesting survey paper ([link](https://arxiv.org/pdf/2101.06286.pdf)) summarizing some techniques for recommender systems using reinforcement learning and deep learning. So far, it is out of my capabilities, but I found it interesting, and the team might be able to extract values from it. I would be delighted to learn how to implement this kind of model during the project. Tomorrow we have our first meeting to frame the problem, and hopefully, the first task will flourish.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). I continued with the *NumPy* chapter, basically the fundamental operations and why they are different from normal Python. Also, it is reviewing the *ufuncs*, which gives me a good idea of *NumPy* capabilities and a reference to use in my code.

---

### **Day 9 of #100DaysOfData Challenge**

On the first day being part of **Omdena**'s project, I have spent most of the time reading and learning as basically it is my first time in almost all the facets of the project. Also, I kept working on my personal project and reading the book slowly but steady.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Once I cleared my issues with pattern extraction, I have been able to progress at a good pace. Today I have completed the feature extraction from text features and almost finished cleaning and filling missing values. My plan for tomorrow is to finish the dataset and create the SQL database, which won't be easy as I have never done it.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/) On the first day of the project, I explored and read all I could from **Omdena**'s internal resources, mainly Git procedures and other articles for data flow and treatment. Also, I have read many articles and papers for recommendation systems, but as it is the first time I face this sort of project, I still need to learn a lot. So my plan for tomorrow is to finish with the internal resources, keep learning about recommendation systems and find any valuable resource that I can share with the team. So far, I am finding quite challenging the interaction and the way of working, but I am sure that soon I will get used to and be able to collaborate more and better.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): Today I started the *NumPy* chapter, and again, as it starts from the basics, I am learning a lot. Also, I am understanding now some issues I was having because I did not have the knowledge adequately settled. Today's readings were focused on why *NumPy* is faster than normal *Python* and the data types handled as a *NumPy* array.

---

### **Day 8 of #100DaysOfData Challenge**

Today I had the kick-off meeting of the new project I am involved in, with [**Omdena**](https://omdena.com/). For those who do not know what **Omdena** is, it is an *NGO* focus on *AI* and *ML* for good. Apart from that, I could work a little bit on my personal project.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). The little time I had today for this project, I reviewed the data I currently had cleaned it. Remove or complete missing values, remove useless or already used features, etc. For tomorrow I hope I can find some time to start extracting various features from *features* and *description* texts, such as parking, tenure, etc.
2. **Project**: [Building A Recommendation System For Cognitive Exercises and Training Programs](https://omdena.com/projects/cognitive-exercises/) Today was the meeting with the company with which we will work to understand better the goals and requirements of the project or product. The project aims to develop a machine learning algorithm that recommends cognitive exercises and training to people in mental treatment to improve their condition. One of the keys is that it must take into account implicit feedback from the user. So far, I have started by reading different papers and resources suggested as my knowledge is really limited in this field. Also, I am very interested in the way *Omdena* works, with huge freedom and a completely horizontal hierarchy.

---

### **Day 7 of #100DaysOfData Challenge**

After loads of effort and incredibly huge learning, not only on pattern extraction but also about flow and data types, I managed to get the best possible quantity of floor area records. I spent almost the day finalizing the code, but I could read something at the end of the day.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Today, I improved yesterday's mark of 26% to 40% of floor area feature records. It means that I have around 20k houses with floor area information out of 50k houses. However, I don't think it is enough to fill the missing values, so that I will drop the NaN values rows. Also, a sample of 20k houses with a total population of 50k seems enough to make reliable predictions. The next step is to finalize the feature extraction from text features and clean the data before storing it in a SQL server.
2. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): I couldn't read as much as I wish, but at least I finished *IPython* chapter, being surprisingly didactic. From tomorrow, I will start reading the *NumPy* chapter, and hopefully I can grasp deep knowledge on this library.

---

### **Day 6 of #100DaysOfData Challenge**

Yesterday I was so focused on improve pattern extraction that I couldn't write here how was the day. Finally, I could improve the results, but there is still a long way. I could also spend some time with the course and the book.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). As I said, I could improve the floor area extraction, but it is still around 25% of records with information. To be able to work with this dataset, I need to improve such an important feature.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). I also finalized the *Seaborn* section, and hopefully, I can practice what I learnt soon by doing some exploratory analysis in my project.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): Sadly, I spent the least time was reading the book. I could just keep reading the IPython chapter, in this case about time measurement and profiling.

---

### **Day 5 of #100DaysOfData Challenge**

Finally, I beat the pattern extraction issue I was having, and it has been thanks to some essential debugging tips I learnt from the book. However, today most than any, I feel how important it is to settle down the learnings.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). I managed to find my issues with pattern extraction, mainly inappropriate use of data flow and data types. With these, I take two main learnings: first, taking a step back sometimes is more effective than keeping fighting, and second, debugging practices are essential and a weakness I detected and need to improve. The next step will be to improve the patterns list to extract floor area data as current performance is relatively poor.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). Today, I finished the *Matplotlib* section, even though I had already experience using it, it was good to improve my understanding of the OOP way to use it. The next one will be the *Seaborn* library.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): I am currently reading the first chapter, which speaks extensively about IPython. Even though I was already using Jupytern Notebooks that runs with IPython, I didn't know 99% of its features. Today, it was especially useful the debugging one.

---

### **Day 4 of #100DaysOfData Challenge**

Most of the day, I have been battling to extract floor area from the *"description"* and *"features"* texts; after that, I finalised the *Pandas* section of the course and finally started another book.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). As I said, I spent most of the day trying to extract floor data from text features. I have found many issues, mainly due to data types and data flow, when I wanted to solve them. I think I am overcomplicating the functions. Therefore my plan for tomorrow is to start from scratch the functions with what I learned in the first trial loop.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). Today, I finished *Pandas* section of the course, including the Notebook with exercises. So far, I am finding the course quite complete and with a good combination of theory and practice, of course, if you have the will to complete the exercises.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): Finally, today I have started another Python book, the aim is to settle down and complete my Python for Data Science before start going deeper in Machine Learning. I have begun the *Chapter 1*, which is about IPython and gives a basic overview of its added functions to normal Python.
 
---

### **Day 3 of #100DaysOfData Challenge**

Today I spent most of the time on the London Houses project as the extraction of floor area information is quite tricky. Also, I kept watching some videos from the course.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). The main point I have been working on today has been the pattern extraction for the floor area I started yesterday. First, I reviewed and improved the custom functions I built, basically improving the efficiency and dealing with some possible problems it may raise in the future. And second, to try to adapt the functions to work more generally and apply to the *"description"* as well as the *"features"*. I expect to finalize the floor area extraction tomorrow and then decide how to deal with the missing values.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). Today I couldn't progress that much in the course. In this case, I continued watching the *Pandas* section, talking about string, time and date methods and how to deal with these data types in a DataFrame.

---

### **Day 2 of #100DaysOfData Challenge**

Today wasn't the most productive day because I went to get my second Covid-19 jab. But anyway, I managed to spend some time on my house price project and watch some more videos.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Floor area is, in theory, one of the most important features when it comes to determining a house price, but I found that from scrapping features directly from JSON code, I could get around a 20% of the records. With such a small amount, I would very likely drop this feature and lose loads of information. Currently, I am trying to extract floor area information from *"features"* and *"description"* features using pattern recognition. So far, I have succeeded using *"features"*, and the previous 20% turns to 26%. The next step will be to use the *"description"*, which might be more challenging because it is less structured.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). From the course, I watched more videos of the *Pandas* section. Specifically to cover the following functions:
    - **Groupby**: Function to aggregate or combine specific rows or columns, where it is also possible to apply statistical functions, like mean, count, etc. It is handy to summarize a DataFrame using specific values and features.
    - **Cross Section**: This function is related to filter or select data action. It is helpful to use it when the DataFrame has more than one level of index.
    - **Aggregate**: Similar to groupby function but with the extra functionality of passing a dictionary with the statistical operations to apply in specific features.
    - **Concatenate and Merge**: These functions are the most commonly used to join DataFrames with *Pandas*, concatenate basically will join the rows or columns filling the non-common values with NaNs and merge gives you much more options of the type of join we want to perform (inner, left, right or outer) and which column use as joining index.

---

### **Day 1 of #100DaysOfData Challenge**

**Challenge Presentation**: I am starting a repository to track my first #100DaysOfData challenge. Currently, I am looking to have a change in my career from Mechanical Engineer to Data Scientist. So far, I have taken several courses, read books and tried exercises and the famous [Titanic Competition](https://github.com/diequies/Titanic_Kaggle) from Kaggle. But from now and for the next 100 days, I will start recording all the work I do to become a Data Scientist.

I will establish some rules to follow this challenge to make sure I can have the best output:
1. To do something related to Data Science every single day. As a minimum, read some pages of a book, an article, whatever but something.
2. To keep a record of everything I do, then I can go back to check what I have done and review my performance or effectiveness. Also, it would be beneficial if someone arrives at this repository as a summary of resources.
3. Try always to keep activated the three main items, a project, a book/paper and a course or certification.

To start the challenge, I currently have the following activities ongoing:
1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Where I am trying to perform as a primary objective a price prediction on London Houses prices with information scrapped from Zoopla. As a side aim, I want to add as much information as possible from several sources, like crime indexes, distances to tube, etc. and produce some clustering output.
2. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). I have found excellent critiques about this Udemy course. Therefore I am taking it as a review and to settle my current knowledge in Python and Data Science tools. I have already started the course and going through the Pandas module at the moment.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): I haven't started yet to read it, but it seems a good book to, again, settle the knowledge of Python and Data Science I have learnt so far. Also it will be helpful as a reference book.
