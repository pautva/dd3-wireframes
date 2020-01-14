# API Guidance Document

[API Guidance Docs on Gitlab pages](http://apis.glpages.ad.nerc.ac.uk/api-guidance-docs)

Project is based on [docsify](https://docsify.js.org/) documentation site generator.

## Updating pages

* Edit markdown files directly in [Gitlab](https://kwvmxgit.ad.nerc.ac.uk/apis/api-guidance-docs/tree/master/docs) or click the 'Edit on Gitlab' button on any page and it will take you the right file.
* Make your changes and commit (or submit a merge request for somebody else to review).
* Once the changes merge into master it will be deployed on [gitlab pages](http://apis.glpages.ad.nerc.ac.uk/api-guidance-docs)

![Edit on gitlab](https://i.ibb.co/9hgk9kY/edit-on-gitlab.png)

## Creating new pages

* Create a new markdown file in docs folder (e.g. `readonly-methods.md`)
* Add a line in the `_sidebar.md` to create a link to that file in the sidebar (e.g `-  [Readonly Methods](readonly-methods.md)`)
* Once the changes merge into master it will be deployed on [gitlab pages](http://apis.glpages.ad.nerc.ac.uk/api-guidance-docs)

## Running documentation localy

You can also run the project locally, make the changes and then submit your changes to gitlab.

* Pull the project to your computer
* cd into api-guidance-docs
* Run the project - `docsify serve ./docs`
* Website will run on `http://localhost:3000/`


