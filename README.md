# Django Syntax

Syntax highlighting of Django templates for Sublime Text using the `.sublime-syntax` format.

![Django Syntax](https://user-images.githubusercontent.com/335152/70323213-27922580-1824-11ea-97db-d6bea285e9f8.png)

### Installing

You can install from [Package Control](https://packagecontrol.io/packages/Django%20Syntax), or manually using the Development instructions below.

### Development

To install for development clone this repo (or symlink it) to `~/.config/sublime-text-3/Packages/Django Syntax` on linux. For other operating systems use `Preferences` -> `Browse Packages` to find the location of the Packages folder.

Once symlinked, when editing the syntax definition any loaded files using that definition should update automatically.

Edit only `Django HTML.sublime-syntax` and then run `build.py` to generate the `CSS` and `XML` variants before committing changes.
