
# heroku-deno-getting-started

## Running Locally
Make sure you have [Deno](https://deno.land/) and the [Heroku CLI](https://cli.heroku.com/) installed.
```
$ git clone https://github.com/chibat/heroku-deno-getting-started.git
$ cd heroku-deno-getting-started
$ deno main.ts --allow-net --allow-env
```

## Deploying to Heroku
```
$ heroku create --buildpack https://github.com/chibat/heroku-deno-buildpack.git
$ git push heroku master
$ heroku open
```






