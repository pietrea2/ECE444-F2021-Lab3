# CARTE Education Pathways

Adam Pietrewicz

This repo is a clone of https://github.com/nelaturuk/education-pathways 

Activity 1 Screenshot:

![Activity 1 Screenshot](https://user-images.githubusercontent.com/60241038/135723990-f610c55b-5343-46f1-9f49-af17be597f8f.png)


Activity 2 Screenshots:

![Activity 2 Screenshot](https://user-images.githubusercontent.com/60241038/135724010-d4a9e3d3-c568-4b49-a1eb-224f240ac950.png)

![Activity 2 Screenshot 2](https://user-images.githubusercontent.com/60241038/135724019-302f4e4a-6a53-4bc4-a127-860960a6f8ad.png)


Activity 3 Screenshots (Building Docker Image):

![Activity 3 Screenshot 1](https://user-images.githubusercontent.com/60241038/135724744-22aa80fd-a434-4544-9823-6b6c4f730ba2.png)

![Activity 3 Screenshot 2](https://user-images.githubusercontent.com/60241038/135724749-d7d928bc-2cf7-483d-8dcf-273477b78ad8.png)








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
