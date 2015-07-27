# Rprofile
Simple RProfile additions

# Organizing

To sync Rprofile across computers, put all customizations into a Dropbox file, e.g., ~/Dropbox/.Rprofile.

Then, create the .Rprofile file your local R will grab, e.g.:

```
vim ~/.Rprofile
```

This will will simply source in your actual customizations from the Dropbox file:

```R
source("~/Dropbox/.Rprofile")
```

Save off that file (note that you'll need to restart R for it to read this in).

# Customizations

My .Rprofile contains three functions useful for making nice looking default plots.

###plot.hall()

This function overrides various plot defaults for a cleaner look.  Any/all of these can, in turn, be overwritten by the user.

###par.hall()

This function overrides various par defaults for a cleaner look.  Mainly it moves the tick marks and labels closer to the axes.  Again, any defaults can be overwritten by the user.

###makeTransparent()

Simple function written by [Michael Gill](http://scholar.harvard.edu/gill/home) which lets the user quickly create colors with varying levels of transperency.
