[![npm version](https://badge.fury.io/js/@renekorss/tipsy.svg)](https://badge.fury.io/js/@renekorss/tipsy)
[![npm](https://img.shields.io/npm/dt/@renekorss/tipsy.svg)](https://www.npmjs.com/package/@renekorss/tipsy)
[![Known Vulnerabilities](https://snyk.io/test/github/renekorss/@renekorss/tipsy/badge.svg?targetFile=package.json)](https://snyk.io/test/github/renekorss/@renekorss/tipsy?targetFile=package.json)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# Tipsy (with hoverStay)

Facebook-style tooltip plugin for jQuery.

Supports `hoverStay` options which doesn't hide tipsy (if set to `true`). Great for HTML content which has links, buttons etc.

(c) 2008-2010 Jason Frame (jason@onehackoranother.com)

Released under The MIT License.

## Description

tipsy is a simple jQuery plugin for generating Facebook-style tooltips.

It's used by Twitter, Github, Slideshare and Bitbucket, amongst others.

## Source

Hosted at GitHub; browse at:

  http://github.com/renekorss/tipsy/tree/master

Or clone from:

  git://github.com/renekorss/tipsy.git

## Usage

### NPM

    npm install @renekorss/tipsy

### Direct

1. Copy the contents of src/{images,javascripts,stylesheets} to the corresponding asset directories in your project. 
   If the relative path of your images directory from your stylesheets   directory is not "../images", you'll need to adjust tipsy.css appropriately.

2. Insert the neccesary elements in your document's `<head>` section, e.g.:
   
        <script type='text/javascript' src='/javascripts/jquery.tipsy.js'></script>
        <link rel="stylesheet" href="/stylesheets/tipsy.css" type="text/css" />

 Remember to include jquery.tipsy.js *after* including the main jQuery library.

3. Initialise Tipsy in your document.onload, e.g.:

        <script type='text/javascript'>
        $(function() {
            $('a[rel=tipsy]').tipsy({fade: true, gravity: 'n'});
        });
        </script>

Please refer to the docs directory for more examples and documentation.

## A note on forking:

By forking this project you hereby grant permission for any commits to your fork to be
merged back into this repository and, with attribution, be released under the terms of
the MIT License.
