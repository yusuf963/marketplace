## Run virtual env
`virtualenv -p python3.8 .`
## Install virtual env
`pip install Django==4.0.3`
## Check Django version
 `python -m django --version`
## Create Django App
 `django-admin startproject marketplace`
## Run django 
`python manage.py runserver`

## Install a formatter
`python -m pip install -U autopep8`
## Collect static
`python manage.py collectstatic`




deployment  the app on ElasticbeansTalk
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-django.html


`pip install awsebcli `
`eb --version`