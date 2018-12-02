# About

[![CircleCI](https://circleci.com/gh/heroku/java-getting-started.svg?style=svg)](https://circleci.com/gh/heroku/java-getting-started)

## User guide

Steps to create and deploy on heroku
* Download this source code

```bash
git clone https://github.com/ddovnar/herokujavaweb.git
```

* Open folder `herokujavaweb`

```bash
cd herokujavaweb
```

* Create new heroku app

```bash
heroku create
```

* Create database

To show installed heroku addons on app:

```bash
heroku addons
```

To add postgre database, goto heroku on web browser and add manualy postgresql database addons.
Then to check if it's created success, use command.

To show database connection jdbc-url:

```bash
heroku config
```

Setup database connection in the .etc-file

* Push to heroku server

```bash
git push heroku master
```

* Run application