---
layout: patterns
permalink: "/alerts"
title:  Alerts
htmlpath: "patterns/alerts/alerts.md"
csspath: "patterns/alerts/alerts.scss"
varspath: "patterns/alerts/alert-variations.md"
description: "An alert keeps users informed of important and sometimes time-sensitive changes." 
usa-link: https://designsystem.digital.gov/components/alert/
specification: |
  - Note that alert content should be text only, but may contain a link.
  <br /> - For authoring. There should be an option to apply to multiple pages or sections.
  <br /> - <strong>If</strong> the alert is a <strong>site wide</strong> communication, consider using the <a href="/site-alert/">Site Alert</a> instead.
schema: 
  - fieldname: heading
    class-name: usa-alert__heading
    type: h4
    required: on standard type only
    content: 80 characters
    example: "Watch out for Cat Zombies"
  - fieldname: body
    class-name: usa-alert__text
    type: text
    required: true
    character: 140 characters
    example: "Run off table persian cat jump eat fish hack. Paw at beetle and eat it before it gets away demand"
  - fieldname: alert type
    type: selection
    class-name: usa-alert--info | usa-alert--warning | usa-alert--error | usa-alert--success
    required: true
    content: "Options: Information, Warning, Error, Success"
  - fieldname: alert style
    class-name: usa-alert--slim | usa-alert--no-icon
    type: selection
    required: applies standard if not added
    content: "Options: Standard, Slim, No Icon"
  - fieldname: icon
    type: icon
    class-name: (icons are set in the base uswds-styles )
    required: 
    content: (icons live in the uswds images folder)




last-updated: 5/18/2021
---

