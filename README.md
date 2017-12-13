# How to build the assets

If you haven't installed SASS yet, please run the following command once:

```
sudo gem install sass
```

Then, start the watcher inside the repository root like this:

```
sass --watch sass:stylesheets
```

Your .css files under $ROOT/stylesheets will be updated on the fly as you change your .scss files under $ROOT/sass

# How to push to CF:

```
cf login

cf push
```
