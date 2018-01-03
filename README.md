# charlesreid1.com pelican theme

This Pelican theme provides templates for charlesreid1.com pages.

## How to install theme

To install the theme, use the `pelican-theme` utility:

```
git clone https://charlesreid1.com:3000/charlesreid1/charlesreid1.com-theme.git

pelican-themes -i charlesreid1.com-theme
```

Now you can set the theme in pelicanconf.py from any directory,
and specify the theme as `charlesreid1.com-theme`, and it will
use this theme.

When the files in the theme are changed, the installation 
command should be run again.

For help, run

```
pelican-themes -h
```

## How to use the theme

To use the theme, set the Pelican theme in pelicanconf.py.
Then, the Pelican site should:

* Create an index landing page
* Create main landing pages for each sub-category (about/consulting/writing/projects/etc)
* Landing pages may use theme templates, or may define totally different stuff.
* New/separate apps go in their own folder, see pelicanconf.py

## How to customize the navbar

This theme doesn't make many assumptions about site layout,
but what assumptions it does make are made in the navbar.

To customize the navbar, edit the file `templates/_includes/navbar.html`.

## What to do next

This is the base charlesreid1.com theme, but there are others.
These should be updated accordingly:

* Charlesreid1.com wiki theme
* charlesreid1.github.io theme

