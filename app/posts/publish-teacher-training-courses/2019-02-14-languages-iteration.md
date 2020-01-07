---
title: Modern Languages – 5 February iteration
description: Simplify the fields for languages.
tags: publish-teacher-training-courses
---
Providers model their modern languages courses differently.

For example:

* One modern language course for all languages they offer
* A separate course for each language, or language combination
* Sometimes pairs of languages have a hierarchy – a dominant language and one or more other languages
* Sometimes the languages are equal

The original design only catered for the dominant use case. For MVP we can ask for all of the languages on offer without inferring anything.

## Screenshots

{% from "gallery/macro.njk" import appGallery %}
{{ appGallery({
  path: page.filePathStem | replace("/posts", "/images"),
  items: [
    {text: "Pick the languages for this course"},
    {text: "Original design"}
  ]
}) }}