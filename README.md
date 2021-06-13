># online-classroom
>
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Django Version](https://img.shields.io/badge/django-3.2.3-orange.svg)](https://djangoproject.com)


*An online classroom where students taking the exam are divided into panels and are evaluated by a percentile ranking system.
This is implemented in python framework Django, javascript and styled with CSS and bootstrap classes. There are two types of authentication present, one for the teacher and the other for the student.*<br />


### Functionalities.<br />
---
*A Teacher can create panels and add quizzes for them. When a user with student role register, he/she have to select which panel do he/she belongs (as provided by the administration).
<br />Now when the student sign-in, only the exam that belongs to his/her panel will be shown to his/her feed.<br /> On completion of the exam he/she gets the absolute numbers scored.
while in the teacher's dashboard results of all the panels and the students who have given the exams are available. <br  />There Teacher can examine the panel-wise statistics (like maximum, minimum, and average scores
in the particular panel) and the data for the percentile distribution of respondents' scores in a particular panel.*<br />

> ## Instructions to run this web app:
---
#### Clone the repository by running the following command in your command prompt. 
```console
git clone https://github.com/amandeep4272/online-classroom
```
### After activating your virtual environment and entering into this project's directory from your terminal follow these steps:<br />
+ Step 1: Enter into the directory userAuth.<br />
+ Step 2: Enter the following command<br />
 ```console
pip install -r requirements.txt
```

+ Step 3: To run the server enter the following command<br />
```console
  python manage.py runserver
```

  Open localhost:8000 in your browser to open the home page of our website<br />

Github link: https://github.com/amandeep4272/online-classroom<br />
