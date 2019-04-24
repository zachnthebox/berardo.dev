---
title: Groupr
excerpt: Manage group locations for a weekly meeting
layout: single
classes: wide
header:
  overlay_color: "#c75a5a"
  overlay_filter: "0.3"
  teaser: assets/images/groupr-logo.jpg
  actions:
    - label: "<i class='fab fa-github'></i> View Web Application on Github"
      url: "https://github.com/zachnthebox/groupr"
    - label: "<i class='fab fa-github'></i> View API on Github"
      url: "https://github.com/zachnthebox/groupr-api"
---

The intention of group was to automate the process of selecting a group location for my small group for church.

It was tedious posting to a facebook group and a google calendar at the same time each week.

This [Ember](http://www.emberjs.com) application and [NodeJS](http://nodejs.org) application handle this task for me each week automatically.

The API is not currently developed to handle multiple groups, but support for that will come in the future.
I would like to expand the compatibility of the application, so it can support multiple tenants.

## How To Deploy

There are two pieces of this project: the [api](https://github.com/zachnthebox/groupr-api) and [web application](https://github.com/zachnthebox/groupr).

In the README, there is a "Deploy to Heroku" button to deploy each part to Heroku.
The application can be run on the free tear of their service.
More detailed instructions will come later.
