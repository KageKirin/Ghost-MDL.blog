# Ghost-MDL.blog

This is a quick port of Google's [Material Design Lite](http://www.getmdl.io) [Blog template](http://www.getmdl.io/templates/blog/index.html)
into a Ghost theme.

## Getting the theme

ATM, the theme is on the [ghost/templating branch](https://github.com/KageKirin/Ghost-MDL.blog/tree/ghost/templating).
In order to add it to your Ghost `content/themes` folder, please follow theesesteps:

1. in `content/themes` add the submodule MDL.blog with `$ git submodule add https://github.com/KageKirin/Ghost-MDL.blog.git MDL.blog`
2. `cd MDL.blog` and `git pull origin ghost/templating` iether into the master branch or into a new branch
3. `git commit` the submodule (`.gitmodules` and the entry for the submodule)
4. update your Ghost blog

## Status

As initially stated, this is a quick port of the MDL blog template. It does the rough of displaying content etc, but still requires more work to be really usable.

Consider this a project as a start to create your own theme based on the MDL blog template.
