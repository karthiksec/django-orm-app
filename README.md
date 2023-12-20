# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

I![Er diagram](https://github.com/karthiksec/django-orm-app/assets/147473368/1b79b468-5bfc-42ad-8519-6e086f4697ec)


## DESIGN STEPS

### STEP 1:
Create the problem from GitHub
### STEP 2:
Create a new app in Django project
### STEP 3:

Enter the code for admin.py and models.py 

## PROGRAM
```python
models.py
from django.db inport models
from django.contrib import admin
class Football_player (models.Model):
     Name-models.CharField(max_length=20)
     Dob models.DateField()
     Height models. IntegerField()
     Address-models.CharField(max_length=100)
     MobileNo=models. IntegerField()
class Football_player (admib.ModelAdmin):
     list_display=["Name", "Bob", "Height", "Address","MobileNo"]
```
```python
admin.py
from django.contrib impot admin
from.models import Football_player,Football_playerAdmin
admin.site.register(football_player, Football_playerAdmin)
```

## OUTPUT

![output](https://github.com/karthiksec/django-orm-app/assets/147473368/b973b0de-77e4-46df-bfb8-00e6f206a66f)

## RESULT
Thus the program for creating a database using ORM has been executed successfully
