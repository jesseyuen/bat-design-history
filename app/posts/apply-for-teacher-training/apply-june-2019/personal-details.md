---
title: Personal details
description: Adding name, nationality and visas.
---

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [
    { text: "Dashboard" },
    { text: "Personal teaching profile" },
    { text: "Personal details" },
    { text: "What is your residency status?" },
    { text: "Residency status: general work visa" },
    { text: "Residency status: general student visa" },
    { text: "Residency status: unknown" }
  ]
}) }}
