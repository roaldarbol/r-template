# r-template for pixi
This template generates variables, R version and some handy R tasks. You need to have [pixi](https://pixi.sh) installed. 

## Using global installation of `copier`
The current way to use the template is to first install `copier` in your global pixi environment:
```
pixi global install copier
```

You can then use the template with:
```
copier copy gh:roaldarbol/r-template .
```

## Using `pixi exec`
`exec` is a function in pixi under development - once it's implemented, you can run:
```
pixi exec copier copy gh:roaldarbol/r-template .
```

## Using `pixi init --template`
Another feature that is under development is the `--template` flag for `pixi init`. Once that is implemented, the usage will be along the lines of:
```
pixi init --template gh:roaldarbol/r-template
```
