RebuildPH
=========

This is a website cateloging the rebuilding efforts in the Philippines post typhoon haiyan.

Installation
-------------
    gem install jekyll
    git clone https://github.com/rebuildph/homepage.git
    jekyll serve --watch


Adding Locations / Projects
-----------------

Locations are located in the `/locations` folder as .md files, supporting images reside in `/images`. 

The text file **must** be structured as follows:

    ---
    layout: location
    name: Name of the project
    latitude: 37.776368
    longitude: -122.408594
    ---

    Description of the project...


