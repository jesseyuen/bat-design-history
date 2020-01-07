---
title: Add a location – 13 February iteration
description: Clarify the purpose of locations.
tags: publish-teacher-training-courses
---
The term ‘training locations’ is ambiguous.

Providers can misinterpret what ‘training locations’ should mean. The data we want to capture is specifically a set of locations that candidates will choose between when they apply.

Training locations is used in the UCAS application and on Find.

This design tries to fix this by:

* renaming ‘training locations’ to ‘locations’
* adding content about candidates selecting these locations
* providing a definition with a link to further guidance
* checking the meaning is understood at the point of adding a location (using a checkbox)

Success messages after saving and edited have been added, these reinforce the message and give routes to editing courses.

## Screenshots

{% from "gallery/macro.njk" import appGallery %}
{{ appGallery({
  path: page.filePathStem | replace("/posts", "/images"),
  items: [
    {text: "Organisation"},
    {text: "Locations"},
    {text: "Add a location"},
    {text: "Location added"},
    {text: "Location edited"}
  ]
}) }}