# DA1-Capstone

**Analysis of Movies and TV Shows Available on Netflix**

=======

**Project Overview**
This project assembles datasets of movies and tv shows from Netflix and explores what is the most often watched.

Once the project is running, it will provide a means for researching information to identify:
    *   the oldest movies on Netflix
    *   display ratings by content
    *   top actors on Netflix TV shows and movies
    
The Netflix data may compare entertainment choices by titles, date of release, duration, genre, IMDb ratings and description.

Total Records:
    Ratings Dataset: 19,375 rows, 5 columns
    Netflix Dataset: 8,800 rows, 7 columns

**Project Requirements**
VSCode
Jupter Notebook
GitHub repository
pandas
sqlite3
numpy
matplotlib.pyplot
seaborn
WordCloud

**Project Setup Instructions**
• Copy the code link to this repository and clone to your computer.
• Open the repository folder in a code editor, and create the virtual environment in that folder.
• Create and Activate a Virtual Environment(commands in table above)
• Install the requirements.txt file
• When you are finished, deactivate the virtual environment and close the repository folder.

**Virtual Environment Instructions**
---
1.  After you have cloned the repo to your machine, navigate to the project folder in GitBash/Terminal.
2.  Create a virtual environment in the project folder.
3.  Activate the virtual environment.
4.  Install the required packages.
5.  When you are done working on your repo, deactivate the virtual environment.

**Virtual Environment Commands**

-Linux/Mac

Create -    python3 -m venv venv
Activate -  source venv/bin/activate source venv/Scripts/activate
Install -   pip install -r requirements.txt pip install -r requirements.txt
Deactivate- deactivate

-Windows/GitBash

Create  -   python -m venv venv
Activate -  source venv/bin/activate
Install -   pip install -r requirements.txt
Deactivate- deactivate

**Data Dictionary**

type (object) - identifies two categories of media - Movies and TV Shows
title (object) - names of movies and TV shows
Year Released (int) - year movies and TV shows were released
rating (object) - ratings for movies and TV shows
duration (object) - length of movies and TV shows
casts (object) - actors in movies and TV shows
description (object) - summary of movies and TV shows
genres (object) - descriptive types of entertainment