```diff
+ Disclaimar!
  The ultimate goal of this project was to learn Django, but it will be kept private
  Live version: http://weblab.pt/
```
# WebLab Project
This project aims to offer healthcare software solutions to physiological laboratories. 
At this stage, our app offers a tool for writing and managing medical reports. A future goal is a full featured platform that allows you to review and report physiological exams.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


### Installing

We recommend installing a virtualenv first for development.

1. Activate your env and run 'pip install -r requirements.txt' to install all dependencies
2. run 'python manage.py migrate'
3. then 'python manage.py createsuperuser 
4. start the development server with the command 'python manage.py runserver'. 
    
### Admin setup
Login with as superuser and go to the admin url and:
1. Create an Entity
2. Create at least an exam type
3. Create at least 1 device
4. Create at least one report template per exam type
5. Create the following Status:
    - pending
    - flagged
    - done


## Deployment
At the momment the platform is running on Heroku. 
If you need to run something only in development or production environment you can do something like
'''python
if production():
    #doStuff '''


## Built With

* [Django](https://www.djangoproject.com/) - Django 

## Authors

* **Vinicius Duarte** -  [vduarte06](https://github.com/vduarte06)
* **Bruno Mendes** -  [BrunoEMendes](https://github.com/BrunoEMendes)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

Commercial

## Acknowledgments


