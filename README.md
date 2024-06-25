[![HTL-Grieskirchen](http://www.htl-grieskirchen.net/fileadmin/bilder/logo.png)](http://htl-grieskirchen.net)
# Showcase 2023-24


Click here to open the projects:

====================
# [**List of projects**](https://alfredDoppler.github.io/HTLGrieskirchenShowcase2023-24/)
====================



The projects in this repository are for demonstration purposes only. 
All copyrights and trademarks belong to their rightful owner.
If there is any problem with any demo just leave a short message.



Many thanks to my student Elias Lexl for the creation of this site.
Additional thanks go to Rene Buchmayr and Alexander Melem for providing the
first solutions of how to run the GIT-repository Web GL games directly in the browser.

@students:
You must change the Compression Format in the Unity Player settings to "Disabled" before creating the WebGL Build:

![CompressionFormat](https://github.com/AlfredDoppler/HTLGrieskirchenShowcase2023-24/assets/19311233/6bdf692d-2cf0-4f22-babb-b08d31e3d4a4)



After uploading your project to the `projects-folder` update the `projects.json`.
(Maybe uploading a Development build with WebGL is a problem)


## `projects.json` properties
```
[
    {  
        "title": "project title",
        "folder": "name of the folder",
        "author": "my name",
        "year": "folder name of the year",
        "info": "info about your project",
        "status": "0"
    },
    ...
]
```
### title
Project title

### folder
Name of your project folder

### author
Author(s) of the project

### year
Name of the year (must be the same as the year folder directly in the `projects` folder)

### info
(optional) e.g. your project works in specific versions of a browser
### status
| status  | description        |
| ------: | ------------------ |
| -1      | not working        |
| 0       | partly working     |
| 1       | completly working |

## Create new repository (@AlfredDoppler)
Just copy the `index.html`, `app.json` and `projects.json` to the new repository. There create a new folder called `projects` with subfolders named by year (e.g. 2017_SS) and update the `app.json` with the new values.
### That´s it :)

