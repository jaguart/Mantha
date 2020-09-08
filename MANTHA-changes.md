# Mantha Changes

This is a record of the Casper things I have changed/added to get Mantha working, along with notes on some of the tooling I used to get here...

Are you looking for the [MANTHA-readme](README.md)?


## Tooling

* updated ``.gitignore`` to exclude things in ``assets/built/``
* removed tracking of the current content of ``assets/built/`` - ``git rm --cache assets/built/*``
* added to LICENCE
* updated package.json for Mantha
* removed all Casper tags
* created tag 0.0.0 to get ``yarn run ship`` to work.
* created config.json with github access token.
* updated gulpfile.js

## Core structure

* Created assets/css/mantha.css
  * added line into default.hbs to include this CSS
* Created assets/js/mantha.js
  * added line into default.hbs to include this JS
  * will use `{{#contentFor "scripts"}}` in templates to activate JS.


## Feature

* Hide link to ghost.org in footer.
* Tags and Author indexes - added page-tags.hbs, page-authors.hbs and CSS in mantha.css