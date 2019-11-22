# Django Syntax

Syntax highlighting of Django templates for Sublime Text

Written to overcome some limitations with [Djaneiro's](https://github.com/squ1b3r/Djaneiro) tmLanguage based syntaxes.

![Django Syntax](https://user-images.githubusercontent.com/335152/69388951-75eee280-0cc2-11ea-909f-834bc242af08.png)

### Installing
[This package is pending acceptance onto packagecontrol.io](https://github.com/wbond/package_control_channel/pull/7766)

In the meantime you can install as you would for development.

### Development

To install for development clone this repo (or symlink it) to `~/.config/sublime-text-3/Packages/Django Syntax` on linux. For other operating systems use `Preferences` -> `Browse Packages` to find the location of the Packages folder.

Once symlinked, when editing the syntax definition any loaded files using that definition should update automatically.

Edit only `Django HTML.sublime-syntax` and use `build.py` to generate the `CSS` and `XML` variants.
