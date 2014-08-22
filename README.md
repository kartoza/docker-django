docker-django
=============

A simple docker container that runs a basic django app. This is intended as a base docker project for you to extend with your own django app.

To build the image do:

```
docker build -t kartoza/django git://github.com/timlinux/docker-django
```

To run a container do:

```
docker run --name "django" -p 9080:80 -d -t kartoza/django
```

To open the web site go to http://localhost:9080

-----------

Tim Sutton (tim@linfiniti.com)
May 2014
