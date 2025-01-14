# Citistat Quarto Template

OPI is abandoning powerpoint decks for interactive quarto documents. This is the template for citistat meetings.


## Install and use

There are two possible ways to install and use this template.


### Create an new folder and template

In this scenario, an analyst is starting a fresh new quarto doc in a new folder. A folder will be created, with a bloilerplate `.qmd` template and the Citistat branding. The `.qmd` template is then editted with original content.

The following line will create a new folder containing a boilerplate `.qmd` template with Citistat branding:

```bash
quarto use template city-of-baltimore/citistatQuartoTemplate
```



### Install into existing folder

In this scenario, an analyst already has a folder with a quarto file and maybe some related data and code files. The template just needs to be added to an existing file. 


The template style can be installed into an existing folder using the following command:

```bash
quarto add city-of-baltimore/citistatQuartoTemplate
```

Then the line `format: citistat-html` needs to be added into the yaml at the top of the `.qmd` to add the OPI branding.



### Links to learn more about quarto extensions

* [Official Quarto Extension](https://quarto.org/docs/extensions/listing-formats.html)
* [schochastics example](https://github.com/schochastics)

### Quarto basics
* [Installing and starting](https://quarto.org/docs/get-started/hello/rstudio.html)
* [command commands](https://quarto.org/docs/visual-editor/options.html)
