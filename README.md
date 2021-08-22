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

> ## INSTRUCTIONS TO RUN THE WEB APP:
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
Github link: https://github.com/amandeep4272/online-classroom<br /><br />

<!-- >## SOME SNAP-SHOTS OF THE APPLICATION.


![Screenshot (169)](https://user-images.githubusercontent.com/56021490/121811941-ae2e8b00-cc83-11eb-80a2-ea811a2e138f.png)
---
![Screenshot (170)](https://user-images.githubusercontent.com/56021490/121811970-c7cfd280-cc83-11eb-9290-ba403a4aa6a4.png)
---
![Screenshot (172)](https://user-images.githubusercontent.com/56021490/121811974-c9999600-cc83-11eb-94c4-71dc359a932f.png)
---
![Screenshot (173)](https://user-images.githubusercontent.com/56021490/121811977-ca322c80-cc83-11eb-8cc1-1b82805d5d6b.png)
---
![Screenshot (174)](https://user-images.githubusercontent.com/56021490/121811984-cf8f7700-cc83-11eb-9ef9-d45143400a10.png)
---
![Screenshot (175)](https://user-images.githubusercontent.com/56021490/121811987-d1f1d100-cc83-11eb-9231-635188d184f4.png)
---
![Screenshot (176)](https://user-images.githubusercontent.com/56021490/121811988-d322fe00-cc83-11eb-9f26-1de5e8a55650.png)
--- -->

## License

The source code is released under the [MIT License](https://github.com/sibtc/django-multiple-user-types-example/blob/master/LICENSE).



