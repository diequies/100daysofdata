# **My 1<sup>st</sup> #100DaysOfData Challenge**
In this repository I will track my first challenge of #100daysofdata, using as a summary of my activities, the books I read, the courses I take and the projects I make.

| Projects |
| -------- |
| 1. [**Zoopla London Houses Price Prediction from Scratch**](https://github.com/diequies/zoopla_houses) |

| Course and Certifications |
| ------------------------- |
| 1. [**2021 Python for Machine Learning & Data Science**](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/) |

| Books and Papers |
| ---------------- |
| 1. [**Python Data Science Handbook**](https://jakevdp.github.io/PythonDataScienceHandbook/)

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
