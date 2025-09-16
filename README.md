# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from Car Inventory Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
from django.contrib import admin
class Movies(models.Model):
    M_ID = models.IntegerField(primary_key=True)
    M_name = models.CharField(max_length=100)
    Release_date=models.DateField()
    Director=models. CharField(max_length=50)
    Actors=models. CharField(max_length=100)
from .models import Movies
admin.site.register(Movies)
class MoviesAdmin(admin.ModelAdmin):
    list_display=('M_ID', 'M_name', 'Release_date```

```


## OUTPUT
<img width="1906" height="972" alt="image" src="https://github.com/user-attachments/assets/7ddedd1c-db02-4051-aa2d-741bd53fc6e4" />



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
