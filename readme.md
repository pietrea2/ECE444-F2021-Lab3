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


Activity 4 Screenshots:

![Activity 4 Screenshot 1](https://user-images.githubusercontent.com/60241038/135727130-3435e5e4-6f32-41b7-adbd-cc49f25c1b90.png)

![Activity 4 Screenshot 2](https://user-images.githubusercontent.com/60241038/135727140-23b8dd2b-4b10-404d-a26e-0602b8a6058d.png)


Activity 5, Feedback on EP application:

Hello! This is Adam here. After running the Education Pathways application on my computer, I had a chance to test it out and see how it works.
One functional requirement of this system is: the system must clearly display all search results to the user, or indicate to the user how the system responded their request.
This course exploration system must let the user know if any results were found, so that the user is not confused.
This is a functional requirement I want to improve right away because when I was playing with the application, I did not see any course results when I tried to use the search bar.
I don't know if the application understood my search or if it even looked for the courses because the page stayed blank after I hit the search button. Nothing changed. So I don't know if I used the application correctly.
I would want to print out messages to the user everytime they hit the search bar, to either let them know courses were found, if nothing was found, or if it was an invalid search.

Next, a non-functional requirement of this system is: usability.
This application must be easy and intuitive to use for end users. Otherwise...why would they want to use it for course exploration?
Therefore, usibility is something I want to improve in this system by updating the user-interface and layout of the application page.
Right now, the main search page is just coloured white, and the search bars/buttons are not too appealing. Therefore i want to update the interface to have an intuitive layout of the search buttons and bars. So the end user has no problems figuring out how to use the application.
Usibility is rooted from the user-interface of an application, if there is bad UI, then an application can be deemed un-usable.





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
