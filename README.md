# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from github

### STEP 2:
Create a new app in Django project

### STEP 3:

Enter the code from admin.py and models.py

### STEP 4:
Execute Django admin and enter ten football players

## PROGRAM

models.py
from django.db import models
from django.contrib import admin
class football_players(models. Model):
  first_name=models. CharField(max_length=30)
  last_name=models. CharField(max_length=30)
  dob=models.DateField()
  age=models.IntegerField()
  matches_played models. IntegerField()
  total_goals=models. IntegerField()
  email=models. EmailField()
class football_playersAdmin(admin. ModelAdmin):
  list_display=
('first_name', 'last_name', 'dob', 'age','matches_played', 'total_goals', 'email')
admin.py
 from django.contrib import admin
from.models import football_players, football_playersAdmin
admin.site.register(football_players, football_playersAdmin)

## OUTPUT

![Screenshot 2023-12-30 162309](https://github.com/PREETHI3312/django-orm-app/assets/151625222/10b0b7c3-952f-4d41-a98c-3defe4132988)
.


## RESULT
Thus the program for creating database using ORM has been executed successfully
