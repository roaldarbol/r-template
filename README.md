# Pixi Template for R

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier)

# Features
- Use the R version you want
- Sets library paths to `.pixi`
- Supports multiple IDEs (RStudio, VS Code, JupyterLab, Positron)
- Use tasks to quickly open the project in your preferred IDE

# Usage
To use the template it is required to have [pixi](https://pixi.sh) installed.

Then, generate the template in the current folder:
```
pixi exec copier copy gh:roaldarbol/r-template .
```
or to generate a new folder:
```
pixi exec copier copy gh:roaldarbol/r-template my-new-project
```

Then, from the terminal open your project in your preferred IDE with cross-platform commands:
- RStudio: `pixi run rstudio`
- Visual Studio Code: `pixi run code`
- JupyterLab: `pixi run jupyter lab`
- Positron: `pixi run positron`
