# heroku-notes
Heroku notes.

## Node.js

### devDependencies

For Heroku to build, it needs `devDependencies`, so trick it:
```
heroku config:set NPM_CONFIG_PRODUCTION=false
```
(see http://stackoverflow.com/questions/22954782/install-devdependencies-on-heroku)

## Multiple Buildpacks

https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app
