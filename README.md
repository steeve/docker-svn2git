docker-svn2git
==============

svn2git Docker image

Run with:
```
$ docker run --rm -i -t steeve/svn2git
```

You can of course mount your volumes with your local files, for instance:
```
$ docker run --name mycode -v /mycode debian:wheezy true
$ docker run --rm --volumes-from mycode -i -t steeve/svn2git
```
