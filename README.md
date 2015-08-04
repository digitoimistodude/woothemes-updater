WooThemes Helper
=================

A composer repository for WooThemes Helper. Created because [the original download url](http://woodojo.s3.amazonaws.com/downloads/woothemes-updater/woothemes-updater.zip) does not work with composer.json directly.

## Usage 

Add to your composer.json repositories:

    {
      "type": "vcs",
      "url": "git@github.com:digitoimistodude/woothemes-updater.git"
    },

Then add to require:

    "digitoimistodude/woothemes-updater": "*"

After installation you can access the admin screen by going to **Dashboard > WooThemes Helper**.