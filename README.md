# charlesreid1.com pelican theme

This Pelican theme provides templates for charlesreid1.com pages.

## How to install theme

To install the theme, use the `pelican-theme` utility:

```
git clone https://git.charlesreid1.com/charlesreid1/charlesreid1.com-theme.git

# if theme not installed, install:
pelican-themes -i charlesreid1.com-theme

# if theme already installed, upgrade:
pelican-themes -U charlesreid1.com-theme
```

Now you can set the theme in `pelicanconf.py` from any directory,
and specify the theme as `charlesreid1.com-theme`, and it will
use this theme. In `pelicanconf.py`, include this:

```
THEME = 'charlesreid1.com-theme'
```

If/when files in this theme are changed, 
the `-i` install or `-U` upgrade command 
should be run again.

For help, run:

```
pelican-themes -h
```

## How to use the theme

To use the theme, set the Pelican theme in `pelicanconf.py`.
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
* Charlesreid1.github.io theme
* Charlesreid1 notes theme

