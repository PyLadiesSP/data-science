#Fundamentals of Social Data Science#|

This is the course repository for the introductory python course in Oxford's Social Data Science program.

This course, currently named Python for Social Data Science, teaches the skills needed to begin working in soical data science. This focuses first on programming skills in python. It includes some key basic programming skills, such as lists and functions, as well as more abstract and complex topics like API access, file types, text processing and dataFrames.

Data science is an emerging discipline concerned with the processing and management of data. Because data is now so prevalent, complex and volumous there is a niche for those with specific skills in data processing. Data science has four pillars: theory, data access, data wrangling and data analysis.

This course only goes into very rudimentary detail on theory and analysis. Theory in our degree program is taught through the course "Foundations of Social Data Science". Analysis is partially taught with a focus on descriptives. But it is undoubtedly the case that data science is steeped in statistics. In our program statistics skills are taught in two other courses, Statistics for Social Data Science and Intro to Machine Learning. That said, some skills in this course really do benefit from knowing a little theory and a little statistics, so you will encounter some basic theoretical ideas in the pages in this repository. For example, in Week 4, lecture 1 on visualization, several visualization frameworks are included and the visualizations will be based off of some standard statistical distributions, like a normal distribution or an exponential distribution.
The repository

The repository consists of four main folders:

    course work,
    assignments,
    supplementary data (public),
    supplementeary data (withheld).

The latter one is really just more data that should be in the supplementary data folder but for licensing reasons we will not be sharing that data in a public GitHub repository. In the case of the database of tweets, this is unavoidable as per the licensing agreement for use of the Twitter API is not to share tweets collected.

In the assignments folder are the assignments and some model answers (where available). The model answers were typically drafted by teaching assistant Patrick Gildersleve. Updated versions of these can also be found at Patrick's own GitHub repository for model answers.
About this course.

Some of the information about programming in the course is partial. It's not meant to be incorrect, but we are definitely omitting or papering over certain topics for brevity's sake. The goal here is to get people the skills and wisdom to put a study together for analysis and publication. In that sense, this course is a little more directed but also more concise than a repository such as Jake Vanderplas' Python for Data Science. Jake's repository, by contrast appears to be much closer to emphasizing completeness.

You will also notice various Muppet-themed examples throughout the course. This is because as a television show, Muppets offer an extensive amount of accessible data, from episode guides to wikipedia profiles on characters. This can help give is a flavor for high dimensional data while steer a little clear of some complex theoretical issues that are sure to arise in a more focused and sustained project.
How to run these files

The course is written almost entirely in Jupyter notebooks. We recommend downloading the Anaconda package for scientific python, installing it and then launching the Anaconda Navigator. This navigator provides access to a host of scientific programming tools and particularly to JupyterLab. Run Jupyter lab and then navigate to a folder that includes the .ipynb files.
Running this course in a browser

Python notebooks can be run directly in the browser using Google Collab. To do this, simply get a url from a notebook page, such as github.com/oxfordinternetinstitute/sds-python/blob/master/Course_Material/Week_0/PySDS_week0_lecture1.ipynb Then, where it says github.com replace this with: https://colab.research.google.com/github so you would navigate to: https://colab.research.google.com/github/oxfordinternetinstitute/sds-python/blob/master/Course_Material/Week_0/PySDS_week0_lecture1.ipynb in order to run that page in the browser.
Week 1. Introduction to Programming in Python.

This week teaches the basics from variable types, loops, execptions and functions.
Week 2. Data Wrangling

This week covers the basics of working with the Python for Data Analysis library (pandas). We look to DataFrames, SQL, XML and JSON. We parse datetime objects and introduce regular expressions.
Week 3. Accessing and exploring data

This week examines ways to collect data from the web, how to examine that data and how to turn it into a table or DataFrame for analysis.
Week 4. Research and presentation skills

This week presents skills in data visualization, working on a server, ethical data access and LaTeX. It is more oriented towards lectures than the prior two weeks. To that end, you will see several .pdf files here based on lectures created in PowerPoint and LaTeX beamer.
