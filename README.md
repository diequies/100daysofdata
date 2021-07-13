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

### **Day 13 of #100DaysOfData Challenge**

Today I found difficult to spend time in my Data Science project of life but as a minimum I had 2h working on **Omdena** project and just a little bit on my house pricing project. 

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). I am a little bit stuck with [*Overpass Turbo API*](https://overpass-turbo.eu), as it seems it is giving me problems because of too many attempts. I am trying different ways, like sleep time to wait between requests. Tomorrow I will keep trying other methods.
2. **Project**: [**Building A Recommendation System For Cognitive Exercises and Training Programs**](https://omdena.com/projects/cognitive-exercises/). Today we made a clear statement of the task we have been assigned, data-set acquisition, and specified the different methods we believe we can use to solve the task. While we wait for the data from the partner to decide the best approach, I will start looking for information and a baseline for each.

---

### **Day 12 of #100DaysOfData Challenge**

Quite an intense day today. We had our first team meeting with **Omdena**, I still feel pretty lost, but it is improving. Also, I made the first step forwards on Overpass Turbo API, although still far from what I want.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Today, I had almost no time to invest in this project but, still, I have managed to make some progress using [*Overpass Turbo API*](https://overpass-turbo.eu). I can get now, for each house, using its coordinates, the tube stations within a specific range. The loop is relatively slow, and also I am still playing with the API timeouts. Currently, I am waiting 1 second per request, but I guess I will need to increase that. Once I get the stations related to each house, I have to find a way to estimate its walking distance and select the shortest one. I believe I won't be able to do it with Overpass Turbo API, but I am sure that there are resources out there to do it.
2. **Project**: [**Building A Recommendation System For Cognitive Exercises and Training Programs**](https://omdena.com/projects/cognitive-exercises/). Today, we had our first team meeting, and I wish I was more participative and that we could get more output from it. However I could improve my problem understanding and could suggest one task. This task is to create the dataset via survey, it is quite simple from a Data Science point of view, but it requires time and some research to avoid bias and get the required output. Tomorrow I will draft a path and some possible sub-tasks to propose.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). I keep going with the *NumPy* chapter, now it is going deeper, and it is showing how to do fancy indexing, binning or sorting using *NumPy*. Slow progress, but progress it is.
4. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). I completed the capstone exercise, where we had to use what we have learnt so far from *NumPy*, *Pandas*, *Matplotlib* and *Seaborn*. It was not so difficult but very useful to settle the previous work.

---

### **Day 11 of #100DaysOfData Challenge**

Another day of reading general Data Science articles suggested by **Omdena**, I am also trying to frame the problem myself, but I feel inexperience. I could start the second phase of my house pricing prediction project and continue reading and watching the course, quite a productive day.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). The objective of this new phase is to add more information and features related to the location of the house, such as walking distance to the closest tube station, the density of supermarkets/shops/restaurants, etc. To do so, I will use [*Overpass Turbo API*](https://overpass-turbo.eu), which is an open-source data filtering tool that uses OpenStreetMap data. So far, I am finding the query language a little bit complex, but I am now getting used. Tomorrow I want to extract at least the details of the tube stations in a range of 2km.
2. **Project**: [**Building A Recommendation System For Cognitive Exercises and Training Programs**](https://omdena.com/projects/cognitive-exercises/). Today, apart from keeping reading and trying to catch up on knowledge with my peers, I have started to frame the problem we need to solve. Tomorrow I will continue, and we will have a meeting to share our ideas and repeat the activity altogether again. The purpose will be to define the first tasks and hopefully some subtasks.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). I continued with the *NumPy* chapter, I am learning now the importance of vectorization and how it can improve the efficiency and speed of our code. Also, it explains the main aggregation and arithmetic functions, and the use of mask arrays.
4. **Course**: [2021 Python for Machine Learning & Data Science](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/). After some days not being able to watch more videos of the course, I managed to finish the *seaborn* library module. Nothing entirely new, but quite useful to better understand how it works and some not straightforward functions. The following module is a capstone project for visualization to check what we have learnt so far.

---

### **Day 10 of #100DaysOfData Challenge**

Even though I was focused today to gain knowledge for **Omdena**'s project, I also managed to finalise Zoopla data extraction on my personal project for house pricing prediction. Additionally, as every day, I spend some time reading the book.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). I have finalised data extraction and processing from Zoopla. It has been very tedious, mainly because web scrapping was very slow; I was scrapping information from more than 50k houses (and therefore webpages). Also, the quality of the data encoded was relatively low, and I had to complement it using complex pattern extraction. I am sure that with NLP techniques, it would be much easier. The next step is to add information about the location of the house. I am thinking of something like the closest station, supermarket, etc. and the distance in time.
2. **Project**: [**Building A Recommendation System For Cognitive Exercises and Training Programs**](https://omdena.com/projects/cognitive-exercises/). Today I have been reviewing articles and papers provided by **Omdena** and some shared by the team collaborators. I could also find an interesting survey paper ([link](https://arxiv.org/pdf/2101.06286.pdf)) summarizing some techniques for recommender systems using reinforcement learning and deep learning. So far, it is out of my capabilities, but I found it interesting, and the team might be able to extract values from it. I would be delighted to learn how to implement this kind of model during the project. Tomorrow we have our first meeting to frame the problem, and hopefully, the first task will flourish.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). I continued with the *NumPy* chapter, basically the fundamental operations and why they are different from normal Python. Also, it is reviewing the *ufuncs*, which gives me a good idea of *NumPy* capabilities and a reference to use in my code.

---

### **Day 9 of #100DaysOfData Challenge**

On the first day being part of **Omdena**'s project, I have spent most of the time reading and learning as basically it is my first time in almost all the facets of the project. Also, I kept working on my personal project and reading the book slowly but steady.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). Once I cleared my issues with pattern extraction, I have been able to progress at a good pace. Today I have completed the feature extraction from text features and almost finished cleaning and filling missing values. My plan for tomorrow is to finish the dataset and create the SQL database, which won't be easy as I have never done it.
2. **Project**: [**Building A Recommendation System For Cognitive Exercises and Training Programs**](https://omdena.com/projects/cognitive-exercises/) On the first day of the project, I explored and read all I could from **Omdena**'s internal resources, mainly Git procedures and other articles for data flow and treatment. Also, I have read many articles and papers for recommendation systems, but as it is the first time I face this sort of project, I still need to learn a lot. So my plan for tomorrow is to finish with the internal resources, keep learning about recommendation systems and find any valuable resource that I can share with the team. So far, I am finding quite challenging the interaction and the way of working, but I am sure that soon I will get used to and be able to collaborate more and better.
3. **Book**: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): Today I started the *NumPy* chapter, and again, as it starts from the basics, I am learning a lot. Also, I am understanding now some issues I was having because I did not have the knowledge adequately settled. Today's readings were focused on why *NumPy* is faster than normal *Python* and the data types handled as a *NumPy* array.

---

### **Day 8 of #100DaysOfData Challenge**

Today I had the kick-off meeting of the new project I am involved in, with [**Omdena**](https://omdena.com/). For those who do not know what **Omdena** is, it is an *NGO* focus on *AI* and *ML* for good. Apart from that, I could work a little bit on my personal project.

1. **Project**: [Zoopla London Houses Price Prediction from Scratch](https://github.com/diequies/zoopla_houses). The little time I had today for this project, I reviewed the data I currently had cleaned it. Remove or complete missing values, remove useless or already used features, etc. For tomorrow I hope I can find some time to start extracting various features from *features* and *description* texts, such as parking, tenure, etc.
2. **Project**: [**Building A Recommendation System For Cognitive Exercises and Training Programs**](https://omdena.com/projects/cognitive-exercises/) Today was the meeting with the company with which we will work to understand better the goals and requirements of the project or product. The project aims to develop a machine learning algorithm that recommends cognitive exercises and training to people in mental treatment to improve their condition. One of the keys is that it must take into account implicit feedback from the user. So far, I have started by reading different papers and resources suggested as my knowledge is really limited in this field. Also, I am very interested in the way *Omdena* works, with huge freedom and a completely horizontal hierarchy.

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
