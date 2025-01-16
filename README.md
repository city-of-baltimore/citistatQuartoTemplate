# Citistat Quarto Template

OPI is abandoning powerpoint decks for interactive quarto documents. This is the template for citistat meetings.

## Install and use

There are two possible ways to install and use this template.

### Create new folder and template

In this scenario, an analyst is starting a fresh new quarto doc in a new or existing folder. The following line will create a boilerplate `.qmd` template with Citistat branding in a new or existing folder:

``` bash
### do this in the "terminal" of Rstudio, not the "console"

quarto use template city-of-baltimore/citistatQuartoTemplate
```

After the line is entered, there will be a few questions about permissions and whether a new folder should be created. Be aware that the boilerplate `.qmd` template file that gets created will take the name of its folder. That means it will overwrite an existing `.qmd` file if it has the same name.

### Install template into existing folder/document

In this scenario, an analyst already has a folder with a quarto file and maybe some related data and code files. The template and branding just needs to be added to an existing file.

The template style can be installed into an existing folder using the following command:

``` bash
### done in the "terminal" of Rstudio, not the "console"

quarto add city-of-baltimore/citistatQuartoTemplate
```

Then the line `format: citistat-html` needs to be added into the yaml at the top of the `.qmd` to add the OPI branding.

### Links to learn more about quarto extensions

-   [Official Quarto Extension](https://quarto.org/docs/extensions/listing-formats.html)
-   [Extension examples from 'schochastics'](https://github.com/schochastics)

### Quarto basics

-   [Installing and starting](https://quarto.org/docs/get-started/hello/rstudio.html)
-   [Common Quarto commands](https://quarto.org/docs/visual-editor/options.html)
