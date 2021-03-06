Zeyuan Liu

this repo is a clone of https://github.com/nelaturuk/education_pathways

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

Activity 1:
![act1](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab3/main/screenshots/Activity%201.png)

Activity 2:
![act2](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab3/main/screenshots/Activity%202.png)

Activity 3:
![act3](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab3/main/screenshots/Activity%203.png)

Activity 4:
![act4-1](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab3/main/screenshots/Activity%204-1.png)
![act4-2](https://raw.githubusercontent.com/Liuzysjtu/ECE444-F2021-Lab3/main/screenshots/Activity%204-2.png)

Activity 5:
Functional Requirement: The system should display courses related to the search keywords
Imporvement: When I entering the keyword "machine learning", the courses displayed on the webpages aren't related to the keyword, whether on course title or course information. What need to further improve is exactly marking the word related to keyword as red, so that user can clearly know why the search result is about the keyword.

Non-functional Requirement: The usability of the system
Improvement: Current website is inaesthetic and lack of navigation bar, which makes users confused at the function and unpleasant to visit again. F-shaped pattern should be adoped on placing important items and a help page should be added to display how to use the website.
