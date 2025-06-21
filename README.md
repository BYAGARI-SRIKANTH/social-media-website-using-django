# Django Social Network

A social media web-application with Django.

<h2>📷 Images of the Website</h2>

<div align="center">

  <img src="https://github.com/BYAGARI-SRIKANTH/social-media-website-using-django/blob/main/photos/photo1.png" alt="Photo 1" width="30%" style="margin: 10px;" />
  <img src="https://github.com/BYAGARI-SRIKANTH/social-media-website-using-django/blob/main/photos/photo3.png" alt="Photo 2" width="30%" style="margin: 10px;" />
  <img src="https://github.com/BYAGARI-SRIKANTH/social-media-website-using-django/blob/main/photos/photo4.png" alt="Photo 3" width="30%" style="margin: 10px;" />

  <br />

  <img src="https://github.com/BYAGARI-SRIKANTH/social-media-website-using-django/blob/main/photos/photo5.png" alt="Photo 4" width="30%" style="margin: 10px;" />
  <img src="photos/photo5.jpg" alt="Photo 5" width="30%" style="margin: 10px;" />

</div>


## Features :

<li>Sign Up, Login, OAuth 2.0(Google, Github), Logout, Forgot Password</li>
<li>Public Profile view</li>
<li>Create, Edit, Delete Posts with customized text, pictures and links</li>
<li>Like, Comment / Reply, Save and Search posts</li>
<li>Follow and Unfollow users to view their posts</li>
<li>Friend Request</li>
<li>Notifications</li>
<li>Chats using websockets</li>
<li>Video Calls</li>



## Adding env variables

- Add env variables to ".test.env" and rename it to ".env"

- Add GOOGLE_RECAPTCHA_SECRET_KEY to both .env and the file mentioned below https://github.com/Ronik22/Django_Social_Network_App/blob/main/users/templates/users/register.html#L45

- Add agora app_id to .env and to https://github.com/Ronik22/Django_Social_Network_App/blob/main/blog/static/blog/js/streams.js#L2

## Installation

```bash
    $ python -m venv venv
    $ source venv/Scripts/activate
    (venv) pip install -r requirements.txt
    (venv) cd Django_Social_Network_App
    (venv) python manage.py makemigrations
    (venv) python manage.py migrate
    (venv) python manage.py createsuperuser
    (venv) python manage.py runserver
```


## Add django-allauth config

https://django-allauth.readthedocs.io/en/latest/installation.html#post-installation

## Others

- To use other DB edit this https://github.com/Ronik22/Django_Social_Network_App/blob/main/myproject/settings.py#L107
- To use other providers edit this https://github.com/Ronik22/Django_Social_Network_App/blob/main/myproject/settings.py#L205
- To use redis instead edit this https://github.com/Ronik22/Django_Social_Network_App/blob/main/myproject/settings.py#L197

## Running Tests

To run tests, run the following command

```bash
  python manage.py test
```
