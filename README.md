# DSE-Static-Cookiecutter

[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template a Static-Site Digital Scholarly Edition

## Quickstart
* Install the latest Cookiecutter if you haven't installed it yet (this requires Cookiecutter 1.4.0 or higher) by running `pip install -U cookiecutter`
* To generate a new dse-static-site project run `cookiecutter gh:csae8092/dse-static-cookiecutter` and answer the following questions, see below:

```json
{
    "directory_name": "dse-static",
    "project_title": "Digital Scholarly Editions Static Site Cookiecutter",
    "project_short_title": "DSE Static-Site",
    "github_url": "https://github.com/csae8092/dse-static-cookiecutter",
    "html_head": "DSE-Static",
    "color_main": "#88dbdf",
    "color_hover": "#fff",
    "title_xpath": ".//tei:title[@level='a'][1]/text()"
} 
```