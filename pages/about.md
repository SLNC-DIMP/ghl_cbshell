---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: demo_031
# set background-position for featured image, "center", "top", "bottom"
position: bottom
# major heading to display over featured image
heading: About the Collection
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 6em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

## About This Collection

This collection features items from the Library of North Carolina's [Digital Collections](https://digital.ncdcr.gov/) and online resources [NCpedia](https://www.ncpedia.org/) and [ANCHOR](https://www.ncanchor.org/) focusing on ...

{% include feature/card.html header="_____ Calendar" heading_level="h3" alt="" objectid="/objects/___.jpg" text="View the Calendar" centered="true" caption=false width="50" link="https://events.dncr.nc.gov/A250NC" %}

## About _____

{% include feature/card.html text="." objectid="___" width="50" centered=true %}

---------------------------------------------------------------------------------------
## The North Carolina Digital Collections
The North Carolina Digital Collections (NCDC) contain over 90,000 historic and recent photographs, state government publications, manuscripts, and other resources on topics related to North Carolina.  The Collections are free and full-text searchable, and bring together content from the State Archives of North Carolina and the Library of North Carolina.

{% include feature/button.html text="Find Out More About the NC Digital Collections" link="https://digital.ncdcr.gov/about" color="prime" centered="true" %}## About CollectionBuilder CSV


<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
