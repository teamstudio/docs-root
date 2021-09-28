# docs-root

This repository contains the **source** files for the root site for the *teamstudio* organization. The generated HTML files are in the separate
*teamstudio.github.io* repository, which should be cloned locally sibling to this repository prior to publishing.

## Installation
* Install Python and pip
* Using pip, install
    * mkdocs
    * mkdocs-material
    * mkdocs-static-i18n
    * mike
 
## Develop and Test
Test the doc using
```
mkdocs serve
```

## Publish
Ensure that you have also cloned the teamstudio.github.io repository, as noted above. 

With that in place, publish using these commands.

``` sh
cd ../teamstudio.github.io
mkdocs gh-deploy --config-file ../docs-root/mkdocs.yml --remote-branch main
```

Don't forget to also commit and push the source changes in this repository!
