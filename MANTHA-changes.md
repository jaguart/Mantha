# Mantha Changes

This is a record of the Casper things I have changed/added to get Mantha working, along with notes on some of the tooling I used to get here...

Are you looking for the [MANTHA-readme](README.md)?

## Tooling

* updated ``.gitignore`` to exclude things in ``assets/built/``
* removed tracking of the current content of ``assets/built/`` - ``git rm --cache assets/built/*``
* added to [LICENCE](LICENCE)
* Mantharised package.json
* removed all Casper repo tags `git tag -d $(git tag -l)`
* don't fetch Casper tags - `git config remote.upstream.tagOpt --no-tags`
* updated gulpfile.js - attemping to get `yarn run ship` to work... oh, all it needs is a starting tag
* created tag 0.0.0 to get ``yarn run ship`` to work. `git tag 0.0.0`
* created config.json with github access token - checked .gitignore first!

## Core structure

* Created assets/css/mantha.css
  * added line into default.hbs to include this CSS
* Created assets/js/mantha.js
  * added line into default.hbs to include this JS
  * will use `{{#contentFor "scripts"}}` in templates to activate JS.


## Feature

* Hide link to ghost.org in footer - mantha.css.
* Tags and Author indexes - page-tags.hbs, page-authors.hbs, mantha.css
* Casper-fix: font-family: inheritance - set your site font once, on `body` - mantha.css
* Casper-tweak: half some of the vertical padding to show more content - mantha.css