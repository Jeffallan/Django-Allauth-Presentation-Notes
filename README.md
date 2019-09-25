## Abstract

This material was presented to hte Omaha Oython User Group on 09/25/19.

Django allauth is a python package that implements user:

    - authentication;
    - registration;
    - account management and;
    - 3rd party authentication.

This presentation covers:

- Getting started with django-all auth.
- Introduces the Django cookiecutter project which implements django-all auth out of the box.
- Creating a custom user model for authentication.
- Integrating social logins to your django application.

This presentation has an accompanying code base which can be cloned from here:

(https://github.com/Jeffallan/Django-Allauth-Demo)

## Viewing This Presentation Locally
- Clone this repository.
- Create a virtual environment and activate it:
```
python -m venv /path/to/ENV
source ENV/bin/activate
```
- Install the the required libraries in your virtual environment:
```
pip install -r requirements.txt
```
To open as a Jupyter Notebook:
```
jupyter notebook
```
To display as a slideshow:

```
jupyter nbconvert --to slides  --ServePostProcessor.port=8001 --ServerPostProcessor.ip='*' --post serve *.ipynb
```

## Good Resources

- [Allauth github page](https://github.com/pennersr/django-allauth)
- [Allauth documentation](https://django-allauth.readthedocs.io/en/latest/)
- [Django cookiecutter github page](https://github.com/pydanny/cookiecutter-django)
- [Django cookicutter documentation page](https://cookiecutter-django.readthedocs.io/en/latest/)
- [A detailed walkthrough](https://medium.com/@ksarthak4ever/django-custom-user-model-allauth-for-oauth-20c84888c318)
- [Another detailed walkthrough](https://wsvincent.com/django-allauth-tutorial-custom-user-model/)

## Helpful Docker Commands
`docker-compose -f local.yml run --rm django python manage.py <command>`
`docker container rm <container>`
`docker volume prune`
