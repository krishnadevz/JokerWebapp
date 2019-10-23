# Jokerpollwebapp
# this is a Jokerpollwebapp created in django 

<br>

# Following are steps for how i setup project and all things you need to know if you ae begginer to Django 
And this project go according to the django documentation and here is no erros so you can use for yourself and i used basic bootstrap overhere and i create gif type project view for that i used <b>ScreentoGif</b> convertor overhere you can see that

# View of Project in Gif(Graphics Interchange Format) form
<br>
<img src="https://github.com/krishnakakade1999/pollswebapp/blob/master/Gifviewproject/demokrishna.gif" alt="one">

# Steps for steuping djago project also you can check out my blog on Medium end of this readme  link is Give

Step 1 First make your own Directory in windows Command prompt or in Powershell using command ```mkdir mydjango``` for example -mydjango i used here

Then simply change that directory using command ```cd Mydjango```

Step 2 Then lets make your own virtual environment in that directory for that particular project using command ```python -m venv myenv```

venv is virtual environment -m is for make i guess

After that you to activate your virtual environment using command

command :- ```myenv\Scripts\activate```

Then you to install django in that particular directory using command

Command :- ```pip install django```

Note:- in your system before doing this python is installed this is must for working of django commands and pip also

and after that for creating django project command is

Command :- ```django-admin.exe startproject mysite .```

. for the directory structure if donot used then you can experience that i experience that :))

And after that you can run your project using

Command ```python manage.py runserver```

```127.0.0.1:8000``` on your local system ok

and for creating app in django in your particular directory ```python manage.py startapp myapp```

and for migrations of databases make sure add your app in settings.py file in installed app section ok

And for creating superuser for admin interface use command

Command :- ```python manage.py createsuperuser```

and then migrate that particular file using

Command using ```python manage.py migrate```
form creating pages for home page ```127.0.0.1:8000```
we have to create new app  in django using ```python manage.py startapp pages```

and check your browser for django project working

See using this command ```localhost:8000 ```port and for admin pannel or adding mannualy questions in database use this
```localhost:8000/admin``` and for admin access you have to create <b>superuser</b>
<br>
# You can check it out my blog for setuping django on windows machine on Medium 
<a href="https://medium.com/@krishnakakade77" target="_blank"><b>krishnakakade</b></a>
<br>

# REFERENCES
<b>Official Django Documentation And Youtube Tutorials For Beginners On django Ex traversymedia and Freecodecamp</b>

# Thank you 
