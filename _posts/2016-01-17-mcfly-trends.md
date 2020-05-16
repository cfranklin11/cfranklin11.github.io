---
layout: post
position: right
title: 'McFly Trends'
date: 2016-01-17
categories: analytics data development
tags: React Javascript Node Express
featured_image: 'img/posts/mcfly-trends.png'
project_links:
  - project_link: 'https://github.com/cfranklin11/mcfly-trends'
    button_icon: 'github'
    button_text: 'Visit Project'
  - project_link: 'https://mcflytrends.herokuapp.com'
    button_icon: 'cog'
    button_text: 'Visit Site'
lead_text:
---

Fetching and presenting Google Trends data in a more-useful format, this is my first fully-functional app that was the result of a real-world need: getting Trends data segmented by month rather than week, which is how the standard CSV export organises it. The commit history shows my evolution as a developer, starting with a thousand-plus-line `.js` file of spaghetti jQuery, followed by a Backbone.js app with all logic and math handled by the client (using D3.js data methods in place of `Array.reduce` is particularly fun), finally resulting in a React app with data-fetching and -cleaning logic contained in Express middleware. I may even get around to adding Jest tests and doing a proper refactor someday.