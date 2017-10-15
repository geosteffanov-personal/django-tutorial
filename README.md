# django-tutorial
A repo following through the tutorial on building websites with Django (the official one)


## This is a list of all the steps I've taken and the current django-tutorial level I am on

1. Tutorial 01: The Basics
	- Started the project 'mysite'
	- Started app 'polls'
	- Created the index view of the _polls_ app


2. Tutorial 02: Database setup and Admin Site
	- Set the TZ field ( time zone ) in the settings file as 'Europe/Sofia'
	- Applied the migrate command
	- Defined the preliminary models
	- Added polls app in the settings.py file in mysite/settings.py
	- Ran makemigrations command to create migration
	- Ran 'sqlmigrate' that doesn't really do anything but tell what kind of sql commands will be run
	- 'committed' the migration with 'migrate' command
	- created a few instances of the models
	- created admin
	- registered the polls models in polls/admin.py


3. Tutorial 03: Creating the views (the public interface)
	- created preliminary details, results and vote views
	- edited the index view to display the latest 5 questions
	- created a 'templates' folder in the polls app
	- used a shortcut render
	- added exception handling when there is no specific question
	- added a shortened version for the error handling
	- used url name parameter to remove the reliance on a specific url
 	- added app_name='polls' line to urls.py in polls to create an app namespace and modified the index.html

4. Tutorial 04: Simple form processing and cutting down the code
	- updated detail.html to containt a simple form
	- have NOT made the server respond to the voting action
        - created a results template.
	- modified the results view
	- changed the URLconf of the polls app to make use of generic views
	- created generic view classes

5. Tutorial 05: Automated Testing
	- fixed bug of returning True for 'recency' of future blogposts and created an automated test for that


