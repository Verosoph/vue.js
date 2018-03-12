# vue.js
how to use vue.js

## install

clone the repo:
build the docker: 
```
$ docker build -t mysite .
```
start the docker container:
```
$ docker run -p 8080:80 -d -v source_edirectory:/var/www/site mysite

```

source_directory is the directory where your project is located
