# heroku-buildpack-clickfunnels

This buildpack will run the `bin/prepare` script as part of a
deployment.

To use this buildpack run this command, substituting the correct app
name for `your-app`

```
$ heroku buildpacks:add --index 2 https://github.com/Etison/heroku-buildpack-clickfunnels
```

Doing the above will _add_ this buildpack to the build pipeline, leaving
other buildpacks in place. If you already have 2 or more buildpacks you
may want to adjust the number passed to `--index`.

