# Task Title: Django Models

1. Create a new GitHub repository with a README.md, and Python .gitignore file.

2. Clone it to your machine/computer, which will create a new folder on your computer with your repository’s content.

3. Create a new virtual environment in that folder named .env and install Django in it.

4. Create a new Django project. Use your Zuriboard Student ID as the name of the project.

5. Create a new application using the Django startapp command. The app should be called blog.

6. Add the blog app to the main_projects INSTALLED_APPS.

7. Create a new model in the blog app called Post. It should have the following fields:

 **Post**

**--------**

**Title : A string of maxlength 200, use Django’s models.CharField** 

**Text : Any amount of text, use Django’s TextField**

**Author : A Foreign Key to the current user model. Make use of Django’s get_user_model function.**
 
**Created_date : A date-time column, use Django’s models.DateTimeField.**

**Published_date : A date-time column, use Django’s models.DateTimeField.**

8. Create migrations for your new model using the makemigrations Django command. 

9. Run all migrations using the migrate Django command.

10. Stage and Commit your Django project and push your changes to your GitHub repository.

11. Ensure your final code/submission is on the default branch of your GitHub repository.