# r-template for pixi
This template generates variables, R version and some handy R tasks. You need to have [pixi](https://pixi.sh) installed. 

## Using `pixi exec`
To generate the template in the current folder:
```
pixi exec copier copy gh:roaldarbol/r-template .
```
or to generate a new folder:
```
pixi exec copier copy gh:roaldarbol/r-template my-new-project
```

## Using `pixi init --template`
A feature that is under development is the `--template` flag for `pixi init`. Once that is implemented it will be the preferred way to install templates, the usage will be along the lines of:
```
pixi init --template gh:roaldarbol/r-template
```
