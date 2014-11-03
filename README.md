# SPEL Web Site

## Editing content

* First clone this repository in your machine
* Main pages are under _page directory (that simlink to _posts).
* To edit content just modify any of this files, writing in Markwdown style.
* Commit and push changes to master (git commit -am "some message")
* Github automatically will regenerate site content (git push)

## Adding new pages

* First clone this repository in your machine
* Create a new file under _posts with the following name convention: aaaa-mm-dd-page_name
* Optionally create a simlink into _page directory
* Add the following header

        ------
        layout: page
        title: <Page title>
        ------

* Write content in Markdown format
* OR use an existing file as base
* Add new files to git (git add <files>)
* Commit and push changes to master (git commit -am "some message")
* Github automatically will regenerate site content (git push)

## Adding images

To easily add images centred and responsive inside post and pages the image.html
include was created. It is used as follows:

    {% include image.html src="path_to_image" title="image_description" %}
    
For example, the following code is added in a markdown text to add an image from 
*images/test_brasil/* path and the description *Image* in the bottom:

    {% include image.html src="images/test_brasil/suchai_inpe_1.png" title="Image" %}

## Request and issues

Please use git issues tracker to submit requirements and report bugs. (https://github.com/proyectoSuchai/proyectoSuchai.github.io/issues)
