docker-ssh
==========

A simple docker container that runs ssh

To build the image do:

```
docker build -t kartoza/django git://github.com/timlinux/docker-django
```

To run a container do:

```
docker run --name "ssh" -p 2222:22 -p 9080:80 -d -t kartoza/django
```

To log into your container do:

```
ssh root@localhost -p 2222
```

Default password will appear in docker logs:

```
docker logs <container name> | grep root login password
```

To open the web site go to http://localhost:9080

-----------

Tim Sutton (tim@linfiniti.com)
May 2014
