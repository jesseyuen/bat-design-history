---
layout: page
title: Mission patches
description: Archive of patches created to celebrate milestones and the development of our different services.
permalink: "/mission-patches.html"
tags: reference
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---

<style>
  .app-figure > a { outline: 0 }
</style>

{% from "gallery/macro.njk" import appGallery with context %}

## Apply for teacher training

<p class="govuk-body-l">Apply’s mascot is a beaver called Brian Townley. We chose a beaver because we are building a complex service and delivering it regardless of the ever-changing environment we work in.</p>

{{ appGallery({
  path: "/images/mission-patches",
  items: [{
    text: "Apply for teacher training SCITT Pilot",
    caption: "This patch celebrated the tenacity of our team, who despite a power cut and several building evacuations, launched the service from a nearby pub. November 2019"
  }, {
    text: "Transition team 10,000 miles travelled",
    caption: "This patch celebrated the work of the transition team, who travelled the length of breadth of England to encourage providers to join our pilots. April 2020"
  }, {
    text: "Find and Apply for teacher training",
    caption: "This patch marked the candidate-facing Find and Apply services joining together under one team. August 2020"
  }, {
    text: "Apply for teacher training HEI Pilot",
    caption: "This patch celebrated 11 early-adopter HEIs joining Apply as we embarked on our second recruitment cycle. As the University of Bedfordshire the first HEI to be onboarded, Brian’s mortarboard featured a red tassel. October 2020"
  }]
}) }}

* * *

## Find postgraduate teacher training

<p class="govuk-body-l">Find’s mascot is a canary (a mysterious bird, we still don’t know her name). We chose a canary because ???</p>

{{ appGallery({
  path: "/images/mission-patches",
  items: [{
    id: "missing",
    text: "Private beta",
    caption: "This patch celebrated the launch of the initial service. November 2018"
  }, {
    id: "missing",
    text: "2020-21 recruitment cycle",
    caption: "This patch celebrated the start of the 2020-21 recruitment cycle. October 2020"
  }, {
    text: "2021-22 recruitment cycle",
    caption: "This patch celebrated the start of the 2021-22 recruitment cycle. October 2021"
  }]
}) }}

* * *

## Register trainee teachers

<p class="govuk-body-l">Register’s mascot is an octopus called Inky. We chose an octopus because ???</p>

{{ appGallery({
  path: "/images/mission-patches",
  items: [{
    text: "Register trainee teachers private beta",
    caption: "???. January 2021"
  }]
}) }}

* * *

## Other projects

{{ appGallery({
  path: "/images/mission-patches",
  items: [{
    text: "Allocations discovery",
    caption: "???"
  }, {
    text: "Allocations 2020",
    caption: "???"
  }, {
    text: "Data discovery",
    caption: "???. February 2020"
  }]
}) }}
