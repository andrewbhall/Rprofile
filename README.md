# Rprofile
Simple RProfile additions

# Organizing

To sync Rprofile across computers, put all customizations into a Dropbox file, e.g., ~/Dropbox/.Rprofile.

Then, create the .Rprofile file your local R will grab:

```
vim ~/.Rprofile
```

This will will simply source in your actual customizations from the Dropbox file:

```R
source("~/Dropbox/.Rprofile")
```

# Customizations


