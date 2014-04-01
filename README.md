#SPEL Web Site

## Editing content

* First clone this repository in your machine
* Main pages are under _page directory (that simlink to _posts).
* To edit content just modify any of this files, writing in Markwdown style.
* Commit and push changes to master (git commit -am "some message")
* Github automatycally will regenerate site content (git push)

## Adding new pages

* First clone this repository in your machine
* Create a new file under _posts with the following name convention: aaaa-mm-dd-page_name
* Optionaly create a simlink into _page directory
* Add the folowing header

        ------
        layout: page
        title: <Page title>
        ------

* Write content in Markdown format
* OR use an existing file as base
* Add new files to git (git add <files>)
* Commit and push changes to master (git commit -am "some message")
* Github automatycally will regenerate site content (git push)

## Request and issues

Please use git issues tracker to submit requirements and report bugs. (https://github.com/proyectoSuchai/proyectoSuchai.github.io/issues)
