README
================

Build
----------------

```bash
$ docker build -t 'koduki/rails' .
```

Create project
----------------

```bash
$ docker run -it -p 3000:3000 -v `pwd`:/usr/src/app -w /usr/src/app koduki/rails bundle install
$ docker run -it -p 3000:3000 -v `pwd`:/usr/src/app -w /usr/src/app koduki/rails rails new .
```