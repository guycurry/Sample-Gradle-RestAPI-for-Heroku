# Sample-Gradle-RestAPI-for-Heroku

A VERY SIMPLE Gradle Rest API app, which can easily be deployed to Heroku.

## Setup Code Locally

Make sure you have Java installed.  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```sh
$ git clone https://github.com/heroku/gradle-getting-started.git
$ cd gradle-getting-started
$ ./gradlew stage
```


## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku open
```

## Finally

You will have to add '/greeting' to the end of the heroku app URL in order to get the expected JSON response.

- [Java on Heroku](https://devcenter.heroku.com/categories/java)# Sample-Gradle-RestAPI-for-Heroku
