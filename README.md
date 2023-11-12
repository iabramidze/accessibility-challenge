# accessibility-challenge

## Description 

Changed the title to a more descriptive one to improve SEO.

Used <a href="/" class="logo"> instead of <h1> for 'Horiseon', cause it's a logo, not a heading.

Replaced <h2> in the footer with <p class="copyright"> cause that's not a heading.

Deleted id's (they don't do anything).

Added alt-tags to image and icon elements.

Replaced div's with semantic elements where nesessary (navigation bar, header, footer, sections).

All combinations of background and foreground colors fail WCAG contrast check. 
Replaced -
.benefits 
background-color: #2589bd with #73bde3
color: #ffffff with #000000
.content-card
background-color: #0072bb with #005992
header
background-color: #2a607c with #275973

Cleaned up the code and made it shorter.

Replaced 'search-engine-optimization', 'online-reputation-management', 'social-media-marketing' classes with one "content-card" class (they all do the same). Same goes for the "benefit-..." classes.