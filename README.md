# Heroku Buildpack Yarn

Simple buildpack helping to initialize private npm registries using yarn specification.


## How to install

You should add this buildpack before the nodejs basic flow (`heroku/nodejs`).

```bash
heroku buildpacks:add https://github.com/RuBAN-GT/heroku-buildpack-yarn.git -i 1
```

If you want to use private registry your environment should have configured variable `NODE_AUTH_TOKEN`.
