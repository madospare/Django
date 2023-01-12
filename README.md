# Django
 
# In cmd ...

* Find correct directory (C:\Users\[Username]\Documents\GitHub\[Folder name])
* Write: pipenv shell

# Run server
* Write: python manage.py runserver

# Create a new app
* Write: python mamage.py startapp [app name]

# Create admin user
* Write: python manage.py createsuperuser
* Fill inn username, email and password

# Python shell console
* Write this to enter shell: python manage.py shell
* Write this to exit shell: exit()

# Search for an object in python shell console
* Write: [var name] = [name of object].objects
* Write this for a list of all of this object: [var name].all()
* Write this to filter by name & letters: [var name].filter(name__startswith="[filter symbols]")
* Or write this to filter by id: [var name].filter(id=[id number])

# Misc commands for python shell console
* To save a variable: [var name].save()
* To delete a variable: [var name].delete()