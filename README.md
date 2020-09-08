# Mantha

Mantha is the very best friend of Casper - the default theme for [Ghost](http://github.com/tryghost/ghost/).

You can find [Casper here!](https://github.com/TryGhost/Casper/) - and if you haven't met [Ghost](http://github.com/tryghost/ghost/) - well, where have you been??

## But first coffee...

This is my first repo on GitHub - so I may well get things in a muddle as I grapple with the new-to-me GitHub workflows - apologies in advance.

# Why Mantha?

I created Mantha because I want to:
* Tweak very minor things in Caper to my taste.
* Fix some things in Casper that I think might be _features_.
* Automatically deploy the Mantha theme to my blog.

# The Mantha Way

I want Mantha to be stable, and to very easily accept upstream merges from Casper, so I use the following approach:
* Make the absolute minimum changes to Casper source files.
* Keep Mantha enhancements in their own source files.
* Utilise Ghost's automatic template selection.
* Integrate nicely with Ghost routes.yaml.
* Comment the _why_ rather than the how.

> Less is so much more!

Please note that I do understand that my approach makes it harder to get some of these tweaks back
into upstream [Casper](https://github.com/TryGhost/Casper/).

Some of the Mantha tweaks might be considered bug-fixes - e.g. the addition of ``font-face:
inherit;`` so that you can just set your preferred font in one place. I have kept Mantha isolated
from Casper because when I did query Casper behaviour, my posts were deleted without comment in the
Ghost moderated forums. Maybe my sense of humour is too whacky for the Ghost team?

# Mantha Does...

The following tweaks are incorporated in Mantha:
* Hide link to ghost.org in footer.

# Mantha Will...

The following tweaks are planned:
* Presentation - reduction of vertical whites-space.
* Index - a template for /tags/ to list all Tags.
* Index - a template for /authors/ to list all Authors.
* Index - a template for /my-tag-route/ to list ``routes:`` specified in ``routes.yaml``
* Fix - support single site-wide font selection in code-injection.
* Secondary Menu - visible on Mobile

# How Mantha, How?

Some of Mantha's tweaks are automatic. Some of them require a little set-up on your site.

## Installing Mantha
* TBC

## Under Mantha's Hoodie

How Mantha does what she does... can be found here: [MANTHA-changes](MANTHA-changes.md)

# Copyright & License

Casper: Copyright (c) 2013-2020 Ghost Foundation - Released under the MIT license.

Mantha: Copyright (c) 2020 [jaguart](https://github.com/jaguart) - Released under the [MIT license](LICENSE).
