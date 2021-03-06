# Sample-Gradle-RestAPI-for-Heroku

A VERY SIMPLE Gradle Rest API app, which can easily be deployed to Heroku.

## Setup Code Locally

Make sure you have Java installed.  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```sh
$ git clone https://github.com/guycurry/Sample-Gradle-RestAPI-for-Heroku.git
$ cd Sample-Gradle-RestAPI-for-Heroku
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

## References

I combined the following two sources into this sample heroku app

- [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
- [Getting Started with Gradle on Heroku](https://devcenter.heroku.com/articles/getting-started-with-gradle-on-heroku)
