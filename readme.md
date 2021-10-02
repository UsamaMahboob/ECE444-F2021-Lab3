# Activity 1:

![part1](https://user-images.githubusercontent.com/51336964/135734471-fe539431-5bc5-4ceb-a3a1-0bcfdbdbe5a4.PNG)

# Activity 2:
# Disclaimer:
Name: Usama Mahboob
This repository is a copy of https://github.com/nelaturuk/education_pathways

![part2](https://user-images.githubusercontent.com/51336964/135734488-8acc48c2-e3f0-4ffd-b628-95e20b4a9c6d.PNG)

# Activity 3:
![part3](https://user-images.githubusercontent.com/51336964/135734487-04e334f4-fafc-4ca5-9a97-d933163d8a65.PNG)

# Activity 4:

![part4](https://user-images.githubusercontent.com/51336964/135734516-839b4388-74a2-4545-8831-df6053a4f408.PNG)
![part4_2](https://user-images.githubusercontent.com/51336964/135734514-4bca6fbc-af84-404a-818f-ab082159d025.PNG)

# Activity 5: 
One functional requirement I would like to improve is when I press search without giving any input in the search filters, it would give me a list of all the courses available instead of doing nothing.

One non functional requirement i would like to improve on is the system usability of the website. For example in the search box when you type "engineering" it shows courses that are relevant to this keyword but when i type "engineering." nothing shows up. So i would improve the error checking in the search box inputs, or even ask users if they meant to type "engineering" if they typed "engineeering". 

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
